# 変更履歴

- CHANGE
    - 下位互換のない変更
- UPDATE
    - 下位互換がある変更
- ADD
    - 下位互換がある追加
- FIX
    - バグ修正


## develop

## 2022.1.0

- [UPDATE] 依存ライブラリの更新
    - `boost` を `1.78.0` に
    - `CLI11` を `2.1.2` に
    - `fmt` を `8.0.1` に
    - `spdlog` を `1.9.2` に
    - `rapidcsv` を `8.53` に
    - @haruyama
- [FIX] 宇宙船演算子を利用している箇所に #include <compare> を追加
    - @haruyama
    - https://github.com/shiguredo/cpp-mp4/pull/12

## 2021.3

- [UPDATE] `boost` を `1.76.0` に
    - @haruyama
    - https://github.com/shiguredo/cpp-mp4/pull/8

## 2021.2

- [ADD] av01, av1C box のサポート
    - @haruyama
- [ADD] get_version_string() の追加
    - @haruyama
- [UPDATE] `rapidcsv` を `8.48` に
    - @haruyama
- [FIX] MP4 ファイルの読み込み時に, ファイル終端を越える box のサイズを指定されたら例外を投げる
    - @haruyama
- [FIX] VPCodecConfiguration::getDataSize() のバグ修正
    - @haruyama

## 2021.1

**祝リリース**
