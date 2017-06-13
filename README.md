# ChineseToUnicode
将中文转为相应的unicode：javascript:var str = window.prompt('请输入中文：', ''); var temp = [];for(var i=0; i&lt;str.length; i++){ var number = str.charCodeAt(i);    var hex = number.toString(16); temp.push(hex);}var res = '\\u'+temp.join('\\u');window.alert(str + ': ' + res);document.writeln('&lt;p>&lt;span>' +str + ': &lt;/span>' + res + '&lt;/p>');console.log(str, ': ' + res);
