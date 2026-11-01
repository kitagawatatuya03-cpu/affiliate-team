# FANZA（DMMアフィリエイト）不承認の原因と、サイト・代替ASPの調査

- 作成: researcher ／ 調査日・確認日: 2026-11-01（本書の全URLの確認日は 2026-11-01）
- 背景: オーナーが @mio_ukkari_jimu（https://x.com/mio_ukkari_jimu）で申請 → 「サイトがないため」不承認（strategy/20261025_オーナー決定.md 進捗 2026-11-01）
- ステータス: **リサーチ段階。承認済みではない。** 登録・ログインはしていない

> **調査方法の制約（必読）**
> WebFetch は今回も DNS エラー（support.dmm.com、chishikiya.blog で `ENOTFOUND`）。**規約・ヘルプの原文は開けていません**。すべて Web 検索結果の抜粋・要約から拾っています。原文を読むには、セッションのネットワーク設定で support.dmm.com（ほか各社ドメイン）を許可する必要があります。
> - **A** = 公式ドメイン（DMM・各サーバー会社・GitHub 等）の検索結果で確認。原文の全文は未読
> - **B** = 第三者ブログ・知恵袋・比較サイト等。参考値で、事実としては扱わない
> - **未確認** = A でも B でも確認できなかったもの。推測で埋めていない
> - **推測** と明記したものは、事実ではなく researcher の見立て

---

## 3行まとめ

1. **DMMアフィリエイトは「サイト必須」ではない**。公式ヘルプに「サイト（ブログ）や SNS アカウントを運営されていないとご登録できません」とあり、SNS アカウントでも登録できる（A）。不承認理由の公式例に「初回登録時の状態でサイト内容が確認できない」がある（A）。
2. 申請時点（10/27）の @mio_ukkari_jimu は、`published/` に投稿記録が0件で、日常投稿の開始も 11/8 の予定。**「サイトがない」は「X に中身（投稿）がなく、審査で内容を確認できなかった」という意味である可能性が高い**（推測。ただし根拠は公式の不承認理由と投稿記録0件という事実）。
3. 最短ルートは **ブログを作らずに、X に日常投稿を積んでから同じ X の URL で「追加申請」すること**。ブログを作る場合、アダルトを規約で認めているのはシン・レンタルサーバー、ColorfulBox（アダルト対応プランのみ）、mixhost（いずれも A）。GitHub Pages・はてなブログ・note は不可（A）。

## 推奨ルート

**ルート1（推奨・最短）: X のまま「追加申請」で再申請**
1. 11/8 から日常投稿を開始（決定 #19 のとおり。ただし第1週の医療事務版は使用停止のため、コスプレ版の投稿は承認②を経たものに限る）
2. 審査前にアカウントを整える: 公開アカウント（鍵なし）、プロフィール・固定投稿に「PRを含みます」「18歳未満閲覧禁止」「キャラ設定で運用中」、**アフィリエイトリンクはまだ貼らない**（登録前のアフィリンク投稿は規約違反の可能性ありとする記事がある、B）
3. 投稿が **10件程度**（B の経験則。公式の基準値はない）たまった時点で、DMMアフィリエイトの管理画面から **追加申請**（公式ヘルプの案内、A）。サイト名欄に X 名、URL 欄に X の URL（前回調査 A：support.dmm.com/affiliate/article/44083）
4. 平日3本・土日2本のペースなら、10件は 11/8 から **約3日〜1週間**（11/11〜11/14ごろ）。審査結果は「最短1日」「約3営業日」とする記事がある（B）
5. **所要日数の目安: 11/8 から 1〜2 週間（11/12〜11/22ごろに承認見込み）**。11/15 の案件開始は「11/14 までに承認されたら」の条件付き（推測）

