## Merge conflicts colors(マージコンフリクトカラー)

**Merge conflicts colors** は、エディター内に特殊な差分範囲（マージコンフリクト）があるときに表示される装飾に関する色設定である。

### インラインマージコンフリクト


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
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>merge.currentHeaderBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在の変更（Current）のヘッダー背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">`<<<<<<< HEAD` のヘッダー部分の背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>merge.currentContentBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在の変更（Current）のコンテンツ背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">`<<<<<<< HEAD` のコード部分の背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>merge.incomingHeaderBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">取り込む変更（Incoming）のヘッダー背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">`<<<<<<< somebranch` のヘッダー部分の背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>merge.incomingContentBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">取り込む変更（Incoming）のコンテンツ背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">`<<<<<<< somebranch` のコード部分の背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>merge.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ヘッダーと区切り線の境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コンフリクト各セクションのヘッダーや区切り線の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>merge.commonContentBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">共通の祖先（Common ancestor）のコンテンツ背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">3-way diffでの`<<<<<<< common`のコード部分の背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>merge.commonHeaderBackground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">共通の祖先（Common ancestor）のヘッダー背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">3-way diffでの`<<<<<<< common`ののヘッダー部分の背景（半透明）</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.currentContentForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">現在の変更（Current）の概要ルーラーのマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター右端のスクロールバーの下に重なっている、エディター内の装飾の概要を示す欄で、現在の変更部分（Current）を示すマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.incomingContentForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">取り込む変更（Incoming）の概要ルーラーのマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター右端のスクロールバーの下に重なっている、エディター内の装飾の概要を示す欄で、取り込む変更部分を示すマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.commonContentForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">共通の祖先（Common ancestor）の概要ルーラーのマーカー色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター右端のスクロールバーの下に重なっている、エディター内の装飾の概要を示す欄で、共通部分を示すマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.commentForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">解決済みコメントの概要ルーラー装飾色（不透明）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター右端のスクロールバーの下に重なっている、エディター内の装飾の概要を示す欄で、解決済みコメントを示すマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>editorOverviewRuler.commentUnresolvedForeground</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未解決コメントの概要ルーラー装飾色（不透明）</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">エディター右端のスクロールバーの下に重なっている、エディター内の装飾の概要を示す欄で、未解決のコメントを示すマーカー</td>
  </tr>
</tbody>
</table>

### マージエディター（3-wayマージ）

`3-way merge editor`とは、エディター上に
現在のブランチの更新内容と競合部分が表示される画面(Current, 上部右側画面)
現在のブランチにマージするブランチの更新内容と競合部分が表示される画面(Incoming, 上部左側画面)
競合の解決を行う編集画面(Result, 下画面)
の3画面を表示させてブランチとの競合の解決を行う専用の画面である。
タブの欄の一番右にある"その他の操作..."から「ベースの表示（Show Base）」を押すとIncomingやCurrentに書き換えられる前の、元々のコード(Base)が出現する。


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
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.change.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">変更箇所の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マージエディターで変更がある行の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.change.word.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">単語単位の変更箇所の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">マージエディターで変更された単語部分の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.conflict.unhandledUnfocused.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未処理・非フォーカス時のコンフリクトの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">まだ解決していない、選択していないコンフリクト箇所の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.conflict.unhandledFocused.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未処理・フォーカス時のコンフリクトの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">まだ解決していない、現在選択中のコンフリクト箇所の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.conflict.handledUnfocused.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">処理済み・非フォーカス時のコンフリクトの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">解決済みで、選択していないコンフリクト箇所の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.conflict.handledFocused.border</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">処理済み・フォーカス時のコンフリクトの境界線の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">解決済みで、現在選択中のコンフリクト箇所の枠線</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.conflict.handled.minimapOverViewRuler</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">処理済みコンフリクトのミニマップ／概要ルーラー上の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">右側のファイルのズームアウトを示すミニマップ上の解決済みコンフリクトのマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.conflict.unhandled.minimapOverViewRuler</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">未処理コンフリクトのミニマップ／概要ルーラー上の色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">右側のファイルのズームアウトを示すミニマップ上の未解決コンフリクトのマーカー</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.conflictingLines.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">「Conflicting Lines」テキストの背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">コンフリクトがある行数を示すメッセージの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.changeBase.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ベース（Base）側の変更箇所の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">3-way diffでの元々のコードにおける変更された行の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.changeBase.word.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">ベース（Base）側の単語単位の変更箇所の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">3-way diffでの元々のコードにおける変更された単語部分の背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.conflict.input1.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Input1側の装飾の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">3-way diffでの自分側（Current, Input1）コードの背景</td>
  </tr>
  <tr>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;"><code>mergeEditor.conflict.input2.background</code></td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">Input2側の装飾の背景色</td>
    <td style="padding: 12px; border: 1px solid #666; text-align: left;">3-way diffでのマージ元側（Incoming, Input2）コードの背景</td>
  </tr>
</tbody>
</table>

---

[もどる](../README.md)
