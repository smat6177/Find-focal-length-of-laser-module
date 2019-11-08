# Find-focal-length-of-laser-module
This program is used to find out the focal length of laser module on my cr-7 cr-8 cr-10 ender-3 3D print machine.

這個程式是用來找出我的cr-7 cr-8 cr-10 ender-3 3D印表機上雷射模組的焦距。

<BR>一、請先手動執行AutoHome</BR>
<BR>二、移動軸 X,Y,Z 到起始測試點(平台左下角)及高度(例如35) </BR>
<BR>三、Print From SD 這個檔案，每移動10mm，Z軸會上升1mm，共會在影印紙上雷雕出20個線段(Z從35上升到54)。 </BR>
<BR>四、若仍沒看到線條，就直接再Print From SD 這個檔案一次，就會接著雕出另外20線段(55~74)。 </BR>
<BR>五、檢視雷雕結果，即可找出焦距。 </BR>
<BR>    以聖順的cr8為例，Z手動調整到35，再執行FindFocus20170130.gcode後，我認定有完整刻出的是z=43～51，所以我設定焦距為中間值 47 就可以了。 </BR>
<BR>六、如果想要改變焦距，可手動旋轉雷射模組前端的透鏡來調整。</BR>
