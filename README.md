## gank.io
感谢 http://gank.io 提供的api帮助完成这个app  
该项目完全开源，单纯为了学习与交流，希望大家喜欢，多多提意见。  
后续会将未来学到的新的技术或者框架运用到该项目，持续更新

<img src="https://github.com/zhujian1989/gank.io/blob/master/screenshots/1.png" width="200"> <img src="https://github.com/zhujian1989/gank.io/blob/master/screenshots/2.png" width="200"> <img src="https://github.com/zhujian1989/gank.io/blob/master/screenshots/3.png" width="200">
  
  
[点击下载 gankio.apk](http://fir.im/gzs1)

## 核心思想
整体采取MVP架构，在项目中做了一些实践
## 使用到的主流第三方库
dagger2  
retrofit2  
okhttp3  
glide  
rxandroid  
butterknife  
arouter  
(朋友的库，欢迎大家去体验)  
bga-refreshlayout  
bga-adapter   
   
## 关于我
快乐的程序猿，热衷撸代码
## 联系方式
QQ：370159662

微信：yangcong_370159662
## License

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
    
PS:如果跑代码无法跳转，请关闭InstantRun！
    开启InstantRun之后无法跳转(高版本Gradle插件下无法跳转)？
    因为开启InstantRun之后，很多类文件不会放在原本的dex中，需要单独去加载，ARouter默认不会去加载这些文件，因为安全原因，只有在开启了openDebug之后 ARouter才回去加载InstantRun产生的文件，所以在以上的情况下，需要在init之前调用openDebug

