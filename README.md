<h1>貪吃蛇遊戲</h1>
<h3>作者:108321002廖翊得 108321007黃舟淵</h3>
<h2>Input/Output unit:</h2><br>
* 8x8 LED 矩陣，用來顯示遊戲畫面。下圖為撞到牆壁後的哭臉。<br>
<img src="https://github.com/AlanjyHuang/Verilog-snake-game/blob/main/137318900_173068304577734_6861558222315300370_n.jpg" width="300"/><br>
* 從左至右控制分別為下上左右<br>
<img src="https://github.com/AlanjyHuang/Verilog-snake-game/blob/main/137587388_472858437449908_4353284761955897336_n.jpg" width="300"/><br>
* 控制器為暫停<br>
<img src="https://github.com/AlanjyHuang/Verilog-snake-game/blob/main/137281901_766069700675228_6092086914492976812_n.jpg" width="300"/><br>
* 七段顯示器，用來顯示目前得分。<br>
<img src="https://github.com/kamiry/FPGA-project-1/blob/master/images/IO2.jpg" width="300"/><br>
<h3>功能說明:</h3><br>
利用按鈕上下左右控制蛇去吃蘋果，每吃一顆加一分，在不撞到牆壁的前提下獲得6分即可勝利<br>
P.s.分數越高蛇跑越快

<h2>程式模組說明:</h2><br>
module slide_game(output reg[3:0]S //控制亮燈排數,output reg [7:0]Red //紅色燈,output reg [7:0]Green //綠色燈,
output reg [7:0]Blue //藍色燈,output reg [4:0]A_count,B_count //計分,output [6:0]O //倒計時,output reg beep //叫聲,input [1:0]button //玩家一左右,input [1:0]button2 //玩家二左右,input CLk,Clear); <br><br>
*** 請說明各 I/O 變數接到哪個 FPGA I/O 裝置，例如: button, button2 -> 接到 4-bit SW <br>
*** 請加強說明程式邏輯 <br>

<h2>Demo video: (請將影片放到雲端空間)</h2>

<a href="https://drive.google.com/file/d/1dsUKFF945moWpXyD0L86eseNf1l3repO/view?usp=sharing" title="Demo Video"><img src="https://github.com/kamiry/FPGA-project-1/blob/master/images/IO4.jpg" alt="Demo Video" width="500"/></a>