**ルート2（ルート1で2回落ちた場合の予備）: アダルト可のサーバーでサイトを作る**
- シン・レンタルサーバー / ColorfulBox アダルト対応プラン / mixhost に独自ドメインで WordPress を立て、記事を数本以上用意して追加申請
- 所要日数の目安: 契約・設置に数日、記事づくりに1〜2週間（推測）。費用は月額＋ドメイン代
- **アダルトラインの媒体は「Xのみ」と CLAUDE.md で決まっているため、サイトを作るのは媒体の追加にあたり、承認①のやり直しが必要**

**ルート3（並行候補・FANZA の代わりにはならない）: DUGA（APEXアフィリエイト）**
- 「審査なし」とする記事が複数（B）。ただし登録時にブログ名とブログURLを入れる仕組みとする記事もあり（B）、X だけで登録できるかは未確認

## オーナーに判断してほしい点

1. **ルート1（X のまま再申請）で進めてよいか**。再申請のタイミングは「日常投稿が10件程度たまったら」でよいか（10件は第三者の経験則で、公式の基準ではありません）
2. **案件開始日（11/15）の扱い**: 承認が間に合わなければ、案件投稿の開始を承認日の翌週などに後ろ倒しにするか
3. **ルート2（サイトを作る）を予備として認めるか**。作る場合は「アダルトラインは X のみ」のルール変更になります。またサイトには運営者情報・プライバシーポリシーなどを置くのが一般的で、**オーナーの個人情報をどこまで出すか**の判断も必要です
4. **不承認通知の文面の確認**: 「サイトがないため」以外の理由（例: 「コンテンツを2つ以上作成のうえ再申請」など）が書かれていないか、通知の全文を見せてほしい。DMM への問い合わせ（再申請の間隔・回数の制限、X の審査の見方）をオーナー名義で行うか
5. **DUGA（APEX）を並行で登録するか**（扱う場合は規約原文の確認と承認①が必要）

---

## 1. DMMアフィリエイトの登録・審査の条件

| 項目 | 内容 | 信頼度 | 情報源 |
|---|---|---|---|
| SNS のみで登録できるか | **できる**。「サイト（ブログ）や SNS アカウントを運営されていないとご登録できませんので作成の後にご登録ください」 | A | https://support.dmm.com/affiliate/article/44094 |
| X での申請方法 | サイト名に X の名前、URL に X の URL を書いて申請する | A（前回調査 2026-10-25） | https://support.dmm.com/affiliate/article/44083 |
| 不承認の主な理由（公式） | ①サイトが WEB 公開されていない ②ブログなど初回登録時の状態でサイト内容が確認できない ③サイトの内容が DMMアフィリエイトとマッチしない ④知的財産権の侵害 | A | https://support.dmm.com/affiliate/article/44022 |
| 再申請の方法 | 「ご自身のサイトを確認し、**追加申請**にて再申請をしてください」 | A | https://support.dmm.com/affiliate/article/44022 |
| 再申請の間隔・回数の制限 | **未確認**（公式・第三者とも、間隔や回数の規定は見つからない）。知恵袋に「2回とも不承認」という質問がある | 未確認 / B | https://detail.chiebukuro.yahoo.co.jp/qa/question_detail/q13309380488 |
| 審査期間 | 公式には明記なし。「最短1日」「約3営業日」とする記事あり | B | https://mobinc.jp/column/?p=1484 ／ https://chishikiya.blog/2026/10/09/dmm-affiliate/ |
| 記事数・投稿数の目安 | 公式の数値なし。「約10記事で通った」（体験談）、X は「投稿10件未満・フォロワー極端に少ない・最終投稿から1か月以上」が問題になりやすい、「最低5件程度」など、記事によって差がある | B | https://note.com/ren_5970/n/ne5ae357371f3 ／ https://bloggertomoco.hatenablog.com/entry/2026/07/15/090951 ／ https://mobinc.jp/media/2026/01/15/ （FANZA審査のコツ） |
| X 申請で不承認になった例 | 「サイト内にコンテンツが不足 → コンテンツを2つ以上作成のうえ再申請」と DMM から案内された例、「ログイン画面のため」不承認の例 | B（知恵袋） | https://detail.chiebukuro.yahoo.co.jp/qa/question_detail/q13321311818 |
| 初回登録時に内容が確認できない例（解説） | 「X のポストがない」「フォロワー数が0」 | B | 同上・検索要約 |
| 鍵アカウント | 非公開だと審査できないので公開にしてから申請、とする解説 | B | https://poyaran.com/entry/dmm-affiliate-screening-x |
| 申請時の名前 | サイト名には表示名ではなく ID（@〜）を使うべき、とする解説 | B | https://bloggertomoco.hatenablog.com/entry/2026/07/15/090951 |
| 登録前のアフィリンク | 登録前にアフィリエイトリンクを投稿すると規約違反の可能性、とする解説 | B | https://poyaran.com/entry/dmm-affiliate-screening-x |
| 参加規約での不承認事由（第三者の要約） | 運営者が未成年、非公開・閲覧制限のあるサイト、国内で運営されていないサイト など | B（原文未読） | 規約: https://terms.dmm.com/affiliate_service/ （検索要約で所在のみ確認） |
| 再申請で承認された例 | 改善後の再申請で承認された体験談あり | B | https://note.com/mendoboku/n/nd475c9b81d86 ／ https://www.caliberelectronics.com/dmm-fell/ |
| サイトで申請する場合の要件（プライバシーポリシー・運営者情報・年齢確認） | **公式の要件としては未確認**。検索では DMM がこれらを必須とする記載は見つからなかった | 未確認 | ― |

