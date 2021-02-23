# Bringing-Old-Photos-Back-to-Life
黑白照片修复


使用方法：
1、没有裂痕的图像即图片不清晰：

python run.py --input_folder [test_image_folder_path] \
              --output_folder [output_path] \
              --GPU 0
将想修复的图片放到 [test_image_folder_path] 目录下（自己指定），
生成的图片会放到 [output_path] 目录中。

2、对于裂痕的图片，需要额外增加一个参数，指令如下

python run.py --input_folder [test_image_folder_path] \
              --output_folder [output_path] \
              --GPU 0 \
              --with_scratch
