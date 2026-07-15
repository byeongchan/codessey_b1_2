# codessey_b1_2

## 목차
[1. 기획 정의](#1-기획-정의)

[2. 스토리보드](#2-스토리보드)

[3. 영상 스펙](#3-영상-스펙)

[4. 제작 절차 및 검수](#4-제작-절차-및-검수)

[5. T2I(Text-to-Image) vs I2V(Image-to-Video)](#5-t2itext-to-image-vs-i2vimage-to-video)

[6. 도구 선택 비교](#6-도구-선택-비교)

[7. 예산(크레딧) 부족 시 대응 방안](#7-예산크레딧-부족-시-대응-방안)

[8. 시간축 단축 기준 및 메시지 재구성 전략](#8-시간축-단축-기준-및-메시지-재구성-전략)

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
- 생성 계획
    - 예상 생성 시도 횟수 : 최대 3회
    - 대체 도구
        - 이미지 : Google Gemini
        - 영상 : Runway
        - 음성 : OpenAI-TTS
- 목표 메시지
    - AI 시대에 필요한 역량을 실습 중심 AI 교육을 통해 효과적으로 배울 수 있음을 전달한다.
- 화면 구성
    - 미래적인 강의실
    - 노트북을 바라보는 학생
    - AI 홀로그램 등장
- 내레이션
    - "AI를 배우는 가장 확실한 방법"
- 사용도구
    - ChatGPT Image : 학생 이미지 생성(직접 촬영 및 유료 스톡 이미지는 사용하지 않았으며, ChatGPT Image에서 생성한 결과물만 사용)
    - GPT-4o Mini TTS : 내레이션 생성
    - Google Veo 3.1 : 영상 생성
- 입력 프롬프트
    - Main Character: A young Korean university student in his early 20s with short black hair, wearing a navy hoodie, black pants, white sneakers, and carrying a laptop. Keep the same appearance throughout the video.
    - The student sits alone in a modern classroom looking at his laptop with a thoughtful expression. Blue holographic AI elements such as coding, machine learning, artificial intelligence, neural networks, and data visualization slowly appear around him. The lighting is slightly dark and cinematic. The camera slowly moves toward the student.
    - Transition
        - The holograms expand into a bright futuristic digital environment.
    - No logos, company names, or text should appear anywhere during these scenes.
- 후처리 및 제어 파라미터
    - 후처리 범위 : 색감(블루 계열 톤) 보정, 장면 간 밝기와 분위기 일관성 유지, 불필요한 요소 제거
    - 제어 가능한 파라미터
        - 포즈 : 노트북을 바라보는 앉은 자세
        - 표정 : 고민하는 표정에서 자신감 있는 표정으로 변화
        - 색감 : 미래지향적인 블루 계열 색감 유지
        - 조명 : 어두운 분위기에서 밝은 분위기로 전환

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
- 추가 사유 : 영상을 하나의 프롬프트로 생성했을 때, 레퍼런스로 추가한 브랜드 로고가 첫 번째 Scene부터 노출되는 문제가 발생하였다. 첫 번째 Scene에서는 브랜드를 노출하지 않는 연출이 필요했기 때문에, 로고를 마지막 Scene에서만 표시하도록 명시하는 프롬프트를 추가하여 수정하였다. 수정 후 마지막 Scene에서만 로고가 표시되었다.

- 출력 결과 요약
    - AI 학습을 통해 성장하는 학생의 모습을 미래적인 분위기로 표현
- 파일명
    - codyssey_s01_character_v01.png
    - codyssey_s01_narration_v01.mp3
    - codyssey_final_v01.mp4
---

#### Scene 2 (4~8초)
- 생성 계획
    - 예상 생성 시도 횟수 : 최대 3회
    - 대체 도구
        - 영상 : Runway
        - 음성 : OpenAI-TTS
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
    - codyssey_s02_logo_v01.png
    - codyssey_final_v01.mp4

---

### 3. 영상 스펙
|속성|값|
|---|---|
|해상도|720p|
|프레임|24fps|
|비디오 코덱|H.264|
|오디오 코덱|AAC|
|색공간|Rec.709, 블루 계열의 미래지향적 색감(Futuristic Blue Tone)|
|도구 통합 워크플로우|ChatGPT Image로 생성한 이미지를 Google Veo 3.1에서 영상으로 생성한 후, 최종 결과를 720p(Rec.709 색공간)로 출력하고 GPT-4o Mini TTS로 생성한 내레이션을 결합하여 최종 영상을 제작하였다.|

---

### 4. 제작 절차 및 검수
|단계|주요 작업|책임|핵심 산출물|검수 체크리스트|
|---|---|---|---|---|
|기획|브랜드 아이덴티티, 타겟, 핵심 메시지 및 스토리보드 작성|제작자|기획서,스토리보드|브랜드 목적이 명확한가? / 씬 구성이 스토리 흐름에 맞는가?|
|생성|AI 이미지, 영상, 음성 생성 및 프롬프트 작성|제작자|AI 이미지, AI 영상, AI 음성|캐릭터 일관성이 유지되는가? / 프롬프트 의도대로 생성되었는가? / 브랜드 로고가 마지막 장면에만 노출되는가?|
|검수·편집/통합|생성 결과 검토, 내레이션 및 영상 통합, 최종 출력|제작자|최종 광고 영상(MP4)|영상 길이가 10초 이내인가? / 음성과 영상이 자연스럽게 연결되는가? / 최종 장면에 브랜드 로고가 정상적으로 노출되는가?|

---

### 5. T2I(Text-to-Image) vs I2V(Image-to-Video)
|구분|내용|
|---|---|
|T2I|프롬프트만으로 이미지를 생성할 수 있어 다양한 아이디어를 빠르게 구현할 수 있지만, 장면 간 캐릭터와 구도의 일관성을 유지하기 어렵다.|
|I2V|생성된 이미지를 기반으로 영상을 제작하므로 캐릭터와 장면의 일관성을 유지하기 쉽고, 광고와 같은 연속적인 영상 제작에 적합하다.|

#### 본 프로젝트의 선택 근거
- 본 프로젝트는 동일한 캐릭터를 유지하면서 브랜드 광고 영상을 제작하는 것이 중요했기 때문에, 먼저 ChatGPT Image로 캐릭터 이미지를 생성한 후 Google Veo 3.1의 I2V(Image-to-Video) 기능을 활용하여 영상을 제작하였다. 이를 통해 장면 간 캐릭터의 외형과 분위기를 일관되게 유지할 수 있었다.

---

### 6. 도구 선택 비교
|작업|사용 도구|대안 도구|예상 품질|예상 생성 시간|예상 비용|
|---|---|---|---|---|---|
|이미지 생성|ChatGPT Image|Google Gemini Image|ChatGPT Image가 캐릭터 일관성 표현에 유리|ChatGPT Image 약간 느림|둘 다 무료 사용 가능 범위|
|영상 생성|Google Veo 3.1|Runway|Veo 3.1이 자연스러운 영상 전환에 유리|Veo 3.1이 다소 느림|둘 다 유료 플랜에서 고품질 지원|
|음성 생성|GPT-4o Mini TTS|OpenAI TTS|두 도구 모두 자연스러운 음성을 제공하며, GPT-4o Mini TTS는 프로젝트에서 사용한 워크플로와의 호환성이 높음|OpenAI TTS가 유사하거나 다소 빠름|GPT-4o Mini TTS가 상대적으로 비용 부담이 적음|

- 도구 선택 기준
    - 품질(50%), 생성 속도(30%), 비용(20%)을 기준으로 평가하여 도구를 선정하였다. 광고 영상의 완성도를 가장 중요하게 고려하여 품질을 최우선으로 두었다.

---

### 7. 예산(크레딧) 부족 시 대응 방안
|상황|대응 방안|
|---|---|
|이미지 생성 크레딧 부족|ChatGPT Image 대신 Google Gemini를 사용하여 이미지 생성|
|영상 생성 크레딧 부족|Scene 1의 생성 횟수를 우선 줄이거나 영상 길이를 단축하고, Runway를 대체 도구로 사용|
|음성 생성 크레딧 부족|OpenAI TTS를 사용하여 동일한 내레이션 생성|

- 우선순위
1. Scene 1의 재생성 횟수를 줄여 크레딧을 절감한다.
2. 영상 생성이 어려운 경우 Runway를 활용하여 동일한 장면을 생성한다.
3. 이미지와 음성은 각각 Google Gemini, OpenAI TTS를 사용하여 기존 워크플로를 유지한다.

### 8. 시간축 단축 기준 및 메시지 재구성 전략

#### 핵심 메시지 우선순위(메시지 스코어)
|요소|중요도|유지 여부|
|---|---|---|
|브랜드 로고 및 브랜드 리빌|★★★★★|반드시 유지|
|핵심 내레이션 ("AI를 배우는 가장 확실한 방법. 실무 중심 AI 교육, 코디세이.")|★★★★★|반드시 유지|
|AI 학습 장면|★★★★|우선 유지|
|AI 홀로그램 및 시각 효과|★★★|필요 시 축소 가능|
|카메라 이동 및 전환 효과|★★|필요 시 단순화 가능|

- 메시지 재구성 원칙
    - 영상 시간이 부족한 경우 브랜드 리빌과 핵심 내레이션은 반드시 유지한다.
    - 부가적인 시각 효과(홀로그램, 파티클, 카메라 연출)는 축소하거나 단순화한다.
    - 장면 수는 유지하되 각 장면의 길이를 조정하여 "AI 학습 → 브랜드 소개"의 핵심 흐름이 유지되도록 구성한다.