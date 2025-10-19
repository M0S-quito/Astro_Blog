# 🚀 M0S_quito Blog — Built with Astro  

-> codespace에서 테스트 해봄!!
> Personal development log & experimental publishing system.  
> Built for portability, automation, and long-term record keeping.

---

## 🧩 Overview  

이 리포지토리는 **M0S_quito**의 개인 블로그 겸 개발 기록 아카이브다.  
모든 글은 **Obsidian**에서 작성되며, **Astro**를 통해 정적 웹사이트로 빌드된다.  
목표는 **로컬에서 작성 → 자동 빌드 → Git 푸시 → 즉시 배포**의 완전한 자동화를 구현하는 것이다.  

주요 키워드:  
- Termux / Raspberry Pi 기반 로컬 환경  
- Markdown → Astro 변환 파이프라인  
- 개인 지식베이스 & 개발 로그 통합  
- LLM 기반 자동 요약 및 글 정제 실험  

---

## 🧠 Tech Stack  

| Layer | Stack |
| :---- | :---- |
| **Frontend** | [Astro](https://astro.build/) + Markdown/MDX |
| **Styling** | Vanilla CSS / Tailwind (optional) |
| **Content** | Obsidian Vault → `src/content/blog/` |
| **Automation** | Bash + Git Hooks + Termux Scripts |
| **Deployment** | Vercel / GitHub Pages (환경에 따라 선택) |

---

## 📂 Project Structure  

```text
├── public/                 # 정적 파일 (이미지, 폰트 등)
├── src/
│   ├── components/         # 공용 UI 컴포넌트
│   ├── content/
│   │   └── blog/           # Markdown 기반 포스트
│   ├── layouts/            # 페이지 레이아웃
│   └── pages/              # 라우트별 페이지 (*.astro, *.md)
├── astro.config.mjs        # Astro 설정
├── package.json            # 의존성 및 스크립트
└── README.md               # 바로 이 파일
```

---

## ⚙️ Commands  

| Command | Description |
| :------- | :----------- |
| `npm install` | 의존성 설치 |
| `npm run dev` | 로컬 개발 서버 실행 (`localhost:4321`) |
| `npm run build` | 프로덕션 빌드 (`/dist/` 폴더 생성) |
| `npm run preview` | 빌드 결과 미리보기 |
| `npm run astro ...` | Astro CLI 명령 실행 (`astro add`, `astro check` 등) |

---

## 🧭 Vision  

> **“기록은 개발의 일부다.”**  
> 이 프로젝트는 단순한 블로그가 아니라,  
> 나의 학습과 실험이 자동화된 형태로 쌓이는 공간이다.  

앞으로 다음과 같은 기능들이 추가될 예정이다:
- Git 커밋 기반 자동 요약 및 포스트 생성  
- Markdown 기반 OS 실험: **M0S_MD**  
- 로컬 LLM 통합 및 지식 그래프 시각화  

---

## 🧾 Credits  

기본 테마는 [Astro Blog Starter](https://astro.build/themes/details/astro-blog/)를 기반으로 수정되었으며,  
UI 구조는 [Bear Blog](https://github.com/HermanMartinus/bearblog/)의 간결한 설계에서 영감을 받았다.  

---

### 💬 Contact  
- GitHub: [@M0S-quito](https://github.com/M0S-quito)  
- Mail: mosquito.dev@proton.me *(예시, 실제 메일로 변경 가능)*  
