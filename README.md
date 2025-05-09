# STM32F103VET6+ESP8266+OV2640 网络摄像头项目

## 项目简介

本项目基于STM32F103VET6微控制器、ESP8266 Wi-Fi模块和OV2640摄像头模块，实现了一个简单的网络摄像头功能。该项目是在原子的开源基础上进行修改和扩展的，目前服务器端接收功能尚未实现，但可以通过串口查看摄像头捕捉到的图片。

## 主要功能

- **摄像头图像捕捉**：使用OV2640摄像头模块捕捉图像。
- **图像传输**：通过ESP8266 Wi-Fi模块将图像数据传输到服务器端。
- **串口调试**：当前版本中，图像数据可以通过串口输出，方便调试和查看。

## 使用说明

1. **硬件连接**：
   - STM32F103VET6与OV2640摄像头模块连接。
      - STM32F103VET6与ESP8266 Wi-Fi模块连接。
         - 通过USB线连接STM32F103VET6与电脑，用于串口调试。

         2. **软件配置**：
            - 使用Keil或其他支持STM32的开发环境打开项目文件。
               - 配置串口调试工具，接收来自STM32F103VET6的图像数据。

               3. **运行程序**：
                  - 编译并下载程序到STM32F103VET6。
                     - 打开串口调试工具，查看摄像头捕捉到的图像数据。

                     ## 注意事项

                     - 当前版本中，服务器端接收功能尚未实现，因此无法通过网络查看图像。
                     - 项目仍在开发中，后续版本将完善服务器端接收功能。

                     ## 贡献与反馈

                     欢迎大家提出改进建议和反馈问题。如果您有任何疑问或建议，请在项目中提交Issue或Pull Request。

                     ## 许可证

                     本项目基于原子的开源项目进行修改，遵循相应的开源许可证。具体许可证信息请参考项目源码中的LICENSE文件。

                     ## 下载链接
                     [STM32F103VET6ESP8266OV2640网络摄像头项目](https://pan.quark.cn/s/43cee7758e35) 

                     (备用: [备用下载](https://pan.baidu.com/s/1w4jjkwmaRwzs-W1Edicr1A?pwd=1234))

                     ## 说明

                     该仓库仅用于学习交流，请勿用于商业用途。
