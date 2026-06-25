## Integrated Terminal colors(統合ターミナルカラー)

**Integrated Terminal colors** は、統合ターミナルに関する色設定である。`terminalSymbolIcon`が出現するターミナルの補完候補はsettings.json に `"terminal.integrated.suggest.enabled": true` を追加することで表示される。


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

---

[もどる](../README.md)
