# ClockView
Clock for iOS 

####用法简介
    ClockView *clockView = [[ClockView alloc] initWithFrame:CGRectMake(0, 200, 200, 200)];
    [self.view addSubview:clockView];
    [clockView start];
    ........
    [clockView stop];
    [clockView release];

####变换秒针旋转样式
    clock.secRoll = NO / YES;
    
####样式设置方法
    [self setClockBackgroundImage:[UIImage imageNamed:@"xxx"].CGImage];
    [self setSecHandImage:[UIImage imageNamed:@"xxx"].CGImage];
    [self setMinHandImage:[UIImage imageNamed:@"xxx"].CGImage];
    [self setHourHandImage:[UIImage imageNamed:@"xxx"].CGImage];

####示例 
秒针两种旋转样式
<img src="http://ww2.sinaimg.cn/large/e70bae90gw1f3q88b02n3g20pg0q07wh.gif" alt="" width="431" /></p>

