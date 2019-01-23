# yolov3_cv
yolov3 on opencv 3.4.x

运行前请下载权重文件，并拷贝到 yolo_cfg 目录下

下载地址：https://pjreddie.com/media/files/yolov3.weights

mkdir build && cd build

cmake ..

make -j8

./yolo_opencv -source=../data/person.jpg 

