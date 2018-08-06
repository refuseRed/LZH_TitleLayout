# LZH_TitleLayout
一行代码创建常用的标题栏

代码使用案列展示

//样式1 ：6个元素、2行、4列、图上文下、图文间隙10pt

NSArray * titleArr = @[@"埃菲尔铁塔",@"埃及金字塔",@"比萨斜塔",@"迪拜帆船酒店",@"富士山",@"凯旋门"] ;

LZHTitleLayoutView * titleLayoutView = [[LZHTitleLayoutView alloc]initWithFrame:CGRectMake(0, 20, 375, 250) TitleArr:titleArr LineNumber:2 ColumnsNumber:4 EdgeInsetsStyle:LZHEdgeInsetsStyleTop ImageTitleSpace:10];

titleLayoutView.delegate = self ;

[self.view addSubview:titleLayoutView];

