# css-flow-step
纯CSS写的流程箭头，可自定义宽高尺寸，兼容IE6+

<img width="622" alt="er4546" src="https://cloud.githubusercontent.com/assets/1295348/11021407/6f599194-867b-11e5-8b1a-8d5731c06b6b.png">


## 默认型

````html
<ol class="flowStep clearfix">
    <li class="flowStep__item flowStep__item--done">
        <span class="flowStep__before flowStep__before--first"></span>
        <span class="flowStep__txt">确认订单信息</span>
        <span class="flowStep__after"></span>
    </li>
    <li class="flowStep__item flowStep__item--current">
        <span class="flowStep__before"></span>
        <span class="flowStep__txt">付款到支付宝</span>
        <span class="flowStep__after"></span>
    </li>
    <li class="flowStep__item">
        <span class="flowStep__before"></span>
        <span class="flowStep__txt">购买成功</span>
        <span class="flowStep__after"></span>
    </li>
</ol>
````

## 头尾带箭头型

````html
<ol class="flowStep clearfix">
    <li class="flowStep__item flowStep__item--done">
        <span class="flowStep__before"></span>
        <span class="flowStep__txt">确认订单信息</span>
        <span class="flowStep__after"></span>
    </li>
    <li class="flowStep__item flowStep__item--current">
        <span class="flowStep__before"></span>
        <span class="flowStep__txt">付款到支付宝</span>
        <span class="flowStep__after"></span>
    </li>
    <li class="flowStep__item">
        <span class="flowStep__before"></span>
        <span class="flowStep__txt">购买成功</span>
        <span class="flowStep__after flowStep__after--last"></span>
    </li>
</ol>
````