### 不承認の原因の見立て（事実と推測を分ける）
- 事実: 公式の不承認理由に「初回登録時の状態でサイト内容が確認できない」がある（A）
- 事実: `published/README.md` の投稿記録は0件。日常投稿の開始は 11/8 予定（決定 #19）。第1週の承認済み投稿は使用停止（決定 #15）
- 推測: 申請時の X に投稿がほぼなく、DMM 側は「サイト（中身）がない」と判断した可能性が高い。「サイト＝ブログが必要」という意味ではないと考える（公式に SNS 登録可と書かれているため）
- 推測（未検証）: X は未ログインだと投稿が見られない場合があり、センシティブ設定のアカウントには警告画面が出る。審査担当者が中身を見られず「ログイン画面のため」不承認になった例が B にある。**センシティブ設定と審査の関係は未確認**。対策の可否は DMM への問い合わせで確認するのが確実

## 2. アダルトのアフィリエイトサイトを作れる場所

| サービス | アダルト | 条件・注意 | 信頼度 | 情報源 |
|---|---|---|---|---|
| **シン・レンタルサーバー**（エックスサーバー株式会社） | **可** | 「はい、可能です。ただし、無修正・児童ポルノなど、法令又は公序良俗に反する内容は禁止」。ビジネスプランでアダルトを運営すると保証 vCPU が半分になる。2025/10 に運営移管・規約改定、2026/3 にも改定あり | A | https://www.shin-server.jp/support/faq/dont_adult.php ／ https://www.shin-server.jp/rule.php |
| **ColorfulBox** | **可（アダルト対応プランのみ）** | 申込み時に「アダルトサーバー」を選ぶ。BOX1 は対象外で最安は BOX2。通常プランとは別サーバー・別IP、相互のプラン変更不可。「18歳以上の年齢認証を設けた成人向けサイト」は可、無修正・**年齢認証のないコンテンツは不可**。事前審査なし | A | https://help.colorfulbox.jp/faq/adult-permission/ ／ https://www.colorfulbox.jp/adult/ |
| **mixhost** | **可** | 「日本国内において合法なアダルトサイトの運営を行う事ができます」。無修正など違法性の高いサイトは不可 | A | https://help.mixhost.jp/articles/115003736031 ／ https://mixhost.jp/hosting/adult/ |
| **FC2ブログ** | 可とする記事が多い | 作成時にジャンル「アダルト」を選ぶ。アダルト・アフィリエイトのジャンルは後から変更できない、アダルトを選ばずに載せると ID 凍結のリスク、とする記事。**公式の規約・ヘルプは検索で出てこず未確認** | B | https://www.colorfulbox.jp/media/fc2-affiliate-adult/ ／ https://affilabo.com/fc2/12069/ |
| エックスサーバー | **不可（アダルト動画のアフィリエイトサイトは不可と考える）** | 「ポルノサイト、またはそれに類似するもの」と、それらへの**リンクを含むもの**が禁止。性行為を連想させる画像・動画も禁止。風俗店・アダルトグッズ・同人系の運用自体は禁止に当たらない | A | https://www.xserver.ne.jp/support/faq/dont_contents_stint.php |
| ConoHa WING | 不可 | 会員規約でわいせつな画像・映像の表示等を禁止、アダルトアフィリエイトも対象とする解説 | B | https://www.colorfulbox.jp/media/conoha-wing_adult/ ／ https://web.ess-centre.org/conoha-adult-ng/ |
| ロリポップ！ | 不可 | 禁止事項に「アダルト、性風俗に関するコンテンツ」、アダルトサイトへのリンクも禁止とする解説 | B | https://www.colorfulbox.jp/media/lolipop_adult/ |
| さくらのレンタルサーバ | 判断が分かれる（未確認） | 「禁止」とする記事と「軽いアダルトは問題ない」とする記事がある | B | https://webst8.com/blog/lolipop-sakura-comparison/ ／ https://uohhyou.com/adarutotukaenai/ |
| カゴヤ・ジャパン | 非推奨 | わいせつ画像等の表示を禁止。別サービスではアダルト系を完全禁止とする記事 | B | https://www.colorfulbox.jp/media/kagoya-japan-adult/ |
| **GitHub Pages** | **不可** | Pages は GitHub 利用規約の制限（sexually obscene content を含む）に従う。ポルノ的コンテンツは対象 | A | https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits ／ https://docs.github.com/en/site-policy/acceptable-use-policies/github-sexually-obscene-content |
| **Vercel** | **不可（扱わない）** | AUP で「obscene, graphic」なコンテンツを禁止。通常のアダルトが含まれるかは明記を確認できないが、判断が Vercel 側の裁量 | A（抜粋のみ） | https://vercel.com/legal/acceptable-use-policy |
| **Netlify** | **扱わない** | 公式フォーラムでスタッフが「米国法で合法なら可」と回答しているが、AUP 本文は未確認。**「規約で禁止」とは確認できなかった**ため、正確には「不可」ではなく「候補外（規約が米国法基準・日本語の公式ルールなし・削除は Netlify の裁量）」 | B（公式フォーラム） | https://answers.netlify.com/t/hosting-adult-18-content-on-netlify/2612 |
| **はてなブログ** | **不可** | コミュニティガイドラインでポルノ等の投稿を原則禁止。個人営利利用ガイドラインで「成人向け情報の掲載や成人向け情報への誘導」を禁止 | A | https://policies.hatena.ne.jp/community-guideline ／ https://help.hatenablog.com/entry/commercial-guidelines |
| **note** | **不可** | コミュニティガイドラインでアダルト・性的・わいせつ的な表現と、そうしたサイトへのリンクを避けるべき内容としている | A | https://www.help-note.com/hc/ja/articles/4409925863193 |
| ライブドアブログ | 未確認 | 規約本文が検索で出てこなかった | 未確認 | ― |

