<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<title>計算タップゲーム</title>

<style>

body{
font-family:sans-serif;
text-align:center;
}

#question{
font-size:40px;
margin:20px;
}

.grid{
display:grid;
grid-template-columns:repeat(3,100px);
grid-gap:10px;
justify-content:center;
}

.cell{
width:100px;
height:100px;
font-size:35px;
background:#f0f0f0;
border-radius:10px;
display:flex;
align-items:center;
justify-content:center;
cursor:pointer;
}

.cell:hover{
background:#ddd;
}

</style>
</head>

<body>

<div id="question">0 + 0</div>

<div class="grid" id="grid"></div>

<div id="result"></div>

<script>

let correctAnswer
let questionCount=0
let mistake=false
let maxQuestions=9

function createQuestion(){

let a=Math.floor(Math.random()*10)
let b=Math.floor(Math.random()*10)

correctAnswer=a+b

document.getElementById("question").innerText=a+" + "+b

createGrid()

}

function createGrid(){

let grid=document.getElementById("grid")
grid.innerHTML=""

let numbers=[]

while(numbers.length<8){

let n=Math.floor(Math.random()*19)

if(n!=correctAnswer && !numbers.includes(n)){
numbers.push(n)
}

}

numbers.push(correctAnswer)

numbers.sort(()=>Math.random()-0.5)

numbers.forEach(num=>{

let div=document.createElement("div")
div.className="cell"
div.innerText=num

div.onclick=()=>checkAnswer(num)

grid.appendChild(div)

})

}

function checkAnswer(num){

questionCount++

if(num!=correctAnswer){

mistake=true
maxQuestions=16

}

if(questionCount>=maxQuestions){

document.getElementById("result").innerText="終了！問題数："+questionCount
document.getElementById("grid").innerHTML=""
return

}

createQuestion()

}

createQuestion()

</script>

</body>
</html>
