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