# LFPhotoBrowser
图片浏览器（更多请见LFPhotoBrowser.h）

由于使用了第三方框架，请使用项目前执行pod install

# 调用代码
LFPhotoBrowser *pbVC = [[LFPhotoBrowser alloc] initWithImageArray:@[PhotoInfo]];
[pbVC showPhotoBrowser];

设置代理方法，按钮实现

pbVC.delegate;

![image](https://github.com/lincf0912/LFPhotoBrowser/raw/master/screenshots/screenshot.gif)
