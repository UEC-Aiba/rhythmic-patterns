# リズムと時間：体験アプリ

知覚・認知心理学特殊Ⅰ 第6回「リズムと時間」（2026年秋学期）で使う，体験用のウェブアプリです．ブラウザだけで動きます．インストールも，ログインも，いりません．

| アプリ | 内容 | フォルダ |
|---|---|---|
| リズムを聞いて，書いてみよう | リズムの同定課題（Desain & Honing, 2003 の実験1にならった体験用）．回答を，三角形の地図にプロット | `rhythm-identification/` |
| リズムに合わせて叩いてみよう | 同期タッピング（Polak et al., 2018 の課題と同じ形）．叩いたリズムの比を推定 | `tapping/` |
| ドラムのリズムを聞いて，評定しよう | シンコペーションとグルーヴ（Witek et al., 2014 に，ならった体験用）．動きたくなる度合いと心地よさを，評定 | `groove/` |

## 使い方

公開ページのアドレス（GitHub Pages）を開きます．

- `https://（ユーザー名）.github.io/（リポジトリ名）/`：アプリの一覧
- `.../rhythm-identification/`，`.../tapping/`，`.../groove/`：各アプリ

自分のパソコンで試すには，`index.html` を，ブラウザで，開くだけです．

## プライバシー

3つのアプリは，外部との通信も，端末への保存も，していません．回答は，各自の画面にだけ表示され，ページを閉じると，消えます．

## 注意

- 音は，ブラウザの Web Audio で作った**合成音**で，論文の刺激そのものでは，ありません（体験用の近似）．
- 結果を，論文の結果と，直接，比べることは，できません．
- スマートフォンの，マナーモード（iPhone は消音スイッチ）を，解除してください．Bluetooth のイヤホンは，音の遅れがあるため，タッピングには，向きません．

## 参考文献

- Desain, P., & Honing, H. (2003). The formation of rhythmic categories and metric priming. *Perception, 32*(3), 341–365.
- Polak, R., Jacoby, N., Fischinger, T., Goldberg, D., Holzapfel, A., & London, J. (2018). Rhythmic prototypes across cultures: A comparative study of tapping synchronization. *Music Perception, 36*(1), 1–23.
- Witek, M. A. G., Clarke, E. F., Wallentin, M., Kringelbach, M. L., & Vuust, P. (2014). Syncopation, body-movement and pleasure in groove music. *PLoS ONE, 9*(4), e94446.

## 作成

企画・授業での利用：（先生のお名前）．コードの作成には，AI（Claude, Anthropic）を使用しました．

## ライセンス

MIT License（`LICENSE` を参照）．
