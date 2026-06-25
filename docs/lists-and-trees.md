## Lists and trees(リストとツリー)

**Lists and trees** は、ファイルエクスプローラーなどのリスト・ツリーUIに関する色設定である。アクティブなリスト/ツリーはキーボードフォーカスを持ち、非アクティブなものは持たない。


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

---

[もどる](../README.md)