補足（推測）: ルート2でサイトを作る場合、ColorfulBox は「年齢認証のないコンテンツは不可」としているため、入口に18歳以上の確認ページを置く前提になる。CLAUDE.md の「18歳未満閲覧禁止」とも合う。

## 3. サイトなし（SNS のみ）で登録できるアダルト系 ASP

| ASP | SNS のみで登録 | 審査 | X 掲載 | 実写・コスプレ案件 | 信頼度 | 情報源 |
|---|---|---|---|---|---|---|
| **DUGA（APEXアフィリエイト）** | **未確認**。登録時に「ブログ名とブログURL」を入れるとする記事あり | 「審査なし」とする記事が複数 | X で使えるとする記事あり。サンプル動画だけの投稿は不可でリンク付きで紹介、とする記事 | 実写の動画サイト。コスプレ作品の有無は検索で確認できず未確認 | B | https://www.colorfulbox.jp/media/apex-affiliate/ ／ https://note.com/affiri_gen/n/n7bbaae97409e ／ https://afifree.net/apex-affiliate/ |
| **MGS動画（MGSアフィリエイト）** | 記事によって食い違う（「審査なし・メールと口座で登録可」と「URL 最低1つ必須・記事が少ないと落ちる」） | 同左 | 登録時に「Twitter やブログなど紹介する場所」を書く、とする記事。公式の SNS ルールは未確認 | 実写。コスプレ作品の有無は未確認 | B | https://note.com/affiri_gen/n/nd7235b3e515f ／ https://chishikiya.blog/2025/07/14/mgs-affiliate/ |
| **DLsite** | 未確認 | 未確認 | 未確認 | **実写は扱っていない**とみられる（DLsite のコンプライアンスポリシーでは写真ベースの作品は登録不可、と報道） | B（報道） | https://www.itmedia.co.jp/news/article/2511/06/1251106077/ |

