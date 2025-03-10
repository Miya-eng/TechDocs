## 1. HTML とは
HTML（HyperText Markup Language）は、**ウェブページの骨組みを作るための言語**で、ウェブサイトの**部品（見出し・文章・画像・ボタンなど）**を作る役割を担ってる。

## 2. CSS とは
CSS（Cascading Style Sheets）は、**HTMLで作られたページのデザイン（見た目）を整えるための言語**。
HTMLが「家の骨組み」なら、CSSは「壁紙や家具などの装飾」のようなもの。

## 3. JavaScript とは
JavaScriptは、**ウェブページに動きをつけるためのプログラミング言語**。
HTMLが「骨組み」、CSSが「デザイン」なら、JavaScriptは「動きや機能を追加するエンジン」のようなもの。

## 4. ECMAScript とは
ECMAScript（エクマスクリプト）は、**JavaScriptのルール（仕様）を決めたもの**。
JavaScriptは、もともと自由に開発されていましたが、ルールを統一するためにECMAScriptという基準が作られた。

### ECMAScript 2015（ES6）以降について
ECMAScriptは定期的にアップデートされており、特に**ECMAScript 2015（ES6）**以降は、モダンな書き方が導入された。JavaScriptを学ぶときは、ES2015（ES6）以降の書き方を使うようにする。

ES6以前とES6以降の違い👇

🔹 変数の宣言
ES6以前（古い書き方）
```js
var name = "佐藤";
```
ES6以降（推奨される書き方）
```js
let name = "佐藤"; // 変更可能な変数
const age = 25; // 変更できない定数
```

🔹 関数の書き方
ES6以前（古い書き方）
```js
function hello() {
  return "こんにちは！";
}
```

ES6以降（アロー関数）
```js
const hello = () => "こんにちは！";
```

🔹 テンプレートリテラル（文字列の扱い）
ES6以前
```js
let name = "佐藤";
console.log("こんにちは、" + name + "さん！");
```

ES6以降
```js
let name = "佐藤";
console.log(`こんにちは、${name}さん！`);
```
→ 「`（バッククォート）」を使うことで、文字列を簡単に組み立てられる！

## 5. データ型とは
データ型（Data Type） とは、**プログラムで扱う値の種類**のこと。
もし型がなかったら、数値か文字列かわからず、プログラムが正しく動かなくなる 可能性がある。
データ型を正しく選択することで、メモリの使用量を最適化できるため、パフォーマンスの向上に寄与する。
## 6. JavaScriptのデータ型の種類
1. number（数値）
2. string（文字列）
3. boolean（真偽値）
4. null（ヌル）
5. undefined（未定義）
6. symbol（シンボル）
7. object（オブジェクト）

## 6. DOMとは
DOM（Document Object Model、ドキュメント・オブジェクト・モデル）は、**Webページ（HTML）をプログラムで操作できるようにする仕組み**のこと。
簡単に言うと、「Webページの地図」みたいなもので、ページ内のタグ（HTML要素）をプログラムで変更したり、追加・削除したりするために使う。
ブラウザに表示された Webページの内容（HTML）をJavaScriptで操作できるようにするためにある。

## 7. npmとは
npm（エヌピーエム） は、Node.jsを使うときに**便利なツールやプログラムを管理するためのシステム**のこと。
どのライブラリを使ったかpackage.jsonというファイルに記録して、後で簡単に同じ環境を再現できるようにしてくれる。

## 8. 非同期処理とは
まず、同期処理（順番に進む処理）とは、**1つの処理が終わるまで、次の処理を待つというルール**のことで、非同期処理（待たずに進む処理）
**処理を待たずに、別の作業を同時に進められる仕組み**のこと。
非同期処理を使えば、データを待っている間に他の部分を表示できたり、ダウンロード中にページの他の部分を表示できる。

## 9. Ajax通信とは？
Ajax（Asynchronous JavaScript and XML）は、**Webページをリロードせずに、非同期でデータを取得・送信する技術**。