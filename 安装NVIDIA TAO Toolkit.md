## 安装NVIDIA TAO Toolkit 

#### 1.docker配置

成功地运行了一个使用 NVIDIA GPU 的 Docker 容器

![image-20240523101425090](/home/longyue/.config/Typora/typora-user-images/image-20240523101425090.png)

去nvidia官方注册并获取一个密匙

![image-20240523103435238](/home/longyue/.config/Typora/typora-user-images/image-20240523103435238.png)

API密匙：`MnBsM3Q1ZTMwNmdzc281cnZxcHVsaWlwdjY6OTUwYzEyMTYtYzExYy00MzA3LThiZmItNDkxMDlhZWVkNzU4`

`docker login nvcr.io`

`Username: $oauthtoken`
`Password: MnBsM3Q1ZTMwNmdzc281cnZxcHVsaWlwdjY6OTUwYzEyMTYtYzExYy00MzA3LThiZmItNDkxMDlhZWVkNzU4`

录NGC：只要登录一次就行

![image-20240523104153889](/home/longyue/.config/Typora/typora-user-images/image-20240523104153889.png)

#### 2. Tao Toolkit的安装

下载Tao安装脚本

`wget --content-disposition https://api.ngc.nvidia.com/v2/resources/nvidia/tao/tao-getting-started/versions/4.0.1/zip -O getting_started_v4.0.1.zip`
`unzip -u getting_started_v4.0.1.zip  -d ./getting_started_v4.0.1 && rm -rf getting_started_v4.0.1.zip && cd ./getting_started_v4.0.1`

安装nvidia-pyindex与nvidia-tao

`bash setup/quickstart_launcher.sh --install`

wget --content-disposition https://api.ngc.nvidia.com/v2/resources/nvidia/tao/tao-getting-started/versions/4.0.1/zip -O getting_started_v4.0.1.zip
unzip -u getting_started_v4.0.1.zip  -d ./getting_started_v4.0.1 && rm -rf getting_started_v4.0.1.zip && cd ./getting_started_v4.0.1

