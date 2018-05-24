# try Open vSwitch

devstackの環境を整備する過程でOpen vSwitchが出てきたわけだが扱いがよくわからないので問題を疎結合させるために別個で[Open vSwitchのチュートリアル](http://docs.openvswitch.org/en/latest/tutorials/)でもやろうかなと。

## OVS Faucet Tutorial
[Faucet](https://faucet.nz)は商用ネットワークのためのOSSのSDNコントローラ。

## OpenFlowとは

Software Defined Networkと呼ばれるコンセプトの実装技術の一つ。よく聞くSDNを支えているらしい。従来のネットワーク機器は、各レイヤにわけられた機器が各々で経路を決定したいた。一方、OpenFlowはOpenFlowコントローラが経路を決定する。つまり、経路をより抽象的に扱うことができるようになった？
> [ネットワーク機器の世界を一変させるかもしれない「OpenFlow」 ｜これからは、コレ！｜ITソリューション&サービスならコベルコシステム](http://www.kobelcosys.co.jp/column/itwords/243/)

>ソフトウェアのように柔軟に制御可能なネットワーク技術(Software Defined Network)が求められています。
>
>OpenFlow技術です。**制御機能と転送機能が共存する既存のネットワーク機器とは異なり、OpenFlowでは、制御部と転送部を分離したアーキテクチャを採用しています**。
>
>[インターネット10分講座：OpenFlow - JPNIC](https://www.nic.ad.jp/ja/newsletter/No52/0800.html)


>## OpenFlowスイッチがさまざまなネットワーク機器になる
>
>フローテーブルの定義によって、OpenFlowスイッチが従来のネットワーク機器としてのスイッチ、ルータはもちろん、ファイアウォールやロードバランサのように振る舞うことも可能です。必要なときに必要なネットワークの機器を、ソフトウェアだけで迅速に調達できるようになります。
>
>[5分で絶対に分かるOpenFlow (4/6)：5分で絶対に分かる - ＠IT](http://www.atmarkit.co.jp/ait/articles/1112/12/news117_4.html)






