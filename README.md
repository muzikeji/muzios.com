
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
    background-color: #42dbbc;
}

@media only screen and (max-width: 500px) {
    body {
        background-color: #e9c89b;
    }
}

div.x
{
	background:url(https://ae01.alicdn.com/kf/Ha9e1b15964ed4844850be91f302ad7e2w.png);
	background-size:100% 100%;
	background-repeat:no-repeat;
  width:100%;
    height:170px;
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
border: #906326 solid 1px;
width:90%;
	height:60px;
margin:0 auto;
border-radius: 5px;
   }
div.tp {border-radius: 10px;
width:95%;
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
h2  {text-align: center; color:#ffffff; font-size:20px;}
p.cc  {text-align: center; color:#ffffff; font-size:15px;}
p.c  {text-align: center; color: #4ae414; font-size:35px;}
p.cd  {text-align: justify; color:#ffffff; }
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
div,ul,span,li {
                 margin: 0;    padding: 1px; 
            }

            .nav {
                width: 100%;
       background-color: rgba(0,0,0,0.5);
                height: 30px;
            }
            .nav ul li {
                float: left;
                list-style-type: none;
                width: 70px;
            }
            .nav ul li a {
                color: #fff;
                text-decoration: none;
                display: block;
            }
            .nav ul li a:hover {
                color: #fff;
                background-color: #45abc1;
            }
            .nav li {
                line-height: 30px;
                text-align: justify;
            }
            .nav ul li span{
                display: none;
                text-decoration: none;
                position: absolute;
                width: 70px;
            }
            .nav span ul li a{
                background-color: #b3addb;
            }
            .nav ul li:hover span {
                display: block;
                text-decoration: none;
            }
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

<a href="https://jiejinghe.com/users/6563404841"><div  class="x">
 <div id="sunav" class="nav">
            <ul>
            <li class="sunav"><a href="#"> <b>☰ </b></a>
                <span>
                <ul>
                    <li><a href="/JJ.html">下载捷径</a></li>
                    <li><a href="https://jiejinghe.com/search">搜索捷径</a></li>
                    <li><a href="/guanyu.html">关于捷径</a></li>
  <li><a href="/LX.html">联系我们</a></li>
                </ul>
                </span>
            </li>
       </ul>
        </div>
<p class="text_line"> </p>
<p class="text_line"> </p>
<p class="c"><b>木子科技</b></p>
<p class="text_line"> </p>
<p class="text_line"> </p>
<p class="cc"><b>越接近，越完美；用捷径，更轻松！</b></p><p class="text_line"> </p>

</div></a>

<p class="text_line"> </p>
<p class="text_line"> </p>

	<a href="/JJ.html" target="_blank"><div id="box" onmouseover="stop()" onmouseout="start()">
		<div id="red" class="slide"></div>
		<div id="green" class="slide"></div>
		<div id="blue" class="slide"></div>
	</div></a>

<p class="text_line"> </p>

<div  class="tp"><a href="https://www.icloud.com/shortcuts/d13f35eaee30421ab2e781cb0c8cd493"><img class="thumbnail" src="https://ae01.alicdn.com/kf/H52d01364e8fd4a6c8bab517078d47b3de.jpeg" width="46%" height="80" ><a>
<a href="https://www.icloud.com/shortcuts/c4bc0fed9a054e6db76976e505ff38dc"><img class="thumbnail" src="https://ae01.alicdn.com/kf/Hc6f126b58f94406e901d7d79fb4229f5R.png" width="46%" height="80" ><a>
<p class="text_line"> </p>

<a href="/JJ.html">
<img class="thumbnail" src="https://ae01.alicdn.com/kf/H38a948bc9a6a447eb746c2d0111703781.png" alt="快捷指令" width="150px" height="86px"></a>
<a href="/JJ.html">
<img class="thumbnail" src="https://ae01.alicdn.com/kf/Hdc1e7ef25ade4734889d24a94dd56fe9G.jpeg" alt="快捷指令" width="150px" height="86px"></a>
<a href="/JJ.html">
<img class="thumbnail" src="https://ae01.alicdn.com/kf/Hd642943752d9412a8ab016bb62406256f.png" alt="快捷指令" width="150px" height="86px"></a>
<a href="/JJ.html">
<img class="thumbnail" src="https://ae01.alicdn.com/kf/Hc56d45c5f865427d91e84562f26e3c98d.png" alt="快捷指令" width="150px" height="86px"></a>
<a href="/JJ.html">
<img class="thumbnail" src="https://ae01.alicdn.com/kf/Hd2e7cf0941e9404fa19d584c9bdd1b5bN.png" alt="快捷指令" width="150px" height="86px"></a>
<a href="/JJ.html">
<img class="thumbnail" src="https://ae01.alicdn.com/kf/Hdf80d780315741d29e035ed3f7f9b636Z.jpeg" alt="快捷指令" width="150px" height="86px"></a>
<a href="/JJ.html">
<img class="thumbnail" src="https://ae01.alicdn.com/kf/He3b8bb526cc648658e617210c09ccda1E.png" alt="快捷指令" width="150px" height="86px"></a>
<a href="/JJ.html">
<img class="thumbnail" src="https://ae01.alicdn.com/kf/H7be5df09cd124b05b72f07b93a71424e4.png" alt="快捷指令" width="150px" height="86px"></a>
<a href="/JJ.html">
<img class="thumbnail" src="https://ae01.alicdn.com/kf/He40012c871de4ebdb843c6bc634643e2U.png" alt="快捷指令" width="150px" height="86px"></a>
<a href="/JJ.html">
<img class="thumbnail" src="https://ae01.alicdn.com/kf/Hfedc1bdbfe7e4d86bfd20afb3cb1eb89G.png" alt="快捷指令" width="150px" height="86px"></a><p class="text_line"> 
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
<a href="https://s7.addthis.com/static/wechat_follow.html?id=Miss-baby_&u=https://u.wechat.com/MIDWVwUtuk6_gUB48_Fy41U">
<img  class="thumbnail 1"  src="https://ae01.alicdn.com/kf/H6ab49d692360416199684aadf1b64023E.png" alt="木子李" width="30" height="auto"></a>

<a href="mqq://im/chat?chat_type=wpa&uin=56794501&version=1&src_type=web">
<img  class="thumbnail 1"  src="https://ae01.alicdn.com/kf/H8db64cccea0a4ee3bf88ebf242b21d2es.png" alt="木子李" width="30" height="auto"></a>

<a href="https://ae01.alicdn.com/kf/H92b91557d9264af682723e9369a426b0p.png">
<img  class="thumbnail 1"  src="https://ae01.alicdn.com/kf/Ha3ee2ed657c34d68a0bb7fb65bdd89caF.png" alt="木子李" width="30" height="auto"></a>

<a href="https://jq.qq.com/?_wv=1027&k=5wclJSO">
<img  class="thumbnail 1"  src="https://ae01.alicdn.com/kf/H294277aebe3a45338b6d8b7fa5ee79ecT.png" alt="木子李" width="30" height="auto"></a>

<a href="https://weibo.com/u/5090561214">
<img  class="thumbnail 1"  src="https://ae01.alicdn.com/kf/H6308a6002fe64acdb5ca92ad99bce84fy.png" alt="木子李" width="30" height="auto"></a>

<a href="mailto: 56794501@qq.com">
<img  class="thumbnail 1"  src="https://ae01.alicdn.com/kf/Hf60141ed2e4249389a38ba8a38ad1fefS.png" alt="木子李" width="30" height="auto"></a>

<a href="http://v.douyin.com/kkpWm9/">
<img  class="thumbnail 1"  src="https://ae01.alicdn.com/kf/H3d53a50f12af40cda87601096b153325z.jpeg" alt="木子李" width="30" height="auto"></a>

<p class="text_line"> </p>
<p class="cc">感谢访问本站好用记得收藏</p>
<div  class="s" style="background-color: #7ba0f1"><p class="cc">
木子科技唯一官方网站</p></div><p class="cc">版权所有©️木子科技(2019-2028)</p>

<p class="text_line"> </p>
<script type="text/javascript" src="//js.users.51.la/20228817.js"></script>
<script type="text/javascript" src="//quote.51.la/q?id=20228817&mb=4"></script>
