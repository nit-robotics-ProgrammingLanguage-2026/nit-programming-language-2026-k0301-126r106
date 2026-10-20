# 課題0301 int型のscanf
キーボードから入力されたint型のデータをprintfで表示するプログラムを書け．
わからなければ、生成AIに「答え」ではなく「ヒント」をもらうこと
#include <stdio.h>
int main(void){
    int i;
    scanf("入力：%d",&i);
    printf("出力：%d",i);
}


