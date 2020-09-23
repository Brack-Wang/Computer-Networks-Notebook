# 多路复用技术
四种多路复用的意义和英文名称

最重要的是 码分多路复用

## 频分多路复用
一个大车道有很多的车

频谱搬移技术，如果频谱有重叠，则将频谱转移，使得每个信息在一个单独的频谱中传输

## 分时复用
每一种信息轮流使用

### 同步TDM
时间片的分配事先约定，且固定不变。每一个用户在帧里周期性出现。帧就是每一个用户都出现一次的时间，成为TDM帧。用户在帧内的位置不变。

时分复用：每一个时序进行扫描，如果有信息，则出传入。

### 异步TDM
统计时分复用 ： 为更多的用户提供服务。

但是需要在每一个帧的时系前需要加入地址，说明是来自谁的信息。

### TDM的应用
#### T1信号： 北美和日本的信号 1.544Mbps
带宽：3400Hz，每秒8000次速率对模拟信号采样

每一个采样值编码为7bit ，加上1bit控制信号

24路信号组成一帧

外加1个帧同步比特

`长度有多长？每个期间的帧：24*（7+1）+！=193bit； 每秒传输8000帧：193*8000=1.544Mbps`

E1传输系统： 中国 2.048Mbps







