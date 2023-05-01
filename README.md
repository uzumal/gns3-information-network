# gns3-information-network
[講義で使用する教材](https://amzn.asia/d/defdVg0)に登場するネットワーク環境を、[GNS3](https://www.gns3.com/)を用いて実装


## <p align="center">Contributors</p>

<div align="center">
<a href="https://github.com/uzumal/gns3-information-network/graphs/contributors"><img src="https://img.shields.io/github/contributors/uzumal/gns3-information-network" alt="contributors"></a>
</div>

<div align="center">
<a href="https://github.com/uzumal"><img src="https://avatars.githubusercontent.com/u/52265875?v=4" alt="uzumal" height="120px"></a>
<a href="https://github.com/ryota"><img src="https://avatars.githubusercontent.com/u/46432620?v=4" alt="ryota" height="120px"></a>
</div>

## <p align="center">Assets</p>

<div align="center">
<a href="https://www.gns3.com/" target="_blank" rel="noopener noreferrer"><img src="https://user-images.githubusercontent.com/52265875/235428356-8960b7e4-ba66-4fcf-88dd-357f1eb562fc.png" alt="gns3" height="75px"></a>
<a href="https://www.docker.com/" target="_blank" rel="noopener noreferrer"><img src="https://user-images.githubusercontent.com/52265875/235428607-19d5f033-42cb-4b16-b566-3ce2cd339fea.png" alt="docker" height="75px"></a>
<a href="https://www.wireshark.org/download.html" target="_blank" rel="noopener noreferrer"><img src="https://user-images.githubusercontent.com/52265875/235428912-e4ce9614-3ed7-47ee-b11f-5b09bfdada67.png" alt="wireshark" height="75px"></a>
<a href="https://www.oracle.com/jp/virtualization/technologies/vm/downloads/virtualbox-downloads.html" target="_blank" rel="noopener noreferrer"><img src="https://user-images.githubusercontent.com/52265875/235428527-205f81c9-09b9-4ca0-91e5-7b7ebe566575.png" alt="virtualbox" height="75px"></a>
</div>

## Preview
<p align="center" >
 OSPF（Open Shortest Path First）
</p>

<p align="center">
 <img width = "500" height = "207" alt="Screenshot 2023-05-01 at 16 43 04" src="https://user-images.githubusercontent.com/52265875/235425898-3a616086-d1ee-4626-8476-fd07affce28c.png">
 <img width = "500" height = "207" alt="Screenshot 2023-05-01 at 16 43 11" src="https://user-images.githubusercontent.com/52265875/235425927-b99dac2f-79f4-4a48-b5f7-d8e4c32c562e.png">
</p>　　

<p align="center" >
 Proxy Server
</p>

<p align="center" >
 <img img width = "500" height = "207" alt="Screenshot 2023-05-01 at 16 58 35" src="https://user-images.githubusercontent.com/52265875/235426022-653cb195-cbb0-4125-83a4-46dd15a0ce2a.png">
 <img img width = "500" height = "207" alt="Screenshot 2023-05-01 at 16 59 10" src="https://user-images.githubusercontent.com/52265875/235426088-5c14106d-26c8-4536-9ce8-4b31a788a62f.png">
</p>

## Tools
- Router
  - [Cisco 7200 Series Router : c7200p-adventerprisek9-mz.152-4.M11.bin](https://software.cisco.com/download/home/282188585/type/280805680/release/15.2.4M11)
- VM
  - [VirtualBox](https://www.oracle.com/jp/virtualization/technologies/vm/downloads/virtualbox-downloads.html)

## 作成したDocker Image
### 2-1-http

* client
  * <https://hub.docker.com/repository/docker/uzumal/gns3-firefox>
* server
  * <https://hub.docker.com/repository/docker/uzumal/2-1-http>

### 13-ftp-tftp

<https://hub.docker.com/repository/docker/ryotamaru/13-1-ftp-client>

### 15-proxy

<https://hub.docker.com/r/minimum2scp/squid>
