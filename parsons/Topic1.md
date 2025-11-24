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
    "print(&quot;Nice to meet you,&quot;, name)";
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
    "print(&quot;Nice to meet you,&quot;, name)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "3-sortable",
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
    "print(&quot;Nice to meet you,&quot;, name)";
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

## Puzzle 6 Simple shopping program
## Place the correct coding in the correct order!

<div id="6-sortableTrash" class="sortable-code"></div> 
<div id="6-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="6-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="6-newInstanceLink" value="Reset Problem" type="button" /> 
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
    "print(&quot;Thank you for shopping!&quot;)
\n" +
    "";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "6-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "6-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#6-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#6-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 7 Temperature converter
## Place the coding in the correct order!

<div id="7-sortableTrash" class="sortable-code"></div> 
<div id="7-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="7-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="7-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "print(&quot;Temperature Converter&quot;)
\n" +
    "
\n" +
    "celsius = float(input(&quot;Enter temperature in Celsius: &quot;))
\n" +
    "
\n" +
    "fahrenheit = (celsius * 9/5) + 32
\n" +
    "
\n" +
    "print(&quot;In Fahrenheit, that is:&quot;, fahrenheit)
\n" +
    "
\n" +
    "";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "7-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "7-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#7-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#7-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 8 Basic quiz program
## Place the coding in the correct order!

<div id="8-sortableTrash" class="sortable-code"></div> 
<div id="8-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="8-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="8-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "print(&quot;Welcome to the mini quiz!&quot;)
\n" +
    "
\n" +
    "score = 0
\n" +
    "
\n" +
    "answer1 = input(&quot;Q1: What colour is the sky? &quot;)
\n" +
    "if answer1.lower() == &quot;blue&quot;:
\n" +
    "    print(&quot;Correct!&quot;)
\n" +
    "    score = score + 1
\n" +
    "else:
\n" +
    "    print(&quot;Incorrect.&quot;)
\n" +
    "
\n" +
    "answer2 = input(&quot;Q2: How many days are in a week? &quot;)
\n" +
    "if answer2 == &quot;7&quot;:
\n" +
    "    print(&quot;Correct!&quot;)
\n" +
    "    score = score + 1
\n" +
    "else:
\n" +
    "    print(&quot;Incorrect.&quot;)
\n" +
    "
\n" +
    "print(&quot;You scored&quot;, score, &quot;out of 2!&quot;)
\n" +
    "
\n" +
    "";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "8-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "8-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#8-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#8-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 9 Casting your age
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

## Puzzle 10 Name and age story generator
## Place the coding in the correct order!

<div id="10-sortableTrash" class="sortable-code"></div> 
<div id="10-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="10-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="10-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "print(&quot;Story Generator&quot;)
\n" +
    "
\n" +
    "name = input(&quot;Enter your name: &quot;)
\n" +
    "age = input(&quot;Enter your age: &quot;)
\n" +
    "hobby = input(&quot;Enter a hobby: &quot;)
\n" +
    "
\n" +
    "print()
\n" +
    "print(&quot;Here is your story:&quot;)
\n" +
    "print(name, &quot;is&quot;, age, &quot;years old and loves&quot;, hobby + &quot;.&quot;)
\n" +
    "print(&quot;Every day,&quot;, name, &quot;practices&quot;, hobby, &quot;and gets better and better!&quot;)
\n" +
    "";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "10-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "10-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#10-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#10-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 11 Simple calculator
## Place the coding in the correct order!

<div id="11-sortableTrash" class="sortable-code"></div> 
<div id="11-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="11-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="11-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "print(&quot;Simple Calculator&quot;)
\n" +
    "print(&quot;1 = Add&quot;)
\n" +
    "print(&quot;2 = Subtract&quot;)
\n" +
    "print(&quot;3 = Multiply&quot;)
\n" +
    "print(&quot;4 = Divide&quot;)
\n" +
    "
\n" +
    "choice = input(&quot;Choose an option (1-4): &quot;)
\n" +
    "
\n" +
    "num1 = float(input(&quot;Enter first number: &quot;))
