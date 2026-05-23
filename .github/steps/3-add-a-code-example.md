## ステップ 3: コードサンプルを追加する

言語に応じた [コードブロック](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-code) と [構文ハイライト](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks) について学びましょう。

> [!TIP]
> 多くのプログラミング言語がサポートされています。他のファイル拡張子も試してみてください。

### 例: ターミナルコマンド

````md
```bash
git clone https://github.com/skills/communicate-using-markdown
```
````

```bash
git clone https://github.com/skills/communicate-using-markdown
```

### 例: JavaScript コード

````md
```js
var myVar = "Hello, world!";
```
````

```js
var myVar = "Hello, world!";
```

### :keyboard: アクティビティ: コード例を追加する

1. `start-blog` ブランチで、`day-1.md` ファイルを編集用に開きます。

1. **Review** のレベル 2 見出しの下に、GitHub Blog で学んだすばらしいコードスニペットとして次の内容を追加します。

   ````md
   Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

   ```bash
   ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
   ```
   ````

1. **Preview** タブを使って Markdown の書式を確認します。

1. 右上の **Commit changes** ボタンをクリックし、`start-blog` ブランチに直接コミットします。

1. コードブロックをコミットできたので、Mona が作業を確認し、次のステップを準備しているはずです。

<details>
<summary>うまくいきませんか？</summary><br/>

- 正しいファイルとブランチを編集していることを確認してください。
- 構文をもう一度確認してください。コードブロックは 3 つのバッククォート ` ``` ` であり、3 つのアポストロフィ `'''` ではありません。

</details>
