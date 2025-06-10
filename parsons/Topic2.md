---
layout: default
title: Michelle
---
## Puzzle 1
---
layout: default
title: Michelle
---


## Puzzle 1

<div id="parsons1-sortableTrash" class="sortable-code"></div> 
<div id="parsons1-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="parsons1-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="parsons1-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "print (&quot;Hello world!&quot;)\n" +
    "print &quot;Hello world!&quot; #distractor\n" +
    "print (Hello world!) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "parsons1-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "parsons1-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#parsons1-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#parsons1-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>



## Puzzle 2

<div id="parsons2-sortableTrash" class="sortable-code"></div> 
<div id="parsons2-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="parsons2-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="parsons2-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "answer = input(&quot;What has hands but can’t clap? &quot;)\n" +
    "print(&quot;Interesting answer: &quot; + answer)\n" +
    "print(&quot;The real answer is: A clock!&quot;)\n" +
    "answer = input(What has hands but can’t clap? ) #distractor\n" +
    "print&quot;Interesting answer: &quot; + answer #distractor\n" +
    "print(&quot;The real answer is: A clock!) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "parsons2-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "parsons2-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#parsons2-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#parsons2-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 3
<div id="parsons3-sortableTrash" class="sortable-code"></div> 
<div id="parsons3-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="parsons3-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="parsons3-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "eye_colour = input(&quot;What colour are your eyes? &quot;)\n" +
    "print(eye_colour)\n" +
    "eye_colour = input(What colour are your eyes? ) #distractor\n" +
    "eye_colour = input&quot;What colour are your eyes? &quot; #distractor\n" +
    "print eye_colour #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "parsons3-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "parsons3-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#parsons3-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#parsons3-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 4

<div id="parsons4-sortableTrash" class="sortable-code"></div> 
<div id="parsons4-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="parsons4-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="parsons4-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "total_pets=0\n" +
    "dogs = 1\n" +
    "cats = 4\n" +
    "total_pets = dogs + cats\n" +
    "print (&quot;Total number of pets is:&quot;,total_pets)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "parsons4-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "parsons4-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#parsons4-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#parsons4-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>










