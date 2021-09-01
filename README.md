# Ken Honda Web Site

This is my portfolio web site for research, work and some activities.  
URL :

## HUGO

[Go 言語](https://golang.org/)製の [Static Site Generator (SSG, 静的サイトジェネレータ)](https://jamstack.org/generators/) である **[HUGO](https://gohugo.io/)** を用いて実装．この README では主に HUGO を用いた開発方法について記述する．

### HUGO Setup

[HUGO Quick Start](https://gohugo.io/getting-started/quick-start/)に沿ってすすめる．

#### 1. HUGO のインストール

- `brew install hugo`
- `hugo version`
- バージョンが表示されれば成功

#### 2. プロジェクトの作成

HUGO はデフォルトで様々なテーマが用意されている．  
[themes.gohugo.io](https://themes.gohugo.io/) ですべての公式テーマを探すことができる．  
今回は研究者向けのポートフォリオ作成に適した [Academic](https://themes.gohugo.io/themes/hugo-academic/) というテーマを採用する．

Academic を利用したプロジェクトの作成は Academic 公式の git をクローンして編集する．

- 任意のディレクトリで `git clone https://github.com/sourcethemes/academic-kickstart.git ProjectName`
- `cd ProjectName`
- `git submodule update --init --recursive` でテーマを initialize する

#### 3. サーバの起動

- `hugo server -D`

#### 4. コンテンツの追加

- [ドキュメント](https://wowchemy.com/docs/content/#manually)参照

#### 5. カスタマイズ

- 公式ドキュメント参照

## Links

- [Golang](https://golang.org/)
- [Hugo](https://gohugo.io/)
- [Hugo Quick Start](https://gohugo.io/getting-started/quick-start/)
- [Hugo Themes](https://themes.gohugo.io/)
- [Hugo Themes Academic](https://themes.gohugo.io/themes/hugo-academic/)
- [Hugo Academic GitHub](https://github.com/wowchemy/wowchemy-hugo-themes)
- [Hugo Academic Demo](https://academic-demo.netlify.app/)
- [wochemy Document](https://wowchemy.com/)

---
