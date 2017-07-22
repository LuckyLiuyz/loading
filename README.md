# loading-demo
	This is a simple loading demo.
	It's just one html page.
	You can easily introduce it into your project


## How to get it? --->By git.

    git clone https://github.com/Liuxiang66/loading.git


## How to use? 

	1、show loading.

		Wait.showAnimation(
			{
				message:{
					first:"正在加载中",//第一部分显示的文字
					second:"请稍后..."//第二部分显示的文字
				},
				imgbg:"#cba162",//动画的背景色
				ishide:false//是否隐藏默认的动画
			}
		);
	

	2、hide loading.

		Wait.hideAnimation();