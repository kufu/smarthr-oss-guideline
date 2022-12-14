SmartHR OSS ガイドライン
===


## ライセンス

この文章のライセンスはCC0です。この文章に関して、SmartHRはいかなる権利も保有しません。
[CC0 - Creative Commons](https://creativecommons.org/share-your-work/public-domain/cc0)

## バージョン

1.0

## ガイドラインの趣旨

SmartHR OSS ガイドラインは、SmartHRの従業員がよりオープンソースソフトウェアの改善（以下、OSS活動）に参加しやすくするための手助けをするものです。

SmartHRでは、数多くのOSSを使用してプロダクトを構築しています。SmartHRがOSSから多くの恩恵を受けているからこそ、SmartHRもOSSに貢献することでコミュニティをより活性化させていく責務があると言えます。

しかし、会社の従業員としてOSSに貢献するにはいくつかのハードルが存在します。それは会社との契約の問題であったり、法の問題であったり、また前例がなく判断できないといった心理的な問題もあります。このガイドラインでは、契約・法・前例などに代表される、従業員によるOSS活動の障壁を取り除くことを目指します。そのために、OSSに貢献するための定型的なルールを決め、相談窓口を設けます。

このガイドラインはCC0のもとSmartHRはいかなる権利も保有しません。具体的な運用例を記述したOSSガイドラインとして、さまざまなOSSを利用している会社に再利用され、ひいては日本の企業によるOSS活動がさらなる発展を迎えることに貢献したいと考えています。

## オープンソースソフトウェア（OSS）とは

OSSとは、自由で再頒布可能なライセンスのもと公開されたソースコードで作成されたソフトウェアです。より厳密な定義は、[Open Source Initiative で公開されています](https://opensource.org/osd)（[日本語訳](https://opensource.jp/osd/osd19/)）。ただソースコードが公開されているだけではなく、そのソースコードに変更を加えての再利用や再頒布も自由であることが特徴です。昨今のWeb開発において、OSSの使用を避けて通ることは現実的ではありません。OSSに向き合うときに、このガイドラインが参考になると幸いです。

## 重要箇所の抜粋

- SmartHRのOSSは、すべてGitHub上で管理します
- SmartHRの従業員が作成したOSSコードの著作権は、SmartHRのリポジトリに置かれるものはSmartHRに、それ以外のリポジトリに置かれるものは書いた本人に帰属します
- SmartHRの従業員としてOSS活動をする場合は、必ず時間を記録して勤怠報告をします。また、休憩時間の取得や連続稼働時間の制限ルールにも従います
- SmartHRのOSSが掲示できるライセンスは、MITもしくはApache 2.0です
- SmartHRのプロダクトに新たにOSSを取り入れる場合、許可されたライセンスリストを確認します
- CLAの署名は、個人で署名する場合は自身で判断し、企業として署名する場合は許可リストを確認します
- OSSにコミットするときは、コミット先のコントリビューションガイドを遵守します
- SmartHRのOSSに脆弱性があった場合、速やかに修正し公開します


## 著作権・商標・特許のガイドライン

SmartHRでの業務時間中に発生したOSS活動における著作権の帰属は、以下の基準に従って決定します。

1. SmartHRの管理する非公開のコードは、例外なくすべてSmartHRが著作権を有する
2. 世の中にOSSとして公開されるコードは、業務命令の有無を問わず、次のルールで著作権の所有者を決定する
    1. SmartHR社外で管理されるOSSに起案されたコードに関する著作権は開発者個人に帰属する
    2. SmartHR社内で管理されるOSSに起案されたコードに関する著作権はSmartHRに帰属する
    3. 業務中に作成された未公開のOSSを公開するとき、社内で管理するか社外で管理するかを主たる開発者とマネージャーが選択できる
    4. 起案されたコードについて複数の従業員が起案した場合は、起案した割合に応じて著作権を共有するものとする。但し、起案した従業員全員の合意がある場合は、著作者を代表者1名とすることができる。



SmartHRの管理しているリポジトリとは、GitHub上で `kufu` のOrganization下にあるリポジトリを意味します。このOrganizationで管理されているコードに関しては、SmartHRが著作権を所有します。一方で、SmartHRが管理していないすべてのOSSリポジトリに関しては、コードを記述した本人が著作権を所有します。この結論に至る過程を知りたい場合は、SmartHR社内の議事録を検索してください。

このルールの趣旨は、OSSにコミットする際に、どこまで自分の意志でコードをコントロールできるかを定義することにあります。SmartHRが管理するOSSは、その性質上SmartHRが開発の主導権を持つことが望ましいため、著作権をSmartHRが保持します。SmartHRのOSSには、社内では非常に多くの開発者が関わっているため、管理の複雑さなどを考慮してこのようなルールに決めました。一方で、SmartHR以外のOSSにコミットする際には、コードを書いた本人が自らの意思でそのコードを対象のOSSに提出することを妨げないように、本人に著作権を持たせるようにしています。SmartHR以外のOSSに関しては、コードを書いた本人がコードの著作権を持っているため、例えばパッチを送る際に権利の放棄を要求されたり、CLAへの署名を求められたときに、あなたは自らの意思でそれらを選択してください（個人開発者CLAの場合は自由ですが、企業CLAの場合はガイドライン内のCLAの項目に従ってください）。

一方で、商標や特許に関しては、すべてSmartHRに帰属します。個人の判断でそれらを自由に取り扱うことはできません。法務チームとの相談が必要になります。

## SmartHRでのOSS活動に関するガイドライン

### 業務としてのOSS活動とは

SmartHRにおける業務としてのOSS活動とは、業務として指示があったものを指します。また、業務外での自らの意思や趣味によるOSS活動に関しては、会社は関知しません。そのため、業務として実施するものに関しては必ず勤怠をきちんと報告したうえで実施し、それ以外のものは個人の自由の範疇で実施してください。

業務としてのOSS貢献活動へのハードルをより下げるために、「会社からの指示」とは何か、以下に例を挙げます。もちろん、この例がすべてではありません。OSS貢献をする必要性を感じたら、上長もしくはOSSチームになんでも質問をしてください。

#### 会社の指示の例

- 業務で使ってはいないOSSのバグを発見したので業務時間中に修正を送りたいと上長に相談し、承認された場合
- プロダクトに使用しているOSSにバグが発見されたので、修正する場合
- 社内で共通で使われているロジックを切り出し、社外に公開するために新しいライブラリを作成する場合
- 専業のフルタイムコミッタとして特定のOSSに貢献することを業務とする場合

その他、「会社の指示」とは「上長と合意が取れている」もしくは「業務遂行上必要」のどちらかを満たしていれば成立します。SmartHRの業務として積極的にOSS活動をするためにも、気兼ねなく上長と相談してみましょう。

### OSS貢献の例

OSSへの貢献とは、OSSを改善するための活動すべてが含まれます。以下の例は、OSSへの貢献のごく一部です。

- 自らが発見したバグを報告する
- すでに報告されているバグを修正するパッチを送る
- READMEやusageが古くなっているので更新する
- 新しい機能を提案する
- 自らが直面した問題の解決策を、他の人に共有するためにブログを書く

その他、OSSをより良くする活動があればそれはすべてOSSへの貢献です。もし迷った場合は、OSSチームに相談をしてください。業務で使っていないOSSであっても、必要性を説明したうえで上長と合意がとれれば、それは業務としてのOSS活動となります。どんどん上長と相談してみましょう。

### CODE OF CONDUCT

CODE OF CONDUCT とは、行動規範のことです。OSSのプロジェクトの中には、行動規範を定めているものがあります。これは、関連するカンファレンスや地域コミュニティなどにも用意されており、適用されるケースがほとんどです。

多くのCODE OF CONDUCTでは、アンチハラスメントポリシーや、いかなる差別も許容しない姿勢、コミュニケーションにおいて攻撃的な行動をとらないなどといった禁止された行動に関する内容とともに、それらに違反した場合にコミュニティから罰則や追放が課される旨が書かれているケースが多いです。

SmartHRにおけるOSS活動では、各コミュニティの掲げるCODE OF CONDUCTを遵守することを求めます。また、SmartHRでは自社のOSSやコミュニティにおけるCODE OF CONDUCTIONを定めます。そして、SmartHRのOSSに参加するすべての人に対して遵守を求めます。

```markdown
SmartHR CODE OF CONDUCT
===

# コントリビューター行動規範

## 私たちの約束
メンバー、コントリビューター、およびリーダーとして、年齢、体の大きさ、目に見えるまたは目に見えない障害、民族性、性別、
性同一性、表現、経験のレベル、教育、社会経済的地位、国籍、人格、人種、宗教、または性的同一性と指向に関係なく、
コミュニティへの参加をハラスメントのない体験にすることを誓います。

私たちは、オープンで親しみやすく、多様で包括的で健全なコミュニティに貢献する方法で行動し、交流することを誓います。

## 私たちの標準

前向きな環境を作り上げることに貢献する行動の例：

* 他人への共感と優しさを示す

* 異なる意見、視点、経験を尊重する

* 建設的なフィードバックを与え、優雅に受け入れる

* 私たちの過ちの影響を受けた人々に責任を受け入れ、謝罪し、そしてその経験から学ぶ

* 個人としてだけでなく、コミュニティ全体にとっても最善であることに焦点を当てる

許容できない行動の例は次のとおりです。

* 性的な言葉や画像の使用、および性的な注意またはその他あらゆる種類の問題行為

* トローリング、侮辱的または中傷的なコメント、個人的または政治的攻撃

* 公的またはプライベートの嫌がらせ

* 明示的な許可なしに、住所や電子メールアドレスなど、他者の個人情報を公開する

* 職業上不適切と合理的に考えられるその他の行為

## 執行責任

コミュニティリーダーは、許容される行動の基準を明確にし、実施する責任があり、不適切、脅迫的、攻撃的、または有害と見なされる行動に応じて、適切で公正な是正措置を講じます。

コミュニティリーダーは、コメント、コミット、コード、wikiの編集、問題、およびこの行動規範に沿っていないその他の貢献を削除、編集、または拒否する権利と責任を持ち、適切な場合はモデレーションの決定の理由を伝えます。

## 適用範囲

この行動規範は、すべてのコミュニティスペース内で適用され、個人がパブリックスペースでコミュニティを公式に代表している場合にも適用されます。
私たちのコミュニティを代表する例には、公式の電子メールアドレスの使用、公式のソーシャルメディアアカウントを介した投稿、オンラインまたはオフラインのイベントでの指定代理人としての行動などがあります。

## 執行

虐待的、嫌がらせ、またはその他の許容できない行動の事例は、執行を担当するコミュニティリーダーに対して[INSERT CONTACT METHOD]で報告される場合があります。
すべての苦情は迅速かつ公正にレビューおよび調査されます。

すべてのコミュニティリーダーは、問題の報告者のプライバシーとセキュリティを尊重する義務があります。

## 執行ガイドライン

コミュニティリーダーは、この行動規範に違反していると見なした行動への帰結を判断する際に、これらのコミュニティガイドラインに従います。

### 1. 更生

**コミュニティへの影響**: コミュニティで専門家にふさわしくない、または歓迎されないと思われる不適切な言葉の使用やその他の不適切な行動をすること。

**帰結**: コミュニティリーダーからの非公開の書面による警告。違反の理由を明確にし、行動が不適切だった理由を説明します。 公の謝罪が要求される場合があります。

### 2. 警告

**コミュニティへの影響**: 単一の出来事または一連の動作による違反。

**帰結**: 持続的な行動の結果を伴う警告。 指定された期間、行動規範の実施者との一方的な対話を含め、関係者との対話はありません。 これには、コミュニティスペースやソーシャルメディアなどの外部チャネルでの相互作用の回避が含まれます。 これらの条件に違反すると、一時的または永続的に禁止される場合があります。

### 3. 一時的な禁止
**コミュニティへの影響**: 持続的で不適切な行動を含む、コミュニティ標準の重大な違反。

**帰結**: 指定された期間のコミュニティとのあらゆる種類の相互関係または公的なコミュニケーションの一時的な禁止。 この期間中、行動規範を実施する人々との一方的な対話を含め、関係する人々との公的または私的な対話は許可されません。
これらの条件に違反すると、永久的に禁止される場合があります。
### 4. 永久的な禁止
**コミュニティへの影響**: 連続的な不適切な行動、個人への嫌がらせ、または個人の集団に対する攻撃または名誉毀損を含む、コミュニティの標準への違反のパターンを示す。

**帰結**: コミュニティ内でのあらゆる種類の公的な相互関係の永久的な禁止。

## 帰属
この行動規範は、https://www.contributor-covenant.org/version/2/0/code_of_conduct.html で利用可能な [Contributor Covenant][homepage] バージョン2.0を基に作成されています。

コミュニティへの影響ガイドラインは[Mozilla's code of conduct enforcement ladder](https://github.com/mozilla/diversity)に適合しています。

[homepage]: https://www.contributor-covenant.org
この行動規範に関する一般的な質問への回答については、https://www.contributor-covenant.org/faq のFAQを参照してください。翻訳はhttps://www.contributor-covenant.org/translations で入手できます。
```

OSSのリポジトリに含める場合は、Markdownファイルを利用してください。Markdownファイルは、[Contributor Covenant: Contributor Covenant Translations](https://www.contributor-covenant.org/translations/)から取得可能です。連絡手段の項目を、 `oss@smarthr.co.jp` に書き換えた上で利用してください。

### GitHubでのソースコード管理と議論の透明性

SmartHRで公開するOSSは、すべてGitHub上でソースコードを管理してください。そしてすべてのIssueおよびPull Requestでは、議論の透明性を心がけてください。以下は、議論の透明性を確保するためのガイドラインです。

- SmartHRの従業員のみがアクセスできる情報をIssueやPull Request内で参照しないこと
  - Slackのリンク、DocBaseのリンクなど、外部公開されないすべての情報を指します
- 英語でのコミュニケーションを推奨します
  - 英語以外も許容されます。意図を伝えることが難しければ得意な言語を用いましょう
- SmartHR UIやSmartHR Design System など、SmartHR以外が利用することを想定していないが公開されているソースコードや情報に関しては、これらの透明性の議論の対象外とします

### 通常勤務時間外及び深夜休日におけるOSS活動

業務としてOSSに携わる場合、脆弱性への対応や英語圏のエンジニアとのコミュニケーションの都合などで、SmartHRにおける勤務時間の範囲を逸脱する可能性があります。ですが、必要であればその業務を遂行するために、通常の業務時間外での業務としてのOSS活動に関する方針を定めます。

大前提として、フレキシブルタイム外での業務は例外的であり緊急を要する場合に限られているということを意識してください。フレキシブルタイム外での勤務が常態的に必要になる場合、例えば日本以外のタイムゾーンでのOSS活動が主務となる場合などは、通常の勤務制度の適用ではなく、特別な勤務体系における契約などを結ぶ必要があります。その際は、別途上長や労務チームとのミーティングを設けてください。その点を理解したうえで、以下のルールを遵守し業務でのOSS活動をしてください。

#### 勤務時間の報告

原則として、いかなる場合でも勤怠ツールを使い必ず正しい業務時間を報告してください。以下のガイドラインは、正しい業務時間の報告が守られていることを前提としています。

SmartHRでは、平日の5:00〜22:00をフレキシブルタイムと定めています。それ以外の時間で働く場合は上長の事前承認が必要ですが、やむを得ない理由で許可を受けずに業務時間外にOSS活動をした場合は、必ず勤怠ツール上で働いた証左を残し、後日承認を得てください。

休日にOSS活動をする場合は、事前に上長の許可を得たうえで振替休日の申請をしてください。障害対応などやむを得ず当日に働く必要が発生した場合でも、必ず勤怠ツール上で働いた証左を残し、後日承認を得てください。振替が難しい場合は休日出勤として働くこともできますが、可能な限り振替休日を取得してください。

#### 休憩時間の確保

従業員の休憩時間は、法律で定められた義務です。1日6時間を超える勤務の場合は最低でも45分の休憩を、1日8時間を超える勤務の場合は最低でも1時間以上の休憩を、勤務時間の間に必ず取得してください。

1勤務と1勤務の間には、SmartHRの規定として原則9時間のインターバルを設けることが、就業規則の39条 1-(7) で定められています。これは従業員の安全配慮義務を確保するための義務に従った規定です。フレキシブルタイム外や、休日に稼働するなどの変則的な勤務をした場合は、次の勤務までに必ず9時間のインターバルを空けることを忘れないでください。

#### 残業の制限

やむを得ない理由で月の残業時間が45時間を超過する可能性がある場合、必ず上長および労務チームへ相談してください。会社からの指示なく長時間の残業はできないので、業務負荷の見直しなどを含めた対応が必要です。

## ライセンスに関するガイドライン

### SmartHRの公開するOSSに使用できるライセンス

SmartHRでOSSを新規で開発し公開する場合のライセンスは、以下のいずれかを利用してください。

- MIT
- Apache 2.0

基本的にMITを推奨します。ただし、特許に関連する技術、商標に係る表示が含まれる場合などは、Apache 2.0を利用してください。

既存のOSSを何らかの理由でforkし公開する場合は、fork元のライセンスに準じてください。その際に、何らかの理由でライセンスの決定に困難が生じた際は、OSSチームに相談してください。

#### MITを利用する場合

以下の内容を、LICENSE.mdというファイル名でリポジトリ直下に設置してください。また、パッケージ管理システムのライセンス表記手順に従い、ライセンス名を明示してください（方法は後述）。

```
Copyright <YEAR> SmartHR, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

#### Apache 2.0を利用する場合

以下の内容を、LICENSE.mdというファイル名でリポジトリ直下に設置してください。また、パッケージ管理システムのライセンス表記手順に従い、ライセンス名を明示してください（方法は後述）。

```
Copyright [yyyy] SmartHR, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```

#### パッケージ管理システムのライセンス表記手順とは

OSSを公開する際は、公開するOSSの言語が標準でサポートしているパッケージ管理システムを利用してください。Rubyの場合はRubyGems、Node.jsの場合はnpmがそれに該当します。

また、パッケージ管理システムによって認識されるメタデータに、適切にライセンス情報をを記述してください。例えばRubyGemsの場合には、`.gemspec` ファイルにライセンス名を定義する箇所があります。それぞれのパッケージ管理システムの仕様に従い、ライセンスを明記してください。

[Specification Reference - RubyGems Guides](https://guides.rubygems.org/specification-reference/#license=)
[package.json | npm Docs](https://docs.npmjs.com/cli/v8/configuring-npm/package-json#license)

パッケージ管理システムのメタデータにAuthorとemailを記述する箇所がある場合には、以下のように入力してください。

- Authorには筆頭に `SmartHR, Inc.` を入力してください
  - 複数入力でき、かつ必要であれば、追加で個々の開発者の名前を入れてください
- emailには、 `oss@smarthr.co.jp` を設定してください

### SmartHRが公開しているOSSのライセンスを変更する場合

すでに公開しているOSSのライセンスは、必要がない限り変更してはいけません。ライセンスの変更が認められるのは、以下の2つのケースです。

- 公開済みのOSSに、特許に関わるコード、商標に関わる表示が新たに追加される場合
    - MITのライセンスで公開されていた場合は、Apahce 2.0に変更してください
- 公開済みのOSSから、特許に関わるコード、商標に関わる表示が削除される場合
    - Apache 2.0のライセンスで公開されていた場合は、MITに変更してください

また、いずれのケースでもライセンスの変更は慎重に周知してください。具体的には、以下のステップを踏んで変更されることが望ましいです。

- Issueでライセンスを変更することの周知
- インストール後に警告が出せるパッケージ管理システムを使っている場合、インストール後のメッセージにライセンスが変更されることを記述し、周知
- Pull Requestでライセンスを変更
- READMEの末尾に、ライセンス変更に関する理由を記述する
- リリースノートにてライセンスの変更を再周知

### SamrtHR のプロダクトに取り込むことができるOSSのライセンス

公開されているOSSには、ライセンスが明示されていることがほとんどです。SmartHRのプロダクトでは、不必要なトラブルを避けるために、以下のライセンスを使用しているOSSを利用できると定義します。これらのライセンスは、Open Source Initiativeによって承認されているか、もしくは利用が自由であることが自明であるものを選択しています。

- MIT
  - [The MIT License | Open Source Initiative](https://opensource.org/licenses/MIT)
  - [日本語訳](https://licenses.opensource.jp/MIT/MIT.html)
- Apache 2.0
  - [Apache License, Version 2.0 | Open Source Initiative](https://opensource.org/licenses/Apache-2.0)
  - [日本語訳](https://licenses.opensource.jp/Apache-2.0/Apache-2.0.html)
- BSD 3-Clause "New" or "Revised" license
  - [The 3-Clause BSD License | Open Source Initiative](https://opensource.org/licenses/BSD-3-Clause)
  - [日本語訳](https://licenses.opensource.jp/BSD-3-Clause/BSD-3-Clause.html)
- BSD 2-Clause "Simplified" or "FreeBSD" license
  - [The 2-Clause BSD License | Open Source Initiative](https://opensource.org/licenses/BSD-2-Clause)
  - [日本語訳](https://licenses.opensource.jp/BSD-2-Clause/BSD-2-Clause.html)
- 1-clause BSD License (BSD-1-Clause)
  - [1-clause BSD License (BSD-1-Clause) | Open Source Initiative](https://opensource.org/licenses/BSD-1-Clause)
  - [日本語訳](https://licenses.opensource.jp/BSD-1-Clause/BSD-1-Clause.html)
- BSD Zero Clause License
  - [Zero-Clause BSD (0BSD) | Open Source Initiative](https://opensource.org/licenses/0BSD)
  - [日本語訳](https://licenses.opensource.jp/0BSD/0BSD.html)
- ISC
  - [ISC License (ISC) | Open Source Initiative](https://opensource.org/licenses/ISC)
  - [日本語訳](https://licenses.opensource.jp/ISC/ISC.html)
- GPL
  - [GNU General Public License version 3 | Open Source Initiative](https://opensource.org/licenses/GPL-3.0)
  - [日本語訳](https://licenses.opensource.jp/GPL-3.0/GPL-3.0.html)
- LGPL
  - [GNU Lesser General Public License version 3 | Open Source Initiative](https://opensource.org/licenses/LGPL-3.0)
  - [日本語訳](https://licenses.opensource.jp/LGPL-3.0/LGPL-3.0.html)
- Ruby License
  - [https://www.ruby-lang.org/en/about/license.txt](https://www.ruby-lang.org/en/about/license.txt)
- Mozilla Public License 2.0
  - [Mozilla Public License 2.0 (MPL-2.0) | Open Source Initiative](https://opensource.org/licenses/MPL-2.0)
  - [日本語訳](https://licenses.opensource.jp/MPL-2.0/MPL-2.0.html)
- CC-BY
  - [Creative Commons — 表示 4.0 国際 — CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ja)
- CC0
  - [Creative Commons — CC0 1.0 全世界](https://creativecommons.org/publicdomain/zero/1.0/deed.ja)
- WTFPL
  - [About the WTFPL](http://www.wtfpl.net/about/)
- Unlicense
  - [The Unlicense | Open Source Initiative](https://opensource.org/licenses/unlicense)
  - [日本語訳](https://licenses.opensource.jp/Unlicense/Unlicense.html)

#### 利用可能ライセンスに関する補足事項

##### ライセンスが不明なコードの利用

ライセンスが明記されていないコードの利用は禁止します。前提として、ライセンスが明記されていないコードは、Open Source Initiativeの定める [OSSの定義](https://opensource.org/osd)に当てはまりません。そのため、OSSのガイドラインとしては本来扱う対象ではないのですが、ソースが公開されているということはOSSであるという誤解が広く残っているため、この項で補足します。ソースコードには著作権が存在します。SmartHRのOSSガイドラインでも、ソースコードの著作者が誰になるかを定めている項があります。その著作権のあるコードを、一定の取り決めのもとで再利用を許可するための条文がライセンスです。つまり、ライセンスが付与されていないソースコードを利用することは、著作権を無断で侵害していることと同義の行為です。そのため、SmartHRのOSSガイドラインでは、ライセンスの明記がないソースコードを利用することは禁止します。OSSのを利用する前には、必ずライセンスを確認してください。

##### GPL及びLGPL

一般的によく知られている事柄として、GPLおよびLGPLのライセンスを採用しているOSSを自社プロダクトに取り入れた場合、GPLのライセンスにより自社プロダクトのソースコードも開示しなくてはならないという認識があります。この認識は半分正解であり、半分間違いです。GPLおよびLGPLライセンスでは、「プログラムおよび派生物をオブジェクトコードないし実行形式で複製または配布する」際に、「プログラムに対応した完全かつ機械で読み取り可能なソースコードを添付する、もしくは希望に応じて公開する」ことを定めています（第3条）。これは、プログラムを実行形式で公開する場合の規定であり、GPL及びLGPLのOSSを利用して作成したプログラムの機能をネットワーク経由で提供する場合に関する規定はありません。そのため、GPL及びLGPLライセンスのOSSに関しても、SmartHRでは利用可能であると判断しています。

一方で、AGPLというライセンスがあります。このライセンスは、GPLおよびLGPLがネットワーク経由で提供される場合に関する一種の抜け穴を塞ぐために定められたライセンスであり、ネットワークを介しての機能提供をする場合でもソースコードの公開が求められます。また、このライセンスから派生したServer Side Public Licenseも存在します（ただし、Open Source Initiativeの認証は受けていません）。これらのライセンスのOSSをプロダクトに直接取り込むことは、ビジネス上の不都合が生じるので避けましょう。
[GNU Affero General Public License version 3 | Open Source Initiative](https://opensource.org/licenses/AGPL-3.0)

ただし、AGPLであっても、該当ソースコードを改変せず、他のOSSとも組み合わせずに単体で動作させる場合においては、それを利用するアプリケーションはAGPLの対象にはならず、ソースコードを公開する必要はありません。例として、MongoDBはAGPLライセンスですが、MongoDBをクライアントとして利用するソフトウェアにはAGPLが適用されません。そのため、もしどうしてもAGPLのOSSの使用に迫られた場合は、OSSチームと法務チームに #pj_oss-team チャンネルで相談をしてください。

- 参考情報
  - [GNUライセンスに関してよく聞かれる質問 - GNUプロジェクト - フリーソフトウェアファウンデーション](https://www.gnu.org/licenses/gpl-faq.ja.html#GPLRequireSourcePostedPublic)
  - [GPL系のOSSライセンスとソースコード開示義務 | IT法務.COM｜システム・ソフトウェア・ネットビジネスに関するご相談なら弁護士法人内田・鮫島法律事務所](https://www.it-houmu.com/archives/1902)

##### The Unlicenseと、ライセンス不明の違い

The Unlicenseが利用可能ライセンスに含まれていますが、これはライセンス不明とは明確に異なるものなので注意しましょう。The Unlicenseは、ライセンスをつけずパブリックドメインとすることを明示したOSSです。ライセンスが不明なOSSを、The Unlicenseと誤認しないように気をつけてください。

##### 取り込むことができるライセンスを増やしたい場合

OSSチームに相談のうえ、ガイドラインを改定してください。

### ライセンス不明である公開されたソースコードの取り扱いについて

利用を禁じます。すでに利用しているライブラリの依存関係の中に、ライセンス不明なソースコードが含まれていた場合、該当ソースコードの管理者にライセンスの明示を要求するか、利用しているライブラリ側に別のライセンスが明示されている同機能のOSSに切り替えるプロポーザルを出すなどの対応をしてください。ライセンスが不明なソースコードを利用し続けないようにしましょう。

## OSSを公開するときのガイドライン

OSSを新規に公開する場合、以下の内容を確認してください。

- 正しいライセンスが設定されている
    - 正しいライセンスの選択に関しては、[ライセンスに関するガイドライン](#ライセンスに関するガイドライン)を参照してください
- パッケージマネージャを利用するOSSの場合は、以下の内容が設定されていることを確認する
    - Author: SmartHR, Inc.
    - email: oss@smarthr.co.jp
    - license: 上記で選択したライセンス
- CODE_OF_CONDUCT.mdがリポジトリルートに設置されている
    - CODE_OF_CONDUCTの内容は[SmartHRでのOSS活動に関するガイドライン](#SmartHRでのOSS活動に関するガイドライン)を参照してください
- CONTRIBUTION.mdがリポジトリルートに設置されている
    - CONTRIBUTIONの内容は、[SmartHRのOSSに脆弱性報告があった場合のガイドライン](#SmartHRのOSSに脆弱性報告があった場合のガイドライン)を参照してください
- GitHub上で公開する

## CLAのガイドライン

CLAとは、Contributor License Agreementの略です。稀にですが、大規模なOSSや企業が管理するOSSにコントリビュートする際に、OSSが定めているライセンスに加え、そのプロジェクトが用意している追加のライセンスに同意することを求められるケースがあります。その追加ライセンスに同意することを、「CLAに署名する」と一般的に言います。CLAには、個人貢献者と企業貢献者という2つのライセンスが用意されているものもあります。このガイドラインでは、それらCLAへの同意をより簡単にするための手順を示します。

社外のリポジトリで管理されるコードに関しては、OSSポリシーに従い著作権はコードを書いたあなた自身に帰属します。そのため、基本的にあなた自身の裁量で個人貢献者のCLAに同意できます。

どうしても企業貢献者のCLAを求められる場合、以下に列挙された既知のCLAに関しては確認せずに署名できます。既知でない場合は、CLAの内容を法務に確認したうえで署名の可否を決定してください。法務確認は、Slackチャンネル #pj_oss-team でOSSチームに依頼してください。

### SmartHRが事前に確認済みのCLA

SmartHRで使用している技術スタックに関わる可能性があるOSSに関して、会社の審査フローをスキップして署名できるリストを、事前に法務チームとOSSチームで作成しています。以下のCLAに関しては審査の必要が無いため、法務フローの捺印申請をし、自らの判断で署名して構いません。

Google
[New CLA - Google CLA](https://cla.developers.google.com/clas/new?domain=DOMAIN_GOOGLE&kind=KIND_CORPORATE)

Microsoft
[Microsoft Contribution License Agreement Sample](https://opensource.microsoft.com/pdf/microsoft-contribution-license-agreement.pdf)

Meta
[Contributing to Meta Open Source Projects](https://code.facebook.com/cla/corporate)

CNCF
[cla/corporate-cla.pdf at master · cncf/cla](https://github.com/cncf/cla/blob/master/corporate-cla.pdf)

## 不具合報告・パッチの送り方についてのガイドライン

利用しているOSSに不具合を発見した場合、SmartHRのOSSポリシーでは開発者への不具合報告を努力義務として定めています。一方で、不具合報告は未経験者にとって高い心理的障壁があることも事実です。このガイドラインでは、不具合報告に何が必要なのかを明示し、より多くの人がOSSへ貢献できるよう手助けをします。

### 不具合報告の前にまず確認すること

実際に不具合報告をする前に必要な行動のチェックリストです。チェックの内容の詳細を確認したうえで実施していきましょう。

- [ ] 本当に不具合なのかどうかを複数人で確認した
- [ ] 再現手順を作成した
  - [ ] もし再現コードが作成可能ならば作成した
- [ ] 対象のOSSのコントリビューションガイドを確認した
  - [ ] セキュリティに関連する報告の場合は専用のレポートラインを使う
  - [ ] 報告対象のバグトラッキングシステムを確認した
  - [ ] 動作確認している環境の詳細情報を用意した
  - [ ] 報告用のテンプレートを使用した（存在する場合）

#### 本当に不具合なのかどうかを、複数人で確認する

不具合を発見しても、実は自分が書いているコードに問題があるケースもあります。まずは慌てず、チームやバックエンド/フロントエンドミーティングなど、複数人がレビューできる機会を利用して、発生した現象と期待する挙動の違いを報告しましょう。

複数人が確認して、これはOSS側の不具合だと判明したら、必要な情報をまとめてできるだけ早くOSS側に報告しましょう。もし自分で報告することを躊躇うのであれば、誰かに代役かペア作業をお願いしてみましょう。

#### 再現手順を作成する、可能であれば再現コードかテストを作成する

不具合報告をするうえで必ず必要なのは、問題の症状を再現するための詳細な手順です。可能であれば、再現するための最小限のコード、もしくはテストコードも用意しましょう。

再現するための手順として求められるのは、実際に該当の不具合（と疑われる）動作を、まっさらな環境で再現させるために必要な最低限の手順です。特殊な理由がない限りは、不具合と思われる動作を発見したときに作っていたプロダクトの都合とは完全に分離した形で記述します。また、必ず「期待する動作」と「実際の動作」を記述するようにしましょう。この2点がないと、開発者は何が問題なのかを認識できず、報告がリジェクトされてしまいます。

再現手順とともに必要なのは、どんな環境で動作確認をしたかという情報です。これには、使用しているOSSのバージョンに加え、動作しているOSのバージョンや、RubyやNodeやブラウザなどのランタイム情報などが求められていることが多いです。

不具合を再現する最小限のコードは、バグを修正する際の大きな助けになります。たとえば、RailsはActiveRecordやActionControllerなど、多種多様なOSSが入り混じって作成されています。その中で、本当にこの部分に問題があるということを示す最小限のコードは、開発者に問題を伝える最良の手段です。最小限の再現コードは、書くのがとてもむずかしいケースがあります。その場合には、チームやバックエンド/フロントエンドミーティングで助けを求め、モブプログラミングで作成するのが良いでしょう。

テストコードは最良の報告です。「期待する動作」と「実際の動作」を的確に伝えられ、かつ開発者が不具合報告の意図する点を正しく修正できたかを確認できる手段を提供するからです。しかし、適切なテストコードを書くことは難しいので、この場合もモブプログラミングなどで作成すると良いでしょう。もしくは、無くても構いません。用意できたとしたら、最良のオプションというような認識で大丈夫です。

#### 対象OSSのコントリビューションガイドを確認する

大規模なOSSプロジェクトの多くには、コントリビューションのガイドラインが存在します。ほとんどの場合は、リポジトリのトップレベルにCONTRIBUTING.mdなどの名前で置かれているので、必ず参照しましょう。例として、Railsに不具合報告 or パッチを送る際のガイドラインのリンクを紹介します。
[rails/CONTRIBUTING.md at main · rails/rails](https://github.com/rails/rails/blob/main/CONTRIBUTING.md)

Railsの場合はより詳細なガイドラインもあります。他のプロジェクトでも、詳細なガイドが用意されているのであれば、多くの場合でリポジトリのCONTRIBUTING.mdからリンクされているはずです。
[Ruby on Rails に貢献する方法 - Railsガイド](https://railsguides.jp/contributing_to_ruby_on_rails.html)
[Contributing to Ruby on Rails — Ruby on Rails Guides](https://edgeguides.rubyonrails.org/contributing_to_ruby_on_rails.html)

プロジェクトによって多少の差異はありますが、概ねどのプロジェクトでも要約すると以下の内容のものが多いです。

- セキュリティに関わる報告は、オープンな場ではなく専用の方法で連絡してほしい
- 同じバグがすでに報告されてないか確認してほしい
- バグを報告する際には、詳細な動作環境の情報提供と、可能であれば再現コードを書いてほしい

バグの報告方法は、GitHubのIssueであったり、専用のバグトラッカーシステムやMLが存在することがあるので、Issueを作成する前にプロジェクトごとの報告方法を必ず確認しましょう。また、報告用のテンプレートなどが示されているプロジェクトも多いので、必ずそれに従うようにしましょう。

一方で、中規模から小規模なOSSにはコントリビューションのガイドラインが無いことも珍しくありません。その場合は、GitHubのIssueなどで「最小限の再現コード」を送るだけで済む場合が多いです。実際に送る前に、OSSにパッチを送ったことのある経験者に意見を聞きながらモブで作業することをおすすめします。

#### ガイドラインに沿った方法（なければ一般的な方法）で報告する

上記の準備がすべて済んだら、ガイドラインで提示されている方法を使って不具合を報告しましょう。ガイドラインがない場合は、リポジトリ管理システムの不具合報告ツール（GitHubであればIssueが該当します）を使用しましょう。

報告後、開発者から追加の情報を求められることがあります。その場合は、公開できる範囲で求められている情報を速やかに提示しましょう。

## SmartHRのOSSに脆弱性報告があった場合のガイドライン

### CONTRIBUTION.md at SmartHR

SmartHRでは、OSSの公開管理にGitHubを使用します。そのため、OSS開発に関わる情報は、必ずGitHubのIssue上もしくはPull Request上でやり取りしてください。

例外的に、セキュリティに関わる不具合報告に関しては、 `oss@smarthr.co.jp` へのメールで受け付けます。

```markdown
SmartHR OSSプロダクトへのコントリビューションガイド
===

SmartHRのOSSプロダクトは、一部の例外を除き、GitHub上ですべてのやり取りを完結させ、情報の公開と共有を心がけてください。また、SmartHRのOSSにコントリビュートした場合、SmartHR CODE OF CONDUCTに同意したとみなします。

# バグを発見した場合

- **脆弱性に関わるバグを発見した場合、GitHub上ではレポートしないでください、必ず `oss@smarthr.co.jp` 経由でのコンタクトをお願いします**
- すでに同様のバグがIssue上で報告されていないかどうかを確認してください
- 同様の報告が見当たらない場合、新規にIssueをオープンしてください
  - Issueのタイトルで簡潔にバグの内容を説明し、本文でその詳細を説明してください
  - 動作環境など、再現情報は可能な限り提供してください
  - 期待してる動作と実際の動作を明確に説明してください
  - 問題を再現するための最小限のコードを記述してください

# パッチを提供したい場合

- 新規にPull Requestをオープンしてください
  - Pull Requestのタイトルで簡潔に修正の内容を説明し、本文でその詳細を説明してください
  - 対応するIssueがある場合は、その番号を本文に含めてください

# バグやパッチ以外の、ソースコードに関する質問

各OSSのGitHub Discussionを通じて質問をしてください。
```

### 脆弱性への対応

SmartHRのOSSで脆弱性が発見されたとき、また報告を受けたときには、可能な限り速やかに脆弱性を修正したバージョンを公開してください。

## これってOSS活動？

本ガイドラインでは、OSS活動の定義を明確に示しません。本ガイドラインは、可能な限り業務としてOSSに関わるハードルを下げ、すべての従業員のOSS活動への参加の手助けを目指しています。そのため、業務としてOSS活動に関わるにあたり、明確な範囲は定義していません。可能な限り広い範囲をOSS活動として認めてもらうべく、範囲を定義することなく業務上必要であれば、必要なだけOSS活動をしてください。それでももし自分がやろうとしていることがOSS活動にあたるかどうか不安がある場合は、OSSチームに相談してください。どんな質問でも気軽にお問い合わせいただければと思います。
