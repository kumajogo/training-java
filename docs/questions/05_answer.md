# Answer5

## if文の解答例

### 問題１ 解答例

```java
int x = 5;

if (x > 0) {
    System.out.println("xは正の数です");
} else {
    System.out.println("xは負の数です");
}
```

### 問題２ 解答例

```java
int x = -5;

if (x > 0) {
    System.out.println("xは正の数です");
} else if (x < 0) {
    System.out.println("xは負の数です");
} else {
    System.out.println("xは0です");
}
```

### 問題３ 解答例

```java
int x = 9;

if ((x % 2) == 0) {
    System.out.println("xは偶数です");
} else {
    System.out.println("xは奇数です");
}
```

### 問題４ 解答例

```java
int x = 50;

if ((x % 10) == 0) {
    System.out.println("xは10の倍数です");
} else {
    System.out.println("xは10の倍数ではありません");
}
```

### 問題５ 解答例

```java
int x = 24;
int y = 8;

if ((x % y) == 0 ) {
    System.out.println("xはyで割り切れる");
}else{
    System.out.println("xはyで割り切れない");
}
```

[Answer Example](./05_question.html)