# diagrams_test
diagramを書く環境およびレシピ集をgitpodで提供  
ブラウザで開く　だけ：　` https://gitpod.io/#https://github.com/eritsi/diagrams_test `  
レシピは以下より引用  
https://diagrams.mingrammer.com/docs/getting-started/examples


# やり残し
xdg-open と　gitpodの食い合わせが悪そうなのでエイリアスでエラーメッセージを抑制しただけで放置

もう少し詳細は以下
https://github.com/gitpod-io/gitpod/issues/274
```
$ xdg-open simple_diagram.png
$ gp preview simple_diagram.png
$ gp preview /workspace/diagrams_test/simple_diagram.png
```
このあたりでブラウザチェック出来ないが、作成されたpng自体はファイルクリックで見えるので放置

# サンプルコード実行結果のpng  
### GCPの例  
<img src=./recipes/message_collecting.png height=600>  

### AWSの例  
<img src=./recipes/event_processing.png height=600>  
<img src=./recipes/grouped_workers.png height=600>  
