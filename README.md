OV7670 に映った映像をUARTでPCに送り640*480pixelのjpegにした。<br>
使ったFPGAボードDE0cv<br>
pinのアサインはqsf参照<br>
C言語でttyS3はCOM3である。(WSL1の場合)<br>
INTELのクオータスで＊sofがFPGAに書き込める<br>
VGAにも映像が映る。<br>
![image](https://github.com/user-attachments/assets/7675e224-16c4-435f-83b7-8f232ae32beb)

<br>
sudo apt install  libjpeg-dev<br>
gcc *.c -ljpeg
