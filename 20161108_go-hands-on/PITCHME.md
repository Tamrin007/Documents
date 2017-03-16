#HSLIDE

## ご飯だよ！〜 Go Hands-on 〜

2016.11.08

#HSLIDE

## 目次

- 自己紹介
- Goとは
- 基本文法・機能
- 入門資料紹介
- もくもくタイム

#HSLIDE

## 自己紹介

- Tamrin007
- M1
- 好きなエディタはAtom
- 夏からGoを書き始めた

#HSLIDE

## Goとは

- Googleのエンジニアによって開発された言語
- シンプルな言語設計と文法
- シングルバイナリ・クロスコンパイル
- 便利な標準ツール
- 手軽に扱える平行プログラミング

#HSLIDE

## 基本文法

#HSLIDE

## Hello world

```go
package main

import "fmt"

func main()  {
    fmt.Println("Hello world")
}
```

#HSLIDE

## 変数宣言

```go
var hoge int
fuga := string

var (
    piyo int
    poyo string
)

one, two := 1, "2"
```

#HSLIDE

## if

```go
if a == 0 {
    // 処理
} else {

}

if a = func(); a == 0 {

}
```

#HSLIDE

## for

```go
for i := 0;i < 3;i++ {
    // 処理
}

for {
    // 無限ループ
}
```

#HSLIDE

## switch

```go
switch number {
case 1:
    // 処理
    fallthrough
case 2:
    // fallthrough を使わなければ break
default:
    // 処理
}

```

#HSLIDE

## デモ

ファイルから Hello world してみる

#HSLIDE

## 他にも

- 配列、スライス、マップ
- type、構造体
- インタフェース、メソッド
- などなど

#HSLIDE

## 入門資料

### 基本的な文法

- [はじめてのGo―シンプルな言語仕様，型システム，並行処理：特集｜gihyo.jp … 技術評論社](http://gihyo.jp/dev/feature/01/go_4beginners)

#HSLIDE

## 入門資料

### 実践学習

- [A Tour of Go](tour.golang.org)
- [tenntenn/gohandson](https://github.com/tenntenn/gohandson/)

#HSLIDE

## ドキュメント

- [GoDoc](https://godoc.org/)

#HSLIDE

## もくもくタイムスタート!
