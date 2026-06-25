## Editor widget colors(エディターウィジェットカラー)

**Editor widget colors** は、エディターコンテンツの手前に表示されるウィジェットに関する色設定である。Find(`Ctrl`+`F`)/Replace(`Ctrl`+`H`) ダイアログ、サジェストウィジェット(変数名や関数の候補のポップアップ、`Ctrl`+`Space`で表示)、エディターホバー(コード内の関数や変数にカーソルを合わせたときに、その型や使い方を教える吹き出しのポップアップ)などが該当する。

### 基本ウィジェット


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

### サジェストウィジェット


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

### ホバーウィジェット


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

### ゴーストテキスト


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

### スティッキースクロール

巨大なファイルをスクロールしているとき、現在どの関数やクラス、ネストの中にいるのかを明確にするために、親要素の行（定義部分）をエディタの最上部に固定して表示する機能である。
`"editor.stickyScroll.enabled": true`とすることで表示される。


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

### デバッグ例外ウィジェット

デバッグ中に例外で停止したときにエディター内に表示されるピークビュー。
(参考: [Extension API to Access ExceptionWidget (or ZoneWidget)](https://github.com/microsoft/vscode/issues/140752)
)


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

### エディターマーカーナビゲーション

「次のエラーまたは警告へ移動(`F8`)」を実行した際に、コードのすぐ下に出現するエラーメッセージ表示用の専用ウィジェット（ダイアログボックス）です。


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

---

[もどる](../README.md)
