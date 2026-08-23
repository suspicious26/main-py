<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>message_to_sharanya.py</title>

<style>
*{box-sizing:border-box}

body{
    margin:0;
    min-height:100vh;
    background:#0d1117;
    color:#d4d4d4;
    font-family:Consolas,Monaco,monospace;
    display:flex;
    justify-content:center;
    align-items:center;
    padding:20px;
}

.window{
    width:100%;
    max-width:900px;
    background:#1e1e1e;
    border:1px solid #333;
    border-radius:12px;
    overflow:hidden;
    box-shadow:0 20px 60px rgba(0,0,0,.5);
}

.titlebar{
    height:45px;
    background:#181818;
    display:flex;
    align-items:center;
    padding:0 15px;
    border-bottom:1px solid #333;
}

.dots{
    display:flex;
    gap:7px;
    margin-right:20px;
}

.dot{
    width:12px;
    height:12px;
    border-radius:50%;
    background:#555;
}

.filename{
    color:#ccc;
    font-size:14px;
}

.editor{
    padding:25px 20px;
    min-height:500px;
    overflow:auto;
}

.code{
    font-size:15px;
    line-height:1.8;
    white-space:pre-wrap;
}

.line{
    display:flex;
}

.num{
    color:#555;
    width:40px;
    text-align:right;
    margin-right:20px;
    user-select:none;
}

.keyword{color:#569cd6}
.func{color:#dcdcaa}
.string{color:#ce9178}
.comment{color:#6a9955}

.output{
    margin-top:25px;
    padding:18px;
    border-left:3px solid #569cd6;
    background:#151515;
    display:none;
}

.output h3{
    margin:0 0 12px;
    color:#569cd6;
    font-size:14px;
}

.message{
    color:#e6e6e6;
    line-height:1.8;
    font-family:Arial,sans-serif;
    font-size:16px;
}

button{
    margin-top:20px;
    background:#569cd6;
    color:white;
    border:0;
    padding:10px 20px;
    border-radius:5px;
    cursor:pointer;
    font-family:Consolas,monospace;
}

button:hover{
    opacity:.85;
}
</style>
</head>

<body>

<div class="window">

<div class="titlebar">
    <div class="dots">
        <div class="dot"></div>
        <div class="dot"></div>
        <div class="dot"></div>
    </div>
    <div class="filename">message_to_sharanya.py</div>
</div>

<div class="editor">

<div class="code">

<div class="line">
<span class="num">1</span>
<span class="comment"># A little message...</span>
</div>

<div class="line">
<span class="num">2</span>
</div>

<div class="line">
<span class="num">3</span>
<span class="keyword">def</span>&nbsp;
<span class="func">message_to_sharanya</span>():
</div>

<div class="line">
<span class="num">4</span>
&nbsp;&nbsp;&nbsp;&nbsp;<span class="keyword">return</span>&nbsp;<span class="string">"""Some things are difficult to say."""</span>
</div>

<div class="line">
<span class="num">5</span>
</div>

<div class="line">
<span class="num">6</span>
<span class="keyword">print</span>(<span class="string">"Running message..."</span>)
</div>

</div>

<button onclick="runMessage()">▶ Run Python</button>

<div class="output" id="output">

<h3>OUTPUT</h3>

<div class="message">
Hey Sharanya,<br><br>

I know I don't want to disturb you, and there's no pressure to reply.<br><br>

I just wanted to say that I still miss you a lot.<br><br>

I'm genuinely grateful for all the memories we shared. 
I'm still emotionally attached to them, and maybe that's why 
I haven't been able to connect with other girls the same way.<br><br>

You're such a kind and beautiful person.<br><br>

Thank you for everything.<br><br>

Take care, buddy. ❤️
</div>

</div>

</div>
</div>

<script>
function runMessage(){
    document.getElementById("output").style.display="block";
    window.scrollTo({
        top:document.body.scrollHeight,
        behavior:"smooth"
    });
}
</script>

</body>
</html>