- 公式ドメインに絞った検索（dlsite.com / duga.jp / mgstage.com）では結果が0件で、**3社とも公式の登録条件は未確認**
- 推測: DUGA・MGS も登録時に掲載先の URL を求めるため、「X に中身がない」状態では FANZA と同じ問題が起きうる。どちらにしても X に投稿を積むことが先
- コスプレ案件: 決定 #23 で11月のコスプレ作品は月2本まで。作品単位で未成年を想起させるもの（制服・学生など）を除外する方針は他社でも同じ

## 4. 最短で FANZA を使えるようにするルートと日数の目安

| ルート | 手順 | 日数の目安 | 根拠 |
|---|---|---|---|
| **1. X のまま追加申請（推奨）** | 11/8 から日常投稿 → 10件程度で追加申請 → 審査 | 11/8 から **1〜2週間** | SNS 登録可・追加申請で再申請（A）、投稿数・審査日数（B）、日数は推測 |
| 2. アダルト可サーバーでサイト作成 | サーバー・ドメイン契約 → WordPress → 年齢確認ページ・記事数本 → 追加申請 | **2〜3週間以上**（推測） | サーバー各社の規約（A）、記事数（B） |
| 3. FC2ブログ（アダルトジャンル） | 無料で作成 → 記事数本 → 追加申請 | 1〜2週間（推測） | FC2 の公式規約は未確認（B のみ） |

推奨理由: 公式で SNS 登録が可能とされており、X の投稿は 11/8 から予定どおり積み上がるため、追加の費用・媒体追加（ルール変更）・個人情報の公開が要らない。ルート2・3 はルール変更と準備時間が必要。

---

## 除外・候補外にしたもの

| 対象 | 理由 | 根拠 |
|---|---|---|
| GitHub Pages / はてなブログ / note | 規約でポルノ・成人向け情報を禁止 | A（上表） |
| Vercel | AUP で obscene なコンテンツを禁止。裁量で停止されうる | A（抜粋） |
| Netlify | 規約の禁止は確認できず。ただし米国法基準で日本の公式ルールがなく、停止は裁量のため候補外 | B |
| エックスサーバー / ConoHa WING / ロリポップ！ | ポルノサイトや、そこへのリンクを禁止 | A（エックスサーバー）／ B（他2社） |
| 無修正を扱うサーバー・海外サーバーでの無修正 | CLAUDE.md の絶対NG（各社の規約でも無修正は禁止） | CLAUDE.md、A |

## 次のアクション案
- オーナー判断の1〜5への回答をもらう
- ルート1の場合: 11/8 開始の日常投稿の承認②を優先（再申請の材料になるため）。プロフィール・固定投稿の整備を compliance でチェック
- support.dmm.com を許可した環境で、44094・44022・参加規約の原文を compliance に確認してもらう
- DMM への問い合わせ（再申請の間隔・回数、X 審査で見る点、センシティブ設定の影響）はオーナー名義で

