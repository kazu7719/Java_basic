## 変数定義

型名　変数名;

ex:
class Main {
  public static void main(String[] args) {
    int radius;
    radius = 5;
    System.out.println(radius * radius * 3.14);
  }
}

型名 = int 変数名 = radius

System.out.println = puts

## 型推論を利用した変数宣言

var 変数名　= 値

##　配列の使い方

①変数の宣言を行う

int[] scores;

②配列の要素を作成し、配列に代入する

scores = new int[3];

③配列の要素に値を代入する

scores[0] = 1;
scores[1] = 2;
scores[2] = 3;

## 配列のさまざまな記述方法

①配列の宣言と同時に、要素の作成も行う方法

int[] scores; = new int[3];

②配列の宣言時に型推論を使用する方法

var scores = new int[3];

③配列の宣言から値の代入まで全て同時に行う方法

int[] scores = {1, 5, 10};

## ArrayListの使い方

①ライブラリをインポートする

import java.util.ArrayList;

②ArrayListの宣言を行う

ArrayList<データ型> scores = new ArrayList<データ型>();

③ArrayListに値を代入する

scores.add(1);

④ArrayListから要素を取り出す

scores.get(0)
