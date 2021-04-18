---
title: "タイトル"
emoji: "✨"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: []
published: false
---

## 1. Nextjs Project 新規作成

---

### 1-1. create-next-app

コマンドに --use-npm をつけると Yarn ではなく npm を使用することができる

```jsx
npx create-next-app . --use-npm
```

Node.js version 10.13 以降が必要です。→ ターミナル `node -v`でバージョン確認

### 1-2. 必要 module のインストール

- msw(mock service worker) ・・・ REST API の API を Mock するためのモジュール

```jsx
axios;
msw;
swr;
```

コピー用

```jsx
npm i axios msw swr
```

### 1-3. vscode 拡張機能をインストール

- ES7 React/Redux/GraphQL/React-Native snippets
  [https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
- Jest
  [https://marketplace.visualstudio.com/items?itemName=Orta.vscode-jest](https://marketplace.visualstudio.com/items?itemName=Orta.vscode-jest)
- Prettier - Code formatter
  [https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

### 1-3. package.json に prettier の設定を追加

```jsx
"prettier": {
  "singleQuote": true,
  "semi": false
}
```
