## Voeg een lijst met regels toe

In deze stap neem je een lijst met regels op om het kostuum te wijzigen in **leuk** of **niet leuk**.

\--- task \---
+ Klik op het tabblad **Code** en voer de volgende code in.

```blocks3
when green flag clicked
switch costume to (not sure v)
ask [Type a comment about a recent movie you've seen or book you've read!] and wait
if <(answer) = [I loved the characters]> then
switch costume to (like v)
end
if <(answer) = [The adventure was boring]> then
switch costume to (dislike v)
end
```

+ Click on **File** and then on **Save to your computer** to save the program to a file. \--- /task \---

\--- task \---

+ Click on the **green flag** to test your program. ![Scratch interface just after green flag is clicked](images/test-rules-annotated.png)

+ Type in a comment about a movie or book and watch it react! Type in `I loved the characters` and press <kbd>Enter</kbd>. The character will smile. Click on the green flag again, type in `The adventure was boring`, and press <kbd>Enter</kbd>. The character will cry. Type in anything else, press <kbd>Enter</kbd>, and the character’s face won’t change. \--- /task \---

You have created a character that should react to what people type in, and programmed it using a simple rules-based approach. If you want it to react to other messages, you would need to add more `if` blocks. The problem with this is that you would need to predict exactly what messages the character will receive — it would take forever to make a list of every possible message!
