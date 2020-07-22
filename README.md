# 多重録画のための画像を取得するためのツール

*※実際に、このツールで録画したものを合成してみたら、タイミングがズレていました… orz*

## 挙動

- 再生したいYouTubeのID（伴奏動画のID）を入力して、「開始」を押すと、再生と同時に録画を始める。
- 「終了」を押すと動画再生と録画が停止する。
- 「ダウンロード」を押すと、自分の端末に録画データをダウンロードできる。
-- もちろん、サーバ上などには録画データは保存されない。

https://stagingpost.github.io/rec/

![qr20200721230308166](https://user-images.githubusercontent.com/3211869/88141599-defe6f80-cc2e-11ea-9a7e-f9c0e4310204.png)

# 各要素を試すためのサンプルプログラム
## カメラ許可＆録画
https://stagingpost.github.io/rec/recording.html

![qr20200722160942504](https://user-images.githubusercontent.com/3211869/88145711-d198b380-cc35-11ea-97fe-27386ad13c40.png)

※PCではうまくいくが、iPhoneではうまくいっていない。

### ref
- https://qiita.com/niisan-tokyo/items/fa6ff649a9a3312148bc

## YouTube再生(Youtube Player API)
https://stagingpost.github.io/rec/youtube-api.html

