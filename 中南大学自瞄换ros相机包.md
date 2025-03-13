//
launch启动文件#图像处

package='mindvision_camera'
暂时不知道具体定义在那里，但是可以打开终端ros2 run m并且通过tab键补全（初步估计在xml文件或者是在CMakeList.txt中被定义了）

plugin='mindvision_camera::MVCameraNode'
此处要与mv_camera_node.cpp文件中的RCLCPP_COMPONENTS_REGISTER_NODE(mindvision_camera::MVCameraNode)括号内相同。
//


//
camera_driver_params.yaml文件中camera_name需要与cmaera_info.yaml中的camera_name相同
//


//
报错could not find requested resource in ament index,可能是launch没有改干净，具体参考GGbond的github
//


//
报错no camera found,可能是因为相机驱动没有安装。
//
