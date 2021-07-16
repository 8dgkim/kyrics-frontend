![키릭 로고-01](https://user-images.githubusercontent.com/81923229/124728683-c0ca7600-df4a-11eb-98aa-d80d92e90df1.jpg)

[사이트링크](https://kyrics.vercel.app/)


## 💫 `kyrics`는 이런 서비스입니다!

🎶 Learn Korean through your favorite K-Pop artists and songs!

케이팝 가사로 배우는 우리말, 키릭스 ✨  
키릭스를 통해 우리말을 쉽고 재미있게 배워보세요!

<br/>

## 기능 소개

1. Home View
![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0b0c2ed6-1092-4ab6-bf76-5228fe06ce4f/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0b0c2ed6-1092-4ab6-bf76-5228fe06ce4f/Untitled.png)

아티스트를 선택하는 화면입니다.

2. Artist View
![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/60b4c177-49f9-452a-8e90-387c695a0206/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/60b4c177-49f9-452a-8e90-387c695a0206/Untitled.png)

아티스트의 노래를 선택하는 화면입니다. 

3. Study View
![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/08b5e52b-aeed-4ca6-b11b-b9bae06d3f75/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/08b5e52b-aeed-4ca6-b11b-b9bae06d3f75/Untitled.png)

- 학습이 가능하도록 player를 만들고, Key Expressions 제공합니다.
- 음악이 흘러감에 따라 가사가 하이라이팅 됩니다.
- 가사를 클릭하면, 해당 가사가 흘러나오는 시간으로 이동합니다.

4. Login View
![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/498fe92f-30cb-4344-b4bd-8dcf6009f6c6/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/498fe92f-30cb-4344-b4bd-8dcf6009f6c6/Untitled.png)

- Google, Facebook Social Login을 제공합니다.

5. My Songs View
![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f55a6fa8-231a-4a81-857b-63bfeb5e67ed/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f55a6fa8-231a-4a81-857b-63bfeb5e67ed/Untitled.png)

- 즐겨찾기 추가한 노래를 모아둡니다

6. My Vocab View
![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/740134ca-371e-4508-8498-207c99dd5f1a/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/740134ca-371e-4508-8498-207c99dd5f1a/Untitled.png)

- 즐겨찾기 추가한 단어를 모아둡니다

구현

<br/>

## 🛠 사용한 기술

<img src="https://img.shields.io/badge/-ReactJs-61DAFB?logo=react&logoColor=white&style=flat" height=40>&nbsp;&nbsp;<img src="https://img.shields.io/badge/-Typescript-3074BF?logo=Typescript&logoColor=white&style=flat" height=40>&nbsp;&nbsp;<img src="https://img.shields.io/badge/-Next.js-000000?logo=Next.js&logoColor=white&style=flat" height=40>

```json
"@emotion/react": "^11.4.0",
"@emotion/styled": "^11.3.0",
"axios": "^0.21.1",
"next": "11.0.1",
"react": "17.0.2",
"react-dom": "17.0.2",
"recoil": "^0.3.1",
"reset-css": "^5.0.1",
"swr": "^0.5.6"
```

<br/>

## 🗂 프로젝트 구조

```
.
├── components
│   ├── common
│   │   ├── Footer.tsx
│   │   └── Header.tsx
│   ├── home
│   │   └── Title.tsx
│   ├── mypage
│   │   ├── MySong.tsx
│   │   ├── MyVoca.tsx
│   │   └── Setting.tsx
│   └── study
│       ├── AddVocab.tsx
│       ├── KeyExpression.tsx
│       ├── Lyrics.tsx
│       ├── Player.tsx
│       └── PlayerBtns.tsx
├── hooks
│   └── useExample.ts
├── lib
│   ├── constants
│   │   └── example.ts
│   └── utils
│       └── example.ts
├── next-env.d.ts
├── next.config.js
├── pages
│   ├── _app.tsx
│   ├── category.tsx
│   ├── index.tsx
│   ├── login.tsx
│   ├── mypage
│   │   └── [id].tsx
│   └── study.tsx
├── public
│   └── assets
│       ├── icons
│       │   └── favicon.ico
│       └── images
│           └── example.ts
├── styles
│   └── globals.css
└── types
    └── index.ts
```

## 🖥 Contributer
- [김의진](https://github.com/euijinkk)
- [박나희](https://github.com/Nahee-Park)
- [이다은](https://github.com/Daeun-Danna-Lee)
- [이정연](https://github.com/pa-rang)
