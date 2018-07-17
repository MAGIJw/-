<html>
<head>
<style type="text/css">
#header{
  font-family:SimHei,Microsoft YaHei;
　width:360px;
　height:80px;
　text-align:center;
　line-height:80px;
　font-size:15px;
　color:black;
　background-color:black;
}
#body{
　text-align:center;
　line-height:280px;
  width: 300px;
  height: 300px;
　font-size:15px;
　font-family:SimHei,Microsoft YaHei;
　background-color:black;
}
.tab {
    font-family:SimHei,Microsoft YaHei;
    overflow: hidden;
    border: 2px solid 	#000000;
    background-color: black;
    text-shadow:2px 2px 4px #FFFFFF;
}
.tab button {
    font-family:SimHei,Microsoft YaHei;
    float: left;
    border:#33FFFF;
    outline: none;
    cursor: pointer;
    padding: 12px 14px;
    transition: 0.3s;
    font-size: 17px;
    color:#000000;
  text-shadow:2px 2px 5px #FFFFFF;
}
.tab button:hover {
    background-color:#FFB3FF;
}
.tab button.active {
    background-color:	#FF00FF;
}
.tabcontent {
    display: none;
    padding: 8px 12px;
    text-shadow:2px 2px 5px ;
    background-color:black;
    font-family:SimHei,Microsoft YaHei;
}
table.blueTable {
  border: 4px solid #FEFFFC;
  background-color: #FAFFE7;
  height:450px;
}
table.blueTable td, table.blueTable th {
  border: 3px solid #F9F9F3;
  padding: 10px 10px;
}
table.blueTable tbody td {
  font-size: 26px;
}
table.blueTable td:nth-child(even) {
  background: #D0E4F5;
}
</style>
</head>
<body>
<div id="Body"> </div>
<div class="tab">
  <button class="tablinks" onclick="openCity(event, '字母&發音')">字母&發音</button>
</div>

<div id="字母&發音" class="tabcontent">
  <h3>韓語字母包括14個基本輔音和10個基本元音，以一個輔音和一個元音组合成一個音節</h3>
<table class="blueTable">
<tbody>
<tr>
<td>ㅏ<br>a</td>
<td>ㅐ ae</td>
<td>ㅑ ya</td>
<td>ㅒ yae</td>
<td>ㅓ eo</td>
<td>ㅔ e</td>
<td>ㅕ yeo</td>
<td>ㅖ ye</td>
<td>ㅗ<br>o</td>
<td>ᅪ wa</td>

</tr>
<tr>
<td>ㅚ<br>oe</td>
<td>ㅛ yo</td>
<td>ㅜ u</td>
<td>ㅝ wo</td>
<td>ㅞ we</td>
<td>ㅟ wi</td>
<td>ㅠ<br>yu</td>
<td>ㅡ eu</td>
<td>ㅢ ui</td>
<td>ㅣ<br>i</td>

</tr>
<tr>
<td>ㅙ wae</td>
<td>ㄱ g/k</td>
<td>ㄲ kk</td>
<td>ㄴ n</td>
<td>ㄷ d/t</td>
<td>ㄸ tt</td>
<td>ㄹ l/r</td>
<td>ㅁ m</td>
<td>ㅂ p/b</td>
<td>ㅃ pp</td>
</tr>

<tr>
<td>ㅅ     s</td>
<td>ㅆ ss</td>
<td>ㅇ ng</td>
<td>ㅈ j</td>
<td>ㅉ jj</td>
<td>ㅊ ch</td>
<td>ㅋ k</td>
<td>ㅌ t</td>
<td>ㅍ p</td>
<td>ㅎ h</td>
</tr>

</tbody>
</table> 
</div>


<script>
function openCity(evt, cityName) {
    var i, tabcontent, tablinks;
    tabcontent = document.getElementsByClassName("tabcontent");
    for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
    }
    tablinks = document.getElementsByClassName("tablinks");
    for (i = 0; i < tablinks.length; i++) {
        tablinks[i].className = tablinks[i].className.replace(" active", "");
    }
    document.getElementById(cityName).style.display = "block";
    evt.currentTarget.className += " active";
}
</script>
     
</body>
