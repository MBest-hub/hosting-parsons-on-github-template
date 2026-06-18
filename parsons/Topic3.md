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


## 16. Menu System (6 marks)
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


## 17. Caesar Cipher (6 marks)
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


## 18. Number Frequency Counter (6 marks)
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

## Puzzle 19 Ticket booking system (6 marks)
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

## Puzzle 20 Password strength checker (6 marks)
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

## Puzzle 21 Find the largest number in a list (7 marks)
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

## Puzzle 22 Guess the random number (6 marks)
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

## Puzzle 23 Frequency counter (6 marks)
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

## Puzzle 24 Menu system using functions (8 marks)
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

## Puzzle 25 Two-Dimensional Array Seating Plan (8 marks)
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

