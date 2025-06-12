---
layout: default
title: Michelle
---

## Puzzle 1
## Drag the code in the correct order - don't forget the indents!

<div id="puzzlepart2no1-sortableTrash" class="sortable-code"></div> 
<div id="puzzlepart2no1-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzlepart2no1-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzlepart2no1-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "for x in range(1,13):\n" +
    "    for y in range(1,13):\n" +
    "        print (x*y)\n" +
    "        print()";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzlepart2no1-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "puzzlepart2no1-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzlepart2no1-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzlepart2no1-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 2
## Drag the code in the correct order - don't forget the indents!

<div id="puzzlepart2no2-sortableTrash" class="sortable-code"></div> 
<div id="puzzlepart2no2-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzlepart2no2-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzlepart2no2-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "loan=int(input(&quot;Enter Amount of Loan&gt; &quot;))\n" +
    "days=int(input(&quot;Enter Number of days &quot;))\n" +
    "print(&quot;Day   Amount&quot;)\n" +
    "for x in range(1,days+1):\n" +
    "    loan=loan*1.01\n" +
    "    print(x,&quot;\t&quot;,loan)\n" +
    "    ";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzlepart2no2-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "puzzlepart2no2-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzlepart2no2-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzlepart2no2-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 3
## Drag the code in the correct order - don't forget the indents!

<div id="puzzlepart2no3-sortableTrash" class="sortable-code"></div> 
<div id="puzzlepart2no3-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzlepart2no3-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzlepart2no3-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "while True:\n" +
    "    choice=int(input(&quot;Enter a value &quot;))\n" +
    "    for x in range(1,13):\n" +
    "        print(x, &quot;times &quot;,choice,&quot;=&quot;, x*choice)\n" +
    "        print()\n" +
    "    ";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzlepart2no3-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "puzzlepart2no3-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzlepart2no3-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzlepart2no3-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 4
## Drag the code in the correct order - don't forget the indents!

<div id="puzzlepart2no4-sortableTrash" class="sortable-code"></div> 
<div id="puzzlepart2no4-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzlepart2no4-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzlepart2no4-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "def multiply():\n" +
    "    num1=int(input(&quot;Enter number 1? &quot;))\n" +
    "    num2=int(input(&quot;Enter number 2? &quot;))\n" +
    "    total=num1*num2\n" +
    "    print(num1,&quot;muliplied by&quot;,num2,&quot;=&quot;,total)\n" +
    "multiply()";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzlepart2no4-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "puzzlepart2no4-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzlepart2no4-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzlepart2no4-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>
