# flprintr

<h1>打印 js对象数组 函数, 模仿php的print_r()</h1>
<h2>flprintr.js-fl20151223gz</h2>

<p>To output the content of an array or object in JS, as print_r() in PHP.<br>
 Github: <a href="https://github.com/jiaju99/printr" target="_blank">https://github.com/jiaju99/flprintr</a><br>
Author: <a href="http://feilong.org" target="_blank">http://feilong.org</a>
</p>


<p><b>what</b>, now what to output. default none<br>
<b>deep</b>, now the deep length. begin from 0<br>
<b>gap</b>,  to insert before output</p>

<p>Thanks to <a href="https://github.com/Hootrix/js_print_r" target="_blank">Hootrix</a></p>

<h3>举例</h3>
<pre>
/** On your project,Use uglified flprintr **/

/* eg. have a test */
var arr = [];
arr['0'] = ['i', 'love', 'you','baby'];
arr['1'] = ['a', 'b', 'c','d'];
arr['1'][1] = {a:'6y', b:'9z'};
arr['2'] = {'k0':'va','k1':'vb'};
arr['3'] = {};
arr['4'] = null;

var arrTree1=flprintr(arr);
console.log(arrTree1);

var arrTree2=flprintr(arr,'----');
console.log(arrTree2);

var arrTree3=flprintr(arr,'    ');
console.log(arrTree3);
</pre>
