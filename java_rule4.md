## 代数演算子について(+ - * / %)
・・・Rubyと一緒

## 比較演算子について
・・・Rubyと一緒

## Rubyの配列との違い
Javaの配列は、格納する要素の数を最初に決める必要があり、
後で要素数を変更することができない

int[] scores;
    scores = new int[3];

    scores[0] = 1;
    scores[1] = 5;
    scores[2] = 10;

    System.out.println(scores[0]);
    System.out.println(scores[1]);
    System.out.println(scores[2]);

  ①配列の宣言を行う
  int[] scores;

  ②配列の要素を作成し、配列に代入する
  scores = new int[3];

  ③配列の要素に値を代入する
  scores[0] = 1;


## 配列のさまざまな記述方法
①配列の宣言と同時に、要素の作成も行う方法
int[] scores;
scores = new int[3];

→ int[] scores = new int[3];

②配列の宣言時に型推論を使用する方法
var scores = new int[3];

③配列の宣言から値の代入まで全て同時に行う方法
int[] scores = {1,5,10}; 