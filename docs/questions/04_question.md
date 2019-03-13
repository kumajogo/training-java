# Question4

次のプログラムは何が出力されるでしょうか。

```java
/*問1*/
int[] a = new int[]{1,2,3};//①
int[] b = a;               //②  
b[0] = 5;                  //③
System.out.println(a[0]);
```

問1  
①int配列aを宣言、要素は1,2,3。  
②int配列bを宣言、そこに配列変数aを代入。（ここがポイント！配列変数aには何が入っていたんでしたか？）  
③b[0]に5を代入。  
さて、a[0]の値は何でしょうか？？  

```java
/*問2*/
int c = 1;                 //④
int d = c;                 //⑤
d = 5;                     //⑥
System.out.println(c);
```

問2  
④int変数cを宣言し、そこに1を代入。  
⑤int変数dを宣言し、そこにcを代入。  
⑥dに5を代入。  
さて、cの値は何でしょうか？？

[Answer Example](./04_answer.html)