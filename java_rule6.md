## 拡張for文

int[] scores = {1, 5, 10};

    for(int score : scores) {
      System.out.println(score);  
    }

for ( 要素を格納する変数宣言  :  配列あるいはArrayListの変数名) {
  取り出した要素を使用して行う処理
}

①配列、あるいはArrayListから要素を１つ取り出す
②取り出した要素を変数に代入する
③{}内の処理を行う
④配列、あるいはArrayListの要素数分だけ処理を繰り返す


## mainメソッドについて

①ファイルを実行するとmainメソッドが実行される
class Main {
  public static void main(String[] args) {  
      // ここに処理を書く
  {
}

②mainメソッドの引数などは、必ず決められた通りに記述する
public static void main(String[] args) {  
      // ここに処理を書く
}

## 引数がない場合のメソッドの使い方
class Main {
  public static void main(String[] args) {  
    sayHello();
  }

  public static void sayHello() {
    System.out.println("Hello World");
    return;
  }
}

アクセス修飾子 static修飾子 返り値のデータ型　メソッド名() {
  // 行いたい処理
}

・Javaでのメソッド定義は、Rubyと以下の点が異なります。
①返り値のデータ型を指定する必要がある
public static void sayHello() 

②引数がないメソッドでも定義時にかっこの省略は不可
③Rubyの「def」「end」の代わりに、波かっこでコードを囲む

アクセス修飾子の種類
・public
・protected
・private

## 引数がある場合のメソッドの使い方
class Main {
  public static void main(String[] args) {
    var answer = square(5);
    System.out.println(answer);
  }

  public static int square(int number){
    return number * number;
  }
}
