<!-- $theme: default -->

# ユーザー増加中のIntelliJ IDEAを中心にIDEを探る

- 講師：前田和昭
- 担当：中部大学オープンソース研究会
- kmaeda@gmail.com
- https://github.com/kmaeda/OscNagoya2018
- オープンソースカンファレンス 2018 Nagoya (2018年5月19日)

多くのスライドでは，Wikipediaのコンテンツを使っています．

この文書は，クリエイティブ・コモンズ 表示-継承ライセンスの下で
利用可能です．
![](images/by-sa.png)

---
<!-- page_number: true -->

# IntelliJ IDEAを中心にIDEを探る

IntelliJ IDEA Community Editionがオープンソースとして公開されてから約８年たちました．
以前はIDE（統合開発環境）と言えばEclipseが主流だったはずなのに，
いつの間にかIntelliJ IDEAの利用者が大幅に増えてきました．
このセミナーでは，IDEの歴史から始まり，無料で公開されている
IntelliJ IDEA Community Editionを中心にIDEを解説します．

のはずが...


	　
	　
	　

---
# IntelliJ IDEAを中心にIDEを探る

IntelliJ IDEA Community Editionがオープンソースとして公開されてから約８年たちました．
以前はIDE（統合開発環境）と言えばEclipseが主流だったはずなのに，
いつの間にかIntelliJ IDEAの利用者が大幅に増えてきました．
このセミナーでは，IDEの歴史から始まり，無料で公開されている
~~IntelliJ IDEA Community Editionを中心にIDEを解説します．~~

のはずが...

