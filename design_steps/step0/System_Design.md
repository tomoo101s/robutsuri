# 計算コードの設計

## 機能
- 1次元体系の取り扱い
    - 将来的には、3次元体系に拡張する
- 2群拡散理論2
    - 将来的には、多群計算に対応させる

## 設計・実装アプローチ
- オブジェクト指向
- テスト駆動型開発
- 外部ライブラリは用いない
    - Pure Python での実装

## プログラミング・フレームワーク
- MVC (Model-View-Controller) モデル
    - MVCM (Model-View-Contoller-Manager)モデル

## クラス
- Model
    - 断面積 (CrossSection)
    - 中性子束 (Flux)
    - 中性子流 (Current)
    - 計算ノード (Node)
    - 計算体系 (Container)

- View (今回は実装しない)
    - 帳票出力 (Editor)
     

- Controller & Manager
    - 計算体系制御 (ContainerController)
    - 計算全体管理 (CalculationManager)
