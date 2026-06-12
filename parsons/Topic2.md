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

## Puzzle 10
## Drag the code in the correct order - don't forget the indents!

<div id="puzzlepart2no10-sortableTrash" class="sortable-code"></div> 
<div id="puzzlepart2no10-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzlepart2no10-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzlepart2no10-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "for i in range (0,10,2):\n" +
    "    if i==6:\n" +
    "        break\n" +
    "    print (i)\n" +
    "while True:\n" +
    "    print(&quot;Hello World!&quot;)\n" +
    "    x = input(&quot;&gt;&gt;&gt; &quot;)\n" +
    "    if x==&quot;x&quot;:\n" +
    "        break\n" +
    "print(&quot;You have entered &#039;x&#039;!&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzlepart2no10-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "puzzlepart2no10-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzlepart2no10-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzlepart2no10-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 11
## Drag the code in the correct order - don't forget the indents!

<div id="puzzlepart2no11-sortableTrash" class="sortable-code"></div> 
<div id="puzzlepart2no11-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzlepart2no11-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzlepart2no11-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "num = int(input(&#039;Please enter a whole number between 1 and 20 &gt;&gt;&gt; &#039;))\n" +
    "    \n" +
    "while num not in range(1,20):\n" +
    "    if num &lt; 1 :\n" +
    "        print(&#039;Range is too low.&#039;)\n" +
    "        num = int(input(&#039;Please enter a whole number between 1 and 20 &gt;&gt;&gt; &#039;))\n" +
    "    elif num &gt; 20:\n" +
    "        print(&#039;Range is too high.&#039;)\n" +
    "        num = int(input(&#039;Please enter a whole number between 1 and 20 &gt;&gt;&gt; &#039;))\n" +
    "print(&#039;Thank you. Your entry is in the correct range&#039;";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzlepart2no11-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "puzzlepart2no11-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzlepart2no11-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzlepart2no11-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 12
## Drag the code in the correct order - don't forget the indents!

<div id="puzzlepart2no12-sortableTrash" class="sortable-code"></div> 
<div id="puzzlepart2no12-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzlepart2no12-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzlepart2no12-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "mark = int(input(&quot;Enter test score: &quot;))\n" +
    "if mark &lt;= 49:\n" +
    "    print (&quot;Grade D: Please attend resit&quot;)\n" +
    "elif mark &gt;50 and mark &lt;56:\n" +
    "    print (&quot;Grade C - needs improvement&quot;)\n" +
    "elif mark &gt;=56 and mark &lt;65:\n" +
    "    print (&quot;Grade B - good work&quot;)\n" +
    "elif mark &gt;=65 and mark &lt;70:\n" +
    "    print (&quot;Grade A - well done&quot;)\n" +
    "else:\n" +
    "    print (&quot;Grade A* - excellent!&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzlepart2no12-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "puzzlepart2no12-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzlepart2no12-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzlepart2no12-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 13
## Drag the code in the correct order - don't forget the indents!

<div id="puzzlepart2no13-sortableTrash" class="sortable-code"></div> 
<div id="puzzlepart2no13-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzlepart2no13-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzlepart2no13-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "nums1 = [5,3,7,9,15,12]\n" +
    "nums2 = [7,5,9,11,16,8]\n" +
    "for x in nums1:\n" +
    "    for y in nums2:\n" +
    "        if x == y:\n" +
    "            print(&quot;{0} in both arrays&quot;.format(x))";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzlepart2no13-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "puzzlepart2no13-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzlepart2no13-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzlepart2no13-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 14
## Drag the code in the correct order - don't forget the indents!

<div id="puzzlepart2no14-sortableTrash" class="sortable-code"></div> 
<div id="puzzlepart2no14-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzlepart2no14-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzlepart2no14-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "from random import*\n" +
    "from time import*\n" +
    "passwordslist=[&quot;Moat123&quot;,&quot;Banana110&quot;,&quot;East&amp;West!&quot;,&quot;MyO4word&quot;]\n" +
    "while True:\n" +
    "    password=choice(passwordslist)\n" +
    "    print(password)\n" +
    "    sleep(1)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzlepart2no14-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "puzzlepart2no14-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzlepart2no14-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzlepart2no14-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 15
## Random Number Guessing Game
## Drag the code in the correct order - don't forget the indents!

<div id="puzzle15-sortableTrash" class="sortable-code"></div> 
<div id="puzzle15-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle15-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle15-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "import random\"\n" +
    "secret = random.randint(1, 10)\n" +
    "guess = int(input(&quot;Guess: &quot;))\n" +
    "while guess != secret:\n" +
    "    guess = int(input(&quot;Try again: &quot;))\n" +
    "print(&quot;Correct!&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle15-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "python3": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzle15-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle15-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>


## Puzzle 16
## Dice Roller
## Drag the code in the correct order - don't forget the indents!

<div id="puzzle16-sortableTrash" class="sortable-code"></div> 
<div id="puzzle16-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle16-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle16-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "import random\n" +
    "dice = random.randint(1, 6)\n" +
    "print(&quot;You rolled&quot;)\n" +
    "print(dice)\n" +
    "";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle16-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "python3": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzle16-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle16-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>


## Puzzle 17
## Countdown Timer
## Drag the code in the correct order - don't forget the indents!

<div id="puzzle17-sortableTrash" class="sortable-code"></div> 
<div id="puzzle17-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle17-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle17-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "import time\n" +
    "for count in range(5, 0, -1):\n" +
    "    print(count)\n" +
    "    time.sleep(1)\n" +
    "print(&quot;Go!&quot;)\n" +
    "";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle17-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "python3": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzle17-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle17-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 18
## Random Password Generator
## Drag the code in the correct order - don't forget the indents!

<div id="puzzle18-sortableTrash" class="sortable-code"></div> 
<div id="puzzle18-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle18-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle18-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "import random\n" +
    "letters = &quot;ABCDEF123456&quot;\n" +
    "password = &quot;&quot;\n" +
    "for i in range(6):\n" +
    "    password = password + random.choice(letters)\n" +
    "print(password)\n" +
    "";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle18-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "python3": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzle18-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle18-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 19
## Square Root Calculator
## Drag the code in the correct order - don't forget the indents!

<div id="puzzle19-sortableTrash" class="sortable-code"></div> 
<div id="puzzle19-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle19-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle19-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "import math\n" +
    "number = int(input(&quot;Enter number: &quot;))\n" +
    "answer = math.sqrt(number)\n" +
    "print(answer)\n" +
    "";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle19-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "python3": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzle19-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle19-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 20
## Area of Circle
## Drag the code in the correct order - don't forget the indents!

<div id="puzzle20-sortableTrash" class="sortable-code"></div> 
<div id="puzzle20-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle20-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle20-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "import math\n" +
    "radius = float(input())\n" +
    "area = math.pi * radius ** 2\n" +
    "print(area)\n" +
    "";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle20-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "python3": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzle20-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle20-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 21
## Random Student Picker
## Drag the code in the correct order - don't forget the indents!

<div id="puzzle21-sortableTrash" class="sortable-code"></div> 
<div id="puzzle21-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle21-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle21-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "import random\n" +
    "students = [\n" +
    "&quot;Ben&quot;,\n" +
    "&quot;Aisha&quot;,\n" +
    "&quot;Luca&quot;,\n" +
    "&quot;Sam&quot;\n" +
    "]\n" +
    "chosen = random.choice(students)\n" +
    "print(chosen)\n" +
    "";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle21-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "python3": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzle21-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle21-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 22
## Stopwatch
## Drag the code in the correct order - don't forget the indents!

<div id="puzzle22-sortableTrash" class="sortable-code"></div> 
<div id="puzzle22-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle22-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle22-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "import time\n" +
    "start = time.time()\n" +
    "input(&quot;Press Enter&quot;)\n" +
    "end = time.time()\n" +
    "print(end - start)\n" +
    "";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle22-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "python3": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzle22-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle22-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 23
## Coin Toss Simulator
## Drag the code in the correct order - don't forget the indents

<div id="puzzle23-sortableTrash" class="sortable-code"></div> 
<div id="puzzle23-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle23-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle23-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "import random\n" +
    "flip = random.choice(\n" +
    "[&quot;Heads&quot;, &quot;Tails&quot;]\n" +
    ")\n" +
    "if flip == &quot;Heads&quot;:\n" +
    "    print(&quot;Win&quot;)\n" +
    "else:\n" +
    "    print(&quot;Lose&quot;)\n" +
    "";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle23-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "python3": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzle23-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle23-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 24
## Random Multiplication Quiz

## Drag the code in the correct order - don't forget the indents

<div id="puzzle24-sortableTrash" class="sortable-code"></div> 
<div id="puzzle24-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle24-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle24-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "import random\n" +
    "num1 = random.randint(1,12)\n" +
    "num2 = random.randint(1,12)\n" +
    "nswer = int(input(f&quot;{num1} x {num2}: &quot;))\n" +
    "if answer == num1 * num2:\n" +
    "    print(&quot;Correct&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle24-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "python3": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzle24-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle24-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>
