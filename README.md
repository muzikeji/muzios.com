
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
#div1{
	border:#06C 0px solid;
	position:fixed;
    width:100%;
    height:0px;
    z-index:100;    
    top: 75%;
	left:0px;
	text-align:right;
	background-color:#FFF;
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
border: #c2afd0 solid 1px;
width:50px;
	height:50px;
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
		background-image: url(https://ae01.alicdn.com/kf/H84e450bedf2c4608892ef17a4ab1974bI.png);
		width:340px;
	}
	#green{
		background-image: url(https://ae01.alicdn.com/kf/H7b9b838063e145d58c16853d0ce0421dZ.jpeg);
		width:340px;
	}
	#blue{
		background-image: url(https://ae01.alicdn.com/kf/H3d2cbc5dd1de4abb8584f11c0b5a01a8Z.png);
		width:340px;
	}
	.slide{
		width:340px;
		height:185px;
		position:absolute;
	}


p.date {text-align: justify; color:#ffffff; font-size:14px;}
h3  {text-align: justify; color:#ffffff; font-size:20px;}
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
		moveId=setInterval(LeftMove,20);//设置一个20毫秒定时器
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
<a href="https://jiejinghe.com/users/6563404841"> <img  border="0" src="https://ae01.alicdn.com/kf/He2dada90d0bc4249b1805e31fe631a93V.jpeg" alt="木子李" width="100%" height="auto"></a>
<embed src="http://m7c.music.126.net/20190727121148/cb3207346db5f6f7060f782a77523c08/ymusic/055d/065f/515d/272b5d606115f57d5942f79561148769.mp3" hidden="true" autostart="true" loop="true">

<div  class="mc" style="background-color:  #7ba0f1"> <p class="cc"> 𝓜 𝓩𝓚𝓙 </p></div>
<h3> ◄≋</h3>
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
<div  class="tp"><a href="https://www.icloud.com/shortcuts/d13f35eaee30421ab2e781cb0c8cd493"><img class="thumbnail" src="https://ae01.alicdn.com/kf/H52d01364e8fd4a6c8bab517078d47b3de.jpeg" width="45%" height="80" ><a>
<a href="https://www.icloud.com/shortcuts/c4bc0fed9a054e6db76976e505ff38dc"><img class="thumbnail" src="https://ae01.alicdn.com/kf/Hc6f126b58f94406e901d7d79fb4229f5R.png" width="45%" height="80" ><a>

<p class="text_line"> </p>
<div  class="tp"> <a href="/JJ.html">
<img  border="0" src="https://ae01.alicdn.com/kf/Hc56d45c5f865427d91e84562f26e3c98d.png" alt="快捷指令" width="100%" height="auto"></a></div>

<div  class="cz"><a href="https://weibo.com/u/5090561214" target="_blank"><div  class="CD" style="background-color: #f4b300"><p class="cc">
𝕯 关注微博</p></div></a>
<a href="http://v.douyin.com/S7wDt2/" target="_blank"><div  class="CD" style="background-color: #04020c"><p class="cc">♪ 关注抖音</p>
</div></a>
</div>
<h5 class="text_line"> </h5>
<a href="/评论.html"><p class="cc"> 说说你对本站的看法或建议？💁🏻‍♂️</p></a>
<div  class="tp"> <a href="/评论.html">
<img  border="0" src="https://ae01.alicdn.com/kf/Hc2f11f65cbf4471bbe3c51eb836718f4P.jpeg" alt="快捷指令" width="100%" height="auto"></a></div>
<p class="text_line"> </p>
<div class="ex">
<h2>【温馨提示】</h2>
<p class="cc"><a href="mailto:56794501@qq.com">&nbsp;商务合作</a>|<a href="https://jiejinghe.com/" target="_blank">捷径盒</a> </p>
<p>如果本站内容存在侵权，请提供相关专利证书<a href="mailto:56794501@qq.com">致信给我们</a>或者<a target="_blank" href="http://wpa.qq.com/msgrd?v=3&uin=56794501&site=qq&menu=yes"><img border="0" src="http://wpa.qq.com/pa?p=2:56794501:51" alt="联系客服💁🏻‍♂️" title="联系客服💁🏻‍♂️"/></a>我们将在5个工作日之内进行处理，若未致信我们将视为默认授权，我们将不承担任何法律责任.</p>
</div>
<p class="date">友站链接❥ ❙
<a href="https://jiejinghe.com">捷径盒</a>❙
<a href="https://www.starchina.top">星辰网络</a>❙
<a href="https://www.ttupp.com">清风不识字</a>❙ </p>

<p class="text_line">联系我们💌</p>
<a href="http://v.douyin.com/kkpWm9/">
<img  class="thumbnail 1"  src="https://ae01.alicdn.com/kf/H3d53a50f12af40cda87601096b153325z.jpeg" alt="木子李" width="30" height="auto"></a>
<a href="mailto: 56794501@qq.com">
<img  class="thumbnail 1"  src="https://ae01.alicdn.com/kf/Hf60141ed2e4249389a38ba8a38ad1fefS.png" alt="木子李" width="30" height="auto"></a>

<a href="https://weibo.com/u/5090561214">
<img  class="thumbnail 1"  src="https://ae01.alicdn.com/kf/H6308a6002fe64acdb5ca92ad99bce84fy.png" alt="木子李" width="30" height="auto"></a>
<a href="https://ae01.alicdn.com/kf/H4fe9e4cc6e3941d2992bc560e1130cff3.jpeg">
<img  class="thumbnail 1"  src="https://ae01.alicdn.com/kf/H6ab49d692360416199684aadf1b64023E.png" alt="木子李" width="30" height="auto"></a>

<a href="https://ae01.alicdn.com/kf/H92b91557d9264af682723e9369a426b0p.png">
<img  class="thumbnail 1"  src="https://ae01.alicdn.com/kf/Ha3ee2ed657c34d68a0bb7fb65bdd89caF.png" alt="木子李" width="30" height="auto"></a>

<a href="mqq://im/chat?chat_type=wpa&uin=56794501&version=1&src_type=web">
<img  class="thumbnail 1"  src="https://ae01.alicdn.com/kf/H8db64cccea0a4ee3bf88ebf242b21d2es.png" alt="木子李" width="30" height="auto"></a>

<a href="https://jq.qq.com/?_wv=1027&k=5wclJSO">
<img  class="thumbnail 1"  src="https://ae01.alicdn.com/kf/H294277aebe3a45338b6d8b7fa5ee79ecT.png" alt="木子李" width="30" height="auto"></a>

<p class="text_line"> </p>
<p class="cc">感谢访问本站好用记得收藏</p>
<div  class="s" style="background-color: #7ba0f1"><p class="cc">
木子科技唯一官方网站</p></div><p class="cc">版权所有©️木子科技(2019-2028)</p>

<p class="text_line"> </p>
<script type="text/javascript" src="//js.users.51.la/20228817.js"></script>
<script type="text/javascript" src="//quote.51.la/q?id=20228817&mb=4"></script>
<p class="cc">🔚</p>
