# verilog音频解码
verilog_WAV音频解码(WM8731芯片)

读取SD卡内WAV音频文件并通过WM8731进行解码

MIC_DACDAT 文件夹实现实事麦克风音频输入和扬声器播放

SD_WM8731_Wav_Decod 文件夹实现verilog_WAV音频解码(WM8731芯片)

如果需要改变FPGA的芯片，IP核要重新调用，或者自己写分频器。

SD卡的读取是采样SPI协议
