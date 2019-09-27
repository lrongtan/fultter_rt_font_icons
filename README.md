

# iconfont 以package 方式 导入项目


将项目的iconfont提取出来通过 pakcage 方式导入项目。单独管理iconfont


## iconfont 通过 package 打包 的方式

iconfont创建：http://fluttericon.com

将生成好的 fonts文件夹 拖入创建好的 package 里的lib文件夹里面

读取字体图标：IconData(0xe851, fontFamily: _kFontFam, fontPackage:(package的包名));

pubsepc.yaml 配置iconfont资源

```
    fonts:
      - family: RtFont
        fonts:
          - asset: lib/fonts/RtFont.ttf
```

