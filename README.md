3D_Printer_DIY_Prusa_i3
=======================


參考資料
========

(請先看這個)參考資料:https://github.com/open3dengineering/Prusa-i3 <br>
考資料:http://reprap.org/wiki/Prusa_i3_Build_Manual <br>
h簡中的版本:ttp://reprap.org/wiki/Prusa_i3_Build_Manual/zh_cn <br>
Taiwan 3D Printing Group Facebook: https://www.facebook.com/groups/427010570716215/ <br>
中文的說明組裝文件: http://diy3dprint.blogspot.tw/2013/10/prusa-i3-3d-diy.html <br>


目前看到幾個機型, 不確定是否相同:
```
Prusa Mendel i2 
Prusa i3
```

## 準備工作 ##
* 收集五金零件
* 收集模具零件
* 收集機械零件
* 收集電子零件

### 收集五金零件 ###

五金零件在露天上面都可以買的到, 也有人專門幫你都收集好了, 
如果想要自己購買的話可以參考文件的零件表, 照表的編號跟數量直接買下去就對了
譬如: M3x10mm 6 個, 就直接在露天打 M3x10mm 就會找到零件
零件表中的所有零件都要買到.

零件表位置: https://github.com/open3dengineering/Prusa-i3/blob/master/Manual/BuildManual%20i3.pdf <br>
請把第一頁的東西全部買到

3D printing 社團提供的五金採購地點
https://docs.google.com/spreadsheet/pub?key=0ApabUwkcTEfrdHlDYUQyQmt2clQ4OXo0TmZOM2dfdmc&output=html


### 收集模具零件 ###

模具零件可以自己用印的, 可是如果你沒有 3D 印表機的話, 就要找人幫你印, 或是用買的

#### 用印的 ####

如果要自己印零件的話, 要安裝軟體, 請裝 OpenSCAD `http://www.openscad.org/` 軟體是免費的,
裝好之後打開 open3dengineering\Prusa-i3\Extruder\src\compact-extruder_o3d_ceramic.scad 這個檔,
然後按 Design -> Compile and Render(CGAL) 右側看到的圖就是你最基本的模具, 當然還有其他的


#### 用買的 ####

Prusa_i2 套件, 我還不確定是否跟 i3 一樣: http://goods.ruten.com.tw/item/qa?21306258383258#qna

e-bay:
http://0rz.tw/MRDgE


### 收集機械零件 ###

步進馬達等請到露天買.

連結: http://class.ruten.com.tw/user/index00.php?s=theta_james
這個賣家是我露天找的, `不代表我推薦他`, 你自己可以找你自己喜歡的

### 收集電子零件 ###

請直接到露天買.

連結: 同機械零件賣家

## 組裝順序 ##
* 五金零件 
* 模具零件
* 機械零件
* 電子零件
* 韌體/軟體 
* 調教
* 測試

## README.md 格式 ##

```
$ ./preview_github_readme README.md
```

link in text `http://localhost/`






