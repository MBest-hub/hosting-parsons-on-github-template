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
  var initial = "selection = &#039;&#039;\n" +
    "while selection != &#039;C&#039;:\n" +
    "    selection = display_menu()\n" +
    "    if selection == &#039;A&#039;:\n" +
    "        name = input(&quot;Please enter your name&quot;)\n" +
    "        print(&quot;Hello &quot;,name)\n" +
    "    elif selection == &#039;B&#039;:\n" +
    "        print(&quot;Game is starting&quot;)\n" +
    "if selection == &#039;C&#039;:\n" +
    "    print(&quot;Thank you for playing&quot;)\n" +
    "    sys.exit()";
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
