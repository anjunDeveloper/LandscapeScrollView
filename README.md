# LandscapeScrollView
以tab的形式切换视图，同时支持点击和滑动

使用方法：
比如在你需要使用的控制器中加上以下代码即可。

TestView * test = [[TestView alloc] initWithTitleArray:@[@"我喜欢的明星",@"明星广场",@"非常星魅力"] frame:CGRectMake(0,50,320,400) hasSlider:NO];

[self.view addSubview:test];
