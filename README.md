```markdown
# 🚀 [GenAI] 멀티모달 AI 기반 브랜드 광고 캠페인: "오디(Odi)의 ODA 진로 탐방"

> **과제명**: GenAI 기초 2 - 멀티모달 콘텐츠 제작  
> **학습 시간**: 40시간  
> **브랜드명**: 오디(Odi) - 학과진로 x ODA 안내 프로젝트  
> **최종 영상**: 숏폼 광고 영상 (`.mp4`, 8.5초, 9:16 비율)  

---

## 📌 1. 프로젝트 개요 & 브랜드 아이덴티티

본 프로젝트는 AI 생성 도구 및 디자인 플랫폼(Gemini, NATO AI, Canva, CapCut)을 활용하여 **기획 의도 → 프롬프트 설계 → 멀티모달 생성 → 통합 편집**으로 이어지는 완성형 제작 파이프라인을 구축하는 것을 목표로 합니다.

* **브랜드명**: 오디(Odi)
* **타겟**: 학부 전공과 글로벌 진로/ODA(공적개발원조) 연계에 관심 있는 대학생 및 청년층
* **톤앤매너**: 친근함, 교육적, 트렌디함, 2D 일러스트 애니메이션 스타일
* **USP (차별점)**: 어렵게 느껴지는 ODA 및 국제개발협력 정보를 학과별(간호학과, 사회학과, 경영학과 등) 맞춤형 진로 트랙과 결합하여 귀여운 캐릭터 '오디'가 직관적으로 안내
* **캠페인 핵심 메시지**: **"너의 전공이 세계를 바꾼다! 오디와 함께 알아보는 학과별 ODA 진로 탐방!"**

---

## 🛠️ 2. 멀티모달 AI 파이프라인 및 도구 구성

과제 요구사항에 맞춰 시각/청각 요소 모두 생성형 AI 소스와 디지털 디자인 툴을 주된 소스로 활용했습니다.

| 구분 | 주요 사용 도구 | 선택 이유 및 주요 역할 | 대체 도구 (비상용) |
| :--- | :--- | :--- | :--- |
| **이미지 생성/디자인** | **Canva** | 마스코트('오디') 레이아웃 배치, 소스 합성 및 2D 디자인 보정 | Midjourney / DALL-E 3 |
| **비디오 변환/생성** | **Gemini & NATO AI** | 텍스트/이미지 기반 비디오 소스 생성 및 애니메이션 연출 | Runway / Pika |
| **오디오 생성** | **NATO AI & Gemini** | 내레이션 TTS 및 배경 음악 소스 생성 | ElevenLabs / Typecast |
| **통합 편집** | **CapCut** | 컷 편집, 자막 배치, 오디오 레벨 조정 및 최종 숏폼 인코딩 | Premiere Pro |

---

## 💡 3. 도구별 활용 경험 및 장단점 분석 (Tool Experience)

프로젝트 제작 과정에서 각 AI 및 디자인 도구를 직접 활용하며 경험한 강점과 한계점은 다음과 같습니다.

* **NATO AI (네이토 AI)**
  * **경험**: 미션 수행 과정에서 생성 토큰 수량의 한계(Credit Limit)가 존재하여, 프롬프트 시도를 무제한으로 하기 어려웠습니다. 이에 따라 스토리보드 단계에서 사전 구상을 명확히 한 후 생성 횟수를 최소화하는 전략을 사용했습니다.
* **Gemini (제미나이)**
  * **경험**: 영상 및 비주얼 소스 생성 시 매우 뛰어난 화질과 고품질의 결과물을 보여주었습니다. 다만, 프롬프트나 씬 전환에 따라 캐릭터의 세부 디자인이나 화풍의 일관성(Consistency)을 지속적으로 유지하는 데에는 다소 아쉬움이 있었습니다.
* **Canva (캔바)**
  * **경험**: 전문 디자인 툴답게 레이아웃, 요소 배치, 텍스트 스타일 수정 등 디자인 수정의 자유도가 매우 높아 원하는 구도를 잡기 용이했습니다. 하지만 원본 비율 제어나 특정 멀티모달 캔버스 비율 커스텀 제작에 있어서는 세밀한 조율에 한계가 있었습니다.
* **CapCut (캡컷)**
  * **경험**: 각 생성 소스(영상, 음성, BGM)를 타임라인에 올려 완벽히 동기화하고, 9:16 비율에 맞게 컷 편집 및 최종 텍스트 레이어링을 통합 완료하는 용도로 적절히 활용되었습니다.

---

## 🎬 4. 씬별 상세 스토리보드 (총 8.5초)

### 📍 Scene 1: Intro (0.0s ~ 3.0s)
* **목표 메시지**: "내 전공으로 글로벌 ODA 무대에 도전할 수 있을까?" 호기심 유발
* **화면 구성**: 밝은 대학 캠퍼스 배경, 다양한 학과 학생들과 전면에 파란색 지구 마스코트 '오디' 배치
* **내레이션/카피**: *"학과 진로와 ODA를 새로 새로 알아보자! 간호학과, 사회학과, 경영학과편!"*
* **사용 도구**: Canva (디자인/레이아웃), Gemini/NATO AI (영상/오디오 생성), CapCut (통합)
* **입력 프롬프트**:
  ```text
  2D clean illustration, bright university campus background, students walking with backpacks, a cute round blue earth-like mascot character named 'Odi' wearing purple pants with a name tag '오디', bright typography header, vibrant colors, webtoon style --ar 9:16

