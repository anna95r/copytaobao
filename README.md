# copytaobao
copy taobao.com
<!DOCTYPE html>
<html>
<head>
	<title>淘宝网 - 淘！我喜欢</title>
	<meta charset="utf-8">
	<style type="text/css">
		body{
			font-size: 12px;
			margin: 0;
			padding: 0;
			background-color: #f5f5f5;
		}
		a{
			text-decoration: none;
			color: #000000;
		}
		img{
			width: 100%;
			height: 100%;
		}
		ul{
			list-style: none;
			margin: 3px;
			padding: 0px;
			height: 35px;
			text-align: center;
		}
		ul>li{
			float: left;
			margin: 0 5px;
		}
		/*顶部导航*/
		#top{
			width: 1349px;
			height: 36px;
			background-color: #f5f5f5;
		}
		#blank{
			margin: 0 79.5px;
			clear: both;
			width: 1190px;
			height: 35px;
		}
		#top-left{
			float: left;
		}
		#top-right{
			float: right;
		}
		#login{
			color: #dc143c;
		}
		.changecolor:hover{
			color: #ff0000;
		}
		.top-menu{
			float: left; 
			padding: 6px 0 0 0;
		}
		.drop-down-menu-where{
			display: inline-block;
			padding: 0 6px;
			height: 29px;
		}
		.drop-down-menu-content-where{
			display: none;
			position: absolute;
			background-color: #ffffff;
			width: 70px;
			max-height: 150px;
			overflow: scroll;
			overflow-x: hidden;
			text-align: left;
			top: 35px;
		}
		.drop-down-menu-where:hover .drop-down-menu-content-where{
			display: block;
		}
		.drop-down-menu-content-where a{
			display: block;
			padding: 6px 0;
		}
		.drop-down-menu-content-where a:hover{
			background-color: #f5f5f5;
		}
		.drop-down-menu{
			display: inline-block;
			padding: 0 6px;
			height: 29px;
		}
		.drop-down-menu-content{
			display: none;
			position: absolute;
			background-color: #ffffff;
			width: 90px;
			text-align: left;
			top: 35px;
		}
		.drop-down-menu:hover .drop-down-menu-content{
			display: block;
		}
		.drop-down-menu-content a{
			display: block;
			padding: 6px 0;
		}
		.drop-down-menu-content a:hover{
			background-color: #f5f5f5;
		}
		#web-nav-menu-content{
			display: none;
			position: absolute;
			background-color: #ffffff;
			width: 1190px;
			text-align: left;
			top: 35px;
			left: 200px;
		}
		.drop-down-menu:hover #web-nav-menu-content{
			display: block;
		}
		#web-nav-menu-content a{
			display: block;
			padding: 6px;
			border-radius: 5px;
		}
		.webnav{
			border: 1px solid #f5f5f5;
			float: left;
			padding: 20px;
			height: 350px;
		}
		td>a{
			margin: 0 10px;
		}
		#mainmark h2{
			color: #ff0000;
		}
		#mainmark a:hover{
			background-color: #ff0000;
		}
		#chrmark h2{
			color: #32cd32;
		}
		#chrmark a:hover{
			background-color: #32cd32;
		}
		#aliapp h2{
			color: #9932cc;
		}
		#aliapp a:hover{
			background-color: #9932cc;
		}
		#recommend h2{
			color: #6495ed;
		}
		#recommend a:hover{
			background-color: #6495ed;
		}
		/*body顶部*/
		#bodytop{
			position: absolute;
			top: 36px;
			width: 1349px;
			height: 121px;
			background-color: #ffffff;
		}
		#body-top{
			width: 1190px;
			height: 97px;
			margin: 24px 79.5px 0 79.5px;
		}
		/*logo*/
		#logo{
			width: 190px;
			height: 88px;
			float: left;
		}
		/*搜索栏*/
		#search{
			width: 700px;
			height: 87px;
			float: left;
			margin: 0 70px;
		}
		#search ul{
			height: 22px;
			margin-bottom: 0;
		}
		#baobei{
			background-color: #ff8c00;
			color: #ffffff;
			width: 36px;
			height: 22px;
			border: none;
			margin: 0 0 0 4px;
			padding: 0;
			cursor: pointer;
			border-radius: 5px 5px 0 0;
			margin-left: 15px;
		}
		#tianmao, #dianpu{
			background-color: #ffffff;
			color: #ff8c00;
			width: 36px;
			height: 22px;
			border: none;
			margin: 0 0 0 4px;
			padding: 0;
			cursor: pointer;
			border-radius: 5px 5px 0 0;
		}
		#tianmao:focus{
			background-color: #ff8c00;
			color: #ffffff;
		}
		#tianmao:focus #baobei{
			background-color: #ffffff;
			color: #ff8c00;
		}
		#dianpu:focus{
			background-color: #ff8c00;
			color: #ffffff;
		}
		#dianpu:focus #baobei{
			background-color: #ffffff;
			color: #ff8c00;
		}
		/*搜索栏*/
		#search1{
			width: 530px;
			height: 36px;
			border: 2px solid #ff8c00;
			border-right: none;
			border-radius: 20px 0 0 20px;
			float: left;
			padding: 0;
			overflow: hidden;
			margin-bottom: 5px;
		}
		#camera{
			width: 24px;
			height: 36px;
			border: 2px solid #ff8c00;
			border-left: none;
			border-right: none;
			float: left;
			margin-bottom: 5px;
		}
		#searchbtn{
			width: 74px;
			height: 40px;
			border: 2px solid #ff8c00;
			color: #ffffff;
			background-color: #ff8c00;
			border-radius: 0 20px 20px 0;
			float: left;
			margin-bottom: 5px;
			padding: 0;
			cursor: pointer;
		}
		/*二维码*/
		#qr{
			width: 79px;
			height: 90px;
			float: left;
		}
		#close{
			position: absolute;
			border: 1px solid #f5f5f5;
			color: #f5f5f5;
			left: 1094px;
			top: 60px;
			width: 16px;
			text-align: center;
			cursor: pointer;
			z-index: -1;
		}
		#qrcode{
			float: left;
			border: 1px solid #f5f5f5;
			padding: 5px;
		}
		#qrcode p{
			color: #ff8c00;
			text-align: center;
			margin: 0;
			padding: 0;
		}
		#qrcode img{
			width: 62px;
			height: 62px;
		}
		/*导航栏*/
		#navbar1{
			position: absolute;
			top: 157px;
			background-color: #ff9000;
			color: #ffffff;
			width: 1349px;
			height: 30px;
		}
		#navbar2{
			margin: 0 79.5px;
		}
		#navbar2 h2{
			float: left;
			background-color: #ff5000;
			margin: 0;
			width: 190px;
			height: 30px;
			text-align: center;
		}
		#navbar2 ul{
			float: left;
			margin: 0px;
			height: 30px;
		}
		#navbar2 a{
			color: #ffffff;
		}
		#navbar2 li{
			padding: 4px;
			margin: 0 3px;
			font-size: 16px;
		}
		/*主体*/
		#main{
			position: absolute;
			top: 187px;
			width: 1190px;
			height: 632px;
			margin: 0 79.5px;
		}
		#classify-all{
			width: 188px;
			height: 520px;
			border: 1px solid #ff5000;
		}
		#classify{
			width: 188px;
			height: 513px;
			padding: 5px 0 3px 0;
			margin: 0;
			text-align: left;
		}
		.nav{
			width: 153px;
			height: 32px;
			padding: 0 19px 0 17px;
			margin: 0;
			font-size: 14px;
			line-height: 32px;
			float: left;
		}
		#classify i{
			float: right;
			font-style: normal;
			display: inline-block;
			margin: 0;
		}
		.nav-content{
			width: 700px;
			height: 522px;
			display: none;
			position: absolute;
			left: 269.5px;
			top: 187px;
		}
		.nav:hover{
			background-color: #ffe4e1;
			color: #ff0000;
		}
		.nav:hover .nav-a{
			color: #ff0000;
		}
		.nav-a:hover{
			text-decoration: underline;
		}
		.nav:hover .nav-content{
			display: block;
			float: left;
			background-color: #ffe4e1;
		}
	</style>
