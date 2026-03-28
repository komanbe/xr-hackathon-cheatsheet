# XR開発チートシート

**ハッカソンやプロトタイピングですぐ使えるXR開発の実践リファレンス**

> ジャーナリズム × XR / デジタルアース × 没入体験 をテーマにした開発に特化したチートシートです。
> [クリエイティブメディアハッカソン](https://www.ntv.co.jp/hackathon/)向けに作成しましたが、XR開発全般に活用できます。

## チートシートを見る

**[XR開発チートシート（GitHub Pages）](https://komanbe.github.io/xr-hackathon-cheatsheet/)**

ブラウザで開くだけでインタラクティブに閲覧できます。カテゴリフィルタで必要な情報にすばやくアクセスできます。

## 内容

| セクション | 内容 |
|---|---|
| デバイス早見表 | Meta Quest 3 / Apple Vision Pro / スマートフォン / WebXR の比較 |
| 開発エンジン | Unity / Unreal Engine 5 / WebXR / Spark AR / Cesium / Android XR |
| 3D Gaussian Splatting | 撮影→処理→エクスポート→VR組み込みの完全ワークフロー |
| デジタルアース × XR UI | レイヤー構造設計 / ズームイン設計 / 空間UIの配置ルール |
| UX・演出設計 | 視線誘導 / ナラティブデザイン / VR酔い対策 |
| ハッカソン戦略 | スタック決定フロー / 発表前チェックリスト / ピッチで伝えること |

## 主要リンク集

### 開発ツール
- [Unity](https://unity.com/ja) — XR開発のデファクトスタンダード
- [Unreal Engine 5](https://www.unrealengine.com/) — 映像クオリティの空間表現
- [A-Frame](https://aframe.io/) — WebXRフレームワーク（HTMLタグだけでVR）
- [three.js](https://threejs.org/) — WebGL 3Dライブラリ
- [Babylon.js](https://www.babylonjs.com/) — エンタープライズ向けWebXR

### 3Dスキャン・3DGS
- [Scaniverse](https://scaniverse.com/) — 3DGSキャプチャアプリ（iOS/Android、無料）
- [Luma AI](https://lumalabs.ai/) — Web上で3DGS処理
- [Polycam](https://poly.cam/) — LiDARスキャン＆3DGS
- [UnityGaussianSplatting](https://github.com/aras-p/UnityGaussianSplatting) — Unity用3DGSレンダラー

### デジタルアース・地理情報
- [CesiumJS](https://cesium.com/platform/cesiumjs/) — オープンソース3Dデジタル地球儀
- [Cesium for Unity](https://cesium.com/platform/cesium-for-unity/) — UnityにCesiumの地球儀を表示
- [Re:Earth](https://reearth.io/) — Cesiumベース WebGISプラットフォーム
- [Google Maps 3D Tiles](https://developers.google.com/maps/documentation/tile/3d-tiles-overview) — フォトリアルな3D都市データ
- [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/) — カスタマイズ可能な3Dマップ
- [deck.gl](https://deck.gl/) — 大量地理データのGPU可視化

### SNS AR
- [Spark AR Studio](https://spark.meta.com/ar-studio/) — Instagram/Facebook向けARエフェクト制作
- [Effect House](https://effecthouse.tiktok.com/) — TikTok向けARエフェクト制作
- [Adobe Aero](https://www.adobe.com/products/aero.html) — ノーコード空間ARコンテンツ

### デプロイ
- [Vercel](https://vercel.com/) — WebXRプロジェクトの即座デプロイ
- [GitHub Pages](https://pages.github.com/) — 静的サイトの無料ホスティング

### 参考資料
- [WebXR Device API](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API) — MDN Web Docs
- [Meta Quest開発ドキュメント](https://developer.oculus.com/documentation/) — Meta公式
- [visionOS開発](https://developer.apple.com/visionos/) — Apple公式
- [Android XR](https://developer.android.com/xr) — Google公式
- [OpenXR](https://www.khronos.org/openxr/) — クロスプラットフォームXR標準仕様

## ライセンス

MIT License

## 作者

東京大学大学院 情報学環 渡邉英徳研究室 / [@komanbe](https://github.com/komanbe)
