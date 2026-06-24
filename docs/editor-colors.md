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