\n" +
    "num2 = float(input(&quot;Enter second number: &quot;))
\n" +
    "
\n" +
    "if choice == &quot;1&quot;:
\n" +
    "    print(&quot;Answer:&quot;, num1 + num2)
\n" +
    "elif choice == &quot;2&quot;:
\n" +
    "    print(&quot;Answer:&quot;, num1 - num2)
\n" +
    "elif choice == &quot;3&quot;:
\n" +
    "    print(&quot;Answer:&quot;, num1 * num2)
\n" +
    "elif choice == &quot;4&quot;:
\n" +
    "    print(&quot;Answer:&quot;, num1 / num2)
\n" +
    "else:
\n" +
    "    print(&quot;Invalid choice!&quot;)
\n" +
    "";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "11-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "11-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#11-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#11-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 12 Total price calculator
## Place the coding in order!

<div id="12-sortableTrash" class="sortable-code"></div> 
<div id="12-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="12-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="12-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "price1 = float(input(&quot;Price 1: &quot;))
\n" +
    "price2 = float(input(&quot;Price 2: &quot;))
\n" +
    "price3 = float(input(&quot;Price 3: &quot;))
\n" +
    "
\n" +
    "total = price1 + price2 + price3
\n" +
    "print(&quot;Total cost =&quot;, total)
\n" +
    "
\n" +
    "";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "12-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "12-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#12-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#12-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 13 Simple greeting story
## Place the coding in order!

<div id="13-sortableTrash" class="sortable-code"></div> 
<div id="13-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="13-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="13-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "name = input(&quot;Enter your name: &quot;)
\n" +
    "age = input(&quot;Enter your age: &quot;)
\n" +
    "
\n" +
    "print(&quot;Hello&quot;, name)
\n" +
    "print(&quot;You are&quot;, age, &quot;years old&quot;)
\n" +
    "print(&quot;Nice to meet you!&quot;)
\n" +
    "
\n" +
    "";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "13-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "13-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#13-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#13-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 14 Convert minutes to hours/minutes
## Place the coding in order!

<div id="14-sortableTrash" class="sortable-code"></div> 
<div id="14-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="14-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="14-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "mins = int(input(&quot;Enter minutes: &quot;))
\n" +
    "
\n" +
    "hours = mins // 60
\n" +
    "leftover = mins % 60
\n" +
    "
\n" +
    "print(&quot;Hours:&quot;, hours)
\n" +
    "print(&quot;Minutes:&quot;, leftover)
\n" +
    "
\n" +
    "";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "14-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "14-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#14-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#14-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 15 Temperature check
## Place the coding in order!

<div id="15-sortableTrash" class="sortable-code"></div> 
<div id="15-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="15-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="15-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "temp = int(input(&quot;Enter temperature: &quot;))
\n" +
    "
\n" +
    "if temp &gt; 20:
\n" +
    "    print(&quot;Warm&quot;)
\n" +
    "else:
\n" +
    "    print(&quot;Cold&quot;)
\n" +
    "
\n" +
    "";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "15-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "15-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#15-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#15-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 16 Item quantity multiplier
## Place the coding in order!

<div id="16-sortableTrash" class="sortable-code"></div> 
<div id="16-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="16-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="16-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "item = input(&quot;Item name: &quot;)
\n" +
    "amount = int(input(&quot;How many? &quot;))
\n" +
    "price = float(input(&quot;Price each: &quot;))
\n" +
    "
\n" +
    "total = amount * price
\n" +
    "print(&quot;You spent £&quot;, total)
\n" +
    "
\n" +
    "  
\n" +
    "";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "16-sortable",
    "max_wrong_lines": 10,
    "grader": ParsonsWidget._graders.LineBasedGrader,
    "exec_limit": 2500,
    "can_indent": true,
    "x_indent": 50,
    "lang": "en",
    "show_feedback": true,
    "trashId": "16-sortableTrash"
  });
  parsonsPuzzle.init(initial);
  parsonsPuzzle.shuffleLines();
  $("#16-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#16-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 17
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
