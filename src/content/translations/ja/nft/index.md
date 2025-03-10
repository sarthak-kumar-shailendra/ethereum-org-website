---
title: 非代替性トークン(NFT)
description: イーサリアムにおける非代替性トークン(NFT)の概要
lang: ja
template: use-cases
emoji: ":frame_with_picture:"
sidebarDepth: 2
image: ../../../../assets/infrastructure_transparent.png
alt: ホログラムを介して表示されているETHロゴ
summaryPoint1: イーサリアムベースのアセットとして、唯一無二なものをトークンとして表現する方法。
summaryPoint2: NFTは、これまで以上に多くのコンテンツ・クリエイターを後押ししています。
summaryPoint3: イーサリアムブロックチェーン上のスマートコントラクトを利用。
---

## What are NFTs? {#what-are-nfts}

NFT は、個別の固有性を持つトークンで、 それぞれ固有の特性(非代替性)があり、その希少性が証明されています。 これは、セット内のすべてのトークンが同一であり、同じ特性(代替性)を持つ ERC-20 トークンとは異なります。 例えば、財布の中にある 1 ドル札を例に考えてみましょう。1 ドル札はすべて同じであり、同一の価値を持つため、お札の種類を気にする必要はありません。 しかし、所有する NFT の種類は*重要です*。NFT にはそれぞれ固有の特性があり、他とは異なるからです(非代替性)。

各 NFT の一意性により、美術品、収集品、あるいは不動産などのトークン化が可能になり、NFT が現実世界やデジタル世界における固有のアイテムとなります。 NFT の所有権はイーサリアムブロックチェーンによって担保されており、誰も所有権の記録を勝手に変更したり、コピー＆ペーストで NFT を複製することはできません。

<YouTube id="Xdkkux6OxfM" />

## 資産のインターネット {#internet-of-assets}

NFT とイーサリアムによって、現在のインターネットが持つ複数の課題を解決することができます。 あらゆるもののデジタル化が進むにつれて、希少性、独自性、所有権の証明などの物理的なアイテムの特性を複製する必要性が高まっており、 中央集権型の組織に管理されない形での実現を求められます。 例えば、NFT を使えば、特定の企業の音楽アプリに限定されない音楽の mp3 ファイルや、売買や交換ができるソーシャルメディア上のハンドル名を所有することができます。これらは、プラットフォーム提供者によって一方的に奪われることはありません。

ここで、今私たちが使用しているインターネットと、NFT のインターネットを比べてみましょう。

### 比較 {#nft-comparison}

| 非代替性トークン(NFT)インターネット                                                                                                         | 現在のインターネット                                                                                                                       |
| ------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| 自分で資産を所有する。 売買や交換できるのは自分のみ。                                                                                       | 組織から資産を賃借する。                                                                                                                   |
| NFT は唯一無二のデジタル資産であり、全く同じ NFT は存在しない。                                                                             | コピーとオリジナルの区別が難しい。                                                                                                         |
| NFT の所有権はブロックチェーン上に保存され、誰でも確認できる。                                                                              | デジタルアイテムの所有権記録は、当該アイテムが属する組織のサーバに保存される。その扱いについては、属する組織の方針に従わなければならない。 |
| NFT の所有権はブロックチェーン上に保存され、誰でも確認できる。 つまり、イーサリアム上の他のスマートコントラクトやアプリで簡単に使用できる。 | 通常、デジタルアイテムを扱う企業には、独自のインフラ（「ウォールド・ガーデン」）が必要となる。                                             |
| コンテンツクリエイターはどこでも作品を販売し、世界市場にアクセスできる。                                                                    | クリエイターは、使用するプラットフォームのインフラと流通経路に依存する。 通常、利用規約や地理的制限に大きく影響を受ける。                  |
| NFT の作成者は、自身の作品の所有権を保持し、ロイヤリティを NFT コントラクトに直接プログラムすることができる。                               | 音楽ストリーミングサービスなどのプラットフォームは、売上が利益の大部分を占めている。                                                       |

## 非代替性トークン(NFT)の仕組み {#how-nfts-work}

イーサリアム上で発行されるトークンと同様、NFT はスマートコントラクトによって発行されます。 スマートコントラクトは、コントラクトが持つ機能を定義した複数の NFT 規格(一般的には ERC-721 または ERC-1155)のいずれかに準拠しています。 コントラクトは NFT を作成(ミント)し、特定の所有者に割り当てることができます。 所有権は、特定の NFT を特定のアドレスにマッピングすることによってコントラクトで定義されます。 NFT には ID があり、通常は特定のトークンを一意にするメタデータが関連付けられています。

