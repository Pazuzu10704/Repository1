

<html>
<head>
<title>Animation</title>
<style>
.box1{width:100px; height:100px;
animation:anim 2s infinite; background-color:yellow; display:grid; place-items:center;}
@keyframes anim {
0%{margin-left:0px;transform:rotate(0deg);background-color:yellow;}
50%{margin-left:300px;transform:rotate(360deg);background-color:green;}
100%{margin-left:600px;transform:rotate(0deg);background-color:red;}
}

</style>
</head>
<body>
<div class="box1">
<h2>Sale</h2>
</div>
</body>
</html>