</head>
<body>
	<header>
		<div id="top">
			<!--顶端-->
			<div id="blank">
				<ul id="top-left">
					<!--登陆-->
					<li class="top-menu">
						<div class="drop-down-menu-where">
							<!--地区-->
							<span>中国大陆</span>
							<span>ˇ</span>
							<div class="drop-down-menu-content-where">
								<a href="">全球</a>
								<a href="">中国大陆</a>
								<a href="">香港</a>
								<a href="">台湾</a>
								<a href="">澳门</a>
								<a href="">韩国</a>
								<a href="">马来西亚</a>
								<a href="">澳大利亚</a>
								<a href="">新加坡</a>
								<a href="">新西兰</a>
								<a href="">加拿大</a>
								<a href="">美国</a>
								<a href="">日本</a>
							</div>
						</div>
					</li>
					<li class="top-menu">
						<div class="drop-down-menu">
							<a href="" id="login">亲，请登录</a>
							<a href="" class="changecolor">免费注册</a>
						</div>
					</li>
					<li class="top-menu">
						<div class="drop-down-menu">
							<a href="" class="changecolor">手机逛淘宝</a>
						</div>
					</li>
				</ul>
				<ul id="top-right">
					<!--右-->
					<li class="top-menu">
						<div class="drop-down-menu">
							<a href="" class="changecolor">我的淘宝</a>
							<span>ˇ</span>
							<div class="drop-down-menu-content">
								<a href="">已买到的宝贝</a>
								<a href="">我的足迹</a>
							</div>
						</div>
					</li>
					<li class="top-menu">
						<div class="drop-down-menu">
							<span></span>
							<a href="" class="changecolor">购物车</a>
							<span>ˇ</span>
							<div class="drop-down-menu-content">
							</div>
						</div>
					</li>
					<li class="top-menu">
						<div class="drop-down-menu">
							<a href="" class="changecolor">★ 收藏夹</a>
							<span>ˇ</span>
							<div class="drop-down-menu-content">
								<a href="">收藏的宝贝</a>
								<a href="">收藏的店铺</a>
							</div>
						</div>
					</li>
					<li class="top-menu">
						<div class="drop-down-menu">
							<a href="" class="changecolor">商品分类</a>
						</div>
					</li>
					<li class="top-menu">
						<span>|</span>
					</li>
					<li class="top-menu">
						<div class="drop-down-menu">
							<a href="" class="changecolor">卖家中心</a>
							<span>ˇ</span>
							<div class="drop-down-menu-content">
								<a href="">免费开店</a>
								<a href="">已卖出的宝贝</a>
								<a href="">出售中的宝贝</a>
								<a href="">卖家服务市场</a>
								<a href="">卖家培训中心</a>
								<a href="">体检中心</a>
								<a href="">问商友</a>
							</div>
						</div>
					</li>
					<li class="top-menu">
						<div class="drop-down-menu">
							<a href="" class="changecolor">联系客服</a>
							<span>ˇ</span>
							<div class="drop-down-menu-content">
								<a href="">消费者客服</a>
								<a href="">卖家客服</a>
							</div>
						</div>
					</li>
					<li class="top-menu">
						<div class="drop-down-menu">
							<a href="" class="changecolor">≡ 网站导航</a>
							<span>ˇ</span>
							<div id="web-nav-menu-content">
								<div class="webnav">
									<div id="mainmark">
										<h2>主题市场</h2>
										<table>
											<tr>
												<td><a href="">女装</a></td>
												<td><a href="">男装</a></td>
												<td><a href="">内衣</a></td>
												<td><a href="">鞋靴</a></td>
											</tr>
											<tr>
												<td><a href="">箱包</a></td>
												<td><a href="">婴童</a></td>
												<td><a href="">家电</a></td>
												<td><a href="">数码</a></td>
											</tr>
											<tr>
												<td><a href="">手机</a></td>
												<td><a href="">美妆</a></td>
												<td><a href="">珠宝</a></td>
												<td><a href="">眼镜</a></td>
											</tr>
											<tr>
												<td><a href="">手表</a></td>
												<td><a href="">运动</a></td>
												<td><a href="">户外</a></td>
												<td><a href="">乐器</a></td>
											</tr>
											<tr>
												<td><a href="">游戏</a></td>
												<td><a href="">动漫</a></td>
												<td><a href="">影视</a></td>
												<td><a href="">美食</a></td>
											</tr>
											<tr>
												<td><a href="">鲜花</a></td>
												<td><a href="">宠物</a></td>
												<td><a href="">农资</a></td>
												<td><a href="">房产</a></td>
											</tr>
											<tr>
												<td><a href="">装修</a></td>
												<td><a href="">建材</a></td>
												<td><a href="">家居</a></td>
												<td><a href="">百货</a></td>
											</tr>
											<tr>
												<td><a href="">汽车</a></td>
												<td><a href="">二手车</a></td>
												<td><a href="">办公</a></td>
												<td><a href="">定制</a></td>
											</tr>
											<tr>
												<td><a href="">教育</a></td>
												<td><a href="">卡券</a></td>
												<td><a href="">本地</a></td>
												<td></td>
											</tr>
										</table>
									</div>
								</div>
								<div class="webnav">
									<div id="chrmark">
										<h2>特色市场</h2>
										<table>
											<tr>
												<td><a href="">iFashion</a></td>
												<td><a href="">爱逛街</a></td>
												<td><a href="">美妆秀</a></td>
											</tr>
											<tr>
												<td><a href="">全球购</a></td>
												<td><a href="">腔调</a></td>
												<td><a href="">淘女郎</a></td>
											</tr>
											<tr>
												<td><a href="">星店</a></td>
												<td><a href="">极有家</a></td>
												<td><a href="">特色中国</a></td>
											</tr>
											<tr>
												<td><a href="">拍卖会</a></td>
												<td><a href="">淘宝众筹</a></td>
												<td><a href="">中国质造</a></td>
											</tr>
											<tr>
												<td><a href="">飞猪</a></td>
												<td><a href="">亲宝贝</a></td>
												<td><a href="">闲鱼</a></td>
											</tr>
											<tr>
												<td><a href="">农资</a></td>
												<td><a href="">天天特价</a></td>
												<td><a href="">Outlets</a></td>
											</tr>
											<tr>
												<td><a href="">俪人购</a></td>
												<td><a href="">聚名品</a></td>
												<td><a href="">淘抢购</a></td>
											</tr>
											<tr>
												<td><a href="">全球精选</a></td>
												<td><a href="">非常大牌</a></td>
												<td><a href="">试用</a></td>
											</tr>
											<tr>
												<td><a href="">量贩团</a></td>
												<td><a href="">阿里翻译</a></td>
												<td></td>
											</tr>
										</table>
									</div>
								</div>
								<div class="webnav">
									<div id="aliapp">
										<table>
											<h2>阿里App</h2>
											<tr>
												<td><a href="">淘宝</a></td>
												<td><a href="">天猫</a></td>
												<td><a href="">支付宝</a></td>
											</tr>
											<tr>
												<td><a href="">聚划算</a></td>
												<td><a href="">飞猪</a></td>
												<td><a href="">蚂蚁聚宝</a></td>
											</tr>
											<tr>
												<td><a href="">旺信</a></td>
												<td><a href="">闲鱼</a></td>
												<td><a href="">阿里钱盾</a></td>
											</tr>
											<tr>
												<td><a href="">钉钉</a></td>
												<td><a href="">高德地图</a></td>
												<td><a href="">点点虫</a></td>
											</tr>
											<tr>
												<td><a href="">虾米音乐</a></td>
												<td><a href="">淘票票</a></td>
												<td><a href="">菜鸟裹裹</a></td>
											</tr>
											<tr>
												<td><a href="">爱逛街</a></td>
												<td><a href="">拍卖会</a></td>
												<td><a href="">阿里云</a></td>
											</tr>
											<tr>
												<td><a href="">网商银行</a></td>
												<td><a href="">阿里邮箱</a></td>
												<td><a href="">阿里众包</a></td>
											</tr>
										</table>
									</div>
								</div>
								<div class="webnav">
									<div id="recommend">
										<table>
											<h2 id="h24">特色推荐集</h2>
											<tr>
												<td><a href="">余额宝</a></td>
												<td><a href="">大牌捡宝</a></td>
											</tr>
											<tr>
												<td><a href="">淘公仔</a></td>
												<td><a href="">浏览器</a></td>
											</tr>
											<tr>
												<td><a href="">淘宝香港</a></td>
												<td><a href="">淘宝台湾</a></td>
											</tr>
											<tr>
												<td><a href="">淘宝全球</a></td>
												<td><a href="">淘宝东南亚</a></td>
											</tr>
											<tr>
												<td><a href="">闺蜜淘货</a></td>
												<td><a href="">大众评审</a></td>
											</tr>
											<tr>
												<td><a href="">淘工作</a></td>
												<td><a href=""></a></td>
											</tr>
										</table>
									</div>
								</div>
							</div>
						</div>
					</li>
				</ul>
			</div>
		</div>
	</header>
	<body>
		<div id="bodytop">
			<div id="body-top">
				<!--顶端、搜索-->
				<div id="logo">
					<a href=""><img src="logo.jpg"></a>
				</div>
				<div id="search">
					<ul id="which">
						<li><button id="baobei">宝贝</button></li>
						<li><button id="tianmao">天猫</button></li>
						<li><button id="dianpu">店铺</button></li>
					</ul>
					<div id="search-in">
						<input type="text" name="" placeholder="魅族手机16" id="search1">
						<a href="" id="camera"><img src=""></a>
						<button id="searchbtn">搜索</button>
					</div>
					<ul id="under-search">
						<li><a href="">新款连衣裙</a></li>
						<li><a href="">四件套</a></li>
						<li><a href="">潮流T恤</a></li>
						<li><a href="">时尚女鞋</a></li>
						<li><a href="">短裤</a></li>
						<li><a href="">半身裙</a></li>
						<li><a href="">男士外套</a></li>
						<li><a href="">墙纸</a></li>
						<li><a href="">行车记录仪</a></li>
						<li><a href="">新款男鞋</a></li>
						<li><a href="">耳机</a></li>
						<li><a href="">时尚女包</a></li>
						<li><a href="">沙发</a></li>
					</ul>
				</div>
				<div id="qr">
					<div id="close">X</div>
					<a href="">
						<div id="qrcode">
							<p>手机淘宝</p>
							<img src="qr.png">
						</div>
					</a>
				</div>
			</div>
		</div>
		<div id="navbar1">
			<!--导航栏-->
			<div id="navbar2">
				<h2>主题市场</h2>
				<ul>
					<li><a href="">天猫</a></li>
					<li><a href="">聚划算</a></li>
					<li><a href="">天猫超市</a></li>
				</ul>
				<ul>
					<li>|</li>
					<li><a href="">淘抢购</a></li>
					<li><a href="">电器城</a></li>
					<li><a href="">司法拍卖</a></li>
					<li><a href="">中国质造</a></li>
					<li><a href="">兴农扶贫</a></li>
				</ul>
				<ul>
					<li>|</li>
					<li><a href="">飞猪旅行</a></li>
					<li><a href="">智能生活</a></li>
					<li><a href="">苏宁易购</a></li>
					<li><a href="">云栖大会</a></li>
				</ul>
			</div>
		</div>
		<div id="main">
			<!--主体-->
			<div>
				<!--左-->
				<div>
					<!--左上-->
					<div id="classify-all">
						<!--分类-->
						<ul id="classify">
							<li class="nav">
								<a href="" class="nav-a">女装</a>
								<span>/</span>
								<a href="" class="nav-a">男装</a>
								<span>/</span>
								<a href="" class="nav-a">内衣</a>
								<i>></i>
								<div class="nav-content"></div>
							</li>
							<li class="nav">
								<a href="" class="nav-a">鞋靴</a>
								<span>/</span>
								<a href="" class="nav-a">箱包</a>
								<span>/</span>
								<a href="" class="nav-a">配件</a>
								<i>></i>
								<div class="nav-content"></div>
							</li>
							<li class="nav">
								<a href="" class="nav-a">童装玩具</a>
								<span>/</span>
								<a href="" class="nav-a">孕产</a>
								<span>/</span>
								<a href="" class="nav-a">用品</a>
								<i>></i>
								<div class="nav-content"></div>
							</li>
							<li class="nav">
								<a href="" class="nav-a">家电</a>
								<span>/</span>
								<a href="" class="nav-a">数码</a>
								<span>/</span>
								<a href="" class="nav-a">手机</a>
								<i>></i>
								<div class="nav-content"></div>
							</li>
							<li class="nav">
								<a href="" class="nav-a">美妆</a>
								<span>/</span>
								<a href="" class="nav-a">洗护</a>
								<span>/</span>
								<a href="" class="nav-a">保健品</a>
								<i>></i>
								<div class="nav-content"></div>
							</li>
							<li class="nav">
								<a href="" class="nav-a">珠宝</a>
								<span>/</span>
								<a href="" class="nav-a">眼镜</a>
								<span>/</span>
								<a href="" class="nav-a">手表</a>
								<i>></i>
								<div class="nav-content"></div>
							</li>
							<li class="nav">
								<a href="" class="nav-a">运动</a>
								<span>/</span>
								<a href="" class="nav-a">户外</a>
								<span>/</span>
								<a href="" class="nav-a">乐器</a>
								<i>></i>
								<div class="nav-content"></div>
							</li>
							<li class="nav">
								<a href="" class="nav-a">游戏</a>
								<span>/</span>
								<a href="" class="nav-a">动漫</a>
								<span>/</span>
								<a href="" class="nav-a">影视</a>
								<i>></i>
								<div class="nav-content"></div>
							</li>
							<li class="nav">
								<a href="" class="nav-a">美食</a>
								<span>/</span>
								<a href="" class="nav-a">生鲜</a>
								<span>/</span>
								<a href="" class="nav-a">零食</a>
								<i>></i>
								<div class="nav-content"></div>
							</li>
							<li class="nav">
								<a href="" class="nav-a">鲜花</a>
								<span>/</span>
								<a href="" class="nav-a">宠物</a>
								<span>/</span>
								<a href="" class="nav-a">农资</a>
								<i>></i>
								<div class="nav-content"></div>
							</li >
							<li class="nav">
								<a href="" class="nav-a">工具</a>
								<span>/</span>
								<a href="" class="nav-a">装修</a>
								<span>/</span>
								<a href="" class="nav-a">建材</a>
								<i>></i>
								<div class="nav-content"></div>
							</li>
							<li class="nav">
								<a href="" class="nav-a">家具</a>
								<span>/</span>
								<a href="" class="nav-a">家饰</a>
								<span>/</span>
								<a href="" class="nav-a">家纺</a>
								<i>></i>
								<div class="nav-content"></div>
							</li>
							<li class="nav">
								<a href="" class="nav-a">汽车</a>
								<span>/</span>
								<a href="" class="nav-a">二手车</a>
								<span>/</span>
								<a href="" class="nav-a">用品</a>
								<i>></i>
								<div class="nav-content"></div>
							</li>
							<li class="nav">
								<a href="" class="nav-a">办公</a>
								<span>/</span>
								<a href="" class="nav-a">DIY</a>
								<span>/</span>
								<a href="" class="nav-a">五金电子</a>
								<i>></i>
								<div class="nav-content"></div>
							</li>
							<li class="nav">
								<a href="" class="nav-a">百货</a>
								<span>/</span>
								<a href="" class="nav-a">餐厨</a>
								<span>/</span>
								<a href="" class="nav-a">家庭保健</a>
								<i>></i>
								<div class="nav-content"></div>
							</li>
							<li class="nav">
								<a href="" class="nav-a">学习</a>
								<span>/</span>
								<a href="" class="nav-a">卡券</a>
								<span>/</span>
								<a href="" class="nav-a">本地服务</a>
								<i>></i>
								<div class="nav-content"></div>
							</li>
						</ul>
					</div>
					<div>
						<div>
							<!--轮播图-->
							<div>
								<!--上-->
							</div>
							<div>
								<!--天猫-->
							</div>
						</div>
					</div>
					<div>
						<!--ad-->
						<div>
							<!--新势力周-->
						</div>
						<div>
							<!--今日热卖-->
						</div>
					</div>
				</div>
				<div>
					<!--淘宝头条-->
					<div>
						<!--头条Logo-->
					</div>
					<div>
						<!--轮播图-->
					</div>
				</div>
			</div>
			<div>
				<!--右-->
				<div>
					<!--登录框-->
				</div>
				<div>
					<!--举报专区-->
				</div>
				<div>
					<!--公告……-->
				</div>
				<div>
					<!--十六格-->
				</div>
				<div>
					<!--阿里APP-->
				</div>
			</div>
		</div>
		<div>
			<!--生活研究所-->
		</div>
		<div>
			<!--有好货+爱逛街-->
		</div>
		<div>
			<!--淘抢购-->
		</div>
		<div>
			<!--横幅广告-->
		</div>
		<div>
			<!--每日好店+淘宝直播-->
		</div>
		<div>
			<!--时尚爆料王+广告-->
		</div>
		<div>
			<!--品质生活家+特色玩味控-->
		</div>
		<div>
			<!--实惠专业户-->
		</div>
		<div>
			<!--热卖单品-->
		</div>
		<div>
			<!--猜你喜欢-->
		</div>
		<div>
			<!--END-->
		</div>
		<div>
			<!--消费者保障……-->
		</div>
	</body>
	<footer>
		<div>
			<!--友情链接-->
		</div>
		<div>
			<!--关于淘宝-->
		</div>
		<div>
			<!--证件-->
		</div>
		<div>
			<!--举报平台-->
		</div>
	</footer>
</body>
</html>
