ハードウェアの説明
==================
　ここでは本研究の実験に用いたロボットの説明をします。  
　  
今回はヒューマノイドロボットの最も簡易的なモデルである、3軸のロボットを用いました。  
このロボットは左右の足にピッチ方向の軸を、胴体にロール方向の軸を持っており、  
胴体を左右に振りながら重心を移動し、足を交互に前に出すことで歩行することができます。  
　  
　私たちはサーボの種類によって2機のロボットを製作し、実験に用いました。
### 1．PWM方式のサーボモータを用いたロボット ###
　　[![画像1][image1]](http://cloud.github.com/downloads/s-ryuki/Pictures/3axis_prs-ff09pii.png)
[image1]:http://cloud.github.com/downloads/s-ryuki/Pictures/3axis_prs-ff09pii.png

　　　サーボモータ：PRS-FF09PⅡ（Pirkus製）  
　　　電源：LiPo 7.4V (Hyperion製)  
　　　使用マイコン：mbed NXP LPC1768  
　  
### 2．コマンド方式のサーボモータを用いたロボット ###
　　[![画像2][image2]](http://cloud.github.com/downloads/s-ryuki/Pictures/3axis_prs-s40m2.png)
[image2]:http://cloud.github.com/downloads/s-ryuki/Pictures/3axis_prs-s40m2.png

　　　サーボモータ：PRS-S40M（Pirkus製）  
　　　電源：LiPo 7.4V  (Hyperion製)  

PRS-S40Mのハードウェアマニュアルはこちらをご覧ください。
　  
　　　[PRS-S07M/PRS-S40M ハードウェアマニュアル]()
　  
　これらのロボットは市販されているサーボモータを使用し、  
フレームはホビーロボットを自主制作する際に通常行うようなアルミ板の切削加工、曲げ加工等を施して製作しました。    
切削加工に用いるDXFデータをそれぞれのロボットに関してアップロードしましたのでご使用ください。  
　  
　　　PRS-FF09PⅡ用：[3axis_prs-ff09pii_frame.dxf]()  
　　　PRS-S40M用：[3axis_prs-s40m_frame.dxf]()  
　  
[Robotma.com](http://www.robotma.com/)では「オリジナルロボット製作支援サービス」としてDXFデータを渡せばアルミ板の切削加工を  
代行するサービスがあります。ほかのロボットショップでもこのような加工代行サービスを行っているところは多く、  
加工設備が無い場合でも製作できますので、ぜひお試しください。  
　このようなロボットは私たちの研究で使用した２種類のサーボモータ以外のものを用いても製作可能です。  
各軸間等を揃えたフレームを用いれば、入手しやすいサーボモータを使用してもロボットを動かすことができます。  
またフレームは、タミヤ社製ユニバーサルプレート（[http://www.tamiya.com/japan/products/70172plate/index.htm](http://www.tamiya.com/japan/products/70172plate/index.htm)）等を  
使用すれば簡単に製作できます。　　

