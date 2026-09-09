# 작업 계획

### 📁 폴더 구조 및 브랜치 전략
___

```
.
├── members
│   ├── about.md
│   ├── goals.md
│   └── skills.md
└── README.md
```

**폴더 구조** : 과제의 목표에 맞게 members라는 상위 디렉토리에
각 주제에 해당하는 md파일을 생성했습니다.

- about.md : 한 줄 소개
- skills.md : 관심 기술
- goals.md : 이번 온보딩 목표

**브랜치 전략** :
- 소규모 과제이므로 간단한 GitHub Flow 선택

파일마다 다른 feature 브랜치에서 작업 후 각각 PR하여 main에 병합할 예정입니다.

- main : 작업 통합 브랜치
- feature/about : "about.md" 작성 전용 브랜치
- feature/skills : "skills.md" 작성 전용 브랜치
- feature/goals : "goals.md" 작성 전용 브랜치

### 📌 PR 순서

- **about -> skills -> goals**

자기소개에서 중요한 순서대로 먼저 완성되도록 이렇게 순서를 정하였습니다.

- 브랜치별로 작업 -> PR -> merge까지 한 번에 진행

하나의 작업에 집중하기 위하여 브랜치를 병행하지 않고 차례대로 진행하였습니다.

### 🔗 페이지 연결
- **[about.md](./members/about.md)**
- **[skills.md](./members/skills.md)**
- **[goals.md](./members/skills.md)**