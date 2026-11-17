# karabiner-config

個人用の [Karabiner-Elements](https://karabiner-elements.pqrs.org/) 設定。  
汎用テンプレではない。自分の機材・癖向け。

## 入れる

```bash
mkdir -p ~/.config/karabiner
cp karabiner.json ~/.config/karabiner/karabiner.json
```

適用後、Karabiner を開き直すか Reload する。

## 中身のクセ

| 変なところ | 何してるか |
|------------|------------|
| Kensington マウス | ボタン同時押しで Enter / Cmd+C / Cmd+V、ボタン差し替え |
| ILITEK（vendor 8746） | タッチの button1 を潰す（ゴミ入力対策） |
| F1 / F2 | `open -a` で iTerm / Chrome 起動 |
| F8 | Mission Control 相当（Cmd+D） |
| F9 / F10 / F11 | コピー / カット / ペースト |
| Fn + h/j/k/l 系 | 矢印・削除・ペースト等の独自レイヤ |
| Mouse Keys Mode | キーボードでポインタ操作 |
| Caps ↔ Control | 入れ替え。一部キーボードは device_if 付き |
| selected devices | 特定 vendor/product だけ対象 |

無い機材・別環境ではキーが変に感じることがある。そのときはこの JSON を外すか、Karabiner のプロファイルを切る。