誰かが NFT を作成または生成する際、実際にはスマートコントラクト内の特定の関数を実行して、その NFT を自身のアドレスに割り当てています。 この情報は、ブロックチェーンの一部であるコントラクトのストレージに保存されます。 コントラクトの作成者は、コントラクト内に追加のロジックを記述することができます。例えば、総供給量の制限を設定したり、トークンが転送されるたびに作成者に支払われるロイヤリティを定義したりすることができます。

## 非代替性トークン(NFT)の使用方法 {#nft-use-cases}

NFT は以下のような多数の用途に使用されます。

- イベントの参加証明
- コースの修了証明
- ゲームの所有可能アイテム
- デジタルアート
- 現実世界における資産のトークン化
- オンライン ID の証明
- コンテンツへのアクセス権
- 発券
- 分散型インターネットのドメイン名
- DeFi の担保

例えばあなたが、NFT を使用して、権利を失ったり、仲介業者に利益を支払ったりすることなく、自分の作品を共有したいと考えているアーティストだとします。 新しいコントラクトを作成し、NFT の数、その特性、特定のアートワークへのリンクを指定することができます。 さらに、スマートコントラクトに、自分に支払われるべきロイヤリティをプログラムすることができます(例えば、NFT が譲渡されるたびに、販売価格の 5％をコントラクト所有者に譲渡する)。 また、コントラクトをデプロイしたウォレットを所有しているため、NFT を作成したことをいつでも証明することができます。 購入者のウォレットアドレスは、スマートコントラクト内のトークンと関連付けられているため、購入者はあなたのコレクションから本物の NFT を所有していることを簡単に証明することができます。 つまり、イーサリアムのエコシステム全体で、その信頼性を確信した上で使用できるということです。

あるいは、スポーツイベントのチケットを例に考えてみましょう。 イベントの主催者がチケットの販売枚数を決めるように、NFT の作成者はレプリカの数を決めることができます。 時には、5,000 枚の一般入場券のようなまったく同じレプリカも存在します。 例えば、座席指定のチケットのように、よく似ていてもそれぞれに微妙な違いがあるものが複数枚ミントされることもあります。 チケットの売買はピアツーピアで行われ、購入者はコントラクトアドレスを確認することで、常にチケットの正当性を確認することができます。

ethereum.org では、Github リポジトリへの貢献や電話会議への出席を示すために NFT が使用されており、独自の NFT ドメイン名も取得しています。 ethereum.org に貢献することで、POAP NFT(出席証明 NFT)を獲得できます。 一部のクリプトミートアップでは、チケットとして POAP が使用されています。 [貢献の詳細](/contributing/#poap)

![ethereum.orgの出席証明プロトコル(POAP)](../../../../assets/use-cases/poap.png)

このウェブサイトには、NFT による代替ドメイン名**ethereum.eth**があります。 `.org`アドレスは、ドメインネームシステム(DNS)プロバイダーによって集中管理されていますが、ethereum`.eth`は、イーサリアム・ネーム・サービス(ENS)を介してイーサリアム上に登録されています。 つまり、私たち自身が所有、管理しているということです。 [ENS レコードの確認](https://app.ens.domains/name/ethereum.eth)

[イーサリアム・ネーム・サービス(ENS)の詳細](https://app.ens.domains)

<Divider />

### NFT のセキュリティ {#nft-security}

イーサリアムのセキュリティは、プルーフ・オブ・ステークによって確保されています。 経済的なインセンティブによって悪意のある行為を抑止するように設計されており、その結果、改ざんを防止しています。 こうして、NFT が実現しています。 NFT のトランザクションを含むブロックが確定した後に攻撃者が変更しようとすると、数百万 ETH の費用がかかることになります。 イーサリアムのソフトウェアを実行している人なら誰でも、NFT に対する不正な改ざんを直ちに検出することができ、悪質な行為を行う者は、経済的なペナルティが課せられ、ネットワークから追放されます。

NFT に関連するセキュリティの問題の大半は、フィッシング詐欺、スマートコントラクトの脆弱性、ユーザーの過失(不注意で秘密鍵を公開するなど)のいずれかに関連しており、ウォレットのセキュリティが NFT 所有者にとって非常に重要になります。

<ButtonLink to="/security/">
  セキュリティの詳細
</ButtonLink>

## 参考文献 {#further-reading}

- [非代替性トークン(NFT)初心者向けガイド](https://linda.mirror.xyz/df649d61efb92c910464a4e74ae213c4cab150b9cbcc4b7fb6090fc77881a95d) – _Linda Xie, 2020 年 1 月_
- [EtherscanNFT トラッカー](https://etherscan.io/nft-top-contracts)
- [ERC-721 トークン標準](/developers/docs/standards/tokens/erc-721/)
- [ERC-1155 トークン標準](/developers/docs/standards/tokens/erc-1155/)

<Divider />

<QuizWidget quizKey="nfts" />
