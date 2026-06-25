## Input control(インプットコントロール)

**Input control** は、検索ビューや Find/Replace ダイアログなどの入力フィールドに関する色設定である。


<table style="table-layout: fixed; width: 100%; border-collapse: collapse;">
<colgroup>
  <col style="width: 25%">
  <col style="width: 35%">
  <col style="width: 40%">
</colgroup>
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

---

[もどる](../README.md)
