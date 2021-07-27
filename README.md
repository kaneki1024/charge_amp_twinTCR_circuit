# 卒論にて作成した圧電センサ用の回路
力を加えると電荷、電圧が発生する圧電体という材料がある。中心対称性が無ければ圧電性は示すが、圧電体は誘電体であるため出力インピーダンスが非常に大きいという特徴をもつ。よって圧電体の電圧を計測ではなく表面の電荷計測を行い、センサとして利用する。
## チャージアンプ回路と50 HzノイズカットのTwinTCR回路
![chargeamp](https://user-images.githubusercontent.com/43879424/127097449-987aae51-a448-4a72-a7f9-6b7a19f854bc.jpg)

チャージアンプ回路は上の通り。電荷を電圧に変換させる。<br>
![TwinTCR](https://user-images.githubusercontent.com/43879424/127098384-d3f10031-cab2-4e95-baa6-ee736f62c8c3.jpg)
<br>
TwinTCR回路は上の通り。コンデンサCと抵抗Rの組み合わせを変えることでノッチフィルターの周波数を選択することが出来る。今回は、電源ノイズを消したいため、関東の電源は50 Hzであることに基づいて作成。
## 圧電体の電圧計測に基づく新規回路
