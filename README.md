<html>
<body>
<form>
<label>Number 1</label><input type="text" placeholder="enter a num" id="num1"></input>
<br/><br/>
<label>Nnumber 2</label><input type="text" placeholder="enter a num" id="num2"></input>
<br/>
<br/>
<label>Result:</label><input type="text" disabled id="t"/>
<br/>
<br/>
<input type="button" onclick="add()" value="ADDITION"/>
<input type="button" onclick="sub()" value="SUBTRACTION"/>
<input type="button" onclick="mul()" value="MULTIPLICATION"/>
<input type="button" onclick="div()" value="DIVISION"/>
</form>
<script>
function add() {
let a,b;
a=parseInt(document.getElementById("num1").value);
b=parseInt(document.getElementById("num2").value);
document.getElementById("t").value=(a+b);
}
function sub() {
let a,b;
a=parseInt(document.getElementById("num1").value);
b=parseInt(document.getElementById("num2").value);
document.getElementById("t").value=(a-b);
}
function mul() {
let a,b;
a=parseInt(document.getElementById("num1").value);
b=parseInt(document.getElementById("num2").value);
document.getElementById("t").value=(a*b);
}
function div() {
let a,b;
a=parseInt(document.getElementById("num1").value);
b=parseInt(document.getElementById("num2").value);
document.getElementById("t").value=(a/b);
}
</script>
</body>
</html>
