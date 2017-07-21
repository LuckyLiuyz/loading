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
					first:"正在加载中",
					second:"请稍后..."
				},
				imgbg:"#cba162",
				ishide:false
			}
		);
	

	2、hide loading.

		Wait.hideAnimation();