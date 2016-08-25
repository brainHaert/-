
# NSMutableAttributedString-XZCategory-富文本的简单封装
######最下面有图<br>
封装为了更方便，因为我自己都不知道会不会记得那个name<br>
`NSMutableAttributedString+XZCategory.h`<br>
`NSMutableAttributedString+XZCategory.m`<br>
以上两个文件拖进项目里，在想用的地方`#import "NSMutableAttributedString+XZCategory.h"`<br>
即可

项目内有不少的中文注释，无需担心

/**改变某位置的颜色*/
`-(NSRange)changeColor:(UIColor *)color rang:(NSRange)rang;`
/**改变某位置的颜色*/
`-(NSRange)changeColor:(UIColor *)color from:(NSInteger)loc legth:(NSInteger)legth;`

/**改变某位置的普通字号*/
`-(NSRange)changeSystemFontFloat:(CGFloat)fontFloat rang:(NSRange)rang;`
/**改变某位置的普通字号*/
`-(NSRange)changeSystemFontFloat:(CGFloat)fontFloat from:(NSInteger)loc legth:(NSInteger)legth;`

/**改变某位置的粗体字号*/
`-(NSRange)changeBoldFontFloat:(CGFloat)fontFloat rang:(NSRange)rang;`
/**改变某位置的粗体字号*/
`-(NSRange)changeBoldFontFloat:(CGFloat)fontFloat from:(NSInteger)loc legth:(NSInteger)legth;`

/**改变某位置的行距*/
`-(NSRange)changelineSpacing:(CGFloat)spacing from:(NSInteger)loc legth:(NSInteger)legth;`

/**改变某位置的段落距离*/
`-(NSRange)changelparagraphSpacing:(CGFloat)spacing from:(NSInteger)loc legth:(NSInteger)legth;`

/**改变段的顶部和文本内容的开头之间的距离。*/
`-(NSRange)changeBeforeLparagraphSpacing:(CGFloat)spacing from:(NSInteger)loc legth:(NSInteger)legth;`

/**根据位置加下划线*/
`-(NSRange)changeUnderlineWitRang:(NSRange)rang;`
/**根据位置加下划线*/
`-(NSRange)changeUnderlineFrom:(NSInteger)loc legth:(NSInteger)legth;`
/**全部加下划线*/
`-(void)changeUnderlineAtAll;`

/**根据位置加中划线*/
`-(NSRange)changeStrikethroughWitRang:(NSRange)rang;`
/**根据位置加中划线*/
`-(NSRange)changeStrikethroughFrom:(NSInteger)loc legth:(NSInteger)legth;`
/**全部加中划线*/
`-(void)changeStrikethroughAtAll;`<br>

![](https://raw.githubusercontent.com/brainHaert/NSMutableAttributedString-XZCategory-/master/textAtt1.png)
