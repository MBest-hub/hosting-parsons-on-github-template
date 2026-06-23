---
layout: default
title: Michelle
---
## These are GCSE style exam questions 3-6 Marks!

## Puzzle 1 - Random Dice Roll (3 marks)
## This program, imports a module, generates a random number between 1 and 6, displays the results, drag into order, beware of indents!

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
 

## Puzzle 2 - Positive Number Check (3 marks)
## This program gets a number from the user, Displays "Positive" if above 0, Otherwise displays "Not positive", Drag into order, beware of indents!

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


## Puzzle 3 - Countdown (3 marks)
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

## Puzzle 4 - Square Function (3 marks)
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


## Puzzle 5 - Password Validation (4 marks)
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


## Puzzle 6 - Running Total (4 marks)
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


## Puzzle 7 - Random Multiplication Quiz (4 marks)
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


## Puzzle 8 - Largest Number (4 marks)
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


## Puzzle 9 - Average Calculator (5 marks)
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


## Puzzle 10 - Number Guessing Game (5 marks)
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


## Puzzle 11 - Grade Calculator (5 marks)
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


## Puzzle 12 - Character Counter (5 marks)
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


## Puzzle 13 - Mini Login System (6 marks)
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


## Puzzle 14 - Lottery Simulator (6 marks)
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


## Puzzle 15 - Temperature Tracker (6 marks)
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


## Puzzle 16 - Menu System (6 marks)
## This program will create a menu until Exit.

