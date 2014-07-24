
##**捞仔外卖摇号神器（RandomLow）**

###核心需求：解决团体内没人愿意去拿外卖的问题。
 
###使用流程：

 1. 首先需要设定随机数范围大小、幸运规则以及幸运星人数，然后分别输入需要叫外卖的全体人的名字，无误后点击确认；
 2. 通过 Html5 实现类似于六合彩的摇号机的功能，在确认名字之后机器开始运转；
 3. 机器随机产生一系列号码，随机号码与人名一一对应，直至全部号码生成完毕；
 4. 所有人的名字和摇号号码生成，存储在数组列表里，并恭喜幸运之星。

###后续可以考虑集成开发的功能之“捞埋我食饭”：

 1. 设置随机数为1-99，每次摇出的数字有且只能出现一次
 2. 在每次团体摇号之前，先随机生成一个 Lucky Number
 3. 每个人获得其号码后，与 Lucky Number 相同的号码成为“捞饭仔”
 4. 其余未中奖的人若不共同分担“捞饭仔”的餐费，则成为......“落柚仔”一个星期
 5. “落柚仔”必须每次去拿饭，玩狼人自动成为普通村民，收拾垃圾，等等杂活
 6. “落柚仔”若不遵守“落柚仔法则”则成为......“落柚仔”一个星期
