# recur
使用方法: 


1, 导入头文件     
#import "UIControl+recurClick.h"



2, 设置持续时间
UIButton *button  = [[ UIButton alloc] init];

button.uxy_acceptEventInterval = 3.0;

[button addTarget:self action:@selector(buttonClick:) forControlEvents:UIControlEventTouchUpInside];
