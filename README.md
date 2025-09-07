# Urban Scene Reconstruction

<!--
![model overview](NeRFwithRealWorld.png)
--> 

## Overall
This repository focuses on Large Scene Reconstruction in Autonomous Driving. Our group belongs to [Pseudo3DV](https://github.com/Pseudo-Lab/Pseudo3DV). </br>
This curated collection of resources is related to tackling real-world challenges in autonomous driving perception using NeRF (Neural Radiance Fields) and 3D Gaussian Splatting (3D-GS).

Furthermore, we are currently operating a paper and code review study in [PsuedoLab](https://discord.gg/mNAT2GKM). Go check it out!
(Every Tuesday at 9pm, PseudoLab Discord Room YL!) 🚗💡

### 스터디 소개
**"리처드 파인만(Feynman)"**
**What I cannot create, I do not understand.**

안녕하세요. 저희가 진행할 스터디는 네이버와 같은 기업에서 디지털 트윈을 만들 때 사용되는 3D 재구성 기술인 **Large Scene Reconstruction**들을 살펴보고자 합니다. 기본적인 Large Scene Reconstruction도 일부 다루기는 하나 Autonomous Driving 데이터셋인 nuScenes, kitti 등의 데이터셋을 활용한 Urban Scene Reconstruction 분야를 심도있게 다룰 예정입니다.</br>
그리고, 관련 논문으로는 하기의 **Schedule**을 참고해주시고, **논문은 년도별로 순차적으로 읽으며,스터디장이 매주 스터디 진행한 당일에 다음 주에 읽고 발표할 논문에 대해서 정해줍니다. 매주 3편의 논문 및 관련 중요한 코드를 리뷰하는 형식으로 진행하며, 모든 러너분들이 격주로 발표를 진행하게 됩니다.** (스터디원이 관심있으신 논문과 발표하고 싶은 논문이 있으시면 미리 말씀주시면 반영하겠습니다.)
이전 스터디 [링크](https://github.com/Pseudo-Lab/NeRFwithRealWorld)를 참고하시면 감사하겠습니다.

저희 **스터디는 밀도 있고, 심도 있는 이해를 목표**로 진행할 예정입니다. 
그리하여 다음과 같은 [LINK](https://github.com/Pseudo-Lab/Pseudo3DV)를 따릅니다.

## 모집 대상
- **적극적은 의사소통 및 도전정신을 가지신 분**
- **NeRF에 대해서 읽어보고, 테스트 해보신 분**
- **건설적인 의사소통을 지향하는 분**
- **코드 읽는데 큰 부담 없으신 분**
- **향후 모임 진행 시 참여 가능하신 분**

${\textsf{\color{red}* NeRF, 3D-GS에 대한 기본적인 이해가 필요하며, 적극적으로 건설적인 의사소통 하실 분을 선호합니다.}}$
${\textsf{\color{red}*  캠(CAM)을 필수로 켜야 합니다.}}$

**매주 2명씩 논문과 코드를 PPT에 반드시 첨부하여..! 발표를 진행합니다.**

**모집 인원**
- 4-5명 (현재 이전기수로부터 진행중인 스터디원이 2명이 추가적으로 있습니다.)

**주의사항**
  - 발표 시 PPT를 활용해야합니다. (청중이 이해할 수 있도록 준비해주셔야 합니다.)  (경고 2회 시 제명)
  - 스터디 참가가 불가능한 경우 미리 5일 전에는 말씀주셔야 합니다. (경고 2회 시 제명)

## 활동 기간
### 첫 모임 날짜 & 시간 & 장소
- 날짜: 3월 11일 (화요일)
- 시간: 오후 21시
- 장소: [#ROOM-YL](https://discord.gg/nbpAWKUm)


## Team member
- _Seongjun Choi_ | [Contact](sjchoi.dp@gmail.com) | [Github](https://github.com/DrawingProcess) | [LinkedIn](https://www.linkedin.com/in/seongjun-choi-60b718205/) |
- _Sejun Hong_ | [Github](https://github.com/SEJUNHONG) | [LinkedIn](https://www.linkedin.com/in/sejun-hong-073758289/) |
- _Wongi Park_ | [Github](https://github.com/kalelpark) | [LinkedIn](https://www.linkedin.com/in/wongipark/) |

## Schedule

| Date | Paper | Task | Speaker |
| -------- | -------- | ---- | ---- |
| 25/03/11 | OT       | ---- | Seongjun Choi |
| 24/03/18 | [Block NeRF](https://waymo.com/research/block-nerf/), [gridnerf](https://city-super.github.io/gridnerf/), [CityGaussian](https://dekuliutesla.github.io/citygs/) | large scene recon   | All Members |
| 24/03/25 | [VastGaussian](https://vastgaussian.github.io/), [CityGaussianV2](https://dekuliutesla.github.io/CityGaussianV2/) | large scene recon   | All Members |
| 24/04/01 | [Hierarchical 3D Gaussians](https://repo-sam.inria.fr/fungraph/hierarchical-3d-gaussians), [Street Gaussians](https://github.com/zju3dv/street_gaussians), [EmerNeRF](https://emernerf.github.io/) | large scene, autonomous driving   | All Members |
| 24/04/08 | [HUGS](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhou_HUGS_Holistic_Urban_3D_Scene_Understanding_via_Gaussian_Splatting_CVPR_2024_paper.pdf), [DrivingGaussian](https://pkuvdig.github.io/DrivingGaussian/), [ULSR-GS](https://ulsrgs.github.io)   | large scene, autonomous driving   | All Members |
| 24/04/15 | [DC-Gaussian](https://arxiv.org/abs/2405.17705), [OmniRe](https://ziyc.github.io/omnire/), [STORM](https://jiawei-yang.github.io/STORM/) | large scene, autonomous driving   | All Members |
| 24/04/29 | [Urban4D](https://arxiv.org/abs/2412.03473), [StreetUnveiler](https://streetunveiler.github.io/) | large scene, autonomous driving   | All Members |
| 24/05/13 | [Urban4D](https://arxiv.org/abs/2412.03473), [StreetUnveiler](https://streetunveiler.github.io/) | large scene, autonomous driving   | All Members |
| 24/05/27 | [SGD](https://arxiv.org/abs/2403.20079), [STORM](https://jiawei-yang.github.io/STORM/) | large scene, autonomous driving   | All Members |
| 24/06/17 | [ReconDreamer](https://arxiv.org/pdf/2411.19548), [DriveDreamer4D](https://arxiv.org/pdf/2410.13571) | large scene, autonomous driving   | All Members |
