# codessey_b1_2

## 목차
[1. 기획 정의](#1-기획-정의)

[2. 스토리보드](#2-스토리보드)

[3. 영상 스펙](#3-영상-스펙)

---

### 1. 기획 정의
- 브랜드 : 코디세이(Codyssey)
- 브랜드 소개 : AI 및 디지털 기술 교육을 통해 누구나 실무형 AI 역량을 갖출 수 있도록 지원하는 교육 플랫폼
- 타겟 : AI에 관심 있는 대학생, 취업 준비생, 직장인
- 톤앤매너 : 미래지향적, 전문적, 신뢰감 있는, 희망적인
- USP : 실습 중심 AI 교육과 프로젝트 기반 학습으로 실무 역량을 빠르게 향상시킬 수 있는 교육 프로그램
- 광고 목적 : 브랜드 인지도 향상 및 교육 과정 신청 유도
- 핵심 메시지 : AI를 배우는 가장 확실한 방법. 실무 중심 AI 교육,코디세이.

---

### 2. 스토리보드

#### Scene 1 (0~4초)
- 목표 메시지
    - AI 시대에 필요한 역량을 실습 중심 AI 교육을 통해 효과적으로 배울 수 있음을 전달한다.
- 화면 구성
    - 미래적인 강의실
    - 노트북을 바라보는 학생
    - AI 홀로그램 등장
- 내레이션
    - "AI를 배우는 가장 확실한 방법"
- 사용도구
    - ChatGPT Image : 학생 이미지 생성
    - GPT-4o Mini TTS : 내레이션 생성
    - Google Veo 3.1 : 영상 생성
- 입력 프롬프트
    - Main Character: A young Korean university student in his early 20s with short black hair, wearing a navy hoodie, black pants, white sneakers, and carrying a laptop. Keep the same appearance throughout the video.
    - The student sits alone in a modern classroom looking at his laptop with a thoughtful expression. Blue holographic AI elements such as coding, machine learning, artificial intelligence, neural networks, and data visualization slowly appear around him. The lighting is slightly dark and cinematic. The camera slowly moves toward the student.
    - Transition
        - The holograms expand into a bright futuristic digital environment.
    - No logos, company names, or text should appear anywhere during these scenes.


#### 프롬프트 수정 전/후 비교
## v1
```
- Main Character: A young Korean university student in his early 20s with short black hair, wearing a navy hoodie, black pants, white sneakers, and carrying a laptop. Keep the same appearance throughout the video.

- The student sits alone in a modern classroom looking at his laptop with a thoughtful expression. Blue holographic AI elements such as coding, machine learning, artificial intelligence, neural networks, and data visualization slowly appear around him. The lighting is slightly dark and cinematic. The camera slowly moves toward the student.

- Transition
    - The holograms expand into a bright futuristic digital environment.

```

## v2
```
- Main Character: A young Korean university student in his early 20s with short black hair, wearing a navy hoodie, black pants, white sneakers, and carrying a laptop. Keep the same appearance throughout the video.

- The student sits alone in a modern classroom looking at his laptop with a thoughtful expression. Blue holographic AI elements such as coding, machine learning, artificial intelligence, neural networks, and data visualization slowly appear around him. The lighting is slightly dark and cinematic. The camera slowly moves toward the student.

- Transition
    - The holograms expand into a bright futuristic digital environment.

- No logos, company names, or text should appear anywhere during these scenes.
```
- 추가 사유 : 영상을 하나의 프롬프트로 생성했을 때, 레퍼런스로 추가한 브랜드 로고가 첫 번째 Scene부터 노출되는 문제가 발생하였다. 첫 번째 Scene에서는 브랜드를 노출하지 않는 연출이 필요했기 때문에, 로고를 마지막 Scene에서만 표시하도록 명시하는 프롬프트를 추가하여 수정하였다.

- 출력 결과 요약
    - AI 학습을 통해 성장하는 학생의 모습을 미래적인 분위기로 표현
- 파일명
    - chr_ref.png
    - 내레이션.mp3
    - 코디세이.mp4
---

#### Scene 2 (4~8초)
- 목표 메시지
    - 브랜드를 소개하고 AI 교육 플랫폼임을 전달한다.
- 화면 구성
    - 코디세이 로고
    - 블루 배경과 파티클
- 내레이션
    - "실무 중심 AI 교육,코디세이"
- 사용도구
    - GPT-4o Mini TTS : 내레이션 생성
    - Google Veo 3.1 : 영상 생성
- 입력 프롬프트
    - The glowing particles gather together and smoothly reveal the uploaded reference image. Use the uploaded reference image as the official brand logo only in this final scene.
- 출력 결과 요약
    - 로고를 활용하여 브랜드 리빌 장면 생성
- 파일명
    - logo_ref.png
    - 코디세이.mp4

---

### 3. 영상 스펙
|속성|값|
|---|---|
|해상도|720p|
|프레임|24fps|
|비디오 코덱|H.264|
|오디오 코덱|AAC|