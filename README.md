# yolov3_cv
yolov3 on opencv 3.4.x

运行前请下载权重文件，并拷贝到 yolo_cfg 目录下

下载地址：https://pjreddie.com/media/files/yolov3.weights

编译：

mkdir build && cd build

cmake ..

make -j8

运行：

./yolo_opencv -source=../data/person.jpg   %图像
./yolo_opencv -source=../data/test.avi     %视频
./yolo_opencv -device=0                    %摄像头


