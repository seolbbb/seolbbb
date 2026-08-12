<h1 align="center">설성범</h1>
<p align="center"><strong>AI/ML Engineer</strong></p>

<p align="center">
  <a href="https://seongbeom-seol.vercel.app"><img alt="포트폴리오" src="https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge&amp;logo=googlechrome&amp;logoColor=white"></a>
  <a href="https://woojab.tistory.com/"><img alt="블로그" src="https://img.shields.io/badge/Blog-7C3AED?style=for-the-badge&amp;logo=tistory&amp;logoColor=white"></a>
</p>

RAG, 컴퓨터 비전, AI 에이전트 워크플로를 실제로 쓸 수 있는 제품으로 구현하는 데 관심이 있습니다.

[![Solved.ac
프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj={tjftjdqja})](https://solved.ac/{tjftjdqja})
## 주요 프로젝트

### [Reweave](https://github.com/seolbbb/reweave)

AI와 나눈 대화 속엔 결정한 것, 배운 것, 아직 풀지 못한 질문들이 쌓입니다. 그런데 대화창을 닫고 나면 다시 꺼내 보기 어렵고, 새 채팅을 열 때마다 맥락을 처음부터 다시 설명해야 합니다. Reweave는 저장해둔 ChatGPT·Claude 대화를 출처가 남아있는 문서로 정리하고, 문서끼리 링크를 걸어 나만의 Context Library로 만들어줍니다. 필요한 맥락은 지금 쓰고 있는 채팅창에 바로 가져와 쓸 수 있습니다.

`Python` · `FastAPI` · `SQLite / FTS5` · `FastEmbed` · `BM25 / RRF` · `React` · `TypeScript`

### [Re:View](https://github.com/seolbbb/Re-View)
**네이버 커넥트재단 부스트캠프 AI Tech 8기 최종 프로젝트**

강의 영상을 음성만으로 기록하면 슬라이드와 판서에 담긴 맥락이 사라집니다. Clova Speech와 Whisper로 뽑은 STT 결과에 VLM의 화면 분석을 더해 요약하는 서비스입니다. 챗봇이 RAG를 통해 요약본과 원문 근거를 찾아 후속 질문에 답합니다.
[`서비스 바로가기`](https://www.smrtreview.com)

`Python` · `FastAPI` · `React` · `LangGraph` · `RAG` · `Supabase (PostgreSQL / pgvector)` · `Clova Speech` · `OpenCV` · `VLM` · `Prompt Engineering`

### [Pazule](https://github.com/seolbbb/pazule)

키워드에 맞는 장소를 찾아가는 AI 보물찾기 서비스입니다. BLIP-VQA로 랜드마크를 확인하고 CLIP으로 사진 분위기를 판별합니다. 미션에 실패하면 두 모델의 판정 결과를 LLM에 전달해 상황에 맞는 힌트를 만들어줍니다.

`Python` · `PyTorch` · `Hugging Face Transformers` · `BLIP-VQA` · `CLIP` · `OpenAI API (GPT-4o-mini)` · `Pillow`

## Skills

### [manage-project-intent](https://github.com/seolbbb/manage-project-intent) - 프로젝트 Context 관리

AI 덕분에 구현 속도는 빨라졌지만, 사용자의 의도와 선택의 이유, 명세가 제대로 기록되지 않으면 기술 부채와 방향 수정 비용은 그대로 쌓입니다. manage-project-intent는 구현에 들어가기 전 중요한 질문들이 모두 정리될 때까지 인터뷰를 진행하고, 제품 명세·로드맵·현재 상태·결정 기록을 저장소에 남깁니다. Goldfish 검증으로 문서와 실제 코드 사이에 차이가 없는지 확인합니다.

### [write-korean-cover-letter](https://github.com/seolbbb/write-korean-cover-letter)

자기소개서는 아무리 고쳐도 문항과 맞지 않는 경험, 과장된 역할, 서로 충돌하는 수치가 남기 마련입니다. 공고와 사용자 자료를 먼저 대조해 문항별로 쓸 경험을 고르고, 사실 관계와 기여 범위, 문항 간 중복을 확인한 뒤에야 문장을 다듬습니다. 잡코리아·링커리어에 공개된 합격 자기소개서 223건을 구조 중심으로 분석해 만들었습니다.

## 컴퓨터 비전 프로젝트
**네이버 커넥트재단 부스트캠프 AI Tech 8기**

### [손 뼈 X-ray 이미지 분할](https://github.com/boostcampaitech8/pro-cv-semanticsegmentation-cv-02)

`Python` · `PyTorch` · `Segmentation Models PyTorch (SMP)` · `MMSegmentation` · `W&B`

### [재활용 쓰레기 객체 탐지](https://github.com/boostcampaitech8/pro-cv-objectdetection-cv-02)

`Python` · `PyTorch` · `MMDetection` · `Ultralytics YOLO` · `W&B`

## 기술

`Python` · `PyTorch` · `FastAPI` · `Computer Vision` · `RAG`

## Links

[포트폴리오](https://seongbeom-seol.vercel.app/) · [블로그](https://woojab.tistory.com/) · [solved.ac](https://solved.ac/profile/tjftjdqja)

---

<p align="right"><a href="./README.en.md">English</a></p>
