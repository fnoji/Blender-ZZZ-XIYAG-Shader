# Blender-ZenlessZoneZero-Shader (XIYAG) / Blender用ゼンレスゾーンゼロ再現シェーダー

# JP

## 概要
このシェーダーの開発者はbilibiliの"新杨XIYAG"さんとなっており、ノード類が最適化されている"Carbnuts"さんの[こちら](https://crabnuts.gumroad.com/l/crabanbyrig)のリグを含んだblendファイルへ同梱されているものとなります。
この同梱されているマテリアルから、各種テクスチャ等を除いたblendファイルが当リポジトリです。

### 開発者などへのリンク
 - [新杨XIYAG](https://space.bilibili.com/8179669)
 - [Crabnuts](https://x.com/Kani_Natto_)
 - [Luci](https://x.com/luci_animates/)

## 使用方法
1. リリースより`.blend`をダウンロードしてください。
2. 好きなキャラクターメッシュを使用した新規プロジェクトで、ダウンロードした`.blend`のマテリアルをアペンドしてください。
3. メッシュの元々のマテリアルを、追加したシェーダーマテリアルに置き換えてください。
5. エフェクトテクスチャやモデルテクスチャをイメージノードにインポートし、メッシュのUVMapへUV0,UV1,UV2を作成してください。
6. **headOrgn** とした空のオブジェクトを **Child Of** コンストレイトを使用して、キャラクターの頭ボーンにコンストレイトしてください。

## 問い合わせ
### 当リポジトリの問い合わせ先
編集されたこのシェーダーは、基本的に**ソースリポジトリの開発者や貢献者は関係がなく、原則サポートしていません。**
改修済のシェーダーの取り扱い方法などの質問は、当リポジトリのIssueや以下へ行ってください。開発者などへは行わないでください。
- [Discord server](https://discord.gg/3p9cT4ajqy) / Hoyo Animation Creator [JP/EN]
- [Twitter / fnoji](https://twitter.com/fnoji) / [JP/EN]

## ルール
- このシェーダーは、基本的に大元の提供者である新杨XIYAGのルールが継承されています。
- このシェーダーをレンダリング、アニメーション、シェーダを直接変更しない作品で使用する場合、”新杨XIYAG”とクレジットを行ってください。
- このシェーダーを独自のシェーダーの主要資料として使用する場合、適切なクレジット表記を行ったり、作成者へ確認を行ってください。

## シェーダーのメーカー公認作品採用例
シェーダーのメーカー公認二次創作作品採用例があり、HoYoCreators会員者や、Hoyoverse公式主催の動画コンテスト受賞作品などで使用された実績があります。

詳細な点は全て [Discord server](https://discord.gg/3p9cT4ajqy) / Hoyo Animation Creator [JP/EN] へ 日本語で記載していますので、問い合わせはこちらへよろしくお願いいたします。

# EN

## Overview

This shader was originally developed by "**新杨XIYAG**" on bilibili. It's included in a .blend file, along with a highly optimized rig created by "**Carbnuts**," available [here](https://crabnuts.gumroad.com/l/crabanbyrig). This repository contains a .blend file that extracts the material from that file, with all textures and unnecessary elements removed.

### Links to Developers and Related Parties:

*   [**新杨XIYAG**](https://space.bilibili.com/8179669) (Original Shader Developer)
*   [**Crabnuts**](https://x.com/Kani_Natto_) (Rig Developer)
*   [**Luci**](https://x.com/luci_animates/) (Material optimized)

## Instructions for Use

1.  Download the `.blend` file from the Releases section.
2.  In a new Blender project with your desired character mesh, append all the material from the downloaded `.blend` file.
3.  Replace the original materials of your mesh with the appended shader materials.
4.  Import effect and model textures into the appropriate image nodes and create UV Maps (UV0, UV1, UV2) for your mesh.
5.  Create an empty object named **headOrgn** and use a **Child Of** constraint to constrain it to your character's head bone.

## Inquiries

### Contact for This Repository

Please note that **the original developer and contributors of the source repository are generally not involved with this edited shader and, in principle, do not provide support for it.**

For questions regarding the handling of this modified shader, please use the Issues section of this repository or contact:

*   [Discord server](https://discord.gg/3p9cT4ajqy) / Hoyo Animation Creator [JP/EN]
*   [Twitter / fnoji](https://twitter.com/fnoji) / [JP/EN]

**Please do not contact the original developers or contributors regarding this modified shader.**

## Rules

*   This shader fundamentally inherits the rules of the original provider, 新杨XIYAG.
*   When using this shader in rendered images, animations, or any work where the shader itself is not directly modified, please credit "**新杨XIYAG**".
*   If you use this shader as a primary reference for creating your own shaders, ensure proper credit is given and consider contacting the original creator for clarification.

## Examples of Officially Recognized Works Using the Shader

There are instances of this shader being used in officially recognized fan works, including works by HoYoCreators members and award-winning entries in video contests hosted by Hoyoverse.

For more detailed information, please visit the [Discord server](https://discord.gg/3p9cT4ajqy) / Hoyo Animation Creator [JP/EN], where everything is also documented in Japanese.(EN OK) Please direct any inquiries there.
