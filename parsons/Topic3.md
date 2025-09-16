---
layout: default
title: Michelle
---


## Puzzle 1
## Drag into order, beware of indents!

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

## Puzzle 2
## Drag into order, beware of indents!

<div id="parsons3Puzzle2-sortableTrash" class="sortable-code"></div> 
<div id="parsons3Puzzle2-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="parsons3Puzzle2-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="parsons3Puzzle2-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "def get_mark():\n" +
    "    \n" +
    "    mark = int(input(&quot;Enter your exam mark (0-100): &quot;))\n" +
    "    return mark\n" +
    "def calculate_grade(mark):\n" +
    "    if mark &gt;= 70:\n" +
    "        return &quot;A&quot;\n" +
    "    elif mark &gt;= 60:\n" +
    "        return &quot;B&quot;\n" +
    "    elif mark &gt;= 50:\n" +
    "        return &quot;C&quot;\n" +
    "    elif mark &gt;= 40:\n" +
    "        return &quot;D&quot;\n" +
    "    else:\n" +
    "        return &quot;U&quot;\n" +
    "def display_result(mark, grade):\n" +
    "    print(f&quot;You scored {mark}, which is grade {grade}.&quot;)\n" +
    "def main():\n" +
    "    print(&quot;=== Grade Calculator ===&quot;)\n" +
    "   \n" +
    "    while True:  \n" +
    "        mark = get_mark()                \n" +
    "        grade = calculate_grade(mark)    \n" +
    "        display_result(mark, grade)\n" +
    "        \n" +
    "        again = input(&quot;Do you want to enter another mark? (yes/no): &quot;).lower()\n" +
    "        if again != &quot;yes&quot;:  \n" +
    "            print(&quot;Goodbye!&quot;)\n" +
    "            break\n" +
    "main()";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "parsons3Puzzle2-sortable",
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
  $("#parsons3Puzzle2-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#parsons3Puzzle2-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 3
## Drag into order, beware of indents!

<div id="parsons3Puzzle3-sortableTrash" class="sortable-code"></div> 
<div id="parsons3Puzzle3-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="parsons3Puzzle3-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="parsons3Puzzle3-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "def get_item():\n" +
    "    name = input(&quot;Enter item name: &quot;)\n" +
    "    price = float(input(f&quot;Enter price of {name} (£): &quot;))\n" +
    "    return name, price\n" +
    "def calculate_discount(total):\n" +
    "    \n" +
    "    if total &gt;= 100:\n" +
    "        return total * 0.9   \n" +
    "    elif total &gt;= 50:\n" +
    "        return total * 0.95  \n" +
    "    else:\n" +
    "        return total         \n" +
    "def display_receipt(items, total, final_total):\n" +
    "    \n" +
    "    print(&quot;\n=== Receipt ===&quot;)\n" +
    "    for name, price in items:\n" +
    "        print(f&quot;{name}: £{price:.2f}&quot;)\n" +
    "    print(f&quot;Total before discount: £{total:.2f}&quot;)\n" +
    "    print(f&quot;Total after discount:  £{final_total:.2f}&quot;)\n" +
    "def main():\n" +
    "    items = []\n" +
    "    total = 0.0\n" +
    "    print(&quot;=== Shopping Bill Calculator ===&quot;)\n" +
    "    \n" +
    "    while True:\n" +
    "        name, price = get_item()\n" +
    "        items.append((name, price))\n" +
    "        total += price\n" +
    "        more = input(&quot;Add another item? (yes/no): &quot;).lower()\n" +
    "        if more != &quot;yes&quot;:\n" +
    "            break\n" +
    "    final_total = calculate_discount(total)\n" +
    "    display_receipt(items, total, final_total)\n" +
    "main()";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "parsons3Puzzle3-sortable",
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
  $("#parsons3Puzzle3-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#parsons3Puzzle3-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

## Puzzle 4
## Drag into order, beware of indents!
<div id="parsons3Puzzle4-sortableTrash" class="sortable-code"></div> 
<div id="parsons3Puzzle4-sortable" class="sortable-code"></div> 
<div style="clear:both;"></div> 
<p> 
    <input id="parsons3Puzzle4-feedbackLink" value="Get Feedback" type="button" /> 
    <input id="parsons3Puzzle4-newInstanceLink" value="Reset Problem" type="button" /> 
</p> 
<script type="text/javascript"> 
(function(){
  var initial = "import random\n" +
    "def welcome():\n" +
    "    print(&quot;=== Welcome to the Number Guessing Game ===&quot;)\n" +
    "    print(&quot;I am thinking of a number between 1 and 100...\n&quot;)\n" +
    "def get_guess():\n" +
    "   \n" +
    "    return int(input(&quot;Enter your guess: &quot;))\n" +
    "def check_guess(secret, guess):\n" +
    "    \n" +
    "    if guess &lt; secret:\n" +
    "        print(&quot;Too low! Try again.&quot;)\n" +
    "        return False\n" +
    "    elif guess &gt; secret:\n" +
    "        print(&quot;Too high! Try again.&quot;)\n" +
    "        return False\n" +
    "    else:\n" +
    "        print(&quot;Correct! You guessed it!&quot;)\n" +
    "        return True\n" +
    "def play_game():\n" +
    "   \n" +
    "    secret = random.randint(1, 100)\n" +
    "    attempts = 0\n" +
    "    while True:\n" +
    "        guess = get_guess()\n" +
    "        attempts += 1\n" +
    "        if check_guess(secret, guess):   # selection inside loop\n" +
    "            print(f&quot;You took {attempts} attempts.&quot;)\n" +
    "            break\n" +
    "def main():\n" +
    "    welcome()\n" +
    "    while True:\n" +
    "        play_game()\n" +
    "        again = input(&quot;Play again? (yes/no): &quot;).lower()\n" +
    "        if again != &quot;yes&quot;:\n" +
    "            print(&quot;Thanks for playing! Goodbye.&quot;)\n" +
    "            break\n" +
    "main()";
  var parsonsPuzzle = new ParsonsWidget({
    "sortableId": "parsons3Puzzle4-sortable",
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
  $("#parsons3Puzzle4-newInstanceLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.shuffleLines(); 
  }); 
  $("#parsons3Puzzle4-feedbackLink").click(function(event){ 
      event.preventDefault(); 
      parsonsPuzzle.getFeedback(); 
  }); 
})(); 
</script>

