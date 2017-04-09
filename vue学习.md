# 灵活运用逻辑运用
举个例子:
<p v-if="seen">Now you see me </p>
当seen的布尔值为true时，p中的内容显示
那么可以
<p v-if="seen > 5">..</p>
当seen>5时，显示出来
可以利用各种逻辑运算

# watch 耗内存
# v-if v-else 必须挨着在一起
# v-if(is_login) 显示一个页面
# v-else 显示另一个页面
# vue的过渡动画只能存在与不同的标签，如p和div，如果标签相同，则需要使用key来区分才能使用过渡动画
