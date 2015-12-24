# print_r array or object in javascript
<h3>Output/return content of js array or object, as PHP print_r() </h3>
<h3>打印 js对象数组 函数, 模仿php的print_r()</h3>
<p>flprintr.js-fl20151223gz</p>

<p>
Github: <a href="https://github.com/jiaju99/flprintr" target="_blank">https://github.com/jiaju99/flprintr</a><br>
Author: <a href="http://feilong.org" target="_blank">http://feilong.org</a></p>
<p><b>what</b>, now what to output. default none<br>
<b>gap</b>,  to insert before output</p>


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
