
<html>
<head>
<meta charset="utf-8"> 
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black">
<style type="text/css">
h1 { display:none; }
body {
/* 加载背景图 */
background-image: url();
/* 背景图垂直、水平均居中 */
background-position: center center;
/* 背景图不平铺 */
background-repeat: no-repeat;
/* 当内容高度大于图片高度时，背景图像的位置相对于viewport固定 */
background-attachment: fixed;
/* 让背景图基于容器大小伸缩 */
background-size: cover;
/* 设置背景颜色，背景图加载过程中会显示背景色 */
background-color: #7ba0f1;
}
	#box{
		width:340px;
		height:185px;
		border:1px solid black;
		position:relative;
		overflow:hidden;
margin:0 auto;
	}
div.ex
{
background-color: #f4ea00;
width:auto;
padding:5px;
border:5px solid gray;
margin:0px;
}

body{ text-align:center} 
div.cd {border-radius: 10px;
border: #e9e9e9 solid 1px;
width:90%;
	height:60px;
margin:0 auto;
border-radius: 5px;
   }
div.sm {border-radius: 10px;
border: #e9e9e9 solid 1px;
width:70px;
	height:70px;
margin:0 auto;
border-radius: 50%;
   overflow:hidden;}

div.mc {border-radius: 10px;
border:  #c2afd0 solid 1px;
width:80px;
	height:20px;
margin:0 auto;
border-radius: 35px;
   overflow:hidden;}

div.s {border-radius: 10px;
border: #e9e9e9 solid 1px;
width:200px;
	height:20px;
margin:0 auto;
border-radius: 35px;
   overflow:hidden;}
 .thumbnail
{
	float:left;	
margin:5px;
}
div.cz {border-radius: 10px;
border: #e9e9e9 solid 1px;
width:89%;
	height:60px;
margin:0 auto;
border-radius: 5px;
   }
div.tp {border-radius: 10px;
width:90%;
	height:auto;
margin:0 auto;
border-radius: 5px;
   }
div.sz {border-radius: 10px;
border: #e9e9e9 solid 1px;
width:200px;
	height:20px;
margin:0 auto;
border-radius: 35px;
   }
div.fd
{
	float:left;
	width:320px;
	height:175px;
	margin:5px;
border: #e9e9e9 solid 1px;
border-radius: 10px;
    padding: 5px; 
overflow:hidden;
}
div.CC
{
	float:left;
	width:29%;
	height:50px;
	line-height:50px; 
border:blue solid 1px;
border-radius: 10px;
    padding: 1px; 
overflow:hidden;
margin:5px; 
}
div.CD
{
	float:left;
	width:45%;
	height:50px;
	line-height:50px; 
border:blue solid 1px;
border-radius: 10px;
    padding: 1px; 
overflow:hidden;
margin:5px; 
}
.text_line
{
	clear:both;
	margin-bottom:0px;
}
	#red{
		background-image: url(https://i.loli.net/2019/07/27/5d3c170ee773143216.jpg);
		width:340px;
	}
	#green{
		background-image: url(https://i.loli.net/2019/07/27/5d3c170e622fd23976.jpg);
		width:340px;
	}
	#blue{
		background-image: url(https://i.loli.net/2019/07/27/5d3c170f4d0e255749.jpg);
		width:340px;
	}
	.slide{
		width:340px;
		height:185px;
		position:absolute;
	}


