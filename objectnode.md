
 //节点类型
  TAttrib = (
    saNone,    //0
    saBlank,   //1
    saRoot,    //2
    saUnit,    //3
    saPro,     //4
    saSheet,   //5
    saPart,    //6
    saBill,    //7
    saRation,  //8
    saBasic,   //9
    saRG,      //10
    saCL,      //11
    saJX,      //12
    saZC,      //13
    saSB,      //14
    saPHB, //配合比 15
    saJXTB //机械台班 16
  );
  
### 对象属性
```
{
"nodetype":3,    
"level":3,
"postionmode":0,
"sortcode":0,
"partid":-1,
"attrib":5,     // 0=无  1=空 2=整体 3=单位 4=专业 5= 分部分项、技术措施  6=分部  7=清单 8=定额 9=材料(统称) 10=人工 11=材料 12=机械 13=主材 14=设备  15=配合比  16=机械台班

"origin":0,
"exchangemode":0, 
"gljguid":"",   //工料机guid
"tguid":"",
"bid":"",       //专业， 13t表示13清单   18t 表示18定额土建 
"codeid":"P1",
"id":232,
"groupid":-1,
"treeid":-1,"
linenno":"",
"remark":"",
"expanded":true,  //是否展开
"avar":"",
"feecode":"",  //取费号
"view":{   //视图数据
   "co":"",
   "n":"分部分项",
    "sn":"",
     "pn":"",
     "un":"",
   "ae":"",
   "am":1,
   "ur":1,
   "in":"",
   "ic":"",
   "p":64522.6423,
   "r":42762.5013,
   "c":9908.484,
   "j":11851.657,
   "z":9908.484,
   "s":0,
   "q":0,
   "zg":0,
   "dp":64522.6423,
   "dr":42762.5013,
   "dc":9908.484,
   "dj":0,
   "dz":0,
   "ds":0,
   "dq":0,
   "aj":0,
   "bj":0,
   "cj":0,
   "ej":0,
   "ab":"",
   "bb":"",
   "cb":"",
   "db":"",
   "eb":"",
   "ax":false,
   "bx":false,
   "cx":false,
   "rr":1,
   "cr":1,
   "jr":1,
   "zr":1,
   "sr":1,
   "qr":1,
   "ar":1,
   "dam":0,
   
   //扩展变量，回车换行
   "dv":"定额人工费=42762.5\r\n定额材料费=9908.48\r\n定额机械费=11851.66\r\n定额主材费=0\r\n定额设备费=0\r\n人工费=42762.5\r\n材料费=9908.48\r\n主材费=0\r\n设备费=0\r\n机械费=11851.66\r\n管理费=9049.57\r\n利润=4423.75\r\n风险=0\r\n综合单价=77995.96\r\n综合合价=77995.96\r\n",
   
   "dco":""
 }

```


