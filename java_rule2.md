## 拡張for文の使い方

for (　要素を格納する変数宣言　: 配列あるいはArrayListの変数名) {
  取り出した要素を使用して行う処理
}

## 条件分岐の使い方

if ( 条件式　)　{
  条件式を満たす時に実行する処理
} else if ( 条件式　) {
  条件式を満たす時に実行する処理
} else {
   処理名
}

## javaのmainメソッドについて

# 2つのルール
①ファイルを実行するとmainメソッドが実行される

class Main {
  public static void main(String[] args) {  
      // ここに処理を書く
  {
}

②mainメソッドの引数などは、必ず決められた通りに記述する必要がある
→データ型等を変更してしまうとエラーになる
public static void main(String[] args) {  
      // ここに処理を書く
}

##　メソッドの使い方(引数がない場合)

class Main {
  public static void main(String[] args) {  
    sayHello();
  }

  public static void sayHello() {
    System.out.println("Hello World");
    return;
  }
}

# メソッドを定義するための構文
アクセス修飾子　static修飾子　返り値のデータ型 メソッド名() {
  // 行いたい処理
}

rubyとの相違点
① 返り値のデータ型を定義する必要がある
void = 返り値がない、中身がないを意味する

② 引数がないメソッドでも定義時にかっこの省略はできない
③ Rubyの「def」「end」の代わりに、波かっこでコードを囲む

## アクセス修飾子について

・public ・・・　どのクラスからもアクセスできる
・private ・・・　同一クラス内からのみアクセスできる
・protected

## static修飾子について

static = 静的

## メソッドの使い方(引数がある場合)

class Main {
  public static void main(String[] args) {
    var answer = square(5);  ←本引数
    System.out.println(answer);
  }
                             仮引数(変数名numberの前に、データ型の指定が必要)
                              ↓
  public static int square(int number){
    return number * number;
  }
}