調子に乗りすぎて，IntelliJ IDEAの話に入る前に，
スライドは既に30枚以上... (^_^;;
**ど〜しよ〜**

---
![](images/intro.jpg)

---
![](images/slide25.jpg)

---
![](images/slide26.jpg) CC BY 2.0

---
![](images/slide27.jpg)

---
![](images/slide28.jpg)

---
![](images/slide29.jpg)

---
# PDP11/23でUNIX V7の頃 (メモリ64KB)

![](images/slide29ed.jpg)

---
![](images/slide30.jpg)

---
![](images/slide31.jpg)

---
![](images/slide32.jpg)

---
![](images/slide33.jpg)

---
![](images/slide34.jpg)

---

# GUI (Graphical User Interface) の到来

![](images/Tektronix4404.jpg)

[Tektronix 4404 Smalltalk Demo](https://www.youtube.com/watch?v=8yxCJfayW-8)
https://www.youtube.com/watch?v=8yxCJfayW-8

クリエイティブ・コモンズ表示ライセンス

CC BY

---
# Tektronix 4404

- Motorola 68010 32bit microprocessor
- 1 Mbyte high-speed dynamic RAM memory
- Virutual memory management for 8 Mbyte address space
- 640x480 monocrome, bit-mapped display
- 1024x1024 display bit-map with smooth panning
- 40 Mbyte, 5.25" hard disk and 320 Kbyte, 5.25" floopy disk
- (option) Franz LISP programming language
- (option) Prolog programming language
- (option) EMACS Editor

http://www.wirfs-brock.com/allen/files/tek/4404-Flyer.pdf より抜粋

Commercial, sold for $14,950 

http://www.merlintec.com/swiki/hardware/26.html

---

# 統合開発環境

IDE (Integrated Development Environment) 
ソフトウェアの開発環境

従来、コンパイラ、テキストエディタ、デバッガなどがばらばらで利用していたものをひとつの対話型操作環境（多くはGUI）から利用できるようにしたもの．

https://ja.wikipedia.org/wiki/統合開発環境

---
# Integrated development environment

An integrated development environment (IDE) is a software application that provides comprehensive facilities to computer programmers for software development.
An IDE normally consists of a source code editor, build automation tools, and a debugger.
Most modern IDEs have **intelligent code completion**. 

https://en.wikipedia.org/wiki/Integrated_development_environment
より

---
# 統合開発環境の特徴

- プロジェクト管理
- バージョン管理
- GUIの作成
- チーム開発
- 作成補助
- ビルド、デバッグ補助

https://ja.wikipedia.org/wiki/統合開発環境より

---

# 代表的なIDE（統合開発環境）

- Visual Studio Code
- Eclipse
- NetBeans
- IntelliJ IDEA

---

# Visual Studio Code

Visual Studio Codeはソースコードエディタである。マイクロソフトにより開発され、Windows、Linux、macOS上で動作する。デバッグ、Gitクライアントの統合、シンタックスハイライト、インテリセンス、スニペット、リファクタリングなどの機能を持つ。カスタマイズもでき、利用者はエディタのテーマやキーボードショートカット等を変更できる。

## 歴史

Visual Studio Codeは、マイクロソフトの開発者会議Build 2015（2015年4月29日）にて公開され、プレビュー版がリリースされた。

2015年11月18日、Visual Studio Codeはリリースされ、その一部ソースコードがGitHubにMIT Licenseのもとで公開された。その際、拡張機能のサポートも追加された。

https://ja.wikipedia.org/wiki/Visual_Studio_Code より

---

# Visual Studio Code

Visual Studio Code is a source code editor developed by Microsoft for Windows, Linux and macOS. It includes support for debugging, embedded Git control, syntax highlighting, intelligent code completion, snippets, and code refactoring.
It is also customizable, so users can change the editor's theme, keyboard shortcuts, and preferences. It is free and open-source

https://en.wikipedia.org/wiki/Visual_Studio_Code より

---
# Visual Studio Code

![](images/vscode.png)


https://ja.wikipedia.org/wiki/Visual_Studio_Code#/media/File:Visual_Studio_Code_0.10.1_on_Windows_7,_with_search.png

MIT License

---

# Java Tools and Technologies Landscape Report 2016: Trends and Historical data

July 14, 2016


| |Eclipse|IntelliJ IDEA| NetBeans |
| :-: | :-: | :-: | :-: |
| 2012 | 62% | 24% | 14% |
| 2014 | 54% | 33% | 10% |
| 2016 | 41% | 46% | 10% |


https://zeroturnaround.com/rebellabs/java-tools-and-technologies-landscape-2016-trends/

他の調査でも2016年で，Eclipse = IntelliJ IDEA

http://www.baeldung.com/java-ides-2016

---
# Android Studio

Android Studio（アンドロイド スタジオ）は、Googleが提供するAndroidプラットフォームに対応する統合開発環境（IDE）。JetBrains社が開発したIntelliJ IDEAをベースにAndroid開発に最適化されており、Windows、macOSおよびLinux用が存在する。

2013年5月16日、Google I/Oカンファレンスにおいて発表され[5]、同年5月にアーリーアクセスプレビュー版がリリースされた[4]。その後、2014年6月に公開されたバージョン0.8.0からは、開発段階がベータ版へ移行した[6]。

更にその後、2014年12月8日に正式バージョン1.0.0が公開され、従来EclipseとADT（Android Developer Tools）により実現されていた開発環境を、Android Studioで実現できる様になった。 2015年末をもってEclipseとADTのサポートが打ち切られ[7]、Android開発環境はAndroid Studioに完全移行された。

https://ja.wikipedia.org/wiki/Android_Studio

---
# Developer Survey Results 2016
by stack overflow

## VII. Development Environments

https://insights.stackoverflow.com/survey/2016

---
# Java IDE: Eclipse, IntelliJ, NetBeans　3大 Java IDEを比較(2017年版)

@jhChoi 2017年09月28日に更新


シンプルさ（学習コスト）

- Eclipse: △
package explorer 画面、debugging画面、team synchronizing画面など、画面数が多く、最初は混乱する。
- IntelliJ: ○
Eclipseよりはシンプル。
- NetBeans: ◎
わかりやすくて初心者にも良い。

https://qiita.com/jhChoi/items/d60fe8cf396dfc11d51d

---
# Eclipseの歴史

1990年代後半の状況は、JBuilder、VisualCafe（英語版）、そしてIBMのVisualAge、PFUのteikadeなど第1世代のJava開発ツールが存在している。IBMは様々なプラットフォームの製品を抱えていることから、Javaのマルチプラットフォームの可能性に注目していた。単なるVisualAgeの代替ではなく、IBMや他社のツールを統合するための共通プラットフォームの開発という基本構想の下、1998年11月にIBMカナダでプロジェクトが開始された。開発に携わったのは、VisualAgeの開発を行ったObject Technology International (OTI) 研究所である。

その後、IBMはこのプラットフォームに搭載するツールの開発のために組織の編成を行い、さらにオープンソース化することで新しい開発者の引き込みを図った。2001年11月、IBMはEclipseをオープンソース化するとともに、

https://ja.wikipedia.org/wiki/Eclipse_(統合開発環境)

---
Eclipse is an integrated development environment (IDE) used in computer programming, and is the most widely used Java IDE(6). It contains a base workspace and an extensible plug-in system for customizing the environment.

(6)https://zeroturnaround.com/rebellabs/ides-vs-build-tools-how-eclipse-intellij-idea-netbeans-users-work-with-maven-ant-sbt-gradle/

## History

Eclipse was inspired by the Smalltalk-based VisualAge family of integrated development environment (IDE) products.

https://en.wikipedia.org/wiki/Eclipse_(software) より

---
# Eclipseの名前

![](images/Eclipse-name.jpg)

https://ja.wikipedia.org/wiki/Eclipse_(統合開発環境)

---

![](images/Eclipse_4.5.png)

https://ja.wikipedia.org/wiki/Eclipse_(統合開発環境)#/media/File:Eclipse_4.5.png

---
# Eclise日本語版

Pleiades - 日本語化プラグイン Eclipse, IntelliJ, PhpStorm...

http://mergedoc.osdn.jp/

- Pleiades All in One ダウンロード
- Pleiades プラグイン・ダウンロード

Pleiades は Eclipse や Android Studio のような Java アプリケーションを日本語化するためのツール

Jetbrains社の IDE (IntelliJ IDEA, PhpStorm, RubyMine, PyCharm など) の日本語化も可能

---
# IntelliJと前田の出会い ♡

- JavaScriptのIDEを探していた
- WebStormに出会い，そして惚れた ♡
- 同じ会社の製品にIntelliJ IDEAがある
- あれ？IntelliJ IDEAって聞いたことある
どこかのオープンソースイベントだったような...

![](images/OSCportland.jpg) ![](images/LinuxWorld.jpg)

---
# WebStormの価格 (2018年5月)

ビジネス向け
- US $129.00 / 1st year
- US $103.00 / 2nd year
- US $77.00 / 3rd yearとそれ以降

個人向け
- US $59.00 / 1st year
- US $47.00 / 2nd year
- US $35.00 / 3rd yearとそれ以降

無料の対象
- 学生と先生
- 教育用 (クラスライセンス)
- 非商用オープンソースプロジェクト

https://www.jetbrains.com/webstorm/buy/

---
# クラスライセンスを取得

Type: Classroom License
Reference No*: LC-xxxxx-Dxxxxx
Date of Issue: 25 November 2010
Expiration Date: 25 November 2011
Number of Authorized Users: not limited

=========== LICENSEE ============

Name: Chubu University

======= SOFTWARE PRODUCT ========

Product Name: WebStorm

---
# WebStormでデバッグ中

![](images/WebStorm.jpg)

---

# JetBrains社の製品

- IntelliJ IDEA
Ultimate版 と Community版
- WebStorm
- PhpStorm
- PyCharm
Professional版 と Community版
- RubyMine
- CLion
- GoLand

Education向けの無料版
- Java Edu
- Python Edu
- Kotlin Edu

---
# IntelliJ IDEA Ultimateの価格 (2018年5月)

ビジネス向け
- US $499.00 / 1st year
- US $399.00 / 2nd year
- US $299.00 / 3rd yearとそれ以降

個人向け
- US $149.00 / 1st year
- US $119.00 / 2nd year
- US $89.00 / 3rd yearとそれ以降

無料の対象
- 学生と先生
- 教育用 (クラスライセンス)
- 非商用オープンソースプロジェクト

https://www.jetbrains.com/idea/buy/

---

# IntelliJ IDEA

IntelliJ IDEA(インテリジェイ アイディア)は、チェコに本社を置くJetBrains社が開発した、Javaなど数多くのプログラミング言語に対応した統合開発環境である。

リファクタリング機能をJava用の統合開発環境としては初めて搭載したことでも知られる。変数に型のないプログラミング言語に対してもリファクタリングを提供している。

ZeroTurnaroundの調査によると、Javaの統合開発環境としてはEclipseに続いて2番目に人気である (2011年はシェア22%、2012年はシェア28%。

https://ja.wikipedia.org/wiki/IntelliJ_IDEA

2012年:24%, 2014年:33%, 2016年:46%

https://zeroturnaround.com/rebellabs/java-tools-and-technologies-landscape-2016-trends/

---
# History of IntelliJ IDEA

The first version of IntelliJ IDEA was released in January 2001, and was one of the first available Java IDEs with advanced code navigation and code refactoring capabilities integrated.

In December 2014, Google announced version 1.0 of Android Studio, an open source IDE for Android apps, based on the open source community edition of IntelliJ IDEA.

Other development environments based on IntelliJ's framework include AppCode, CLion, PhpStorm, PyCharm, RubyMine, WebStorm.

https://en.wikipedia.org/wiki/IntelliJ_IDEA

---
# IntelliJ IDEA Community版

![](images/IntelliJ-winprop.jpg)

---
# IntelliJ IDEA Community版

ソースコード
https://github.com/JetBrains/intellij-community

![](images/IntelliJ-source.jpg)

---
# IntelliJ IDEA Community版のデモ

---
# Developer Survey Results 2016
(by stack overflow)

### (Technology) VII. Development Environments

https://insights.stackoverflow.com/survey/2016

# 今絶好調のIntelliJ IDEA

https://zeroturnaround.com/rebellabs/java-tools-and-technologies-landscape-2016-trends/

これからの活躍が楽しみです！
