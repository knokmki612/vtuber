# デフォルメダーラヘスト

## これは何

Facerigでの使用を想定してLive2D Cubism Editor フリー版で作成したLive2Dアバターです。

## 名前の由来

元々使用している[アバター画像](https://ja.gravatar.com/knokmki612)が家族から土産としてもらったダーラヘスト（木彫りの馬）で、それをデフォルメして立ち絵にしようと思いました。

## 使い方

### FaceRig

`dalahast` ディレクトリを `<FaceRigをインストールしたドライブのドライブレター>:\Steam\steamapps\common\FaceRig\Mod\VP\PC_CustomData\Objects` 下に配置してください。

調整済みのトラッキング設定を使用する場合は、FaceRigを起動後 `Switch to Advanced UI` > `Advanced Tracking Configuration` > `Expression Units` > `Load Options` で `dalahast.tkc` を読み込んでください。

### Live2d Cubism Editor

psd形式でのパーツの読み込みが必要な場合は、 `デフォルメダーラヘスト.xcf` をGimpで読み込みpsd形式で書き出してください。

## ディレクトリ構成

```
.
├── dalahast: Live2D Cubism Editor 4.1から書き出したCubism 3.3対応のモデルデータ
│   ├── cc_names_dalahast.cfg: FaceRig用の名称設定
│   ├── dalahast.2048
│   │   └── texture_00.png
│   ├── dalahast.cdi3.json
│   ├── dalahast.moc3
│   ├── dalahast.model3.json
│   ├── dalahast.physics3.json
│   ├── dalahast.vtube.json: VTube Studio用の設定
│   └── ico_dalahast.png: アイコン
├── dalahast.tkc: FaceRig用のトラッキング設定
├── デフォルメダーラヘスト.cmo3: Live2d Cubism Editor 4.1の編集データ
├── デフォルメダーラヘスト.svg: Vectornatorから書き出したベクターデータ
├── デフォルメダーラヘスト.xcf: 各パーツのラスターデータをレイヤーとして追加したGimpの編集データ
└── *.png: Inkscapeで書き出した各パーツのラスターデータ
```

## 参考情報

- [Live2D 超入門講座①準備・基本操作・目と口を動かす【ディープブリザード】Facerig・Animaze](https://www.youtube.com/watch?v=SwaW002RBGQ)
- [Live2D 超入門講座②顔のXYZ設定【ディープブリザード】Facerig・Animaze](https://www.youtube.com/watch?v=h-pJnw9kSLU)
- [Live2D 超入門講座③仕上げ・物理演算・Facerig 実装【ディープブリザード】Facerig・Animaze](https://www.youtube.com/watch?v=Zl7VuRXXIw0)
- [[Live2Dメモ] 続！肌の塗り足しを行わない口の作り方（グルー利用）。[cmo3ファイル配布あり]](https://spinalien.fanbox.cc/posts/2203512)
- [3日で完成！無料版を使ったLive2Dモデルの作り方](https://vtuberkaibougaku.site/2020/05/04/live2d-free-howto/)
- [FaceRigでLive2Dモデルを使えるようにする](https://live2d.wiki.fc2.com/wiki/FaceRig%E3%81%A7Live2D%E3%83%A2%E3%83%87%E3%83%AB%E3%82%92%E4%BD%BF%E3%81%88%E3%82%8B%E3%82%88%E3%81%86%E3%81%AB%E3%81%99%E3%82%8B)

## ライセンス

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="クリエイティブ・コモンズ・ライセンス" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/knokmki612/vtuber" property="cc:attributionName" rel="cc:attributionURL">Kimiaki Kuno</a> 作『<span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Dataset" property="dct:title" rel="dct:type">デフォルメダーラヘスト</span>』は<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">クリエイティブ・コモンズ 表示 - 継承 4.0 国際 ライセンス</a>で提供されています。
