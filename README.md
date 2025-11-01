# 3D Scene Understanding

<!--
![model overview](NeRFwithRealWorld.png)
--> 

## Overall
This repository focuses on Large Scene Reconstruction in Autonomous Driving. Our group belongs to [Pseudo3DV](https://github.com/Pseudo-Lab/Pseudo3DV). </br>
This curated collection of resources is related to tackling real-world challenges in autonomous driving perception using NeRF (Neural Radiance Fields) and 3D Gaussian Splatting (3D-GS).

Furthermore, we are currently operating a paper and code review study in [PsuedoLab](https://discord.gg/mNAT2GKM). Go check it out!
(Every Tuesday at 7pm, PseudoLab Discord Room YL!) 🚗💡

### 스터디 소개
**"리처드 파인만(Feynman)"**
**What I cannot create, I do not understand.**

안녕하세요. 저희가 진행할 스터디는 로봇이 세상을 이해하는 방식을 다루는 **3D Scene Understanding** 논문들을 살펴보고자 합니다. 기본적으로 3차원 재구성 모델을 기반으로 (Semantic, Language 등 전반에 걸쳐서) 세상을 이해하는 방식을 Survey함으로써 3D Reconstruction의 활용 가능성을 모색하고자 합니다. 기본적인 3D Reconstruction을 메인으로 다루기는 하나, VLA, Scene Graph Generation 등 자신이 공부하고 싶은 도메인에 맞춰 진행하셔도 무방합니다.</br>
논문은 년도별로 순차적으로 읽으며, 주제에 벗어나지 않으며 자신의 도메인에 맞는 논문을 정하여 리뷰합니다. 그리고 하기의 **Schedule**을 참고해주시고, 모든 러너분들이 자신의 도메인의 논문 및 관련 중요한 코드를 리뷰하는 형식으로 진행하며, 격주로 발표를 진행하게 됩니다.** (스터디원이 관심있으신 논문과 발표하고 싶은 논문이 있으시면 미리 말씀주시면 반영하겠습니다.)
이전 스터디 [NeRFwithRealWorld](https://github.com/Pseudo-Lab/NeRFwithRealWorld), [UrbanSceneRecon](https://github.com/Pseudo-Lab/UrbanSceneRecon)를 참고하시면 감사하겠습니다.

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

**격주 논문과 코드를 PPT에 반드시 첨부하여 발표를 진행합니다.**

**모집 인원**
- 4-5명

**주의사항**
  - 발표 시 PPT를 활용해야합니다. (청중이 이해할 수 있도록 준비해주셔야 합니다.)  (경고 2회 시 제명)
  - 스터디 참가가 불가능한 경우 미리 5일 전에는 말씀주셔야 합니다. (경고 2회 시 제명)

## 활동 기간
### 첫 모임 날짜 & 시간 & 장소
- 날짜: 9월 9일 (화요일)
- 시간: 오후 7시
- 장소: [#ROOM-YL](https://discord.gg/nbpAWKUm)


## Team member
- _Seongjun Choi_ | [Contact](sjchoi.dp@gmail.com) | [Github](https://github.com/DrawingProcess) | [LinkedIn](https://www.linkedin.com/in/seongjun-choi-60b718205/) |
- _Gihyoen Kim_ | [Contact](kimh060618@gmail.com) | [Gtihub](https://github.com/kimh060612) | [LinkedIn](https://www.linkedin.com/in/gihyeon-%E2%80%8Dkim-a684a1209/)
- _Jihyeong Yoo_ | [Contact](jihyeongyoo566@gmail.com) | [Github](https://github.com/Shhyea) | [LinkedIn](https://www.linkedin.com/in/%EC%A7%80%ED%98%95-%EC%9C%A0-99b701326/)
- _Youngseo Chang_ | [Contact](jysjis7@gmail.com) | [Github](https://github.com/j-ys) | [LinkedIn](https://www.linkedin.com/in/youngseo-chang-b7552b26b?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)
- _Seokhyun Kim_ | [Contact](k0104912@gmail.com) | [Github](https://github.com/kimsuckhyun) | [LinkedIn](www.linkedin.com/in/kimseokhyun02)
- _Yunkyu Choi_ | [Contact](ckyun777@gmail.com) | [Github](https://github.com/ckyun777) | [LinkedIn](https://www.linkedin.com/in/yunkyu-choi-7a838649)

## Schedule

| Date | Paper | Task | Speaker |
| -------- | -------- | ---- | ---- |
| 25/09/09 | OT       | ---- | Seongjun Choi |
| 25/09/16 | [Survey 3DGS](https://arxiv.org/abs/2401.03890), [Survey 3DGS in Robotics](https://arxiv.org/abs/2410.12262) | basic study  | All Members |
| 25/09/23 | [Survey 3DGS](https://arxiv.org/abs/2401.03890), [Survey 3DGS in Robotics](https://arxiv.org/abs/2410.12262) | Survey on each domain | All Members |
| 25/10/14 | TBD... |
| 25/10/28 | TBD... |
| 25/11/11 | TBD... |
| 25/11/25 | TBD... |
| 25/12/09 | TBD... |
| 25/12/23 | TBD... |
