使用方法：盲水印
————————————————
文件：
origin.jpg 未隐藏水印的图片
watermark.jpg 水印图片，即需要隐藏的信息（上面内容是57117228 陈佑）
test.jpg 隐藏水印后的输出图片
watermark_result.jpg （使用decode.py）提取出的水印
encode.py 隐藏代码
decode.py 提取代码
————————————————
准备：
使用python3，将encode.py、decode.py与图片放在一个文件夹中。
————————————————
步骤：
（1）hide information:
输入以下命令：
python3 encode.py --image origin.jpg --watermark watermark.jpg --result test.jpg
即可得到隐藏信息后的输出图片test.jpg

（2）extract information:
输入以下命令：
python3 decode.py --image test.jpg --orig origin.jpg --result watermark_result.jpg
即可提取出水印watermark_result.jpg（即需要隐藏的信息）
————————————————
PS：watermark_result.jpg右上方的信息辨识度有点低...换了几张origin.jpg依旧如此。orz