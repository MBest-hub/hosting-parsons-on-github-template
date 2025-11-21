---
layout: default
title: Michelle
---
## Puzzle 1 
## Drag the correct coding
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
## Place the correct coding in the correct order!
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


## Puzzle 3 Ask for the user's name
## Place the correct coding in the correct order!

<div id="3-sortableTrash" class="sortable-code"></div> 
<div id="3-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="3-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="3-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "name = input(&quot;What is your name? &quot;)
\n" +
    "print(&quot;Nice to meet you,&quot;, name)
\n" +
    "name = (&quot;What is your name? &quot;)
\n" +
    "#distractor
\n" +
    "print(&quot;Nice to meet you, name)
\n" +
    "#distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "3-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "3-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#3-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#3-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>
## Puzzle 4 Add two numbers
## Place in the correct order and use only the correct pieces of coding

num1 = float(input("Enter a number: "))
num2 = float(input("Enter another number: "))

total = num1 + num2

print("The total is:", total)


## Puzzle 5 Ask the user's age
## Place the correct coding in the correct order!

<div id="5-sortableTrash" class="sortable-code"></div> 
<div id="5-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="5-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="5-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "age = input(&quot;How old are you? &quot;)
\n" +
    "print(&quot;You are&quot;, age, &quot;years old.&quot;)
\n" +
    "age = input(How old are you? &quot;)
\n" +
    "#distractor
\n" +
    "print &quot;You are&quot;, age, &quot;years old.&quot;
\n" +
    "#distractor
\n" +
    "
\n" +
    "#distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "5-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "5-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#5-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#5-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 6
## Place the correct coding in the correct order!

<div id="puzzle6-sortableTrash" class="sortable-code"></div> 
<div id="puzzle6-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle6-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle6-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "forename=input(&quot;What is your first name? &quot;)\n" +
    "surname=input(&quot;What is your surname? &quot;)\n" +
    "height=input(&quot;What is your height? &quot;)\n" +
    "print(&quot;Hello &quot;,forename,surname,&quot;at &quot;,height,&quot;we are about the same height&quot;)\n" +
    "pets=input(&quot;Do you have any pets? &quot;) #distractor\n" +
    "forename=(&quot;What is your first name? &quot;) #distractor\n" +
    "surname=input(What is your surname? &quot;) #distractor\n" +
    "height=input(&quot;What is your height? &quot; #distractor\n" +
    "print(&quot;Hello &quot;,forename,surname,&quot;at &quot;height,&quot;we are about the same height&quot;) #distractor";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle6-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "puzzle6-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzle6-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle6-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 7
## Place the coding in the correct order!

<div id="puzzle7-sortableTrash" class="sortable-code"></div> 
<div id="puzzle7-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle7-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle7-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "a = [3, 7, 45, 98]\n" +
    "b = [13, 17, 2, 1, 9]\n" +
    "c = a + b\n" +
    "c.sort()\n" +
    "print (c";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle7-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "puzzle7-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#puzzle7-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle7-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 8
## Place the coding in the correct order!

<div id="parsons1Puzzle8-sortableTrash" class="sortable-code"></div> 
<div id="parsons1Puzzle8-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="parsons1Puzzle8-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="parsons1Puzzle8-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "age_input = input(&quot;Enter your age: &quot;)\n" +
    "print(&quot;You entered:&quot;, age_input, &quot;which is a&quot;, type(age_input))";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "parsons1Puzzle8-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#parsons1Puzzle8-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#parsons1Puzzle8-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 9
## Place the coding in the correct order!

<div id="parsons1Puzzle9-sortableTrash" class="sortable-code"></div> 
<div id="parsons1Puzzle9-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="parsons1Puzzle9-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="parsons1Puzzle9-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "age = int(age_input)\n" +
    "print(&quot;After casting, your age is:&quot;, age, &quot;which is a&quot;, type(age))\n" +
    "age_float = float(age_input)\n" +
    "print(&quot;As a float, your age is:&quot;, age_float, &quot;which is a&quot;, type(age_float))\n" +
    "age_str = str(age)\n" +
    "print(&quot;Back to string:&quot;, age_str, &quot;which is a&quot;, type(age_str))";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "parsons1Puzzle9-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#parsons1Puzzle9-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#parsons1Puzzle9-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 10
## Place the coding in the correct order!

<div id="parsons1Puzzle10-sortableTrash" class="sortable-code"></div> 
<div id="parsons1Puzzle10-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="parsons1Puzzle10-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="parsons1Puzzle10-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "length_str = input(&quot;Enter the length of a rectangle (cm): &quot;)\n" +
    "width_str = input(&quot;Enter the width of a rectangle (cm): &quot;)\n" +
    "length = float(length_str)   \n" +
    "width = float(width_str)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "parsons1Puzzle10-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#parsons1Puzzle10-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#parsons1Puzzle10-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 11
## Place the coding in the correct order!

<div id="parsons1Puzzle11-sortableTrash" class="sortable-code"></div> 
<div id="parsons1Puzzle11-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="parsons1Puzzle11-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="parsons1Puzzle11-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "num_str = &quot;42&quot;\n" +
    "print(&quot;Original:&quot;, num_str, &quot;Type:&quot;, type(num_str))\n" +
    "num_int = int(num_str)      \n" +
    "num_float = float(num_str)   \n" +
    "print(&quot;As int:&quot;, num_int, &quot;Type:&quot;, type(num_int))\n" +
    "print(&quot;As float:&quot;, num_float, &quot;Type:&quot;, type(num_float))";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "parsons1Puzzle11-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#parsons1Puzzle11-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#parsons1Puzzle11-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 12
## Place the coding in order!

<div id="parsons1Puzzle12-sortableTrash" class="sortable-code"></div> 
<div id="parsons1Puzzle12-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="parsons1Puzzle12-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="parsons1Puzzle12-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "print(&quot;\nCasting to bool:&quot;)\n" +
    "print(&quot;bool(&#039;Hello&#039;) =&quot;, bool(&quot;Hello&quot;))   \n" +
    "print(&quot;bool(&#039;&#039;) =&quot;, bool(&quot;&quot;))            \n" +
    "print(&quot;bool(0) =&quot;, bool(0))               \n" +
    "print(&quot;bool(5) =&quot;, bool(5))  ";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "parsons1Puzzle12-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#parsons1Puzzle12-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#parsons1Puzzle12-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>
