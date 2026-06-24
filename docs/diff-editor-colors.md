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