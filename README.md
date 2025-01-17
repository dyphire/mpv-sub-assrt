# mpv-sub-assrt

## assrt  字幕下载

使用 curl 通过 assrt 提供的 API 来搜索和下载中文字幕

通过 [uosc](https://github.com/tomasklaen/uosc) 的菜单 API 和 mpv 内部的 mp.input 原生菜单渲染（mpv 版本需不低于 0.39.0）提供菜单支持

### 用法

将脚本放入 mpv 配置目录的 `scripts` 文件夹中；

然后在`input.conf`中添加相应的键绑定：

```
key  script-message-to  sub_assrt sub-assrt
```

## 鸣谢

- [mpv-assrt](https://github.com/AssrtOSS/mpv-assrt)


