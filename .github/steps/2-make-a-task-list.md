## ステップ 2: リストを作成する

Markdown は、よく使われる 3 種類のリストをサポートしています。

- [順序なしリスト](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#lists) - 箇条書きリスト
- [順序付きリスト](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#lists) - 番号付きリスト
- [タスクリスト](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) - チェックボックス付きリスト

### 順序なしリスト

順序なしリストは簡単に表示できます。各項目を別々の行に置き、`-`、`*`、または `+` の文字を使います。

```md
- 項目 1
- 項目 2
- 項目 3
```

- 項目 1
- 項目 2
- 項目 3

### 順序付きリスト

リスト記号の代わりに数字を使うと、順序付きリストになります。Markdown が自動的に番号を処理してくれる点に注目してください。便利ですね。

```md
1. 手順 1
1. 手順 2
1. 手順 3
```

1. 手順 1
1. 手順 2
1. 手順 3

### タスクリスト

タスクリストは、順序なしリストを拡張してチェックボックスを使えるようにしたものです。未完了のタスクには空の角括弧 `[ ]` を、完了したタスクには `[x]` を追加します。メモ: 空の角括弧にはスペースが必要です。

```md
- [x] このタスクは完了済み
- [ ] このタスクは未完了
```

- [x] このタスクは完了済み
- [ ] このタスクは未完了

> [!TIP]
> Issues と pull requests では、[進捗を伝える](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/about-tasklists)ためにタスク構文を使えます。

### :keyboard: アクティビティ: 朝の計画にアイデアと目標を追加する

1. `start-blog` ブランチで、`day-1.md` ファイルを編集用に開きます。

1. **朝の計画** のレベル 2 見出しの下に、達成したい目標を追跡する次のタスクリストを追加します。

   ```md
   - [ ] トピックのアイデアを得るために [GitHub Blog](https://github.blog/) を確認する。
   - [ ] [GitHub Pages](https://github.com/tsato-cnlab/github-pages) について学ぶ。
   - [ ] 最初のブログ記事を実際の Web ページにする。
   ```

1. **Preview** タブを使って Markdown の書式を確認します。

1. 右上の **Commit changes** ボタンをクリックし、`start-blog` ブランチに直接コミットします。

1. タスクリストをコミットできたので、Mona が作業を確認し、次のステップを準備しているはずです。

<details>
<summary>うまくいきませんか？</summary><br/>

- 正しいファイルとブランチを編集していることを確認してください。
- 構文をもう一度確認してください。タスクリストでは `[ ]` の中にスペースが必要です。

</details>
