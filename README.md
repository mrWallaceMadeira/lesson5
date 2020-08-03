# Lesson 5: Talking to yourself

Yesterday we covered printing to the console (i.e. the little box at the bottom of IntelliJ).\
Today we'll get interactive & learn how to respond to prompts in that same box.

### `System.in`teresting
  - [x] `System.out.println("A message");` allowed us to print
  - [x] Reading input requires two things
    1. `Scanner`
    2. `System.in`

### `Scanner` + `System.in` + `System.out` = your new quarantine friend
  - [x] `Scanner` is another Java variable type (e.g. `String`)
  - [x] `System.in` is another method (e.g.`System.out`)
  
We use them like this &nbsp;:arrow_down:
```
  Scanner myScanner = new Scanner(System.in);
  System.out.println(myScanner.nextLine());
```
### :hand:&nbsp; Stop!
Watch [this](https://youtube.com)

### :thought_balloon:&nbsp; Noticing themes
  - [x] `System.out.println("An argument")` takes an _argument_
  - [x] So does `new Scanner(System.in)`\
Some similarties here
  1. The last item in the string of commands tends to take `()` which usually has an _argument_ between these `()`
  2. The things that end in `()` tend to do things (i.e. print, read, etc.)
Both `println()` and `nextLine()` are types of _methods_

### C'est fini
Entry ticket [here]()
