**CSS学习笔记**（层叠样式表）
**样式规则**
    <style>选择器{属性:修改值; 属性:修改值;}</stlye>
**基础属性**
    font-size:10px像素；
              em
    font-family:"字体"；用，号隔开，多个单词或含#等符号需用“”包起来
    font-weight:"" normal=400;bold=700;bolder;lighter;
    font-style;normal;italic倾斜;效果同<em></em>标签
**CSS注释**
    格式为/*注释*/  快捷键ctrl+/
**类选择器**   
    style里为.类名。而在标签里为class=“类名”作为属性，一般用下划线来命名
**多类名**
    class="类名一 类名二"即同时拥有多个类名
**id选择器**
    stlye部分 #id名 标签属性id="id名"
        类选择器可以重复使用，而id选择器不可以重复使用
**通配符选择器**
    *{}这样；*代表所有的标签
**伪类选择器**
    链接伪类选择器
        链接标签名   ：link      未访问的链接
                    :visited    已访问的链接
                    :hover      鼠标放到链接上
                    :active     选定的链接
                    注意顺序不要颠倒 记忆：love hate
    结构伪类选择器
        first-child:选定首个子项目
        last-child:选定最后一个子项目
        nth-child():选择第n个子项目
        nth-child(even/odd):even为选择偶数，odd为奇数
        nth-last-child(even):反向数
    目标伪类选择器：
        :target{}对当前目标的选择修改                    