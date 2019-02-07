# 2019年2月　内定者研修


## 本日の研修について
- [ ] 振り返り
- [ ] hello world
- [ ] コンパイルと実行
- [ ] 変数
- [ ] 演算子
- [ ] if
- [ ] 配列
- [ ] 繰り返し
- [ ] 
- [ ] 


## 環境

- JDK Version : java8
- テキストエディタ : Visual studio code

## HelloWorld

### プログラミングファイル作成

まずはファイルを作成しよう。
コーディング用に用意したフォルダをエクスプローラで開いて、ファイルの新規作成で拡張子.javaファイルを作成する。

HelloWorld.java

作成したファイルをVSC等のエディタで開いて、プログラムを記述。
```java
public class HelloWorld { 
    public static void main(String[] args) { 
        System.out.println("Hello world");
    }
}
```

### コマンド実行手順

* コマンドプロンプトを起動する。　

【起動方法例】
1. windowsキー＋rキーで「ファイル名を指定して実行」を起動する。
1. cmdと入力してOKボタン または、 Enterキーを押下する。

cd コマンドでカレントディレクトリ(*)を移動する。

```sh
cd c:¥java
```

javacコマンドで実行したいjavaファイルをコンパイルする。

```sh
javac HelloWorld.java
```
コンパイルが完了すると、拡張子.classファイルが作成される。
.classを省いたファイル名をjavaコマンドで実行する。

```sh
java HelloWorld
```

## 型と変数

まずは、型を書いて変数を書きます。
```
int hanakoAge;
```
これで、int型のhanakoAge変数が宣言できました。  intは、整数を扱う型なのでhanakoAgeは、整数を扱う変数となります。
変数名は、自由に付けることができます。ただし、以下のルールがあります。

- 予約後は使用できない。（public, private, int, String...)
- 先頭文字に数値は使えない。

今hanakoAgeは宣言しただけで、中身がありません。嘘をつきました。変数を宣言時に値を指定しなかった場合は、初期値が設定されます。

|型|初期値
|..|..
|byte|0
short	0
int	0
long	0L
float	0.0f
double	0.0d
char	'\u0000'
boolean	false
参照型	null

変数を宣言した後は、初期化処理を行います。初期値が設定されることや、使い方を明確に分かっている場合は、初期化処理を行わなくても使うことができますが、慣れるまでは必ず初期化処理をしましょう。

初期化は以下のように記述します。

```java
hanakoAge = 3;
```




### プリミティブ型

型付きで変数を宣言することで、型に合わせてメモリ上に領域が確保されます。確保された領域を利用して様々な値や文字あるいは参照アドレスを保持する事ができるようになります。

基本データ型 一覧表

boolean1bittrue or falsechar16bitUnicodeの一文字byte8bit符号付き整数 -128～127short16bit符号付き整数 -32768～32767int32bit符号付き整数 -2147483648～2147483647long64bit符号付き整数 約-922京～約922京float32bit浮動小数点数double64bit浮動小数点数

```java
public class VariableTest{ 
    public static void main(String[] args){ int age = 35;
        System.out.print("age:");
        System.out.print(age);
    }
}
```

### 参照型（オブジェクト型？）

## 演算子

どんな演算子がある？

### 算術演算子

計算をします。

#### 優先順位

### 代入演算子

何

### 比較演算子

結果は、booleanだよ。

### インクリメント、デクリメント

i++

### 論理演算子

「&&」「||」「!」

### 用語集
カレントディレクトリ 現在作業しているディレクトリの事。コマンドプロンプト等でカレントディレクトリをcdコマンドで変更してコマンドを実行することで、選択されているカレントディレクトリの中で作業が行われる。
