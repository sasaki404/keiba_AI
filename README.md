# 競馬予想AI
## 目的  
馬が３着以内に入る確率を予測すること。  
netkeiba.comの出馬表データをもとに予測する。

## モデル  
勾配ブースティング決定木を用いて学習させている。  
実行速度が速く、xgboostと同程度の精度を持っているlightgbmを用いている。
## 使い方  
![image](https://user-images.githubusercontent.com/62131201/120872457-c6464080-c5d9-11eb-8874-7e8158ab7e14.png)
