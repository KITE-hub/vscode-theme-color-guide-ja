<details>
<summary><b>Base colors(ベースカラー)</b></summary><br>


**Base colors** は、VSCode UI 全体に共通して使われるデフォルトの色設定である。各コンポーネントが独自の色を持たない場合のフォールバックとして機能する。


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
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>focusBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">フォーカスされた要素の全体的な境界線の色。各コンポーネントで上書きされない場合に使用するフォールバック値</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">クリックによるフォーカス中のテキストボックス、リストの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">UI 全体のデフォルト文字色。各コンポーネントで上書きされない場合に使用するフォールバック値</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーのテキスト、メニュー項目</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>disabledForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">無効化された要素の文字色。各コンポーネントで上書きされない場合に使用するフォールバック値</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>widget.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内ウィジェットの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Find(<code>Ctrl</code>+<code>F</code>)やQuick Pick(<code>Ctrl</code>+<code>Shift</code>+<code>P</code>) ダイアログの枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>widget.shadow</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター内ウィジェットの影の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Find(<code>Ctrl</code>+<code>F</code>)やQuick Pick(<code>Ctrl</code>+<code>Shift</code>+<code>P</code>) ダイアログの影</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>selection.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ワークベンチ内のテキスト選択時の背景色。エディターやターミナル内の選択には適用されない</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>descriptionForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">補足情報として表示される説明テキストの文字色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"></td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>errorForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラーメッセージ全体の文字色。各コンポーネントで上書きされない場合に使用するフォールバック値</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディタ上のFind(<code>Ctrl</code>+<code>F</code>)でヒットしない文字列を検索したときに表示される"結果はありません。"</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>icon.foreground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ワークベンチ内のアイコンのデフォルトカラー</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーやツールバーのアイコン</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>sash.hoverBorder</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ドラッグ可能なサッシュ（ペイン間の境界線）のクリック、ドラッグ時の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">サイドバーとエディター間の境界線をクリックまたはドラッグしたとき(参考: [VS Code tips — The sash hover border](https://www.youtube.com/watch?v=eU0zxM5kpoc))</td>
  </tr>
</tbody>
</table>
</div>

---


</details>