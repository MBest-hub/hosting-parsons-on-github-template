---
layout: default
title: Michelle
---


## Puzzle 1

<div id="puzzle1part3-sortableTrash" class="sortable-code"></div> 
<div id="puzzle1part3-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle1part3-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle1part3-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "print(&quot;\t\tGame Menu\n&quot;)\n" +
    "print(&quot;\t\tA - Enter Name\n\t\tB - Play Game\n\t\tC - Quit&quot;)\n" +
    "valid_option = [&#039;A&#039;,&#039;B&#039;,&#039;C&#039;]\n" +
    "while True:\n" +
    "    selection = input(&quot;Please enter your choice: &quot;).upper()\n" +
    "    if selection in valid_option:\n" +
    "        print(&quot;That is a valid choice&quot;)\n" +
    "        break\n" +
    "    else:\n" +
    "        print(&quot;That is not a valid choice&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle1part3-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "puzzle1part3-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzle1part3-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle1part3-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>
