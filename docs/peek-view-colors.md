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