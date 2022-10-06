# JavaScript勉強用

## DOMの取得

### getElementById
指定したIDのDOM情報を取得

### getElementsByClassName
指定したclassのDOM情報を取得
HTMLCollection(動的)

### querySelector
指定したセレクタ―で一番最初に一致する要素を返す
idの場合#とつける
classの場合は.をつける
NodeList(静的)
<br>

#### 使い分け
常に最新の情報を取得したい場合はgetElementByで取得する。
且つこちらのほうがパフォーマンスがよい

ただforで回さなくてもquerySelectorAllを使うと要素をまとめて取得できる面もある。


### querySelectorAll
複数取りたい場合はquerySelectorAllを使う。





