ペア兢プロしよう

vvv

せっかくの機会なので、前回のLTとかでも押してたペアプロしながら  
競技プログラミングでもしようやっていうやつです

---

前提：ペアプロ

vvv

ペアプロ(ペアプログラミング)とは？

vvv

**ペアプログラミング**（英: pair programming）は、
2人のプログラマが1台のワークステーションを使って共同で
ソフトウェア開発を行う手法である

driver(コードを書く人)とobserver(アドバイスとか補助する人)に分かれる

vvv

らしい

vvv

[ここ](https://gist.github.com/j5ik2o/2970973)にコツがあります  
問題が出来たらハイタッチとかして喜びましょう！！

---

前提：入出力

vvv

入出力は知識として知っておかないと難しいので、言語ごとの例をのせておきます

vvv

Java  
```java
import java.util.Scanner;

public class Main {
  public static void main(String[] args){
    Scanner s = new Scanner(System.in);
    String a = s.next();
    System.out.pritnln(a);
  }
}
```

vvv

Python  
```python
a = input()
print(a)
```

vvv

Ruby  
```ruby
a = gets
puts a
```

vvv

C++
```cpp
#include<bits/stdc++.h>
using namespace std;

int main(){
  string a;
  cin >> a;
  cout << a << endl;
}

```

vvv

オンライン上のジャッジさえあればどの言語でも解けます  
これからやるAtcoderは、50言語以上くらいは使えます  

---

ペア分け

vvv

言語同じがいいですね

vvv

レベルとか学年の差はあんまり気にしなくても良いかも  
レベル高い方が横からObserverしてた方が良い気がする

---

問題

vvv

[A問題](https://beta.atcoder.jp/contests/abc086/tasks/abc086_a)  
[B問題](https://beta.atcoder.jp/contests/abc088/tasks/abc088_b)  
[C問題](https://beta.atcoder.jp/contests/abc085/tasks/abc085_c)  
[D問題](https://beta.atcoder.jp/contests/abc085/tasks/abc085_d)

vvv

C問題とか解けたら良い感じ！  
D問題は当日のレベルが分からないので一応入れておきました

vvv

適宜検索してもらって大丈夫です！  
となりのページにヒントものせておきます。

---

ヒント

vvv

if文使う！  
[A問題のヒント](https://qiita.com/drken/items/fd4e5e3630d0f5859067#%E7%AC%AC-1-%E5%95%8F--abc-086-a---product-100-%E7%82%B9)

vvv

sort使う！  
[B問題のヒント](https://qiita.com/drken/items/fd4e5e3630d0f5859067#%E7%AC%AC-6-%E5%95%8F--abc-088-b---card-game-for-two-200-%E7%82%B9)

vvv

全探索使う(全部試してみる)！  
[C問題のヒント](https://qiita.com/drken/items/fd4e5e3630d0f5859067#%E7%AC%AC-8-%E5%95%8F--abc-085-c---otoshidama-300-%E7%82%B9)