<div id="puzzle3no16-sortableTrash" class="sortable-code"></div> 
<div id="puzzle3no16-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle3no16-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle3no16-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "choice = &quot;&quot;\n" +
    "while choice != &quot;3&quot;:\n" +
    "    print(&quot;1 Add&quot;)\n" +
    "    print(&quot;2 Remove&quot;)\n" +
    "    print(&quot;3 Exit&quot;)\n" +
    "    choice = input()\n" +
    "print(&quot;Finished&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle3no16-sortable",
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
  $("#puzzle3no16-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle3no16-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>


## Puzzle 17 - Caesar Cipher (6 marks)
## This program will shift letters by +1.

<div id="puzzle3no17-sortableTrash" class="sortable-code"></div> 
<div id="puzzle3no17-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle3no17-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle3no17-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "message = input()\n" +
    "encrypted = &quot;&quot;\n" +
    "for letter in message:\n" +
    "    encrypted += chr(\n" +
    "        ord(letter) + 1)\n" +
    "print(encrypted)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle3no17-sortable",
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
  $("#puzzle3no17-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle3no17-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>


## Puzzle 18 - Number Frequency Counter (6 marks)
## This program counts even numbers.

<div id="puzzle3no18-sortableTrash" class="sortable-code"></div> 
<div id="puzzle3no18-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle3no18-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle3no18-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "count = 0\n" +
    "for i in range(10):\n" +
    "    number = int(input())\n" +
    "    if number % 2 == 0:\n" +
    "        count += 1\n" +
    "print(count)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle3no18-sortable",
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
  $("#puzzle3no18-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle3no18-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 19 - Ticket booking system (6 marks)
## A cinema sells tickets. Asks for the number of tickets, charges £8 per ticket, gives 10% discount if buying 5 or more, outputs the final price.

<div id="puzzle19-sortableTrash" class="sortable-code"></div> 
<div id="puzzle19-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle19-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle19-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "tickets = int(input(&quot;Number of tickets: &quot;))\n" +
    "price = tickets * 8\n" +
    "if tickets &gt;= 5:\n" +
    "    price = price * 0.9\n" +
    "print(&quot;Total price = £&quot;, round(price, 2))";
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

## Puzzle 20 - Password strength checker (6 marks)
## This program asks for a password, checks whether it contains at least 8 characters, outputs "Strong" or "Weak".

<div id="puzzle20-sortableTrash" class="sortable-code"></div> 
<div id="puzzle20-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle20-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle20-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "password = input(&quot;Enter password: &quot;)\n" +
    "if len(password) &gt;= 8:\n" +
    "    print(&quot;Strong&quot;)\n" +
    "else:\n" +
    "    print(&quot;Weak&quot;)";
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

## Puzzle 21 - Find the largest number in a list (7 marks)
## This program A list stores five numbers. Output the largest value.

<div id="puzzle21-sortableTrash" class="sortable-code"></div> 
<div id="puzzle21-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle21-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle21-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "numbers = [12, 45, 9, 77, 32]\n" +
    "largest = numbers[0]\n" +
    "for value in numbers:\n" +
    "    if value &gt; largest:\n" +
    "        largest = value\n" +
    "print(&quot;Largest =&quot;, largest)";
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

## Puzzle 22 - Guess the random number (6 marks)
## This program generates a random number between 1 and 10, allows the user up to 3 guesses, tells them if they win.

<div id="puzzle22-sortableTrash" class="sortable-code"></div> 
<div id="puzzle22-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle22-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle22-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "import random\n" +
    "secret = random.randint(1, 10)\n" +
    "found = False\n" +
    "for attempt in range(3):\n" +
    "    guess = int(input(&quot;Guess: &quot;))\n" +
    "    if guess == secret:\n" +
    "        found = True\n" +
    "        break\n" +
    "if found:\n" +
    "    print(&quot;Correct&quot;)\n" +
    "else:\n" +
    "    print(&quot;Number was&quot;, secret";
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

## Puzzle 23 - Frequency counter (6 marks)
## This program Write stores names in a list and counts how many times "Sam" appears.

<div id="puzzle23-sortableTrash" class="sortable-code"></div> 
<div id="puzzle23-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle23-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle23-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "names = [&quot;Sam&quot;, &quot;Alex&quot;, &quot;Sam&quot;, &quot;Jess&quot;, &quot;Sam&quot;]\n" +
    "\n" +
    "count = 0\n" +
    "\n" +
    "for person in names:\n" +
    "    if person == &quot;Sam&quot;:\n" +
    "        count += 1\n" +
    "\n" +
    "print(count)";
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

## Puzzle 24 - Menu system using functions (8 marks)
## This program has a menu that can add, multiply and exit

<div id="puzzle24-sortableTrash" class="sortable-code"></div> 
<div id="puzzle24-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle24-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle24-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "def add(a, b):\n" +
    "    return a + b\n" +
    "def multiply(a, b):\n" +
    "    return a * b\n" +
    "choice = 0\n" +
    "while choice != 3:\n" +
    "    print(&quot;1 Add&quot;)\n" +
    "    print(&quot;2 Multiply&quot;)\n" +
    "    print(&quot;3 Exit&quot;)\n" +
    "    choice = int(input())\n" +
    "    if choice == 1:\n" +
    "        x = int(input())\n" +
    "        y = int(input())\n" +
    "        print(add(x, y))\n" +
    "    elif choice == 2:\n" +    
      "        x = int(input())\n" +
    "        y = int(input())\n" +
    "        print(multiply(x, y))";
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

## Puzzle 25 - Two-Dimensional Array Seating Plan (6 marks)
## This program stores a seating plan

<div id="puzzle25-sortableTrash" class="sortable-code"></div> 
<div id="puzzle25-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle25-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle25-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "seats = [\n" +
    "    [&quot;X&quot;, &quot;X&quot;, &quot;O&quot;],\n" +
    "    [&quot;O&quot;, &quot;X&quot;, &quot;O&quot;]\n" +
    "]\n" +
    "\n" +
    "available = 0\n" +
    "\n" +
    "for row in seats:\n" +
    "    for seat in row:\n" +
    "        if seat == &quot;O&quot;:\n" +
    "            available += 1\n" +
    "\n" +
    "print(&quot;Available =&quot;, available)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle25-sortable",
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
  $("#puzzle25-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle25-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## These are GCSE style exam questions 6-8 Marks!

## Puzzle 26 - Count Even Numbers (6 marks) 
## A list contains integer values.
## This program stores the values in a list, counts how many values are even, outputs the total

<div id="puzzle26-sortableTrash" class="sortable-code"></div> 
<div id="puzzle26-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle26-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle26-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "numbers = [7, 12, 15, 22, 18, 9]\n" +
    "count = 0\n" +
    "for number in numbers:\n" +
    "    if number % 2 == 0:\n" +
    "        count += 1\n" +
    "print(&quot;Even numbers =&quot;, count)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle26-sortable",
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
  $("#puzzle26-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle26-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 27 - Enter Scores Until Finished (6 marks)
## This program repeatedly asks for a score, stops when the user enters -1, outputs the total score entered.

<div id="puzzle27-sortableTrash" class="sortable-code"></div> 
<div id="puzzle27-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle27-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle27-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "total = 0\n" +
    "score = int(input(&quot;Enter score (-1 to stop): &quot;))\n" +
    "while score != -1:\n" +
    "    total += score\n" +
    "    score = int(input(&quot;Enter score (-1 to stop): &quot;))\n" +
    "print(&quot;Total =&quot;, total)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle27-sortable",
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
  $("#puzzle27-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle27-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 28 - Highest and Lowest (7 marks)
## This puzzle asks for 5 numbers, outputs the highest and lowest values entered.

<div id="puzzle28-sortableTrash" class="sortable-code"></div> 
<div id="puzzle28-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle28-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle28-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "first = int(input(&quot;Enter number: &quot;))\n" +
    "highest = first\n" +
    "lowest = first\n" +
    "for count in range(4):\n" +
    "    number = int(input(&quot;Enter number: &quot;))\n" +
    "    if number &gt; highest:\n" +
    "        highest = number\n" +
    "    if number &lt; lowest:\n" +
    "        lowest = number\n" +
    "print(&quot;Highest =&quot;, highest)\n" +
    "print(&quot;Lowest =&quot;, lowest)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle28-sortable",
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
  $("#puzzle28-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle28-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 29 - Username Validation (7 marks)
## This program asks for a username and repeats until: length is between 5 and 10 characters then outputs "Accepted"

<div id="puzzle29-sortableTrash" class="sortable-code"></div> 
<div id="puzzle29-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle29-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle29-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "username = input(&quot;Enter username: &quot;)\n" +
    "while len(username) &lt; 5 or len(username) &gt; 10:\n" +
    "    print(&quot;Invalid&quot;)\n" +
    "    username = input(&quot;Enter username: &quot;)\n" +
    "print(&quot;Accepted&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle29-sortable",
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
  $("#puzzle29-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle29-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 30 - Search a List (7 marks)
## This program is a list containing names, asks for a name, searches the list, outputs "Found" or "Not Found".

<div id="puzzle30-sortableTrash" class="sortable-code"></div> 
<div id="puzzle30-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle30-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle30-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "names = [&quot;Ali&quot;, &quot;Mia&quot;, &quot;Jake&quot;, &quot;Ava&quot;]\n" +
    "search = input(&quot;Enter name: &quot;)\n" +
    "found = False\n" +
    "for name in names:\n" +
    "    if name == search:\n" +
    "        found = True\n" +
    "if found:\n" +
    "    print(&quot;Found&quot;)\n" +
    "else:\n" +
    "    print(&quot;Not Found&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle30-sortable",
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
  $("#puzzle30-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle30-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 31 - Calculate Average Temperature (8 marks)
## This program stores 7 temperatures in a list, calculates the average, outputs temperatures above the average.

<div id="puzzle31-sortableTrash" class="sortable-code"></div> 
<div id="puzzle31-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle31-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle31-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "temps = [16, 18, 21, 19, 23, 17, 20]\n" +
    "total = 0\n" +
    "for value in temps:\n" +
    "    total += value\n" +
    "average = total / len(temps)\n" +
    "print(&quot;Average =&quot;, average)\n" +
    "for value in temps:\n" +
    "    if value &gt; average:\n" +
    "        print(value)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle31-sortable",
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
  $("#puzzle31-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle31-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 32 - Password Attempts (8 marks) Correct password = "AQA8525"
## This program allows 3 attempts, stops if password entered correctly, outputs "Access Granted" or "Locked".

<div id="puzzle32-sortableTrash" class="sortable-code"></div> 
<div id="puzzle32-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle32-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle32-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "password = &quot;AQA8525&quot;\n" +
    "attempt = 0\n" +
    "success = False\n" +
    "while attempt &lt; 3 and success == False:\n" +
    "    entry = input(&quot;Password: &quot;)\n" +
    "    if entry == password:\n" +
    "        success = True\n" +
    "    attempt += 1\n" +
    "if success:\n" +
    "    print(&quot;Access Granted&quot;)\n" +
    "else:\n" +
    "    print(&quot;Locked&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle32-sortable",
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
  $("#puzzle32-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle32-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 33 - Shopping Basket (8 marks)
## This program stores prices in a list, calculates total, applies: 10% discount if total exceeds £50.

<div id="puzzle33-sortableTrash" class="sortable-code"></div> 
<div id="puzzle33-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle33-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle33-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "prices = [10, 15, 20, 25]\n" +
    "total = 0\n" +
    "for price in prices:\n" +
    "    total += price\n" +
    "if total &gt; 50:\n" +
    "    total = total * 0.9\n" +
    "print(&quot;Total = £&quot;, round(total, 2))";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle33-sortable",
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
  $("#puzzle33-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle33-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 34 - Count Positive and Negative Numbers (6 marks)
## This program stores numbers in a list, counts positive values, counts negative values, outputs both totals.

<div id="puzzle34-sortableTrash" class="sortable-code"></div> 
<div id="puzzle34-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle34-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle34-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "numbers = [-5, 7, 3, -2, 8, -1]\n" +
    "positive = 0\n" +
    "negative = 0\n" +
    "for value in numbers:\n" +
    "    if value &gt; 0:\n" +
    "        positive += 1\n" +
    "    elif value &lt; 0:\n" +
    "        negative += 1\n" +
    "print(&quot;Positive =&quot;, positive)\n" +
    "print(&quot;Negative =&quot;, negative)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle34-sortable",
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
  $("#puzzle34-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle34-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 35 - Find Multiples of 5 (6 marks)
## This program asks the user to enter 8 numbers, counts how many are multiples of 5, outputs the total.

<div id="puzzle35-sortableTrash" class="sortable-code"></div> 
<div id="puzzle35-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle35-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle35-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "count = 0\n" +
    "for number in range(8):\n" +
    "    value = int(input(&quot;Enter number: &quot;))\n" +
    "    if value % 5 == 0:\n" +
    "        count += 1\n" +
    "print(&quot;Multiples of 5 =&quot;, count)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle35-sortable",
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
  $("#puzzle35-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle35-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 36 - Secret Number Game (7 marks)
## This program stores the secret number 24, repeatedly asks for guesses, stops when correct, outputs the number of attempts.

<div id="puzzle36-sortableTrash" class="sortable-code"></div> 
<div id="puzzle36-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle36-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle36-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "secret = 24\n" +
    "attempts = 0\n" +
    "guess = -1\n" +
    "while guess != secret:\n" +
    "    guess = int(input(&quot;Guess: &quot;))\n" +
    "    attempts += 1\n" +
    "print(&quot;Correct&quot;)\n" +
    "print(&quot;Attempts =&quot;, attempts)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle36-sortable",
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
  $("#puzzle36-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle36-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 37 - Total Cost with Validation (7 marks)
## This program asks for quantity, quantity must be between 1 and 10, calculates total cost (£6 each)

<div id="puzzle37-sortableTrash" class="sortable-code"></div> 
<div id="puzzle37-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle37-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle37-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "quantity = int(input(&quot;Quantity: &quot;))\n" +
    "while quantity &lt; 1 or quantity &gt; 10:\n" +
    "    print(&quot;Invalid&quot;)\n" +
    "    quantity = int(input(&quot;Quantity: &quot;))\n" +
    "total = quantity * 6\n" +
    "print(&quot;Total = £&quot;, total)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle37-sortable",
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
  $("#puzzle37-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle37-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 38 - Reverse a List (7 marks)
## This program stores numbers in a list, outputs them in reverse order.

<div id="puzzle38-sortableTrash" class="sortable-code"></div> 
<div id="puzzle38-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle38-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle38-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "numbers = [3, 6, 9, 12]\n" +
    "for index in range(len(numbers)-1, -1, -1):\n" +
    "    print(numbers[index])";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle38-sortable",
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
  $("#puzzle38-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle38-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 39 - Count Vowels (6 marks)
## This program asks the user for a word, counts vowels, outputs the total

<div id="puzzle39-sortableTrash" class="sortable-code"></div> 
<div id="puzzle39-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle39-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle39-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "word = input(&quot;Enter word: &quot;)\n" +
    "count = 0\n" +
    "for letter in word:\n" +
    "    if letter in &quot;aeiouAEIOU&quot;:\n" +
    "        count += 1\n" +
    "print(&quot;Vowels =&quot;, count)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle39-sortable",
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
  $("#puzzle39-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle39-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 40 - Enter and Store Names (8 marks)
## This program allows the user to enter 5 names, stores them in a list, displays all names entered.

<div id="puzzle40-sortableTrash" class="sortable-code"></div> 
<div id="puzzle40-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle40-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle40-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "names = []\n" +
    "for count in range(5):\n" +
    "    name = input(&quot;Enter name: &quot;)\n" +
    "    names.append(name)\n" +
    "for item in names:\n" +
    "    print(item)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle40-sortable",
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
  $("#puzzle40-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle40-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 41 - Mini Login System (8 marks) Username = admin, Password = python
## This program asks for username and password, allows 3 attempts, outputs "Access Granted" or "Account Locked".

<div id="puzzle41-sortableTrash" class="sortable-code"></div> 
<div id="puzzle41-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle41-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle41-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "attempt = 0\n" +
    "success = False\n" +
    "while attempt &lt; 3 and success == False:\n" +
    "    username = input(&quot;Username: &quot;)\n" +
    "    password = input(&quot;Password: &quot;)\n" +
    "    if username == &quot;admin&quot; and password == &quot;python&quot;:\n" +
    "        success = True\n" +
    "    attempt += 1\n" +
    "if success:\n" +
    "    print(&quot;Access Granted&quot;)\n" +
    "else:\n" +
    "    print(&quot;Account Locked&quot;)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle41-sortable",
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
  $("#puzzle41-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle41-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 42 - Find Average and Highest (8 marks)
## This program stores 6 numbers, calculates average, outputs highest value.

<div id="puzzle42-sortableTrash" class="sortable-code"></div> 
<div id="puzzle42-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle42-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle42-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "numbers = [12, 25, 8, 31, 19, 14]\n" +
    "total = 0\n" +
    "highest = numbers[0]\n" +
    "for value in numbers:\n" +
    "    total += value\n" +
    "    if value &gt; highest:\n" +
    "        highest = value\n" +
    "average = total / len(numbers)\n" +
    "print(&quot;Average =&quot;, average)\n" +
    "print(&quot;Highest =&quot;, highest)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle42-sortable",
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
  $("#puzzle42-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle42-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 43 - Count Letter Occurrences (8 marks)
## This program asks for a sentence, asks for a letter, counts occurrences of the letter.

<div id="puzzle43-sortableTrash" class="sortable-code"></div> 
<div id="puzzle43-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle43-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle43-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "sentence = input(&quot;Sentence: &quot;)\n" +
    "letter = input(&quot;Letter: &quot;)\n" +
    "count = 0\n" +
    "for character in sentence:\n" +
    "    if character == letter:\n" +
    "        count += 1\n" +
    "print(&quot;Occurrences =&quot;, count)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle43-sortable",
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
  $("#puzzle43-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle43-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## These are GCSE style exam questions higher marks!
## Puzzle 44  - Student Score Analysis (8 marks)
## This program asks the user to enter 10 test scores, stores them in a list outputs: highest score, lowest score, average score and number of scores above average

<div id="puzzle44-sortableTrash" class="sortable-code"></div> 
<div id="puzzle44-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle44-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle44-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "scores = []\n" +
    "for count in range(10):\n" +
    "\n" +
    "    score = int(input(&quot;Enter score: &quot;))\n" +
    "    scores.append(score)\n" +
    "\n" +
    "highest = scores[0]\n" +
    "lowest = scores[0]\n" +
    "total = 0\n" +
    "for score in scores:\n" +
    "    total += score\n" +
    "    if score &gt; highest:\n" +
    "        highest = score\n" +
    "    if score &lt; lowest:\n" +
    "        lowest = score\n" +
    "average = total / len(scores)\n" +
    "above = 0\n" +
    "for score in scores:\n" +
    "    if score &gt; average:\n" +
    "        above += 1\n" +
    "print(&quot;Highest =&quot;, highest)\n" +
    "print(&quot;Lowest =&quot;, lowest)\n" +
    "print(&quot;Average =&quot;, average)\n" +
    "print(&quot;Above Average =&quot;, above)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle44-sortable",
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
  $("#puzzle44-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle44-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 45  - Ticket Booking with Remaining Seats (8 marks) A theatre has 50 seats.
## This program repeatedly asks users how many tickets they want, subtracts tickets from available seats, stops when: seats reach 0 OR user enters 0, output seats remaining

<div id="puzzle45-sortableTrash" class="sortable-code"></div> 
<div id="puzzle45-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="puzzle45-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="puzzle45-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "seats = 50\n" +
    "while seats &gt; 0:\n" +
    "    print(&quot;Seats remaining:&quot;, seats)\n" +
    "    booking = int(input(&quot;Tickets (0 to stop): &quot;))\n" +
    "    if booking == 0:\n" +
    "        break\n" +
    "    while booking &gt; seats:\n" +
    "        print(&quot;Not enough seats&quot;)\n" +
    "        booking = int(input())\n" +
    "    seats -= booking\n" +
    "print(&quot;Booking closed&quot;)\n" +
    "print(&quot;Remaining =&quot;, seats)";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "puzzle45-sortable",
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
  $("#puzzle45-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#puzzle45-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 46  - 
## This program
