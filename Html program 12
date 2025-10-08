<!DOCTYPE html>
<html lang="en">
<head>
 <meta charset="UTF-8">
 <title>Sri GCSR College- Program-12</title>
 <script>
 function appendValue(val) {
 document.getElementById("result").value += val;
 }
 function clearDisplay() {
 document.getElementById("result").value = "";
 }
 function deleteChar() {
 const current = document.getElementById("result").value;
 document.getElementById("result").value = current.slice(0, -1);
 }
 function calculate() {
 const expression = document.getElementById("result").value;
 try {
 document.getElementById("result").value = eval(expression);
 } catch {
 document.getElementById("result").value = "Error";
 }
 }
 </script>
</head>
<body>
 <h2><center>Simple Calculator</center></h2>
 <table border="1" cellspacing="0" cellpadding="5" align="center">
 <tr>
 <td colspan="4">
 <input type="text" id="result" readonly 
 style="width:100%; height:40px; text-align:right; box-sizing:border-box;">
 </td>
 </tr>
 <tr>
 <td><button style="width:100%; height:40px;" onclick="clearDisplay()">C</button></td>
 <td><button style="width:100%; height:40px;" onclick="deleteChar()">DEL</button></td>
 <td><button style="width:100%; height:40px;" onclick="appendValue('%')">%</button></td>
 <td><button style="width:100%; height:40px;" onclick="appendValue('/')">/</button></td>
 </tr>
 <tr>
 <td><button style="width:100%; height:40px;" onclick="appendValue('7')">7</button></td>
 <td><button style="width:100%; height:40px;" onclick="appendValue('8')">8</button></td>
 <td><button style="width:100%; height:40px;" onclick="appendValue('9')">9</button></td>
 <td><button style="width:100%; height:40px;" onclick="appendValue('*')">*</button></td>
 </tr>
 <tr>
 <td><button style="width:100%; height:40px;" onclick="appendValue('4')">4</button></td>
 <td><button style="width:100%; height:40px;" onclick="appendValue('5')">5</button></td>
 <td><button style="width:100%; height:40px;" onclick="appendValue('6')">6</button></td>
 <td><button style="width:100%; height:40px;" onclick="appendValue('-')">-</button></td>
 </tr>
 <tr>
 <td><button style="width:100%; height:40px;" onclick="appendValue('1')">1</button></td>
 <td><button style="width:100%; height:40px;" onclick="appendValue('2')">2</button></td>
 <td><button style="width:100%; height:40px;" onclick="appendValue('3')">3</button></td>
 <td><button style="width:100%; height:40px;" onclick="appendValue('+')">+</button></td>
 </tr>
 <tr>
 <td><button style="width:100%; height:40px;" onclick="appendValue('0')">0</button></td>
<td><button style="width:100%; height:40px;" onclick="appendValue('.')">.</button></td>
 <td colspan="2"><button style="width:100%; height:40px;" 
onclick="calculate()">=</button></td>
 </tr>
 </table>
</body>
</html>