```


---

### 📍 Scene 2: Main Body (3.0s ~ 6.0s)

* **목표 메시지**: 간호, 사회학, 경영학 등 전공별 ODA 진로 가능성 제시
* **화면 구성**: 화면 3등분 분할 (청진기/보건, 사람 네트워크/사회학, 서류가방/경영학 아이콘) 및 오디의 안내 동작
* **내레이션/카피**: *"보건의료, 사회개발, 경영컨설팅까지! 너의 전공이 글로벌 무대의 열쇠가 돼!"*
* **사용 도구**: Canva (전공 아이콘 합성), Gemini (비디오 생성), NATO AI (음성)
* **입력 프롬프트**:
```text
Infographic style 2D graphic showing three major fields: healthcare stethoscope, social network map, and business growth chart with cute mascot Odi explaining, vector style, bright colors --ar 9:16

```



---

### 📍 Scene 3: Outro / Call To Action (6.0s ~ 8.5s)

* **목표 메시지**: 오디 ODA 프로젝트 참여 및 상세 정보 확인 유도 (브랜드 각인)
* **화면 구성**: 오디 캐릭터 줌인 샷, 검색창 UI("학과진로 ODA") 및 CTA 버튼("지금 확인하기")
* **내레이션/카피**: *"지금 바로 오디와 함께 새로운 진로를 찾아봐!"* (하단 카피: *오디와 함께하는 ODA 진로 탐방*)
* **사용 도구**: Gemini (캐릭터 줌인 영상), CapCut (검색창 자막 및 CTA 최종 합성)
* **입력 프롬프트**:
```text
Cute blue mascot character Odi waving hands enthusiastically, central focus, white/light blue clean gradient background, high quality 2D webtoon animation style --ar 9:16

```



---

## 🔍 5. 프롬프트 개선 및 해결 과정 (Prompt Iteration Log)

* **수정 전 의도**: `cute blue mascot character in front of university, title text '학과진로와 ODA'`
* **문제점**:
1. AI 비디오/이미지 생성을 직접 시도했을 때 텍스트 뭉개짐 및 캐릭터 일관성 저하 문제 발생
2. 네이토 AI 토큰 한계로 인해 다수의 프롬프트 테스트에 제약 발생


* **수정 후 프롬프트 & 접근 방식**:
```text
2D clean vector illustration, cute round blue earth-like mascot character named 'Odi' with big eyes, wearing purple pants and a small nametag '오디', bright university campus background, educational cartoon style, high quality --ar 9:16

```


* **개선 및 해결 성과**:
* AI 생성 단계에서는 오디 캐릭터의 비주얼과 퀄리티(Gemini 활용)에 집중
* 텍스트 및 상세 요소 배치는 디자인 툴인 Canva와 CapCut 편집 단계를 병행하여 일관성 불일치 및 토큰 소모 문제 극복



---

## 🎞️ 6. 최종 인코딩 및 출력 스펙

* **파일명**: '코디세이 제출_1분'
* **영상 길이**: 8.5초 (10초 이내 요구사항 준수)
* **해상도 / 비율**: 1080 x 1920 (9:16 숏폼 표준)
* **프레임레이트**: 30 fps
* **비디오/오디오 코덱**: H.264 / AAC

```

```
