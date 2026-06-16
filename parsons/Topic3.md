---
layout: default
title: Michelle
---
## These are GCSE style exam questions!

## 1. Random Dice Roll (3 marks)
## This program:
## Imports a module
## Generates a random number between 1 and 6
## Displays the result
## Drag into order, beware of indents!

<div id="puzzle3no1-sortableTrash" class="sortable-code"></div> 
<div id="puzzle3no1-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle3no1-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle3no1-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "import random\n" +
    "dice = random.randint(1, 6)\n" +
    "print(&quot;You rolled&quot;, dice)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle3no1-sortable",
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
  $("#puzzle3no1-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle3no1-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>
 

## 2. Positive Number Check (3 marks)
## This program:
## Gets a number from the user
## Displays "Positive" if above 0
## Otherwise displays "Not positive"
## Drag into order, beware of indents!

<div id="puzzle3no2-sortableTrash" class="sortable-code"></div> 
<div id="puzzle3no2-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle3no2-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle3no2-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "number = int(input(&quot;Enter number: &quot;))\n" +
    "if number &gt; 0:\n" +
    "    print(&quot;Positive&quot;)\n" +
    "else:\n" +
    "    print(&quot;Not positive&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle3no2-sortable",
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
  $("#puzzle3no2-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle3no2-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>


## 3. Countdown (3 marks)
## This program:
## Counts from 5 to 1
## Displays "GO!"
## This program:
## Drag into order, beware of indents!

<div id="puzzle3no3-sortableTrash" class="sortable-code"></div> 
<div id="puzzle3no3-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle3no3-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle3no3-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "for count in range(5, 0, -1):\n" +
    "    print(count)\n" +
    "print(&quot;GO!&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle3no3-sortable",
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
  $("#puzzle3no3-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle3no3-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## 4. Square Function (3 marks)
## This program:
## Write a function called square() that:
## Accepts one parameter
## Returns the square
## Drag into order, beware of indents!

<div id="puzzle3no4-sortableTrash" class="sortable-code"></div> 
<div id="puzzle3no4-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle3no4-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle3no4-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "def square(number):\n" +
    "    return number * number\n" +
    "answer = square(4)\n" +
    "print(answer)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle3no4-sortable",
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
  $("#puzzle3no4-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle3no4-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>


## 5. Password Validation (4 marks)
## A program that repeatedly ask for a password until "computer" is entered.
## Drag into order, beware of indents!

<div id="puzzle3no5-sortableTrash" class="sortable-code"></div> 
<div id="puzzle3no5-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle3no5-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle3no5-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "password = &quot;&quot;\n" +
    "while password != &quot;computer&quot;:\n" +
    "    password = input(&quot;Password: &quot;)\n" +
    "print(&quot;Access Granted&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle3no5-sortable",
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
  $("#puzzle3no5-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle3no5-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>


## 6. Running Total (4 marks)
## This program allows you to input 5 numbers and display the total.
## Drag into order, beware of indents!

<div id="puzzle3no6-sortableTrash" class="sortable-code"></div> 
<div id="puzzle3no6-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle3no6-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle3no6-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "total = 0\n" +
    "for i in range(5):\n" +
    "    number = int(input())\n" +
    "    total = total + number\n" +
    "print(total)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle3no6-sortable",
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
  $("#puzzle3no6-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle3no6-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>


## 7. Random Multiplication Quiz (4 marks)
## This program will generate two random numbers and check answer.

<div id="puzzle3no7-sortableTrash" class="sortable-code"></div> 
<div id="puzzle3no7-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle3no7-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle3no7-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "import random\n" +
    "num1 = random.randint(1, 10)\n" +
    "num2 = random.randint(1, 10)\n" +
    "answer = int(\n" +
    "    input(str(num1) + &quot; x &quot; + str(num2) + &quot;: &quot;))\n" +
    "if answer == num1 * num2:\n" +
    "    print(&quot;Correct&quot;)\n" +
    "else:\n" +
    "    print(&quot;Wrong&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle3no7-sortable",
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
  $("#puzzle3no7-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle3no7-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>


## 8. Largest Number (4 marks)
## This program allows the users to input 5 numbers and display largest.

<div id="puzzle3no8-sortableTrash" class="sortable-code"></div> 
<div id="puzzle3no8-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle3no8-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle3no8-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "largest = 0\n" +
    "for i in range(5):\n" +
    "    num = int(input())\n" +
    "    if num &gt; largest:\n" +
    "        largest = num\n" +
    "print(largest)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle3no8-sortable",
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
  $("#puzzle3no8-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle3no8-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>


## 9. Average Calculator (5 marks)
## This program stores 5 values in a list and display average.

<div id="puzzle3no9-sortableTrash" class="sortable-code"></div> 
<div id="puzzle3no9-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle3no9-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle3no9-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "numbers = []\n" +
    "for i in range(5):\n" +
    "    value = int(input())\n" +
    "    numbers.append(value)\n" +
    "average = sum(numbers) / len(numbers)\n" +
    "print(average)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle3no9-sortable",
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
  $("#puzzle3no9-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle3no9-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>


## 10. Number Guessing Game (5 marks)
## This program will generate a random number and count attempts to guess it.

<div id="puzzle3no10-sortableTrash" class="sortable-code"></div> 
<div id="puzzle3no10-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle3no10-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle3no10-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "import random\n" +
    "secret = random.randint(1, 20)\n" +
    "attempts = 0\n" +
    "guess = 0\n" +
    "while guess != secret:\n" +
    "    guess = int(input())\n" +
    "    attempts += 1\n" +
    "print(&quot;Correct&quot;)\n" +
    "print(&quot;Attempts:&quot;, attempts)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle3no10-sortable",
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
  $("#puzzle3no10-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle3no10-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>


## 11. Grade Calculator (5 marks)
## This program will ask for a mark and output grade:
## A = 70+
## B = 50–69
## C = below 50

<div id="puzzle3no11-sortableTrash" class="sortable-code"></div> 
<div id="puzzle3no11-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle3no11-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle3no11-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "mark = int(input())\n" +
    "if mark &gt;= 70:\n" +
    "    print(&quot;A&quot;)\n" +
    "elif mark &gt;= 50:\n" +
    "    print(&quot;B&quot;)\n" +
    "else:\n" +
    "    print(&quot;C&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle3no11-sortable",
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
  $("#puzzle3no11-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle3no11-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>


## 12. Character Counter (5 marks)
## This program counts vowels in a word.

<div id="puzzle3no12-sortableTrash" class="sortable-code"></div> 
<div id="puzzle3no12-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle3no12-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle3no12-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "word = input()\n" +
    "count = 0\n" +
    "for letter in word:\n" +
    "    if letter in &quot;aeiou&quot;:        count += 1\n" +
    "print(count)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle3no12-sortable",
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
  $("#puzzle3no12-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle3no12-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>


## 13. Mini Login System (6 marks)
## This allow 3 attempts to login.

<div id="puzzle3no13-sortableTrash" class="sortable-code"></div> 
<div id="puzzle3no13-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle3no13-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle3no13-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "username = &quot;admin&quot;\n" +
    "password = &quot;8525&quot;\n" +
    "attempt = 0\n" +
    "while attempt &lt; 3:\n" +
    "    user = input()\n" +
    "    pw = input()\n" +
    "    if user == username and pw == password:\n" +
    "        print(&quot;Access granted&quot;)\n" +
    "        break\n" +
    "    attempt += 1\n" +
    "if attempt == 3:\n" +
    "    print(&quot;Account locked&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle3no13-sortable",
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
  $("#puzzle3no13-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle3no13-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>


## 14. Lottery Simulator (6 marks)
## This program will generate six random numbers.

<div id="puzzle3no14-sortableTrash" class="sortable-code"></div> 
<div id="puzzle3no14-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle3no14-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle3no14-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "import random\n" +
    "numbers = []\n" +
    "for i in range(6):\n" +
    "    value = random.randint(1, 59)\n" +
    "    numbers.append(value)\n" +
    "print(numbers)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle3no14-sortable",
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
  $("#puzzle3no14-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle3no14-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>


## 15. Temperature Tracker (6 marks)
## This program stores temperatures and output highest, lowest and average.

<div id="puzzle3no15-sortableTrash" class="sortable-code"></div> 
<div id="puzzle3no15-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle3no15-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle3no15-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "temps = []\n" +
    "for i in range(7):\n" +
    "    value = int(input())\n" +
    "    temps.append(value)\n" +
    "print(&quot;Highest:&quot;, max(temps))\n" +
    "print(&quot;Lowest:&quot;, min(temps))\n" +
    "print(&quot;Average:&quot;,\n" +
    "      sum(temps) / len(temps))";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle3no15-sortable",
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
  $("#puzzle3no15-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle3no15-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>
