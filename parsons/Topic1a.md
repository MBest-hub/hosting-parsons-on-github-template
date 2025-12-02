---
layout: default
title: Michelle
---

## Puzzle 1 
##Ask the users name. Drag and drop the correct code to the correct order.

<div id="1a-sortableTrash" class="sortable-code"></div> 
<div id="1a-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="1a-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="1a-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "print (&quot;Hello world!&quot;)\n" +
    "print &quot;Hello world!&quot; #distractor\n" +
    "print (Hello world!) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "1a-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "1a-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#1a-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#1a-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 

</script>

## Puzzle 2
##Add 2 numbers. Drag and drop the correct code to the correct order.

<div id="2a-sortableTrash" class="sortable-code"></div> 
<div id="2a-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="2a-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="2a-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "num1 = float(input(&quot;Enter a number: &quot;))\n" +
    "num2 = float(input(&quot;Enter another number: &quot;))\n" +
    "\n" +
    "total = num1 + num2\n" +
    "\n" +
    "print(&quot;The total is:&quot;, total)\n" +
    "\n" +
    "#distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "2a-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "2a-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#2a-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#2a-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

##Puzzle 3
##Ask the user their age. Drag and drop the correct code to the correct order.

<div id="3a-sortableTrash" class="sortable-code"></div> 
<div id="3a-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="3a-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="3a-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "age = input(&quot;How old are you? &quot;)\n" +
    "print(&quot;You are&quot;, age, &quot;years old.&quot;)\n" +
    "age = input(How old are you? &quot;)\n" +
    "#distractor\n" +
    "print(&quot;You are&quot;, age, &quot;years old.)\n" +
    "#distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "3a-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "3a-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#3a-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#3a-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 4
##Drag and drop - Simple Shopping List

<div id="4a-sortableTrash" class="sortable-code"></div> 
<div id="4a-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="4a-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="4a-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "print(&quot;Welcome to the mini shop!&quot;)
\n" +
    "
\n" +
    "item1 = float(input(&quot;Enter the price of item 1: &quot;))
\n" +
    "item2 = float(input(&quot;Enter the price of item 2: &quot;))
\n" +
    "item3 = float(input(&quot;Enter the price of item 3: &quot;))
\n" +
    "
\n" +
    "total = item1 + item2 + item3
\n" +
    "
\n" +
    "print(&quot;Your total is:&quot;, total)
\n" +
    "print(&quot;Thank you for shopping!&quot;
\n" +
    "
\n" +
    "#distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "4a-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "4a-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#4a-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#4a-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>
