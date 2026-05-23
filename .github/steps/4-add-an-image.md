## ステップ 4: 画像を追加する

相対 URL、絶対 URL、サイズ指定、基本的な配置を使って、[Markdown に画像を含める方法](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images)を学びましょう。

### 通常の Markdown

画像は、リポジトリ内のファイルへの相対 URL、またはインターネット上の任意の場所への絶対 URL を指定して表示できます。

角括弧の中の説明テキストは、画像を読み込めない場合に表示されます。また、スクリーンリーダーを使う人向けに読み上げられます。

メモ: Markdown 構文には、画像サイズを変更するオプションはありません。

### 例

リポジトリ内の画像への相対 URL:
```md
![Mona the Octocat](myrepo/original.png)

```

インターネット上の画像への絶対 URL:
```md
![Mona the Octocat](https://octodex.github.com/images/original.png)
```

<img alt="Mona the Octocat" src="https://octodex.github.com/images/original.png" width="200">

### シンプルな HTML

画像のサイズを小さくしたり、テキストの横に配置したりしたい場面はよくあります。通常の HTML 構文を使うと、もう少し柔軟に指定できます。

- `alt` フィールドは代替テキストを指定します。
- `src` フィールドは画像のソース URL を指定します。
- `width` や `height` フィールドを使うと、ピクセル単位でサイズを指定できます。
- `align` フィールドでは位置（`left`、`right`）を設定できます。

```md
<img alt="Mona the Octocat" src="https://octodex.github.com/images/original.png"
width="200" align="right">
```

### :keyboard: アクティビティ: 少し装飾を追加する

今のブログ記事はかなりシンプルです。少し装飾を追加しましょう。

1. `start-blog` ブランチで、`day-1.md` ファイルを編集用に開きます。

1. **Morning Planning** のレベル 2 見出しの下に画像を挿入します。

   ```md
   ![Cloudy morning](https://octodex.github.com/images/cloud.jpg)
   ```

1. **Preview** タブを使って Markdown の書式を確認します。

   - この目的には画像が大きすぎることに注目してください。

1. シンプルな Markdown 版を、サイズと位置情報を含む HTML 版に置き換えます。ずっと良くなります。

   ```md
   <img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">
   ```

1. 右上の **Commit changes** ボタンをクリックし、`start-blog` ブランチに直接コミットします。

1. 画像を追加してコミットできたので、Mona が作業を確認し、次のステップを準備しているはずです。

<details>
<summary>うまくいきませんか？</summary><br/>

- 正しいファイルとブランチを編集していることを確認してください。
- 構文をもう一度確認してください。HTML の画像タグは `img` で始まり、`src` プロパティを含める必要があります。

</details>
