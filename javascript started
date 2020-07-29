use var to create a value

# use spilt()&join() to switch string&array
var leng = "1:2:3:4"
var leng1 = leng.split(':')
console.log(leng1)
console.log(leng1.join(":"))

use node xx.js to run it in cmd

#use push()&pop() to add or remove the tail element of array
leng1.push('5') // if '5': char; if 5: number
leng1.pop()

#use unshift()&shift() for the element of the header
leng1.unshift('0')
leng1.shift()

null == 0 : false
null == false : false
0 == false : true

0 === false :false
# == 是相等操作符，比较值是否相等
# === 是全等操作符，比较值和类型是否都相等
undefined == null : true
undefined === null : false
undefined == 0 : false
# undefined 表示未赋值时变量的默认值
# null 表示一个变量不再指向任何对象地址

字符串连接：可以直接通过+进行连接

字符串长度: myString.length属性，非length()

字符串查找：indexof()方法，详见API文档str.indexOf(searchValue, fromIndex)
"Blue Sky".indexOf("Blue") // returns 0
返回值指的是指定值第一次出现的索引，如果没有找到返回-1

字符串提取：slice(start,end) 闭开区间。如无end，代表提取所有剩余字符。
"Blue Sky".slice(2) // returns "ue Sky"

#数字与字符串转换：toString() & Number()
var myString = myNum.toString()
var myNum=Number(myString)
# typeof检查类型
typeof(myString)

#转换大小写：toLowerCase() 和 toUpperCase() 
var string = "I like study"
string.toLowerCase()
string.toUpperCase()

#替换字符串：replace()，详见API
var string = "I like study"
string.replace("study", "sleep")
#此时只能替换第一个出现的字符串，第二个出现的不会被替换。所以可用正则表达式：
string.replace(/study/g, "sleep")


JavaScript中有7种数据类型：
Undefined，Null，Boolean（布尔值），String，Number，Object，及ES6新引入的Symbol，作为对象属性的唯一标识符，防止对象属性冲突发生

对于Undefined 与Null，转String，使用String方法：
String(null)
String(undefined)

Number() 可以把任意值转换成数值:
Number(null) // returns 0
Number(undefined) // return NaN
Number("123abc") // return NaN
如果要转换的字符串中有一个不是数值的字符，返回 NaN（not a number）

parseInt() 把字符串转换成整数，详见API
parseFloat() 把字符串转换成浮点数，但如果解析的内容里只有整数，解析成整数；且只能十进制
parseInt("12.3abc") // return 12

使用 Boolean() 函数转换为布尔类型：
Boolean(124) // returns true
