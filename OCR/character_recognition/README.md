# 这是文字识别
>aip-ocr-php-sdk-1.4.0.zip 

文件是PHP 的SDK的接口可以直接下载

然后里面有文件如下


lib//库文件

demo//这里主要要做写改的是里面的 

      -const APP_ID = '请填写你的appid';

      -const API_KEY = '请填写你的API_KEY';

      -const SECRET_KEY = '请填写你的SECRET_KEY';

      -到demo文件夹的DemoApiOcr.php配置参数即可实现文字识别

AipOcr.php //这个算是主函数吧


>注意:因为程序运行的过程中会调用getimagesizefromstring 函数 — Get the size of an image from a string 把图像转化成字符 所以要求PHP版本(PHP 5 >= 5.4.0, PHP 7)

调用的是百度的OCR接口
