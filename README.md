# vscode-theme-color-guide-ja

<details>
<summary><b>Contrast colors(コントラスト色)</b></summary><br>


**Contrast colors** は、VSCode のハイコントラストテーマ専用の設定で、UI 全体の要素に追加のボーダー（枠線）を付けることで、近視やディスプレイの発色が悪い環境での作業をサポートする。
`"type": "hc-black"`の時のみ適用され、通常のテーマでは基本的に使用されない。

<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>contrastBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">UI 全体の要素の周囲に追加ボーダーを表示し、要素同士の境界をはっきりさせる</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウインドウ、ボタン、バッジ</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>contrastActiveBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在フォーカス中・選択中の**アクティブな要素**の周囲に追加のボーダーを表示し、他の要素と区別しやすくする</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テキストボックス、タブやリストの項目のクリックによるフォーカス、エディター上の単語を選択</td>
  </tr>
</tbody>
</table>
</div>
---


</details>
<details>
<summary><b>Base colors(ベースカラー)</b></summary><br>


**Base colors** は、VSCode UI 全体に共通して使われるデフォルトの色設定である。各コンポーネントが独自の色を持たない場合のフォールバックとして機能する。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>focusBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォーカスされた要素の全体的な境界線の色。各コンポーネントで上書きされない場合に使用するフォールバック値</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">クリックによるフォーカス中のテキストボックス、リストの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">UI 全体のデフォルト文字色。各コンポーネントで上書きされない場合に使用するフォールバック値</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのテキスト、メニュー項目</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>disabledForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">無効化された要素の文字色。各コンポーネントで上書きされない場合に使用するフォールバック値</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>widget.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター内ウィジェットの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Find(<code>Ctrl</code>+<code>F</code>)やQuick Pick(<code>Ctrl</code>+<code>Shift</code>+<code>P</code>) ダイアログの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>widget.shadow</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター内ウィジェットの影の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Find(<code>Ctrl</code>+<code>F</code>)やQuick Pick(<code>Ctrl</code>+<code>Shift</code>+<code>P</code>) ダイアログの影</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>selection.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ワークベンチ内のテキスト選択時の背景色。エディターやターミナル内の選択には適用されない</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>descriptionForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">補足情報として表示される説明テキストの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>errorForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラーメッセージ全体の文字色。各コンポーネントで上書きされない場合に使用するフォールバック値</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディタ上のFind(<code>Ctrl</code>+<code>F</code>)でヒットしない文字列を検索したときに表示される"結果はありません。"</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>icon.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ワークベンチ内のアイコンのデフォルトカラー</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーやツールバーのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>sash.hoverBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ドラッグ可能なサッシュ（ペイン間の境界線）のクリック、ドラッグ時の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーとエディター間の境界線をクリックまたはドラッグしたとき(参考: [VS Code tips — The sash hover border](https://www.youtube.com/watch?v=eU0zxM5kpoc))</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Window border(ウィンドウボーダー)</b></summary><br>


**Window border** は、VSCode ウィンドウ自体の境界線の色設定である。アクティブ（フォーカス中）と非アクティブ（フォーカスなし）で色を切り替えられる。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>window.activeBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブ（フォーカス中）ウィンドウの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在操作中の VSCode ウィンドウの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>window.inactiveBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非アクティブ（フォーカスなし）ウィンドウの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">背面にある VSCode ウィンドウの枠線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Text colors(テキストカラー)</b></summary><br>


**Text colors** は、ウェルカムページなどのテキストドキュメント内で使われる色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>textBlockQuote.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ブロック引用の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウェルカムページの引用ブロック背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>textBlockQuote.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ブロック引用の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウェルカムページの引用ブロック左の縦線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>textCodeBlock.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コードブロックの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウェルカムページのインラインコード背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>textLink.activeForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">クリック時・ホバー時のリンクの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウェルカムページのリンクをクリック・ホバーしたとき</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>textLink.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通常状態のリンクの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウェルカムページのリンクテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>textPreformat.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">整形済みテキスト（pre）の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウェルカムページのキーボードショートカット表記</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>textPreformat.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">整形済みテキスト（pre）の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウェルカムページのキーボードショートカット表記の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>textPreformat.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">整形済みテキスト（pre）の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウェルカムページのキーボードショートカット表記の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>textSeparator.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テキスト区切り線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウェルカムページのセクション間の区切り線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Action colors(アクションカラー)</b></summary><br>


**Action colors** は、ワークベンチ全体のアクション操作に関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>toolbar.hoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ツールバーのアイコンをホバーしたときの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">タブの欄の一番右にある"エディターを右に分割"や"その他の操作..."のアイコンにホバーしたとき</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>toolbar.hoverOutline</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ツールバーのアイコンをホバーしたときのアウトライン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">タブの欄の一番右にある"エディターを右に分割"や"その他の操作..."のアイコンにホバーしたときの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>toolbar.activeBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ツールバーのアイコンをクリック押下中の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">タブの欄の一番右にある"エディターを右に分割"や"その他の操作..."のアイコンをクリックして押し込んでいるとき</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorActionList.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクションリストの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">間違ったコードを書いたときに出てくるダイアログ("式が必要です。ts(1109)"などが表示されるダイアログ)</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorActionList.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクションリストの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">間違ったコードを書いたときに出てくるダイアログ("式が必要です。ts(1109)"などが表示されるダイアログ)</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorActionList.focusForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクションリストのフォーカス中の項目の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">間違ったコードを書いたときに出てくるダイアログ("式が必要です。ts(1109)"などが表示されるダイアログ)</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorActionList.focusBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクションリストのフォーカス中の項目の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">間違ったコードを書いたときに出てくるダイアログ("式が必要です。ts(1109)"などが表示されるダイアログ)</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Button control(ボタンコントロール)</b></summary><br>


**Button control** は、エクスプローラーの「フォルダーを開く」、ソース管理の「リポジトリを初期化する」ボタンなど、ボタンウィジェットに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>button.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ボタンの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「フォルダーを開く」や「リポジトリを初期化する」ボタンの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>button.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ボタンの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「フォルダーを開く」や「リポジトリを初期化する」ボタンのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>button.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ボタンの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「フォルダーを開く」や「リポジトリを初期化する」ボタンの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>button.separator</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ドロップダウン付きボタンの区切り線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能の詳細画面の「アンインストール」ボタンの区切り線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>button.hoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時のボタンの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「フォルダーを開く」や「リポジトリを初期化する」ボタンにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>button.secondaryForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">セカンダリボタンの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">キャンセルなどの補助的なボタンのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>button.secondaryBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">セカンダリボタンの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">キャンセルなどの補助的なボタンの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>button.secondaryHoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時のセカンダリボタンの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">セカンダリボタンにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>button.secondaryBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">セカンダリボタンの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">セカンダリボタンの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>checkbox.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チェックボックスの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能の詳細画面の「自動更新」のチェックボックスの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>checkbox.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チェックボックスのマーク</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能の詳細画面の「自動更新」のチェックボックスのチェックマーク</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>checkbox.disabled.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">無効化されたチェックボックスの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">グレーアウトされたチェックボックスの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>checkbox.disabled.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">無効化されたチェックボックスのマーク</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">グレーアウトされたチェックボックスのチェックマーク</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>checkbox.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チェックボックスの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能の詳細画面の「自動更新」のチェックボックスの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>checkbox.selectBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中の要素内にあるチェックボックスの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面(<code>Ctrl</code>+<code>,</code>)でリスト項目が選択されているときのチェックボックス背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>checkbox.selectBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中の要素内にあるチェックボックスの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面(<code>Ctrl</code>+<code>,</code>)でリスト項目が選択されているときのチェックボックス枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>radio.activeForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブなラジオボタンの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>radio.activeBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブなラジオボタンの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>radio.activeBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブなラジオボタンの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>radio.inactiveForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非アクティブなラジオボタンの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>radio.inactiveBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非アクティブなラジオボタンの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>radio.inactiveBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非アクティブなラジオボタンの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>radio.inactiveHoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非アクティブなラジオボタンのホバー時の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Dropdown control(ドロップダウンコントロール)</b></summary><br>


**Dropdown control** は、統合ターミナルや出力パネルなどのドロップダウンウィジェットに関する色設定である。なお、macOS では現在ドロップダウンコントロールは使用されていない。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>dropdown.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ドロップダウンの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面(<code>Ctrl</code>+<code>,</code>)の<code>window.titleBarStyle</code>や出力(<code>Ctrl</code>+<code>Shift</code>+<code>U</code>)のドロップダウンの選択欄の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>dropdown.listBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ドロップダウンリストの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面(<code>Ctrl</code>+<code>,</code>)の<code>window.titleBarStyle</code>や出力(<code>Ctrl</code>+<code>Shift</code>+<code>U</code>)のドロップダウンを開いたときの選択肢リストの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>dropdown.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ドロップダウンの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面(<code>Ctrl</code>+<code>,</code>)の<code>window.titleBarStyle</code>や出力(<code>Ctrl</code>+<code>Shift</code>+<code>U</code>)のドロップダウンの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>dropdown.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ドロップダウンの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面(<code>Ctrl</code>+<code>,</code>)の<code>window.titleBarStyle</code>や出力(<code>Ctrl</code>+<code>Shift</code>+<code>U</code>)のドロップダウンの選択中の項目のテキスト</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Input control(インプットコントロール)</b></summary><br>


**Input control** は、検索ビューや Find/Replace ダイアログなどの入力フィールドに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>input.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">入力ボックスの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">検索ビューの入力フィールド背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>input.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">入力ボックスの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">検索ビューの入力フィールドの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>input.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">入力ボックスの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">検索ビューの入力テキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>input.placeholderForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">入力ボックスのプレースホルダーの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">検索ビューの「検索(Find)」などのヒントテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inputOption.activeBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">入力フィールドのアクティブなオプションの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">検索ビューの「大文字と小文字を区別」ボタンのオン時の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inputOption.activeBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">入力フィールドのアクティブなオプションの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">検索ビューの「大文字と小文字を区別」ボタンのオン時の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inputOption.activeForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">入力フィールドのアクティブなオプションの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">検索ビューの「大文字と小文字を区別」ボタンのオン時のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inputOption.hoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">入力フィールドのオプションのホバー時の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">検索ビューの「大文字と小文字を区別」ボタンにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inputValidation.errorBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラー時のバリデーションメッセージの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">正規表現を使用して<code>sdd\</code>を検索したときのエラーメッセージの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inputValidation.errorForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラー時のバリデーションメッセージの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">正規表現を使用して<code>sdd\</code>を検索したときのエラーメッセージのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inputValidation.errorBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラー時のバリデーションメッセージの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">正規表現を使用して<code>sdd\</code>を検索したときのエラーメッセージの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inputValidation.infoBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">情報レベルのバリデーションメッセージの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inputValidation.infoForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">情報レベルのバリデーションメッセージの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inputValidation.infoBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">情報レベルのバリデーションメッセージの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inputValidation.warningBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告レベルのバリデーションメッセージの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inputValidation.warningForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告レベルのバリデーションメッセージの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inputValidation.warningBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告レベルのバリデーションメッセージの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Scrollbar control(スクロールバーコントロール)</b></summary><br>


**Scrollbar control** は、エディターの一番右にあるスクロールバーに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>scrollbar.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スクロールバーの可動領域のトラック（レール部分）の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターのスクロールバー背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>scrollbar.shadow</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スクロール中であることを示すスライダーの影の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スクロール位置がトップ以外のときのエディター上部の影</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>scrollbarSlider.activeBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">クリック押下中のスクロールバースライダーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スクロールバーにあるスライダーをクリックして押し込んでいるときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>scrollbarSlider.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スクロールバースライダーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スクロールバーにあるスライダーの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>scrollbarSlider.hoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時のスクロールバースライダーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スクロールバーにあるスライダーにホバーしたときの背景</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Badge(バッジ)</b></summary><br>


**Badge** は、拡張機能の発行元(例: `ms-vscode`)などを表示する小さなアイコンに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>badge.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">バッジの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能の発行元(例: <code>ms-vscode</code>)のバッジのチェックマーク</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>badge.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">バッジの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能の発行元(例: <code>ms-vscode</code>)のバッジの背景</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Progress bar(プログレスバー)</b></summary><br>


**Progress bar** は、長時間かかる処理中に表示されるプログレスバーに関する色設定である。

<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>progressBar.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">プログレスバーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能インストール中やファイル読み込み中のプログレスバー</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Lists and trees(リストとツリー)</b></summary><br>


**Lists and trees** は、ファイルエクスプローラーなどのリスト・ツリーUIに関する色設定である。アクティブなリスト/ツリーはキーボードフォーカスを持ち、非アクティブなものは持たない。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.activeSelectionBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブ時の選択中の項目の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーでフォーカスされた選択中のファイルの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.activeSelectionForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブ時の選択中の項目の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーでフォーカスされた選択中のファイル名のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.activeSelectionIconForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブ時の選択中の項目のアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーでフォーカスされた選択中のファイルアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.dropBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ドラッグ&ドロップ中の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーでファイルをドラッグして移動中の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.focusBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブ時のフォーカス中の項目の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーでキーボード操作によりフォーカスされたファイルの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.focusForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブ時のフォーカス中の項目の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーでキーボード操作によりフォーカスされたファイルのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.focusHighlightForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブ時のフォーカス中の項目の検索マッチハイライトの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">リスト内検索でフォーカス中の項目のマッチ部分のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.focusOutline</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブ時のフォーカス中の項目のアウトライン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーでキーボード操作によりフォーカスされたファイルの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.focusAndSelectionOutline</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブ時のフォーカスかつ選択中の項目のアウトライン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーでキーボード操作によるフォーカスと選択が重なった項目の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.highlightForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">リスト内検索のマッチハイライトの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーの検索でマッチした文字のテキスト色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.hoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時の項目の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーのファイルにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.hoverForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時の項目の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーのファイルにホバーしたときのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.inactiveSelectionBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非アクティブ時の選択中の項目の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーで非アクティブ(別ウィンドウ操作中)かつ選択中のファイルの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.inactiveSelectionForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非アクティブ時の選択中の項目の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーで非アクティブ(別ウィンドウ操作中)かつ選択中のファイル名のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.inactiveSelectionIconForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非アクティブ時の選択中の項目のアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーで非アクティブ(別ウィンドウ操作中)かつ選択中のファイルアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.inactiveFocusBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非アクティブ時のフォーカス中の項目の背景色（リストのみ対応）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーで非アクティブ(別ウィンドウ操作中)かつフォーカスされた項目の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.inactiveFocusOutline</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーで非アクティブ時のフォーカス中の項目のアウトライン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">リスト/ツリーで非アクティブ(別ウィンドウ操作中)かつフォーカスされた項目の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.invalidItemForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">無効な項目の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エクスプローラーで未解決のルートフォルダーのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.errorForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラーを含む項目の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラーのあるファイル・フォルダー名のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.warningForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告を含む項目の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告のあるファイル・フォルダー名のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>listFilterWidget.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">リスト内検索ウィジェットの入力テキストの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>listFilterWidget.outline</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">リスト内検索ウィジェットの入力テキストのアウトライン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>listFilterWidget.noMatchesOutline</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">リスト内検索ウィジェットでマッチなし時のアウトライン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>listFilterWidget.shadow</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">リスト内検索ウィジェットの影の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.filterMatchBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フィルタリングされたマッチ項目の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.filterMatchBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フィルタリングされたマッチ項目の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.deemphasizedForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非強調項目の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>list.dropBetweenBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">項目間へのドラッグ&ドロップ時の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ファイルを項目と項目の間にドロップするときの境界線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tree.indentGuidesStroke</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ツリーのアクティブなインデントガイドの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エクスプローラーのフォルダー階層を示すアクティブな縦線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tree.inactiveIndentGuidesStroke</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ツリーの非アクティブなインデントガイドの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エクスプローラーのフォルダー階層を示す非アクティブな縦線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tree.tableColumnsBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ツリーのテーブルカラムの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tree.tableOddRowsBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テーブルの奇数行の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Activity Bar(アクティビティバー)</b></summary><br>


**Activity Bar** は、VSCodeの左端（または右端）に縦に並んでいるアイコン群の列であり、サイドバーのビューを素早く切り替えるためのバーに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>activityBar.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティビティバー全体の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>activityBar.dropBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティビティバーへのドラッグ&ドロップ時の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>activityBar.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティビティバーのアイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>activityBar.inactiveForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティビティバーの非アクティブなアイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">未選択のビューアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>activityBar.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティビティバーとサイドバーの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">左端のアクティビティバーとサイドバーの間の縦線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>activityBarBadge.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティビティバーの通知バッジの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティビティバーのアイコン右下にある通知数を示す丸いバッジの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>activityBarBadge.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティビティバーの通知バッジの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティビティバーのアイコン右下にある通知数を示す丸いバッジのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>activityBar.activeBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブなアイテムのインジケーターの縦線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中のビューアイコンの横のアクティブな縦線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>activityBar.activeBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブなアイテムのオプション背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中のビューアイコンの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>activityBar.activeFocusBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブなアイテムのフォーカス時の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>activityBarTop.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">上部配置時のアクティブなアイテムの文字・アイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティビティバーを上部に配置したときの選択中のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>activityBarTop.activeBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">上部配置時のアクティブなアイテムのフォーカス境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティビティバーを上部に配置したときの選択中アイコンの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>activityBarTop.inactiveForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">上部配置時の非アクティブなアイテムの文字・アイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティビティバーを上部に配置したときの未選択のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>activityBarTop.dropBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">上部配置時のドラッグ&ドロップ時の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティビティバーを上部に配置してアイコンをドラッグするときの境界線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>activityBarTop.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">上部・下部配置時のアクティビティバーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティビティバーを上部または下部に配置したときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>activityBarTop.activeBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">上部・下部配置時のアクティブなアイテムの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティビティバーを上部または下部に配置したときの選択中アイコンの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>activityWarningBadge.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告アクティビティバッジの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>activityWarningBadge.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告アクティビティバッジの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>activityErrorBadge.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラーアクティビティバッジの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>activityErrorBadge.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラーアクティビティバッジの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Profiles(プロファイル)</b></summary><br>


**Profiles** は、アクティビティバーの設定（歯車）アイコンの上に表示されるプロファイルバッジに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>profileBadge.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">プロファイルバッジの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定アイコン上に表示されるプロファイルバッジの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>profileBadge.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">プロファイルバッジの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定アイコン上に表示されるプロファイルバッジのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>profiles.sashBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">プロファイルエディターの分割ビューのサッシュ（境界線）の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">プロファイルエディターの2分割表示の間の境界線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Side Bar(サイドバー)</b></summary><br>


**Side Bar** は、ウィンドウ左側に位置するエクスプローラーや検索などのビューを格納するコンテナに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>sideBar.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバー全体の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>sideBar.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバー内のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>sideBar.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーとエディターを区切る境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーとエディターの間の縦線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>sideBar.dropBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーセクションへのドラッグ&ドロップ時の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーにファイルをドラッグしているときの背景（透過色）</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>sideBarTitle.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのタイトルの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーの上部にある「エクスプローラー」などのタイトルテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>sideBarSectionHeader.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのセクションヘッダーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エクスプローラー内の「アウトライン」や「タイムライン」などのセクション見出しの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>sideBarSectionHeader.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのセクションヘッダーの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エクスプローラー内の「アウトライン」や「タイムライン」などのセクション見出しのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>sideBarSectionHeader.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのセクションヘッダーの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エクスプローラー内の「アウトライン」や「タイムライン」などのセクション見出しの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>sideBarActivityBarTop.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">上部配置したアクティビティバーとビューの間の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティビティバーを上部に配置したときのビューとの境界線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>sideBarTitle.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのタイトルの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーの上部にある「エクスプローラー」などのタイトル部分の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>sideBarTitle.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのタイトル下部の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーの上部にある「エクスプローラー」などのタイトルとビューを区切る下部の線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>sideBarStickyScroll.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのスティッキースクロールの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エクスプローラーでフォルダーをスクロールしたときに上部に固定される現在見ている場所の親フォルダーの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>sideBarStickyScroll.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのスティッキースクロールの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エクスプローラーでフォルダーをスクロールしたときに上部に固定される現在見ている場所の親フォルダー部分の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>sideBarStickyScroll.shadow</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのスティッキースクロールの影の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エクスプローラーでフォルダーをスクロールしたときに上部に固定される現在見ている場所の親フォルダー部分の影</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Minimap(ミニマップ)</b></summary><br>


**Minimap** は、エディタの右側に位置する現在のファイルのズームアウトしたものを表示する機能に関する色設定である。コマンドパレット（`Ctrl`+`Shift`+`P`）を開いて、「Toggle Minimap」と入力して実行することで表示される。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>minimap.findMatchHighlight</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ファイル内検索のマッチ箇所のハイライト色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ミニマップ上で検索ワードと一致した箇所のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>minimap.selectionHighlight</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター上の選択範囲のハイライト色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ミニマップ上の現在選択中のテキスト範囲のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>minimap.errorHighlight</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター上のエラー箇所のハイライト色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラーがある行のミニマップ上のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>minimap.warningHighlight</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター上の警告箇所のハイライト色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告がある行のミニマップ上のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>minimap.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ミニマップの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ミニマップ全体の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>minimap.selectionOccurrenceHighlight</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中の文字列と同じ語が繰り返し出現する箇所のマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ミニマップ上の選択中の単語と一致する箇所のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>minimap.foregroundOpacity</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ミニマップ内に描画される前景要素の不透明度</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ミニマップに表示されるコードの縮小テキストの濃さ</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>minimap.infoHighlight</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">情報レベルのマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ミニマップ上の情報通知がある行のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>minimap.chatEditHighlight</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">保留中の編集領域の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">AI等のインライン編集で未確定の変更箇所のハイライト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>minimapSlider.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ミニマップスライダーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ミニマップ上の現在の表示範囲を示すものの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>minimapSlider.hoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時のミニマップスライダーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ミニマップの表示範囲枠にホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>minimapSlider.activeBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">クリック押下時のミニマップスライダーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ミニマップの表示範囲枠をクリックして押し込んでいるときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>minimapGutter.addedBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">追加された内容を示すミニマップガターの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Git差分で追加された行のミニマップ左端のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>minimapGutter.modifiedBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更された内容を示すミニマップガターの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Git差分で変更された行のミニマップ左端のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>minimapGutter.deletedBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">削除された内容を示すミニマップガターの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Git差分で削除された行のミニマップ左端のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorMinimap.inlineChatInserted</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インラインチャットで挿入されたコンテンツのマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">AIによって挿入されたコードのミニマップ上のマーカー</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Editor Groups & Tabs(エディターグループとタブ)</b></summary><br>


**Editor Group** はタブ群とエディタを格納する領域で、通常は1つだが画面分割により複数存在できる。
**Tab** はエディタ上に開かれたファイルを表す横並びの見出しで、エディタの上部に位置している。1つの Editor Group 内に複数の Tab を開いて切り替えることができる。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGroup.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">複数のエディターグループを区切る境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">画面分割した場合の複数のエディター間の境界線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGroup.dropBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターをドラッグ中の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">画面分割した場合のタブをドラッグしてエディタへ移動しているときのエディタの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGroupHeader.noTabsBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">シングルタブ表示時のエディターグループタイトルヘッダーの背景色（<code>"workbench.editor.showTabs": "single"</code> 設定時）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGroupHeader.tabsBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">タブコンテナの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGroupHeader.tabsBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">タブ有効時のタブコントロール下の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGroupHeader.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターグループヘッダーとエディターの間の境界線の色（ブレッドクラム有効時はその下）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGroup.emptyBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">空のエディターグループの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ファイルを開いていない空のエディターグループの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGroup.focusedEmptyBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォーカス中の空のエディターグループの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォーカスされている空のエディターグループの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGroup.dropIntoPromptForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ファイルドラッグ中に表示される案内テキストの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ファイルをエディター上にドラッグ・ドロップしようとするときに表示される「Shiftをホールドしてエディターにドロップする」という案内文のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGroup.dropIntoPromptBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ファイルドラッグ中に表示される案内テキストの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ファイルをエディター上にドラッグ・ドロップしようとするときに表示される「Shiftをホールドしてエディターにドロップする」という案内文の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGroup.dropIntoPromptBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ファイルドラッグ中に表示される案内テキストの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ファイルをエディター上にドラッグ・ドロップしようとするときに表示される「Shiftをホールドしてエディターにドロップする」という案内文の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.activeBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブなグループ内のアクティブタブの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在操作しているエディターグループで開いているタブの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.unfocusedActiveBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非アクティブなグループ内のアクティブタブの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在操作していないエディターグループで開いているタブの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.activeForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブなグループ内のアクティブタブの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在操作しているエディターグループで開いているタブのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">タブ同士を区切る境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">隣り合うタブの間の縦線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.activeBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブタブの下部境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在操作しているエディターグループで開いているタブの下線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.selectedBorderTop</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中タブの上部境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中のタブの上側に表示される線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.selectedBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中のタブの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>Shift</code>や<code>Ctrl</code>で複数選択したタブの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.selectedForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中のタブの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>Shift</code>や<code>Ctrl</code>で複数選択したタブののテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.dragAndDropBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">タブ間に挿入可能であることを示す境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">タブをドラッグして別タブの間に挿入できることを示す横線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.unfocusedActiveBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非アクティブなグループ内のアクティブタブの下部境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在操作していないエディターグループで開いているタブの下線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.activeBorderTop</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブタブの上部境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在操作しているエディターグループで開いているタブの上に表示される線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.unfocusedActiveBorderTop</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非アクティブなグループ内のアクティブタブの上部境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在操作していないエディターグループで開いているタブの上線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.lastPinnedBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">最後にピン留めされたタブの右側の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピン留めタブと未ピン留めタブを区切る縦線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.inactiveBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非アクティブタブの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在操作しているエディターグループで開いていないタブの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.unfocusedInactiveBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非フォーカスグループ内の非アクティブタブの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在操作していないエディターグループで開いていないタブの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.inactiveForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブなグループ内の非アクティブタブの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在操作しているエディターグループで開いていないタブのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.unfocusedActiveForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非アクティブなグループ内のアクティブタブの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在操作していないエディターグループで開いているタブのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.unfocusedInactiveForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非アクティブなグループ内の非アクティブタブの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在操作していないエディターグループで開いていないタブのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.hoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時のタブの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">タブにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.unfocusedHoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非フォーカスグループでホバー時のタブの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在操作していないエディターグループのタブにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.hoverForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時のタブの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">タブにホバーしたときのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.unfocusedHoverForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非フォーカスグループでホバー時のタブの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在操作していないエディターグループのタブにホバーしたときのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.hoverBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時のタブを強調する境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">タブにホバーしたときに表示される枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.unfocusedHoverBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非フォーカスグループでホバー時のタブを強調する境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在操作していないエディターグループのタブにホバーしたときの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.activeModifiedBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブグループ内の変更済み（未保存）アクティブタブの上部境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">未保存の変更があり、現在操作しているタブの上部に表示される線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.inactiveModifiedBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブグループ内の変更済み（未保存）非アクティブタブの上部境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">未保存の変更があり、現在操作していないタブの上部に表示される線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.unfocusedActiveModifiedBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非フォーカスグループ内の変更済み（未保存）アクティブタブの上部境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">未保存の変更があり、現在操作していないエディターグループの開いているタブの上部に表示される線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>tab.unfocusedInactiveModifiedBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非フォーカスグループ内の変更済み（未保存）非アクティブタブの上部境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">未保存の変更があり、現在操作していないエディターグループの開いていないタブの上部に表示される線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorPane.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">中央レイアウト時、エディターの左右に見えるエディターペインの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターを中央寄せ表示にしたときの左右の余白部分の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>sideBySideEditor.horizontalBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターグループ内で上下に並べて表示する2つのエディターを区切る色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">縦に分割した2つのエディター間の境界線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>sideBySideEditor.verticalBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターグループ内で左右に並べて表示する2つのエディターを区切る色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">横に分割した2つのエディター間の境界線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Editor colors(エディターカラー)</b></summary><br>


**Editor colors** は、エディター本体に関する色設定である。ここでは、シンタックスハイライト(言語文法に基づいたエディター内のテキストの色設定)以外のエディター関連の色設定の項目を以下にまとめる。

### 基本


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター全体の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターのデフォルト文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターのデフォルトテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorLineNumber.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">行番号の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター左端の行番号</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorLineNumber.activeForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カーソルがある行の行番号の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター左端の選択中の行番号</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorLineNumber.dimmedForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.renderFinalNewline</code> が <code>dimmed</code> のときの最終行の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ファイル末尾の空行の行番号</td>
  </tr>
</tbody>
</table>
</div>

### カーソル


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorCursor.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カーソルに重なった文字の背景色（ブロックカーソル時）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ブロックカーソルが文字に重なったときの文字色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorCursor.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カーソルの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター上の点滅するカーソル</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorMultiCursor.primary.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">複数カーソル使用時のメインカーソルの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マルチカーソル編集時の元から置いていたカーソル</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorMultiCursor.primary.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">複数カーソル使用時のメインカーソルに重なる文字の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">文字に重なったときの元から置いていたマルチカーソル(ブロックカーソル時)の文字色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorMultiCursor.secondary.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">複数カーソル使用時のサブカーソルの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マルチカーソル編集時の後から追加されたカーソル</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorMultiCursor.secondary.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">複数カーソル使用時のサブカーソルに重なる文字の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マルチカーソル編集時の後から追加されたカーソル(ブロックカーソル時)の文字色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.placeholder.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">プレースホルダーテキストの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">空のエディターに表示される案内のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.compositionBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">IME入力中の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">日本語入力中の変換候補のアンダーライン</td>
  </tr>
</tbody>
</table>
</div>

### 選択範囲

選択範囲の色は、1文字以上を選択したときに表示される。選択箇所に加え、同じ内容を持つ範囲もハイライトされる。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.selectionBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択範囲の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テキストをドラッグして選択したときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.selectionForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ハイコントラスト時の選択テキストの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">キストをドラッグして選択したときの文字色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.inactiveSelectionBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非アクティブなエディターでの選択範囲の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在操作していないエディターグループで選択中のテキストの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.selectionHighlightBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中と同じ内容を持つ範囲の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択した単語と同じ文字列がある箇所の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.selectionHighlightBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中と同じ内容を持つ範囲の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択した単語と同じ文字列がある箇所の枠線</td>
  </tr>
</tbody>
</table>
</div>

### ワードハイライト

カーソルがシンボルや単語の上にあるとき表示される。言語サポートがあれば参照・宣言箇所がハイライトされ、読み取り/書き込みアクセスで異なる色になる。言語サポートがない場合は単語単位のハイライトにフォールバックする。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.wordHighlightBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">シンボルの読み取りアクセス時の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">その変数を使用している箇所の背景（半透明）</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.wordHighlightBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">シンボルの読み取りアクセス時の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">その変数を使用している箇所の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.wordHighlightStrongBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">シンボルの書き込みアクセス時の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">その変数に値を代入している箇所の背景（半透明）</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.wordHighlightStrongBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">シンボルの書き込みアクセス時の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">その変数に値を代入している箇所の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.wordHighlightTextBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">シンボルのテキスト一致箇所の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">言語サポートがない場合の同一単語の背景（半透明）</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.wordHighlightTextBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">シンボルのテキスト一致箇所の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">言語サポートがない場合の同一単語の枠線</td>
  </tr>
</tbody>
</table>
</div>

### 検索（Find）

Find/Replace ダイアログの検索文字列に応じて表示される色。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.findMatchBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在の検索マッチの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">検索語句にマッチし、現在選択している箇所の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.findMatchForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在の検索マッチの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">検索語句にマッチし、現在選択している箇所のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.findMatchHighlightForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">その他の検索マッチの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">検索語句にマッチしているが、現在選択していない箇所のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.findMatchHighlightBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">その他の検索マッチの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">検索語句にマッチしているが、現在選択していない箇所の背景（半透明）</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.findRangeHighlightBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">検索範囲を限定するハイライトの背景色（Find widgetの「選択範囲内で検索」有効時）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「選択範囲内で検索」を有効化したときの対象範囲の背景（半透明）</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.findMatchBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在の検索マッチの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">検索語句にマッチし、現在選択している箇所の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.findMatchHighlightBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">検索語句にマッチしているが、現在選択していない箇所の枠線</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.findRangeHighlightBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">検索範囲を限定するハイライトの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「選択範囲内で検索」を有効化したときの対象範囲の枠線</td>
  </tr>
</tbody>
</table>
</div>

### 検索ビューレット / Search Editor


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>search.resultsInfoForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">検索ビューレットの完了メッセージの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーで検索したときに表示される<code>y 個のファイルに x 件の結果(x results in y files)</code>というテキストの文字色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>searchEditor.findMatchBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Search Editor の検索結果の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーで検索したときのマッチした箇所の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>searchEditor.findMatchBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Search Editor の検索結果の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーで検索したときのマッチした箇所の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>searchEditor.textInputBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Search Editor のテキスト入力欄の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーの検索ボックスの枠線</td>
  </tr>
</tbody>
</table>
</div>

### ホバーハイライト


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.hoverHighlightBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー表示中の単語の下に表示されるハイライト色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバーしたときの型情報の小さいポップアップの背景（半透明）</td>
  </tr>
</tbody>
</table>
</div>

### 現在行のハイライト

現在行は背景ハイライトまたはボーダーのどちらかで表示されるのが一般的（両方同時には使われない）。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.lineHighlightBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カーソル位置の行のハイライト背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カーソルが位置している(=選択している)行全体の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.inactiveLineHighlightBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターが非フォーカス時のカーソル位置行のハイライト背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在操作していないエディターグループでのカーソルが位置している(=選択している)行全体の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.lineHighlightBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カーソル位置の行の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カーソルが位置している(=選択している)行全体を囲む枠線</td>
  </tr>
</tbody>
</table>
</div>

### Unicodeハイライト


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorUnicodeHighlight.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Unicode文字をハイライトする境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">全角スペースなど特殊なUnicode文字を囲む枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorUnicodeHighlight.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Unicode文字をハイライトする背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">全角スペースなど特殊なUnicode文字の背景</td>
  </tr>
</tbody>
</table>
</div>

### リンク


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorLink.activeForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブなリンクの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Ctrlキーを押しながらホバーしたリンクの文字色</td>
  </tr>
</tbody>
</table>
</div>

### 範囲ハイライト（Range Highlight）

検索結果を選択したときに表示される。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.rangeHighlightBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ハイライトされた範囲の背景色（Quick Open、Symbol in File、Find機能で使用）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">検索語句にマッチし、現在選択している箇所の行全体の背景（半透明）</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.rangeHighlightBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ハイライトされた範囲の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">索語句にマッチし、現在選択している箇所の行全体の枠線</td>
  </tr>
</tbody>
</table>
</div>

### シンボルハイライト

「定義へ移動」などのコマンドでシンボルへ移動したときに表示される。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.symbolHighlightBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ハイライトされたシンボルの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">関数、クラス、変数の定義元へ移動した直後に対象シンボルにつく背景（半透明）</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.symbolHighlightBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ハイライトされたシンボルの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">関数、クラス、変数の定義元へ移動した直後に対象シンボルにつく枠線</td>
  </tr>
</tbody>
</table>
</div>

### 空白文字

`Toggle Render Whitespace` を有効にすると表示される。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorWhitespace.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">空白文字の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択したテキストに含まれるスペースやタブを示す点の色</td>
  </tr>
</tbody>
</table>
</div>

### インデントガイド

`"editor.guides.indentation": true` と `"editor.guides.highlightActiveIndentation": true` を設定すると表示される。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorIndentGuide.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インデントガイドの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コードのインデントを示す縦線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorIndentGuide.background1</code>〜<code>background6</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インデントガイドの色（深さ1〜6段階）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ネストの深さごとに色分けされた縦線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorIndentGuide.activeBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブなインデントガイドの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カーソルがある階層のインデント縦線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorIndentGuide.activeBackground1</code>〜<code>activeBackground6</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブなインデントガイドの色（深さ1〜6段階）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カーソルがある階層の縦線（深さごとに色分け）</td>
  </tr>
</tbody>
</table>
</div>

### インレイヒント

`"editor.inlineSuggest.enabled": true` を設定すると表示される。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorInlayHint.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インラインヒントの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">関数の戻り値や変数の型などのインラインヒントの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorInlayHint.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インラインヒントの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">関数の戻り値や変数の型などのインラインヒントのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorInlayHint.typeForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">型ヒントの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変数の推論された型を示すヒントのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorInlayHint.typeBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">型ヒントの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変数の推論された型を示すヒントの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorInlayHint.parameterForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パラメータヒントの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">関数呼び出し時の引数名ヒントのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorInlayHint.parameterBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パラメータヒントの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">関数呼び出し時の引数名ヒントの背景</td>
  </tr>
</tbody>
</table>
</div>

### ルーラー・リンク付き編集

settings.jsonにて例えば`"editor.rulers": [80, 120],`と入力することでルーラー（縦線）を80文字目と120文字目に表示される。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorRuler.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディタールーラーの色（<code>"editor.rulers"</code> で位置指定）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">一定文字数の位置に表示される縦線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.linkedEditingBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">リンク付き編集モード時の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
</tbody>
</table>
</div>

### CodeLens / Lightbulb


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorCodeLens.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">CodeLensの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">関数の上に表示される「1 reference」などのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorLightBulb.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通常のクイックフィックスのアイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コードアクションを示す電球アイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorLightBulbAutoFix.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">自動修正のクイックフィックスのアイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">自動修正可能なときの電球アイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorLightBulbAi.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">AI機能のクイックフィックスのアイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">AI提案を示す電球アイコン</td>
  </tr>
</tbody>
</table>
</div>

### 括弧（Bracket）


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorBracketMatch.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マッチする括弧の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カーソルに位置している括弧とそれに対応する括弧同士の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorBracketMatch.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マッチする括弧のボックスの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カーソルに位置している括弧とそれに対応する括弧同士を囲む枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorBracketMatch.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マッチする括弧の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カーソルに位置している括弧とそれに対応する括弧同士のテキスト色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorBracketHighlight.foreground1</code>〜<code>foreground6</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">括弧ペアの色分け（深さ1〜6段階、Bracket Pair Colorization有効時）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ネストした括弧をネストの深さごとに色分け表示</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorBracketHighlight.unexpectedBracket.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">想定外（不一致）の括弧の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">閉じ括弧が足りない・余分なときの色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorBracketPairGuide.activeBackground1</code>〜<code>activeBackground6</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブな括弧ペアガイドの背景色（深さ1〜6段階、Bracket Pair Guide有効時）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カーソルが位置している場所の括弧ペアを結ぶ下線のガイドの色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorBracketPairGuide.background1</code>〜<code>background6</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非アクティブな括弧ペアガイドの背景色（深さ1〜6段階）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カーソルが位置している場所以外の括弧ペアを結ぶ下線のガイドの色</td>
  </tr>
</tbody>
</table>
</div>

### 折り畳み（Folding）


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.foldBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">折り畳まれた範囲の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コードの行の左にあるアイコンをクリックしてコードを折り畳んだ行の背景（半透明）</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.foldPlaceholderForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">折り畳み範囲の最初の行以降に表示される省略テキストの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">折り畳まれたコードを示す「...」の文字色</td>
  </tr>
</tbody>
</table>
</div>

### Overview ruler（概要ルーラー）

エディター右端のスクロールバーの下に重なっている、エディター内の装飾の概要を示す。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">概要ルーラーの背景色（ミニマップ有効かつ右側配置時のみ使用）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">概要ルーラー部分の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">概要ルーラーの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">概要ルーラーの左端の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.findMatchForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">検索マッチのマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">検索ワードと一致した箇所を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.rangeHighlightForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ハイライト範囲（Quick Open等）のマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.selectionHighlightForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択ハイライトのマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択した単語と同じ文字列がある箇所を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.wordHighlightForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">シンボルハイライトのマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">その変数を使用している箇所を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.wordHighlightStrongForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">書き込みアクセスのシンボルハイライトのマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">その変数へ代入している箇所を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.wordHighlightTextForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テキスト一致のマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">言語サポートがない場合の同一単語箇所を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.modifiedForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更された内容のマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Git差分で変更された行を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.addedForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">追加された内容のマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Git差分で追加された行を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.deletedForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">削除された内容のマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Git差分で削除された行を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.errorForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラーのマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラーがある行を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.warningForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告のマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告がある行を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.infoForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">情報のマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">情報通知がある行を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.bracketMatchForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マッチする括弧のマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カーソルに位置している括弧とそれに対応する括弧同士を示すマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.inlineChatInserted</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インラインチャットで挿入されたコンテンツのマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">AIによって挿入されたコードがある行を示すマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.inlineChatRemoved</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インラインチャットで削除されたコンテンツのマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">AIによって削除されたコードがある行を示すマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.commentDraftForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ドラフトコメントを含むコメントスレッドの装飾色（不透明）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">レビュー中の未送信コメントがある行を示すマーカー</td>
  </tr>
</tbody>
</table>
</div>

### エラーと警告


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorError.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラーの波線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コードのエラー箇所に表示される赤い波線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorError.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラーボックスの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラー箇所を囲む枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorError.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラーテキストの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラー箇所のテキスト背景（半透明）</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorWarning.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告の波線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コードの警告箇所に表示される黄色い波線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorWarning.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告ボックスの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告箇所を囲む枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorWarning.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告テキストの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告箇所のテキスト背景（半透明）</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorInfo.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">情報の波線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorInfo.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">情報ボックスの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorInfo.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">情報テキストの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorHint.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ヒントの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorHint.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ヒントボックスの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>problemsErrorIcon.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">問題パネルのエラーアイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターより下部にある「問題」パネル(<code>Ctrl</code>+<code>Shift</code>+<code>M</code>)のエラー項目のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>problemsWarningIcon.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">問題パネルの警告アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターより下部にある「問題」パネル(<code>Ctrl</code>+<code>Shift</code>+<code>M</code>)の警告項目のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>problemsInfoIcon.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">問題パネルの情報アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターより下部にある「問題」パネル(<code>Ctrl</code>+<code>Shift</code>+<code>M</code>)の情報項目のアイコン</td>
  </tr>
</tbody>
</table>
</div>

### 未使用コード


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorUnnecessaryCode.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">未使用コードの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">使われていない変数やインポートを示す枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorUnnecessaryCode.opacity</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">未使用コードの不透明度</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">使われていないコードを薄く表示する際の濃さ（ハイコントラストテーマでは枠線表示が推奨）</td>
  </tr>
</tbody>
</table>
</div>

### ガター（行番号・グリフマージン）

ガターには行番号とグリフマージン（アイコン表示領域）が含まれる。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGutter.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ガターの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">行番号やアイコンが表示されるエディターの左端領域の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGutter.modifiedBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更された行のガター背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域のGit差分で変更された行のマーカー背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGutter.modifiedSecondaryBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更された行のガターのセカンダリ背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域のGit差分の変更行のマーカーの補助色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGutter.addedBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">追加された行のガター背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域のGit差分で追加された行のマーカー背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGutter.addedSecondaryBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">追加された行のガターのセカンダリ背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域のGit差分の追加行のマーカーの補助色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGutter.deletedBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">削除された行のガター背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域のGit差分で削除された行のマーカー背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGutter.deletedSecondaryBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">削除された行のガターのセカンダリ背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域のGit差分の削除行のマーカーの補助色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGutter.commentRangeForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コメント可能範囲のガター装飾色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域のプルリクエストレビューでコメント可能な行に表示されるアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGutter.commentGlyphForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コメントグリフのガター装飾色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域のコメントが付いている行のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGutter.commentUnresolvedGlyphForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">未解決コメントスレッドのグリフ色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域の未解決のレビューコメントがある行のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGutter.foldingControlForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">折り畳みコントロールの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域の行番号の右横に表示される折り畳み用の矢印アイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGutter.itemGlyphForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ガターアイテムのグリフ色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域のデバッグのブレークポイントなどのアイコン色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGutter.itemBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ガターアイテムの背景色（不透明）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域のデバッグのブレークポイントなどのアイコン背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGutter.commentDraftGlyphForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ドラフトコメントスレッドのグリフ色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域の未送信のコメントがある行のアイコン</td>
  </tr>
</tbody>
</table>
</div>

### コメントウィジェット

プルリクエストのレビュー時に表示される。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorCommentsWidget.resolvedBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">解決済みコメントの枠線・矢印の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">レビューで解決済みとされたコメントの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorCommentsWidget.unresolvedBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">未解決コメントの枠線・矢印の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">レビューで未解決のコメントの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorCommentsWidget.rangeBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コメント対象範囲の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コメントが付けられたコード範囲の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorCommentsWidget.rangeActiveBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中・ホバー中のコメント対象範囲の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在開いているコメントが対象とするコード範囲の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorCommentsWidget.replyInputBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コメント返信入力欄の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コメントへの返信を入力するテキストボックスの背景</td>
  </tr>
</tbody>
</table>
</div>

### インライン編集（Inline Edit）

AIなどが次の変更を提案する際に表示される。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineEdit.gutterIndicator.primaryBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">メインのインライン編集インジケーターの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域のAI提案の表示の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineEdit.gutterIndicator.primaryForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">メインのインライン編集インジケーターの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域のAI提案の表示のテキスト・アイコン色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineEdit.gutterIndicator.primaryBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">メインのインライン編集インジケーターの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域のAI提案の表示の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineEdit.gutterIndicator.secondaryBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サブのインライン編集インジケーターの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域の複数が提案がある場合の2つ目以降の表示の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineEdit.gutterIndicator.secondaryForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サブのインライン編集インジケーターの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域の複数が提案がある場合の2つ目以降の表示のテキスト・アイコン色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineEdit.gutterIndicator.secondaryBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サブのインライン編集インジケーターの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域の複数が提案がある場合の2つ目以降の表示の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineEdit.gutterIndicator.successfulBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">提案が成功したときのインジケーターの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域の提案を適用したときの表示の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineEdit.gutterIndicator.successfulForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">提案が成功したときのインジケーターの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域の提案を適用したときの表示のテキスト・アイコン色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineEdit.gutterIndicator.successfulBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">提案が成功したときのインジケーターの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域の提案を適用したときの表示の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineEdit.gutterIndicator.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インライン編集インジケーターの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域の表示全体のデフォルト背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineEdit.originalBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更前テキストの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">AI提案の変更前部分の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineEdit.modifiedBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更後テキストの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">AI提案の変更後部分の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineEdit.originalChangedLineBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更前テキストの変更行の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更前のコードで変更対象となった行の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineEdit.originalChangedTextBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更前テキストの変更箇所のオーバーレイ色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更前のコードで変更対象となった文字列の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineEdit.modifiedChangedLineBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更後テキストの変更行の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更後のコードで変更された行の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineEdit.modifiedChangedTextBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更後テキストの変更箇所のオーバーレイ色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更後のコードで変更された文字列の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineEdit.originalBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更前テキストの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">AI提案の変更前部分を囲む枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineEdit.modifiedBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更後テキストの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">AI提案の変更後部分を囲む枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineEdit.tabWillAcceptModifiedBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Tabキーで適用される際の変更後テキストの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Tabキーで提案を確定できる状態の変更後部分の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineEdit.tabWillAcceptOriginalBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Tabキーで適用される際の変更前テキストの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Tabキーで提案を確定できる状態の変更前部分の枠線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Diff editor colors(差分エディターカラー)</b></summary><br>


**Diff editor colors** は、同じファイルの修正前と修正後を左右、あるいは上下に並べて変更点を比較するための専用画面に関する色設定である。挿入・削除されたテキストの色付けには、背景色か境界線の色のどちらか一方のみを使用する（両方同時には使わない）。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>diffEditor.insertedTextBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">挿入されたテキストの背景色（半透明）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">追加された文字列の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>diffEditor.insertedTextBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">挿入されたテキストのアウトライン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">追加された文字列を囲む枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>diffEditor.removedTextBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">削除されたテキストの背景色（半透明）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">削除された文字列の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>diffEditor.removedTextBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">削除されたテキストのアウトライン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">削除された文字列を囲む枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>diffEditor.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">2つのエディター間の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">並んでいる差分エディターの境界線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>diffEditor.diagonalFill</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">差分エディターの斜線塗りつぶしの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">対応する変更がない領域の斜線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>diffEditor.insertedLineBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">挿入された行の背景色（半透明）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">追加された行全体の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>diffEditor.removedLineBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">削除された行の背景色（半透明）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">削除された行全体の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>diffEditorGutter.insertedLineBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">挿入された行のガター（余白）の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域の行番号左端の追加された行のマーカー背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>diffEditorGutter.removedLineBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">削除された行のガター（余白）の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの左端領域の行番号左端の削除された行のマーカー背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>diffEditorOverview.insertedForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">差分概要ルーラーの挿入コンテンツの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">差分エディター右端の概要ルーラーの追加箇所マーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>diffEditorOverview.removedForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">差分概要ルーラーの削除コンテンツの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">差分エディター右端の概要ルーラーの削除箇所マーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>diffEditor.unchangedRegionBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更のない折り畳まれた範囲のブロックの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">差分がない折り畳まれた領域のブロック背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>diffEditor.unchangedRegionForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更のない折り畳まれた範囲のブロックの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">差分がない折り畳まれた領域のブロックテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>diffEditor.unchangedRegionShadow</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更のない範囲ウィジェット周囲の影の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">折り畳まれた変更なし領域の周囲の影</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>diffEditor.unchangedCodeBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更のないコードの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">差分エディターで変更がないコード部分の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>diffEditor.move.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">移動されたテキストの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">別の場所に移動されたコードブロックの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>diffEditor.moveActive.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブな移動テキストの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在選択中の移動されたコードブロックの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>multiDiffEditor.headerBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マルチファイル差分エディターのヘッダー背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">複数ファイルの差分表示時の各ファイルヘッダーの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>multiDiffEditor.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マルチファイル差分エディターの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">複数ファイルの差分表示全体の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>multiDiffEditor.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マルチファイル差分エディターの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">複数ファイルの差分表示での各ファイル間の境界線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Chat colors(チャットカラー)</b></summary><br>


**Chat colors** は、VSCode のチャット機能に関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>chat.requestBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャットリクエストの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャットパネルのユーザー入力欄の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>chat.requestBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャットリクエストの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャットパネルのユーザー入力欄の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>chat.slashCommandBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スラッシュコマンドの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャットに入力された <code>/explain</code> などのスラッシュコマンドの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>chat.slashCommandForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スラッシュコマンドの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャットに入力された <code>/explain</code> などのスラッシュコマンドのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>chat.avatarBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャットアバターの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ユーザーやAIのアイコン部分の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>chat.avatarForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャットアバターの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ユーザーやAIのアイコン部分のテキスト・アイコン色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>chat.editedFileForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">編集済みファイルリストのファイル名の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャットで編集されたファイルの一覧に表示されるファイル名</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>chat.linesAddedForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コードブロックピルの追加行数の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コードブロック内の「+N lines」の文字色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>chat.linesRemovedForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コードブロックピルの削除行数の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コードブロック内の「-N lines」の文字色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>chat.requestCodeBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャットリクエストバブル内のコードブロックの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>chat.requestBubbleBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャットリクエストバブルの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>chat.requestBubbleHoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時のチャットリクエストバブルの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>chat.checkpointSeparator</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャットチェックポイントの区切り線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>chat.thinkingShimmer</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">思考中・処理中ラベルのシマーハイライト色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">AIが回答を生成中に表示される「Thinking...」などのアニメーション色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>chatManagement.sashBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Chat Managementエディターの分割ビューのサッシュ（境界線）の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャット画面とエディター間の境界線をクリックまたはドラッグしたときの境界線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Inline Chat colors(インラインチャットカラー)</b></summary><br>


**Inline Chat colors** は、エディター内に表示されるインラインチャットウィジェットに関する色設定である。
(参考: [Inline chat](https://code.visualstudio.com/docs/chat/inline-chat))


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineChat.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インラインチャットウィジェットの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター内に表示されるAIのチャットのウィジェットの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineChat.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インラインチャットウィジェットの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター内に表示されるAIチャットのウィジェットのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineChat.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インラインチャットウィジェットの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター内に表示されるAIチャットのウィジェットの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineChat.shadow</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インラインチャットウィジェットの影の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター内に表示されるAIチャットのウィジェットの影</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineChatInput.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インラインチャット入力欄の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター内に表示されるAIチャットのテキスト入力フィールドの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineChatInput.focusBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォーカス時のインラインチャット入力欄の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター内に表示されるAIチャットの入力フィールドを選択したときの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineChatInput.placeholderForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インラインチャット入力欄のプレースホルダーの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター内に表示されるAIチャットの入力フィールド内の「Ask Copilot」などのヒントテキストの色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineChatInput.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インラインチャット入力欄の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター内に表示されるAIチャットの入力フィールドの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineChatDiff.inserted</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インラインチャット入力欄の挿入テキストの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター内に表示されるAIチャットが提案したコードの追加部分の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>inlineChatDiff.removed</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インラインチャット入力欄の削除テキストの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター内に表示されるAIチャットが提案したコードの削除部分の背景</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Panel Chat colors(パネルチャットカラー)</b></summary><br>


**Panel Chat colors** は、インタラクティブなコードセルに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>interactive.activeCodeBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォーカス中のインタラクティブコードセルの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>interactive.inactiveCodeBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非フォーカス時のインタラクティブコードセルの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Editor widget colors(エディターウィジェットカラー)</b></summary><br>


**Editor widget colors** は、エディターコンテンツの手前に表示されるウィジェットに関する色設定である。Find(`Ctrl`+`F`)/Replace(`Ctrl`+`H`) ダイアログ、サジェストウィジェット(変数名や関数の候補のポップアップ、`Ctrl`+`Space`で表示)、エディターホバー(コード内の関数や変数にカーソルを合わせたときに、その型や使い方を教える吹き出しのポップアップ)などが該当する。

### 基本ウィジェット


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorWidget.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターウィジェットの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Find/Replace ダイアログのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorWidget.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターウィジェットの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Find/Replace ダイアログの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorWidget.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターウィジェットの境界線の色（ウィジェット固有の色がない場合に使用）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Find/Replace ダイアログの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorWidget.resizeBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターウィジェットのリサイズバーの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウィジェットの下端にあるドラッグしてサイズ変更するための線</td>
  </tr>
</tbody>
</table>
</div>

### サジェストウィジェット


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorSuggestWidget.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サジェストウィジェットの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変数名や関数の候補のポップアップの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorSuggestWidget.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サジェストウィジェットの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変数名や関数の候補のポップアップの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorSuggestWidget.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サジェストウィジェットの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変数名や関数の候補のポップアップのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorSuggestWidget.focusHighlightForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォーカス中の項目のマッチハイライト色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変数名や関数の候補のポップアップの現在選択している候補内の入力文字に一致する部分の色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorSuggestWidget.highlightForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マッチハイライトの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変数名や関数の候補のポップアップの候補内の入力文字に一致する部分の色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorSuggestWidget.selectedBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中の項目の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変数名や関数の候補のポップアップで選択中の項目の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorSuggestWidget.selectedForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中の項目の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変数名や関数の候補のポップアップで選択中の項目のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorSuggestWidget.selectedIconForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中の項目のアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変数名や関数の候補のポップアップで選択中の項目の種別アイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorSuggestWidgetStatus.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サジェストウィジェットのステータスの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変数名や関数の候補のポップアップ内のリスト下部に表示されるステータステキスト</td>
  </tr>
</tbody>
</table>
</div>

### ホバーウィジェット


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorHoverWidget.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターホバーの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コード内の関数や変数にカーソルを合わせたときに、その型や使い方を教える吹き出しのポップアップのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorHoverWidget.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターホバーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コード内の関数や変数にカーソルを合わせたときに、その型や使い方を教える吹き出しのポップアップの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorHoverWidget.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターホバーの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コード内の関数や変数にカーソルを合わせたときに、その型や使い方を教える吹き出しのポップアップの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorHoverWidget.highlightForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パラメータヒントのアクティブな項目の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">関数の引数のヒントで現在入力中の引数のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorHoverWidget.statusBarBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターホバーのステータスバーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コード内の関数や変数にカーソルを合わせたときに、その型や使い方を教える吹き出しのポップアップ下部のステータスバー背景</td>
  </tr>
</tbody>
</table>
</div>

### ゴーストテキスト


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGhostText.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ゴーストテキストの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">AIが自動で補完するテキスト領域の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGhostText.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ゴーストテキストの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">AIが自動で補完するテキスト領域の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorGhostText.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ゴーストテキストの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">AIが自動で補完するテキスト</td>
  </tr>
</tbody>
</table>
</div>

### スティッキースクロール

巨大なファイルをスクロールしているとき、現在どの関数やクラス、ネストの中にいるのかを明確にするために、親要素の行（定義部分）をエディタの最上部に固定して表示する機能である。
`"editor.stickyScroll.enabled": true`とすることで表示される。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorStickyScroll.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターのスティッキースクロールの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スクロール時にエディター上部に固定表示されるスコープ（クラス名・関数名など）の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorStickyScroll.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターのスティッキースクロールの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スクロール時にエディター上部に固定表示されるスコープ部分の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorStickyScroll.shadow</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターのスティッキースクロールの影の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スクロール時にエディター上部に固定表示されるスコープ部分とエディター本体の間の影</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorStickyScrollGutter.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スティッキースクロールのガター部分の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スクロール時にエディター上部に固定表示されるスコープの行番号領域の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorStickyScrollHover.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時のスティッキースクロールの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スクロール時にエディター上部に固定表示されるスコープにホバーしたときの背景</td>
  </tr>
</tbody>
</table>
</div>

### デバッグ例外ウィジェット

デバッグ中に例外で停止したときにエディター内に表示されるピークビュー。
(参考: [Extension API to Access ExceptionWidget (or ZoneWidget)](https://github.com/microsoft/vscode/issues/140752)
)


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugExceptionWidget.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">例外ウィジェットの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中に例外が発生したときのポップアップ背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugExceptionWidget.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">例外ウィジェットの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中に例外が発生したときのポップアップ枠線</td>
  </tr>
</tbody>
</table>
</div>

### エディターマーカーナビゲーション

「次のエラーまたは警告へ移動(`F8`)」を実行した際に、コードのすぐ下に出現するエラーメッセージ表示用の専用ウィジェット（ダイアログボックス）です。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorMarkerNavigation.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マーカーナビゲーションウィジェットの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラー・警告ナビゲーションポップアップの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorMarkerNavigationError.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マーカーナビゲーションのエラー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラー箇所に移動したときのポップアップのエラー表示の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorMarkerNavigationWarning.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マーカーナビゲーションの警告色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告箇所に移動したときのポップアップの警告表示の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorMarkerNavigationInfo.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マーカーナビゲーションの情報色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">情報箇所に移動したときのポップアップの情報表示の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorMarkerNavigationError.headerBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マーカーナビゲーションのエラーヘッダーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラーナビゲーションポップアップのヘッダー背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorMarkerNavigationWarning.headerBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マーカーナビゲーションの警告ヘッダーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告ナビゲーションポップアップのヘッダー背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorMarkerNavigationInfo.headerBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マーカーナビゲーションの情報ヘッダーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">情報ナビゲーションポップアップのヘッダー背景</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Peek view colors(ピークビューカラー)</b></summary><br>


**Peek view colors** は、関数の定義元や参照されている場所をエディター内の現在のコードの行間に表示するビューに関する色設定である。`Alt` + `F12`で表示される。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>peekView.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビューの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>peekViewEditor.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビューエディターの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュー内のコード表示部分の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>peekViewEditorGutter.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビューエディターのガターの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュー内の行番号領域の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>peekViewEditor.matchHighlightBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビューエディター内のマッチハイライトの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュー内で検索文字列に一致する箇所の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>peekViewEditor.matchHighlightBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビューエディター内のマッチハイライトの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュー内で検索文字列に一致する箇所の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>peekViewResult.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュー結果リストの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュー右側に表示される参照箇所一覧の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>peekViewResult.fileForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュー結果リストのファイルノードの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュー右側に表示される参照箇所一覧に表示されるファイル名のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>peekViewResult.lineForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュー結果リストの行ノードの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュー右側に表示される参照箇所一覧に表示される<code>peekViewResult.fileForeground</code>以外のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>peekViewResult.matchHighlightBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュー結果リストのマッチハイライトの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュー右側に表示される参照箇所一覧で検索文字列に一致する箇所の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>peekViewResult.selectionBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュー結果リストの選択中項目の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュー右側に表示される参照箇所一覧で選択中の(ピークビューに現在表示させている)項目の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>peekViewResult.selectionForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュー結果リストの選択中項目の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュー右側に表示される参照箇所一覧で選択中の(ピークビューに現在表示させている)項目のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>peekViewTitle.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュータイトル領域の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュー上部のタイトルバーの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>peekViewTitleDescription.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュータイトルの補足情報の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">タイトルバーのタイトルの右に表示されるディレクトリ場所の表記などの補足テキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>peekViewTitleLabel.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュータイトルの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">タイトルバーに表示されるファイル名(タイトル)のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>peekViewEditorStickyScroll.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビューエディターのスティッキースクロールの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュー内でスクロール時に固定表示されるスコープの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>peekViewEditorStickyScrollGutter.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビューエディターのスティッキースクロールのガター部分の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビュー内で固定表示されるスコープの行番号領域の背景</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Merge conflicts colors(マージコンフリクトカラー)</b></summary><br>


**Merge conflicts colors** は、エディター内に特殊な差分範囲（マージコンフリクト）があるときに表示される装飾に関する色設定である。

### インラインマージコンフリクト


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>merge.currentHeaderBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在の変更（Current）のヘッダー背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">`<<<<<<< HEAD` のヘッダー部分の背景（半透明）</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>merge.currentContentBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在の変更（Current）のコンテンツ背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">`<<<<<<< HEAD` のコード部分の背景（半透明）</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>merge.incomingHeaderBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">取り込む変更（Incoming）のヘッダー背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">`<<<<<<< somebranch` のヘッダー部分の背景（半透明）</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>merge.incomingContentBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">取り込む変更（Incoming）のコンテンツ背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">`<<<<<<< somebranch` のコード部分の背景（半透明）</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>merge.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ヘッダーと区切り線の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コンフリクト各セクションのヘッダーや区切り線の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>merge.commonContentBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">共通の祖先（Common ancestor）のコンテンツ背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">3-way diffでの`<<<<<<< common`のコード部分の背景（半透明）</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>merge.commonHeaderBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">共通の祖先（Common ancestor）のヘッダー背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">3-way diffでの`<<<<<<< common`ののヘッダー部分の背景（半透明）</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.currentContentForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在の変更（Current）の概要ルーラーのマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター右端のスクロールバーの下に重なっている、エディター内の装飾の概要を示す欄で、現在の変更部分（Current）を示すマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.incomingContentForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">取り込む変更（Incoming）の概要ルーラーのマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター右端のスクロールバーの下に重なっている、エディター内の装飾の概要を示す欄で、取り込む変更部分を示すマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.commonContentForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">共通の祖先（Common ancestor）の概要ルーラーのマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター右端のスクロールバーの下に重なっている、エディター内の装飾の概要を示す欄で、共通部分を示すマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.commentForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">解決済みコメントの概要ルーラー装飾色（不透明）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター右端のスクロールバーの下に重なっている、エディター内の装飾の概要を示す欄で、解決済みコメントを示すマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editorOverviewRuler.commentUnresolvedForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">未解決コメントの概要ルーラー装飾色（不透明）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター右端のスクロールバーの下に重なっている、エディター内の装飾の概要を示す欄で、未解決のコメントを示すマーカー</td>
  </tr>
</tbody>
</table>
</div>

### マージエディター（3-wayマージ）

`3-way merge editor`とは、エディター上に
現在のブランチの更新内容と競合部分が表示される画面(Current, 上部右側画面)
現在のブランチにマージするブランチの更新内容と競合部分が表示される画面(Incoming, 上部左側画面)
競合の解決を行う編集画面(Result, 下画面)
の3画面を表示させてブランチとの競合の解決を行う専用の画面である。
タブの欄の一番右にある"その他の操作..."から「ベースの表示（Show Base）」を押すとIncomingやCurrentに書き換えられる前の、元々のコード(Base)が出現する。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>mergeEditor.change.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更箇所の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マージエディターで変更がある行の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>mergeEditor.change.word.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">単語単位の変更箇所の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マージエディターで変更された単語部分の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>mergeEditor.conflict.unhandledUnfocused.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">未処理・非フォーカス時のコンフリクトの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">まだ解決していない、選択していないコンフリクト箇所の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>mergeEditor.conflict.unhandledFocused.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">未処理・フォーカス時のコンフリクトの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">まだ解決していない、現在選択中のコンフリクト箇所の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>mergeEditor.conflict.handledUnfocused.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">処理済み・非フォーカス時のコンフリクトの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">解決済みで、選択していないコンフリクト箇所の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>mergeEditor.conflict.handledFocused.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">処理済み・フォーカス時のコンフリクトの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">解決済みで、現在選択中のコンフリクト箇所の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>mergeEditor.conflict.handled.minimapOverViewRuler</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">処理済みコンフリクトのミニマップ／概要ルーラー上の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">右側のファイルのズームアウトを示すミニマップ上の解決済みコンフリクトのマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>mergeEditor.conflict.unhandled.minimapOverViewRuler</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">未処理コンフリクトのミニマップ／概要ルーラー上の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">右側のファイルのズームアウトを示すミニマップ上の未解決コンフリクトのマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>mergeEditor.conflictingLines.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「Conflicting Lines」テキストの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コンフリクトがある行数を示すメッセージの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>mergeEditor.changeBase.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ベース（Base）側の変更箇所の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">3-way diffでの元々のコードにおける変更された行の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>mergeEditor.changeBase.word.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ベース（Base）側の単語単位の変更箇所の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">3-way diffでの元々のコードにおける変更された単語部分の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>mergeEditor.conflict.input1.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Input1側の装飾の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">3-way diffでの自分側（Current, Input1）コードの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>mergeEditor.conflict.input2.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Input2側の装飾の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">3-way diffでのマージ元側（Incoming, Input2）コードの背景</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Panel colors(パネルカラー)</b></summary><br>


**Panel colors** は、エディター領域の下に表示されるパネルに関する色設定である。問題、出力、デバッグコンソール、ターミナル、ポートなどを含む欄。

<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>panel.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネルの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネル全体の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>panel.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネルとエディターを区切る境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネルとエディター領域の間の境界線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>panel.dropBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネルタイトルへのドラッグ&ドロップ時の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネル上部のタブ(タイトル)をドラッグして並び替えるときのタブ間の境界線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>panelTitle.activeBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブなパネルタイトルの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中のパネルタブ（「ターミナル」など）の下に表示される線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>panelTitle.activeForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブなパネルのタイトル色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中のパネルタブ（「ターミナル」など）のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>panelTitle.inactiveForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非アクティブなパネルのタイトル色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">未選択のパネルタブのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>panelTitle.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネルタイトル下部の境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネルタイトルとビュー(本体)を区切る下線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>panelTitleBadge.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネルタイトルバッジの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「問題」タブの件数表示バッジの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>panelTitleBadge.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネルタイトルバッジの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「問題」タブの件数表示バッジのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>panelInput.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネル内の入力ボックスの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグコンソールの入力欄の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>panelSection.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">複数ビューが横に並んでいるときのパネルセクションの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネルを横分割して複数表示したときの境界線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>panelSection.dropBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネルセクションへのドラッグ&ドロップ時の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネル内でビューをドラッグしているときの背景（半透明）</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>panelSectionHeader.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネルセクションヘッダーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネル内の各セクション見出しの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>panelSectionHeader.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネルセクションヘッダーの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネル内の各セクション見出しのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>panelStickyScroll.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネルのスティッキースクロールの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネル内でスクロール時に上部に固定表示される親要素の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>panelStickyScroll.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネルのスティッキースクロールの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネル内でスクロール時に上部に固定表示される親要素の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>panelStickyScroll.shadow</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネルのスティッキースクロールの影の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネル内でスクロール時に上部に固定表示される親要素の影</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>panelSectionHeader.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">複数ビューが縦に並んでいるときのパネルセクションヘッダーの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネルを縦分割して複数表示したときのセクション見出しの境界線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>outputView.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">出力ビューの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「出力」パネルの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>outputViewStickyScroll.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">出力ビューのスティッキースクロールの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「出力」パネルでスクロール時に固定表示される部分の背景</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Status Bar colors(ステータスバーカラー)</b></summary><br>


**Status Bar colors** は、ウィンドウ最下部に表示されるステータスバーに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBar.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">標準時のステータスバーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ステータスバー全体の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBar.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ステータスバーの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ステータスバーに表示されるテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBar.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ステータスバーとエディターを区切る境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ステータスバー上部の境界線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBar.debuggingBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中のステータスバーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">プログラムをデバッグ実行中のステータスバー背景（通常オレンジ系）</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBar.debuggingForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中のステータスバーの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ実行中のステータスバーのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBar.debuggingBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中のステータスバーとエディターを区切る境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ実行中のステータスバーとエディターを区切る境界線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBar.noFolderForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォルダーを開いていないときのステータスバーの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォルダー未オープン時のステータスバーのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBar.noFolderBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォルダーを開いていないときのステータスバーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォルダー未オープン時のステータスバー背景（通常紫系）</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBar.noFolderBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォルダーを開いていないときのステータスバーとエディターを区切る境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォルダー未オープン時のステータスバーとエディターを区切る境界線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.activeBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">クリック時のステータスバーアイテムの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ステータスバーの項目をクリックして押し込んでいるときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.hoverForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時のステータスバーアイテムの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ステータスバーの項目にホバーしたときのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.hoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時のステータスバーアイテムの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ステータスバーの項目にホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.prominentForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">強調アイテムの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能の Live Server を使ってローカルサーバーを起動したときにステータスバーの右側に表示される「Port: 5500（停止ボタン）」の強調表示項目のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.prominentBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">強調アイテムの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能の Live Server を使ってローカルサーバーを起動したときにステータスバーの右側に表示される「Port: 5500（停止ボタン）」の強調表示項目の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.prominentHoverForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時の強調アイテムの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能の Live Server を使ってローカルサーバーを起動したときにステータスバーの右側に表示される「Port: 5500（停止ボタン）」の強調表示項目にホバーしたときのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.prominentHoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時の強調アイテムの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能の Live Server を使ってローカルサーバーを起動したときにステータスバーの右側に表示される「Port: 5500（停止ボタン）」の強調表示項目にホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.remoteBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">リモートインジケーターの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「リモート接続中」を示す左下のアイコン部分の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.remoteForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">リモートインジケーターの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「リモート接続中」を示す左下のアイコン部分のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.remoteHoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時のリモートインジケーターの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「リモート接続中」を示す左下のアイコン部分にホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.remoteHoverForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時のリモートインジケーターの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「リモート接続中」を示す左下のアイコン部分にホバーしたときのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.errorBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラーアイテムの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラー状態を示すステータスバーの項目の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.errorForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラーアイテムの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラー状態を示すステータスバーの項目のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.errorHoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時のエラーアイテムの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラー状態のステータスバーの項目にホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.errorHoverForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時のエラーアイテムの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラー状態のステータスバーの項目にホバーしたときのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.warningBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告アイテムの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告状態を示すステータスバーの項目の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.warningForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告アイテムの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告状態を示すステータスバーの項目のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.warningHoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時の警告アイテムの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告状態のステータスバーの項目にホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.warningHoverForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時の警告アイテムの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告状態のステータスバーの項目にホバーしたときのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.compactHoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">2つのホバー情報を持つ項目にホバーしたときの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.focusBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">キーボード操作でフォーカス時のステータスバーアイテムの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドパレット(<code>Ctrl</code>+<code>Shift</code>+<code>P</code>)から「View: Focus Status Bar」を選択し、左右の矢印キー(←, →)で項目を移動したときに表示されるターゲットの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBar.focusBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">キーボード操作でフォーカス時のステータスバーの境界線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドパレット(<code>Ctrl</code>+<code>Shift</code>+<code>P</code>)から「View: Focus Status Bar」を選択し、ステータスバー自体にフォーカスしたときの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.offlineBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ワークベンチがオフライン時のアイテムの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ネットワーク未接続時のステータスバー項目の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.offlineForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ワークベンチがオフライン時のアイテムの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ネットワーク未接続時のステータスバー項目のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.offlineHoverForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">オフライン時、ホバーしたアイテムの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ネットワーク未接続時のステータスバー項目にホバーしたときのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>statusBarItem.offlineHoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">オフライン時、ホバーしたアイテムの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ネットワーク未接続時のステータスバー項目にホバーしたときの背景</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Title Bar colors(タイトルバーカラー)</b></summary><br>


**Title Bar colors** は、ウィンドウ最上部に表示されるタイトルバーに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>titleBar.activeBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウィンドウがアクティブなときのタイトルバーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">VSCodeウィンドウを操作しているときのタイトルバー背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>titleBar.activeForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウィンドウがアクティブなときのタイトルバーの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">VSCodeウィンドウを操作しているときのタイトルバーのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>titleBar.inactiveBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウィンドウが非アクティブなときのタイトルバーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">VSCodeウィンドウを操作していないときのタイトルバー背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>titleBar.inactiveForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウィンドウが非アクティブなときのタイトルバーの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">VSCodeウィンドウを操作していないときのタイトルバーのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>titleBar.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">タイトルバーのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">タイトルバー下部の境界線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Menu Bar colors(メニューバーカラー)</b></summary><br>


**Menu Bar colors** は、ウィンドウ最上部にあるメニューバーとそれを開いたときのメニュー項目に関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>menubar.selectionForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">メニューバーで選択中の項目の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「ファイル」「編集」などのメニューバーの項目を選択したときのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>menubar.selectionBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">メニューバーで選択中の項目の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「ファイル」「編集」などのメニューバーの項目を選択したときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>menubar.selectionBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">メニューバーで選択中の項目のボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「ファイル」「編集」などのメニューバーの項目を選択したときの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>menu.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">メニュー項目の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「ファイル」をクリックして開いたドロップダウンメニューのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>menu.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">メニュー項目の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">開いたときのドロップダウンメニュー全体の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>menu.selectionForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">メニュー内で選択中の項目の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ドロップダウンメニュー内でホバー・選択中の項目のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>menu.selectionBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">メニュー内で選択中の項目の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ドロップダウンメニュー内でホバー・選択中の項目の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>menu.selectionBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">メニュー内で選択中の項目のボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ドロップダウンメニュー内でホバー・選択中の項目の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>menu.separatorBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">メニュー内の区切り線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ドロップダウンメニュー内のセクションを分ける横線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>menu.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">メニューのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">開いたときのドロップダウンメニュー全体の枠線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Command Center colors(コマンドセンターカラー)</b></summary><br>


**Command Center colors** は、タイトルバー中央のタイトルをクリックしたときに表示されるコマンドセンターに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>commandCenter.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドセンターの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドセンターのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>commandCenter.activeForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブ時のコマンドセンターの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドセンター内のクリック・選択した項目のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>commandCenter.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドセンターの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドセンターの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>commandCenter.activeBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブ時のコマンドセンターの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドセンター内のクリック・選択した項目の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>commandCenter.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドセンターのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドセンターの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>commandCenter.inactiveForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウィンドウが非アクティブなときのコマンドセンターの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドセンター内のクリック・選択していない項目のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>commandCenter.inactiveBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウィンドウが非アクティブなときのコマンドセンターのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドセンター内のクリック・選択していない項目の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>commandCenter.activeBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクティブ時のコマンドセンターのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドセンター内のクリック・選択した項目の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>commandCenter.debuggingBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中のコマンドセンターの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">プログラムをデバッグ実行中のコマンドセンターの背景</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Notification colors(通知カラー)</b></summary><br>


**Notification colors** は、ワークベンチ右下から表示される通知に関する色設定である。
notificationCenter(通知センター)は、ヘッダー付きの通知のリストであり、notificationToast(通知トースト)は、ヘッダーがない単通知のポップアップを指す。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notificationCenter.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通知センターのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通知センター全体を囲む枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notificationCenterHeader.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通知センターのヘッダーの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通知センター上部の「Notifications」などのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notificationCenterHeader.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通知センターのヘッダーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通知センター上部のヘッダー部分の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notificationToast.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通知のボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ヘッダーがない単通知のポップアップの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notifications.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通知の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通知に表示されるメッセージのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notifications.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通知の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通知全体の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notifications.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通知センター内で他の通知と区切るボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通知センター内で複数の通知を区切る線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notificationLink.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通知内のリンクの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通知メッセージ内に含まれるリンクテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notificationsErrorIcon.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通知のエラーアイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラー通知に表示されるアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notificationsWarningIcon.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通知の警告アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">警告通知に表示されるアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notificationsInfoIcon.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通知の情報アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">情報通知に表示されるアイコン</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Banner colors(バナーカラー)</b></summary><br>


**Banner colors** は、タイトルバーの下に表示され、ワークベンチの幅いっぱいに広がるバナーに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>banner.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">バナーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>banner.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">バナーの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>banner.iconForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">バナーテキスト前のアイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Extensions colors(拡張機能カラー)</b></summary><br>


**Extensions colors** は、拡張機能ビューに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>extensionButton.prominentForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能ビューの強調ボタンの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「インストール」や「再読み込み」ボタンのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>extensionButton.prominentBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能ビューの強調ボタンの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「インストール」や「再読み込み」ボタンの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>extensionButton.prominentHoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時の強調ボタンの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「インストール」や「再読み込み」ボタンにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>extensionButton.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能アクションボタンの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「無効にする」など通常のアクションボタンの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>extensionButton.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能アクションボタンの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「無効にする」など通常のアクションボタンのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>extensionButton.hoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時の拡張機能アクションボタンの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">通常のアクションボタンにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>extensionButton.separator</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能アクションボタンの区切り線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「無効にする」や「アンインストール」などのドロップダウン付きボタンの区切り線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>extensionButton.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能アクションボタンのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「無効にする」など通常のアクションボタンの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>extensionBadge.remoteBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能ビューのリモートバッジの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">VSCodeをリモート接続モードで起動した状態で、拡張機能タブを開いたときに各拡張機能のタイトルの右横にある接続先の環境名が書かれたバッジの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>extensionBadge.remoteForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能ビューのリモートバッジの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">VSCodeをリモート接続モードで起動した状態で、拡張機能タブを開いたときに各拡張機能のタイトルの右横にある接続先の環境名が書かれたバッジのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>extensionIcon.starForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能の評価アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能の星評価（★）アイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>extensionIcon.verifiedForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">拡張機能の認証済み発行者アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">公式認証(発行元)済みを示すチェックマークアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>extensionIcon.preReleaseForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">プレリリース版拡張機能のアイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">プレリリース版や推奨欄の左上にあるアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>extensionIcon.sponsorForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スポンサー機能のアイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スポンサーを募集している拡張機能のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>extensionIcon.privateForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">プライベート拡張機能のアイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">非公開の拡張機能を示すアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>mcpIcon.starForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">MCPのスター付きアイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スター登録されたMCPサーバーを示すアイコン</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Quick picker colors(クイックピッカーカラー)</b></summary><br>


**Quick picker colors** は、コマンドパレット(`Ctrl`+`Shift`+`P`)やカラーテーマ選択ウィンドウなどに使われるクイックピッカー（クイックオープン）UIに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>pickerGroup.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">クイックピッカーのグループ区切りボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドパレットでカテゴリ間を区切る線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>pickerGroup.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">クイックピッカーのグループラベルの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドパレットのカテゴリ見出しのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>quickInput.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">クイック入力ウィジェットの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドパレットやカラーテーマ選択ウィンドウの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>quickInput.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">クイック入力ウィジェットの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドパレットやカラーテーマ選択ウィンドウのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>quickInputList.focusBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォーカス中の項目の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドパレットでカーソルが当たっている項目の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>quickInputList.focusForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォーカス中の項目の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドパレットでカーソルが当たっている項目のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>quickInputList.focusIconForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォーカス中の項目のアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドパレットでカーソルが当たっている項目の右側のギアマークのアイコン、拡張機能の固有アイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>quickInputTitle.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">クイックピッカーのタイトルの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Keybinding label colors(キーバインドラベルカラー)</b></summary><br>


**Keybinding label colors** は、コマンドに関連付けられたキーボードショートカットを表示するラベルに関する色設定である。コマンドパレット、キーボードショートカットエディター、キーボードショートカット記録モーダル、拡張機能のマーケットプレイスページの機能紹介セクションなどで使われる。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>keybindingLabel.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">キーバインドラベルの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドパレットに表示される「Ctrl+Shift+P」などのキー表示の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>keybindingLabel.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">キーバインドラベルの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドパレットに表示される「Ctrl+Shift+P」などのキー表示のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>keybindingLabel.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">キーバインドラベルのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">キー表示を囲む枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>keybindingLabel.bottomBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">キーバインドラベルの下部ボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">キー表示の下端に表示される線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Keyboard shortcut table colors(キーボードショートカットテーブルカラー)</b></summary><br>


**Keyboard shortcut table colors** は、キーボードショートカットエディターのテーブルに関する色設定である。コマンドパレット（`Ctrl`+`Shift`+`P`）を開いて、「Preferences: Open Keyboard Shortcuts」と入力して実行することで表示される。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>keybindingTable.headerBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">キーボードショートカットテーブルのヘッダーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「コマンド」「キーバインド」などの見出し行の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>keybindingTable.rowsBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">キーボードショートカットテーブルの交互行の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">表の1行おきに付く背景色（縞模様）</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Integrated Terminal colors(統合ターミナルカラー)</b></summary><br>


**Integrated Terminal colors** は、統合ターミナルに関する色設定である。`terminalSymbolIcon`が出現するターミナルの補完候補はsettings.json に `"terminal.integrated.suggest.enabled": true` を追加することで表示される。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">統合ターミナルのビューポートの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナル全体の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナル内の分割ペインを区切るボーダー色（デフォルトは <code>panel.border</code>）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルを分割表示したときの境界線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">統合ターミナルのデフォルト文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルのデフォルトテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.ansiBlack</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルのANSI「Black」カラー</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>black</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.ansiBlue</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルのANSI「Blue」カラー</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>blue</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.ansiBrightBlack</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルのANSI「BrightBlack」カラー</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>bright black</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.ansiBrightBlue</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルのANSI「BrightBlue」カラー</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>bright blue</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.ansiBrightCyan</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルのANSI「BrightCyan」カラー</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>bright cyan</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.ansiBrightGreen</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルのANSI「BrightGreen」カラー</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>bright green</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.ansiBrightMagenta</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルのANSI「BrightMagenta」カラー</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>bright magenta</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.ansiBrightRed</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルのANSI「BrightRed」カラー</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>bright red</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.ansiBrightWhite</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルのANSI「BrightWhite」カラー</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>bright white</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.ansiBrightYellow</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルのANSI「BrightYellow」カラー</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>bright yellow</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.ansiCyan</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルのANSI「Cyan」カラー</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>cyan</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.ansiGreen</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルのANSI「Green」カラー</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>green</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.ansiMagenta</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルのANSI「Magenta」カラー</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>magenta</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.ansiRed</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルのANSI「Red」カラー</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>red</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.ansiWhite</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルのANSI「White」カラー</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>white</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.ansiYellow</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルのANSI「Yellow」カラー</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>yellow</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.selectionBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルの選択範囲の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナル上でテキストを選択したときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.selectionForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルの選択範囲の文字色（nullの場合は最小コントラスト比が適用される）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナル上で選択中のテキストの文字色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.inactiveSelectionBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォーカスのないターミナルの選択範囲の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在操作していないターミナルでの選択中テキストの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.findMatchBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナル内検索の現在のマッチ箇所の背景色（半透明）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナル内の検索でマッチ箇所の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.findMatchBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナル内検索の現在のマッチ箇所のボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナル内の検索でマッチ箇所の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.findMatchHighlightBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナル内検索のその他のマッチ箇所の背景色（半透明）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナル内検索で選択していないマッチ箇所の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.findMatchHighlightBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナル内検索のその他のマッチ箇所のボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナル内検索で選択していないマッチ箇所の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.hoverHighlightBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナル内のリンクにホバーしたときのハイライト色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルに出力されたURLなどにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalCursor.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルカーソルの背景色（ブロックカーソルに重なる文字色の調整用）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ブロックカーソルが文字に重なったときの文字色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalCursor.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルカーソルの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナル上の点滅するカーソル</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.dropBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナル上にドラッグしたときの背景色（半透明）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ファイルをターミナルにドラッグしているときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.tab.activeBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パネル内のターミナルタブの側面のボーダー色（デフォルトは <code>tab.activeBorder</code>）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの下に表示されるパネル内で選択中のターミナルタブの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalCommandDecoration.defaultBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルコマンド装飾のデフォルト背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンド実行結果を示すターミナルの左側の丸いアイコンの標準背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalCommandDecoration.successBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">成功したコマンドのターミナルコマンド装飾の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">正常終了したコマンドを示すターミナルの行の左端の丸いアイコンの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalCommandDecoration.errorBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">失敗したコマンドのターミナルコマンド装飾の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エラー終了したコマンドを示すターミナルの行の左端の丸いアイコンの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalOverviewRuler.cursorForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">概要ルーラーのカーソル色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナル右端のスクロールバーの下に重なっている概要ルーラー上のカーソル位置マーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalOverviewRuler.findMatchForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナル内検索の概要ルーラーのマッチマーカー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナル右端のスクロールバーの下に重なっている概要ルーラー上の検索ワードと一致した箇所のマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalStickyScroll.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルのスティッキースクロールオーバーレイの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スクロール時にターミナルの上部に固定表示されるコマンド行の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalStickyScroll.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルのスティッキースクロールオーバーレイのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スクロール時にターミナルの上部に固定表示されるコマンド行の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalStickyScrollHover.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時のターミナルのスティッキースクロールオーバーレイの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スクロール時にターミナルの上部に固定表示されるコマンド行にホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminal.initialHintForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルの初期ヒントの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">新規ターミナルを開いたときに表示されるヒントテキスト(参考: [Consider defaulting terminal.integrated.initialHint to false](https://github.com/posit-dev/positron/issues/13227))</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalOverviewRuler.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">概要ルーラー左側のボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナル右端のスクロールバーの下に重なっている概要ルーラーの左の境界線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalCommandGuide.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドガイドの文字色（コマンドとその出力の左側にホバー時表示）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンド実行結果にホバーしたときに左に表示されるガイド線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalSymbolIcon.aliasForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エイリアスアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルに <code>g</code> などエイリアスの一部を入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalSymbolIcon.branchForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ブランチアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルで <code>git checkout</code> の後に入力したときに表示されるブランチ名補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalSymbolIcon.commitForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コミットアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルで <code>git show</code> の後に入力したときに表示されるコミット補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalSymbolIcon.flagForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フラグアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルで <code>ls -</code> のように <code>-</code> を入力したときに表示されるフラグ補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalSymbolIcon.optionForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">オプションアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルで <code>--</code> のように長いオプション名を入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalSymbolIcon.optionValueForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">enumメンバーアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ターミナルでオプションの後にTabキーを押したときに表示される選択可能な値（例：<code>--color=</code> の後の <code>always</code>/<code>never</code>）の補完候補アイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalSymbolIcon.methodForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">メソッドアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">npmスクリプトなどコマンド内のサブコマンドを入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalSymbolIcon.argumentForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">引数アイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドの後にスペースを入力したときに表示される引数候補のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalSymbolIcon.inlineSuggestionForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インライン提案アイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">過去に実行したコマンドの履歴から薄く表示されるインライン補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalSymbolIcon.fileForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ファイルアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>cat</code> などの後にファイル名を入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalSymbolIcon.folderForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォルダーアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>cd</code> の後にフォルダー名を入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalSymbolIcon.pullRequestDoneForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">完了したプルリクエストアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">GitHub CLI（<code>gh pr</code> など）でクローズ済みPR番号を入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalSymbolIcon.pullRequestForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">プルリクエストアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">GitHub CLIでオープン中のPR番号を入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalSymbolIcon.remoteForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">リモートアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>git push</code> の後にリモート名を入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalSymbolIcon.stashForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スタッシュアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>git stash apply</code> の後にスタッシュ名を入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalSymbolIcon.symbolText</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">プレーンテキスト提案の文字色（ターミナルサジェストウィジェットに表示）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">種別の判別がつかない単純な文字列補完候補のアイコン色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalSymbolIcon.symbolicLinkFileForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">シンボリックリンクファイルアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>cat</code> などの後にシンボリックリンクされたファイル名を入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalSymbolIcon.symbolicLinkFolderForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">シンボリックリンクフォルダーアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>cd</code> の後にシンボリックリンクされたフォルダー名を入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>terminalSymbolIcon.tagForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">タグアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>git checkout</code> の後にタグ名を入力したときに表示される補完候補のアイコン</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Debug colors(デバッグカラー)</b></summary><br>


**Debug colors** は、デバッグ機能に関する色設定である。`Ctrl`+`Shift`+`D`で「実行とデバッグ」をクリックすることでサイドバーがデバッグツールバーとなる。
変数ビューやウォッチ式はデバッグ時のサイドバーの下部に表示される。
参考: [VS Codeしか勝たん](https://qiita.com/Kuroi_Cc/items/7f4bc810538daf4d3c35)


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugToolBar.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグツールバーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグツールバーのの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugToolBar.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグツールバーのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグツールバーの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.stackFrameHighlightBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター内の最上位スタックフレームのハイライト背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中にブレークポイントで現在一時停止（ブレーク）している、エディター内の実行中のコード行（スタックフレーム）の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.focusedStackFrameHighlightBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター内のフォーカス中スタックフレームのハイライト背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中にブレークポイントで現在一時停止（ブレーク）している、エディター内で選択している実行中のコード行（スタックフレーム）の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.inlineValuesForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグのインライン値表示の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中にエディターのコード行末に表示される変数の値のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.inlineValuesBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグのインライン値表示の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中にエディターのコード行末に表示される変数の値の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugView.exceptionLabelForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">例外で停止したときのコールスタックビューのラベルの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ時で例外が発生したときにエディターのコード行間に表示されるラベルのテキスト(参考: [Ability to hide/show VSCode Exception area](https://github.com/microsoft/vscode/issues/88217))</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugView.exceptionLabelBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">例外で停止したときのコールスタックビューのラベルの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ時で例外が発生したときにエディターのコード行間に表示されるラベルの背景(参考: [Ability to hide/show VSCode Exception area](https://github.com/microsoft/vscode/issues/88217))</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugView.stateLabelForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コールスタックの状態ラベルの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中のサイドバーの下部にあるコールスタックビューに表示される「一時停止中」などの状態ラベルのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugView.stateLabelBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コールスタックビューの状態ラベルの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中のサイドバーの下部にあるコールスタックビューに表示される「一時停止中」などの状態ラベルの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugView.valueChangedHighlight</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグビューで値が変化したときのハイライト色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中のサイドバーの下部にある変数ビューで前回と値が変わった変数のハイライト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugTokenExpression.name</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグビューのトークン名の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中のサイドバーの下部にある変数ビューやウォッチ式に表示される変数名のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugTokenExpression.value</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグビューのトークン値の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中のサイドバーの下部にある変数ビューやウォッチ式に表示される変数の値のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugTokenExpression.string</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグビューの文字列値の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中のサイドバーの下部にある変数ビューで文字列型の値のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugTokenExpression.boolean</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグビューの真偽値の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中のサイドバーの下部にある変数ビューで <code>true</code>/<code>false</code> 値のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugTokenExpression.number</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグビューの数値の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中のサイドバーの下部にある変数ビューで数値型の値のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugTokenExpression.error</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグビューの式エラーの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中のサイドバーの下部にあるウォッチ式が評価できないときのエラーテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugTokenExpression.type</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグビューのトークン型の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中のサイドバーの下部にある変数ビューやウォッチ式に表示される変数の型名のテキスト</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Testing colors(テストカラー)</b></summary><br>


**Testing colors** は、テスト関連機能に関する色設定である。
アクティビティバーからテストエクスプローラーを選択すると、サイドバーにテストエクスプローラーが表示される。
参考: [Testing](https://code.visualstudio.com/docs/debugtest/testing)
参考: [VSCodeのPython拡張機能でテストカバレッジ表示機能が追加されました](https://dev.classmethod.jp/articles/python-vscode-test-coverage-view/)


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.runAction</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター内の「実行」アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター内のテストされる関数の行番号の左に表示される再生ボタンアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.iconErrored</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テストエクスプローラーの「エラー」アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのテストエクスプローラーでエラーになったテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.iconFailed</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テストエクスプローラーの「失敗」アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのテストエクスプローラーで失敗したテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.iconPassed</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テストエクスプローラーの「成功」アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのテストエクスプローラーで成功したテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.iconQueued</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テストエクスプローラーの「待機中」アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのテストエクスプローラーで実行待ちのテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.iconUnset</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テストエクスプローラーの「未実行」アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのテストエクスプローラーでまだ実行されていないテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.iconSkipped</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テストエクスプローラーの「スキップ」アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのテストエクスプローラーでスキップされたテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.iconErrored.retired</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">古くなった「エラー」アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのテストエクスプローラーでコード変更後、再実行されていないエラー状態のテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.iconFailed.retired</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">古くなった「失敗」アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのテストエクスプローラーでコード変更後、再実行されていない失敗状態のテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.iconPassed.retired</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">古くなった「成功」アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのテストエクスプローラーでコード変更後、再実行されていない成功状態のテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.iconQueued.retired</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">古くなった「待機中」アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのテストエクスプローラーでコード変更後、再実行されていない待機状態のテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.iconUnset.retired</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">古くなった「未実行」アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのテストエクスプローラーでコード変更後、再実行されていない未実行のテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.iconSkipped.retired</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">古くなった「スキップ」アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのテストエクスプローラーでコード変更後、再実行されていないスキップ状態のテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.peekBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビューのボーダーと矢印の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テスト結果を表示するエディター内のピークビュー(<code>Alt</code> + <code>F12</code>で表示)の枠線・矢印</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.peekHeaderBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ピークビューのボーダーと矢印の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テスト結果を表示するエディター内のピークビュー(<code>Alt</code> + <code>F12</code>で表示)のヘッダー背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.message.error.lineBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インライン表示されるエラーメッセージ横のマージン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター内のエラー部分の右に表示されるテストエラーメッセージの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.message.info.decorationForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インライン表示されるテスト情報メッセージの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター内のエラー部分の右に表示されるテスト情報メッセージのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.message.info.lineBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インライン表示される情報メッセージ横のマージン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター内のエラー部分の右に表示されるテスト情報メッセージの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.messagePeekBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ログメッセージをピーク表示する際のボーダーと矢印の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テストログメッセージのエディター内のピークビューの枠線・矢印</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.messagePeekHeaderBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ログメッセージをピーク表示する際のヘッダー背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テストログメッセージのエディター内のピークビューのヘッダー背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.coveredBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カバレッジが取れたテキストの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「カバレッジ付きで実行（Run Test with Coverage）」を実行したとき、コードカバレッジでカバーされたエディター内の行の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.coveredBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カバレッジが取れたテキストのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「カバレッジ付きで実行（Run Test with Coverage）」を実行したとき、コードカバレッジでカバーされたエディター内の行の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.coveredGutterBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カバレッジが取れた範囲のガター色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「カバレッジ付きで実行（Run Test with Coverage）」を実行したとき、コードカバレッジでカバーされたエディター内の行の左端マーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.uncoveredBranchBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カバーされていない分岐に表示されるウィジェットの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カバレッジが取れていない条件分岐を示すウィジェットの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.uncoveredBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カバレッジが取れていないテキストの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「カバレッジ付きで実行（Run Test with Coverage）」を実行したとき、コードカバレッジでカバーされていないエディター内の行の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.uncoveredBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カバレッジが取れていないテキストのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「カバレッジ付きで実行（Run Test with Coverage）」を実行したとき、コードカバレッジでカバーされていないエディター内の行の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.uncoveredGutterBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カバレッジが取れていない範囲のガター色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">「カバレッジ付きで実行（Run Test with Coverage）」を実行したとき、コードカバレッジでカバーされていないエディター内の行の左端マーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.coverCountBadgeBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">実行回数を示すバッジの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カバレッジレポートの実行回数バッジの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.coverCountBadgeForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">実行回数を示すバッジの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">カバレッジレポートの実行回数バッジのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.message.error.badgeBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インライン表示されるテストエラーメッセージのバッジ背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テストエラーメッセージのバッジの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.message.error.badgeBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インライン表示されるテストエラーメッセージのバッジボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テストエラーメッセージのバッジの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>testing.message.error.badgeForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インライン表示されるテストエラーメッセージのバッジ文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テストエラーメッセージのバッジのテキスト</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Welcome page colors(ウェルカムページカラー)</b></summary><br>


**Welcome page colors** は、VSCode起動時に表示されるウェルカムページに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>welcomePage.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウェルカムページの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウェルカムページ全体の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>welcomePage.progress.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウェルカムページのプログレスバーの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウェルカムページに表示される進捗バーの前景部分</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>welcomePage.progress.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウェルカムページのプログレスバーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウェルカムページに表示される進捗バーの背景部分</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>welcomePage.tileBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウェルカムページのタイルの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウェルカムページに並ぶ各機能紹介タイルの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>welcomePage.tileHoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウェルカムページのタイルのホバー時背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">機能紹介タイルにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>welcomePage.tileBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウェルカムページのタイルのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">機能紹介タイルの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>walkThrough.embeddedEditorBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インタラクティブプレイグラウンドの埋め込みエディターの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チュートリアル内に埋め込まれたコードエディターの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>walkthrough.stepTitle.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ウォークスループ各ステップの見出しの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チュートリアルの各手順の見出しテキスト</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Git colors(Gitカラー)</b></summary><br>


**Git colors** は、Git関連の装飾に関する色設定である。サイドバーのエクスプローラーやソース管理ビューに使用される。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>gitDecoration.addedResourceForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">追加されたGitリソースの色（ファイルラベルやSCMビューレットで使用）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーやソース管理ビューで新規追加されたファイル名の文字色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>gitDecoration.modifiedResourceForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更されたGitリソースの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーやソース管理ビューで変更されたファイル名の文字色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>gitDecoration.deletedResourceForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">削除されたGitリソースの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーやソース管理ビューで削除されたファイル名の文字色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>gitDecoration.renamedResourceForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">リネーム・コピーされたGitリソースの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーやソース管理ビューでリネームされたファイル名の文字色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>gitDecoration.stageModifiedResourceForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ステージ済み変更の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ソース管理ビューでステージされた変更ファイル名の文字色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>gitDecoration.stageDeletedResourceForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ステージ済み削除の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ソース管理ビューでステージされた削除ファイル名の文字色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>gitDecoration.untrackedResourceForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">未追跡のGitリソースの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エクスプローラーやソース管理ビューで未追跡（Untracked）ファイル名の文字色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>gitDecoration.ignoredResourceForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">無視されたGitリソースの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>.gitignore</code> で無視されているファイル名の文字色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>gitDecoration.conflictingResourceForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コンフリクトしているGitリソースの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">マージコンフリクトが発生しているファイル名の文字色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>gitDecoration.submoduleResourceForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サブモジュールリソースの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Gitサブモジュールのフォルダー名の文字色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>git.blame.editorDecorationForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">blame表示のエディター装飾色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター行末に表示されるGit blame情報（最終変更者など）のテキスト</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Source Control Graph colors(ソースコントロールグラフカラー)</b></summary><br>


**Source Control Graph colors** は、サイドバーのソース管理ビュー(`Ctrl`+`Shift`+`G`)に表示されるコミット履歴グラフ(GRAPH)に関する色設定である。
参考:


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>scmGraph.historyItemHoverLabelForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">履歴項目ホバー時のラベルの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コミット履歴グラフでコミット項目にホバーしたときのポップアップのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>scmGraph.foreground1</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ソースコントロールグラフの色（1）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コミット履歴グラフの1本目のブランチラインの色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>scmGraph.foreground2</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ソースコントロールグラフの色（2）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コミット履歴グラフの2本目のブランチラインの色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>scmGraph.foreground3</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ソースコントロールグラフの色（3）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コミット履歴グラフの3本目のブランチラインの色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>scmGraph.foreground4</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ソースコントロールグラフの色（4）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コミット履歴グラフの4本目のブランチラインの色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>scmGraph.foreground5</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ソースコントロールグラフの色（5）</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コミット履歴グラフの5本目のブランチラインの色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>scmGraph.historyItemHoverAdditionsForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">履歴項目ホバー時の追加行数の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コミット履歴グラフでコミット項目にホバーしたときのポップアップに表示される「+N」のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>scmGraph.historyItemHoverDeletionsForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">履歴項目ホバー時の削除行数の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コミット履歴グラフでコミット項目にホバーしたときのポップアップに表示される「-N」のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>scmGraph.historyItemRefColor</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">履歴項目の参照（ブランチ・タグ）の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コミット履歴グラフに表示されるブランチ名やタグ名のラベル色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>scmGraph.historyItemRemoteRefColor</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">履歴項目のリモート参照の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コミット履歴グラフに表示されるリモートブランチ名のラベル色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>scmGraph.historyItemBaseRefColor</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">履歴項目のベース参照の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コミット履歴グラフに表示されるベースブランチ名のラベル色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>scmGraph.historyItemHoverDefaultLabelForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">履歴項目ホバー時のデフォルトラベルの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コミット項目にホバーしたときのポップアップの標準テキスト色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>scmGraph.historyItemHoverDefaultLabelBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">履歴項目ホバー時のデフォルトラベルの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コミット項目にホバーしたときのポップアップの標準背景色</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Settings Editor colors(設定エディターカラー)</b></summary><br>


**Settings Editor colors** は、コマンドパレットで`Preferences: Open Settings (UI)` で開けるGUI設定エディターに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.headerForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">セクション見出しまたはアクティブなタイトルの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面の「エディター」などのセクション見出しのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.modifiedItemIndicator</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変更された設定を示す線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デフォルト値から変更した設定項目の左に表示される縦線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.dropdownBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ドロップダウンの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面のドロップダウン選択欄の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.dropdownForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ドロップダウンの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面のドロップダウン選択欄のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.dropdownBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ドロップダウンのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面のドロップダウン選択欄の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.dropdownListBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ドロップダウンリストのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面のドロップダウンを開いたときの選択肢リストの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.checkboxBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チェックボックスの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面のチェックボックスの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.checkboxForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チェックボックスの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面のチェックボックスのチェックマーク</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.checkboxBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チェックボックスのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面のチェックボックスの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.rowHoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時の設定行の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定項目の行にホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.textInputBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テキスト入力ボックスの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面の文字列入力欄の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.textInputForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テキスト入力ボックスの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面の文字列入力欄のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.textInputBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テキスト入力ボックスのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面の文字列入力欄の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.numberInputBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">数値入力ボックスの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面の数値入力欄の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.numberInputForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">数値入力ボックスの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面の数値入力欄のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.numberInputBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">数値入力ボックスのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面の数値入力欄の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.focusedRowBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォーカス中の設定行の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">キーボード操作によって選択された設定項目の行の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.focusedRowBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォーカス中の設定行の上下ボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">キーボード操作によって選択された設定項目の行の上下の線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.headerBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ヘッダーコンテナのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面上部のヘッダー部分の下の境界線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.sashBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定エディターの分割ビューのサッシュ（境界線）の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>settings.settingsHeaderHoverForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">セクション見出しまたはホバー中タイトルの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">設定画面のセクション見出しにホバーしたときのテキスト色</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Breadcrumbs colors(ブレッドクラムカラー)</b></summary><br>


**Breadcrumbs colors** は、タブとエディタの間にあるどのファイルを開いているかを階層構造で示すブレッドクラムナビゲーションに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>breadcrumb.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ブレッドクラム項目の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター上部に表示されるファイルパスやシンボル階層のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>breadcrumb.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ブレッドクラム項目の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ブレッドクラム全体の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>breadcrumb.focusForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォーカス中のブレッドクラム項目の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー・キーボード操作でフォーカスされたブレッドクラム項目のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>breadcrumb.activeSelectionForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中のブレッドクラム項目の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">クリックして選択中のブレッドクラム項目のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>breadcrumbPicker.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ブレッドクラム項目ピッカーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ブレッドクラムをクリックして開くドロップダウンの背景</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Snippets colors(スニペットカラー)</b></summary><br>


**Snippets colors** は、入力補完リストに出てくる、スニペット（予め登録していたコード定型文）に関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.snippetTabstopHighlightBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スニペットのタブストップのハイライト背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スニペット展開後、Tabキーで移動可能な途中の入力箇所（登録したスニペット内の<code>$1</code> や <code>$2</code> など）の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.snippetTabstopHighlightBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スニペットのタブストップのハイライトボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スニペット展開後、Tabキーで移動可能な途中の入力箇所（登録したスニペット内の<code>$1</code> や <code>$2</code> など）の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.snippetFinalTabstopHighlightBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スニペットの最終タブストップのハイライト背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スニペット入力の最後にカーソルが移動する箇所の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>editor.snippetFinalTabstopHighlightBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スニペットの最終タブストップのハイライトボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スニペット入力の最後にカーソルが移動する箇所の枠線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Symbol Icons colors(シンボルアイコンカラー)</b></summary><br>


**Symbol Icons colors** は、サイドバーのエクスプローラーの最下部にあるアウトラインビュー、ブレッドクラムナビゲーション、サジェストウィジェットに表示されるシンボルアイコンに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.arrayForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">配列シンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される配列変数のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.booleanForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">真偽値シンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される真偽値変数のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.classForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">クラスシンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるクラスのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.colorForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">色シンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">CSSファイルなどで色を表すシンボルのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.constantForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">定数シンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される定数のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.constructorForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コンストラクタシンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるコンストラクタのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.enumeratorForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">列挙型シンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるenum（列挙型）のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.enumeratorMemberForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">列挙型メンバーシンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるenumメンバーのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.eventForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">イベントシンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるイベントのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.fieldForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フィールドシンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるクラスのフィールドのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.fileForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ファイルシンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サジェストウィジェットに表示されるファイルのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.folderForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォルダーシンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サジェストウィジェットに表示されるフォルダーのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.functionForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">関数シンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される関数のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.interfaceForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">インターフェースシンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるインターフェースのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.keyForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">キーシンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">JSONファイルなどのキーを表すシンボルのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.keywordForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">キーワードシンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サジェストウィジェットに表示される言語キーワードのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.methodForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">メソッドシンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるメソッドのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.moduleForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">モジュールシンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるモジュールのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.namespaceForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">名前空間シンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される名前空間のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.nullForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">nullシンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サジェストウィジェットに表示される <code>null</code> のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.numberForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">数値シンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される数値変数のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.objectForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">オブジェクトシンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるオブジェクト変数のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.operatorForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">演算子シンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サジェストウィジェットに表示される演算子のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.packageForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">パッケージシンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるパッケージのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.propertyForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">プロパティシンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるプロパティのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.referenceForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">参照シンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される参照のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.snippetForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">スニペットシンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サジェストウィジェットに表示されるスニペットのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.stringForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">文字列シンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される文字列変数のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.structForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">構造体シンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される構造体のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.textForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">テキストシンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サジェストウィジェットに表示されるテキストのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.typeParameterForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">型パラメータシンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるジェネリック型パラメータのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.unitForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">単位シンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される単位のアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>symbolIcon.variableForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">変数シンボルのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される変数のアイコン</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Debug Icons colors(デバッグアイコンカラー)</b></summary><br>


**Debug Icons colors** は、デバッグ関連のアイコンに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugIcon.breakpointForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ブレークポイントのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディター左端に設置したブレークポイントのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugIcon.breakpointDisabledForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">無効化されたブレークポイントのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">一時的に無効化したブレークポイントのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugIcon.breakpointUnverifiedForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">未検証のブレークポイントのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッガーがまだ確認していないブレークポイントのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugIcon.breakpointCurrentStackframeForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">現在のブレークポイントスタックフレームのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中に現在停止しているスタックフレームのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugIcon.breakpointStackframeForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">全てのブレークポイントスタックフレームのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグ中のコールスタック上にあるブレークポイントのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugIcon.startForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグツールバーの「開始」アイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>F5</code>でデバッグを実行したときに右上に現れるデバッグツールバーの再生ボタンアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugIcon.pauseForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグツールバーの「一時停止」アイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>F5</code>でデバッグを実行したときに右上に現れるデバッグツールバーの一時停止ボタンアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugIcon.stopForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグツールバーの「停止」アイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>F5</code>でデバッグを実行したときに右上に現れるデバッグツールバーの停止ボタンアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugIcon.disconnectForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグツールバーの「切断」アイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>F5</code>でデバッグを実行したときに右上に現れるデバッグツールバーの切断ボタンアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugIcon.restartForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグツールバーの「再起動」アイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>F5</code>でデバッグを実行したときに右上に現れるデバッグツールバーの再起動ボタンアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugIcon.stepOverForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグツールバーの「ステップオーバー」アイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>F5</code>でデバッグを実行したときに右上に現れるデバッグツールバーの次の行に進むボタンアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugIcon.stepIntoForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグツールバーの「ステップイン」アイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>F5</code>でデバッグを実行したときに右上に現れるデバッグツールバーの関数内部に入るボタンアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugIcon.stepOutForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグツールバーの「ステップアウト」アイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>F5</code>でデバッグを実行したときに右上に現れるデバッグツールバーの関数から抜けるボタンアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugIcon.continueForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグツールバーの「続行」アイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>F5</code>でデバッグを実行したときに右上に現れるデバッグツールバーの次のブレークポイントまで実行するボタンアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugIcon.stepBackForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグツールバーの「ステップバック」アイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>F5</code>でデバッグを実行したときに右上に現れるデバッグツールバーの1ステップ前に戻るボタンアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugConsole.infoForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグREPLコンソールの情報メッセージの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>F5</code>でデバッグを実行したときにエディターの下のパネルのデバッグコンソールに表示される情報メッセージのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugConsole.warningForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグREPLコンソールの警告メッセージの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>F5</code>でデバッグを実行したときにエディターの下のパネルのデバッグコンソールに表示される警告メッセージのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugConsole.errorForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグREPLコンソールのエラーメッセージの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>F5</code>でデバッグを実行したときにエディターの下のパネルのデバッグコンソールに表示されるエラーメッセージのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugConsole.sourceForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグREPLコンソールのソースファイル名の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>F5</code>でデバッグを実行したときにエディターの下のパネルのデバッグコンソールに表示される出力元ファイル名のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>debugConsoleInputIcon.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">デバッグコンソール入力マーカーアイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>F5</code>でデバッグを実行したときにエディターの下のパネルのデバッグコンソールの入力欄に表示される <code>></code> のようなマーカーアイコン</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Notebook colors(ノートブックカラー)</b></summary><br>


**Notebook colors** は、Jupyter Notebookなどのノートブックエディターに関する色設定である。Notebookは、拡張機能から「Jupyter」をインストールし、ipynbファイルを作成することで表示される。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebook.editorBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ノートブックの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ノートブックエディター全体の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebook.cellBorderColor</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ノートブックセルのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">各セルを囲む枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebook.cellHoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時のセルの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">セルにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebook.cellInsertionIndicator</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">セル挿入インジケーターの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">セルとセルの間にマウスを置いたときに表示される挿入位置の線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebook.cellStatusBarItemHoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ノートブックセルステータスバー項目のホバー時の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">セル下部のステータスバー項目にホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebook.cellToolbarSeparator</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">セル下部ツールバーの区切り線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">セル下部に表示されるアイコン群の間の区切り線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebook.cellEditorBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ノートブックセルエディターの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">セル内のコード入力部分の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebook.focusedCellBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォーカス中のセルの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">編集モードでフォーカスされているセルの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebook.focusedCellBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォーカス中のセルのフォーカスインジケーターのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォーカスされているセルを示す枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebook.focusedEditorBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ノートブックセルエディターのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">フォーカスされているセル内のコード入力部分の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebook.inactiveFocusedCellBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">主フォーカスがエディター外にあるときのセルの上下ボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebook.inactiveSelectedCellBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">複数セルが選択されているときのセルのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">複数のセルをまとめて選択しているときの各セルの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebook.outputContainerBackgroundColor</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ノートブック出力コンテナの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コード実行結果が表示される部分の背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebook.outputContainerBorderColor</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ノートブック出力コンテナのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コード実行結果が表示される部分の枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebook.selectedCellBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中のセルの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コマンドモードで選択されているセルの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebook.selectedCellBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中（フォーカスなし）のセルの上下ボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択されているがフォーカスはされていないセルの上下の線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebook.symbolHighlightBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ハイライトされたセルの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アウトラインなどから移動した先のセルのハイライト背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebookScrollbarSlider.activeBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">クリック時のノートブックスクロールバースライダーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ノートブックのスクロールバーにあるスライダーをクリックしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebookScrollbarSlider.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ノートブックスクロールバースライダーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ノートブックのスクロールバーにあるスライダーの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebookScrollbarSlider.hoverBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ホバー時のノートブックスクロールバースライダーの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ノートブックのスクロールバーにあるスライダーにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebookStatusErrorIcon.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">セルステータスバーのエラーアイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">セル実行がエラーになったときのステータスバーのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebookStatusRunningIcon.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">セルステータスバーの実行中アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">セルが実行中のときのステータスバーのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebookStatusSuccessIcon.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">セルステータスバーの成功アイコンの色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">セル実行が成功したときのステータスバーのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>notebookEditorOverviewRuler.runningCellForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">概要ルーラーの実行中セル装飾の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ノートブック右端のスクロールバーの下に重なっている、概要ルーラーで実行中セルを示すマーカー</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Chart colors(チャートカラー)</b></summary><br>


**Chart colors** は、VSCode内のチャート表示に関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>charts.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャート内テキストのコントラスト色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャートに表示されるラベルや数値のテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>charts.lines</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャート内の線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">グラフの罫線やグリッド線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>charts.red</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャート内の赤色要素の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">グラフ内で赤色に割り当てられたデータ系列</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>charts.blue</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャート内の青色要素の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">グラフ内で青色に割り当てられたデータ系列</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>charts.yellow</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャート内の黄色要素の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">グラフ内で黄色に割り当てられたデータ系列</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>charts.orange</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャート内の橙色要素の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">グラフ内で橙色に割り当てられたデータ系列</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>charts.green</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャート内の緑色要素の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">グラフ内で緑色に割り当てられたデータ系列</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>charts.purple</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャート内の紫色要素の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">グラフ内で紫色に割り当てられたデータ系列</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>chart.line</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャートの線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">グラフの折れ線部分の色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>chart.axis</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャートの軸の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">グラフのX軸・Y軸の線の色</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>chart.guide</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">チャートのガイド線の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">グラフの目盛りを示す補助線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Ports colors(ポートカラー)</b></summary><br>


**Ports colors** は、ポート転送機能に関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>ports.iconRunningProcessForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">実行中プロセスが関連付けられたポートのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エディターの下にあるパネルの「ポート」で実行中プロセスがあるポートのアイコン</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Comments View colors(コメントビューカラー)</b></summary><br>


**Comments View colors** は、コメントビューに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>commentsView.resolvedIcon</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">解決済みコメントのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コメントビューで解決済みとされたコメントのアイコン</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>commentsView.unresolvedIcon</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">未解決コメントのアイコン色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">コメントビューで未解決のコメントのアイコン</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Action Bar colors(アクションバーカラー)</b></summary><br>


**Action Bar colors** は、アクションバーに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>actionBar.toggledBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">アクションバーでトグルされたアクション項目の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">オン/オフを切り替えるトグルボタンが有効時の背景</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Simple Find Widget colors(シンプル検索ウィジェットカラー)</b></summary><br>


**Simple Find Widget colors** は、エディタ上の通常の検索（Ctrl + F）ではなく、「出力（Output）パネル」や「デバッグコンソール（Debug Console）」の文字を検索するときのシンプル検索ウィジェットに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>simpleFindWidget.sashBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">サッシュ（境界線）のボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">シンプル検索ウィジェットのリサイズ用境界線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Gauge colors(ゲージカラー)</b></summary><br>


**Gauge colors** は、ゲージ表示に関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>gauge.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ゲージの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>gauge.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ゲージの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>gauge.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ゲージのボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>gauge.warningBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ゲージの警告時の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>gauge.warningForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ゲージの警告時の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>gauge.errorBackground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ゲージのエラー時の背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>gauge.errorForeground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ゲージのエラー時の文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"></td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Markdown(マークダウン)</b></summary><br>


**Markdown** は、Markdownのアラート（注釈ブロック）に関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>markdownAlert.note.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Markdownの「Note」アラートの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">mdファイル内に<code>> [!NOTE]</code> で書かれた注釈ブロックのプレビューのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>markdownAlert.tip.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Markdownの「Tip」アラートの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">mdファイル内に<code>> [!TIP]</code> で書かれた注釈ブロックのプレビューのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>markdownAlert.important.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Markdownの「Important」アラートの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">mdファイル内に<code>> [!IMPORTANT]</code> で書かれた注釈ブロックのプレビューのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>markdownAlert.warning.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Markdownの「Warning」アラートの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">mdファイル内に<code>> [!WARNING]</code> で書かれた注釈ブロックのプレビューのテキスト</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>markdownAlert.caution.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Markdownの「Caution」アラートの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">mdファイル内に<code>> [!CAUTION]</code> で書かれた注釈ブロックのプレビューのテキスト</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Agent Session colors(エージェントセッションカラー)</b></summary><br>


**Agent Session colors** は、AIエージェントセッションに関する色設定である。


<div style="overflow-x: auto; border-radius: 6px; margin: 10px 0;">
<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="width: 25%; text-align: left; padding: 12px; border: 1px solid #666; ">key名</th>
    <th style="width: 35%; text-align: left; padding: 12px; border: 1px solid #666; ">役割</th>
    <th style="width: 40%; text-align: left; padding: 12px; border: 1px solid #666; ">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>agentSessionReadIndicator.foreground</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">エージェントセッションの既読インジケーターの文字色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">AIエージェントとのセッション一覧で既読を示すマーカー</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>agentSessionSelectedBadge.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中のエージェントセッション項目のバッジボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">選択中のセッション項目に表示されるバッジの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>agentSessionSelectedUnfocusedBadge.border</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">ビューが非フォーカス時の選択中エージェントセッション項目のバッジボーダー色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">操作していないビューで選択中のセッション項目のバッジの枠線</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>agentStatusIndicator.background</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">タイトルバーのエージェントステータスインジケーターの背景色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">タイトルバーに表示されるAIエージェントの状態を示すアイコンの背景</td>
  </tr>
  <tr>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;"><code>aiCustomizationManagement.sashBorder</code></td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">Chat Customization Managementエディターの分割ビューのサッシュ（境界線）の色</td>
    <td style="word-break: break-word; text-align: left; padding: 12px; border: 1px solid #666;">AIカスタマイズ管理画面の2分割表示の境界線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>参考</b></summary><br>


- [VSCode Theme Color Reference](https://code.visualstudio.com/api/references/theme-color)
- [Visual Studio Code Color Theme Guide](https://sw27.net/vsc/color-theme-guide/index.ja.html)

</details>
