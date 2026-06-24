<details>
<summary><b>Minimap(ミニマップ)</b></summary><br>


**Minimap** は、エディタの右側に位置する現在のファイルのズームアウトしたものを表示する機能に関する色設定である。コマンドパレット（`Ctrl`+`Shift`+`P`）を開いて、「Toggle Minimap」と入力して実行することで表示される。


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
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimap.findMatchHighlight</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ファイル内検索のマッチ箇所のハイライト色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップ上で検索ワードと一致した箇所のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimap.selectionHighlight</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター上の選択範囲のハイライト色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップ上の現在選択中のテキスト範囲のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimap.errorHighlight</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター上のエラー箇所のハイライト色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エラーがある行のミニマップ上のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimap.warningHighlight</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター上の警告箇所のハイライト色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">警告がある行のミニマップ上のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimap.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップ全体の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimap.selectionOccurrenceHighlight</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">選択中の文字列と同じ語が繰り返し出現する箇所のマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップ上の選択中の単語と一致する箇所のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimap.foregroundOpacity</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップ内に描画される前景要素の不透明度</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップに表示されるコードの縮小テキストの濃さ</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimap.infoHighlight</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">情報レベルのマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップ上の情報通知がある行のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimap.chatEditHighlight</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">保留中の編集領域の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">AI等のインライン編集で未確定の変更箇所のハイライト</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimapSlider.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップスライダーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップ上の現在の表示範囲を示すものの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimapSlider.hoverBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ホバー時のミニマップスライダーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップの表示範囲枠にホバーしたときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimapSlider.activeBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">クリック押下時のミニマップスライダーの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ミニマップの表示範囲枠をクリックして押し込んでいるときの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimapGutter.addedBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">追加された内容を示すミニマップガターの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Git差分で追加された行のミニマップ左端のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimapGutter.modifiedBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更された内容を示すミニマップガターの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Git差分で変更された行のミニマップ左端のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>minimapGutter.deletedBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">削除された内容を示すミニマップガターの色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Git差分で削除された行のミニマップ左端のマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorMinimap.inlineChatInserted</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">インラインチャットで挿入されたコンテンツのマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">AIによって挿入されたコードのミニマップ上のマーカー</td>
  </tr>
</tbody>
</table>
</div>

---


</details>