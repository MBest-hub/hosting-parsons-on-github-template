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

## Puzzle 5
## Drag the code in the correct order - don't forget the indents!

<div id="puzzlepart2no5-sortableTrash" class="sortable-code"></div> 
<div id="puzzlepart2no5-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzlepart2no5-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzlepart2no5-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "levels=[1,2,3,4,5,6,7,8,9,10]\n" +
    "if 4 in levels:\n" +
    "    print (&quot;this is in the list&quot;)\n" +
    "    \n" +
    "else:\n" +
    "    print(&quot;this is not in the list&quot;";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzlepart2no5-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "puzzlepart2no5-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzlepart2no5-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzlepart2no5-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 6
## Drag the code in the correct order - don't forget the indents!

<div id="puzzlepart2no6-sortableTrash" class="sortable-code"></div> 
<div id="puzzlepart2no6-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzlepart2no6-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzlepart2no6-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "print(&quot;Joe&#039;s car park&quot;)\n" +
    "print(&quot;Please insert 8 for a ticket&quot;)\n" +
    "totalcash=0\n" +
    "while totalcash&lt;8:\n" +
    "    coins=int(input(&quot;Enter pound coins &quot;))\n" +
    "    totalcash=totalcash+coins\n" +
    "print (&quot;Thank you&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzlepart2no6-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "puzzlepart2no6-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzlepart2no6-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzlepart2no6-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 7
## Drag the code in the correct order - don't forget the indents!

<div id="puzzlepart2no7-sortableTrash" class="sortable-code"></div> 
<div id="puzzlepart2no7-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzlepart2no7-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzlepart2no7-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "reg=input(&quot;Enter the first 3 digits of your reg: &quot;)\n" +
    "while True:\n" +
    "    if (len(reg)==3):\n" +
    "        print(&quot;Thank you&quot;)\n" +
    "        break\n" +
    "        \n" +
    "    else:\n" +
    "        print(&quot;Please try again&quot;)\n" +
    "        reg=input(&quot;Enter the first 3 digits of your reg: &quot;)\n" +
    "        \n" +
    "        break\n" +
    " \n" +
    "  \n" +
    "timespent=int(input(&quot;How long did you park for? &quot;))\n" +
    "totalfee=timespent*1.50\n" +
    "print(&quot;You owe: &quot;,totalfee) &quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzlepart2no7-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "puzzlepart2no7-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzlepart2no7-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzlepart2no7-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 8
## Drag the code in the correct order - don't forget the indents!

<div id="puzzlepart2no8-sortableTrash" class="sortable-code"></div> 
<div id="puzzlepart2no8-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzlepart2no8-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzlepart2no8-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "def output(name):\n" +
    "    return(&quot;The pupil is called &quot;+name)\n" +
    "print(output(&quot;David&quot;))\n" +
    "print(output(&quot;Katy&quot;))";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzlepart2no8-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "puzzlepart2no8-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzlepart2no8-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzlepart2no8-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 9
## Drag the code in the correct order - don't forget the indents!

<div id="puzzlepart2no9-sortableTrash" class="sortable-code"></div> 
<div id="puzzlepart2no9-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzlepart2no9-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzlepart2no9-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "password = &quot;secret&quot;\n" +
    "encrypted = &#039; &#039; \n" +
    "key = 7\n" +
    "for each in password:\n" +
    "    newLetter = ord (each)+key\n" +
    "    encrypted +=chr(newLetter)\n" +
    "print (encrypted)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzlepart2no9-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "puzzlepart2no9-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzlepart2no9-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzlepart2no9-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>
