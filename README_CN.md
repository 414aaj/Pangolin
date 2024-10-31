# 穿山甲

<p align="center">
  <a href="https://github.com/414aaj/Pangolin/blob/main/README">English</a> •
  <a href="https://github.com/414aaj/Pangolin/blob/main/README_CN.md">中文</a> 
</p>

免责声明：
    该分享工具仅供网络安全研究与教育用途，旨在提供给具备专业技能的白帽渗透测试人员进行合法的渗透测试和安全评估。非相关人员切勿随意使用或滥用。用户在使用本工具前，需明确知晓其行为的合法性和合规性。任何未经授权的网络渗透、入侵或对他人网络的破坏行为均违反法律规定，使用者应对自身行为负责。本工具开发者及分享者不对用户滥用或非法使用工具导致的任何后果承担责任。请务必遵循当地相关法律法规，在取得明确授权后，方可使用本工具进行渗透测试或安全研究。




![穿](https://github.com/user-attachments/assets/3aaefddf-8a39-40de-a97a-70a22138a7a6)




该工具使用 Go 和 Fyne 开发,内置中英文两种语言,目前专注于基于近源内网渗透测试。目前仅编译安卓端(PC端、iOS后续看需适配编译),绿色安全无后门,程序未加壳可自行反编译检验。

## 代理
支持HTTP、Socks5全局、局部代理(暂不支持凭据设置)

| <img src="https://github.com/user-attachments/assets/607721b0-d49d-4faf-98d9-a9571c192859" width="400"/> | <img src="https://github.com/user-attachments/assets/242d4a63-4240-4d24-bfba-2eb8a1efa681" width="400"/> | <img src="https://github.com/user-attachments/assets/60d8fecc-ecf5-4ab2-b18d-0f35a74fe33c" width="400"/> |
|:-----------------------------------------------------:|:-----------------------------------------------------:|:-----------------------------------------------------:|
| <img src="https://github.com/user-attachments/assets/4f3f0579-9e2c-47d6-9479-84d21449d8ef" width="400"/> | <img src="https://github.com/user-attachments/assets/52ad19e0-e995-4d92-b230-6a8ef44f4d2a" width="400"/> | <img src="https://github.com/user-attachments/assets/4b2f0184-2b3e-44fe-afea-fd98d203f341" width="400"/> |




<img src="https://github.com/user-attachments/assets/dbc461e9-4068-4858-8619-9306362ff600"  width="50" height="50">

## 主机存活探测
主机存活探测使用Ping命令进行探测(避免设备需要root授权)
## 端口扫描
  Socks5代理

        
  指纹识别
  
    服务指纹【VCN、SSH、HTTP】

    设备指纹【RM路由器、TP-LinK路由器、Apple AirTunes】

    框架指纹【beegoServer、Shiro】

  漏洞扫描【右键发送Shiro】

| <img src="https://github.com/user-attachments/assets/2af32cee-3f20-4861-9c4f-ac4803a0689a" width="400"/> | <img src="https://github.com/user-attachments/assets/6d77baff-3a5b-4259-91b2-1b9c8963791a" width="400"/> | <img src="https://github.com/user-attachments/assets/47f27b07-97b9-4c9c-94dd-3463c3341c50" width="400"/> |
|:-----------------------------------------------------:|:-----------------------------------------------------:|:-----------------------------------------------------:|
| <img src="https://github.com/user-attachments/assets/68f6d2be-c438-49de-99d7-c71bda19ec88" width="400"/> | <img src="https://github.com/user-attachments/assets/687ed407-5549-4a17-8afd-efe8c99ae471" width="400"/> | <img src="https://github.com/user-attachments/assets/90591650-c685-4393-a6d9-3c9ac230c677" width="400"/> |

<img src="https://github.com/user-attachments/assets/cbc12168-e52a-4daf-b435-9aa6c949a640"  width="50" height="50">

## fofa
支持HTTP、Socks5代理

支持Size和字段设置

支持表内多字段内容筛选

发送跳转【主机端口扫描、Shiro】




| <img src="https://github.com/user-attachments/assets/ad1f2e63-cb7c-4842-bce0-fabc6d130460" width="400"/> | <img src="https://github.com/user-attachments/assets/076596b4-55f8-41c9-b80e-070a43efa35e" width="400"/> | <img src="https://github.com/user-attachments/assets/357c474a-32e6-4f99-8e76-20bacb4176df" width="400"/> |
|:-----------------------------------------------------:|:-----------------------------------------------------:|:-----------------------------------------------------:|
| <img src="https://github.com/user-attachments/assets/7d7d6547-08ce-441d-9b89-c48ecca25cf7" width="400"/> | <img src="https://github.com/user-attachments/assets/be1d568d-d254-4b56-a9aa-c5a642b67f70" width="400"/> | <img src="https://github.com/user-attachments/assets/1e2f767d-b439-4d01-a5e8-41054025fd6c" width="400"/> |
| <img src="https://github.com/user-attachments/assets/db974120-cef3-4c27-821b-391f2b5b005b" width="400"/> | <img src="https://github.com/user-attachments/assets/4c02c9af-008b-49cb-a013-c7a71dd053ef" width="400"/> | <img src="https://github.com/user-attachments/assets/a41bfa0b-42c1-441c-8833-5347251d0e63" width="400"/> |


<img src="https://github.com/user-attachments/assets/99889507-57b9-4dcd-869d-f70f0d70ad06"  width="50" height="50">

## Shiro
支持HTTP、Socks5代理

批量Shiro检查

利用链【CommonsBeanutils1、OnlyCommonsBeanutils、CommonsCollectionsK1、CommonsCollections10、CommonsBeanutilsString】

cmd命令执行、内存马写入【Godzilla[Fiter]、Behinder[Fiter]、AntSword[Fiter]】

![shiro](https://github.com/user-attachments/assets/e4801d91-cb18-415b-b95a-97bfb721166a)



