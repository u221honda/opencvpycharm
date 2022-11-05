# とりあえず撮る
- opencvのAIkitを使って
- 邪魔だからpycharmの開発環境のよくわからん奴消去

## デモ用プログラムで使用可能な検出モデル
<! -- 実行するといろいろ変わる　-- >
age-gender-recognition-retail-0013
deeplabv3p_person
emotions-recognition-retail-0003 *
face-detection-adas-0001
face-detection-retail-0004
facial-landmarks-35-adas-0002 *
human-pose-estimation-0001
landmarks-regression-retail-0009 *
mobilenet-ssd
mobileNetV2-PoseEstimation
pedestrian-detection-adas-0002
person-detection-retail-0013
person-vehicle-bike-detection-crossroad-1016
tiny-yolo-v3
vehicle-detection-adas-0002
vehicle-license-plate-detection-barrier-0106
yolo-v3
注）*印のモデルのみが、-cnn2 オプションでも使用できます。

<<<<<<< HEAD

## 実行

$ [python3 depthai_demo.py] [-cnn] deeplabv3p_person
<!-- ↑python3実行　　　　　　↑モデルを引用して実行できる -->

なぜかカメラだけで表示されない

- 何でだろう。
- とりあえず調べてみると
- カメラが左、設定が右に表示される
- webサイトではカメラだけなのに設定の問題か？
- 土曜日午前中に解決できたら良き
