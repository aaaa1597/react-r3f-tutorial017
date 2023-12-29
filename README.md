# react-r3f-tutorial017
React+TypeScriptなWebアプリで、R3Fのtutorial17。(Environmentで簡単背景描画)

![](https://storage.googleapis.com/zenn-user-upload/a9233c7842dd-20231229.png)
森林背景が簡単に設定できた!!

# ポイント
Environmentを埋め込むだけ。ものすごい簡単!!
自前の背景を埋め込みたい時は、下記を実行する。

```ts:Environment
<Environment preset="forest" background />	
```

```ts:Environment
<Environment files="./img/venice_sunset_1k.hdr" background />
```

# 解説HP
https://zenn.dev/rg687076/articles/9c218a190451d0

