# Book-Comparing
## 概要
おすすめの本を複数のショップから表示してくれるWebサービス（Google Books, 楽天Books, ITBOOKSTORE)
## 制作背景
複数のショップで情報を比較する機会が増えている一方で、情報を比較するのが大変である現状があるのではないかと考えた。  
そこで、一度の検索で同時に複数のショップの情報を画面に表示できれば、比較が簡単のではないかと考え、「Book Comparing」を制作した。
## 制作メンバー
皆川翔哉(他大学生3名)（プライバシーのため、共同制作者の名前は非公表)
## 制作期間（※何のアプリを作るか？の話し合いも含む)
１ヶ月(12月〜)
## 仕組み
検索ワードをFirebaseに格納して、その検索ワードを元にAPIからデータを取得し、画面に表示させている
## 工夫点
* 検索結果が見つからなかった場合に、画像は"No Image"、タイトルは"不明"と表示させるようにした
* タイトル/本の画像上でマウスをクリックすると、商品のURLに飛ぶことができる
* 本の画像にマウスを当てると、表示が大きくなる
## 課題点
* Firebaseのキーワードの格納場所が一つなので、ユーザが複数同時に検索すると、他人のキーワードの結果が表示されてしまう可能性がある
* タイトルの長さなどの影響で、レイアウトが崩れてしまうこと
* レスポンシブなデザインでないこと
## 感想
1ヶ月間という短い時間で、学校やバイトもありながらチームで制作したものなので、悔しいが妥協した部分がたくさんあった。  
しかしながら、個人での開発ではなくチームでの開発というところで、共同開発をできたという経験はとても良かった。
## リンク
[Book Comparing](https://team-original-app-72914.web.app/)

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
