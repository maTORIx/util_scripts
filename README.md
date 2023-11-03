# util_scripts

便利スクリプト群おきば。

## コマンド一覧

- random ランダムなBASE64を生成
- img2webp 画像をwebpに変換。recursive対応。ディスク容量削減に便利。(ffmpeg必須)

## How to use
```sh
cd $インストール先
git clone https://github.com/maTORIx/util_scripts

# ffmpegがない場合(Ubuntu)
sudo apt install -y ffmpeg
```

bashの場合は.bashrcに以下を追記
```sh
export PATH="$インストール先/util_scripts/bin:$PATH"
```

## Licence
Unlicense
