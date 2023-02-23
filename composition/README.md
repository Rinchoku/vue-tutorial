# Vue Tutorial (Composition)

Vue Composition APIのチュートリアル用

## Step1

単純にVueで「Hello Vue!」が表示されるだけ

## Step2

宣言的レンダリング

基本的な更新時のトリガーの宣言、変数を用いた描画の仕方について

reactive：オブジェクトのみ
ref：任意の値の型

## Step3

属性バインディング(v-bind)

## Step4

イベントリスナー(v-on)

## Step5

フォームバインディング(v-model)

双方向バインディングを行う簡略化して行うために、v-modelが存在する。
実態としてはv-bindとv-onを組み合わせたもの

## Step6

条件付きレンダリング(v-if)

## Step7

リストレンダリング(v-for)

v-forの説明ではあるが、ハンズオンはリストの追加・削除になっている

## Step8

算出プロパティ(computed)

computed内で使用された変数を監視し、変更があると再計算を行なってくれる。
計算結果はキャッシュされている

## Step9

ライフサイクルとテンプレート参照(mountedやupdatedなど)

refを用いることでテンプレート(DOM)を変数で参照することができる
