<h1 align="center">설성범</h1>
<p align="center"><strong>AI/ML Engineer</strong></p>

<p align="center">
  <a href="https://seongbeom-seol.vercel.app"><img alt="포트폴리오" src="https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge&amp;logo=googlechrome&amp;logoColor=white"></a>
  <a href="https://woojab.tistory.com/"><img alt="블로그" src="https://img.shields.io/badge/Blog-7C3AED?style=for-the-badge&amp;logo=tistory&amp;logoColor=white"></a>
</p>

검색, 컴퓨터 비전, AI 에이전트 워크플로를 다룹니다. 근거를 확인할 수 있고, 결과를 측정할 수 있으며, 다른 사람이 이어서 개발할 수 있는 소프트웨어를 만들고 있습니다.

**알고리즘 문제 해결:** [백준 플래티넘 V](https://solved.ac/profile/tjftjdqja)

## 주요 프로젝트

### [Reweave](https://github.com/seolbbb/reweave)

AI와 나눈 대화에는 결정과 배운 점, 아직 풀지 못한 질문이 쌓입니다. 하지만 대화가 끝나면 다시 꺼내 쓰기 어렵고, 새 채팅을 열 때마다 맥락을 처음부터 설명하게 됩니다. Reweave는 사용자가 저장한 ChatGPT·Claude 대화를 출처가 연결된 Conversation Brief와 Context Item으로 정리해 하나의 Context Library로 만듭니다. 필요할 때 관련 맥락을 지금 쓰는 웹 채팅에 넣습니다. 기록은 로컬에 남기고, 사용자가 Save나 Use를 눌렀을 때만 브라우저 대화를 읽습니다.

`Python` · `FastAPI` · `SQLite / FTS5` · `FastEmbed` · `BM25 / RRF` · `React` · `TypeScript` · `Chrome/Edge Extension (Manifest V3)` · `Native Messaging` · `pywebview`

검색은 FTS5/BM25와 로컬 다국어 임베딩을 RRF로 결합했습니다. 한국어·영어 32개 질의 골든셋에서 Recall@10은 키워드 검색 `0.3438`에서 하이브리드 검색 `0.9688`로 향상되었습니다.

### [Re:View](https://github.com/seolbbb/Re-View)

- 네이버 커넥트재단 부스트캠프 AI Tech 8기 최종 프로젝트.

강의 영상을 음성으로만 옮기면 슬라이드와 판서의 맥락이 빠집니다. Clova Speech와 Whisper의 STT 결과를 VLM 화면 분석과 시간축으로 결합해 요약했습니다. LangGraph로 구성한 RAG 챗봇은 요약과 원문 근거를 찾아 후속 질문에 답합니다. 요약, 판정, 질문 추천에 쓰는 프롬프트도 단계별로 분리해 반복 실험할 수 있게 했습니다.

[`서비스 바로가기`](https://www.smrtreview.com)

`Python` · `FastAPI` · `React` · `LangGraph` · `RAG` · `Supabase (PostgreSQL / pgvector)` · `Clova Speech / Whisper` · `OpenCV` · `Gemini / Qwen VLM` · `Prompt Engineering`

### [Pazule](https://github.com/seolbbb/pazule)

사진 한 장의 정답 여부만 판정하지 않고, 실제 장소를 찾아다니는 과정을 AI 미션으로 만들었습니다. BLIP-VQA로 랜드마크를 확인하고 CLIP으로 사진의 분위기를 판별합니다. 미션에 실패하면 두 모델의 판정 결과를 GPT-4o-mini에 전달해 정답을 바로 말하지 않는 힌트를 만듭니다.

`Python` · `PyTorch` · `Hugging Face Transformers` · `BLIP-VQA` · `CLIP` · `OpenAI API (GPT-4o-mini)` · `Pillow`

## 공개한 Skills

### [manage-project-intent](https://github.com/seolbbb/manage-project-intent)

AI 덕분에 구현은 빨라졌지만, 선택의 이유와 우선순위가 대화에만 남으면 기술 부채와 방향 수정 비용도 함께 커집니다. manage-project-intent는 구현 전에 중요한 질문이 모두 정리될 때까지 인터뷰하고, 제품 명세·로드맵·현재 상태·결정 기록을 저장소에 남깁니다. 여러 세션은 문서에 적힌 하나의 Next task를 기준으로 작업을 나눠 이어갈 수 있습니다. Goldfish 검증으로 새 세션이 문서만 읽고도 사용자의 의도와 다음 작업을 복원하는지 확인합니다.

`Python` · `Markdown` · `YAML` · `pytest`

### [write-korean-cover-letter](https://github.com/seolbbb/write-korean-cover-letter)

자기소개서를 여러 번 고쳐도 문항에 맞지 않는 경험, 과장된 역할, 충돌하는 수치가 남곤 합니다. 공고와 사용자 자료를 먼저 대조해 문항별 경험을 고릅니다. 사실과 기여 범위, 문항 간 중복을 확인한 뒤에만 문장을 다듬습니다. 잡코리아·링커리어에 공개된 합격 자기소개서 223건을 구조 중심으로 분석하고, 고용24와 NCS 공정채용 자료를 함께 검토해 작성 방법론에 반영했습니다.

`Markdown` · `Python` · `YAML` · `Shell`

## 컴퓨터 비전 프로젝트

- 네이버 커넥트재단 부스트캠프 AI Tech 8기에서 진행했습니다.

### [손 뼈 X-ray 이미지 분할](https://github.com/boostcampaitech8/pro-cv-semanticsegmentation-cv-02)

`Python` · `PyTorch` · `Segmentation Models PyTorch (SMP)` · `MMSegmentation` · `Albumentations` · `W&B`

### [재활용 쓰레기 객체 탐지](https://github.com/boostcampaitech8/pro-cv-objectdetection-cv-02)

`Python` · `PyTorch` · `MMDetection` · `Ultralytics YOLO` · `COCO` · `W&B`

## 기술

`Python` · `PyTorch` · `FastAPI` · `SQLite` · `React` · `TypeScript` · `컴퓨터 비전` · `검색 및 평가`

## Links

[포트폴리오](https://seongbeom-seol.vercel.app/) · [블로그](https://woojab.tistory.com/) · [solved.ac](https://solved.ac/profile/tjftjdqja)

---

<p align="right"><a href="./README.en.md">English</a></p>
