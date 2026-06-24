# vscode-theme-color-guide-ja

<details>
<summary><b>Contrast colors(コントラスト色)</b></summary><br>


**Contrast colors** は、VSCode のハイコントラストテーマ専用の設定で、UI 全体の要素に追加のボーダー（枠線）を付けることで、近視やディスプレイの発色が悪い環境での作業をサポートする。
`"type": "hc-black"`の時のみ適用され、通常のテーマでは基本的に使用されない。

<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>contrastBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">UI 全体の要素の周囲に追加ボーダーを表示し、要素同士の境界をはっきりさせる</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウインドウ、ボタン、バッジ</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>contrastActiveBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在フォーカス中・選択中の**アクティブな要素**の周囲に追加のボーダーを表示し、他の要素と区別しやすくする</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テキストボックス、タブやリストの項目のクリックによるフォーカス、エディター上の単語を選択</td>
  </tr>
</tbody>
</table>
---


</details>
<details>
<summary><b>Base colors(ベースカラー)</b></summary><br>


**Base colors** は、VSCode UI 全体に共通して使われるデフォルトの色設定である。各コンポーネントが独自の色を持たない場合のフォールバックとして機能する。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>focusBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォーカスされた要素の全体的な境界線の色。各コンポーネントで上書きされない場合に使用するフォールバック値</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">クリックによるフォーカス中のテキストボックス、リストの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">UI 全体のデフォルト文字色。各コンポーネントで上書きされない場合に使用するフォールバック値</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのテキスト、メニュー項目</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>disabledForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">無効化された要素の文字色。各コンポーネントで上書きされない場合に使用するフォールバック値</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>widget.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内ウィジェットの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Find(<code>Ctrl</code>+<code>F</code>)やQuick Pick(<code>Ctrl</code>+<code>Shift</code>+<code>P</code>) ダイアログの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>widget.shadow</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内ウィジェットの影の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Find(<code>Ctrl</code>+<code>F</code>)やQuick Pick(<code>Ctrl</code>+<code>Shift</code>+<code>P</code>) ダイアログの影</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>selection.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ワークベンチ内のテキスト選択時の背景色。エディターやターミナル内の選択には適用されない</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>descriptionForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">補足情報として表示される説明テキストの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>errorForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラーメッセージ全体の文字色。各コンポーネントで上書きされない場合に使用するフォールバック値</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディタ上のFind(<code>Ctrl</code>+<code>F</code>)でヒットしない文字列を検索したときに表示される"結果はありません。"</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>icon.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ワークベンチ内のアイコンのデフォルトカラー</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーやツールバーのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>sash.hoverBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ドラッグ可能なサッシュ（ペイン間の境界線）のクリック、ドラッグ時の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーとエディター間の境界線をクリックまたはドラッグしたとき(参考: [VS Code tips — The sash hover border](https://www.youtube.com/watch?v=eU0zxM5kpoc))</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Window border(ウィンドウボーダー)</b></summary><br>


**Window border** は、VSCode ウィンドウ自体の境界線の色設定である。アクティブ（フォーカス中）と非アクティブ（フォーカスなし）で色を切り替えられる。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>window.activeBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブ（フォーカス中）ウィンドウの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在操作中の VSCode ウィンドウの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>window.inactiveBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非アクティブ（フォーカスなし）ウィンドウの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">背面にある VSCode ウィンドウの枠線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Text colors(テキストカラー)</b></summary><br>


**Text colors** は、ウェルカムページなどのテキストドキュメント内で使われる色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>textBlockQuote.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ブロック引用の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウェルカムページの引用ブロック背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>textBlockQuote.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ブロック引用の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウェルカムページの引用ブロック左の縦線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>textCodeBlock.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コードブロックの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウェルカムページのインラインコード背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>textLink.activeForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">クリック時・ホバー時のリンクの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウェルカムページのリンクをクリック・ホバーしたとき</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>textLink.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通常状態のリンクの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウェルカムページのリンクテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>textPreformat.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">整形済みテキスト（pre）の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウェルカムページのキーボードショートカット表記</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>textPreformat.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">整形済みテキスト（pre）の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウェルカムページのキーボードショートカット表記の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>textPreformat.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">整形済みテキスト（pre）の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウェルカムページのキーボードショートカット表記の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>textSeparator.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テキスト区切り線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウェルカムページのセクション間の区切り線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Action colors(アクションカラー)</b></summary><br>


**Action colors** は、ワークベンチ全体のアクション操作に関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>toolbar.hoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ツールバーのアイコンをホバーしたときの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">タブの欄の一番右にある"エディターを右に分割"や"その他の操作..."のアイコンにホバーしたとき</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>toolbar.hoverOutline</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ツールバーのアイコンをホバーしたときのアウトライン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">タブの欄の一番右にある"エディターを右に分割"や"その他の操作..."のアイコンにホバーしたときの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>toolbar.activeBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ツールバーのアイコンをクリック押下中の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">タブの欄の一番右にある"エディターを右に分割"や"その他の操作..."のアイコンをクリックして押し込んでいるとき</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorActionList.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクションリストの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">間違ったコードを書いたときに出てくるダイアログ("式が必要です。ts(1109)"などが表示されるダイアログ)</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorActionList.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクションリストの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">間違ったコードを書いたときに出てくるダイアログ("式が必要です。ts(1109)"などが表示されるダイアログ)</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorActionList.focusForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクションリストのフォーカス中の項目の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">間違ったコードを書いたときに出てくるダイアログ("式が必要です。ts(1109)"などが表示されるダイアログ)</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorActionList.focusBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクションリストのフォーカス中の項目の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">間違ったコードを書いたときに出てくるダイアログ("式が必要です。ts(1109)"などが表示されるダイアログ)</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Button control(ボタンコントロール)</b></summary><br>


**Button control** は、エクスプローラーの「フォルダーを開く」、ソース管理の「リポジトリを初期化する」ボタンなど、ボタンウィジェットに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>button.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ボタンの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「フォルダーを開く」や「リポジトリを初期化する」ボタンの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>button.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ボタンの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「フォルダーを開く」や「リポジトリを初期化する」ボタンのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>button.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ボタンの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「フォルダーを開く」や「リポジトリを初期化する」ボタンの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>button.separator</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ドロップダウン付きボタンの区切り線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能の詳細画面の「アンインストール」ボタンの区切り線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>button.hoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時のボタンの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「フォルダーを開く」や「リポジトリを初期化する」ボタンにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>button.secondaryForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">セカンダリボタンの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">キャンセルなどの補助的なボタンのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>button.secondaryBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">セカンダリボタンの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">キャンセルなどの補助的なボタンの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>button.secondaryHoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時のセカンダリボタンの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">セカンダリボタンにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>button.secondaryBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">セカンダリボタンの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">セカンダリボタンの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>checkbox.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チェックボックスの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能の詳細画面の「自動更新」のチェックボックスの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>checkbox.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チェックボックスのマーク</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能の詳細画面の「自動更新」のチェックボックスのチェックマーク</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>checkbox.disabled.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">無効化されたチェックボックスの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">グレーアウトされたチェックボックスの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>checkbox.disabled.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">無効化されたチェックボックスのマーク</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">グレーアウトされたチェックボックスのチェックマーク</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>checkbox.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チェックボックスの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能の詳細画面の「自動更新」のチェックボックスの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>checkbox.selectBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中の要素内にあるチェックボックスの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面(<code>Ctrl</code>+<code>,</code>)でリスト項目が選択されているときのチェックボックス背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>checkbox.selectBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中の要素内にあるチェックボックスの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面(<code>Ctrl</code>+<code>,</code>)でリスト項目が選択されているときのチェックボックス枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>radio.activeForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブなラジオボタンの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>radio.activeBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブなラジオボタンの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>radio.activeBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブなラジオボタンの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>radio.inactiveForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非アクティブなラジオボタンの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>radio.inactiveBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非アクティブなラジオボタンの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>radio.inactiveBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非アクティブなラジオボタンの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>radio.inactiveHoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非アクティブなラジオボタンのホバー時の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Dropdown control(ドロップダウンコントロール)</b></summary><br>


**Dropdown control** は、統合ターミナルや出力パネルなどのドロップダウンウィジェットに関する色設定である。なお、macOS では現在ドロップダウンコントロールは使用されていない。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>dropdown.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ドロップダウンの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面(<code>Ctrl</code>+<code>,</code>)の<code>window.titleBarStyle</code>や出力(<code>Ctrl</code>+<code>Shift</code>+<code>U</code>)のドロップダウンの選択欄の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>dropdown.listBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ドロップダウンリストの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面(<code>Ctrl</code>+<code>,</code>)の<code>window.titleBarStyle</code>や出力(<code>Ctrl</code>+<code>Shift</code>+<code>U</code>)のドロップダウンを開いたときの選択肢リストの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>dropdown.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ドロップダウンの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面(<code>Ctrl</code>+<code>,</code>)の<code>window.titleBarStyle</code>や出力(<code>Ctrl</code>+<code>Shift</code>+<code>U</code>)のドロップダウンの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>dropdown.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ドロップダウンの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面(<code>Ctrl</code>+<code>,</code>)の<code>window.titleBarStyle</code>や出力(<code>Ctrl</code>+<code>Shift</code>+<code>U</code>)のドロップダウンの選択中の項目のテキスト</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Input control(インプットコントロール)</b></summary><br>


**Input control** は、検索ビューや Find/Replace ダイアログなどの入力フィールドに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>input.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">入力ボックスの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">検索ビューの入力フィールド背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>input.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">入力ボックスの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">検索ビューの入力フィールドの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>input.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">入力ボックスの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">検索ビューの入力テキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>input.placeholderForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">入力ボックスのプレースホルダーの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">検索ビューの「検索(Find)」などのヒントテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inputOption.activeBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">入力フィールドのアクティブなオプションの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">検索ビューの「大文字と小文字を区別」ボタンのオン時の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inputOption.activeBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">入力フィールドのアクティブなオプションの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">検索ビューの「大文字と小文字を区別」ボタンのオン時の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inputOption.activeForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">入力フィールドのアクティブなオプションの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">検索ビューの「大文字と小文字を区別」ボタンのオン時のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inputOption.hoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">入力フィールドのオプションのホバー時の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">検索ビューの「大文字と小文字を区別」ボタンにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inputValidation.errorBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラー時のバリデーションメッセージの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">正規表現を使用して<code>sdd\</code>を検索したときのエラーメッセージの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inputValidation.errorForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラー時のバリデーションメッセージの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">正規表現を使用して<code>sdd\</code>を検索したときのエラーメッセージのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inputValidation.errorBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラー時のバリデーションメッセージの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">正規表現を使用して<code>sdd\</code>を検索したときのエラーメッセージの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inputValidation.infoBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">情報レベルのバリデーションメッセージの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inputValidation.infoForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">情報レベルのバリデーションメッセージの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inputValidation.infoBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">情報レベルのバリデーションメッセージの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inputValidation.warningBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告レベルのバリデーションメッセージの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inputValidation.warningForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告レベルのバリデーションメッセージの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inputValidation.warningBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告レベルのバリデーションメッセージの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Scrollbar control(スクロールバーコントロール)</b></summary><br>


**Scrollbar control** は、エディターの一番右にあるスクロールバーに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>scrollbar.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スクロールバーの可動領域のトラック（レール部分）の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターのスクロールバー背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>scrollbar.shadow</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スクロール中であることを示すスライダーの影の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スクロール位置がトップ以外のときのエディター上部の影</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>scrollbarSlider.activeBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">クリック押下中のスクロールバースライダーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スクロールバーにあるスライダーをクリックして押し込んでいるときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>scrollbarSlider.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スクロールバースライダーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スクロールバーにあるスライダーの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>scrollbarSlider.hoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時のスクロールバースライダーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スクロールバーにあるスライダーにホバーしたときの背景</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Badge(バッジ)</b></summary><br>


**Badge** は、拡張機能の発行元(例: `ms-vscode`)などを表示する小さなアイコンに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>badge.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">バッジの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能の発行元(例: <code>ms-vscode</code>)のバッジのチェックマーク</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>badge.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">バッジの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能の発行元(例: <code>ms-vscode</code>)のバッジの背景</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Progress bar(プログレスバー)</b></summary><br>


**Progress bar** は、長時間かかる処理中に表示されるプログレスバーに関する色設定である。

<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>progressBar.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">プログレスバーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能インストール中やファイル読み込み中のプログレスバー</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Lists and trees(リストとツリー)</b></summary><br>


**Lists and trees** は、ファイルエクスプローラーなどのリスト・ツリーUIに関する色設定である。アクティブなリスト/ツリーはキーボードフォーカスを持ち、非アクティブなものは持たない。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.activeSelectionBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブ時の選択中の項目の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーでフォーカスされた選択中のファイルの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.activeSelectionForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブ時の選択中の項目の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーでフォーカスされた選択中のファイル名のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.activeSelectionIconForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブ時の選択中の項目のアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーでフォーカスされた選択中のファイルアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.dropBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ドラッグ&ドロップ中の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーでファイルをドラッグして移動中の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.focusBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブ時のフォーカス中の項目の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーでキーボード操作によりフォーカスされたファイルの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.focusForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブ時のフォーカス中の項目の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーでキーボード操作によりフォーカスされたファイルのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.focusHighlightForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブ時のフォーカス中の項目の検索マッチハイライトの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">リスト内検索でフォーカス中の項目のマッチ部分のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.focusOutline</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブ時のフォーカス中の項目のアウトライン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーでキーボード操作によりフォーカスされたファイルの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.focusAndSelectionOutline</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブ時のフォーカスかつ選択中の項目のアウトライン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーでキーボード操作によるフォーカスと選択が重なった項目の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.highlightForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">リスト内検索のマッチハイライトの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーの検索でマッチした文字のテキスト色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.hoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時の項目の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーのファイルにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.hoverForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時の項目の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーのファイルにホバーしたときのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.inactiveSelectionBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非アクティブ時の選択中の項目の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーで非アクティブ(別ウィンドウ操作中)かつ選択中のファイルの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.inactiveSelectionForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非アクティブ時の選択中の項目の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーで非アクティブ(別ウィンドウ操作中)かつ選択中のファイル名のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.inactiveSelectionIconForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非アクティブ時の選択中の項目のアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーで非アクティブ(別ウィンドウ操作中)かつ選択中のファイルアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.inactiveFocusBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非アクティブ時のフォーカス中の項目の背景色（リストのみ対応）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーで非アクティブ(別ウィンドウ操作中)かつフォーカスされた項目の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.inactiveFocusOutline</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーで非アクティブ時のフォーカス中の項目のアウトライン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">リスト/ツリーで非アクティブ(別ウィンドウ操作中)かつフォーカスされた項目の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.invalidItemForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">無効な項目の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エクスプローラーで未解決のルートフォルダーのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.errorForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラーを含む項目の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラーのあるファイル・フォルダー名のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.warningForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告を含む項目の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告のあるファイル・フォルダー名のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>listFilterWidget.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">リスト内検索ウィジェットの入力テキストの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>listFilterWidget.outline</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">リスト内検索ウィジェットの入力テキストのアウトライン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>listFilterWidget.noMatchesOutline</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">リスト内検索ウィジェットでマッチなし時のアウトライン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>listFilterWidget.shadow</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">リスト内検索ウィジェットの影の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.filterMatchBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フィルタリングされたマッチ項目の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.filterMatchBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フィルタリングされたマッチ項目の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.deemphasizedForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非強調項目の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>list.dropBetweenBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">項目間へのドラッグ&ドロップ時の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ファイルを項目と項目の間にドロップするときの境界線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tree.indentGuidesStroke</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ツリーのアクティブなインデントガイドの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エクスプローラーのフォルダー階層を示すアクティブな縦線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tree.inactiveIndentGuidesStroke</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ツリーの非アクティブなインデントガイドの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エクスプローラーのフォルダー階層を示す非アクティブな縦線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tree.tableColumnsBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ツリーのテーブルカラムの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tree.tableOddRowsBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テーブルの奇数行の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Activity Bar(アクティビティバー)</b></summary><br>


**Activity Bar** は、VSCodeの左端（または右端）に縦に並んでいるアイコン群の列であり、サイドバーのビューを素早く切り替えるためのバーに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>activityBar.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティビティバー全体の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>activityBar.dropBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティビティバーへのドラッグ&ドロップ時の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>activityBar.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティビティバーのアイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>activityBar.inactiveForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティビティバーの非アクティブなアイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未選択のビューアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>activityBar.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティビティバーとサイドバーの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">左端のアクティビティバーとサイドバーの間の縦線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>activityBarBadge.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティビティバーの通知バッジの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティビティバーのアイコン右下にある通知数を示す丸いバッジの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>activityBarBadge.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティビティバーの通知バッジの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティビティバーのアイコン右下にある通知数を示す丸いバッジのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>activityBar.activeBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブなアイテムのインジケーターの縦線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中のビューアイコンの横のアクティブな縦線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>activityBar.activeBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブなアイテムのオプション背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中のビューアイコンの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>activityBar.activeFocusBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブなアイテムのフォーカス時の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>activityBarTop.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">上部配置時のアクティブなアイテムの文字・アイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティビティバーを上部に配置したときの選択中のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>activityBarTop.activeBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">上部配置時のアクティブなアイテムのフォーカス境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティビティバーを上部に配置したときの選択中アイコンの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>activityBarTop.inactiveForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">上部配置時の非アクティブなアイテムの文字・アイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティビティバーを上部に配置したときの未選択のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>activityBarTop.dropBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">上部配置時のドラッグ&ドロップ時の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティビティバーを上部に配置してアイコンをドラッグするときの境界線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>activityBarTop.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">上部・下部配置時のアクティビティバーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティビティバーを上部または下部に配置したときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>activityBarTop.activeBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">上部・下部配置時のアクティブなアイテムの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティビティバーを上部または下部に配置したときの選択中アイコンの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>activityWarningBadge.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告アクティビティバッジの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>activityWarningBadge.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告アクティビティバッジの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>activityErrorBadge.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラーアクティビティバッジの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>activityErrorBadge.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラーアクティビティバッジの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Profiles(プロファイル)</b></summary><br>


**Profiles** は、アクティビティバーの設定（歯車）アイコンの上に表示されるプロファイルバッジに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>profileBadge.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">プロファイルバッジの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定アイコン上に表示されるプロファイルバッジの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>profileBadge.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">プロファイルバッジの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定アイコン上に表示されるプロファイルバッジのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>profiles.sashBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">プロファイルエディターの分割ビューのサッシュ（境界線）の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">プロファイルエディターの2分割表示の間の境界線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Side Bar(サイドバー)</b></summary><br>


**Side Bar** は、ウィンドウ左側に位置するエクスプローラーや検索などのビューを格納するコンテナに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>sideBar.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバー全体の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>sideBar.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバー内のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>sideBar.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーとエディターを区切る境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーとエディターの間の縦線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>sideBar.dropBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーセクションへのドラッグ&ドロップ時の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーにファイルをドラッグしているときの背景（透過色）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>sideBarTitle.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのタイトルの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーの上部にある「エクスプローラー」などのタイトルテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>sideBarSectionHeader.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのセクションヘッダーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エクスプローラー内の「アウトライン」や「タイムライン」などのセクション見出しの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>sideBarSectionHeader.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのセクションヘッダーの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エクスプローラー内の「アウトライン」や「タイムライン」などのセクション見出しのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>sideBarSectionHeader.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのセクションヘッダーの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エクスプローラー内の「アウトライン」や「タイムライン」などのセクション見出しの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>sideBarActivityBarTop.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">上部配置したアクティビティバーとビューの間の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティビティバーを上部に配置したときのビューとの境界線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>sideBarTitle.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのタイトルの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーの上部にある「エクスプローラー」などのタイトル部分の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>sideBarTitle.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのタイトル下部の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーの上部にある「エクスプローラー」などのタイトルとビューを区切る下部の線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>sideBarStickyScroll.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのスティッキースクロールの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エクスプローラーでフォルダーをスクロールしたときに上部に固定される現在見ている場所の親フォルダーの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>sideBarStickyScroll.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのスティッキースクロールの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エクスプローラーでフォルダーをスクロールしたときに上部に固定される現在見ている場所の親フォルダー部分の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>sideBarStickyScroll.shadow</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのスティッキースクロールの影の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エクスプローラーでフォルダーをスクロールしたときに上部に固定される現在見ている場所の親フォルダー部分の影</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Minimap(ミニマップ)</b></summary><br>


**Minimap** は、エディタの右側に位置する現在のファイルのズームアウトしたものを表示する機能に関する色設定である。コマンドパレット（`Ctrl`+`Shift`+`P`）を開いて、「Toggle Minimap」と入力して実行することで表示される。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimap.findMatchHighlight</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ファイル内検索のマッチ箇所のハイライト色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップ上で検索ワードと一致した箇所のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimap.selectionHighlight</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター上の選択範囲のハイライト色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップ上の現在選択中のテキスト範囲のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimap.errorHighlight</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター上のエラー箇所のハイライト色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラーがある行のミニマップ上のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimap.warningHighlight</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター上の警告箇所のハイライト色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告がある行のミニマップ上のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimap.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップ全体の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimap.selectionOccurrenceHighlight</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中の文字列と同じ語が繰り返し出現する箇所のマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップ上の選択中の単語と一致する箇所のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimap.foregroundOpacity</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップ内に描画される前景要素の不透明度</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップに表示されるコードの縮小テキストの濃さ</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimap.infoHighlight</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">情報レベルのマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップ上の情報通知がある行のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimap.chatEditHighlight</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">保留中の編集領域の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">AI等のインライン編集で未確定の変更箇所のハイライト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimapSlider.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップスライダーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップ上の現在の表示範囲を示すものの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimapSlider.hoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時のミニマップスライダーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップの表示範囲枠にホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimapSlider.activeBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">クリック押下時のミニマップスライダーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップの表示範囲枠をクリックして押し込んでいるときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimapGutter.addedBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">追加された内容を示すミニマップガターの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Git差分で追加された行のミニマップ左端のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimapGutter.modifiedBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更された内容を示すミニマップガターの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Git差分で変更された行のミニマップ左端のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimapGutter.deletedBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">削除された内容を示すミニマップガターの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Git差分で削除された行のミニマップ左端のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorMinimap.inlineChatInserted</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インラインチャットで挿入されたコンテンツのマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">AIによって挿入されたコードのミニマップ上のマーカー</td>
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


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGroup.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">複数のエディターグループを区切る境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">画面分割した場合の複数のエディター間の境界線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGroup.dropBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターをドラッグ中の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">画面分割した場合のタブをドラッグしてエディタへ移動しているときのエディタの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGroupHeader.noTabsBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">シングルタブ表示時のエディターグループタイトルヘッダーの背景色（<code>"workbench.editor.showTabs": "single"</code> 設定時）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGroupHeader.tabsBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">タブコンテナの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGroupHeader.tabsBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">タブ有効時のタブコントロール下の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGroupHeader.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターグループヘッダーとエディターの間の境界線の色（ブレッドクラム有効時はその下）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGroup.emptyBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">空のエディターグループの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ファイルを開いていない空のエディターグループの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGroup.focusedEmptyBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォーカス中の空のエディターグループの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォーカスされている空のエディターグループの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGroup.dropIntoPromptForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ファイルドラッグ中に表示される案内テキストの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ファイルをエディター上にドラッグ・ドロップしようとするときに表示される「Shiftをホールドしてエディターにドロップする」という案内文のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGroup.dropIntoPromptBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ファイルドラッグ中に表示される案内テキストの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ファイルをエディター上にドラッグ・ドロップしようとするときに表示される「Shiftをホールドしてエディターにドロップする」という案内文の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGroup.dropIntoPromptBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ファイルドラッグ中に表示される案内テキストの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ファイルをエディター上にドラッグ・ドロップしようとするときに表示される「Shiftをホールドしてエディターにドロップする」という案内文の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.activeBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブなグループ内のアクティブタブの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在操作しているエディターグループで開いているタブの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.unfocusedActiveBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非アクティブなグループ内のアクティブタブの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在操作していないエディターグループで開いているタブの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.activeForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブなグループ内のアクティブタブの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在操作しているエディターグループで開いているタブのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">タブ同士を区切る境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">隣り合うタブの間の縦線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.activeBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブタブの下部境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在操作しているエディターグループで開いているタブの下線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.selectedBorderTop</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中タブの上部境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中のタブの上側に表示される線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.selectedBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中のタブの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>Shift</code>や<code>Ctrl</code>で複数選択したタブの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.selectedForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中のタブの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>Shift</code>や<code>Ctrl</code>で複数選択したタブののテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.dragAndDropBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">タブ間に挿入可能であることを示す境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">タブをドラッグして別タブの間に挿入できることを示す横線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.unfocusedActiveBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非アクティブなグループ内のアクティブタブの下部境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在操作していないエディターグループで開いているタブの下線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.activeBorderTop</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブタブの上部境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在操作しているエディターグループで開いているタブの上に表示される線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.unfocusedActiveBorderTop</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非アクティブなグループ内のアクティブタブの上部境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在操作していないエディターグループで開いているタブの上線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.lastPinnedBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">最後にピン留めされたタブの右側の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピン留めタブと未ピン留めタブを区切る縦線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.inactiveBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非アクティブタブの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在操作しているエディターグループで開いていないタブの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.unfocusedInactiveBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非フォーカスグループ内の非アクティブタブの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在操作していないエディターグループで開いていないタブの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.inactiveForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブなグループ内の非アクティブタブの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在操作しているエディターグループで開いていないタブのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.unfocusedActiveForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非アクティブなグループ内のアクティブタブの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在操作していないエディターグループで開いているタブのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.unfocusedInactiveForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非アクティブなグループ内の非アクティブタブの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在操作していないエディターグループで開いていないタブのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.hoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時のタブの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">タブにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.unfocusedHoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非フォーカスグループでホバー時のタブの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在操作していないエディターグループのタブにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.hoverForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時のタブの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">タブにホバーしたときのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.unfocusedHoverForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非フォーカスグループでホバー時のタブの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在操作していないエディターグループのタブにホバーしたときのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.hoverBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時のタブを強調する境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">タブにホバーしたときに表示される枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.unfocusedHoverBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非フォーカスグループでホバー時のタブを強調する境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在操作していないエディターグループのタブにホバーしたときの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.activeModifiedBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブグループ内の変更済み（未保存）アクティブタブの上部境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未保存の変更があり、現在操作しているタブの上部に表示される線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.inactiveModifiedBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブグループ内の変更済み（未保存）非アクティブタブの上部境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未保存の変更があり、現在操作していないタブの上部に表示される線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.unfocusedActiveModifiedBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非フォーカスグループ内の変更済み（未保存）アクティブタブの上部境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未保存の変更があり、現在操作していないエディターグループの開いているタブの上部に表示される線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>tab.unfocusedInactiveModifiedBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非フォーカスグループ内の変更済み（未保存）非アクティブタブの上部境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未保存の変更があり、現在操作していないエディターグループの開いていないタブの上部に表示される線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorPane.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">中央レイアウト時、エディターの左右に見えるエディターペインの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターを中央寄せ表示にしたときの左右の余白部分の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>sideBySideEditor.horizontalBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターグループ内で上下に並べて表示する2つのエディターを区切る色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">縦に分割した2つのエディター間の境界線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>sideBySideEditor.verticalBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターグループ内で左右に並べて表示する2つのエディターを区切る色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">横に分割した2つのエディター間の境界線</td>
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


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター全体の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターのデフォルト文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターのデフォルトテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorLineNumber.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">行番号の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター左端の行番号</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorLineNumber.activeForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カーソルがある行の行番号の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター左端の選択中の行番号</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorLineNumber.dimmedForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.renderFinalNewline</code> が <code>dimmed</code> のときの最終行の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ファイル末尾の空行の行番号</td>
  </tr>
</tbody>
</table>
</div>

### カーソル


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorCursor.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カーソルに重なった文字の背景色（ブロックカーソル時）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ブロックカーソルが文字に重なったときの文字色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorCursor.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カーソルの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター上の点滅するカーソル</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorMultiCursor.primary.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">複数カーソル使用時のメインカーソルの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マルチカーソル編集時の元から置いていたカーソル</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorMultiCursor.primary.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">複数カーソル使用時のメインカーソルに重なる文字の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">文字に重なったときの元から置いていたマルチカーソル(ブロックカーソル時)の文字色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorMultiCursor.secondary.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">複数カーソル使用時のサブカーソルの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マルチカーソル編集時の後から追加されたカーソル</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorMultiCursor.secondary.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">複数カーソル使用時のサブカーソルに重なる文字の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マルチカーソル編集時の後から追加されたカーソル(ブロックカーソル時)の文字色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.placeholder.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">プレースホルダーテキストの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">空のエディターに表示される案内のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.compositionBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">IME入力中の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">日本語入力中の変換候補のアンダーライン</td>
  </tr>
</tbody>
</table>
</div>

### 選択範囲

選択範囲の色は、1文字以上を選択したときに表示される。選択箇所に加え、同じ内容を持つ範囲もハイライトされる。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.selectionBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択範囲の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テキストをドラッグして選択したときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.selectionForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ハイコントラスト時の選択テキストの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">キストをドラッグして選択したときの文字色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.inactiveSelectionBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非アクティブなエディターでの選択範囲の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在操作していないエディターグループで選択中のテキストの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.selectionHighlightBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中と同じ内容を持つ範囲の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択した単語と同じ文字列がある箇所の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.selectionHighlightBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中と同じ内容を持つ範囲の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択した単語と同じ文字列がある箇所の枠線</td>
  </tr>
</tbody>
</table>
</div>

### ワードハイライト

カーソルがシンボルや単語の上にあるとき表示される。言語サポートがあれば参照・宣言箇所がハイライトされ、読み取り/書き込みアクセスで異なる色になる。言語サポートがない場合は単語単位のハイライトにフォールバックする。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.wordHighlightBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">シンボルの読み取りアクセス時の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">その変数を使用している箇所の背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.wordHighlightBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">シンボルの読み取りアクセス時の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">その変数を使用している箇所の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.wordHighlightStrongBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">シンボルの書き込みアクセス時の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">その変数に値を代入している箇所の背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.wordHighlightStrongBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">シンボルの書き込みアクセス時の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">その変数に値を代入している箇所の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.wordHighlightTextBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">シンボルのテキスト一致箇所の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">言語サポートがない場合の同一単語の背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.wordHighlightTextBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">シンボルのテキスト一致箇所の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">言語サポートがない場合の同一単語の枠線</td>
  </tr>
</tbody>
</table>
</div>

### 検索（Find）

Find/Replace ダイアログの検索文字列に応じて表示される色。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.findMatchBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在の検索マッチの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">検索語句にマッチし、現在選択している箇所の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.findMatchForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在の検索マッチの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">検索語句にマッチし、現在選択している箇所のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.findMatchHighlightForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">その他の検索マッチの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">検索語句にマッチしているが、現在選択していない箇所のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.findMatchHighlightBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">その他の検索マッチの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">検索語句にマッチしているが、現在選択していない箇所の背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.findRangeHighlightBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">検索範囲を限定するハイライトの背景色（Find widgetの「選択範囲内で検索」有効時）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「選択範囲内で検索」を有効化したときの対象範囲の背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.findMatchBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在の検索マッチの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">検索語句にマッチし、現在選択している箇所の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.findMatchHighlightBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">検索語句にマッチしているが、現在選択していない箇所の枠線</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.findRangeHighlightBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">検索範囲を限定するハイライトの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「選択範囲内で検索」を有効化したときの対象範囲の枠線</td>
  </tr>
</tbody>
</table>
</div>

### 検索ビューレット / Search Editor


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>search.resultsInfoForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">検索ビューレットの完了メッセージの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーで検索したときに表示される<code>y 個のファイルに x 件の結果(x results in y files)</code>というテキストの文字色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>searchEditor.findMatchBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Search Editor の検索結果の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーで検索したときのマッチした箇所の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>searchEditor.findMatchBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Search Editor の検索結果の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーで検索したときのマッチした箇所の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>searchEditor.textInputBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Search Editor のテキスト入力欄の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーの検索ボックスの枠線</td>
  </tr>
</tbody>
</table>
</div>

### ホバーハイライト


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.hoverHighlightBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー表示中の単語の下に表示されるハイライト色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバーしたときの型情報の小さいポップアップの背景（半透明）</td>
  </tr>
</tbody>
</table>
</div>

### 現在行のハイライト

現在行は背景ハイライトまたはボーダーのどちらかで表示されるのが一般的（両方同時には使われない）。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.lineHighlightBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カーソル位置の行のハイライト背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カーソルが位置している(=選択している)行全体の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.inactiveLineHighlightBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターが非フォーカス時のカーソル位置行のハイライト背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在操作していないエディターグループでのカーソルが位置している(=選択している)行全体の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.lineHighlightBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カーソル位置の行の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カーソルが位置している(=選択している)行全体を囲む枠線</td>
  </tr>
</tbody>
</table>
</div>

### Unicodeハイライト


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorUnicodeHighlight.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Unicode文字をハイライトする境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">全角スペースなど特殊なUnicode文字を囲む枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorUnicodeHighlight.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Unicode文字をハイライトする背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">全角スペースなど特殊なUnicode文字の背景</td>
  </tr>
</tbody>
</table>
</div>

### リンク


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorLink.activeForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブなリンクの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Ctrlキーを押しながらホバーしたリンクの文字色</td>
  </tr>
</tbody>
</table>
</div>

### 範囲ハイライト（Range Highlight）

検索結果を選択したときに表示される。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.rangeHighlightBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ハイライトされた範囲の背景色（Quick Open、Symbol in File、Find機能で使用）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">検索語句にマッチし、現在選択している箇所の行全体の背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.rangeHighlightBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ハイライトされた範囲の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">索語句にマッチし、現在選択している箇所の行全体の枠線</td>
  </tr>
</tbody>
</table>
</div>

### シンボルハイライト

「定義へ移動」などのコマンドでシンボルへ移動したときに表示される。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.symbolHighlightBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ハイライトされたシンボルの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">関数、クラス、変数の定義元へ移動した直後に対象シンボルにつく背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.symbolHighlightBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ハイライトされたシンボルの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">関数、クラス、変数の定義元へ移動した直後に対象シンボルにつく枠線</td>
  </tr>
</tbody>
</table>
</div>

### 空白文字

`Toggle Render Whitespace` を有効にすると表示される。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorWhitespace.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">空白文字の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択したテキストに含まれるスペースやタブを示す点の色</td>
  </tr>
</tbody>
</table>
</div>

### インデントガイド

`"editor.guides.indentation": true` と `"editor.guides.highlightActiveIndentation": true` を設定すると表示される。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorIndentGuide.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インデントガイドの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コードのインデントを示す縦線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorIndentGuide.background1</code>〜<code>background6</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インデントガイドの色（深さ1〜6段階）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ネストの深さごとに色分けされた縦線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorIndentGuide.activeBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブなインデントガイドの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カーソルがある階層のインデント縦線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorIndentGuide.activeBackground1</code>〜<code>activeBackground6</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブなインデントガイドの色（深さ1〜6段階）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カーソルがある階層の縦線（深さごとに色分け）</td>
  </tr>
</tbody>
</table>
</div>

### インレイヒント

`"editor.inlineSuggest.enabled": true` を設定すると表示される。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorInlayHint.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インラインヒントの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">関数の戻り値や変数の型などのインラインヒントの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorInlayHint.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インラインヒントの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">関数の戻り値や変数の型などのインラインヒントのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorInlayHint.typeForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">型ヒントの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変数の推論された型を示すヒントのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorInlayHint.typeBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">型ヒントの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変数の推論された型を示すヒントの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorInlayHint.parameterForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パラメータヒントの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">関数呼び出し時の引数名ヒントのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorInlayHint.parameterBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パラメータヒントの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">関数呼び出し時の引数名ヒントの背景</td>
  </tr>
</tbody>
</table>
</div>

### ルーラー・リンク付き編集

settings.jsonにて例えば`"editor.rulers": [80, 120],`と入力することでルーラー（縦線）を80文字目と120文字目に表示される。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorRuler.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディタールーラーの色（<code>"editor.rulers"</code> で位置指定）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">一定文字数の位置に表示される縦線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.linkedEditingBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">リンク付き編集モード時の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
</tbody>
</table>
</div>

### CodeLens / Lightbulb


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorCodeLens.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">CodeLensの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">関数の上に表示される「1 reference」などのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorLightBulb.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通常のクイックフィックスのアイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コードアクションを示す電球アイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorLightBulbAutoFix.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">自動修正のクイックフィックスのアイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">自動修正可能なときの電球アイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorLightBulbAi.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">AI機能のクイックフィックスのアイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">AI提案を示す電球アイコン</td>
  </tr>
</tbody>
</table>
</div>

### 括弧（Bracket）


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorBracketMatch.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マッチする括弧の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カーソルに位置している括弧とそれに対応する括弧同士の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorBracketMatch.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マッチする括弧のボックスの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カーソルに位置している括弧とそれに対応する括弧同士を囲む枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorBracketMatch.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マッチする括弧の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カーソルに位置している括弧とそれに対応する括弧同士のテキスト色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorBracketHighlight.foreground1</code>〜<code>foreground6</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">括弧ペアの色分け（深さ1〜6段階、Bracket Pair Colorization有効時）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ネストした括弧をネストの深さごとに色分け表示</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorBracketHighlight.unexpectedBracket.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">想定外（不一致）の括弧の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">閉じ括弧が足りない・余分なときの色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorBracketPairGuide.activeBackground1</code>〜<code>activeBackground6</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブな括弧ペアガイドの背景色（深さ1〜6段階、Bracket Pair Guide有効時）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カーソルが位置している場所の括弧ペアを結ぶ下線のガイドの色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorBracketPairGuide.background1</code>〜<code>background6</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非アクティブな括弧ペアガイドの背景色（深さ1〜6段階）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カーソルが位置している場所以外の括弧ペアを結ぶ下線のガイドの色</td>
  </tr>
</tbody>
</table>
</div>

### 折り畳み（Folding）


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.foldBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">折り畳まれた範囲の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コードの行の左にあるアイコンをクリックしてコードを折り畳んだ行の背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.foldPlaceholderForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">折り畳み範囲の最初の行以降に表示される省略テキストの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">折り畳まれたコードを示す「...」の文字色</td>
  </tr>
</tbody>
</table>
</div>

### Overview ruler（概要ルーラー）

エディター右端のスクロールバーの下に重なっている、エディター内の装飾の概要を示す。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">概要ルーラーの背景色（ミニマップ有効かつ右側配置時のみ使用）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">概要ルーラー部分の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">概要ルーラーの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">概要ルーラーの左端の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.findMatchForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">検索マッチのマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">検索ワードと一致した箇所を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.rangeHighlightForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ハイライト範囲（Quick Open等）のマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.selectionHighlightForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択ハイライトのマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択した単語と同じ文字列がある箇所を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.wordHighlightForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">シンボルハイライトのマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">その変数を使用している箇所を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.wordHighlightStrongForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">書き込みアクセスのシンボルハイライトのマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">その変数へ代入している箇所を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.wordHighlightTextForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テキスト一致のマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">言語サポートがない場合の同一単語箇所を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.modifiedForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更された内容のマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Git差分で変更された行を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.addedForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">追加された内容のマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Git差分で追加された行を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.deletedForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">削除された内容のマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Git差分で削除された行を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.errorForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラーのマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラーがある行を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.warningForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告のマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告がある行を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.infoForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">情報のマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">情報通知がある行を示す概要ルーラー上のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.bracketMatchForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マッチする括弧のマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カーソルに位置している括弧とそれに対応する括弧同士を示すマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.inlineChatInserted</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インラインチャットで挿入されたコンテンツのマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">AIによって挿入されたコードがある行を示すマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.inlineChatRemoved</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インラインチャットで削除されたコンテンツのマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">AIによって削除されたコードがある行を示すマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.commentDraftForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ドラフトコメントを含むコメントスレッドの装飾色（不透明）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">レビュー中の未送信コメントがある行を示すマーカー</td>
  </tr>
</tbody>
</table>
</div>

### エラーと警告


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorError.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラーの波線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コードのエラー箇所に表示される赤い波線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorError.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラーボックスの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラー箇所を囲む枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorError.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラーテキストの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラー箇所のテキスト背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorWarning.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告の波線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コードの警告箇所に表示される黄色い波線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorWarning.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告ボックスの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告箇所を囲む枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorWarning.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告テキストの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告箇所のテキスト背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorInfo.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">情報の波線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorInfo.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">情報ボックスの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorInfo.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">情報テキストの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorHint.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ヒントの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorHint.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ヒントボックスの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>problemsErrorIcon.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">問題パネルのエラーアイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターより下部にある「問題」パネル(<code>Ctrl</code>+<code>Shift</code>+<code>M</code>)のエラー項目のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>problemsWarningIcon.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">問題パネルの警告アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターより下部にある「問題」パネル(<code>Ctrl</code>+<code>Shift</code>+<code>M</code>)の警告項目のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>problemsInfoIcon.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">問題パネルの情報アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターより下部にある「問題」パネル(<code>Ctrl</code>+<code>Shift</code>+<code>M</code>)の情報項目のアイコン</td>
  </tr>
</tbody>
</table>
</div>

### 未使用コード


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorUnnecessaryCode.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未使用コードの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">使われていない変数やインポートを示す枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorUnnecessaryCode.opacity</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未使用コードの不透明度</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">使われていないコードを薄く表示する際の濃さ（ハイコントラストテーマでは枠線表示が推奨）</td>
  </tr>
</tbody>
</table>
</div>

### ガター（行番号・グリフマージン）

ガターには行番号とグリフマージン（アイコン表示領域）が含まれる。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGutter.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ガターの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">行番号やアイコンが表示されるエディターの左端領域の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGutter.modifiedBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更された行のガター背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域のGit差分で変更された行のマーカー背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGutter.modifiedSecondaryBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更された行のガターのセカンダリ背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域のGit差分の変更行のマーカーの補助色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGutter.addedBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">追加された行のガター背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域のGit差分で追加された行のマーカー背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGutter.addedSecondaryBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">追加された行のガターのセカンダリ背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域のGit差分の追加行のマーカーの補助色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGutter.deletedBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">削除された行のガター背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域のGit差分で削除された行のマーカー背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGutter.deletedSecondaryBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">削除された行のガターのセカンダリ背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域のGit差分の削除行のマーカーの補助色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGutter.commentRangeForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コメント可能範囲のガター装飾色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域のプルリクエストレビューでコメント可能な行に表示されるアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGutter.commentGlyphForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コメントグリフのガター装飾色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域のコメントが付いている行のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGutter.commentUnresolvedGlyphForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未解決コメントスレッドのグリフ色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域の未解決のレビューコメントがある行のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGutter.foldingControlForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">折り畳みコントロールの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域の行番号の右横に表示される折り畳み用の矢印アイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGutter.itemGlyphForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ガターアイテムのグリフ色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域のデバッグのブレークポイントなどのアイコン色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGutter.itemBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ガターアイテムの背景色（不透明）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域のデバッグのブレークポイントなどのアイコン背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGutter.commentDraftGlyphForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ドラフトコメントスレッドのグリフ色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域の未送信のコメントがある行のアイコン</td>
  </tr>
</tbody>
</table>
</div>

### コメントウィジェット

プルリクエストのレビュー時に表示される。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorCommentsWidget.resolvedBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">解決済みコメントの枠線・矢印の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">レビューで解決済みとされたコメントの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorCommentsWidget.unresolvedBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未解決コメントの枠線・矢印の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">レビューで未解決のコメントの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorCommentsWidget.rangeBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コメント対象範囲の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コメントが付けられたコード範囲の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorCommentsWidget.rangeActiveBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中・ホバー中のコメント対象範囲の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在開いているコメントが対象とするコード範囲の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorCommentsWidget.replyInputBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コメント返信入力欄の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コメントへの返信を入力するテキストボックスの背景</td>
  </tr>
</tbody>
</table>
</div>

### インライン編集（Inline Edit）

AIなどが次の変更を提案する際に表示される。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineEdit.gutterIndicator.primaryBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">メインのインライン編集インジケーターの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域のAI提案の表示の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineEdit.gutterIndicator.primaryForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">メインのインライン編集インジケーターの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域のAI提案の表示のテキスト・アイコン色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineEdit.gutterIndicator.primaryBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">メインのインライン編集インジケーターの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域のAI提案の表示の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineEdit.gutterIndicator.secondaryBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サブのインライン編集インジケーターの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域の複数が提案がある場合の2つ目以降の表示の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineEdit.gutterIndicator.secondaryForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サブのインライン編集インジケーターの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域の複数が提案がある場合の2つ目以降の表示のテキスト・アイコン色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineEdit.gutterIndicator.secondaryBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サブのインライン編集インジケーターの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域の複数が提案がある場合の2つ目以降の表示の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineEdit.gutterIndicator.successfulBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">提案が成功したときのインジケーターの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域の提案を適用したときの表示の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineEdit.gutterIndicator.successfulForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">提案が成功したときのインジケーターの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域の提案を適用したときの表示のテキスト・アイコン色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineEdit.gutterIndicator.successfulBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">提案が成功したときのインジケーターの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域の提案を適用したときの表示の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineEdit.gutterIndicator.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インライン編集インジケーターの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域の表示全体のデフォルト背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineEdit.originalBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更前テキストの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">AI提案の変更前部分の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineEdit.modifiedBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更後テキストの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">AI提案の変更後部分の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineEdit.originalChangedLineBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更前テキストの変更行の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更前のコードで変更対象となった行の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineEdit.originalChangedTextBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更前テキストの変更箇所のオーバーレイ色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更前のコードで変更対象となった文字列の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineEdit.modifiedChangedLineBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更後テキストの変更行の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更後のコードで変更された行の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineEdit.modifiedChangedTextBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更後テキストの変更箇所のオーバーレイ色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更後のコードで変更された文字列の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineEdit.originalBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更前テキストの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">AI提案の変更前部分を囲む枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineEdit.modifiedBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更後テキストの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">AI提案の変更後部分を囲む枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineEdit.tabWillAcceptModifiedBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Tabキーで適用される際の変更後テキストの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Tabキーで提案を確定できる状態の変更後部分の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineEdit.tabWillAcceptOriginalBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Tabキーで適用される際の変更前テキストの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Tabキーで提案を確定できる状態の変更前部分の枠線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Diff editor colors(差分エディターカラー)</b></summary><br>


**Diff editor colors** は、同じファイルの修正前と修正後を左右、あるいは上下に並べて変更点を比較するための専用画面に関する色設定である。挿入・削除されたテキストの色付けには、背景色か境界線の色のどちらか一方のみを使用する（両方同時には使わない）。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>diffEditor.insertedTextBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">挿入されたテキストの背景色（半透明）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">追加された文字列の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>diffEditor.insertedTextBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">挿入されたテキストのアウトライン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">追加された文字列を囲む枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>diffEditor.removedTextBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">削除されたテキストの背景色（半透明）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">削除された文字列の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>diffEditor.removedTextBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">削除されたテキストのアウトライン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">削除された文字列を囲む枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>diffEditor.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">2つのエディター間の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">並んでいる差分エディターの境界線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>diffEditor.diagonalFill</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">差分エディターの斜線塗りつぶしの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">対応する変更がない領域の斜線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>diffEditor.insertedLineBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">挿入された行の背景色（半透明）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">追加された行全体の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>diffEditor.removedLineBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">削除された行の背景色（半透明）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">削除された行全体の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>diffEditorGutter.insertedLineBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">挿入された行のガター（余白）の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域の行番号左端の追加された行のマーカー背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>diffEditorGutter.removedLineBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">削除された行のガター（余白）の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの左端領域の行番号左端の削除された行のマーカー背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>diffEditorOverview.insertedForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">差分概要ルーラーの挿入コンテンツの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">差分エディター右端の概要ルーラーの追加箇所マーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>diffEditorOverview.removedForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">差分概要ルーラーの削除コンテンツの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">差分エディター右端の概要ルーラーの削除箇所マーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>diffEditor.unchangedRegionBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更のない折り畳まれた範囲のブロックの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">差分がない折り畳まれた領域のブロック背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>diffEditor.unchangedRegionForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更のない折り畳まれた範囲のブロックの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">差分がない折り畳まれた領域のブロックテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>diffEditor.unchangedRegionShadow</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更のない範囲ウィジェット周囲の影の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">折り畳まれた変更なし領域の周囲の影</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>diffEditor.unchangedCodeBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更のないコードの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">差分エディターで変更がないコード部分の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>diffEditor.move.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">移動されたテキストの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">別の場所に移動されたコードブロックの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>diffEditor.moveActive.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブな移動テキストの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在選択中の移動されたコードブロックの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>multiDiffEditor.headerBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マルチファイル差分エディターのヘッダー背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">複数ファイルの差分表示時の各ファイルヘッダーの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>multiDiffEditor.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マルチファイル差分エディターの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">複数ファイルの差分表示全体の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>multiDiffEditor.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マルチファイル差分エディターの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">複数ファイルの差分表示での各ファイル間の境界線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Chat colors(チャットカラー)</b></summary><br>


**Chat colors** は、VSCode のチャット機能に関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>chat.requestBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャットリクエストの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャットパネルのユーザー入力欄の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>chat.requestBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャットリクエストの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャットパネルのユーザー入力欄の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>chat.slashCommandBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スラッシュコマンドの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャットに入力された <code>/explain</code> などのスラッシュコマンドの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>chat.slashCommandForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スラッシュコマンドの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャットに入力された <code>/explain</code> などのスラッシュコマンドのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>chat.avatarBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャットアバターの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ユーザーやAIのアイコン部分の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>chat.avatarForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャットアバターの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ユーザーやAIのアイコン部分のテキスト・アイコン色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>chat.editedFileForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">編集済みファイルリストのファイル名の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャットで編集されたファイルの一覧に表示されるファイル名</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>chat.linesAddedForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コードブロックピルの追加行数の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コードブロック内の「+N lines」の文字色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>chat.linesRemovedForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コードブロックピルの削除行数の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コードブロック内の「-N lines」の文字色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>chat.requestCodeBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャットリクエストバブル内のコードブロックの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>chat.requestBubbleBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャットリクエストバブルの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>chat.requestBubbleHoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時のチャットリクエストバブルの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>chat.checkpointSeparator</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャットチェックポイントの区切り線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>chat.thinkingShimmer</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">思考中・処理中ラベルのシマーハイライト色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">AIが回答を生成中に表示される「Thinking...」などのアニメーション色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>chatManagement.sashBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Chat Managementエディターの分割ビューのサッシュ（境界線）の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャット画面とエディター間の境界線をクリックまたはドラッグしたときの境界線</td>
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


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineChat.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インラインチャットウィジェットの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内に表示されるAIのチャットのウィジェットの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineChat.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インラインチャットウィジェットの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内に表示されるAIチャットのウィジェットのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineChat.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インラインチャットウィジェットの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内に表示されるAIチャットのウィジェットの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineChat.shadow</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インラインチャットウィジェットの影の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内に表示されるAIチャットのウィジェットの影</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineChatInput.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インラインチャット入力欄の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内に表示されるAIチャットのテキスト入力フィールドの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineChatInput.focusBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォーカス時のインラインチャット入力欄の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内に表示されるAIチャットの入力フィールドを選択したときの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineChatInput.placeholderForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インラインチャット入力欄のプレースホルダーの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内に表示されるAIチャットの入力フィールド内の「Ask Copilot」などのヒントテキストの色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineChatInput.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インラインチャット入力欄の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内に表示されるAIチャットの入力フィールドの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineChatDiff.inserted</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インラインチャット入力欄の挿入テキストの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内に表示されるAIチャットが提案したコードの追加部分の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>inlineChatDiff.removed</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インラインチャット入力欄の削除テキストの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内に表示されるAIチャットが提案したコードの削除部分の背景</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Panel Chat colors(パネルチャットカラー)</b></summary><br>


**Panel Chat colors** は、インタラクティブなコードセルに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>interactive.activeCodeBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォーカス中のインタラクティブコードセルの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>interactive.inactiveCodeBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非フォーカス時のインタラクティブコードセルの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
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


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorWidget.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターウィジェットの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Find/Replace ダイアログのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorWidget.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターウィジェットの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Find/Replace ダイアログの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorWidget.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターウィジェットの境界線の色（ウィジェット固有の色がない場合に使用）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Find/Replace ダイアログの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorWidget.resizeBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターウィジェットのリサイズバーの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウィジェットの下端にあるドラッグしてサイズ変更するための線</td>
  </tr>
</tbody>
</table>
</div>

### サジェストウィジェット


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorSuggestWidget.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サジェストウィジェットの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変数名や関数の候補のポップアップの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorSuggestWidget.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サジェストウィジェットの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変数名や関数の候補のポップアップの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorSuggestWidget.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サジェストウィジェットの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変数名や関数の候補のポップアップのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorSuggestWidget.focusHighlightForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォーカス中の項目のマッチハイライト色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変数名や関数の候補のポップアップの現在選択している候補内の入力文字に一致する部分の色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorSuggestWidget.highlightForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マッチハイライトの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変数名や関数の候補のポップアップの候補内の入力文字に一致する部分の色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorSuggestWidget.selectedBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中の項目の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変数名や関数の候補のポップアップで選択中の項目の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorSuggestWidget.selectedForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中の項目の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変数名や関数の候補のポップアップで選択中の項目のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorSuggestWidget.selectedIconForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中の項目のアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変数名や関数の候補のポップアップで選択中の項目の種別アイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorSuggestWidgetStatus.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サジェストウィジェットのステータスの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変数名や関数の候補のポップアップ内のリスト下部に表示されるステータステキスト</td>
  </tr>
</tbody>
</table>
</div>

### ホバーウィジェット


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorHoverWidget.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターホバーの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コード内の関数や変数にカーソルを合わせたときに、その型や使い方を教える吹き出しのポップアップのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorHoverWidget.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターホバーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コード内の関数や変数にカーソルを合わせたときに、その型や使い方を教える吹き出しのポップアップの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorHoverWidget.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターホバーの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コード内の関数や変数にカーソルを合わせたときに、その型や使い方を教える吹き出しのポップアップの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorHoverWidget.highlightForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パラメータヒントのアクティブな項目の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">関数の引数のヒントで現在入力中の引数のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorHoverWidget.statusBarBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターホバーのステータスバーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コード内の関数や変数にカーソルを合わせたときに、その型や使い方を教える吹き出しのポップアップ下部のステータスバー背景</td>
  </tr>
</tbody>
</table>
</div>

### ゴーストテキスト


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGhostText.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ゴーストテキストの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">AIが自動で補完するテキスト領域の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGhostText.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ゴーストテキストの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">AIが自動で補完するテキスト領域の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorGhostText.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ゴーストテキストの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">AIが自動で補完するテキスト</td>
  </tr>
</tbody>
</table>
</div>

### スティッキースクロール

巨大なファイルをスクロールしているとき、現在どの関数やクラス、ネストの中にいるのかを明確にするために、親要素の行（定義部分）をエディタの最上部に固定して表示する機能である。
`"editor.stickyScroll.enabled": true`とすることで表示される。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorStickyScroll.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターのスティッキースクロールの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スクロール時にエディター上部に固定表示されるスコープ（クラス名・関数名など）の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorStickyScroll.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターのスティッキースクロールの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スクロール時にエディター上部に固定表示されるスコープ部分の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorStickyScroll.shadow</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターのスティッキースクロールの影の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スクロール時にエディター上部に固定表示されるスコープ部分とエディター本体の間の影</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorStickyScrollGutter.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スティッキースクロールのガター部分の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スクロール時にエディター上部に固定表示されるスコープの行番号領域の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorStickyScrollHover.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時のスティッキースクロールの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スクロール時にエディター上部に固定表示されるスコープにホバーしたときの背景</td>
  </tr>
</tbody>
</table>
</div>

### デバッグ例外ウィジェット

デバッグ中に例外で停止したときにエディター内に表示されるピークビュー。
(参考: [Extension API to Access ExceptionWidget (or ZoneWidget)](https://github.com/microsoft/vscode/issues/140752)
)


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugExceptionWidget.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">例外ウィジェットの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中に例外が発生したときのポップアップ背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugExceptionWidget.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">例外ウィジェットの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中に例外が発生したときのポップアップ枠線</td>
  </tr>
</tbody>
</table>
</div>

### エディターマーカーナビゲーション

「次のエラーまたは警告へ移動(`F8`)」を実行した際に、コードのすぐ下に出現するエラーメッセージ表示用の専用ウィジェット（ダイアログボックス）です。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorMarkerNavigation.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マーカーナビゲーションウィジェットの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラー・警告ナビゲーションポップアップの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorMarkerNavigationError.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マーカーナビゲーションのエラー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラー箇所に移動したときのポップアップのエラー表示の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorMarkerNavigationWarning.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マーカーナビゲーションの警告色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告箇所に移動したときのポップアップの警告表示の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorMarkerNavigationInfo.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マーカーナビゲーションの情報色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">情報箇所に移動したときのポップアップの情報表示の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorMarkerNavigationError.headerBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マーカーナビゲーションのエラーヘッダーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラーナビゲーションポップアップのヘッダー背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorMarkerNavigationWarning.headerBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マーカーナビゲーションの警告ヘッダーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告ナビゲーションポップアップのヘッダー背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorMarkerNavigationInfo.headerBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マーカーナビゲーションの情報ヘッダーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">情報ナビゲーションポップアップのヘッダー背景</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Peek view colors(ピークビューカラー)</b></summary><br>


**Peek view colors** は、関数の定義元や参照されている場所をエディター内の現在のコードの行間に表示するビューに関する色設定である。`Alt` + `F12`で表示される。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>peekView.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビューの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>peekViewEditor.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビューエディターの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュー内のコード表示部分の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>peekViewEditorGutter.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビューエディターのガターの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュー内の行番号領域の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>peekViewEditor.matchHighlightBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビューエディター内のマッチハイライトの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュー内で検索文字列に一致する箇所の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>peekViewEditor.matchHighlightBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビューエディター内のマッチハイライトの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュー内で検索文字列に一致する箇所の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>peekViewResult.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュー結果リストの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュー右側に表示される参照箇所一覧の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>peekViewResult.fileForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュー結果リストのファイルノードの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュー右側に表示される参照箇所一覧に表示されるファイル名のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>peekViewResult.lineForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュー結果リストの行ノードの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュー右側に表示される参照箇所一覧に表示される<code>peekViewResult.fileForeground</code>以外のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>peekViewResult.matchHighlightBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュー結果リストのマッチハイライトの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュー右側に表示される参照箇所一覧で検索文字列に一致する箇所の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>peekViewResult.selectionBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュー結果リストの選択中項目の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュー右側に表示される参照箇所一覧で選択中の(ピークビューに現在表示させている)項目の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>peekViewResult.selectionForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュー結果リストの選択中項目の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュー右側に表示される参照箇所一覧で選択中の(ピークビューに現在表示させている)項目のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>peekViewTitle.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュータイトル領域の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュー上部のタイトルバーの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>peekViewTitleDescription.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュータイトルの補足情報の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">タイトルバーのタイトルの右に表示されるディレクトリ場所の表記などの補足テキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>peekViewTitleLabel.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュータイトルの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">タイトルバーに表示されるファイル名(タイトル)のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>peekViewEditorStickyScroll.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビューエディターのスティッキースクロールの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュー内でスクロール時に固定表示されるスコープの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>peekViewEditorStickyScrollGutter.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビューエディターのスティッキースクロールのガター部分の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビュー内で固定表示されるスコープの行番号領域の背景</td>
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


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>merge.currentHeaderBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在の変更（Current）のヘッダー背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">`<<<<<<< HEAD` のヘッダー部分の背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>merge.currentContentBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在の変更（Current）のコンテンツ背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">`<<<<<<< HEAD` のコード部分の背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>merge.incomingHeaderBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">取り込む変更（Incoming）のヘッダー背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">`<<<<<<< somebranch` のヘッダー部分の背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>merge.incomingContentBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">取り込む変更（Incoming）のコンテンツ背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">`<<<<<<< somebranch` のコード部分の背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>merge.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ヘッダーと区切り線の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コンフリクト各セクションのヘッダーや区切り線の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>merge.commonContentBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">共通の祖先（Common ancestor）のコンテンツ背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">3-way diffでの`<<<<<<< common`のコード部分の背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>merge.commonHeaderBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">共通の祖先（Common ancestor）のヘッダー背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">3-way diffでの`<<<<<<< common`ののヘッダー部分の背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.currentContentForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在の変更（Current）の概要ルーラーのマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター右端のスクロールバーの下に重なっている、エディター内の装飾の概要を示す欄で、現在の変更部分（Current）を示すマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.incomingContentForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">取り込む変更（Incoming）の概要ルーラーのマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター右端のスクロールバーの下に重なっている、エディター内の装飾の概要を示す欄で、取り込む変更部分を示すマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.commonContentForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">共通の祖先（Common ancestor）の概要ルーラーのマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター右端のスクロールバーの下に重なっている、エディター内の装飾の概要を示す欄で、共通部分を示すマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.commentForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">解決済みコメントの概要ルーラー装飾色（不透明）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター右端のスクロールバーの下に重なっている、エディター内の装飾の概要を示す欄で、解決済みコメントを示すマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.commentUnresolvedForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未解決コメントの概要ルーラー装飾色（不透明）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター右端のスクロールバーの下に重なっている、エディター内の装飾の概要を示す欄で、未解決のコメントを示すマーカー</td>
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


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.change.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更箇所の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マージエディターで変更がある行の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.change.word.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">単語単位の変更箇所の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マージエディターで変更された単語部分の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.conflict.unhandledUnfocused.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未処理・非フォーカス時のコンフリクトの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">まだ解決していない、選択していないコンフリクト箇所の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.conflict.unhandledFocused.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未処理・フォーカス時のコンフリクトの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">まだ解決していない、現在選択中のコンフリクト箇所の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.conflict.handledUnfocused.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">処理済み・非フォーカス時のコンフリクトの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">解決済みで、選択していないコンフリクト箇所の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.conflict.handledFocused.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">処理済み・フォーカス時のコンフリクトの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">解決済みで、現在選択中のコンフリクト箇所の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.conflict.handled.minimapOverViewRuler</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">処理済みコンフリクトのミニマップ／概要ルーラー上の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">右側のファイルのズームアウトを示すミニマップ上の解決済みコンフリクトのマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.conflict.unhandled.minimapOverViewRuler</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未処理コンフリクトのミニマップ／概要ルーラー上の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">右側のファイルのズームアウトを示すミニマップ上の未解決コンフリクトのマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.conflictingLines.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「Conflicting Lines」テキストの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コンフリクトがある行数を示すメッセージの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.changeBase.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ベース（Base）側の変更箇所の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">3-way diffでの元々のコードにおける変更された行の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.changeBase.word.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ベース（Base）側の単語単位の変更箇所の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">3-way diffでの元々のコードにおける変更された単語部分の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.conflict.input1.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Input1側の装飾の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">3-way diffでの自分側（Current, Input1）コードの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.conflict.input2.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Input2側の装飾の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">3-way diffでのマージ元側（Incoming, Input2）コードの背景</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Panel colors(パネルカラー)</b></summary><br>


**Panel colors** は、エディター領域の下に表示されるパネルに関する色設定である。問題、出力、デバッグコンソール、ターミナル、ポートなどを含む欄。

<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>panel.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネルの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネル全体の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>panel.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネルとエディターを区切る境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネルとエディター領域の間の境界線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>panel.dropBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネルタイトルへのドラッグ&ドロップ時の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネル上部のタブ(タイトル)をドラッグして並び替えるときのタブ間の境界線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>panelTitle.activeBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブなパネルタイトルの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中のパネルタブ（「ターミナル」など）の下に表示される線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>panelTitle.activeForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブなパネルのタイトル色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中のパネルタブ（「ターミナル」など）のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>panelTitle.inactiveForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非アクティブなパネルのタイトル色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未選択のパネルタブのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>panelTitle.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネルタイトル下部の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネルタイトルとビュー(本体)を区切る下線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>panelTitleBadge.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネルタイトルバッジの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「問題」タブの件数表示バッジの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>panelTitleBadge.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネルタイトルバッジの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「問題」タブの件数表示バッジのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>panelInput.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネル内の入力ボックスの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグコンソールの入力欄の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>panelSection.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">複数ビューが横に並んでいるときのパネルセクションの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネルを横分割して複数表示したときの境界線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>panelSection.dropBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネルセクションへのドラッグ&ドロップ時の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネル内でビューをドラッグしているときの背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>panelSectionHeader.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネルセクションヘッダーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネル内の各セクション見出しの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>panelSectionHeader.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネルセクションヘッダーの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネル内の各セクション見出しのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>panelStickyScroll.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネルのスティッキースクロールの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネル内でスクロール時に上部に固定表示される親要素の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>panelStickyScroll.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネルのスティッキースクロールの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネル内でスクロール時に上部に固定表示される親要素の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>panelStickyScroll.shadow</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネルのスティッキースクロールの影の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネル内でスクロール時に上部に固定表示される親要素の影</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>panelSectionHeader.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">複数ビューが縦に並んでいるときのパネルセクションヘッダーの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネルを縦分割して複数表示したときのセクション見出しの境界線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>outputView.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">出力ビューの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「出力」パネルの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>outputViewStickyScroll.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">出力ビューのスティッキースクロールの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「出力」パネルでスクロール時に固定表示される部分の背景</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Status Bar colors(ステータスバーカラー)</b></summary><br>


**Status Bar colors** は、ウィンドウ最下部に表示されるステータスバーに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBar.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">標準時のステータスバーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ステータスバー全体の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBar.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ステータスバーの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ステータスバーに表示されるテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBar.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ステータスバーとエディターを区切る境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ステータスバー上部の境界線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBar.debuggingBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中のステータスバーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">プログラムをデバッグ実行中のステータスバー背景（通常オレンジ系）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBar.debuggingForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中のステータスバーの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ実行中のステータスバーのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBar.debuggingBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中のステータスバーとエディターを区切る境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ実行中のステータスバーとエディターを区切る境界線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBar.noFolderForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォルダーを開いていないときのステータスバーの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォルダー未オープン時のステータスバーのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBar.noFolderBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォルダーを開いていないときのステータスバーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォルダー未オープン時のステータスバー背景（通常紫系）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBar.noFolderBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォルダーを開いていないときのステータスバーとエディターを区切る境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォルダー未オープン時のステータスバーとエディターを区切る境界線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.activeBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">クリック時のステータスバーアイテムの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ステータスバーの項目をクリックして押し込んでいるときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.hoverForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時のステータスバーアイテムの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ステータスバーの項目にホバーしたときのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.hoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時のステータスバーアイテムの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ステータスバーの項目にホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.prominentForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">強調アイテムの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能の Live Server を使ってローカルサーバーを起動したときにステータスバーの右側に表示される「Port: 5500（停止ボタン）」の強調表示項目のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.prominentBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">強調アイテムの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能の Live Server を使ってローカルサーバーを起動したときにステータスバーの右側に表示される「Port: 5500（停止ボタン）」の強調表示項目の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.prominentHoverForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時の強調アイテムの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能の Live Server を使ってローカルサーバーを起動したときにステータスバーの右側に表示される「Port: 5500（停止ボタン）」の強調表示項目にホバーしたときのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.prominentHoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時の強調アイテムの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能の Live Server を使ってローカルサーバーを起動したときにステータスバーの右側に表示される「Port: 5500（停止ボタン）」の強調表示項目にホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.remoteBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">リモートインジケーターの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「リモート接続中」を示す左下のアイコン部分の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.remoteForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">リモートインジケーターの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「リモート接続中」を示す左下のアイコン部分のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.remoteHoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時のリモートインジケーターの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「リモート接続中」を示す左下のアイコン部分にホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.remoteHoverForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時のリモートインジケーターの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「リモート接続中」を示す左下のアイコン部分にホバーしたときのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.errorBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラーアイテムの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラー状態を示すステータスバーの項目の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.errorForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラーアイテムの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラー状態を示すステータスバーの項目のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.errorHoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時のエラーアイテムの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラー状態のステータスバーの項目にホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.errorHoverForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時のエラーアイテムの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラー状態のステータスバーの項目にホバーしたときのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.warningBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告アイテムの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告状態を示すステータスバーの項目の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.warningForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告アイテムの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告状態を示すステータスバーの項目のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.warningHoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時の警告アイテムの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告状態のステータスバーの項目にホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.warningHoverForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時の警告アイテムの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告状態のステータスバーの項目にホバーしたときのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.compactHoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">2つのホバー情報を持つ項目にホバーしたときの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.focusBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">キーボード操作でフォーカス時のステータスバーアイテムの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドパレット(<code>Ctrl</code>+<code>Shift</code>+<code>P</code>)から「View: Focus Status Bar」を選択し、左右の矢印キー(←, →)で項目を移動したときに表示されるターゲットの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBar.focusBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">キーボード操作でフォーカス時のステータスバーの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドパレット(<code>Ctrl</code>+<code>Shift</code>+<code>P</code>)から「View: Focus Status Bar」を選択し、ステータスバー自体にフォーカスしたときの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.offlineBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ワークベンチがオフライン時のアイテムの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ネットワーク未接続時のステータスバー項目の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.offlineForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ワークベンチがオフライン時のアイテムの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ネットワーク未接続時のステータスバー項目のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.offlineHoverForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">オフライン時、ホバーしたアイテムの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ネットワーク未接続時のステータスバー項目にホバーしたときのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>statusBarItem.offlineHoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">オフライン時、ホバーしたアイテムの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ネットワーク未接続時のステータスバー項目にホバーしたときの背景</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Title Bar colors(タイトルバーカラー)</b></summary><br>


**Title Bar colors** は、ウィンドウ最上部に表示されるタイトルバーに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>titleBar.activeBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウィンドウがアクティブなときのタイトルバーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">VSCodeウィンドウを操作しているときのタイトルバー背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>titleBar.activeForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウィンドウがアクティブなときのタイトルバーの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">VSCodeウィンドウを操作しているときのタイトルバーのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>titleBar.inactiveBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウィンドウが非アクティブなときのタイトルバーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">VSCodeウィンドウを操作していないときのタイトルバー背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>titleBar.inactiveForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウィンドウが非アクティブなときのタイトルバーの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">VSCodeウィンドウを操作していないときのタイトルバーのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>titleBar.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">タイトルバーのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">タイトルバー下部の境界線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Menu Bar colors(メニューバーカラー)</b></summary><br>


**Menu Bar colors** は、ウィンドウ最上部にあるメニューバーとそれを開いたときのメニュー項目に関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>menubar.selectionForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">メニューバーで選択中の項目の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「ファイル」「編集」などのメニューバーの項目を選択したときのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>menubar.selectionBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">メニューバーで選択中の項目の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「ファイル」「編集」などのメニューバーの項目を選択したときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>menubar.selectionBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">メニューバーで選択中の項目のボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「ファイル」「編集」などのメニューバーの項目を選択したときの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>menu.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">メニュー項目の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「ファイル」をクリックして開いたドロップダウンメニューのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>menu.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">メニュー項目の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">開いたときのドロップダウンメニュー全体の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>menu.selectionForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">メニュー内で選択中の項目の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ドロップダウンメニュー内でホバー・選択中の項目のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>menu.selectionBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">メニュー内で選択中の項目の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ドロップダウンメニュー内でホバー・選択中の項目の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>menu.selectionBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">メニュー内で選択中の項目のボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ドロップダウンメニュー内でホバー・選択中の項目の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>menu.separatorBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">メニュー内の区切り線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ドロップダウンメニュー内のセクションを分ける横線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>menu.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">メニューのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">開いたときのドロップダウンメニュー全体の枠線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Command Center colors(コマンドセンターカラー)</b></summary><br>


**Command Center colors** は、タイトルバー中央のタイトルをクリックしたときに表示されるコマンドセンターに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>commandCenter.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドセンターの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドセンターのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>commandCenter.activeForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブ時のコマンドセンターの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドセンター内のクリック・選択した項目のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>commandCenter.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドセンターの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドセンターの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>commandCenter.activeBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブ時のコマンドセンターの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドセンター内のクリック・選択した項目の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>commandCenter.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドセンターのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドセンターの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>commandCenter.inactiveForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウィンドウが非アクティブなときのコマンドセンターの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドセンター内のクリック・選択していない項目のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>commandCenter.inactiveBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウィンドウが非アクティブなときのコマンドセンターのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドセンター内のクリック・選択していない項目の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>commandCenter.activeBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクティブ時のコマンドセンターのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドセンター内のクリック・選択した項目の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>commandCenter.debuggingBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中のコマンドセンターの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">プログラムをデバッグ実行中のコマンドセンターの背景</td>
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


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notificationCenter.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通知センターのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通知センター全体を囲む枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notificationCenterHeader.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通知センターのヘッダーの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通知センター上部の「Notifications」などのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notificationCenterHeader.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通知センターのヘッダーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通知センター上部のヘッダー部分の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notificationToast.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通知のボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ヘッダーがない単通知のポップアップの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notifications.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通知の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通知に表示されるメッセージのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notifications.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通知の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通知全体の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notifications.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通知センター内で他の通知と区切るボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通知センター内で複数の通知を区切る線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notificationLink.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通知内のリンクの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通知メッセージ内に含まれるリンクテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notificationsErrorIcon.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通知のエラーアイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラー通知に表示されるアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notificationsWarningIcon.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通知の警告アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告通知に表示されるアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notificationsInfoIcon.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通知の情報アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">情報通知に表示されるアイコン</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Banner colors(バナーカラー)</b></summary><br>


**Banner colors** は、タイトルバーの下に表示され、ワークベンチの幅いっぱいに広がるバナーに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>banner.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">バナーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>banner.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">バナーの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>banner.iconForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">バナーテキスト前のアイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Extensions colors(拡張機能カラー)</b></summary><br>


**Extensions colors** は、拡張機能ビューに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>extensionButton.prominentForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能ビューの強調ボタンの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「インストール」や「再読み込み」ボタンのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>extensionButton.prominentBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能ビューの強調ボタンの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「インストール」や「再読み込み」ボタンの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>extensionButton.prominentHoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時の強調ボタンの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「インストール」や「再読み込み」ボタンにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>extensionButton.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能アクションボタンの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「無効にする」など通常のアクションボタンの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>extensionButton.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能アクションボタンの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「無効にする」など通常のアクションボタンのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>extensionButton.hoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時の拡張機能アクションボタンの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">通常のアクションボタンにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>extensionButton.separator</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能アクションボタンの区切り線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「無効にする」や「アンインストール」などのドロップダウン付きボタンの区切り線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>extensionButton.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能アクションボタンのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「無効にする」など通常のアクションボタンの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>extensionBadge.remoteBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能ビューのリモートバッジの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">VSCodeをリモート接続モードで起動した状態で、拡張機能タブを開いたときに各拡張機能のタイトルの右横にある接続先の環境名が書かれたバッジの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>extensionBadge.remoteForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能ビューのリモートバッジの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">VSCodeをリモート接続モードで起動した状態で、拡張機能タブを開いたときに各拡張機能のタイトルの右横にある接続先の環境名が書かれたバッジのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>extensionIcon.starForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能の評価アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能の星評価（★）アイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>extensionIcon.verifiedForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">拡張機能の認証済み発行者アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">公式認証(発行元)済みを示すチェックマークアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>extensionIcon.preReleaseForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">プレリリース版拡張機能のアイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">プレリリース版や推奨欄の左上にあるアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>extensionIcon.sponsorForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スポンサー機能のアイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スポンサーを募集している拡張機能のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>extensionIcon.privateForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">プライベート拡張機能のアイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">非公開の拡張機能を示すアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mcpIcon.starForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">MCPのスター付きアイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スター登録されたMCPサーバーを示すアイコン</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Quick picker colors(クイックピッカーカラー)</b></summary><br>


**Quick picker colors** は、コマンドパレット(`Ctrl`+`Shift`+`P`)やカラーテーマ選択ウィンドウなどに使われるクイックピッカー（クイックオープン）UIに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>pickerGroup.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">クイックピッカーのグループ区切りボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドパレットでカテゴリ間を区切る線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>pickerGroup.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">クイックピッカーのグループラベルの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドパレットのカテゴリ見出しのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>quickInput.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">クイック入力ウィジェットの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドパレットやカラーテーマ選択ウィンドウの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>quickInput.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">クイック入力ウィジェットの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドパレットやカラーテーマ選択ウィンドウのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>quickInputList.focusBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォーカス中の項目の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドパレットでカーソルが当たっている項目の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>quickInputList.focusForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォーカス中の項目の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドパレットでカーソルが当たっている項目のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>quickInputList.focusIconForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォーカス中の項目のアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドパレットでカーソルが当たっている項目の右側のギアマークのアイコン、拡張機能の固有アイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>quickInputTitle.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">クイックピッカーのタイトルの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Keybinding label colors(キーバインドラベルカラー)</b></summary><br>


**Keybinding label colors** は、コマンドに関連付けられたキーボードショートカットを表示するラベルに関する色設定である。コマンドパレット、キーボードショートカットエディター、キーボードショートカット記録モーダル、拡張機能のマーケットプレイスページの機能紹介セクションなどで使われる。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>keybindingLabel.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">キーバインドラベルの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドパレットに表示される「Ctrl+Shift+P」などのキー表示の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>keybindingLabel.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">キーバインドラベルの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドパレットに表示される「Ctrl+Shift+P」などのキー表示のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>keybindingLabel.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">キーバインドラベルのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">キー表示を囲む枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>keybindingLabel.bottomBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">キーバインドラベルの下部ボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">キー表示の下端に表示される線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Keyboard shortcut table colors(キーボードショートカットテーブルカラー)</b></summary><br>


**Keyboard shortcut table colors** は、キーボードショートカットエディターのテーブルに関する色設定である。コマンドパレット（`Ctrl`+`Shift`+`P`）を開いて、「Preferences: Open Keyboard Shortcuts」と入力して実行することで表示される。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>keybindingTable.headerBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">キーボードショートカットテーブルのヘッダーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「コマンド」「キーバインド」などの見出し行の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>keybindingTable.rowsBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">キーボードショートカットテーブルの交互行の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">表の1行おきに付く背景色（縞模様）</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Integrated Terminal colors(統合ターミナルカラー)</b></summary><br>


**Integrated Terminal colors** は、統合ターミナルに関する色設定である。`terminalSymbolIcon`が出現するターミナルの補完候補はsettings.json に `"terminal.integrated.suggest.enabled": true` を追加することで表示される。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">統合ターミナルのビューポートの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナル全体の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナル内の分割ペインを区切るボーダー色（デフォルトは <code>panel.border</code>）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルを分割表示したときの境界線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">統合ターミナルのデフォルト文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルのデフォルトテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.ansiBlack</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルのANSI「Black」カラー</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>black</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.ansiBlue</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルのANSI「Blue」カラー</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>blue</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.ansiBrightBlack</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルのANSI「BrightBlack」カラー</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>bright black</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.ansiBrightBlue</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルのANSI「BrightBlue」カラー</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>bright blue</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.ansiBrightCyan</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルのANSI「BrightCyan」カラー</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>bright cyan</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.ansiBrightGreen</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルのANSI「BrightGreen」カラー</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>bright green</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.ansiBrightMagenta</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルのANSI「BrightMagenta」カラー</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>bright magenta</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.ansiBrightRed</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルのANSI「BrightRed」カラー</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>bright red</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.ansiBrightWhite</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルのANSI「BrightWhite」カラー</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>bright white</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.ansiBrightYellow</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルのANSI「BrightYellow」カラー</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>bright yellow</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.ansiCyan</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルのANSI「Cyan」カラー</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>cyan</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.ansiGreen</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルのANSI「Green」カラー</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>green</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.ansiMagenta</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルのANSI「Magenta」カラー</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>magenta</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.ansiRed</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルのANSI「Red」カラー</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>red</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.ansiWhite</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルのANSI「White」カラー</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>white</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.ansiYellow</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルのANSI「Yellow」カラー</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>yellow</code> カラーコードを使った出力テキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.selectionBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルの選択範囲の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナル上でテキストを選択したときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.selectionForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルの選択範囲の文字色（nullの場合は最小コントラスト比が適用される）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナル上で選択中のテキストの文字色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.inactiveSelectionBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォーカスのないターミナルの選択範囲の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在操作していないターミナルでの選択中テキストの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.findMatchBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナル内検索の現在のマッチ箇所の背景色（半透明）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナル内の検索でマッチ箇所の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.findMatchBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナル内検索の現在のマッチ箇所のボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナル内の検索でマッチ箇所の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.findMatchHighlightBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナル内検索のその他のマッチ箇所の背景色（半透明）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナル内検索で選択していないマッチ箇所の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.findMatchHighlightBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナル内検索のその他のマッチ箇所のボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナル内検索で選択していないマッチ箇所の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.hoverHighlightBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナル内のリンクにホバーしたときのハイライト色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルに出力されたURLなどにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalCursor.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルカーソルの背景色（ブロックカーソルに重なる文字色の調整用）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ブロックカーソルが文字に重なったときの文字色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalCursor.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルカーソルの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナル上の点滅するカーソル</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.dropBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナル上にドラッグしたときの背景色（半透明）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ファイルをターミナルにドラッグしているときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.tab.activeBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パネル内のターミナルタブの側面のボーダー色（デフォルトは <code>tab.activeBorder</code>）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの下に表示されるパネル内で選択中のターミナルタブの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalCommandDecoration.defaultBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルコマンド装飾のデフォルト背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンド実行結果を示すターミナルの左側の丸いアイコンの標準背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalCommandDecoration.successBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">成功したコマンドのターミナルコマンド装飾の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">正常終了したコマンドを示すターミナルの行の左端の丸いアイコンの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalCommandDecoration.errorBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">失敗したコマンドのターミナルコマンド装飾の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラー終了したコマンドを示すターミナルの行の左端の丸いアイコンの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalOverviewRuler.cursorForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">概要ルーラーのカーソル色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナル右端のスクロールバーの下に重なっている概要ルーラー上のカーソル位置マーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalOverviewRuler.findMatchForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナル内検索の概要ルーラーのマッチマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナル右端のスクロールバーの下に重なっている概要ルーラー上の検索ワードと一致した箇所のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalStickyScroll.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルのスティッキースクロールオーバーレイの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スクロール時にターミナルの上部に固定表示されるコマンド行の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalStickyScroll.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルのスティッキースクロールオーバーレイのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スクロール時にターミナルの上部に固定表示されるコマンド行の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalStickyScrollHover.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時のターミナルのスティッキースクロールオーバーレイの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スクロール時にターミナルの上部に固定表示されるコマンド行にホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminal.initialHintForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルの初期ヒントの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">新規ターミナルを開いたときに表示されるヒントテキスト(参考: [Consider defaulting terminal.integrated.initialHint to false](https://github.com/posit-dev/positron/issues/13227))</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalOverviewRuler.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">概要ルーラー左側のボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナル右端のスクロールバーの下に重なっている概要ルーラーの左の境界線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalCommandGuide.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドガイドの文字色（コマンドとその出力の左側にホバー時表示）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンド実行結果にホバーしたときに左に表示されるガイド線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalSymbolIcon.aliasForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エイリアスアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルに <code>g</code> などエイリアスの一部を入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalSymbolIcon.branchForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ブランチアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルで <code>git checkout</code> の後に入力したときに表示されるブランチ名補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalSymbolIcon.commitForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コミットアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルで <code>git show</code> の後に入力したときに表示されるコミット補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalSymbolIcon.flagForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フラグアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルで <code>ls -</code> のように <code>-</code> を入力したときに表示されるフラグ補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalSymbolIcon.optionForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">オプションアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルで <code>--</code> のように長いオプション名を入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalSymbolIcon.optionValueForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">enumメンバーアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ターミナルでオプションの後にTabキーを押したときに表示される選択可能な値（例：<code>--color=</code> の後の <code>always</code>/<code>never</code>）の補完候補アイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalSymbolIcon.methodForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">メソッドアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">npmスクリプトなどコマンド内のサブコマンドを入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalSymbolIcon.argumentForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">引数アイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドの後にスペースを入力したときに表示される引数候補のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalSymbolIcon.inlineSuggestionForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インライン提案アイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">過去に実行したコマンドの履歴から薄く表示されるインライン補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalSymbolIcon.fileForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ファイルアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>cat</code> などの後にファイル名を入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalSymbolIcon.folderForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォルダーアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>cd</code> の後にフォルダー名を入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalSymbolIcon.pullRequestDoneForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">完了したプルリクエストアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">GitHub CLI（<code>gh pr</code> など）でクローズ済みPR番号を入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalSymbolIcon.pullRequestForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">プルリクエストアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">GitHub CLIでオープン中のPR番号を入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalSymbolIcon.remoteForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">リモートアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>git push</code> の後にリモート名を入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalSymbolIcon.stashForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スタッシュアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>git stash apply</code> の後にスタッシュ名を入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalSymbolIcon.symbolText</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">プレーンテキスト提案の文字色（ターミナルサジェストウィジェットに表示）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">種別の判別がつかない単純な文字列補完候補のアイコン色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalSymbolIcon.symbolicLinkFileForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">シンボリックリンクファイルアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>cat</code> などの後にシンボリックリンクされたファイル名を入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalSymbolIcon.symbolicLinkFolderForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">シンボリックリンクフォルダーアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>cd</code> の後にシンボリックリンクされたフォルダー名を入力したときに表示される補完候補のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>terminalSymbolIcon.tagForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">タグアイコンの色（ターミナルサジェストウィジェットに表示）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>git checkout</code> の後にタグ名を入力したときに表示される補完候補のアイコン</td>
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


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugToolBar.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグツールバーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグツールバーのの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugToolBar.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグツールバーのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグツールバーの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.stackFrameHighlightBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内の最上位スタックフレームのハイライト背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中にブレークポイントで現在一時停止（ブレーク）している、エディター内の実行中のコード行（スタックフレーム）の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.focusedStackFrameHighlightBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内のフォーカス中スタックフレームのハイライト背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中にブレークポイントで現在一時停止（ブレーク）している、エディター内で選択している実行中のコード行（スタックフレーム）の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.inlineValuesForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグのインライン値表示の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中にエディターのコード行末に表示される変数の値のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.inlineValuesBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグのインライン値表示の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中にエディターのコード行末に表示される変数の値の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugView.exceptionLabelForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">例外で停止したときのコールスタックビューのラベルの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ時で例外が発生したときにエディターのコード行間に表示されるラベルのテキスト(参考: [Ability to hide/show VSCode Exception area](https://github.com/microsoft/vscode/issues/88217))</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugView.exceptionLabelBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">例外で停止したときのコールスタックビューのラベルの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ時で例外が発生したときにエディターのコード行間に表示されるラベルの背景(参考: [Ability to hide/show VSCode Exception area](https://github.com/microsoft/vscode/issues/88217))</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugView.stateLabelForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コールスタックの状態ラベルの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中のサイドバーの下部にあるコールスタックビューに表示される「一時停止中」などの状態ラベルのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugView.stateLabelBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コールスタックビューの状態ラベルの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中のサイドバーの下部にあるコールスタックビューに表示される「一時停止中」などの状態ラベルの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugView.valueChangedHighlight</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグビューで値が変化したときのハイライト色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中のサイドバーの下部にある変数ビューで前回と値が変わった変数のハイライト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugTokenExpression.name</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグビューのトークン名の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中のサイドバーの下部にある変数ビューやウォッチ式に表示される変数名のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugTokenExpression.value</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグビューのトークン値の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中のサイドバーの下部にある変数ビューやウォッチ式に表示される変数の値のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugTokenExpression.string</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグビューの文字列値の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中のサイドバーの下部にある変数ビューで文字列型の値のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugTokenExpression.boolean</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグビューの真偽値の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中のサイドバーの下部にある変数ビューで <code>true</code>/<code>false</code> 値のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugTokenExpression.number</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグビューの数値の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中のサイドバーの下部にある変数ビューで数値型の値のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugTokenExpression.error</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグビューの式エラーの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中のサイドバーの下部にあるウォッチ式が評価できないときのエラーテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugTokenExpression.type</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグビューのトークン型の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中のサイドバーの下部にある変数ビューやウォッチ式に表示される変数の型名のテキスト</td>
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


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.runAction</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内の「実行」アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内のテストされる関数の行番号の左に表示される再生ボタンアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.iconErrored</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テストエクスプローラーの「エラー」アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのテストエクスプローラーでエラーになったテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.iconFailed</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テストエクスプローラーの「失敗」アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのテストエクスプローラーで失敗したテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.iconPassed</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テストエクスプローラーの「成功」アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのテストエクスプローラーで成功したテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.iconQueued</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テストエクスプローラーの「待機中」アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのテストエクスプローラーで実行待ちのテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.iconUnset</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テストエクスプローラーの「未実行」アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのテストエクスプローラーでまだ実行されていないテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.iconSkipped</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テストエクスプローラーの「スキップ」アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのテストエクスプローラーでスキップされたテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.iconErrored.retired</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">古くなった「エラー」アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのテストエクスプローラーでコード変更後、再実行されていないエラー状態のテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.iconFailed.retired</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">古くなった「失敗」アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのテストエクスプローラーでコード変更後、再実行されていない失敗状態のテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.iconPassed.retired</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">古くなった「成功」アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのテストエクスプローラーでコード変更後、再実行されていない成功状態のテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.iconQueued.retired</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">古くなった「待機中」アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのテストエクスプローラーでコード変更後、再実行されていない待機状態のテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.iconUnset.retired</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">古くなった「未実行」アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのテストエクスプローラーでコード変更後、再実行されていない未実行のテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.iconSkipped.retired</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">古くなった「スキップ」アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのテストエクスプローラーでコード変更後、再実行されていないスキップ状態のテスト項目の左にあるアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.peekBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビューのボーダーと矢印の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テスト結果を表示するエディター内のピークビュー(<code>Alt</code> + <code>F12</code>で表示)の枠線・矢印</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.peekHeaderBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ピークビューのボーダーと矢印の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テスト結果を表示するエディター内のピークビュー(<code>Alt</code> + <code>F12</code>で表示)のヘッダー背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.message.error.lineBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インライン表示されるエラーメッセージ横のマージン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内のエラー部分の右に表示されるテストエラーメッセージの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.message.info.decorationForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インライン表示されるテスト情報メッセージの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内のエラー部分の右に表示されるテスト情報メッセージのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.message.info.lineBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インライン表示される情報メッセージ横のマージン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内のエラー部分の右に表示されるテスト情報メッセージの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.messagePeekBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ログメッセージをピーク表示する際のボーダーと矢印の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テストログメッセージのエディター内のピークビューの枠線・矢印</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.messagePeekHeaderBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ログメッセージをピーク表示する際のヘッダー背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テストログメッセージのエディター内のピークビューのヘッダー背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.coveredBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カバレッジが取れたテキストの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「カバレッジ付きで実行（Run Test with Coverage）」を実行したとき、コードカバレッジでカバーされたエディター内の行の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.coveredBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カバレッジが取れたテキストのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「カバレッジ付きで実行（Run Test with Coverage）」を実行したとき、コードカバレッジでカバーされたエディター内の行の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.coveredGutterBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カバレッジが取れた範囲のガター色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「カバレッジ付きで実行（Run Test with Coverage）」を実行したとき、コードカバレッジでカバーされたエディター内の行の左端マーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.uncoveredBranchBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カバーされていない分岐に表示されるウィジェットの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カバレッジが取れていない条件分岐を示すウィジェットの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.uncoveredBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カバレッジが取れていないテキストの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「カバレッジ付きで実行（Run Test with Coverage）」を実行したとき、コードカバレッジでカバーされていないエディター内の行の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.uncoveredBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カバレッジが取れていないテキストのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「カバレッジ付きで実行（Run Test with Coverage）」を実行したとき、コードカバレッジでカバーされていないエディター内の行の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.uncoveredGutterBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カバレッジが取れていない範囲のガター色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「カバレッジ付きで実行（Run Test with Coverage）」を実行したとき、コードカバレッジでカバーされていないエディター内の行の左端マーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.coverCountBadgeBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">実行回数を示すバッジの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カバレッジレポートの実行回数バッジの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.coverCountBadgeForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">実行回数を示すバッジの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">カバレッジレポートの実行回数バッジのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.message.error.badgeBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インライン表示されるテストエラーメッセージのバッジ背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テストエラーメッセージのバッジの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.message.error.badgeBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インライン表示されるテストエラーメッセージのバッジボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テストエラーメッセージのバッジの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>testing.message.error.badgeForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インライン表示されるテストエラーメッセージのバッジ文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テストエラーメッセージのバッジのテキスト</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Welcome page colors(ウェルカムページカラー)</b></summary><br>


**Welcome page colors** は、VSCode起動時に表示されるウェルカムページに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>welcomePage.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウェルカムページの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウェルカムページ全体の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>welcomePage.progress.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウェルカムページのプログレスバーの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウェルカムページに表示される進捗バーの前景部分</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>welcomePage.progress.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウェルカムページのプログレスバーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウェルカムページに表示される進捗バーの背景部分</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>welcomePage.tileBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウェルカムページのタイルの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウェルカムページに並ぶ各機能紹介タイルの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>welcomePage.tileHoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウェルカムページのタイルのホバー時背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">機能紹介タイルにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>welcomePage.tileBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウェルカムページのタイルのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">機能紹介タイルの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>walkThrough.embeddedEditorBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インタラクティブプレイグラウンドの埋め込みエディターの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チュートリアル内に埋め込まれたコードエディターの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>walkthrough.stepTitle.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ウォークスループ各ステップの見出しの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チュートリアルの各手順の見出しテキスト</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Git colors(Gitカラー)</b></summary><br>


**Git colors** は、Git関連の装飾に関する色設定である。サイドバーのエクスプローラーやソース管理ビューに使用される。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>gitDecoration.addedResourceForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">追加されたGitリソースの色（ファイルラベルやSCMビューレットで使用）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーやソース管理ビューで新規追加されたファイル名の文字色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>gitDecoration.modifiedResourceForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更されたGitリソースの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーやソース管理ビューで変更されたファイル名の文字色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>gitDecoration.deletedResourceForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">削除されたGitリソースの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーやソース管理ビューで削除されたファイル名の文字色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>gitDecoration.renamedResourceForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">リネーム・コピーされたGitリソースの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーやソース管理ビューでリネームされたファイル名の文字色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>gitDecoration.stageModifiedResourceForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ステージ済み変更の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ソース管理ビューでステージされた変更ファイル名の文字色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>gitDecoration.stageDeletedResourceForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ステージ済み削除の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ソース管理ビューでステージされた削除ファイル名の文字色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>gitDecoration.untrackedResourceForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未追跡のGitリソースの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エクスプローラーやソース管理ビューで未追跡（Untracked）ファイル名の文字色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>gitDecoration.ignoredResourceForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">無視されたGitリソースの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>.gitignore</code> で無視されているファイル名の文字色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>gitDecoration.conflictingResourceForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コンフリクトしているGitリソースの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マージコンフリクトが発生しているファイル名の文字色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>gitDecoration.submoduleResourceForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サブモジュールリソースの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Gitサブモジュールのフォルダー名の文字色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>git.blame.editorDecorationForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">blame表示のエディター装飾色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター行末に表示されるGit blame情報（最終変更者など）のテキスト</td>
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


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>scmGraph.historyItemHoverLabelForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">履歴項目ホバー時のラベルの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コミット履歴グラフでコミット項目にホバーしたときのポップアップのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>scmGraph.foreground1</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ソースコントロールグラフの色（1）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コミット履歴グラフの1本目のブランチラインの色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>scmGraph.foreground2</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ソースコントロールグラフの色（2）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コミット履歴グラフの2本目のブランチラインの色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>scmGraph.foreground3</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ソースコントロールグラフの色（3）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コミット履歴グラフの3本目のブランチラインの色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>scmGraph.foreground4</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ソースコントロールグラフの色（4）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コミット履歴グラフの4本目のブランチラインの色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>scmGraph.foreground5</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ソースコントロールグラフの色（5）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コミット履歴グラフの5本目のブランチラインの色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>scmGraph.historyItemHoverAdditionsForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">履歴項目ホバー時の追加行数の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コミット履歴グラフでコミット項目にホバーしたときのポップアップに表示される「+N」のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>scmGraph.historyItemHoverDeletionsForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">履歴項目ホバー時の削除行数の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コミット履歴グラフでコミット項目にホバーしたときのポップアップに表示される「-N」のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>scmGraph.historyItemRefColor</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">履歴項目の参照（ブランチ・タグ）の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コミット履歴グラフに表示されるブランチ名やタグ名のラベル色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>scmGraph.historyItemRemoteRefColor</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">履歴項目のリモート参照の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コミット履歴グラフに表示されるリモートブランチ名のラベル色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>scmGraph.historyItemBaseRefColor</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">履歴項目のベース参照の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コミット履歴グラフに表示されるベースブランチ名のラベル色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>scmGraph.historyItemHoverDefaultLabelForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">履歴項目ホバー時のデフォルトラベルの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コミット項目にホバーしたときのポップアップの標準テキスト色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>scmGraph.historyItemHoverDefaultLabelBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">履歴項目ホバー時のデフォルトラベルの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コミット項目にホバーしたときのポップアップの標準背景色</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Settings Editor colors(設定エディターカラー)</b></summary><br>


**Settings Editor colors** は、コマンドパレットで`Preferences: Open Settings (UI)` で開けるGUI設定エディターに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.headerForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">セクション見出しまたはアクティブなタイトルの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面の「エディター」などのセクション見出しのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.modifiedItemIndicator</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更された設定を示す線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デフォルト値から変更した設定項目の左に表示される縦線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.dropdownBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ドロップダウンの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面のドロップダウン選択欄の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.dropdownForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ドロップダウンの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面のドロップダウン選択欄のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.dropdownBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ドロップダウンのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面のドロップダウン選択欄の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.dropdownListBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ドロップダウンリストのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面のドロップダウンを開いたときの選択肢リストの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.checkboxBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チェックボックスの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面のチェックボックスの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.checkboxForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チェックボックスの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面のチェックボックスのチェックマーク</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.checkboxBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チェックボックスのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面のチェックボックスの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.rowHoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時の設定行の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定項目の行にホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.textInputBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テキスト入力ボックスの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面の文字列入力欄の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.textInputForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テキスト入力ボックスの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面の文字列入力欄のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.textInputBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テキスト入力ボックスのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面の文字列入力欄の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.numberInputBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">数値入力ボックスの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面の数値入力欄の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.numberInputForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">数値入力ボックスの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面の数値入力欄のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.numberInputBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">数値入力ボックスのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面の数値入力欄の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.focusedRowBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォーカス中の設定行の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">キーボード操作によって選択された設定項目の行の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.focusedRowBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォーカス中の設定行の上下ボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">キーボード操作によって選択された設定項目の行の上下の線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.headerBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ヘッダーコンテナのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面上部のヘッダー部分の下の境界線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.sashBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定エディターの分割ビューのサッシュ（境界線）の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>settings.settingsHeaderHoverForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">セクション見出しまたはホバー中タイトルの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">設定画面のセクション見出しにホバーしたときのテキスト色</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Breadcrumbs colors(ブレッドクラムカラー)</b></summary><br>


**Breadcrumbs colors** は、タブとエディタの間にあるどのファイルを開いているかを階層構造で示すブレッドクラムナビゲーションに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>breadcrumb.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ブレッドクラム項目の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター上部に表示されるファイルパスやシンボル階層のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>breadcrumb.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ブレッドクラム項目の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ブレッドクラム全体の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>breadcrumb.focusForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォーカス中のブレッドクラム項目の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー・キーボード操作でフォーカスされたブレッドクラム項目のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>breadcrumb.activeSelectionForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中のブレッドクラム項目の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">クリックして選択中のブレッドクラム項目のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>breadcrumbPicker.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ブレッドクラム項目ピッカーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ブレッドクラムをクリックして開くドロップダウンの背景</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Snippets colors(スニペットカラー)</b></summary><br>


**Snippets colors** は、入力補完リストに出てくる、スニペット（予め登録していたコード定型文）に関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.snippetTabstopHighlightBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スニペットのタブストップのハイライト背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スニペット展開後、Tabキーで移動可能な途中の入力箇所（登録したスニペット内の<code>$1</code> や <code>$2</code> など）の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.snippetTabstopHighlightBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スニペットのタブストップのハイライトボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スニペット展開後、Tabキーで移動可能な途中の入力箇所（登録したスニペット内の<code>$1</code> や <code>$2</code> など）の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.snippetFinalTabstopHighlightBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スニペットの最終タブストップのハイライト背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スニペット入力の最後にカーソルが移動する箇所の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editor.snippetFinalTabstopHighlightBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スニペットの最終タブストップのハイライトボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スニペット入力の最後にカーソルが移動する箇所の枠線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Symbol Icons colors(シンボルアイコンカラー)</b></summary><br>


**Symbol Icons colors** は、サイドバーのエクスプローラーの最下部にあるアウトラインビュー、ブレッドクラムナビゲーション、サジェストウィジェットに表示されるシンボルアイコンに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.arrayForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">配列シンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される配列変数のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.booleanForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">真偽値シンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される真偽値変数のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.classForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">クラスシンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるクラスのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.colorForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">色シンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">CSSファイルなどで色を表すシンボルのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.constantForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">定数シンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される定数のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.constructorForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コンストラクタシンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるコンストラクタのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.enumeratorForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">列挙型シンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるenum（列挙型）のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.enumeratorMemberForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">列挙型メンバーシンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるenumメンバーのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.eventForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">イベントシンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるイベントのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.fieldForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フィールドシンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるクラスのフィールドのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.fileForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ファイルシンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サジェストウィジェットに表示されるファイルのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.folderForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォルダーシンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サジェストウィジェットに表示されるフォルダーのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.functionForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">関数シンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される関数のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.interfaceForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インターフェースシンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるインターフェースのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.keyForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">キーシンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">JSONファイルなどのキーを表すシンボルのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.keywordForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">キーワードシンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サジェストウィジェットに表示される言語キーワードのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.methodForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">メソッドシンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるメソッドのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.moduleForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">モジュールシンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるモジュールのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.namespaceForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">名前空間シンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される名前空間のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.nullForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">nullシンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サジェストウィジェットに表示される <code>null</code> のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.numberForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">数値シンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される数値変数のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.objectForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">オブジェクトシンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるオブジェクト変数のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.operatorForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">演算子シンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サジェストウィジェットに表示される演算子のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.packageForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">パッケージシンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるパッケージのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.propertyForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">プロパティシンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるプロパティのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.referenceForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">参照シンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される参照のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.snippetForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">スニペットシンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サジェストウィジェットに表示されるスニペットのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.stringForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">文字列シンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される文字列変数のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.structForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">構造体シンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される構造体のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.textForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">テキストシンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サジェストウィジェットに表示されるテキストのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.typeParameterForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">型パラメータシンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示されるジェネリック型パラメータのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.unitForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">単位シンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される単位のアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>symbolIcon.variableForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変数シンボルのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのエクスプローラーの最下部にあるアウトラインビューに表示される変数のアイコン</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Debug Icons colors(デバッグアイコンカラー)</b></summary><br>


**Debug Icons colors** は、デバッグ関連のアイコンに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugIcon.breakpointForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ブレークポイントのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター左端に設置したブレークポイントのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugIcon.breakpointDisabledForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">無効化されたブレークポイントのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">一時的に無効化したブレークポイントのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugIcon.breakpointUnverifiedForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未検証のブレークポイントのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッガーがまだ確認していないブレークポイントのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugIcon.breakpointCurrentStackframeForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在のブレークポイントスタックフレームのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中に現在停止しているスタックフレームのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugIcon.breakpointStackframeForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">全てのブレークポイントスタックフレームのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグ中のコールスタック上にあるブレークポイントのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugIcon.startForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグツールバーの「開始」アイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>F5</code>でデバッグを実行したときに右上に現れるデバッグツールバーの再生ボタンアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugIcon.pauseForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグツールバーの「一時停止」アイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>F5</code>でデバッグを実行したときに右上に現れるデバッグツールバーの一時停止ボタンアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugIcon.stopForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグツールバーの「停止」アイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>F5</code>でデバッグを実行したときに右上に現れるデバッグツールバーの停止ボタンアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugIcon.disconnectForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグツールバーの「切断」アイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>F5</code>でデバッグを実行したときに右上に現れるデバッグツールバーの切断ボタンアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugIcon.restartForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグツールバーの「再起動」アイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>F5</code>でデバッグを実行したときに右上に現れるデバッグツールバーの再起動ボタンアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugIcon.stepOverForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグツールバーの「ステップオーバー」アイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>F5</code>でデバッグを実行したときに右上に現れるデバッグツールバーの次の行に進むボタンアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugIcon.stepIntoForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグツールバーの「ステップイン」アイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>F5</code>でデバッグを実行したときに右上に現れるデバッグツールバーの関数内部に入るボタンアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugIcon.stepOutForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグツールバーの「ステップアウト」アイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>F5</code>でデバッグを実行したときに右上に現れるデバッグツールバーの関数から抜けるボタンアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugIcon.continueForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグツールバーの「続行」アイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>F5</code>でデバッグを実行したときに右上に現れるデバッグツールバーの次のブレークポイントまで実行するボタンアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugIcon.stepBackForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグツールバーの「ステップバック」アイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>F5</code>でデバッグを実行したときに右上に現れるデバッグツールバーの1ステップ前に戻るボタンアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugConsole.infoForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグREPLコンソールの情報メッセージの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>F5</code>でデバッグを実行したときにエディターの下のパネルのデバッグコンソールに表示される情報メッセージのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugConsole.warningForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグREPLコンソールの警告メッセージの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>F5</code>でデバッグを実行したときにエディターの下のパネルのデバッグコンソールに表示される警告メッセージのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugConsole.errorForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグREPLコンソールのエラーメッセージの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>F5</code>でデバッグを実行したときにエディターの下のパネルのデバッグコンソールに表示されるエラーメッセージのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugConsole.sourceForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグREPLコンソールのソースファイル名の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>F5</code>でデバッグを実行したときにエディターの下のパネルのデバッグコンソールに表示される出力元ファイル名のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>debugConsoleInputIcon.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">デバッグコンソール入力マーカーアイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>F5</code>でデバッグを実行したときにエディターの下のパネルのデバッグコンソールの入力欄に表示される <code>></code> のようなマーカーアイコン</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Notebook colors(ノートブックカラー)</b></summary><br>


**Notebook colors** は、Jupyter Notebookなどのノートブックエディターに関する色設定である。Notebookは、拡張機能から「Jupyter」をインストールし、ipynbファイルを作成することで表示される。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebook.editorBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ノートブックの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ノートブックエディター全体の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebook.cellBorderColor</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ノートブックセルのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">各セルを囲む枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebook.cellHoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時のセルの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">セルにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebook.cellInsertionIndicator</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">セル挿入インジケーターの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">セルとセルの間にマウスを置いたときに表示される挿入位置の線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebook.cellStatusBarItemHoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ノートブックセルステータスバー項目のホバー時の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">セル下部のステータスバー項目にホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebook.cellToolbarSeparator</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">セル下部ツールバーの区切り線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">セル下部に表示されるアイコン群の間の区切り線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebook.cellEditorBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ノートブックセルエディターの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">セル内のコード入力部分の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebook.focusedCellBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォーカス中のセルの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">編集モードでフォーカスされているセルの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebook.focusedCellBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォーカス中のセルのフォーカスインジケーターのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォーカスされているセルを示す枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebook.focusedEditorBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ノートブックセルエディターのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォーカスされているセル内のコード入力部分の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebook.inactiveFocusedCellBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">主フォーカスがエディター外にあるときのセルの上下ボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebook.inactiveSelectedCellBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">複数セルが選択されているときのセルのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">複数のセルをまとめて選択しているときの各セルの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebook.outputContainerBackgroundColor</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ノートブック出力コンテナの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コード実行結果が表示される部分の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebook.outputContainerBorderColor</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ノートブック出力コンテナのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コード実行結果が表示される部分の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebook.selectedCellBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中のセルの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コマンドモードで選択されているセルの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebook.selectedCellBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中（フォーカスなし）のセルの上下ボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択されているがフォーカスはされていないセルの上下の線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebook.symbolHighlightBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ハイライトされたセルの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アウトラインなどから移動した先のセルのハイライト背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebookScrollbarSlider.activeBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">クリック時のノートブックスクロールバースライダーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ノートブックのスクロールバーにあるスライダーをクリックしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebookScrollbarSlider.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ノートブックスクロールバースライダーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ノートブックのスクロールバーにあるスライダーの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebookScrollbarSlider.hoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時のノートブックスクロールバースライダーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ノートブックのスクロールバーにあるスライダーにホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebookStatusErrorIcon.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">セルステータスバーのエラーアイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">セル実行がエラーになったときのステータスバーのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebookStatusRunningIcon.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">セルステータスバーの実行中アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">セルが実行中のときのステータスバーのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebookStatusSuccessIcon.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">セルステータスバーの成功アイコンの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">セル実行が成功したときのステータスバーのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>notebookEditorOverviewRuler.runningCellForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">概要ルーラーの実行中セル装飾の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ノートブック右端のスクロールバーの下に重なっている、概要ルーラーで実行中セルを示すマーカー</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Chart colors(チャートカラー)</b></summary><br>


**Chart colors** は、VSCode内のチャート表示に関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>charts.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャート内テキストのコントラスト色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャートに表示されるラベルや数値のテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>charts.lines</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャート内の線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">グラフの罫線やグリッド線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>charts.red</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャート内の赤色要素の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">グラフ内で赤色に割り当てられたデータ系列</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>charts.blue</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャート内の青色要素の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">グラフ内で青色に割り当てられたデータ系列</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>charts.yellow</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャート内の黄色要素の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">グラフ内で黄色に割り当てられたデータ系列</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>charts.orange</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャート内の橙色要素の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">グラフ内で橙色に割り当てられたデータ系列</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>charts.green</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャート内の緑色要素の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">グラフ内で緑色に割り当てられたデータ系列</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>charts.purple</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャート内の紫色要素の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">グラフ内で紫色に割り当てられたデータ系列</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>chart.line</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャートの線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">グラフの折れ線部分の色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>chart.axis</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャートの軸の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">グラフのX軸・Y軸の線の色</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>chart.guide</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">チャートのガイド線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">グラフの目盛りを示す補助線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Ports colors(ポートカラー)</b></summary><br>


**Ports colors** は、ポート転送機能に関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>ports.iconRunningProcessForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">実行中プロセスが関連付けられたポートのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディターの下にあるパネルの「ポート」で実行中プロセスがあるポートのアイコン</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Comments View colors(コメントビューカラー)</b></summary><br>


**Comments View colors** は、コメントビューに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>commentsView.resolvedIcon</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">解決済みコメントのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コメントビューで解決済みとされたコメントのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>commentsView.unresolvedIcon</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未解決コメントのアイコン色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コメントビューで未解決のコメントのアイコン</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Action Bar colors(アクションバーカラー)</b></summary><br>


**Action Bar colors** は、アクションバーに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>actionBar.toggledBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">アクションバーでトグルされたアクション項目の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">オン/オフを切り替えるトグルボタンが有効時の背景</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Simple Find Widget colors(シンプル検索ウィジェットカラー)</b></summary><br>


**Simple Find Widget colors** は、エディタ上の通常の検索（Ctrl + F）ではなく、「出力（Output）パネル」や「デバッグコンソール（Debug Console）」の文字を検索するときのシンプル検索ウィジェットに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>simpleFindWidget.sashBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サッシュ（境界線）のボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">シンプル検索ウィジェットのリサイズ用境界線</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Gauge colors(ゲージカラー)</b></summary><br>


**Gauge colors** は、ゲージ表示に関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>gauge.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ゲージの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>gauge.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ゲージの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>gauge.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ゲージのボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>gauge.warningBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ゲージの警告時の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>gauge.warningForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ゲージの警告時の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>gauge.errorBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ゲージのエラー時の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>gauge.errorForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ゲージのエラー時の文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Markdown(マークダウン)</b></summary><br>


**Markdown** は、Markdownのアラート（注釈ブロック）に関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>markdownAlert.note.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Markdownの「Note」アラートの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">mdファイル内に<code>> [!NOTE]</code> で書かれた注釈ブロックのプレビューのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>markdownAlert.tip.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Markdownの「Tip」アラートの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">mdファイル内に<code>> [!TIP]</code> で書かれた注釈ブロックのプレビューのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>markdownAlert.important.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Markdownの「Important」アラートの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">mdファイル内に<code>> [!IMPORTANT]</code> で書かれた注釈ブロックのプレビューのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>markdownAlert.warning.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Markdownの「Warning」アラートの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">mdファイル内に<code>> [!WARNING]</code> で書かれた注釈ブロックのプレビューのテキスト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>markdownAlert.caution.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Markdownの「Caution」アラートの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">mdファイル内に<code>> [!CAUTION]</code> で書かれた注釈ブロックのプレビューのテキスト</td>
  </tr>
</tbody>
</table>
</div>

---


</details>
<details>
<summary><b>Agent Session colors(エージェントセッションカラー)</b></summary><br>


**Agent Session colors** は、AIエージェントセッションに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<thead>
  <tr>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">key名</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">役割</th>
    <th style="padding: 12px; border: 1px solid #666; text-align: left;">適用要素の例</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>agentSessionReadIndicator.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エージェントセッションの既読インジケーターの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">AIエージェントとのセッション一覧で既読を示すマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>agentSessionSelectedBadge.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中のエージェントセッション項目のバッジボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中のセッション項目に表示されるバッジの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>agentSessionSelectedUnfocusedBadge.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ビューが非フォーカス時の選択中エージェントセッション項目のバッジボーダー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">操作していないビューで選択中のセッション項目のバッジの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>agentStatusIndicator.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">タイトルバーのエージェントステータスインジケーターの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">タイトルバーに表示されるAIエージェントの状態を示すアイコンの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>aiCustomizationManagement.sashBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Chat Customization Managementエディターの分割ビューのサッシュ（境界線）の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">AIカスタマイズ管理画面の2分割表示の境界線</td>
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
