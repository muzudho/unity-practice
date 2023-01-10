Plane に 画像テクスチャーを貼り付ける方法を調べてみる  

📖[【Unity】Plane(床・地面)の作成・マテリアル設定](https://algorithm.joho.info/unity/unity-plane/)  
📖[第4回目：オブジェクトにマテリアルやテキスチャを適用する（後編）](https://book.mynavi.jp/manatee/detail/id=59718)  

`LocalImage` というものが見当たらない  

👇 Material の名前を `LocalImage` にして、右クリックするらしい  

Project View:  

```
    📂 Assets
    └── 📂 Materials
        └── 📄 LocalImage   # Material
```

コンテキスト・メニューから `Import New Asset...` を選ぶ  

予め `Number_1.png` 画像を作っておき、それを選ぶ。  
マテリアルにできたようだ。  

Plane にドラッグ＆ドロップすると、表面に貼り付いた。  
Plane は 裏から見ても不可視のようだ  