p.date {text-align: justify; color:#ffffff; font-size:14px;}
h3  {text-align: center; color:#ffffff; font-size:20px;}
h2  {text-align: center; color: #ffffff; font-size:20px;}
p.cc  {text-align: center; color:#ffffff; font-size:15px;}

a {
color: #0508b9;
text-decoration: none;
}
a:active {
text-decoration: none;
color: #001997;
}

a:link {text-decoration:none;}
a:visited {text-decoration:none;}
a:hover {text-decoration:none;}
a:active {text-decoration:none;}

</style>
<script type="text/javascript">
	onload=function(){
		var arr = document.getElementsByClassName("slide");
		for(var i=0;i<arr.length;i++){
			arr[i].style.left = i*340+"px";
		}
	}
	function LeftMove(){
		var arr = document.getElementsByClassName("slide");//获取三个子div
		for(var i=0;i<arr.length;i++){
			var left = parseFloat(arr[i].style.left);
			left-=2;
			var width = 340;//图片的宽度
			if(left<=-width){
				left=(arr.length-1)*width;//当图片完全走出显示框，拼接到末尾
				clearInterval(moveId);
			}
			arr[i].style.left = left+"px";
		}
	}
	function divInterval(){
		moveId=setInterval(LeftMove,10);//设置一个10毫秒定时器
	}
	
	
	timeId=setInterval(divInterval,3000);//设置一个3秒的定时器。
	
	function stop(){
		clearInterval(timeId);
	}
	function start(){
		clearInterval(timeId);
		timeId=setInterval(divInterval,3000);
	}
	
	//页面失去焦点停止
	onblur = function(){
		stop();
	}
	//页面获取焦点时开始
	onfocus = function(){
		start();
	}
</script>
</head>
<body>
<div  class="sm" style="background-color: #7fc4e5"> <img src="https://i.loli.net/2019/07/27/5d3c317ee785b81349.jpg" alt="Computer man" width="70" height="70"> </div>
<div  class="mc" style="background-color:  #7ba0f1"> <p class="cc">木子科技</p></div>
<p class="text_line"> </p>

	<a href="/JJ.html" target="_blank"><div id="box" onmouseover="stop()" onmouseout="start()">
		<div id="red" class="slide"></div>
		<div id="green" class="slide"></div>
		<div id="blue" class="slide"></div>
	</div></a>

<p class="text_line"> </p>
<div  class="cz"><a href="/JJ.html" target="_blank"><div  class="CC" style="background-color: #f3a073"><p class="cc">
⌘ 下载捷径</p>
</div></a><a href="/guanyu.html" target="_blank"><div  class="CC" style="background-color: #335bd6"><p class="cc">
𝓲 关于捷径</p>
</div></a>
<a href="/LX.html" target="_blank"><div  class="CC" style="background-color: #2fe1cb"><p class="cc">
✆联系我们</p>
</div></a>
</div>
<p class="text_line"> </p>
<div  class="tp"><img class="thumbnail" src="https://i.loli.net/2019/07/27/5d3c40e2f0e9124271.jpg" width="46%" height="80" alt="Planets" usemap="#1">

<map name="1">
  <area shape="rect" coords="280,142,310,173" alt="下载" href="https://www.icloud.com/shortcuts/d13f35eaee30421ab2e781cb0c8cd493"></map>
<img class="thumbnail" src="https://i.loli.net/2019/07/27/5d3c40efd06ab98419.jpg" width="46%" height="80" alt="Planets" usemap="#2">

<map name="2">
  <area shape="rect" coords="280,142,310,173" alt="下载" href="https://www.icloud.com/shortcuts/c4bc0fed9a054e6db76976e505ff38dc">
</map></div>
<p class="text_line"> </p>
<div  class="tp"> <a href="/JJ.html">
<img  border="0" src="https://i.loli.net/2019/07/27/5d3c4b6e4773234939.jpg" alt="快捷指令" width="100%" height="auto"></a></div>

<div  class="cz"><a href="https://weibo.com/u/5090561214" target="_blank"><div  class="CD" style="background-color: #f4b300"><p class="cc">
𝕯 关注微博</p>
</div></a><a href="http://v.douyin.com/S7wDt2/" target="_blank"><div  class="CD" style="background-color: #04020c"><p class="cc">
♪ 关注抖音</p>
</div></a></div>
<p class="text_line"> </p>
<div class="ex">
<h2>【温馨提示】</h2>
<p class="cc"><a href="mailto:56794501@qq.com">&nbsp;商务合作</a>|<a href="https://jiejinghe.com/" target="_blank">捷径盒</a> </p>
<p>如果本站内容存在侵权，请提供相关专利证书<a href="mailto:56794501@qq.com">致信给我们</a>或者<a target="_blank" href="http://wpa.qq.com/msgrd?v=3&uin=56794501&site=qq&menu=yes"><img border="0" src="http://wpa.qq.com/pa?p=2:56794501:51" alt="联系客服💁🏻‍♂️" title="联系客服💁🏻‍♂️"/></a>我们将在5个工作日之内进行处理，若未致信我们将视为默认授权，我们将不承担任何法律责任.</p>
</div>

<p class="text_line"> </p>

<p class="cc">感谢访问本站好用记得收藏</p>
<div  class="s" style="background-color: #7ba0f1"><p class="cc">
木子科技唯一官方网站</p></div><p class="cc">版权所有©️木子科技(2019-2028)</p>

