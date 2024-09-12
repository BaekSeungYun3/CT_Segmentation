<h1 align="middle">DICOM Medical Twin Object System</h1>
<h3 align="middle">의료 영상 기반 메디컬 트윈 객체 생성 시스템</h3>

<br/>

## 📝 작품소개

의료 영상 자료인 DICOM을 학습된 segmentation 모델을 통해 전체 장기를 디지털 트윈 환경으로  사용자에게 제공함으로써
빠른 진단 ,  교육 환경 ,  Portable한 신체 모델링이 가능하게 합니다.

<br/>

## 🌁 프로젝트 배경
 - 3D 모델링에 많은 시간 소모
 - 장기에 대한 모델링 필요
 - 시각화에 비중을 둔 뷰어 시스템

<br/>

## ✔️ 주요 기능
- **장기 분류** : MONAI MODEL zoo - Wholebody ct segmentation model 사용하여 CT 이미지상 장기 분류
![image](https://github.com/user-attachments/assets/aaba9d8b-3fae-4a48-831b-9365ebd13d50)

- **분류된 장기를 기반으로 3D화 진행** : 분류된 장기를 STL파일로 변환하여 3D화
![image](https://github.com/user-attachments/assets/638a343e-dbb1-46c0-8949-7b329c6cf128)

- **STL파일을 통해 Unity에서 프론트 개발** :  Unity에서 장기를 시각화
![image](https://github.com/user-attachments/assets/9f067067-e4da-41cb-b51d-91f75fc209c7)
<br/>

## 🔨 프로젝트 구조
![image](https://github.com/user-attachments/assets/173542fd-1e1c-4428-b631-7927130e740e)

<br/>

## 🔧 Stack

**Frontend**
- **Developemt** : Unity
<br />

**Backend**
- **Language** : Python
- **Library & Framework** : numpy, pydicom, pandas, matplotlib, scipy, skimage...
<br/>

## 💡 기대효과

**세그멘테이션 모델 활용으로 장기 분류 정확도를 높여 신뢰도 향상**

**무료로 제공하여 사용자의 접근성 향상**

**가상환경에서  장기를 사용자가 보고 자유롭게 제어할 수 있도록 개발**


<br/>
