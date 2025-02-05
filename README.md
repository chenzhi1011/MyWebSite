# URL
[MyWebSite](http://chenzhi.site/)

# Motivation and Overview
While studying architecture, I identified the following issues:
1.	Architecture students typically have many individual projects and compile them into a portfolio. Traditionally, portfolios are created in PDF format or printed as booklets, which is inconvenient for sharing.
2.	Except for in-person sharing, it is difficult to receive immediate feedback from viewers on each project.  
Considering the security concerns of relying on third-party platforms, I decided to utilize my technical skills to create a portfolio website from scratch (0→1).

# Pages
![myweb-intro](images/myWeb-intro.jpg)
# Modules
- Display Module
- Interaction Module
  -	Comment Module
	-	ContactMe Module

# Backend API
-	Comment API
Stores visitors’ comments in the database for data persistence.
![commentAPI](images/commentAPI)
-	Email API
Calls Gmail’s SMTP API to send emails to myself.
![emailAPI](images/emailAPI)

# Tech Stack
-	Frontend: HTML, CSS, JavaScript (Rebuilding with React)
-	Backend: Java, Spring, Spring Boot, MyBatis, MySQL
- Other: Docker, AWS EC2, AWS Linux, Nginx, Postman

# Deployment Structure
The frontend and backend are deployed on separate servers. The frontend accesses the backend server through an Nginx reverse proxy, preventing the backend address from being exposed and enhancing security.
![deployment](images/deployment-myweb.jpg)

---

# 動機と概要
建築を学んでいた時代で、以下の課題を発見しました。
1.	建築学科の学生は多くの個人作品を持っており、それらをまとめてポートフォリオを作成するのが一般的です。従来のポートフォリオはPDF形式や冊子として印刷されることが多いですが、共有する際に不便さを感じることがあります。
2.	対面共有の場合を除いて、各作品に対して閲覧者から即時のフィードバックを得ることができません。
第三者プラットフォームに依存することのセキュリティ面を考慮し、自分の技術を活かして０→１ポートフォリオサイトを制作しようと考えています。  

# 画面表示
![mywebintro]()

# 機能モジュール
- 表示モジュール
- インタラクションモジュール
  - commentモジュール
  - contact meモジュール
 
# Backend API
- comment API
訪問者のコメントをdbに書き込み、データを永続化する  
[!commentAPI]()
- Email API
GmailのSMTPのAPIが呼び出されて、自分宛にメールを送信する  
[!emailAPI]()

# 技术栈
- Frontend: HTML,CSS,JavaScript（Reactで再構築中）
- Backend: Java,Spring,SpringBoot,Mybatis,MySQL
- Other: docker, AWS EC2,AWS Linux,Nginx,Postman

# 部署结构
フロントエンドとバックエンドを別々のサーバーにデプロイする。フロントエンドはNginxのリバースプロキシを通じてバックエンドサーバーにアクセスし、バックエンドのアドレスを公開しないことでセキュリティを強化する。
[!deployment]()


