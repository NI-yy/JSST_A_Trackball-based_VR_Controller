# オブジェクトの効率的な回転操作を可能とするトラックボール型VRコントローラ

本リポジトリは，論文「オブジェクトの効率的な回転操作を可能とするトラックボール型VRコントローラ」のプロトタイプ実装において使用した3Dプリント用STLファイルを公開するものです．

## 概要の動画(WISS2025投稿時点)

https://github.com/user-attachments/assets/62c76dcf-048d-4372-a7d2-90046dcec173


## 注意

この実装はハードウェアに損傷を与える可能性があります．使用にあたっては自己責任でお願いします．これらの条件に同意いただけない場合はこのファイルを使用しないでください．

## 内容物 (Contents)

本リポジトリに含まれるSTLファイルは以下の通りです．各パーツは，既存の公開モデルを元に，本プロトタイプ用に調整・統合を行ったものです．

- **トラックボール台座部 (Ball Holder)**
    - `ballHolder_25mm.stl`: 25mmトラックボール用
    - `ballHolder_34mm.stl`: 34mmトラックボール用
    - `ballHolder_40mm.stl`: 40mmトラックボール用
    - *元モデル*: [ParRotHardware](https://github.com/ParRot-3DMouse/ParRotHardware)

- **コントローラ上部カバー・アタッチメント (Upside / Attachment)**
    - `25mm_body_upside.stl`: 25mm球用の上部カバー
    - `34mm_body_upside.stl`: 34mm球用の上部カバー
    - `40mm_body_upside.stl`: 40mm球用の上部カバー
    - `upper_attachment.stl`: 上部固定用のパーツ
    - *元モデル*:
        - [HTC Vive Joystick mod.](https://www.thingiverse.com/thing:2705398) (Thingiverse)
        - [SteamVR Unity Plugin - v2.8.0 (sdk 2.0.10)](https://github.com/ValveSoftware/steamvr_unity_plugin/tree/master) (Valve)

- **コントローラ下部カバー (Downside)**
    - `body_downside.stl`: コントローラ下部固定パーツ
    - *元モデル*: [SteamVR Unity Plugin - v2.8.0 (sdk 2.0.10)](https://github.com/ValveSoftware/steamvr_unity_plugin/tree/master) (Valve)

## 組み立て (Assembly)

1. **出力**: 提供されているSTLファイルを3Dプリンタで出力してください．本研究ではPETGフィラメントを使用しました．
2. **必要部品**:
    - HTC VIVE コントローラ
    - PMW3360 イメージセンサ x2
    - Arduino Nano Every
    - トラックボール (直径25mm, 34mm, または 40mm)
3. **配線**: 論文内の記述に従い，PMW3360センサーとArduino Nano Everyを接続してください．
4. **組み立て**: 出力したパーツをVIVEコントローラに装着します．
    - トラックボール台座部とコントローラ上部カバーは接着剤等で接着してください

## 出版物 (Publication)

岩井 望, 阿部 優樹, 坂本 大介

本プロジェクト・成果物を研究等で利用される場合は，論文が出版され次第，引用をお願いいたします．

## ライセンス
| ファイル名 | ライセンス / 権利情報 | 由来・権利者 |
| :--- | :--- | :--- |
| `ballHolder_*.stl` | **LGPL v2.1** | [ParRotHardware](https://github.com/ParRot-3DMouse/ParRotHardware) |
| `upper_attachment.stl` | **CC BY-NC 4.0** | [HTC Vive Joystick mod.](https://www.thingiverse.com/thing:2705398) |
| `body_downside.stl`<br>`upside_cover_*.stl` | **Copyright Valve Corporation** | [SteamVR Unity Plugin - v2.8.0 (sdk 2.0.10)](https://github.com/ValveSoftware/steamvr_unity_plugin/tree/master) |

## 連絡先 (Contact)

岩井 望 / Nozomu Iwai
(連絡先情報があればここに記載)
