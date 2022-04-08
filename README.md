# 月の日数判定アプリ

## 仕様
西暦と月を入力するとその月の日数を教えてくれるアプリを作成する

## 実行例
西暦と月を入力>>2022,4 [enter]  
2022年4月は30日まであります  

## 作成方法
以下の３つのメソッドを作成すること  
1.csv文字列を受け取り、int型配列を返却する  
public static int[] csvToIntArr(String csv){}  
2.西暦を受け取りそれが閏年なのかを判定する  
閏年の判定は以下  
400で割り切れたら閏年  
4で割り切れて100で割り切れなかったら閏年  
public static boolean isLeapYear(int year){}  
3.西暦と月を受け取り日数を返す  
public static int daysOfMonth(int year,int month){}  
4.作成したメソッドを利用して、アプリを作成する
