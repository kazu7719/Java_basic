## リストについて
・・・リストは、Rubyの配列と似たデータ管理の仕組み

・要素を順序づけて管理する
・要素を事後的に追加したり削除できる

## ArrayList・・・要素数を変更できる配列

import java.util.ArrayList;

ArrayList<Integer> scores = new ArrayList<Integer>();

    scores.add(1);
    scores.add(5);
    scores.add(10);
    scores.add(15);

    System.out.println(scores.get(0));
    System.out.println(scores.get(1));
    System.out.println(scores.get(2));
    System.out.println(scores.get(3));

  
①ライブラリをインポートする
import java.util.ArrayList;

②ArrayListの宣言を行う
ArrayList<データ型> scores = new ArrayList<データ型>();

③ArrayListに値を代入する
scores.add(1);

④ArrayListから要素を取り出す
scores.get(0)

## if文

class Main {
  public static void main(String[] args) {
    int value = 3;

    if (value > 0){
      System.out.println("値は正です"); 
    }
  }
}

if(条件式){
  条件式を満たす時に実行する処理
}

Rubyでの記述と異なる点
・条件式を()で囲む必要がある
・行いたい処理を{}で囲む必要がある

if (条件A) { 
  // 処理A
} else if () {
  // 処理B
} else {
  // 処理C
}