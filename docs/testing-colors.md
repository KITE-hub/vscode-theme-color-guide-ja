## Testing colors(テストカラー)

**Testing colors** は、テスト関連機能に関する色設定である。
アクティビティバーからテストエクスプローラーを選択すると、サイドバーにテストエクスプローラーが表示される。
参考: [Testing](https://code.visualstudio.com/docs/debugtest/testing)
参考: [VSCodeのPython拡張機能でテストカバレッジ表示機能が追加されました](https://dev.classmethod.jp/articles/python-vscode-test-coverage-view/)


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

---

[もどる](../README.md)
