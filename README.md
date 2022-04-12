# Colabで動くFaster R-CNN
使いやすいようにColab実装版を書きました。
あまり実行環境に左右されず誰でも動かせると思います。
詳しくは[qiita](https://qiita.com/ImR0305/private/c2674dfe9f5ec1301304)をご参照ください。

データセット展開時の想定ディレクトリ構造

colab_frcnn-main/

┣Faster-R-CNN.ipynb

┣ smallbdd/

　　　┣test/
   
　　　┣xml/
   
　　　┣img/

# localで動かす際の環境構築方法
```
pip install torch==1.8.0+cu111 torchvision==0.9.0+cu111 torchaudio==0.8.0 -f https://download.pytorch.org/whl/torch_stable.html
pip install jupyterlab
pip install -r requirements.txt
```