# これは？

Webアプリを作っていくための白紙ページ

## 開発ガントチャート

```mermaid
gantt
    dateFormat  MM-DD
    excludes weekends
    axisFormat %m/%d
    tickInterval 1week
    section フレームワーク
        技術選定:des0, 2024-06-15, 6d
        設計: des1, after des0,12d
        コーディング: des2, after des1,18d
        デバッグ: des3, after des2,6d

```

```mermaid
gantt
    dateFormat  MM-DD
    excludes weekends
    axisFormat %m/%d
    tickInterval 1week
    section フォームアプリ開発
        設計:des4, after 2024, 3d
        デザイン: des5, after des4,3d
        コーディング: des6, after des5,12d
        デバッグ: des7, after des6,6d
```

## 試験稼働

```
git clone https://github.com/miatia1025/firstReact
cd firstReact
npm install
npm start
```

## 開発者

```
git clone https://github.com/miatia1025/firstReact
cd firstReact
npm install
code .
```
