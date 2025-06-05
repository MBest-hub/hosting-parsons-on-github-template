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
</script



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








