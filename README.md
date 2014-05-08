antrace
=======

This app is a port and front end of potrace(<http://potrace.sourceforge.net/>) on Android! It can transform a bitmap into a vector graphic.

To use this app, firstly please select a photo on your phone or take a photo. Next you can wrap the photo, select the region you want to trace:

![Image](https://github.com/jiangpeng79/antrace/blob/master/snapshots/crop.png)

Next step please specify a threshold value for black/white image, potrace will process the output black/white image:

![Image](https://github.com/jiangpeng79/antrace/blob/master/snapshots/threshold.png)

Now you will see a preview of output vector graphic:

![Image](https://github.com/jiangpeng79/antrace/blob/master/snapshots/preview.png)

Save it to file, we support svg and dxf formats:

![Image](https://github.com/jiangpeng79/antrace/blob/master/snapshots/save.png)

To build this app, firstly please setup Android development environment. Then please import the project to your workspace. Because potrace is a c program, you will also need NDK.

Thanks
