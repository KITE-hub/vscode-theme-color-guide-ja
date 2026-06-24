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