## 情報源（すべて確認日 2026-11-01。WebSearch の結果で確認し、原文は未読）

### DMM（A）
- https://support.dmm.com/affiliate/article/44094 （サイトがなくても登録できるか）
- https://support.dmm.com/affiliate/article/44022 （不承認の理由）
- https://support.dmm.com/affiliate/article/44083 （X への掲載。前回 2026-10-25 確認）
- https://terms.dmm.com/affiliate_service/ （参加規約の所在のみ）

### DMM 審査（B）
- https://mobinc.jp/column/?p=1484
- https://mobinc.jp/media/2026/01/15/fanza%e3%82%a2%e3%83%95%e3%82%a3%e3%83%aa%e3%82%a8%e3%82%a4%e3%83%88%e3%81%ae%e7%99%bb%e9%8c%b2%e6%96%b9%e6%b3%95%e3%81%8b%e3%82%89%e5%af%a9%e6%9f%bb%e9%80%9a%e9%81%8e%e3%81%ae%e3%82%b3%e3%83%84-3/
- https://chishikiya.blog/2026/10/09/dmm-affiliate/
- https://websalesstylist.com/dmm-affiliate-shinsa-kijisuu/
- https://note.com/ren_5970/n/ne5ae357371f3
- https://note.com/megumi_k1/n/n227d8d47f32f
- https://note.com/mendoboku/n/nd475c9b81d86
- https://detail.chiebukuro.yahoo.co.jp/qa/question_detail/q13321311818
- https://detail.chiebukuro.yahoo.co.jp/qa/question_detail/q13309380488
- https://bloggertomoco.hatenablog.com/entry/2026/07/15/090951
- https://poyaran.com/entry/dmm-affiliate-screening-x
- https://www.caliberelectronics.com/dmm-fell/
- https://works.awaisora.com/2025/06/13/9ebbb77e-f22f-411c-a459-7b5e8ce5cdcc/

### サーバー・ブログ（A）
- https://www.shin-server.jp/support/faq/dont_adult.php ／ https://www.shin-server.jp/support/faq/dont_contents_stint.php ／ https://www.shin-server.jp/rule.php
- https://help.colorfulbox.jp/faq/adult-permission/ ／ https://www.colorfulbox.jp/adult/ ／ https://www.colorfulbox.jp/function/
- https://help.mixhost.jp/articles/115003736031 ／ https://mixhost.jp/hosting/adult/
- https://www.xserver.ne.jp/support/faq/dont_contents_stint.php
- https://docs.github.com/en/pages/getting-started-with-github-pages/github-pages-limits ／ https://docs.github.com/en/site-policy/acceptable-use-policies/github-sexually-obscene-content
- https://vercel.com/legal/acceptable-use-policy
- https://policies.hatena.ne.jp/community-guideline ／ https://help.hatenablog.com/entry/commercial-guidelines
- https://www.help-note.com/hc/ja/articles/4409925863193

### サーバー・ブログ（B）
- https://answers.netlify.com/t/hosting-adult-18-content-on-netlify/2612
- https://www.colorfulbox.jp/media/fc2-affiliate-adult/ ／ https://affilabo.com/fc2/12069/
- https://www.colorfulbox.jp/media/conoha-wing_adult/ ／ https://web.ess-centre.org/conoha-adult-ng/ ／ https://www.colorfulbox.jp/media/lolipop_adult/ ／ https://www.colorfulbox.jp/media/kagoya-japan-adult/
- https://webst8.com/blog/lolipop-sakura-comparison/ ／ https://uohhyou.com/adarutotukaenai/

### 他 ASP（B）
- https://www.colorfulbox.jp/media/apex-affiliate/ ／ https://note.com/affiri_gen/n/n7bbaae97409e ／ https://afifree.net/apex-affiliate/
- https://note.com/affiri_gen/n/nd7235b3e515f ／ https://chishikiya.blog/2025/07/14/mgs-affiliate/
- https://www.itmedia.co.jp/news/article/2511/06/1251106077/ （DLsite のコンプライアンスポリシー）
