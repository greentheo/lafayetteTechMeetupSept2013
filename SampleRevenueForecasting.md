<link href="css/bootstrap.min.css" rel="stylesheet" media="screen">
<link href="css/bootstrap.fluidlayout.css" rel="stylesheet" media="screen">
<script src="http://code.jquery.com/jquery-latest.js"></script>
<script src="js/bootstrap.min.js"></script>  


<!-- Stuff for Rcharts -->
<link rel='stylesheet' href='../rCharts/nvd3/css/nv.d3.css'>
<link rel='stylesheet' href='../rCharts/nvd3/css/rNVD3.css'>
<script src='../rCharts/nvd3/js/jquery-1.8.2.min.js' type='text/javascript'></script>
<script src='../rCharts/nvd3/js/d3.v2.min.js' type='text/javascript'></script>
<script src='../rCharts/nvd3/js/nv.d3.js' type='text/javascript'></script>
<script src='../rCharts/nvd3/js/fisheye.js' type='text/javascript'></script>





```
## Attaching package: 'zoo'
```

```
## The following object is masked from 'package:base':
## 
## as.Date, as.Date.numeric
```


<div class="navbar navbar-fixed-top">
  <div class="navbar-inner">
    <a class="brand" href="http://royaltyAnalytics.com">Royalty Analytics</a>
    <ul class="nav">
      <li><a href="#introduction">Introduction</a></li>
      <li><a href="#DataSummary">Data Summary</a></li>
      <li><a href="#Model">Model</a></li>
      <li><a href="#Results">Results</a></li>
    </ul>
  </div>
</div>




<div class="container">

<div class="row-fluid">

<div class="span12">

<div></div>

<h1>Stratego.com Revenue Forecasting Report</h1>
<hr>


<h2>Authors</h2>


<h3>Theodore Van Rooy on Behalf of Royalty Analytics</h3>
  
<div class="leaderboard">

  <a name="introduction"></a>
  
  <h1>Introduction</h1>
  
  <p>To help Stratego.com better manage its business, we have set out to predict future revenues.<p>
</div>  

<a name="DataSummary"></a>

Data Summary
------------------------

We are using sales and revenue data from 2009 to current (2013).  While the general trend is that Stratego.com is increasing revenues, the day to day and month to month planning can be difficult to predict.  

As we can see in the following data there are 2 strong features:





<div id='data' class='rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawdata()
    });
    function drawdata(){  
      var opts = {
 "dom": "data",
"width":    800,
"height":    400,
"x": "dates",
"y": "data",
"type": "lineChart",
"id": "data" 
},
        data = [
 {
 "dates":      1,
"data": 977.09 
},
{
 "dates":      2,
"data": 989.11 
},
{
 "dates":      3,
"data": 977.84 
},
{
 "dates":      4,
"data": 1027.8 
},
{
 "dates":      5,
"data": 1027.9 
},
{
 "dates":      6,
"data": 978.44 
},
{
 "dates":      7,
"data": 1008.4 
},
{
 "dates":      8,
"data": 967.67 
},
{
 "dates":      9,
"data": 989.06 
},
{
 "dates":     10,
"data": 991.83 
},
{
 "dates":     11,
"data": 1048.2 
},
{
 "dates":     12,
"data": 1001.9 
},
{
 "dates":     13,
"data": 1033.8 
},
{
 "dates":     14,
"data": 1069.1 
},
{
 "dates":     15,
"data": 1057.3 
},
{
 "dates":     16,
"data": 1093.1 
},
{
 "dates":     17,
"data": 1015.2 
},
{
 "dates":     18,
"data": 1037.5 
},
{
 "dates":     19,
"data": 1010.9 
},
{
 "dates":     20,
"data": 1046.4 
},
{
 "dates":     21,
"data": 1013.2 
},
{
 "dates":     22,
"data": 1039.9 
},
{
 "dates":     23,
"data": 1041.3 
},
{
 "dates":     24,
"data": 1103.9 
},
{
 "dates":     25,
"data":   1034 
},
{
 "dates":     26,
"data": 1057.8 
},
{
 "dates":     27,
"data":   1070 
},
{
 "dates":     28,
"data": 1044.4 
},
{
 "dates":     29,
"data": 1041.5 
},
{
 "dates":     30,
"data": 1100.5 
},
{
 "dates":     31,
"data": 1088.3 
},
{
 "dates":     32,
"data": 1109.4 
},
{
 "dates":     33,
"data": 1071.2 
},
{
 "dates":     34,
"data":   1108 
},
{
 "dates":     35,
"data": 1106.9 
},
{
 "dates":     36,
"data": 1081.5 
},
{
 "dates":     37,
"data": 1118.8 
},
{
 "dates":     38,
"data": 1084.4 
},
{
 "dates":     39,
"data": 1085.1 
},
{
 "dates":     40,
"data": 1016.3 
},
{
 "dates":     41,
"data": 1124.5 
},
{
 "dates":     42,
"data":   1066 
},
{
 "dates":     43,
"data": 1098.7 
},
{
 "dates":     44,
"data": 1035.6 
},
{
 "dates":     45,
"data": 1055.3 
},
{
 "dates":     46,
"data": 1111.6 
},
{
 "dates":     47,
"data": 1110.6 
},
{
 "dates":     48,
"data": 1084.4 
},
{
 "dates":     49,
"data": 1157.3 
},
{
 "dates":     50,
"data": 1077.3 
},
{
 "dates":     51,
"data": 1074.4 
},
{
 "dates":     52,
"data": 1095.2 
},
{
 "dates":     53,
"data": 1082.6 
},
{
 "dates":     54,
"data": 1067.6 
},
{
 "dates":     55,
"data": 1095.4 
},
{
 "dates":     56,
"data": 1075.5 
},
{
 "dates":     57,
"data": 1108.7 
},
{
 "dates":     58,
"data": 1045.7 
},
{
 "dates":     59,
"data": 1097.8 
},
{
 "dates":     60,
"data": 1094.3 
},
{
 "dates":     61,
"data":   1133 
},
{
 "dates":     62,
"data": 1100.4 
},
{
 "dates":     63,
"data": 1120.3 
},
{
 "dates":     64,
"data": 1077.1 
},
{
 "dates":     65,
"data": 1063.8 
},
{
 "dates":     66,
"data": 1154.9 
},
{
 "dates":     67,
"data": 1075.7 
},
{
 "dates":     68,
"data": 1136.6 
},
{
 "dates":     69,
"data": 1087.6 
},
{
 "dates":     70,
"data": 1183.6 
},
{
 "dates":     71,
"data": 1163.6 
},
{
 "dates":     72,
"data": 1127.7 
},
{
 "dates":     73,
"data": 1139.8 
},
{
 "dates":     74,
"data": 1133.8 
},
{
 "dates":     75,
"data": 1108.8 
},
{
 "dates":     76,
"data": 1175.7 
},
{
 "dates":     77,
"data": 1084.9 
},
{
 "dates":     78,
"data": 1145.3 
},
{
 "dates":     79,
"data": 1168.8 
},
{
 "dates":     80,
"data": 1123.3 
},
{
 "dates":     81,
"data": 1153.5 
},
{
 "dates":     82,
"data":   1097 
},
{
 "dates":     83,
"data": 1150.4 
},
{
 "dates":     84,
"data": 1164.5 
},
{
 "dates":     85,
"data": 1119.8 
},
{
 "dates":     86,
"data":   1153 
},
{
 "dates":     87,
"data": 1235.1 
},
{
 "dates":     88,
"data": 1118.8 
},
{
 "dates":     89,
"data": 1091.2 
},
{
 "dates":     90,
"data": 1111.4 
},
{
 "dates":     91,
"data": 1100.9 
},
{
 "dates":     92,
"data": 1157.9 
},
{
 "dates":     93,
"data": 1147.1 
},
{
 "dates":     94,
"data": 1105.2 
},
{
 "dates":     95,
"data":   1100 
},
{
 "dates":     96,
"data": 1111.7 
},
{
 "dates":     97,
"data": 1093.6 
},
{
 "dates":     98,
"data": 1166.2 
},
{
 "dates":     99,
"data": 1094.5 
},
{
 "dates":    100,
"data": 1163.7 
},
{
 "dates":    101,
"data": 1164.7 
},
{
 "dates":    102,
"data": 1129.4 
},
{
 "dates":    103,
"data": 1088.8 
},
{
 "dates":    104,
"data":   1076 
},
{
 "dates":    105,
"data": 1202.8 
},
{
 "dates":    106,
"data": 1080.7 
},
{
 "dates":    107,
"data": 1146.4 
},
{
 "dates":    108,
"data": 1175.4 
},
{
 "dates":    109,
"data": 1182.1 
},
{
 "dates":    110,
"data": 1151.6 
},
{
 "dates":    111,
"data": 1139.9 
},
{
 "dates":    112,
"data": 1150.9 
},
{
 "dates":    113,
"data": 1146.1 
},
{
 "dates":    114,
"data": 1190.2 
},
{
 "dates":    115,
"data": 1145.1 
},
{
 "dates":    116,
"data": 1172.5 
},
{
 "dates":    117,
"data": 1095.4 
},
{
 "dates":    118,
"data": 1106.9 
},
{
 "dates":    119,
"data": 1085.2 
},
{
 "dates":    120,
"data": 1130.6 
},
{
 "dates":    121,
"data": 1095.4 
},
{
 "dates":    122,
"data": 1111.9 
},
{
 "dates":    123,
"data": 1117.4 
},
{
 "dates":    124,
"data": 1074.2 
},
{
 "dates":    125,
"data": 1127.7 
},
{
 "dates":    126,
"data": 1121.5 
},
{
 "dates":    127,
"data": 1139.8 
},
{
 "dates":    128,
"data": 1112.7 
},
{
 "dates":    129,
"data": 1099.1 
},
{
 "dates":    130,
"data": 1090.1 
},
{
 "dates":    131,
"data": 1175.9 
},
{
 "dates":    132,
"data": 1114.5 
},
{
 "dates":    133,
"data": 1067.1 
},
{
 "dates":    134,
"data": 1097.4 
},
{
 "dates":    135,
"data":   1123 
},
{
 "dates":    136,
"data": 1130.7 
},
{
 "dates":    137,
"data": 1134.2 
},
{
 "dates":    138,
"data": 1138.2 
},
{
 "dates":    139,
"data": 1110.6 
},
{
 "dates":    140,
"data": 1085.6 
},
{
 "dates":    141,
"data": 1096.9 
},
{
 "dates":    142,
"data": 1115.9 
},
{
 "dates":    143,
"data": 1144.2 
},
{
 "dates":    144,
"data": 1181.2 
},
{
 "dates":    145,
"data": 1138.2 
},
{
 "dates":    146,
"data": 1117.5 
},
{
 "dates":    147,
"data": 1148.1 
},
{
 "dates":    148,
"data": 1113.5 
},
{
 "dates":    149,
"data": 1076.3 
},
{
 "dates":    150,
"data": 1113.9 
},
{
 "dates":    151,
"data": 1069.7 
},
{
 "dates":    152,
"data": 1107.1 
},
{
 "dates":    153,
"data": 1102.7 
},
{
 "dates":    154,
"data": 1082.4 
},
{
 "dates":    155,
"data": 1047.1 
},
{
 "dates":    156,
"data": 1160.4 
},
{
 "dates":    157,
"data": 1062.6 
},
{
 "dates":    158,
"data": 1124.5 
},
{
 "dates":    159,
"data": 1086.8 
},
{
 "dates":    160,
"data": 1130.5 
},
{
 "dates":    161,
"data": 1133.3 
},
{
 "dates":    162,
"data":   1074 
},
{
 "dates":    163,
"data": 1065.7 
},
{
 "dates":    164,
"data": 1053.1 
},
{
 "dates":    165,
"data": 1113.9 
},
{
 "dates":    166,
"data": 1048.2 
},
{
 "dates":    167,
"data": 1061.1 
},
{
 "dates":    168,
"data": 1080.8 
},
{
 "dates":    169,
"data": 1026.4 
},
{
 "dates":    170,
"data": 1005.9 
},
{
 "dates":    171,
"data": 1087.3 
},
{
 "dates":    172,
"data": 1133.6 
},
{
 "dates":    173,
"data":   1111 
},
{
 "dates":    174,
"data": 1063.6 
},
{
 "dates":    175,
"data":   1073 
},
{
 "dates":    176,
"data": 1061.3 
},
{
 "dates":    177,
"data": 1054.5 
},
{
 "dates":    178,
"data": 1055.1 
},
{
 "dates":    179,
"data": 1054.6 
},
{
 "dates":    180,
"data":   1094 
},
{
 "dates":    181,
"data": 1086.7 
},
{
 "dates":    182,
"data": 1088.7 
},
{
 "dates":    183,
"data": 1103.3 
},
{
 "dates":    184,
"data": 1069.8 
},
{
 "dates":    185,
"data": 1066.1 
},
{
 "dates":    186,
"data": 1103.6 
},
{
 "dates":    187,
"data": 1123.2 
},
{
 "dates":    188,
"data":   1069 
},
{
 "dates":    189,
"data": 1070.5 
},
{
 "dates":    190,
"data": 1093.9 
},
{
 "dates":    191,
"data": 1091.2 
},
{
 "dates":    192,
"data": 1049.8 
},
{
 "dates":    193,
"data": 1091.1 
},
{
 "dates":    194,
"data": 1029.2 
},
{
 "dates":    195,
"data": 1131.2 
},
{
 "dates":    196,
"data": 1063.2 
},
{
 "dates":    197,
"data": 1055.2 
},
{
 "dates":    198,
"data": 1046.1 
},
{
 "dates":    199,
"data": 1061.1 
},
{
 "dates":    200,
"data": 1054.8 
},
{
 "dates":    201,
"data": 1015.8 
},
{
 "dates":    202,
"data": 1006.8 
},
{
 "dates":    203,
"data":   1052 
},
{
 "dates":    204,
"data": 1034.1 
},
{
 "dates":    205,
"data": 1041.2 
},
{
 "dates":    206,
"data": 1079.3 
},
{
 "dates":    207,
"data": 1056.6 
},
{
 "dates":    208,
"data": 1012.3 
},
{
 "dates":    209,
"data": 1019.9 
},
{
 "dates":    210,
"data": 1003.7 
},
{
 "dates":    211,
"data": 997.72 
},
{
 "dates":    212,
"data": 1028.9 
},
{
 "dates":    213,
"data": 996.95 
},
{
 "dates":    214,
"data": 1029.4 
},
{
 "dates":    215,
"data":  993.2 
},
{
 "dates":    216,
"data": 979.12 
},
{
 "dates":    217,
"data": 1008.8 
},
{
 "dates":    218,
"data": 1054.6 
},
{
 "dates":    219,
"data": 1051.5 
},
{
 "dates":    220,
"data": 1007.7 
},
{
 "dates":    221,
"data": 1053.3 
},
{
 "dates":    222,
"data": 1047.1 
},
{
 "dates":    223,
"data": 1024.2 
},
{
 "dates":    224,
"data": 1005.8 
},
{
 "dates":    225,
"data": 960.91 
},
{
 "dates":    226,
"data": 1064.4 
},
{
 "dates":    227,
"data": 994.03 
},
{
 "dates":    228,
"data": 992.33 
},
{
 "dates":    229,
"data": 963.23 
},
{
 "dates":    230,
"data": 1003.3 
},
{
 "dates":    231,
"data": 1015.8 
},
{
 "dates":    232,
"data": 991.48 
},
{
 "dates":    233,
"data": 999.36 
},
{
 "dates":    234,
"data": 996.64 
},
{
 "dates":    235,
"data": 942.52 
},
{
 "dates":    236,
"data": 927.01 
},
{
 "dates":    237,
"data": 982.69 
},
{
 "dates":    238,
"data": 1037.5 
},
{
 "dates":    239,
"data": 1033.7 
},
{
 "dates":    240,
"data": 1004.6 
},
{
 "dates":    241,
"data": 1027.9 
},
{
 "dates":    242,
"data": 1044.6 
},
{
 "dates":    243,
"data": 1002.6 
},
{
 "dates":    244,
"data": 1021.6 
},
{
 "dates":    245,
"data": 1022.8 
},
{
 "dates":    246,
"data": 1027.3 
},
{
 "dates":    247,
"data": 1028.8 
},
{
 "dates":    248,
"data": 1001.6 
},
{
 "dates":    249,
"data": 987.07 
},
{
 "dates":    250,
"data": 963.46 
},
{
 "dates":    251,
"data": 992.24 
},
{
 "dates":    252,
"data": 1025.7 
},
{
 "dates":    253,
"data":  984.8 
},
{
 "dates":    254,
"data": 961.19 
},
{
 "dates":    255,
"data":    962 
},
{
 "dates":    256,
"data": 993.08 
},
{
 "dates":    257,
"data": 962.69 
},
{
 "dates":    258,
"data": 980.53 
},
{
 "dates":    259,
"data": 1048.9 
},
{
 "dates":    260,
"data": 977.48 
},
{
 "dates":    261,
"data": 955.39 
},
{
 "dates":    262,
"data": 956.52 
},
{
 "dates":    263,
"data": 984.45 
},
{
 "dates":    264,
"data":  955.9 
},
{
 "dates":    265,
"data": 1057.8 
},
{
 "dates":    266,
"data": 1029.1 
},
{
 "dates":    267,
"data": 1043.9 
},
{
 "dates":    268,
"data": 985.68 
},
{
 "dates":    269,
"data": 952.26 
},
{
 "dates":    270,
"data":   1011 
},
{
 "dates":    271,
"data": 1005.6 
},
{
 "dates":    272,
"data": 1009.1 
},
{
 "dates":    273,
"data": 982.41 
},
{
 "dates":    274,
"data": 992.78 
},
{
 "dates":    275,
"data": 990.18 
},
{
 "dates":    276,
"data": 974.67 
},
{
 "dates":    277,
"data": 999.46 
},
{
 "dates":    278,
"data": 996.93 
},
{
 "dates":    279,
"data":   1004 
},
{
 "dates":    280,
"data": 976.56 
},
{
 "dates":    281,
"data": 1010.7 
},
{
 "dates":    282,
"data": 965.13 
},
{
 "dates":    283,
"data": 1052.2 
},
{
 "dates":    284,
"data": 985.13 
},
{
 "dates":    285,
"data":   1008 
},
{
 "dates":    286,
"data": 1010.1 
},
{
 "dates":    287,
"data": 1006.2 
},
{
 "dates":    288,
"data": 978.15 
},
{
 "dates":    289,
"data": 1039.5 
},
{
 "dates":    290,
"data": 1054.7 
},
{
 "dates":    291,
"data": 1008.8 
},
{
 "dates":    292,
"data": 998.92 
},
{
 "dates":    293,
"data": 998.28 
},
{
 "dates":    294,
"data": 1020.8 
},
{
 "dates":    295,
"data": 931.21 
},
{
 "dates":    296,
"data": 1000.8 
},
{
 "dates":    297,
"data": 935.35 
},
{
 "dates":    298,
"data": 1010.2 
},
{
 "dates":    299,
"data": 1056.4 
},
{
 "dates":    300,
"data": 1036.6 
},
{
 "dates":    301,
"data":  993.9 
},
{
 "dates":    302,
"data": 1031.1 
},
{
 "dates":    303,
"data":   1025 
},
{
 "dates":    304,
"data": 997.85 
},
{
 "dates":    305,
"data": 973.84 
},
{
 "dates":    306,
"data":  980.9 
},
{
 "dates":    307,
"data": 1062.2 
},
{
 "dates":    308,
"data": 967.27 
},
{
 "dates":    309,
"data": 1035.6 
},
{
 "dates":    310,
"data": 1046.3 
},
{
 "dates":    311,
"data": 1078.6 
},
{
 "dates":    312,
"data": 1064.3 
},
{
 "dates":    313,
"data": 1025.9 
},
{
 "dates":    314,
"data": 1088.4 
},
{
 "dates":    315,
"data": 1041.7 
},
{
 "dates":    316,
"data":   1071 
},
{
 "dates":    317,
"data": 1006.4 
},
{
 "dates":    318,
"data": 1023.1 
},
{
 "dates":    319,
"data": 1005.6 
},
{
 "dates":    320,
"data": 1082.4 
},
{
 "dates":    321,
"data": 1041.8 
},
{
 "dates":    322,
"data": 1068.4 
},
{
 "dates":    323,
"data": 1063.5 
},
{
 "dates":    324,
"data": 991.38 
},
{
 "dates":    325,
"data": 992.71 
},
{
 "dates":    326,
"data": 1089.5 
},
{
 "dates":    327,
"data": 1069.7 
},
{
 "dates":    328,
"data": 1036.7 
},
{
 "dates":    329,
"data": 1111.1 
},
{
 "dates":    330,
"data": 1051.1 
},
{
 "dates":    331,
"data": 1032.5 
},
{
 "dates":    332,
"data":   1033 
},
{
 "dates":    333,
"data": 1052.8 
},
{
 "dates":    334,
"data": 1059.1 
},
{
 "dates":    335,
"data": 1087.8 
},
{
 "dates":    336,
"data": 1069.6 
},
{
 "dates":    337,
"data":   1033 
},
{
 "dates":    338,
"data": 1063.9 
},
{
 "dates":    339,
"data":   1118 
},
{
 "dates":    340,
"data": 1092.6 
},
{
 "dates":    341,
"data": 1062.1 
},
{
 "dates":    342,
"data": 1044.7 
},
{
 "dates":    343,
"data":   1127 
},
{
 "dates":    344,
"data": 1118.9 
},
{
 "dates":    345,
"data": 1023.7 
},
{
 "dates":    346,
"data": 1053.7 
},
{
 "dates":    347,
"data": 1129.3 
},
{
 "dates":    348,
"data": 1003.4 
},
{
 "dates":    349,
"data": 1121.8 
},
{
 "dates":    350,
"data": 1068.4 
},
{
 "dates":    351,
"data": 1059.8 
},
{
 "dates":    352,
"data": 1087.3 
},
{
 "dates":    353,
"data": 1104.4 
},
{
 "dates":    354,
"data": 1053.2 
},
{
 "dates":    355,
"data": 1061.2 
},
{
 "dates":    356,
"data": 1054.1 
},
{
 "dates":    357,
"data": 1115.4 
},
{
 "dates":    358,
"data": 1137.2 
},
{
 "dates":    359,
"data": 1124.7 
},
{
 "dates":    360,
"data": 1078.2 
},
{
 "dates":    361,
"data": 1124.5 
},
{
 "dates":    362,
"data": 1160.2 
},
{
 "dates":    363,
"data": 1122.5 
},
{
 "dates":    364,
"data": 1151.4 
},
{
 "dates":    365,
"data": 1197.1 
},
{
 "dates":    366,
"data":   1071 
},
{
 "dates":    367,
"data": 1121.9 
},
{
 "dates":    368,
"data": 1050.8 
},
{
 "dates":    369,
"data": 1086.4 
},
{
 "dates":    370,
"data": 1113.6 
},
{
 "dates":    371,
"data": 1056.3 
},
{
 "dates":    372,
"data": 1159.8 
},
{
 "dates":    373,
"data": 1168.8 
},
{
 "dates":    374,
"data": 1073.1 
},
{
 "dates":    375,
"data": 1189.4 
},
{
 "dates":    376,
"data": 1174.7 
},
{
 "dates":    377,
"data": 1173.7 
},
{
 "dates":    378,
"data": 1128.2 
},
{
 "dates":    379,
"data": 1154.2 
},
{
 "dates":    380,
"data": 1103.2 
},
{
 "dates":    381,
"data":   1141 
},
{
 "dates":    382,
"data":   1196 
},
{
 "dates":    383,
"data": 1118.8 
},
{
 "dates":    384,
"data": 1153.1 
},
{
 "dates":    385,
"data":   1210 
},
{
 "dates":    386,
"data": 1215.2 
},
{
 "dates":    387,
"data": 1120.2 
},
{
 "dates":    388,
"data": 1206.6 
},
{
 "dates":    389,
"data": 1144.4 
},
{
 "dates":    390,
"data": 1180.7 
},
{
 "dates":    391,
"data":   1211 
},
{
 "dates":    392,
"data": 1226.4 
},
{
 "dates":    393,
"data": 1153.1 
},
{
 "dates":    394,
"data": 1188.6 
},
{
 "dates":    395,
"data": 1177.1 
},
{
 "dates":    396,
"data": 1194.7 
},
{
 "dates":    397,
"data": 1213.8 
},
{
 "dates":    398,
"data": 1210.9 
},
{
 "dates":    399,
"data": 1178.4 
},
{
 "dates":    400,
"data": 1233.2 
},
{
 "dates":    401,
"data": 1223.7 
},
{
 "dates":    402,
"data": 1205.7 
},
{
 "dates":    403,
"data": 1164.2 
},
{
 "dates":    404,
"data": 1235.6 
},
{
 "dates":    405,
"data": 1110.9 
},
{
 "dates":    406,
"data": 1216.6 
},
{
 "dates":    407,
"data": 1182.7 
},
{
 "dates":    408,
"data": 1181.7 
},
{
 "dates":    409,
"data": 1226.1 
},
{
 "dates":    410,
"data": 1174.6 
},
{
 "dates":    411,
"data": 1190.9 
},
{
 "dates":    412,
"data": 1229.2 
},
{
 "dates":    413,
"data": 1215.9 
},
{
 "dates":    414,
"data": 1293.7 
},
{
 "dates":    415,
"data": 1255.7 
},
{
 "dates":    416,
"data": 1220.4 
},
{
 "dates":    417,
"data": 1273.7 
},
{
 "dates":    418,
"data": 1204.4 
},
{
 "dates":    419,
"data": 1205.7 
},
{
 "dates":    420,
"data": 1299.5 
},
{
 "dates":    421,
"data": 1246.5 
},
{
 "dates":    422,
"data": 1238.4 
},
{
 "dates":    423,
"data": 1155.2 
},
{
 "dates":    424,
"data": 1240.5 
},
{
 "dates":    425,
"data": 1206.7 
},
{
 "dates":    426,
"data":   1202 
},
{
 "dates":    427,
"data": 1234.6 
},
{
 "dates":    428,
"data": 1237.3 
},
{
 "dates":    429,
"data": 1287.4 
},
{
 "dates":    430,
"data": 1231.7 
},
{
 "dates":    431,
"data": 1235.7 
},
{
 "dates":    432,
"data":   1195 
},
{
 "dates":    433,
"data": 1280.6 
},
{
 "dates":    434,
"data": 1240.3 
},
{
 "dates":    435,
"data": 1265.3 
},
{
 "dates":    436,
"data": 1241.6 
},
{
 "dates":    437,
"data": 1185.9 
},
{
 "dates":    438,
"data": 1272.1 
},
{
 "dates":    439,
"data": 1241.1 
},
{
 "dates":    440,
"data": 1257.2 
},
{
 "dates":    441,
"data": 1274.5 
},
{
 "dates":    442,
"data": 1273.9 
},
{
 "dates":    443,
"data": 1139.6 
},
{
 "dates":    444,
"data": 1256.7 
},
{
 "dates":    445,
"data":   1235 
},
{
 "dates":    446,
"data": 1239.3 
},
{
 "dates":    447,
"data": 1228.5 
},
{
 "dates":    448,
"data": 1230.5 
},
{
 "dates":    449,
"data": 1175.5 
},
{
 "dates":    450,
"data": 1275.5 
},
{
 "dates":    451,
"data": 1308.9 
},
{
 "dates":    452,
"data": 1261.4 
},
{
 "dates":    453,
"data": 1259.4 
},
{
 "dates":    454,
"data":   1232 
},
{
 "dates":    455,
"data": 1241.1 
},
{
 "dates":    456,
"data": 1261.5 
},
{
 "dates":    457,
"data": 1246.8 
},
{
 "dates":    458,
"data": 1264.2 
},
{
 "dates":    459,
"data": 1228.5 
},
{
 "dates":    460,
"data": 1185.7 
},
{
 "dates":    461,
"data": 1252.8 
},
{
 "dates":    462,
"data": 1246.6 
},
{
 "dates":    463,
"data": 1244.7 
},
{
 "dates":    464,
"data": 1196.9 
},
{
 "dates":    465,
"data": 1237.4 
},
{
 "dates":    466,
"data": 1254.5 
},
{
 "dates":    467,
"data": 1227.9 
},
{
 "dates":    468,
"data": 1245.7 
},
{
 "dates":    469,
"data": 1263.2 
},
{
 "dates":    470,
"data": 1266.2 
},
{
 "dates":    471,
"data": 1265.2 
},
{
 "dates":    472,
"data": 1239.4 
},
{
 "dates":    473,
"data": 1269.9 
},
{
 "dates":    474,
"data": 1290.9 
},
{
 "dates":    475,
"data": 1290.3 
},
{
 "dates":    476,
"data": 1284.3 
},
{
 "dates":    477,
"data": 1253.4 
},
{
 "dates":    478,
"data": 1273.1 
},
{
 "dates":    479,
"data": 1330.7 
},
{
 "dates":    480,
"data": 1303.5 
},
{
 "dates":    481,
"data": 1268.6 
},
{
 "dates":    482,
"data": 1262.1 
},
{
 "dates":    483,
"data": 1310.1 
},
{
 "dates":    484,
"data": 1277.8 
},
{
 "dates":    485,
"data": 1247.8 
},
{
 "dates":    486,
"data": 1220.9 
},
{
 "dates":    487,
"data": 1258.9 
},
{
 "dates":    488,
"data": 1245.6 
},
{
 "dates":    489,
"data": 1225.6 
},
{
 "dates":    490,
"data": 1180.4 
},
{
 "dates":    491,
"data":   1257 
},
{
 "dates":    492,
"data": 1223.8 
},
{
 "dates":    493,
"data": 1294.2 
},
{
 "dates":    494,
"data":   1221 
},
{
 "dates":    495,
"data": 1207.2 
},
{
 "dates":    496,
"data": 1248.6 
},
{
 "dates":    497,
"data": 1221.2 
},
{
 "dates":    498,
"data": 1207.7 
},
{
 "dates":    499,
"data": 1236.6 
},
{
 "dates":    500,
"data": 1179.9 
},
{
 "dates":    501,
"data":   1260 
},
{
 "dates":    502,
"data": 1282.7 
},
{
 "dates":    503,
"data": 1251.4 
},
{
 "dates":    504,
"data": 1311.9 
},
{
 "dates":    505,
"data": 1202.9 
},
{
 "dates":    506,
"data": 1259.9 
},
{
 "dates":    507,
"data": 1231.5 
},
{
 "dates":    508,
"data": 1241.3 
},
{
 "dates":    509,
"data": 1231.4 
},
{
 "dates":    510,
"data": 1258.2 
},
{
 "dates":    511,
"data": 1234.5 
},
{
 "dates":    512,
"data": 1259.9 
},
{
 "dates":    513,
"data": 1189.1 
},
{
 "dates":    514,
"data": 1159.6 
},
{
 "dates":    515,
"data": 1192.1 
},
{
 "dates":    516,
"data": 1248.6 
},
{
 "dates":    517,
"data": 1289.8 
},
{
 "dates":    518,
"data": 1198.8 
},
{
 "dates":    519,
"data": 1319.6 
},
{
 "dates":    520,
"data": 1220.6 
},
{
 "dates":    521,
"data": 1211.1 
},
{
 "dates":    522,
"data": 1321.8 
},
{
 "dates":    523,
"data": 1134.8 
},
{
 "dates":    524,
"data": 1182.5 
},
{
 "dates":    525,
"data":   1165 
},
{
 "dates":    526,
"data": 1169.9 
},
{
 "dates":    527,
"data": 1132.7 
},
{
 "dates":    528,
"data": 1255.6 
},
{
 "dates":    529,
"data": 1181.1 
},
{
 "dates":    530,
"data": 1209.1 
},
{
 "dates":    531,
"data": 1180.6 
},
{
 "dates":    532,
"data": 1164.4 
},
{
 "dates":    533,
"data": 1228.6 
},
{
 "dates":    534,
"data": 1185.8 
},
{
 "dates":    535,
"data": 1181.4 
},
{
 "dates":    536,
"data": 1180.5 
},
{
 "dates":    537,
"data": 1270.7 
},
{
 "dates":    538,
"data": 1201.3 
},
{
 "dates":    539,
"data": 1184.7 
},
{
 "dates":    540,
"data":   1173 
},
{
 "dates":    541,
"data": 1230.1 
},
{
 "dates":    542,
"data":   1179 
},
{
 "dates":    543,
"data": 1200.6 
},
{
 "dates":    544,
"data": 1163.9 
},
{
 "dates":    545,
"data": 1229.5 
},
{
 "dates":    546,
"data": 1178.8 
},
{
 "dates":    547,
"data": 1213.6 
},
{
 "dates":    548,
"data": 1218.7 
},
{
 "dates":    549,
"data": 1239.4 
},
{
 "dates":    550,
"data": 1177.4 
},
{
 "dates":    551,
"data": 1215.4 
},
{
 "dates":    552,
"data": 1185.9 
},
{
 "dates":    553,
"data": 1160.8 
},
{
 "dates":    554,
"data": 1231.6 
},
{
 "dates":    555,
"data": 1135.6 
},
{
 "dates":    556,
"data": 1152.5 
},
{
 "dates":    557,
"data": 1174.1 
},
{
 "dates":    558,
"data": 1168.1 
},
{
 "dates":    559,
"data": 1129.8 
},
{
 "dates":    560,
"data": 1199.6 
},
{
 "dates":    561,
"data": 1141.4 
},
{
 "dates":    562,
"data": 1149.4 
},
{
 "dates":    563,
"data": 1167.5 
},
{
 "dates":    564,
"data": 1182.6 
},
{
 "dates":    565,
"data": 1164.1 
},
{
 "dates":    566,
"data": 1209.3 
},
{
 "dates":    567,
"data": 1157.7 
},
{
 "dates":    568,
"data": 1189.8 
},
{
 "dates":    569,
"data": 1112.2 
},
{
 "dates":    570,
"data": 1156.9 
},
{
 "dates":    571,
"data": 1111.9 
},
{
 "dates":    572,
"data": 1195.4 
},
{
 "dates":    573,
"data": 1194.1 
},
{
 "dates":    574,
"data": 1115.5 
},
{
 "dates":    575,
"data": 1136.1 
},
{
 "dates":    576,
"data":   1143 
},
{
 "dates":    577,
"data": 1237.7 
},
{
 "dates":    578,
"data": 1151.5 
},
{
 "dates":    579,
"data": 1103.4 
},
{
 "dates":    580,
"data": 1156.4 
},
{
 "dates":    581,
"data": 1173.2 
},
{
 "dates":    582,
"data": 1166.4 
},
{
 "dates":    583,
"data": 1163.8 
},
{
 "dates":    584,
"data": 1132.8 
},
{
 "dates":    585,
"data": 1100.5 
},
{
 "dates":    586,
"data": 1152.9 
},
{
 "dates":    587,
"data": 1151.7 
},
{
 "dates":    588,
"data": 1134.8 
},
{
 "dates":    589,
"data": 1175.5 
},
{
 "dates":    590,
"data": 1125.3 
},
{
 "dates":    591,
"data": 1165.9 
},
{
 "dates":    592,
"data":   1176 
},
{
 "dates":    593,
"data":   1137 
},
{
 "dates":    594,
"data": 1159.2 
},
{
 "dates":    595,
"data": 1143.4 
},
{
 "dates":    596,
"data": 1077.9 
},
{
 "dates":    597,
"data": 1110.5 
},
{
 "dates":    598,
"data": 1131.8 
},
{
 "dates":    599,
"data": 1109.1 
},
{
 "dates":    600,
"data": 1086.6 
},
{
 "dates":    601,
"data": 1196.5 
},
{
 "dates":    602,
"data": 1216.6 
},
{
 "dates":    603,
"data": 1098.4 
},
{
 "dates":    604,
"data": 1110.2 
},
{
 "dates":    605,
"data": 1156.4 
},
{
 "dates":    606,
"data": 1140.2 
},
{
 "dates":    607,
"data": 1161.3 
},
{
 "dates":    608,
"data":   1144 
},
{
 "dates":    609,
"data": 1103.7 
},
{
 "dates":    610,
"data": 1173.6 
},
{
 "dates":    611,
"data": 1130.3 
},
{
 "dates":    612,
"data": 1065.9 
},
{
 "dates":    613,
"data": 1079.4 
},
{
 "dates":    614,
"data": 1092.5 
},
{
 "dates":    615,
"data": 1152.9 
},
{
 "dates":    616,
"data": 1130.2 
},
{
 "dates":    617,
"data":   1173 
},
{
 "dates":    618,
"data": 1126.2 
},
{
 "dates":    619,
"data": 1116.3 
},
{
 "dates":    620,
"data": 1135.4 
},
{
 "dates":    621,
"data": 1087.4 
},
{
 "dates":    622,
"data": 1148.4 
},
{
 "dates":    623,
"data": 1152.1 
},
{
 "dates":    624,
"data": 1128.7 
},
{
 "dates":    625,
"data": 1108.6 
},
{
 "dates":    626,
"data":   1187 
},
{
 "dates":    627,
"data": 1076.4 
},
{
 "dates":    628,
"data": 1154.9 
},
{
 "dates":    629,
"data": 1118.4 
},
{
 "dates":    630,
"data": 1037.1 
},
{
 "dates":    631,
"data": 1114.9 
},
{
 "dates":    632,
"data": 1113.1 
},
{
 "dates":    633,
"data": 1185.6 
},
{
 "dates":    634,
"data": 1165.1 
},
{
 "dates":    635,
"data": 1132.2 
},
{
 "dates":    636,
"data": 1134.2 
},
{
 "dates":    637,
"data":   1177 
},
{
 "dates":    638,
"data": 1158.7 
},
{
 "dates":    639,
"data": 1166.3 
},
{
 "dates":    640,
"data": 1101.7 
},
{
 "dates":    641,
"data": 1175.8 
},
{
 "dates":    642,
"data": 1088.8 
},
{
 "dates":    643,
"data": 1101.4 
},
{
 "dates":    644,
"data": 1107.7 
},
{
 "dates":    645,
"data": 1158.8 
},
{
 "dates":    646,
"data": 1161.4 
},
{
 "dates":    647,
"data": 1145.2 
},
{
 "dates":    648,
"data": 1199.9 
},
{
 "dates":    649,
"data": 1131.4 
},
{
 "dates":    650,
"data": 1106.2 
},
{
 "dates":    651,
"data": 1094.1 
},
{
 "dates":    652,
"data":   1120 
},
{
 "dates":    653,
"data":   1109 
},
{
 "dates":    654,
"data": 1119.8 
},
{
 "dates":    655,
"data": 1179.6 
},
{
 "dates":    656,
"data": 1127.1 
},
{
 "dates":    657,
"data": 1108.4 
},
{
 "dates":    658,
"data": 1163.1 
},
{
 "dates":    659,
"data": 1116.1 
},
{
 "dates":    660,
"data": 1133.7 
},
{
 "dates":    661,
"data": 1184.1 
},
{
 "dates":    662,
"data": 1105.2 
},
{
 "dates":    663,
"data": 1128.7 
},
{
 "dates":    664,
"data": 1152.5 
},
{
 "dates":    665,
"data": 1096.3 
},
{
 "dates":    666,
"data": 1100.3 
},
{
 "dates":    667,
"data": 1130.2 
},
{
 "dates":    668,
"data": 1171.9 
},
{
 "dates":    669,
"data": 1089.6 
},
{
 "dates":    670,
"data": 1118.5 
},
{
 "dates":    671,
"data":   1150 
},
{
 "dates":    672,
"data": 1102.1 
},
{
 "dates":    673,
"data": 1139.8 
},
{
 "dates":    674,
"data": 1144.5 
},
{
 "dates":    675,
"data": 1109.2 
},
{
 "dates":    676,
"data": 1195.5 
},
{
 "dates":    677,
"data": 1102.2 
},
{
 "dates":    678,
"data": 1138.5 
},
{
 "dates":    679,
"data": 1152.9 
},
{
 "dates":    680,
"data": 1136.1 
},
{
 "dates":    681,
"data": 1119.9 
},
{
 "dates":    682,
"data": 1084.3 
},
{
 "dates":    683,
"data":   1213 
},
{
 "dates":    684,
"data": 1118.3 
},
{
 "dates":    685,
"data": 1152.1 
},
{
 "dates":    686,
"data": 1182.3 
},
{
 "dates":    687,
"data": 1154.9 
},
{
 "dates":    688,
"data": 1167.2 
},
{
 "dates":    689,
"data": 1197.3 
},
{
 "dates":    690,
"data": 1178.7 
},
{
 "dates":    691,
"data": 1126.5 
},
{
 "dates":    692,
"data": 1154.3 
},
{
 "dates":    693,
"data": 1198.4 
},
{
 "dates":    694,
"data": 1130.7 
},
{
 "dates":    695,
"data":   1138 
},
{
 "dates":    696,
"data": 1148.3 
},
{
 "dates":    697,
"data": 1133.8 
},
{
 "dates":    698,
"data": 1223.6 
},
{
 "dates":    699,
"data": 1224.2 
},
{
 "dates":    700,
"data": 1176.4 
},
{
 "dates":    701,
"data": 1137.4 
},
{
 "dates":    702,
"data": 1187.5 
},
{
 "dates":    703,
"data": 1202.2 
},
{
 "dates":    704,
"data": 1224.1 
},
{
 "dates":    705,
"data": 1161.9 
},
{
 "dates":    706,
"data": 1197.8 
},
{
 "dates":    707,
"data": 1160.3 
},
{
 "dates":    708,
"data": 1199.3 
},
{
 "dates":    709,
"data": 1166.5 
},
{
 "dates":    710,
"data": 1256.8 
},
{
 "dates":    711,
"data": 1228.5 
},
{
 "dates":    712,
"data": 1242.1 
},
{
 "dates":    713,
"data": 1222.3 
},
{
 "dates":    714,
"data": 1249.8 
},
{
 "dates":    715,
"data":   1251 
},
{
 "dates":    716,
"data": 1222.6 
},
{
 "dates":    717,
"data": 1170.7 
},
{
 "dates":    718,
"data": 1297.5 
},
{
 "dates":    719,
"data": 1205.8 
},
{
 "dates":    720,
"data": 1231.6 
},
{
 "dates":    721,
"data": 1255.6 
},
{
 "dates":    722,
"data": 1210.7 
},
{
 "dates":    723,
"data": 1210.6 
},
{
 "dates":    724,
"data": 1249.5 
},
{
 "dates":    725,
"data": 1255.7 
},
{
 "dates":    726,
"data":   1193 
},
{
 "dates":    727,
"data":   1260 
},
{
 "dates":    728,
"data": 1284.6 
},
{
 "dates":    729,
"data": 1255.2 
},
{
 "dates":    730,
"data": 1245.5 
},
{
 "dates":    731,
"data": 1209.3 
},
{
 "dates":    732,
"data": 1197.3 
},
{
 "dates":    733,
"data": 1210.3 
},
{
 "dates":    734,
"data": 1239.4 
},
{
 "dates":    735,
"data": 1300.5 
},
{
 "dates":    736,
"data": 1194.7 
},
{
 "dates":    737,
"data": 1311.9 
},
{
 "dates":    738,
"data": 1312.5 
},
{
 "dates":    739,
"data": 1273.8 
},
{
 "dates":    740,
"data": 1297.2 
},
{
 "dates":    741,
"data": 1218.4 
},
{
 "dates":    742,
"data": 1288.4 
},
{
 "dates":    743,
"data": 1292.8 
},
{
 "dates":    744,
"data": 1247.4 
},
{
 "dates":    745,
"data": 1323.9 
},
{
 "dates":    746,
"data": 1373.5 
},
{
 "dates":    747,
"data": 1300.3 
},
{
 "dates":    748,
"data": 1293.2 
},
{
 "dates":    749,
"data": 1230.5 
},
{
 "dates":    750,
"data": 1368.8 
},
{
 "dates":    751,
"data": 1220.1 
},
{
 "dates":    752,
"data": 1273.1 
},
{
 "dates":    753,
"data": 1248.4 
},
{
 "dates":    754,
"data": 1330.7 
},
{
 "dates":    755,
"data":   1325 
},
{
 "dates":    756,
"data": 1284.9 
},
{
 "dates":    757,
"data": 1302.5 
},
{
 "dates":    758,
"data": 1328.7 
},
{
 "dates":    759,
"data": 1309.5 
},
{
 "dates":    760,
"data": 1236.1 
},
{
 "dates":    761,
"data": 1337.1 
},
{
 "dates":    762,
"data": 1318.8 
},
{
 "dates":    763,
"data": 1309.7 
},
{
 "dates":    764,
"data": 1291.7 
},
{
 "dates":    765,
"data": 1296.7 
},
{
 "dates":    766,
"data": 1324.9 
},
{
 "dates":    767,
"data": 1367.3 
},
{
 "dates":    768,
"data":   1335 
},
{
 "dates":    769,
"data": 1288.6 
},
{
 "dates":    770,
"data": 1395.8 
},
{
 "dates":    771,
"data": 1328.3 
},
{
 "dates":    772,
"data": 1206.5 
},
{
 "dates":    773,
"data": 1324.3 
},
{
 "dates":    774,
"data": 1347.4 
},
{
 "dates":    775,
"data": 1347.9 
},
{
 "dates":    776,
"data": 1338.8 
},
{
 "dates":    777,
"data": 1308.7 
},
{
 "dates":    778,
"data": 1363.8 
},
{
 "dates":    779,
"data": 1343.2 
},
{
 "dates":    780,
"data":   1343 
},
{
 "dates":    781,
"data": 1380.2 
},
{
 "dates":    782,
"data": 1324.5 
},
{
 "dates":    783,
"data": 1373.3 
},
{
 "dates":    784,
"data": 1358.9 
},
{
 "dates":    785,
"data": 1336.7 
},
{
 "dates":    786,
"data":   1368 
},
{
 "dates":    787,
"data": 1321.1 
},
{
 "dates":    788,
"data": 1304.7 
},
{
 "dates":    789,
"data": 1354.9 
},
{
 "dates":    790,
"data": 1376.7 
},
{
 "dates":    791,
"data": 1344.1 
},
{
 "dates":    792,
"data": 1327.8 
},
{
 "dates":    793,
"data": 1395.5 
},
{
 "dates":    794,
"data": 1392.3 
},
{
 "dates":    795,
"data": 1350.6 
},
{
 "dates":    796,
"data": 1407.6 
},
{
 "dates":    797,
"data": 1378.6 
},
{
 "dates":    798,
"data":   1283 
},
{
 "dates":    799,
"data": 1377.6 
},
{
 "dates":    800,
"data":   1317 
},
{
 "dates":    801,
"data": 1455.3 
},
{
 "dates":    802,
"data": 1426.1 
},
{
 "dates":    803,
"data": 1367.9 
},
{
 "dates":    804,
"data": 1342.6 
},
{
 "dates":    805,
"data": 1332.9 
},
{
 "dates":    806,
"data": 1326.3 
},
{
 "dates":    807,
"data": 1456.4 
},
{
 "dates":    808,
"data": 1378.8 
},
{
 "dates":    809,
"data": 1326.2 
},
{
 "dates":    810,
"data": 1475.7 
},
{
 "dates":    811,
"data": 1372.6 
},
{
 "dates":    812,
"data":   1220 
},
{
 "dates":    813,
"data": 1382.5 
},
{
 "dates":    814,
"data": 1385.9 
},
{
 "dates":    815,
"data": 1446.3 
},
{
 "dates":    816,
"data": 1406.6 
},
{
 "dates":    817,
"data": 1360.2 
},
{
 "dates":    818,
"data": 1411.9 
},
{
 "dates":    819,
"data": 1319.3 
},
{
 "dates":    820,
"data": 1362.6 
},
{
 "dates":    821,
"data": 1348.7 
},
{
 "dates":    822,
"data": 1394.4 
},
{
 "dates":    823,
"data": 1387.5 
},
{
 "dates":    824,
"data": 1353.4 
},
{
 "dates":    825,
"data":   1350 
},
{
 "dates":    826,
"data": 1332.1 
},
{
 "dates":    827,
"data": 1349.5 
},
{
 "dates":    828,
"data": 1368.6 
},
{
 "dates":    829,
"data": 1346.4 
},
{
 "dates":    830,
"data": 1376.4 
},
{
 "dates":    831,
"data": 1392.4 
},
{
 "dates":    832,
"data": 1318.2 
},
{
 "dates":    833,
"data": 1371.8 
},
{
 "dates":    834,
"data": 1397.8 
},
{
 "dates":    835,
"data": 1374.3 
},
{
 "dates":    836,
"data": 1441.2 
},
{
 "dates":    837,
"data":   1418 
},
{
 "dates":    838,
"data": 1401.4 
},
{
 "dates":    839,
"data": 1432.6 
},
{
 "dates":    840,
"data": 1294.2 
},
{
 "dates":    841,
"data": 1387.3 
},
{
 "dates":    842,
"data": 1381.2 
},
{
 "dates":    843,
"data": 1359.5 
},
{
 "dates":    844,
"data": 1415.4 
},
{
 "dates":    845,
"data": 1383.1 
},
{
 "dates":    846,
"data": 1367.3 
},
{
 "dates":    847,
"data": 1374.8 
},
{
 "dates":    848,
"data": 1437.6 
},
{
 "dates":    849,
"data": 1401.4 
},
{
 "dates":    850,
"data": 1434.5 
},
{
 "dates":    851,
"data": 1375.3 
},
{
 "dates":    852,
"data": 1325.8 
},
{
 "dates":    853,
"data": 1374.5 
},
{
 "dates":    854,
"data": 1385.8 
},
{
 "dates":    855,
"data": 1337.3 
},
{
 "dates":    856,
"data": 1283.1 
},
{
 "dates":    857,
"data": 1394.9 
},
{
 "dates":    858,
"data": 1259.7 
},
{
 "dates":    859,
"data": 1375.8 
},
{
 "dates":    860,
"data": 1350.9 
},
{
 "dates":    861,
"data": 1347.4 
},
{
 "dates":    862,
"data": 1372.5 
},
{
 "dates":    863,
"data": 1346.1 
},
{
 "dates":    864,
"data": 1338.9 
},
{
 "dates":    865,
"data": 1347.4 
},
{
 "dates":    866,
"data": 1379.3 
},
{
 "dates":    867,
"data": 1396.5 
},
{
 "dates":    868,
"data": 1277.9 
},
{
 "dates":    869,
"data": 1368.7 
},
{
 "dates":    870,
"data": 1335.9 
},
{
 "dates":    871,
"data": 1308.1 
},
{
 "dates":    872,
"data": 1414.9 
},
{
 "dates":    873,
"data": 1309.3 
},
{
 "dates":    874,
"data": 1398.7 
},
{
 "dates":    875,
"data": 1296.3 
},
{
 "dates":    876,
"data": 1408.3 
},
{
 "dates":    877,
"data": 1412.2 
},
{
 "dates":    878,
"data": 1329.3 
},
{
 "dates":    879,
"data": 1370.5 
},
{
 "dates":    880,
"data": 1389.7 
},
{
 "dates":    881,
"data": 1397.3 
},
{
 "dates":    882,
"data": 1352.7 
},
{
 "dates":    883,
"data": 1335.3 
},
{
 "dates":    884,
"data": 1328.9 
},
{
 "dates":    885,
"data": 1315.2 
},
{
 "dates":    886,
"data": 1331.8 
},
{
 "dates":    887,
"data": 1327.4 
},
{
 "dates":    888,
"data": 1377.4 
},
{
 "dates":    889,
"data": 1364.8 
},
{
 "dates":    890,
"data": 1327.1 
},
{
 "dates":    891,
"data": 1337.6 
},
{
 "dates":    892,
"data": 1391.7 
},
{
 "dates":    893,
"data": 1348.1 
},
{
 "dates":    894,
"data": 1349.6 
},
{
 "dates":    895,
"data": 1310.7 
},
{
 "dates":    896,
"data":   1341 
},
{
 "dates":    897,
"data": 1357.4 
},
{
 "dates":    898,
"data": 1276.5 
},
{
 "dates":    899,
"data": 1320.8 
},
{
 "dates":    900,
"data": 1253.7 
},
{
 "dates":    901,
"data": 1441.3 
},
{
 "dates":    902,
"data": 1349.3 
},
{
 "dates":    903,
"data": 1378.1 
},
{
 "dates":    904,
"data": 1366.2 
},
{
 "dates":    905,
"data": 1293.9 
},
{
 "dates":    906,
"data":   1275 
},
{
 "dates":    907,
"data": 1258.9 
},
{
 "dates":    908,
"data": 1385.2 
},
{
 "dates":    909,
"data": 1340.2 
},
{
 "dates":    910,
"data": 1368.2 
},
{
 "dates":    911,
"data": 1355.9 
},
{
 "dates":    912,
"data": 1271.1 
},
{
 "dates":    913,
"data": 1327.2 
},
{
 "dates":    914,
"data": 1283.5 
},
{
 "dates":    915,
"data": 1282.3 
},
{
 "dates":    916,
"data": 1379.6 
},
{
 "dates":    917,
"data": 1346.6 
},
{
 "dates":    918,
"data": 1321.4 
},
{
 "dates":    919,
"data": 1291.8 
},
{
 "dates":    920,
"data": 1285.4 
},
{
 "dates":    921,
"data": 1258.3 
},
{
 "dates":    922,
"data": 1298.7 
},
{
 "dates":    923,
"data": 1277.9 
},
{
 "dates":    924,
"data": 1325.6 
},
{
 "dates":    925,
"data": 1307.5 
},
{
 "dates":    926,
"data": 1264.3 
},
{
 "dates":    927,
"data": 1339.3 
},
{
 "dates":    928,
"data": 1315.6 
},
{
 "dates":    929,
"data": 1282.9 
},
{
 "dates":    930,
"data": 1368.8 
},
{
 "dates":    931,
"data":   1298 
},
{
 "dates":    932,
"data": 1179.1 
},
{
 "dates":    933,
"data":   1253 
},
{
 "dates":    934,
"data": 1280.7 
},
{
 "dates":    935,
"data": 1320.9 
},
{
 "dates":    936,
"data": 1235.7 
},
{
 "dates":    937,
"data": 1287.3 
},
{
 "dates":    938,
"data": 1311.1 
},
{
 "dates":    939,
"data": 1272.6 
},
{
 "dates":    940,
"data": 1275.6 
},
{
 "dates":    941,
"data": 1271.6 
},
{
 "dates":    942,
"data": 1239.2 
},
{
 "dates":    943,
"data": 1269.4 
},
{
 "dates":    944,
"data": 1303.5 
},
{
 "dates":    945,
"data":   1215 
},
{
 "dates":    946,
"data": 1296.2 
},
{
 "dates":    947,
"data": 1297.8 
},
{
 "dates":    948,
"data": 1293.5 
},
{
 "dates":    949,
"data": 1257.9 
},
{
 "dates":    950,
"data": 1265.5 
},
{
 "dates":    951,
"data": 1342.1 
},
{
 "dates":    952,
"data": 1279.5 
},
{
 "dates":    953,
"data": 1241.7 
},
{
 "dates":    954,
"data": 1301.1 
},
{
 "dates":    955,
"data": 1202.3 
},
{
 "dates":    956,
"data": 1294.2 
},
{
 "dates":    957,
"data": 1231.3 
},
{
 "dates":    958,
"data": 1285.2 
},
{
 "dates":    959,
"data": 1246.5 
},
{
 "dates":    960,
"data": 1307.6 
},
{
 "dates":    961,
"data": 1362.4 
},
{
 "dates":    962,
"data":   1275 
},
{
 "dates":    963,
"data": 1248.7 
},
{
 "dates":    964,
"data": 1184.6 
},
{
 "dates":    965,
"data": 1319.9 
},
{
 "dates":    966,
"data": 1165.8 
},
{
 "dates":    967,
"data": 1264.7 
},
{
 "dates":    968,
"data":   1253 
},
{
 "dates":    969,
"data": 1294.3 
},
{
 "dates":    970,
"data": 1216.6 
},
{
 "dates":    971,
"data": 1269.8 
},
{
 "dates":    972,
"data": 1214.2 
},
{
 "dates":    973,
"data": 1313.1 
},
{
 "dates":    974,
"data": 1241.7 
},
{
 "dates":    975,
"data": 1235.6 
},
{
 "dates":    976,
"data": 1236.2 
},
{
 "dates":    977,
"data": 1227.1 
},
{
 "dates":    978,
"data": 1209.7 
},
{
 "dates":    979,
"data": 1314.3 
},
{
 "dates":    980,
"data": 1258.3 
},
{
 "dates":    981,
"data":   1214 
},
{
 "dates":    982,
"data": 1215.3 
},
{
 "dates":    983,
"data":   1287 
},
{
 "dates":    984,
"data": 1232.4 
},
{
 "dates":    985,
"data": 1212.1 
},
{
 "dates":    986,
"data": 1264.5 
},
{
 "dates":    987,
"data":   1256 
},
{
 "dates":    988,
"data": 1211.5 
},
{
 "dates":    989,
"data": 1311.8 
},
{
 "dates":    990,
"data": 1245.1 
},
{
 "dates":    991,
"data": 1275.4 
},
{
 "dates":    992,
"data": 1218.1 
},
{
 "dates":    993,
"data":   1178 
},
{
 "dates":    994,
"data": 1258.9 
},
{
 "dates":    995,
"data": 1204.2 
},
{
 "dates":    996,
"data": 1242.6 
},
{
 "dates":    997,
"data": 1202.7 
},
{
 "dates":    998,
"data": 1215.7 
},
{
 "dates":    999,
"data": 1213.3 
},
{
 "dates":   1000,
"data": 1272.3 
},
{
 "dates":   1001,
"data": 1232.5 
},
{
 "dates":   1002,
"data": 1277.3 
},
{
 "dates":   1003,
"data": 1227.5 
},
{
 "dates":   1004,
"data": 1242.5 
},
{
 "dates":   1005,
"data": 1303.2 
},
{
 "dates":   1006,
"data": 1281.2 
},
{
 "dates":   1007,
"data": 1278.4 
},
{
 "dates":   1008,
"data": 1289.7 
},
{
 "dates":   1009,
"data": 1228.6 
},
{
 "dates":   1010,
"data": 1295.8 
},
{
 "dates":   1011,
"data": 1259.4 
},
{
 "dates":   1012,
"data": 1239.5 
},
{
 "dates":   1013,
"data": 1235.4 
},
{
 "dates":   1014,
"data": 1232.3 
},
{
 "dates":   1015,
"data": 1295.8 
},
{
 "dates":   1016,
"data": 1275.6 
},
{
 "dates":   1017,
"data": 1340.5 
},
{
 "dates":   1018,
"data": 1263.4 
},
{
 "dates":   1019,
"data": 1276.3 
},
{
 "dates":   1020,
"data": 1212.9 
},
{
 "dates":   1021,
"data": 1282.4 
},
{
 "dates":   1022,
"data": 1246.4 
},
{
 "dates":   1023,
"data": 1336.5 
},
{
 "dates":   1024,
"data": 1214.2 
},
{
 "dates":   1025,
"data": 1232.7 
},
{
 "dates":   1026,
"data": 1226.8 
},
{
 "dates":   1027,
"data":   1230 
},
{
 "dates":   1028,
"data": 1256.3 
},
{
 "dates":   1029,
"data": 1235.4 
},
{
 "dates":   1030,
"data": 1251.6 
},
{
 "dates":   1031,
"data": 1211.1 
},
{
 "dates":   1032,
"data": 1215.2 
},
{
 "dates":   1033,
"data": 1269.7 
},
{
 "dates":   1034,
"data": 1274.4 
},
{
 "dates":   1035,
"data":   1234 
},
{
 "dates":   1036,
"data": 1254.8 
},
{
 "dates":   1037,
"data": 1278.4 
},
{
 "dates":   1038,
"data": 1288.8 
},
{
 "dates":   1039,
"data":   1259 
},
{
 "dates":   1040,
"data": 1255.3 
},
{
 "dates":   1041,
"data": 1266.9 
},
{
 "dates":   1042,
"data": 1279.9 
},
{
 "dates":   1043,
"data": 1301.2 
},
{
 "dates":   1044,
"data": 1277.4 
},
{
 "dates":   1045,
"data": 1376.9 
},
{
 "dates":   1046,
"data": 1300.3 
},
{
 "dates":   1047,
"data": 1306.7 
},
{
 "dates":   1048,
"data": 1288.7 
},
{
 "dates":   1049,
"data": 1302.3 
},
{
 "dates":   1050,
"data": 1326.7 
},
{
 "dates":   1051,
"data": 1333.3 
},
{
 "dates":   1052,
"data": 1280.6 
},
{
 "dates":   1053,
"data": 1246.9 
},
{
 "dates":   1054,
"data": 1370.1 
},
{
 "dates":   1055,
"data":   1320 
},
{
 "dates":   1056,
"data": 1327.7 
},
{
 "dates":   1057,
"data": 1343.3 
},
{
 "dates":   1058,
"data": 1317.9 
},
{
 "dates":   1059,
"data": 1327.7 
},
{
 "dates":   1060,
"data": 1309.8 
},
{
 "dates":   1061,
"data":   1310 
},
{
 "dates":   1062,
"data": 1276.2 
},
{
 "dates":   1063,
"data": 1277.3 
},
{
 "dates":   1064,
"data":   1359 
},
{
 "dates":   1065,
"data": 1319.3 
},
{
 "dates":   1066,
"data": 1263.7 
},
{
 "dates":   1067,
"data": 1321.7 
},
{
 "dates":   1068,
"data": 1299.9 
},
{
 "dates":   1069,
"data": 1352.6 
},
{
 "dates":   1070,
"data":   1309 
},
{
 "dates":   1071,
"data": 1345.3 
},
{
 "dates":   1072,
"data": 1364.9 
},
{
 "dates":   1073,
"data":   1327 
},
{
 "dates":   1074,
"data": 1339.3 
},
{
 "dates":   1075,
"data": 1350.1 
},
{
 "dates":   1076,
"data": 1263.2 
},
{
 "dates":   1077,
"data": 1320.9 
},
{
 "dates":   1078,
"data": 1307.6 
},
{
 "dates":   1079,
"data": 1378.3 
},
{
 "dates":   1080,
"data": 1340.4 
},
{
 "dates":   1081,
"data": 1404.8 
},
{
 "dates":   1082,
"data": 1297.6 
},
{
 "dates":   1083,
"data": 1408.8 
},
{
 "dates":   1084,
"data":   1368 
},
{
 "dates":   1085,
"data": 1319.7 
},
{
 "dates":   1086,
"data": 1336.2 
},
{
 "dates":   1087,
"data": 1394.1 
},
{
 "dates":   1088,
"data": 1346.1 
},
{
 "dates":   1089,
"data":   1300 
},
{
 "dates":   1090,
"data": 1313.4 
},
{
 "dates":   1091,
"data": 1319.9 
},
{
 "dates":   1092,
"data": 1376.5 
},
{
 "dates":   1093,
"data": 1374.7 
},
{
 "dates":   1094,
"data": 1374.1 
},
{
 "dates":   1095,
"data": 1383.5 
},
{
 "dates":   1096,
"data": 1310.4 
},
{
 "dates":   1097,
"data": 1435.3 
},
{
 "dates":   1098,
"data": 1331.9 
},
{
 "dates":   1099,
"data": 1367.9 
},
{
 "dates":   1100,
"data":   1368 
},
{
 "dates":   1101,
"data": 1395.1 
},
{
 "dates":   1102,
"data":   1400 
},
{
 "dates":   1103,
"data": 1400.8 
},
{
 "dates":   1104,
"data": 1374.5 
},
{
 "dates":   1105,
"data": 1369.1 
},
{
 "dates":   1106,
"data": 1396.1 
},
{
 "dates":   1107,
"data": 1333.3 
},
{
 "dates":   1108,
"data": 1446.8 
},
{
 "dates":   1109,
"data": 1485.6 
},
{
 "dates":   1110,
"data": 1419.6 
},
{
 "dates":   1111,
"data": 1457.4 
},
{
 "dates":   1112,
"data": 1427.2 
},
{
 "dates":   1113,
"data": 1437.3 
},
{
 "dates":   1114,
"data": 1365.8 
},
{
 "dates":   1115,
"data": 1443.8 
},
{
 "dates":   1116,
"data": 1360.1 
},
{
 "dates":   1117,
"data": 1491.6 
},
{
 "dates":   1118,
"data":   1424 
},
{
 "dates":   1119,
"data":   1398 
},
{
 "dates":   1120,
"data": 1329.1 
},
{
 "dates":   1121,
"data": 1402.7 
},
{
 "dates":   1122,
"data": 1453.7 
},
{
 "dates":   1123,
"data": 1491.4 
},
{
 "dates":   1124,
"data": 1512.6 
},
{
 "dates":   1125,
"data": 1480.5 
},
{
 "dates":   1126,
"data": 1445.5 
},
{
 "dates":   1127,
"data": 1428.1 
},
{
 "dates":   1128,
"data": 1404.5 
},
{
 "dates":   1129,
"data": 1454.2 
},
{
 "dates":   1130,
"data": 1392.1 
},
{
 "dates":   1131,
"data":   1502 
},
{
 "dates":   1132,
"data": 1418.1 
},
{
 "dates":   1133,
"data": 1425.3 
},
{
 "dates":   1134,
"data": 1430.2 
},
{
 "dates":   1135,
"data": 1425.8 
},
{
 "dates":   1136,
"data": 1407.1 
},
{
 "dates":   1137,
"data": 1483.2 
},
{
 "dates":   1138,
"data": 1459.3 
},
{
 "dates":   1139,
"data": 1381.6 
},
{
 "dates":   1140,
"data": 1458.2 
},
{
 "dates":   1141,
"data": 1449.7 
},
{
 "dates":   1142,
"data": 1537.8 
},
{
 "dates":   1143,
"data": 1457.3 
},
{
 "dates":   1144,
"data": 1517.4 
},
{
 "dates":   1145,
"data": 1487.5 
},
{
 "dates":   1146,
"data": 1488.5 
},
{
 "dates":   1147,
"data": 1405.6 
},
{
 "dates":   1148,
"data": 1445.1 
},
{
 "dates":   1149,
"data": 1480.5 
},
{
 "dates":   1150,
"data": 1462.9 
},
{
 "dates":   1151,
"data": 1525.7 
},
{
 "dates":   1152,
"data": 1440.3 
},
{
 "dates":   1153,
"data": 1434.7 
},
{
 "dates":   1154,
"data": 1447.2 
},
{
 "dates":   1155,
"data": 1539.5 
},
{
 "dates":   1156,
"data": 1435.8 
},
{
 "dates":   1157,
"data": 1473.4 
},
{
 "dates":   1158,
"data": 1418.1 
},
{
 "dates":   1159,
"data": 1468.8 
},
{
 "dates":   1160,
"data": 1414.2 
},
{
 "dates":   1161,
"data": 1434.1 
},
{
 "dates":   1162,
"data":   1383 
},
{
 "dates":   1163,
"data": 1498.1 
},
{
 "dates":   1164,
"data": 1549.4 
},
{
 "dates":   1165,
"data": 1485.6 
},
{
 "dates":   1166,
"data": 1493.7 
},
{
 "dates":   1167,
"data": 1549.9 
},
{
 "dates":   1168,
"data": 1498.2 
},
{
 "dates":   1169,
"data":   1564 
},
{
 "dates":   1170,
"data": 1461.3 
},
{
 "dates":   1171,
"data": 1533.6 
},
{
 "dates":   1172,
"data": 1449.5 
},
{
 "dates":   1173,
"data": 1546.3 
},
{
 "dates":   1174,
"data": 1500.4 
},
{
 "dates":   1175,
"data": 1486.6 
},
{
 "dates":   1176,
"data": 1478.1 
},
{
 "dates":   1177,
"data": 1551.1 
},
{
 "dates":   1178,
"data": 1451.6 
},
{
 "dates":   1179,
"data": 1511.4 
},
{
 "dates":   1180,
"data": 1425.2 
},
{
 "dates":   1181,
"data": 1506.6 
},
{
 "dates":   1182,
"data": 1486.8 
},
{
 "dates":   1183,
"data": 1512.6 
},
{
 "dates":   1184,
"data":   1476 
},
{
 "dates":   1185,
"data":   1578 
},
{
 "dates":   1186,
"data": 1474.5 
},
{
 "dates":   1187,
"data": 1614.7 
},
{
 "dates":   1188,
"data": 1445.8 
},
{
 "dates":   1189,
"data": 1539.5 
},
{
 "dates":   1190,
"data": 1520.9 
},
{
 "dates":   1191,
"data": 1520.6 
},
{
 "dates":   1192,
"data": 1505.4 
},
{
 "dates":   1193,
"data": 1550.5 
},
{
 "dates":   1194,
"data": 1421.2 
},
{
 "dates":   1195,
"data": 1484.7 
},
{
 "dates":   1196,
"data": 1623.7 
},
{
 "dates":   1197,
"data": 1607.2 
},
{
 "dates":   1198,
"data": 1525.6 
},
{
 "dates":   1199,
"data": 1563.9 
},
{
 "dates":   1200,
"data": 1515.4 
},
{
 "dates":   1201,
"data": 1427.1 
},
{
 "dates":   1202,
"data": 1509.6 
},
{
 "dates":   1203,
"data":   1505 
},
{
 "dates":   1204,
"data": 1565.1 
},
{
 "dates":   1205,
"data": 1442.7 
},
{
 "dates":   1206,
"data": 1557.9 
},
{
 "dates":   1207,
"data": 1481.8 
},
{
 "dates":   1208,
"data": 1556.8 
},
{
 "dates":   1209,
"data":   1544 
},
{
 "dates":   1210,
"data": 1499.6 
},
{
 "dates":   1211,
"data": 1587.4 
},
{
 "dates":   1212,
"data": 1478.8 
},
{
 "dates":   1213,
"data": 1509.6 
},
{
 "dates":   1214,
"data": 1458.6 
},
{
 "dates":   1215,
"data": 1481.5 
},
{
 "dates":   1216,
"data": 1521.2 
},
{
 "dates":   1217,
"data": 1523.6 
},
{
 "dates":   1218,
"data": 1441.5 
},
{
 "dates":   1219,
"data": 1588.2 
},
{
 "dates":   1220,
"data": 1545.8 
},
{
 "dates":   1221,
"data": 1509.1 
},
{
 "dates":   1222,
"data": 1551.3 
},
{
 "dates":   1223,
"data": 1391.7 
},
{
 "dates":   1224,
"data": 1505.3 
},
{
 "dates":   1225,
"data":   1509 
},
{
 "dates":   1226,
"data": 1495.8 
},
{
 "dates":   1227,
"data": 1470.7 
},
{
 "dates":   1228,
"data": 1496.5 
},
{
 "dates":   1229,
"data": 1541.6 
},
{
 "dates":   1230,
"data": 1554.4 
},
{
 "dates":   1231,
"data": 1526.2 
},
{
 "dates":   1232,
"data": 1546.7 
},
{
 "dates":   1233,
"data": 1457.1 
},
{
 "dates":   1234,
"data":   1451 
},
{
 "dates":   1235,
"data": 1414.4 
},
{
 "dates":   1236,
"data": 1458.9 
},
{
 "dates":   1237,
"data": 1386.3 
},
{
 "dates":   1238,
"data": 1441.9 
},
{
 "dates":   1239,
"data":   1557 
},
{
 "dates":   1240,
"data": 1422.2 
},
{
 "dates":   1241,
"data": 1500.1 
},
{
 "dates":   1242,
"data": 1479.1 
},
{
 "dates":   1243,
"data": 1463.8 
},
{
 "dates":   1244,
"data": 1544.9 
},
{
 "dates":   1245,
"data": 1518.2 
},
{
 "dates":   1246,
"data": 1458.1 
},
{
 "dates":   1247,
"data": 1557.8 
},
{
 "dates":   1248,
"data": 1437.8 
},
{
 "dates":   1249,
"data": 1487.3 
},
{
 "dates":   1250,
"data": 1520.4 
},
{
 "dates":   1251,
"data": 1487.1 
},
{
 "dates":   1252,
"data":   1491 
},
{
 "dates":   1253,
"data": 1430.8 
},
{
 "dates":   1254,
"data": 1498.1 
},
{
 "dates":   1255,
"data": 1467.3 
},
{
 "dates":   1256,
"data": 1466.1 
},
{
 "dates":   1257,
"data":   1518 
},
{
 "dates":   1258,
"data": 1465.2 
},
{
 "dates":   1259,
"data":   1489 
},
{
 "dates":   1260,
"data": 1391.7 
},
{
 "dates":   1261,
"data": 1462.4 
},
{
 "dates":   1262,
"data": 1490.4 
},
{
 "dates":   1263,
"data": 1445.1 
},
{
 "dates":   1264,
"data": 1461.5 
},
{
 "dates":   1265,
"data": 1482.2 
},
{
 "dates":   1266,
"data": 1446.6 
},
{
 "dates":   1267,
"data": 1445.6 
},
{
 "dates":   1268,
"data": 1445.6 
},
{
 "dates":   1269,
"data": 1469.8 
},
{
 "dates":   1270,
"data": 1421.7 
},
{
 "dates":   1271,
"data": 1433.9 
},
{
 "dates":   1272,
"data": 1511.7 
},
{
 "dates":   1273,
"data": 1500.6 
},
{
 "dates":   1274,
"data": 1415.6 
},
{
 "dates":   1275,
"data": 1435.4 
},
{
 "dates":   1276,
"data": 1421.1 
},
{
 "dates":   1277,
"data": 1489.8 
},
{
 "dates":   1278,
"data": 1451.4 
},
{
 "dates":   1279,
"data":   1390 
},
{
 "dates":   1280,
"data": 1424.2 
},
{
 "dates":   1281,
"data": 1491.4 
},
{
 "dates":   1282,
"data": 1453.1 
},
{
 "dates":   1283,
"data": 1412.2 
},
{
 "dates":   1284,
"data": 1491.7 
},
{
 "dates":   1285,
"data":   1421 
},
{
 "dates":   1286,
"data": 1473.2 
},
{
 "dates":   1287,
"data": 1458.8 
},
{
 "dates":   1288,
"data": 1384.1 
},
{
 "dates":   1289,
"data": 1511.5 
},
{
 "dates":   1290,
"data": 1423.7 
},
{
 "dates":   1291,
"data": 1432.3 
},
{
 "dates":   1292,
"data": 1367.8 
},
{
 "dates":   1293,
"data": 1379.4 
},
{
 "dates":   1294,
"data": 1388.3 
},
{
 "dates":   1295,
"data": 1389.1 
},
{
 "dates":   1296,
"data": 1428.5 
},
{
 "dates":   1297,
"data": 1404.8 
},
{
 "dates":   1298,
"data": 1467.4 
},
{
 "dates":   1299,
"data": 1438.7 
},
{
 "dates":   1300,
"data": 1370.6 
},
{
 "dates":   1301,
"data":   1432 
},
{
 "dates":   1302,
"data": 1417.9 
},
{
 "dates":   1303,
"data": 1411.4 
},
{
 "dates":   1304,
"data": 1492.7 
},
{
 "dates":   1305,
"data": 1455.6 
},
{
 "dates":   1306,
"data": 1393.5 
},
{
 "dates":   1307,
"data": 1444.1 
},
{
 "dates":   1308,
"data": 1372.2 
},
{
 "dates":   1309,
"data": 1439.2 
},
{
 "dates":   1310,
"data": 1418.4 
},
{
 "dates":   1311,
"data": 1463.3 
},
{
 "dates":   1312,
"data": 1399.5 
},
{
 "dates":   1313,
"data": 1442.8 
},
{
 "dates":   1314,
"data": 1366.8 
},
{
 "dates":   1315,
"data": 1385.7 
},
{
 "dates":   1316,
"data": 1343.4 
},
{
 "dates":   1317,
"data": 1378.1 
},
{
 "dates":   1318,
"data": 1335.3 
},
{
 "dates":   1319,
"data":   1341 
},
{
 "dates":   1320,
"data": 1425.5 
},
{
 "dates":   1321,
"data": 1287.6 
},
{
 "dates":   1322,
"data": 1275.8 
},
{
 "dates":   1323,
"data": 1374.9 
},
{
 "dates":   1324,
"data": 1363.9 
},
{
 "dates":   1325,
"data": 1432.2 
},
{
 "dates":   1326,
"data": 1400.3 
},
{
 "dates":   1327,
"data": 1320.9 
},
{
 "dates":   1328,
"data": 1431.1 
},
{
 "dates":   1329,
"data": 1452.2 
},
{
 "dates":   1330,
"data": 1332.8 
},
{
 "dates":   1331,
"data": 1413.5 
},
{
 "dates":   1332,
"data": 1370.6 
},
{
 "dates":   1333,
"data": 1399.6 
},
{
 "dates":   1334,
"data": 1374.8 
},
{
 "dates":   1335,
"data":   1355 
},
{
 "dates":   1336,
"data": 1399.1 
},
{
 "dates":   1337,
"data": 1420.2 
},
{
 "dates":   1338,
"data": 1414.2 
},
{
 "dates":   1339,
"data": 1419.8 
},
{
 "dates":   1340,
"data": 1418.9 
},
{
 "dates":   1341,
"data": 1396.9 
},
{
 "dates":   1342,
"data": 1400.7 
},
{
 "dates":   1343,
"data": 1369.4 
},
{
 "dates":   1344,
"data": 1408.2 
},
{
 "dates":   1345,
"data": 1409.2 
},
{
 "dates":   1346,
"data": 1417.4 
},
{
 "dates":   1347,
"data": 1446.5 
},
{
 "dates":   1348,
"data": 1270.9 
},
{
 "dates":   1349,
"data": 1452.2 
},
{
 "dates":   1350,
"data": 1365.7 
},
{
 "dates":   1351,
"data": 1359.5 
},
{
 "dates":   1352,
"data": 1346.6 
},
{
 "dates":   1353,
"data": 1322.6 
},
{
 "dates":   1354,
"data": 1388.8 
},
{
 "dates":   1355,
"data": 1371.9 
},
{
 "dates":   1356,
"data": 1408.8 
},
{
 "dates":   1357,
"data": 1284.7 
},
{
 "dates":   1358,
"data": 1394.3 
},
{
 "dates":   1359,
"data": 1309.8 
},
{
 "dates":   1360,
"data": 1326.1 
},
{
 "dates":   1361,
"data": 1383.5 
},
{
 "dates":   1362,
"data": 1350.4 
},
{
 "dates":   1363,
"data": 1435.9 
},
{
 "dates":   1364,
"data": 1412.3 
},
{
 "dates":   1365,
"data": 1402.2 
},
{
 "dates":   1366,
"data": 1272.1 
},
{
 "dates":   1367,
"data": 1349.9 
},
{
 "dates":   1368,
"data": 1419.2 
},
{
 "dates":   1369,
"data": 1362.4 
},
{
 "dates":   1370,
"data": 1406.5 
},
{
 "dates":   1371,
"data": 1346.2 
},
{
 "dates":   1372,
"data": 1367.8 
},
{
 "dates":   1373,
"data": 1317.8 
},
{
 "dates":   1374,
"data": 1409.5 
},
{
 "dates":   1375,
"data": 1300.1 
},
{
 "dates":   1376,
"data": 1423.6 
},
{
 "dates":   1377,
"data": 1393.9 
},
{
 "dates":   1378,
"data": 1367.7 
},
{
 "dates":   1379,
"data": 1366.6 
},
{
 "dates":   1380,
"data": 1335.9 
},
{
 "dates":   1381,
"data": 1368.8 
},
{
 "dates":   1382,
"data": 1403.6 
},
{
 "dates":   1383,
"data": 1412.8 
},
{
 "dates":   1384,
"data": 1305.4 
},
{
 "dates":   1385,
"data": 1348.3 
},
{
 "dates":   1386,
"data": 1333.9 
},
{
 "dates":   1387,
"data": 1300.8 
},
{
 "dates":   1388,
"data": 1405.4 
},
{
 "dates":   1389,
"data": 1311.7 
},
{
 "dates":   1390,
"data": 1451.5 
},
{
 "dates":   1391,
"data": 1378.6 
},
{
 "dates":   1392,
"data": 1420.9 
},
{
 "dates":   1393,
"data": 1411.7 
},
{
 "dates":   1394,
"data": 1396.6 
},
{
 "dates":   1395,
"data": 1364.2 
},
{
 "dates":   1396,
"data": 1419.1 
},
{
 "dates":   1397,
"data":   1382 
},
{
 "dates":   1398,
"data": 1412.5 
},
{
 "dates":   1399,
"data": 1418.8 
},
{
 "dates":   1400,
"data": 1364.4 
},
{
 "dates":   1401,
"data": 1414.2 
},
{
 "dates":   1402,
"data": 1465.3 
},
{
 "dates":   1403,
"data": 1426.4 
},
{
 "dates":   1404,
"data": 1415.3 
},
{
 "dates":   1405,
"data": 1437.5 
},
{
 "dates":   1406,
"data": 1395.5 
},
{
 "dates":   1407,
"data":   1322 
},
{
 "dates":   1408,
"data": 1392.1 
},
{
 "dates":   1409,
"data":   1381 
},
{
 "dates":   1410,
"data": 1344.2 
},
{
 "dates":   1411,
"data": 1435.1 
},
{
 "dates":   1412,
"data": 1337.1 
},
{
 "dates":   1413,
"data": 1346.1 
},
{
 "dates":   1414,
"data": 1348.3 
},
{
 "dates":   1415,
"data": 1428.5 
},
{
 "dates":   1416,
"data":   1389 
},
{
 "dates":   1417,
"data": 1423.9 
},
{
 "dates":   1418,
"data": 1377.8 
},
{
 "dates":   1419,
"data":   1395 
},
{
 "dates":   1420,
"data": 1425.3 
},
{
 "dates":   1421,
"data": 1450.5 
},
{
 "dates":   1422,
"data": 1436.3 
},
{
 "dates":   1423,
"data": 1384.4 
},
{
 "dates":   1424,
"data": 1462.6 
},
{
 "dates":   1425,
"data": 1433.1 
},
{
 "dates":   1426,
"data": 1412.7 
},
{
 "dates":   1427,
"data": 1439.2 
},
{
 "dates":   1428,
"data": 1479.7 
},
{
 "dates":   1429,
"data": 1446.2 
},
{
 "dates":   1430,
"data": 1518.8 
},
{
 "dates":   1431,
"data": 1410.2 
},
{
 "dates":   1432,
"data": 1467.1 
},
{
 "dates":   1433,
"data": 1409.1 
},
{
 "dates":   1434,
"data": 1516.8 
},
{
 "dates":   1435,
"data":   1524 
},
{
 "dates":   1436,
"data": 1455.4 
},
{
 "dates":   1437,
"data": 1440.6 
},
{
 "dates":   1438,
"data":   1484 
},
{
 "dates":   1439,
"data": 1450.4 
},
{
 "dates":   1440,
"data":   1488 
},
{
 "dates":   1441,
"data": 1418.5 
},
{
 "dates":   1442,
"data": 1446.3 
},
{
 "dates":   1443,
"data": 1422.4 
},
{
 "dates":   1444,
"data": 1456.8 
},
{
 "dates":   1445,
"data": 1486.5 
},
{
 "dates":   1446,
"data": 1488.8 
},
{
 "dates":   1447,
"data": 1484.5 
},
{
 "dates":   1448,
"data": 1486.1 
},
{
 "dates":   1449,
"data": 1453.1 
},
{
 "dates":   1450,
"data": 1529.3 
},
{
 "dates":   1451,
"data": 1507.6 
},
{
 "dates":   1452,
"data": 1484.6 
},
{
 "dates":   1453,
"data": 1511.6 
},
{
 "dates":   1454,
"data": 1448.8 
},
{
 "dates":   1455,
"data": 1455.3 
},
{
 "dates":   1456,
"data": 1481.9 
},
{
 "dates":   1457,
"data": 1470.2 
},
{
 "dates":   1458,
"data": 1530.4 
},
{
 "dates":   1459,
"data": 1505.8 
},
{
 "dates":   1460,
"data": 1523.2 
},
{
 "dates":   1461,
"data": 1464.8 
} 
]
  
      var data = d3.nest()
        .key(function(d){
          return opts.group === undefined ? 'main' : d[opts.group]
        })
        .entries(data)
      
      nv.addGraph(function() {
        var chart = nv.models[opts.type]()
          .x(function(d) { return d[opts.x] })
          .y(function(d) { return d[opts.y] })
          .width(opts.width)
          .height(opts.height)
         
        
          
        

        
        
        
      
       d3.select("#" + opts.id)
        .append('svg')
        .datum(data)
        .transition().duration(500)
        .call(chart);

       nv.utils.windowResize(chart.update);
       return chart;
      });
    };
</script>


1.  A linear or slow exponential upward growth.
2.  A cyclic component
  *  Given that the cycle appears to start at the beginning of the year, it might have a sin component.
  
Let's take a look at the first difference (stationary form) of the data.





<div id='dataDiff' class='rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawdataDiff()
    });
    function drawdataDiff(){  
      var opts = {
 "dom": "dataDiff",
"width":    800,
"height":    400,
"x": "dates",
"y": "data",
"type": "lineChart",
"id": "dataDiff" 
},
        data = [
 {
 "dates":      2,
"data": 12.024 
},
{
 "dates":      3,
"data": -11.273 
},
{
 "dates":      4,
"data": 49.971 
},
{
 "dates":      5,
"data": 0.13879 
},
{
 "dates":      6,
"data": -49.506 
},
{
 "dates":      7,
"data": 29.981 
},
{
 "dates":      8,
"data": -40.75 
},
{
 "dates":      9,
"data": 21.388 
},
{
 "dates":     10,
"data": 2.7674 
},
{
 "dates":     11,
"data": 56.393 
},
{
 "dates":     12,
"data": -46.349 
},
{
 "dates":     13,
"data": 31.946 
},
{
 "dates":     14,
"data": 35.237 
},
{
 "dates":     15,
"data": -11.782 
},
{
 "dates":     16,
"data": 35.827 
},
{
 "dates":     17,
"data": -77.857 
},
{
 "dates":     18,
"data": 22.291 
},
{
 "dates":     19,
"data": -26.623 
},
{
 "dates":     20,
"data": 35.528 
},
{
 "dates":     21,
"data": -33.244 
},
{
 "dates":     22,
"data": 26.725 
},
{
 "dates":     23,
"data": 1.3423 
},
{
 "dates":     24,
"data": 62.677 
},
{
 "dates":     25,
"data": -69.965 
},
{
 "dates":     26,
"data": 23.775 
},
{
 "dates":     27,
"data": 12.296 
},
{
 "dates":     28,
"data": -25.691 
},
{
 "dates":     29,
"data": -2.9004 
},
{
 "dates":     30,
"data": 58.996 
},
{
 "dates":     31,
"data": -12.122 
},
{
 "dates":     32,
"data": 21.032 
},
{
 "dates":     33,
"data": -38.21 
},
{
 "dates":     34,
"data": 36.861 
},
{
 "dates":     35,
"data": -1.0938 
},
{
 "dates":     36,
"data": -25.402 
},
{
 "dates":     37,
"data": 37.277 
},
{
 "dates":     38,
"data": -34.394 
},
{
 "dates":     39,
"data": 0.67007 
},
{
 "dates":     40,
"data": -68.819 
},
{
 "dates":     41,
"data": 108.26 
},
{
 "dates":     42,
"data": -58.492 
},
{
 "dates":     43,
"data": 32.659 
},
{
 "dates":     44,
"data": -63.116 
},
{
 "dates":     45,
"data":  19.75 
},
{
 "dates":     46,
"data": 56.238 
},
{
 "dates":     47,
"data": -0.90547 
},
{
 "dates":     48,
"data": -26.271 
},
{
 "dates":     49,
"data": 72.929 
},
{
 "dates":     50,
"data": -79.97 
},
{
 "dates":     51,
"data": -2.9217 
},
{
 "dates":     52,
"data": 20.813 
},
{
 "dates":     53,
"data": -12.611 
},
{
 "dates":     54,
"data": -14.98 
},
{
 "dates":     55,
"data": 27.775 
},
{
 "dates":     56,
"data": -19.867 
},
{
 "dates":     57,
"data": 33.129 
},
{
 "dates":     58,
"data": -62.963 
},
{
 "dates":     59,
"data": 52.045 
},
{
 "dates":     60,
"data": -3.4293 
},
{
 "dates":     61,
"data": 38.678 
},
{
 "dates":     62,
"data": -32.559 
},
{
 "dates":     63,
"data": 19.833 
},
{
 "dates":     64,
"data": -43.17 
},
{
 "dates":     65,
"data": -13.308 
},
{
 "dates":     66,
"data": 91.085 
},
{
 "dates":     67,
"data": -79.229 
},
{
 "dates":     68,
"data": 60.975 
},
{
 "dates":     69,
"data": -48.995 
},
{
 "dates":     70,
"data": 96.014 
},
{
 "dates":     71,
"data": -20.089 
},
{
 "dates":     72,
"data": -35.861 
},
{
 "dates":     73,
"data": 12.056 
},
{
 "dates":     74,
"data": -5.9099 
},
{
 "dates":     75,
"data": -25.02 
},
{
 "dates":     76,
"data": 66.913 
},
{
 "dates":     77,
"data":  -90.8 
},
{
 "dates":     78,
"data": 60.374 
},
{
 "dates":     79,
"data": 23.445 
},
{
 "dates":     80,
"data": -45.463 
},
{
 "dates":     81,
"data":  30.19 
},
{
 "dates":     82,
"data": -56.483 
},
{
 "dates":     83,
"data": 53.415 
},
{
 "dates":     84,
"data": 14.118 
},
{
 "dates":     85,
"data": -44.746 
},
{
 "dates":     86,
"data":  33.24 
},
{
 "dates":     87,
"data": 82.107 
},
{
 "dates":     88,
"data": -116.37 
},
{
 "dates":     89,
"data": -27.548 
},
{
 "dates":     90,
"data": 20.173 
},
{
 "dates":     91,
"data": -10.466 
},
{
 "dates":     92,
"data": 57.002 
},
{
 "dates":     93,
"data": -10.787 
},
{
 "dates":     94,
"data": -41.935 
},
{
 "dates":     95,
"data": -5.156 
},
{
 "dates":     96,
"data":  11.65 
},
{
 "dates":     97,
"data": -18.066 
},
{
 "dates":     98,
"data": 72.568 
},
{
 "dates":     99,
"data": -71.71 
},
{
 "dates":    100,
"data": 69.224 
},
{
 "dates":    101,
"data": 0.99141 
},
{
 "dates":    102,
"data": -35.325 
},
{
 "dates":    103,
"data": -40.556 
},
{
 "dates":    104,
"data": -12.842 
},
{
 "dates":    105,
"data": 126.82 
},
{
 "dates":    106,
"data": -122.1 
},
{
 "dates":    107,
"data": 65.705 
},
{
 "dates":    108,
"data": 29.019 
},
{
 "dates":    109,
"data": 6.6364 
},
{
 "dates":    110,
"data": -30.477 
},
{
 "dates":    111,
"data": -11.734 
},
{
 "dates":    112,
"data": 11.013 
},
{
 "dates":    113,
"data": -4.7808 
},
{
 "dates":    114,
"data": 44.093 
},
{
 "dates":    115,
"data": -45.059 
},
{
 "dates":    116,
"data": 27.343 
},
{
 "dates":    117,
"data": -77.044 
},
{
 "dates":    118,
"data": 11.485 
},
{
 "dates":    119,
"data": -21.698 
},
{
 "dates":    120,
"data": 45.381 
},
{
 "dates":    121,
"data": -35.238 
},
{
 "dates":    122,
"data":   16.5 
},
{
 "dates":    123,
"data": 5.5394 
},
{
 "dates":    124,
"data": -43.211 
},
{
 "dates":    125,
"data": 53.535 
},
{
 "dates":    126,
"data": -6.1802 
},
{
 "dates":    127,
"data": 18.297 
},
{
 "dates":    128,
"data": -27.124 
},
{
 "dates":    129,
"data": -13.583 
},
{
 "dates":    130,
"data": -8.9842 
},
{
 "dates":    131,
"data": 85.773 
},
{
 "dates":    132,
"data": -61.44 
},
{
 "dates":    133,
"data": -47.33 
},
{
 "dates":    134,
"data": 30.223 
},
{
 "dates":    135,
"data": 25.671 
},
{
 "dates":    136,
"data": 7.6375 
},
{
 "dates":    137,
"data": 3.4849 
},
{
 "dates":    138,
"data": 4.0383 
},
{
 "dates":    139,
"data": -27.63 
},
{
 "dates":    140,
"data": -25.001 
},
{
 "dates":    141,
"data": 11.286 
},
{
 "dates":    142,
"data": 19.067 
},
{
 "dates":    143,
"data": 28.321 
},
{
 "dates":    144,
"data": 37.004 
},
{
 "dates":    145,
"data": -43.046 
},
{
 "dates":    146,
"data": -20.739 
},
{
 "dates":    147,
"data": 30.613 
},
{
 "dates":    148,
"data": -34.624 
},
{
 "dates":    149,
"data": -37.167 
},
{
 "dates":    150,
"data": 37.627 
},
{
 "dates":    151,
"data": -44.183 
},
{
 "dates":    152,
"data":  37.34 
},
{
 "dates":    153,
"data": -4.3577 
},
{
 "dates":    154,
"data": -20.354 
},
{
 "dates":    155,
"data": -35.251 
},
{
 "dates":    156,
"data": 113.25 
},
{
 "dates":    157,
"data": -97.789 
},
{
 "dates":    158,
"data": 61.974 
},
{
 "dates":    159,
"data": -37.782 
},
{
 "dates":    160,
"data": 43.748 
},
{
 "dates":    161,
"data": 2.7977 
},
{
 "dates":    162,
"data": -59.317 
},
{
 "dates":    163,
"data": -8.2811 
},
{
 "dates":    164,
"data": -12.644 
},
{
 "dates":    165,
"data": 60.798 
},
{
 "dates":    166,
"data": -65.68 
},
{
 "dates":    167,
"data": 12.893 
},
{
 "dates":    168,
"data": 19.719 
},
{
 "dates":    169,
"data": -54.359 
},
{
 "dates":    170,
"data": -20.499 
},
{
 "dates":    171,
"data": 81.338 
},
{
 "dates":    172,
"data": 46.344 
},
{
 "dates":    173,
"data": -22.66 
},
{
 "dates":    174,
"data": -47.339 
},
{
 "dates":    175,
"data": 9.4081 
},
{
 "dates":    176,
"data": -11.769 
},
{
 "dates":    177,
"data": -6.7046 
},
{
 "dates":    178,
"data": 0.53229 
},
{
 "dates":    179,
"data": -0.44289 
},
{
 "dates":    180,
"data":  39.41 
},
{
 "dates":    181,
"data": -7.3129 
},
{
 "dates":    182,
"data": 1.9301 
},
{
 "dates":    183,
"data": 14.669 
},
{
 "dates":    184,
"data": -33.493 
},
{
 "dates":    185,
"data": -3.698 
},
{
 "dates":    186,
"data": 37.416 
},
{
 "dates":    187,
"data": 19.612 
},
{
 "dates":    188,
"data": -54.186 
},
{
 "dates":    189,
"data":  1.527 
},
{
 "dates":    190,
"data": 23.348 
},
{
 "dates":    191,
"data": -2.6305 
},
{
 "dates":    192,
"data": -41.458 
},
{
 "dates":    193,
"data":  41.31 
},
{
 "dates":    194,
"data": -61.86 
},
{
 "dates":    195,
"data": 101.99 
},
{
 "dates":    196,
"data": -68.044 
},
{
 "dates":    197,
"data": -7.9525 
},
{
 "dates":    198,
"data": -9.1103 
},
{
 "dates":    199,
"data": 15.007 
},
{
 "dates":    200,
"data": -6.279 
},
{
 "dates":    201,
"data":    -39 
},
{
 "dates":    202,
"data": -9.0751 
},
{
 "dates":    203,
"data": 45.228 
},
{
 "dates":    204,
"data": -17.842 
},
{
 "dates":    205,
"data": 7.0588 
},
{
 "dates":    206,
"data": 38.062 
},
{
 "dates":    207,
"data": -22.673 
},
{
 "dates":    208,
"data": -44.302 
},
{
 "dates":    209,
"data": 7.5959 
},
{
 "dates":    210,
"data": -16.152 
},
{
 "dates":    211,
"data": -6.0194 
},
{
 "dates":    212,
"data": 31.198 
},
{
 "dates":    213,
"data": -31.965 
},
{
 "dates":    214,
"data": 32.432 
},
{
 "dates":    215,
"data": -36.186 
},
{
 "dates":    216,
"data": -14.081 
},
{
 "dates":    217,
"data": 29.657 
},
{
 "dates":    218,
"data": 45.827 
},
{
 "dates":    219,
"data": -3.057 
},
{
 "dates":    220,
"data": -43.846 
},
{
 "dates":    221,
"data": 45.564 
},
{
 "dates":    222,
"data": -6.1189 
},
{
 "dates":    223,
"data": -22.924 
},
{
 "dates":    224,
"data": -18.412 
},
{
 "dates":    225,
"data": -44.899 
},
{
 "dates":    226,
"data": 103.53 
},
{
 "dates":    227,
"data": -70.409 
},
{
 "dates":    228,
"data": -1.6997 
},
{
 "dates":    229,
"data": -29.096 
},
{
 "dates":    230,
"data": 40.066 
},
{
 "dates":    231,
"data": 12.544 
},
{
 "dates":    232,
"data": -24.363 
},
{
 "dates":    233,
"data": 7.8794 
},
{
 "dates":    234,
"data": -2.7146 
},
{
 "dates":    235,
"data": -54.123 
},
{
 "dates":    236,
"data": -15.513 
},
{
 "dates":    237,
"data": 55.683 
},
{
 "dates":    238,
"data":   54.8 
},
{
 "dates":    239,
"data": -3.8313 
},
{
 "dates":    240,
"data": -29.033 
},
{
 "dates":    241,
"data": 23.277 
},
{
 "dates":    242,
"data": 16.673 
},
{
 "dates":    243,
"data": -41.955 
},
{
 "dates":    244,
"data": 18.988 
},
{
 "dates":    245,
"data": 1.1602 
},
{
 "dates":    246,
"data": 4.5801 
},
{
 "dates":    247,
"data": 1.4777 
},
{
 "dates":    248,
"data": -27.214 
},
{
 "dates":    249,
"data": -14.544 
},
{
 "dates":    250,
"data": -23.613 
},
{
 "dates":    251,
"data": 28.787 
},
{
 "dates":    252,
"data": 33.452 
},
{
 "dates":    253,
"data": -40.899 
},
{
 "dates":    254,
"data": -23.611 
},
{
 "dates":    255,
"data": 0.81879 
},
{
 "dates":    256,
"data":  31.08 
},
{
 "dates":    257,
"data": -30.399 
},
{
 "dates":    258,
"data": 17.847 
},
{
 "dates":    259,
"data": 68.368 
},
{
 "dates":    260,
"data": -71.423 
},
{
 "dates":    261,
"data": -22.089 
},
{
 "dates":    262,
"data": 1.1357 
},
{
 "dates":    263,
"data":  27.93 
},
{
 "dates":    264,
"data": -28.556 
},
{
 "dates":    265,
"data": 101.89 
},
{
 "dates":    266,
"data": -28.721 
},
{
 "dates":    267,
"data": 14.784 
},
{
 "dates":    268,
"data": -58.17 
},
{
 "dates":    269,
"data": -33.427 
},
{
 "dates":    270,
"data":  58.79 
},
{
 "dates":    271,
"data": -5.4195 
},
{
 "dates":    272,
"data": 3.4815 
},
{
 "dates":    273,
"data": -26.697 
},
{
 "dates":    274,
"data": 10.371 
},
{
 "dates":    275,
"data": -2.5979 
},
{
 "dates":    276,
"data": -15.511 
},
{
 "dates":    277,
"data": 24.789 
},
{
 "dates":    278,
"data": -2.5331 
},
{
 "dates":    279,
"data": 7.1141 
},
{
 "dates":    280,
"data": -27.48 
},
{
 "dates":    281,
"data": 34.169 
},
{
 "dates":    282,
"data": -45.606 
},
{
 "dates":    283,
"data":  87.04 
},
{
 "dates":    284,
"data": -67.032 
},
{
 "dates":    285,
"data": 22.853 
},
{
 "dates":    286,
"data": 2.0628 
},
{
 "dates":    287,
"data": -3.8743 
},
{
 "dates":    288,
"data": -28.023 
},
{
 "dates":    289,
"data": 61.322 
},
{
 "dates":    290,
"data": 15.209 
},
{
 "dates":    291,
"data": -45.859 
},
{
 "dates":    292,
"data": -9.9017 
},
{
 "dates":    293,
"data": -0.64154 
},
{
 "dates":    294,
"data": 22.563 
},
{
 "dates":    295,
"data": -89.633 
},
{
 "dates":    296,
"data": 69.607 
},
{
 "dates":    297,
"data": -65.47 
},
{
 "dates":    298,
"data": 74.888 
},
{
 "dates":    299,
"data": 46.135 
},
{
 "dates":    300,
"data": -19.739 
},
{
 "dates":    301,
"data": -42.731 
},
{
 "dates":    302,
"data":  37.22 
},
{
 "dates":    303,
"data": -6.081 
},
{
 "dates":    304,
"data": -27.197 
},
{
 "dates":    305,
"data": -24.01 
},
{
 "dates":    306,
"data": 7.0671 
},
{
 "dates":    307,
"data": 81.255 
},
{
 "dates":    308,
"data": -94.892 
},
{
 "dates":    309,
"data": 68.361 
},
{
 "dates":    310,
"data": 10.681 
},
{
 "dates":    311,
"data": 32.253 
},
{
 "dates":    312,
"data": -14.283 
},
{
 "dates":    313,
"data": -38.385 
},
{
 "dates":    314,
"data": 62.479 
},
{
 "dates":    315,
"data": -46.691 
},
{
 "dates":    316,
"data":  29.29 
},
{
 "dates":    317,
"data": -64.575 
},
{
 "dates":    318,
"data": 16.671 
},
{
 "dates":    319,
"data": -17.431 
},
{
 "dates":    320,
"data": 76.769 
},
{
 "dates":    321,
"data": -40.647 
},
{
 "dates":    322,
"data":  26.63 
},
{
 "dates":    323,
"data": -4.9128 
},
{
 "dates":    324,
"data":  -72.1 
},
{
 "dates":    325,
"data":  1.339 
},
{
 "dates":    326,
"data": 96.802 
},
{
 "dates":    327,
"data": -19.863 
},
{
 "dates":    328,
"data": -32.905 
},
{
 "dates":    329,
"data": 74.378 
},
{
 "dates":    330,
"data": -59.986 
},
{
 "dates":    331,
"data": -18.593 
},
{
 "dates":    332,
"data": 0.49713 
},
{
 "dates":    333,
"data": 19.768 
},
{
 "dates":    334,
"data": 6.3177 
},
{
 "dates":    335,
"data": 28.656 
},
{
 "dates":    336,
"data": -18.154 
},
{
 "dates":    337,
"data": -36.661 
},
{
 "dates":    338,
"data": 30.964 
},
{
 "dates":    339,
"data": 54.054 
},
{
 "dates":    340,
"data": -25.378 
},
{
 "dates":    341,
"data": -30.469 
},
{
 "dates":    342,
"data": -17.455 
},
{
 "dates":    343,
"data": 82.263 
},
{
 "dates":    344,
"data": -8.0676 
},
{
 "dates":    345,
"data": -95.172 
},
{
 "dates":    346,
"data": 30.032 
},
{
 "dates":    347,
"data": 75.588 
},
{
 "dates":    348,
"data": -125.95 
},
{
 "dates":    349,
"data": 118.46 
},
{
 "dates":    350,
"data": -53.411 
},
{
 "dates":    351,
"data": -8.6036 
},
{
 "dates":    352,
"data":  27.45 
},
{
 "dates":    353,
"data": 17.092 
},
{
 "dates":    354,
"data": -51.156 
},
{
 "dates":    355,
"data": 7.9834 
},
{
 "dates":    356,
"data": -7.0539 
},
{
 "dates":    357,
"data": 61.258 
},
{
 "dates":    358,
"data": 21.832 
},
{
 "dates":    359,
"data": -12.531 
},
{
 "dates":    360,
"data": -46.485 
},
{
 "dates":    361,
"data": 46.259 
},
{
 "dates":    362,
"data": 35.757 
},
{
 "dates":    363,
"data": -37.716 
},
{
 "dates":    364,
"data": 28.844 
},
{
 "dates":    365,
"data": 45.763 
},
{
 "dates":    366,
"data": -126.12 
},
{
 "dates":    367,
"data": 50.946 
},
{
 "dates":    368,
"data": -71.167 
},
{
 "dates":    369,
"data": 35.623 
},
{
 "dates":    370,
"data":   27.2 
},
{
 "dates":    371,
"data": -57.277 
},
{
 "dates":    372,
"data": 103.45 
},
{
 "dates":    373,
"data": 9.0772 
},
{
 "dates":    374,
"data": -95.763 
},
{
 "dates":    375,
"data": 116.34 
},
{
 "dates":    376,
"data": -14.772 
},
{
 "dates":    377,
"data": -0.94682 
},
{
 "dates":    378,
"data": -45.493 
},
{
 "dates":    379,
"data": 26.033 
},
{
 "dates":    380,
"data": -51.03 
},
{
 "dates":    381,
"data":  37.81 
},
{
 "dates":    382,
"data": 54.993 
},
{
 "dates":    383,
"data": -77.251 
},
{
 "dates":    384,
"data":  34.32 
},
{
 "dates":    385,
"data": 56.889 
},
{
 "dates":    386,
"data": 5.2208 
},
{
 "dates":    387,
"data": -94.993 
},
{
 "dates":    388,
"data": 86.399 
},
{
 "dates":    389,
"data": -62.206 
},
{
 "dates":    390,
"data": 36.341 
},
{
 "dates":    391,
"data": 30.292 
},
{
 "dates":    392,
"data": 15.402 
},
{
 "dates":    393,
"data": -73.353 
},
{
 "dates":    394,
"data": 35.511 
},
{
 "dates":    395,
"data": -11.534 
},
{
 "dates":    396,
"data": 17.609 
},
{
 "dates":    397,
"data": 19.185 
},
{
 "dates":    398,
"data": -2.925 
},
{
 "dates":    399,
"data": -32.478 
},
{
 "dates":    400,
"data": 54.781 
},
{
 "dates":    401,
"data": -9.5382 
},
{
 "dates":    402,
"data": -17.943 
},
{
 "dates":    403,
"data": -41.504 
},
{
 "dates":    404,
"data": 71.369 
},
{
 "dates":    405,
"data": -124.68 
},
{
 "dates":    406,
"data":  105.7 
},
{
 "dates":    407,
"data": -33.974 
},
{
 "dates":    408,
"data": -0.92936 
},
{
 "dates":    409,
"data": 44.382 
},
{
 "dates":    410,
"data": -51.498 
},
{
 "dates":    411,
"data": 16.267 
},
{
 "dates":    412,
"data": 38.285 
},
{
 "dates":    413,
"data": -13.272 
},
{
 "dates":    414,
"data": 77.759 
},
{
 "dates":    415,
"data": -37.909 
},
{
 "dates":    416,
"data": -35.391 
},
{
 "dates":    417,
"data": 53.353 
},
{
 "dates":    418,
"data": -69.265 
},
{
 "dates":    419,
"data": 1.2193 
},
{
 "dates":    420,
"data": 93.796 
},
{
 "dates":    421,
"data": -52.963 
},
{
 "dates":    422,
"data": -8.1189 
},
{
 "dates":    423,
"data": -83.192 
},
{
 "dates":    424,
"data": 85.352 
},
{
 "dates":    425,
"data": -33.793 
},
{
 "dates":    426,
"data": -4.7872 
},
{
 "dates":    427,
"data": 32.643 
},
{
 "dates":    428,
"data": 2.6967 
},
{
 "dates":    429,
"data": 50.105 
},
{
 "dates":    430,
"data": -55.692 
},
{
 "dates":    431,
"data": 3.9848 
},
{
 "dates":    432,
"data": -40.67 
},
{
 "dates":    433,
"data": 85.616 
},
{
 "dates":    434,
"data": -40.331 
},
{
 "dates":    435,
"data": 25.031 
},
{
 "dates":    436,
"data": -23.751 
},
{
 "dates":    437,
"data": -55.666 
},
{
 "dates":    438,
"data": 86.181 
},
{
 "dates":    439,
"data": -30.954 
},
{
 "dates":    440,
"data": 16.064 
},
{
 "dates":    441,
"data": 17.301 
},
{
 "dates":    442,
"data": -0.6354 
},
{
 "dates":    443,
"data": -134.3 
},
{
 "dates":    444,
"data": 117.13 
},
{
 "dates":    445,
"data": -21.675 
},
{
 "dates":    446,
"data": 4.2723 
},
{
 "dates":    447,
"data": -10.787 
},
{
 "dates":    448,
"data": 1.9974 
},
{
 "dates":    449,
"data": -55.063 
},
{
 "dates":    450,
"data": 100.06 
},
{
 "dates":    451,
"data": 33.423 
},
{
 "dates":    452,
"data": -47.54 
},
{
 "dates":    453,
"data": -2.0169 
},
{
 "dates":    454,
"data": -27.37 
},
{
 "dates":    455,
"data": 9.0809 
},
{
 "dates":    456,
"data": 20.451 
},
{
 "dates":    457,
"data": -14.777 
},
{
 "dates":    458,
"data": 17.464 
},
{
 "dates":    459,
"data": -35.716 
},
{
 "dates":    460,
"data": -42.821 
},
{
 "dates":    461,
"data": 67.147 
},
{
 "dates":    462,
"data": -6.2185 
},
{
 "dates":    463,
"data": -1.9225 
},
{
 "dates":    464,
"data": -47.774 
},
{
 "dates":    465,
"data": 40.461 
},
{
 "dates":    466,
"data":  17.07 
},
{
 "dates":    467,
"data": -26.518 
},
{
 "dates":    468,
"data": 17.774 
},
{
 "dates":    469,
"data": 17.531 
},
{
 "dates":    470,
"data": 2.9796 
},
{
 "dates":    471,
"data": -0.97255 
},
{
 "dates":    472,
"data": -25.896 
},
{
 "dates":    473,
"data":  30.53 
},
{
 "dates":    474,
"data": 21.053 
},
{
 "dates":    475,
"data": -0.65423 
},
{
 "dates":    476,
"data": -5.9869 
},
{
 "dates":    477,
"data": -30.88 
},
{
 "dates":    478,
"data": 19.695 
},
{
 "dates":    479,
"data": 57.623 
},
{
 "dates":    480,
"data": -27.262 
},
{
 "dates":    481,
"data": -34.919 
},
{
 "dates":    482,
"data": -6.4868 
},
{
 "dates":    483,
"data": 47.993 
},
{
 "dates":    484,
"data": -32.292 
},
{
 "dates":    485,
"data": -29.937 
},
{
 "dates":    486,
"data": -26.932 
},
{
 "dates":    487,
"data": 38.007 
},
{
 "dates":    488,
"data": -13.343 
},
{
 "dates":    489,
"data": -19.968 
},
{
 "dates":    490,
"data": -45.219 
},
{
 "dates":    491,
"data": 76.658 
},
{
 "dates":    492,
"data": -33.221 
},
{
 "dates":    493,
"data": 70.376 
},
{
 "dates":    494,
"data": -73.226 
},
{
 "dates":    495,
"data": -13.745 
},
{
 "dates":    496,
"data": 41.357 
},
{
 "dates":    497,
"data": -27.37 
},
{
 "dates":    498,
"data": -13.524 
},
{
 "dates":    499,
"data": 28.878 
},
{
 "dates":    500,
"data": -56.697 
},
{
 "dates":    501,
"data": 80.149 
},
{
 "dates":    502,
"data": 22.665 
},
{
 "dates":    503,
"data": -31.309 
},
{
 "dates":    504,
"data":   60.5 
},
{
 "dates":    505,
"data": -108.97 
},
{
 "dates":    506,
"data": 56.985 
},
{
 "dates":    507,
"data": -28.389 
},
{
 "dates":    508,
"data": 9.8381 
},
{
 "dates":    509,
"data": -9.9316 
},
{
 "dates":    510,
"data": 26.832 
},
{
 "dates":    511,
"data": -23.713 
},
{
 "dates":    512,
"data": 25.342 
},
{
 "dates":    513,
"data": -70.72 
},
{
 "dates":    514,
"data": -29.575 
},
{
 "dates":    515,
"data": 32.511 
},
{
 "dates":    516,
"data": 56.495 
},
{
 "dates":    517,
"data":  41.26 
},
{
 "dates":    518,
"data": -90.993 
},
{
 "dates":    519,
"data": 120.78 
},
{
 "dates":    520,
"data": -99.056 
},
{
 "dates":    521,
"data": -9.4921 
},
{
 "dates":    522,
"data": 110.74 
},
{
 "dates":    523,
"data": -186.97 
},
{
 "dates":    524,
"data":  47.67 
},
{
 "dates":    525,
"data": -17.514 
},
{
 "dates":    526,
"data": 4.8665 
},
{
 "dates":    527,
"data": -37.175 
},
{
 "dates":    528,
"data":  122.9 
},
{
 "dates":    529,
"data": -74.52 
},
{
 "dates":    530,
"data": 28.072 
},
{
 "dates":    531,
"data": -28.504 
},
{
 "dates":    532,
"data": -16.277 
},
{
 "dates":    533,
"data": 64.206 
},
{
 "dates":    534,
"data": -42.751 
},
{
 "dates":    535,
"data": -4.3852 
},
{
 "dates":    536,
"data": -0.9004 
},
{
 "dates":    537,
"data":  90.21 
},
{
 "dates":    538,
"data": -69.461 
},
{
 "dates":    539,
"data": -16.618 
},
{
 "dates":    540,
"data": -11.692 
},
{
 "dates":    541,
"data": 57.176 
},
{
 "dates":    542,
"data": -51.11 
},
{
 "dates":    543,
"data": 21.534 
},
{
 "dates":    544,
"data": -36.704 
},
{
 "dates":    545,
"data": 65.664 
},
{
 "dates":    546,
"data": -50.738 
},
{
 "dates":    547,
"data": 34.756 
},
{
 "dates":    548,
"data": 5.1879 
},
{
 "dates":    549,
"data": 20.631 
},
{
 "dates":    550,
"data": -62.012 
},
{
 "dates":    551,
"data": 38.068 
},
{
 "dates":    552,
"data":  -29.5 
},
{
 "dates":    553,
"data": -25.118 
},
{
 "dates":    554,
"data": 70.839 
},
{
 "dates":    555,
"data": -96.001 
},
{
 "dates":    556,
"data": 16.842 
},
{
 "dates":    557,
"data": 21.599 
},
{
 "dates":    558,
"data": -5.9923 
},
{
 "dates":    559,
"data": -38.257 
},
{
 "dates":    560,
"data": 69.753 
},
{
 "dates":    561,
"data": -58.213 
},
{
 "dates":    562,
"data": 7.9733 
},
{
 "dates":    563,
"data": 18.157 
},
{
 "dates":    564,
"data":  15.12 
},
{
 "dates":    565,
"data": -18.572 
},
{
 "dates":    566,
"data": 45.238 
},
{
 "dates":    567,
"data": -51.565 
},
{
 "dates":    568,
"data":  32.07 
},
{
 "dates":    569,
"data": -77.586 
},
{
 "dates":    570,
"data": 44.709 
},
{
 "dates":    571,
"data": -45.025 
},
{
 "dates":    572,
"data":   83.5 
},
{
 "dates":    573,
"data": -1.3287 
},
{
 "dates":    574,
"data": -78.606 
},
{
 "dates":    575,
"data": 20.675 
},
{
 "dates":    576,
"data": 6.8402 
},
{
 "dates":    577,
"data": 94.755 
},
{
 "dates":    578,
"data": -86.254 
},
{
 "dates":    579,
"data": -48.042 
},
{
 "dates":    580,
"data": 53.008 
},
{
 "dates":    581,
"data": 16.773 
},
{
 "dates":    582,
"data": -6.808 
},
{
 "dates":    583,
"data": -2.6091 
},
{
 "dates":    584,
"data": -31.024 
},
{
 "dates":    585,
"data": -32.311 
},
{
 "dates":    586,
"data": 52.439 
},
{
 "dates":    587,
"data": -1.2498 
},
{
 "dates":    588,
"data": -16.874 
},
{
 "dates":    589,
"data": 40.726 
},
{
 "dates":    590,
"data": -50.219 
},
{
 "dates":    591,
"data": 40.636 
},
{
 "dates":    592,
"data": 10.077 
},
{
 "dates":    593,
"data": -39.016 
},
{
 "dates":    594,
"data":  22.24 
},
{
 "dates":    595,
"data": -15.858 
},
{
 "dates":    596,
"data": -65.481 
},
{
 "dates":    597,
"data": 32.624 
},
{
 "dates":    598,
"data": 21.279 
},
{
 "dates":    599,
"data": -22.718 
},
{
 "dates":    600,
"data": -22.472 
},
{
 "dates":    601,
"data": 109.94 
},
{
 "dates":    602,
"data": 20.096 
},
{
 "dates":    603,
"data": -118.25 
},
{
 "dates":    604,
"data":  11.79 
},
{
 "dates":    605,
"data": 46.193 
},
{
 "dates":    606,
"data": -16.196 
},
{
 "dates":    607,
"data": 21.147 
},
{
 "dates":    608,
"data": -17.289 
},
{
 "dates":    609,
"data": -40.288 
},
{
 "dates":    610,
"data":   69.9 
},
{
 "dates":    611,
"data": -43.362 
},
{
 "dates":    612,
"data": -64.408 
},
{
 "dates":    613,
"data": 13.508 
},
{
 "dates":    614,
"data": 13.113 
},
{
 "dates":    615,
"data": 60.419 
},
{
 "dates":    616,
"data": -22.733 
},
{
 "dates":    617,
"data": 42.813 
},
{
 "dates":    618,
"data": -46.781 
},
{
 "dates":    619,
"data": -9.9347 
},
{
 "dates":    620,
"data": 19.121 
},
{
 "dates":    621,
"data": -48.009 
},
{
 "dates":    622,
"data":  60.97 
},
{
 "dates":    623,
"data": 3.7907 
},
{
 "dates":    624,
"data": -23.394 
},
{
 "dates":    625,
"data": -20.189 
},
{
 "dates":    626,
"data": 78.446 
},
{
 "dates":    627,
"data": -110.62 
},
{
 "dates":    628,
"data": 78.472 
},
{
 "dates":    629,
"data": -36.484 
},
{
 "dates":    630,
"data": -81.224 
},
{
 "dates":    631,
"data": 77.774 
},
{
 "dates":    632,
"data": -1.7947 
},
{
 "dates":    633,
"data": 72.434 
},
{
 "dates":    634,
"data": -20.425 
},
{
 "dates":    635,
"data": -32.907 
},
{
 "dates":    636,
"data": 1.9656 
},
{
 "dates":    637,
"data": 42.807 
},
{
 "dates":    638,
"data": -18.354 
},
{
 "dates":    639,
"data": 7.6011 
},
{
 "dates":    640,
"data": -64.517 
},
{
 "dates":    641,
"data": 74.084 
},
{
 "dates":    642,
"data": -87.036 
},
{
 "dates":    643,
"data": 12.618 
},
{
 "dates":    644,
"data":  6.343 
},
{
 "dates":    645,
"data": 51.083 
},
{
 "dates":    646,
"data": 2.5589 
},
{
 "dates":    647,
"data": -16.19 
},
{
 "dates":    648,
"data": 54.731 
},
{
 "dates":    649,
"data": -68.533 
},
{
 "dates":    650,
"data": -25.197 
},
{
 "dates":    651,
"data": -12.115 
},
{
 "dates":    652,
"data": 25.927 
},
{
 "dates":    653,
"data":    -11 
},
{
 "dates":    654,
"data": 10.775 
},
{
 "dates":    655,
"data": 59.819 
},
{
 "dates":    656,
"data": -52.514 
},
{
 "dates":    657,
"data": -18.675 
},
{
 "dates":    658,
"data": 54.685 
},
{
 "dates":    659,
"data": -46.952 
},
{
 "dates":    660,
"data": 17.539 
},
{
 "dates":    661,
"data": 50.443 
},
{
 "dates":    662,
"data": -78.944 
},
{
 "dates":    663,
"data": 23.473 
},
{
 "dates":    664,
"data": 23.829 
},
{
 "dates":    665,
"data": -56.207 
},
{
 "dates":    666,
"data":  3.999 
},
{
 "dates":    667,
"data": 29.902 
},
{
 "dates":    668,
"data": 41.769 
},
{
 "dates":    669,
"data": -82.319 
},
{
 "dates":    670,
"data": 28.912 
},
{
 "dates":    671,
"data": 31.472 
},
{
 "dates":    672,
"data": -47.941 
},
{
 "dates":    673,
"data":  37.76 
},
{
 "dates":    674,
"data": 4.6552 
},
{
 "dates":    675,
"data": -35.29 
},
{
 "dates":    676,
"data": 86.312 
},
{
 "dates":    677,
"data": -93.334 
},
{
 "dates":    678,
"data":  36.31 
},
{
 "dates":    679,
"data": 14.389 
},
{
 "dates":    680,
"data": -16.792 
},
{
 "dates":    681,
"data": -16.23 
},
{
 "dates":    682,
"data": -35.58 
},
{
 "dates":    683,
"data": 128.68 
},
{
 "dates":    684,
"data": -94.67 
},
{
 "dates":    685,
"data": 33.841 
},
{
 "dates":    686,
"data": 30.163 
},
{
 "dates":    687,
"data": -27.398 
},
{
 "dates":    688,
"data": 12.325 
},
{
 "dates":    689,
"data": 30.068 
},
{
 "dates":    690,
"data": -18.587 
},
{
 "dates":    691,
"data": -52.203 
},
{
 "dates":    692,
"data": 27.842 
},
{
 "dates":    693,
"data": 44.017 
},
{
 "dates":    694,
"data": -67.608 
},
{
 "dates":    695,
"data": 7.2587 
},
{
 "dates":    696,
"data":  10.28 
},
{
 "dates":    697,
"data": -14.503 
},
{
 "dates":    698,
"data": 89.817 
},
{
 "dates":    699,
"data": 0.60465 
},
{
 "dates":    700,
"data": -47.816 
},
{
 "dates":    701,
"data": -39.033 
},
{
 "dates":    702,
"data": 50.158 
},
{
 "dates":    703,
"data": 14.679 
},
{
 "dates":    704,
"data": 21.898 
},
{
 "dates":    705,
"data": -62.209 
},
{
 "dates":    706,
"data": 35.924 
},
{
 "dates":    707,
"data": -37.504 
},
{
 "dates":    708,
"data": 39.002 
},
{
 "dates":    709,
"data": -32.818 
},
{
 "dates":    710,
"data": 90.316 
},
{
 "dates":    711,
"data": -28.319 
},
{
 "dates":    712,
"data": 13.655 
},
{
 "dates":    713,
"data": -19.881 
},
{
 "dates":    714,
"data":  27.56 
},
{
 "dates":    715,
"data": 1.2022 
},
{
 "dates":    716,
"data": -28.452 
},
{
 "dates":    717,
"data": -51.862 
},
{
 "dates":    718,
"data": 126.83 
},
{
 "dates":    719,
"data": -91.763 
},
{
 "dates":    720,
"data": 25.822 
},
{
 "dates":    721,
"data": 24.027 
},
{
 "dates":    722,
"data": -44.915 
},
{
 "dates":    723,
"data": -0.078086 
},
{
 "dates":    724,
"data":  38.87 
},
{
 "dates":    725,
"data": 6.1996 
},
{
 "dates":    726,
"data": -62.707 
},
{
 "dates":    727,
"data":  67.02 
},
{
 "dates":    728,
"data": 24.632 
},
{
 "dates":    729,
"data": -29.457 
},
{
 "dates":    730,
"data": -9.6357 
},
{
 "dates":    731,
"data": -36.28 
},
{
 "dates":    732,
"data": -12.014 
},
{
 "dates":    733,
"data": 13.013 
},
{
 "dates":    734,
"data": 29.156 
},
{
 "dates":    735,
"data": 61.033 
},
{
 "dates":    736,
"data": -105.75 
},
{
 "dates":    737,
"data": 117.21 
},
{
 "dates":    738,
"data": 0.61498 
},
{
 "dates":    739,
"data": -38.736 
},
{
 "dates":    740,
"data": 23.424 
},
{
 "dates":    741,
"data": -78.848 
},
{
 "dates":    742,
"data": 69.986 
},
{
 "dates":    743,
"data": 4.4692 
},
{
 "dates":    744,
"data": -45.473 
},
{
 "dates":    745,
"data": 76.597 
},
{
 "dates":    746,
"data": 49.556 
},
{
 "dates":    747,
"data": -73.219 
},
{
 "dates":    748,
"data": -7.0542 
},
{
 "dates":    749,
"data": -62.777 
},
{
 "dates":    750,
"data": 138.38 
},
{
 "dates":    751,
"data": -148.68 
},
{
 "dates":    752,
"data": 52.902 
},
{
 "dates":    753,
"data": -24.696 
},
{
 "dates":    754,
"data": 82.339 
},
{
 "dates":    755,
"data": -5.6603 
},
{
 "dates":    756,
"data": -40.114 
},
{
 "dates":    757,
"data": 17.548 
},
{
 "dates":    758,
"data":  26.22 
},
{
 "dates":    759,
"data": -19.226 
},
{
 "dates":    760,
"data": -73.408 
},
{
 "dates":    761,
"data": 101.02 
},
{
 "dates":    762,
"data": -18.281 
},
{
 "dates":    763,
"data": -9.0522 
},
{
 "dates":    764,
"data": -18.07 
},
{
 "dates":    765,
"data": 4.9975 
},
{
 "dates":    766,
"data": 28.206 
},
{
 "dates":    767,
"data": 42.468 
},
{
 "dates":    768,
"data": -32.39 
},
{
 "dates":    769,
"data": -46.307 
},
{
 "dates":    770,
"data": 107.17 
},
{
 "dates":    771,
"data": -67.508 
},
{
 "dates":    772,
"data": -121.84 
},
{
 "dates":    773,
"data": 117.83 
},
{
 "dates":    774,
"data": 23.134 
},
{
 "dates":    775,
"data": 0.44001 
},
{
 "dates":    776,
"data": -9.0809 
},
{
 "dates":    777,
"data": -30.051 
},
{
 "dates":    778,
"data": 55.087 
},
{
 "dates":    779,
"data": -20.641 
},
{
 "dates":    780,
"data": -0.1794 
},
{
 "dates":    781,
"data": 37.197 
},
{
 "dates":    782,
"data": -55.727 
},
{
 "dates":    783,
"data": 48.832 
},
{
 "dates":    784,
"data": -14.386 
},
{
 "dates":    785,
"data": -22.235 
},
{
 "dates":    786,
"data": 31.291 
},
{
 "dates":    787,
"data": -46.855 
},
{
 "dates":    788,
"data": -16.394 
},
{
 "dates":    789,
"data": 50.206 
},
{
 "dates":    790,
"data": 21.728 
},
{
 "dates":    791,
"data": -32.557 
},
{
 "dates":    792,
"data": -16.26 
},
{
 "dates":    793,
"data": 67.689 
},
{
 "dates":    794,
"data": -3.1854 
},
{
 "dates":    795,
"data": -41.743 
},
{
 "dates":    796,
"data":  56.97 
},
{
 "dates":    797,
"data": -28.927 
},
{
 "dates":    798,
"data": -95.609 
},
{
 "dates":    799,
"data": 94.601 
},
{
 "dates":    800,
"data": -60.605 
},
{
 "dates":    801,
"data": 138.29 
},
{
 "dates":    802,
"data": -29.275 
},
{
 "dates":    803,
"data": -58.143 
},
{
 "dates":    804,
"data": -25.312 
},
{
 "dates":    805,
"data": -9.7196 
},
{
 "dates":    806,
"data": -6.5565 
},
{
 "dates":    807,
"data":  130.1 
},
{
 "dates":    808,
"data": -77.605 
},
{
 "dates":    809,
"data": -52.614 
},
{
 "dates":    810,
"data": 149.52 
},
{
 "dates":    811,
"data": -103.14 
},
{
 "dates":    812,
"data": -152.57 
},
{
 "dates":    813,
"data":  162.5 
},
{
 "dates":    814,
"data": 3.3944 
},
{
 "dates":    815,
"data": 60.361 
},
{
 "dates":    816,
"data": -39.706 
},
{
 "dates":    817,
"data": -46.399 
},
{
 "dates":    818,
"data": 51.705 
},
{
 "dates":    819,
"data": -92.607 
},
{
 "dates":    820,
"data": 43.357 
},
{
 "dates":    821,
"data": -13.864 
},
{
 "dates":    822,
"data": 45.658 
},
{
 "dates":    823,
"data": -6.8952 
},
{
 "dates":    824,
"data": -34.112 
},
{
 "dates":    825,
"data": -3.393 
},
{
 "dates":    826,
"data": -17.853 
},
{
 "dates":    827,
"data": 17.366 
},
{
 "dates":    828,
"data": 19.091 
},
{
 "dates":    829,
"data": -22.216 
},
{
 "dates":    830,
"data": 30.024 
},
{
 "dates":    831,
"data": 16.008 
},
{
 "dates":    832,
"data": -74.243 
},
{
 "dates":    833,
"data": 53.584 
},
{
 "dates":    834,
"data": 26.083 
},
{
 "dates":    835,
"data": -23.59 
},
{
 "dates":    836,
"data": 66.899 
},
{
 "dates":    837,
"data":  -23.2 
},
{
 "dates":    838,
"data": -16.561 
},
{
 "dates":    839,
"data": 31.222 
},
{
 "dates":    840,
"data": -138.4 
},
{
 "dates":    841,
"data": 93.114 
},
{
 "dates":    842,
"data": -6.1587 
},
{
 "dates":    843,
"data": -21.635 
},
{
 "dates":    844,
"data": 55.872 
},
{
 "dates":    845,
"data": -32.356 
},
{
 "dates":    846,
"data": -15.75 
},
{
 "dates":    847,
"data": 7.5006 
},
{
 "dates":    848,
"data": 62.812 
},
{
 "dates":    849,
"data": -36.229 
},
{
 "dates":    850,
"data": 33.102 
},
{
 "dates":    851,
"data": -59.181 
},
{
 "dates":    852,
"data": -49.558 
},
{
 "dates":    853,
"data": 48.737 
},
{
 "dates":    854,
"data": 11.321 
},
{
 "dates":    855,
"data": -48.51 
},
{
 "dates":    856,
"data": -54.179 
},
{
 "dates":    857,
"data": 111.78 
},
{
 "dates":    858,
"data": -135.17 
},
{
 "dates":    859,
"data": 116.12 
},
{
 "dates":    860,
"data": -24.923 
},
{
 "dates":    861,
"data": -3.5013 
},
{
 "dates":    862,
"data": 25.046 
},
{
 "dates":    863,
"data": -26.38 
},
{
 "dates":    864,
"data": -7.2119 
},
{
 "dates":    865,
"data": 8.5285 
},
{
 "dates":    866,
"data": 31.892 
},
{
 "dates":    867,
"data": 17.247 
},
{
 "dates":    868,
"data": -118.6 
},
{
 "dates":    869,
"data": 90.743 
},
{
 "dates":    870,
"data": -32.797 
},
{
 "dates":    871,
"data": -27.807 
},
{
 "dates":    872,
"data": 106.78 
},
{
 "dates":    873,
"data": -105.57 
},
{
 "dates":    874,
"data":  89.41 
},
{
 "dates":    875,
"data": -102.43 
},
{
 "dates":    876,
"data": 112.01 
},
{
 "dates":    877,
"data": 3.8998 
},
{
 "dates":    878,
"data": -82.895 
},
{
 "dates":    879,
"data": 41.214 
},
{
 "dates":    880,
"data": 19.236 
},
{
 "dates":    881,
"data": 7.5755 
},
{
 "dates":    882,
"data": -44.66 
},
{
 "dates":    883,
"data": -17.381 
},
{
 "dates":    884,
"data": -6.3638 
},
{
 "dates":    885,
"data": -13.668 
},
{
 "dates":    886,
"data": 16.581 
},
{
 "dates":    887,
"data": -4.4691 
},
{
 "dates":    888,
"data": 50.033 
},
{
 "dates":    889,
"data": -12.606 
},
{
 "dates":    890,
"data": -37.646 
},
{
 "dates":    891,
"data":  10.47 
},
{
 "dates":    892,
"data": 54.106 
},
{
 "dates":    893,
"data": -43.665 
},
{
 "dates":    894,
"data": 1.5471 
},
{
 "dates":    895,
"data": -38.892 
},
{
 "dates":    896,
"data":  30.26 
},
{
 "dates":    897,
"data": 16.423 
},
{
 "dates":    898,
"data": -80.885 
},
{
 "dates":    899,
"data": 44.261 
},
{
 "dates":    900,
"data": -67.065 
},
{
 "dates":    901,
"data": 187.56 
},
{
 "dates":    902,
"data": -91.928 
},
{
 "dates":    903,
"data": 28.738 
},
{
 "dates":    904,
"data": -11.848 
},
{
 "dates":    905,
"data": -72.287 
},
{
 "dates":    906,
"data": -18.969 
},
{
 "dates":    907,
"data": -16.089 
},
{
 "dates":    908,
"data":  126.3 
},
{
 "dates":    909,
"data": -45.002 
},
{
 "dates":    910,
"data": 28.032 
},
{
 "dates":    911,
"data": -12.342 
},
{
 "dates":    912,
"data": -84.794 
},
{
 "dates":    913,
"data":   56.1 
},
{
 "dates":    914,
"data": -43.679 
},
{
 "dates":    915,
"data": -1.2258 
},
{
 "dates":    916,
"data": 97.296 
},
{
 "dates":    917,
"data": -32.925 
},
{
 "dates":    918,
"data": -25.278 
},
{
 "dates":    919,
"data": -29.526 
},
{
 "dates":    920,
"data": -6.4037 
},
{
 "dates":    921,
"data": -27.087 
},
{
 "dates":    922,
"data": 40.401 
},
{
 "dates":    923,
"data": -20.862 
},
{
 "dates":    924,
"data": 47.761 
},
{
 "dates":    925,
"data": -18.106 
},
{
 "dates":    926,
"data": -43.25 
},
{
 "dates":    927,
"data": 75.018 
},
{
 "dates":    928,
"data": -23.703 
},
{
 "dates":    929,
"data": -32.701 
},
{
 "dates":    930,
"data": 85.856 
},
{
 "dates":    931,
"data": -70.802 
},
{
 "dates":    932,
"data": -118.83 
},
{
 "dates":    933,
"data": 73.864 
},
{
 "dates":    934,
"data": 27.719 
},
{
 "dates":    935,
"data": 40.234 
},
{
 "dates":    936,
"data": -85.283 
},
{
 "dates":    937,
"data": 51.642 
},
{
 "dates":    938,
"data": 23.786 
},
{
 "dates":    939,
"data": -38.445 
},
{
 "dates":    940,
"data": 2.9604 
},
{
 "dates":    941,
"data": -3.9821 
},
{
 "dates":    942,
"data": -32.45 
},
{
 "dates":    943,
"data":  30.22 
},
{
 "dates":    944,
"data": 34.086 
},
{
 "dates":    945,
"data": -88.446 
},
{
 "dates":    946,
"data": 81.146 
},
{
 "dates":    947,
"data": 1.6155 
},
{
 "dates":    948,
"data": -4.2468 
},
{
 "dates":    949,
"data": -35.688 
},
{
 "dates":    950,
"data": 7.6053 
},
{
 "dates":    951,
"data": 76.641 
},
{
 "dates":    952,
"data": -62.565 
},
{
 "dates":    953,
"data": -37.847 
},
{
 "dates":    954,
"data": 59.421 
},
{
 "dates":    955,
"data": -98.822 
},
{
 "dates":    956,
"data": 91.882 
},
{
 "dates":    957,
"data": -62.828 
},
{
 "dates":    958,
"data": 53.882 
},
{
 "dates":    959,
"data": -38.711 
},
{
 "dates":    960,
"data": 61.079 
},
{
 "dates":    961,
"data": 54.794 
},
{
 "dates":    962,
"data": -87.395 
},
{
 "dates":    963,
"data": -26.248 
},
{
 "dates":    964,
"data": -64.184 
},
{
 "dates":    965,
"data":  135.3 
},
{
 "dates":    966,
"data": -154.09 
},
{
 "dates":    967,
"data": 98.903 
},
{
 "dates":    968,
"data": -11.67 
},
{
 "dates":    969,
"data": 41.245 
},
{
 "dates":    970,
"data": -77.626 
},
{
 "dates":    971,
"data": 53.166 
},
{
 "dates":    972,
"data": -55.632 
},
{
 "dates":    973,
"data": 98.969 
},
{
 "dates":    974,
"data": -71.452 
},
{
 "dates":    975,
"data": -6.1103 
},
{
 "dates":    976,
"data": 0.66398 
},
{
 "dates":    977,
"data":  -9.15 
},
{
 "dates":    978,
"data": -17.348 
},
{
 "dates":    979,
"data": 104.59 
},
{
 "dates":    980,
"data": -56.034 
},
{
 "dates":    981,
"data": -44.331 
},
{
 "dates":    982,
"data": 1.3295 
},
{
 "dates":    983,
"data": 71.689 
},
{
 "dates":    984,
"data": -54.594 
},
{
 "dates":    985,
"data": -20.292 
},
{
 "dates":    986,
"data": 52.399 
},
{
 "dates":    987,
"data": -8.5305 
},
{
 "dates":    988,
"data": -44.46 
},
{
 "dates":    989,
"data": 100.34 
},
{
 "dates":    990,
"data": -66.762 
},
{
 "dates":    991,
"data": 30.304 
},
{
 "dates":    992,
"data": -57.298 
},
{
 "dates":    993,
"data": -40.082 
},
{
 "dates":    994,
"data": 80.902 
},
{
 "dates":    995,
"data": -54.697 
},
{
 "dates":    996,
"data": 38.413 
},
{
 "dates":    997,
"data": -39.889 
},
{
 "dates":    998,
"data": 12.998 
},
{
 "dates":    999,
"data": -2.4496 
},
{
 "dates":   1000,
"data": 58.982 
},
{
 "dates":   1001,
"data": -39.796 
},
{
 "dates":   1002,
"data": 44.858 
},
{
 "dates":   1003,
"data":  -49.8 
},
{
 "dates":   1004,
"data": 15.017 
},
{
 "dates":   1005,
"data": 60.653 
},
{
 "dates":   1006,
"data": -22.024 
},
{
 "dates":   1007,
"data": -2.7384 
},
{
 "dates":   1008,
"data": 11.248 
},
{
 "dates":   1009,
"data": -61.076 
},
{
 "dates":   1010,
"data":  67.25 
},
{
 "dates":   1011,
"data": -36.433 
},
{
 "dates":   1012,
"data": -19.873 
},
{
 "dates":   1013,
"data": -4.1701 
},
{
 "dates":   1014,
"data": -3.0276 
},
{
 "dates":   1015,
"data": 63.469 
},
{
 "dates":   1016,
"data": -20.219 
},
{
 "dates":   1017,
"data":  64.86 
},
{
 "dates":   1018,
"data": -77.053 
},
{
 "dates":   1019,
"data": 12.929 
},
{
 "dates":   1020,
"data": -63.402 
},
{
 "dates":   1021,
"data": 69.444 
},
{
 "dates":   1022,
"data": -35.96 
},
{
 "dates":   1023,
"data": 90.044 
},
{
 "dates":   1024,
"data": -122.26 
},
{
 "dates":   1025,
"data": 18.454 
},
{
 "dates":   1026,
"data": -5.8435 
},
{
 "dates":   1027,
"data": 3.1825 
},
{
 "dates":   1028,
"data": 26.306 
},
{
 "dates":   1029,
"data": -20.871 
},
{
 "dates":   1030,
"data": 16.219 
},
{
 "dates":   1031,
"data": -40.551 
},
{
 "dates":   1032,
"data": 4.1466 
},
{
 "dates":   1033,
"data": 54.438 
},
{
 "dates":   1034,
"data": 4.6983 
},
{
 "dates":   1035,
"data": -40.36 
},
{
 "dates":   1036,
"data": 20.813 
},
{
 "dates":   1037,
"data": 23.551 
},
{
 "dates":   1038,
"data": 10.424 
},
{
 "dates":   1039,
"data": -29.789 
},
{
 "dates":   1040,
"data": -3.7138 
},
{
 "dates":   1041,
"data": 11.631 
},
{
 "dates":   1042,
"data":  12.98 
},
{
 "dates":   1043,
"data": 21.269 
},
{
 "dates":   1044,
"data": -23.742 
},
{
 "dates":   1045,
"data": 99.439 
},
{
 "dates":   1046,
"data": -76.559 
},
{
 "dates":   1047,
"data": 6.4122 
},
{
 "dates":   1048,
"data": -18.06 
},
{
 "dates":   1049,
"data": 13.592 
},
{
 "dates":   1050,
"data": 24.397 
},
{
 "dates":   1051,
"data": 6.6595 
},
{
 "dates":   1052,
"data": -52.767 
},
{
 "dates":   1053,
"data": -33.663 
},
{
 "dates":   1054,
"data": 123.25 
},
{
 "dates":   1055,
"data": -50.12 
},
{
 "dates":   1056,
"data": 7.6452 
},
{
 "dates":   1057,
"data":  15.64 
},
{
 "dates":   1058,
"data": -25.385 
},
{
 "dates":   1059,
"data": 9.7933 
},
{
 "dates":   1060,
"data": -17.894 
},
{
 "dates":   1061,
"data": 0.20474 
},
{
 "dates":   1062,
"data": -33.786 
},
{
 "dates":   1063,
"data": 1.0975 
},
{
 "dates":   1064,
"data": 81.677 
},
{
 "dates":   1065,
"data": -39.713 
},
{
 "dates":   1066,
"data": -55.603 
},
{
 "dates":   1067,
"data": 58.045 
},
{
 "dates":   1068,
"data": -21.874 
},
{
 "dates":   1069,
"data": 52.699 
},
{
 "dates":   1070,
"data": -43.57 
},
{
 "dates":   1071,
"data": 36.298 
},
{
 "dates":   1072,
"data": 19.652 
},
{
 "dates":   1073,
"data": -37.995 
},
{
 "dates":   1074,
"data": 12.301 
},
{
 "dates":   1075,
"data": 10.852 
},
{
 "dates":   1076,
"data":  -86.9 
},
{
 "dates":   1077,
"data": 57.651 
},
{
 "dates":   1078,
"data": -13.233 
},
{
 "dates":   1079,
"data": 70.726 
},
{
 "dates":   1080,
"data": -37.919 
},
{
 "dates":   1081,
"data": 64.374 
},
{
 "dates":   1082,
"data": -107.21 
},
{
 "dates":   1083,
"data": 111.25 
},
{
 "dates":   1084,
"data": -40.865 
},
{
 "dates":   1085,
"data": -48.318 
},
{
 "dates":   1086,
"data": 16.531 
},
{
 "dates":   1087,
"data": 57.901 
},
{
 "dates":   1088,
"data": -47.972 
},
{
 "dates":   1089,
"data": -46.114 
},
{
 "dates":   1090,
"data": 13.392 
},
{
 "dates":   1091,
"data":  6.545 
},
{
 "dates":   1092,
"data": 56.525 
},
{
 "dates":   1093,
"data": -1.7864 
},
{
 "dates":   1094,
"data": -0.56638 
},
{
 "dates":   1095,
"data": 9.3758 
},
{
 "dates":   1096,
"data": -73.061 
},
{
 "dates":   1097,
"data": 124.88 
},
{
 "dates":   1098,
"data": -103.42 
},
{
 "dates":   1099,
"data": 36.008 
},
{
 "dates":   1100,
"data": 0.088267 
},
{
 "dates":   1101,
"data": 27.124 
},
{
 "dates":   1102,
"data": 4.9341 
},
{
 "dates":   1103,
"data": 0.78132 
},
{
 "dates":   1104,
"data": -26.373 
},
{
 "dates":   1105,
"data": -5.3492 
},
{
 "dates":   1106,
"data":  26.95 
},
{
 "dates":   1107,
"data": -62.799 
},
{
 "dates":   1108,
"data": 113.55 
},
{
 "dates":   1109,
"data": 38.745 
},
{
 "dates":   1110,
"data": -65.997 
},
{
 "dates":   1111,
"data": 37.872 
},
{
 "dates":   1112,
"data": -30.251 
},
{
 "dates":   1113,
"data": 10.086 
},
{
 "dates":   1114,
"data": -71.421 
},
{
 "dates":   1115,
"data": 77.989 
},
{
 "dates":   1116,
"data": -83.682 
},
{
 "dates":   1117,
"data": 131.48 
},
{
 "dates":   1118,
"data": -67.655 
},
{
 "dates":   1119,
"data": -25.968 
},
{
 "dates":   1120,
"data": -68.908 
},
{
 "dates":   1121,
"data": 73.651 
},
{
 "dates":   1122,
"data": 50.946 
},
{
 "dates":   1123,
"data": 37.681 
},
{
 "dates":   1124,
"data": 21.211 
},
{
 "dates":   1125,
"data": -32.115 
},
{
 "dates":   1126,
"data": -34.933 
},
{
 "dates":   1127,
"data": -17.476 
},
{
 "dates":   1128,
"data": -23.556 
},
{
 "dates":   1129,
"data":  49.74 
},
{
 "dates":   1130,
"data": -62.165 
},
{
 "dates":   1131,
"data": 109.93 
},
{
 "dates":   1132,
"data":  -83.9 
},
{
 "dates":   1133,
"data": 7.2175 
},
{
 "dates":   1134,
"data": 4.8526 
},
{
 "dates":   1135,
"data": -4.3905 
},
{
 "dates":   1136,
"data": -18.704 
},
{
 "dates":   1137,
"data":   76.1 
},
{
 "dates":   1138,
"data": -23.873 
},
{
 "dates":   1139,
"data": -77.746 
},
{
 "dates":   1140,
"data": 76.644 
},
{
 "dates":   1141,
"data": -8.5464 
},
{
 "dates":   1142,
"data": 88.132 
},
{
 "dates":   1143,
"data": -80.501 
},
{
 "dates":   1144,
"data":  60.09 
},
{
 "dates":   1145,
"data": -29.888 
},
{
 "dates":   1146,
"data":  1.039 
},
{
 "dates":   1147,
"data": -82.949 
},
{
 "dates":   1148,
"data": 39.502 
},
{
 "dates":   1149,
"data": 35.448 
},
{
 "dates":   1150,
"data": -17.61 
},
{
 "dates":   1151,
"data": 62.755 
},
{
 "dates":   1152,
"data": -85.399 
},
{
 "dates":   1153,
"data": -5.6015 
},
{
 "dates":   1154,
"data": 12.501 
},
{
 "dates":   1155,
"data": 92.301 
},
{
 "dates":   1156,
"data": -103.63 
},
{
 "dates":   1157,
"data": 37.512 
},
{
 "dates":   1158,
"data": -55.271 
},
{
 "dates":   1159,
"data": 50.726 
},
{
 "dates":   1160,
"data": -54.663 
},
{
 "dates":   1161,
"data": 19.983 
},
{
 "dates":   1162,
"data": -51.098 
},
{
 "dates":   1163,
"data": 115.05 
},
{
 "dates":   1164,
"data": 51.278 
},
{
 "dates":   1165,
"data": -63.75 
},
{
 "dates":   1166,
"data": 8.0368 
},
{
 "dates":   1167,
"data": 56.273 
},
{
 "dates":   1168,
"data": -51.734 
},
{
 "dates":   1169,
"data": 65.754 
},
{
 "dates":   1170,
"data": -102.64 
},
{
 "dates":   1171,
"data": 72.246 
},
{
 "dates":   1172,
"data": -84.031 
},
{
 "dates":   1173,
"data": 96.742 
},
{
 "dates":   1174,
"data": -45.827 
},
{
 "dates":   1175,
"data": -13.823 
},
{
 "dates":   1176,
"data": -8.5108 
},
{
 "dates":   1177,
"data": 72.949 
},
{
 "dates":   1178,
"data": -99.423 
},
{
 "dates":   1179,
"data": 59.776 
},
{
 "dates":   1180,
"data": -86.209 
},
{
 "dates":   1181,
"data": 81.393 
},
{
 "dates":   1182,
"data": -19.801 
},
{
 "dates":   1183,
"data": 25.788 
},
{
 "dates":   1184,
"data": -36.596 
},
{
 "dates":   1185,
"data": 101.99 
},
{
 "dates":   1186,
"data": -103.46 
},
{
 "dates":   1187,
"data": 140.14 
},
{
 "dates":   1188,
"data": -168.81 
},
{
 "dates":   1189,
"data": 93.695 
},
{
 "dates":   1190,
"data": -18.621 
},
{
 "dates":   1191,
"data": -0.28341 
},
{
 "dates":   1192,
"data": -15.237 
},
{
 "dates":   1193,
"data": 45.103 
},
{
 "dates":   1194,
"data": -129.25 
},
{
 "dates":   1195,
"data": 63.494 
},
{
 "dates":   1196,
"data": 138.92 
},
{
 "dates":   1197,
"data": -16.516 
},
{
 "dates":   1198,
"data": -81.563 
},
{
 "dates":   1199,
"data": 38.316 
},
{
 "dates":   1200,
"data": -48.493 
},
{
 "dates":   1201,
"data": -88.351 
},
{
 "dates":   1202,
"data": 82.584 
},
{
 "dates":   1203,
"data": -4.6432 
},
{
 "dates":   1204,
"data": 60.072 
},
{
 "dates":   1205,
"data": -122.36 
},
{
 "dates":   1206,
"data": 115.19 
},
{
 "dates":   1207,
"data": -76.08 
},
{
 "dates":   1208,
"data": 75.002 
},
{
 "dates":   1209,
"data": -12.842 
},
{
 "dates":   1210,
"data": -44.349 
},
{
 "dates":   1211,
"data": 87.784 
},
{
 "dates":   1212,
"data": -108.61 
},
{
 "dates":   1213,
"data": 30.746 
},
{
 "dates":   1214,
"data": -50.954 
},
{
 "dates":   1215,
"data":  22.88 
},
{
 "dates":   1216,
"data":  39.67 
},
{
 "dates":   1217,
"data": 2.4841 
},
{
 "dates":   1218,
"data": -82.105 
},
{
 "dates":   1219,
"data":  146.7 
},
{
 "dates":   1220,
"data": -42.418 
},
{
 "dates":   1221,
"data": -36.721 
},
{
 "dates":   1222,
"data": 42.187 
},
{
 "dates":   1223,
"data": -159.62 
},
{
 "dates":   1224,
"data": 113.62 
},
{
 "dates":   1225,
"data": 3.7505 
},
{
 "dates":   1226,
"data": -13.194 
},
{
 "dates":   1227,
"data": -25.153 
},
{
 "dates":   1228,
"data": 25.833 
},
{
 "dates":   1229,
"data": 45.114 
},
{
 "dates":   1230,
"data": 12.733 
},
{
 "dates":   1231,
"data": -28.202 
},
{
 "dates":   1232,
"data": 20.526 
},
{
 "dates":   1233,
"data": -89.62 
},
{
 "dates":   1234,
"data": -6.0772 
},
{
 "dates":   1235,
"data": -36.558 
},
{
 "dates":   1236,
"data": 44.484 
},
{
 "dates":   1237,
"data": -72.612 
},
{
 "dates":   1238,
"data": 55.594 
},
{
 "dates":   1239,
"data": 115.11 
},
{
 "dates":   1240,
"data": -134.83 
},
{
 "dates":   1241,
"data":  77.92 
},
{
 "dates":   1242,
"data": -21.001 
},
{
 "dates":   1243,
"data": -15.295 
},
{
 "dates":   1244,
"data":  81.14 
},
{
 "dates":   1245,
"data": -26.735 
},
{
 "dates":   1246,
"data": -60.079 
},
{
 "dates":   1247,
"data": 99.706 
},
{
 "dates":   1248,
"data": -120.03 
},
{
 "dates":   1249,
"data": 49.451 
},
{
 "dates":   1250,
"data": 33.123 
},
{
 "dates":   1251,
"data": -33.234 
},
{
 "dates":   1252,
"data": 3.8746 
},
{
 "dates":   1253,
"data": -60.245 
},
{
 "dates":   1254,
"data": 67.345 
},
{
 "dates":   1255,
"data": -30.803 
},
{
 "dates":   1256,
"data": -1.2168 
},
{
 "dates":   1257,
"data": 51.876 
},
{
 "dates":   1258,
"data": -52.775 
},
{
 "dates":   1259,
"data": 23.828 
},
{
 "dates":   1260,
"data": -97.284 
},
{
 "dates":   1261,
"data": 70.673 
},
{
 "dates":   1262,
"data": 27.945 
},
{
 "dates":   1263,
"data": -45.226 
},
{
 "dates":   1264,
"data": 16.329 
},
{
 "dates":   1265,
"data": 20.729 
},
{
 "dates":   1266,
"data": -35.542 
},
{
 "dates":   1267,
"data": -1.0223 
},
{
 "dates":   1268,
"data": -0.045787 
},
{
 "dates":   1269,
"data":  24.26 
},
{
 "dates":   1270,
"data": -48.129 
},
{
 "dates":   1271,
"data":  12.14 
},
{
 "dates":   1272,
"data":  77.87 
},
{
 "dates":   1273,
"data": -11.153 
},
{
 "dates":   1274,
"data": -84.949 
},
{
 "dates":   1275,
"data": 19.758 
},
{
 "dates":   1276,
"data": -14.253 
},
{
 "dates":   1277,
"data": 68.722 
},
{
 "dates":   1278,
"data": -38.421 
},
{
 "dates":   1279,
"data": -61.438 
},
{
 "dates":   1280,
"data":  34.26 
},
{
 "dates":   1281,
"data": 67.133 
},
{
 "dates":   1282,
"data": -38.327 
},
{
 "dates":   1283,
"data": -40.882 
},
{
 "dates":   1284,
"data": 79.561 
},
{
 "dates":   1285,
"data": -70.743 
},
{
 "dates":   1286,
"data": 52.191 
},
{
 "dates":   1287,
"data": -14.348 
},
{
 "dates":   1288,
"data": -74.777 
},
{
 "dates":   1289,
"data": 127.42 
},
{
 "dates":   1290,
"data": -87.756 
},
{
 "dates":   1291,
"data": 8.5714 
},
{
 "dates":   1292,
"data": -64.445 
},
{
 "dates":   1293,
"data": 11.563 
},
{
 "dates":   1294,
"data": 8.9227 
},
{
 "dates":   1295,
"data": 0.79904 
},
{
 "dates":   1296,
"data": 39.331 
},
{
 "dates":   1297,
"data": -23.674 
},
{
 "dates":   1298,
"data":  62.65 
},
{
 "dates":   1299,
"data": -28.76 
},
{
 "dates":   1300,
"data": -68.036 
},
{
 "dates":   1301,
"data": 61.367 
},
{
 "dates":   1302,
"data": -14.092 
},
{
 "dates":   1303,
"data": -6.5511 
},
{
 "dates":   1304,
"data": 81.376 
},
{
 "dates":   1305,
"data": -37.148 
},
{
 "dates":   1306,
"data": -62.097 
},
{
 "dates":   1307,
"data": 50.601 
},
{
 "dates":   1308,
"data": -71.883 
},
{
 "dates":   1309,
"data": 67.008 
},
{
 "dates":   1310,
"data": -20.805 
},
{
 "dates":   1311,
"data": 44.907 
},
{
 "dates":   1312,
"data": -63.823 
},
{
 "dates":   1313,
"data": 43.317 
},
{
 "dates":   1314,
"data": -76.048 
},
{
 "dates":   1315,
"data": 18.926 
},
{
 "dates":   1316,
"data": -42.253 
},
{
 "dates":   1317,
"data": 34.699 
},
{
 "dates":   1318,
"data": -42.816 
},
{
 "dates":   1319,
"data": 5.6835 
},
{
 "dates":   1320,
"data": 84.468 
},
{
 "dates":   1321,
"data": -137.93 
},
{
 "dates":   1322,
"data": -11.784 
},
{
 "dates":   1323,
"data": 99.167 
},
{
 "dates":   1324,
"data": -10.985 
},
{
 "dates":   1325,
"data": 68.243 
},
{
 "dates":   1326,
"data": -31.938 
},
{
 "dates":   1327,
"data": -79.319 
},
{
 "dates":   1328,
"data": 110.18 
},
{
 "dates":   1329,
"data":  21.09 
},
{
 "dates":   1330,
"data": -119.4 
},
{
 "dates":   1331,
"data": 80.711 
},
{
 "dates":   1332,
"data": -42.901 
},
{
 "dates":   1333,
"data": 28.959 
},
{
 "dates":   1334,
"data": -24.763 
},
{
 "dates":   1335,
"data": -19.847 
},
{
 "dates":   1336,
"data": 44.159 
},
{
 "dates":   1337,
"data":  21.08 
},
{
 "dates":   1338,
"data": -5.9585 
},
{
 "dates":   1339,
"data":  5.589 
},
{
 "dates":   1340,
"data": -0.90971 
},
{
 "dates":   1341,
"data": -21.991 
},
{
 "dates":   1342,
"data": 3.7233 
},
{
 "dates":   1343,
"data": -31.285 
},
{
 "dates":   1344,
"data": 38.816 
},
{
 "dates":   1345,
"data": 0.97738 
},
{
 "dates":   1346,
"data": 8.1925 
},
{
 "dates":   1347,
"data": 29.183 
},
{
 "dates":   1348,
"data": -175.6 
},
{
 "dates":   1349,
"data": 181.25 
},
{
 "dates":   1350,
"data": -86.469 
},
{
 "dates":   1351,
"data": -6.2607 
},
{
 "dates":   1352,
"data": -12.861 
},
{
 "dates":   1353,
"data": -23.967 
},
{
 "dates":   1354,
"data": 66.136 
},
{
 "dates":   1355,
"data": -16.905 
},
{
 "dates":   1356,
"data": 36.977 
},
{
 "dates":   1357,
"data": -124.18 
},
{
 "dates":   1358,
"data": 109.59 
},
{
 "dates":   1359,
"data": -84.414 
},
{
 "dates":   1360,
"data": 16.306 
},
{
 "dates":   1361,
"data": 57.381 
},
{
 "dates":   1362,
"data": -33.152 
},
{
 "dates":   1363,
"data":  85.48 
},
{
 "dates":   1364,
"data": -23.545 
},
{
 "dates":   1365,
"data": -10.065 
},
{
 "dates":   1366,
"data": -130.17 
},
{
 "dates":   1367,
"data": 77.848 
},
{
 "dates":   1368,
"data": 69.269 
},
{
 "dates":   1369,
"data": -56.841 
},
{
 "dates":   1370,
"data":  44.14 
},
{
 "dates":   1371,
"data": -60.333 
},
{
 "dates":   1372,
"data": 21.654 
},
{
 "dates":   1373,
"data": -49.972 
},
{
 "dates":   1374,
"data": 91.693 
},
{
 "dates":   1375,
"data": -109.48 
},
{
 "dates":   1376,
"data": 123.58 
},
{
 "dates":   1377,
"data": -29.704 
},
{
 "dates":   1378,
"data": -26.266 
},
{
 "dates":   1379,
"data": -1.0483 
},
{
 "dates":   1380,
"data": -30.683 
},
{
 "dates":   1381,
"data": 32.862 
},
{
 "dates":   1382,
"data": 34.821 
},
{
 "dates":   1383,
"data": 9.1458 
},
{
 "dates":   1384,
"data": -107.4 
},
{
 "dates":   1385,
"data": 42.904 
},
{
 "dates":   1386,
"data": -14.352 
},
{
 "dates":   1387,
"data": -33.108 
},
{
 "dates":   1388,
"data": 104.58 
},
{
 "dates":   1389,
"data": -93.734 
},
{
 "dates":   1390,
"data": 139.81 
},
{
 "dates":   1391,
"data": -72.914 
},
{
 "dates":   1392,
"data": 42.325 
},
{
 "dates":   1393,
"data": -9.1356 
},
{
 "dates":   1394,
"data": -15.108 
},
{
 "dates":   1395,
"data": -32.41 
},
{
 "dates":   1396,
"data": 54.869 
},
{
 "dates":   1397,
"data": -37.062 
},
{
 "dates":   1398,
"data": 30.429 
},
{
 "dates":   1399,
"data": 6.3572 
},
{
 "dates":   1400,
"data": -54.377 
},
{
 "dates":   1401,
"data": 49.769 
},
{
 "dates":   1402,
"data": 51.065 
},
{
 "dates":   1403,
"data": -38.922 
},
{
 "dates":   1404,
"data": -11.023 
},
{
 "dates":   1405,
"data":  22.22 
},
{
 "dates":   1406,
"data": -42.007 
},
{
 "dates":   1407,
"data": -73.515 
},
{
 "dates":   1408,
"data": 70.053 
},
{
 "dates":   1409,
"data": -11.111 
},
{
 "dates":   1410,
"data": -36.784 
},
{
 "dates":   1411,
"data": 90.947 
},
{
 "dates":   1412,
"data": -98.056 
},
{
 "dates":   1413,
"data": 8.9735 
},
{
 "dates":   1414,
"data": 2.2029 
},
{
 "dates":   1415,
"data": 80.207 
},
{
 "dates":   1416,
"data": -39.498 
},
{
 "dates":   1417,
"data": 34.896 
},
{
 "dates":   1418,
"data": -46.073 
},
{
 "dates":   1419,
"data": 17.249 
},
{
 "dates":   1420,
"data": 30.269 
},
{
 "dates":   1421,
"data": 25.212 
},
{
 "dates":   1422,
"data": -14.202 
},
{
 "dates":   1423,
"data": -51.927 
},
{
 "dates":   1424,
"data":  78.18 
},
{
 "dates":   1425,
"data": -29.476 
},
{
 "dates":   1426,
"data": -20.349 
},
{
 "dates":   1427,
"data": 26.467 
},
{
 "dates":   1428,
"data": 40.462 
},
{
 "dates":   1429,
"data": -33.454 
},
{
 "dates":   1430,
"data": 72.564 
},
{
 "dates":   1431,
"data": -108.62 
},
{
 "dates":   1432,
"data": 56.972 
},
{
 "dates":   1433,
"data": -58.007 
},
{
 "dates":   1434,
"data": 107.72 
},
{
 "dates":   1435,
"data": 7.1494 
},
{
 "dates":   1436,
"data": -68.575 
},
{
 "dates":   1437,
"data": -14.852 
},
{
 "dates":   1438,
"data": 43.418 
},
{
 "dates":   1439,
"data": -33.604 
},
{
 "dates":   1440,
"data": 37.584 
},
{
 "dates":   1441,
"data": -69.482 
},
{
 "dates":   1442,
"data": 27.821 
},
{
 "dates":   1443,
"data": -23.879 
},
{
 "dates":   1444,
"data": 34.348 
},
{
 "dates":   1445,
"data": 29.755 
},
{
 "dates":   1446,
"data": 2.2855 
},
{
 "dates":   1447,
"data": -4.2755 
},
{
 "dates":   1448,
"data": 1.5598 
},
{
 "dates":   1449,
"data": -32.969 
},
{
 "dates":   1450,
"data": 76.221 
},
{
 "dates":   1451,
"data": -21.718 
},
{
 "dates":   1452,
"data": -22.995 
},
{
 "dates":   1453,
"data": 27.017 
},
{
 "dates":   1454,
"data":  -62.8 
},
{
 "dates":   1455,
"data": 6.4725 
},
{
 "dates":   1456,
"data": 26.536 
},
{
 "dates":   1457,
"data": -11.672 
},
{
 "dates":   1458,
"data": 60.252 
},
{
 "dates":   1459,
"data": -24.638 
},
{
 "dates":   1460,
"data": 17.441 
},
{
 "dates":   1461,
"data": -58.411 
} 
]
  
      var data = d3.nest()
        .key(function(d){
          return opts.group === undefined ? 'main' : d[opts.group]
        })
        .entries(data)
      
      nv.addGraph(function() {
        var chart = nv.models[opts.type]()
          .x(function(d) { return d[opts.x] })
          .y(function(d) { return d[opts.y] })
          .width(opts.width)
          .height(opts.height)
         
        
          
        

        
        
        
      
       d3.select("#" + opts.id)
        .append('svg')
        .datum(data)
        .transition().duration(500)
        .call(chart);

       nv.utils.windowResize(chart.update);
       return chart;
      });
    };
</script>


While we now  have a stationary mean (0) we can see that the variance in the time series seems to be growing over time.  It will be useful here to log-normalize the data  first.





<div id='dataDiffLog' class='rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawdataDiffLog()
    });
    function drawdataDiffLog(){  
      var opts = {
 "dom": "dataDiffLog",
"width":    800,
"height":    400,
"x": "dates",
"y": "data",
"type": "lineChart",
"id": "dataDiffLog" 
},
        data = [
 {
 "dates":      2,
"data": 0.01223 
},
{
 "dates":      3,
"data": -0.011463 
},
{
 "dates":      4,
"data": 0.049841 
},
{
 "dates":      5,
"data": 0.00013502 
},
{
 "dates":      6,
"data": -0.049358 
},
{
 "dates":      7,
"data": 0.030181 
},
{
 "dates":      8,
"data": -0.041249 
},
{
 "dates":      9,
"data": 0.021862 
},
{
 "dates":     10,
"data": 0.0027941 
},
{
 "dates":     11,
"data": 0.0553 
},
{
 "dates":     12,
"data": -0.045225 
},
{
 "dates":     13,
"data": 0.031389 
},
{
 "dates":     14,
"data": 0.033516 
},
{
 "dates":     15,
"data": -0.011082 
},
{
 "dates":     16,
"data": 0.033325 
},
{
 "dates":     17,
"data": -0.07389 
},
{
 "dates":     18,
"data": 0.021719 
},
{
 "dates":     19,
"data": -0.025995 
},
{
 "dates":     20,
"data": 0.034541 
},
{
 "dates":     21,
"data": -0.032284 
},
{
 "dates":     22,
"data": 0.026035 
},
{
 "dates":     23,
"data": 0.0012899 
},
{
 "dates":     24,
"data": 0.058451 
},
{
 "dates":     25,
"data": -0.065475 
},
{
 "dates":     26,
"data": 0.022734 
},
{
 "dates":     27,
"data": 0.011557 
},
{
 "dates":     28,
"data": -0.024302 
},
{
 "dates":     29,
"data": -0.0027811 
},
{
 "dates":     30,
"data": 0.055101 
},
{
 "dates":     31,
"data": -0.011077 
},
{
 "dates":     32,
"data": 0.019141 
},
{
 "dates":     33,
"data": -0.03505 
},
{
 "dates":     34,
"data": 0.033834 
},
{
 "dates":     35,
"data": -0.00098763 
},
{
 "dates":     36,
"data": -0.023215 
},
{
 "dates":     37,
"data": 0.033886 
},
{
 "dates":     38,
"data": -0.031224 
},
{
 "dates":     39,
"data": 0.00061772 
},
{
 "dates":     40,
"data": -0.065524 
},
{
 "dates":     41,
"data": 0.10123 
},
{
 "dates":     42,
"data": -0.053417 
},
{
 "dates":     43,
"data": 0.030177 
},
{
 "dates":     44,
"data": -0.059163 
},
{
 "dates":     45,
"data": 0.018893 
},
{
 "dates":     46,
"data": 0.051919 
},
{
 "dates":     47,
"data": -0.00081493 
},
{
 "dates":     48,
"data": -0.023938 
},
{
 "dates":     49,
"data": 0.06509 
},
{
 "dates":     50,
"data": -0.071604 
},
{
 "dates":     51,
"data": -0.0027156 
},
{
 "dates":     52,
"data": 0.019186 
},
{
 "dates":     53,
"data": -0.011582 
},
{
 "dates":     54,
"data": -0.013933 
},
{
 "dates":     55,
"data": 0.025683 
},
{
 "dates":     56,
"data": -0.018303 
},
{
 "dates":     57,
"data": 0.030337 
},
{
 "dates":     58,
"data": -0.058467 
},
{
 "dates":     59,
"data": 0.048571 
},
{
 "dates":     60,
"data": -0.0031288 
},
{
 "dates":     61,
"data": 0.034734 
},
{
 "dates":     62,
"data": -0.029158 
},
{
 "dates":     63,
"data": 0.017862 
},
{
 "dates":     64,
"data": -0.039297 
},
{
 "dates":     65,
"data": -0.012433 
},
{
 "dates":     66,
"data": 0.082154 
},
{
 "dates":     67,
"data": -0.07107 
},
{
 "dates":     68,
"data": 0.055138 
},
{
 "dates":     69,
"data": -0.044062 
},
{
 "dates":     70,
"data": 0.084596 
},
{
 "dates":     71,
"data": -0.017117 
},
{
 "dates":     72,
"data": -0.031305 
},
{
 "dates":     73,
"data": 0.010634 
},
{
 "dates":     74,
"data": -0.0051987 
},
{
 "dates":     75,
"data": -0.022314 
},
{
 "dates":     76,
"data": 0.058596 
},
{
 "dates":     77,
"data": -0.080374 
},
{
 "dates":     78,
"data": 0.054154 
},
{
 "dates":     79,
"data": 0.020264 
},
{
 "dates":     80,
"data": -0.039676 
},
{
 "dates":     81,
"data": 0.026522 
},
{
 "dates":     82,
"data": -0.050207 
},
{
 "dates":     83,
"data": 0.047543 
},
{
 "dates":     84,
"data": 0.012198 
},
{
 "dates":     85,
"data": -0.039182 
},
{
 "dates":     86,
"data": 0.029253 
},
{
 "dates":     87,
"data": 0.068789 
},
{
 "dates":     88,
"data": -0.098958 
},
{
 "dates":     89,
"data": -0.024931 
},
{
 "dates":     90,
"data": 0.018318 
},
{
 "dates":     91,
"data": -0.0094621 
},
{
 "dates":     92,
"data": 0.05048 
},
{
 "dates":     93,
"data": -0.0093594 
},
{
 "dates":     94,
"data": -0.037241 
},
{
 "dates":     95,
"data": -0.0046762 
},
{
 "dates":     96,
"data": 0.010535 
},
{
 "dates":     97,
"data": -0.016384 
},
{
 "dates":     98,
"data": 0.064246 
},
{
 "dates":     99,
"data": -0.063462 
},
{
 "dates":    100,
"data": 0.061328 
},
{
 "dates":    101,
"data": 0.00085157 
},
{
 "dates":    102,
"data": -0.030799 
},
{
 "dates":    103,
"data": -0.03657 
},
{
 "dates":    104,
"data": -0.011865 
},
{
 "dates":    105,
"data": 0.11142 
},
{
 "dates":    106,
"data": -0.10704 
},
{
 "dates":    107,
"data": 0.059021 
},
{
 "dates":    108,
"data": 0.024997 
},
{
 "dates":    109,
"data": 0.00563 
},
{
 "dates":    110,
"data": -0.026121 
},
{
 "dates":    111,
"data": -0.010241 
},
{
 "dates":    112,
"data": 0.0096157 
},
{
 "dates":    113,
"data": -0.0041627 
},
{
 "dates":    114,
"data": 0.037751 
},
{
 "dates":    115,
"data": -0.038594 
},
{
 "dates":    116,
"data": 0.023597 
},
{
 "dates":    117,
"data": -0.06797 
},
{
 "dates":    118,
"data": 0.01043 
},
{
 "dates":    119,
"data": -0.019797 
},
{
 "dates":    120,
"data": 0.040967 
},
{
 "dates":    121,
"data": -0.031664 
},
{
 "dates":    122,
"data": 0.014951 
},
{
 "dates":    123,
"data": 0.0049698 
},
{
 "dates":    124,
"data": -0.039439 
},
{
 "dates":    125,
"data": 0.048636 
},
{
 "dates":    126,
"data": -0.0054953 
},
{
 "dates":    127,
"data": 0.016182 
},
{
 "dates":    128,
"data": -0.024084 
},
{
 "dates":    129,
"data": -0.012282 
},
{
 "dates":    130,
"data": -0.0082076 
},
{
 "dates":    131,
"data": 0.075739 
},
{
 "dates":    132,
"data": -0.053663 
},
{
 "dates":    133,
"data": -0.043396 
},
{
 "dates":    134,
"data": 0.027928 
},
{
 "dates":    135,
"data": 0.023123 
},
{
 "dates":    136,
"data": 0.0067777 
},
{
 "dates":    137,
"data": 0.0030774 
},
{
 "dates":    138,
"data": 0.0035543 
},
{
 "dates":    139,
"data": -0.024575 
},
{
 "dates":    140,
"data": -0.022769 
},
{
 "dates":    141,
"data": 0.010343 
},
{
 "dates":    142,
"data": 0.017234 
},
{
 "dates":    143,
"data": 0.025062 
},
{
 "dates":    144,
"data": 0.031828 
},
{
 "dates":    145,
"data": -0.037121 
},
{
 "dates":    146,
"data": -0.018389 
},
{
 "dates":    147,
"data": 0.027026 
},
{
 "dates":    148,
"data": -0.030623 
},
{
 "dates":    149,
"data": -0.03395 
},
{
 "dates":    150,
"data": 0.034363 
},
{
 "dates":    151,
"data": -0.040472 
},
{
 "dates":    152,
"data": 0.03431 
},
{
 "dates":    153,
"data": -0.003944 
},
{
 "dates":    154,
"data": -0.01863 
},
{
 "dates":    155,
"data": -0.033111 
},
{
 "dates":    156,
"data": 0.10269 
},
{
 "dates":    157,
"data": -0.088039 
},
{
 "dates":    158,
"data": 0.056688 
},
{
 "dates":    159,
"data": -0.034175 
},
{
 "dates":    160,
"data": 0.039466 
},
{
 "dates":    161,
"data": 0.0024717 
},
{
 "dates":    162,
"data": -0.053759 
},
{
 "dates":    163,
"data": -0.0077406 
},
{
 "dates":    164,
"data": -0.011935 
},
{
 "dates":    165,
"data": 0.056129 
},
{
 "dates":    166,
"data": -0.060776 
},
{
 "dates":    167,
"data": 0.012225 
},
{
 "dates":    168,
"data": 0.018414 
},
{
 "dates":    169,
"data": -0.051605 
},
{
 "dates":    170,
"data": -0.020174 
},
{
 "dates":    171,
"data": 0.077756 
},
{
 "dates":    172,
"data": 0.041741 
},
{
 "dates":    173,
"data": -0.020192 
},
{
 "dates":    174,
"data": -0.043546 
},
{
 "dates":    175,
"data": 0.0088066 
},
{
 "dates":    176,
"data": -0.011028 
},
{
 "dates":    177,
"data": -0.0063376 
},
{
 "dates":    178,
"data": 0.00050463 
},
{
 "dates":    179,
"data": -0.00041986 
},
{
 "dates":    180,
"data": 0.036687 
},
{
 "dates":    181,
"data": -0.0067067 
},
{
 "dates":    182,
"data": 0.0017745 
},
{
 "dates":    183,
"data": 0.013384 
},
{
 "dates":    184,
"data": -0.030826 
},
{
 "dates":    185,
"data": -0.0034625 
},
{
 "dates":    186,
"data": 0.034493 
},
{
 "dates":    187,
"data": 0.017615 
},
{
 "dates":    188,
"data": -0.049446 
},
{
 "dates":    189,
"data": 0.0014274 
},
{
 "dates":    190,
"data": 0.021576 
},
{
 "dates":    191,
"data": -0.0024077 
},
{
 "dates":    192,
"data": -0.038732 
},
{
 "dates":    193,
"data": 0.038597 
},
{
 "dates":    194,
"data": -0.058366 
},
{
 "dates":    195,
"data": 0.094489 
},
{
 "dates":    196,
"data": -0.062036 
},
{
 "dates":    197,
"data": -0.0075081 
},
{
 "dates":    198,
"data": -0.0086711 
},
{
 "dates":    199,
"data": 0.014244 
},
{
 "dates":    200,
"data": -0.0059349 
},
{
 "dates":    201,
"data": -0.037674 
},
{
 "dates":    202,
"data": -0.0089737 
},
{
 "dates":    203,
"data": 0.043944 
},
{
 "dates":    204,
"data": -0.017106 
},
{
 "dates":    205,
"data": 0.0068025 
},
{
 "dates":    206,
"data": 0.035903 
},
{
 "dates":    207,
"data": -0.021231 
},
{
 "dates":    208,
"data": -0.042833 
},
{
 "dates":    209,
"data": 0.0074757 
},
{
 "dates":    210,
"data": -0.015964 
},
{
 "dates":    211,
"data": -0.006015 
},
{
 "dates":    212,
"data": 0.030791 
},
{
 "dates":    213,
"data": -0.031559 
},
{
 "dates":    214,
"data": 0.032013 
},
{
 "dates":    215,
"data": -0.035785 
},
{
 "dates":    216,
"data": -0.014279 
},
{
 "dates":    217,
"data": 0.02984 
},
{
 "dates":    218,
"data": 0.044427 
},
{
 "dates":    219,
"data": -0.0029029 
},
{
 "dates":    220,
"data": -0.042591 
},
{
 "dates":    221,
"data": 0.044224 
},
{
 "dates":    222,
"data": -0.0058264 
},
{
 "dates":    223,
"data": -0.022135 
},
{
 "dates":    224,
"data": -0.01814 
},
{
 "dates":    225,
"data": -0.045667 
},
{
 "dates":    226,
"data": 0.10232 
},
{
 "dates":    227,
"data": -0.068436 
},
{
 "dates":    228,
"data": -0.0017114 
},
{
 "dates":    229,
"data": -0.02976 
},
{
 "dates":    230,
"data": 0.040754 
},
{
 "dates":    231,
"data": 0.012425 
},
{
 "dates":    232,
"data": -0.024275 
},
{
 "dates":    233,
"data": 0.0079157 
},
{
 "dates":    234,
"data": -0.00272 
},
{
 "dates":    235,
"data": -0.055836 
},
{
 "dates":    236,
"data": -0.016596 
},
{
 "dates":    237,
"data": 0.058332 
},
{
 "dates":    238,
"data": 0.054266 
},
{
 "dates":    239,
"data": -0.0036997 
},
{
 "dates":    240,
"data": -0.028489 
},
{
 "dates":    241,
"data": 0.022906 
},
{
 "dates":    242,
"data": 0.016091 
},
{
 "dates":    243,
"data": -0.040993 
},
{
 "dates":    244,
"data": 0.018761 
},
{
 "dates":    245,
"data": 0.001135 
},
{
 "dates":    246,
"data": 0.0044681 
},
{
 "dates":    247,
"data": 0.0014373 
},
{
 "dates":    248,
"data": -0.026807 
},
{
 "dates":    249,
"data": -0.014627 
},
{
 "dates":    250,
"data": -0.024213 
},
{
 "dates":    251,
"data": 0.029442 
},
{
 "dates":    252,
"data": 0.033157 
},
{
 "dates":    253,
"data": -0.040691 
},
{
 "dates":    254,
"data": -0.024268 
},
{
 "dates":    255,
"data": 0.0008515 
},
{
 "dates":    256,
"data": 0.031797 
},
{
 "dates":    257,
"data": -0.031089 
},
{
 "dates":    258,
"data": 0.018369 
},
{
 "dates":    259,
"data": 0.067402 
},
{
 "dates":    260,
"data": -0.070522 
},
{
 "dates":    261,
"data": -0.022857 
},
{
 "dates":    262,
"data": 0.001188 
},
{
 "dates":    263,
"data": 0.028781 
},
{
 "dates":    264,
"data": -0.029436 
},
{
 "dates":    265,
"data": 0.10129 
},
{
 "dates":    266,
"data": -0.027527 
},
{
 "dates":    267,
"data": 0.014264 
},
{
 "dates":    268,
"data": -0.057339 
},
{
 "dates":    269,
"data": -0.0345 
},
{
 "dates":    270,
"data": 0.059906 
},
{
 "dates":    271,
"data": -0.0053747 
},
{
 "dates":    272,
"data": 0.003456 
},
{
 "dates":    273,
"data": -0.026813 
},
{
 "dates":    274,
"data": 0.010502 
},
{
 "dates":    275,
"data": -0.0026203 
},
{
 "dates":    276,
"data": -0.015789 
},
{
 "dates":    277,
"data": 0.025115 
},
{
 "dates":    278,
"data": -0.0025377 
},
{
 "dates":    279,
"data": 0.0071107 
},
{
 "dates":    280,
"data": -0.027751 
},
{
 "dates":    281,
"data": 0.034391 
},
{
 "dates":    282,
"data": -0.046172 
},
{
 "dates":    283,
"data": 0.086348 
},
{
 "dates":    284,
"data": -0.065828 
},
{
 "dates":    285,
"data": 0.022933 
},
{
 "dates":    286,
"data": 0.0020444 
},
{
 "dates":    287,
"data": -0.0038432 
},
{
 "dates":    288,
"data": -0.028246 
},
{
 "dates":    289,
"data": 0.060805 
},
{
 "dates":    290,
"data": 0.014526 
},
{
 "dates":    291,
"data": -0.044454 
},
{
 "dates":    292,
"data": -0.0098636 
},
{
 "dates":    293,
"data": -0.00064244 
},
{
 "dates":    294,
"data": 0.02235 
},
{
 "dates":    295,
"data": -0.091899 
},
{
 "dates":    296,
"data": 0.072086 
},
{
 "dates":    297,
"data": -0.067654 
},
{
 "dates":    298,
"data": 0.07702 
},
{
 "dates":    299,
"data": 0.044655 
},
{
 "dates":    300,
"data": -0.018863 
},
{
 "dates":    301,
"data": -0.042094 
},
{
 "dates":    302,
"data": 0.036764 
},
{
 "dates":    303,
"data": -0.0059149 
},
{
 "dates":    304,
"data": -0.026891 
},
{
 "dates":    305,
"data": -0.024356 
},
{
 "dates":    306,
"data": 0.0072308 
},
{
 "dates":    307,
"data": 0.079585 
},
{
 "dates":    308,
"data": -0.093584 
},
{
 "dates":    309,
"data": 0.068289 
},
{
 "dates":    310,
"data": 0.01026 
},
{
 "dates":    311,
"data": 0.03036 
},
{
 "dates":    312,
"data": -0.013331 
},
{
 "dates":    313,
"data": -0.036733 
},
{
 "dates":    314,
"data": 0.05912 
},
{
 "dates":    315,
"data": -0.043847 
},
{
 "dates":    316,
"data": 0.02773 
},
{
 "dates":    317,
"data": -0.06219 
},
{
 "dates":    318,
"data": 0.016429 
},
{
 "dates":    319,
"data": -0.017185 
},
{
 "dates":    320,
"data": 0.073566 
},
{
 "dates":    321,
"data": -0.038276 
},
{
 "dates":    322,
"data": 0.025241 
},
{
 "dates":    323,
"data": -0.0046089 
},
{
 "dates":    324,
"data": -0.070204 
},
{
 "dates":    325,
"data": 0.0013497 
},
{
 "dates":    326,
"data": 0.093046 
},
{
 "dates":    327,
"data": -0.0184 
},
{
 "dates":    328,
"data": -0.031245 
},
{
 "dates":    329,
"data": 0.069285 
},
{
 "dates":    330,
"data": -0.055499 
},
{
 "dates":    331,
"data": -0.017846 
},
{
 "dates":    332,
"data": 0.00048134 
},
{
 "dates":    333,
"data": 0.018955 
},
{
 "dates":    334,
"data": 0.0059829 
},
{
 "dates":    335,
"data": 0.026697 
},
{
 "dates":    336,
"data": -0.01683 
},
{
 "dates":    337,
"data": -0.034876 
},
{
 "dates":    338,
"data": 0.029535 
},
{
 "dates":    339,
"data": 0.049558 
},
{
 "dates":    340,
"data": -0.022961 
},
{
 "dates":    341,
"data": -0.028282 
},
{
 "dates":    342,
"data": -0.01657 
},
{
 "dates":    343,
"data": 0.075797 
},
{
 "dates":    344,
"data": -0.0071845 
},
{
 "dates":    345,
"data": -0.088897 
},
{
 "dates":    346,
"data": 0.028914 
},
{
 "dates":    347,
"data": 0.069277 
},
{
 "dates":    348,
"data": -0.11825 
},
{
 "dates":    349,
"data": 0.1116 
},
{
 "dates":    350,
"data": -0.048781 
},
{
 "dates":    351,
"data": -0.0080852 
},
{
 "dates":    352,
"data": 0.025571 
},
{
 "dates":    353,
"data": 0.015598 
},
{
 "dates":    354,
"data": -0.047428 
},
{
 "dates":    355,
"data": 0.0075514 
},
{
 "dates":    356,
"data": -0.0066693 
},
{
 "dates":    357,
"data": 0.056486 
},
{
 "dates":    358,
"data": 0.019384 
},
{
 "dates":    359,
"data": -0.01108 
},
{
 "dates":    360,
"data": -0.042209 
},
{
 "dates":    361,
"data": 0.042008 
},
{
 "dates":    362,
"data": 0.031303 
},
{
 "dates":    363,
"data": -0.033047 
},
{
 "dates":    364,
"data": 0.025371 
},
{
 "dates":    365,
"data": 0.038977 
},
{
 "dates":    366,
"data": -0.11133 
},
{
 "dates":    367,
"data": 0.046471 
},
{
 "dates":    368,
"data": -0.065533 
},
{
 "dates":    369,
"data": 0.03334 
},
{
 "dates":    370,
"data": 0.024729 
},
{
 "dates":    371,
"data": -0.052804 
},
{
 "dates":    372,
"data": 0.093427 
},
{
 "dates":    373,
"data": 0.0077963 
},
{
 "dates":    374,
"data": -0.085481 
},
{
 "dates":    375,
"data": 0.10293 
},
{
 "dates":    376,
"data": -0.012497 
},
{
 "dates":    377,
"data": -0.00080637 
},
{
 "dates":    378,
"data": -0.039532 
},
{
 "dates":    379,
"data": 0.022812 
},
{
 "dates":    380,
"data": -0.045218 
},
{
 "dates":    381,
"data": 0.033699 
},
{
 "dates":    382,
"data": 0.047071 
},
{
 "dates":    383,
"data": -0.066771 
},
{
 "dates":    384,
"data": 0.030216 
},
{
 "dates":    385,
"data": 0.048158 
},
{
 "dates":    386,
"data": 0.0043055 
},
{
 "dates":    387,
"data": -0.081395 
},
{
 "dates":    388,
"data": 0.074298 
},
{
 "dates":    389,
"data": -0.052931 
},
{
 "dates":    390,
"data": 0.031262 
},
{
 "dates":    391,
"data": 0.025332 
},
{
 "dates":    392,
"data": 0.012638 
},
{
 "dates":    393,
"data": -0.061674 
},
{
 "dates":    394,
"data": 0.030332 
},
{
 "dates":    395,
"data": -0.0097513 
},
{
 "dates":    396,
"data": 0.014849 
},
{
 "dates":    397,
"data": 0.015931 
},
{
 "dates":    398,
"data": -0.0024126 
},
{
 "dates":    399,
"data": -0.027187 
},
{
 "dates":    400,
"data": 0.045438 
},
{
 "dates":    401,
"data": -0.0077644 
},
{
 "dates":    402,
"data": -0.014771 
},
{
 "dates":    403,
"data": -0.035028 
},
{
 "dates":    404,
"data": 0.059495 
},
{
 "dates":    405,
"data": -0.10637 
},
{
 "dates":    406,
"data": 0.090888 
},
{
 "dates":    407,
"data": -0.028322 
},
{
 "dates":    408,
"data": -0.00078613 
},
{
 "dates":    409,
"data": 0.036869 
},
{
 "dates":    410,
"data": -0.042909 
},
{
 "dates":    411,
"data": 0.013754 
},
{
 "dates":    412,
"data": 0.031643 
},
{
 "dates":    413,
"data": -0.010856 
},
{
 "dates":    414,
"data": 0.06199 
},
{
 "dates":    415,
"data": -0.029742 
},
{
 "dates":    416,
"data": -0.028588 
},
{
 "dates":    417,
"data": 0.042791 
},
{
 "dates":    418,
"data": -0.055915 
},
{
 "dates":    419,
"data": 0.0010118 
},
{
 "dates":    420,
"data": 0.074918 
},
{
 "dates":    421,
"data": -0.041611 
},
{
 "dates":    422,
"data": -0.0065347 
},
{
 "dates":    423,
"data": -0.069542 
},
{
 "dates":    424,
"data": 0.071284 
},
{
 "dates":    425,
"data": -0.027618 
},
{
 "dates":    426,
"data": -0.0039749 
},
{
 "dates":    427,
"data": 0.026796 
},
{
 "dates":    428,
"data": 0.0021819 
},
{
 "dates":    429,
"data": 0.039697 
},
{
 "dates":    430,
"data": -0.044223 
},
{
 "dates":    431,
"data": 0.0032299 
},
{
 "dates":    432,
"data": -0.033466 
},
{
 "dates":    433,
"data": 0.069193 
},
{
 "dates":    434,
"data": -0.032 
},
{
 "dates":    435,
"data": 0.019981 
},
{
 "dates":    436,
"data": -0.018949 
},
{
 "dates":    437,
"data": -0.045871 
},
{
 "dates":    438,
"data": 0.070151 
},
{
 "dates":    439,
"data": -0.024634 
},
{
 "dates":    440,
"data": 0.01286 
},
{
 "dates":    441,
"data": 0.013668 
},
{
 "dates":    442,
"data": -0.00049867 
},
{
 "dates":    443,
"data": -0.11141 
},
{
 "dates":    444,
"data": 0.09784 
},
{
 "dates":    445,
"data": -0.017398 
},
{
 "dates":    446,
"data": 0.0034533 
},
{
 "dates":    447,
"data": -0.008742 
},
{
 "dates":    448,
"data": 0.0016245 
},
{
 "dates":    449,
"data": -0.04578 
},
{
 "dates":    450,
"data": 0.081696 
},
{
 "dates":    451,
"data": 0.025866 
},
{
 "dates":    452,
"data": -0.036996 
},
{
 "dates":    453,
"data": -0.0016002 
},
{
 "dates":    454,
"data": -0.021972 
},
{
 "dates":    455,
"data": 0.0073438 
},
{
 "dates":    456,
"data": 0.016344 
},
{
 "dates":    457,
"data": -0.011782 
},
{
 "dates":    458,
"data": 0.01391 
},
{
 "dates":    459,
"data": -0.028658 
},
{
 "dates":    460,
"data": -0.035478 
},
{
 "dates":    461,
"data": 0.055086 
},
{
 "dates":    462,
"data": -0.0049759 
},
{
 "dates":    463,
"data": -0.0015434 
},
{
 "dates":    464,
"data": -0.039138 
},
{
 "dates":    465,
"data": 0.033246 
},
{
 "dates":    466,
"data": 0.013701 
},
{
 "dates":    467,
"data": -0.021366 
},
{
 "dates":    468,
"data": 0.014371 
},
{
 "dates":    469,
"data": 0.013975 
},
{
 "dates":    470,
"data": 0.0023559 
},
{
 "dates":    471,
"data": -0.00076836 
},
{
 "dates":    472,
"data": -0.020679 
},
{
 "dates":    473,
"data": 0.024335 
},
{
 "dates":    474,
"data": 0.016443 
},
{
 "dates":    475,
"data": -0.00050692 
},
{
 "dates":    476,
"data": -0.0046508 
},
{
 "dates":    477,
"data": -0.024338 
},
{
 "dates":    478,
"data": 0.015591 
},
{
 "dates":    479,
"data": 0.044267 
},
{
 "dates":    480,
"data": -0.0207 
},
{
 "dates":    481,
"data": -0.027155 
},
{
 "dates":    482,
"data": -0.0051267 
},
{
 "dates":    483,
"data": 0.037322 
},
{
 "dates":    484,
"data": -0.024958 
},
{
 "dates":    485,
"data": -0.023708 
},
{
 "dates":    486,
"data": -0.021819 
},
{
 "dates":    487,
"data": 0.030656 
},
{
 "dates":    488,
"data": -0.010655 
},
{
 "dates":    489,
"data": -0.016161 
},
{
 "dates":    490,
"data": -0.037593 
},
{
 "dates":    491,
"data": 0.062922 
},
{
 "dates":    492,
"data": -0.026784 
},
{
 "dates":    493,
"data": 0.055913 
},
{
 "dates":    494,
"data": -0.058244 
},
{
 "dates":    495,
"data": -0.011322 
},
{
 "dates":    496,
"data": 0.033684 
},
{
 "dates":    497,
"data": -0.022165 
},
{
 "dates":    498,
"data": -0.011136 
},
{
 "dates":    499,
"data": 0.02363 
},
{
 "dates":    500,
"data": -0.046935 
},
{
 "dates":    501,
"data": 0.065723 
},
{
 "dates":    502,
"data": 0.017828 
},
{
 "dates":    503,
"data": -0.024712 
},
{
 "dates":    504,
"data": 0.047215 
},
{
 "dates":    505,
"data": -0.086715 
},
{
 "dates":    506,
"data": 0.046285 
},
{
 "dates":    507,
"data": -0.022791 
},
{
 "dates":    508,
"data": 0.007957 
},
{
 "dates":    509,
"data": -0.0080329 
},
{
 "dates":    510,
"data": 0.021556 
},
{
 "dates":    511,
"data": -0.019026 
},
{
 "dates":    512,
"data": 0.02032 
},
{
 "dates":    513,
"data": -0.05777 
},
{
 "dates":    514,
"data": -0.025185 
},
{
 "dates":    515,
"data": 0.027651 
},
{
 "dates":    516,
"data": 0.046303 
},
{
 "dates":    517,
"data": 0.032511 
},
{
 "dates":    518,
"data": -0.073158 
},
{
 "dates":    519,
"data": 0.095989 
},
{
 "dates":    520,
"data": -0.07803 
},
{
 "dates":    521,
"data": -0.0078072 
},
{
 "dates":    522,
"data": 0.087499 
},
{
 "dates":    523,
"data": -0.15251 
},
{
 "dates":    524,
"data": 0.041147 
},
{
 "dates":    525,
"data": -0.014922 
},
{
 "dates":    526,
"data": 0.0041686 
},
{
 "dates":    527,
"data": -0.032293 
},
{
 "dates":    528,
"data": 0.10301 
},
{
 "dates":    529,
"data": -0.061185 
},
{
 "dates":    530,
"data": 0.02349 
},
{
 "dates":    531,
"data": -0.023856 
},
{
 "dates":    532,
"data": -0.013883 
},
{
 "dates":    533,
"data": 0.053676 
},
{
 "dates":    534,
"data": -0.035417 
},
{
 "dates":    535,
"data": -0.0037049 
},
{
 "dates":    536,
"data": -0.00076241 
},
{
 "dates":    537,
"data": 0.073636 
},
{
 "dates":    538,
"data": -0.056212 
},
{
 "dates":    539,
"data": -0.01393 
},
{
 "dates":    540,
"data": -0.0099185 
},
{
 "dates":    541,
"data": 0.047594 
},
{
 "dates":    542,
"data": -0.042435 
},
{
 "dates":    543,
"data": 0.018099 
},
{
 "dates":    544,
"data": -0.031049 
},
{
 "dates":    545,
"data": 0.054884 
},
{
 "dates":    546,
"data": -0.042142 
},
{
 "dates":    547,
"data": 0.029058 
},
{
 "dates":    548,
"data": 0.0042659 
},
{
 "dates":    549,
"data": 0.016787 
},
{
 "dates":    550,
"data": -0.051331 
},
{
 "dates":    551,
"data": 0.031821 
},
{
 "dates":    552,
"data": -0.02457 
},
{
 "dates":    553,
"data": -0.021408 
},
{
 "dates":    554,
"data": 0.059236 
},
{
 "dates":    555,
"data": -0.081151 
},
{
 "dates":    556,
"data": 0.014721 
},
{
 "dates":    557,
"data": 0.018568 
},
{
 "dates":    558,
"data": -0.0051169 
},
{
 "dates":    559,
"data": -0.0333 
},
{
 "dates":    560,
"data": 0.059906 
},
{
 "dates":    561,
"data": -0.049744 
},
{
 "dates":    562,
"data": 0.0069614 
},
{
 "dates":    563,
"data": 0.015674 
},
{
 "dates":    564,
"data": 0.012867 
},
{
 "dates":    565,
"data": -0.015829 
},
{
 "dates":    566,
"data": 0.038126 
},
{
 "dates":    567,
"data": -0.043577 
},
{
 "dates":    568,
"data": 0.027324 
},
{
 "dates":    569,
"data": -0.067433 
},
{
 "dates":    570,
"data": 0.039411 
},
{
 "dates":    571,
"data": -0.039695 
},
{
 "dates":    572,
"data": 0.07241 
},
{
 "dates":    573,
"data": -0.0011121 
},
{
 "dates":    574,
"data": -0.068097 
},
{
 "dates":    575,
"data": 0.018365 
},
{
 "dates":    576,
"data": 0.0060025 
},
{
 "dates":    577,
"data": 0.079645 
},
{
 "dates":    578,
"data": -0.072234 
},
{
 "dates":    579,
"data": -0.042617 
},
{
 "dates":    580,
"data": 0.04692 
},
{
 "dates":    581,
"data": 0.0144 
},
{
 "dates":    582,
"data": -0.0058197 
},
{
 "dates":    583,
"data": -0.0022394 
},
{
 "dates":    584,
"data": -0.027019 
},
{
 "dates":    585,
"data": -0.028938 
},
{
 "dates":    586,
"data": 0.046551 
},
{
 "dates":    587,
"data": -0.0010846 
},
{
 "dates":    588,
"data": -0.01476 
},
{
 "dates":    589,
"data": 0.03526 
},
{
 "dates":    590,
"data": -0.04366 
},
{
 "dates":    591,
"data": 0.035475 
},
{
 "dates":    592,
"data": 0.0086062 
},
{
 "dates":    593,
"data": -0.03374 
},
{
 "dates":    594,
"data": 0.019372 
},
{
 "dates":    595,
"data": -0.013775 
},
{
 "dates":    596,
"data": -0.058976 
},
{
 "dates":    597,
"data": 0.029818 
},
{
 "dates":    598,
"data": 0.01898 
},
{
 "dates":    599,
"data": -0.020277 
},
{
 "dates":    600,
"data": -0.02047 
},
{
 "dates":    601,
"data": 0.096381 
},
{
 "dates":    602,
"data": 0.016655 
},
{
 "dates":    603,
"data": -0.10225 
},
{
 "dates":    604,
"data": 0.010676 
},
{
 "dates":    605,
"data": 0.040766 
},
{
 "dates":    606,
"data": -0.014105 
},
{
 "dates":    607,
"data": 0.018377 
},
{
 "dates":    608,
"data": -0.014999 
},
{
 "dates":    609,
"data": -0.035851 
},
{
 "dates":    610,
"data": 0.061406 
},
{
 "dates":    611,
"data": -0.037646 
},
{
 "dates":    612,
"data": -0.058673 
},
{
 "dates":    613,
"data": 0.012593 
},
{
 "dates":    614,
"data": 0.012075 
},
{
 "dates":    615,
"data": 0.053829 
},
{
 "dates":    616,
"data": -0.019915 
},
{
 "dates":    617,
"data": 0.037182 
},
{
 "dates":    618,
"data": -0.040699 
},
{
 "dates":    619,
"data": -0.0088606 
},
{
 "dates":    620,
"data": 0.016984 
},
{
 "dates":    621,
"data": -0.043204 
},
{
 "dates":    622,
"data": 0.054555 
},
{
 "dates":    623,
"data": 0.0032956 
},
{
 "dates":    624,
"data": -0.020514 
},
{
 "dates":    625,
"data": -0.018048 
},
{
 "dates":    626,
"data": 0.068372 
},
{
 "dates":    627,
"data": -0.097825 
},
{
 "dates":    628,
"data": 0.070369 
},
{
 "dates":    629,
"data": -0.032102 
},
{
 "dates":    630,
"data": -0.075399 
},
{
 "dates":    631,
"data": 0.072309 
},
{
 "dates":    632,
"data": -0.001611 
},
{
 "dates":    633,
"data": 0.063043 
},
{
 "dates":    634,
"data": -0.017378 
},
{
 "dates":    635,
"data": -0.028649 
},
{
 "dates":    636,
"data": 0.0017345 
},
{
 "dates":    637,
"data": 0.037047 
},
{
 "dates":    638,
"data": -0.015717 
},
{
 "dates":    639,
"data": 0.0065389 
},
{
 "dates":    640,
"data": -0.056909 
},
{
 "dates":    641,
"data": 0.065079 
},
{
 "dates":    642,
"data": -0.076905 
},
{
 "dates":    643,
"data": 0.011523 
},
{
 "dates":    644,
"data": 0.0057425 
},
{
 "dates":    645,
"data": 0.045082 
},
{
 "dates":    646,
"data": 0.0022057 
},
{
 "dates":    647,
"data": -0.014038 
},
{
 "dates":    648,
"data": 0.046685 
},
{
 "dates":    649,
"data": -0.058811 
},
{
 "dates":    650,
"data": -0.022522 
},
{
 "dates":    651,
"data": -0.011012 
},
{
 "dates":    652,
"data": 0.023421 
},
{
 "dates":    653,
"data": -0.0098701 
},
{
 "dates":    654,
"data": 0.0096689 
},
{
 "dates":    655,
"data": 0.052042 
},
{
 "dates":    656,
"data": -0.04554 
},
{
 "dates":    657,
"data": -0.016708 
},
{
 "dates":    658,
"data": 0.048158 
},
{
 "dates":    659,
"data": -0.041205 
},
{
 "dates":    660,
"data": 0.015592 
},
{
 "dates":    661,
"data": 0.043533 
},
{
 "dates":    662,
"data": -0.068995 
},
{
 "dates":    663,
"data": 0.021017 
},
{
 "dates":    664,
"data": 0.020893 
},
{
 "dates":    665,
"data": -0.049999 
},
{
 "dates":    666,
"data": 0.0036411 
},
{
 "dates":    667,
"data": 0.026814 
},
{
 "dates":    668,
"data": 0.036291 
},
{
 "dates":    669,
"data": -0.07283 
},
{
 "dates":    670,
"data": 0.026188 
},
{
 "dates":    671,
"data": 0.027748 
},
{
 "dates":    672,
"data": -0.042581 
},
{
 "dates":    673,
"data": 0.033689 
},
{
 "dates":    674,
"data": 0.0040758 
},
{
 "dates":    675,
"data": -0.03132 
},
{
 "dates":    676,
"data": 0.074936 
},
{
 "dates":    677,
"data": -0.081287 
},
{
 "dates":    678,
"data": 0.032413 
},
{
 "dates":    679,
"data": 0.01256 
},
{
 "dates":    680,
"data": -0.014673 
},
{
 "dates":    681,
"data": -0.014389 
},
{
 "dates":    682,
"data": -0.032288 
},
{
 "dates":    683,
"data": 0.11215 
},
{
 "dates":    684,
"data": -0.081263 
},
{
 "dates":    685,
"data": 0.029813 
},
{
 "dates":    686,
"data": 0.025844 
},
{
 "dates":    687,
"data": -0.023447 
},
{
 "dates":    688,
"data": 0.010615 
},
{
 "dates":    689,
"data": 0.025434 
},
{
 "dates":    690,
"data": -0.015646 
},
{
 "dates":    691,
"data": -0.0453 
},
{
 "dates":    692,
"data": 0.024415 
},
{
 "dates":    693,
"data": 0.037423 
},
{
 "dates":    694,
"data": -0.058071 
},
{
 "dates":    695,
"data": 0.0063989 
},
{
 "dates":    696,
"data": 0.008993 
},
{
 "dates":    697,
"data": -0.012711 
},
{
 "dates":    698,
"data": 0.076238 
},
{
 "dates":    699,
"data": 0.00049403 
},
{
 "dates":    700,
"data": -0.039843 
},
{
 "dates":    701,
"data": -0.033743 
},
{
 "dates":    702,
"data": 0.043156 
},
{
 "dates":    703,
"data": 0.012286 
},
{
 "dates":    704,
"data": 0.018051 
},
{
 "dates":    705,
"data": -0.052157 
},
{
 "dates":    706,
"data": 0.03045 
},
{
 "dates":    707,
"data": -0.031811 
},
{
 "dates":    708,
"data": 0.033061 
},
{
 "dates":    709,
"data": -0.027746 
},
{
 "dates":    710,
"data": 0.074575 
},
{
 "dates":    711,
"data": -0.02279 
},
{
 "dates":    712,
"data": 0.011054 
},
{
 "dates":    713,
"data": -0.016135 
},
{
 "dates":    714,
"data": 0.022298 
},
{
 "dates":    715,
"data": 0.00096143 
},
{
 "dates":    716,
"data": -0.023006 
},
{
 "dates":    717,
"data": -0.043346 
},
{
 "dates":    718,
"data": 0.10286 
},
{
 "dates":    719,
"data": -0.073347 
},
{
 "dates":    720,
"data": 0.02119 
},
{
 "dates":    721,
"data": 0.019321 
},
{
 "dates":    722,
"data": -0.036427 
},
{
 "dates":    723,
"data": -6.4499e-05 
},
{
 "dates":    724,
"data": 0.031603 
},
{
 "dates":    725,
"data": 0.0049494 
},
{
 "dates":    726,
"data": -0.051228 
},
{
 "dates":    727,
"data": 0.054657 
},
{
 "dates":    728,
"data": 0.019361 
},
{
 "dates":    729,
"data": -0.023197 
},
{
 "dates":    730,
"data": -0.0077064 
},
{
 "dates":    731,
"data": -0.02956 
},
{
 "dates":    732,
"data": -0.009985 
},
{
 "dates":    733,
"data": 0.01081 
},
{
 "dates":    734,
"data": 0.023805 
},
{
 "dates":    735,
"data": 0.048069 
},
{
 "dates":    736,
"data": -0.084816 
},
{
 "dates":    737,
"data": 0.093589 
},
{
 "dates":    738,
"data": 0.00046866 
},
{
 "dates":    739,
"data": -0.029957 
},
{
 "dates":    740,
"data": 0.018222 
},
{
 "dates":    741,
"data": -0.062708 
},
{
 "dates":    742,
"data": 0.055853 
},
{
 "dates":    743,
"data": 0.0034629 
},
{
 "dates":    744,
"data": -0.035807 
},
{
 "dates":    745,
"data": 0.059596 
},
{
 "dates":    746,
"data": 0.036747 
},
{
 "dates":    747,
"data": -0.054782 
},
{
 "dates":    748,
"data": -0.0054399 
},
{
 "dates":    749,
"data": -0.049761 
},
{
 "dates":    750,
"data": 0.10658 
},
{
 "dates":    751,
"data": -0.11499 
},
{
 "dates":    752,
"data": 0.042444 
},
{
 "dates":    753,
"data": -0.019589 
},
{
 "dates":    754,
"data": 0.063874 
},
{
 "dates":    755,
"data": -0.0042628 
},
{
 "dates":    756,
"data": -0.030742 
},
{
 "dates":    757,
"data": 0.013564 
},
{
 "dates":    758,
"data": 0.019931 
},
{
 "dates":    759,
"data": -0.014575 
},
{
 "dates":    760,
"data": -0.057692 
},
{
 "dates":    761,
"data": 0.07856 
},
{
 "dates":    762,
"data": -0.013767 
},
{
 "dates":    763,
"data": -0.0068877 
},
{
 "dates":    764,
"data": -0.013893 
},
{
 "dates":    765,
"data": 0.0038615 
},
{
 "dates":    766,
"data": 0.02152 
},
{
 "dates":    767,
"data": 0.031552 
},
{
 "dates":    768,
"data": -0.023973 
},
{
 "dates":    769,
"data": -0.035304 
},
{
 "dates":    770,
"data": 0.079889 
},
{
 "dates":    771,
"data": -0.049573 
},
{
 "dates":    772,
"data": -0.096212 
},
{
 "dates":    773,
"data": 0.093182 
},
{
 "dates":    774,
"data": 0.017318 
},
{
 "dates":    775,
"data": 0.00032651 
},
{
 "dates":    776,
"data": -0.00676 
},
{
 "dates":    777,
"data": -0.022702 
},
{
 "dates":    778,
"data": 0.04123 
},
{
 "dates":    779,
"data": -0.015251 
},
{
 "dates":    780,
"data": -0.00013358 
},
{
 "dates":    781,
"data": 0.027321 
},
{
 "dates":    782,
"data": -0.041214 
},
{
 "dates":    783,
"data": 0.036205 
},
{
 "dates":    784,
"data": -0.01053 
},
{
 "dates":    785,
"data": -0.016497 
},
{
 "dates":    786,
"data": 0.02314 
},
{
 "dates":    787,
"data": -0.034852 
},
{
 "dates":    788,
"data": -0.012487 
},
{
 "dates":    789,
"data": 0.037758 
},
{
 "dates":    790,
"data": 0.015909 
},
{
 "dates":    791,
"data": -0.023933 
},
{
 "dates":    792,
"data": -0.012171 
},
{
 "dates":    793,
"data": 0.04972 
},
{
 "dates":    794,
"data": -0.0022852 
},
{
 "dates":    795,
"data": -0.030439 
},
{
 "dates":    796,
"data": 0.041316 
},
{
 "dates":    797,
"data": -0.020765 
},
{
 "dates":    798,
"data": -0.071872 
},
{
 "dates":    799,
"data": 0.07114 
},
{
 "dates":    800,
"data": -0.044989 
},
{
 "dates":    801,
"data": 0.099848 
},
{
 "dates":    802,
"data": -0.020321 
},
{
 "dates":    803,
"data": -0.041627 
},
{
 "dates":    804,
"data": -0.018677 
},
{
 "dates":    805,
"data": -0.0072657 
},
{
 "dates":    806,
"data": -0.0049312 
},
{
 "dates":    807,
"data": 0.09357 
},
{
 "dates":    808,
"data": -0.054757 
},
{
 "dates":    809,
"data": -0.038906 
},
{
 "dates":    810,
"data": 0.10683 
},
{
 "dates":    811,
"data": -0.072451 
},
{
 "dates":    812,
"data": -0.11783 
},
{
 "dates":    813,
"data": 0.12504 
},
{
 "dates":    814,
"data": 0.0024522 
},
{
 "dates":    815,
"data": 0.042632 
},
{
 "dates":    816,
"data": -0.027838 
},
{
 "dates":    817,
"data": -0.033544 
},
{
 "dates":    818,
"data": 0.037309 
},
{
 "dates":    819,
"data": -0.067842 
},
{
 "dates":    820,
"data": 0.032336 
},
{
 "dates":    821,
"data": -0.010227 
},
{
 "dates":    822,
"data": 0.033292 
},
{
 "dates":    823,
"data": -0.0049572 
},
{
 "dates":    824,
"data": -0.024892 
},
{
 "dates":    825,
"data": -0.0025102 
},
{
 "dates":    826,
"data": -0.013313 
},
{
 "dates":    827,
"data": 0.012952 
},
{
 "dates":    828,
"data": 0.014048 
},
{
 "dates":    829,
"data": -0.016366 
},
{
 "dates":    830,
"data": 0.022055 
},
{
 "dates":    831,
"data": 0.011563 
},
{
 "dates":    832,
"data": -0.054794 
},
{
 "dates":    833,
"data": 0.039845 
},
{
 "dates":    834,
"data": 0.018836 
},
{
 "dates":    835,
"data": -0.01702 
},
{
 "dates":    836,
"data": 0.047532 
},
{
 "dates":    837,
"data": -0.016229 
},
{
 "dates":    838,
"data": -0.011748 
},
{
 "dates":    839,
"data": 0.022035 
},
{
 "dates":    840,
"data": -0.1016 
},
{
 "dates":    841,
"data": 0.069476 
},
{
 "dates":    842,
"data": -0.0044491 
},
{
 "dates":    843,
"data": -0.015788 
},
{
 "dates":    844,
"data": 0.040274 
},
{
 "dates":    845,
"data": -0.023125 
},
{
 "dates":    846,
"data": -0.011453 
},
{
 "dates":    847,
"data": 0.0054707 
},
{
 "dates":    848,
"data": 0.044675 
},
{
 "dates":    849,
"data": -0.025524 
},
{
 "dates":    850,
"data": 0.023346 
},
{
 "dates":    851,
"data": -0.042131 
},
{
 "dates":    852,
"data": -0.0367 
},
{
 "dates":    853,
"data": 0.036102 
},
{
 "dates":    854,
"data": 0.0082024 
},
{
 "dates":    855,
"data": -0.035633 
},
{
 "dates":    856,
"data": -0.041357 
},
{
 "dates":    857,
"data": 0.083528 
},
{
 "dates":    858,
"data": -0.10193 
},
{
 "dates":    859,
"data": 0.088172 
},
{
 "dates":    860,
"data": -0.018281 
},
{
 "dates":    861,
"data": -0.0025952 
},
{
 "dates":    862,
"data": 0.018417 
},
{
 "dates":    863,
"data": -0.019408 
},
{
 "dates":    864,
"data": -0.0053721 
},
{
 "dates":    865,
"data": 0.0063497 
},
{
 "dates":    866,
"data": 0.023393 
},
{
 "dates":    867,
"data": 0.012427 
},
{
 "dates":    868,
"data": -0.088747 
},
{
 "dates":    869,
"data": 0.068599 
},
{
 "dates":    870,
"data": -0.024254 
},
{
 "dates":    871,
"data": -0.021035 
},
{
 "dates":    872,
"data": 0.078472 
},
{
 "dates":    873,
"data": -0.077544 
},
{
 "dates":    874,
"data": 0.066058 
},
{
 "dates":    875,
"data": -0.076054 
},
{
 "dates":    876,
"data": 0.08288 
},
{
 "dates":    877,
"data": 0.0027654 
},
{
 "dates":    878,
"data": -0.060493 
},
{
 "dates":    879,
"data": 0.030533 
},
{
 "dates":    880,
"data": 0.013938 
},
{
 "dates":    881,
"data": 0.0054362 
},
{
 "dates":    882,
"data": -0.032483 
},
{
 "dates":    883,
"data": -0.012933 
},
{
 "dates":    884,
"data": -0.0047772 
},
{
 "dates":    885,
"data": -0.010339 
},
{
 "dates":    886,
"data": 0.012528 
},
{
 "dates":    887,
"data": -0.0033613 
},
{
 "dates":    888,
"data": 0.037001 
},
{
 "dates":    889,
"data": -0.0091944 
},
{
 "dates":    890,
"data": -0.027971 
},
{
 "dates":    891,
"data": 0.007858 
},
{
 "dates":    892,
"data": 0.039653 
},
{
 "dates":    893,
"data": -0.031877 
},
{
 "dates":    894,
"data": 0.001147 
},
{
 "dates":    895,
"data": -0.029241 
},
{
 "dates":    896,
"data": 0.022825 
},
{
 "dates":    897,
"data": 0.012173 
},
{
 "dates":    898,
"data": -0.061437 
},
{
 "dates":    899,
"data": 0.034086 
},
{
 "dates":    900,
"data": -0.052112 
},
{
 "dates":    901,
"data": 0.13942 
},
{
 "dates":    902,
"data": -0.065908 
},
{
 "dates":    903,
"data": 0.021074 
},
{
 "dates":    904,
"data": -0.0086348 
},
{
 "dates":    905,
"data": -0.054361 
},
{
 "dates":    906,
"data": -0.014769 
},
{
 "dates":    907,
"data": -0.012699 
},
{
 "dates":    908,
"data": 0.095609 
},
{
 "dates":    909,
"data": -0.033028 
},
{
 "dates":    910,
"data": 0.020701 
},
{
 "dates":    911,
"data": -0.0090612 
},
{
 "dates":    912,
"data": -0.064579 
},
{
 "dates":    913,
"data": 0.04319 
},
{
 "dates":    914,
"data": -0.033465 
},
{
 "dates":    915,
"data": -0.00095554 
},
{
 "dates":    916,
"data": 0.073137 
},
{
 "dates":    917,
"data": -0.024155 
},
{
 "dates":    918,
"data": -0.01895 
},
{
 "dates":    919,
"data": -0.022599 
},
{
 "dates":    920,
"data": -0.0049694 
},
{
 "dates":    921,
"data": -0.021297 
},
{
 "dates":    922,
"data": 0.031602 
},
{
 "dates":    923,
"data": -0.016193 
},
{
 "dates":    924,
"data": 0.036694 
},
{
 "dates":    925,
"data": -0.013752 
},
{
 "dates":    926,
"data": -0.033637 
},
{
 "dates":    927,
"data": 0.057642 
},
{
 "dates":    928,
"data": -0.017856 
},
{
 "dates":    929,
"data": -0.02517 
},
{
 "dates":    930,
"data": 0.064779 
},
{
 "dates":    931,
"data": -0.053113 
},
{
 "dates":    932,
"data": -0.096019 
},
{
 "dates":    933,
"data": 0.060759 
},
{
 "dates":    934,
"data": 0.021881 
},
{
 "dates":    935,
"data": 0.030932 
},
{
 "dates":    936,
"data": -0.066741 
},
{
 "dates":    937,
"data": 0.040943 
},
{
 "dates":    938,
"data": 0.018309 
},
{
 "dates":    939,
"data": -0.029762 
},
{
 "dates":    940,
"data": 0.0023235 
},
{
 "dates":    941,
"data": -0.0031266 
},
{
 "dates":    942,
"data": -0.02585 
},
{
 "dates":    943,
"data": 0.024095 
},
{
 "dates":    944,
"data": 0.026498 
},
{
 "dates":    945,
"data": -0.070266 
},
{
 "dates":    946,
"data": 0.064649 
},
{
 "dates":    947,
"data": 0.0012456 
},
{
 "dates":    948,
"data": -0.0032777 
},
{
 "dates":    949,
"data": -0.027977 
},
{
 "dates":    950,
"data": 0.006028 
},
{
 "dates":    951,
"data": 0.0588 
},
{
 "dates":    952,
"data": -0.047739 
},
{
 "dates":    953,
"data": -0.030025 
},
{
 "dates":    954,
"data": 0.046745 
},
{
 "dates":    955,
"data": -0.078991 
},
{
 "dates":    956,
"data": 0.073643 
},
{
 "dates":    957,
"data": -0.049765 
},
{
 "dates":    958,
"data": 0.042828 
},
{
 "dates":    959,
"data": -0.030583 
},
{
 "dates":    960,
"data": 0.047837 
},
{
 "dates":    961,
"data": 0.04105 
},
{
 "dates":    962,
"data": -0.066298 
},
{
 "dates":    963,
"data": -0.020801 
},
{
 "dates":    964,
"data": -0.052767 
},
{
 "dates":    965,
"data": 0.10815 
},
{
 "dates":    966,
"data": -0.12415 
},
{
 "dates":    967,
"data": 0.081432 
},
{
 "dates":    968,
"data": -0.0092705 
},
{
 "dates":    969,
"data": 0.032387 
},
{
 "dates":    970,
"data": -0.061852 
},
{
 "dates":    971,
"data": 0.042772 
},
{
 "dates":    972,
"data": -0.044801 
},
{
 "dates":    973,
"data": 0.078361 
},
{
 "dates":    974,
"data": -0.05595 
},
{
 "dates":    975,
"data": -0.0049332 
},
{
 "dates":    976,
"data": 0.00053724 
},
{
 "dates":    977,
"data": -0.0074291 
},
{
 "dates":    978,
"data": -0.014238 
},
{
 "dates":    979,
"data": 0.082921 
},
{
 "dates":    980,
"data": -0.043569 
},
{
 "dates":    981,
"data": -0.035867 
},
{
 "dates":    982,
"data": 0.0010946 
},
{
 "dates":    983,
"data": 0.057315 
},
{
 "dates":    984,
"data": -0.043346 
},
{
 "dates":    985,
"data": -0.016603 
},
{
 "dates":    986,
"data": 0.042322 
},
{
 "dates":    987,
"data": -0.0067691 
},
{
 "dates":    988,
"data": -0.036041 
},
{
 "dates":    989,
"data": 0.079571 
},
{
 "dates":    990,
"data": -0.052233 
},
{
 "dates":    991,
"data": 0.024048 
},
{
 "dates":    992,
"data": -0.045967 
},
{
 "dates":    993,
"data": -0.033459 
},
{
 "dates":    994,
"data": 0.066422 
},
{
 "dates":    995,
"data": -0.044421 
},
{
 "dates":    996,
"data": 0.031401 
},
{
 "dates":    997,
"data": -0.032627 
},
{
 "dates":    998,
"data": 0.010749 
},
{
 "dates":    999,
"data": -0.002017 
},
{
 "dates":   1000,
"data": 0.047469 
},
{
 "dates":   1001,
"data": -0.031779 
},
{
 "dates":   1002,
"data": 0.035751 
},
{
 "dates":   1003,
"data": -0.039768 
},
{
 "dates":   1004,
"data": 0.01216 
},
{
 "dates":   1005,
"data": 0.04766 
},
{
 "dates":   1006,
"data": -0.017044 
},
{
 "dates":   1007,
"data": -0.0021397 
},
{
 "dates":   1008,
"data": 0.0087602 
},
{
 "dates":   1009,
"data": -0.048516 
},
{
 "dates":   1010,
"data": 0.053292 
},
{
 "dates":   1011,
"data": -0.028518 
},
{
 "dates":   1012,
"data": -0.015905 
},
{
 "dates":   1013,
"data": -0.0033699 
},
{
 "dates":   1014,
"data": -0.0024538 
},
{
 "dates":   1015,
"data": 0.05022 
},
{
 "dates":   1016,
"data": -0.015726 
},
{
 "dates":   1017,
"data": 0.049597 
},
{
 "dates":   1018,
"data": -0.059201 
},
{
 "dates":   1019,
"data": 0.010181 
},
{
 "dates":   1020,
"data": -0.050951 
},
{
 "dates":   1021,
"data": 0.055674 
},
{
 "dates":   1022,
"data": -0.028442 
},
{
 "dates":   1023,
"data": 0.069752 
},
{
 "dates":   1024,
"data": -0.095938 
},
{
 "dates":   1025,
"data": 0.015084 
},
{
 "dates":   1026,
"data": -0.0047518 
},
{
 "dates":   1027,
"data": 0.0025908 
},
{
 "dates":   1028,
"data": 0.021161 
},
{
 "dates":   1029,
"data": -0.016752 
},
{
 "dates":   1030,
"data": 0.013043 
},
{
 "dates":   1031,
"data": -0.032934 
},
{
 "dates":   1032,
"data": 0.003418 
},
{
 "dates":   1033,
"data": 0.043822 
},
{
 "dates":   1034,
"data": 0.0036936 
},
{
 "dates":   1035,
"data": -0.032183 
},
{
 "dates":   1036,
"data": 0.016726 
},
{
 "dates":   1037,
"data": 0.018594 
},
{
 "dates":   1038,
"data": 0.008121 
},
{
 "dates":   1039,
"data": -0.023385 
},
{
 "dates":   1040,
"data": -0.0029541 
},
{
 "dates":   1041,
"data": 0.009223 
},
{
 "dates":   1042,
"data": 0.010193 
},
{
 "dates":   1043,
"data": 0.016481 
},
{
 "dates":   1044,
"data": -0.018415 
},
{
 "dates":   1045,
"data": 0.074961 
},
{
 "dates":   1046,
"data": -0.057209 
},
{
 "dates":   1047,
"data": 0.0049191 
},
{
 "dates":   1048,
"data": -0.013917 
},
{
 "dates":   1049,
"data": 0.010492 
},
{
 "dates":   1050,
"data": 0.018561 
},
{
 "dates":   1051,
"data": 0.0050072 
},
{
 "dates":   1052,
"data": -0.04038 
},
{
 "dates":   1053,
"data": -0.026639 
},
{
 "dates":   1054,
"data": 0.094258 
},
{
 "dates":   1055,
"data": -0.037266 
},
{
 "dates":   1056,
"data": 0.005775 
},
{
 "dates":   1057,
"data": 0.011711 
},
{
 "dates":   1058,
"data": -0.019078 
},
{
 "dates":   1059,
"data": 0.0074034 
},
{
 "dates":   1060,
"data": -0.013569 
},
{
 "dates":   1061,
"data": 0.0001563 
},
{
 "dates":   1062,
"data": -0.026129 
},
{
 "dates":   1063,
"data": 0.00085958 
},
{
 "dates":   1064,
"data": 0.061982 
},
{
 "dates":   1065,
"data": -0.029658 
},
{
 "dates":   1066,
"data": -0.043059 
},
{
 "dates":   1067,
"data": 0.044909 
},
{
 "dates":   1068,
"data": -0.016688 
},
{
 "dates":   1069,
"data": 0.039742 
},
{
 "dates":   1070,
"data": -0.032743 
},
{
 "dates":   1071,
"data": 0.027352 
},
{
 "dates":   1072,
"data": 0.014503 
},
{
 "dates":   1073,
"data": -0.028231 
},
{
 "dates":   1074,
"data": 0.0092274 
},
{
 "dates":   1075,
"data": 0.0080705 
},
{
 "dates":   1076,
"data": -0.06653 
},
{
 "dates":   1077,
"data": 0.044628 
},
{
 "dates":   1078,
"data": -0.010069 
},
{
 "dates":   1079,
"data": 0.052675 
},
{
 "dates":   1080,
"data": -0.027896 
},
{
 "dates":   1081,
"data": 0.046907 
},
{
 "dates":   1082,
"data": -0.079385 
},
{
 "dates":   1083,
"data": 0.082258 
},
{
 "dates":   1084,
"data": -0.029435 
},
{
 "dates":   1085,
"data": -0.035959 
},
{
 "dates":   1086,
"data": 0.012449 
},
{
 "dates":   1087,
"data": 0.04242 
},
{
 "dates":   1088,
"data": -0.035017 
},
{
 "dates":   1089,
"data": -0.034857 
},
{
 "dates":   1090,
"data": 0.010249 
},
{
 "dates":   1091,
"data": 0.0049709 
},
{
 "dates":   1092,
"data": 0.041932 
},
{
 "dates":   1093,
"data": -0.0012986 
},
{
 "dates":   1094,
"data": -0.00041209 
},
{
 "dates":   1095,
"data": 0.0068 
},
{
 "dates":   1096,
"data": -0.054254 
},
{
 "dates":   1097,
"data": 0.091022 
},
{
 "dates":   1098,
"data": -0.07478 
},
{
 "dates":   1099,
"data": 0.026676 
},
{
 "dates":   1100,
"data": 6.4525e-05 
},
{
 "dates":   1101,
"data": 0.019633 
},
{
 "dates":   1102,
"data": 0.0035304 
},
{
 "dates":   1103,
"data": 0.00055791 
},
{
 "dates":   1104,
"data": -0.019006 
},
{
 "dates":   1105,
"data": -0.0038994 
},
{
 "dates":   1106,
"data": 0.019493 
},
{
 "dates":   1107,
"data": -0.046027 
},
{
 "dates":   1108,
"data": 0.081736 
},
{
 "dates":   1109,
"data": 0.026428 
},
{
 "dates":   1110,
"data": -0.045443 
},
{
 "dates":   1111,
"data": 0.026329 
},
{
 "dates":   1112,
"data": -0.020975 
},
{
 "dates":   1113,
"data": 0.0070419 
},
{
 "dates":   1114,
"data": -0.050969 
},
{
 "dates":   1115,
"data": 0.055529 
},
{
 "dates":   1116,
"data": -0.059706 
},
{
 "dates":   1117,
"data": 0.092271 
},
{
 "dates":   1118,
"data": -0.046417 
},
{
 "dates":   1119,
"data": -0.018405 
},
{
 "dates":   1120,
"data": -0.050546 
},
{
 "dates":   1121,
"data": 0.053934 
},
{
 "dates":   1122,
"data": 0.035675 
},
{
 "dates":   1123,
"data": 0.025591 
},
{
 "dates":   1124,
"data": 0.014123 
},
{
 "dates":   1125,
"data": -0.021461 
},
{
 "dates":   1126,
"data": -0.023879 
},
{
 "dates":   1127,
"data": -0.012163 
},
{
 "dates":   1128,
"data": -0.016633 
},
{
 "dates":   1129,
"data": 0.034802 
},
{
 "dates":   1130,
"data": -0.043688 
},
{
 "dates":   1131,
"data": 0.076005 
},
{
 "dates":   1132,
"data": -0.057479 
},
{
 "dates":   1133,
"data": 0.0050766 
},
{
 "dates":   1134,
"data": 0.0033987 
},
{
 "dates":   1135,
"data": -0.0030746 
},
{
 "dates":   1136,
"data": -0.013205 
},
{
 "dates":   1137,
"data": 0.052672 
},
{
 "dates":   1138,
"data": -0.016227 
},
{
 "dates":   1139,
"data": -0.054747 
},
{
 "dates":   1140,
"data": 0.053992 
},
{
 "dates":   1141,
"data": -0.0058781 
},
{
 "dates":   1142,
"data": 0.059019 
},
{
 "dates":   1143,
"data": -0.053768 
},
{
 "dates":   1144,
"data": 0.040407 
},
{
 "dates":   1145,
"data": -0.019894 
},
{
 "dates":   1146,
"data": 0.00069828 
},
{
 "dates":   1147,
"data": -0.057338 
},
{
 "dates":   1148,
"data": 0.027716 
},
{
 "dates":   1149,
"data": 0.024234 
},
{
 "dates":   1150,
"data": -0.011965 
},
{
 "dates":   1151,
"data": 0.042002 
},
{
 "dates":   1152,
"data": -0.057602 
},
{
 "dates":   1153,
"data": -0.0038968 
},
{
 "dates":   1154,
"data": 0.0086754 
},
{
 "dates":   1155,
"data": 0.061828 
},
{
 "dates":   1156,
"data": -0.069688 
},
{
 "dates":   1157,
"data": 0.02579 
},
{
 "dates":   1158,
"data": -0.038236 
},
{
 "dates":   1159,
"data": 0.035146 
},
{
 "dates":   1160,
"data": -0.037926 
},
{
 "dates":   1161,
"data": 0.014032 
},
{
 "dates":   1162,
"data": -0.03628 
},
{
 "dates":   1163,
"data": 0.07991 
},
{
 "dates":   1164,
"data": 0.033656 
},
{
 "dates":   1165,
"data": -0.042016 
},
{
 "dates":   1166,
"data": 0.0053951 
},
{
 "dates":   1167,
"data": 0.036982 
},
{
 "dates":   1168,
"data": -0.033948 
},
{
 "dates":   1169,
"data": 0.042953 
},
{
 "dates":   1170,
"data": -0.067884 
},
{
 "dates":   1171,
"data": 0.048256 
},
{
 "dates":   1172,
"data": -0.056354 
},
{
 "dates":   1173,
"data": 0.064608 
},
{
 "dates":   1174,
"data": -0.030085 
},
{
 "dates":   1175,
"data": -0.0092553 
},
{
 "dates":   1176,
"data": -0.0057414 
},
{
 "dates":   1177,
"data": 0.048174 
},
{
 "dates":   1178,
"data": -0.066247 
},
{
 "dates":   1179,
"data": 0.040353 
},
{
 "dates":   1180,
"data": -0.058731 
},
{
 "dates":   1181,
"data": 0.055539 
},
{
 "dates":   1182,
"data": -0.01323 
},
{
 "dates":   1183,
"data": 0.017196 
},
{
 "dates":   1184,
"data": -0.024492 
},
{
 "dates":   1185,
"data": 0.066819 
},
{
 "dates":   1186,
"data": -0.067811 
},
{
 "dates":   1187,
"data": 0.090795 
},
{
 "dates":   1188,
"data": -0.11043 
},
{
 "dates":   1189,
"data": 0.06279 
},
{
 "dates":   1190,
"data": -0.012169 
},
{
 "dates":   1191,
"data": -0.00018636 
},
{
 "dates":   1192,
"data": -0.010071 
},
{
 "dates":   1193,
"data": 0.029521 
},
{
 "dates":   1194,
"data": -0.087044 
},
{
 "dates":   1195,
"data": 0.043706 
},
{
 "dates":   1196,
"data": 0.089446 
},
{
 "dates":   1197,
"data": -0.010224 
},
{
 "dates":   1198,
"data": -0.052083 
},
{
 "dates":   1199,
"data": 0.024805 
},
{
 "dates":   1200,
"data": -0.031499 
},
{
 "dates":   1201,
"data": -0.06007 
},
{
 "dates":   1202,
"data": 0.056258 
},
{
 "dates":   1203,
"data": -0.0030804 
},
{
 "dates":   1204,
"data": 0.039139 
},
{
 "dates":   1205,
"data": -0.081408 
},
{
 "dates":   1206,
"data": 0.076818 
},
{
 "dates":   1207,
"data": -0.050067 
},
{
 "dates":   1208,
"data": 0.049375 
},
{
 "dates":   1209,
"data": -0.0082829 
},
{
 "dates":   1210,
"data": -0.029145 
},
{
 "dates":   1211,
"data": 0.056888 
},
{
 "dates":   1212,
"data": -0.070872 
},
{
 "dates":   1213,
"data": 0.020578 
},
{
 "dates":   1214,
"data": -0.034337 
},
{
 "dates":   1215,
"data": 0.015564 
},
{
 "dates":   1216,
"data": 0.026425 
},
{
 "dates":   1217,
"data": 0.0016317 
},
{
 "dates":   1218,
"data": -0.055394 
},
{
 "dates":   1219,
"data": 0.096912 
},
{
 "dates":   1220,
"data": -0.027071 
},
{
 "dates":   1221,
"data": -0.024042 
},
{
 "dates":   1222,
"data": 0.027571 
},
{
 "dates":   1223,
"data": -0.10858 
},
{
 "dates":   1224,
"data": 0.078481 
},
{
 "dates":   1225,
"data": 0.0024885 
},
{
 "dates":   1226,
"data": -0.0087818 
},
{
 "dates":   1227,
"data": -0.016959 
},
{
 "dates":   1228,
"data": 0.017413 
},
{
 "dates":   1229,
"data": 0.0297 
},
{
 "dates":   1230,
"data": 0.0082257 
},
{
 "dates":   1231,
"data": -0.018311 
},
{
 "dates":   1232,
"data": 0.01336 
},
{
 "dates":   1233,
"data": -0.05969 
},
{
 "dates":   1234,
"data": -0.0041796 
},
{
 "dates":   1235,
"data": -0.025518 
},
{
 "dates":   1236,
"data": 0.030965 
},
{
 "dates":   1237,
"data": -0.051053 
},
{
 "dates":   1238,
"data": 0.039319 
},
{
 "dates":   1239,
"data": 0.076807 
},
{
 "dates":   1240,
"data": -0.090579 
},
{
 "dates":   1241,
"data": 0.053341 
},
{
 "dates":   1242,
"data": -0.014099 
},
{
 "dates":   1243,
"data": -0.010395 
},
{
 "dates":   1244,
"data": 0.053949 
},
{
 "dates":   1245,
"data": -0.017457 
},
{
 "dates":   1246,
"data": -0.040376 
},
{
 "dates":   1247,
"data": 0.066143 
},
{
 "dates":   1248,
"data": -0.080179 
},
{
 "dates":   1249,
"data": 0.033815 
},
{
 "dates":   1250,
"data": 0.022027 
},
{
 "dates":   1251,
"data": -0.022101 
},
{
 "dates":   1252,
"data": 0.002602 
},
{
 "dates":   1253,
"data": -0.041244 
},
{
 "dates":   1254,
"data": 0.045995 
},
{
 "dates":   1255,
"data": -0.020776 
},
{
 "dates":   1256,
"data": -0.00082959 
},
{
 "dates":   1257,
"data": 0.034772 
},
{
 "dates":   1258,
"data": -0.035386 
},
{
 "dates":   1259,
"data": 0.016132 
},
{
 "dates":   1260,
"data": -0.067566 
},
{
 "dates":   1261,
"data": 0.049533 
},
{
 "dates":   1262,
"data": 0.018928 
},
{
 "dates":   1263,
"data": -0.030816 
},
{
 "dates":   1264,
"data": 0.011236 
},
{
 "dates":   1265,
"data": 0.014084 
},
{
 "dates":   1266,
"data": -0.024272 
},
{
 "dates":   1267,
"data": -0.00070695 
},
{
 "dates":   1268,
"data": -3.1673e-05 
},
{
 "dates":   1269,
"data": 0.016643 
},
{
 "dates":   1270,
"data": -0.033293 
},
{
 "dates":   1271,
"data": 0.008503 
},
{
 "dates":   1272,
"data": 0.052885 
},
{
 "dates":   1273,
"data": -0.0074052 
},
{
 "dates":   1274,
"data": -0.058277 
},
{
 "dates":   1275,
"data": 0.013861 
},
{
 "dates":   1276,
"data": -0.0099797 
},
{
 "dates":   1277,
"data": 0.047224 
},
{
 "dates":   1278,
"data": -0.026127 
},
{
 "dates":   1279,
"data": -0.043252 
},
{
 "dates":   1280,
"data": 0.024349 
},
{
 "dates":   1281,
"data": 0.046058 
},
{
 "dates":   1282,
"data": -0.026035 
},
{
 "dates":   1283,
"data": -0.028539 
},
{
 "dates":   1284,
"data": 0.05481 
},
{
 "dates":   1285,
"data": -0.048584 
},
{
 "dates":   1286,
"data": 0.03607 
},
{
 "dates":   1287,
"data": -0.0097869 
},
{
 "dates":   1288,
"data": -0.052618 
},
{
 "dates":   1289,
"data": 0.08807 
},
{
 "dates":   1290,
"data": -0.059813 
},
{
 "dates":   1291,
"data": 0.0060023 
},
{
 "dates":   1292,
"data": -0.046038 
},
{
 "dates":   1293,
"data": 0.0084182 
},
{
 "dates":   1294,
"data": 0.0064476 
},
{
 "dates":   1295,
"data": 0.00057537 
},
{
 "dates":   1296,
"data": 0.02792 
},
{
 "dates":   1297,
"data": -0.016712 
},
{
 "dates":   1298,
"data": 0.043631 
},
{
 "dates":   1299,
"data": -0.019794 
},
{
 "dates":   1300,
"data": -0.048446 
},
{
 "dates":   1301,
"data": 0.043799 
},
{
 "dates":   1302,
"data": -0.0098893 
},
{
 "dates":   1303,
"data": -0.0046309 
},
{
 "dates":   1304,
"data": 0.056056 
},
{
 "dates":   1305,
"data": -0.0252 
},
{
 "dates":   1306,
"data": -0.043597 
},
{
 "dates":   1307,
"data": 0.035669 
},
{
 "dates":   1308,
"data": -0.051059 
},
{
 "dates":   1309,
"data": 0.047677 
},
{
 "dates":   1310,
"data": -0.014561 
},
{
 "dates":   1311,
"data": 0.031169 
},
{
 "dates":   1312,
"data": -0.044595 
},
{
 "dates":   1313,
"data": 0.030482 
},
{
 "dates":   1314,
"data": -0.054148 
},
{
 "dates":   1315,
"data": 0.013752 
},
{
 "dates":   1316,
"data": -0.030967 
},
{
 "dates":   1317,
"data": 0.0255 
},
{
 "dates":   1318,
"data": -0.031561 
},
{
 "dates":   1319,
"data": 0.0042473 
},
{
 "dates":   1320,
"data": 0.061084 
},
{
 "dates":   1321,
"data": -0.10177 
},
{
 "dates":   1322,
"data": -0.0091945 
},
{
 "dates":   1323,
"data": 0.074858 
},
{
 "dates":   1324,
"data": -0.0080214 
},
{
 "dates":   1325,
"data": 0.048822 
},
{
 "dates":   1326,
"data": -0.022552 
},
{
 "dates":   1327,
"data": -0.058314 
},
{
 "dates":   1328,
"data": 0.080113 
},
{
 "dates":   1329,
"data": 0.014629 
},
{
 "dates":   1330,
"data": -0.0858 
},
{
 "dates":   1331,
"data": 0.058795 
},
{
 "dates":   1332,
"data": -0.030821 
},
{
 "dates":   1333,
"data": 0.020909 
},
{
 "dates":   1334,
"data": -0.017852 
},
{
 "dates":   1335,
"data": -0.014541 
},
{
 "dates":   1336,
"data": 0.032071 
},
{
 "dates":   1337,
"data": 0.014954 
},
{
 "dates":   1338,
"data": -0.0042043 
},
{
 "dates":   1339,
"data": 0.0039441 
},
{
 "dates":   1340,
"data": -0.00064092 
},
{
 "dates":   1341,
"data": -0.01562 
},
{
 "dates":   1342,
"data": 0.0026618 
},
{
 "dates":   1343,
"data": -0.022589 
},
{
 "dates":   1344,
"data": 0.027952 
},
{
 "dates":   1345,
"data": 0.00069383 
},
{
 "dates":   1346,
"data": 0.0057969 
},
{
 "dates":   1347,
"data": 0.020381 
},
{
 "dates":   1348,
"data": -0.12942 
},
{
 "dates":   1349,
"data": 0.13332 
},
{
 "dates":   1350,
"data": -0.06139 
},
{
 "dates":   1351,
"data": -0.0045947 
},
{
 "dates":   1352,
"data": -0.0095057 
},
{
 "dates":   1353,
"data": -0.017959 
},
{
 "dates":   1354,
"data": 0.048793 
},
{
 "dates":   1355,
"data": -0.012247 
},
{
 "dates":   1356,
"data": 0.026597 
},
{
 "dates":   1357,
"data": -0.092269 
},
{
 "dates":   1358,
"data": 0.081859 
},
{
 "dates":   1359,
"data": -0.062454 
},
{
 "dates":   1360,
"data": 0.012372 
},
{
 "dates":   1361,
"data": 0.042359 
},
{
 "dates":   1362,
"data": -0.024254 
},
{
 "dates":   1363,
"data": 0.061378 
},
{
 "dates":   1364,
"data": -0.016534 
},
{
 "dates":   1365,
"data": -0.007152 
},
{
 "dates":   1366,
"data": -0.097421 
},
{
 "dates":   1367,
"data": 0.059398 
},
{
 "dates":   1368,
"data": 0.05004 
},
{
 "dates":   1369,
"data": -0.040876 
},
{
 "dates":   1370,
"data": 0.031886 
},
{
 "dates":   1371,
"data": -0.043843 
},
{
 "dates":   1372,
"data": 0.015958 
},
{
 "dates":   1373,
"data": -0.037219 
},
{
 "dates":   1374,
"data": 0.067264 
},
{
 "dates":   1375,
"data": -0.080853 
},
{
 "dates":   1376,
"data": 0.090805 
},
{
 "dates":   1377,
"data": -0.021086 
},
{
 "dates":   1378,
"data": -0.019023 
},
{
 "dates":   1379,
"data": -0.00076677 
},
{
 "dates":   1380,
"data": -0.022708 
},
{
 "dates":   1381,
"data": 0.024301 
},
{
 "dates":   1382,
"data": 0.025121 
},
{
 "dates":   1383,
"data": 0.0064947 
},
{
 "dates":   1384,
"data": -0.079065 
},
{
 "dates":   1385,
"data": 0.032339 
},
{
 "dates":   1386,
"data": -0.010702 
},
{
 "dates":   1387,
"data": -0.025133 
},
{
 "dates":   1388,
"data": 0.077329 
},
{
 "dates":   1389,
"data": -0.069024 
},
{
 "dates":   1390,
"data": 0.10129 
},
{
 "dates":   1391,
"data": -0.051541 
},
{
 "dates":   1392,
"data": 0.030241 
},
{
 "dates":   1393,
"data": -0.0064503 
},
{
 "dates":   1394,
"data": -0.010759 
},
{
 "dates":   1395,
"data": -0.023479 
},
{
 "dates":   1396,
"data": 0.039432 
},
{
 "dates":   1397,
"data": -0.026464 
},
{
 "dates":   1398,
"data": 0.021779 
},
{
 "dates":   1399,
"data": 0.0044907 
},
{
 "dates":   1400,
"data": -0.039079 
},
{
 "dates":   1401,
"data": 0.035826 
},
{
 "dates":   1402,
"data": 0.035472 
},
{
 "dates":   1403,
"data": -0.026922 
},
{
 "dates":   1404,
"data": -0.0077584 
},
{
 "dates":   1405,
"data": 0.015578 
},
{
 "dates":   1406,
"data": -0.029657 
},
{
 "dates":   1407,
"data": -0.054117 
},
{
 "dates":   1408,
"data": 0.051633 
},
{
 "dates":   1409,
"data": -0.0080138 
},
{
 "dates":   1410,
"data": -0.026997 
},
{
 "dates":   1411,
"data": 0.065469 
},
{
 "dates":   1412,
"data": -0.070772 
},
{
 "dates":   1413,
"data": 0.0066889 
},
{
 "dates":   1414,
"data": 0.0016352 
},
{
 "dates":   1415,
"data": 0.057787 
},
{
 "dates":   1416,
"data": -0.02804 
},
{
 "dates":   1417,
"data": 0.024813 
},
{
 "dates":   1418,
"data": -0.032893 
},
{
 "dates":   1419,
"data": 0.012441 
},
{
 "dates":   1420,
"data": 0.021465 
},
{
 "dates":   1421,
"data": 0.017534 
},
{
 "dates":   1422,
"data": -0.009839 
},
{
 "dates":   1423,
"data": -0.036823 
},
{
 "dates":   1424,
"data": 0.054936 
},
{
 "dates":   1425,
"data": -0.02036 
},
{
 "dates":   1426,
"data": -0.014301 
},
{
 "dates":   1427,
"data": 0.018561 
},
{
 "dates":   1428,
"data": 0.027726 
},
{
 "dates":   1429,
"data": -0.022868 
},
{
 "dates":   1430,
"data": 0.048957 
},
{
 "dates":   1431,
"data": -0.074207 
},
{
 "dates":   1432,
"data": 0.039607 
},
{
 "dates":   1433,
"data": -0.040341 
},
{
 "dates":   1434,
"data": 0.073661 
},
{
 "dates":   1435,
"data": 0.0047023 
},
{
 "dates":   1436,
"data": -0.046041 
},
{
 "dates":   1437,
"data": -0.010257 
},
{
 "dates":   1438,
"data": 0.029694 
},
{
 "dates":   1439,
"data": -0.022905 
},
{
 "dates":   1440,
"data": 0.025583 
},
{
 "dates":   1441,
"data": -0.047822 
},
{
 "dates":   1442,
"data": 0.019423 
},
{
 "dates":   1443,
"data": -0.016648 
},
{
 "dates":   1444,
"data": 0.023861 
},
{
 "dates":   1445,
"data": 0.020219 
},
{
 "dates":   1446,
"data": 0.0015363 
},
{
 "dates":   1447,
"data": -0.0028759 
},
{
 "dates":   1448,
"data": 0.0010501 
},
{
 "dates":   1449,
"data": -0.022435 
},
{
 "dates":   1450,
"data": 0.051124 
},
{
 "dates":   1451,
"data": -0.014303 
},
{
 "dates":   1452,
"data": -0.01537 
},
{
 "dates":   1453,
"data": 0.018034 
},
{
 "dates":   1454,
"data": -0.042431 
},
{
 "dates":   1455,
"data": 0.0044574 
},
{
 "dates":   1456,
"data": 0.01807 
},
{
 "dates":   1457,
"data": -0.0079075 
},
{
 "dates":   1458,
"data": 0.040165 
},
{
 "dates":   1459,
"data": -0.01623 
},
{
 "dates":   1460,
"data": 0.011516 
},
{
 "dates":   1461,
"data": -0.039101 
} 
]
  
      var data = d3.nest()
        .key(function(d){
          return opts.group === undefined ? 'main' : d[opts.group]
        })
        .entries(data)
      
      nv.addGraph(function() {
        var chart = nv.models[opts.type]()
          .x(function(d) { return d[opts.x] })
          .y(function(d) { return d[opts.y] })
          .width(opts.width)
          .height(opts.height)
         
        
          
        

        
        
        
      
       d3.select("#" + opts.id)
        .append('svg')
        .datum(data)
        .transition().duration(500)
        .call(chart);

       nv.utils.windowResize(chart.update);
       return chart;
      });
    };
</script>


###  Summary Value

Last we can take a look at some summary values for this dataset.

<table class="table table-striped"><thead><tr><th> Data Normalization </th><th> Min. </th><th> 1st Qu. </th><th> Median </th><th> Mean </th><th> 3rd Qu. </th><th> Max. </th></tr></thead><tr><td> raw </td><td> 927 </td><td> 1130 </td><td> 1250 </td><td> 1250 </td><td> 1370 </td><td> 1620 </td></tr><tr><td> diffed </td><td> -187 </td><td> -35.2 </td><td> -1.22 </td><td> 0.334 </td><td> 34.8 </td><td> 188 </td></tr><tr><td> diffLog </td><td> -0.153 </td><td> -0.0282 </td><td> -0.000972 </td><td> 0.000277 </td><td> 0.0288 </td><td> 0.139 </td></tr></table>


<a name="Model"></a>

Model
------------------------

In our interviews with Stratego.com we found a few key findings:

1.  Revenue was steadily growing, and they were not projecting to make any major leaps forward in efficiency or hiring.
2.  Q1 was always their strong quarter due to their primary income being derived from a product aimed at home heating.
3.  Q3 was always their weakest quarter due to their primary ncome being derive from a product aimed at home heating.

###  Prediction Goals

Stratego Needs to make predictions at the following levels:

1.  Month to Month
2.  Quarterly 
3.  Year End

Furthermore, they would like to know under what conditions they were likely to miss their revenue targets.  

### Model Details

After some experimentation it was determined that the best model of Stratego.com's revenue should include the following:

1.  Day of Year
2.  Sin(x) with x in [0, $pi$] over 365 days
3.  t, time since start of revenue tracking

And should use a linear model (lm).

<div class="leaderboard">
  
  <h1>Base Model</h1>
  
  <p>The Base model is: <br><center>Revenue ~ sin($x_{d}$)+t+d </center><br>
  where:<br>
  <ul>
    <li>t - time since start</li>
    <li>d - day of year</li>
    <li>$x_{d}$ - [0, 2$pi$] over 365 days</li>
  </ul>
  <p>
</div>  


<a name="Results"></a>

Results
------------------------

### How Good is the Model?

Using our simple model of Revenue ~ sin($x_{d}$)+t+d we get the following visual confirmation that this is indeed a good fit (actually a great fit!).





<div id='dataMod' class='rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawdataMod()
    });
    function drawdataMod(){  
      var opts = {
 "dom": "dataMod",
"width":    800,
"height":    400,
"x": "dates",
"y": "data",
"group": "group",
"type": "lineWithFocusChart",
"id": "dataMod" 
},
        data = [
 {
 "dates": 1,
"data": 977.09,
"group": "actual" 
},
{
 "dates": 2,
"data": 989.11,
"group": "actual" 
},
{
 "dates": 3,
"data": 977.84,
"group": "actual" 
},
{
 "dates": 4,
"data": 1027.8,
"group": "actual" 
},
{
 "dates": 5,
"data": 1027.9,
"group": "actual" 
},
{
 "dates": 6,
"data": 978.44,
"group": "actual" 
},
{
 "dates": 7,
"data": 1008.4,
"group": "actual" 
},
{
 "dates": 8,
"data": 967.67,
"group": "actual" 
},
{
 "dates": 9,
"data": 989.06,
"group": "actual" 
},
{
 "dates": 10,
"data": 991.83,
"group": "actual" 
},
{
 "dates": 11,
"data": 1048.2,
"group": "actual" 
},
{
 "dates": 12,
"data": 1001.9,
"group": "actual" 
},
{
 "dates": 13,
"data": 1033.8,
"group": "actual" 
},
{
 "dates": 14,
"data": 1069.1,
"group": "actual" 
},
{
 "dates": 15,
"data": 1057.3,
"group": "actual" 
},
{
 "dates": 16,
"data": 1093.1,
"group": "actual" 
},
{
 "dates": 17,
"data": 1015.2,
"group": "actual" 
},
{
 "dates": 18,
"data": 1037.5,
"group": "actual" 
},
{
 "dates": 19,
"data": 1010.9,
"group": "actual" 
},
{
 "dates": 20,
"data": 1046.4,
"group": "actual" 
},
{
 "dates": 21,
"data": 1013.2,
"group": "actual" 
},
{
 "dates": 22,
"data": 1039.9,
"group": "actual" 
},
{
 "dates": 23,
"data": 1041.3,
"group": "actual" 
},
{
 "dates": 24,
"data": 1103.9,
"group": "actual" 
},
{
 "dates": 25,
"data":   1034,
"group": "actual" 
},
{
 "dates": 26,
"data": 1057.8,
"group": "actual" 
},
{
 "dates": 27,
"data":   1070,
"group": "actual" 
},
{
 "dates": 28,
"data": 1044.4,
"group": "actual" 
},
{
 "dates": 29,
"data": 1041.5,
"group": "actual" 
},
{
 "dates": 30,
"data": 1100.5,
"group": "actual" 
},
{
 "dates": 31,
"data": 1088.3,
"group": "actual" 
},
{
 "dates": 32,
"data": 1109.4,
"group": "actual" 
},
{
 "dates": 33,
"data": 1071.2,
"group": "actual" 
},
{
 "dates": 34,
"data":   1108,
"group": "actual" 
},
{
 "dates": 35,
"data": 1106.9,
"group": "actual" 
},
{
 "dates": 36,
"data": 1081.5,
"group": "actual" 
},
{
 "dates": 37,
"data": 1118.8,
"group": "actual" 
},
{
 "dates": 38,
"data": 1084.4,
"group": "actual" 
},
{
 "dates": 39,
"data": 1085.1,
"group": "actual" 
},
{
 "dates": 40,
"data": 1016.3,
"group": "actual" 
},
{
 "dates": 41,
"data": 1124.5,
"group": "actual" 
},
{
 "dates": 42,
"data":   1066,
"group": "actual" 
},
{
 "dates": 43,
"data": 1098.7,
"group": "actual" 
},
{
 "dates": 44,
"data": 1035.6,
"group": "actual" 
},
{
 "dates": 45,
"data": 1055.3,
"group": "actual" 
},
{
 "dates": 46,
"data": 1111.6,
"group": "actual" 
},
{
 "dates": 47,
"data": 1110.6,
"group": "actual" 
},
{
 "dates": 48,
"data": 1084.4,
"group": "actual" 
},
{
 "dates": 49,
"data": 1157.3,
"group": "actual" 
},
{
 "dates": 50,
"data": 1077.3,
"group": "actual" 
},
{
 "dates": 51,
"data": 1074.4,
"group": "actual" 
},
{
 "dates": 52,
"data": 1095.2,
"group": "actual" 
},
{
 "dates": 53,
"data": 1082.6,
"group": "actual" 
},
{
 "dates": 54,
"data": 1067.6,
"group": "actual" 
},
{
 "dates": 55,
"data": 1095.4,
"group": "actual" 
},
{
 "dates": 56,
"data": 1075.5,
"group": "actual" 
},
{
 "dates": 57,
"data": 1108.7,
"group": "actual" 
},
{
 "dates": 58,
"data": 1045.7,
"group": "actual" 
},
{
 "dates": 59,
"data": 1097.8,
"group": "actual" 
},
{
 "dates": 60,
"data": 1094.3,
"group": "actual" 
},
{
 "dates": 61,
"data":   1133,
"group": "actual" 
},
{
 "dates": 62,
"data": 1100.4,
"group": "actual" 
},
{
 "dates": 63,
"data": 1120.3,
"group": "actual" 
},
{
 "dates": 64,
"data": 1077.1,
"group": "actual" 
},
{
 "dates": 65,
"data": 1063.8,
"group": "actual" 
},
{
 "dates": 66,
"data": 1154.9,
"group": "actual" 
},
{
 "dates": 67,
"data": 1075.7,
"group": "actual" 
},
{
 "dates": 68,
"data": 1136.6,
"group": "actual" 
},
{
 "dates": 69,
"data": 1087.6,
"group": "actual" 
},
{
 "dates": 70,
"data": 1183.6,
"group": "actual" 
},
{
 "dates": 71,
"data": 1163.6,
"group": "actual" 
},
{
 "dates": 72,
"data": 1127.7,
"group": "actual" 
},
{
 "dates": 73,
"data": 1139.8,
"group": "actual" 
},
{
 "dates": 74,
"data": 1133.8,
"group": "actual" 
},
{
 "dates": 75,
"data": 1108.8,
"group": "actual" 
},
{
 "dates": 76,
"data": 1175.7,
"group": "actual" 
},
{
 "dates": 77,
"data": 1084.9,
"group": "actual" 
},
{
 "dates": 78,
"data": 1145.3,
"group": "actual" 
},
{
 "dates": 79,
"data": 1168.8,
"group": "actual" 
},
{
 "dates": 80,
"data": 1123.3,
"group": "actual" 
},
{
 "dates": 81,
"data": 1153.5,
"group": "actual" 
},
{
 "dates": 82,
"data":   1097,
"group": "actual" 
},
{
 "dates": 83,
"data": 1150.4,
"group": "actual" 
},
{
 "dates": 84,
"data": 1164.5,
"group": "actual" 
},
{
 "dates": 85,
"data": 1119.8,
"group": "actual" 
},
{
 "dates": 86,
"data":   1153,
"group": "actual" 
},
{
 "dates": 87,
"data": 1235.1,
"group": "actual" 
},
{
 "dates": 88,
"data": 1118.8,
"group": "actual" 
},
{
 "dates": 89,
"data": 1091.2,
"group": "actual" 
},
{
 "dates": 90,
"data": 1111.4,
"group": "actual" 
},
{
 "dates": 91,
"data": 1100.9,
"group": "actual" 
},
{
 "dates": 92,
"data": 1157.9,
"group": "actual" 
},
{
 "dates": 93,
"data": 1147.1,
"group": "actual" 
},
{
 "dates": 94,
"data": 1105.2,
"group": "actual" 
},
{
 "dates": 95,
"data":   1100,
"group": "actual" 
},
{
 "dates": 96,
"data": 1111.7,
"group": "actual" 
},
{
 "dates": 97,
"data": 1093.6,
"group": "actual" 
},
{
 "dates": 98,
"data": 1166.2,
"group": "actual" 
},
{
 "dates": 99,
"data": 1094.5,
"group": "actual" 
},
{
 "dates": 100,
"data": 1163.7,
"group": "actual" 
},
{
 "dates": 101,
"data": 1164.7,
"group": "actual" 
},
{
 "dates": 102,
"data": 1129.4,
"group": "actual" 
},
{
 "dates": 103,
"data": 1088.8,
"group": "actual" 
},
{
 "dates": 104,
"data":   1076,
"group": "actual" 
},
{
 "dates": 105,
"data": 1202.8,
"group": "actual" 
},
{
 "dates": 106,
"data": 1080.7,
"group": "actual" 
},
{
 "dates": 107,
"data": 1146.4,
"group": "actual" 
},
{
 "dates": 108,
"data": 1175.4,
"group": "actual" 
},
{
 "dates": 109,
"data": 1182.1,
"group": "actual" 
},
{
 "dates": 110,
"data": 1151.6,
"group": "actual" 
},
{
 "dates": 111,
"data": 1139.9,
"group": "actual" 
},
{
 "dates": 112,
"data": 1150.9,
"group": "actual" 
},
{
 "dates": 113,
"data": 1146.1,
"group": "actual" 
},
{
 "dates": 114,
"data": 1190.2,
"group": "actual" 
},
{
 "dates": 115,
"data": 1145.1,
"group": "actual" 
},
{
 "dates": 116,
"data": 1172.5,
"group": "actual" 
},
{
 "dates": 117,
"data": 1095.4,
"group": "actual" 
},
{
 "dates": 118,
"data": 1106.9,
"group": "actual" 
},
{
 "dates": 119,
"data": 1085.2,
"group": "actual" 
},
{
 "dates": 120,
"data": 1130.6,
"group": "actual" 
},
{
 "dates": 121,
"data": 1095.4,
"group": "actual" 
},
{
 "dates": 122,
"data": 1111.9,
"group": "actual" 
},
{
 "dates": 123,
"data": 1117.4,
"group": "actual" 
},
{
 "dates": 124,
"data": 1074.2,
"group": "actual" 
},
{
 "dates": 125,
"data": 1127.7,
"group": "actual" 
},
{
 "dates": 126,
"data": 1121.5,
"group": "actual" 
},
{
 "dates": 127,
"data": 1139.8,
"group": "actual" 
},
{
 "dates": 128,
"data": 1112.7,
"group": "actual" 
},
{
 "dates": 129,
"data": 1099.1,
"group": "actual" 
},
{
 "dates": 130,
"data": 1090.1,
"group": "actual" 
},
{
 "dates": 131,
"data": 1175.9,
"group": "actual" 
},
{
 "dates": 132,
"data": 1114.5,
"group": "actual" 
},
{
 "dates": 133,
"data": 1067.1,
"group": "actual" 
},
{
 "dates": 134,
"data": 1097.4,
"group": "actual" 
},
{
 "dates": 135,
"data":   1123,
"group": "actual" 
},
{
 "dates": 136,
"data": 1130.7,
"group": "actual" 
},
{
 "dates": 137,
"data": 1134.2,
"group": "actual" 
},
{
 "dates": 138,
"data": 1138.2,
"group": "actual" 
},
{
 "dates": 139,
"data": 1110.6,
"group": "actual" 
},
{
 "dates": 140,
"data": 1085.6,
"group": "actual" 
},
{
 "dates": 141,
"data": 1096.9,
"group": "actual" 
},
{
 "dates": 142,
"data": 1115.9,
"group": "actual" 
},
{
 "dates": 143,
"data": 1144.2,
"group": "actual" 
},
{
 "dates": 144,
"data": 1181.2,
"group": "actual" 
},
{
 "dates": 145,
"data": 1138.2,
"group": "actual" 
},
{
 "dates": 146,
"data": 1117.5,
"group": "actual" 
},
{
 "dates": 147,
"data": 1148.1,
"group": "actual" 
},
{
 "dates": 148,
"data": 1113.5,
"group": "actual" 
},
{
 "dates": 149,
"data": 1076.3,
"group": "actual" 
},
{
 "dates": 150,
"data": 1113.9,
"group": "actual" 
},
{
 "dates": 151,
"data": 1069.7,
"group": "actual" 
},
{
 "dates": 152,
"data": 1107.1,
"group": "actual" 
},
{
 "dates": 153,
"data": 1102.7,
"group": "actual" 
},
{
 "dates": 154,
"data": 1082.4,
"group": "actual" 
},
{
 "dates": 155,
"data": 1047.1,
"group": "actual" 
},
{
 "dates": 156,
"data": 1160.4,
"group": "actual" 
},
{
 "dates": 157,
"data": 1062.6,
"group": "actual" 
},
{
 "dates": 158,
"data": 1124.5,
"group": "actual" 
},
{
 "dates": 159,
"data": 1086.8,
"group": "actual" 
},
{
 "dates": 160,
"data": 1130.5,
"group": "actual" 
},
{
 "dates": 161,
"data": 1133.3,
"group": "actual" 
},
{
 "dates": 162,
"data":   1074,
"group": "actual" 
},
{
 "dates": 163,
"data": 1065.7,
"group": "actual" 
},
{
 "dates": 164,
"data": 1053.1,
"group": "actual" 
},
{
 "dates": 165,
"data": 1113.9,
"group": "actual" 
},
{
 "dates": 166,
"data": 1048.2,
"group": "actual" 
},
{
 "dates": 167,
"data": 1061.1,
"group": "actual" 
},
{
 "dates": 168,
"data": 1080.8,
"group": "actual" 
},
{
 "dates": 169,
"data": 1026.4,
"group": "actual" 
},
{
 "dates": 170,
"data": 1005.9,
"group": "actual" 
},
{
 "dates": 171,
"data": 1087.3,
"group": "actual" 
},
{
 "dates": 172,
"data": 1133.6,
"group": "actual" 
},
{
 "dates": 173,
"data":   1111,
"group": "actual" 
},
{
 "dates": 174,
"data": 1063.6,
"group": "actual" 
},
{
 "dates": 175,
"data":   1073,
"group": "actual" 
},
{
 "dates": 176,
"data": 1061.3,
"group": "actual" 
},
{
 "dates": 177,
"data": 1054.5,
"group": "actual" 
},
{
 "dates": 178,
"data": 1055.1,
"group": "actual" 
},
{
 "dates": 179,
"data": 1054.6,
"group": "actual" 
},
{
 "dates": 180,
"data":   1094,
"group": "actual" 
},
{
 "dates": 181,
"data": 1086.7,
"group": "actual" 
},
{
 "dates": 182,
"data": 1088.7,
"group": "actual" 
},
{
 "dates": 183,
"data": 1103.3,
"group": "actual" 
},
{
 "dates": 184,
"data": 1069.8,
"group": "actual" 
},
{
 "dates": 185,
"data": 1066.1,
"group": "actual" 
},
{
 "dates": 186,
"data": 1103.6,
"group": "actual" 
},
{
 "dates": 187,
"data": 1123.2,
"group": "actual" 
},
{
 "dates": 188,
"data":   1069,
"group": "actual" 
},
{
 "dates": 189,
"data": 1070.5,
"group": "actual" 
},
{
 "dates": 190,
"data": 1093.9,
"group": "actual" 
},
{
 "dates": 191,
"data": 1091.2,
"group": "actual" 
},
{
 "dates": 192,
"data": 1049.8,
"group": "actual" 
},
{
 "dates": 193,
"data": 1091.1,
"group": "actual" 
},
{
 "dates": 194,
"data": 1029.2,
"group": "actual" 
},
{
 "dates": 195,
"data": 1131.2,
"group": "actual" 
},
{
 "dates": 196,
"data": 1063.2,
"group": "actual" 
},
{
 "dates": 197,
"data": 1055.2,
"group": "actual" 
},
{
 "dates": 198,
"data": 1046.1,
"group": "actual" 
},
{
 "dates": 199,
"data": 1061.1,
"group": "actual" 
},
{
 "dates": 200,
"data": 1054.8,
"group": "actual" 
},
{
 "dates": 201,
"data": 1015.8,
"group": "actual" 
},
{
 "dates": 202,
"data": 1006.8,
"group": "actual" 
},
{
 "dates": 203,
"data":   1052,
"group": "actual" 
},
{
 "dates": 204,
"data": 1034.1,
"group": "actual" 
},
{
 "dates": 205,
"data": 1041.2,
"group": "actual" 
},
{
 "dates": 206,
"data": 1079.3,
"group": "actual" 
},
{
 "dates": 207,
"data": 1056.6,
"group": "actual" 
},
{
 "dates": 208,
"data": 1012.3,
"group": "actual" 
},
{
 "dates": 209,
"data": 1019.9,
"group": "actual" 
},
{
 "dates": 210,
"data": 1003.7,
"group": "actual" 
},
{
 "dates": 211,
"data": 997.72,
"group": "actual" 
},
{
 "dates": 212,
"data": 1028.9,
"group": "actual" 
},
{
 "dates": 213,
"data": 996.95,
"group": "actual" 
},
{
 "dates": 214,
"data": 1029.4,
"group": "actual" 
},
{
 "dates": 215,
"data":  993.2,
"group": "actual" 
},
{
 "dates": 216,
"data": 979.12,
"group": "actual" 
},
{
 "dates": 217,
"data": 1008.8,
"group": "actual" 
},
{
 "dates": 218,
"data": 1054.6,
"group": "actual" 
},
{
 "dates": 219,
"data": 1051.5,
"group": "actual" 
},
{
 "dates": 220,
"data": 1007.7,
"group": "actual" 
},
{
 "dates": 221,
"data": 1053.3,
"group": "actual" 
},
{
 "dates": 222,
"data": 1047.1,
"group": "actual" 
},
{
 "dates": 223,
"data": 1024.2,
"group": "actual" 
},
{
 "dates": 224,
"data": 1005.8,
"group": "actual" 
},
{
 "dates": 225,
"data": 960.91,
"group": "actual" 
},
{
 "dates": 226,
"data": 1064.4,
"group": "actual" 
},
{
 "dates": 227,
"data": 994.03,
"group": "actual" 
},
{
 "dates": 228,
"data": 992.33,
"group": "actual" 
},
{
 "dates": 229,
"data": 963.23,
"group": "actual" 
},
{
 "dates": 230,
"data": 1003.3,
"group": "actual" 
},
{
 "dates": 231,
"data": 1015.8,
"group": "actual" 
},
{
 "dates": 232,
"data": 991.48,
"group": "actual" 
},
{
 "dates": 233,
"data": 999.36,
"group": "actual" 
},
{
 "dates": 234,
"data": 996.64,
"group": "actual" 
},
{
 "dates": 235,
"data": 942.52,
"group": "actual" 
},
{
 "dates": 236,
"data": 927.01,
"group": "actual" 
},
{
 "dates": 237,
"data": 982.69,
"group": "actual" 
},
{
 "dates": 238,
"data": 1037.5,
"group": "actual" 
},
{
 "dates": 239,
"data": 1033.7,
"group": "actual" 
},
{
 "dates": 240,
"data": 1004.6,
"group": "actual" 
},
{
 "dates": 241,
"data": 1027.9,
"group": "actual" 
},
{
 "dates": 242,
"data": 1044.6,
"group": "actual" 
},
{
 "dates": 243,
"data": 1002.6,
"group": "actual" 
},
{
 "dates": 244,
"data": 1021.6,
"group": "actual" 
},
{
 "dates": 245,
"data": 1022.8,
"group": "actual" 
},
{
 "dates": 246,
"data": 1027.3,
"group": "actual" 
},
{
 "dates": 247,
"data": 1028.8,
"group": "actual" 
},
{
 "dates": 248,
"data": 1001.6,
"group": "actual" 
},
{
 "dates": 249,
"data": 987.07,
"group": "actual" 
},
{
 "dates": 250,
"data": 963.46,
"group": "actual" 
},
{
 "dates": 251,
"data": 992.24,
"group": "actual" 
},
{
 "dates": 252,
"data": 1025.7,
"group": "actual" 
},
{
 "dates": 253,
"data":  984.8,
"group": "actual" 
},
{
 "dates": 254,
"data": 961.19,
"group": "actual" 
},
{
 "dates": 255,
"data":    962,
"group": "actual" 
},
{
 "dates": 256,
"data": 993.08,
"group": "actual" 
},
{
 "dates": 257,
"data": 962.69,
"group": "actual" 
},
{
 "dates": 258,
"data": 980.53,
"group": "actual" 
},
{
 "dates": 259,
"data": 1048.9,
"group": "actual" 
},
{
 "dates": 260,
"data": 977.48,
"group": "actual" 
},
{
 "dates": 261,
"data": 955.39,
"group": "actual" 
},
{
 "dates": 262,
"data": 956.52,
"group": "actual" 
},
{
 "dates": 263,
"data": 984.45,
"group": "actual" 
},
{
 "dates": 264,
"data":  955.9,
"group": "actual" 
},
{
 "dates": 265,
"data": 1057.8,
"group": "actual" 
},
{
 "dates": 266,
"data": 1029.1,
"group": "actual" 
},
{
 "dates": 267,
"data": 1043.9,
"group": "actual" 
},
{
 "dates": 268,
"data": 985.68,
"group": "actual" 
},
{
 "dates": 269,
"data": 952.26,
"group": "actual" 
},
{
 "dates": 270,
"data":   1011,
"group": "actual" 
},
{
 "dates": 271,
"data": 1005.6,
"group": "actual" 
},
{
 "dates": 272,
"data": 1009.1,
"group": "actual" 
},
{
 "dates": 273,
"data": 982.41,
"group": "actual" 
},
{
 "dates": 274,
"data": 992.78,
"group": "actual" 
},
{
 "dates": 275,
"data": 990.18,
"group": "actual" 
},
{
 "dates": 276,
"data": 974.67,
"group": "actual" 
},
{
 "dates": 277,
"data": 999.46,
"group": "actual" 
},
{
 "dates": 278,
"data": 996.93,
"group": "actual" 
},
{
 "dates": 279,
"data":   1004,
"group": "actual" 
},
{
 "dates": 280,
"data": 976.56,
"group": "actual" 
},
{
 "dates": 281,
"data": 1010.7,
"group": "actual" 
},
{
 "dates": 282,
"data": 965.13,
"group": "actual" 
},
{
 "dates": 283,
"data": 1052.2,
"group": "actual" 
},
{
 "dates": 284,
"data": 985.13,
"group": "actual" 
},
{
 "dates": 285,
"data":   1008,
"group": "actual" 
},
{
 "dates": 286,
"data": 1010.1,
"group": "actual" 
},
{
 "dates": 287,
"data": 1006.2,
"group": "actual" 
},
{
 "dates": 288,
"data": 978.15,
"group": "actual" 
},
{
 "dates": 289,
"data": 1039.5,
"group": "actual" 
},
{
 "dates": 290,
"data": 1054.7,
"group": "actual" 
},
{
 "dates": 291,
"data": 1008.8,
"group": "actual" 
},
{
 "dates": 292,
"data": 998.92,
"group": "actual" 
},
{
 "dates": 293,
"data": 998.28,
"group": "actual" 
},
{
 "dates": 294,
"data": 1020.8,
"group": "actual" 
},
{
 "dates": 295,
"data": 931.21,
"group": "actual" 
},
{
 "dates": 296,
"data": 1000.8,
"group": "actual" 
},
{
 "dates": 297,
"data": 935.35,
"group": "actual" 
},
{
 "dates": 298,
"data": 1010.2,
"group": "actual" 
},
{
 "dates": 299,
"data": 1056.4,
"group": "actual" 
},
{
 "dates": 300,
"data": 1036.6,
"group": "actual" 
},
{
 "dates": 301,
"data":  993.9,
"group": "actual" 
},
{
 "dates": 302,
"data": 1031.1,
"group": "actual" 
},
{
 "dates": 303,
"data":   1025,
"group": "actual" 
},
{
 "dates": 304,
"data": 997.85,
"group": "actual" 
},
{
 "dates": 305,
"data": 973.84,
"group": "actual" 
},
{
 "dates": 306,
"data":  980.9,
"group": "actual" 
},
{
 "dates": 307,
"data": 1062.2,
"group": "actual" 
},
{
 "dates": 308,
"data": 967.27,
"group": "actual" 
},
{
 "dates": 309,
"data": 1035.6,
"group": "actual" 
},
{
 "dates": 310,
"data": 1046.3,
"group": "actual" 
},
{
 "dates": 311,
"data": 1078.6,
"group": "actual" 
},
{
 "dates": 312,
"data": 1064.3,
"group": "actual" 
},
{
 "dates": 313,
"data": 1025.9,
"group": "actual" 
},
{
 "dates": 314,
"data": 1088.4,
"group": "actual" 
},
{
 "dates": 315,
"data": 1041.7,
"group": "actual" 
},
{
 "dates": 316,
"data":   1071,
"group": "actual" 
},
{
 "dates": 317,
"data": 1006.4,
"group": "actual" 
},
{
 "dates": 318,
"data": 1023.1,
"group": "actual" 
},
{
 "dates": 319,
"data": 1005.6,
"group": "actual" 
},
{
 "dates": 320,
"data": 1082.4,
"group": "actual" 
},
{
 "dates": 321,
"data": 1041.8,
"group": "actual" 
},
{
 "dates": 322,
"data": 1068.4,
"group": "actual" 
},
{
 "dates": 323,
"data": 1063.5,
"group": "actual" 
},
{
 "dates": 324,
"data": 991.38,
"group": "actual" 
},
{
 "dates": 325,
"data": 992.71,
"group": "actual" 
},
{
 "dates": 326,
"data": 1089.5,
"group": "actual" 
},
{
 "dates": 327,
"data": 1069.7,
"group": "actual" 
},
{
 "dates": 328,
"data": 1036.7,
"group": "actual" 
},
{
 "dates": 329,
"data": 1111.1,
"group": "actual" 
},
{
 "dates": 330,
"data": 1051.1,
"group": "actual" 
},
{
 "dates": 331,
"data": 1032.5,
"group": "actual" 
},
{
 "dates": 332,
"data":   1033,
"group": "actual" 
},
{
 "dates": 333,
"data": 1052.8,
"group": "actual" 
},
{
 "dates": 334,
"data": 1059.1,
"group": "actual" 
},
{
 "dates": 335,
"data": 1087.8,
"group": "actual" 
},
{
 "dates": 336,
"data": 1069.6,
"group": "actual" 
},
{
 "dates": 337,
"data":   1033,
"group": "actual" 
},
{
 "dates": 338,
"data": 1063.9,
"group": "actual" 
},
{
 "dates": 339,
"data":   1118,
"group": "actual" 
},
{
 "dates": 340,
"data": 1092.6,
"group": "actual" 
},
{
 "dates": 341,
"data": 1062.1,
"group": "actual" 
},
{
 "dates": 342,
"data": 1044.7,
"group": "actual" 
},
{
 "dates": 343,
"data":   1127,
"group": "actual" 
},
{
 "dates": 344,
"data": 1118.9,
"group": "actual" 
},
{
 "dates": 345,
"data": 1023.7,
"group": "actual" 
},
{
 "dates": 346,
"data": 1053.7,
"group": "actual" 
},
{
 "dates": 347,
"data": 1129.3,
"group": "actual" 
},
{
 "dates": 348,
"data": 1003.4,
"group": "actual" 
},
{
 "dates": 349,
"data": 1121.8,
"group": "actual" 
},
{
 "dates": 350,
"data": 1068.4,
"group": "actual" 
},
{
 "dates": 351,
"data": 1059.8,
"group": "actual" 
},
{
 "dates": 352,
"data": 1087.3,
"group": "actual" 
},
{
 "dates": 353,
"data": 1104.4,
"group": "actual" 
},
{
 "dates": 354,
"data": 1053.2,
"group": "actual" 
},
{
 "dates": 355,
"data": 1061.2,
"group": "actual" 
},
{
 "dates": 356,
"data": 1054.1,
"group": "actual" 
},
{
 "dates": 357,
"data": 1115.4,
"group": "actual" 
},
{
 "dates": 358,
"data": 1137.2,
"group": "actual" 
},
{
 "dates": 359,
"data": 1124.7,
"group": "actual" 
},
{
 "dates": 360,
"data": 1078.2,
"group": "actual" 
},
{
 "dates": 361,
"data": 1124.5,
"group": "actual" 
},
{
 "dates": 362,
"data": 1160.2,
"group": "actual" 
},
{
 "dates": 363,
"data": 1122.5,
"group": "actual" 
},
{
 "dates": 364,
"data": 1151.4,
"group": "actual" 
},
{
 "dates": 365,
"data": 1197.1,
"group": "actual" 
},
{
 "dates": 366,
"data":   1071,
"group": "actual" 
},
{
 "dates": 367,
"data": 1121.9,
"group": "actual" 
},
{
 "dates": 368,
"data": 1050.8,
"group": "actual" 
},
{
 "dates": 369,
"data": 1086.4,
"group": "actual" 
},
{
 "dates": 370,
"data": 1113.6,
"group": "actual" 
},
{
 "dates": 371,
"data": 1056.3,
"group": "actual" 
},
{
 "dates": 372,
"data": 1159.8,
"group": "actual" 
},
{
 "dates": 373,
"data": 1168.8,
"group": "actual" 
},
{
 "dates": 374,
"data": 1073.1,
"group": "actual" 
},
{
 "dates": 375,
"data": 1189.4,
"group": "actual" 
},
{
 "dates": 376,
"data": 1174.7,
"group": "actual" 
},
{
 "dates": 377,
"data": 1173.7,
"group": "actual" 
},
{
 "dates": 378,
"data": 1128.2,
"group": "actual" 
},
{
 "dates": 379,
"data": 1154.2,
"group": "actual" 
},
{
 "dates": 380,
"data": 1103.2,
"group": "actual" 
},
{
 "dates": 381,
"data":   1141,
"group": "actual" 
},
{
 "dates": 382,
"data":   1196,
"group": "actual" 
},
{
 "dates": 383,
"data": 1118.8,
"group": "actual" 
},
{
 "dates": 384,
"data": 1153.1,
"group": "actual" 
},
{
 "dates": 385,
"data":   1210,
"group": "actual" 
},
{
 "dates": 386,
"data": 1215.2,
"group": "actual" 
},
{
 "dates": 387,
"data": 1120.2,
"group": "actual" 
},
{
 "dates": 388,
"data": 1206.6,
"group": "actual" 
},
{
 "dates": 389,
"data": 1144.4,
"group": "actual" 
},
{
 "dates": 390,
"data": 1180.7,
"group": "actual" 
},
{
 "dates": 391,
"data":   1211,
"group": "actual" 
},
{
 "dates": 392,
"data": 1226.4,
"group": "actual" 
},
{
 "dates": 393,
"data": 1153.1,
"group": "actual" 
},
{
 "dates": 394,
"data": 1188.6,
"group": "actual" 
},
{
 "dates": 395,
"data": 1177.1,
"group": "actual" 
},
{
 "dates": 396,
"data": 1194.7,
"group": "actual" 
},
{
 "dates": 397,
"data": 1213.8,
"group": "actual" 
},
{
 "dates": 398,
"data": 1210.9,
"group": "actual" 
},
{
 "dates": 399,
"data": 1178.4,
"group": "actual" 
},
{
 "dates": 400,
"data": 1233.2,
"group": "actual" 
},
{
 "dates": 401,
"data": 1223.7,
"group": "actual" 
},
{
 "dates": 402,
"data": 1205.7,
"group": "actual" 
},
{
 "dates": 403,
"data": 1164.2,
"group": "actual" 
},
{
 "dates": 404,
"data": 1235.6,
"group": "actual" 
},
{
 "dates": 405,
"data": 1110.9,
"group": "actual" 
},
{
 "dates": 406,
"data": 1216.6,
"group": "actual" 
},
{
 "dates": 407,
"data": 1182.7,
"group": "actual" 
},
{
 "dates": 408,
"data": 1181.7,
"group": "actual" 
},
{
 "dates": 409,
"data": 1226.1,
"group": "actual" 
},
{
 "dates": 410,
"data": 1174.6,
"group": "actual" 
},
{
 "dates": 411,
"data": 1190.9,
"group": "actual" 
},
{
 "dates": 412,
"data": 1229.2,
"group": "actual" 
},
{
 "dates": 413,
"data": 1215.9,
"group": "actual" 
},
{
 "dates": 414,
"data": 1293.7,
"group": "actual" 
},
{
 "dates": 415,
"data": 1255.7,
"group": "actual" 
},
{
 "dates": 416,
"data": 1220.4,
"group": "actual" 
},
{
 "dates": 417,
"data": 1273.7,
"group": "actual" 
},
{
 "dates": 418,
"data": 1204.4,
"group": "actual" 
},
{
 "dates": 419,
"data": 1205.7,
"group": "actual" 
},
{
 "dates": 420,
"data": 1299.5,
"group": "actual" 
},
{
 "dates": 421,
"data": 1246.5,
"group": "actual" 
},
{
 "dates": 422,
"data": 1238.4,
"group": "actual" 
},
{
 "dates": 423,
"data": 1155.2,
"group": "actual" 
},
{
 "dates": 424,
"data": 1240.5,
"group": "actual" 
},
{
 "dates": 425,
"data": 1206.7,
"group": "actual" 
},
{
 "dates": 426,
"data":   1202,
"group": "actual" 
},
{
 "dates": 427,
"data": 1234.6,
"group": "actual" 
},
{
 "dates": 428,
"data": 1237.3,
"group": "actual" 
},
{
 "dates": 429,
"data": 1287.4,
"group": "actual" 
},
{
 "dates": 430,
"data": 1231.7,
"group": "actual" 
},
{
 "dates": 431,
"data": 1235.7,
"group": "actual" 
},
{
 "dates": 432,
"data":   1195,
"group": "actual" 
},
{
 "dates": 433,
"data": 1280.6,
"group": "actual" 
},
{
 "dates": 434,
"data": 1240.3,
"group": "actual" 
},
{
 "dates": 435,
"data": 1265.3,
"group": "actual" 
},
{
 "dates": 436,
"data": 1241.6,
"group": "actual" 
},
{
 "dates": 437,
"data": 1185.9,
"group": "actual" 
},
{
 "dates": 438,
"data": 1272.1,
"group": "actual" 
},
{
 "dates": 439,
"data": 1241.1,
"group": "actual" 
},
{
 "dates": 440,
"data": 1257.2,
"group": "actual" 
},
{
 "dates": 441,
"data": 1274.5,
"group": "actual" 
},
{
 "dates": 442,
"data": 1273.9,
"group": "actual" 
},
{
 "dates": 443,
"data": 1139.6,
"group": "actual" 
},
{
 "dates": 444,
"data": 1256.7,
"group": "actual" 
},
{
 "dates": 445,
"data":   1235,
"group": "actual" 
},
{
 "dates": 446,
"data": 1239.3,
"group": "actual" 
},
{
 "dates": 447,
"data": 1228.5,
"group": "actual" 
},
{
 "dates": 448,
"data": 1230.5,
"group": "actual" 
},
{
 "dates": 449,
"data": 1175.5,
"group": "actual" 
},
{
 "dates": 450,
"data": 1275.5,
"group": "actual" 
},
{
 "dates": 451,
"data": 1308.9,
"group": "actual" 
},
{
 "dates": 452,
"data": 1261.4,
"group": "actual" 
},
{
 "dates": 453,
"data": 1259.4,
"group": "actual" 
},
{
 "dates": 454,
"data":   1232,
"group": "actual" 
},
{
 "dates": 455,
"data": 1241.1,
"group": "actual" 
},
{
 "dates": 456,
"data": 1261.5,
"group": "actual" 
},
{
 "dates": 457,
"data": 1246.8,
"group": "actual" 
},
{
 "dates": 458,
"data": 1264.2,
"group": "actual" 
},
{
 "dates": 459,
"data": 1228.5,
"group": "actual" 
},
{
 "dates": 460,
"data": 1185.7,
"group": "actual" 
},
{
 "dates": 461,
"data": 1252.8,
"group": "actual" 
},
{
 "dates": 462,
"data": 1246.6,
"group": "actual" 
},
{
 "dates": 463,
"data": 1244.7,
"group": "actual" 
},
{
 "dates": 464,
"data": 1196.9,
"group": "actual" 
},
{
 "dates": 465,
"data": 1237.4,
"group": "actual" 
},
{
 "dates": 466,
"data": 1254.5,
"group": "actual" 
},
{
 "dates": 467,
"data": 1227.9,
"group": "actual" 
},
{
 "dates": 468,
"data": 1245.7,
"group": "actual" 
},
{
 "dates": 469,
"data": 1263.2,
"group": "actual" 
},
{
 "dates": 470,
"data": 1266.2,
"group": "actual" 
},
{
 "dates": 471,
"data": 1265.2,
"group": "actual" 
},
{
 "dates": 472,
"data": 1239.4,
"group": "actual" 
},
{
 "dates": 473,
"data": 1269.9,
"group": "actual" 
},
{
 "dates": 474,
"data": 1290.9,
"group": "actual" 
},
{
 "dates": 475,
"data": 1290.3,
"group": "actual" 
},
{
 "dates": 476,
"data": 1284.3,
"group": "actual" 
},
{
 "dates": 477,
"data": 1253.4,
"group": "actual" 
},
{
 "dates": 478,
"data": 1273.1,
"group": "actual" 
},
{
 "dates": 479,
"data": 1330.7,
"group": "actual" 
},
{
 "dates": 480,
"data": 1303.5,
"group": "actual" 
},
{
 "dates": 481,
"data": 1268.6,
"group": "actual" 
},
{
 "dates": 482,
"data": 1262.1,
"group": "actual" 
},
{
 "dates": 483,
"data": 1310.1,
"group": "actual" 
},
{
 "dates": 484,
"data": 1277.8,
"group": "actual" 
},
{
 "dates": 485,
"data": 1247.8,
"group": "actual" 
},
{
 "dates": 486,
"data": 1220.9,
"group": "actual" 
},
{
 "dates": 487,
"data": 1258.9,
"group": "actual" 
},
{
 "dates": 488,
"data": 1245.6,
"group": "actual" 
},
{
 "dates": 489,
"data": 1225.6,
"group": "actual" 
},
{
 "dates": 490,
"data": 1180.4,
"group": "actual" 
},
{
 "dates": 491,
"data":   1257,
"group": "actual" 
},
{
 "dates": 492,
"data": 1223.8,
"group": "actual" 
},
{
 "dates": 493,
"data": 1294.2,
"group": "actual" 
},
{
 "dates": 494,
"data":   1221,
"group": "actual" 
},
{
 "dates": 495,
"data": 1207.2,
"group": "actual" 
},
{
 "dates": 496,
"data": 1248.6,
"group": "actual" 
},
{
 "dates": 497,
"data": 1221.2,
"group": "actual" 
},
{
 "dates": 498,
"data": 1207.7,
"group": "actual" 
},
{
 "dates": 499,
"data": 1236.6,
"group": "actual" 
},
{
 "dates": 500,
"data": 1179.9,
"group": "actual" 
},
{
 "dates": 501,
"data":   1260,
"group": "actual" 
},
{
 "dates": 502,
"data": 1282.7,
"group": "actual" 
},
{
 "dates": 503,
"data": 1251.4,
"group": "actual" 
},
{
 "dates": 504,
"data": 1311.9,
"group": "actual" 
},
{
 "dates": 505,
"data": 1202.9,
"group": "actual" 
},
{
 "dates": 506,
"data": 1259.9,
"group": "actual" 
},
{
 "dates": 507,
"data": 1231.5,
"group": "actual" 
},
{
 "dates": 508,
"data": 1241.3,
"group": "actual" 
},
{
 "dates": 509,
"data": 1231.4,
"group": "actual" 
},
{
 "dates": 510,
"data": 1258.2,
"group": "actual" 
},
{
 "dates": 511,
"data": 1234.5,
"group": "actual" 
},
{
 "dates": 512,
"data": 1259.9,
"group": "actual" 
},
{
 "dates": 513,
"data": 1189.1,
"group": "actual" 
},
{
 "dates": 514,
"data": 1159.6,
"group": "actual" 
},
{
 "dates": 515,
"data": 1192.1,
"group": "actual" 
},
{
 "dates": 516,
"data": 1248.6,
"group": "actual" 
},
{
 "dates": 517,
"data": 1289.8,
"group": "actual" 
},
{
 "dates": 518,
"data": 1198.8,
"group": "actual" 
},
{
 "dates": 519,
"data": 1319.6,
"group": "actual" 
},
{
 "dates": 520,
"data": 1220.6,
"group": "actual" 
},
{
 "dates": 521,
"data": 1211.1,
"group": "actual" 
},
{
 "dates": 522,
"data": 1321.8,
"group": "actual" 
},
{
 "dates": 523,
"data": 1134.8,
"group": "actual" 
},
{
 "dates": 524,
"data": 1182.5,
"group": "actual" 
},
{
 "dates": 525,
"data":   1165,
"group": "actual" 
},
{
 "dates": 526,
"data": 1169.9,
"group": "actual" 
},
{
 "dates": 527,
"data": 1132.7,
"group": "actual" 
},
{
 "dates": 528,
"data": 1255.6,
"group": "actual" 
},
{
 "dates": 529,
"data": 1181.1,
"group": "actual" 
},
{
 "dates": 530,
"data": 1209.1,
"group": "actual" 
},
{
 "dates": 531,
"data": 1180.6,
"group": "actual" 
},
{
 "dates": 532,
"data": 1164.4,
"group": "actual" 
},
{
 "dates": 533,
"data": 1228.6,
"group": "actual" 
},
{
 "dates": 534,
"data": 1185.8,
"group": "actual" 
},
{
 "dates": 535,
"data": 1181.4,
"group": "actual" 
},
{
 "dates": 536,
"data": 1180.5,
"group": "actual" 
},
{
 "dates": 537,
"data": 1270.7,
"group": "actual" 
},
{
 "dates": 538,
"data": 1201.3,
"group": "actual" 
},
{
 "dates": 539,
"data": 1184.7,
"group": "actual" 
},
{
 "dates": 540,
"data":   1173,
"group": "actual" 
},
{
 "dates": 541,
"data": 1230.1,
"group": "actual" 
},
{
 "dates": 542,
"data":   1179,
"group": "actual" 
},
{
 "dates": 543,
"data": 1200.6,
"group": "actual" 
},
{
 "dates": 544,
"data": 1163.9,
"group": "actual" 
},
{
 "dates": 545,
"data": 1229.5,
"group": "actual" 
},
{
 "dates": 546,
"data": 1178.8,
"group": "actual" 
},
{
 "dates": 547,
"data": 1213.6,
"group": "actual" 
},
{
 "dates": 548,
"data": 1218.7,
"group": "actual" 
},
{
 "dates": 549,
"data": 1239.4,
"group": "actual" 
},
{
 "dates": 550,
"data": 1177.4,
"group": "actual" 
},
{
 "dates": 551,
"data": 1215.4,
"group": "actual" 
},
{
 "dates": 552,
"data": 1185.9,
"group": "actual" 
},
{
 "dates": 553,
"data": 1160.8,
"group": "actual" 
},
{
 "dates": 554,
"data": 1231.6,
"group": "actual" 
},
{
 "dates": 555,
"data": 1135.6,
"group": "actual" 
},
{
 "dates": 556,
"data": 1152.5,
"group": "actual" 
},
{
 "dates": 557,
"data": 1174.1,
"group": "actual" 
},
{
 "dates": 558,
"data": 1168.1,
"group": "actual" 
},
{
 "dates": 559,
"data": 1129.8,
"group": "actual" 
},
{
 "dates": 560,
"data": 1199.6,
"group": "actual" 
},
{
 "dates": 561,
"data": 1141.4,
"group": "actual" 
},
{
 "dates": 562,
"data": 1149.4,
"group": "actual" 
},
{
 "dates": 563,
"data": 1167.5,
"group": "actual" 
},
{
 "dates": 564,
"data": 1182.6,
"group": "actual" 
},
{
 "dates": 565,
"data": 1164.1,
"group": "actual" 
},
{
 "dates": 566,
"data": 1209.3,
"group": "actual" 
},
{
 "dates": 567,
"data": 1157.7,
"group": "actual" 
},
{
 "dates": 568,
"data": 1189.8,
"group": "actual" 
},
{
 "dates": 569,
"data": 1112.2,
"group": "actual" 
},
{
 "dates": 570,
"data": 1156.9,
"group": "actual" 
},
{
 "dates": 571,
"data": 1111.9,
"group": "actual" 
},
{
 "dates": 572,
"data": 1195.4,
"group": "actual" 
},
{
 "dates": 573,
"data": 1194.1,
"group": "actual" 
},
{
 "dates": 574,
"data": 1115.5,
"group": "actual" 
},
{
 "dates": 575,
"data": 1136.1,
"group": "actual" 
},
{
 "dates": 576,
"data":   1143,
"group": "actual" 
},
{
 "dates": 577,
"data": 1237.7,
"group": "actual" 
},
{
 "dates": 578,
"data": 1151.5,
"group": "actual" 
},
{
 "dates": 579,
"data": 1103.4,
"group": "actual" 
},
{
 "dates": 580,
"data": 1156.4,
"group": "actual" 
},
{
 "dates": 581,
"data": 1173.2,
"group": "actual" 
},
{
 "dates": 582,
"data": 1166.4,
"group": "actual" 
},
{
 "dates": 583,
"data": 1163.8,
"group": "actual" 
},
{
 "dates": 584,
"data": 1132.8,
"group": "actual" 
},
{
 "dates": 585,
"data": 1100.5,
"group": "actual" 
},
{
 "dates": 586,
"data": 1152.9,
"group": "actual" 
},
{
 "dates": 587,
"data": 1151.7,
"group": "actual" 
},
{
 "dates": 588,
"data": 1134.8,
"group": "actual" 
},
{
 "dates": 589,
"data": 1175.5,
"group": "actual" 
},
{
 "dates": 590,
"data": 1125.3,
"group": "actual" 
},
{
 "dates": 591,
"data": 1165.9,
"group": "actual" 
},
{
 "dates": 592,
"data":   1176,
"group": "actual" 
},
{
 "dates": 593,
"data":   1137,
"group": "actual" 
},
{
 "dates": 594,
"data": 1159.2,
"group": "actual" 
},
{
 "dates": 595,
"data": 1143.4,
"group": "actual" 
},
{
 "dates": 596,
"data": 1077.9,
"group": "actual" 
},
{
 "dates": 597,
"data": 1110.5,
"group": "actual" 
},
{
 "dates": 598,
"data": 1131.8,
"group": "actual" 
},
{
 "dates": 599,
"data": 1109.1,
"group": "actual" 
},
{
 "dates": 600,
"data": 1086.6,
"group": "actual" 
},
{
 "dates": 601,
"data": 1196.5,
"group": "actual" 
},
{
 "dates": 602,
"data": 1216.6,
"group": "actual" 
},
{
 "dates": 603,
"data": 1098.4,
"group": "actual" 
},
{
 "dates": 604,
"data": 1110.2,
"group": "actual" 
},
{
 "dates": 605,
"data": 1156.4,
"group": "actual" 
},
{
 "dates": 606,
"data": 1140.2,
"group": "actual" 
},
{
 "dates": 607,
"data": 1161.3,
"group": "actual" 
},
{
 "dates": 608,
"data":   1144,
"group": "actual" 
},
{
 "dates": 609,
"data": 1103.7,
"group": "actual" 
},
{
 "dates": 610,
"data": 1173.6,
"group": "actual" 
},
{
 "dates": 611,
"data": 1130.3,
"group": "actual" 
},
{
 "dates": 612,
"data": 1065.9,
"group": "actual" 
},
{
 "dates": 613,
"data": 1079.4,
"group": "actual" 
},
{
 "dates": 614,
"data": 1092.5,
"group": "actual" 
},
{
 "dates": 615,
"data": 1152.9,
"group": "actual" 
},
{
 "dates": 616,
"data": 1130.2,
"group": "actual" 
},
{
 "dates": 617,
"data":   1173,
"group": "actual" 
},
{
 "dates": 618,
"data": 1126.2,
"group": "actual" 
},
{
 "dates": 619,
"data": 1116.3,
"group": "actual" 
},
{
 "dates": 620,
"data": 1135.4,
"group": "actual" 
},
{
 "dates": 621,
"data": 1087.4,
"group": "actual" 
},
{
 "dates": 622,
"data": 1148.4,
"group": "actual" 
},
{
 "dates": 623,
"data": 1152.1,
"group": "actual" 
},
{
 "dates": 624,
"data": 1128.7,
"group": "actual" 
},
{
 "dates": 625,
"data": 1108.6,
"group": "actual" 
},
{
 "dates": 626,
"data":   1187,
"group": "actual" 
},
{
 "dates": 627,
"data": 1076.4,
"group": "actual" 
},
{
 "dates": 628,
"data": 1154.9,
"group": "actual" 
},
{
 "dates": 629,
"data": 1118.4,
"group": "actual" 
},
{
 "dates": 630,
"data": 1037.1,
"group": "actual" 
},
{
 "dates": 631,
"data": 1114.9,
"group": "actual" 
},
{
 "dates": 632,
"data": 1113.1,
"group": "actual" 
},
{
 "dates": 633,
"data": 1185.6,
"group": "actual" 
},
{
 "dates": 634,
"data": 1165.1,
"group": "actual" 
},
{
 "dates": 635,
"data": 1132.2,
"group": "actual" 
},
{
 "dates": 636,
"data": 1134.2,
"group": "actual" 
},
{
 "dates": 637,
"data":   1177,
"group": "actual" 
},
{
 "dates": 638,
"data": 1158.7,
"group": "actual" 
},
{
 "dates": 639,
"data": 1166.3,
"group": "actual" 
},
{
 "dates": 640,
"data": 1101.7,
"group": "actual" 
},
{
 "dates": 641,
"data": 1175.8,
"group": "actual" 
},
{
 "dates": 642,
"data": 1088.8,
"group": "actual" 
},
{
 "dates": 643,
"data": 1101.4,
"group": "actual" 
},
{
 "dates": 644,
"data": 1107.7,
"group": "actual" 
},
{
 "dates": 645,
"data": 1158.8,
"group": "actual" 
},
{
 "dates": 646,
"data": 1161.4,
"group": "actual" 
},
{
 "dates": 647,
"data": 1145.2,
"group": "actual" 
},
{
 "dates": 648,
"data": 1199.9,
"group": "actual" 
},
{
 "dates": 649,
"data": 1131.4,
"group": "actual" 
},
{
 "dates": 650,
"data": 1106.2,
"group": "actual" 
},
{
 "dates": 651,
"data": 1094.1,
"group": "actual" 
},
{
 "dates": 652,
"data":   1120,
"group": "actual" 
},
{
 "dates": 653,
"data":   1109,
"group": "actual" 
},
{
 "dates": 654,
"data": 1119.8,
"group": "actual" 
},
{
 "dates": 655,
"data": 1179.6,
"group": "actual" 
},
{
 "dates": 656,
"data": 1127.1,
"group": "actual" 
},
{
 "dates": 657,
"data": 1108.4,
"group": "actual" 
},
{
 "dates": 658,
"data": 1163.1,
"group": "actual" 
},
{
 "dates": 659,
"data": 1116.1,
"group": "actual" 
},
{
 "dates": 660,
"data": 1133.7,
"group": "actual" 
},
{
 "dates": 661,
"data": 1184.1,
"group": "actual" 
},
{
 "dates": 662,
"data": 1105.2,
"group": "actual" 
},
{
 "dates": 663,
"data": 1128.7,
"group": "actual" 
},
{
 "dates": 664,
"data": 1152.5,
"group": "actual" 
},
{
 "dates": 665,
"data": 1096.3,
"group": "actual" 
},
{
 "dates": 666,
"data": 1100.3,
"group": "actual" 
},
{
 "dates": 667,
"data": 1130.2,
"group": "actual" 
},
{
 "dates": 668,
"data": 1171.9,
"group": "actual" 
},
{
 "dates": 669,
"data": 1089.6,
"group": "actual" 
},
{
 "dates": 670,
"data": 1118.5,
"group": "actual" 
},
{
 "dates": 671,
"data":   1150,
"group": "actual" 
},
{
 "dates": 672,
"data": 1102.1,
"group": "actual" 
},
{
 "dates": 673,
"data": 1139.8,
"group": "actual" 
},
{
 "dates": 674,
"data": 1144.5,
"group": "actual" 
},
{
 "dates": 675,
"data": 1109.2,
"group": "actual" 
},
{
 "dates": 676,
"data": 1195.5,
"group": "actual" 
},
{
 "dates": 677,
"data": 1102.2,
"group": "actual" 
},
{
 "dates": 678,
"data": 1138.5,
"group": "actual" 
},
{
 "dates": 679,
"data": 1152.9,
"group": "actual" 
},
{
 "dates": 680,
"data": 1136.1,
"group": "actual" 
},
{
 "dates": 681,
"data": 1119.9,
"group": "actual" 
},
{
 "dates": 682,
"data": 1084.3,
"group": "actual" 
},
{
 "dates": 683,
"data":   1213,
"group": "actual" 
},
{
 "dates": 684,
"data": 1118.3,
"group": "actual" 
},
{
 "dates": 685,
"data": 1152.1,
"group": "actual" 
},
{
 "dates": 686,
"data": 1182.3,
"group": "actual" 
},
{
 "dates": 687,
"data": 1154.9,
"group": "actual" 
},
{
 "dates": 688,
"data": 1167.2,
"group": "actual" 
},
{
 "dates": 689,
"data": 1197.3,
"group": "actual" 
},
{
 "dates": 690,
"data": 1178.7,
"group": "actual" 
},
{
 "dates": 691,
"data": 1126.5,
"group": "actual" 
},
{
 "dates": 692,
"data": 1154.3,
"group": "actual" 
},
{
 "dates": 693,
"data": 1198.4,
"group": "actual" 
},
{
 "dates": 694,
"data": 1130.7,
"group": "actual" 
},
{
 "dates": 695,
"data":   1138,
"group": "actual" 
},
{
 "dates": 696,
"data": 1148.3,
"group": "actual" 
},
{
 "dates": 697,
"data": 1133.8,
"group": "actual" 
},
{
 "dates": 698,
"data": 1223.6,
"group": "actual" 
},
{
 "dates": 699,
"data": 1224.2,
"group": "actual" 
},
{
 "dates": 700,
"data": 1176.4,
"group": "actual" 
},
{
 "dates": 701,
"data": 1137.4,
"group": "actual" 
},
{
 "dates": 702,
"data": 1187.5,
"group": "actual" 
},
{
 "dates": 703,
"data": 1202.2,
"group": "actual" 
},
{
 "dates": 704,
"data": 1224.1,
"group": "actual" 
},
{
 "dates": 705,
"data": 1161.9,
"group": "actual" 
},
{
 "dates": 706,
"data": 1197.8,
"group": "actual" 
},
{
 "dates": 707,
"data": 1160.3,
"group": "actual" 
},
{
 "dates": 708,
"data": 1199.3,
"group": "actual" 
},
{
 "dates": 709,
"data": 1166.5,
"group": "actual" 
},
{
 "dates": 710,
"data": 1256.8,
"group": "actual" 
},
{
 "dates": 711,
"data": 1228.5,
"group": "actual" 
},
{
 "dates": 712,
"data": 1242.1,
"group": "actual" 
},
{
 "dates": 713,
"data": 1222.3,
"group": "actual" 
},
{
 "dates": 714,
"data": 1249.8,
"group": "actual" 
},
{
 "dates": 715,
"data":   1251,
"group": "actual" 
},
{
 "dates": 716,
"data": 1222.6,
"group": "actual" 
},
{
 "dates": 717,
"data": 1170.7,
"group": "actual" 
},
{
 "dates": 718,
"data": 1297.5,
"group": "actual" 
},
{
 "dates": 719,
"data": 1205.8,
"group": "actual" 
},
{
 "dates": 720,
"data": 1231.6,
"group": "actual" 
},
{
 "dates": 721,
"data": 1255.6,
"group": "actual" 
},
{
 "dates": 722,
"data": 1210.7,
"group": "actual" 
},
{
 "dates": 723,
"data": 1210.6,
"group": "actual" 
},
{
 "dates": 724,
"data": 1249.5,
"group": "actual" 
},
{
 "dates": 725,
"data": 1255.7,
"group": "actual" 
},
{
 "dates": 726,
"data":   1193,
"group": "actual" 
},
{
 "dates": 727,
"data":   1260,
"group": "actual" 
},
{
 "dates": 728,
"data": 1284.6,
"group": "actual" 
},
{
 "dates": 729,
"data": 1255.2,
"group": "actual" 
},
{
 "dates": 730,
"data": 1245.5,
"group": "actual" 
},
{
 "dates": 731,
"data": 1209.3,
"group": "actual" 
},
{
 "dates": 732,
"data": 1197.3,
"group": "actual" 
},
{
 "dates": 733,
"data": 1210.3,
"group": "actual" 
},
{
 "dates": 734,
"data": 1239.4,
"group": "actual" 
},
{
 "dates": 735,
"data": 1300.5,
"group": "actual" 
},
{
 "dates": 736,
"data": 1194.7,
"group": "actual" 
},
{
 "dates": 737,
"data": 1311.9,
"group": "actual" 
},
{
 "dates": 738,
"data": 1312.5,
"group": "actual" 
},
{
 "dates": 739,
"data": 1273.8,
"group": "actual" 
},
{
 "dates": 740,
"data": 1297.2,
"group": "actual" 
},
{
 "dates": 741,
"data": 1218.4,
"group": "actual" 
},
{
 "dates": 742,
"data": 1288.4,
"group": "actual" 
},
{
 "dates": 743,
"data": 1292.8,
"group": "actual" 
},
{
 "dates": 744,
"data": 1247.4,
"group": "actual" 
},
{
 "dates": 745,
"data": 1323.9,
"group": "actual" 
},
{
 "dates": 746,
"data": 1373.5,
"group": "actual" 
},
{
 "dates": 747,
"data": 1300.3,
"group": "actual" 
},
{
 "dates": 748,
"data": 1293.2,
"group": "actual" 
},
{
 "dates": 749,
"data": 1230.5,
"group": "actual" 
},
{
 "dates": 750,
"data": 1368.8,
"group": "actual" 
},
{
 "dates": 751,
"data": 1220.1,
"group": "actual" 
},
{
 "dates": 752,
"data": 1273.1,
"group": "actual" 
},
{
 "dates": 753,
"data": 1248.4,
"group": "actual" 
},
{
 "dates": 754,
"data": 1330.7,
"group": "actual" 
},
{
 "dates": 755,
"data":   1325,
"group": "actual" 
},
{
 "dates": 756,
"data": 1284.9,
"group": "actual" 
},
{
 "dates": 757,
"data": 1302.5,
"group": "actual" 
},
{
 "dates": 758,
"data": 1328.7,
"group": "actual" 
},
{
 "dates": 759,
"data": 1309.5,
"group": "actual" 
},
{
 "dates": 760,
"data": 1236.1,
"group": "actual" 
},
{
 "dates": 761,
"data": 1337.1,
"group": "actual" 
},
{
 "dates": 762,
"data": 1318.8,
"group": "actual" 
},
{
 "dates": 763,
"data": 1309.7,
"group": "actual" 
},
{
 "dates": 764,
"data": 1291.7,
"group": "actual" 
},
{
 "dates": 765,
"data": 1296.7,
"group": "actual" 
},
{
 "dates": 766,
"data": 1324.9,
"group": "actual" 
},
{
 "dates": 767,
"data": 1367.3,
"group": "actual" 
},
{
 "dates": 768,
"data":   1335,
"group": "actual" 
},
{
 "dates": 769,
"data": 1288.6,
"group": "actual" 
},
{
 "dates": 770,
"data": 1395.8,
"group": "actual" 
},
{
 "dates": 771,
"data": 1328.3,
"group": "actual" 
},
{
 "dates": 772,
"data": 1206.5,
"group": "actual" 
},
{
 "dates": 773,
"data": 1324.3,
"group": "actual" 
},
{
 "dates": 774,
"data": 1347.4,
"group": "actual" 
},
{
 "dates": 775,
"data": 1347.9,
"group": "actual" 
},
{
 "dates": 776,
"data": 1338.8,
"group": "actual" 
},
{
 "dates": 777,
"data": 1308.7,
"group": "actual" 
},
{
 "dates": 778,
"data": 1363.8,
"group": "actual" 
},
{
 "dates": 779,
"data": 1343.2,
"group": "actual" 
},
{
 "dates": 780,
"data":   1343,
"group": "actual" 
},
{
 "dates": 781,
"data": 1380.2,
"group": "actual" 
},
{
 "dates": 782,
"data": 1324.5,
"group": "actual" 
},
{
 "dates": 783,
"data": 1373.3,
"group": "actual" 
},
{
 "dates": 784,
"data": 1358.9,
"group": "actual" 
},
{
 "dates": 785,
"data": 1336.7,
"group": "actual" 
},
{
 "dates": 786,
"data":   1368,
"group": "actual" 
},
{
 "dates": 787,
"data": 1321.1,
"group": "actual" 
},
{
 "dates": 788,
"data": 1304.7,
"group": "actual" 
},
{
 "dates": 789,
"data": 1354.9,
"group": "actual" 
},
{
 "dates": 790,
"data": 1376.7,
"group": "actual" 
},
{
 "dates": 791,
"data": 1344.1,
"group": "actual" 
},
{
 "dates": 792,
"data": 1327.8,
"group": "actual" 
},
{
 "dates": 793,
"data": 1395.5,
"group": "actual" 
},
{
 "dates": 794,
"data": 1392.3,
"group": "actual" 
},
{
 "dates": 795,
"data": 1350.6,
"group": "actual" 
},
{
 "dates": 796,
"data": 1407.6,
"group": "actual" 
},
{
 "dates": 797,
"data": 1378.6,
"group": "actual" 
},
{
 "dates": 798,
"data":   1283,
"group": "actual" 
},
{
 "dates": 799,
"data": 1377.6,
"group": "actual" 
},
{
 "dates": 800,
"data":   1317,
"group": "actual" 
},
{
 "dates": 801,
"data": 1455.3,
"group": "actual" 
},
{
 "dates": 802,
"data": 1426.1,
"group": "actual" 
},
{
 "dates": 803,
"data": 1367.9,
"group": "actual" 
},
{
 "dates": 804,
"data": 1342.6,
"group": "actual" 
},
{
 "dates": 805,
"data": 1332.9,
"group": "actual" 
},
{
 "dates": 806,
"data": 1326.3,
"group": "actual" 
},
{
 "dates": 807,
"data": 1456.4,
"group": "actual" 
},
{
 "dates": 808,
"data": 1378.8,
"group": "actual" 
},
{
 "dates": 809,
"data": 1326.2,
"group": "actual" 
},
{
 "dates": 810,
"data": 1475.7,
"group": "actual" 
},
{
 "dates": 811,
"data": 1372.6,
"group": "actual" 
},
{
 "dates": 812,
"data":   1220,
"group": "actual" 
},
{
 "dates": 813,
"data": 1382.5,
"group": "actual" 
},
{
 "dates": 814,
"data": 1385.9,
"group": "actual" 
},
{
 "dates": 815,
"data": 1446.3,
"group": "actual" 
},
{
 "dates": 816,
"data": 1406.6,
"group": "actual" 
},
{
 "dates": 817,
"data": 1360.2,
"group": "actual" 
},
{
 "dates": 818,
"data": 1411.9,
"group": "actual" 
},
{
 "dates": 819,
"data": 1319.3,
"group": "actual" 
},
{
 "dates": 820,
"data": 1362.6,
"group": "actual" 
},
{
 "dates": 821,
"data": 1348.7,
"group": "actual" 
},
{
 "dates": 822,
"data": 1394.4,
"group": "actual" 
},
{
 "dates": 823,
"data": 1387.5,
"group": "actual" 
},
{
 "dates": 824,
"data": 1353.4,
"group": "actual" 
},
{
 "dates": 825,
"data":   1350,
"group": "actual" 
},
{
 "dates": 826,
"data": 1332.1,
"group": "actual" 
},
{
 "dates": 827,
"data": 1349.5,
"group": "actual" 
},
{
 "dates": 828,
"data": 1368.6,
"group": "actual" 
},
{
 "dates": 829,
"data": 1346.4,
"group": "actual" 
},
{
 "dates": 830,
"data": 1376.4,
"group": "actual" 
},
{
 "dates": 831,
"data": 1392.4,
"group": "actual" 
},
{
 "dates": 832,
"data": 1318.2,
"group": "actual" 
},
{
 "dates": 833,
"data": 1371.8,
"group": "actual" 
},
{
 "dates": 834,
"data": 1397.8,
"group": "actual" 
},
{
 "dates": 835,
"data": 1374.3,
"group": "actual" 
},
{
 "dates": 836,
"data": 1441.2,
"group": "actual" 
},
{
 "dates": 837,
"data":   1418,
"group": "actual" 
},
{
 "dates": 838,
"data": 1401.4,
"group": "actual" 
},
{
 "dates": 839,
"data": 1432.6,
"group": "actual" 
},
{
 "dates": 840,
"data": 1294.2,
"group": "actual" 
},
{
 "dates": 841,
"data": 1387.3,
"group": "actual" 
},
{
 "dates": 842,
"data": 1381.2,
"group": "actual" 
},
{
 "dates": 843,
"data": 1359.5,
"group": "actual" 
},
{
 "dates": 844,
"data": 1415.4,
"group": "actual" 
},
{
 "dates": 845,
"data": 1383.1,
"group": "actual" 
},
{
 "dates": 846,
"data": 1367.3,
"group": "actual" 
},
{
 "dates": 847,
"data": 1374.8,
"group": "actual" 
},
{
 "dates": 848,
"data": 1437.6,
"group": "actual" 
},
{
 "dates": 849,
"data": 1401.4,
"group": "actual" 
},
{
 "dates": 850,
"data": 1434.5,
"group": "actual" 
},
{
 "dates": 851,
"data": 1375.3,
"group": "actual" 
},
{
 "dates": 852,
"data": 1325.8,
"group": "actual" 
},
{
 "dates": 853,
"data": 1374.5,
"group": "actual" 
},
{
 "dates": 854,
"data": 1385.8,
"group": "actual" 
},
{
 "dates": 855,
"data": 1337.3,
"group": "actual" 
},
{
 "dates": 856,
"data": 1283.1,
"group": "actual" 
},
{
 "dates": 857,
"data": 1394.9,
"group": "actual" 
},
{
 "dates": 858,
"data": 1259.7,
"group": "actual" 
},
{
 "dates": 859,
"data": 1375.8,
"group": "actual" 
},
{
 "dates": 860,
"data": 1350.9,
"group": "actual" 
},
{
 "dates": 861,
"data": 1347.4,
"group": "actual" 
},
{
 "dates": 862,
"data": 1372.5,
"group": "actual" 
},
{
 "dates": 863,
"data": 1346.1,
"group": "actual" 
},
{
 "dates": 864,
"data": 1338.9,
"group": "actual" 
},
{
 "dates": 865,
"data": 1347.4,
"group": "actual" 
},
{
 "dates": 866,
"data": 1379.3,
"group": "actual" 
},
{
 "dates": 867,
"data": 1396.5,
"group": "actual" 
},
{
 "dates": 868,
"data": 1277.9,
"group": "actual" 
},
{
 "dates": 869,
"data": 1368.7,
"group": "actual" 
},
{
 "dates": 870,
"data": 1335.9,
"group": "actual" 
},
{
 "dates": 871,
"data": 1308.1,
"group": "actual" 
},
{
 "dates": 872,
"data": 1414.9,
"group": "actual" 
},
{
 "dates": 873,
"data": 1309.3,
"group": "actual" 
},
{
 "dates": 874,
"data": 1398.7,
"group": "actual" 
},
{
 "dates": 875,
"data": 1296.3,
"group": "actual" 
},
{
 "dates": 876,
"data": 1408.3,
"group": "actual" 
},
{
 "dates": 877,
"data": 1412.2,
"group": "actual" 
},
{
 "dates": 878,
"data": 1329.3,
"group": "actual" 
},
{
 "dates": 879,
"data": 1370.5,
"group": "actual" 
},
{
 "dates": 880,
"data": 1389.7,
"group": "actual" 
},
{
 "dates": 881,
"data": 1397.3,
"group": "actual" 
},
{
 "dates": 882,
"data": 1352.7,
"group": "actual" 
},
{
 "dates": 883,
"data": 1335.3,
"group": "actual" 
},
{
 "dates": 884,
"data": 1328.9,
"group": "actual" 
},
{
 "dates": 885,
"data": 1315.2,
"group": "actual" 
},
{
 "dates": 886,
"data": 1331.8,
"group": "actual" 
},
{
 "dates": 887,
"data": 1327.4,
"group": "actual" 
},
{
 "dates": 888,
"data": 1377.4,
"group": "actual" 
},
{
 "dates": 889,
"data": 1364.8,
"group": "actual" 
},
{
 "dates": 890,
"data": 1327.1,
"group": "actual" 
},
{
 "dates": 891,
"data": 1337.6,
"group": "actual" 
},
{
 "dates": 892,
"data": 1391.7,
"group": "actual" 
},
{
 "dates": 893,
"data": 1348.1,
"group": "actual" 
},
{
 "dates": 894,
"data": 1349.6,
"group": "actual" 
},
{
 "dates": 895,
"data": 1310.7,
"group": "actual" 
},
{
 "dates": 896,
"data":   1341,
"group": "actual" 
},
{
 "dates": 897,
"data": 1357.4,
"group": "actual" 
},
{
 "dates": 898,
"data": 1276.5,
"group": "actual" 
},
{
 "dates": 899,
"data": 1320.8,
"group": "actual" 
},
{
 "dates": 900,
"data": 1253.7,
"group": "actual" 
},
{
 "dates": 901,
"data": 1441.3,
"group": "actual" 
},
{
 "dates": 902,
"data": 1349.3,
"group": "actual" 
},
{
 "dates": 903,
"data": 1378.1,
"group": "actual" 
},
{
 "dates": 904,
"data": 1366.2,
"group": "actual" 
},
{
 "dates": 905,
"data": 1293.9,
"group": "actual" 
},
{
 "dates": 906,
"data":   1275,
"group": "actual" 
},
{
 "dates": 907,
"data": 1258.9,
"group": "actual" 
},
{
 "dates": 908,
"data": 1385.2,
"group": "actual" 
},
{
 "dates": 909,
"data": 1340.2,
"group": "actual" 
},
{
 "dates": 910,
"data": 1368.2,
"group": "actual" 
},
{
 "dates": 911,
"data": 1355.9,
"group": "actual" 
},
{
 "dates": 912,
"data": 1271.1,
"group": "actual" 
},
{
 "dates": 913,
"data": 1327.2,
"group": "actual" 
},
{
 "dates": 914,
"data": 1283.5,
"group": "actual" 
},
{
 "dates": 915,
"data": 1282.3,
"group": "actual" 
},
{
 "dates": 916,
"data": 1379.6,
"group": "actual" 
},
{
 "dates": 917,
"data": 1346.6,
"group": "actual" 
},
{
 "dates": 918,
"data": 1321.4,
"group": "actual" 
},
{
 "dates": 919,
"data": 1291.8,
"group": "actual" 
},
{
 "dates": 920,
"data": 1285.4,
"group": "actual" 
},
{
 "dates": 921,
"data": 1258.3,
"group": "actual" 
},
{
 "dates": 922,
"data": 1298.7,
"group": "actual" 
},
{
 "dates": 923,
"data": 1277.9,
"group": "actual" 
},
{
 "dates": 924,
"data": 1325.6,
"group": "actual" 
},
{
 "dates": 925,
"data": 1307.5,
"group": "actual" 
},
{
 "dates": 926,
"data": 1264.3,
"group": "actual" 
},
{
 "dates": 927,
"data": 1339.3,
"group": "actual" 
},
{
 "dates": 928,
"data": 1315.6,
"group": "actual" 
},
{
 "dates": 929,
"data": 1282.9,
"group": "actual" 
},
{
 "dates": 930,
"data": 1368.8,
"group": "actual" 
},
{
 "dates": 931,
"data":   1298,
"group": "actual" 
},
{
 "dates": 932,
"data": 1179.1,
"group": "actual" 
},
{
 "dates": 933,
"data":   1253,
"group": "actual" 
},
{
 "dates": 934,
"data": 1280.7,
"group": "actual" 
},
{
 "dates": 935,
"data": 1320.9,
"group": "actual" 
},
{
 "dates": 936,
"data": 1235.7,
"group": "actual" 
},
{
 "dates": 937,
"data": 1287.3,
"group": "actual" 
},
{
 "dates": 938,
"data": 1311.1,
"group": "actual" 
},
{
 "dates": 939,
"data": 1272.6,
"group": "actual" 
},
{
 "dates": 940,
"data": 1275.6,
"group": "actual" 
},
{
 "dates": 941,
"data": 1271.6,
"group": "actual" 
},
{
 "dates": 942,
"data": 1239.2,
"group": "actual" 
},
{
 "dates": 943,
"data": 1269.4,
"group": "actual" 
},
{
 "dates": 944,
"data": 1303.5,
"group": "actual" 
},
{
 "dates": 945,
"data":   1215,
"group": "actual" 
},
{
 "dates": 946,
"data": 1296.2,
"group": "actual" 
},
{
 "dates": 947,
"data": 1297.8,
"group": "actual" 
},
{
 "dates": 948,
"data": 1293.5,
"group": "actual" 
},
{
 "dates": 949,
"data": 1257.9,
"group": "actual" 
},
{
 "dates": 950,
"data": 1265.5,
"group": "actual" 
},
{
 "dates": 951,
"data": 1342.1,
"group": "actual" 
},
{
 "dates": 952,
"data": 1279.5,
"group": "actual" 
},
{
 "dates": 953,
"data": 1241.7,
"group": "actual" 
},
{
 "dates": 954,
"data": 1301.1,
"group": "actual" 
},
{
 "dates": 955,
"data": 1202.3,
"group": "actual" 
},
{
 "dates": 956,
"data": 1294.2,
"group": "actual" 
},
{
 "dates": 957,
"data": 1231.3,
"group": "actual" 
},
{
 "dates": 958,
"data": 1285.2,
"group": "actual" 
},
{
 "dates": 959,
"data": 1246.5,
"group": "actual" 
},
{
 "dates": 960,
"data": 1307.6,
"group": "actual" 
},
{
 "dates": 961,
"data": 1362.4,
"group": "actual" 
},
{
 "dates": 962,
"data":   1275,
"group": "actual" 
},
{
 "dates": 963,
"data": 1248.7,
"group": "actual" 
},
{
 "dates": 964,
"data": 1184.6,
"group": "actual" 
},
{
 "dates": 965,
"data": 1319.9,
"group": "actual" 
},
{
 "dates": 966,
"data": 1165.8,
"group": "actual" 
},
{
 "dates": 967,
"data": 1264.7,
"group": "actual" 
},
{
 "dates": 968,
"data":   1253,
"group": "actual" 
},
{
 "dates": 969,
"data": 1294.3,
"group": "actual" 
},
{
 "dates": 970,
"data": 1216.6,
"group": "actual" 
},
{
 "dates": 971,
"data": 1269.8,
"group": "actual" 
},
{
 "dates": 972,
"data": 1214.2,
"group": "actual" 
},
{
 "dates": 973,
"data": 1313.1,
"group": "actual" 
},
{
 "dates": 974,
"data": 1241.7,
"group": "actual" 
},
{
 "dates": 975,
"data": 1235.6,
"group": "actual" 
},
{
 "dates": 976,
"data": 1236.2,
"group": "actual" 
},
{
 "dates": 977,
"data": 1227.1,
"group": "actual" 
},
{
 "dates": 978,
"data": 1209.7,
"group": "actual" 
},
{
 "dates": 979,
"data": 1314.3,
"group": "actual" 
},
{
 "dates": 980,
"data": 1258.3,
"group": "actual" 
},
{
 "dates": 981,
"data":   1214,
"group": "actual" 
},
{
 "dates": 982,
"data": 1215.3,
"group": "actual" 
},
{
 "dates": 983,
"data":   1287,
"group": "actual" 
},
{
 "dates": 984,
"data": 1232.4,
"group": "actual" 
},
{
 "dates": 985,
"data": 1212.1,
"group": "actual" 
},
{
 "dates": 986,
"data": 1264.5,
"group": "actual" 
},
{
 "dates": 987,
"data":   1256,
"group": "actual" 
},
{
 "dates": 988,
"data": 1211.5,
"group": "actual" 
},
{
 "dates": 989,
"data": 1311.8,
"group": "actual" 
},
{
 "dates": 990,
"data": 1245.1,
"group": "actual" 
},
{
 "dates": 991,
"data": 1275.4,
"group": "actual" 
},
{
 "dates": 992,
"data": 1218.1,
"group": "actual" 
},
{
 "dates": 993,
"data":   1178,
"group": "actual" 
},
{
 "dates": 994,
"data": 1258.9,
"group": "actual" 
},
{
 "dates": 995,
"data": 1204.2,
"group": "actual" 
},
{
 "dates": 996,
"data": 1242.6,
"group": "actual" 
},
{
 "dates": 997,
"data": 1202.7,
"group": "actual" 
},
{
 "dates": 998,
"data": 1215.7,
"group": "actual" 
},
{
 "dates": 999,
"data": 1213.3,
"group": "actual" 
},
{
 "dates": 1000,
"data": 1272.3,
"group": "actual" 
},
{
 "dates": 1001,
"data": 1232.5,
"group": "actual" 
},
{
 "dates": 1002,
"data": 1277.3,
"group": "actual" 
},
{
 "dates": 1003,
"data": 1227.5,
"group": "actual" 
},
{
 "dates": 1004,
"data": 1242.5,
"group": "actual" 
},
{
 "dates": 1005,
"data": 1303.2,
"group": "actual" 
},
{
 "dates": 1006,
"data": 1281.2,
"group": "actual" 
},
{
 "dates": 1007,
"data": 1278.4,
"group": "actual" 
},
{
 "dates": 1008,
"data": 1289.7,
"group": "actual" 
},
{
 "dates": 1009,
"data": 1228.6,
"group": "actual" 
},
{
 "dates": 1010,
"data": 1295.8,
"group": "actual" 
},
{
 "dates": 1011,
"data": 1259.4,
"group": "actual" 
},
{
 "dates": 1012,
"data": 1239.5,
"group": "actual" 
},
{
 "dates": 1013,
"data": 1235.4,
"group": "actual" 
},
{
 "dates": 1014,
"data": 1232.3,
"group": "actual" 
},
{
 "dates": 1015,
"data": 1295.8,
"group": "actual" 
},
{
 "dates": 1016,
"data": 1275.6,
"group": "actual" 
},
{
 "dates": 1017,
"data": 1340.5,
"group": "actual" 
},
{
 "dates": 1018,
"data": 1263.4,
"group": "actual" 
},
{
 "dates": 1019,
"data": 1276.3,
"group": "actual" 
},
{
 "dates": 1020,
"data": 1212.9,
"group": "actual" 
},
{
 "dates": 1021,
"data": 1282.4,
"group": "actual" 
},
{
 "dates": 1022,
"data": 1246.4,
"group": "actual" 
},
{
 "dates": 1023,
"data": 1336.5,
"group": "actual" 
},
{
 "dates": 1024,
"data": 1214.2,
"group": "actual" 
},
{
 "dates": 1025,
"data": 1232.7,
"group": "actual" 
},
{
 "dates": 1026,
"data": 1226.8,
"group": "actual" 
},
{
 "dates": 1027,
"data":   1230,
"group": "actual" 
},
{
 "dates": 1028,
"data": 1256.3,
"group": "actual" 
},
{
 "dates": 1029,
"data": 1235.4,
"group": "actual" 
},
{
 "dates": 1030,
"data": 1251.6,
"group": "actual" 
},
{
 "dates": 1031,
"data": 1211.1,
"group": "actual" 
},
{
 "dates": 1032,
"data": 1215.2,
"group": "actual" 
},
{
 "dates": 1033,
"data": 1269.7,
"group": "actual" 
},
{
 "dates": 1034,
"data": 1274.4,
"group": "actual" 
},
{
 "dates": 1035,
"data":   1234,
"group": "actual" 
},
{
 "dates": 1036,
"data": 1254.8,
"group": "actual" 
},
{
 "dates": 1037,
"data": 1278.4,
"group": "actual" 
},
{
 "dates": 1038,
"data": 1288.8,
"group": "actual" 
},
{
 "dates": 1039,
"data":   1259,
"group": "actual" 
},
{
 "dates": 1040,
"data": 1255.3,
"group": "actual" 
},
{
 "dates": 1041,
"data": 1266.9,
"group": "actual" 
},
{
 "dates": 1042,
"data": 1279.9,
"group": "actual" 
},
{
 "dates": 1043,
"data": 1301.2,
"group": "actual" 
},
{
 "dates": 1044,
"data": 1277.4,
"group": "actual" 
},
{
 "dates": 1045,
"data": 1376.9,
"group": "actual" 
},
{
 "dates": 1046,
"data": 1300.3,
"group": "actual" 
},
{
 "dates": 1047,
"data": 1306.7,
"group": "actual" 
},
{
 "dates": 1048,
"data": 1288.7,
"group": "actual" 
},
{
 "dates": 1049,
"data": 1302.3,
"group": "actual" 
},
{
 "dates": 1050,
"data": 1326.7,
"group": "actual" 
},
{
 "dates": 1051,
"data": 1333.3,
"group": "actual" 
},
{
 "dates": 1052,
"data": 1280.6,
"group": "actual" 
},
{
 "dates": 1053,
"data": 1246.9,
"group": "actual" 
},
{
 "dates": 1054,
"data": 1370.1,
"group": "actual" 
},
{
 "dates": 1055,
"data":   1320,
"group": "actual" 
},
{
 "dates": 1056,
"data": 1327.7,
"group": "actual" 
},
{
 "dates": 1057,
"data": 1343.3,
"group": "actual" 
},
{
 "dates": 1058,
"data": 1317.9,
"group": "actual" 
},
{
 "dates": 1059,
"data": 1327.7,
"group": "actual" 
},
{
 "dates": 1060,
"data": 1309.8,
"group": "actual" 
},
{
 "dates": 1061,
"data":   1310,
"group": "actual" 
},
{
 "dates": 1062,
"data": 1276.2,
"group": "actual" 
},
{
 "dates": 1063,
"data": 1277.3,
"group": "actual" 
},
{
 "dates": 1064,
"data":   1359,
"group": "actual" 
},
{
 "dates": 1065,
"data": 1319.3,
"group": "actual" 
},
{
 "dates": 1066,
"data": 1263.7,
"group": "actual" 
},
{
 "dates": 1067,
"data": 1321.7,
"group": "actual" 
},
{
 "dates": 1068,
"data": 1299.9,
"group": "actual" 
},
{
 "dates": 1069,
"data": 1352.6,
"group": "actual" 
},
{
 "dates": 1070,
"data":   1309,
"group": "actual" 
},
{
 "dates": 1071,
"data": 1345.3,
"group": "actual" 
},
{
 "dates": 1072,
"data": 1364.9,
"group": "actual" 
},
{
 "dates": 1073,
"data":   1327,
"group": "actual" 
},
{
 "dates": 1074,
"data": 1339.3,
"group": "actual" 
},
{
 "dates": 1075,
"data": 1350.1,
"group": "actual" 
},
{
 "dates": 1076,
"data": 1263.2,
"group": "actual" 
},
{
 "dates": 1077,
"data": 1320.9,
"group": "actual" 
},
{
 "dates": 1078,
"data": 1307.6,
"group": "actual" 
},
{
 "dates": 1079,
"data": 1378.3,
"group": "actual" 
},
{
 "dates": 1080,
"data": 1340.4,
"group": "actual" 
},
{
 "dates": 1081,
"data": 1404.8,
"group": "actual" 
},
{
 "dates": 1082,
"data": 1297.6,
"group": "actual" 
},
{
 "dates": 1083,
"data": 1408.8,
"group": "actual" 
},
{
 "dates": 1084,
"data":   1368,
"group": "actual" 
},
{
 "dates": 1085,
"data": 1319.7,
"group": "actual" 
},
{
 "dates": 1086,
"data": 1336.2,
"group": "actual" 
},
{
 "dates": 1087,
"data": 1394.1,
"group": "actual" 
},
{
 "dates": 1088,
"data": 1346.1,
"group": "actual" 
},
{
 "dates": 1089,
"data":   1300,
"group": "actual" 
},
{
 "dates": 1090,
"data": 1313.4,
"group": "actual" 
},
{
 "dates": 1091,
"data": 1319.9,
"group": "actual" 
},
{
 "dates": 1092,
"data": 1376.5,
"group": "actual" 
},
{
 "dates": 1093,
"data": 1374.7,
"group": "actual" 
},
{
 "dates": 1094,
"data": 1374.1,
"group": "actual" 
},
{
 "dates": 1095,
"data": 1383.5,
"group": "actual" 
},
{
 "dates": 1096,
"data": 1310.4,
"group": "actual" 
},
{
 "dates": 1097,
"data": 1435.3,
"group": "actual" 
},
{
 "dates": 1098,
"data": 1331.9,
"group": "actual" 
},
{
 "dates": 1099,
"data": 1367.9,
"group": "actual" 
},
{
 "dates": 1100,
"data":   1368,
"group": "actual" 
},
{
 "dates": 1101,
"data": 1395.1,
"group": "actual" 
},
{
 "dates": 1102,
"data":   1400,
"group": "actual" 
},
{
 "dates": 1103,
"data": 1400.8,
"group": "actual" 
},
{
 "dates": 1104,
"data": 1374.5,
"group": "actual" 
},
{
 "dates": 1105,
"data": 1369.1,
"group": "actual" 
},
{
 "dates": 1106,
"data": 1396.1,
"group": "actual" 
},
{
 "dates": 1107,
"data": 1333.3,
"group": "actual" 
},
{
 "dates": 1108,
"data": 1446.8,
"group": "actual" 
},
{
 "dates": 1109,
"data": 1485.6,
"group": "actual" 
},
{
 "dates": 1110,
"data": 1419.6,
"group": "actual" 
},
{
 "dates": 1111,
"data": 1457.4,
"group": "actual" 
},
{
 "dates": 1112,
"data": 1427.2,
"group": "actual" 
},
{
 "dates": 1113,
"data": 1437.3,
"group": "actual" 
},
{
 "dates": 1114,
"data": 1365.8,
"group": "actual" 
},
{
 "dates": 1115,
"data": 1443.8,
"group": "actual" 
},
{
 "dates": 1116,
"data": 1360.1,
"group": "actual" 
},
{
 "dates": 1117,
"data": 1491.6,
"group": "actual" 
},
{
 "dates": 1118,
"data":   1424,
"group": "actual" 
},
{
 "dates": 1119,
"data":   1398,
"group": "actual" 
},
{
 "dates": 1120,
"data": 1329.1,
"group": "actual" 
},
{
 "dates": 1121,
"data": 1402.7,
"group": "actual" 
},
{
 "dates": 1122,
"data": 1453.7,
"group": "actual" 
},
{
 "dates": 1123,
"data": 1491.4,
"group": "actual" 
},
{
 "dates": 1124,
"data": 1512.6,
"group": "actual" 
},
{
 "dates": 1125,
"data": 1480.5,
"group": "actual" 
},
{
 "dates": 1126,
"data": 1445.5,
"group": "actual" 
},
{
 "dates": 1127,
"data": 1428.1,
"group": "actual" 
},
{
 "dates": 1128,
"data": 1404.5,
"group": "actual" 
},
{
 "dates": 1129,
"data": 1454.2,
"group": "actual" 
},
{
 "dates": 1130,
"data": 1392.1,
"group": "actual" 
},
{
 "dates": 1131,
"data":   1502,
"group": "actual" 
},
{
 "dates": 1132,
"data": 1418.1,
"group": "actual" 
},
{
 "dates": 1133,
"data": 1425.3,
"group": "actual" 
},
{
 "dates": 1134,
"data": 1430.2,
"group": "actual" 
},
{
 "dates": 1135,
"data": 1425.8,
"group": "actual" 
},
{
 "dates": 1136,
"data": 1407.1,
"group": "actual" 
},
{
 "dates": 1137,
"data": 1483.2,
"group": "actual" 
},
{
 "dates": 1138,
"data": 1459.3,
"group": "actual" 
},
{
 "dates": 1139,
"data": 1381.6,
"group": "actual" 
},
{
 "dates": 1140,
"data": 1458.2,
"group": "actual" 
},
{
 "dates": 1141,
"data": 1449.7,
"group": "actual" 
},
{
 "dates": 1142,
"data": 1537.8,
"group": "actual" 
},
{
 "dates": 1143,
"data": 1457.3,
"group": "actual" 
},
{
 "dates": 1144,
"data": 1517.4,
"group": "actual" 
},
{
 "dates": 1145,
"data": 1487.5,
"group": "actual" 
},
{
 "dates": 1146,
"data": 1488.5,
"group": "actual" 
},
{
 "dates": 1147,
"data": 1405.6,
"group": "actual" 
},
{
 "dates": 1148,
"data": 1445.1,
"group": "actual" 
},
{
 "dates": 1149,
"data": 1480.5,
"group": "actual" 
},
{
 "dates": 1150,
"data": 1462.9,
"group": "actual" 
},
{
 "dates": 1151,
"data": 1525.7,
"group": "actual" 
},
{
 "dates": 1152,
"data": 1440.3,
"group": "actual" 
},
{
 "dates": 1153,
"data": 1434.7,
"group": "actual" 
},
{
 "dates": 1154,
"data": 1447.2,
"group": "actual" 
},
{
 "dates": 1155,
"data": 1539.5,
"group": "actual" 
},
{
 "dates": 1156,
"data": 1435.8,
"group": "actual" 
},
{
 "dates": 1157,
"data": 1473.4,
"group": "actual" 
},
{
 "dates": 1158,
"data": 1418.1,
"group": "actual" 
},
{
 "dates": 1159,
"data": 1468.8,
"group": "actual" 
},
{
 "dates": 1160,
"data": 1414.2,
"group": "actual" 
},
{
 "dates": 1161,
"data": 1434.1,
"group": "actual" 
},
{
 "dates": 1162,
"data":   1383,
"group": "actual" 
},
{
 "dates": 1163,
"data": 1498.1,
"group": "actual" 
},
{
 "dates": 1164,
"data": 1549.4,
"group": "actual" 
},
{
 "dates": 1165,
"data": 1485.6,
"group": "actual" 
},
{
 "dates": 1166,
"data": 1493.7,
"group": "actual" 
},
{
 "dates": 1167,
"data": 1549.9,
"group": "actual" 
},
{
 "dates": 1168,
"data": 1498.2,
"group": "actual" 
},
{
 "dates": 1169,
"data":   1564,
"group": "actual" 
},
{
 "dates": 1170,
"data": 1461.3,
"group": "actual" 
},
{
 "dates": 1171,
"data": 1533.6,
"group": "actual" 
},
{
 "dates": 1172,
"data": 1449.5,
"group": "actual" 
},
{
 "dates": 1173,
"data": 1546.3,
"group": "actual" 
},
{
 "dates": 1174,
"data": 1500.4,
"group": "actual" 
},
{
 "dates": 1175,
"data": 1486.6,
"group": "actual" 
},
{
 "dates": 1176,
"data": 1478.1,
"group": "actual" 
},
{
 "dates": 1177,
"data": 1551.1,
"group": "actual" 
},
{
 "dates": 1178,
"data": 1451.6,
"group": "actual" 
},
{
 "dates": 1179,
"data": 1511.4,
"group": "actual" 
},
{
 "dates": 1180,
"data": 1425.2,
"group": "actual" 
},
{
 "dates": 1181,
"data": 1506.6,
"group": "actual" 
},
{
 "dates": 1182,
"data": 1486.8,
"group": "actual" 
},
{
 "dates": 1183,
"data": 1512.6,
"group": "actual" 
},
{
 "dates": 1184,
"data":   1476,
"group": "actual" 
},
{
 "dates": 1185,
"data":   1578,
"group": "actual" 
},
{
 "dates": 1186,
"data": 1474.5,
"group": "actual" 
},
{
 "dates": 1187,
"data": 1614.7,
"group": "actual" 
},
{
 "dates": 1188,
"data": 1445.8,
"group": "actual" 
},
{
 "dates": 1189,
"data": 1539.5,
"group": "actual" 
},
{
 "dates": 1190,
"data": 1520.9,
"group": "actual" 
},
{
 "dates": 1191,
"data": 1520.6,
"group": "actual" 
},
{
 "dates": 1192,
"data": 1505.4,
"group": "actual" 
},
{
 "dates": 1193,
"data": 1550.5,
"group": "actual" 
},
{
 "dates": 1194,
"data": 1421.2,
"group": "actual" 
},
{
 "dates": 1195,
"data": 1484.7,
"group": "actual" 
},
{
 "dates": 1196,
"data": 1623.7,
"group": "actual" 
},
{
 "dates": 1197,
"data": 1607.2,
"group": "actual" 
},
{
 "dates": 1198,
"data": 1525.6,
"group": "actual" 
},
{
 "dates": 1199,
"data": 1563.9,
"group": "actual" 
},
{
 "dates": 1200,
"data": 1515.4,
"group": "actual" 
},
{
 "dates": 1201,
"data": 1427.1,
"group": "actual" 
},
{
 "dates": 1202,
"data": 1509.6,
"group": "actual" 
},
{
 "dates": 1203,
"data":   1505,
"group": "actual" 
},
{
 "dates": 1204,
"data": 1565.1,
"group": "actual" 
},
{
 "dates": 1205,
"data": 1442.7,
"group": "actual" 
},
{
 "dates": 1206,
"data": 1557.9,
"group": "actual" 
},
{
 "dates": 1207,
"data": 1481.8,
"group": "actual" 
},
{
 "dates": 1208,
"data": 1556.8,
"group": "actual" 
},
{
 "dates": 1209,
"data":   1544,
"group": "actual" 
},
{
 "dates": 1210,
"data": 1499.6,
"group": "actual" 
},
{
 "dates": 1211,
"data": 1587.4,
"group": "actual" 
},
{
 "dates": 1212,
"data": 1478.8,
"group": "actual" 
},
{
 "dates": 1213,
"data": 1509.6,
"group": "actual" 
},
{
 "dates": 1214,
"data": 1458.6,
"group": "actual" 
},
{
 "dates": 1215,
"data": 1481.5,
"group": "actual" 
},
{
 "dates": 1216,
"data": 1521.2,
"group": "actual" 
},
{
 "dates": 1217,
"data": 1523.6,
"group": "actual" 
},
{
 "dates": 1218,
"data": 1441.5,
"group": "actual" 
},
{
 "dates": 1219,
"data": 1588.2,
"group": "actual" 
},
{
 "dates": 1220,
"data": 1545.8,
"group": "actual" 
},
{
 "dates": 1221,
"data": 1509.1,
"group": "actual" 
},
{
 "dates": 1222,
"data": 1551.3,
"group": "actual" 
},
{
 "dates": 1223,
"data": 1391.7,
"group": "actual" 
},
{
 "dates": 1224,
"data": 1505.3,
"group": "actual" 
},
{
 "dates": 1225,
"data":   1509,
"group": "actual" 
},
{
 "dates": 1226,
"data": 1495.8,
"group": "actual" 
},
{
 "dates": 1227,
"data": 1470.7,
"group": "actual" 
},
{
 "dates": 1228,
"data": 1496.5,
"group": "actual" 
},
{
 "dates": 1229,
"data": 1541.6,
"group": "actual" 
},
{
 "dates": 1230,
"data": 1554.4,
"group": "actual" 
},
{
 "dates": 1231,
"data": 1526.2,
"group": "actual" 
},
{
 "dates": 1232,
"data": 1546.7,
"group": "actual" 
},
{
 "dates": 1233,
"data": 1457.1,
"group": "actual" 
},
{
 "dates": 1234,
"data":   1451,
"group": "actual" 
},
{
 "dates": 1235,
"data": 1414.4,
"group": "actual" 
},
{
 "dates": 1236,
"data": 1458.9,
"group": "actual" 
},
{
 "dates": 1237,
"data": 1386.3,
"group": "actual" 
},
{
 "dates": 1238,
"data": 1441.9,
"group": "actual" 
},
{
 "dates": 1239,
"data":   1557,
"group": "actual" 
},
{
 "dates": 1240,
"data": 1422.2,
"group": "actual" 
},
{
 "dates": 1241,
"data": 1500.1,
"group": "actual" 
},
{
 "dates": 1242,
"data": 1479.1,
"group": "actual" 
},
{
 "dates": 1243,
"data": 1463.8,
"group": "actual" 
},
{
 "dates": 1244,
"data": 1544.9,
"group": "actual" 
},
{
 "dates": 1245,
"data": 1518.2,
"group": "actual" 
},
{
 "dates": 1246,
"data": 1458.1,
"group": "actual" 
},
{
 "dates": 1247,
"data": 1557.8,
"group": "actual" 
},
{
 "dates": 1248,
"data": 1437.8,
"group": "actual" 
},
{
 "dates": 1249,
"data": 1487.3,
"group": "actual" 
},
{
 "dates": 1250,
"data": 1520.4,
"group": "actual" 
},
{
 "dates": 1251,
"data": 1487.1,
"group": "actual" 
},
{
 "dates": 1252,
"data":   1491,
"group": "actual" 
},
{
 "dates": 1253,
"data": 1430.8,
"group": "actual" 
},
{
 "dates": 1254,
"data": 1498.1,
"group": "actual" 
},
{
 "dates": 1255,
"data": 1467.3,
"group": "actual" 
},
{
 "dates": 1256,
"data": 1466.1,
"group": "actual" 
},
{
 "dates": 1257,
"data":   1518,
"group": "actual" 
},
{
 "dates": 1258,
"data": 1465.2,
"group": "actual" 
},
{
 "dates": 1259,
"data":   1489,
"group": "actual" 
},
{
 "dates": 1260,
"data": 1391.7,
"group": "actual" 
},
{
 "dates": 1261,
"data": 1462.4,
"group": "actual" 
},
{
 "dates": 1262,
"data": 1490.4,
"group": "actual" 
},
{
 "dates": 1263,
"data": 1445.1,
"group": "actual" 
},
{
 "dates": 1264,
"data": 1461.5,
"group": "actual" 
},
{
 "dates": 1265,
"data": 1482.2,
"group": "actual" 
},
{
 "dates": 1266,
"data": 1446.6,
"group": "actual" 
},
{
 "dates": 1267,
"data": 1445.6,
"group": "actual" 
},
{
 "dates": 1268,
"data": 1445.6,
"group": "actual" 
},
{
 "dates": 1269,
"data": 1469.8,
"group": "actual" 
},
{
 "dates": 1270,
"data": 1421.7,
"group": "actual" 
},
{
 "dates": 1271,
"data": 1433.9,
"group": "actual" 
},
{
 "dates": 1272,
"data": 1511.7,
"group": "actual" 
},
{
 "dates": 1273,
"data": 1500.6,
"group": "actual" 
},
{
 "dates": 1274,
"data": 1415.6,
"group": "actual" 
},
{
 "dates": 1275,
"data": 1435.4,
"group": "actual" 
},
{
 "dates": 1276,
"data": 1421.1,
"group": "actual" 
},
{
 "dates": 1277,
"data": 1489.8,
"group": "actual" 
},
{
 "dates": 1278,
"data": 1451.4,
"group": "actual" 
},
{
 "dates": 1279,
"data":   1390,
"group": "actual" 
},
{
 "dates": 1280,
"data": 1424.2,
"group": "actual" 
},
{
 "dates": 1281,
"data": 1491.4,
"group": "actual" 
},
{
 "dates": 1282,
"data": 1453.1,
"group": "actual" 
},
{
 "dates": 1283,
"data": 1412.2,
"group": "actual" 
},
{
 "dates": 1284,
"data": 1491.7,
"group": "actual" 
},
{
 "dates": 1285,
"data":   1421,
"group": "actual" 
},
{
 "dates": 1286,
"data": 1473.2,
"group": "actual" 
},
{
 "dates": 1287,
"data": 1458.8,
"group": "actual" 
},
{
 "dates": 1288,
"data": 1384.1,
"group": "actual" 
},
{
 "dates": 1289,
"data": 1511.5,
"group": "actual" 
},
{
 "dates": 1290,
"data": 1423.7,
"group": "actual" 
},
{
 "dates": 1291,
"data": 1432.3,
"group": "actual" 
},
{
 "dates": 1292,
"data": 1367.8,
"group": "actual" 
},
{
 "dates": 1293,
"data": 1379.4,
"group": "actual" 
},
{
 "dates": 1294,
"data": 1388.3,
"group": "actual" 
},
{
 "dates": 1295,
"data": 1389.1,
"group": "actual" 
},
{
 "dates": 1296,
"data": 1428.5,
"group": "actual" 
},
{
 "dates": 1297,
"data": 1404.8,
"group": "actual" 
},
{
 "dates": 1298,
"data": 1467.4,
"group": "actual" 
},
{
 "dates": 1299,
"data": 1438.7,
"group": "actual" 
},
{
 "dates": 1300,
"data": 1370.6,
"group": "actual" 
},
{
 "dates": 1301,
"data":   1432,
"group": "actual" 
},
{
 "dates": 1302,
"data": 1417.9,
"group": "actual" 
},
{
 "dates": 1303,
"data": 1411.4,
"group": "actual" 
},
{
 "dates": 1304,
"data": 1492.7,
"group": "actual" 
},
{
 "dates": 1305,
"data": 1455.6,
"group": "actual" 
},
{
 "dates": 1306,
"data": 1393.5,
"group": "actual" 
},
{
 "dates": 1307,
"data": 1444.1,
"group": "actual" 
},
{
 "dates": 1308,
"data": 1372.2,
"group": "actual" 
},
{
 "dates": 1309,
"data": 1439.2,
"group": "actual" 
},
{
 "dates": 1310,
"data": 1418.4,
"group": "actual" 
},
{
 "dates": 1311,
"data": 1463.3,
"group": "actual" 
},
{
 "dates": 1312,
"data": 1399.5,
"group": "actual" 
},
{
 "dates": 1313,
"data": 1442.8,
"group": "actual" 
},
{
 "dates": 1314,
"data": 1366.8,
"group": "actual" 
},
{
 "dates": 1315,
"data": 1385.7,
"group": "actual" 
},
{
 "dates": 1316,
"data": 1343.4,
"group": "actual" 
},
{
 "dates": 1317,
"data": 1378.1,
"group": "actual" 
},
{
 "dates": 1318,
"data": 1335.3,
"group": "actual" 
},
{
 "dates": 1319,
"data":   1341,
"group": "actual" 
},
{
 "dates": 1320,
"data": 1425.5,
"group": "actual" 
},
{
 "dates": 1321,
"data": 1287.6,
"group": "actual" 
},
{
 "dates": 1322,
"data": 1275.8,
"group": "actual" 
},
{
 "dates": 1323,
"data": 1374.9,
"group": "actual" 
},
{
 "dates": 1324,
"data": 1363.9,
"group": "actual" 
},
{
 "dates": 1325,
"data": 1432.2,
"group": "actual" 
},
{
 "dates": 1326,
"data": 1400.3,
"group": "actual" 
},
{
 "dates": 1327,
"data": 1320.9,
"group": "actual" 
},
{
 "dates": 1328,
"data": 1431.1,
"group": "actual" 
},
{
 "dates": 1329,
"data": 1452.2,
"group": "actual" 
},
{
 "dates": 1330,
"data": 1332.8,
"group": "actual" 
},
{
 "dates": 1331,
"data": 1413.5,
"group": "actual" 
},
{
 "dates": 1332,
"data": 1370.6,
"group": "actual" 
},
{
 "dates": 1333,
"data": 1399.6,
"group": "actual" 
},
{
 "dates": 1334,
"data": 1374.8,
"group": "actual" 
},
{
 "dates": 1335,
"data":   1355,
"group": "actual" 
},
{
 "dates": 1336,
"data": 1399.1,
"group": "actual" 
},
{
 "dates": 1337,
"data": 1420.2,
"group": "actual" 
},
{
 "dates": 1338,
"data": 1414.2,
"group": "actual" 
},
{
 "dates": 1339,
"data": 1419.8,
"group": "actual" 
},
{
 "dates": 1340,
"data": 1418.9,
"group": "actual" 
},
{
 "dates": 1341,
"data": 1396.9,
"group": "actual" 
},
{
 "dates": 1342,
"data": 1400.7,
"group": "actual" 
},
{
 "dates": 1343,
"data": 1369.4,
"group": "actual" 
},
{
 "dates": 1344,
"data": 1408.2,
"group": "actual" 
},
{
 "dates": 1345,
"data": 1409.2,
"group": "actual" 
},
{
 "dates": 1346,
"data": 1417.4,
"group": "actual" 
},
{
 "dates": 1347,
"data": 1446.5,
"group": "actual" 
},
{
 "dates": 1348,
"data": 1270.9,
"group": "actual" 
},
{
 "dates": 1349,
"data": 1452.2,
"group": "actual" 
},
{
 "dates": 1350,
"data": 1365.7,
"group": "actual" 
},
{
 "dates": 1351,
"data": 1359.5,
"group": "actual" 
},
{
 "dates": 1352,
"data": 1346.6,
"group": "actual" 
},
{
 "dates": 1353,
"data": 1322.6,
"group": "actual" 
},
{
 "dates": 1354,
"data": 1388.8,
"group": "actual" 
},
{
 "dates": 1355,
"data": 1371.9,
"group": "actual" 
},
{
 "dates": 1356,
"data": 1408.8,
"group": "actual" 
},
{
 "dates": 1357,
"data": 1284.7,
"group": "actual" 
},
{
 "dates": 1358,
"data": 1394.3,
"group": "actual" 
},
{
 "dates": 1359,
"data": 1309.8,
"group": "actual" 
},
{
 "dates": 1360,
"data": 1326.1,
"group": "actual" 
},
{
 "dates": 1361,
"data": 1383.5,
"group": "actual" 
},
{
 "dates": 1362,
"data": 1350.4,
"group": "actual" 
},
{
 "dates": 1363,
"data": 1435.9,
"group": "actual" 
},
{
 "dates": 1364,
"data": 1412.3,
"group": "actual" 
},
{
 "dates": 1365,
"data": 1402.2,
"group": "actual" 
},
{
 "dates": 1366,
"data": 1272.1,
"group": "actual" 
},
{
 "dates": 1367,
"data": 1349.9,
"group": "actual" 
},
{
 "dates": 1368,
"data": 1419.2,
"group": "actual" 
},
{
 "dates": 1369,
"data": 1362.4,
"group": "actual" 
},
{
 "dates": 1370,
"data": 1406.5,
"group": "actual" 
},
{
 "dates": 1371,
"data": 1346.2,
"group": "actual" 
},
{
 "dates": 1372,
"data": 1367.8,
"group": "actual" 
},
{
 "dates": 1373,
"data": 1317.8,
"group": "actual" 
},
{
 "dates": 1374,
"data": 1409.5,
"group": "actual" 
},
{
 "dates": 1375,
"data": 1300.1,
"group": "actual" 
},
{
 "dates": 1376,
"data": 1423.6,
"group": "actual" 
},
{
 "dates": 1377,
"data": 1393.9,
"group": "actual" 
},
{
 "dates": 1378,
"data": 1367.7,
"group": "actual" 
},
{
 "dates": 1379,
"data": 1366.6,
"group": "actual" 
},
{
 "dates": 1380,
"data": 1335.9,
"group": "actual" 
},
{
 "dates": 1381,
"data": 1368.8,
"group": "actual" 
},
{
 "dates": 1382,
"data": 1403.6,
"group": "actual" 
},
{
 "dates": 1383,
"data": 1412.8,
"group": "actual" 
},
{
 "dates": 1384,
"data": 1305.4,
"group": "actual" 
},
{
 "dates": 1385,
"data": 1348.3,
"group": "actual" 
},
{
 "dates": 1386,
"data": 1333.9,
"group": "actual" 
},
{
 "dates": 1387,
"data": 1300.8,
"group": "actual" 
},
{
 "dates": 1388,
"data": 1405.4,
"group": "actual" 
},
{
 "dates": 1389,
"data": 1311.7,
"group": "actual" 
},
{
 "dates": 1390,
"data": 1451.5,
"group": "actual" 
},
{
 "dates": 1391,
"data": 1378.6,
"group": "actual" 
},
{
 "dates": 1392,
"data": 1420.9,
"group": "actual" 
},
{
 "dates": 1393,
"data": 1411.7,
"group": "actual" 
},
{
 "dates": 1394,
"data": 1396.6,
"group": "actual" 
},
{
 "dates": 1395,
"data": 1364.2,
"group": "actual" 
},
{
 "dates": 1396,
"data": 1419.1,
"group": "actual" 
},
{
 "dates": 1397,
"data":   1382,
"group": "actual" 
},
{
 "dates": 1398,
"data": 1412.5,
"group": "actual" 
},
{
 "dates": 1399,
"data": 1418.8,
"group": "actual" 
},
{
 "dates": 1400,
"data": 1364.4,
"group": "actual" 
},
{
 "dates": 1401,
"data": 1414.2,
"group": "actual" 
},
{
 "dates": 1402,
"data": 1465.3,
"group": "actual" 
},
{
 "dates": 1403,
"data": 1426.4,
"group": "actual" 
},
{
 "dates": 1404,
"data": 1415.3,
"group": "actual" 
},
{
 "dates": 1405,
"data": 1437.5,
"group": "actual" 
},
{
 "dates": 1406,
"data": 1395.5,
"group": "actual" 
},
{
 "dates": 1407,
"data":   1322,
"group": "actual" 
},
{
 "dates": 1408,
"data": 1392.1,
"group": "actual" 
},
{
 "dates": 1409,
"data":   1381,
"group": "actual" 
},
{
 "dates": 1410,
"data": 1344.2,
"group": "actual" 
},
{
 "dates": 1411,
"data": 1435.1,
"group": "actual" 
},
{
 "dates": 1412,
"data": 1337.1,
"group": "actual" 
},
{
 "dates": 1413,
"data": 1346.1,
"group": "actual" 
},
{
 "dates": 1414,
"data": 1348.3,
"group": "actual" 
},
{
 "dates": 1415,
"data": 1428.5,
"group": "actual" 
},
{
 "dates": 1416,
"data":   1389,
"group": "actual" 
},
{
 "dates": 1417,
"data": 1423.9,
"group": "actual" 
},
{
 "dates": 1418,
"data": 1377.8,
"group": "actual" 
},
{
 "dates": 1419,
"data":   1395,
"group": "actual" 
},
{
 "dates": 1420,
"data": 1425.3,
"group": "actual" 
},
{
 "dates": 1421,
"data": 1450.5,
"group": "actual" 
},
{
 "dates": 1422,
"data": 1436.3,
"group": "actual" 
},
{
 "dates": 1423,
"data": 1384.4,
"group": "actual" 
},
{
 "dates": 1424,
"data": 1462.6,
"group": "actual" 
},
{
 "dates": 1425,
"data": 1433.1,
"group": "actual" 
},
{
 "dates": 1426,
"data": 1412.7,
"group": "actual" 
},
{
 "dates": 1427,
"data": 1439.2,
"group": "actual" 
},
{
 "dates": 1428,
"data": 1479.7,
"group": "actual" 
},
{
 "dates": 1429,
"data": 1446.2,
"group": "actual" 
},
{
 "dates": 1430,
"data": 1518.8,
"group": "actual" 
},
{
 "dates": 1431,
"data": 1410.2,
"group": "actual" 
},
{
 "dates": 1432,
"data": 1467.1,
"group": "actual" 
},
{
 "dates": 1433,
"data": 1409.1,
"group": "actual" 
},
{
 "dates": 1434,
"data": 1516.8,
"group": "actual" 
},
{
 "dates": 1435,
"data":   1524,
"group": "actual" 
},
{
 "dates": 1436,
"data": 1455.4,
"group": "actual" 
},
{
 "dates": 1437,
"data": 1440.6,
"group": "actual" 
},
{
 "dates": 1438,
"data":   1484,
"group": "actual" 
},
{
 "dates": 1439,
"data": 1450.4,
"group": "actual" 
},
{
 "dates": 1440,
"data":   1488,
"group": "actual" 
},
{
 "dates": 1441,
"data": 1418.5,
"group": "actual" 
},
{
 "dates": 1442,
"data": 1446.3,
"group": "actual" 
},
{
 "dates": 1443,
"data": 1422.4,
"group": "actual" 
},
{
 "dates": 1444,
"data": 1456.8,
"group": "actual" 
},
{
 "dates": 1445,
"data": 1486.5,
"group": "actual" 
},
{
 "dates": 1446,
"data": 1488.8,
"group": "actual" 
},
{
 "dates": 1447,
"data": 1484.5,
"group": "actual" 
},
{
 "dates": 1448,
"data": 1486.1,
"group": "actual" 
},
{
 "dates": 1449,
"data": 1453.1,
"group": "actual" 
},
{
 "dates": 1450,
"data": 1529.3,
"group": "actual" 
},
{
 "dates": 1451,
"data": 1507.6,
"group": "actual" 
},
{
 "dates": 1452,
"data": 1484.6,
"group": "actual" 
},
{
 "dates": 1453,
"data": 1511.6,
"group": "actual" 
},
{
 "dates": 1454,
"data": 1448.8,
"group": "actual" 
},
{
 "dates": 1455,
"data": 1455.3,
"group": "actual" 
},
{
 "dates": 1456,
"data": 1481.9,
"group": "actual" 
},
{
 "dates": 1457,
"data": 1470.2,
"group": "actual" 
},
{
 "dates": 1458,
"data": 1530.4,
"group": "actual" 
},
{
 "dates": 1459,
"data": 1505.8,
"group": "actual" 
},
{
 "dates": 1460,
"data": 1523.2,
"group": "actual" 
},
{
 "dates": 1461,
"data": 1464.8,
"group": "actual" 
},
{
 "dates": 1,
"data": 1002.7,
"group": "fitted" 
},
{
 "dates": 2,
"data": 1004.7,
"group": "fitted" 
},
{
 "dates": 3,
"data": 1006.7,
"group": "fitted" 
},
{
 "dates": 4,
"data": 1008.8,
"group": "fitted" 
},
{
 "dates": 5,
"data": 1010.8,
"group": "fitted" 
},
{
 "dates": 6,
"data": 1012.8,
"group": "fitted" 
},
{
 "dates": 7,
"data": 1014.8,
"group": "fitted" 
},
{
 "dates": 8,
"data": 1016.8,
"group": "fitted" 
},
{
 "dates": 9,
"data": 1018.8,
"group": "fitted" 
},
{
 "dates": 10,
"data": 1020.7,
"group": "fitted" 
},
{
 "dates": 11,
"data": 1022.7,
"group": "fitted" 
},
{
 "dates": 12,
"data": 1024.7,
"group": "fitted" 
},
{
 "dates": 13,
"data": 1026.7,
"group": "fitted" 
},
{
 "dates": 14,
"data": 1028.7,
"group": "fitted" 
},
{
 "dates": 15,
"data": 1030.6,
"group": "fitted" 
},
{
 "dates": 16,
"data": 1032.6,
"group": "fitted" 
},
{
 "dates": 17,
"data": 1034.5,
"group": "fitted" 
},
{
 "dates": 18,
"data": 1036.5,
"group": "fitted" 
},
{
 "dates": 19,
"data": 1038.4,
"group": "fitted" 
},
{
 "dates": 20,
"data": 1040.3,
"group": "fitted" 
},
{
 "dates": 21,
"data": 1042.2,
"group": "fitted" 
},
{
 "dates": 22,
"data": 1044.1,
"group": "fitted" 
},
{
 "dates": 23,
"data":   1046,
"group": "fitted" 
},
{
 "dates": 24,
"data": 1047.9,
"group": "fitted" 
},
{
 "dates": 25,
"data": 1049.8,
"group": "fitted" 
},
{
 "dates": 26,
"data": 1051.7,
"group": "fitted" 
},
{
 "dates": 27,
"data": 1053.5,
"group": "fitted" 
},
{
 "dates": 28,
"data": 1055.3,
"group": "fitted" 
},
{
 "dates": 29,
"data": 1057.2,
"group": "fitted" 
},
{
 "dates": 30,
"data":   1059,
"group": "fitted" 
},
{
 "dates": 31,
"data": 1060.8,
"group": "fitted" 
},
{
 "dates": 32,
"data": 1062.6,
"group": "fitted" 
},
{
 "dates": 33,
"data": 1064.3,
"group": "fitted" 
},
{
 "dates": 34,
"data": 1066.1,
"group": "fitted" 
},
{
 "dates": 35,
"data": 1067.8,
"group": "fitted" 
},
{
 "dates": 36,
"data": 1069.5,
"group": "fitted" 
},
{
 "dates": 37,
"data": 1071.2,
"group": "fitted" 
},
{
 "dates": 38,
"data": 1072.9,
"group": "fitted" 
},
{
 "dates": 39,
"data": 1074.6,
"group": "fitted" 
},
{
 "dates": 40,
"data": 1076.2,
"group": "fitted" 
},
{
 "dates": 41,
"data": 1077.9,
"group": "fitted" 
},
{
 "dates": 42,
"data": 1079.5,
"group": "fitted" 
},
{
 "dates": 43,
"data": 1081.1,
"group": "fitted" 
},
{
 "dates": 44,
"data": 1082.7,
"group": "fitted" 
},
{
 "dates": 45,
"data": 1084.2,
"group": "fitted" 
},
{
 "dates": 46,
"data": 1085.8,
"group": "fitted" 
},
{
 "dates": 47,
"data": 1087.3,
"group": "fitted" 
},
{
 "dates": 48,
"data": 1088.8,
"group": "fitted" 
},
{
 "dates": 49,
"data": 1090.3,
"group": "fitted" 
},
{
 "dates": 50,
"data": 1091.7,
"group": "fitted" 
},
{
 "dates": 51,
"data": 1093.1,
"group": "fitted" 
},
{
 "dates": 52,
"data": 1094.6,
"group": "fitted" 
},
{
 "dates": 53,
"data": 1095.9,
"group": "fitted" 
},
{
 "dates": 54,
"data": 1097.3,
"group": "fitted" 
},
{
 "dates": 55,
"data": 1098.7,
"group": "fitted" 
},
{
 "dates": 56,
"data":   1100,
"group": "fitted" 
},
{
 "dates": 57,
"data": 1101.3,
"group": "fitted" 
},
{
 "dates": 58,
"data": 1102.5,
"group": "fitted" 
},
{
 "dates": 59,
"data": 1103.8,
"group": "fitted" 
},
{
 "dates": 60,
"data":   1105,
"group": "fitted" 
},
{
 "dates": 61,
"data": 1106.2,
"group": "fitted" 
},
{
 "dates": 62,
"data": 1107.4,
"group": "fitted" 
},
{
 "dates": 63,
"data": 1108.5,
"group": "fitted" 
},
{
 "dates": 64,
"data": 1109.7,
"group": "fitted" 
},
{
 "dates": 65,
"data": 1110.8,
"group": "fitted" 
},
{
 "dates": 66,
"data": 1111.8,
"group": "fitted" 
},
{
 "dates": 67,
"data": 1112.9,
"group": "fitted" 
},
{
 "dates": 68,
"data": 1113.9,
"group": "fitted" 
},
{
 "dates": 69,
"data": 1114.9,
"group": "fitted" 
},
{
 "dates": 70,
"data": 1115.9,
"group": "fitted" 
},
{
 "dates": 71,
"data": 1116.8,
"group": "fitted" 
},
{
 "dates": 72,
"data": 1117.7,
"group": "fitted" 
},
{
 "dates": 73,
"data": 1118.6,
"group": "fitted" 
},
{
 "dates": 74,
"data": 1119.5,
"group": "fitted" 
},
{
 "dates": 75,
"data": 1120.3,
"group": "fitted" 
},
{
 "dates": 76,
"data": 1121.1,
"group": "fitted" 
},
{
 "dates": 77,
"data": 1121.9,
"group": "fitted" 
},
{
 "dates": 78,
"data": 1122.6,
"group": "fitted" 
},
{
 "dates": 79,
"data": 1123.4,
"group": "fitted" 
},
{
 "dates": 80,
"data":   1124,
"group": "fitted" 
},
{
 "dates": 81,
"data": 1124.7,
"group": "fitted" 
},
{
 "dates": 82,
"data": 1125.3,
"group": "fitted" 
},
{
 "dates": 83,
"data": 1125.9,
"group": "fitted" 
},
{
 "dates": 84,
"data": 1126.5,
"group": "fitted" 
},
{
 "dates": 85,
"data": 1127.1,
"group": "fitted" 
},
{
 "dates": 86,
"data": 1127.6,
"group": "fitted" 
},
{
 "dates": 87,
"data": 1128.1,
"group": "fitted" 
},
{
 "dates": 88,
"data": 1128.6,
"group": "fitted" 
},
{
 "dates": 89,
"data":   1129,
"group": "fitted" 
},
{
 "dates": 90,
"data": 1129.4,
"group": "fitted" 
},
{
 "dates": 91,
"data": 1129.8,
"group": "fitted" 
},
{
 "dates": 92,
"data": 1130.1,
"group": "fitted" 
},
{
 "dates": 93,
"data": 1130.4,
"group": "fitted" 
},
{
 "dates": 94,
"data": 1130.7,
"group": "fitted" 
},
{
 "dates": 95,
"data":   1131,
"group": "fitted" 
},
{
 "dates": 96,
"data": 1131.2,
"group": "fitted" 
},
{
 "dates": 97,
"data": 1131.4,
"group": "fitted" 
},
{
 "dates": 98,
"data": 1131.6,
"group": "fitted" 
},
{
 "dates": 99,
"data": 1131.7,
"group": "fitted" 
},
{
 "dates": 100,
"data": 1131.9,
"group": "fitted" 
},
{
 "dates": 101,
"data": 1131.9,
"group": "fitted" 
},
{
 "dates": 102,
"data":   1132,
"group": "fitted" 
},
{
 "dates": 103,
"data":   1132,
"group": "fitted" 
},
{
 "dates": 104,
"data":   1132,
"group": "fitted" 
},
{
 "dates": 105,
"data":   1132,
"group": "fitted" 
},
{
 "dates": 106,
"data":   1132,
"group": "fitted" 
},
{
 "dates": 107,
"data": 1131.9,
"group": "fitted" 
},
{
 "dates": 108,
"data": 1131.8,
"group": "fitted" 
},
{
 "dates": 109,
"data": 1131.6,
"group": "fitted" 
},
{
 "dates": 110,
"data": 1131.5,
"group": "fitted" 
},
{
 "dates": 111,
"data": 1131.3,
"group": "fitted" 
},
{
 "dates": 112,
"data": 1131.1,
"group": "fitted" 
},
{
 "dates": 113,
"data": 1130.8,
"group": "fitted" 
},
{
 "dates": 114,
"data": 1130.5,
"group": "fitted" 
},
{
 "dates": 115,
"data": 1130.2,
"group": "fitted" 
},
{
 "dates": 116,
"data": 1129.9,
"group": "fitted" 
},
{
 "dates": 117,
"data": 1129.6,
"group": "fitted" 
},
{
 "dates": 118,
"data": 1129.2,
"group": "fitted" 
},
{
 "dates": 119,
"data": 1128.8,
"group": "fitted" 
},
{
 "dates": 120,
"data": 1128.3,
"group": "fitted" 
},
{
 "dates": 121,
"data": 1127.9,
"group": "fitted" 
},
{
 "dates": 122,
"data": 1127.4,
"group": "fitted" 
},
{
 "dates": 123,
"data": 1126.9,
"group": "fitted" 
},
{
 "dates": 124,
"data": 1126.4,
"group": "fitted" 
},
{
 "dates": 125,
"data": 1125.8,
"group": "fitted" 
},
{
 "dates": 126,
"data": 1125.2,
"group": "fitted" 
},
{
 "dates": 127,
"data": 1124.6,
"group": "fitted" 
},
{
 "dates": 128,
"data":   1124,
"group": "fitted" 
},
{
 "dates": 129,
"data": 1123.3,
"group": "fitted" 
},
{
 "dates": 130,
"data": 1122.6,
"group": "fitted" 
},
{
 "dates": 131,
"data": 1121.9,
"group": "fitted" 
},
{
 "dates": 132,
"data": 1121.2,
"group": "fitted" 
},
{
 "dates": 133,
"data": 1120.5,
"group": "fitted" 
},
{
 "dates": 134,
"data": 1119.7,
"group": "fitted" 
},
{
 "dates": 135,
"data": 1118.9,
"group": "fitted" 
},
{
 "dates": 136,
"data": 1118.1,
"group": "fitted" 
},
{
 "dates": 137,
"data": 1117.3,
"group": "fitted" 
},
{
 "dates": 138,
"data": 1116.4,
"group": "fitted" 
},
{
 "dates": 139,
"data": 1115.6,
"group": "fitted" 
},
{
 "dates": 140,
"data": 1114.7,
"group": "fitted" 
},
{
 "dates": 141,
"data": 1113.8,
"group": "fitted" 
},
{
 "dates": 142,
"data": 1112.8,
"group": "fitted" 
},
{
 "dates": 143,
"data": 1111.9,
"group": "fitted" 
},
{
 "dates": 144,
"data": 1110.9,
"group": "fitted" 
},
{
 "dates": 145,
"data": 1109.9,
"group": "fitted" 
},
{
 "dates": 146,
"data": 1108.9,
"group": "fitted" 
},
{
 "dates": 147,
"data": 1107.9,
"group": "fitted" 
},
{
 "dates": 148,
"data": 1106.9,
"group": "fitted" 
},
{
 "dates": 149,
"data": 1105.8,
"group": "fitted" 
},
{
 "dates": 150,
"data": 1104.7,
"group": "fitted" 
},
{
 "dates": 151,
"data": 1103.7,
"group": "fitted" 
},
{
 "dates": 152,
"data": 1102.6,
"group": "fitted" 
},
{
 "dates": 153,
"data": 1101.4,
"group": "fitted" 
},
{
 "dates": 154,
"data": 1100.3,
"group": "fitted" 
},
{
 "dates": 155,
"data": 1099.2,
"group": "fitted" 
},
{
 "dates": 156,
"data":   1098,
"group": "fitted" 
},
{
 "dates": 157,
"data": 1096.8,
"group": "fitted" 
},
{
 "dates": 158,
"data": 1095.7,
"group": "fitted" 
},
{
 "dates": 159,
"data": 1094.5,
"group": "fitted" 
},
{
 "dates": 160,
"data": 1093.3,
"group": "fitted" 
},
{
 "dates": 161,
"data":   1092,
"group": "fitted" 
},
{
 "dates": 162,
"data": 1090.8,
"group": "fitted" 
},
{
 "dates": 163,
"data": 1089.6,
"group": "fitted" 
},
{
 "dates": 164,
"data": 1088.3,
"group": "fitted" 
},
{
 "dates": 165,
"data": 1087.1,
"group": "fitted" 
},
{
 "dates": 166,
"data": 1085.8,
"group": "fitted" 
},
{
 "dates": 167,
"data": 1084.5,
"group": "fitted" 
},
{
 "dates": 168,
"data": 1083.2,
"group": "fitted" 
},
{
 "dates": 169,
"data":   1082,
"group": "fitted" 
},
{
 "dates": 170,
"data": 1080.7,
"group": "fitted" 
},
{
 "dates": 171,
"data": 1079.4,
"group": "fitted" 
},
{
 "dates": 172,
"data": 1078.1,
"group": "fitted" 
},
{
 "dates": 173,
"data": 1076.7,
"group": "fitted" 
},
{
 "dates": 174,
"data": 1075.4,
"group": "fitted" 
},
{
 "dates": 175,
"data": 1074.1,
"group": "fitted" 
},
{
 "dates": 176,
"data": 1072.8,
"group": "fitted" 
},
{
 "dates": 177,
"data": 1071.4,
"group": "fitted" 
},
{
 "dates": 178,
"data": 1070.1,
"group": "fitted" 
},
{
 "dates": 179,
"data": 1068.8,
"group": "fitted" 
},
{
 "dates": 180,
"data": 1067.4,
"group": "fitted" 
},
{
 "dates": 181,
"data": 1066.1,
"group": "fitted" 
},
{
 "dates": 182,
"data": 1064.7,
"group": "fitted" 
},
{
 "dates": 183,
"data": 1063.4,
"group": "fitted" 
},
{
 "dates": 184,
"data": 1062.1,
"group": "fitted" 
},
{
 "dates": 185,
"data": 1060.7,
"group": "fitted" 
},
{
 "dates": 186,
"data": 1059.4,
"group": "fitted" 
},
{
 "dates": 187,
"data":   1058,
"group": "fitted" 
},
{
 "dates": 188,
"data": 1056.7,
"group": "fitted" 
},
{
 "dates": 189,
"data": 1055.4,
"group": "fitted" 
},
{
 "dates": 190,
"data":   1054,
"group": "fitted" 
},
{
 "dates": 191,
"data": 1052.7,
"group": "fitted" 
},
{
 "dates": 192,
"data": 1051.4,
"group": "fitted" 
},
{
 "dates": 193,
"data": 1050.1,
"group": "fitted" 
},
{
 "dates": 194,
"data": 1048.7,
"group": "fitted" 
},
{
 "dates": 195,
"data": 1047.4,
"group": "fitted" 
},
{
 "dates": 196,
"data": 1046.1,
"group": "fitted" 
},
{
 "dates": 197,
"data": 1044.8,
"group": "fitted" 
},
{
 "dates": 198,
"data": 1043.6,
"group": "fitted" 
},
{
 "dates": 199,
"data": 1042.3,
"group": "fitted" 
},
{
 "dates": 200,
"data":   1041,
"group": "fitted" 
},
{
 "dates": 201,
"data": 1039.7,
"group": "fitted" 
},
{
 "dates": 202,
"data": 1038.5,
"group": "fitted" 
},
{
 "dates": 203,
"data": 1037.2,
"group": "fitted" 
},
{
 "dates": 204,
"data":   1036,
"group": "fitted" 
},
{
 "dates": 205,
"data": 1034.8,
"group": "fitted" 
},
{
 "dates": 206,
"data": 1033.5,
"group": "fitted" 
},
{
 "dates": 207,
"data": 1032.3,
"group": "fitted" 
},
{
 "dates": 208,
"data": 1031.1,
"group": "fitted" 
},
{
 "dates": 209,
"data":   1030,
"group": "fitted" 
},
{
 "dates": 210,
"data": 1028.8,
"group": "fitted" 
},
{
 "dates": 211,
"data": 1027.6,
"group": "fitted" 
},
{
 "dates": 212,
"data": 1026.5,
"group": "fitted" 
},
{
 "dates": 213,
"data": 1025.4,
"group": "fitted" 
},
{
 "dates": 214,
"data": 1024.2,
"group": "fitted" 
},
{
 "dates": 215,
"data": 1023.1,
"group": "fitted" 
},
{
 "dates": 216,
"data": 1022.1,
"group": "fitted" 
},
{
 "dates": 217,
"data":   1021,
"group": "fitted" 
},
{
 "dates": 218,
"data": 1019.9,
"group": "fitted" 
},
{
 "dates": 219,
"data": 1018.9,
"group": "fitted" 
},
{
 "dates": 220,
"data": 1017.9,
"group": "fitted" 
},
{
 "dates": 221,
"data": 1016.9,
"group": "fitted" 
},
{
 "dates": 222,
"data": 1015.9,
"group": "fitted" 
},
{
 "dates": 223,
"data": 1014.9,
"group": "fitted" 
},
{
 "dates": 224,
"data":   1014,
"group": "fitted" 
},
{
 "dates": 225,
"data":   1013,
"group": "fitted" 
},
{
 "dates": 226,
"data": 1012.1,
"group": "fitted" 
},
{
 "dates": 227,
"data": 1011.2,
"group": "fitted" 
},
{
 "dates": 228,
"data": 1010.4,
"group": "fitted" 
},
{
 "dates": 229,
"data": 1009.5,
"group": "fitted" 
},
{
 "dates": 230,
"data": 1008.7,
"group": "fitted" 
},
{
 "dates": 231,
"data": 1007.9,
"group": "fitted" 
},
{
 "dates": 232,
"data": 1007.1,
"group": "fitted" 
},
{
 "dates": 233,
"data": 1006.3,
"group": "fitted" 
},
{
 "dates": 234,
"data": 1005.6,
"group": "fitted" 
},
{
 "dates": 235,
"data": 1004.9,
"group": "fitted" 
},
{
 "dates": 236,
"data": 1004.2,
"group": "fitted" 
},
{
 "dates": 237,
"data": 1003.5,
"group": "fitted" 
},
{
 "dates": 238,
"data": 1002.8,
"group": "fitted" 
},
{
 "dates": 239,
"data": 1002.2,
"group": "fitted" 
},
{
 "dates": 240,
"data": 1001.6,
"group": "fitted" 
},
{
 "dates": 241,
"data":   1001,
"group": "fitted" 
},
{
 "dates": 242,
"data": 1000.4,
"group": "fitted" 
},
{
 "dates": 243,
"data": 999.91,
"group": "fitted" 
},
{
 "dates": 244,
"data": 999.41,
"group": "fitted" 
},
{
 "dates": 245,
"data": 998.92,
"group": "fitted" 
},
{
 "dates": 246,
"data": 998.46,
"group": "fitted" 
},
{
 "dates": 247,
"data": 998.03,
"group": "fitted" 
},
{
 "dates": 248,
"data": 997.63,
"group": "fitted" 
},
{
 "dates": 249,
"data": 997.25,
"group": "fitted" 
},
{
 "dates": 250,
"data": 996.89,
"group": "fitted" 
},
{
 "dates": 251,
"data": 996.56,
"group": "fitted" 
},
{
 "dates": 252,
"data": 996.26,
"group": "fitted" 
},
{
 "dates": 253,
"data": 995.99,
"group": "fitted" 
},
{
 "dates": 254,
"data": 995.74,
"group": "fitted" 
},
{
 "dates": 255,
"data": 995.52,
"group": "fitted" 
},
{
 "dates": 256,
"data": 995.33,
"group": "fitted" 
},
{
 "dates": 257,
"data": 995.16,
"group": "fitted" 
},
{
 "dates": 258,
"data": 995.03,
"group": "fitted" 
},
{
 "dates": 259,
"data": 994.92,
"group": "fitted" 
},
{
 "dates": 260,
"data": 994.84,
"group": "fitted" 
},
{
 "dates": 261,
"data": 994.78,
"group": "fitted" 
},
{
 "dates": 262,
"data": 994.76,
"group": "fitted" 
},
{
 "dates": 263,
"data": 994.76,
"group": "fitted" 
},
{
 "dates": 264,
"data": 994.79,
"group": "fitted" 
},
{
 "dates": 265,
"data": 994.85,
"group": "fitted" 
},
{
 "dates": 266,
"data": 994.94,
"group": "fitted" 
},
{
 "dates": 267,
"data": 995.06,
"group": "fitted" 
},
{
 "dates": 268,
"data":  995.2,
"group": "fitted" 
},
{
 "dates": 269,
"data": 995.38,
"group": "fitted" 
},
{
 "dates": 270,
"data": 995.58,
"group": "fitted" 
},
{
 "dates": 271,
"data": 995.81,
"group": "fitted" 
},
{
 "dates": 272,
"data": 996.07,
"group": "fitted" 
},
{
 "dates": 273,
"data": 996.36,
"group": "fitted" 
},
{
 "dates": 274,
"data": 996.68,
"group": "fitted" 
},
{
 "dates": 275,
"data": 997.03,
"group": "fitted" 
},
{
 "dates": 276,
"data": 997.41,
"group": "fitted" 
},
{
 "dates": 277,
"data": 997.81,
"group": "fitted" 
},
{
 "dates": 278,
"data": 998.25,
"group": "fitted" 
},
{
 "dates": 279,
"data": 998.71,
"group": "fitted" 
},
{
 "dates": 280,
"data":  999.2,
"group": "fitted" 
},
{
 "dates": 281,
"data": 999.72,
"group": "fitted" 
},
{
 "dates": 282,
"data": 1000.3,
"group": "fitted" 
},
{
 "dates": 283,
"data": 1000.9,
"group": "fitted" 
},
{
 "dates": 284,
"data": 1001.5,
"group": "fitted" 
},
{
 "dates": 285,
"data": 1002.1,
"group": "fitted" 
},
{
 "dates": 286,
"data": 1002.8,
"group": "fitted" 
},
{
 "dates": 287,
"data": 1003.4,
"group": "fitted" 
},
{
 "dates": 288,
"data": 1004.2,
"group": "fitted" 
},
{
 "dates": 289,
"data": 1004.9,
"group": "fitted" 
},
{
 "dates": 290,
"data": 1005.7,
"group": "fitted" 
},
{
 "dates": 291,
"data": 1006.5,
"group": "fitted" 
},
{
 "dates": 292,
"data": 1007.3,
"group": "fitted" 
},
{
 "dates": 293,
"data": 1008.2,
"group": "fitted" 
},
{
 "dates": 294,
"data": 1009.1,
"group": "fitted" 
},
{
 "dates": 295,
"data":   1010,
"group": "fitted" 
},
{
 "dates": 296,
"data": 1010.9,
"group": "fitted" 
},
{
 "dates": 297,
"data": 1011.9,
"group": "fitted" 
},
{
 "dates": 298,
"data": 1012.9,
"group": "fitted" 
},
{
 "dates": 299,
"data": 1013.9,
"group": "fitted" 
},
{
 "dates": 300,
"data":   1015,
"group": "fitted" 
},
{
 "dates": 301,
"data":   1016,
"group": "fitted" 
},
{
 "dates": 302,
"data": 1017.1,
"group": "fitted" 
},
{
 "dates": 303,
"data": 1018.3,
"group": "fitted" 
},
{
 "dates": 304,
"data": 1019.4,
"group": "fitted" 
},
{
 "dates": 305,
"data": 1020.6,
"group": "fitted" 
},
{
 "dates": 306,
"data": 1021.8,
"group": "fitted" 
},
{
 "dates": 307,
"data":   1023,
"group": "fitted" 
},
{
 "dates": 308,
"data": 1024.3,
"group": "fitted" 
},
{
 "dates": 309,
"data": 1025.5,
"group": "fitted" 
},
{
 "dates": 310,
"data": 1026.8,
"group": "fitted" 
},
{
 "dates": 311,
"data": 1028.1,
"group": "fitted" 
},
{
 "dates": 312,
"data": 1029.5,
"group": "fitted" 
},
{
 "dates": 313,
"data": 1030.9,
"group": "fitted" 
},
{
 "dates": 314,
"data": 1032.2,
"group": "fitted" 
},
{
 "dates": 315,
"data": 1033.7,
"group": "fitted" 
},
{
 "dates": 316,
"data": 1035.1,
"group": "fitted" 
},
{
 "dates": 317,
"data": 1036.5,
"group": "fitted" 
},
{
 "dates": 318,
"data":   1038,
"group": "fitted" 
},
{
 "dates": 319,
"data": 1039.5,
"group": "fitted" 
},
{
 "dates": 320,
"data":   1041,
"group": "fitted" 
},
{
 "dates": 321,
"data": 1042.6,
"group": "fitted" 
},
{
 "dates": 322,
"data": 1044.1,
"group": "fitted" 
},
{
 "dates": 323,
"data": 1045.7,
"group": "fitted" 
},
{
 "dates": 324,
"data": 1047.3,
"group": "fitted" 
},
{
 "dates": 325,
"data": 1048.9,
"group": "fitted" 
},
{
 "dates": 326,
"data": 1050.6,
"group": "fitted" 
},
{
 "dates": 327,
"data": 1052.2,
"group": "fitted" 
},
{
 "dates": 328,
"data": 1053.9,
"group": "fitted" 
},
{
 "dates": 329,
"data": 1055.6,
"group": "fitted" 
},
{
 "dates": 330,
"data": 1057.3,
"group": "fitted" 
},
{
 "dates": 331,
"data":   1059,
"group": "fitted" 
},
{
 "dates": 332,
"data": 1060.7,
"group": "fitted" 
},
{
 "dates": 333,
"data": 1062.5,
"group": "fitted" 
},
{
 "dates": 334,
"data": 1064.2,
"group": "fitted" 
},
{
 "dates": 335,
"data":   1066,
"group": "fitted" 
},
{
 "dates": 336,
"data": 1067.8,
"group": "fitted" 
},
{
 "dates": 337,
"data": 1069.6,
"group": "fitted" 
},
{
 "dates": 338,
"data": 1071.5,
"group": "fitted" 
},
{
 "dates": 339,
"data": 1073.3,
"group": "fitted" 
},
{
 "dates": 340,
"data": 1075.1,
"group": "fitted" 
},
{
 "dates": 341,
"data":   1077,
"group": "fitted" 
},
{
 "dates": 342,
"data": 1078.9,
"group": "fitted" 
},
{
 "dates": 343,
"data": 1080.8,
"group": "fitted" 
},
{
 "dates": 344,
"data": 1082.7,
"group": "fitted" 
},
{
 "dates": 345,
"data": 1084.6,
"group": "fitted" 
},
{
 "dates": 346,
"data": 1086.5,
"group": "fitted" 
},
{
 "dates": 347,
"data": 1088.4,
"group": "fitted" 
},
{
 "dates": 348,
"data": 1090.3,
"group": "fitted" 
},
{
 "dates": 349,
"data": 1092.3,
"group": "fitted" 
},
{
 "dates": 350,
"data": 1094.2,
"group": "fitted" 
},
{
 "dates": 351,
"data": 1096.2,
"group": "fitted" 
},
{
 "dates": 352,
"data": 1098.1,
"group": "fitted" 
},
{
 "dates": 353,
"data": 1100.1,
"group": "fitted" 
},
{
 "dates": 354,
"data": 1102.1,
"group": "fitted" 
},
{
 "dates": 355,
"data": 1104.1,
"group": "fitted" 
},
{
 "dates": 356,
"data": 1106.1,
"group": "fitted" 
},
{
 "dates": 357,
"data":   1108,
"group": "fitted" 
},
{
 "dates": 358,
"data":   1110,
"group": "fitted" 
},
{
 "dates": 359,
"data":   1112,
"group": "fitted" 
},
{
 "dates": 360,
"data":   1114,
"group": "fitted" 
},
{
 "dates": 361,
"data":   1116,
"group": "fitted" 
},
{
 "dates": 362,
"data":   1118,
"group": "fitted" 
},
{
 "dates": 363,
"data": 1120.1,
"group": "fitted" 
},
{
 "dates": 364,
"data": 1122.1,
"group": "fitted" 
},
{
 "dates": 365,
"data": 1124.1,
"group": "fitted" 
},
{
 "dates": 366,
"data": 1127.9,
"group": "fitted" 
},
{
 "dates": 367,
"data": 1129.9,
"group": "fitted" 
},
{
 "dates": 368,
"data": 1131.9,
"group": "fitted" 
},
{
 "dates": 369,
"data": 1133.9,
"group": "fitted" 
},
{
 "dates": 370,
"data": 1135.9,
"group": "fitted" 
},
{
 "dates": 371,
"data": 1137.9,
"group": "fitted" 
},
{
 "dates": 372,
"data": 1139.9,
"group": "fitted" 
},
{
 "dates": 373,
"data": 1141.9,
"group": "fitted" 
},
{
 "dates": 374,
"data": 1143.9,
"group": "fitted" 
},
{
 "dates": 375,
"data": 1145.9,
"group": "fitted" 
},
{
 "dates": 376,
"data": 1147.9,
"group": "fitted" 
},
{
 "dates": 377,
"data": 1149.9,
"group": "fitted" 
},
{
 "dates": 378,
"data": 1151.8,
"group": "fitted" 
},
{
 "dates": 379,
"data": 1153.8,
"group": "fitted" 
},
{
 "dates": 380,
"data": 1155.8,
"group": "fitted" 
},
{
 "dates": 381,
"data": 1157.7,
"group": "fitted" 
},
{
 "dates": 382,
"data": 1159.7,
"group": "fitted" 
},
{
 "dates": 383,
"data": 1161.6,
"group": "fitted" 
},
{
 "dates": 384,
"data": 1163.5,
"group": "fitted" 
},
{
 "dates": 385,
"data": 1165.5,
"group": "fitted" 
},
{
 "dates": 386,
"data": 1167.4,
"group": "fitted" 
},
{
 "dates": 387,
"data": 1169.3,
"group": "fitted" 
},
{
 "dates": 388,
"data": 1171.2,
"group": "fitted" 
},
{
 "dates": 389,
"data": 1173.1,
"group": "fitted" 
},
{
 "dates": 390,
"data": 1174.9,
"group": "fitted" 
},
{
 "dates": 391,
"data": 1176.8,
"group": "fitted" 
},
{
 "dates": 392,
"data": 1178.6,
"group": "fitted" 
},
{
 "dates": 393,
"data": 1180.5,
"group": "fitted" 
},
{
 "dates": 394,
"data": 1182.3,
"group": "fitted" 
},
{
 "dates": 395,
"data": 1184.1,
"group": "fitted" 
},
{
 "dates": 396,
"data": 1185.9,
"group": "fitted" 
},
{
 "dates": 397,
"data": 1187.7,
"group": "fitted" 
},
{
 "dates": 398,
"data": 1189.5,
"group": "fitted" 
},
{
 "dates": 399,
"data": 1191.2,
"group": "fitted" 
},
{
 "dates": 400,
"data": 1192.9,
"group": "fitted" 
},
{
 "dates": 401,
"data": 1194.7,
"group": "fitted" 
},
{
 "dates": 402,
"data": 1196.4,
"group": "fitted" 
},
{
 "dates": 403,
"data": 1198.1,
"group": "fitted" 
},
{
 "dates": 404,
"data": 1199.7,
"group": "fitted" 
},
{
 "dates": 405,
"data": 1201.4,
"group": "fitted" 
},
{
 "dates": 406,
"data":   1203,
"group": "fitted" 
},
{
 "dates": 407,
"data": 1204.6,
"group": "fitted" 
},
{
 "dates": 408,
"data": 1206.2,
"group": "fitted" 
},
{
 "dates": 409,
"data": 1207.8,
"group": "fitted" 
},
{
 "dates": 410,
"data": 1209.4,
"group": "fitted" 
},
{
 "dates": 411,
"data": 1210.9,
"group": "fitted" 
},
{
 "dates": 412,
"data": 1212.4,
"group": "fitted" 
},
{
 "dates": 413,
"data": 1213.9,
"group": "fitted" 
},
{
 "dates": 414,
"data": 1215.4,
"group": "fitted" 
},
{
 "dates": 415,
"data": 1216.8,
"group": "fitted" 
},
{
 "dates": 416,
"data": 1218.3,
"group": "fitted" 
},
{
 "dates": 417,
"data": 1219.7,
"group": "fitted" 
},
{
 "dates": 418,
"data": 1221.1,
"group": "fitted" 
},
{
 "dates": 419,
"data": 1222.4,
"group": "fitted" 
},
{
 "dates": 420,
"data": 1223.8,
"group": "fitted" 
},
{
 "dates": 421,
"data": 1225.1,
"group": "fitted" 
},
{
 "dates": 422,
"data": 1226.4,
"group": "fitted" 
},
{
 "dates": 423,
"data": 1227.7,
"group": "fitted" 
},
{
 "dates": 424,
"data": 1228.9,
"group": "fitted" 
},
{
 "dates": 425,
"data": 1230.2,
"group": "fitted" 
},
{
 "dates": 426,
"data": 1231.4,
"group": "fitted" 
},
{
 "dates": 427,
"data": 1232.5,
"group": "fitted" 
},
{
 "dates": 428,
"data": 1233.7,
"group": "fitted" 
},
{
 "dates": 429,
"data": 1234.8,
"group": "fitted" 
},
{
 "dates": 430,
"data": 1235.9,
"group": "fitted" 
},
{
 "dates": 431,
"data":   1237,
"group": "fitted" 
},
{
 "dates": 432,
"data":   1238,
"group": "fitted" 
},
{
 "dates": 433,
"data":   1239,
"group": "fitted" 
},
{
 "dates": 434,
"data":   1240,
"group": "fitted" 
},
{
 "dates": 435,
"data":   1241,
"group": "fitted" 
},
{
 "dates": 436,
"data": 1241.9,
"group": "fitted" 
},
{
 "dates": 437,
"data": 1242.9,
"group": "fitted" 
},
{
 "dates": 438,
"data": 1243.7,
"group": "fitted" 
},
{
 "dates": 439,
"data": 1244.6,
"group": "fitted" 
},
{
 "dates": 440,
"data": 1245.4,
"group": "fitted" 
},
{
 "dates": 441,
"data": 1246.2,
"group": "fitted" 
},
{
 "dates": 442,
"data":   1247,
"group": "fitted" 
},
{
 "dates": 443,
"data": 1247.8,
"group": "fitted" 
},
{
 "dates": 444,
"data": 1248.5,
"group": "fitted" 
},
{
 "dates": 445,
"data": 1249.2,
"group": "fitted" 
},
{
 "dates": 446,
"data": 1249.8,
"group": "fitted" 
},
{
 "dates": 447,
"data": 1250.5,
"group": "fitted" 
},
{
 "dates": 448,
"data": 1251.1,
"group": "fitted" 
},
{
 "dates": 449,
"data": 1251.7,
"group": "fitted" 
},
{
 "dates": 450,
"data": 1252.2,
"group": "fitted" 
},
{
 "dates": 451,
"data": 1252.7,
"group": "fitted" 
},
{
 "dates": 452,
"data": 1253.2,
"group": "fitted" 
},
{
 "dates": 453,
"data": 1253.7,
"group": "fitted" 
},
{
 "dates": 454,
"data": 1254.1,
"group": "fitted" 
},
{
 "dates": 455,
"data": 1254.5,
"group": "fitted" 
},
{
 "dates": 456,
"data": 1254.9,
"group": "fitted" 
},
{
 "dates": 457,
"data": 1255.3,
"group": "fitted" 
},
{
 "dates": 458,
"data": 1255.6,
"group": "fitted" 
},
{
 "dates": 459,
"data": 1255.9,
"group": "fitted" 
},
{
 "dates": 460,
"data": 1256.1,
"group": "fitted" 
},
{
 "dates": 461,
"data": 1256.4,
"group": "fitted" 
},
{
 "dates": 462,
"data": 1256.6,
"group": "fitted" 
},
{
 "dates": 463,
"data": 1256.7,
"group": "fitted" 
},
{
 "dates": 464,
"data": 1256.9,
"group": "fitted" 
},
{
 "dates": 465,
"data":   1257,
"group": "fitted" 
},
{
 "dates": 466,
"data": 1257.1,
"group": "fitted" 
},
{
 "dates": 467,
"data": 1257.1,
"group": "fitted" 
},
{
 "dates": 468,
"data": 1257.2,
"group": "fitted" 
},
{
 "dates": 469,
"data": 1257.2,
"group": "fitted" 
},
{
 "dates": 470,
"data": 1257.2,
"group": "fitted" 
},
{
 "dates": 471,
"data": 1257.1,
"group": "fitted" 
},
{
 "dates": 472,
"data":   1257,
"group": "fitted" 
},
{
 "dates": 473,
"data": 1256.9,
"group": "fitted" 
},
{
 "dates": 474,
"data": 1256.8,
"group": "fitted" 
},
{
 "dates": 475,
"data": 1256.6,
"group": "fitted" 
},
{
 "dates": 476,
"data": 1256.4,
"group": "fitted" 
},
{
 "dates": 477,
"data": 1256.2,
"group": "fitted" 
},
{
 "dates": 478,
"data":   1256,
"group": "fitted" 
},
{
 "dates": 479,
"data": 1255.7,
"group": "fitted" 
},
{
 "dates": 480,
"data": 1255.4,
"group": "fitted" 
},
{
 "dates": 481,
"data":   1255,
"group": "fitted" 
},
{
 "dates": 482,
"data": 1254.7,
"group": "fitted" 
},
{
 "dates": 483,
"data": 1254.3,
"group": "fitted" 
},
{
 "dates": 484,
"data": 1253.9,
"group": "fitted" 
},
{
 "dates": 485,
"data": 1253.5,
"group": "fitted" 
},
{
 "dates": 486,
"data":   1253,
"group": "fitted" 
},
{
 "dates": 487,
"data": 1252.5,
"group": "fitted" 
},
{
 "dates": 488,
"data":   1252,
"group": "fitted" 
},
{
 "dates": 489,
"data": 1251.5,
"group": "fitted" 
},
{
 "dates": 490,
"data": 1250.9,
"group": "fitted" 
},
{
 "dates": 491,
"data": 1250.4,
"group": "fitted" 
},
{
 "dates": 492,
"data": 1249.7,
"group": "fitted" 
},
{
 "dates": 493,
"data": 1249.1,
"group": "fitted" 
},
{
 "dates": 494,
"data": 1248.5,
"group": "fitted" 
},
{
 "dates": 495,
"data": 1247.8,
"group": "fitted" 
},
{
 "dates": 496,
"data": 1247.1,
"group": "fitted" 
},
{
 "dates": 497,
"data": 1246.4,
"group": "fitted" 
},
{
 "dates": 498,
"data": 1245.6,
"group": "fitted" 
},
{
 "dates": 499,
"data": 1244.8,
"group": "fitted" 
},
{
 "dates": 500,
"data": 1244.1,
"group": "fitted" 
},
{
 "dates": 501,
"data": 1243.3,
"group": "fitted" 
},
{
 "dates": 502,
"data": 1242.4,
"group": "fitted" 
},
{
 "dates": 503,
"data": 1241.6,
"group": "fitted" 
},
{
 "dates": 504,
"data": 1240.7,
"group": "fitted" 
},
{
 "dates": 505,
"data": 1239.8,
"group": "fitted" 
},
{
 "dates": 506,
"data": 1238.9,
"group": "fitted" 
},
{
 "dates": 507,
"data":   1238,
"group": "fitted" 
},
{
 "dates": 508,
"data":   1237,
"group": "fitted" 
},
{
 "dates": 509,
"data":   1236,
"group": "fitted" 
},
{
 "dates": 510,
"data": 1235.1,
"group": "fitted" 
},
{
 "dates": 511,
"data": 1234.1,
"group": "fitted" 
},
{
 "dates": 512,
"data":   1233,
"group": "fitted" 
},
{
 "dates": 513,
"data":   1232,
"group": "fitted" 
},
{
 "dates": 514,
"data":   1231,
"group": "fitted" 
},
{
 "dates": 515,
"data": 1229.9,
"group": "fitted" 
},
{
 "dates": 516,
"data": 1228.8,
"group": "fitted" 
},
{
 "dates": 517,
"data": 1227.7,
"group": "fitted" 
},
{
 "dates": 518,
"data": 1226.6,
"group": "fitted" 
},
{
 "dates": 519,
"data": 1225.5,
"group": "fitted" 
},
{
 "dates": 520,
"data": 1224.3,
"group": "fitted" 
},
{
 "dates": 521,
"data": 1223.2,
"group": "fitted" 
},
{
 "dates": 522,
"data":   1222,
"group": "fitted" 
},
{
 "dates": 523,
"data": 1220.8,
"group": "fitted" 
},
{
 "dates": 524,
"data": 1219.6,
"group": "fitted" 
},
{
 "dates": 525,
"data": 1218.4,
"group": "fitted" 
},
{
 "dates": 526,
"data": 1217.2,
"group": "fitted" 
},
{
 "dates": 527,
"data":   1216,
"group": "fitted" 
},
{
 "dates": 528,
"data": 1214.7,
"group": "fitted" 
},
{
 "dates": 529,
"data": 1213.5,
"group": "fitted" 
},
{
 "dates": 530,
"data": 1212.2,
"group": "fitted" 
},
{
 "dates": 531,
"data": 1210.9,
"group": "fitted" 
},
{
 "dates": 532,
"data": 1209.7,
"group": "fitted" 
},
{
 "dates": 533,
"data": 1208.4,
"group": "fitted" 
},
{
 "dates": 534,
"data": 1207.1,
"group": "fitted" 
},
{
 "dates": 535,
"data": 1205.8,
"group": "fitted" 
},
{
 "dates": 536,
"data": 1204.5,
"group": "fitted" 
},
{
 "dates": 537,
"data": 1203.2,
"group": "fitted" 
},
{
 "dates": 538,
"data": 1201.9,
"group": "fitted" 
},
{
 "dates": 539,
"data": 1200.6,
"group": "fitted" 
},
{
 "dates": 540,
"data": 1199.2,
"group": "fitted" 
},
{
 "dates": 541,
"data": 1197.9,
"group": "fitted" 
},
{
 "dates": 542,
"data": 1196.6,
"group": "fitted" 
},
{
 "dates": 543,
"data": 1195.2,
"group": "fitted" 
},
{
 "dates": 544,
"data": 1193.9,
"group": "fitted" 
},
{
 "dates": 545,
"data": 1192.6,
"group": "fitted" 
},
{
 "dates": 546,
"data": 1191.2,
"group": "fitted" 
},
{
 "dates": 547,
"data": 1189.9,
"group": "fitted" 
},
{
 "dates": 548,
"data": 1188.5,
"group": "fitted" 
},
{
 "dates": 549,
"data": 1187.2,
"group": "fitted" 
},
{
 "dates": 550,
"data": 1185.9,
"group": "fitted" 
},
{
 "dates": 551,
"data": 1184.5,
"group": "fitted" 
},
{
 "dates": 552,
"data": 1183.2,
"group": "fitted" 
},
{
 "dates": 553,
"data": 1181.8,
"group": "fitted" 
},
{
 "dates": 554,
"data": 1180.5,
"group": "fitted" 
},
{
 "dates": 555,
"data": 1179.2,
"group": "fitted" 
},
{
 "dates": 556,
"data": 1177.8,
"group": "fitted" 
},
{
 "dates": 557,
"data": 1176.5,
"group": "fitted" 
},
{
 "dates": 558,
"data": 1175.2,
"group": "fitted" 
},
{
 "dates": 559,
"data": 1173.9,
"group": "fitted" 
},
{
 "dates": 560,
"data": 1172.6,
"group": "fitted" 
},
{
 "dates": 561,
"data": 1171.3,
"group": "fitted" 
},
{
 "dates": 562,
"data":   1170,
"group": "fitted" 
},
{
 "dates": 563,
"data": 1168.7,
"group": "fitted" 
},
{
 "dates": 564,
"data": 1167.4,
"group": "fitted" 
},
{
 "dates": 565,
"data": 1166.1,
"group": "fitted" 
},
{
 "dates": 566,
"data": 1164.9,
"group": "fitted" 
},
{
 "dates": 567,
"data": 1163.6,
"group": "fitted" 
},
{
 "dates": 568,
"data": 1162.4,
"group": "fitted" 
},
{
 "dates": 569,
"data": 1161.1,
"group": "fitted" 
},
{
 "dates": 570,
"data": 1159.9,
"group": "fitted" 
},
{
 "dates": 571,
"data": 1158.7,
"group": "fitted" 
},
{
 "dates": 572,
"data": 1157.5,
"group": "fitted" 
},
{
 "dates": 573,
"data": 1156.3,
"group": "fitted" 
},
{
 "dates": 574,
"data": 1155.1,
"group": "fitted" 
},
{
 "dates": 575,
"data": 1153.9,
"group": "fitted" 
},
{
 "dates": 576,
"data": 1152.8,
"group": "fitted" 
},
{
 "dates": 577,
"data": 1151.6,
"group": "fitted" 
},
{
 "dates": 578,
"data": 1150.5,
"group": "fitted" 
},
{
 "dates": 579,
"data": 1149.4,
"group": "fitted" 
},
{
 "dates": 580,
"data": 1148.3,
"group": "fitted" 
},
{
 "dates": 581,
"data": 1147.2,
"group": "fitted" 
},
{
 "dates": 582,
"data": 1146.1,
"group": "fitted" 
},
{
 "dates": 583,
"data": 1145.1,
"group": "fitted" 
},
{
 "dates": 584,
"data":   1144,
"group": "fitted" 
},
{
 "dates": 585,
"data":   1143,
"group": "fitted" 
},
{
 "dates": 586,
"data":   1142,
"group": "fitted" 
},
{
 "dates": 587,
"data":   1141,
"group": "fitted" 
},
{
 "dates": 588,
"data": 1140.1,
"group": "fitted" 
},
{
 "dates": 589,
"data": 1139.1,
"group": "fitted" 
},
{
 "dates": 590,
"data": 1138.2,
"group": "fitted" 
},
{
 "dates": 591,
"data": 1137.3,
"group": "fitted" 
},
{
 "dates": 592,
"data": 1136.4,
"group": "fitted" 
},
{
 "dates": 593,
"data": 1135.5,
"group": "fitted" 
},
{
 "dates": 594,
"data": 1134.7,
"group": "fitted" 
},
{
 "dates": 595,
"data": 1133.8,
"group": "fitted" 
},
{
 "dates": 596,
"data":   1133,
"group": "fitted" 
},
{
 "dates": 597,
"data": 1132.2,
"group": "fitted" 
},
{
 "dates": 598,
"data": 1131.5,
"group": "fitted" 
},
{
 "dates": 599,
"data": 1130.7,
"group": "fitted" 
},
{
 "dates": 600,
"data":   1130,
"group": "fitted" 
},
{
 "dates": 601,
"data": 1129.3,
"group": "fitted" 
},
{
 "dates": 602,
"data": 1128.6,
"group": "fitted" 
},
{
 "dates": 603,
"data":   1128,
"group": "fitted" 
},
{
 "dates": 604,
"data": 1127.3,
"group": "fitted" 
},
{
 "dates": 605,
"data": 1126.7,
"group": "fitted" 
},
{
 "dates": 606,
"data": 1126.1,
"group": "fitted" 
},
{
 "dates": 607,
"data": 1125.6,
"group": "fitted" 
},
{
 "dates": 608,
"data": 1125.1,
"group": "fitted" 
},
{
 "dates": 609,
"data": 1124.5,
"group": "fitted" 
},
{
 "dates": 610,
"data": 1124.1,
"group": "fitted" 
},
{
 "dates": 611,
"data": 1123.6,
"group": "fitted" 
},
{
 "dates": 612,
"data": 1123.2,
"group": "fitted" 
},
{
 "dates": 613,
"data": 1122.8,
"group": "fitted" 
},
{
 "dates": 614,
"data": 1122.4,
"group": "fitted" 
},
{
 "dates": 615,
"data":   1122,
"group": "fitted" 
},
{
 "dates": 616,
"data": 1121.7,
"group": "fitted" 
},
{
 "dates": 617,
"data": 1121.4,
"group": "fitted" 
},
{
 "dates": 618,
"data": 1121.1,
"group": "fitted" 
},
{
 "dates": 619,
"data": 1120.9,
"group": "fitted" 
},
{
 "dates": 620,
"data": 1120.7,
"group": "fitted" 
},
{
 "dates": 621,
"data": 1120.5,
"group": "fitted" 
},
{
 "dates": 622,
"data": 1120.3,
"group": "fitted" 
},
{
 "dates": 623,
"data": 1120.2,
"group": "fitted" 
},
{
 "dates": 624,
"data": 1120.1,
"group": "fitted" 
},
{
 "dates": 625,
"data":   1120,
"group": "fitted" 
},
{
 "dates": 626,
"data": 1119.9,
"group": "fitted" 
},
{
 "dates": 627,
"data": 1119.9,
"group": "fitted" 
},
{
 "dates": 628,
"data": 1119.9,
"group": "fitted" 
},
{
 "dates": 629,
"data": 1119.9,
"group": "fitted" 
},
{
 "dates": 630,
"data":   1120,
"group": "fitted" 
},
{
 "dates": 631,
"data": 1120.1,
"group": "fitted" 
},
{
 "dates": 632,
"data": 1120.2,
"group": "fitted" 
},
{
 "dates": 633,
"data": 1120.3,
"group": "fitted" 
},
{
 "dates": 634,
"data": 1120.5,
"group": "fitted" 
},
{
 "dates": 635,
"data": 1120.7,
"group": "fitted" 
},
{
 "dates": 636,
"data":   1121,
"group": "fitted" 
},
{
 "dates": 637,
"data": 1121.2,
"group": "fitted" 
},
{
 "dates": 638,
"data": 1121.5,
"group": "fitted" 
},
{
 "dates": 639,
"data": 1121.8,
"group": "fitted" 
},
{
 "dates": 640,
"data": 1122.2,
"group": "fitted" 
},
{
 "dates": 641,
"data": 1122.5,
"group": "fitted" 
},
{
 "dates": 642,
"data":   1123,
"group": "fitted" 
},
{
 "dates": 643,
"data": 1123.4,
"group": "fitted" 
},
{
 "dates": 644,
"data": 1123.8,
"group": "fitted" 
},
{
 "dates": 645,
"data": 1124.3,
"group": "fitted" 
},
{
 "dates": 646,
"data": 1124.9,
"group": "fitted" 
},
{
 "dates": 647,
"data": 1125.4,
"group": "fitted" 
},
{
 "dates": 648,
"data":   1126,
"group": "fitted" 
},
{
 "dates": 649,
"data": 1126.6,
"group": "fitted" 
},
{
 "dates": 650,
"data": 1127.2,
"group": "fitted" 
},
{
 "dates": 651,
"data": 1127.9,
"group": "fitted" 
},
{
 "dates": 652,
"data": 1128.6,
"group": "fitted" 
},
{
 "dates": 653,
"data": 1129.3,
"group": "fitted" 
},
{
 "dates": 654,
"data": 1130.1,
"group": "fitted" 
},
{
 "dates": 655,
"data": 1130.8,
"group": "fitted" 
},
{
 "dates": 656,
"data": 1131.6,
"group": "fitted" 
},
{
 "dates": 657,
"data": 1132.5,
"group": "fitted" 
},
{
 "dates": 658,
"data": 1133.3,
"group": "fitted" 
},
{
 "dates": 659,
"data": 1134.2,
"group": "fitted" 
},
{
 "dates": 660,
"data": 1135.1,
"group": "fitted" 
},
{
 "dates": 661,
"data": 1136.1,
"group": "fitted" 
},
{
 "dates": 662,
"data":   1137,
"group": "fitted" 
},
{
 "dates": 663,
"data":   1138,
"group": "fitted" 
},
{
 "dates": 664,
"data": 1139.1,
"group": "fitted" 
},
{
 "dates": 665,
"data": 1140.1,
"group": "fitted" 
},
{
 "dates": 666,
"data": 1141.2,
"group": "fitted" 
},
{
 "dates": 667,
"data": 1142.3,
"group": "fitted" 
},
{
 "dates": 668,
"data": 1143.4,
"group": "fitted" 
},
{
 "dates": 669,
"data": 1144.5,
"group": "fitted" 
},
{
 "dates": 670,
"data": 1145.7,
"group": "fitted" 
},
{
 "dates": 671,
"data": 1146.9,
"group": "fitted" 
},
{
 "dates": 672,
"data": 1148.1,
"group": "fitted" 
},
{
 "dates": 673,
"data": 1149.4,
"group": "fitted" 
},
{
 "dates": 674,
"data": 1150.7,
"group": "fitted" 
},
{
 "dates": 675,
"data":   1152,
"group": "fitted" 
},
{
 "dates": 676,
"data": 1153.3,
"group": "fitted" 
},
{
 "dates": 677,
"data": 1154.6,
"group": "fitted" 
},
{
 "dates": 678,
"data":   1156,
"group": "fitted" 
},
{
 "dates": 679,
"data": 1157.4,
"group": "fitted" 
},
{
 "dates": 680,
"data": 1158.8,
"group": "fitted" 
},
{
 "dates": 681,
"data": 1160.2,
"group": "fitted" 
},
{
 "dates": 682,
"data": 1161.7,
"group": "fitted" 
},
{
 "dates": 683,
"data": 1163.2,
"group": "fitted" 
},
{
 "dates": 684,
"data": 1164.7,
"group": "fitted" 
},
{
 "dates": 685,
"data": 1166.2,
"group": "fitted" 
},
{
 "dates": 686,
"data": 1167.7,
"group": "fitted" 
},
{
 "dates": 687,
"data": 1169.3,
"group": "fitted" 
},
{
 "dates": 688,
"data": 1170.9,
"group": "fitted" 
},
{
 "dates": 689,
"data": 1172.4,
"group": "fitted" 
},
{
 "dates": 690,
"data": 1174.1,
"group": "fitted" 
},
{
 "dates": 691,
"data": 1175.7,
"group": "fitted" 
},
{
 "dates": 692,
"data": 1177.3,
"group": "fitted" 
},
{
 "dates": 693,
"data":   1179,
"group": "fitted" 
},
{
 "dates": 694,
"data": 1180.7,
"group": "fitted" 
},
{
 "dates": 695,
"data": 1182.4,
"group": "fitted" 
},
{
 "dates": 696,
"data": 1184.1,
"group": "fitted" 
},
{
 "dates": 697,
"data": 1185.9,
"group": "fitted" 
},
{
 "dates": 698,
"data": 1187.6,
"group": "fitted" 
},
{
 "dates": 699,
"data": 1189.4,
"group": "fitted" 
},
{
 "dates": 700,
"data": 1191.2,
"group": "fitted" 
},
{
 "dates": 701,
"data":   1193,
"group": "fitted" 
},
{
 "dates": 702,
"data": 1194.8,
"group": "fitted" 
},
{
 "dates": 703,
"data": 1196.6,
"group": "fitted" 
},
{
 "dates": 704,
"data": 1198.4,
"group": "fitted" 
},
{
 "dates": 705,
"data": 1200.3,
"group": "fitted" 
},
{
 "dates": 706,
"data": 1202.1,
"group": "fitted" 
},
{
 "dates": 707,
"data":   1204,
"group": "fitted" 
},
{
 "dates": 708,
"data": 1205.9,
"group": "fitted" 
},
{
 "dates": 709,
"data": 1207.8,
"group": "fitted" 
},
{
 "dates": 710,
"data": 1209.7,
"group": "fitted" 
},
{
 "dates": 711,
"data": 1211.6,
"group": "fitted" 
},
{
 "dates": 712,
"data": 1213.5,
"group": "fitted" 
},
{
 "dates": 713,
"data": 1215.5,
"group": "fitted" 
},
{
 "dates": 714,
"data": 1217.4,
"group": "fitted" 
},
{
 "dates": 715,
"data": 1219.4,
"group": "fitted" 
},
{
 "dates": 716,
"data": 1221.3,
"group": "fitted" 
},
{
 "dates": 717,
"data": 1223.3,
"group": "fitted" 
},
{
 "dates": 718,
"data": 1225.3,
"group": "fitted" 
},
{
 "dates": 719,
"data": 1227.2,
"group": "fitted" 
},
{
 "dates": 720,
"data": 1229.2,
"group": "fitted" 
},
{
 "dates": 721,
"data": 1231.2,
"group": "fitted" 
},
{
 "dates": 722,
"data": 1233.2,
"group": "fitted" 
},
{
 "dates": 723,
"data": 1235.2,
"group": "fitted" 
},
{
 "dates": 724,
"data": 1237.2,
"group": "fitted" 
},
{
 "dates": 725,
"data": 1239.2,
"group": "fitted" 
},
{
 "dates": 726,
"data": 1241.2,
"group": "fitted" 
},
{
 "dates": 727,
"data": 1243.2,
"group": "fitted" 
},
{
 "dates": 728,
"data": 1245.2,
"group": "fitted" 
},
{
 "dates": 729,
"data": 1247.2,
"group": "fitted" 
},
{
 "dates": 730,
"data": 1249.2,
"group": "fitted" 
},
{
 "dates": 731,
"data":   1253,
"group": "fitted" 
},
{
 "dates": 732,
"data":   1255,
"group": "fitted" 
},
{
 "dates": 733,
"data":   1257,
"group": "fitted" 
},
{
 "dates": 734,
"data":   1259,
"group": "fitted" 
},
{
 "dates": 735,
"data":   1261,
"group": "fitted" 
},
{
 "dates": 736,
"data":   1263,
"group": "fitted" 
},
{
 "dates": 737,
"data":   1265,
"group": "fitted" 
},
{
 "dates": 738,
"data":   1267,
"group": "fitted" 
},
{
 "dates": 739,
"data":   1269,
"group": "fitted" 
},
{
 "dates": 740,
"data":   1271,
"group": "fitted" 
},
{
 "dates": 741,
"data":   1273,
"group": "fitted" 
},
{
 "dates": 742,
"data":   1275,
"group": "fitted" 
},
{
 "dates": 743,
"data":   1277,
"group": "fitted" 
},
{
 "dates": 744,
"data": 1278.9,
"group": "fitted" 
},
{
 "dates": 745,
"data": 1280.9,
"group": "fitted" 
},
{
 "dates": 746,
"data": 1282.9,
"group": "fitted" 
},
{
 "dates": 747,
"data": 1284.8,
"group": "fitted" 
},
{
 "dates": 748,
"data": 1286.7,
"group": "fitted" 
},
{
 "dates": 749,
"data": 1288.7,
"group": "fitted" 
},
{
 "dates": 750,
"data": 1290.6,
"group": "fitted" 
},
{
 "dates": 751,
"data": 1292.5,
"group": "fitted" 
},
{
 "dates": 752,
"data": 1294.4,
"group": "fitted" 
},
{
 "dates": 753,
"data": 1296.3,
"group": "fitted" 
},
{
 "dates": 754,
"data": 1298.2,
"group": "fitted" 
},
{
 "dates": 755,
"data": 1300.1,
"group": "fitted" 
},
{
 "dates": 756,
"data": 1301.9,
"group": "fitted" 
},
{
 "dates": 757,
"data": 1303.8,
"group": "fitted" 
},
{
 "dates": 758,
"data": 1305.6,
"group": "fitted" 
},
{
 "dates": 759,
"data": 1307.4,
"group": "fitted" 
},
{
 "dates": 760,
"data": 1309.3,
"group": "fitted" 
},
{
 "dates": 761,
"data":   1311,
"group": "fitted" 
},
{
 "dates": 762,
"data": 1312.8,
"group": "fitted" 
},
{
 "dates": 763,
"data": 1314.6,
"group": "fitted" 
},
{
 "dates": 764,
"data": 1316.3,
"group": "fitted" 
},
{
 "dates": 765,
"data": 1318.1,
"group": "fitted" 
},
{
 "dates": 766,
"data": 1319.8,
"group": "fitted" 
},
{
 "dates": 767,
"data": 1321.5,
"group": "fitted" 
},
{
 "dates": 768,
"data": 1323.2,
"group": "fitted" 
},
{
 "dates": 769,
"data": 1324.9,
"group": "fitted" 
},
{
 "dates": 770,
"data": 1326.5,
"group": "fitted" 
},
{
 "dates": 771,
"data": 1328.2,
"group": "fitted" 
},
{
 "dates": 772,
"data": 1329.8,
"group": "fitted" 
},
{
 "dates": 773,
"data": 1331.4,
"group": "fitted" 
},
{
 "dates": 774,
"data": 1332.9,
"group": "fitted" 
},
{
 "dates": 775,
"data": 1334.5,
"group": "fitted" 
},
{
 "dates": 776,
"data":   1336,
"group": "fitted" 
},
{
 "dates": 777,
"data": 1337.6,
"group": "fitted" 
},
{
 "dates": 778,
"data": 1339.1,
"group": "fitted" 
},
{
 "dates": 779,
"data": 1340.5,
"group": "fitted" 
},
{
 "dates": 780,
"data":   1342,
"group": "fitted" 
},
{
 "dates": 781,
"data": 1343.4,
"group": "fitted" 
},
{
 "dates": 782,
"data": 1344.8,
"group": "fitted" 
},
{
 "dates": 783,
"data": 1346.2,
"group": "fitted" 
},
{
 "dates": 784,
"data": 1347.6,
"group": "fitted" 
},
{
 "dates": 785,
"data": 1348.9,
"group": "fitted" 
},
{
 "dates": 786,
"data": 1350.2,
"group": "fitted" 
},
{
 "dates": 787,
"data": 1351.5,
"group": "fitted" 
},
{
 "dates": 788,
"data": 1352.8,
"group": "fitted" 
},
{
 "dates": 789,
"data": 1354.1,
"group": "fitted" 
},
{
 "dates": 790,
"data": 1355.3,
"group": "fitted" 
},
{
 "dates": 791,
"data": 1356.5,
"group": "fitted" 
},
{
 "dates": 792,
"data": 1357.7,
"group": "fitted" 
},
{
 "dates": 793,
"data": 1358.8,
"group": "fitted" 
},
{
 "dates": 794,
"data": 1359.9,
"group": "fitted" 
},
{
 "dates": 795,
"data":   1361,
"group": "fitted" 
},
{
 "dates": 796,
"data": 1362.1,
"group": "fitted" 
},
{
 "dates": 797,
"data": 1363.2,
"group": "fitted" 
},
{
 "dates": 798,
"data": 1364.2,
"group": "fitted" 
},
{
 "dates": 799,
"data": 1365.2,
"group": "fitted" 
},
{
 "dates": 800,
"data": 1366.1,
"group": "fitted" 
},
{
 "dates": 801,
"data": 1367.1,
"group": "fitted" 
},
{
 "dates": 802,
"data":   1368,
"group": "fitted" 
},
{
 "dates": 803,
"data": 1368.9,
"group": "fitted" 
},
{
 "dates": 804,
"data": 1369.7,
"group": "fitted" 
},
{
 "dates": 805,
"data": 1370.6,
"group": "fitted" 
},
{
 "dates": 806,
"data": 1371.4,
"group": "fitted" 
},
{
 "dates": 807,
"data": 1372.2,
"group": "fitted" 
},
{
 "dates": 808,
"data": 1372.9,
"group": "fitted" 
},
{
 "dates": 809,
"data": 1373.6,
"group": "fitted" 
},
{
 "dates": 810,
"data": 1374.3,
"group": "fitted" 
},
{
 "dates": 811,
"data":   1375,
"group": "fitted" 
},
{
 "dates": 812,
"data": 1375.6,
"group": "fitted" 
},
{
 "dates": 813,
"data": 1376.2,
"group": "fitted" 
},
{
 "dates": 814,
"data": 1376.8,
"group": "fitted" 
},
{
 "dates": 815,
"data": 1377.4,
"group": "fitted" 
},
{
 "dates": 816,
"data": 1377.9,
"group": "fitted" 
},
{
 "dates": 817,
"data": 1378.4,
"group": "fitted" 
},
{
 "dates": 818,
"data": 1378.8,
"group": "fitted" 
},
{
 "dates": 819,
"data": 1379.3,
"group": "fitted" 
},
{
 "dates": 820,
"data": 1379.7,
"group": "fitted" 
},
{
 "dates": 821,
"data":   1380,
"group": "fitted" 
},
{
 "dates": 822,
"data": 1380.4,
"group": "fitted" 
},
{
 "dates": 823,
"data": 1380.7,
"group": "fitted" 
},
{
 "dates": 824,
"data":   1381,
"group": "fitted" 
},
{
 "dates": 825,
"data": 1381.3,
"group": "fitted" 
},
{
 "dates": 826,
"data": 1381.5,
"group": "fitted" 
},
{
 "dates": 827,
"data": 1381.7,
"group": "fitted" 
},
{
 "dates": 828,
"data": 1381.9,
"group": "fitted" 
},
{
 "dates": 829,
"data":   1382,
"group": "fitted" 
},
{
 "dates": 830,
"data": 1382.1,
"group": "fitted" 
},
{
 "dates": 831,
"data": 1382.2,
"group": "fitted" 
},
{
 "dates": 832,
"data": 1382.3,
"group": "fitted" 
},
{
 "dates": 833,
"data": 1382.3,
"group": "fitted" 
},
{
 "dates": 834,
"data": 1382.3,
"group": "fitted" 
},
{
 "dates": 835,
"data": 1382.3,
"group": "fitted" 
},
{
 "dates": 836,
"data": 1382.2,
"group": "fitted" 
},
{
 "dates": 837,
"data": 1382.2,
"group": "fitted" 
},
{
 "dates": 838,
"data": 1382.1,
"group": "fitted" 
},
{
 "dates": 839,
"data": 1381.9,
"group": "fitted" 
},
{
 "dates": 840,
"data": 1381.7,
"group": "fitted" 
},
{
 "dates": 841,
"data": 1381.6,
"group": "fitted" 
},
{
 "dates": 842,
"data": 1381.3,
"group": "fitted" 
},
{
 "dates": 843,
"data": 1381.1,
"group": "fitted" 
},
{
 "dates": 844,
"data": 1380.8,
"group": "fitted" 
},
{
 "dates": 845,
"data": 1380.5,
"group": "fitted" 
},
{
 "dates": 846,
"data": 1380.2,
"group": "fitted" 
},
{
 "dates": 847,
"data": 1379.8,
"group": "fitted" 
},
{
 "dates": 848,
"data": 1379.5,
"group": "fitted" 
},
{
 "dates": 849,
"data":   1379,
"group": "fitted" 
},
{
 "dates": 850,
"data": 1378.6,
"group": "fitted" 
},
{
 "dates": 851,
"data": 1378.2,
"group": "fitted" 
},
{
 "dates": 852,
"data": 1377.7,
"group": "fitted" 
},
{
 "dates": 853,
"data": 1377.2,
"group": "fitted" 
},
{
 "dates": 854,
"data": 1376.6,
"group": "fitted" 
},
{
 "dates": 855,
"data": 1376.1,
"group": "fitted" 
},
{
 "dates": 856,
"data": 1375.5,
"group": "fitted" 
},
{
 "dates": 857,
"data": 1374.9,
"group": "fitted" 
},
{
 "dates": 858,
"data": 1374.3,
"group": "fitted" 
},
{
 "dates": 859,
"data": 1373.6,
"group": "fitted" 
},
{
 "dates": 860,
"data": 1372.9,
"group": "fitted" 
},
{
 "dates": 861,
"data": 1372.2,
"group": "fitted" 
},
{
 "dates": 862,
"data": 1371.5,
"group": "fitted" 
},
{
 "dates": 863,
"data": 1370.8,
"group": "fitted" 
},
{
 "dates": 864,
"data":   1370,
"group": "fitted" 
},
{
 "dates": 865,
"data": 1369.2,
"group": "fitted" 
},
{
 "dates": 866,
"data": 1368.4,
"group": "fitted" 
},
{
 "dates": 867,
"data": 1367.6,
"group": "fitted" 
},
{
 "dates": 868,
"data": 1366.7,
"group": "fitted" 
},
{
 "dates": 869,
"data": 1365.8,
"group": "fitted" 
},
{
 "dates": 870,
"data": 1364.9,
"group": "fitted" 
},
{
 "dates": 871,
"data":   1364,
"group": "fitted" 
},
{
 "dates": 872,
"data": 1363.1,
"group": "fitted" 
},
{
 "dates": 873,
"data": 1362.2,
"group": "fitted" 
},
{
 "dates": 874,
"data": 1361.2,
"group": "fitted" 
},
{
 "dates": 875,
"data": 1360.2,
"group": "fitted" 
},
{
 "dates": 876,
"data": 1359.2,
"group": "fitted" 
},
{
 "dates": 877,
"data": 1358.2,
"group": "fitted" 
},
{
 "dates": 878,
"data": 1357.1,
"group": "fitted" 
},
{
 "dates": 879,
"data": 1356.1,
"group": "fitted" 
},
{
 "dates": 880,
"data":   1355,
"group": "fitted" 
},
{
 "dates": 881,
"data": 1353.9,
"group": "fitted" 
},
{
 "dates": 882,
"data": 1352.8,
"group": "fitted" 
},
{
 "dates": 883,
"data": 1351.7,
"group": "fitted" 
},
{
 "dates": 884,
"data": 1350.6,
"group": "fitted" 
},
{
 "dates": 885,
"data": 1349.4,
"group": "fitted" 
},
{
 "dates": 886,
"data": 1348.3,
"group": "fitted" 
},
{
 "dates": 887,
"data": 1347.1,
"group": "fitted" 
},
{
 "dates": 888,
"data": 1345.9,
"group": "fitted" 
},
{
 "dates": 889,
"data": 1344.7,
"group": "fitted" 
},
{
 "dates": 890,
"data": 1343.5,
"group": "fitted" 
},
{
 "dates": 891,
"data": 1342.3,
"group": "fitted" 
},
{
 "dates": 892,
"data": 1341.1,
"group": "fitted" 
},
{
 "dates": 893,
"data": 1339.9,
"group": "fitted" 
},
{
 "dates": 894,
"data": 1338.6,
"group": "fitted" 
},
{
 "dates": 895,
"data": 1337.3,
"group": "fitted" 
},
{
 "dates": 896,
"data": 1336.1,
"group": "fitted" 
},
{
 "dates": 897,
"data": 1334.8,
"group": "fitted" 
},
{
 "dates": 898,
"data": 1333.5,
"group": "fitted" 
},
{
 "dates": 899,
"data": 1332.2,
"group": "fitted" 
},
{
 "dates": 900,
"data": 1330.9,
"group": "fitted" 
},
{
 "dates": 901,
"data": 1329.6,
"group": "fitted" 
},
{
 "dates": 902,
"data": 1328.3,
"group": "fitted" 
},
{
 "dates": 903,
"data":   1327,
"group": "fitted" 
},
{
 "dates": 904,
"data": 1325.7,
"group": "fitted" 
},
{
 "dates": 905,
"data": 1324.4,
"group": "fitted" 
},
{
 "dates": 906,
"data":   1323,
"group": "fitted" 
},
{
 "dates": 907,
"data": 1321.7,
"group": "fitted" 
},
{
 "dates": 908,
"data": 1320.4,
"group": "fitted" 
},
{
 "dates": 909,
"data":   1319,
"group": "fitted" 
},
{
 "dates": 910,
"data": 1317.7,
"group": "fitted" 
},
{
 "dates": 911,
"data": 1316.4,
"group": "fitted" 
},
{
 "dates": 912,
"data":   1315,
"group": "fitted" 
},
{
 "dates": 913,
"data": 1313.7,
"group": "fitted" 
},
{
 "dates": 914,
"data": 1312.3,
"group": "fitted" 
},
{
 "dates": 915,
"data":   1311,
"group": "fitted" 
},
{
 "dates": 916,
"data": 1309.7,
"group": "fitted" 
},
{
 "dates": 917,
"data": 1308.3,
"group": "fitted" 
},
{
 "dates": 918,
"data":   1307,
"group": "fitted" 
},
{
 "dates": 919,
"data": 1305.6,
"group": "fitted" 
},
{
 "dates": 920,
"data": 1304.3,
"group": "fitted" 
},
{
 "dates": 921,
"data":   1303,
"group": "fitted" 
},
{
 "dates": 922,
"data": 1301.7,
"group": "fitted" 
},
{
 "dates": 923,
"data": 1300.3,
"group": "fitted" 
},
{
 "dates": 924,
"data":   1299,
"group": "fitted" 
},
{
 "dates": 925,
"data": 1297.7,
"group": "fitted" 
},
{
 "dates": 926,
"data": 1296.4,
"group": "fitted" 
},
{
 "dates": 927,
"data": 1295.1,
"group": "fitted" 
},
{
 "dates": 928,
"data": 1293.8,
"group": "fitted" 
},
{
 "dates": 929,
"data": 1292.5,
"group": "fitted" 
},
{
 "dates": 930,
"data": 1291.3,
"group": "fitted" 
},
{
 "dates": 931,
"data":   1290,
"group": "fitted" 
},
{
 "dates": 932,
"data": 1288.7,
"group": "fitted" 
},
{
 "dates": 933,
"data": 1287.5,
"group": "fitted" 
},
{
 "dates": 934,
"data": 1286.3,
"group": "fitted" 
},
{
 "dates": 935,
"data":   1285,
"group": "fitted" 
},
{
 "dates": 936,
"data": 1283.8,
"group": "fitted" 
},
{
 "dates": 937,
"data": 1282.6,
"group": "fitted" 
},
{
 "dates": 938,
"data": 1281.4,
"group": "fitted" 
},
{
 "dates": 939,
"data": 1280.2,
"group": "fitted" 
},
{
 "dates": 940,
"data": 1279.1,
"group": "fitted" 
},
{
 "dates": 941,
"data": 1277.9,
"group": "fitted" 
},
{
 "dates": 942,
"data": 1276.8,
"group": "fitted" 
},
{
 "dates": 943,
"data": 1275.6,
"group": "fitted" 
},
{
 "dates": 944,
"data": 1274.5,
"group": "fitted" 
},
{
 "dates": 945,
"data": 1273.4,
"group": "fitted" 
},
{
 "dates": 946,
"data": 1272.3,
"group": "fitted" 
},
{
 "dates": 947,
"data": 1271.3,
"group": "fitted" 
},
{
 "dates": 948,
"data": 1270.2,
"group": "fitted" 
},
{
 "dates": 949,
"data": 1269.2,
"group": "fitted" 
},
{
 "dates": 950,
"data": 1268.2,
"group": "fitted" 
},
{
 "dates": 951,
"data": 1267.2,
"group": "fitted" 
},
{
 "dates": 952,
"data": 1266.2,
"group": "fitted" 
},
{
 "dates": 953,
"data": 1265.2,
"group": "fitted" 
},
{
 "dates": 954,
"data": 1264.2,
"group": "fitted" 
},
{
 "dates": 955,
"data": 1263.3,
"group": "fitted" 
},
{
 "dates": 956,
"data": 1262.4,
"group": "fitted" 
},
{
 "dates": 957,
"data": 1261.5,
"group": "fitted" 
},
{
 "dates": 958,
"data": 1260.6,
"group": "fitted" 
},
{
 "dates": 959,
"data": 1259.8,
"group": "fitted" 
},
{
 "dates": 960,
"data":   1259,
"group": "fitted" 
},
{
 "dates": 961,
"data": 1258.2,
"group": "fitted" 
},
{
 "dates": 962,
"data": 1257.4,
"group": "fitted" 
},
{
 "dates": 963,
"data": 1256.6,
"group": "fitted" 
},
{
 "dates": 964,
"data": 1255.9,
"group": "fitted" 
},
{
 "dates": 965,
"data": 1255.1,
"group": "fitted" 
},
{
 "dates": 966,
"data": 1254.4,
"group": "fitted" 
},
{
 "dates": 967,
"data": 1253.8,
"group": "fitted" 
},
{
 "dates": 968,
"data": 1253.1,
"group": "fitted" 
},
{
 "dates": 969,
"data": 1252.5,
"group": "fitted" 
},
{
 "dates": 970,
"data": 1251.9,
"group": "fitted" 
},
{
 "dates": 971,
"data": 1251.3,
"group": "fitted" 
},
{
 "dates": 972,
"data": 1250.7,
"group": "fitted" 
},
{
 "dates": 973,
"data": 1250.2,
"group": "fitted" 
},
{
 "dates": 974,
"data": 1249.7,
"group": "fitted" 
},
{
 "dates": 975,
"data": 1249.2,
"group": "fitted" 
},
{
 "dates": 976,
"data": 1248.7,
"group": "fitted" 
},
{
 "dates": 977,
"data": 1248.3,
"group": "fitted" 
},
{
 "dates": 978,
"data": 1247.9,
"group": "fitted" 
},
{
 "dates": 979,
"data": 1247.5,
"group": "fitted" 
},
{
 "dates": 980,
"data": 1247.2,
"group": "fitted" 
},
{
 "dates": 981,
"data": 1246.8,
"group": "fitted" 
},
{
 "dates": 982,
"data": 1246.5,
"group": "fitted" 
},
{
 "dates": 983,
"data": 1246.3,
"group": "fitted" 
},
{
 "dates": 984,
"data":   1246,
"group": "fitted" 
},
{
 "dates": 985,
"data": 1245.8,
"group": "fitted" 
},
{
 "dates": 986,
"data": 1245.6,
"group": "fitted" 
},
{
 "dates": 987,
"data": 1245.4,
"group": "fitted" 
},
{
 "dates": 988,
"data": 1245.3,
"group": "fitted" 
},
{
 "dates": 989,
"data": 1245.2,
"group": "fitted" 
},
{
 "dates": 990,
"data": 1245.1,
"group": "fitted" 
},
{
 "dates": 991,
"data": 1245.1,
"group": "fitted" 
},
{
 "dates": 992,
"data":   1245,
"group": "fitted" 
},
{
 "dates": 993,
"data":   1245,
"group": "fitted" 
},
{
 "dates": 994,
"data": 1245.1,
"group": "fitted" 
},
{
 "dates": 995,
"data": 1245.1,
"group": "fitted" 
},
{
 "dates": 996,
"data": 1245.2,
"group": "fitted" 
},
{
 "dates": 997,
"data": 1245.3,
"group": "fitted" 
},
{
 "dates": 998,
"data": 1245.5,
"group": "fitted" 
},
{
 "dates": 999,
"data": 1245.7,
"group": "fitted" 
},
{
 "dates": 1000,
"data": 1245.9,
"group": "fitted" 
},
{
 "dates": 1001,
"data": 1246.1,
"group": "fitted" 
},
{
 "dates": 1002,
"data": 1246.3,
"group": "fitted" 
},
{
 "dates": 1003,
"data": 1246.6,
"group": "fitted" 
},
{
 "dates": 1004,
"data":   1247,
"group": "fitted" 
},
{
 "dates": 1005,
"data": 1247.3,
"group": "fitted" 
},
{
 "dates": 1006,
"data": 1247.7,
"group": "fitted" 
},
{
 "dates": 1007,
"data": 1248.1,
"group": "fitted" 
},
{
 "dates": 1008,
"data": 1248.5,
"group": "fitted" 
},
{
 "dates": 1009,
"data":   1249,
"group": "fitted" 
},
{
 "dates": 1010,
"data": 1249.5,
"group": "fitted" 
},
{
 "dates": 1011,
"data":   1250,
"group": "fitted" 
},
{
 "dates": 1012,
"data": 1250.5,
"group": "fitted" 
},
{
 "dates": 1013,
"data": 1251.1,
"group": "fitted" 
},
{
 "dates": 1014,
"data": 1251.7,
"group": "fitted" 
},
{
 "dates": 1015,
"data": 1252.4,
"group": "fitted" 
},
{
 "dates": 1016,
"data":   1253,
"group": "fitted" 
},
{
 "dates": 1017,
"data": 1253.7,
"group": "fitted" 
},
{
 "dates": 1018,
"data": 1254.4,
"group": "fitted" 
},
{
 "dates": 1019,
"data": 1255.2,
"group": "fitted" 
},
{
 "dates": 1020,
"data":   1256,
"group": "fitted" 
},
{
 "dates": 1021,
"data": 1256.8,
"group": "fitted" 
},
{
 "dates": 1022,
"data": 1257.6,
"group": "fitted" 
},
{
 "dates": 1023,
"data": 1258.5,
"group": "fitted" 
},
{
 "dates": 1024,
"data": 1259.4,
"group": "fitted" 
},
{
 "dates": 1025,
"data": 1260.3,
"group": "fitted" 
},
{
 "dates": 1026,
"data": 1261.2,
"group": "fitted" 
},
{
 "dates": 1027,
"data": 1262.2,
"group": "fitted" 
},
{
 "dates": 1028,
"data": 1263.2,
"group": "fitted" 
},
{
 "dates": 1029,
"data": 1264.2,
"group": "fitted" 
},
{
 "dates": 1030,
"data": 1265.2,
"group": "fitted" 
},
{
 "dates": 1031,
"data": 1266.3,
"group": "fitted" 
},
{
 "dates": 1032,
"data": 1267.4,
"group": "fitted" 
},
{
 "dates": 1033,
"data": 1268.5,
"group": "fitted" 
},
{
 "dates": 1034,
"data": 1269.7,
"group": "fitted" 
},
{
 "dates": 1035,
"data": 1270.9,
"group": "fitted" 
},
{
 "dates": 1036,
"data": 1272.1,
"group": "fitted" 
},
{
 "dates": 1037,
"data": 1273.3,
"group": "fitted" 
},
{
 "dates": 1038,
"data": 1274.5,
"group": "fitted" 
},
{
 "dates": 1039,
"data": 1275.8,
"group": "fitted" 
},
{
 "dates": 1040,
"data": 1277.1,
"group": "fitted" 
},
{
 "dates": 1041,
"data": 1278.4,
"group": "fitted" 
},
{
 "dates": 1042,
"data": 1279.8,
"group": "fitted" 
},
{
 "dates": 1043,
"data": 1281.1,
"group": "fitted" 
},
{
 "dates": 1044,
"data": 1282.5,
"group": "fitted" 
},
{
 "dates": 1045,
"data": 1283.9,
"group": "fitted" 
},
{
 "dates": 1046,
"data": 1285.4,
"group": "fitted" 
},
{
 "dates": 1047,
"data": 1286.8,
"group": "fitted" 
},
{
 "dates": 1048,
"data": 1288.3,
"group": "fitted" 
},
{
 "dates": 1049,
"data": 1289.8,
"group": "fitted" 
},
{
 "dates": 1050,
"data": 1291.3,
"group": "fitted" 
},
{
 "dates": 1051,
"data": 1292.9,
"group": "fitted" 
},
{
 "dates": 1052,
"data": 1294.4,
"group": "fitted" 
},
{
 "dates": 1053,
"data":   1296,
"group": "fitted" 
},
{
 "dates": 1054,
"data": 1297.6,
"group": "fitted" 
},
{
 "dates": 1055,
"data": 1299.2,
"group": "fitted" 
},
{
 "dates": 1056,
"data": 1300.8,
"group": "fitted" 
},
{
 "dates": 1057,
"data": 1302.5,
"group": "fitted" 
},
{
 "dates": 1058,
"data": 1304.2,
"group": "fitted" 
},
{
 "dates": 1059,
"data": 1305.8,
"group": "fitted" 
},
{
 "dates": 1060,
"data": 1307.5,
"group": "fitted" 
},
{
 "dates": 1061,
"data": 1309.3,
"group": "fitted" 
},
{
 "dates": 1062,
"data":   1311,
"group": "fitted" 
},
{
 "dates": 1063,
"data": 1312.8,
"group": "fitted" 
},
{
 "dates": 1064,
"data": 1314.5,
"group": "fitted" 
},
{
 "dates": 1065,
"data": 1316.3,
"group": "fitted" 
},
{
 "dates": 1066,
"data": 1318.1,
"group": "fitted" 
},
{
 "dates": 1067,
"data": 1319.9,
"group": "fitted" 
},
{
 "dates": 1068,
"data": 1321.7,
"group": "fitted" 
},
{
 "dates": 1069,
"data": 1323.6,
"group": "fitted" 
},
{
 "dates": 1070,
"data": 1325.4,
"group": "fitted" 
},
{
 "dates": 1071,
"data": 1327.3,
"group": "fitted" 
},
{
 "dates": 1072,
"data": 1329.2,
"group": "fitted" 
},
{
 "dates": 1073,
"data":   1331,
"group": "fitted" 
},
{
 "dates": 1074,
"data": 1332.9,
"group": "fitted" 
},
{
 "dates": 1075,
"data": 1334.8,
"group": "fitted" 
},
{
 "dates": 1076,
"data": 1336.8,
"group": "fitted" 
},
{
 "dates": 1077,
"data": 1338.7,
"group": "fitted" 
},
{
 "dates": 1078,
"data": 1340.6,
"group": "fitted" 
},
{
 "dates": 1079,
"data": 1342.6,
"group": "fitted" 
},
{
 "dates": 1080,
"data": 1344.5,
"group": "fitted" 
},
{
 "dates": 1081,
"data": 1346.5,
"group": "fitted" 
},
{
 "dates": 1082,
"data": 1348.4,
"group": "fitted" 
},
{
 "dates": 1083,
"data": 1350.4,
"group": "fitted" 
},
{
 "dates": 1084,
"data": 1352.4,
"group": "fitted" 
},
{
 "dates": 1085,
"data": 1354.3,
"group": "fitted" 
},
{
 "dates": 1086,
"data": 1356.3,
"group": "fitted" 
},
{
 "dates": 1087,
"data": 1358.3,
"group": "fitted" 
},
{
 "dates": 1088,
"data": 1360.3,
"group": "fitted" 
},
{
 "dates": 1089,
"data": 1362.3,
"group": "fitted" 
},
{
 "dates": 1090,
"data": 1364.3,
"group": "fitted" 
},
{
 "dates": 1091,
"data": 1366.3,
"group": "fitted" 
},
{
 "dates": 1092,
"data": 1368.3,
"group": "fitted" 
},
{
 "dates": 1093,
"data": 1370.3,
"group": "fitted" 
},
{
 "dates": 1094,
"data": 1372.3,
"group": "fitted" 
},
{
 "dates": 1095,
"data": 1374.3,
"group": "fitted" 
},
{
 "dates": 1096,
"data": 1378.1,
"group": "fitted" 
},
{
 "dates": 1097,
"data": 1380.2,
"group": "fitted" 
},
{
 "dates": 1098,
"data": 1382.2,
"group": "fitted" 
},
{
 "dates": 1099,
"data": 1384.2,
"group": "fitted" 
},
{
 "dates": 1100,
"data": 1386.2,
"group": "fitted" 
},
{
 "dates": 1101,
"data": 1388.2,
"group": "fitted" 
},
{
 "dates": 1102,
"data": 1390.2,
"group": "fitted" 
},
{
 "dates": 1103,
"data": 1392.2,
"group": "fitted" 
},
{
 "dates": 1104,
"data": 1394.2,
"group": "fitted" 
},
{
 "dates": 1105,
"data": 1396.2,
"group": "fitted" 
},
{
 "dates": 1106,
"data": 1398.1,
"group": "fitted" 
},
{
 "dates": 1107,
"data": 1400.1,
"group": "fitted" 
},
{
 "dates": 1108,
"data": 1402.1,
"group": "fitted" 
},
{
 "dates": 1109,
"data": 1404.1,
"group": "fitted" 
},
{
 "dates": 1110,
"data":   1406,
"group": "fitted" 
},
{
 "dates": 1111,
"data":   1408,
"group": "fitted" 
},
{
 "dates": 1112,
"data": 1409.9,
"group": "fitted" 
},
{
 "dates": 1113,
"data": 1411.9,
"group": "fitted" 
},
{
 "dates": 1114,
"data": 1413.8,
"group": "fitted" 
},
{
 "dates": 1115,
"data": 1415.7,
"group": "fitted" 
},
{
 "dates": 1116,
"data": 1417.7,
"group": "fitted" 
},
{
 "dates": 1117,
"data": 1419.6,
"group": "fitted" 
},
{
 "dates": 1118,
"data": 1421.5,
"group": "fitted" 
},
{
 "dates": 1119,
"data": 1423.3,
"group": "fitted" 
},
{
 "dates": 1120,
"data": 1425.2,
"group": "fitted" 
},
{
 "dates": 1121,
"data": 1427.1,
"group": "fitted" 
},
{
 "dates": 1122,
"data": 1428.9,
"group": "fitted" 
},
{
 "dates": 1123,
"data": 1430.8,
"group": "fitted" 
},
{
 "dates": 1124,
"data": 1432.6,
"group": "fitted" 
},
{
 "dates": 1125,
"data": 1434.4,
"group": "fitted" 
},
{
 "dates": 1126,
"data": 1436.2,
"group": "fitted" 
},
{
 "dates": 1127,
"data":   1438,
"group": "fitted" 
},
{
 "dates": 1128,
"data": 1439.7,
"group": "fitted" 
},
{
 "dates": 1129,
"data": 1441.5,
"group": "fitted" 
},
{
 "dates": 1130,
"data": 1443.2,
"group": "fitted" 
},
{
 "dates": 1131,
"data": 1444.9,
"group": "fitted" 
},
{
 "dates": 1132,
"data": 1446.6,
"group": "fitted" 
},
{
 "dates": 1133,
"data": 1448.3,
"group": "fitted" 
},
{
 "dates": 1134,
"data":   1450,
"group": "fitted" 
},
{
 "dates": 1135,
"data": 1451.7,
"group": "fitted" 
},
{
 "dates": 1136,
"data": 1453.3,
"group": "fitted" 
},
{
 "dates": 1137,
"data": 1454.9,
"group": "fitted" 
},
{
 "dates": 1138,
"data": 1456.5,
"group": "fitted" 
},
{
 "dates": 1139,
"data": 1458.1,
"group": "fitted" 
},
{
 "dates": 1140,
"data": 1459.6,
"group": "fitted" 
},
{
 "dates": 1141,
"data": 1461.2,
"group": "fitted" 
},
{
 "dates": 1142,
"data": 1462.7,
"group": "fitted" 
},
{
 "dates": 1143,
"data": 1464.2,
"group": "fitted" 
},
{
 "dates": 1144,
"data": 1465.7,
"group": "fitted" 
},
{
 "dates": 1145,
"data": 1467.1,
"group": "fitted" 
},
{
 "dates": 1146,
"data": 1468.6,
"group": "fitted" 
},
{
 "dates": 1147,
"data":   1470,
"group": "fitted" 
},
{
 "dates": 1148,
"data": 1471.4,
"group": "fitted" 
},
{
 "dates": 1149,
"data": 1472.7,
"group": "fitted" 
},
{
 "dates": 1150,
"data": 1474.1,
"group": "fitted" 
},
{
 "dates": 1151,
"data": 1475.4,
"group": "fitted" 
},
{
 "dates": 1152,
"data": 1476.7,
"group": "fitted" 
},
{
 "dates": 1153,
"data":   1478,
"group": "fitted" 
},
{
 "dates": 1154,
"data": 1479.2,
"group": "fitted" 
},
{
 "dates": 1155,
"data": 1480.4,
"group": "fitted" 
},
{
 "dates": 1156,
"data": 1481.6,
"group": "fitted" 
},
{
 "dates": 1157,
"data": 1482.8,
"group": "fitted" 
},
{
 "dates": 1158,
"data":   1484,
"group": "fitted" 
},
{
 "dates": 1159,
"data": 1485.1,
"group": "fitted" 
},
{
 "dates": 1160,
"data": 1486.2,
"group": "fitted" 
},
{
 "dates": 1161,
"data": 1487.3,
"group": "fitted" 
},
{
 "dates": 1162,
"data": 1488.3,
"group": "fitted" 
},
{
 "dates": 1163,
"data": 1489.3,
"group": "fitted" 
},
{
 "dates": 1164,
"data": 1490.3,
"group": "fitted" 
},
{
 "dates": 1165,
"data": 1491.3,
"group": "fitted" 
},
{
 "dates": 1166,
"data": 1492.2,
"group": "fitted" 
},
{
 "dates": 1167,
"data": 1493.1,
"group": "fitted" 
},
{
 "dates": 1168,
"data":   1494,
"group": "fitted" 
},
{
 "dates": 1169,
"data": 1494.9,
"group": "fitted" 
},
{
 "dates": 1170,
"data": 1495.7,
"group": "fitted" 
},
{
 "dates": 1171,
"data": 1496.5,
"group": "fitted" 
},
{
 "dates": 1172,
"data": 1497.3,
"group": "fitted" 
},
{
 "dates": 1173,
"data":   1498,
"group": "fitted" 
},
{
 "dates": 1174,
"data": 1498.8,
"group": "fitted" 
},
{
 "dates": 1175,
"data": 1499.5,
"group": "fitted" 
},
{
 "dates": 1176,
"data": 1500.1,
"group": "fitted" 
},
{
 "dates": 1177,
"data": 1500.8,
"group": "fitted" 
},
{
 "dates": 1178,
"data": 1501.4,
"group": "fitted" 
},
{
 "dates": 1179,
"data": 1501.9,
"group": "fitted" 
},
{
 "dates": 1180,
"data": 1502.5,
"group": "fitted" 
},
{
 "dates": 1181,
"data":   1503,
"group": "fitted" 
},
{
 "dates": 1182,
"data": 1503.5,
"group": "fitted" 
},
{
 "dates": 1183,
"data":   1504,
"group": "fitted" 
},
{
 "dates": 1184,
"data": 1504.4,
"group": "fitted" 
},
{
 "dates": 1185,
"data": 1504.8,
"group": "fitted" 
},
{
 "dates": 1186,
"data": 1505.2,
"group": "fitted" 
},
{
 "dates": 1187,
"data": 1505.5,
"group": "fitted" 
},
{
 "dates": 1188,
"data": 1505.9,
"group": "fitted" 
},
{
 "dates": 1189,
"data": 1506.1,
"group": "fitted" 
},
{
 "dates": 1190,
"data": 1506.4,
"group": "fitted" 
},
{
 "dates": 1191,
"data": 1506.6,
"group": "fitted" 
},
{
 "dates": 1192,
"data": 1506.8,
"group": "fitted" 
},
{
 "dates": 1193,
"data":   1507,
"group": "fitted" 
},
{
 "dates": 1194,
"data": 1507.2,
"group": "fitted" 
},
{
 "dates": 1195,
"data": 1507.3,
"group": "fitted" 
},
{
 "dates": 1196,
"data": 1507.4,
"group": "fitted" 
},
{
 "dates": 1197,
"data": 1507.4,
"group": "fitted" 
},
{
 "dates": 1198,
"data": 1507.5,
"group": "fitted" 
},
{
 "dates": 1199,
"data": 1507.5,
"group": "fitted" 
},
{
 "dates": 1200,
"data": 1507.4,
"group": "fitted" 
},
{
 "dates": 1201,
"data": 1507.4,
"group": "fitted" 
},
{
 "dates": 1202,
"data": 1507.3,
"group": "fitted" 
},
{
 "dates": 1203,
"data": 1507.2,
"group": "fitted" 
},
{
 "dates": 1204,
"data": 1507.1,
"group": "fitted" 
},
{
 "dates": 1205,
"data": 1506.9,
"group": "fitted" 
},
{
 "dates": 1206,
"data": 1506.7,
"group": "fitted" 
},
{
 "dates": 1207,
"data": 1506.5,
"group": "fitted" 
},
{
 "dates": 1208,
"data": 1506.2,
"group": "fitted" 
},
{
 "dates": 1209,
"data":   1506,
"group": "fitted" 
},
{
 "dates": 1210,
"data": 1505.7,
"group": "fitted" 
},
{
 "dates": 1211,
"data": 1505.3,
"group": "fitted" 
},
{
 "dates": 1212,
"data":   1505,
"group": "fitted" 
},
{
 "dates": 1213,
"data": 1504.6,
"group": "fitted" 
},
{
 "dates": 1214,
"data": 1504.2,
"group": "fitted" 
},
{
 "dates": 1215,
"data": 1503.8,
"group": "fitted" 
},
{
 "dates": 1216,
"data": 1503.3,
"group": "fitted" 
},
{
 "dates": 1217,
"data": 1502.8,
"group": "fitted" 
},
{
 "dates": 1218,
"data": 1502.3,
"group": "fitted" 
},
{
 "dates": 1219,
"data": 1501.8,
"group": "fitted" 
},
{
 "dates": 1220,
"data": 1501.2,
"group": "fitted" 
},
{
 "dates": 1221,
"data": 1500.6,
"group": "fitted" 
},
{
 "dates": 1222,
"data":   1500,
"group": "fitted" 
},
{
 "dates": 1223,
"data": 1499.4,
"group": "fitted" 
},
{
 "dates": 1224,
"data": 1498.7,
"group": "fitted" 
},
{
 "dates": 1225,
"data": 1498.1,
"group": "fitted" 
},
{
 "dates": 1226,
"data": 1497.4,
"group": "fitted" 
},
{
 "dates": 1227,
"data": 1496.6,
"group": "fitted" 
},
{
 "dates": 1228,
"data": 1495.9,
"group": "fitted" 
},
{
 "dates": 1229,
"data": 1495.1,
"group": "fitted" 
},
{
 "dates": 1230,
"data": 1494.3,
"group": "fitted" 
},
{
 "dates": 1231,
"data": 1493.5,
"group": "fitted" 
},
{
 "dates": 1232,
"data": 1492.7,
"group": "fitted" 
},
{
 "dates": 1233,
"data": 1491.8,
"group": "fitted" 
},
{
 "dates": 1234,
"data":   1491,
"group": "fitted" 
},
{
 "dates": 1235,
"data": 1490.1,
"group": "fitted" 
},
{
 "dates": 1236,
"data": 1489.2,
"group": "fitted" 
},
{
 "dates": 1237,
"data": 1488.2,
"group": "fitted" 
},
{
 "dates": 1238,
"data": 1487.3,
"group": "fitted" 
},
{
 "dates": 1239,
"data": 1486.3,
"group": "fitted" 
},
{
 "dates": 1240,
"data": 1485.3,
"group": "fitted" 
},
{
 "dates": 1241,
"data": 1484.3,
"group": "fitted" 
},
{
 "dates": 1242,
"data": 1483.3,
"group": "fitted" 
},
{
 "dates": 1243,
"data": 1482.3,
"group": "fitted" 
},
{
 "dates": 1244,
"data": 1481.2,
"group": "fitted" 
},
{
 "dates": 1245,
"data": 1480.2,
"group": "fitted" 
},
{
 "dates": 1246,
"data": 1479.1,
"group": "fitted" 
},
{
 "dates": 1247,
"data":   1478,
"group": "fitted" 
},
{
 "dates": 1248,
"data": 1476.9,
"group": "fitted" 
},
{
 "dates": 1249,
"data": 1475.7,
"group": "fitted" 
},
{
 "dates": 1250,
"data": 1474.6,
"group": "fitted" 
},
{
 "dates": 1251,
"data": 1473.4,
"group": "fitted" 
},
{
 "dates": 1252,
"data": 1472.3,
"group": "fitted" 
},
{
 "dates": 1253,
"data": 1471.1,
"group": "fitted" 
},
{
 "dates": 1254,
"data": 1469.9,
"group": "fitted" 
},
{
 "dates": 1255,
"data": 1468.7,
"group": "fitted" 
},
{
 "dates": 1256,
"data": 1467.5,
"group": "fitted" 
},
{
 "dates": 1257,
"data": 1466.2,
"group": "fitted" 
},
{
 "dates": 1258,
"data":   1465,
"group": "fitted" 
},
{
 "dates": 1259,
"data": 1463.7,
"group": "fitted" 
},
{
 "dates": 1260,
"data": 1462.5,
"group": "fitted" 
},
{
 "dates": 1261,
"data": 1461.2,
"group": "fitted" 
},
{
 "dates": 1262,
"data": 1459.9,
"group": "fitted" 
},
{
 "dates": 1263,
"data": 1458.7,
"group": "fitted" 
},
{
 "dates": 1264,
"data": 1457.4,
"group": "fitted" 
},
{
 "dates": 1265,
"data": 1456.1,
"group": "fitted" 
},
{
 "dates": 1266,
"data": 1454.8,
"group": "fitted" 
},
{
 "dates": 1267,
"data": 1453.5,
"group": "fitted" 
},
{
 "dates": 1268,
"data": 1452.2,
"group": "fitted" 
},
{
 "dates": 1269,
"data": 1450.8,
"group": "fitted" 
},
{
 "dates": 1270,
"data": 1449.5,
"group": "fitted" 
},
{
 "dates": 1271,
"data": 1448.2,
"group": "fitted" 
},
{
 "dates": 1272,
"data": 1446.8,
"group": "fitted" 
},
{
 "dates": 1273,
"data": 1445.5,
"group": "fitted" 
},
{
 "dates": 1274,
"data": 1444.2,
"group": "fitted" 
},
{
 "dates": 1275,
"data": 1442.8,
"group": "fitted" 
},
{
 "dates": 1276,
"data": 1441.5,
"group": "fitted" 
},
{
 "dates": 1277,
"data": 1440.2,
"group": "fitted" 
},
{
 "dates": 1278,
"data": 1438.8,
"group": "fitted" 
},
{
 "dates": 1279,
"data": 1437.5,
"group": "fitted" 
},
{
 "dates": 1280,
"data": 1436.1,
"group": "fitted" 
},
{
 "dates": 1281,
"data": 1434.8,
"group": "fitted" 
},
{
 "dates": 1282,
"data": 1433.5,
"group": "fitted" 
},
{
 "dates": 1283,
"data": 1432.1,
"group": "fitted" 
},
{
 "dates": 1284,
"data": 1430.8,
"group": "fitted" 
},
{
 "dates": 1285,
"data": 1429.4,
"group": "fitted" 
},
{
 "dates": 1286,
"data": 1428.1,
"group": "fitted" 
},
{
 "dates": 1287,
"data": 1426.8,
"group": "fitted" 
},
{
 "dates": 1288,
"data": 1425.5,
"group": "fitted" 
},
{
 "dates": 1289,
"data": 1424.2,
"group": "fitted" 
},
{
 "dates": 1290,
"data": 1422.9,
"group": "fitted" 
},
{
 "dates": 1291,
"data": 1421.6,
"group": "fitted" 
},
{
 "dates": 1292,
"data": 1420.3,
"group": "fitted" 
},
{
 "dates": 1293,
"data":   1419,
"group": "fitted" 
},
{
 "dates": 1294,
"data": 1417.7,
"group": "fitted" 
},
{
 "dates": 1295,
"data": 1416.4,
"group": "fitted" 
},
{
 "dates": 1296,
"data": 1415.1,
"group": "fitted" 
},
{
 "dates": 1297,
"data": 1413.9,
"group": "fitted" 
},
{
 "dates": 1298,
"data": 1412.6,
"group": "fitted" 
},
{
 "dates": 1299,
"data": 1411.4,
"group": "fitted" 
},
{
 "dates": 1300,
"data": 1410.2,
"group": "fitted" 
},
{
 "dates": 1301,
"data":   1409,
"group": "fitted" 
},
{
 "dates": 1302,
"data": 1407.7,
"group": "fitted" 
},
{
 "dates": 1303,
"data": 1406.6,
"group": "fitted" 
},
{
 "dates": 1304,
"data": 1405.4,
"group": "fitted" 
},
{
 "dates": 1305,
"data": 1404.2,
"group": "fitted" 
},
{
 "dates": 1306,
"data":   1403,
"group": "fitted" 
},
{
 "dates": 1307,
"data": 1401.9,
"group": "fitted" 
},
{
 "dates": 1308,
"data": 1400.8,
"group": "fitted" 
},
{
 "dates": 1309,
"data": 1399.7,
"group": "fitted" 
},
{
 "dates": 1310,
"data": 1398.6,
"group": "fitted" 
},
{
 "dates": 1311,
"data": 1397.5,
"group": "fitted" 
},
{
 "dates": 1312,
"data": 1396.4,
"group": "fitted" 
},
{
 "dates": 1313,
"data": 1395.3,
"group": "fitted" 
},
{
 "dates": 1314,
"data": 1394.3,
"group": "fitted" 
},
{
 "dates": 1315,
"data": 1393.3,
"group": "fitted" 
},
{
 "dates": 1316,
"data": 1392.3,
"group": "fitted" 
},
{
 "dates": 1317,
"data": 1391.3,
"group": "fitted" 
},
{
 "dates": 1318,
"data": 1390.3,
"group": "fitted" 
},
{
 "dates": 1319,
"data": 1389.4,
"group": "fitted" 
},
{
 "dates": 1320,
"data": 1388.5,
"group": "fitted" 
},
{
 "dates": 1321,
"data": 1387.5,
"group": "fitted" 
},
{
 "dates": 1322,
"data": 1386.7,
"group": "fitted" 
},
{
 "dates": 1323,
"data": 1385.8,
"group": "fitted" 
},
{
 "dates": 1324,
"data": 1384.9,
"group": "fitted" 
},
{
 "dates": 1325,
"data": 1384.1,
"group": "fitted" 
},
{
 "dates": 1326,
"data": 1383.3,
"group": "fitted" 
},
{
 "dates": 1327,
"data": 1382.5,
"group": "fitted" 
},
{
 "dates": 1328,
"data": 1381.7,
"group": "fitted" 
},
{
 "dates": 1329,
"data":   1381,
"group": "fitted" 
},
{
 "dates": 1330,
"data": 1380.3,
"group": "fitted" 
},
{
 "dates": 1331,
"data": 1379.6,
"group": "fitted" 
},
{
 "dates": 1332,
"data": 1378.9,
"group": "fitted" 
},
{
 "dates": 1333,
"data": 1378.2,
"group": "fitted" 
},
{
 "dates": 1334,
"data": 1377.6,
"group": "fitted" 
},
{
 "dates": 1335,
"data":   1377,
"group": "fitted" 
},
{
 "dates": 1336,
"data": 1376.4,
"group": "fitted" 
},
{
 "dates": 1337,
"data": 1375.9,
"group": "fitted" 
},
{
 "dates": 1338,
"data": 1375.3,
"group": "fitted" 
},
{
 "dates": 1339,
"data": 1374.8,
"group": "fitted" 
},
{
 "dates": 1340,
"data": 1374.3,
"group": "fitted" 
},
{
 "dates": 1341,
"data": 1373.9,
"group": "fitted" 
},
{
 "dates": 1342,
"data": 1373.4,
"group": "fitted" 
},
{
 "dates": 1343,
"data":   1373,
"group": "fitted" 
},
{
 "dates": 1344,
"data": 1372.7,
"group": "fitted" 
},
{
 "dates": 1345,
"data": 1372.3,
"group": "fitted" 
},
{
 "dates": 1346,
"data":   1372,
"group": "fitted" 
},
{
 "dates": 1347,
"data": 1371.7,
"group": "fitted" 
},
{
 "dates": 1348,
"data": 1371.4,
"group": "fitted" 
},
{
 "dates": 1349,
"data": 1371.2,
"group": "fitted" 
},
{
 "dates": 1350,
"data": 1370.9,
"group": "fitted" 
},
{
 "dates": 1351,
"data": 1370.7,
"group": "fitted" 
},
{
 "dates": 1352,
"data": 1370.6,
"group": "fitted" 
},
{
 "dates": 1353,
"data": 1370.4,
"group": "fitted" 
},
{
 "dates": 1354,
"data": 1370.3,
"group": "fitted" 
},
{
 "dates": 1355,
"data": 1370.2,
"group": "fitted" 
},
{
 "dates": 1356,
"data": 1370.2,
"group": "fitted" 
},
{
 "dates": 1357,
"data": 1370.2,
"group": "fitted" 
},
{
 "dates": 1358,
"data": 1370.2,
"group": "fitted" 
},
{
 "dates": 1359,
"data": 1370.2,
"group": "fitted" 
},
{
 "dates": 1360,
"data": 1370.3,
"group": "fitted" 
},
{
 "dates": 1361,
"data": 1370.4,
"group": "fitted" 
},
{
 "dates": 1362,
"data": 1370.5,
"group": "fitted" 
},
{
 "dates": 1363,
"data": 1370.6,
"group": "fitted" 
},
{
 "dates": 1364,
"data": 1370.8,
"group": "fitted" 
},
{
 "dates": 1365,
"data":   1371,
"group": "fitted" 
},
{
 "dates": 1366,
"data": 1371.2,
"group": "fitted" 
},
{
 "dates": 1367,
"data": 1371.5,
"group": "fitted" 
},
{
 "dates": 1368,
"data": 1371.8,
"group": "fitted" 
},
{
 "dates": 1369,
"data": 1372.1,
"group": "fitted" 
},
{
 "dates": 1370,
"data": 1372.4,
"group": "fitted" 
},
{
 "dates": 1371,
"data": 1372.8,
"group": "fitted" 
},
{
 "dates": 1372,
"data": 1373.2,
"group": "fitted" 
},
{
 "dates": 1373,
"data": 1373.7,
"group": "fitted" 
},
{
 "dates": 1374,
"data": 1374.1,
"group": "fitted" 
},
{
 "dates": 1375,
"data": 1374.6,
"group": "fitted" 
},
{
 "dates": 1376,
"data": 1375.1,
"group": "fitted" 
},
{
 "dates": 1377,
"data": 1375.7,
"group": "fitted" 
},
{
 "dates": 1378,
"data": 1376.3,
"group": "fitted" 
},
{
 "dates": 1379,
"data": 1376.9,
"group": "fitted" 
},
{
 "dates": 1380,
"data": 1377.5,
"group": "fitted" 
},
{
 "dates": 1381,
"data": 1378.2,
"group": "fitted" 
},
{
 "dates": 1382,
"data": 1378.9,
"group": "fitted" 
},
{
 "dates": 1383,
"data": 1379.6,
"group": "fitted" 
},
{
 "dates": 1384,
"data": 1380.3,
"group": "fitted" 
},
{
 "dates": 1385,
"data": 1381.1,
"group": "fitted" 
},
{
 "dates": 1386,
"data": 1381.9,
"group": "fitted" 
},
{
 "dates": 1387,
"data": 1382.7,
"group": "fitted" 
},
{
 "dates": 1388,
"data": 1383.6,
"group": "fitted" 
},
{
 "dates": 1389,
"data": 1384.5,
"group": "fitted" 
},
{
 "dates": 1390,
"data": 1385.4,
"group": "fitted" 
},
{
 "dates": 1391,
"data": 1386.3,
"group": "fitted" 
},
{
 "dates": 1392,
"data": 1387.3,
"group": "fitted" 
},
{
 "dates": 1393,
"data": 1388.3,
"group": "fitted" 
},
{
 "dates": 1394,
"data": 1389.3,
"group": "fitted" 
},
{
 "dates": 1395,
"data": 1390.4,
"group": "fitted" 
},
{
 "dates": 1396,
"data": 1391.4,
"group": "fitted" 
},
{
 "dates": 1397,
"data": 1392.5,
"group": "fitted" 
},
{
 "dates": 1398,
"data": 1393.7,
"group": "fitted" 
},
{
 "dates": 1399,
"data": 1394.8,
"group": "fitted" 
},
{
 "dates": 1400,
"data":   1396,
"group": "fitted" 
},
{
 "dates": 1401,
"data": 1397.2,
"group": "fitted" 
},
{
 "dates": 1402,
"data": 1398.4,
"group": "fitted" 
},
{
 "dates": 1403,
"data": 1399.7,
"group": "fitted" 
},
{
 "dates": 1404,
"data": 1400.9,
"group": "fitted" 
},
{
 "dates": 1405,
"data": 1402.2,
"group": "fitted" 
},
{
 "dates": 1406,
"data": 1403.6,
"group": "fitted" 
},
{
 "dates": 1407,
"data": 1404.9,
"group": "fitted" 
},
{
 "dates": 1408,
"data": 1406.3,
"group": "fitted" 
},
{
 "dates": 1409,
"data": 1407.7,
"group": "fitted" 
},
{
 "dates": 1410,
"data": 1409.1,
"group": "fitted" 
},
{
 "dates": 1411,
"data": 1410.5,
"group": "fitted" 
},
{
 "dates": 1412,
"data":   1412,
"group": "fitted" 
},
{
 "dates": 1413,
"data": 1413.4,
"group": "fitted" 
},
{
 "dates": 1414,
"data": 1414.9,
"group": "fitted" 
},
{
 "dates": 1415,
"data": 1416.5,
"group": "fitted" 
},
{
 "dates": 1416,
"data":   1418,
"group": "fitted" 
},
{
 "dates": 1417,
"data": 1419.5,
"group": "fitted" 
},
{
 "dates": 1418,
"data": 1421.1,
"group": "fitted" 
},
{
 "dates": 1419,
"data": 1422.7,
"group": "fitted" 
},
{
 "dates": 1420,
"data": 1424.3,
"group": "fitted" 
},
{
 "dates": 1421,
"data":   1426,
"group": "fitted" 
},
{
 "dates": 1422,
"data": 1427.6,
"group": "fitted" 
},
{
 "dates": 1423,
"data": 1429.3,
"group": "fitted" 
},
{
 "dates": 1424,
"data":   1431,
"group": "fitted" 
},
{
 "dates": 1425,
"data": 1432.7,
"group": "fitted" 
},
{
 "dates": 1426,
"data": 1434.4,
"group": "fitted" 
},
{
 "dates": 1427,
"data": 1436.1,
"group": "fitted" 
},
{
 "dates": 1428,
"data": 1437.9,
"group": "fitted" 
},
{
 "dates": 1429,
"data": 1439.7,
"group": "fitted" 
},
{
 "dates": 1430,
"data": 1441.4,
"group": "fitted" 
},
{
 "dates": 1431,
"data": 1443.2,
"group": "fitted" 
},
{
 "dates": 1432,
"data":   1445,
"group": "fitted" 
},
{
 "dates": 1433,
"data": 1446.9,
"group": "fitted" 
},
{
 "dates": 1434,
"data": 1448.7,
"group": "fitted" 
},
{
 "dates": 1435,
"data": 1450.6,
"group": "fitted" 
},
{
 "dates": 1436,
"data": 1452.4,
"group": "fitted" 
},
{
 "dates": 1437,
"data": 1454.3,
"group": "fitted" 
},
{
 "dates": 1438,
"data": 1456.2,
"group": "fitted" 
},
{
 "dates": 1439,
"data": 1458.1,
"group": "fitted" 
},
{
 "dates": 1440,
"data":   1460,
"group": "fitted" 
},
{
 "dates": 1441,
"data": 1461.9,
"group": "fitted" 
},
{
 "dates": 1442,
"data": 1463.8,
"group": "fitted" 
},
{
 "dates": 1443,
"data": 1465.7,
"group": "fitted" 
},
{
 "dates": 1444,
"data": 1467.7,
"group": "fitted" 
},
{
 "dates": 1445,
"data": 1469.6,
"group": "fitted" 
},
{
 "dates": 1446,
"data": 1471.6,
"group": "fitted" 
},
{
 "dates": 1447,
"data": 1473.6,
"group": "fitted" 
},
{
 "dates": 1448,
"data": 1475.5,
"group": "fitted" 
},
{
 "dates": 1449,
"data": 1477.5,
"group": "fitted" 
},
{
 "dates": 1450,
"data": 1479.5,
"group": "fitted" 
},
{
 "dates": 1451,
"data": 1481.5,
"group": "fitted" 
},
{
 "dates": 1452,
"data": 1483.5,
"group": "fitted" 
},
{
 "dates": 1453,
"data": 1485.5,
"group": "fitted" 
},
{
 "dates": 1454,
"data": 1487.5,
"group": "fitted" 
},
{
 "dates": 1455,
"data": 1489.5,
"group": "fitted" 
},
{
 "dates": 1456,
"data": 1491.5,
"group": "fitted" 
},
{
 "dates": 1457,
"data": 1493.5,
"group": "fitted" 
},
{
 "dates": 1458,
"data": 1495.5,
"group": "fitted" 
},
{
 "dates": 1459,
"data": 1497.5,
"group": "fitted" 
},
{
 "dates": 1460,
"data": 1499.5,
"group": "fitted" 
},
{
 "dates": 1461,
"data": 1503.3,
"group": "fitted" 
} 
]
  
      var data = d3.nest()
        .key(function(d){
          return opts.group === undefined ? 'main' : d[opts.group]
        })
        .entries(data)
      
      nv.addGraph(function() {
        var chart = nv.models[opts.type]()
          .x(function(d) { return d[opts.x] })
          .y(function(d) { return d[opts.y] })
          .width(opts.width)
          .height(opts.height)
         
        
          
        

        
        
        
      
       d3.select("#" + opts.id)
        .append('svg')
        .datum(data)
        .transition().duration(500)
        .call(chart);

       nv.utils.windowResize(chart.update);
       return chart;
      });
    };
</script>


In fact our model summary results tell us that the fit is quite excellent:


<table class="table table-striped"><thead><tr><th> Stat </th><th> value </th></tr></thead><tr><td> RSquared </td><td> 0.9383 </td></tr><tr><td> pVal </td><td> 0 </td></tr><tr><td> MeanError </td><td> 30.13 </td></tr></table>


With a P-value of 0, and 93% of the variance explained by the model (R Squared), and an average error of less than 1% (30/mean(Revenue)) we can conclude that the fit is pretty darn good.

### Forecasts

Since our model is so good we can forecast a year out of revenue.  Let's look at those forecasts on a daily, monthly and yearly level.



#### Daily Forecasts

The following chart shows the daily average forecast along with a 95% confidence interval (meaning that on a daily basis the true value will be within the lower and upper limits 90% of the time).





<div id='dataModN' class='rChart nvd3'></div>
<script type='text/javascript'>
 $(document).ready(function(){
      drawdataModN()
    });
    function drawdataModN(){  
      var opts = {
 "dom": "dataModN",
"width":    800,
"height":    400,
"x": "dates",
"y": "data",
"group": "group",
"type": "lineWithFocusChart",
"id": "dataModN" 
},
        data = [
 {
 "dates": 1,
"data": 1503.3,
"group": "Mean" 
},
{
 "dates": 2,
"data": 1505.3,
"group": "Mean" 
},
{
 "dates": 3,
"data": 1507.3,
"group": "Mean" 
},
{
 "dates": 4,
"data": 1509.3,
"group": "Mean" 
},
{
 "dates": 5,
"data": 1511.3,
"group": "Mean" 
},
{
 "dates": 6,
"data": 1513.3,
"group": "Mean" 
},
{
 "dates": 7,
"data": 1515.3,
"group": "Mean" 
},
{
 "dates": 8,
"data": 1517.3,
"group": "Mean" 
},
{
 "dates": 9,
"data": 1519.3,
"group": "Mean" 
},
{
 "dates": 10,
"data": 1521.3,
"group": "Mean" 
},
{
 "dates": 11,
"data": 1523.3,
"group": "Mean" 
},
{
 "dates": 12,
"data": 1525.3,
"group": "Mean" 
},
{
 "dates": 13,
"data": 1527.2,
"group": "Mean" 
},
{
 "dates": 14,
"data": 1529.2,
"group": "Mean" 
},
{
 "dates": 15,
"data": 1531.2,
"group": "Mean" 
},
{
 "dates": 16,
"data": 1533.1,
"group": "Mean" 
},
{
 "dates": 17,
"data": 1535.1,
"group": "Mean" 
},
{
 "dates": 18,
"data":   1537,
"group": "Mean" 
},
{
 "dates": 19,
"data":   1539,
"group": "Mean" 
},
{
 "dates": 20,
"data": 1540.9,
"group": "Mean" 
},
{
 "dates": 21,
"data": 1542.8,
"group": "Mean" 
},
{
 "dates": 22,
"data": 1544.7,
"group": "Mean" 
},
{
 "dates": 23,
"data": 1546.6,
"group": "Mean" 
},
{
 "dates": 24,
"data": 1548.5,
"group": "Mean" 
},
{
 "dates": 25,
"data": 1550.3,
"group": "Mean" 
},
{
 "dates": 26,
"data": 1552.2,
"group": "Mean" 
},
{
 "dates": 27,
"data": 1554.1,
"group": "Mean" 
},
{
 "dates": 28,
"data": 1555.9,
"group": "Mean" 
},
{
 "dates": 29,
"data": 1557.7,
"group": "Mean" 
},
{
 "dates": 30,
"data": 1559.5,
"group": "Mean" 
},
{
 "dates": 31,
"data": 1561.3,
"group": "Mean" 
},
{
 "dates": 32,
"data": 1563.1,
"group": "Mean" 
},
{
 "dates": 33,
"data": 1564.9,
"group": "Mean" 
},
{
 "dates": 34,
"data": 1566.6,
"group": "Mean" 
},
{
 "dates": 35,
"data": 1568.4,
"group": "Mean" 
},
{
 "dates": 36,
"data": 1570.1,
"group": "Mean" 
},
{
 "dates": 37,
"data": 1571.8,
"group": "Mean" 
},
{
 "dates": 38,
"data": 1573.5,
"group": "Mean" 
},
{
 "dates": 39,
"data": 1575.1,
"group": "Mean" 
},
{
 "dates": 40,
"data": 1576.8,
"group": "Mean" 
},
{
 "dates": 41,
"data": 1578.4,
"group": "Mean" 
},
{
 "dates": 42,
"data":   1580,
"group": "Mean" 
},
{
 "dates": 43,
"data": 1581.6,
"group": "Mean" 
},
{
 "dates": 44,
"data": 1583.2,
"group": "Mean" 
},
{
 "dates": 45,
"data": 1584.8,
"group": "Mean" 
},
{
 "dates": 46,
"data": 1586.3,
"group": "Mean" 
},
{
 "dates": 47,
"data": 1587.8,
"group": "Mean" 
},
{
 "dates": 48,
"data": 1589.3,
"group": "Mean" 
},
{
 "dates": 49,
"data": 1590.8,
"group": "Mean" 
},
{
 "dates": 50,
"data": 1592.3,
"group": "Mean" 
},
{
 "dates": 51,
"data": 1593.7,
"group": "Mean" 
},
{
 "dates": 52,
"data": 1595.1,
"group": "Mean" 
},
{
 "dates": 53,
"data": 1596.5,
"group": "Mean" 
},
{
 "dates": 54,
"data": 1597.9,
"group": "Mean" 
},
{
 "dates": 55,
"data": 1599.2,
"group": "Mean" 
},
{
 "dates": 56,
"data": 1600.5,
"group": "Mean" 
},
{
 "dates": 57,
"data": 1601.8,
"group": "Mean" 
},
{
 "dates": 58,
"data": 1603.1,
"group": "Mean" 
},
{
 "dates": 59,
"data": 1604.3,
"group": "Mean" 
},
{
 "dates": 60,
"data": 1605.6,
"group": "Mean" 
},
{
 "dates": 61,
"data": 1606.8,
"group": "Mean" 
},
{
 "dates": 62,
"data": 1607.9,
"group": "Mean" 
},
{
 "dates": 63,
"data": 1609.1,
"group": "Mean" 
},
{
 "dates": 64,
"data": 1610.2,
"group": "Mean" 
},
{
 "dates": 65,
"data": 1611.3,
"group": "Mean" 
},
{
 "dates": 66,
"data": 1612.4,
"group": "Mean" 
},
{
 "dates": 67,
"data": 1613.4,
"group": "Mean" 
},
{
 "dates": 68,
"data": 1614.5,
"group": "Mean" 
},
{
 "dates": 69,
"data": 1615.5,
"group": "Mean" 
},
{
 "dates": 70,
"data": 1616.4,
"group": "Mean" 
},
{
 "dates": 71,
"data": 1617.4,
"group": "Mean" 
},
{
 "dates": 72,
"data": 1618.3,
"group": "Mean" 
},
{
 "dates": 73,
"data": 1619.2,
"group": "Mean" 
},
{
 "dates": 74,
"data":   1620,
"group": "Mean" 
},
{
 "dates": 75,
"data": 1620.9,
"group": "Mean" 
},
{
 "dates": 76,
"data": 1621.7,
"group": "Mean" 
},
{
 "dates": 77,
"data": 1622.4,
"group": "Mean" 
},
{
 "dates": 78,
"data": 1623.2,
"group": "Mean" 
},
{
 "dates": 79,
"data": 1623.9,
"group": "Mean" 
},
{
 "dates": 80,
"data": 1624.6,
"group": "Mean" 
},
{
 "dates": 81,
"data": 1625.3,
"group": "Mean" 
},
{
 "dates": 82,
"data": 1625.9,
"group": "Mean" 
},
{
 "dates": 83,
"data": 1626.5,
"group": "Mean" 
},
{
 "dates": 84,
"data": 1627.1,
"group": "Mean" 
},
{
 "dates": 85,
"data": 1627.6,
"group": "Mean" 
},
{
 "dates": 86,
"data": 1628.2,
"group": "Mean" 
},
{
 "dates": 87,
"data": 1628.6,
"group": "Mean" 
},
{
 "dates": 88,
"data": 1629.1,
"group": "Mean" 
},
{
 "dates": 89,
"data": 1629.5,
"group": "Mean" 
},
{
 "dates": 90,
"data": 1629.9,
"group": "Mean" 
},
{
 "dates": 91,
"data": 1630.3,
"group": "Mean" 
},
{
 "dates": 92,
"data": 1630.7,
"group": "Mean" 
},
{
 "dates": 93,
"data":   1631,
"group": "Mean" 
},
{
 "dates": 94,
"data": 1631.3,
"group": "Mean" 
},
{
 "dates": 95,
"data": 1631.5,
"group": "Mean" 
},
{
 "dates": 96,
"data": 1631.8,
"group": "Mean" 
},
{
 "dates": 97,
"data":   1632,
"group": "Mean" 
},
{
 "dates": 98,
"data": 1632.2,
"group": "Mean" 
},
{
 "dates": 99,
"data": 1632.3,
"group": "Mean" 
},
{
 "dates": 100,
"data": 1632.4,
"group": "Mean" 
},
{
 "dates": 101,
"data": 1632.5,
"group": "Mean" 
},
{
 "dates": 102,
"data": 1632.6,
"group": "Mean" 
},
{
 "dates": 103,
"data": 1632.6,
"group": "Mean" 
},
{
 "dates": 104,
"data": 1632.6,
"group": "Mean" 
},
{
 "dates": 105,
"data": 1632.6,
"group": "Mean" 
},
{
 "dates": 106,
"data": 1632.5,
"group": "Mean" 
},
{
 "dates": 107,
"data": 1632.4,
"group": "Mean" 
},
{
 "dates": 108,
"data": 1632.3,
"group": "Mean" 
},
{
 "dates": 109,
"data": 1632.2,
"group": "Mean" 
},
{
 "dates": 110,
"data":   1632,
"group": "Mean" 
},
{
 "dates": 111,
"data": 1631.8,
"group": "Mean" 
},
{
 "dates": 112,
"data": 1631.6,
"group": "Mean" 
},
{
 "dates": 113,
"data": 1631.4,
"group": "Mean" 
},
{
 "dates": 114,
"data": 1631.1,
"group": "Mean" 
},
{
 "dates": 115,
"data": 1630.8,
"group": "Mean" 
},
{
 "dates": 116,
"data": 1630.5,
"group": "Mean" 
},
{
 "dates": 117,
"data": 1630.1,
"group": "Mean" 
},
{
 "dates": 118,
"data": 1629.7,
"group": "Mean" 
},
{
 "dates": 119,
"data": 1629.3,
"group": "Mean" 
},
{
 "dates": 120,
"data": 1628.9,
"group": "Mean" 
},
{
 "dates": 121,
"data": 1628.4,
"group": "Mean" 
},
{
 "dates": 122,
"data": 1627.9,
"group": "Mean" 
},
{
 "dates": 123,
"data": 1627.4,
"group": "Mean" 
},
{
 "dates": 124,
"data": 1626.9,
"group": "Mean" 
},
{
 "dates": 125,
"data": 1626.3,
"group": "Mean" 
},
{
 "dates": 126,
"data": 1625.8,
"group": "Mean" 
},
{
 "dates": 127,
"data": 1625.2,
"group": "Mean" 
},
{
 "dates": 128,
"data": 1624.5,
"group": "Mean" 
},
{
 "dates": 129,
"data": 1623.9,
"group": "Mean" 
},
{
 "dates": 130,
"data": 1623.2,
"group": "Mean" 
},
{
 "dates": 131,
"data": 1622.5,
"group": "Mean" 
},
{
 "dates": 132,
"data": 1621.8,
"group": "Mean" 
},
{
 "dates": 133,
"data":   1621,
"group": "Mean" 
},
{
 "dates": 134,
"data": 1620.3,
"group": "Mean" 
},
{
 "dates": 135,
"data": 1619.5,
"group": "Mean" 
},
{
 "dates": 136,
"data": 1618.7,
"group": "Mean" 
},
{
 "dates": 137,
"data": 1617.8,
"group": "Mean" 
},
{
 "dates": 138,
"data":   1617,
"group": "Mean" 
},
{
 "dates": 139,
"data": 1616.1,
"group": "Mean" 
},
{
 "dates": 140,
"data": 1615.2,
"group": "Mean" 
},
{
 "dates": 141,
"data": 1614.3,
"group": "Mean" 
},
{
 "dates": 142,
"data": 1613.4,
"group": "Mean" 
},
{
 "dates": 143,
"data": 1612.4,
"group": "Mean" 
},
{
 "dates": 144,
"data": 1611.5,
"group": "Mean" 
},
{
 "dates": 145,
"data": 1610.5,
"group": "Mean" 
},
{
 "dates": 146,
"data": 1609.5,
"group": "Mean" 
},
{
 "dates": 147,
"data": 1608.5,
"group": "Mean" 
},
{
 "dates": 148,
"data": 1607.4,
"group": "Mean" 
},
{
 "dates": 149,
"data": 1606.4,
"group": "Mean" 
},
{
 "dates": 150,
"data": 1605.3,
"group": "Mean" 
},
{
 "dates": 151,
"data": 1604.2,
"group": "Mean" 
},
{
 "dates": 152,
"data": 1603.1,
"group": "Mean" 
},
{
 "dates": 153,
"data":   1602,
"group": "Mean" 
},
{
 "dates": 154,
"data": 1600.9,
"group": "Mean" 
},
{
 "dates": 155,
"data": 1599.7,
"group": "Mean" 
},
{
 "dates": 156,
"data": 1598.6,
"group": "Mean" 
},
{
 "dates": 157,
"data": 1597.4,
"group": "Mean" 
},
{
 "dates": 158,
"data": 1596.2,
"group": "Mean" 
},
{
 "dates": 159,
"data":   1595,
"group": "Mean" 
},
{
 "dates": 160,
"data": 1593.8,
"group": "Mean" 
},
{
 "dates": 161,
"data": 1592.6,
"group": "Mean" 
},
{
 "dates": 162,
"data": 1591.4,
"group": "Mean" 
},
{
 "dates": 163,
"data": 1590.1,
"group": "Mean" 
},
{
 "dates": 164,
"data": 1588.9,
"group": "Mean" 
},
{
 "dates": 165,
"data": 1587.6,
"group": "Mean" 
},
{
 "dates": 166,
"data": 1586.4,
"group": "Mean" 
},
{
 "dates": 167,
"data": 1585.1,
"group": "Mean" 
},
{
 "dates": 168,
"data": 1583.8,
"group": "Mean" 
},
{
 "dates": 169,
"data": 1582.5,
"group": "Mean" 
},
{
 "dates": 170,
"data": 1581.2,
"group": "Mean" 
},
{
 "dates": 171,
"data": 1579.9,
"group": "Mean" 
},
{
 "dates": 172,
"data": 1578.6,
"group": "Mean" 
},
{
 "dates": 173,
"data": 1577.3,
"group": "Mean" 
},
{
 "dates": 174,
"data":   1576,
"group": "Mean" 
},
{
 "dates": 175,
"data": 1574.6,
"group": "Mean" 
},
{
 "dates": 176,
"data": 1573.3,
"group": "Mean" 
},
{
 "dates": 177,
"data":   1572,
"group": "Mean" 
},
{
 "dates": 178,
"data": 1570.7,
"group": "Mean" 
},
{
 "dates": 179,
"data": 1569.3,
"group": "Mean" 
},
{
 "dates": 180,
"data":   1568,
"group": "Mean" 
},
{
 "dates": 181,
"data": 1566.6,
"group": "Mean" 
},
{
 "dates": 182,
"data": 1565.3,
"group": "Mean" 
},
{
 "dates": 183,
"data":   1564,
"group": "Mean" 
},
{
 "dates": 184,
"data": 1562.6,
"group": "Mean" 
},
{
 "dates": 185,
"data": 1561.3,
"group": "Mean" 
},
{
 "dates": 186,
"data": 1559.9,
"group": "Mean" 
},
{
 "dates": 187,
"data": 1558.6,
"group": "Mean" 
},
{
 "dates": 188,
"data": 1557.3,
"group": "Mean" 
},
{
 "dates": 189,
"data": 1555.9,
"group": "Mean" 
},
{
 "dates": 190,
"data": 1554.6,
"group": "Mean" 
},
{
 "dates": 191,
"data": 1553.3,
"group": "Mean" 
},
{
 "dates": 192,
"data": 1551.9,
"group": "Mean" 
},
{
 "dates": 193,
"data": 1550.6,
"group": "Mean" 
},
{
 "dates": 194,
"data": 1549.3,
"group": "Mean" 
},
{
 "dates": 195,
"data":   1548,
"group": "Mean" 
},
{
 "dates": 196,
"data": 1546.7,
"group": "Mean" 
},
{
 "dates": 197,
"data": 1545.4,
"group": "Mean" 
},
{
 "dates": 198,
"data": 1544.1,
"group": "Mean" 
},
{
 "dates": 199,
"data": 1542.8,
"group": "Mean" 
},
{
 "dates": 200,
"data": 1541.5,
"group": "Mean" 
},
{
 "dates": 201,
"data": 1540.3,
"group": "Mean" 
},
{
 "dates": 202,
"data":   1539,
"group": "Mean" 
},
{
 "dates": 203,
"data": 1537.8,
"group": "Mean" 
},
{
 "dates": 204,
"data": 1536.5,
"group": "Mean" 
},
{
 "dates": 205,
"data": 1535.3,
"group": "Mean" 
},
{
 "dates": 206,
"data": 1534.1,
"group": "Mean" 
},
{
 "dates": 207,
"data": 1532.9,
"group": "Mean" 
},
{
 "dates": 208,
"data": 1531.7,
"group": "Mean" 
},
{
 "dates": 209,
"data": 1530.5,
"group": "Mean" 
},
{
 "dates": 210,
"data": 1529.3,
"group": "Mean" 
},
{
 "dates": 211,
"data": 1528.2,
"group": "Mean" 
},
{
 "dates": 212,
"data":   1527,
"group": "Mean" 
},
{
 "dates": 213,
"data": 1525.9,
"group": "Mean" 
},
{
 "dates": 214,
"data": 1524.8,
"group": "Mean" 
},
{
 "dates": 215,
"data": 1523.7,
"group": "Mean" 
},
{
 "dates": 216,
"data": 1522.6,
"group": "Mean" 
},
{
 "dates": 217,
"data": 1521.5,
"group": "Mean" 
},
{
 "dates": 218,
"data": 1520.5,
"group": "Mean" 
},
{
 "dates": 219,
"data": 1519.5,
"group": "Mean" 
},
{
 "dates": 220,
"data": 1518.4,
"group": "Mean" 
},
{
 "dates": 221,
"data": 1517.4,
"group": "Mean" 
},
{
 "dates": 222,
"data": 1516.4,
"group": "Mean" 
},
{
 "dates": 223,
"data": 1515.5,
"group": "Mean" 
},
{
 "dates": 224,
"data": 1514.5,
"group": "Mean" 
},
{
 "dates": 225,
"data": 1513.6,
"group": "Mean" 
},
{
 "dates": 226,
"data": 1512.7,
"group": "Mean" 
},
{
 "dates": 227,
"data": 1511.8,
"group": "Mean" 
},
{
 "dates": 228,
"data": 1510.9,
"group": "Mean" 
},
{
 "dates": 229,
"data": 1510.1,
"group": "Mean" 
},
{
 "dates": 230,
"data": 1509.2,
"group": "Mean" 
},
{
 "dates": 231,
"data": 1508.4,
"group": "Mean" 
},
{
 "dates": 232,
"data": 1507.6,
"group": "Mean" 
},
{
 "dates": 233,
"data": 1506.9,
"group": "Mean" 
},
{
 "dates": 234,
"data": 1506.1,
"group": "Mean" 
},
{
 "dates": 235,
"data": 1505.4,
"group": "Mean" 
},
{
 "dates": 236,
"data": 1504.7,
"group": "Mean" 
},
{
 "dates": 237,
"data":   1504,
"group": "Mean" 
},
{
 "dates": 238,
"data": 1503.4,
"group": "Mean" 
},
{
 "dates": 239,
"data": 1502.7,
"group": "Mean" 
},
{
 "dates": 240,
"data": 1502.1,
"group": "Mean" 
},
{
 "dates": 241,
"data": 1501.6,
"group": "Mean" 
},
{
 "dates": 242,
"data":   1501,
"group": "Mean" 
},
{
 "dates": 243,
"data": 1500.5,
"group": "Mean" 
},
{
 "dates": 244,
"data":   1500,
"group": "Mean" 
},
{
 "dates": 245,
"data": 1499.5,
"group": "Mean" 
},
{
 "dates": 246,
"data":   1499,
"group": "Mean" 
},
{
 "dates": 247,
"data": 1498.6,
"group": "Mean" 
},
{
 "dates": 248,
"data": 1498.2,
"group": "Mean" 
},
{
 "dates": 249,
"data": 1497.8,
"group": "Mean" 
},
{
 "dates": 250,
"data": 1497.4,
"group": "Mean" 
},
{
 "dates": 251,
"data": 1497.1,
"group": "Mean" 
},
{
 "dates": 252,
"data": 1496.8,
"group": "Mean" 
},
{
 "dates": 253,
"data": 1496.5,
"group": "Mean" 
},
{
 "dates": 254,
"data": 1496.3,
"group": "Mean" 
},
{
 "dates": 255,
"data": 1496.1,
"group": "Mean" 
},
{
 "dates": 256,
"data": 1495.9,
"group": "Mean" 
},
{
 "dates": 257,
"data": 1495.7,
"group": "Mean" 
},
{
 "dates": 258,
"data": 1495.6,
"group": "Mean" 
},
{
 "dates": 259,
"data": 1495.5,
"group": "Mean" 
},
{
 "dates": 260,
"data": 1495.4,
"group": "Mean" 
},
{
 "dates": 261,
"data": 1495.3,
"group": "Mean" 
},
{
 "dates": 262,
"data": 1495.3,
"group": "Mean" 
},
{
 "dates": 263,
"data": 1495.3,
"group": "Mean" 
},
{
 "dates": 264,
"data": 1495.3,
"group": "Mean" 
},
{
 "dates": 265,
"data": 1495.4,
"group": "Mean" 
},
{
 "dates": 266,
"data": 1495.5,
"group": "Mean" 
},
{
 "dates": 267,
"data": 1495.6,
"group": "Mean" 
},
{
 "dates": 268,
"data": 1495.8,
"group": "Mean" 
},
{
 "dates": 269,
"data": 1495.9,
"group": "Mean" 
},
{
 "dates": 270,
"data": 1496.1,
"group": "Mean" 
},
{
 "dates": 271,
"data": 1496.4,
"group": "Mean" 
},
{
 "dates": 272,
"data": 1496.6,
"group": "Mean" 
},
{
 "dates": 273,
"data": 1496.9,
"group": "Mean" 
},
{
 "dates": 274,
"data": 1497.2,
"group": "Mean" 
},
{
 "dates": 275,
"data": 1497.6,
"group": "Mean" 
},
{
 "dates": 276,
"data":   1498,
"group": "Mean" 
},
{
 "dates": 277,
"data": 1498.4,
"group": "Mean" 
},
{
 "dates": 278,
"data": 1498.8,
"group": "Mean" 
},
{
 "dates": 279,
"data": 1499.3,
"group": "Mean" 
},
{
 "dates": 280,
"data": 1499.8,
"group": "Mean" 
},
{
 "dates": 281,
"data": 1500.3,
"group": "Mean" 
},
{
 "dates": 282,
"data": 1500.8,
"group": "Mean" 
},
{
 "dates": 283,
"data": 1501.4,
"group": "Mean" 
},
{
 "dates": 284,
"data":   1502,
"group": "Mean" 
},
{
 "dates": 285,
"data": 1502.6,
"group": "Mean" 
},
{
 "dates": 286,
"data": 1503.3,
"group": "Mean" 
},
{
 "dates": 287,
"data":   1504,
"group": "Mean" 
},
{
 "dates": 288,
"data": 1504.7,
"group": "Mean" 
},
{
 "dates": 289,
"data": 1505.5,
"group": "Mean" 
},
{
 "dates": 290,
"data": 1506.2,
"group": "Mean" 
},
{
 "dates": 291,
"data": 1507.1,
"group": "Mean" 
},
{
 "dates": 292,
"data": 1507.9,
"group": "Mean" 
},
{
 "dates": 293,
"data": 1508.7,
"group": "Mean" 
},
{
 "dates": 294,
"data": 1509.6,
"group": "Mean" 
},
{
 "dates": 295,
"data": 1510.5,
"group": "Mean" 
},
{
 "dates": 296,
"data": 1511.5,
"group": "Mean" 
},
{
 "dates": 297,
"data": 1512.5,
"group": "Mean" 
},
{
 "dates": 298,
"data": 1513.4,
"group": "Mean" 
},
{
 "dates": 299,
"data": 1514.5,
"group": "Mean" 
},
{
 "dates": 300,
"data": 1515.5,
"group": "Mean" 
},
{
 "dates": 301,
"data": 1516.6,
"group": "Mean" 
},
{
 "dates": 302,
"data": 1517.7,
"group": "Mean" 
},
{
 "dates": 303,
"data": 1518.8,
"group": "Mean" 
},
{
 "dates": 304,
"data":   1520,
"group": "Mean" 
},
{
 "dates": 305,
"data": 1521.1,
"group": "Mean" 
},
{
 "dates": 306,
"data": 1522.3,
"group": "Mean" 
},
{
 "dates": 307,
"data": 1523.6,
"group": "Mean" 
},
{
 "dates": 308,
"data": 1524.8,
"group": "Mean" 
},
{
 "dates": 309,
"data": 1526.1,
"group": "Mean" 
},
{
 "dates": 310,
"data": 1527.4,
"group": "Mean" 
},
{
 "dates": 311,
"data": 1528.7,
"group": "Mean" 
},
{
 "dates": 312,
"data":   1530,
"group": "Mean" 
},
{
 "dates": 313,
"data": 1531.4,
"group": "Mean" 
},
{
 "dates": 314,
"data": 1532.8,
"group": "Mean" 
},
{
 "dates": 315,
"data": 1534.2,
"group": "Mean" 
},
{
 "dates": 316,
"data": 1535.6,
"group": "Mean" 
},
{
 "dates": 317,
"data": 1537.1,
"group": "Mean" 
},
{
 "dates": 318,
"data": 1538.6,
"group": "Mean" 
},
{
 "dates": 319,
"data": 1540.1,
"group": "Mean" 
},
{
 "dates": 320,
"data": 1541.6,
"group": "Mean" 
},
{
 "dates": 321,
"data": 1543.1,
"group": "Mean" 
},
{
 "dates": 322,
"data": 1544.7,
"group": "Mean" 
},
{
 "dates": 323,
"data": 1546.3,
"group": "Mean" 
},
{
 "dates": 324,
"data": 1547.9,
"group": "Mean" 
},
{
 "dates": 325,
"data": 1549.5,
"group": "Mean" 
},
{
 "dates": 326,
"data": 1551.1,
"group": "Mean" 
},
{
 "dates": 327,
"data": 1552.8,
"group": "Mean" 
},
{
 "dates": 328,
"data": 1554.4,
"group": "Mean" 
},
{
 "dates": 329,
"data": 1556.1,
"group": "Mean" 
},
{
 "dates": 330,
"data": 1557.8,
"group": "Mean" 
},
{
 "dates": 331,
"data": 1559.5,
"group": "Mean" 
},
{
 "dates": 332,
"data": 1561.3,
"group": "Mean" 
},
{
 "dates": 333,
"data":   1563,
"group": "Mean" 
},
{
 "dates": 334,
"data": 1564.8,
"group": "Mean" 
},
{
 "dates": 335,
"data": 1566.6,
"group": "Mean" 
},
{
 "dates": 336,
"data": 1568.4,
"group": "Mean" 
},
{
 "dates": 337,
"data": 1570.2,
"group": "Mean" 
},
{
 "dates": 338,
"data":   1572,
"group": "Mean" 
},
{
 "dates": 339,
"data": 1573.8,
"group": "Mean" 
},
{
 "dates": 340,
"data": 1575.7,
"group": "Mean" 
},
{
 "dates": 341,
"data": 1577.6,
"group": "Mean" 
},
{
 "dates": 342,
"data": 1579.4,
"group": "Mean" 
},
{
 "dates": 343,
"data": 1581.3,
"group": "Mean" 
},
{
 "dates": 344,
"data": 1583.2,
"group": "Mean" 
},
{
 "dates": 345,
"data": 1585.1,
"group": "Mean" 
},
{
 "dates": 346,
"data":   1587,
"group": "Mean" 
},
{
 "dates": 347,
"data":   1589,
"group": "Mean" 
},
{
 "dates": 348,
"data": 1590.9,
"group": "Mean" 
},
{
 "dates": 349,
"data": 1592.8,
"group": "Mean" 
},
{
 "dates": 350,
"data": 1594.8,
"group": "Mean" 
},
{
 "dates": 351,
"data": 1596.7,
"group": "Mean" 
},
{
 "dates": 352,
"data": 1598.7,
"group": "Mean" 
},
{
 "dates": 353,
"data": 1600.7,
"group": "Mean" 
},
{
 "dates": 354,
"data": 1602.6,
"group": "Mean" 
},
{
 "dates": 355,
"data": 1604.6,
"group": "Mean" 
},
{
 "dates": 356,
"data": 1606.6,
"group": "Mean" 
},
{
 "dates": 357,
"data": 1608.6,
"group": "Mean" 
},
{
 "dates": 358,
"data": 1610.6,
"group": "Mean" 
},
{
 "dates": 359,
"data": 1612.6,
"group": "Mean" 
},
{
 "dates": 360,
"data": 1614.6,
"group": "Mean" 
},
{
 "dates": 361,
"data": 1616.6,
"group": "Mean" 
},
{
 "dates": 362,
"data": 1618.6,
"group": "Mean" 
},
{
 "dates": 363,
"data": 1620.6,
"group": "Mean" 
},
{
 "dates": 364,
"data": 1622.6,
"group": "Mean" 
},
{
 "dates": 365,
"data": 1624.6,
"group": "Mean" 
},
{
 "dates": 1,
"data":   1441,
"group": "Worst Case" 
},
{
 "dates": 2,
"data":   1443,
"group": "Worst Case" 
},
{
 "dates": 3,
"data":   1445,
"group": "Worst Case" 
},
{
 "dates": 4,
"data":   1447,
"group": "Worst Case" 
},
{
 "dates": 5,
"data":   1449,
"group": "Worst Case" 
},
{
 "dates": 6,
"data":   1451,
"group": "Worst Case" 
},
{
 "dates": 7,
"data":   1453,
"group": "Worst Case" 
},
{
 "dates": 8,
"data":   1455,
"group": "Worst Case" 
},
{
 "dates": 9,
"data":   1457,
"group": "Worst Case" 
},
{
 "dates": 10,
"data":   1459,
"group": "Worst Case" 
},
{
 "dates": 11,
"data":   1461,
"group": "Worst Case" 
},
{
 "dates": 12,
"data":   1463,
"group": "Worst Case" 
},
{
 "dates": 13,
"data": 1464.9,
"group": "Worst Case" 
},
{
 "dates": 14,
"data": 1466.9,
"group": "Worst Case" 
},
{
 "dates": 15,
"data": 1468.9,
"group": "Worst Case" 
},
{
 "dates": 16,
"data": 1470.8,
"group": "Worst Case" 
},
{
 "dates": 17,
"data": 1472.8,
"group": "Worst Case" 
},
{
 "dates": 18,
"data": 1474.7,
"group": "Worst Case" 
},
{
 "dates": 19,
"data": 1476.7,
"group": "Worst Case" 
},
{
 "dates": 20,
"data": 1478.6,
"group": "Worst Case" 
},
{
 "dates": 21,
"data": 1480.5,
"group": "Worst Case" 
},
{
 "dates": 22,
"data": 1482.4,
"group": "Worst Case" 
},
{
 "dates": 23,
"data": 1484.3,
"group": "Worst Case" 
},
{
 "dates": 24,
"data": 1486.2,
"group": "Worst Case" 
},
{
 "dates": 25,
"data":   1488,
"group": "Worst Case" 
},
{
 "dates": 26,
"data": 1489.9,
"group": "Worst Case" 
},
{
 "dates": 27,
"data": 1491.8,
"group": "Worst Case" 
},
{
 "dates": 28,
"data": 1493.6,
"group": "Worst Case" 
},
{
 "dates": 29,
"data": 1495.4,
"group": "Worst Case" 
},
{
 "dates": 30,
"data": 1497.2,
"group": "Worst Case" 
},
{
 "dates": 31,
"data":   1499,
"group": "Worst Case" 
},
{
 "dates": 32,
"data": 1500.8,
"group": "Worst Case" 
},
{
 "dates": 33,
"data": 1502.6,
"group": "Worst Case" 
},
{
 "dates": 34,
"data": 1504.3,
"group": "Worst Case" 
},
{
 "dates": 35,
"data": 1506.1,
"group": "Worst Case" 
},
{
 "dates": 36,
"data": 1507.8,
"group": "Worst Case" 
},
{
 "dates": 37,
"data": 1509.5,
"group": "Worst Case" 
},
{
 "dates": 38,
"data": 1511.2,
"group": "Worst Case" 
},
{
 "dates": 39,
"data": 1512.8,
"group": "Worst Case" 
},
{
 "dates": 40,
"data": 1514.5,
"group": "Worst Case" 
},
{
 "dates": 41,
"data": 1516.1,
"group": "Worst Case" 
},
{
 "dates": 42,
"data": 1517.7,
"group": "Worst Case" 
},
{
 "dates": 43,
"data": 1519.3,
"group": "Worst Case" 
},
{
 "dates": 44,
"data": 1520.9,
"group": "Worst Case" 
},
{
 "dates": 45,
"data": 1522.5,
"group": "Worst Case" 
},
{
 "dates": 46,
"data":   1524,
"group": "Worst Case" 
},
{
 "dates": 47,
"data": 1525.5,
"group": "Worst Case" 
},
{
 "dates": 48,
"data":   1527,
"group": "Worst Case" 
},
{
 "dates": 49,
"data": 1528.5,
"group": "Worst Case" 
},
{
 "dates": 50,
"data":   1530,
"group": "Worst Case" 
},
{
 "dates": 51,
"data": 1531.4,
"group": "Worst Case" 
},
{
 "dates": 52,
"data": 1532.8,
"group": "Worst Case" 
},
{
 "dates": 53,
"data": 1534.2,
"group": "Worst Case" 
},
{
 "dates": 54,
"data": 1535.6,
"group": "Worst Case" 
},
{
 "dates": 55,
"data": 1536.9,
"group": "Worst Case" 
},
{
 "dates": 56,
"data": 1538.2,
"group": "Worst Case" 
},
{
 "dates": 57,
"data": 1539.5,
"group": "Worst Case" 
},
{
 "dates": 58,
"data": 1540.8,
"group": "Worst Case" 
},
{
 "dates": 59,
"data":   1542,
"group": "Worst Case" 
},
{
 "dates": 60,
"data": 1543.3,
"group": "Worst Case" 
},
{
 "dates": 61,
"data": 1544.5,
"group": "Worst Case" 
},
{
 "dates": 62,
"data": 1545.6,
"group": "Worst Case" 
},
{
 "dates": 63,
"data": 1546.8,
"group": "Worst Case" 
},
{
 "dates": 64,
"data": 1547.9,
"group": "Worst Case" 
},
{
 "dates": 65,
"data":   1549,
"group": "Worst Case" 
},
{
 "dates": 66,
"data": 1550.1,
"group": "Worst Case" 
},
{
 "dates": 67,
"data": 1551.1,
"group": "Worst Case" 
},
{
 "dates": 68,
"data": 1552.2,
"group": "Worst Case" 
},
{
 "dates": 69,
"data": 1553.2,
"group": "Worst Case" 
},
{
 "dates": 70,
"data": 1554.1,
"group": "Worst Case" 
},
{
 "dates": 71,
"data": 1555.1,
"group": "Worst Case" 
},
{
 "dates": 72,
"data":   1556,
"group": "Worst Case" 
},
{
 "dates": 73,
"data": 1556.9,
"group": "Worst Case" 
},
{
 "dates": 74,
"data": 1557.7,
"group": "Worst Case" 
},
{
 "dates": 75,
"data": 1558.6,
"group": "Worst Case" 
},
{
 "dates": 76,
"data": 1559.4,
"group": "Worst Case" 
},
{
 "dates": 77,
"data": 1560.1,
"group": "Worst Case" 
},
{
 "dates": 78,
"data": 1560.9,
"group": "Worst Case" 
},
{
 "dates": 79,
"data": 1561.6,
"group": "Worst Case" 
},
{
 "dates": 80,
"data": 1562.3,
"group": "Worst Case" 
},
{
 "dates": 81,
"data":   1563,
"group": "Worst Case" 
},
{
 "dates": 82,
"data": 1563.6,
"group": "Worst Case" 
},
{
 "dates": 83,
"data": 1564.2,
"group": "Worst Case" 
},
{
 "dates": 84,
"data": 1564.8,
"group": "Worst Case" 
},
{
 "dates": 85,
"data": 1565.3,
"group": "Worst Case" 
},
{
 "dates": 86,
"data": 1565.9,
"group": "Worst Case" 
},
{
 "dates": 87,
"data": 1566.3,
"group": "Worst Case" 
},
{
 "dates": 88,
"data": 1566.8,
"group": "Worst Case" 
},
{
 "dates": 89,
"data": 1567.2,
"group": "Worst Case" 
},
{
 "dates": 90,
"data": 1567.6,
"group": "Worst Case" 
},
{
 "dates": 91,
"data":   1568,
"group": "Worst Case" 
},
{
 "dates": 92,
"data": 1568.4,
"group": "Worst Case" 
},
{
 "dates": 93,
"data": 1568.7,
"group": "Worst Case" 
},
{
 "dates": 94,
"data":   1569,
"group": "Worst Case" 
},
{
 "dates": 95,
"data": 1569.2,
"group": "Worst Case" 
},
{
 "dates": 96,
"data": 1569.5,
"group": "Worst Case" 
},
{
 "dates": 97,
"data": 1569.7,
"group": "Worst Case" 
},
{
 "dates": 98,
"data": 1569.9,
"group": "Worst Case" 
},
{
 "dates": 99,
"data":   1570,
"group": "Worst Case" 
},
{
 "dates": 100,
"data": 1570.1,
"group": "Worst Case" 
},
{
 "dates": 101,
"data": 1570.2,
"group": "Worst Case" 
},
{
 "dates": 102,
"data": 1570.3,
"group": "Worst Case" 
},
{
 "dates": 103,
"data": 1570.3,
"group": "Worst Case" 
},
{
 "dates": 104,
"data": 1570.3,
"group": "Worst Case" 
},
{
 "dates": 105,
"data": 1570.3,
"group": "Worst Case" 
},
{
 "dates": 106,
"data": 1570.2,
"group": "Worst Case" 
},
{
 "dates": 107,
"data": 1570.1,
"group": "Worst Case" 
},
{
 "dates": 108,
"data":   1570,
"group": "Worst Case" 
},
{
 "dates": 109,
"data": 1569.9,
"group": "Worst Case" 
},
{
 "dates": 110,
"data": 1569.7,
"group": "Worst Case" 
},
{
 "dates": 111,
"data": 1569.5,
"group": "Worst Case" 
},
{
 "dates": 112,
"data": 1569.3,
"group": "Worst Case" 
},
{
 "dates": 113,
"data": 1569.1,
"group": "Worst Case" 
},
{
 "dates": 114,
"data": 1568.8,
"group": "Worst Case" 
},
{
 "dates": 115,
"data": 1568.5,
"group": "Worst Case" 
},
{
 "dates": 116,
"data": 1568.2,
"group": "Worst Case" 
},
{
 "dates": 117,
"data": 1567.8,
"group": "Worst Case" 
},
{
 "dates": 118,
"data": 1567.4,
"group": "Worst Case" 
},
{
 "dates": 119,
"data":   1567,
"group": "Worst Case" 
},
{
 "dates": 120,
"data": 1566.6,
"group": "Worst Case" 
},
{
 "dates": 121,
"data": 1566.1,
"group": "Worst Case" 
},
{
 "dates": 122,
"data": 1565.6,
"group": "Worst Case" 
},
{
 "dates": 123,
"data": 1565.1,
"group": "Worst Case" 
},
{
 "dates": 124,
"data": 1564.6,
"group": "Worst Case" 
},
{
 "dates": 125,
"data":   1564,
"group": "Worst Case" 
},
{
 "dates": 126,
"data": 1563.5,
"group": "Worst Case" 
},
{
 "dates": 127,
"data": 1562.9,
"group": "Worst Case" 
},
{
 "dates": 128,
"data": 1562.2,
"group": "Worst Case" 
},
{
 "dates": 129,
"data": 1561.6,
"group": "Worst Case" 
},
{
 "dates": 130,
"data": 1560.9,
"group": "Worst Case" 
},
{
 "dates": 131,
"data": 1560.2,
"group": "Worst Case" 
},
{
 "dates": 132,
"data": 1559.5,
"group": "Worst Case" 
},
{
 "dates": 133,
"data": 1558.7,
"group": "Worst Case" 
},
{
 "dates": 134,
"data":   1558,
"group": "Worst Case" 
},
{
 "dates": 135,
"data": 1557.2,
"group": "Worst Case" 
},
{
 "dates": 136,
"data": 1556.4,
"group": "Worst Case" 
},
{
 "dates": 137,
"data": 1555.5,
"group": "Worst Case" 
},
{
 "dates": 138,
"data": 1554.7,
"group": "Worst Case" 
},
{
 "dates": 139,
"data": 1553.8,
"group": "Worst Case" 
},
{
 "dates": 140,
"data": 1552.9,
"group": "Worst Case" 
},
{
 "dates": 141,
"data":   1552,
"group": "Worst Case" 
},
{
 "dates": 142,
"data": 1551.1,
"group": "Worst Case" 
},
{
 "dates": 143,
"data": 1550.1,
"group": "Worst Case" 
},
{
 "dates": 144,
"data": 1549.2,
"group": "Worst Case" 
},
{
 "dates": 145,
"data": 1548.2,
"group": "Worst Case" 
},
{
 "dates": 146,
"data": 1547.2,
"group": "Worst Case" 
},
{
 "dates": 147,
"data": 1546.2,
"group": "Worst Case" 
},
{
 "dates": 148,
"data": 1545.1,
"group": "Worst Case" 
},
{
 "dates": 149,
"data": 1544.1,
"group": "Worst Case" 
},
{
 "dates": 150,
"data":   1543,
"group": "Worst Case" 
},
{
 "dates": 151,
"data": 1541.9,
"group": "Worst Case" 
},
{
 "dates": 152,
"data": 1540.8,
"group": "Worst Case" 
},
{
 "dates": 153,
"data": 1539.7,
"group": "Worst Case" 
},
{
 "dates": 154,
"data": 1538.6,
"group": "Worst Case" 
},
{
 "dates": 155,
"data": 1537.4,
"group": "Worst Case" 
},
{
 "dates": 156,
"data": 1536.3,
"group": "Worst Case" 
},
{
 "dates": 157,
"data": 1535.1,
"group": "Worst Case" 
},
{
 "dates": 158,
"data": 1533.9,
"group": "Worst Case" 
},
{
 "dates": 159,
"data": 1532.7,
"group": "Worst Case" 
},
{
 "dates": 160,
"data": 1531.5,
"group": "Worst Case" 
},
{
 "dates": 161,
"data": 1530.3,
"group": "Worst Case" 
},
{
 "dates": 162,
"data": 1529.1,
"group": "Worst Case" 
},
{
 "dates": 163,
"data": 1527.8,
"group": "Worst Case" 
},
{
 "dates": 164,
"data": 1526.6,
"group": "Worst Case" 
},
{
 "dates": 165,
"data": 1525.3,
"group": "Worst Case" 
},
{
 "dates": 166,
"data": 1524.1,
"group": "Worst Case" 
},
{
 "dates": 167,
"data": 1522.8,
"group": "Worst Case" 
},
{
 "dates": 168,
"data": 1521.5,
"group": "Worst Case" 
},
{
 "dates": 169,
"data": 1520.2,
"group": "Worst Case" 
},
{
 "dates": 170,
"data": 1518.9,
"group": "Worst Case" 
},
{
 "dates": 171,
"data": 1517.6,
"group": "Worst Case" 
},
{
 "dates": 172,
"data": 1516.3,
"group": "Worst Case" 
},
{
 "dates": 173,
"data":   1515,
"group": "Worst Case" 
},
{
 "dates": 174,
"data": 1513.7,
"group": "Worst Case" 
},
{
 "dates": 175,
"data": 1512.3,
"group": "Worst Case" 
},
{
 "dates": 176,
"data":   1511,
"group": "Worst Case" 
},
{
 "dates": 177,
"data": 1509.7,
"group": "Worst Case" 
},
{
 "dates": 178,
"data": 1508.4,
"group": "Worst Case" 
},
{
 "dates": 179,
"data":   1507,
"group": "Worst Case" 
},
{
 "dates": 180,
"data": 1505.7,
"group": "Worst Case" 
},
{
 "dates": 181,
"data": 1504.3,
"group": "Worst Case" 
},
{
 "dates": 182,
"data":   1503,
"group": "Worst Case" 
},
{
 "dates": 183,
"data": 1501.7,
"group": "Worst Case" 
},
{
 "dates": 184,
"data": 1500.3,
"group": "Worst Case" 
},
{
 "dates": 185,
"data":   1499,
"group": "Worst Case" 
},
{
 "dates": 186,
"data": 1497.6,
"group": "Worst Case" 
},
{
 "dates": 187,
"data": 1496.3,
"group": "Worst Case" 
},
{
 "dates": 188,
"data":   1495,
"group": "Worst Case" 
},
{
 "dates": 189,
"data": 1493.6,
"group": "Worst Case" 
},
{
 "dates": 190,
"data": 1492.3,
"group": "Worst Case" 
},
{
 "dates": 191,
"data":   1491,
"group": "Worst Case" 
},
{
 "dates": 192,
"data": 1489.6,
"group": "Worst Case" 
},
{
 "dates": 193,
"data": 1488.3,
"group": "Worst Case" 
},
{
 "dates": 194,
"data":   1487,
"group": "Worst Case" 
},
{
 "dates": 195,
"data": 1485.7,
"group": "Worst Case" 
},
{
 "dates": 196,
"data": 1484.4,
"group": "Worst Case" 
},
{
 "dates": 197,
"data": 1483.1,
"group": "Worst Case" 
},
{
 "dates": 198,
"data": 1481.8,
"group": "Worst Case" 
},
{
 "dates": 199,
"data": 1480.5,
"group": "Worst Case" 
},
{
 "dates": 200,
"data": 1479.2,
"group": "Worst Case" 
},
{
 "dates": 201,
"data":   1478,
"group": "Worst Case" 
},
{
 "dates": 202,
"data": 1476.7,
"group": "Worst Case" 
},
{
 "dates": 203,
"data": 1475.5,
"group": "Worst Case" 
},
{
 "dates": 204,
"data": 1474.2,
"group": "Worst Case" 
},
{
 "dates": 205,
"data":   1473,
"group": "Worst Case" 
},
{
 "dates": 206,
"data": 1471.8,
"group": "Worst Case" 
},
{
 "dates": 207,
"data": 1470.6,
"group": "Worst Case" 
},
{
 "dates": 208,
"data": 1469.4,
"group": "Worst Case" 
},
{
 "dates": 209,
"data": 1468.2,
"group": "Worst Case" 
},
{
 "dates": 210,
"data":   1467,
"group": "Worst Case" 
},
{
 "dates": 211,
"data": 1465.9,
"group": "Worst Case" 
},
{
 "dates": 212,
"data": 1464.7,
"group": "Worst Case" 
},
{
 "dates": 213,
"data": 1463.6,
"group": "Worst Case" 
},
{
 "dates": 214,
"data": 1462.5,
"group": "Worst Case" 
},
{
 "dates": 215,
"data": 1461.4,
"group": "Worst Case" 
},
{
 "dates": 216,
"data": 1460.3,
"group": "Worst Case" 
},
{
 "dates": 217,
"data": 1459.2,
"group": "Worst Case" 
},
{
 "dates": 218,
"data": 1458.2,
"group": "Worst Case" 
},
{
 "dates": 219,
"data": 1457.2,
"group": "Worst Case" 
},
{
 "dates": 220,
"data": 1456.1,
"group": "Worst Case" 
},
{
 "dates": 221,
"data": 1455.1,
"group": "Worst Case" 
},
{
 "dates": 222,
"data": 1454.1,
"group": "Worst Case" 
},
{
 "dates": 223,
"data": 1453.2,
"group": "Worst Case" 
},
{
 "dates": 224,
"data": 1452.2,
"group": "Worst Case" 
},
{
 "dates": 225,
"data": 1451.3,
"group": "Worst Case" 
},
{
 "dates": 226,
"data": 1450.4,
"group": "Worst Case" 
},
{
 "dates": 227,
"data": 1449.5,
"group": "Worst Case" 
},
{
 "dates": 228,
"data": 1448.6,
"group": "Worst Case" 
},
{
 "dates": 229,
"data": 1447.8,
"group": "Worst Case" 
},
{
 "dates": 230,
"data": 1446.9,
"group": "Worst Case" 
},
{
 "dates": 231,
"data": 1446.1,
"group": "Worst Case" 
},
{
 "dates": 232,
"data": 1445.3,
"group": "Worst Case" 
},
{
 "dates": 233,
"data": 1444.6,
"group": "Worst Case" 
},
{
 "dates": 234,
"data": 1443.8,
"group": "Worst Case" 
},
{
 "dates": 235,
"data": 1443.1,
"group": "Worst Case" 
},
{
 "dates": 236,
"data": 1442.4,
"group": "Worst Case" 
},
{
 "dates": 237,
"data": 1441.7,
"group": "Worst Case" 
},
{
 "dates": 238,
"data": 1441.1,
"group": "Worst Case" 
},
{
 "dates": 239,
"data": 1440.4,
"group": "Worst Case" 
},
{
 "dates": 240,
"data": 1439.8,
"group": "Worst Case" 
},
{
 "dates": 241,
"data": 1439.3,
"group": "Worst Case" 
},
{
 "dates": 242,
"data": 1438.7,
"group": "Worst Case" 
},
{
 "dates": 243,
"data": 1438.2,
"group": "Worst Case" 
},
{
 "dates": 244,
"data": 1437.7,
"group": "Worst Case" 
},
{
 "dates": 245,
"data": 1437.2,
"group": "Worst Case" 
},
{
 "dates": 246,
"data": 1436.7,
"group": "Worst Case" 
},
{
 "dates": 247,
"data": 1436.3,
"group": "Worst Case" 
},
{
 "dates": 248,
"data": 1435.9,
"group": "Worst Case" 
},
{
 "dates": 249,
"data": 1435.5,
"group": "Worst Case" 
},
{
 "dates": 250,
"data": 1435.1,
"group": "Worst Case" 
},
{
 "dates": 251,
"data": 1434.8,
"group": "Worst Case" 
},
{
 "dates": 252,
"data": 1434.5,
"group": "Worst Case" 
},
{
 "dates": 253,
"data": 1434.2,
"group": "Worst Case" 
},
{
 "dates": 254,
"data":   1434,
"group": "Worst Case" 
},
{
 "dates": 255,
"data": 1433.8,
"group": "Worst Case" 
},
{
 "dates": 256,
"data": 1433.6,
"group": "Worst Case" 
},
{
 "dates": 257,
"data": 1433.4,
"group": "Worst Case" 
},
{
 "dates": 258,
"data": 1433.3,
"group": "Worst Case" 
},
{
 "dates": 259,
"data": 1433.2,
"group": "Worst Case" 
},
{
 "dates": 260,
"data": 1433.1,
"group": "Worst Case" 
},
{
 "dates": 261,
"data":   1433,
"group": "Worst Case" 
},
{
 "dates": 262,
"data":   1433,
"group": "Worst Case" 
},
{
 "dates": 263,
"data":   1433,
"group": "Worst Case" 
},
{
 "dates": 264,
"data":   1433,
"group": "Worst Case" 
},
{
 "dates": 265,
"data": 1433.1,
"group": "Worst Case" 
},
{
 "dates": 266,
"data": 1433.2,
"group": "Worst Case" 
},
{
 "dates": 267,
"data": 1433.3,
"group": "Worst Case" 
},
{
 "dates": 268,
"data": 1433.5,
"group": "Worst Case" 
},
{
 "dates": 269,
"data": 1433.6,
"group": "Worst Case" 
},
{
 "dates": 270,
"data": 1433.8,
"group": "Worst Case" 
},
{
 "dates": 271,
"data": 1434.1,
"group": "Worst Case" 
},
{
 "dates": 272,
"data": 1434.3,
"group": "Worst Case" 
},
{
 "dates": 273,
"data": 1434.6,
"group": "Worst Case" 
},
{
 "dates": 274,
"data": 1434.9,
"group": "Worst Case" 
},
{
 "dates": 275,
"data": 1435.3,
"group": "Worst Case" 
},
{
 "dates": 276,
"data": 1435.7,
"group": "Worst Case" 
},
{
 "dates": 277,
"data": 1436.1,
"group": "Worst Case" 
},
{
 "dates": 278,
"data": 1436.5,
"group": "Worst Case" 
},
{
 "dates": 279,
"data":   1437,
"group": "Worst Case" 
},
{
 "dates": 280,
"data": 1437.5,
"group": "Worst Case" 
},
{
 "dates": 281,
"data":   1438,
"group": "Worst Case" 
},
{
 "dates": 282,
"data": 1438.5,
"group": "Worst Case" 
},
{
 "dates": 283,
"data": 1439.1,
"group": "Worst Case" 
},
{
 "dates": 284,
"data": 1439.7,
"group": "Worst Case" 
},
{
 "dates": 285,
"data": 1440.3,
"group": "Worst Case" 
},
{
 "dates": 286,
"data":   1441,
"group": "Worst Case" 
},
{
 "dates": 287,
"data": 1441.7,
"group": "Worst Case" 
},
{
 "dates": 288,
"data": 1442.4,
"group": "Worst Case" 
},
{
 "dates": 289,
"data": 1443.2,
"group": "Worst Case" 
},
{
 "dates": 290,
"data": 1443.9,
"group": "Worst Case" 
},
{
 "dates": 291,
"data": 1444.8,
"group": "Worst Case" 
},
{
 "dates": 292,
"data": 1445.6,
"group": "Worst Case" 
},
{
 "dates": 293,
"data": 1446.4,
"group": "Worst Case" 
},
{
 "dates": 294,
"data": 1447.3,
"group": "Worst Case" 
},
{
 "dates": 295,
"data": 1448.2,
"group": "Worst Case" 
},
{
 "dates": 296,
"data": 1449.2,
"group": "Worst Case" 
},
{
 "dates": 297,
"data": 1450.2,
"group": "Worst Case" 
},
{
 "dates": 298,
"data": 1451.1,
"group": "Worst Case" 
},
{
 "dates": 299,
"data": 1452.2,
"group": "Worst Case" 
},
{
 "dates": 300,
"data": 1453.2,
"group": "Worst Case" 
},
{
 "dates": 301,
"data": 1454.3,
"group": "Worst Case" 
},
{
 "dates": 302,
"data": 1455.4,
"group": "Worst Case" 
},
{
 "dates": 303,
"data": 1456.5,
"group": "Worst Case" 
},
{
 "dates": 304,
"data": 1457.7,
"group": "Worst Case" 
},
{
 "dates": 305,
"data": 1458.8,
"group": "Worst Case" 
},
{
 "dates": 306,
"data":   1460,
"group": "Worst Case" 
},
{
 "dates": 307,
"data": 1461.3,
"group": "Worst Case" 
},
{
 "dates": 308,
"data": 1462.5,
"group": "Worst Case" 
},
{
 "dates": 309,
"data": 1463.8,
"group": "Worst Case" 
},
{
 "dates": 310,
"data": 1465.1,
"group": "Worst Case" 
},
{
 "dates": 311,
"data": 1466.4,
"group": "Worst Case" 
},
{
 "dates": 312,
"data": 1467.7,
"group": "Worst Case" 
},
{
 "dates": 313,
"data": 1469.1,
"group": "Worst Case" 
},
{
 "dates": 314,
"data": 1470.5,
"group": "Worst Case" 
},
{
 "dates": 315,
"data": 1471.9,
"group": "Worst Case" 
},
{
 "dates": 316,
"data": 1473.3,
"group": "Worst Case" 
},
{
 "dates": 317,
"data": 1474.8,
"group": "Worst Case" 
},
{
 "dates": 318,
"data": 1476.3,
"group": "Worst Case" 
},
{
 "dates": 319,
"data": 1477.8,
"group": "Worst Case" 
},
{
 "dates": 320,
"data": 1479.3,
"group": "Worst Case" 
},
{
 "dates": 321,
"data": 1480.8,
"group": "Worst Case" 
},
{
 "dates": 322,
"data": 1482.4,
"group": "Worst Case" 
},
{
 "dates": 323,
"data":   1484,
"group": "Worst Case" 
},
{
 "dates": 324,
"data": 1485.6,
"group": "Worst Case" 
},
{
 "dates": 325,
"data": 1487.2,
"group": "Worst Case" 
},
{
 "dates": 326,
"data": 1488.8,
"group": "Worst Case" 
},
{
 "dates": 327,
"data": 1490.5,
"group": "Worst Case" 
},
{
 "dates": 328,
"data": 1492.1,
"group": "Worst Case" 
},
{
 "dates": 329,
"data": 1493.8,
"group": "Worst Case" 
},
{
 "dates": 330,
"data": 1495.5,
"group": "Worst Case" 
},
{
 "dates": 331,
"data": 1497.2,
"group": "Worst Case" 
},
{
 "dates": 332,
"data":   1499,
"group": "Worst Case" 
},
{
 "dates": 333,
"data": 1500.7,
"group": "Worst Case" 
},
{
 "dates": 334,
"data": 1502.5,
"group": "Worst Case" 
},
{
 "dates": 335,
"data": 1504.3,
"group": "Worst Case" 
},
{
 "dates": 336,
"data": 1506.1,
"group": "Worst Case" 
},
{
 "dates": 337,
"data": 1507.9,
"group": "Worst Case" 
},
{
 "dates": 338,
"data": 1509.7,
"group": "Worst Case" 
},
{
 "dates": 339,
"data": 1511.5,
"group": "Worst Case" 
},
{
 "dates": 340,
"data": 1513.4,
"group": "Worst Case" 
},
{
 "dates": 341,
"data": 1515.3,
"group": "Worst Case" 
},
{
 "dates": 342,
"data": 1517.1,
"group": "Worst Case" 
},
{
 "dates": 343,
"data":   1519,
"group": "Worst Case" 
},
{
 "dates": 344,
"data": 1520.9,
"group": "Worst Case" 
},
{
 "dates": 345,
"data": 1522.8,
"group": "Worst Case" 
},
{
 "dates": 346,
"data": 1524.7,
"group": "Worst Case" 
},
{
 "dates": 347,
"data": 1526.7,
"group": "Worst Case" 
},
{
 "dates": 348,
"data": 1528.6,
"group": "Worst Case" 
},
{
 "dates": 349,
"data": 1530.5,
"group": "Worst Case" 
},
{
 "dates": 350,
"data": 1532.5,
"group": "Worst Case" 
},
{
 "dates": 351,
"data": 1534.4,
"group": "Worst Case" 
},
{
 "dates": 352,
"data": 1536.4,
"group": "Worst Case" 
},
{
 "dates": 353,
"data": 1538.4,
"group": "Worst Case" 
},
{
 "dates": 354,
"data": 1540.3,
"group": "Worst Case" 
},
{
 "dates": 355,
"data": 1542.3,
"group": "Worst Case" 
},
{
 "dates": 356,
"data": 1544.3,
"group": "Worst Case" 
},
{
 "dates": 357,
"data": 1546.3,
"group": "Worst Case" 
},
{
 "dates": 358,
"data": 1548.3,
"group": "Worst Case" 
},
{
 "dates": 359,
"data": 1550.3,
"group": "Worst Case" 
},
{
 "dates": 360,
"data": 1552.3,
"group": "Worst Case" 
},
{
 "dates": 361,
"data": 1554.3,
"group": "Worst Case" 
},
{
 "dates": 362,
"data": 1556.3,
"group": "Worst Case" 
},
{
 "dates": 363,
"data": 1558.3,
"group": "Worst Case" 
},
{
 "dates": 364,
"data": 1560.3,
"group": "Worst Case" 
},
{
 "dates": 365,
"data": 1562.3,
"group": "Worst Case" 
},
{
 "dates": 1,
"data": 1565.6,
"group": "Best Case" 
},
{
 "dates": 2,
"data": 1567.6,
"group": "Best Case" 
},
{
 "dates": 3,
"data": 1569.6,
"group": "Best Case" 
},
{
 "dates": 4,
"data": 1571.6,
"group": "Best Case" 
},
{
 "dates": 5,
"data": 1573.6,
"group": "Best Case" 
},
{
 "dates": 6,
"data": 1575.6,
"group": "Best Case" 
},
{
 "dates": 7,
"data": 1577.6,
"group": "Best Case" 
},
{
 "dates": 8,
"data": 1579.6,
"group": "Best Case" 
},
{
 "dates": 9,
"data": 1581.6,
"group": "Best Case" 
},
{
 "dates": 10,
"data": 1583.6,
"group": "Best Case" 
},
{
 "dates": 11,
"data": 1585.6,
"group": "Best Case" 
},
{
 "dates": 12,
"data": 1587.6,
"group": "Best Case" 
},
{
 "dates": 13,
"data": 1589.5,
"group": "Best Case" 
},
{
 "dates": 14,
"data": 1591.5,
"group": "Best Case" 
},
{
 "dates": 15,
"data": 1593.5,
"group": "Best Case" 
},
{
 "dates": 16,
"data": 1595.4,
"group": "Best Case" 
},
{
 "dates": 17,
"data": 1597.4,
"group": "Best Case" 
},
{
 "dates": 18,
"data": 1599.3,
"group": "Best Case" 
},
{
 "dates": 19,
"data": 1601.3,
"group": "Best Case" 
},
{
 "dates": 20,
"data": 1603.2,
"group": "Best Case" 
},
{
 "dates": 21,
"data": 1605.1,
"group": "Best Case" 
},
{
 "dates": 22,
"data":   1607,
"group": "Best Case" 
},
{
 "dates": 23,
"data": 1608.9,
"group": "Best Case" 
},
{
 "dates": 24,
"data": 1610.8,
"group": "Best Case" 
},
{
 "dates": 25,
"data": 1612.6,
"group": "Best Case" 
},
{
 "dates": 26,
"data": 1614.5,
"group": "Best Case" 
},
{
 "dates": 27,
"data": 1616.4,
"group": "Best Case" 
},
{
 "dates": 28,
"data": 1618.2,
"group": "Best Case" 
},
{
 "dates": 29,
"data":   1620,
"group": "Best Case" 
},
{
 "dates": 30,
"data": 1621.8,
"group": "Best Case" 
},
{
 "dates": 31,
"data": 1623.6,
"group": "Best Case" 
},
{
 "dates": 32,
"data": 1625.4,
"group": "Best Case" 
},
{
 "dates": 33,
"data": 1627.2,
"group": "Best Case" 
},
{
 "dates": 34,
"data": 1628.9,
"group": "Best Case" 
},
{
 "dates": 35,
"data": 1630.7,
"group": "Best Case" 
},
{
 "dates": 36,
"data": 1632.4,
"group": "Best Case" 
},
{
 "dates": 37,
"data": 1634.1,
"group": "Best Case" 
},
{
 "dates": 38,
"data": 1635.8,
"group": "Best Case" 
},
{
 "dates": 39,
"data": 1637.4,
"group": "Best Case" 
},
{
 "dates": 40,
"data": 1639.1,
"group": "Best Case" 
},
{
 "dates": 41,
"data": 1640.7,
"group": "Best Case" 
},
{
 "dates": 42,
"data": 1642.3,
"group": "Best Case" 
},
{
 "dates": 43,
"data": 1643.9,
"group": "Best Case" 
},
{
 "dates": 44,
"data": 1645.5,
"group": "Best Case" 
},
{
 "dates": 45,
"data": 1647.1,
"group": "Best Case" 
},
{
 "dates": 46,
"data": 1648.6,
"group": "Best Case" 
},
{
 "dates": 47,
"data": 1650.1,
"group": "Best Case" 
},
{
 "dates": 48,
"data": 1651.6,
"group": "Best Case" 
},
{
 "dates": 49,
"data": 1653.1,
"group": "Best Case" 
},
{
 "dates": 50,
"data": 1654.6,
"group": "Best Case" 
},
{
 "dates": 51,
"data":   1656,
"group": "Best Case" 
},
{
 "dates": 52,
"data": 1657.4,
"group": "Best Case" 
},
{
 "dates": 53,
"data": 1658.8,
"group": "Best Case" 
},
{
 "dates": 54,
"data": 1660.2,
"group": "Best Case" 
},
{
 "dates": 55,
"data": 1661.5,
"group": "Best Case" 
},
{
 "dates": 56,
"data": 1662.8,
"group": "Best Case" 
},
{
 "dates": 57,
"data": 1664.1,
"group": "Best Case" 
},
{
 "dates": 58,
"data": 1665.4,
"group": "Best Case" 
},
{
 "dates": 59,
"data": 1666.6,
"group": "Best Case" 
},
{
 "dates": 60,
"data": 1667.9,
"group": "Best Case" 
},
{
 "dates": 61,
"data": 1669.1,
"group": "Best Case" 
},
{
 "dates": 62,
"data": 1670.2,
"group": "Best Case" 
},
{
 "dates": 63,
"data": 1671.4,
"group": "Best Case" 
},
{
 "dates": 64,
"data": 1672.5,
"group": "Best Case" 
},
{
 "dates": 65,
"data": 1673.6,
"group": "Best Case" 
},
{
 "dates": 66,
"data": 1674.7,
"group": "Best Case" 
},
{
 "dates": 67,
"data": 1675.7,
"group": "Best Case" 
},
{
 "dates": 68,
"data": 1676.8,
"group": "Best Case" 
},
{
 "dates": 69,
"data": 1677.8,
"group": "Best Case" 
},
{
 "dates": 70,
"data": 1678.7,
"group": "Best Case" 
},
{
 "dates": 71,
"data": 1679.7,
"group": "Best Case" 
},
{
 "dates": 72,
"data": 1680.6,
"group": "Best Case" 
},
{
 "dates": 73,
"data": 1681.5,
"group": "Best Case" 
},
{
 "dates": 74,
"data": 1682.3,
"group": "Best Case" 
},
{
 "dates": 75,
"data": 1683.2,
"group": "Best Case" 
},
{
 "dates": 76,
"data":   1684,
"group": "Best Case" 
},
{
 "dates": 77,
"data": 1684.7,
"group": "Best Case" 
},
{
 "dates": 78,
"data": 1685.5,
"group": "Best Case" 
},
{
 "dates": 79,
"data": 1686.2,
"group": "Best Case" 
},
{
 "dates": 80,
"data": 1686.9,
"group": "Best Case" 
},
{
 "dates": 81,
"data": 1687.6,
"group": "Best Case" 
},
{
 "dates": 82,
"data": 1688.2,
"group": "Best Case" 
},
{
 "dates": 83,
"data": 1688.8,
"group": "Best Case" 
},
{
 "dates": 84,
"data": 1689.4,
"group": "Best Case" 
},
{
 "dates": 85,
"data": 1689.9,
"group": "Best Case" 
},
{
 "dates": 86,
"data": 1690.4,
"group": "Best Case" 
},
{
 "dates": 87,
"data": 1690.9,
"group": "Best Case" 
},
{
 "dates": 88,
"data": 1691.4,
"group": "Best Case" 
},
{
 "dates": 89,
"data": 1691.8,
"group": "Best Case" 
},
{
 "dates": 90,
"data": 1692.2,
"group": "Best Case" 
},
{
 "dates": 91,
"data": 1692.6,
"group": "Best Case" 
},
{
 "dates": 92,
"data":   1693,
"group": "Best Case" 
},
{
 "dates": 93,
"data": 1693.3,
"group": "Best Case" 
},
{
 "dates": 94,
"data": 1693.6,
"group": "Best Case" 
},
{
 "dates": 95,
"data": 1693.8,
"group": "Best Case" 
},
{
 "dates": 96,
"data": 1694.1,
"group": "Best Case" 
},
{
 "dates": 97,
"data": 1694.3,
"group": "Best Case" 
},
{
 "dates": 98,
"data": 1694.5,
"group": "Best Case" 
},
{
 "dates": 99,
"data": 1694.6,
"group": "Best Case" 
},
{
 "dates": 100,
"data": 1694.7,
"group": "Best Case" 
},
{
 "dates": 101,
"data": 1694.8,
"group": "Best Case" 
},
{
 "dates": 102,
"data": 1694.9,
"group": "Best Case" 
},
{
 "dates": 103,
"data": 1694.9,
"group": "Best Case" 
},
{
 "dates": 104,
"data": 1694.9,
"group": "Best Case" 
},
{
 "dates": 105,
"data": 1694.9,
"group": "Best Case" 
},
{
 "dates": 106,
"data": 1694.8,
"group": "Best Case" 
},
{
 "dates": 107,
"data": 1694.7,
"group": "Best Case" 
},
{
 "dates": 108,
"data": 1694.6,
"group": "Best Case" 
},
{
 "dates": 109,
"data": 1694.5,
"group": "Best Case" 
},
{
 "dates": 110,
"data": 1694.3,
"group": "Best Case" 
},
{
 "dates": 111,
"data": 1694.1,
"group": "Best Case" 
},
{
 "dates": 112,
"data": 1693.9,
"group": "Best Case" 
},
{
 "dates": 113,
"data": 1693.7,
"group": "Best Case" 
},
{
 "dates": 114,
"data": 1693.4,
"group": "Best Case" 
},
{
 "dates": 115,
"data": 1693.1,
"group": "Best Case" 
},
{
 "dates": 116,
"data": 1692.8,
"group": "Best Case" 
},
{
 "dates": 117,
"data": 1692.4,
"group": "Best Case" 
},
{
 "dates": 118,
"data":   1692,
"group": "Best Case" 
},
{
 "dates": 119,
"data": 1691.6,
"group": "Best Case" 
},
{
 "dates": 120,
"data": 1691.2,
"group": "Best Case" 
},
{
 "dates": 121,
"data": 1690.7,
"group": "Best Case" 
},
{
 "dates": 122,
"data": 1690.2,
"group": "Best Case" 
},
{
 "dates": 123,
"data": 1689.7,
"group": "Best Case" 
},
{
 "dates": 124,
"data": 1689.2,
"group": "Best Case" 
},
{
 "dates": 125,
"data": 1688.6,
"group": "Best Case" 
},
{
 "dates": 126,
"data": 1688.1,
"group": "Best Case" 
},
{
 "dates": 127,
"data": 1687.5,
"group": "Best Case" 
},
{
 "dates": 128,
"data": 1686.8,
"group": "Best Case" 
},
{
 "dates": 129,
"data": 1686.2,
"group": "Best Case" 
},
{
 "dates": 130,
"data": 1685.5,
"group": "Best Case" 
},
{
 "dates": 131,
"data": 1684.8,
"group": "Best Case" 
},
{
 "dates": 132,
"data": 1684.1,
"group": "Best Case" 
},
{
 "dates": 133,
"data": 1683.3,
"group": "Best Case" 
},
{
 "dates": 134,
"data": 1682.6,
"group": "Best Case" 
},
{
 "dates": 135,
"data": 1681.8,
"group": "Best Case" 
},
{
 "dates": 136,
"data":   1681,
"group": "Best Case" 
},
{
 "dates": 137,
"data": 1680.1,
"group": "Best Case" 
},
{
 "dates": 138,
"data": 1679.3,
"group": "Best Case" 
},
{
 "dates": 139,
"data": 1678.4,
"group": "Best Case" 
},
{
 "dates": 140,
"data": 1677.5,
"group": "Best Case" 
},
{
 "dates": 141,
"data": 1676.6,
"group": "Best Case" 
},
{
 "dates": 142,
"data": 1675.7,
"group": "Best Case" 
},
{
 "dates": 143,
"data": 1674.7,
"group": "Best Case" 
},
{
 "dates": 144,
"data": 1673.8,
"group": "Best Case" 
},
{
 "dates": 145,
"data": 1672.8,
"group": "Best Case" 
},
{
 "dates": 146,
"data": 1671.8,
"group": "Best Case" 
},
{
 "dates": 147,
"data": 1670.8,
"group": "Best Case" 
},
{
 "dates": 148,
"data": 1669.7,
"group": "Best Case" 
},
{
 "dates": 149,
"data": 1668.7,
"group": "Best Case" 
},
{
 "dates": 150,
"data": 1667.6,
"group": "Best Case" 
},
{
 "dates": 151,
"data": 1666.5,
"group": "Best Case" 
},
{
 "dates": 152,
"data": 1665.4,
"group": "Best Case" 
},
{
 "dates": 153,
"data": 1664.3,
"group": "Best Case" 
},
{
 "dates": 154,
"data": 1663.2,
"group": "Best Case" 
},
{
 "dates": 155,
"data":   1662,
"group": "Best Case" 
},
{
 "dates": 156,
"data": 1660.9,
"group": "Best Case" 
},
{
 "dates": 157,
"data": 1659.7,
"group": "Best Case" 
},
{
 "dates": 158,
"data": 1658.5,
"group": "Best Case" 
},
{
 "dates": 159,
"data": 1657.3,
"group": "Best Case" 
},
{
 "dates": 160,
"data": 1656.1,
"group": "Best Case" 
},
{
 "dates": 161,
"data": 1654.9,
"group": "Best Case" 
},
{
 "dates": 162,
"data": 1653.7,
"group": "Best Case" 
},
{
 "dates": 163,
"data": 1652.4,
"group": "Best Case" 
},
{
 "dates": 164,
"data": 1651.2,
"group": "Best Case" 
},
{
 "dates": 165,
"data": 1649.9,
"group": "Best Case" 
},
{
 "dates": 166,
"data": 1648.7,
"group": "Best Case" 
},
{
 "dates": 167,
"data": 1647.4,
"group": "Best Case" 
},
{
 "dates": 168,
"data": 1646.1,
"group": "Best Case" 
},
{
 "dates": 169,
"data": 1644.8,
"group": "Best Case" 
},
{
 "dates": 170,
"data": 1643.5,
"group": "Best Case" 
},
{
 "dates": 171,
"data": 1642.2,
"group": "Best Case" 
},
{
 "dates": 172,
"data": 1640.9,
"group": "Best Case" 
},
{
 "dates": 173,
"data": 1639.6,
"group": "Best Case" 
},
{
 "dates": 174,
"data": 1638.3,
"group": "Best Case" 
},
{
 "dates": 175,
"data": 1636.9,
"group": "Best Case" 
},
{
 "dates": 176,
"data": 1635.6,
"group": "Best Case" 
},
{
 "dates": 177,
"data": 1634.3,
"group": "Best Case" 
},
{
 "dates": 178,
"data":   1633,
"group": "Best Case" 
},
{
 "dates": 179,
"data": 1631.6,
"group": "Best Case" 
},
{
 "dates": 180,
"data": 1630.3,
"group": "Best Case" 
},
{
 "dates": 181,
"data": 1628.9,
"group": "Best Case" 
},
{
 "dates": 182,
"data": 1627.6,
"group": "Best Case" 
},
{
 "dates": 183,
"data": 1626.3,
"group": "Best Case" 
},
{
 "dates": 184,
"data": 1624.9,
"group": "Best Case" 
},
{
 "dates": 185,
"data": 1623.6,
"group": "Best Case" 
},
{
 "dates": 186,
"data": 1622.2,
"group": "Best Case" 
},
{
 "dates": 187,
"data": 1620.9,
"group": "Best Case" 
},
{
 "dates": 188,
"data": 1619.6,
"group": "Best Case" 
},
{
 "dates": 189,
"data": 1618.2,
"group": "Best Case" 
},
{
 "dates": 190,
"data": 1616.9,
"group": "Best Case" 
},
{
 "dates": 191,
"data": 1615.6,
"group": "Best Case" 
},
{
 "dates": 192,
"data": 1614.2,
"group": "Best Case" 
},
{
 "dates": 193,
"data": 1612.9,
"group": "Best Case" 
},
{
 "dates": 194,
"data": 1611.6,
"group": "Best Case" 
},
{
 "dates": 195,
"data": 1610.3,
"group": "Best Case" 
},
{
 "dates": 196,
"data":   1609,
"group": "Best Case" 
},
{
 "dates": 197,
"data": 1607.7,
"group": "Best Case" 
},
{
 "dates": 198,
"data": 1606.4,
"group": "Best Case" 
},
{
 "dates": 199,
"data": 1605.1,
"group": "Best Case" 
},
{
 "dates": 200,
"data": 1603.8,
"group": "Best Case" 
},
{
 "dates": 201,
"data": 1602.6,
"group": "Best Case" 
},
{
 "dates": 202,
"data": 1601.3,
"group": "Best Case" 
},
{
 "dates": 203,
"data": 1600.1,
"group": "Best Case" 
},
{
 "dates": 204,
"data": 1598.8,
"group": "Best Case" 
},
{
 "dates": 205,
"data": 1597.6,
"group": "Best Case" 
},
{
 "dates": 206,
"data": 1596.4,
"group": "Best Case" 
},
{
 "dates": 207,
"data": 1595.2,
"group": "Best Case" 
},
{
 "dates": 208,
"data":   1594,
"group": "Best Case" 
},
{
 "dates": 209,
"data": 1592.8,
"group": "Best Case" 
},
{
 "dates": 210,
"data": 1591.6,
"group": "Best Case" 
},
{
 "dates": 211,
"data": 1590.5,
"group": "Best Case" 
},
{
 "dates": 212,
"data": 1589.3,
"group": "Best Case" 
},
{
 "dates": 213,
"data": 1588.2,
"group": "Best Case" 
},
{
 "dates": 214,
"data": 1587.1,
"group": "Best Case" 
},
{
 "dates": 215,
"data":   1586,
"group": "Best Case" 
},
{
 "dates": 216,
"data": 1584.9,
"group": "Best Case" 
},
{
 "dates": 217,
"data": 1583.8,
"group": "Best Case" 
},
{
 "dates": 218,
"data": 1582.8,
"group": "Best Case" 
},
{
 "dates": 219,
"data": 1581.7,
"group": "Best Case" 
},
{
 "dates": 220,
"data": 1580.7,
"group": "Best Case" 
},
{
 "dates": 221,
"data": 1579.7,
"group": "Best Case" 
},
{
 "dates": 222,
"data": 1578.7,
"group": "Best Case" 
},
{
 "dates": 223,
"data": 1577.8,
"group": "Best Case" 
},
{
 "dates": 224,
"data": 1576.8,
"group": "Best Case" 
},
{
 "dates": 225,
"data": 1575.9,
"group": "Best Case" 
},
{
 "dates": 226,
"data":   1575,
"group": "Best Case" 
},
{
 "dates": 227,
"data": 1574.1,
"group": "Best Case" 
},
{
 "dates": 228,
"data": 1573.2,
"group": "Best Case" 
},
{
 "dates": 229,
"data": 1572.4,
"group": "Best Case" 
},
{
 "dates": 230,
"data": 1571.5,
"group": "Best Case" 
},
{
 "dates": 231,
"data": 1570.7,
"group": "Best Case" 
},
{
 "dates": 232,
"data": 1569.9,
"group": "Best Case" 
},
{
 "dates": 233,
"data": 1569.2,
"group": "Best Case" 
},
{
 "dates": 234,
"data": 1568.4,
"group": "Best Case" 
},
{
 "dates": 235,
"data": 1567.7,
"group": "Best Case" 
},
{
 "dates": 236,
"data":   1567,
"group": "Best Case" 
},
{
 "dates": 237,
"data": 1566.3,
"group": "Best Case" 
},
{
 "dates": 238,
"data": 1565.7,
"group": "Best Case" 
},
{
 "dates": 239,
"data":   1565,
"group": "Best Case" 
},
{
 "dates": 240,
"data": 1564.4,
"group": "Best Case" 
},
{
 "dates": 241,
"data": 1563.9,
"group": "Best Case" 
},
{
 "dates": 242,
"data": 1563.3,
"group": "Best Case" 
},
{
 "dates": 243,
"data": 1562.8,
"group": "Best Case" 
},
{
 "dates": 244,
"data": 1562.3,
"group": "Best Case" 
},
{
 "dates": 245,
"data": 1561.8,
"group": "Best Case" 
},
{
 "dates": 246,
"data": 1561.3,
"group": "Best Case" 
},
{
 "dates": 247,
"data": 1560.9,
"group": "Best Case" 
},
{
 "dates": 248,
"data": 1560.5,
"group": "Best Case" 
},
{
 "dates": 249,
"data": 1560.1,
"group": "Best Case" 
},
{
 "dates": 250,
"data": 1559.7,
"group": "Best Case" 
},
{
 "dates": 251,
"data": 1559.4,
"group": "Best Case" 
},
{
 "dates": 252,
"data": 1559.1,
"group": "Best Case" 
},
{
 "dates": 253,
"data": 1558.8,
"group": "Best Case" 
},
{
 "dates": 254,
"data": 1558.6,
"group": "Best Case" 
},
{
 "dates": 255,
"data": 1558.4,
"group": "Best Case" 
},
{
 "dates": 256,
"data": 1558.2,
"group": "Best Case" 
},
{
 "dates": 257,
"data":   1558,
"group": "Best Case" 
},
{
 "dates": 258,
"data": 1557.9,
"group": "Best Case" 
},
{
 "dates": 259,
"data": 1557.8,
"group": "Best Case" 
},
{
 "dates": 260,
"data": 1557.7,
"group": "Best Case" 
},
{
 "dates": 261,
"data": 1557.6,
"group": "Best Case" 
},
{
 "dates": 262,
"data": 1557.6,
"group": "Best Case" 
},
{
 "dates": 263,
"data": 1557.6,
"group": "Best Case" 
},
{
 "dates": 264,
"data": 1557.6,
"group": "Best Case" 
},
{
 "dates": 265,
"data": 1557.7,
"group": "Best Case" 
},
{
 "dates": 266,
"data": 1557.8,
"group": "Best Case" 
},
{
 "dates": 267,
"data": 1557.9,
"group": "Best Case" 
},
{
 "dates": 268,
"data": 1558.1,
"group": "Best Case" 
},
{
 "dates": 269,
"data": 1558.2,
"group": "Best Case" 
},
{
 "dates": 270,
"data": 1558.4,
"group": "Best Case" 
},
{
 "dates": 271,
"data": 1558.7,
"group": "Best Case" 
},
{
 "dates": 272,
"data": 1558.9,
"group": "Best Case" 
},
{
 "dates": 273,
"data": 1559.2,
"group": "Best Case" 
},
{
 "dates": 274,
"data": 1559.5,
"group": "Best Case" 
},
{
 "dates": 275,
"data": 1559.9,
"group": "Best Case" 
},
{
 "dates": 276,
"data": 1560.3,
"group": "Best Case" 
},
{
 "dates": 277,
"data": 1560.7,
"group": "Best Case" 
},
{
 "dates": 278,
"data": 1561.1,
"group": "Best Case" 
},
{
 "dates": 279,
"data": 1561.6,
"group": "Best Case" 
},
{
 "dates": 280,
"data": 1562.1,
"group": "Best Case" 
},
{
 "dates": 281,
"data": 1562.6,
"group": "Best Case" 
},
{
 "dates": 282,
"data": 1563.1,
"group": "Best Case" 
},
{
 "dates": 283,
"data": 1563.7,
"group": "Best Case" 
},
{
 "dates": 284,
"data": 1564.3,
"group": "Best Case" 
},
{
 "dates": 285,
"data": 1564.9,
"group": "Best Case" 
},
{
 "dates": 286,
"data": 1565.6,
"group": "Best Case" 
},
{
 "dates": 287,
"data": 1566.3,
"group": "Best Case" 
},
{
 "dates": 288,
"data":   1567,
"group": "Best Case" 
},
{
 "dates": 289,
"data": 1567.8,
"group": "Best Case" 
},
{
 "dates": 290,
"data": 1568.5,
"group": "Best Case" 
},
{
 "dates": 291,
"data": 1569.3,
"group": "Best Case" 
},
{
 "dates": 292,
"data": 1570.2,
"group": "Best Case" 
},
{
 "dates": 293,
"data":   1571,
"group": "Best Case" 
},
{
 "dates": 294,
"data": 1571.9,
"group": "Best Case" 
},
{
 "dates": 295,
"data": 1572.8,
"group": "Best Case" 
},
{
 "dates": 296,
"data": 1573.8,
"group": "Best Case" 
},
{
 "dates": 297,
"data": 1574.8,
"group": "Best Case" 
},
{
 "dates": 298,
"data": 1575.7,
"group": "Best Case" 
},
{
 "dates": 299,
"data": 1576.8,
"group": "Best Case" 
},
{
 "dates": 300,
"data": 1577.8,
"group": "Best Case" 
},
{
 "dates": 301,
"data": 1578.9,
"group": "Best Case" 
},
{
 "dates": 302,
"data":   1580,
"group": "Best Case" 
},
{
 "dates": 303,
"data": 1581.1,
"group": "Best Case" 
},
{
 "dates": 304,
"data": 1582.3,
"group": "Best Case" 
},
{
 "dates": 305,
"data": 1583.4,
"group": "Best Case" 
},
{
 "dates": 306,
"data": 1584.6,
"group": "Best Case" 
},
{
 "dates": 307,
"data": 1585.9,
"group": "Best Case" 
},
{
 "dates": 308,
"data": 1587.1,
"group": "Best Case" 
},
{
 "dates": 309,
"data": 1588.4,
"group": "Best Case" 
},
{
 "dates": 310,
"data": 1589.7,
"group": "Best Case" 
},
{
 "dates": 311,
"data":   1591,
"group": "Best Case" 
},
{
 "dates": 312,
"data": 1592.3,
"group": "Best Case" 
},
{
 "dates": 313,
"data": 1593.7,
"group": "Best Case" 
},
{
 "dates": 314,
"data": 1595.1,
"group": "Best Case" 
},
{
 "dates": 315,
"data": 1596.5,
"group": "Best Case" 
},
{
 "dates": 316,
"data": 1597.9,
"group": "Best Case" 
},
{
 "dates": 317,
"data": 1599.4,
"group": "Best Case" 
},
{
 "dates": 318,
"data": 1600.9,
"group": "Best Case" 
},
{
 "dates": 319,
"data": 1602.4,
"group": "Best Case" 
},
{
 "dates": 320,
"data": 1603.9,
"group": "Best Case" 
},
{
 "dates": 321,
"data": 1605.4,
"group": "Best Case" 
},
{
 "dates": 322,
"data":   1607,
"group": "Best Case" 
},
{
 "dates": 323,
"data": 1608.6,
"group": "Best Case" 
},
{
 "dates": 324,
"data": 1610.2,
"group": "Best Case" 
},
{
 "dates": 325,
"data": 1611.8,
"group": "Best Case" 
},
{
 "dates": 326,
"data": 1613.4,
"group": "Best Case" 
},
{
 "dates": 327,
"data": 1615.1,
"group": "Best Case" 
},
{
 "dates": 328,
"data": 1616.7,
"group": "Best Case" 
},
{
 "dates": 329,
"data": 1618.4,
"group": "Best Case" 
},
{
 "dates": 330,
"data": 1620.1,
"group": "Best Case" 
},
{
 "dates": 331,
"data": 1621.8,
"group": "Best Case" 
},
{
 "dates": 332,
"data": 1623.6,
"group": "Best Case" 
},
{
 "dates": 333,
"data": 1625.3,
"group": "Best Case" 
},
{
 "dates": 334,
"data": 1627.1,
"group": "Best Case" 
},
{
 "dates": 335,
"data": 1628.9,
"group": "Best Case" 
},
{
 "dates": 336,
"data": 1630.7,
"group": "Best Case" 
},
{
 "dates": 337,
"data": 1632.5,
"group": "Best Case" 
},
{
 "dates": 338,
"data": 1634.3,
"group": "Best Case" 
},
{
 "dates": 339,
"data": 1636.1,
"group": "Best Case" 
},
{
 "dates": 340,
"data":   1638,
"group": "Best Case" 
},
{
 "dates": 341,
"data": 1639.9,
"group": "Best Case" 
},
{
 "dates": 342,
"data": 1641.7,
"group": "Best Case" 
},
{
 "dates": 343,
"data": 1643.6,
"group": "Best Case" 
},
{
 "dates": 344,
"data": 1645.5,
"group": "Best Case" 
},
{
 "dates": 345,
"data": 1647.4,
"group": "Best Case" 
},
{
 "dates": 346,
"data": 1649.3,
"group": "Best Case" 
},
{
 "dates": 347,
"data": 1651.3,
"group": "Best Case" 
},
{
 "dates": 348,
"data": 1653.2,
"group": "Best Case" 
},
{
 "dates": 349,
"data": 1655.1,
"group": "Best Case" 
},
{
 "dates": 350,
"data": 1657.1,
"group": "Best Case" 
},
{
 "dates": 351,
"data":   1659,
"group": "Best Case" 
},
{
 "dates": 352,
"data":   1661,
"group": "Best Case" 
},
{
 "dates": 353,
"data":   1663,
"group": "Best Case" 
},
{
 "dates": 354,
"data": 1664.9,
"group": "Best Case" 
},
{
 "dates": 355,
"data": 1666.9,
"group": "Best Case" 
},
{
 "dates": 356,
"data": 1668.9,
"group": "Best Case" 
},
{
 "dates": 357,
"data": 1670.9,
"group": "Best Case" 
},
{
 "dates": 358,
"data": 1672.9,
"group": "Best Case" 
},
{
 "dates": 359,
"data": 1674.9,
"group": "Best Case" 
},
{
 "dates": 360,
"data": 1676.9,
"group": "Best Case" 
},
{
 "dates": 361,
"data": 1678.9,
"group": "Best Case" 
},
{
 "dates": 362,
"data": 1680.9,
"group": "Best Case" 
},
{
 "dates": 363,
"data": 1682.9,
"group": "Best Case" 
},
{
 "dates": 364,
"data": 1684.9,
"group": "Best Case" 
},
{
 "dates": 365,
"data": 1686.9,
"group": "Best Case" 
} 
]
  
      var data = d3.nest()
        .key(function(d){
          return opts.group === undefined ? 'main' : d[opts.group]
        })
        .entries(data)
      
      nv.addGraph(function() {
        var chart = nv.models[opts.type]()
          .x(function(d) { return d[opts.x] })
          .y(function(d) { return d[opts.y] })
          .width(opts.width)
          .height(opts.height)
         
        
          
        

        
        
        
      
       d3.select("#" + opts.id)
        .append('svg')
        .datum(data)
        .transition().duration(500)
        .call(chart);

       nv.utils.windowResize(chart.update);
       return chart;
      });
    };
</script>


#### Monthly Forecasts

The following table represents monthly forecasts, and Good, Bad, Best and Worst case scenarios.

<table class="table table-striped"><thead><tr><th> Month </th><th> Mean </th><th> Best Case </th><th> Good Case </th><th> Bad Case </th><th> Worst Case </th></tr></thead><tr><td> January </td><td> 46015 </td><td> 47200 </td><td> 47171 </td><td> 47200 </td><td> 47171 </td></tr><tr><td> February </td><td> 47589 </td><td> 48775 </td><td> 48746 </td><td> 48775 </td><td> 48746 </td></tr><tr><td> March </td><td> 48630 </td><td> 49816 </td><td> 49787 </td><td> 49816 </td><td> 49787 </td></tr><tr><td> April </td><td> 48943 </td><td> 50129 </td><td> 50100 </td><td> 50129 </td><td> 50100 </td></tr><tr><td> May </td><td> 48524 </td><td> 49710 </td><td> 49681 </td><td> 49710 </td><td> 49681 </td></tr><tr><td> June </td><td> 47563 </td><td> 48748 </td><td> 48719 </td><td> 48748 </td><td> 48719 </td></tr><tr><td> July </td><td> 46389 </td><td> 47574 </td><td> 47545 </td><td> 47574 </td><td> 47545 </td></tr><tr><td> August </td><td> 45389 </td><td> 46575 </td><td> 46546 </td><td> 46575 </td><td> 46546 </td></tr><tr><td> September </td><td> 44905 </td><td> 46090 </td><td> 46061 </td><td> 46090 </td><td> 46061 </td></tr><tr><td> October </td><td> 45141 </td><td> 46327 </td><td> 46298 </td><td> 46327 </td><td> 46298 </td></tr><tr><td> November </td><td> 46115 </td><td> 47301 </td><td> 47272 </td><td> 47301 </td><td> 47272 </td></tr><tr><td> December </td><td> 47650 </td><td> 48835 </td><td> 48806 </td><td> 48835 </td><td> 48806 </td></tr></table>


#### Year End Summary

The following table represents a year end summary of Revenue, along with Good, Bad, Best and Worst case scenarios.

<table class="table table-striped"><thead><tr><th> Year </th><th> Mean </th><th> Best Case </th><th> Good Case </th><th> Bad Case </th><th> Worst Case </th></tr></thead><tr><td> year </td><td> 562853 </td><td> 577080 </td><td> 576731 </td><td> 577080 </td><td> 576731 </td></tr></table>


</div>
</div>
</div>
