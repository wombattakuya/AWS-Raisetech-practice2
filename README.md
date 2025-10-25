#1見出しgithubの使い方

1.githubにログインする
2.creat new repository（ブラウザ上・googlechromeなど）
* すでに作成しているリポジトリがあれば活用する
    * アスタリスク+半角スペース　*は斜体になる*
- ハイフン+半角スペースでも可能  
    - リスト２

3.ローカルの任意の場所（保存したい場所　例えばCドライブのdocumentフォルダの中など）で右クリック→git bush hereでgitvashを開く
4.リポジトリの「code」をクリックし、httpsのタブを選択（してあるはず）URLをコピーする
5.（ローカル）先ほど開いたgitbashで「git clone "先ほどコピーしたURL"」
リモートからローカルにリポジトリがクローン・コピーされる
6.「ls」を入力→何もないことを確認　「ls」→フォルダの中のファイルが何があるか確認する
7.「mkdir (フォルダ名raisetech-demo)」　raisetech-demoなどのフォルダを作成するmake directry フォルダを作成する
8.「cd(フォルダ名raisetech-demo)」先ほど作成したフォルダに移動
9.「vim demo.md」マークダウン記法のファイルを作成して編集する
終了する際はESC→:wqで保存して終了する（gitbashに戻る）
10.「git add」


