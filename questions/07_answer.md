# Answer7

## ifとforの解答例

```java
int sum = 0;
for (int i = 1; i <= 100; i++) {
    if (i % 2 == 0) {
        sum += i;
    }
}
System.out.println(sum);
```

## fizzbuzzの解答例

```java
for (int i = 1; i <= 100; i++) {
    if (i % 3 == 0 && i % 5 == 0) {
        System.out.println("fizzbuzz");
    } else if (i % 3 == 0) {
        System.out.println("fizz");
    } else if (0 == i % 5) {
        System.out.println("buzz");
    } else {
        System.out.println(i);
    }
}
```

## fizzbuzzの解答例２

```java
import java.util.stream.IntStream;

public class JavaTraining {
    public static void main(String[] args) {
        IntStream.rangeClosed(1, 100)
        .mapToObj(i -> i % 15 == 0 ? "FizzBuzz"
                     : i % 3 == 0 ? "Fizz"
                     : i % 5 == 0 ? "Buzz"
                     : String.valueOf(i))
        .forEach(s -> System.out.println(s));
    }
}
```

fizzbuzz問題に限った話ではないですが、色々な書き方で同じ結果を得ることができます。  
fuzzbuzzzの解答例２はJava8から導入されたラムダ式を利用しています。  
今はそんなのがあるんだ～ぐらいで眺めるぐらいでいいです。  
ネットで調べるといかに短く書くかや、処理が速い書き方はどうだとかモリモリ情報があるので、調べると楽しいです。  

[Answer Example](./07_question.html)