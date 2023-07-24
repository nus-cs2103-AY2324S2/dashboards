
<panel type="info" header="### 1. ARIF..ALID `@Arif-Khalid` (24 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/53#discussion_r1094053358" expanded>

Should be named something more appropriate now that functionality is more than just an echo.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/53#discussion_r1094056516" expanded>

Should follow naming standard without underscore, also should sound like a verb instead of a noun for methods
```suggestion
private static int handleEventInput(Task[] tasks, int count, String task) {
```
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/53#discussion_r1094057499" expanded>

Should be named something more descriptive
```suggestion
        int numTasks = 0;
```
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/53#discussion_r1094058222" expanded>

Should be named to sound like nouns instead of verbs such as userInput and userInputAsArray
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/53#discussion_r1094059015" expanded>

Should follow naming standard without underscore and sound like a verb
```suggestion
private static int handleDeadlineInput(Task[] tasks, int count, String task) {
```
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/53#discussion_r1094059514" expanded>

Should follow naming standard without underscore and as a verb such as handleTodoInput
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/53#discussion_r1094061063" expanded>

Should follow naming standard without underscore and as a verb such as handleMarkInput
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/53#discussion_r1094061318" expanded>

Should follow naming standard without underscore and as a verb such as handleUnmarkInput
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/53#discussion_r1094061684" expanded>

Should follow naming standard without underscore and as a verb such as handleListInput
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/53#discussion_r1094062072" expanded>

Good use of inheritance and override
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/53#discussion_r1094062568" expanded>

No reason for these to be protected when not accessed directly by its child classes. Should be private instead.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/53#discussion_r1094063244" expanded>

Should be private since only accessed within this class
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/53#discussion_r1094063617" expanded>

Good use of override and inheritance
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/53#pullrequestreview-1280367569" expanded>

**Review Status:** COMMENTED

Overall the functionality is there and the use of inheritance is good. However naming conventions should be worked on.
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/124#discussion_r1094066639" expanded>

Good use of final and appropriate naming for constant literal
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/124#discussion_r1094068625" expanded>

Should be using switch case statements
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/124#discussion_r1094070380" expanded>

Remove unused code
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/124#discussion_r1094071521" expanded>

Seems like this function is unnecessary due to the use of toString to print the tasks
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/124#discussion_r1094076313" expanded>

Naming of arrays should not be each individual element of the arrays. Furthermore, what is the point of every line after line 65 beyond changing the order of the elements in the array? 
Can't you just return at line 65 and assign the appropriate elements in the parent function?
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/124#discussion_r1094077352" expanded>

Should use switch-case statements
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/124#discussion_r1094078936" expanded>

Naming is very confusing should just name individual String variables like taskName, identifier and by.
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/124#discussion_r1094080444" expanded>

Good use of inheritance and override
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/124#discussion_r1094081426" expanded>

What if I pass in something that is none of the commands it would be treated as an event. Handle this case.
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/124#pullrequestreview-1280379183" expanded>

**Review Status:** COMMENTED

Overall functional but code quality can be greatly enhanced. Naming of arrays should be worked on and logic should be refined to reduce number of unnecessary local String arrays created.
</panel>

</panel>

<panel type="info" header="### 2. CHUA..JUIN `@wanjuin` (23 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/11#discussion_r1092830117" expanded>

return statement is abit complicated. Could make it clearer by giving the string a variable name like "String toPrint = "[D]" etc.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/11#discussion_r1092830845" expanded>

good if else blocks, no "deep nesting" 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/11#discussion_r1092832532" expanded>

the 2 statements are in the same level of abstraction
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/11#discussion_r1092833524" expanded>

Good naming of class. (Pascal case and is a Noun)
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/11#discussion_r1092834227" expanded>

Good use of plural nouns in "tasks" to represent a whole collection of tasks.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/11#discussion_r1092834845" expanded>

Good naming for method. (Camel case and verb)
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/11#pullrequestreview-1278527663" expanded>

**Review Status:** COMMENTED

Overall, code quality is good.  Classes, method and variable names matches the coding quality.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1092789816" expanded>

Classes' name written in Pascal case (good)

</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1092790013" expanded>

method name is clear and method name is in camelCase
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1092790613" expanded>

boolean name is good as it clearly shows that this variable is a "boolean" by using the word "is"
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1092790936" expanded>

Boolean variables/methods are named to sound like booleans
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1092791191" expanded>

getter method name is clear 
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1092791265" expanded>

setter method name is clear

</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1092791721" expanded>

Plural form are used on names representing a collection of tasks, instead of "task" (good)
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1092792810" expanded>

good use of task and tasks. (singular and plural to differentiate)
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1092792981" expanded>

constants in ALL CAPS (good)
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1092793472" expanded>

good indentation with 4 tabs and another 4 tabs for within the for loop
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1092807964" expanded>

Method name is a verb and is in camel case which is good
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1092808524" expanded>

method name is "noun". it might be better to use a "verb" such as handleDeadline.
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1092808767" expanded>

method name is "noun". it might be better to use a "verb" such as handleTodoTask
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1092809853" expanded>

instead of noun, could be "modifyDoneValue" which is a verb
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1092812169" expanded>

switch statement should have no indentation for case clauses. For example:
switch (command) {
case "add":
&gt;4 spaces>addCommandHandler(arguments);
&gt;4 spaces>break;
......
}
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#pullrequestreview-1278466747" expanded>

**Review Status:** COMMENTED

[Coding Standard] Overall good coding standard. Most method names are verbs, and all method and variable names are in camelcase. Class names are in nouns and Pascal case. Good indentations except for the switch statement.
</panel>

</panel>

<panel type="info" header="### 3. WOO .. JUN `@woowenjun99` (24 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/65#discussion_r1094069725" expanded>

- [ ] Why will 1 be included in this boolean variable? Supposed that `Task.getNumberOfTasks() == 1`, the value would be true and **not less than one**. Perhaps you would like to review this portion of the code to see if this is the intended functionality as it might cause bugs, or change the naming as it might cause confusion in the future.
- [ ] Would you like to consider removing the brackets as it is unnecessary?
- [ ] Would you like to change the variable name to make it sound boolean instead?
```suggestion
        boolean isLessThanOne = Task.getNumberOfTasks() <= 1;
```
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/65#discussion_r1094076029" expanded>

Would you like to change the value of 100 to a named constant for greater clarity? Also, perhaps you would like to consider shifting the tasks array to a class variable instead to reduce the need to pass it in as arguments in other functions?

```suggestion
        int MAX_TASK = 100;
        Task[] tasks = new Task[MAX_TASK];
```
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/65#discussion_r1094113100" expanded>

Would you like to change this method to contain a verb instead? Furthermore, would you like to consider making this function private as you are only using it inside this class?

```suggestion
    public static void printHorizontalLine() {
```
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/65#discussion_r1094117061" expanded>

- [ ] There are 127 characters on this line, which exceeds the standards of a maximum of 120 characters. Perhaps you might want to wrap the text, or use `printf` instead to make this line shorter.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/65#discussion_r1094118395" expanded>

Perhaps you would like to better name the task instead of using a one-letter variable for greater clarity?
```suggestion
    public static void taskAdded(Task task) {
```
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/65#discussion_r1094124397" expanded>

Perhaps you would like to use `String.format()` instead of concatenation to rewrite this part to make it neater and easier to make changes in the future?

```suggestion
        return String.format("[D]%s (by %s )", super.toString(), by);
```
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/65#discussion_r1094125641" expanded>

Perhaps you should name the logo in capital letter as it is a constant? Also, would you like to consider naming the method with an action instead?

```suggestion
        String LOGO = " ____        _\n"
```
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/65#discussion_r1094126631" expanded>

Would you like to consider naming the method with an action instead?

```suggestion
    private static void printLogoWithHello() {
```
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/65#discussion_r1094129523" expanded>

Would you like to consider using a named constant instead of having a magic number as it might cause confusion why you would choose the number 5? The same applies for the rest of the class

```suggestion
        int lengthOfTo = "/todo".length;
        userInput = userInput.substring(lengthOfTo);
```
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/65#discussion_r1094136882" expanded>

Would you like to consider removing this line as you are importing a package that you are not using? This might seem insignificant, but it might help to reduce compilation time and reduce the potential errors that might be introduced in the future
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/65#discussion_r1094144361" expanded>

Just curious, is there a reason why you would use a static variable here instead of the main function?
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/65#discussion_r1094145407" expanded>

Perhaps you would like to have a setter function instead to reduce repeated code?

```suggestion
    public void setDone(boolean value) {
```
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/65#discussion_r1094150714" expanded>

What is the purpose of this dateTime as I do not see it being used anywhere within this class?
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/65#discussion_r1094151947" expanded>

Perhaps you would like to consider using the type of `int` instead?

```suggestion
        int taskNumber = Integer.parseInt(words[1]) - 1;
```
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/65#pullrequestreview-1280381982" expanded>

**Review Status:** COMMENTED

Overall, I like how you broke down your code into smaller functions so that it abides by the Single Responsibility Principle. However, there are many questionable choices that I would like to clarify with you.

1. There were many magic numbers used in the code. Do consider replacing them with a named constant for greater clarity.
2. Consider using `String.format` or `printf` to format the string instead of concatenation.
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#discussion_r1094071820" expanded>

Code Standards: Perhaps this should be plural to represent a collection of objects?

```suggestion
        int MAX_TASK = 100;
        Task[] lists = new Task[MAX_TASK];
```
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#discussion_r1094073998" expanded>

Coding Standard: Since this is a constant, you have to capitalise the full name.

```suggestion
        String LINEBREAK = "---------------------------------------------";
```
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#discussion_r1094100948" expanded>

Coding Standards: Perhaps this should be plural to represent a collection of objects? Furthermore, I think this variable could be better named as the method seemed to breaking up the line into an array of string.

```suggestion
                    String[] inputLines = line.split(" ", 2);
```
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#discussion_r1094107608" expanded>

Good job on not importing everything!
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#discussion_r1094107880" expanded>

Good job on using plural for the array here!
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#discussion_r1094108709" expanded>

Good job on naming the class in capital letter
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#discussion_r1094108958" expanded>

Good job on using the K&R style for the if-else block
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#pullrequestreview-1280383924" expanded>

**Review Status:** COMMENTED

Overall good job on following the coding standards. However, I feel that the naming could be better improved for some of the variables, such as using `LINE_BREAK` instead of `lineBreak` for constants. Furthermore, for a collection of objects, the variables should be named in plural and better named, especially the `String inputLine = line.split(" ");`. Otherwise, most of the code is well written and abide to the standards.
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/160#pullrequestreview-1280377577" expanded>

**Review Status:** COMMENTED

In terms of coding standards, it is well done. The variables are named using camel case, there are indentations for the if else statement and the indentations are correct
</panel>

</panel>

<panel type="info" header="### 4. HONG..HANG `@honglinshang` (21 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/19#discussion_r1094047705" expanded>

Can add a space between Task and the curly bracket { to fit with the coding standard
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/19#discussion_r1094051812" expanded>

Good job attaching array specifier to the type and not the variable!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/19#discussion_r1094055211" expanded>

The spacing format here should follow the form of
if (condition) {
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/19#discussion_r1094059268" expanded>

Remember to leave a space in between the variable names
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/19#discussion_r1094059858" expanded>

Good placement of comment!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/19#discussion_r1094060788" expanded>

Case statements should not be indented, you can change your settings in your IDE to reflect that so you don't have to manually delete in the future :)
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/19#discussion_r1094061194" expanded>

Take note of the extra space after task
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/19#discussion_r1094062650" expanded>

Good job leaving 8 spaces for this wrapped line
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/19#discussion_r1094063278" expanded>

This also applies to all other if statements in your code
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/19#discussion_r1094064425" expanded>

Similar to before, cases should not be indented
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/19#pullrequestreview-1280362686" expanded>

**Review Status:** COMMENTED

Great job overall! Do take note of the inconsistent spacing throughout your code, you can consider using your IDE to fix these mistakes. Other aspects like naming and staying under 120 characters per line were adhered to well :)
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/86#discussion_r1094094000" expanded>

Consider updating this to reflect the current function of your code
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/86#discussion_r1094103576" expanded>

Like what shawntangy said, you can avoid the magic number by adding a named constant CAPACITY at the beginning of the class. This will help make it easier to change in the future!
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/86#discussion_r1094130257" expanded>

You could use enumerations (COMMAND_EXIT_WORD, COMMAND_LIST_WORD, etc.) since there are only a few instructions. It would also help make it easier to change the command words in the future if needed!
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/86#discussion_r1094131901" expanded>

Consider extracting this as a method (eg. receiveCommand()) to make your code more readable and avoid making your main method too long. Same thing can be applied to the blocks of code within each of your if else statements
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/86#discussion_r1094135239" expanded>

Your main method is rather lengthy, try to cut it down to fewer than 30 lines
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/86#discussion_r1094136483" expanded>

Remember to remove dead code!
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/86#discussion_r1094137924" expanded>

Great job extracting this to minimise code duplication!
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/86#discussion_r1094141166" expanded>

It may be hard for someone to understand what is being done in this step, so you could add a comment explaining or extract it as a method (eg. getIndex()) for readability
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/86#discussion_r1094144506" expanded>

Distinguishing between the variable and its class by case could make your code misleading, maybe directly add it into your array tasks via 
`tasks[numTasks] = new Todo(description);`
Same goes for the other types of tasks
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/86#pullrequestreview-1280408683" expanded>

**Review Status:** COMMENTED

Overall, great job! The readability of the code could be improved, but other aspects like the subclasses and naming were generally well done. Consider adding more comments to explain what your code does!
</panel>

</panel>

<panel type="info" header="### 5. TANG..XUAN `@tangphi` (19 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/43#discussion_r1094150764" expanded>

I like your use of constants and constant names are in the correct format
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/43#discussion_r1094175964" expanded>

I think the naming of the Task array 's' can be more descriptive by using a noun (for instance, 'taskList' as you put in line 34) for the variable name so that it is more understandable and readable
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/43#discussion_r1094178881" expanded>

I think it is better stylistically to put a space between the round and curly brackets as you have done in line 53 here
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/43#discussion_r1094179143" expanded>

Similar to line 58, you should put a space between the round and curly brackets as you have done in line 53 here
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/43#discussion_r1094179357" expanded>

You should put a space between the round and curly brackets as you have done in line 53 here
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/43#discussion_r1094179569" expanded>

Similarly, I think you should put a space between the round and curly brackets as you have done in line 53 here
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/43#discussion_r1094180271" expanded>

I think you should put a space after Task and the curly brackets here
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/43#discussion_r1094180634" expanded>

I think it is better stylistically to put a space between the round and curly brackets
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/43#discussion_r1094180998" expanded>

I think it is better stylistically to put a space after Task 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/43#discussion_r1094181750" expanded>

I think it is better stylistically to put a space between the round and curly brackets
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/43#pullrequestreview-1280491227" expanded>

**Review Status:** COMMENTED

I think you did a great job, just some small minor stylistic improvements to make!
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/67#discussion_r1094197193" expanded>

I like your use of constant names, they are the correct style being all uppercase and having an underscore to separate the words
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/67#discussion_r1094199115" expanded>

I think you should put a space between the if and the first round bracket for better readability and more correct layout
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/67#discussion_r1094199302" expanded>

Similarly, I think you should put a space between the if and the first round bracket for better readability and more correct layout
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/67#discussion_r1094200126" expanded>

I think you can remove the space between the variable deadlineArray and the semicolon for better readability and more correct layout
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/67#discussion_r1094200595" expanded>

I think you should put a space between the if and the first round bracket for better readability and more correct layout here like you did for the catch statement in line 111
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/67#discussion_r1094202005" expanded>

I think it is better stylistically if you put a space between Task and the curly bracket 
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/67#discussion_r1094204064" expanded>

I like your use of descriptive method names, it adds to the readability of your code!
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/67#pullrequestreview-1280558749" expanded>

**Review Status:** COMMENTED

Great code, small spacing improvements, good job!
</panel>

</panel>

<panel type="info" header="### 6. NATA.. TZE `@natashatanyt` (19 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/26#discussion_r1093921900" expanded>

Please be consistent with your spacing! ie. most of your code has the closing brace on the immediate next line, but this one has an additional space
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/26#discussion_r1093923075" expanded>

Again, consistency - usually your last closing brace does not have an extra empty line above it
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/26#discussion_r1093925160" expanded>

You can use a better name (according to prof) - I think you should use a better name that's more specific, such as tasksList or something like that
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/26#discussion_r1093925706" expanded>

Not really a coding standard violation, but if your assistant is called Baymax, why is the ASCII art DUKE?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/26#pullrequestreview-1280145587" expanded>

**Review Status:** COMMENTED

Not sure where to leave a general comment so I'll put it here:
All in all, good job! It's just very minor issues w/ your code.

It's very good that you followed the camel casing your methods.

Keep it up!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#discussion_r1094078281" expanded>

Is there a reason why you use c and counter? 
You might want to consider adding comments, or using a better variable name! 

Or, you can move Line 55-56 to be where line 54 is instead!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#discussion_r1094080312" expanded>

I think you can consider using a switch statement instead of if-else 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#discussion_r1094082639" expanded>

I think this else-if part is very wordy and cluttered. It would be better if you can split up into sections, or create more methods to make it simpler. For example, lines 52-54 could be set as a method to make it look neater.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#discussion_r1094083550" expanded>

Similar to lines 52-54, you can consider using a method instead to make the code easier to read!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#discussion_r1094085141" expanded>

Same as the event case, you can reorder your code to reduce extra variables.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#discussion_r1094085814" expanded>

Not code quality, but to follow conventions, I recommend removing all these extra empty lines.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#discussion_r1094090489" expanded>

You can consider using SCREAMING_SNAKE_CASE (which I just learnt the name of), such as TODO_ARRAY or something similar
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#discussion_r1094092148" expanded>

You might want to consider putting this in your Todos.java instead, similar to what is suggested on the mod website
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#discussion_r1094097993" expanded>

This seems like a very c-style implementation - you have a c and counter, you might want to consider looping until it reaches your counter instead. This will make your code cleaner.

Or, if you want to continue using this method, to make effective use of short-circuiting, you can switch your i &gt; todo.length and todo[i] != null
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#discussion_r1094098260" expanded>

Good job on using specific packages!
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#discussion_r1094099391" expanded>

I think this might be a typo in your code, specifically todo[**i=1**].type
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#discussion_r1094100035" expanded>

While this does not affect your code, I think you only need one ';'. Same goes for line 49
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#discussion_r1094100797" expanded>

For methods, you should be using camelCase, ie. isMarked(), similar to the rest of the methods in this file
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#pullrequestreview-1280390260" expanded>

**Review Status:** COMMENTED

All in all, good attempt! 

However, I think you have some work to do in making your code cleaner and more consistent. If you use IntelliJ, you should be able to CTRL + ALT + L to fix coding standard violations.
</panel>

</panel>

<panel type="info" header="### 7. ZHAN..TONG `@Zhang-Zhitong` (18 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/33#discussion_r1094086040" expanded>

Perhaps it would be better to encapsulate the different command words into an enum so as to use LIST instead of "list" for the cases
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/33#discussion_r1094098778" expanded>

perhaps it would be tidier to refactor "/by" into a constant, since "/by" is used again in line 54.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/33#discussion_r1094102958" expanded>

perhaps it would be tidier to refactor "/from" into a constant, since "/from" is used again in line 77.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/33#discussion_r1094108559" expanded>

done does not convey the boolean nature of the variable that isDone conveys. perhaps it would be better to do:
public void setDone(boolean isDone) {
    this.isDone = isDone;
}
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/33#pullrequestreview-1280402044" expanded>

**Review Status:** COMMENTED

Overall, I found your code easy to read, and easy to understand. The comments were very useful and the classes are well defined. I only found some very minor coding standard issues.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/47#discussion_r1094183416" expanded>

I like the use of packages to organize everything 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/47#discussion_r1094185797" expanded>

I like how the variable is named. it is very clear that that it is a boolean and it is in camelCase
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/47#discussion_r1094187331" expanded>

I like how the class names are all in PascalCase
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/47#discussion_r1094189011" expanded>

I like how the methods are verbs and in camelCase
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/47#discussion_r1094193699" expanded>

Perhaps it might be clearer to use "string" instead of "s", as in "for (String string : strings)".

</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/47#pullrequestreview-1280538352" expanded>

**Review Status:** COMMENTED

I learned a lot reviewing your code. I like how you used the oop principles to make a very readable and easy to follow codebase. I cant find any coding standard issues at all.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/160#discussion_r1094161891" expanded>

It might be useful to extract command[0] into its own variable since you use command[0] again multiple times.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/160#discussion_r1094165437" expanded>

it might be clearer to negate the ! and use the logical equivalent indexToChange >= numberOfTasks
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/160#discussion_r1094166966" expanded>

it might be useful to create an enum containing the different commands and using BYE instead of "bye"
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/160#discussion_r1094168231" expanded>

Perhaps you could extract the String into its own constant, such as GOODBYE_MESSAGE, just like how you did for BLANK and LINE
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/160#discussion_r1094169441" expanded>

similar to my previous comment, perhaps you could extract the String into its own constant.
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/160#discussion_r1094172876" expanded>

perhaps you could refactor this into a method in the Task Class, since isDone is a variable in the Task class?
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/160#pullrequestreview-1280505442" expanded>

**Review Status:** COMMENTED

Overall, it was easy for me to review your code as it is readable and understandable. I liked the use of single line comments that offered insights into what you are doing in the main method. There are some variables that I believe can be extracted and some methods that might be better refactored.
</panel>

</panel>

<panel type="info" header="### 8. CLEO.. WEI `@Khulon` (18 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/77#discussion_r1092797742" expanded>

Very clear and well named functions (good readability)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/77#discussion_r1092799667" expanded>

Well written names that follow naming convention CamelCase 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/77#discussion_r1092800922" expanded>

could use taskNumber instead of "i" to be more clear (better readability)
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/77#discussion_r1092801242" expanded>

Well commented code, makes the code easy to understand!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/77#discussion_r1092801863" expanded>

Indentations are done well throughout the code! (default 4 spaces)
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/77#pullrequestreview-1278478140" expanded>

**Review Status:** COMMENTED

Overall, code is very readable and easy to understand!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/147#discussion_r1092826478" expanded>

Naming should follow convention, use English
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/147#discussion_r1092828092" expanded>

"num" should be written in full to be more clear (for better readability)
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/147#discussion_r1092829654" expanded>

"TaskArrayList" names should follow camelCase naming convention
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/147#discussion_r1092830281" expanded>

index could be further expanded on to make it more clear which index it is referring to (better readability)
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/147#discussion_r1092831604" expanded>

Comments should be indented relative to their position in the code.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/147#pullrequestreview-1278522624" expanded>

**Review Status:** COMMENTED

Overall, code is clear and easy to understand! Just a few suggestions and pointers!
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/180#discussion_r1092794263" expanded>

Good naming convention, follows camel case
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/180#discussion_r1092794374" expanded>

indentation should be 8 spaces
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/180#discussion_r1092794573" expanded>

"str" is not so clear (readability)
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/180#discussion_r1092794713" expanded>

Well commented code
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/180#discussion_r1092795603" expanded>

could use taskNumber instead of "i" to be clearer (for better readability)
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/180#pullrequestreview-1278473130" expanded>

**Review Status:** COMMENTED

Hi, good job on your code!
</panel>

</panel>

<panel type="info" header="### 9. NICH.. JIE `@NicholasChungJunJie` (17 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/50#discussion_r1093921694" expanded>

Inconsistent formatting. No space between `()` and `{` here.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/50#discussion_r1093922063" expanded>

Inconsistent formatting. No space between `()` and `{` here.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/50#discussion_r1093922254" expanded>

Inconsistent formatting. No space between `()` and `{` here.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/50#discussion_r1093922446" expanded>

Inconsistent formatting. No space between `()` and `{` here.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/50#discussion_r1093922971" expanded>

Inconsistent formatting. No space between `Task` and `{` here.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/50#discussion_r1093924860" expanded>

This comment sounds like it is written to the developer. You can choose to remove it.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/50#discussion_r1093925108" expanded>

Inconsistent formatting. No space between `()` and `{` here.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/50#discussion_r1093925241" expanded>

Inconsistent formatting. No space between `()` and `{` here.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/50#discussion_r1093925462" expanded>

Inconsistent formatting. No space between `()` and `{` here.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/50#discussion_r1093925746" expanded>

Inconsistent formatting. No space between `()` and `{` here.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/50#discussion_r1093926535" expanded>

Inconsistent formatting. No space between `()` and `{` here.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/50#discussion_r1093926742" expanded>

Inconsistent formatting. No space between `()` and `{` here.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/50#pullrequestreview-1280145291" expanded>

**Review Status:** COMMENTED

Nice comments.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/130#discussion_r1093939962" expanded>

Complicated expression. You could maybe evaluate it beforehand using easily understandable variable names.
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/130#discussion_r1093987208" expanded>

Maybe could try using more meaningful variable names.
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/130#discussion_r1093988392" expanded>

Nicely named constants.
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/130#pullrequestreview-1280170145" expanded>

**Review Status:** COMMENTED

Overall, very good code quality.
</panel>

</panel>

<panel type="info" header="### 10. WANG..YANG `@haoyangw` (16 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/59#discussion_r1094118840" expanded>

'by' is a bit confusing, perhaps consider something more specific like 'dueDate' for clarity so it's easier to understand what this variable is for
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/59#discussion_r1094119869" expanded>

Perhaps you can abstract out some parts of the main() function into separate functions with descriptive function names for greater readability, as main() currently seems really long and hard to understand
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/59#discussion_r1094137777" expanded>

Maybe you can consider storing the ____ String as a class-level constant variable since it's used multiple times and a variable name would be more readable
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/59#discussion_r1094140232" expanded>

Is this possibly a redundant check? Seems to be the same as the while condition just above
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/59#discussion_r1094141074" expanded>

Maybe you can consider adding a 'default' block too? To catch any unrecognised commands so Duke may let the user know that something funny happened
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/59#discussion_r1094142052" expanded>

Maybe you can consider using more specific names for these variables too? Something like startDate and endDate might be more descriptive for others reading your code
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/59#discussion_r1094143900" expanded>

Great use of abstraction and delegation, this simplifies the code of other classes that will call this class for this functionality
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/59#discussion_r1094147986" expanded>

Great use of abstraction and encapsulation here to simplify each 'case' clause. Maybe you can go even further and abstract longer 'case' clauses like the one for "event" into separate functions to make the long 'switch' block more readable?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/59#pullrequestreview-1280443625" expanded>

**Review Status:** COMMENTED

Good effort at making your code readable with some abstraction, it's good that you managed to keep nesting at up to 3 levels only too. Fix some of the nits and it'll be LGTM!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/98#discussion_r1094012073" expanded>

enum values are constants, so try to write these names all in capital letters
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/98#discussion_r1094012555" expanded>

Also, remember to add a whitespace after every comma!
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/98#discussion_r1094016492" expanded>

Consider changing stringArray to a name in plural form instead? Since it's an array. And perhaps try naming it something more descriptive as well.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/98#discussion_r1094017869" expanded>

I believe unmark() will do? since it's one word, not two words, so camelCase doesn't apply here
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/98#discussion_r1094018797" expanded>

Remember to add a whitespace between Task and '{' yah!
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/98#discussion_r1094019126" expanded>

Remember to add a whitespace between 'Task' and '{' yah!
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/98#pullrequestreview-1280332055" expanded>

**Review Status:** COMMENTED

Overall, your code is very nice to read and follows most of the coding standards well, just a few minor mistakes here and there. Good that indentation has been followed very strictly too. Just a few nits to fix. Well done!
</panel>

</panel>

<panel type="info" header="### 11. DYLA..TIAN `@Dadevchia` (16 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/146#discussion_r1094142041" expanded>

unmarkDone method is relatively long and can be refactored into smaller method
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/146#discussion_r1094142279" expanded>

markDone method is relatively long and can be refactored into smaller method
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/146#discussion_r1094143536" expanded>

Good to initialize string constants as private static final
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/146#discussion_r1094145587" expanded>

Hardcoded strings can be refactored into constants at the top of code for maintainability
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/146#discussion_r1094147254" expanded>

Rica class is doing multiple things such as adding marking and printing tasks and separating into different classes can be used for better clarity
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/146#discussion_r1094147872" expanded>

Comments can be evenly placed into the individual lines of code for better clarity on what each line of code does
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/146#discussion_r1094148953" expanded>

Double negative in logic leads to less clarity
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/146#pullrequestreview-1280477087" expanded>

**Review Status:** COMMENTED

For Task 1 of PR 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/182#discussion_r1094154733" expanded>

Good to declare constants with ALL CAPS
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/182#discussion_r1094155991" expanded>

Scanner is not a string constant and is not advisable to group it together with other string constants
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/182#discussion_r1094156580" expanded>

All methods are in camelCase that is good
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/182#discussion_r1094158741" expanded>

Code can have better indentation
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/182#discussion_r1094159094" expanded>

Good naming to have Task class capitalized
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/182#discussion_r1094159997" expanded>

Better to use a separate name when creating objects from class to minimize confusion
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/182#discussion_r1094160432" expanded>

Good to have standard conversation lines as constants for maintainability
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/182#pullrequestreview-1280495098" expanded>

**Review Status:** COMMENTED

second PR review
</panel>

</panel>

<panel type="info" header="### 12. ENG ..VIEL `@avielcx` (15 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/183#discussion_r1094141019" expanded>

It will be good to eliminate magic numbers and replace them with constants
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/183#discussion_r1094141637" expanded>

It will be good to replace your variable number to be more specific
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/183#discussion_r1094142420" expanded>

It will be good to rename your array to what the array represents
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/183#discussion_r1094143429" expanded>

```suggestion
        String[] array = new String[100];
```
Your array declaration is C-style and not Java
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/183#discussion_r1094144470" expanded>

It will be good to eliminate magic number
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/183#discussion_r1094147533" expanded>

It will be good to replace the variable name for greater readability. It takes time for readers to understand what is the variable for (exit from what?).
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/183#pullrequestreview-1280475622" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/209#discussion_r1094009079" expanded>

It would be good if you make the conditions more understandable such as creating a new variable
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/209#discussion_r1094010516" expanded>

It would be to add more comments to make your code more understandable
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/209#discussion_r1094016754" expanded>

It would be good to remove redundant comments for better readability
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/209#discussion_r1094017306" expanded>

It would be good to move the else if statement to the next line for better readability
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/209#discussion_r1094018174" expanded>

It would be good to avoid shortcuts for readers to better understand the code
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/209#discussion_r1094019873" expanded>

it would be good to improve the indentations to follow the coding standards
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/209#discussion_r1094020928" expanded>

It would be good to not have parameters and variables the same name to avoid confusion
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/209#pullrequestreview-1280329823" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 13. ONG .. JET `@heejet` (15 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/142#discussion_r1094427487" expanded>

Good use of SLAP here to make the code readable.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/142#discussion_r1094428784" expanded>

Perhaps you can consider using a switch statement here instead.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/142#discussion_r1094433129" expanded>

Maybe you can consider renaming this variable to numTasks or something more descriptive to enhance readability.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/142#discussion_r1094434832" expanded>

Consider switching the magic number 7 to a constant to make the code easier to understand.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/142#discussion_r1094436689" expanded>

I like how you extract out these codes into methods to make it more readable and reduce code duplication.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/142#discussion_r1094439343" expanded>

Perhaps you could use your formattingLine() method here to make your code more readable.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/142#discussion_r1094440147" expanded>

Consider setting this as a constant variable so that the length of the line is standardized across all methods.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/142#pullrequestreview-1280903962" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/191#discussion_r1094146481" expanded>

Consider using guard clauses here to make the happy path of the method more visible.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/191#discussion_r1094148317" expanded>

I like how the constant variables are named in upper case, keep up the good work
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/191#discussion_r1094149040" expanded>

I like how the indentation for this switch statement follows the coding standards
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/191#discussion_r1094150533" expanded>

Good job with naming the members and classes
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/191#discussion_r1094152755" expanded>

I like how the imported classes are listed explicitly
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/191#discussion_r1094160189" expanded>

I like how the method names are verbs
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/191#pullrequestreview-1280483578" expanded>

**Review Status:** COMMENTED

Overall good job following the java coding standards. Variables names are in camelCase, constant names are in uppercase with underscore to separate the words. Method names are verbs.
</panel>

</panel>

<panel type="info" header="### 14. ER J..N ZE `@ERJUNZE` (14 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/33#discussion_r1093983691" expanded>

Variables follow naming rules (camel case for normal variables, uppercase for constants), good job.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/33#discussion_r1093984458" expanded>

I like that you adhered to the line length recommendation and wrapped your lines with the recommended 8 spaces.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/33#discussion_r1093986097" expanded>

Shouldn't Javadoc summary and descriptions should end with a period? (also applies to the rest of the Javadocs)
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/33#discussion_r1094064992" expanded>

I like how your boolean variables and methods are named to sound like booleans.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/33#pullrequestreview-1280241748" expanded>

**Review Status:** COMMENTED

Overall, great job following the coding standards. However, all your javadocs are missing periods at the end of each phrase/sentence.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#discussion_r1093986828" expanded>

Perhaps use a named constant instead of a magic number
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#discussion_r1094044959" expanded>

Since dead code can be retrieved using revision control, consider deleting it instead of just commenting it out
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#discussion_r1094046337" expanded>

Since you only use this variable inside the while block below, could it be moved inside to minimise its scope?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#discussion_r1094049749" expanded>

Could this code be abstracted out so the main method is not so long?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#discussion_r1094051074" expanded>

Since this variable is only used in the if else blocks below, could it be moved inside to minimise its scope?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#discussion_r1094051494" expanded>

Once again, consider abstracting this code out into multiple methods so each method is not so long
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#discussion_r1094055993" expanded>

Perhaps you can combine the square brackets into these methods so you don't have to repeat them for each of the different tasks, for example:
```
public String getStatusIcon() {
    return (isDone ? "[X]" : "[ ]");
}
```
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#discussion_r1094057158" expanded>

Since these two methods are mostly the same, could you combine them to reduce code duplication?
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#pullrequestreview-1280270690" expanded>

**Review Status:** COMMENTED

Overall, there are many improvements that can be made. Focus on splitting up into multiple smaller methods so they are not so long.
</panel>

</panel>

<panel type="info" header="### 15. WONG..IANG `@ZhongXiangWong` (14 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/112#discussion_r1092798736" expanded>

Minor spacing issue in line 17.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/112#discussion_r1093268840" expanded>

Perhaps the checkbox variable can be stored in the parent class instead as it is not unique to the child class.(Deadline, ToDo and Event share the attribute) 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/112#discussion_r1093277537" expanded>

Perhaps spacing can be more consistent.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/112#discussion_r1093283377" expanded>

I like your clear and concise comments describing the methods.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/112#discussion_r1093288053" expanded>

Perhaps 'info_e' can be refactored to 'info_event'.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/112#discussion_r1093291410" expanded>

I like the single level of abstraction here.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/112#discussion_r1093302473" expanded>

This method may be unused. Maybe can use the 'super.toString()' method in the child class to call this method. 
For example, Deadline.java Line 15:
'return "[D]" + checkbox + " " + name + " (by:" + deadline + ")";' 
can be written as: 
'return "[D]" + super.toString() + " (by:" + deadline + ")";'
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/112#pullrequestreview-1278479597" expanded>

**Review Status:** COMMENTED

Nice Job! I like how you extracted methods to keep every method short and easy to understand. However, there are some minor refactoring issues.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/135#discussion_r1092786977" expanded>

Perhaps the indention for switch-case can be improved.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/135#discussion_r1092788093" expanded>

Perhaps imported classes can be listed explicitly.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/135#discussion_r1092788758" expanded>

Maybe can split into multiple lines.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/135#discussion_r1092790653" expanded>

Perhaps "this." may be excluded.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/135#discussion_r1092792572" expanded>

I like how you extracted the methods to keep the main method easy to read.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/135#pullrequestreview-1278462814" expanded>

**Review Status:** COMMENTED

Your code is easy to follow, however there are some minor coding standard violations. 
</panel>

</panel>

<panel type="info" header="### 16. NG Y..ZHEN `@Ng-YZ` (15 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/82#discussion_r1092921777" expanded>

I like this section! Very clear and well-named to match coding standards!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/82#discussion_r1092924381" expanded>

Nicely indented relative to the conditionals
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/82#discussion_r1092925206" expanded>

indentation done very clearly and according to standards!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/82#discussion_r1092926448" expanded>

maybe can consider putting the comments in a new line before the if-else statements?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/82#discussion_r1092930506" expanded>

naming of variables follows convention, very easy to understand
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/82#pullrequestreview-1278423759" expanded>

**Review Status:** COMMENTED

Nicely done: Naming of code follows the Java coding standards closely, layout generally follows 4-spaces indentation, and 8-spaces indentation for wrapped text, K&R style used. It was very easy to read for most sections.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/82#pullrequestreview-1278662312" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#discussion_r1092882686" expanded>

perhaps can consider adding .close() for the scanner.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#discussion_r1092885411" expanded>

This looks neat but maybe you could try putting this as a separate method to reduce some levels of nesting instead? Perhaps can directly use if-else form since there are only two possibilities here
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#discussion_r1092886090" expanded>

maybe can consider optimizing these since there are some overlaps
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#discussion_r1092891125" expanded>

maybe consider extracting this section into a method on its own?
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#discussion_r1092891762" expanded>

Maybe can consider adding on to the ones above (or a new method) since there is some overlaps?
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#discussion_r1092893146" expanded>

Maybe you can also consider extracting these lines into a new method?
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#discussion_r1092904815" expanded>

Maybe need to caps the first letter to follow the PascalCase format
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#pullrequestreview-1278427303" expanded>

**Review Status:** COMMENTED

The code is generally easy to understand and well-written, and I like flow of the code. However, it seems that all of the code are written in the 'main' method which makes it really long. Refactoring may help improve code readability!
</panel>

</panel>

<panel type="info" header="### 17. TAN .. ZHE `@tanyizhe` (14 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/100#discussion_r1092785609" expanded>

Good job, only relevant  imports, rather than java.util.*
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/100#discussion_r1092787700" expanded>

Try using switch/case statements for fixed values. If/else statements are better for boolean statements
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/100#discussion_r1092790530" expanded>

Good use of class to prevent main from cluttering up
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/100#discussion_r1092791570" expanded>

You could separate [D] and [X] to different methods, keep [X] in Todo class, then inherit it in Deadline
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/100#discussion_r1092791839" expanded>

Good indentation with switch/case
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/100#discussion_r1092792382" expanded>

could use more descriptive variables like "command" rather than "s"
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/100#pullrequestreview-1278460775" expanded>

**Review Status:** COMMENTED

Good job overall!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#discussion_r1092793710" expanded>

could be extracted into a method
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#discussion_r1092794673" expanded>

Could use switch/case statements instead of if/else statements for this, if/else statements are better for variable conditions that result into a boolean
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#discussion_r1092795082" expanded>

Good that only relevant class is imported rather than java.util.*
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#discussion_r1092795963" expanded>

avoid using "magic numbers", use constants instead
e.g
private static final int ...
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#discussion_r1092796592" expanded>

could be extracted to a "greetUser" method
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#discussion_r1092798413" expanded>

try putting isDone in a new "Todo" class instead of putting it in main
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#pullrequestreview-1278472243" expanded>

**Review Status:** COMMENTED

Overall could refactor and extract more methods, as well as adding a Todo class
</panel>

</panel>

<panel type="info" header="### 18. MITC..LVIN `@mitchmalvin1` (14 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/6#discussion_r1095300683" expanded>

Is there a need to use ArrayList?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/6#discussion_r1095301181" expanded>

Should this chunk of print functions be abstracted to another function?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/6#discussion_r1095302288" expanded>

Can this be moved to a new greeting() function?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/6#discussion_r1095304707" expanded>

Shouldn't this throw an Exception?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/6#discussion_r1095305732" expanded>

This is good considering how there can be more types of task in the future.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/6#discussion_r1095306298" expanded>

Should you put the magic string "(/from|/to)" into a final constant?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/6#pullrequestreview-1282206847" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/101#discussion_r1095308322" expanded>

Why can't you just check for unmark first and then check for the mark, that way you don't have to specify the mark and unmark
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/101#discussion_r1095308663" expanded>

This condition should throw an exception instead of showing that the task has been added
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/101#discussion_r1095309154" expanded>

This should be moved to addTask()
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/101#discussion_r1095309572" expanded>

taskCount should be incremented here and not in the main function
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/101#discussion_r1095310039" expanded>

You should have incremented the taskCount first before printing, hence there is no need to increment it in this print statement
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/101#discussion_r1095310624" expanded>

Should you remove the word event altogether from line?
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/101#pullrequestreview-1282217314" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 19. VU V..DUNG `@joulev` (14 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/29#discussion_r1094143486" expanded>

Really nice :) I love that you are using `switch`/`case` statements here, as it helps a lot in readability compared to `if`/`else` statements.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/29#discussion_r1094145205" expanded>

While `numTasks` is quite clear already, I think it could be made clearer such as `getNumberOfTasks`.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/29#discussion_r1094145577" expanded>

```suggestion
        switch (command) {
```

and I found similar cases in some other places as well.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/29#discussion_r1094145995" expanded>

It might help to have some comments here explaining what this label is for. Same for some other files.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/29#discussion_r1094147952" expanded>

Maybe this variable should have a clearer name. `ret` is not an English word so it's not immediately clear to me what it means.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/29#discussion_r1094148438" expanded>

`isDone` might be a better name in my opinion.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/29#discussion_r1094150755" expanded>

Seeing from the occasions this function is called, I think it might be good to use the method signature of `System.out.printf` instead, so that we can use format strings instead of a *lot* of string concatenation `+` signs.

```java
public void printMessage(String format, Object... args) {
    String message = String.format(format, args);
    this.printMessage(Arrays.asList(message.split("\n")));
}
```
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/29#pullrequestreview-1280479148" expanded>

**Review Status:** COMMENTED

Very good job, and definitely not something like an average iP repo at this time of the semester! 💯

I have a couple of suggestions and comments here, do have a look.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/119#discussion_r1094134660" expanded>

I think `HORIZONTAL_LINE` and `INDENTATION` might be better names for these two variables.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/119#discussion_r1094136430" expanded>

I believe a helper function like

```java
static void printlnWithIndentation(String string) {
    System.out.print(INDENTATIONS);
    System.out.println(string);
}
```

would be helpful in this `main` function to avoid code repetition, as I see a lot of `System.out.println(INDENTATIONS + "something")` in this file.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/119#discussion_r1094136905" expanded>

```suggestion
        while (true) {
```

I noticed similar cases in many other lines as well, it might be good to modify them to fully follow the style guide.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/119#discussion_r1094139638" expanded>

A `switch`/`case` statement might be more readable than `if`/`else` in this situation in my opinion.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/119#discussion_r1094141528" expanded>

Perhaps `userInput` would be a better name here, as I would expect `readLine` to be the name of a function that reads user input instead.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/119#pullrequestreview-1280466284" expanded>

**Review Status:** COMMENTED

Very nice code! Here are some of my thoughts regarding it in more details.
</panel>

</panel>

<panel type="info" header="### 20. NG T..KEAN `@HiIAmTzeKean` (14 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/152#discussion_r1095305711" expanded>

Can using final static constants for these messages to avoid magic values appearing on code
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/152#discussion_r1095305903" expanded>

Confusing name here. deadline string in Deadline class?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/152#discussion_r1095306039" expanded>

Use a constant variable for this?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/152#discussion_r1095306237" expanded>

Use a UI class to perform these UI interface?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/152#discussion_r1095306533" expanded>

Confusing comment here.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/152#discussion_r1095306867" expanded>

can consider from inheriting from deadline class instead since the from attribute is also there.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/152#discussion_r1095307076" expanded>

Use a switch statement for more clarity?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/152#pullrequestreview-1282213830" expanded>

**Review Status:** COMMENTED

Great code overall!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/171#discussion_r1095300973" expanded>

Lots of magic variables. Maybe you could consider having a
final static String CONSTANT = "Some string";
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/171#discussion_r1095302177" expanded>

Protected variables here are a good idea to allow subclass to view the variable
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/171#discussion_r1095302959" expanded>

The main method is very long, maybe you could consider extracting methods out?
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/171#discussion_r1095303619" expanded>

Maybe consider using enums for your switch case. Enums are like "constants" that make your code look neater and more understandable than using magic strings in your case.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/171#discussion_r1095304212" expanded>

Could consider inheriting from Deadline as the attribute "from" is already there. Inheriting from Task would mean you have to generate another from attribute
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/171#pullrequestreview-1282207269" expanded>

**Review Status:** COMMENTED

Overall, I think the code is great and minimal coding violation seen.
</panel>

</panel>

<panel type="info" header="### 21. KONG..EHAO `@kdh3799` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/59#discussion_r1094140904" expanded>

Perhaps you want to make these 2 variable names more specific? the 'from' and 'to' might be ambiguous in the sense that what they are referring to, like time, or space..?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/59#discussion_r1094144119" expanded>

Great that you make these method names proper as verbs and in camel cases
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/59#discussion_r1094145161" expanded>

Great that you make a boolean variable sounds like boolean
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/59#discussion_r1094146091" expanded>

Good indents overall
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/59#discussion_r1094147979" expanded>

Perhaps you may want to create a constant variable for the separator line to make the code cleaner and easier to modify and reuse in the future 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/59#discussion_r1094148211" expanded>

Good indent for switch cases
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/59#pullrequestreview-1280475446" expanded>

**Review Status:** COMMENTED

Great job overall! Just some little suggestions you may want to consider
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/63#discussion_r1094153600" expanded>

Maybe you can extract each switch case into a method, to make it easier to organise and maintain
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/63#discussion_r1094157378" expanded>

Maybe not necessary?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/63#discussion_r1094158221" expanded>

Good abstraction overall! the methods are defined properly
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/63#discussion_r1094160579" expanded>

Great that you make this conditional statement concise
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/63#discussion_r1094161540" expanded>

Great that you avoided magic numbers and deep nested loops!
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/63#pullrequestreview-1280494113" expanded>

**Review Status:** COMMENTED

Good job overall! just a suggestion for extracting methods
</panel>

</panel>

<panel type="info" header="### 22. CHOO..HONG `@choongzhanhong` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/118#discussion_r1092770780" expanded>

I really like that you have extracted all these methods out! However, could it be better to also extract the method to print a horizontal line?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/118#discussion_r1092773277" expanded>

Would it be good to also extract these as a method? Likewise, for the below blocks too.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/118#discussion_r1092774850" expanded>

Perhaps it might be useful to indicate the intended format input via some comments?
So that we can understand why you are splitting through `"/by"` and what the outcome is supposed to be.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/118#discussion_r1092777762" expanded>

Could `temp` as a variable name be insufficiently descriptive?
Likewise, the numbering of the variables as well.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/118#discussion_r1092778554" expanded>

I like how your similar methods are named consistently.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/118#pullrequestreview-1278439976" expanded>

**Review Status:** COMMENTED

Overall, very well-organised.
A few comments on methods that could be extracted, as well as improving code readability for other users.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/203#discussion_r1092755828" expanded>

I like the fact that you split the if/else blocks quite meaningfully, along with descriptive comments.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/203#discussion_r1092758471" expanded>

Perhaps it might be good to indent the multiple line comments to be aligned with the block?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/203#discussion_r1092759671" expanded>

I like that you extracted these as properties. If they're constants, could you give the proper modifiers and variable name as well?

</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/203#discussion_r1092760773" expanded>

Could there be fewer new lines here?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/203#discussion_r1092761332" expanded>

Could the comment be indented/spaced closer to the block it's referring to?
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/203#discussion_r1092766518" expanded>

Perhaps a space could be added before the opening braces, like so: `else {`?
I believe there are multiple occurrences below as well.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/203#pullrequestreview-1278415152" expanded>

**Review Status:** COMMENTED

Looks good!
Mainly, with regards to code style, I have pointed out some areas regarding spacing and comments that you may find could be addressed.
</panel>

</panel>

<panel type="info" header="### 23. BRAN.. WEI `@brennanzuz` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1093007545" expanded>

Interesting use of StringBuilder which was not covered by us. This allowed you to create this TaskList.java file that allows the array to be stored in an object with its own encapsulated methods that allow the inner workings to be abstracted👍
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1093009433" expanded>

While TaskList is a custom object, it still is primarily a container of tasks, and so should follow the naming convention of having a plural form like `tasksList`.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1093012883" expanded>

The `firstSentence` and `secondSentence` variables are constants and should be capitalised. Either that, or simply concatenating them into the `printLines()` function should be fine, as this would be more consistent with the other string literals you left in some lines; converting **all** literals into constants is quite an unnecessary task imo. Not sure if the single line if-else statement is allowed, but I'd rather use normal if-else statement for consistency sake.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1093014641" expanded>

You came prepared with error handling statements, which is great for saving time later on!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1093016085" expanded>

Multi-line code. The line is not excessively long, so I don't see a need for a break line here.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#pullrequestreview-1278800105" expanded>

**Review Status:** COMMENTED

Very professional way of handling each input by creating a handler for each input, and also having very few lines of code in the `main` function. This is characteristic of large projects. However, this might be overly ambitious at this point in time. "Premature optimization is the root of all evil in programming.", and evolving the code as the project grows should be how it progresses, because currently it is a bit difficult to read having to jump around different handlers. This will be improved with some comments in the future, but currently `handler` is pretty vague and expected to be at a higher level of abstraction in a large project; not just the display to console.

I totally get where you're coming from, and there is no harm in leaving room for later implementations, so overall, the code quality is excellent with a clear conscious for neatness and abstraction, though perhaps a little too ambitious.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/180#discussion_r1092939846" expanded>

The plural form should be used to represent the array, so `tasksArray` would follow the coding standard.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/180#discussion_r1092944175" expanded>

`final` variables are constants that should be capitalised, so `MARGIN` would be a better variable name.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/180#discussion_r1092946205" expanded>

I think the coding standards mentioned how single letter iterators are allowed for loops. So I think this is okay :)
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/180#discussion_r1092949842" expanded>

Good and consistent use of setters even though it's tempting to directly access and modify.👍
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/180#discussion_r1092953766" expanded>

The switch statement's cases should all be on the same level of indentation (weird I know, but it said so here [https://se-education.org/guides/conventions/java/basic.html](https://se-education.org/guides/conventions/java/basic.html) :/)
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/180#discussion_r1092956679" expanded>

Not entirely sure if this was allowed, but I'd rather not use it and stick with if-else statements for consistency sake.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/180#pullrequestreview-1278688923" expanded>

**Review Status:** COMMENTED

Has a few minor coding standard violations but otherwise it is mostly acceptable at this stage.
</panel>

</panel>

<panel type="info" header="### 24. KISH..OKAN `@kishore-a00` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/17#discussion_r1093120113" expanded>

Good use of class inheritance (adding just the necessary features for the subclass).
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/17#discussion_r1093120949" expanded>

Code is well structured as there is spacing between methods. Great for readability!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/17#discussion_r1093123454" expanded>

Nice use of enums to standardize the inputs
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/17#discussion_r1093125646" expanded>

Wow, well done grouping files and organising them in separate folders! It makes the code workspace neater.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/17#discussion_r1093291370" expanded>

Good usage of handling exception cases 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/17#discussion_r1093292841" expanded>

Method names describe the function well, nice :)
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/17#pullrequestreview-1278964619" expanded>

**Review Status:** COMMENTED

A job well done :D I like how polished your code looks and great job with the descriptive comments. Keep up the great work thus far!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/106#discussion_r1092757795" expanded>

Good job importing only the classes that you need as it makes the class easier to comprehend and maintain.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/106#discussion_r1092759756" expanded>

Perhaps move the `else if` and `else` blocks to start after the closing bracket (Cuddle braces).
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/106#discussion_r1092760213" expanded>

Perhaps include a space between `else` and the open curly brace.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/106#discussion_r1092761775" expanded>

Perhaps include a space between `bye()` and the opening curly brace to maintain consistency throughout your code. 
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/106#discussion_r1092763903" expanded>

Perhaps include a space between `if (tasks[idx].isDone())` and the opening curly brace.
Also, maybe include a space between `else` and the opening curly brace (line 49)
Lastly, do consider putting the `else` block after the closing brace (line 48 and 49)
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/106#pullrequestreview-1278421626" expanded>

**Review Status:** COMMENTED

Overall, the code is written well. There are just several minor coding standards that have been violated. There is good use of camel case thorughout.
</panel>

</panel>

<panel type="info" header="### 25. WU Z..ZHEN `@wuzhzn` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/32#discussion_r1092756473" expanded>

Boolean variables should be named to sound like booleans. For example, "hasEnded"
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/32#discussion_r1092757899" expanded>

Add a space after the first "+"
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/32#discussion_r1092760713" expanded>

The string divider can be a constant.
Constants should be named in all caps.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/32#discussion_r1092761583" expanded>

The methods to print user output can be extracted
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/32#discussion_r1092762007" expanded>

Divider and line separator can be one variable/constant 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/32#pullrequestreview-1278419776" expanded>

**Review Status:** COMMENTED

Overall, the code is quite easy to understand and follows the coding standards except for a few parts where the methods can be extracted and the variables can be defined as constants to avoid repeating.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/147#discussion_r1093340438" expanded>

The string Dash can be renamed to all caps as it is a constant
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/147#discussion_r1093365846" expanded>

Can possibly extract most of the methods to print user output to a separate class/method for better readability
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/147#discussion_r1093369321" expanded>

The naming can be better. In this case, since it's the index of the task, something like taskIndex might offer better readability.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/147#discussion_r1093371260" expanded>

This is a temporary string array, so should not be named with caps
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/147#discussion_r1093378222" expanded>

The if-else conditions only differ by the [] and [X]. Might be more concise to summarise it in one statement through utilising the isDone method.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/147#discussion_r1093380143" expanded>

Might be more readable to include/delete relevant spaces before and after the + or " "
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/147#pullrequestreview-1279286094" expanded>

**Review Status:** COMMENTED

I like how the main method is quite abstract, and the code is generally quite good, with some mistakes in spaces and naming conventions.
</panel>

</panel>

<panel type="info" header="### 26. LOH ..RIAN `@KedrianLoh` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/117#discussion_r1093982668" expanded>

Hi, you can consider removing the break here as it might not be necessary when you are using if-else statements. 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/117#discussion_r1093984017" expanded>

Hi, you can consider shifting the else-if statement to after the curly brackets(to line 44).
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/117#discussion_r1093988847" expanded>

Good job! Indentation for wrapped lines is 8 spaces!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/117#discussion_r1093989972" expanded>

Hi, you can consider removing these empty spaces as they are not needed.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/117#discussion_r1093990387" expanded>

Hi, you can remove these empty lines after our else statements
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/117#discussion_r1093990499" expanded>

Hi, you can remove these empty lines after the else statements
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/117#pullrequestreview-1280252460" expanded>

**Review Status:** COMMENTED

Good job overall!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/187#discussion_r1094140987" expanded>

Hi, you can consider to using a named constant for the number 100 to avoid using a magic number
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/187#discussion_r1094149236" expanded>

Hi, you can consider using camelCase for method names instead of using PascalCase.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/187#discussion_r1094150147" expanded>

Hi, you can consider using the same level of abstraction instead of having multiple levels of abstraction.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/187#discussion_r1094155951" expanded>

Hi, you can consider using camelCase for TaskName instead of using PascalCase.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/187#discussion_r1094158932" expanded>

Hi, you can consider using camelCase for the variable UserInput.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/187#pullrequestreview-1280475574" expanded>

**Review Status:** COMMENTED

Good job overall!
</panel>

</panel>

<panel type="info" header="### 27. WANG..GBIN `@YongbinWang` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/45#discussion_r1094224443" expanded>

Perhaps it might be better to refactor this portion into a method for better readability of your main function.
For example: greetings().
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/45#discussion_r1094226919" expanded>

If else conditions are defined clearly to avoid deep nesting. Good job!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/45#discussion_r1094229839" expanded>

Expressions are easy to understand and not too complicated. Well done
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/45#discussion_r1094237231" expanded>

Perhaps it might be better to split the user input before the if-else statements to prevent repetitive code such as 
String[] inputs = action.split(" ");
int ind = Integer.parseInt(inputs[1]) - 1; 
Other than that, conditions are well set.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/45#discussion_r1094238678" expanded>

Perhaps you can add in comments before the methods to provide a brief overview of the method for readers to understand it better!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/45#pullrequestreview-1280598947" expanded>

**Review Status:** COMMENTED

Overall good job in implementing the logic of the program, it is well thought out. However some statement can be refactored for better readability of the code, understand that this is still a work in progress.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/140#discussion_r1094014148" expanded>

I like how you name your constants, it is very clear and concise.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/140#discussion_r1094016518" expanded>

I like how you name your methods and follow pascalcase formatting well.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/140#discussion_r1094017652" expanded>

Maybe you can consider following a standard line spacing format such as no spacings inside a {} or one spacing inside a {}.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/140#discussion_r1094021334" expanded>

I like that array specifiers must be attached to the type not the variable.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/140#discussion_r1094023216" expanded>

Maybe you can consider switching to switch cases for readability.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/140#discussion_r1094024237" expanded>

I like that your cases are defined clearly to avoid nesting, it is very clear.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/140#pullrequestreview-1280333647" expanded>

**Review Status:** COMMENTED

Looks good to me. Overall code structure is very smooth and following coding convections very well.
</panel>

</panel>

<panel type="info" header="### 28. CHEN..NITA `@JuneNita` (14 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/12#discussion_r1095228451" expanded>

I think this variable declaration part could be moved to the top
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/12#discussion_r1095230779" expanded>

I am not sure, but maybe this could be removed as it is not used and might be redundant
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/12#discussion_r1095232506" expanded>

I think 't' variable name is quite unclear. Perhaps a more intuitive variable name? 
I noticed the same issue in other places too

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/12#discussion_r1095236478" expanded>

I think maybe this part can be extracted out into a separate method e.g. greet();
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/12#discussion_r1095238330" expanded>

```
    String command = line.substring(DEADLINE_COMMAND);
```
I think the magic number should be avoided, maybe it can be declared as a constant instead.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/12#pullrequestreview-1282103893" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/55#discussion_r1095221031" expanded>

I think this boolean variable (buildContent) could start with is, has, was, etc to make it more intuitive
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/55#discussion_r1095301869" expanded>

Nice and organized layout for switch statement
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/55#discussion_r1095303574" expanded>

Nice job with naming the variables 👍
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/55#discussion_r1095305782" expanded>

I like how you list the imported class explicitly, good job
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/55#discussion_r1095305934" expanded>

I like how you comment the code following Javadoc style 👍
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/55#discussion_r1095312172" expanded>

*only line 140
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/55#pullrequestreview-1282093749" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/55#pullrequestreview-1282222871" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 29. DEEP..AWAN `@DeepanjaliDhawan` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/91#discussion_r1094177209" expanded>

Good job of executing the SLAP method
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/91#discussion_r1094178491" expanded>

Can make the method name for clear for the readers to understand
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/91#discussion_r1094180187" expanded>

good job of putting default in switch case
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/91#discussion_r1094183323" expanded>

good job adding comments
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/91#discussion_r1094193332" expanded>

Hi... according to camelCase, `Deadline` will be `deadline` or `deadLine`
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/91#pullrequestreview-1280529212" expanded>

**Review Status:** COMMENTED

Really nice to read your code where you have successfully adhered to the code quality. Example implementing camelCase and PascalCase... Good Job
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/187#discussion_r1094143547" expanded>

Please consider naming class in PascalCase ie "Todos" to "ToDos" to distinguish between the 2 words
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/187#discussion_r1094145335" expanded>

Please consider writing booleans as booleans ie Instead of is_marked(), can write isMarked
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/187#discussion_r1094147297" expanded>

Please consider using plurals for collection of objects... `todo` to plural
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/187#discussion_r1094150467" expanded>

Please consider giving a much clearer name of the variables to show its purpose instead of `int i`
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/187#discussion_r1094153984" expanded>

Please leave a space between the 2 brackets `) {`
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/187#discussion_r1094155506" expanded>

Please leave a space between `while` and `(`
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/187#pullrequestreview-1280479227" expanded>

**Review Status:** COMMENTED

Overall good implementation and enforcement of the coding standards but please pay attention to some nitty gritty details
</panel>

</panel>

<panel type="info" header="### 30. CHEW.. MAX `@MuxPotato` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/46#discussion_r1094135771" expanded>

Good use of constants to avoid magic literals 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/46#discussion_r1094138580" expanded>

Perhaps this can be replaced with a switch case statement, for every statement besides the first and last? I think it will improve the readability
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/46#pullrequestreview-1280467920" expanded>

**Review Status:** COMMENTED

Overall excellent code with it being very readable. No difficult understanding the code, with notably good use of string constants to replace magic literals. Nice!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/105#discussion_r1094012983" expanded>

Naming of array of string can be better named such as "deadlines" with a 's' at the end
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/105#discussion_r1094016796" expanded>

Possible to to use switch and case instead of if else statements
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/105#discussion_r1094017348" expanded>

should leave one line of spacing in between the methods
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/105#discussion_r1094019334" expanded>

Should this be placed in 3 lines? Following the if statement coding standard
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/105#discussion_r1094020600" expanded>

For the variable name, i think a better name can be used instead of t, such as newTodoTask
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/105#discussion_r1094021322" expanded>

same as above, a more intuitive name can be used suchas newDeadlineTask
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/105#discussion_r1094021615" expanded>

same as comment for deadline and todo tasks as above
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/105#discussion_r1094023314" expanded>

same as above, better naming can be used
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/105#discussion_r1094024462" expanded>

Is this supposed to be a one liner? 
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/105#pullrequestreview-1280332797" expanded>

**Review Status:** COMMENTED

Good job, very clean code besides naming of variables and spacing. Methods were extracted and in the main function it was very easy to read. :)
</panel>

</panel>

<panel type="info" header="### 31. BERN..ENDY `@BernardLesley` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/123#discussion_r1094077850" expanded>

I think you can use private/protected for the attribute for better data encapsulation
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/123#discussion_r1094079328" expanded>

I like how you use all uppercase letters for constant variable
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/123#discussion_r1094080870" expanded>

case clause should not be indented
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/123#discussion_r1094082375" expanded>

I think you can use private/protected for the attribute for better data encapsulation
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/123#discussion_r1094082543" expanded>

I think you can use private/protected for the attribute for better data encapsulation
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/123#discussion_r1094084060" expanded>

Line length should be no longer than 120 chars. Use line wrapping at appropriate place on the sentence
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/123#discussion_r1094086080" expanded>

Line length should be no longer than 120 chars. Use line wrapping at the appropriate place on the sentence
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/123#pullrequestreview-1280389862" expanded>

**Review Status:** COMMENTED

Overall, the naming standard has been used appropriately for the method, class, and constant name. However, pay attention to indentation and line wrapping to make the code more readable.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/178#discussion_r1094106463" expanded>

It may be clearer to declare a constant (for example: TASK_LENGTH) to denote the length of array
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/178#discussion_r1094107213" expanded>

I think you can consider using switch case, instead of if else. However the readability is still good in this case.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/178#discussion_r1094108797" expanded>

You can consider changing the naming of 'list' to 'tasks', because the naming may be too vague
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/178#discussion_r1094111852" expanded>

I like how you extract and group the method
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/178#pullrequestreview-1280425607" expanded>

**Review Status:** COMMENTED

Overall, the code has adhered to the coding standards and code quality guidelines. Some minor fixes and you're good to go. Well done!
</panel>

</panel>

<panel type="info" header="### 32. VINI..AVYD `@DavidVin357` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/24#discussion_r1092832960" expanded>

Well done with extracting method for a welcome!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/24#discussion_r1092833834" expanded>

The name is self-explanatory and follows the convention, very good
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/24#discussion_r1092836855" expanded>

"Not" in a method can be misleading and not very readable -  consider replacing the `setDone` and `setNotDone` with this one method or something similar.
```
public void setIsDone(boolean value) {
		isDone = value;
	}
```
(you can also change the setter name for `setIsDone` in this case)
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/24#discussion_r1092838050" expanded>

I think putting `showWelcomeMessage` in the beginning of the class can increase readability and logical flow of the code
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/24#discussion_r1092842474" expanded>

This line divider usage got quite repetitive in different methods - maybe it's worth to put it into a constant? (like `static final LINE_DIVIDER`)
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/24#discussion_r1092844783" expanded>

I like how you extracted and named methods for the `switch case` - very readable and clean
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/24#pullrequestreview-1278532123" expanded>

**Review Status:** COMMENTED

Overall, the code is clean and readable. The logic is nicely divided in different methods, which makes it very structured. Just several suggestions on readability and logical flow 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/205#discussion_r1092787379" expanded>

Seems like it is a constant, so maybe consider using `static final LINE_DIVIDER` (or some other similar name)?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/205#discussion_r1092789638" expanded>

I think you use this list to store the different tasks, so maybe it's better to name it as `tasks`? :)
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/205#discussion_r1092792218" expanded>

Maybe something like `tasksCount` can tell better on what you are counting here?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/205#discussion_r1092794350" expanded>

I think naming it `checkerContent` or some other noun may better represent the meaning of the variable (verbs are more suitable to be used for the methods)
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/205#discussion_r1092796660" expanded>

Extracting i+1 to another line as `i++` may make the code a little bit more clean)
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/205#pullrequestreview-1278463356" expanded>

**Review Status:** COMMENTED

LGTM, just several naming proposals :) 
Also, maybe consider `switch case` instead of lots `if else` statements.  Some comments for explaining specific variables might also be nice. 
Overall, it's fine in terms of code standard.
</panel>

</panel>

<panel type="info" header="### 33. YI D..AEUN `@de-yi` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/16#discussion_r1093198045" expanded>

Since this part appears in several methods, it can be extracted and reused!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/16#discussion_r1093200502" expanded>

I like how you made different user commands into constants and listed at the front.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/16#discussion_r1093203154" expanded>

I like how you used "private" instead of public scope so that it can only be accessed by methods in this class:)
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/16#discussion_r1093206485" expanded>

Just an idea but maybe you can use (index+1) instead of setting another variable named count!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/16#discussion_r1093209003" expanded>

Just a minor quention: Why is this variable named textCount instead of taskCount??
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/16#discussion_r1093216395" expanded>

Shouldn't this method use small c instead of capital C?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/16#pullrequestreview-1279079765" expanded>

**Review Status:** COMMENTED

Overall I liked how you tried to use OOP and fllow coding standards that we learnt during lecture :) Good luck with latter parts!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/204#discussion_r1092758958" expanded>

Should this method be divided? For example, mark method, unmark method can be seperated from this method.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/204#discussion_r1092759710" expanded>

Should this be indented?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/204#discussion_r1092760152" expanded>

I like how you used protected variables instead of public!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/204#discussion_r1092761092" expanded>

I like how you used @Override to make sure that you are properly overriding method from its parent
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/204#discussion_r1092763539" expanded>

Maybe numberOfTasks can be protected variable too, so that it can only be acceessed by get method:)
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/204#pullrequestreview-1278423181" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 34. NG H.. CHI `@nghochi123` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/16#discussion_r1092859440" expanded>

Good that there are constants for different commands so that it is easy to change everything later on.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/16#discussion_r1092859826" expanded>

Constants and function names are standard and easy to understand.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/16#discussion_r1092860048" expanded>

A switch statement would work as well.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/16#discussion_r1092860253" expanded>

You might want to split this part into a second line as it's too long.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/16#discussion_r1092860602" expanded>

eventDetailsPartOne and Two are quite ambiguous - variables named from and to (or variants) would be sufficient.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/16#discussion_r1092861188" expanded>

The variables 'done' and 'notDone' are constants, and should be fully capitalized.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/16#pullrequestreview-1278570257" expanded>

**Review Status:** COMMENTED

Overall, done pretty well! Good job.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/83#discussion_r1092866617" expanded>

Good that there are constants and the style is correct.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/83#discussion_r1092868120" expanded>

A switch statement could be useful here.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/83#discussion_r1092868793" expanded>

A variable name that gives more information could work, like "taskCount"
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/83#discussion_r1092869504" expanded>

Need to use camelCase instead of snake_case or mixed
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/83#discussion_r1092870515" expanded>

isDone could be in ToDo instead of Task because only ToDo uses it and not the other stuff like Deadline and Event
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/83#pullrequestreview-1278581211" expanded>

**Review Status:** COMMENTED

Overall well done, code is pretty neat and easy to read.
</panel>

</panel>

<panel type="info" header="### 35. ONG .. LIN `@lil1n` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/79#discussion_r1093921605" expanded>

maybe can use enum for the cases
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/79#discussion_r1093922882" expanded>

coding standard: missing space after Task 
`public class Deadline extends Task {`
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/79#discussion_r1093923903" expanded>

coding standards: there should be space after comma
`String[] deadline = commands[1].split("/by", 2);`
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/79#discussion_r1093925398" expanded>

coding standard: there should be space between the brackets
`public static Task getString(int index) {`
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/79#discussion_r1093926374" expanded>

coding standards: there should be space after comma
`String[] commands = input.split(" ", 2);`
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/79#discussion_r1093927289" expanded>

coding standard: inconsistent spacing after `(index + 1)+ "tasks`
`System.out.println("Now you have " + (index + 1) + " tasks in the list");`
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/79#pullrequestreview-1280145162" expanded>

**Review Status:** COMMENTED

maybe can take note of coding standards
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/194#discussion_r1093936615" expanded>

maybe can avoid magic number? maybe use static final int instead?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/194#discussion_r1093936860" expanded>

magic number? maybe use static final int?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/194#discussion_r1093937148" expanded>

maybe can improve the quality of the naming to `INVALID_COMMAND`?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/194#discussion_r1093938260" expanded>

maybe can improve the naming for this `INT` to be more specific and clear?
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/194#discussion_r1093939904" expanded>

coding standard: Use K&R style brackets 
`public Deadline (String taskName, StringdeadLineBy) {`
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/194#pullrequestreview-1280165767" expanded>

**Review Status:** COMMENTED

I see that you mention that you will refract later, then in addition to that maybe can improve on coding standard and maybe code quality can also be improved.
</panel>

</panel>

<panel type="info" header="### 36. KOH ..G EN `@MingEn82` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/82#discussion_r1092867621" expanded>

Code is easy to read, with good choice of method and variable names!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/82#discussion_r1092868705" expanded>

Code is easy to read!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/82#discussion_r1092871543" expanded>

Overall well done! Code is easy to read with return statements are at the top of the methods.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/82#discussion_r1092872759" expanded>

Well done! Code is easy to read
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/82#discussion_r1092873575" expanded>

Code is easy to read! A lot of effort have been made to stick to coding standards!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/82#pullrequestreview-1278582649" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/193#discussion_r1092860909" expanded>

Nice!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/193#discussion_r1092861595" expanded>

Nice! No Coding Violations
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/193#discussion_r1092863014" expanded>

Good job!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/193#discussion_r1092864053" expanded>

Good job!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/193#discussion_r1092864203" expanded>

No coding violations at all!
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/193#pullrequestreview-1278572387" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 37. PANG..MING `@Rayleigh47` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/64#discussion_r1094008975" expanded>

Naming for isValidated1 and isValidated2 can be more specific, for eg. isValidatedMark, is ValidatedUnmark.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/64#discussion_r1094011291" expanded>

Boolean methods can be phrased as a question, for example isATask.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/64#discussion_r1094013917" expanded>

Maybe use a different method name markOrNot, to make it clearer
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/64#discussion_r1094015819" expanded>

Can consider splitting the line to keep it shorter.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/64#discussion_r1094018649" expanded>

Use boolean method names like isInput instead.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/64#pullrequestreview-1280329757" expanded>

**Review Status:** COMMENTED

Comments on coding standard violations
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/87#discussion_r1094023155" expanded>

Maybe can leave a line after import
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/87#discussion_r1094028498" expanded>

Instead of using inputt maybe consider using input1/input2 or refer to the specific input.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/87#discussion_r1094029862" expanded>

Maybe use another name for ur ArrayList such as listOfTasks to be more specific
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/87#discussion_r1094030745" expanded>

Maybe can use full terms for sdnt and ednt for code readability
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/87#discussion_r1094031337" expanded>

Maybe can use full terms for l, id and td for better code readability
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/87#pullrequestreview-1280340512" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 38. TAN ..OONG `@TzeLoong` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/21#discussion_r1094183159" expanded>

I really appreciate the effort put into the randomization the farewell greetings 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/21#discussion_r1094185162" expanded>

Good use of Inheritance here 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/21#discussion_r1094186043" expanded>

Good usage of comments between each command's execution which improves readability.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/21#discussion_r1094191068" expanded>

A possible slight improvement that you can consider is using ArrayList so there is no need to specific a fixed size
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/21#discussion_r1094192132" expanded>

Good job in restricting access to object variables.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/21#pullrequestreview-1280537954" expanded>

**Review Status:** COMMENTED

Overall good job
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/124#discussion_r1094141250" expanded>

Possible improvement is using a switch statement 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/124#discussion_r1094148829" expanded>

Constant names are in uppercase and use underscore to separate words which is appropriate 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/124#discussion_r1094175341" expanded>

Good use of comments to clarify the possible scenarios 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/124#discussion_r1094177202" expanded>

Access to object variables is restricted which is good 
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/124#discussion_r1094178530" expanded>

Consider adding some comments here which can help improve readability.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/124#pullrequestreview-1280475918" expanded>

**Review Status:** COMMENTED

Overall good job
</panel>

</panel>

<panel type="info" header="### 39. KEAN..ZHAO `@typingpanda` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/72#discussion_r1094010408" expanded>

Maybe you could move the comment along the same indentation so as to avoid breaking the logical structure of the program.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/72#discussion_r1094014784" expanded>

The name of this method may be unclear as it does not indicate an action. Maybe add a verb such as print to become printNoMarkArgs. I believe that would make the purpose of the function clearer.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/72#discussion_r1094016556" expanded>

Wonderful job for keeping consistency of capital cases for all your constant values.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/72#discussion_r1094019470" expanded>

Each switch case has clear purpose, well done!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/72#discussion_r1094021459" expanded>

Maybe a verb can be used to increase clarity of function. I suggest printCmdError.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/72#pullrequestreview-1280330797" expanded>

**Review Status:** COMMENTED

Very clear and readable code! Made a few suggestion on coding standard
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/96#discussion_r1094384476" expanded>

Maybe you could abstract the parsing of the string into another method such that the code is more readable
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/96#discussion_r1094385014" expanded>

I see that you have repeated some code here. You could consider abstracting this into a method for reusability.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/96#discussion_r1094386257" expanded>

Each case in the switch statements have clear purpose, good job!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/96#discussion_r1094390438" expanded>

The name cmdSplit has an unclear meaning. Maybe you could consider rawCmd instead if that is what is intended.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/96#discussion_r1094391411" expanded>

The variable name whichTask sounds like a method that would return an integer. I suggest naming it taskNumber for enhanced readability
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/96#pullrequestreview-1280840452" expanded>

**Review Status:** COMMENTED

Good code quality overall, keep it up!
</panel>

</panel>

<panel type="info" header="### 40. PERE..AMES `@Magmanat` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/90#discussion_r1094095399" expanded>

Consider naming userInputs[0] as a more relatable variable

```suggestion
String command = userInputs[0];
            switch(command) {
```
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/90#discussion_r1094098581" expanded>

consider using naming `tasks` instead of `list` to better represent this variable

```suggestion
    private static ArrayList<Task> tasks = new ArrayList<Task>();
```
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/90#discussion_r1094102932" expanded>

consider using a setter for this task
```suggestion
        list.get(index - 1).setIsDone(true);
```
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/90#discussion_r1094121765" expanded>

Using a more descriptive name like ``addTask`` would allow better clarity

```suggestion
    public static void addItem(String item) {
```
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/90#discussion_r1094125364" expanded>

Good use of protected variables
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/90#pullrequestreview-1280411312" expanded>

**Review Status:** COMMENTED

Overall good flow of code, however could consider higher levels of extraction into separate packages
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#discussion_r1094010536" expanded>

perhaps you could use a more descriptive name for your ArrayList
```suggestion
        ArrayList<Task> taskList = new ArrayList<Task>();
```
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#discussion_r1094013876" expanded>

perhaps you could use a boolean variable in your conditional statement for your while loop?

personally I would use `isRunning`
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#discussion_r1094018991" expanded>

Good naming of variables, they are camelCase and follows coding standard
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#discussion_r1094019724" expanded>

Nice importing of individual packages!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#discussion_r1094020781" expanded>

Good use of PascalCase for your class names
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#pullrequestreview-1280330913" expanded>

**Review Status:** COMMENTED

Overall good code, however you could consider abstracting code in your Duke.java to another file to keep code cleanliness, however this would be for Code Quality instead of Coding Standard
</panel>

</panel>

<panel type="info" header="### 41. ARTE..NGOH `@ArtemiszenN` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/157#discussion_r1092751254" expanded>

Is it necessary for this variable name to be in all caps? It is not a constant variable.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/157#discussion_r1092752920" expanded>

Should these classes be extracted out?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/157#discussion_r1092754786" expanded>

Should break be on a different line?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/157#discussion_r1092756630" expanded>

I like the way constant string outputs are stored
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/157#discussion_r1092758176" expanded>

Should 100 be a magic number somewhere?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/157#pullrequestreview-1278412895" expanded>

**Review Status:** COMMENTED

LGTM overall. You might want to consider extracting the different classes in TaskList to different files.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/204#discussion_r1092759783" expanded>

Should these be extracted into different functions?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/204#discussion_r1092761061" expanded>

Should this function be stored outside? Or the class be changed to a TaskList which includes the array of tasks?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/204#discussion_r1092762518" expanded>

Should these variables be explicitly stated public/protected/private?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/204#discussion_r1092764453" expanded>

Should this line be indented?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/204#discussion_r1092766092" expanded>

Should this line (and other similar lines) have a newline added?
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/204#pullrequestreview-1278424307" expanded>

**Review Status:** COMMENTED

Overall the code works well I think, but it is quite cluttered and readability could be improved.
</panel>

</panel>

<panel type="info" header="### 42. KHOO.. RUN `@khooyourun` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/39#discussion_r1095304071" expanded>

Better to name Boolean variables in a way that sounds like a boolean
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/39#discussion_r1095306757" expanded>

I like the naming of methods here. It makes it clear what each method does.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/39#discussion_r1095307766" expanded>

I like the usage of else if statements instead of nested if statements. Makes it easy to understand.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/39#discussion_r1095312706" expanded>

Preferably name whitespaceIndex as whiteSpaceIndex with a capital S (camelCase).
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/39#discussion_r1095313611" expanded>

What does the 5 in input.substring(5) represent? Same question for the other input.substring()
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/39#pullrequestreview-1282211660" expanded>

**Review Status:** COMMENTED

Overall the code is easy to read as it uses well named modules and variables.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/201#discussion_r1095315800" expanded>

Can I check what does CMD mean? If it stands for command. I think it's better to just name it as inputCommand for readibilty.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/201#discussion_r1095316642" expanded>

The numbers like 2, 0, 1 might be considered magic numbers that hinder readability.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/201#discussion_r1095340800" expanded>

Is this if statement necessary? I think markDone would change the status icon to "X" independent of what is originally is
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/201#discussion_r1095343531" expanded>

I like the single level of abstraction applied here. Makes things easy to follow
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/201#discussion_r1095345033" expanded>

Preferably name boolean in such a way that implies it is boolean.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/201#pullrequestreview-1282227982" expanded>

**Review Status:** COMMENTED

Overall, the code is readable and the if statements are not deeply nested.
</panel>

</panel>

<panel type="info" header="### 43. LEE ..XUAN `@itszhixuan` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/23#discussion_r1094143857" expanded>

I think the boolean name of parseUserInput can be made clearer by using prefixes of "is", "has" and so on to improve readability.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/23#discussion_r1094147627" expanded>

All the variable names adheres to camelCase, good job!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/23#discussion_r1094149815" expanded>

Good job in only importing necessary libraries 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/23#discussion_r1094151516" expanded>

It would be better to add a whitespace before each comment to comply with the coding standard
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/23#discussion_r1094174892" expanded>

Good job in adhering to PascalCase for class names
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/23#pullrequestreview-1280479663" expanded>

**Review Status:** COMMENTED

Overall, very clean code. Well done!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/119#discussion_r1094449070" expanded>

Using a named constant could possibly help avoid magic numbers and improve code quality.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/119#discussion_r1094455493" expanded>

The while loop is structured logically and is easy to read. Good job!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/119#discussion_r1094459697" expanded>

You may consider using SLAP to make main easier to read.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/119#discussion_r1094465327" expanded>

Good job in using constants to assign the fixed formatting code
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/119#discussion_r1094482893" expanded>

I like how you ensured that the lines to be printed out are wrapped when appropriate, making the code easier to read.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/119#pullrequestreview-1280936353" expanded>

**Review Status:** COMMENTED

Overall well done!
</panel>

</panel>

<panel type="info" header="### 44. MANO..AJAN `@Manoj364` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/94#discussion_r1092757660" expanded>

I like how the method's name is a verb and written in camelCase
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/94#discussion_r1092758571" expanded>

This can be expressed more explicitly
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/94#discussion_r1092759099" expanded>

Perhaps you can avoid deep-nesting
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/94#discussion_r1092760346" expanded>

I like how you declared the constants appropriately
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/94#discussion_r1092761159" expanded>

I feel that this can be expressed explicitly
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/94#pullrequestreview-1278421486" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/190#discussion_r1093168169" expanded>

I like how you avoided deep-nesting
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/190#discussion_r1093173278" expanded>

Perhaps you can leave a space between your round bracket and curly bracket, so that your formatting looks consistent
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/190#discussion_r1093180697" expanded>

Perhaps this space can be removed
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/190#discussion_r1093187046" expanded>

You can consider refactoring this portion of code into a method as it is repeated multiple times in the if-else statements
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/190#discussion_r1093190758" expanded>

Perhaps you can include spaces like this to be more consistent in your formatting
```suggestion
                    System.out.println("Now you have " + taskList.size() + " task in the list.");
```
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/190#pullrequestreview-1279035924" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 45. TAN ..RETH `@Geeeetyx` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/36#discussion_r1092789395" expanded>

Good naming of methods in camelCase
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/36#discussion_r1092789821" expanded>

Good constant names that follow all uppercase with underscore to seperate words
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/36#discussion_r1092790946" expanded>

Correct form for conditionals on another line for if-else statement
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/36#discussion_r1092791235" expanded>

Correct form for comments
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/36#discussion_r1092792074" expanded>

Can consider using if-else statement for more clarity
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/36#pullrequestreview-1278463197" expanded>

**Review Status:** COMMENTED

Good job overall, the change in name for the program to PAPA was very creative
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/203#discussion_r1095431614" expanded>

Good that variable names follow camel case
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/203#discussion_r1095432849" expanded>

Might be better to use switch case statements here
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/203#discussion_r1095436688" expanded>

It might be good to refactor these else if statements to be methods
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/203#discussion_r1095437243" expanded>

Clear variable names that are easy to understand
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/203#discussion_r1095438054" expanded>

Perhaps remove comments that are not explaining the code 
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/203#pullrequestreview-1282393970" expanded>

**Review Status:** COMMENTED

Overall good work, but you can tidy up the code to make it look like nicer. 
</panel>

</panel>

<panel type="info" header="### 46. CLEO..FENG `@cleoncheng2000` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/44#discussion_r1092757638" expanded>

Perhaps you can create a variable for the array size 100? So that it will be easier to change in the future.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/44#discussion_r1092760341" expanded>

This is a long else-if line. Perhaps you can use a more intuitive method here?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/44#discussion_r1092760879" expanded>

Nested if-else statements in else statement. Perhaps you can extract this out and separate them?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/44#discussion_r1092761914" expanded>

Perhaps you can use a more intuitive variable name for your list in the context of Duke?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/44#discussion_r1092762741" expanded>

Perhaps you can use a more intuitive variable name here?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/44#pullrequestreview-1278421457" expanded>

**Review Status:** COMMENTED

Overall looks good!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/158#discussion_r1093268691" expanded>

Perhaps you can use a variable to store 100? For easy change in the future.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/158#discussion_r1093281044" expanded>

Any reason why you used a loop to just check the first word instead of using the first index?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/158#discussion_r1093293705" expanded>

I like how you used "tasks"  for the name of a collection of objects. Good work!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/158#discussion_r1093296909" expanded>

I like the use of camelCase for the variable name "addTask". Good work!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/158#discussion_r1093301716" expanded>

Perhaps a more intuitive function name here like "getCommand"? 
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/158#pullrequestreview-1279183036" expanded>

**Review Status:** COMMENTED

Good work overall!
</panel>

</panel>

<panel type="info" header="### 47. LEON..CHAO `@Chick3nBoy` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#discussion_r1094141077" expanded>

Could maybe use Tasks instead of Task for array naming.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#discussion_r1094143745" expanded>

Perhaps a switch statement would be better instead of multiple if else since there are multiple conditions.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#discussion_r1094146729" expanded>

The code associated for event could perhaps be made easier to read by refactoring into a doEvent(); method
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#discussion_r1094149725" expanded>

Perhaps the naming should be plural i.e. inputLines
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#discussion_r1094152341" expanded>

Perhaps declare Task item above so that it can be used in the if statement below as well.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/70#pullrequestreview-1280475709" expanded>

**Review Status:** COMMENTED

Overall minimal mistakes, good job!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/174#discussion_r1095393450" expanded>

Good declaration of new variables! Makes code more readable
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/174#discussion_r1095396171" expanded>

Perhaps a comment detailing the while loop could be helpful.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/174#discussion_r1095399128" expanded>

Perhaps using a static final instead of 101 may help.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/174#discussion_r1095401155" expanded>

Perhaps adding more details to the help message on how to use the different commands would be useful.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/174#discussion_r1095404931" expanded>

Maybe adding a line here would be good as there's no space between these two methods.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/174#pullrequestreview-1282338814" expanded>

**Review Status:** COMMENTED

Very well-written and readable code with little details to nitpick on.
</panel>

</panel>

<panel type="info" header="### 48. GAU ..RALD `@jeraldgau` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/105#discussion_r1094073949" expanded>

Perhaps you might want to consider refactoring this chunk of code into another method? Similar chunks of code can be found in deadlineTask and eventTask as well.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/105#discussion_r1094079288" expanded>

I like how you grouped the processing of all the different commands into one method call, it makes the code cleaner and more readable.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/105#discussion_r1094080794" expanded>

Good job refactoring the greet and bye messages into separate method calls to make the code cleaner.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/105#discussion_r1094083193" expanded>

Perhaps you can consider leaving one line of space between different methods to make it more clear where one method ends and the next begins.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/105#discussion_r1094092145" expanded>

Perhaps you might want to avoid using one letter variable names throughout your code? In this case, maybe a variable name like currentDeadline might be better?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/105#pullrequestreview-1280264018" expanded>

**Review Status:** COMMENTED

Overall, I think that your code is very neatly organised and appropriately refactored into separate method calls, making it very readable and easy to follow along. Good job!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/150#discussion_r1093979392" expanded>

Good job explicitly importing java utility classes.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/150#discussion_r1093981748" expanded>

Good job in following the coding standard for if-else statements
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/150#discussion_r1093982367" expanded>

Good job in not making any line of code longer than 120 characters in length.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/150#discussion_r1093982579" expanded>

Good job in making line indentations 4 spaces.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/150#discussion_r1093983023" expanded>

Good job in using K&R style brackets throughout your code.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/150#pullrequestreview-1280236017" expanded>

**Review Status:** COMMENTED

Overall, I find that your code follows the coding standard quite well and is very easy to read through. Well done!
</panel>

</panel>

<panel type="info" header="### 49. NG K.. WEN `@ngkaiwen123` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/61#discussion_r1092804413" expanded>

Great job! Code is extremely readable, no deep nesting and complex expressions over here.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/61#discussion_r1092806178" expanded>

Absence of magic numbers by explaining meaning of number in the variable name. Follows code readability standards. Good job!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/61#discussion_r1092810022" expanded>

Naming of methods follows readability guidelines of using verbs for methods/functions. Nice!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/61#discussion_r1092812917" expanded>

Perhaps this 4 lines can be made into a new method, to improve readability? It seems repeated in many other methods and it may help in structuring the code logically.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/61#discussion_r1092814842" expanded>

Maybe this chunk of code can be shifted below your public static void startProgram( )? It may help in structuring your code to make it more logical and hence readable for the reader.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/61#pullrequestreview-1278487985" expanded>

**Review Status:** COMMENTED

All in all well done! Code is well written and readable for others. Although some parts can be shifted around to make it even more readable.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/112#discussion_r1092753813" expanded>

I believe that "Switch" statements should have no identations for 'case' clauses?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/112#discussion_r1092757207" expanded>

Name of class might fit the coding standards better if it was changed to "ToDo" instead? 
(Class/enum names must be nouns and written in PascalCase E.g Line, AudioSystem).
```suggestion
public class ToDo extends Task{
```
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/112#discussion_r1092758463" expanded>

Great! Array specifiers attached to the type and not the variable.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/112#discussion_r1092760394" expanded>

I think the layout for "if-else" statements would better fit the coding standards if it were to be changed to this?
```suggestion
                        if (t== null){
                            break;
                        } else {
                            System.out.println(counter + ". " + t);
                            counter++;
                        }
```
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/112#discussion_r1092762257" expanded>

Great! Conditionals are put on a separate line.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/112#pullrequestreview-1278416189" expanded>

**Review Status:** COMMENTED

Looks good! Code generally follows the coding standards. Some suggestions for coding standards are given. :)
</panel>

</panel>

<panel type="info" header="### 50. REYN.. LAM `@Reynold-SL` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/26#discussion_r1094101679" expanded>

Perhaps consider using a switch statement to make the code more readable?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/26#discussion_r1094102860" expanded>

```suggestion
    protected String from;
```
perhaps you can consider making this variable protected to prevent accidental changes?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/26#discussion_r1094115980" expanded>

```suggestion
public Deadline(String description, String by) {
```
Perhaps you can amend the method by adding a public for accessibility?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/26#discussion_r1094118541" expanded>

perhaps you can create a method to check for the size to prevent nested loops?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/26#discussion_r1094121458" expanded>

```suggestions
Deadline[] deadline = new Deadline(parts[0], parts[1]);
addTasks(deadline);
```
perhaps you should create a variable first before adding to the method for better readability?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/26#pullrequestreview-1280418571" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/178#discussion_r1094016658" expanded>

```suggestion
    private final String BY
```

perhaps you could try changing the naming of the variable to the above? I notice similar issues in other places
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/178#discussion_r1094021524" expanded>

```suggestion
   } else { 
       // add task
```

Perhaps would it be better if you indent the message above the position in the code? I notice a similar issue in other places

</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/178#discussion_r1094022149" expanded>

```suggestion
   * Method to print the added message to the user after prompting input
```

Perhaps you could add a * in front of this comment? I notice a similar issue in other places.

</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/178#discussion_r1094023888" expanded>

I like the naming convention you have used here
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/178#discussion_r1094093499" expanded>

```suggestion 
 public void setDone(boolean isDone) {
```

Perhaps you can change the naming of the boolean input to the above? 
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/178#pullrequestreview-1280335126" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/178#pullrequestreview-1280408267" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 51. TOH ..FENG `@Toh-HongFeng` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/3#discussion_r1094141493" expanded>

Method names can be changed to PascalCase
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/3#discussion_r1094143929" expanded>

Can standardize across files to have no space between method name and open parenthesis. 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/3#discussion_r1094146634" expanded>

Good variable naming. 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/3#discussion_r1094147544" expanded>

Correct indentation for flow control. 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/3#discussion_r1094148428" expanded>

Variable name can be less vague. 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/3#pullrequestreview-1280476265" expanded>

**Review Status:** COMMENTED

Good coding standards. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/200#discussion_r1094151251" expanded>

Executing list command can be done on another java file. 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/200#discussion_r1094153139" expanded>

Naming for this variable can be clearer. 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/200#discussion_r1094155481" expanded>

Can add comments between each command's execution to improve readability. 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/200#discussion_r1094156192" expanded>

Inheritance to split task types is well done. 
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/200#discussion_r1094158003" expanded>

Good job restricting access to object variables. 
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/200#pullrequestreview-1280491927" expanded>

**Review Status:** COMMENTED

Good job on code quality, but can be improved. 
</panel>

</panel>

<panel type="info" header="### 52. TAN ..RIAN `@briantjs00` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/8#discussion_r1094114584" expanded>

Could extract "____________________________________________________________\n" as a constant instead. To shorten the lines and make the code more readable
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/8#discussion_r1094117417" expanded>

Could the square brackets be added here to simplify the code
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/8#discussion_r1094121477" expanded>

Could the lines be extracted into a function instead for more readability
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/8#discussion_r1094126454" expanded>

Could maybe use .equalsIgnoreCase() instead of .contains() or .equals() for easier coding
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/8#discussion_r1094133725" expanded>

Could these lines be extracted into methods under Task?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/8#pullrequestreview-1280437174" expanded>

**Review Status:** COMMENTED

Overall, the code is difficult to read as everything is put under main and some of the coding standards were not upheld. Could maybe extract the codes under each if-else, else if conditions for easier reading and understanding of what the codes are doing. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/81#discussion_r1094017627" expanded>

I agree with KN-CY, methods should be written in camelCase. But good job with the naming of methods
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/81#discussion_r1094019520" expanded>

Maybe should insert "@Override" here for the toString method. Do it for the other subclasses of Task as well.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/81#discussion_r1094024404" expanded>

Good job in listing the imported classes explicitly
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/81#discussion_r1094025401" expanded>

I agree that maybe you could consider constructing methods for each cases
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/81#discussion_r1094081616" expanded>

I agree, can consider standardising the empty line spacing between each cases and the extra empty lines to make the code look neater.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/81#pullrequestreview-1280336369" expanded>

**Review Status:** COMMENTED

Overall, the code follows most of the coding standards, and the extraction of string literals to static makes the code easy to read.
Well done!
</panel>

</panel>

<panel type="info" header="### 53. KOH ..RCUS `@Koh-Jing-Jie-Marcus` (14 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/49#discussion_r1092874087" expanded>

good readability, avoided use of deep nesting
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/49#discussion_r1092875374" expanded>

good code quality, avoided use of magic numbers
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/49#discussion_r1092876542" expanded>

good naming scheme, using nouns for things/ verbs for actions
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/49#discussion_r1092878009" expanded>

comments are well used to explain the code clearly (minimal and sufficient)
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/49#discussion_r1092880967" expanded>

avoided usage of long methods, good code quality
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/49#pullrequestreview-1278591385" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/49#pullrequestreview-1278597388" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/49#pullrequestreview-1278601736" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/125#discussion_r1092863160" expanded>

Boolean variable (status) should be named to sound like boolean
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/125#discussion_r1092863994" expanded>

very good and neat nesting
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/125#discussion_r1092866025" expanded>

method names are all represented well with the use of camelCase
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/125#discussion_r1092867116" expanded>

switch cases are following the proper form
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/125#discussion_r1092867889" expanded>

correct naming scheme (camelCase) for boolean variable
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/125#pullrequestreview-1278575619" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 54. SURE.. RAM `@TopGun2001` (14 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/137#discussion_r1095334170" expanded>

I like how you have added an extra if statement to check if the task is marked/unmarked. This reduces the task for your program to mark/unmark it again which is quite efficient. 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/137#discussion_r1095334661" expanded>

You have nested the **if-else** statements and they look a bit unstructured. I'd suggest you to use switch statements if that works out for you.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/137#pullrequestreview-1282251428" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/152#discussion_r1095303189" expanded>

I like how you have given comments for the **@Override getStatusAndDescription** method along with the alternative method to execute the required output. I also had doubt how to @Override methods while implementing my own iP but this would be definitely useful for others who read your code. Well done! 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/152#discussion_r1095306538" expanded>

Proper **if-else** coding standards are met according to the **Java Coding Standard**.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/152#pullrequestreview-1282210194" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/206#discussion_r1095328462" expanded>

I agree with @lihka1202 . I'd suggest to give a variable name like **commandIndex** or **inputIndex** as it it a bit more clear for readers to understand what you are referring to.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/206#discussion_r1095329570" expanded>

New implementation I've noticed. I have not seen this before. Maybe something that I should google up. Well done~

</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/206#discussion_r1095330447" expanded>

Perhaps u could use **Index** instead of **Idx**
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/206#pullrequestreview-1282245600" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/214#discussion_r1095358714" expanded>

Yeah, you can refer to this link [https://se-education.org/guides/conventions/java/basic.html] for **if-else** statement coding standards.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/214#discussion_r1095361963" expanded>

You'd want to indent the { } properly, like:
public static void echo(){

// your code
 }
       
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/214#discussion_r1095362968" expanded>

I like how you have added another variable called **taskLabel**.

This is actually clear while storing the data in it instead of explicitly typing [D] / [E] / [T] every time while printing the lists.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/214#pullrequestreview-1282288943" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 55. LEO ..RREN `@dsicol` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/50#discussion_r1094634040" expanded>

Looks good, try to SLAP these into a method as well
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/50#discussion_r1094636753" expanded>

Good use of SLAP
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/50#discussion_r1094637727" expanded>

Better to use case statements for clarity!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/50#discussion_r1094639119" expanded>

Great formatting with indentations!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/50#discussion_r1094640413" expanded>

Great abstraction of methods
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/50#pullrequestreview-1281214337" expanded>

**Review Status:** COMMENTED

Overall SLAP is used wonderfully, remember to refine the other parts to maintain the SLAP!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/192#discussion_r1094141739" expanded>

When wrapping texts, remember to indent 8 spaces (or 2 tabs) from former line
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/192#discussion_r1094143224" expanded>

Good job on formatting your case statements!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/192#discussion_r1094144013" expanded>

Remember to remove extra new lines in your code!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/192#discussion_r1094146297" expanded>

Good use on plurals to define your class!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/192#discussion_r1094147696" expanded>

Good job on wrapping the texts!
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/192#pullrequestreview-1280476633" expanded>

**Review Status:** COMMENTED

Good job overall on your coding standards. Remember to wrap all texts with an indent of 8 spaces.
</panel>

</panel>

<panel type="info" header="### 56. DYLA.. JIE `@ChubbsBunns` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#discussion_r1092796739" expanded>

I think this comment might be wrong (or duplicated)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#discussion_r1092796915" expanded>

Unsure of the use of this empty function
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#discussion_r1092798566" expanded>

Great work with refactoring out multiple functions that is able to add tasks!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#discussion_r1092798716" expanded>

Amazing simple and clear switch case usage!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#discussion_r1092798803" expanded>

Great use of static final variables!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#pullrequestreview-1278476662" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#discussion_r1092792220" expanded>

The task class could also include the "done" and the "type" as well, ensuring better OOP practices as currently that information is segregated.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#discussion_r1092792299" expanded>

The integer i is also not very clearly labelled, hence someone reading the code for the first time might not know what it is.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#discussion_r1092792358" expanded>

Switch cases could also be used over if else statements for more accessible code.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#discussion_r1092793168" expanded>

You could choose to build an output class that helps print out text, allowing you to print out lists with a single function, without using so many lines of text
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#discussion_r1092794777" expanded>

Good relevant import of class
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/163#pullrequestreview-1278470182" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 57. SHAN.. TAN `@shannentan` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/5#discussion_r1094369966" expanded>

Should this bracket be moved to the previous line to follow the K&R style brackets?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/5#discussion_r1094418410" expanded>

Maybe the number of empty lines between lines should be more consistent?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/5#discussion_r1094422226" expanded>

Is it possible to avoid deep nesting here? The code seems to be of arrowhead style.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/5#discussion_r1094427567" expanded>

Maybe this variable can be named as canSkip to make it more obvious.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/5#discussion_r1094428310" expanded>

Would combining this into one print statement improve readability?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/5#pullrequestreview-1280819621" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/51#discussion_r1094171312" expanded>

Should the method getDealineDetails be spelt as getDeadlineDetails instead? (line 72 and line 99)
```suggestion
                getDeadlineDetails(line);
```
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/51#discussion_r1094199344" expanded>

I like the use of the close() method here to close the stream
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/51#discussion_r1094202351" expanded>

Should upTaskCount() be moved into addTask()? (Increment taskCount in addTask)
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/51#discussion_r1094337481" expanded>

Good that you remembered not to indent the switch cases.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/51#discussion_r1094362023" expanded>

What's the difference between having taskList in Task, as compared to having it in Duke?
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/51#pullrequestreview-1280520306" expanded>

**Review Status:** COMMENTED

Good attempt at closely following the coding standards
</panel>

</panel>

<panel type="info" header="### 58. HOO ..JUAN `@TJ-Hoo` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/31#discussion_r1092872217" expanded>

Switch case very easy to read 10/10 code quality
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/31#discussion_r1092876419" expanded>

Comments and short methods make code very easy to read and understand
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/31#discussion_r1092877199" expanded>

Good job avoiding complicated expressions
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/31#discussion_r1092877632" expanded>

Good job avoiding the usage of magic numbers
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/31#discussion_r1092878146" expanded>

Code is overall structured well and logically so is very easy to follow
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/31#pullrequestreview-1278588644" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/95#discussion_r1092861377" expanded>

Code nesting is neat and tidy.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/95#discussion_r1092863848" expanded>

Good use of commenting to explain functionality
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/95#discussion_r1092864788" expanded>

Correct usage of try catch statement!!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/95#discussion_r1092865405" expanded>

Correct naming of boolean!!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/95#discussion_r1092866248" expanded>

Correct naming convention using camelCase
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/95#pullrequestreview-1278573068" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 59. THOM..ALBA `@thomasjlalba` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/80#discussion_r1094012950" expanded>

Would be good if there is spacing among the variables and operators, noticed the same thing for the other places too
```suggestion
        if (input.length() >= 4) {
```
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/80#discussion_r1094016356" expanded>

This particular indentation seems to only be 3 spaces instead of the typical 4 spaces
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/80#discussion_r1094020126" expanded>

Would be nice if there is a space between the bracket and if as such:
```suggestion
            if ("mark".equalsIgnoreCase(input.substring(0,4))) {
```
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/80#discussion_r1094024246" expanded>

Would be nice to expand on the method's details using
```
/**
 * comment
 */
```
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/80#discussion_r1094077180" expanded>

Perhaps you could remove this empty line
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/80#pullrequestreview-1280332766" expanded>

**Review Status:** COMMENTED

Overall the code is well written to the coding standards guidelines! 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/98#discussion_r1094085688" expanded>

Perhaps it would be more readable by adding 2 additional variables to make the keyword and content clearer:

```
String keyword = seperatedKeywordAndContent[0];
String content = seperatedKeywordAndContent[1];
```
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/98#discussion_r1094088522" expanded>

Maybe the magic strings "from " and "to " can be refactored into constants
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/98#discussion_r1094093701" expanded>

Perhaps all caps since it is a constant? "HORIZONTAL_LINE"
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/98#discussion_r1094097292" expanded>

Perhaps consider changing the method's name given it returns a boolean
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/98#discussion_r1094099953" expanded>

Perhaps it could be more readable if "[" and "]" is returned alongside item.getClassSymbol()? such that for Task.java the method could be as such

```
public String getMarkingStatus() {
        return isMarked ? "[X]" : "[ ]";
    }
```
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/98#pullrequestreview-1280401603" expanded>

**Review Status:** COMMENTED

Overall the code quality is done well! I especially like the implementation of constants for the messages!
</panel>

</panel>

<panel type="info" header="### 60. HUNG..MENT `@hyperbola-bear` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/53#discussion_r1094496347" expanded>

would be good to include an else case for invalid inputs
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/53#discussion_r1094508937" expanded>

repeated code to assign input to readInput, maybe can consider a method to reduce this duplication?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/53#discussion_r1094519854" expanded>

might to good to avoid the use of magic number 100, instead define it at the top of file, eg MAX_NUM_OF_TASKS = 100 or something
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/53#discussion_r1094527849" expanded>

Nice SLAP, by abstracting each command into their individual function, it keeps the code clean and readable.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/53#discussion_r1094530746" expanded>

can consider more descriptive names instead of just start and end, maybe startOfEvent  
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/53#pullrequestreview-1281008552" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/138#discussion_r1094014375" expanded>

i think that you can import the ArrayList only in the files that is directly using the ArrayList
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/138#discussion_r1094014462" expanded>

maybe can use setAsDone instead, allow your audience to see that it is a setter.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/138#discussion_r1094020987" expanded>

unnecessary spacing and indentation makes the code slightly harder to read
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/138#discussion_r1094023061" expanded>

good job on avoiding the line limit of 120 by separating this long print statement 
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/138#discussion_r1094023903" expanded>

good to put traditional for loop for better readability
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/138#pullrequestreview-1280333810" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 61. LI M..YUAN `@mingyuannus` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/10#discussion_r1094152811" expanded>

Good job extracting fixed strings into their own constants. Improves readability.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/10#discussion_r1094156554" expanded>

Could be confusing for numItems to be incremented and item to be assigned in the same line. Would be better if broken into 2 separate lines, one for each action.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/10#discussion_r1094159653" expanded>

Multiple for loops using the same i could be confusing.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/10#discussion_r1094160220" expanded>

Good job keeping the main method short by creating additional methods.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/10#discussion_r1094162213" expanded>

This if statement is nested quite deep.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/10#pullrequestreview-1280493341" expanded>

**Review Status:** COMMENTED

PR reviews for coding quality.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/168#discussion_r1094140933" expanded>

It would be better for method name to use a verb.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/168#discussion_r1094142877" expanded>

It would be good if this method name is also a verb.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/168#discussion_r1094146456" expanded>

Constant should be all upper case.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/168#discussion_r1094148018" expanded>

Multiline string hould have same indentation level as the first line.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/168#discussion_r1094149975" expanded>

Good job following the correct layout for while loop.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/168#pullrequestreview-1280475497" expanded>

**Review Status:** COMMENTED

PR reviews for coding standards.
</panel>

</panel>

<panel type="info" header="### 62. YONG..LING `@ysl-28` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/36#discussion_r1092756486" expanded>

Good naming style for constant names.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/36#discussion_r1092757652" expanded>

Good use of plural form to name a collection of objects.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/36#discussion_r1092759100" expanded>

Correct form for if-else statement.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/36#discussion_r1092760349" expanded>

Correct form for writing switch statement.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/36#discussion_r1092760688" expanded>

Correct use of PascalCase to name classes.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/36#pullrequestreview-1278419800" expanded>

**Review Status:** COMMENTED

Overall, the code follows coding standards and makes good use of constants.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/203#discussion_r1092775362" expanded>

Would it be clearer to use a constant instead of a magic number?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/203#discussion_r1092888035" expanded>

Perhaps it would be more readable to remove chunks of commented code?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/203#discussion_r1092895146" expanded>

Perhaps it would be clearer to follow the Java coding standard for writing if-else statements?
```java
if (condition) {
    statements;
} else if (condition) {
    statements;
} else {
    statements;
}
```
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/203#discussion_r1092897595" expanded>

I like the use of comments to explain the code when needed.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/203#discussion_r1092909205" expanded>

I like that the variable names are clear and follow the coding standard.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/203#pullrequestreview-1278446508" expanded>

**Review Status:** COMMENTED

Overall, the code is generally readable. However, the use of magic numbers could be reduced.
</panel>

</panel>

<panel type="info" header="### 63. SEET.. WEN `@SSzeWen` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/89#discussion_r1094420200" expanded>

Should the else statement in line 226 be on line 225 instead?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/89#discussion_r1094431092" expanded>

Perhaps there could be a better naming here for addTask to sound like a boolean function
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/89#discussion_r1094433264" expanded>

This switch statement looks really clean and follows the Java Coding Standard well with no indentation for case clauses
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/89#discussion_r1094439620" expanded>

Informative Comments that follows JavaDoc format
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/89#discussion_r1094442344" expanded>

I am not sure if there is a need to add a break statement here, or write //Fallthrough, since its the last statement
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/89#pullrequestreview-1280893668" expanded>

**Review Status:** COMMENTED

Overall, the code is very neat and understandable that follows Java coding standards with little changes required. Comments are very nice and all the different classes are named well
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/164#discussion_r1094463685" expanded>

Perhaps this code could be refactored out to be used in Event too
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/164#discussion_r1094464716" expanded>

Good use of Polymorphism here
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/164#discussion_r1094480477" expanded>

Method could be too long, exceeding 30 lines of code, it might be better to shorten it or refactor out certain portions to other methods.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/164#discussion_r1094484016" expanded>

I agree that renaming array to tasks would be more clear as inputs could also mean other commands like list. Perhaps, you could refactor out the 100 as a constant like MAX_TASKS to improve readability
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/164#discussion_r1094485938" expanded>

eventHandler Method is also pretty long as it exceeds 30 lines of code. Shortening it and reusing code from before might be better
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/164#pullrequestreview-1280957687" expanded>

**Review Status:** COMMENTED

Overall, Polymorphism is done well, and the subtasks are used well in conjunction to the main Task. There is also simple nesting throughout the functions, which makes code easy to understand. Minor changes could still be made so shorten the methods and refactor out some functions.
</panel>

</panel>

<panel type="info" header="### 64. ZHAO..IUQI `@alexgoexercise` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/113#discussion_r1094148655" expanded>

Maybe can try to use switch here?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/113#discussion_r1094151335" expanded>

Nice use of this boolean method
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/113#discussion_r1094152282" expanded>

Cool way of doing it, I didn't think of this haha
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/113#discussion_r1094155343" expanded>

This can be a boolean function instead?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/113#discussion_r1094156664" expanded>

This will include all the other possibilities other than "unmark"
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/113#pullrequestreview-1280486811" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/136#discussion_r1094138973" expanded>

Nice use of static final(I can't really find anything wrong with your coding standards, salute)
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/136#discussion_r1094142096" expanded>

Nice one separating the lines
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/136#discussion_r1094143427" expanded>

However, this name sounds a bit weird to me, maybe can just change to 'LINE' or something?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/136#discussion_r1094145517" expanded>

Your if-else lines look neat
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/136#discussion_r1094146347" expanded>

Maybe can be 'addToList?'
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/136#pullrequestreview-1280472556" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 65. OW Y..XUAN `@jinxuan-owyong` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#discussion_r1092859942" expanded>

Code is well formatted and readable without deep nesting.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#discussion_r1092861617" expanded>

Good abstraction of functions, makes the code cleaner and easier to understand especially in the switch case statement!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#discussion_r1092862078" expanded>

Formatting of code follows recommended convention, good job.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#discussion_r1092865866" expanded>

Perhaps you should use the name to explain the function.
```suggestion
    private static void printListMessage() {
```

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#pullrequestreview-1278570965" expanded>

**Review Status:** COMMENTED

Well done. The code is of high quality with minor corrections required.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/196#discussion_r1092816670" expanded>

Perhaps line length should be no longer than 120 chars.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/196#discussion_r1092819583" expanded>

Perhaps the switch statement should have the following form: Note there is no indentation for case clauses.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/196#discussion_r1092821420" expanded>

Perhaps the try-catch statement should follow the recommended format (missing space)
```java
try {
    statements;
} catch (Exception exception) {
    statements;
}
```
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/196#discussion_r1092822469" expanded>

Perhaps constant names must be all uppercase using underscore to separate words.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/196#discussion_r1092823048" expanded>

Perhaps you should use K&R style brackets (aka [Egyptian style](https://blog.codinghorror.com/new-programming-jargon/)).
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/196#discussion_r1092823248" expanded>

Perhaps constant names must be all uppercase using underscore to separate words.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/196#pullrequestreview-1278508450" expanded>

**Review Status:** COMMENTED

Great job on enhancing the visuals for the chatbot. However, I noticed repeated deviations from the [recommended coding standard](https://se-education.org/guides/conventions/java/basic.html), and inconsistent spacing in various lines. Consider using the keyboard shortcuts below to format your code in IntelliJ IDEA
> For Windows : Ctrl + Alt + L.
> For Ubuntu : Ctrl + Alt + Windows + L.
> For Mac : ⌥ (Option) + ⌘ (Command) + L.
</panel>

</panel>

<panel type="info" header="### 66. WANG..LANG `@JangusRoundstone` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/57#discussion_r1095308356" expanded>

This is an efficient way to output the string, good job!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/57#discussion_r1095309434" expanded>

Perhaps this variable could be initialised closer to the main function, so that the readers can better follow your code. This makes the happy path more prominent.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/57#discussion_r1095309960" expanded>

Great job writing the separator() function, could be really useful later on in iP!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/57#discussion_r1095310627" expanded>

Good job using the equalsIgnoreCase() function!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/57#discussion_r1095317202" expanded>

Is it better to keep checking for message.length() > 1, or in this case it is better to check for "bye" or "list" at the beginning? I am unsure also, feel free to discuss:)
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/57#pullrequestreview-1282217396" expanded>

**Review Status:** COMMENTED

LGTM, with one question that is debatable. Good job overall!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/101#discussion_r1095322009" expanded>

I do not think you need to check for "umarked" if you have already checked for "marked". However, the efforts are appreciated:)
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/101#discussion_r1095323545" expanded>

Really clever way to get rid of todo! 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/101#discussion_r1095325709" expanded>

Agreed. It is more intuitive to move taskCount++ to addTask()
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/101#discussion_r1095326582" expanded>

If I am not mistaken, print(tasks[taskCount]) by default calls the toString() method of the Task object instantiation, hence no need to explicitly state the .toString() part.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/101#discussion_r1095326865" expanded>

I think based on current implement, it is find. Todo, event, and deadline are more like indicator anyway.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/101#pullrequestreview-1282236806" expanded>

**Review Status:** COMMENTED

LGTM. Some nits here and there, but overall good:) Good job!
</panel>

</panel>

<panel type="info" header="### 67. STEV..KITO `@stevenantya` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/114#discussion_r1094166185" expanded>

Coding Quality : Avoid very long if statements or you can enter it to a new line
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/114#discussion_r1094168663" expanded>

Coding Quality: Avoid complicated expressions create boolean for it

e.g. 
`isValidNumber = number &gt;= 0 || number > 100`
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/114#discussion_r1094171789" expanded>

Coding Quality: can put the return in one variable first.
```suggestion
isValidString = input.contains("mark") && words.length == 2 && isInt(words[1]);
return isValidString;
```
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/114#discussion_r1094172199" expanded>

The same goes for line 44, 48, 53, 57
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/114#pullrequestreview-1280512208" expanded>

**Review Status:** COMMENTED

Overall, good coding quality! Good job!

Remember to create boolean variables if your conditional statement is too long. This increases your readibility 👍 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/198#discussion_r1094147208" expanded>

remove the unnecessary blank spaces, follow one uniform spacing
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/198#discussion_r1094147741" expanded>

Coding Standard violation: Ambiguity of function.

Can change the name of the function to explain more. e.g. addTodo()
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/198#discussion_r1094150180" expanded>

Coding Standard Violation: Plural form is reserved for collections of objects.
```suggestion
String output
```
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/198#discussion_r1094154788" expanded>

Coding Standard Violation: Array should be plural

```suggestion
String[] storeLists;
```
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/198#discussion_r1094157695" expanded>

Coding Standard Violation: Give space before and after statement
'''suggestion
} else if(outputs.equals("list")) {
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/198#discussion_r1094158016" expanded>

same goes for line 30, 35
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/198#pullrequestreview-1280484620" expanded>

**Review Status:** COMMENTED

Overall good job on the pull request! Only few minor consistency and coding standards issues.
</panel>

</panel>

<panel type="info" header="### 68. VARN..TAVA `@varnika1402` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/14#discussion_r1092789068" expanded>

good use of camel case for methods and variables
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/14#discussion_r1092896918" expanded>

Method name is clear and is also in camelCase
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/14#discussion_r1092898632" expanded>

Can avoid .* when importing
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/14#discussion_r1092904760" expanded>

switch statement should have no indentation for case clauses 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/14#discussion_r1092906495" expanded>

Boolean variable sounds like boolean
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/14#pullrequestreview-1278465697" expanded>

**Review Status:** COMMENTED

Overall, the code is clean and easy to understand. You may consider correcting the indentation as per the coding standards.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/132#discussion_r1092879443" expanded>

Method name is both clear and in camelCase. 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/132#discussion_r1092880867" expanded>

Boolean variable name is clear as it sounds like boolean
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/132#discussion_r1092881981" expanded>

good indentation
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/132#discussion_r1092882886" expanded>

method name can be a verb for ex- getCommands()
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/132#discussion_r1092884162" expanded>

Boolean variable does not have the prefix - is,was,has etc.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/132#pullrequestreview-1278599405" expanded>

**Review Status:** COMMENTED

Coding standards are followed well. Good indentation. Method names and variable names can be improved as suggested. Good use of camelCase and pascalCase.
</panel>

</panel>

<panel type="info" header="### 69. ZHAN..ENZE `@kyrixn` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/103#discussion_r1095391500" expanded>

I also suppose that it's better to use break instead of directly return
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/103#discussion_r1095393148" expanded>

this line seems too long, maybe you can saperate it in to two lines.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/103#discussion_r1095394776" expanded>

Yes, you need to put extra Tabs here
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/103#discussion_r1095395891" expanded>

nice you already finished your ip haha
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/103#discussion_r1095398018" expanded>

I suppose here it's better to improve your spacing for good readability.
```suggestion
        if (to == -1 || arguments.charAt(to-1) != ' ' || arguments.charAt(to + 3) != ' ') {
            throw new InvalidCommandException("Command at /to is invalid", new IllegalArgumentException());
        }

```
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/103#pullrequestreview-1282335985" expanded>

**Review Status:** COMMENTED

nice job!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/176#discussion_r1095377723" expanded>

I suppose It's better to make this part as a function and call it in the main function.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/176#discussion_r1095379562" expanded>

instead of multiple "if else" statement, it's better to use a single switch structure to make the code tidier and more readable.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/176#discussion_r1095380895" expanded>

I suppose it not necessary to add a new line between the function definition and the statement
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/176#discussion_r1095383060" expanded>

use this.isDone instead to make the code feels like more consistent?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/176#discussion_r1095388151" expanded>

maybe can revise your spacing here
change to
```suggestion
                    todoList.get(i - 1).getDescription());
```
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/176#pullrequestreview-1282315495" expanded>

**Review Status:** COMMENTED

overall it's Good! keep it up!
</panel>

</panel>

<panel type="info" header="### 70. NGUY..HANG `@Mnsd05` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/123#discussion_r1094156696" expanded>

Maybe you can refactor this kind of message to be a constant variable
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/123#discussion_r1094158124" expanded>

Maybe you  can consider extract some methods to make the code more structurally logical
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/123#discussion_r1094159144" expanded>

should you avoid complicated  expressions?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/123#discussion_r1094159697" expanded>

Maybe you can use a variable to store this complicated expression
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/123#discussion_r1094160714" expanded>

This 6 lines of code can be extracted to a method.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/123#pullrequestreview-1280497849" expanded>

**Review Status:** COMMENTED

Overall, I think you can try to refactor to make the code more readable, and structurally logical.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/182#discussion_r1094144848" expanded>

Should you name the variable in all capital letters?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/182#discussion_r1094147341" expanded>

Is it better to remove this line?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/182#discussion_r1094148620" expanded>

Well done! you name the constant variables correctly
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/182#discussion_r1094150162" expanded>

Well done! You name the method in camelCase.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/182#discussion_r1094153463" expanded>

Well done! You follow strictly the indentation rule.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/182#pullrequestreview-1280396115" expanded>

**Review Status:** COMMENTED

Overall, your code is easy to read and you follow the coding standards very well.  The best thing I found in this code is that you acknowledge the authors of the code which you reuse and refer to.
Well done! 
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/182#pullrequestreview-1280481093" expanded>

**Review Status:** COMMENTED

Well done! I just find a minor mistake and I think you name the variables very well and follow strictly the coding standards.
</panel>

</panel>

<panel type="info" header="### 71. JIRA..RIAN `@superkaiba` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/34#discussion_r1094006765" expanded>

I like how you named your constants in all capital letters with underscores as spaces
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/34#discussion_r1094007494" expanded>

I like how you used camel case for all your method names
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/34#discussion_r1094010754" expanded>

Perhaps you could add some comments to clarify how your code works?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/34#discussion_r1094011732" expanded>

I like how you followed the coding standards for this if/else if statement.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/34#discussion_r1094012051" expanded>

Perhaps this if/else if statement could be replaced by a switch/case statement?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/34#pullrequestreview-1280328072" expanded>

**Review Status:** COMMENTED

Really great! 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/131#discussion_r1094016905" expanded>

It might be better to use a switch/case statement here instead of if/else if
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/131#discussion_r1094017778" expanded>

Perhaps you should rename this to something like "dueDateIndicator" to match with the other variable names and make it clearer what this variable is for
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/131#discussion_r1094019253" expanded>

Perhaps you could separate your functionality into multiple submethods to make the code more readable and modular?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/131#discussion_r1094020585" expanded>

Perhaps you should add some comments throughout your code to explain how it works?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/131#discussion_r1094022129" expanded>

Perhaps you should rename this to isDone instead of done?
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/131#pullrequestreview-1280335803" expanded>

**Review Status:** COMMENTED

Great job! Only some minor things I had comments on.
</panel>

</panel>

<panel type="info" header="### 72. RIZA..ZIZI `@nafisazizir` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/148#discussion_r1094454232" expanded>

Perhaps, you can merge these two methods into one, because there are several repetitive codes
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/148#discussion_r1094456890" expanded>

You could use plural for naming collections
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/148#discussion_r1094458904" expanded>

These two also could be merged into one method
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/148#discussion_r1094461190" expanded>

I like the way you wrap the welcome message and help message into different method
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/148#discussion_r1094467663" expanded>

I think it would be better if you explicitly write the else statement to better readability
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/148#pullrequestreview-1280942914" expanded>

**Review Status:** COMMENTED

Overall, you did a great effort and your code is neat & clean
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/166#discussion_r1094009099" expanded>

Great job, you add space between the operations
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/166#discussion_r1094011974" expanded>

Nice work, you change the constant into uppercase
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/166#discussion_r1094013484" expanded>

Great catch, you add a space between while and the ()
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/166#discussion_r1094016491" expanded>

Maybe, you can use /* */ to do multi lines comments
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/166#discussion_r1094017889" expanded>

Great effort, you import explicitly the package
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/166#pullrequestreview-1280329839" expanded>

**Review Status:** COMMENTED

Keep the good effort!
</panel>

</panel>

<panel type="info" header="### 73. XU J..CHEN `@aaronxujiachen` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/54#discussion_r1093932041" expanded>

I like how you name the variable "scan".
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/54#discussion_r1093932735" expanded>

Well done for the nested while loop.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/54#discussion_r1093932946" expanded>

Good method
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/54#discussion_r1093933228" expanded>

I would prefer to define HORIZONTAL_LINE.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/54#discussion_r1093933626" expanded>

Good job using the conditional operator.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/54#pullrequestreview-1280159227" expanded>

**Review Status:** COMMENTED

Overall, good effort!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#discussion_r1093924081" expanded>

I like how you name the variable "firstWord".
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#discussion_r1093924884" expanded>

I guess there is a missing "}"?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#discussion_r1093925870" expanded>

Good way to define "HORIZONTAL_LINE".
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#discussion_r1093927086" expanded>

Maybe there is a better way to name the Scanner variable? Personally I would prefer "scan" over "sc".
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#discussion_r1093927805" expanded>

Well done for using this conditional operator!
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#pullrequestreview-1280148634" expanded>

**Review Status:** COMMENTED

Overall, I find it quite easy to read your codes. Good effort for following the coding standards and quality. Perhaps next time can add more comments at the side?
</panel>

</panel>

<panel type="info" header="### 74. TAN .. WEI `@TJW0911` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/21#discussion_r1093923226" expanded>

I like how you randomize the farewell greeting for a fresh experience 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/21#discussion_r1093923653" expanded>

Perhaps you can remove this comment if you are not using it 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/21#discussion_r1093924559" expanded>

Perhaps specify what kind of list in the variable name
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/21#discussion_r1093926213" expanded>

Perhaps a different variable name might be better as you are reading in one whole line and not a single word
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/21#discussion_r1093927071" expanded>

good job following the coding standard for switch cases mentioned in lecture
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/21#pullrequestreview-1280147404" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/211#discussion_r1093928853" expanded>

Perhaps you could remove this comment
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/211#discussion_r1093930446" expanded>

perhaps remove this comment if you are no longer using it
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/211#discussion_r1093931203" expanded>

Perhaps you could spell out "position" or change it to "Index"
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/211#discussion_r1093933957" expanded>

I think this print statement is a bit lengthy. Perhaps you could use the ToString override method in your classes to shorten it
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/211#discussion_r1093935536" expanded>

Good job combining the welcome statement into one string
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/211#pullrequestreview-1280154997" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 75. GERA..GUAN `@geraldkoh4` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/45#discussion_r1093928125" expanded>

2. Perhaps this array can be in plural like the array inputs?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/45#discussion_r1093929227" expanded>

3. I like the coding standard for the if-else statements! It looks very clean.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/45#discussion_r1093931274" expanded>

4. Perhaps a space should be used between the names and the inputs. E.g 
Deadline (String description, String by) {
    ...
}
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/45#discussion_r1093932275" expanded>

1. Generally Coding quality is well followed, Good Job!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/45#discussion_r1093932719" expanded>

5. I like how the print strings are separated, looks clean!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/45#pullrequestreview-1280152464" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/110#discussion_r1093935777" expanded>

1. Maybe the long print statements can be put into another class to look neater?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/110#discussion_r1093936300" expanded>

2. I like the way this is presented. The switch - case helps a lot with readability!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/110#discussion_r1093937239" expanded>

3. Overall the code does not have deep nesting, good job!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/110#discussion_r1093938580" expanded>

4. Short method names help with readability. Looks neat
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/110#discussion_r1093944690" expanded>

5. Perhaps you could use a for loop to make it simpler? 
E.g for (int num = 1; num &gt;= timer; num++) {
    //...
}
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/110#pullrequestreview-1280164628" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 76. CHEN..NZEL `@denzelcjy` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/151#discussion_r1093947738" expanded>

Maybe consider just typing out the string if it is 1 character instead of abstracting it into constants 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/151#discussion_r1093948797" expanded>

Similar to the earlier `Task.java` file, you can consider not abstracting out the open brackets and "T" into constants
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/151#discussion_r1093950144" expanded>

Similar to the other ones, you can consider writing out the actual string instead, as using these large amount of constants can affect the readability of the code
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/151#discussion_r1093951882" expanded>

I like how you followed the coding standards to name your methods and variables in camelCase!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/151#discussion_r1093953232" expanded>

You can consider reducing the number of defined constants to improve readability, and you can consider writing `DESC` as `DESCRIPTION` instead to make it clearer, it is good that your constant names must be all uppercase using underscore to separate words.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/151#pullrequestreview-1280180614" expanded>

**Review Status:** COMMENTED

Your code logic is great, however I feel that you can consider reducing the number of constants (especially the single character ones like "T" , "." or "(" )  to improve readability of your code. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/187#discussion_r1093927449" expanded>

You can consider changing the constructor to be named as `isMarked` instead of using an underscore to make it more boolean like
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/187#discussion_r1093928037" expanded>

Maybe you can change the boolean variable to isMarked to sound like booleans
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/187#discussion_r1093929724" expanded>

Maybe you can make sure that the `else` statement follows the same format as your `else if` statement above
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/187#discussion_r1093932194" expanded>

Consider having a space after your `while` declaration before your opening round bracket to follow the coding standard format
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/187#discussion_r1093933038" expanded>

You can consider a space after your `if` declaration in line 24, just like how you did in line 19 of your code to follow the coding standard format👍 
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/187#pullrequestreview-1280152815" expanded>

**Review Status:** COMMENTED

Your code looks great, except for a few namings of boolean variables/constructors that you can consider to change and some minor tweaks to your formatting of `while` and `if` declarations to fit the coding standard
</panel>

</panel>

<panel type="info" header="### 77. NG Y..I DA `@ngyida` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/113#discussion_r1093932434" expanded>

Neat code that uses SLAP and simple nesting.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/113#discussion_r1093933245" expanded>

The naming of this variable may be confusing.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/113#discussion_r1093934385" expanded>

Perhaps this method should not override the Object class method toString() since it does not necessarily print the Event object out. An alternative would be to use another method name that indicates a summary of the event.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/113#discussion_r1093934738" expanded>

Clean code with good use of polymorphism.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/113#pullrequestreview-1280159772" expanded>

**Review Status:** COMMENTED

Clean code with very minor amendments to improve readability. 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/191#discussion_r1093925459" expanded>

This method name might be confusing as incomplete is not a verb.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/191#discussion_r1093926074" expanded>

This method name might be confusing as it does not sound like a boolean e.g. isTaskCompleted
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/191#discussion_r1093927603" expanded>

The heavy nesting here can be hard for others to understand the code logic. Apart from reducing the nesting level, perhaps this can be improved using better method naming for the Task class and also replacing the magic number "-1" with a constant variable name.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/191#discussion_r1093929147" expanded>

This is a very neat code that uses SLAP.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/191#discussion_r1093929868" expanded>

The naming for this method may be confusing as it is not a verb.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/191#discussion_r1093930168" expanded>

The naming for this method may be confusing as it does not sound like a boolean.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/191#pullrequestreview-1280150394" expanded>

**Review Status:** COMMENTED

Mostly clean code that is easy to follow. Minor amendments to naming and cosmetics requested.
</panel>

</panel>

<panel type="info" header="### 78. LIN ..G YA `@jingyaaa` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/170#discussion_r1093932226" expanded>

perhaps can consider another way to do this to avoid deep nesting?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/170#discussion_r1093932749" expanded>

avoided the use of magic numbers, good job
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/170#discussion_r1093939279" expanded>

generally good and readable naming observed, well done

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/170#discussion_r1093940084" expanded>

Distinguishes between single and multi-valued variables :)
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/170#discussion_r1093940665" expanded>

non-empty catch block :)
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/170#pullrequestreview-1280159468" expanded>

**Review Status:** COMMENTED

generally well-readable, good job!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/184#discussion_r1093922833" expanded>

boolean variable named properly, good job
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/184#discussion_r1093925453" expanded>

constant names are in the correct format :)
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/184#discussion_r1093925957" expanded>

can perhaps consider "else if" statements?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/184#discussion_r1093927055" expanded>

all variables and functions are properly named :)
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/184#discussion_r1093927746" expanded>

Imported classes are listed explicitly, good job
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/184#pullrequestreview-1280146858" expanded>

**Review Status:** COMMENTED

Generally no issues with coding standard, well done
</panel>

</panel>

<panel type="info" header="### 79. ONG ..YUAN `@yuanners` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/75#discussion_r1093923516" expanded>

Method name might be confusing, can change to "isInputInteger"
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/75#discussion_r1093925553" expanded>

This looks like a C implementation (by prof)
I think can use string.split to format inputs instead.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/75#discussion_r1093925905" expanded>

Readability issue - if it is default condition, shouldn't call another function
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/75#discussion_r1093926675" expanded>

Readability: I think you should keep the function name shorter (maybe less than 20 characters)
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/75#discussion_r1093926836" expanded>

Same issue with the C implementation
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/75#discussion_r1093927546" expanded>

Good way of extracting the functions from the main function and it looks neat.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/75#pullrequestreview-1280147810" expanded>

**Review Status:** COMMENTED

Code is very clean, can't find any spacing/naming convention issues. 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/79#discussion_r1093930853" expanded>

Good attempt to add another class for user interface, better readability and neater
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/79#discussion_r1093932703" expanded>

Good abstraction - allow overriding of toString function for subclasses.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/79#discussion_r1093933455" expanded>

If the variable is final then the name should be in all caps
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/79#discussion_r1093938199" expanded>

Should use a boolean variable for better readability
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/79#pullrequestreview-1280157649" expanded>

**Review Status:** COMMENTED

Good abstraction , there is no long functions and deeply nested conditions. Easy to read and understand. 
</panel>

</panel>

<panel type="info" header="### 80. BENJ..MING `@Bawfen` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/10#discussion_r1094056069" expanded>

Perhaps this constant should be capitalised i.e. TYPE_REPRESENTATION. This applies to the typeRepresentation in 
the other classes too.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/10#discussion_r1094058804" expanded>

Should this function have the `@Override` annotation?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/10#discussion_r1094061987" expanded>

Good job following the indentation standards!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/10#discussion_r1094063227" expanded>

Good use of Egyptian style brackets
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/10#pullrequestreview-1280369821" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/30#discussion_r1094067119" expanded>

Perhaps you could change this magic literal `101` to a constant.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/30#discussion_r1094068164" expanded>

Might be good to add a `default` case to your switch statement to handle unexpected inputs.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/30#discussion_r1094068510" expanded>

I like that you keep your functions short and easy to understand
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/30#discussion_r1094071889" expanded>

Could consider changing the name of the function to `printTaskStatus` instead since it prints directly? The word `get` implies that it would be returning something.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/30#discussion_r1094076069" expanded>

Perhaps you could add some default behaviour to the function in this base class?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/30#pullrequestreview-1280379575" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 81. MUTH..KHIL `@lihka1202` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/69#discussion_r1095311819" expanded>

I like how you have ensured that SLAP is ensured in the main function
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/69#discussion_r1095313964" expanded>

Perhaps you could remove the flag variables and create two new methods instead.
You could refer to this link for more: https://refactoring.com/catalog/removeFlagArgument.html
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/69#discussion_r1095314814" expanded>

You could abstract this out into a function and also avoid using negative logic.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/69#discussion_r1095315880" expanded>

You could shorten this comversion by splitting based off multiple delimiters.
You can find more info here: https://stackoverflow.com/questions/5993779/use-string-split-with-multiple-delimiters
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/69#pullrequestreview-1282222348" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/206#discussion_r1095306162" expanded>

Perhaps you can leave a space after the conditional clause and opening brace
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/206#discussion_r1095306863" expanded>

I like how you have added error handling
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/206#discussion_r1095308821" expanded>

perhaps you could give this variable a better name, as it is stored as a `String` but is named `func`
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/206#discussion_r1095309514" expanded>

Perhaps you could name object `todo` better, as it has the same name as the class and it might get confusing!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/206#discussion_r1095310297" expanded>

Could you abstract this out to maintain SLAP
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/206#pullrequestreview-1282214416" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 82. SIUT..MENT `@clement559` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/65#discussion_r1093980480" expanded>

Good naming conventions, follows camelCase format for variable names.
Lines are short and have good readability.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/65#discussion_r1093981543" expanded>

Good practice importing the specific packages required
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/65#discussion_r1094142497" expanded>

All functions and loops are wrapped in curly brackets and on the next line. Well done!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/65#discussion_r1094555109" expanded>

Method name may seem a little misleading. markUnmarked may seem like a verb referring to marking the unmarked tasks only.
```suggestion
toggleMarkCommand
```
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/65#pullrequestreview-1280243054" expanded>

**Review Status:** COMMENTED

Overall, the code follows the coding standard very well. Well done!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/80#discussion_r1093983694" expanded>

Class name is slightly ambiguous.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/80#discussion_r1093984855" expanded>

Input lengths appear to be magic numbers. Would be better to explain the different numbers used.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/80#discussion_r1093985247" expanded>

Line is obvious, comment can be omitted.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/80#discussion_r1093985462" expanded>

Extra newline can be omitted.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/80#discussion_r1093986296" expanded>

Main method is too long, can consider breaking up the different parts of the program into different methods.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/80#pullrequestreview-1280256946" expanded>

**Review Status:** COMMENTED

Overall, code is fine, but lengthy methods at certain points. Splitting up the main code into segments will help improve readability!
</panel>

</panel>

<panel type="info" header="### 83. EUGE..HING `@EangJS` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/48#discussion_r1092789356" expanded>

Method naming follows java coding standard of camelCase
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/48#discussion_r1092789810" expanded>

Constant variables are all in capital letters which adheres to the Java Coding standard
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/48#discussion_r1092790597" expanded>

boolean variables have isX which sounds like booleans
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/48#discussion_r1092791206" expanded>

descOfTask is unclear. Maybe use descriptionOfTask instead?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/48#discussion_r1092793479" expanded>

Correct indentation of comments and follows javadoc requirements
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/48#pullrequestreview-1278466096" expanded>

**Review Status:** COMMENTED

Hello there! Good Job
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/111#discussion_r1092795834" expanded>

Cases are too long, maybe create new class to handle each case
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/111#discussion_r1092796263" expanded>

Better to use a constant for Task[100] i.e Task[MAXTOTALSIZE]
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/111#discussion_r1092796545" expanded>

Use better naming instead of just t. i.e task
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/111#discussion_r1092796894" expanded>

Good use of boolean sounding variables
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/111#pullrequestreview-1278475324" expanded>

**Review Status:** COMMENTED

Good job on your work
</panel>

</panel>

<panel type="info" header="### 84. KHAI..ALIM `@kairuler` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/114#discussion_r1094216488" expanded>

I like how all the `if` and `else if` conditional statements in this `while` loop are clearly named and gives readers a good idea of what each statement checks and what the results of each check are. 👍 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/114#discussion_r1094222371" expanded>

☝️ I agree with steven's comment! Perhaps putting the return result in an aptly named variable like `isValidTask` could make this portion of the code easier to understand. However, since the method name already gives a good idea of what the return result is supposed to be, this suggestion may be unnecessary.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/114#discussion_r1094227285" expanded>

I'm not too sure what this number is referring to... Perhaps giving a name such as `taskNumber` could make it clearer on what `number` refers to.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/114#discussion_r1094233797" expanded>

I like the use of constants instead of magic numbers! 👍 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/114#pullrequestreview-1280586959" expanded>

**Review Status:** COMMENTED

Overall very clean and readable code, with just a few minor points to possibly change. 👏 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/198#discussion_r1094146395" expanded>

Nice! I like your usage of constants (instead of magic numbers) and I like how they are typed (all uppercase, underscore to separate words).
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/198#discussion_r1094155723" expanded>

Could `isByeEntered` be named to sound more like a boolean variable? It is a bit confusing what `isByeEntered` does just based off its name 😁 .
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/198#discussion_r1094159148" expanded>

Spacing is sometimes inconsistent (maybe by accident?). Here, `}else{` has no spaces between the braces but elsewhere, there are spaces. I noticed this a few times in the above code too. Be sure to double check!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/198#discussion_r1094162246" expanded>

I like how your array specifier is attached to the type and not the variable 👍 nice
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/198#discussion_r1094186830" expanded>

I wasn't sure on what `a` did until I read the code fully... I think changing the variable name `a` could make it more understandable for readers!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/198#pullrequestreview-1280483476" expanded>

**Review Status:** COMMENTED

Overall, I like how your code is quite clean and you adhered to coding standards most of the time! I noticed some variable names and spacing that you may have unintentionally overlooked but they are just minor errors. Good job!
</panel>

</panel>

<panel type="info" header="### 85. SEOW..HENG `@RuiShengGit` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/116#discussion_r1093985853" expanded>

Should avoid the use of magic numbers. Consider using a named constant for the array size,100, for todo
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/116#discussion_r1094474507" expanded>

Consider shortening the method as method appears to be long, exceeding 30 LOC (lines of code).
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/116#discussion_r1094479697" expanded>

Code does not seem to have deep nesting which is good
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/116#discussion_r1094507685" expanded>

As mentioned before, can consider removing dead code.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/116#discussion_r1094548304" expanded>

I believe that the code can be structured more logically, there is no clear order to the code as everything is written in void main, can consider using using more methods so that the code can be easier to read.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/116#pullrequestreview-1280266264" expanded>

**Review Status:** COMMENTED

Overall, good effort but I think there are still some improvements that can be made to the coding style. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/170#discussion_r1093980234" expanded>

Good naming conventions, variable names are camelCase, boolean variables are made to sound like booleans
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/170#discussion_r1093981034" expanded>

Constant name are uppercases, good job
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/170#discussion_r1094525021" expanded>

Good job that you listed imported classes explicitly
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/170#discussion_r1094529545" expanded>

Good job following the proper coding standard for switch statements
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/170#pullrequestreview-1280241989" expanded>

**Review Status:** COMMENTED

Overall I think you did a great job following the coding standard.
</panel>

</panel>

<panel type="info" header="### 86. RICH.. JUN `@SpawnageLoong` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/97#discussion_r1093986637" expanded>

Could this method be changed to use switch-case for readability?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/97#discussion_r1093986797" expanded>

Lines are long but still stay within 100 char length which is good.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/97#discussion_r1093987042" expanded>

Static literal uses full-caps which is good.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/97#discussion_r1093987321" expanded>

Should the capitalisation here be Todo or ToDo?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/97#pullrequestreview-1280269860" expanded>

**Review Status:** COMMENTED

Overall, the code follows all the coding standard guidelines.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/150#discussion_r1093980815" expanded>

Could you extract this (and other) string literal(s) into a static?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/150#discussion_r1093982166" expanded>

Task and Todo are functionally identical at this point (apart from returning "[T]"). Could they be merged into a single class?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/150#discussion_r1093982750" expanded>

Could the square brackets be added into getStatusIcon() to simplify the code?
```suggestion
    public String getStatusIcon() {
        return (isDone ? "[X]" : "[ ]"); // mark done task with [X]
    }

    @Override
    public String toString() {
        return this.getStatusIcon();
    }
```
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/150#discussion_r1093984037" expanded>

Could the description splitting be abstracted into a separate method?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/150#discussion_r1093984468" expanded>

Could these methods be extracted to the Task class?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/150#pullrequestreview-1280244477" expanded>

**Review Status:** COMMENTED

Overall, the code was easy to read, but the string literals in a lot of the print methods can be extracted to statics and some methods in Duke can be extracted to other classes.
</panel>

</panel>

<panel type="info" header="### 87. VARA..NESH `@Vignesh-30` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/71#discussion_r1093125657" expanded>

Perhaps, you could try to declare this variable as a constant - "static final string line",
This might make it easier to call and print it out.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/71#discussion_r1093127027" expanded>

Perhaps, you could use "**\t** Hello from...." to print out indented text to the user.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/71#discussion_r1093130090" expanded>

I like how you made use of indentations for the switch and case statements maximizing the readability.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/71#discussion_r1093135629" expanded>

Perhaps, you might want to rename this boolean variable or add comments to describe what flag is meant to exit.
Maybe an alternative name like "boolean isByeCommand" might be more clearer to a reader.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/71#discussion_r1093138399" expanded>

Maybe, you could try to extract these commands as seperate methods which are then called in the main function instead of having all these commands listed out in full in the main function.

The switch statement above could also be extracted to be a seperate method which could then call these command methods.

This could improve the flow of your code.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/71#pullrequestreview-1278972629" expanded>

**Review Status:** COMMENTED

Overall, I really liked your indentations and formatting of code. The variable names were well defined and comments were helpful.

</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/107#discussion_r1092761240" expanded>

Consistency could be maintained in leaving a empty line after opening class bracket.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/107#discussion_r1092763624" expanded>

I like how you seperated this line into two to reduce the line length. The indentation in the second line also makes it more readable.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/107#discussion_r1093113457" expanded>

I like how you described the purpose of the functions and also gave references to where you adapted the code from.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/107#discussion_r1093120005" expanded>

An indentation could be left after this closing bracket to follow consistency.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/107#pullrequestreview-1278426210" expanded>

**Review Status:** COMMENTED

Overall, your code is really good and clean with proper naming format and indentations!
</panel>

</panel>

<panel type="info" header="### 88. GOH ..HONG `@waiter-palypoo` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/132#discussion_r1093121008" expanded>

I would consider using the split() method to identify individual words
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/132#discussion_r1093127186" expanded>

I think equals() might be better here so in case a task has substring "bye" in it the program doesn't exit
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/132#discussion_r1093129939" expanded>

Good use of ternary operator
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/132#discussion_r1093133750" expanded>

Variable name length might be confusing as it might refer to length of a string, consider using something else like numberOfTasks for example
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/132#pullrequestreview-1278965981" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/196#discussion_r1093141242" expanded>

The case clauses and switch statement should be aligned, i.e. no indentation.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/196#discussion_r1093141758" expanded>

Nice
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/196#discussion_r1093143392" expanded>

Good error handling
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/196#discussion_r1093144339" expanded>

cute pikachu
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/196#discussion_r1093146395" expanded>

Good job considering such exceptions!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/196#pullrequestreview-1278996260" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 89. POH .. PIN `@firwer` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/60#discussion_r1092754888" expanded>

Would it be better to have a separate display class or something similar that will handle all CLI prints? (including logo print)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/60#discussion_r1092760703" expanded>

I like how you have properly documented the functions and the inputs
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/60#discussion_r1093031273" expanded>

Good practice of indicating function overriding
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/60#discussion_r1093032328" expanded>

Good job on the consistent following of pascal/camel casing for class, method and variable names!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/60#pullrequestreview-1278417624" expanded>

**Review Status:** COMMENTED

LGTM in general, you followed the camel and pascal case requirements and there isn't much coding standards violation to highlight, good job!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/60#pullrequestreview-1278835178" expanded>

**Review Status:** COMMENTED

Follow up to the previous review
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/157#discussion_r1092762515" expanded>

Would it be better to split the different classes up to separate class files rather than storing them all under the same file?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/157#discussion_r1092942984" expanded>

Good way to split print functions out! Would it be better to split them out as a separate class like Display.java? It might make your codebase appear even cleaner :)
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/157#discussion_r1092959145" expanded>

Good use of enum!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/157#discussion_r1092961828" expanded>

Might be good to  document the functions using params learned in cs1010, would improve readability
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/157#discussion_r1092964931" expanded>

This might be better according to switch statement coding standards
```
default:
    System.out.println("Failed to add: Invalid Task format"); 
    return false;
```
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/157#pullrequestreview-1278427884" expanded>

**Review Status:** COMMENTED

LGTM, just some nits here and there to fix, and class file separation is needed. Keep it up!
</panel>

</panel>

<panel type="info" header="### 90. NIKH..DHAR `@nikkiDEEE` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/74#discussion_r1094145867" expanded>

I like how you didnt just use `java.util.*`!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/74#discussion_r1094146343" expanded>

I like how you used a resizable array!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/74#discussion_r1094147518" expanded>

Perhaps this empty nextline can be omitted?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/74#discussion_r1094147897" expanded>

Perhaps this nextline comment can be removed to adhere to the coding standards?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/74#discussion_r1094149593" expanded>

Perhaps you could use the array variable name `isMarked` so it sounds like a boolean?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/74#pullrequestreview-1280482690" expanded>

**Review Status:** CHANGES_REQUESTED

Overall, the codeing standard indentation lengths have been met but there are some minor issues with the empty lines which can be removed to make the overall code slightly cleaner. Keep up the good work!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/108#discussion_r1094156864" expanded>

I like how you used static final variables for code quality (clarity)!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/108#discussion_r1094157053" expanded>

Good job using enums! CommandTypes is an excellent datatype to categorize your different variables.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/108#discussion_r1094161373" expanded>

Excellent work with the additional work on the UI-testing!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/108#discussion_r1094163050" expanded>

isProgramRunning is a great and clear way of using the boolean!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/108#pullrequestreview-1280498104" expanded>

**Review Status:** APPROVED

LGTM!
</panel>

</panel>

<panel type="info" header="### 91. EE J..ARED `@jared-ee` (18 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#discussion_r1092760351" expanded>

Nice-looking case code. Also case clauses are not indented, which is correct
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#discussion_r1092762500" expanded>

If line is too long (>120 characters), wrap lines with 8 spaces indentation.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#discussion_r1092767055" expanded>

Good, array specifier attached to the type 'Task', not the variable 'storedTasks'.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#discussion_r1092767748" expanded>

Good handling of indentation. While loop has even more for loops/if cases inside but code segments are indented so it is clear which block belongs inside which brackets.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#discussion_r1092768978" expanded>

Good, only relevant class imported, instead of java.util.*
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#pullrequestreview-1278425036" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#pullrequestreview-1278427860" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#pullrequestreview-1278434320" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#pullrequestreview-1278435271" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/27#pullrequestreview-1278437101" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/60#discussion_r1092775213" expanded>

Don't leave an empty line here for consistency since all other classes don't leave an empty line after the opening bracket
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/60#discussion_r1092775951" expanded>

Code documenting style is clean, with proper indentation and clear explanation of what the function does.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/60#discussion_r1092776585" expanded>

Standardize whether after the function/class name, will you leave a space before typing the opening bracket or not
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/60#discussion_r1092781187" expanded>

Indentation issues. Since line +15 is within the switch statement, the closing bracket of switch should be aligned with it. Similar issue with closing bracket of while loop on line +17
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/60#pullrequestreview-1278446319" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/60#pullrequestreview-1278447405" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/60#pullrequestreview-1278448248" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/60#pullrequestreview-1278454585" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 92. TEO ..ADEN `@adenteo` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/48#discussion_r1092839962" expanded>

Good use of named constants.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/48#discussion_r1092840540" expanded>

Very creative and interesting feature here! :)
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/48#discussion_r1092845655" expanded>

The code written for the handling of user input is quite clean and easy to understand. Good job!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/48#discussion_r1092849562" expanded>

Good use of comments and named constants to explain the use of the substring functions.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/48#discussion_r1092854406" expanded>

Very interesting feature! Am looking forward to see how this feature develops.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/48#pullrequestreview-1278542436" expanded>

**Review Status:** COMMENTED

Overall, your code was relatively easy to read and follow. Your usage of Javadoc comments made it very easy to understand what every function was for. Your singlish feature is very interesting too! Good job!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/153#discussion_r1092819901" expanded>

Perhaps it is better to modify this into a Boolean function to check whether is it a single/multi-word user input?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/153#discussion_r1092820654" expanded>

Good use of switch statement for a clean description of each case!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/153#discussion_r1092822800" expanded>

Perhaps it is better to use Boolean functions for these code segments on input validation? This is applicable to a few other segments as well that I have noted out.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/153#discussion_r1092825695" expanded>

Perhaps it is better to avoid magic numbers to make it clearer to the reader? Could consider using named constants or other methods to split the user input.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/153#pullrequestreview-1278512908" expanded>

**Review Status:** COMMENTED

Overall, I found your code relatively easy to read. Every function was simple and neat and the flow of events were quite clear. I noted a few segments regarding your validation of user inputs which could be quite confusing. There was also a segment where you used magic numbers to obtain substrings of the user input, which may not be intuitive.  Consider using named constants or creating functions for input validation?
</panel>

</panel>

<panel type="info" header="### 93. SONG..IJIN `@SongZijin` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/108#discussion_r1094137765" expanded>

It may be slightly clearer if all the variables are declared at the start of the document, since other people reading from top to bottom may be a little confused about what additionalParameters is. 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/108#discussion_r1094140275" expanded>

Good catch to not include any spacing before each case under switch!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/108#discussion_r1094143914" expanded>

```suggestion
        } catch (Exception e) {
```
I think that the coding standard for try-catch statements is like this, having the catch on the same line as }
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/108#discussion_r1094145722" expanded>

```suggestion
            } else {
```
According to the coding standards, the else should be on the same line , like how you did below
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/108#discussion_r1094147225" expanded>

```suggestion
        } else {
```
Same error as mentioned above, it may be important to check that these if-else statements are indented in a similar way
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/108#pullrequestreview-1280470797" expanded>

**Review Status:** COMMENTED

The code is very clear and organised in general, but there are some small areas that is not following the coding standard. It may be important to check out the relevant document and adjust accordingly.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/213#discussion_r1094154617" expanded>

Since you abstracted the [greet_user()] function, it may be better if you maintain Single Level of Abstraction Principle (SLAP), and also extract this portion as a separate function
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/213#discussion_r1094157052" expanded>

It may be better to avoid using a magic number (100) and instead define it at the top of the file as MAX_NUMBER_OF_TASKS
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/213#discussion_r1094160071" expanded>

Good job on extracting this part as a separate function
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/213#discussion_r1094160554" expanded>

It may be clearer to extract these parts as separate functions to avoid nesting loops.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/213#pullrequestreview-1280495011" expanded>

**Review Status:** COMMENTED

In general, the code is quite clear, however, there is a lot of potential for clearer and more concise code.
</panel>

</panel>

<panel type="info" header="### 94. LINU..A HE `@linuspuah` (18 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/37#discussion_r1094196773" expanded>

What is the 4 here representing, if possible can create a variable name for the number instead of leaving it as a magic number.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/37#discussion_r1094200083" expanded>

Can create a constant MaxTasks to represent the 100 instead of leaving it as a magic number
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/37#discussion_r1094207369" expanded>

Maybe a clearer name for description would be taskDescription. (applicable change to other classes as well)
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/37#discussion_r1094211849" expanded>

Maybe the naming of this method could be more appropriately changed to getTaskIdentity since the actual method itself is not printing anything. 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/37#discussion_r1094217866" expanded>

Can try to rename the new task t to newTask as t fails to provide ample description of the variable
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/37#pullrequestreview-1280558179" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/37#pullrequestreview-1280563193" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/37#pullrequestreview-1280573957" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/37#pullrequestreview-1280580300" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/37#pullrequestreview-1280589025" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/67#discussion_r1094143702" expanded>

There is an extra space before .length, maybe you can try using the ctrl + alt + L command to auto reformat
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/67#discussion_r1094149084" expanded>

Can try to rename to a more appropriate name like isComplete
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/67#discussion_r1094172741" expanded>

Can try to add a variable for the magic constant 3 in the new String array
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/67#discussion_r1094176406" expanded>

Can try a clearer name for limit, instead can try indexLimit
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/67#pullrequestreview-1280479431" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/67#pullrequestreview-1280487369" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/67#pullrequestreview-1280522592" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/67#pullrequestreview-1280528174" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 95. TENG..-KAI `@iantenkai` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/66#discussion_r1095303182" expanded>

Would it be better to have the welcome message in a single command?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/66#discussion_r1095306205" expanded>

Would it be better to synthesize the output within the constructor instead of the main file?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/66#discussion_r1095307127" expanded>

I like how you check if the input to mark is valid 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/66#discussion_r1095308644" expanded>

I like the use of comments to help make the code more readable
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/66#pullrequestreview-1282210180" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/126#discussion_r1095310023" expanded>

I like the use of a string to store the initial command
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/126#discussion_r1095310592" expanded>

Would issues arise if the user input is longer than the maximum size of the array?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/126#discussion_r1095312131" expanded>

Since you have already parsed the input into a string array, wouldn't it be better to use the second index of the  command array instead?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/126#discussion_r1095313355" expanded>

could these statements be better abstracted?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/126#discussion_r1095315464" expanded>

the mark and unmark cases are the same. I think it would be better to refactor them to a single method
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/126#pullrequestreview-1282219811" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 96. HAMA..HIRO `@Masahiro21` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/135#discussion_r1092873073" expanded>

I like the addition of an error prompt so that you can track unexpected inputs
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/135#discussion_r1092875938" expanded>

I like how you used a different class to handle different types of tasks input
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/135#discussion_r1092877918" expanded>

I like how you added different exceptions to help with the handling of unexpected results
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/135#discussion_r1092879972" expanded>

Perhaps the naming of the methods can be shortened for ease of use
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/135#pullrequestreview-1278589845" expanded>

**Review Status:** COMMENTED

Overall good job, I like the way you implemented different ways to catch errors. Perhaps in the future you can implement more subclasses to handle the inputs
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/149#discussion_r1092863646" expanded>

I like how you used a test file to test your codes 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/149#discussion_r1092865310" expanded>

I like how you clarified the use of a method and the code implementation of simplified
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/149#discussion_r1092866646" expanded>

I like how you annotated that you overridden the toString object and made use of inheritance
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/149#discussion_r1092868370" expanded>

i like your naming convention of variables, follows coding standards which is good
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/149#discussion_r1092871225" expanded>

good that you followed the coding standard use of camel case
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/149#pullrequestreview-1278576188" expanded>

**Review Status:** COMMENTED

Overall I like the way your code is written, it's neat and follows the coding standards well. Good use of different classes and methods for handling different input cases
</panel>

</panel>

<panel type="info" header="### 97. NGUY.. ANH `@quanganh2810` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/61#discussion_r1092789122" expanded>

I like that you have this method to instruct on what the input should be
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/61#discussion_r1092790041" expanded>

should you add a new class like TaskManager to keep all of these methods in the main ?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/61#discussion_r1092790272" expanded>

I like how neat your extensions are
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/61#discussion_r1092790482" expanded>

I like how u did the "optional" hahaa
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/61#discussion_r1092794878" expanded>

your code overall is rather seamless good job !

</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/61#pullrequestreview-1278465761" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/104#discussion_r1092792346" expanded>

Should you remove this greeting function considering that you only used it once throughout the code ?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/104#discussion_r1092792996" expanded>

I like the usage of the horizontalLine function i find it quite smart XD
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/104#discussion_r1092799307" expanded>

Good namings throughout this part !
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/104#discussion_r1092801501" expanded>

i like how you have the getStatus function, it is a very efficient way of doing the print
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/104#pullrequestreview-1278470371" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 98. RYUJ..E SI `@Ryujikjs` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/33#discussion_r1094119946" expanded>

You might want to look into creating a class to read and split the input 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/33#discussion_r1094122009" expanded>

You might want to avoid long main function as it is currently 46 lines which is a bit lengthy and might affect readability of code
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/33#discussion_r1094134829" expanded>

Perhaps you should split mark and unmark case and handle each case separately, this would reduce the use of redundant boolean isMark.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/33#discussion_r1094138012" expanded>

You could look into having "taskname" capitalized as it has been declared as final which would imply that it not a variable. 

''''suggestion
    private final String TASK_NAME;
''''
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/33#pullrequestreview-1280445196" expanded>

**Review Status:** COMMENTED

Generally good code quality, however, could improve on efficiency and readability of code. 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/194#discussion_r1094010728" expanded>

Perhaps you could check if it is spelled deadline or dead line. The uppercase  "L"  affects code readability as It might be interpreted as "dead line" which might  be interpreted differently from "deadline" . 

```suggestion
public class Deadline extends Task
```
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/194#discussion_r1094013904" expanded>

Perhaps you could check if it is spelled deadline or dead line. The uppercase  "L"  affects code readability as It might be interpreted as "dead line" which might  be interpreted differently from "deadline" 

```suggestion
    private String deadlineBy;
```
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/194#discussion_r1094017675" expanded>

Perhaps you could check which style of brackets should be used to comply with the coding standards. 

```suggestion
    if (line.equals("bye")) {
        //code here
    }
```
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/194#discussion_r1094020222" expanded>

Perhaps you could check if it is spelled deadline or dead line. The underscore between "DEAD" and "LINE" affects code readability as It might be interpreted as "dead line" which might be interpreted differently from "deadline". The same applies to "To_Do".

```suggestion
    TODO, DEADLINE, EVENT
```
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/194#discussion_r1094023665" expanded>

Perhaps you could check if it is supposed to be spelled todo or to do. I believe it might be more readable if it is read as one word 

```suggestion
public class Todo extends Task
```
    
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/194#pullrequestreview-1280331062" expanded>

**Review Status:** COMMENTED

Can check your naming of variables and classes to conform to the coding standards and ensure code readability.
</panel>

</panel>

<panel type="info" header="### 99. CHAO..I-JU `@chao2048` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/104#discussion_r1092754602" expanded>

According to the Java coding standards, the variable `is_exit` should be name as `isExit`.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/104#discussion_r1092756428" expanded>

Perhaps you can rename `taskStorage` as `tasks`, as plural form should be used to present a collection :)
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/104#discussion_r1092756792" expanded>

I like this function, and it helps a lot when coding!.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/104#discussion_r1092759381" expanded>

Good job for following the naming standard!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/104#pullrequestreview-1278417285" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/106#discussion_r1092922679" expanded>

Perhaps you can avoid magic number by introducing a constant for the size of tasks.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/106#discussion_r1092923230" expanded>

Good job for avoiding deep nesting if-else statement :))
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/106#discussion_r1092927837" expanded>

I think you can create constant strings (char) for `task_status` done and not done to prevent magic string as well.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/106#discussion_r1093122354" expanded>

Perhaps you can consider making the whole input part into a method as well.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/106#discussion_r1093125659" expanded>

Overall, the code has pretty good readability :))
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/106#pullrequestreview-1278663579" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 100. CHEW..ACEY `@kaceycsn` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/143#discussion_r1092843137" expanded>

Great! Good use of comments to make code readable.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/143#discussion_r1092854181" expanded>

You may consider using line wrapping to keep line length short.
```suggestion
        return "[E][" + getStatusIcon() + "] " + taskDescription 
                + " (from: " + startTime  + " to: " + endTime + ")" ;
```
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/143#discussion_r1092862969" expanded>

Good! Array specifiers attached to the type and not the variable.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/143#discussion_r1092864670" expanded>

Great! Layout for if-else statements fit the coding standards.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/143#discussion_r1092866502" expanded>

Short comments can appear on the same line as the code they describe, but should be shifted far enough to separate them from the statements. Alternatively, you may consider adding the comment on a separate line, indented relative to their position in the code.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/143#pullrequestreview-1278546891" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/202#discussion_r1092941855" expanded>

Consider changing the variable name. Variables named j, k etc. should be used for nested loops only.

```suggestion
        int counter = 1;
```
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/202#discussion_r1092942777" expanded>

Great! Array specifiers is attached to the type not the variable.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/202#discussion_r1092943259" expanded>

Perhaps you can consider using switch instead of multiple if-else statements to make your code cleaner and more readable
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/202#discussion_r1092945869" expanded>

Consider changing method name. Method names must be in camelCase.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/202#pullrequestreview-1278680503" expanded>

**Review Status:** COMMENTED

Looks good! Code generally follows the coding standard. Some suggestions are given.
</panel>

</panel>

<panel type="info" header="### 101. ZENG..IQIU `@ZiqiuZeng` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/103#discussion_r1095310438" expanded>

Perhaps the indexes here need a bit improve.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/103#discussion_r1095336443" expanded>

Nice documentation.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/103#discussion_r1095337321" expanded>

It might be better if the indexes are the same.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/103#discussion_r1095337863" expanded>

Brilliant. I appreciate the way how you extract method here.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/103#discussion_r1095338255" expanded>

It is fantastic to separate the commands like that.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/103#pullrequestreview-1282220460" expanded>

**Review Status:** COMMENTED

Everything is perfect.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/169#discussion_r1095301148" expanded>

I like the way how you separate different tasks! Good job!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/169#discussion_r1095301735" expanded>

May it be a bit more interesting if you keep the logo?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/169#discussion_r1095302473" expanded>

It is so clever to split commands in this way!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/169#discussion_r1095304567" expanded>

I like the ">" added here! It makes the code more readable.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/169#pullrequestreview-1282207489" expanded>

**Review Status:** COMMENTED

Overall, I love the way how you code. These files follow the provided coding standard well and are easy to read. Everything looks good.
</panel>

</panel>

<panel type="info" header="### 102. UDAY..ETHA `@NivethaUdayakumar` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/17#discussion_r1092759503" expanded>

Well-defined enum constants.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/17#discussion_r1092762362" expanded>

Good use of K&R style brackets.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/17#discussion_r1092763098" expanded>

Standard: Case statement should have a default branch.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/17#discussion_r1092763426" expanded>

Good! The imported classes are listed explicitly. 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/17#discussion_r1093006855" expanded>

Good job following the method & variable naming conventions and Javadoc comments structure!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/17#pullrequestreview-1278423903" expanded>

**Review Status:** COMMENTED

Overall, good adherence to coding standards and practices. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/141#discussion_r1093053931" expanded>

Could refactor code into method. 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/141#discussion_r1093058401" expanded>

Good! Code follows logical structure.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/141#discussion_r1093062458" expanded>

Good, no deep nesting!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/141#discussion_r1093070932" expanded>

Suggestion: can be combined into a method named setTaskStatus(boolean state) which sets the state of the task as complete (true) or not complete (false) depending on the value of state variable (this.isDone = state;). 
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/141#pullrequestreview-1278868582" expanded>

**Review Status:** COMMENTED

Overall, good adherence to code quality with only minor suggestions for improvement!
</panel>

</panel>

<panel type="info" header="### 103. STEI..THEW `@jacob-stein1` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/63#discussion_r1094052518" expanded>

I think constants should use the 'final' keyword and be fully capitalized
```suggestion
final String LOGO = *logo text*
final String SYMBOL = "─────▄██▀▀▀▀▀▀▀▀▀▀▀▀▀██▄─────\n"
```
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/63#discussion_r1094055204" expanded>

Good job following switch case indentation
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/63#discussion_r1094057014" expanded>

I think since the Scanner object is also a constant, you must use the final keyword and capitalize
```suggestion
final Scanner INPUT = new Scanner(System.in);
```
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/63#discussion_r1094059040" expanded>

This is very picky, but I think a space is needed before the opening curly bracket, same for the markAsUndone() method below
```suggestion
public void markAsDone() {
```
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/63#discussion_r1094061560" expanded>

Good job following boolean naming conventions
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/63#pullrequestreview-1280366817" expanded>

**Review Status:** COMMENTED

Overall your code is very easy to follow and you did a very good job following coding standards. There are some very small issues like constant naming conventions and spaces before the curly brackets on functions, but otherwise it is good. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/166#discussion_r1094068679" expanded>

Here it may be more clearer to create a constant variable called TASK_ARRAY_LENGTH to denote the length of the array
```suggestion
final int TASK_ARRAY_LENGTH = 100;
Task[] tasks = new Task[TASK_ARRAY_LENGTH];
```
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/166#discussion_r1094070997" expanded>

In this case it may be better to use a switch statement, but it is still clear as is
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/166#discussion_r1094073084" expanded>

It may be good to create a method for this in the task class. Perhaps keep the array of tasks in the Task class and add to it within the constructor
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/166#discussion_r1094075403" expanded>

It may be good to give the Scanner object a clearer name, such as CONSOLE or INPUT
```suggestion
final Scanner INPUT = new Scanner(System.in);
```
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/166#pullrequestreview-1280381000" expanded>

**Review Status:** COMMENTED

Your code is very easy to follow and clear. I think the biggest thing to consider is using a switch statement rather than a string of if-else statements, as it will add more clarity. Besides that I made some small quality suggestions, but otherwise great job!
</panel>

</panel>

<panel type="info" header="### 104. KRIS..HWAN `@kristianachwan` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/13#discussion_r1092854597" expanded>

Perhaps, it is better to change the name of this variable into task since I believe Task is more related to the entity 'Task'?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/13#discussion_r1092854995" expanded>

Perhaps the naming for this variable can be clearer?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/13#discussion_r1092855474" expanded>

Perhaps can use taskIndex instead? 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/13#discussion_r1092857722" expanded>

Can use a more descriptive name I think?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/13#discussion_r1092858405" expanded>

Can use this?
```
else {
  return ... 
}
``` 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/13#pullrequestreview-1278563235" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/107#discussion_r1093149854" expanded>

Perhaps changing into regular if-else statement is more readable? 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/107#discussion_r1093150370" expanded>

I like how you really separate the logic so that this file is staying lean
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/107#discussion_r1093152079" expanded>

I like how you handled the corner case quite neat
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/107#discussion_r1093154591" expanded>

Perhaps it is better to make it into multiple lines of code? I think it is better to make it more step by step rather than chaining multiple methods?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/107#pullrequestreview-1279009175" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 105. ZHAN..ANXU `@danxuZhang` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/15#discussion_r1095306005" expanded>

Attributes in a class should be private. 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/15#discussion_r1095307118" expanded>

Would be better to handle cases when the user tries to mark an already marked task.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/15#discussion_r1095308016" expanded>

It would be better to handle cases when the input is not an integer (To catch the exception).
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/15#discussion_r1095308446" expanded>

Again, attributes should be private.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/15#discussion_r1095308783" expanded>

And use getters and setters to access or modify private attributes.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/15#pullrequestreview-1282214203" expanded>

**Review Status:** COMMENTED

Overall, the file structures are well-organized, just some minor changes need to improve. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/186#discussion_r1095303853" expanded>

Names should be in camelCase, and would be better to use a better name such as `commandArray`.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/186#discussion_r1095304486" expanded>

There is no need to create a new `Scanner` for each input.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/186#discussion_r1095304688" expanded>

Again, there is no need to create a new `Scanner`.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/186#discussion_r1095305205" expanded>

Naming should be in camelCase.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/186#pullrequestreview-1282211357" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 106. ZHAN..SHAN `@zzs-redcocoon` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/49#discussion_r1092762586" expanded>

It's good to name methods as verbs and write them in camelCase.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/49#discussion_r1092762954" expanded>

It's good to name variable in camelCase.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/49#discussion_r1092763566" expanded>

It's good to write class names in nouns and in PascalCase.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/49#discussion_r1092764048" expanded>

I think this method might be better named sendGoodByeMessage,  because names representing methods must be verbs. Other methods like printXxx, createXxxx ... are OK.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/49#pullrequestreview-1278427999" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/143#discussion_r1092994701" expanded>

Perhaps "line" here is better named like "LINE" , as constant names must be all uppercase.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/143#discussion_r1093005853" expanded>

I like one method 'taskStatusHandler' instead of 2 split methods.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/143#discussion_r1093014803" expanded>

I'm not sure whether it's better to merge several 'System.out.println()' into one. Or you may consider using line spacing to structure the code more logically.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/143#discussion_r1093015695" expanded>

I like the addition of an error prompt so that you can track unexpected inputs
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/143#discussion_r1093021669" expanded>

Maybe it's better to do some modifications to the 'index++' here to get a better abstraction, according to the SLAP.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/143#pullrequestreview-1278781674" expanded>

**Review Status:** COMMENTED

Overall, I found your code easy to read for the most part. I noted a few minor coding standard violations. Moreover, I think it's better to separate different functional parts in the methods (e.g. separate data processing and feedback printing). The methods in the code here just do all the things together.
</panel>

</panel>

<panel type="info" header="### 107. POH ..AMIN `@BenjaminPoh` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/25#discussion_r1093932579" expanded>

This line of code is a little too long (Java coding standard's hard limit is 120 characters). Can consider using line wrapping at appropriate places.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/25#discussion_r1093935204" expanded>

This looks like it indicates the number of tasks, but may be misinterpreted to be the index of a specific task. Can consider renaming to numberOfTasks or something similar. 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/25#discussion_r1093935913" expanded>

Line 54, Line 60 and Line 66 works similarly. Can consider refactoring to a separate function instead.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/25#discussion_r1093936534" expanded>

Line 79-80 is similar in function to Line 85-86. Can consider refactoring to a separate function which updates the status of a specific task instead.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/25#pullrequestreview-1280159983" expanded>

**Review Status:** COMMENTED

Good effort, great use of Inheritance and refactoring, and code was easy to read/follow. :)
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/116#discussion_r1093921097" expanded>

Missing newline between line 12 and 13.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/116#discussion_r1093923285" expanded>

Repeated function with line 33, can consider refactoring to a function instead.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/116#discussion_r1093923953" expanded>

Dead code can be removed
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/116#discussion_r1093924518" expanded>

Variables should be written in camelcase, "split" in this case
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/116#discussion_r1093927571" expanded>

This line of code is a too long (Java coding standard's hard limit is 120 characters). Can consider using line wrapping at appropriate places.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/116#pullrequestreview-1280144463" expanded>

**Review Status:** COMMENTED

Good effort, mostly minor coding standard violations. :)
</panel>

</panel>

<panel type="info" header="### 108. NIGE.. HAO `@nigelhao` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/75#discussion_r1093932520" expanded>

This constructor is not necessary
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/75#discussion_r1093938266" expanded>

arrayOfInput could be inputs
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/75#discussion_r1093938366" expanded>

arrayOfInput could be inputs
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/75#discussion_r1093939611" expanded>

System.lineSeparator() is a little long, probably can just use '\n'
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/75#pullrequestreview-1280159897" expanded>

**Review Status:** COMMENTED

So far the code quality is good. Keep it up
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/90#discussion_r1093922732" expanded>

Messages is in plural form, it should be in singular form
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/90#discussion_r1093924048" expanded>

Redundant comment, code itself is understandable
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/90#discussion_r1093925360" expanded>

Lists is also in plural form, it should be in singular form
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/90#discussion_r1093927034" expanded>

These methods should be handled in Task class. Not a coding violation, just best practice. 👍 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/90#discussion_r1093927803" expanded>

Redundant comment
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/90#pullrequestreview-1280146711" expanded>

**Review Status:** COMMENTED

Overall its good and clean! Good job! 👍 
</panel>

</panel>

<panel type="info" header="### 109. CHON..RONG `@ChongQiRong` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/146#discussion_r1093938528" expanded>

Can remove redundant comment
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/146#discussion_r1093940024" expanded>

Variable naming should be camelcase
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/146#discussion_r1093941338" expanded>

Can remove redundant line
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/146#discussion_r1093943294" expanded>

case should be inline with switch
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/146#pullrequestreview-1280168291" expanded>

**Review Status:** COMMENTED

Good refactoring of code with minor coding standard errors
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/174#discussion_r1093921462" expanded>

Extra line
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/174#discussion_r1093922133" expanded>

Redundant comment
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/174#discussion_r1093923892" expanded>

Do not need comment to understand this line of code
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/174#discussion_r1093925260" expanded>

Can remove this extra line
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/174#discussion_r1093926488" expanded>

Can add line before next method
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/174#pullrequestreview-1280144956" expanded>

**Review Status:** COMMENTED

Generally good coding standard with minor errors
</panel>

</panel>

<panel type="info" header="### 110. TANG..DONG `@EthanYidong` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/22#discussion_r1093923369" expanded>

```suggestion
    public Event(String description, int num, String from, String to) {
```
It may improve readability to standardize spacing according to [Google's Coding Standards](https://google.github.io/styleguide/javaguide.html#s4.6.2-horizontal-whitespace). I noticed the same issue in other places too.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/22#discussion_r1093923549" expanded>

I like the usage of capitalization for constants.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/22#discussion_r1093925001" expanded>

I like the naming of your boolean variables indicating that they are booleans using "is".
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/22#discussion_r1093927083" expanded>

```suggestion
            } else {
```
Perhaps add spacing around your else for better readability?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/22#pullrequestreview-1280147593" expanded>

**Review Status:** COMMENTED

Looks good overall, however some coding standards need to be more consistently applied. Specifically, consider inserting spaces between certain symbols to improve readability.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/145#discussion_r1093929046" expanded>

This code appears in very similar forms below. Perhaps it would be a good idea to extract this out to be a method of `Task`?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/145#discussion_r1093930092" expanded>

I think keeping old code present as comments decreases readability as most readers are expecting explanations of code in your comments. Maybe you can delete these and refer to previous commits if you ever need to reference old versions of your code?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/145#discussion_r1093930507" expanded>

I don't like the usage of a magic literal here, perhaps you can extract it to a variable which better explains what the 100 means here?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/145#discussion_r1093931456" expanded>

`isBye = true` is redundant here because `break` will exit from the loop. It may be best if you remove `isBye` from your code as it isn't serving any purpose here.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/145#discussion_r1093931962" expanded>

I like the usage of a named variable instead of a magic literal, but could this be a constant instead?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/145#pullrequestreview-1280155254" expanded>

**Review Status:** COMMENTED

Overall the code was reasonably readable with the most common code extracted to functions. However, I noted that the majority of your business logic is still housed under the main function. As your code becomes more complicated, you should consider further extracting out functionality into other classes and methods.
</panel>

</panel>

<panel type="info" header="### 111. TANG..HAWN `@shawntangy` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/78#discussion_r1093976217" expanded>

Could consider extracting this line out as a constant 'DEADLINE_INSTRUCTION'.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/78#discussion_r1093977396" expanded>

I really liked how you use a try and catch here!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/78#discussion_r1093978043" expanded>

Maybe could do a static counter variable in the Task Class instead of Duke Class. Or is there any reason you chose to do it this way?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/78#discussion_r1093978657" expanded>

Maybe can extract out the '[E]' to be a constant too, also applies for deadline/todo [D]/[T]
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/78#pullrequestreview-1280224579" expanded>

**Review Status:** COMMENTED

Overall the code is very neat, well done :)
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/86#discussion_r1093982407" expanded>

Could consider refactoring and extracting these Strings to be a constant value
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/86#discussion_r1093982927" expanded>

Maybe the 100 can also be extracted to reduce 'magic numbers'
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/86#discussion_r1093983380" expanded>

Is there any reason you put this here instead of making it a static class variable in Task?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/86#discussion_r1093984165" expanded>

Since this variable does not change, could make it a final constant and change the naming to be all caps
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/86#pullrequestreview-1280251211" expanded>

**Review Status:** COMMENTED

Overall code is very readable and understandable :)
</panel>

</panel>

<panel type="info" header="### 112. HO Z..LENN `@ghzr0` (14 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/77#discussion_r1092790136" expanded>

Good to separate the method into 2 lines to help with the user's readability
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/77#discussion_r1092801481" expanded>

Good coding standard for conditional statements , curly braces included
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/77#discussion_r1092802426" expanded>

Good coding standard for loops, curly braces included with proper indentation
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/77#discussion_r1092802887" expanded>

Proper naming method used for defining class and useful naming
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/77#pullrequestreview-1278467270" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/205#discussion_r1093225513" expanded>

Naming of  ' String[ ]  list  ' is quite vague, maybe if possible to provide a more useful name for readability? e.g. ' String [ ] taskList ' 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/205#discussion_r1093231605" expanded>

The naming of ' unmark' is a bit confusing, maybe switch to  ' taskToUnmark '?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/205#discussion_r1093237221" expanded>

Good indentation and presenting the conditional statements, which helps the code's readability.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/205#discussion_r1093246461" expanded>

Naming can be changed to avoid confusion down the code block, could change to  -&gt; e.g. 'static final String margin'  (since its a repeating string pattern to be printed out)
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/205#pullrequestreview-1279120901" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/205#pullrequestreview-1279130694" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/205#pullrequestreview-1279136490" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/205#pullrequestreview-1279148580" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/205#pullrequestreview-1279151983" expanded>

**Review Status:** COMMENTED

Commented about code's quality
</panel>

</panel>

<panel type="info" header="### 113. FOO ..ROME `@jeromeongithub` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/3#discussion_r1094535704" expanded>

I noticed that you used "magic numbers" like 4 (in this line) and 6 (in line 82). Perhaps you could try processing the inputs in a different way? Personally, I found the String.split() function to be very useful for doing so.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/3#discussion_r1094540358" expanded>

It looks like there are many levels of abstraction within your main function. Perhaps you could try to keep it at a single level of abstraction (SLAP)? I found the lecture example of Contacts1 to be very useful as reference to apply SLAP to my own work.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/3#discussion_r1094543219" expanded>

I think "errorMessage" would be better than "errorMsg" here as we are required to avoid 'texting-style' spelling.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/3#discussion_r1094559853" expanded>

Perhaps you could name "markTask" differently as a noun? The current naming makes it sound like a verb (mark the task) which is usually used to name methods.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/3#pullrequestreview-1281063833" expanded>

**Review Status:** COMMENTED

Great job overall! It was very easy to find things in your code, especially the methods because they were very explicitly named.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/155#discussion_r1093982733" expanded>

Perhaps use a verb name for the method?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/155#discussion_r1094501799" expanded>

I'm not too familiar with try-catch statements and could be wrong about this, but after comparing this particular try-catch statement to the others in your code, it stood out to me that you used "break;" twice (in line 80 and 84). Is there any reason why you did this differently from the other try-catch statements?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/155#discussion_r1094505697" expanded>

Great that you listed the imported classes explicitly.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/155#discussion_r1094507691" expanded>

Good job on using plural form for the name of this variable that represents a collection of objects.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/155#pullrequestreview-1280252799" expanded>

**Review Status:** COMMENTED

I think you did a great job!
</panel>

</panel>

<panel type="info" header="### 114. TAY ..YANG `@tyuyang` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/35#discussion_r1094055888" expanded>

Line 50 and line 51 can be split into 4 separate lines, computers with smaller aspect ratios cannot see line 51 on the same line.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/35#discussion_r1094066383" expanded>

Is printBoxBottomBorder() necessary? It has the same function as printBoxBottomBorder(false).
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/35#pullrequestreview-1280369687" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/212#discussion_r1094100680" expanded>

You may want to refactor the greeting and goodbye into another function instead of putting it all in main(). For example a void printGreeting() function that just prints the greeting
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/212#discussion_r1094102951" expanded>

There are no methods that uses taskNumber?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/212#discussion_r1094103621" expanded>

Can be refactored into print logo function, or you can combine it with the print greeting function
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/212#discussion_r1094108215" expanded>

You probably don't need this if clause. Instead, you can see if the input string contains "list", "mark", or "unmark", and create 3 separate switch cases for them. Even better, you can refactor this entire if else block into a function that parses the user input.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/212#discussion_r1094110408" expanded>

You can declare a constant for the row of underscores, or you can just create a function printLine to print the row of underscores. Also, you may want to use System.lineSeparator() instead of '\n' as recommended by the module.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/212#discussion_r1094113669" expanded>

Can be refactored into a separate function printTask(), since all tasks have the same format to be printed. In addition, depending on the situation, you may want to create a new function for each System.out.print() call, if you print the same thing multiple time. 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/212#pullrequestreview-1280417071" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 115. LIM ..RONG `@Zeno-Zr` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/32#discussion_r1092875843" expanded>

The final else should mean 'everything else', and not the final option here.
This will be useful for your level-4 requirements to sort which type of task is being entered.
The else statement can be used to catch errors and helpful for debugging.
https://nus-cs2113-ay2223s2.github.io/website/se-book-adapted/chapters/codeQuality.html#use-the-default-branch
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/32#discussion_r1092880043" expanded>

This can be refactored since it has been repeated a couple times in the code. It makes maintaining and editing changes much easier since you just need to edit it once.
https://nus-cs2113-ay2223s2.github.io/website/se-book-adapted/chapters/codeQuality.html#minimise-code-duplication
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/32#discussion_r1092884667" expanded>

This is a constant used throughout the code. Using a named constant will make it easier to maintain code since you just need to edit once for it to apply to rest of the code.
Something like "public static final String LINE_DIVIDER "______________________________"; " instead might be good.
https://nus-cs2113-ay2223s2.github.io/website/se-book-adapted/chapters/codeQuality.html#avoid-magic-numbers
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/32#discussion_r1092889180" expanded>

I like how the main execution path here is clear in your code. It makes tracing through your code much easier :)
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/32#pullrequestreview-1278594070" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/139#discussion_r1092856136" expanded>

The standard states the array specifiers must be attached to the type not the variable.
Might be good to change this to "String[] arr" instead.
https://se-education.org/guides/conventions/java/basic.html#types
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/139#discussion_r1092861197" expanded>

Minor issue but I think a space should be added between ) and {
So it looks like this: "public Deadline(String description) {"
This issue also appears in the rest of the code too.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/139#discussion_r1092863565" expanded>

I like the use of switch cases to denote clearly how the code flows :)
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/139#discussion_r1092865059" expanded>

Good job following the naming standards for all the methods (use of camelCase) :)
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/139#pullrequestreview-1278565588" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 116. CHEN..RALD `@Jeraldchen` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/4#discussion_r1092786419" expanded>

I like the use of constants instead of magic numbers!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/4#discussion_r1092787111" expanded>

I like the usage of a method for the printing of the '_' as it looks much neater.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/4#discussion_r1092787719" expanded>

You can consider reducing the amount of whitespaces between chunks of code.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/4#discussion_r1092789167" expanded>

I like the implementation of error checks to safeguard against invalid inputs!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/4#pullrequestreview-1278461967" expanded>

**Review Status:** COMMENTED

Overall looks good! 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/149#discussion_r1092792532" expanded>

Code nesting is neat and tidy.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/149#discussion_r1092792983" expanded>

I like the use of comments to clarify the methods functionality.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/149#discussion_r1092793369" expanded>

I like the implementation of input testing.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/149#discussion_r1092794093" expanded>

Perhaps adding a comment to explain what the "number" variable represents would be helpful to other readers.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/149#pullrequestreview-1278470637" expanded>

**Review Status:** COMMENTED

Great job overall!
</panel>

</panel>

<panel type="info" header="### 117. HUI ..CONG `@YC-Michael` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/159#discussion_r1095395498" expanded>

Good usage of constants with the uppercase naming
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/159#discussion_r1095405099" expanded>

.equals() if two objects have the same content while == checks if two objects (non-primitive data type) point to the same address 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/159#discussion_r1095405525" expanded>

Good nesting
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/159#discussion_r1095414189" expanded>

Avoid the use of complicated expression and try to split up the code into intermediate steps.
```suggestion
                Integer taskIndex = Integer.parseInt(commandByWord[1]);
                String messageToUser = tasks.mark(taskIndex);
                speak(messageToUser);
```
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/159#pullrequestreview-1282341779" expanded>

**Review Status:** COMMENTED

Overall, good encapsulation in Tasks class by limiting access to the taskList. Good naming and readability.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/208#discussion_r1095303737" expanded>

I like how you used a resizable array to store the tasks instead of a fixed size of 100. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/208#discussion_r1095340437" expanded>

Please follow the Java coding standards when using _exceptions_.
```suggestion
        try {
            Scanner scan = new Scanner(System.in)
```
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/208#discussion_r1095344647" expanded>

Good use of exceptions here
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/208#discussion_r1095350871" expanded>

variables such as start and end can be more descriptive.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/208#pullrequestreview-1282211202" expanded>

**Review Status:** COMMENTED

Overall, good naming and layout.
</panel>

</panel>

<panel type="info" header="### 118. CHNG..UANG `@L-K-Chng` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/58#discussion_r1092786933" expanded>

Note that there is no indentation for case clauses.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/58#discussion_r1092789387" expanded>

Do include explicit //Fallthrough comment whenever there is a case statement without a break statement
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/58#discussion_r1092790798" expanded>

Good job on adding error handling!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/58#discussion_r1092792449" expanded>

Good job splitting the line length to ensure it fits the required number of chars!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/58#pullrequestreview-1278462749" expanded>

**Review Status:** COMMENTED

Some minor errors with the case statement. But overall, great job!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/173#discussion_r1092803334" expanded>

Avoid magic strings, so perhaps for each of these cases, you can say for ex: LIST = "list" and reference the constant in the if statement
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/173#discussion_r1092804589" expanded>

Good indentation for switch statement and case clauses
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/173#discussion_r1092940932" expanded>

Perhaps you may want to split the line length to ensure it fits the required number of chars per line
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/173#discussion_r1092942590" expanded>

Good listing of imported classes!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/173#pullrequestreview-1278486430" expanded>

**Review Status:** COMMENTED

There are no major coding standard violations. Good job!
</panel>

</panel>

<panel type="info" header="### 119. EU Z..G XI `@euzhengxi` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/20#discussion_r1094167085" expanded>

magic number should be declared as constants
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/20#discussion_r1094167699" expanded>

it will be good to add in a "@Override" above the toString method
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/20#discussion_r1094168491" expanded>

good idea extracting the methods out of Duke
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/20#discussion_r1094169786" expanded>

consider creating a class to manage the inputs by the user rather than putting them under tasks. The purpose of the Task class is not to parse the input of the user
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/20#pullrequestreview-1280513521" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/114#discussion_r1094149992" expanded>

Constants are properly named
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/114#discussion_r1094150640" expanded>

in general, methods should start with a verb, eg: printGreetingMessage
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/114#discussion_r1094153945" expanded>

good attempt at abstracting the methods
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/114#discussion_r1094158071" expanded>

helpful comment on the 1 based indexing
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/114#pullrequestreview-1280489199" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 120. CHIA..XUAN `@chiayuxuan` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/19#discussion_r1093985657" expanded>

for constants, you may can use uppercase and public static final
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/19#discussion_r1093986171" expanded>

Can be more explicit about the usage of these variables.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/19#discussion_r1093986715" expanded>

Maybe you could create another class to handle print statements?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/19#discussion_r1093987004" expanded>

Very clean switch statements 👍
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/19#pullrequestreview-1280265454" expanded>

**Review Status:** COMMENTED

Keep up the good work!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/130#discussion_r1093978956" expanded>

Naming for constants looks good 👍
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/130#discussion_r1093980041" expanded>

Refactoring is done well.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/130#discussion_r1093981604" expanded>

count could be renamed to make it clear what it does? 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/130#discussion_r1093982725" expanded>

Nice personal touch!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/130#pullrequestreview-1280236746" expanded>

**Review Status:** COMMENTED

Keep up the Good job!
</panel>

</panel>

<panel type="info" header="### 121. SENT..IRAM `@sriram-senthilkr` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/38#discussion_r1093981450" expanded>

Perhaps you could save the line as a static variable outside the main function, so that the code looks cleaner whenever you add the line!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/38#discussion_r1093981766" expanded>

Correct coding standard when using switch cases! Good job!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/38#discussion_r1093983381" expanded>

Correct use of coding standards - not more than 120 characters per line! Good job!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/38#discussion_r1093983736" expanded>

Great that you only imported the classes you need, and not eveything! Good job!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/38#pullrequestreview-1280247235" expanded>

**Review Status:** COMMENTED

There were close to no coding standard violations. Some parts of the code could be refactored to make it more readable, but overall a good job!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/161#discussion_r1094027099" expanded>

Perhaps you could use a switch case so that it is easier when there are more commands?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/161#discussion_r1094029284" expanded>

Perhaps you could add a "Task" class to make your life simpler when there are more commands?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/161#discussion_r1094029993" expanded>

Great that you complied with all the coding standards!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/161#discussion_r1094033757" expanded>

Perhaps you could add in more comments before each "function" so that it is easier for you to keep track of what each function does?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/161#pullrequestreview-1280343504" expanded>

**Review Status:** COMMENTED

Generally well written code! Great that you complied with the coding standards! Good job!
</panel>

</panel>

<panel type="info" header="### 122. LEON..WENG `@leonghuenweng` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1092937628" expanded>

I like how you avoid writing long lines of code by transferring some code to the next line! It really improves the readability of your code
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1092951823" expanded>

Try to avoid multiple nested if conditionals whenever possible
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1092966254" expanded>

Good job for not using single character integers in your for-loop! a negative example would be 
for(int a=0;a&gt;tasks.length;a++){
...
}
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#discussion_r1092980738" expanded>

why do you have an extra pair of brackets? just curious
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/62#pullrequestreview-1278685959" expanded>

**Review Status:** COMMENTED

Overall very appropriate names were assigned, and code was highly readable!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/173#discussion_r1092854414" expanded>

_I like how you plan your exception handlers ahead before implementing them!_
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/173#discussion_r1092860415" expanded>

Looks good to me! The name "getStatusIcon" is concise and gives me a clear idea its function!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/173#discussion_r1092862399" expanded>

The cases here are handled well! no "Arrowhead style code", good job
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/173#discussion_r1092865015" expanded>

perhaps this function can just be named as "printLine"?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/173#pullrequestreview-1278562974" expanded>

**Review Status:** COMMENTED

In general everything looks good!
</panel>

</panel>

<panel type="info" header="### 123. MUST..SAIN `@MustafaAH10` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/104#discussion_r1092873819" expanded>

Can consider combining the markAsDone and markAsUndone function if you want by editing the earlier changeTaskStatus function.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/104#discussion_r1092874913" expanded>

Can consider making this main function into a switch-case function to make it more intuitive.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/104#discussion_r1092875792" expanded>

I like how you combined the condition for "mark" and "unmark".
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/104#discussion_r1092878631" expanded>

Good refactoring of code to extract this method that has an easy to understand name. 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/104#pullrequestreview-1278590965" expanded>

**Review Status:** COMMENTED

Overall, code is of good quality and very readable, good job
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/202#discussion_r1092861660" expanded>

userCmdasWords is a bit confusing to reader.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/202#discussion_r1092862914" expanded>

Can be taskCount instead of tasksCount to follow naming convention.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/202#discussion_r1092863712" expanded>

Boolean name is good as status is intuitive.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/202#discussion_r1092865559" expanded>

Can consider combining markTask and unmarkTask into one function.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/202#pullrequestreview-1278573433" expanded>

**Review Status:** COMMENTED

Code is overall of good quality and has minimal errors.
</panel>

</panel>

<panel type="info" header="### 124. NICH..OWEN `@nicholas132000` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/155#discussion_r1094179380" expanded>

You could perhaps shorten this main method by using the extract method refactoring so that it would be easier for you to debug. Perhaps extract methods for each input command.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/155#discussion_r1094188168" expanded>

Good job with this if else statement, it looks readable. Perhaps you could remove the else condition, since once you enter the if condition, the control returns at the end of the if statement and exits this method, therefore there is no need to add the else
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/155#discussion_r1094192618" expanded>

Good job, readable and short and succinctly written class, with good use of @Override keyword to tell the reader that this method is overridden 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/155#discussion_r1094197322" expanded>

Good job for of setting a default condition when all other cases are not met, allows the user to know what command inputs are invalid
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/155#pullrequestreview-1280532541" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/213#discussion_r1094146351" expanded>

Consistent 4 spaces indent throughout the code, good job
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/213#discussion_r1094148618" expanded>

Perhaps you try using camelcase when naming variables. Eg. listOfTasks
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/213#discussion_r1094152357" expanded>

Perhaps you could name this class as "Task" (singular) instead as it refers to one task
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/213#discussion_r1094154595" expanded>

Good job for using a verb to name this method
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/213#pullrequestreview-1280483415" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 125. CALE..A LE `@calebcjl` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/23#discussion_r1094622746" expanded>

Would using prefix "is" make your boolean clearer?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/23#discussion_r1094630586" expanded>

"No" may be confusing. I would suggest "num" or "number"
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/23#discussion_r1094642689" expanded>

Great use of switch and SLAP
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/23#discussion_r1094643388" expanded>

Is there a reason why you do not set the default to help() ?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/23#pullrequestreview-1281197390" expanded>

**Review Status:** COMMENTED

Great code quality overall! I hope my comments will be beneficial to you
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/164#discussion_r1094392764" expanded>

Renaming the array to _tasks_ instead of _listOfInputs_ may give readers better understanding of its array type (array of class task)
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/164#discussion_r1094394644" expanded>

Using switch statement could enhance readability
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/164#discussion_r1094405019" expanded>

Variable name may be confusing since it contains Java reserved word "final"
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/164#discussion_r1094410405" expanded>

Another option is to use trim() to remove trailing spaces
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/164#pullrequestreview-1280852787" expanded>

**Review Status:** COMMENTED

Great job following the coding standard! Next thing you could do is to refactor your code to further increase its readability.
</panel>

</panel>

<panel type="info" header="### 126. DENN..KANG `@dendendenden04` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/31#discussion_r1092759123" expanded>


Seems like an issue with indentation after the changes as the cases for the switch statement are indented afterwards. Can you verify?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/31#discussion_r1092763879" expanded>

Inconsistent naming of variable, new task is named as "task" while for new deadlines and new event it is named as "event".
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/31#discussion_r1092764085" expanded>

Good job for wrapping long lines around.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/31#discussion_r1092795240" expanded>

Do you think that you should add underscore for this constant variable.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/31#pullrequestreview-1278423421" expanded>

**Review Status:** COMMENTED

Hello there.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/31#pullrequestreview-1278474486" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/139#discussion_r1092943759" expanded>

Maybe there is no need to shorten the variable name to keep readability?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/139#discussion_r1092945399" expanded>

Should this boolean variable sound like a boolean? Eg. canExit etc.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/139#discussion_r1092952729" expanded>

Is the `taskcounter` variable following the camelCase format?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/139#discussion_r1092960450" expanded>

It is good that the switch cases are there to enhance readability. However, maybe you can abstract out each case so that this section of the code is not too long?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/139#pullrequestreview-1278694643" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 127. THAN..NYAN `@thant` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/46#discussion_r1093978272" expanded>

Looks good! Great use of parser class to create a generalized input processor :)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/46#discussion_r1093979981" expanded>

Neat indentation and comments :D
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/46#discussion_r1093980557" expanded>

Nice usage of variable naming to indicate the boolean condition for keeping the program running
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/46#discussion_r1093981504" expanded>

Good capitalization on naming!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/46#pullrequestreview-1280233976" expanded>

**Review Status:** COMMENTED

Overall the code was extremely well-structured as well as clean. No major coding violations were identified, and there does not seem to be noticeable logical flaws or naming violations.

LGTM
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#discussion_r1093983903" expanded>

Capitalization and choice of name was good!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#discussion_r1093990688" expanded>

Perhaps could consider a default value for isDone boolean
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#discussion_r1093991268" expanded>

Nice definition here makes overall code clean!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#discussion_r1093991510" expanded>

Perhaps should be named greet() instead
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#pullrequestreview-1280257781" expanded>

**Review Status:** COMMENTED

Promising start to the iP, with a few neat tricks used to make overall code clean and tidy! Will be looking forward to seeing how the code develops with further increments :)
</panel>

</panel>

<panel type="info" header="### 128. GOH ..ARON `@GohJW` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/9#discussion_r1094126264" expanded>

Perhaps these lines of code can be implemented in the addDeadline() method to improve readability. Similarly for the case "event" below.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/9#discussion_r1094130025" expanded>

Good job extracting methods for easier readability
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/9#discussion_r1094132264" expanded>

Good use of an IO class to differentiate methods for inputs and printing.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/9#discussion_r1094134404" expanded>

Good job using line breaks in order to prevent long lines of code.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/9#pullrequestreview-1280454188" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/144#discussion_r1094067628" expanded>

Perhaps the use of named constants such as EVENT_COMMAND_LENGTH rather than magic numbers such as 2 or 3 for better understanding on what you are comparing to.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/144#discussion_r1094113483" expanded>

Good use of indentation on your comments to indicate which part of code you are specifying.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/144#discussion_r1094116813" expanded>

Method should be in camelCase printBorder()
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/144#discussion_r1094121733" expanded>

Good code formatting, allows for easy readability.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/144#pullrequestreview-1280380046" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 129. LIM ..RREN `@darrenlsx` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/89#discussion_r1094298215" expanded>

I like how all the naming of the functions were easily understandable.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/89#discussion_r1094301225" expanded>

I like how you used a switch to make it clear and readable.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/89#discussion_r1094305510" expanded>

Neat and clean use of SLAP
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/89#discussion_r1094313380" expanded>

Perhaps in the function name can add a noun after initialize to know what are we initializing
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/89#pullrequestreview-1280705096" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/102#discussion_r1094017643" expanded>

I like how the functions are easy to understand and it follows the Code Quality naming standards.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/102#discussion_r1094018199" expanded>

I like how the while loop and if else statements are neat.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/102#discussion_r1094276698" expanded>

I like how you explicitly stated which imported class you needed
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/102#discussion_r1094282501" expanded>

I like how the array specifiers are attached to the type not the variable.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/102#pullrequestreview-1280336384" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/102#pullrequestreview-1280676742" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 130. WILS.. WEI `@WilsonLee2000` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/6#discussion_r1095539392" expanded>

I like how you have implemented the "if", "else if" and "else" in such a way that it maximises readability and makes your code easier for audiences to read! :)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/6#discussion_r1095564480" expanded>

I like how you named multi-valued variables using a plural term as it allows readers to distinguish clearly between single-valued and multi-valued variables.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/6#discussion_r1095568511" expanded>

Perhaps there is not a need for the space (line 10) to be here?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/6#discussion_r1095574977" expanded>

I really like how you only import the relevant libraries that are needed! Instead of using * import!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/6#pullrequestreview-1282590003" expanded>

**Review Status:** COMMENTED

Overall, well done on your code quality! I'm really impressed! Just a minor additional spacing issue, kindly refer to one of my comments. :)
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/12#discussion_r1095304166" expanded>

Perhaps you can try adding a space between "if" and "(" ?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/12#discussion_r1095304340" expanded>

Perhaps you can try adding a space between "else" and "{" ?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/12#discussion_r1095366267" expanded>

I like how you add a space after every countructor/objects in this class, this makes code-reading easier for audiences like me! :)
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/12#discussion_r1095367752" expanded>

I like how you followed the naming conventions where Names representing methods must be verbs and are written in camelCase. Keep up the good work! :)
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/12#pullrequestreview-1282211777" expanded>

**Review Status:** COMMENTED

Overall, I like how your code is being implemented and there is only very few and minor violations of coding standards
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/12#pullrequestreview-1282299599" expanded>

**Review Status:** COMMENTED

Once again, good job on the naming conventions and the spacing after every counstructor/objects in the class. Just some few minor indentation issues which I have specified in my previous comment :)
</panel>

</panel>

<panel type="info" header="### 131. ANG ..RREN `@darrenangwx` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/52#discussion_r1092847158" expanded>

I like the use of easy to understand variable names
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/52#discussion_r1092852176" expanded>

Perhaps you can look into using the auto formatting feature in Intellj to standardise the spaces after the curly brackets.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/52#discussion_r1092854834" expanded>

I would like if there are JavaDoc styled comments on your methods so I am able to understand your code better.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/52#discussion_r1092855301" expanded>

I like the correct usage of camelCase in variables and method names while PascalCase is used in Class names.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/52#pullrequestreview-1278552509" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/204#discussion_r1092860851" expanded>

Perhaps you can look into using the auto formatting feature in Intellij to standardise the spaces after the curly brackets.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/204#discussion_r1092861413" expanded>

Perhaps look into using an ArrayList might be better? It allows the array to be dynamically sized.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/204#discussion_r1092862021" expanded>

I feel that using a switch statement might make the code cleaner and easier to read. 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/204#discussion_r1092862943" expanded>

Good job on using UPPERCASE for constants. 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/204#pullrequestreview-1278572303" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 132. CHUA.. WEI `@pinyoko573` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/121#discussion_r1092867247" expanded>

good use of functions to separate codes (instead of everything in main)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/121#discussion_r1092882188" expanded>

You can have a print function in your sub classes to make your code shorter : )
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/121#discussion_r1092883305" expanded>

Try to have spacing between each functions for clearer readability : D
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/121#discussion_r1092883954" expanded>

Great use of polymorphism!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/121#pullrequestreview-1278582265" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/133#discussion_r1092862923" expanded>

Try to divide the lines of code for easy readability
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/133#discussion_r1092863080" expanded>

good to autoindent whenever you're done coding (:
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/133#discussion_r1092863577" expanded>

better to use strings that you are constantly using (e.g. underline) into a new variable
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/133#discussion_r1092863853" expanded>

good to use functions instead of everything in one main (like one for converting substrings)
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/133#pullrequestreview-1278575235" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 133. PANG.. JIE `@pyongjie` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/91#discussion_r1093978251" expanded>

Perhaps a more intuitive method name here?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/91#discussion_r1093981783" expanded>

I like how you adhere to camelCase and verbs usage when naming methods
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/91#discussion_r1093982142" expanded>

I like how you adhere to camelCase when naming variables
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/91#discussion_r1093985415" expanded>

I like how you adhere to using uppercase and underscore to separate words when naming constants
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/91#pullrequestreview-1280233871" expanded>

**Review Status:** COMMENTED

Overall, I found your code easy to read and understand. Almost all parts of the codes have met the coding standards except for one minor issue.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/120#discussion_r1094525403" expanded>

Perhaps a constant could be introduced for the number 100 to avoid magic numbers?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/120#discussion_r1094530363" expanded>

Should this be extracted out as a print welcome message method to avoid long methods?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/120#discussion_r1094533558" expanded>

I like how you avoided complicated expressions in your code
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/120#discussion_r1094553910" expanded>

I like how variables and methods are named well which improves the readability of the code and reduces bugs
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/120#pullrequestreview-1281046328" expanded>

**Review Status:** COMMENTED

Overall, I found your code relatively easy to read and understand. Most parts of the code do adhere to code quality guidelines with the exception of a few minor issues.
</panel>

</panel>

<panel type="info" header="### 134. GAN ..YANG `@Gan868611` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/86#discussion_r1094061928" expanded>

would suggest making a function for each case "todo, event,deadline" for better readability
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/86#discussion_r1094063736" expanded>

clean and neat method to split the args😁
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/86#discussion_r1094068506" expanded>

I would suggest using switch and case to avoid magic literal like "mark", " event". Can use variables like `command` and check against it.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/86#discussion_r1094071501" expanded>

is `unmarkDone()` a better naming?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/86#pullrequestreview-1280374972" expanded>

**Review Status:** COMMENTED

Good Coding Standard!😁
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/175#discussion_r1094074442" expanded>

would suggest a quick function `printHorizontalLine()` since this is a frequently used line
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/175#discussion_r1094075803" expanded>

list is a bit ambiguous, would suggest using name like `tasks` or `tasksList`
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/175#discussion_r1094107130" expanded>

consider using regex to split the string easier `splitIntoArgs[1].split(" \\/(from|to) ");`
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/175#discussion_r1094110905" expanded>

do you think implementing "bye" and "list" in Duke.java is a better option so you dont have to pass the Task[] around?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/175#pullrequestreview-1280386435" expanded>

**Review Status:** COMMENTED

Good code quality !😁
</panel>

</panel>

<panel type="info" header="### 135. BENJ.. TOH `@bentohset` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/43#discussion_r1094034272" expanded>

I like how your main function is short and sweet! Good use of OOP
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/43#discussion_r1094037485" expanded>

I like how the method is easy to read and understand.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/43#discussion_r1094038472" expanded>

The variable index is abit confusing as to what it refers to. Would it be better to give it another name?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/43#discussion_r1094041894" expanded>

I like how you abstracted the print methods into separate methods. Makes the code look cleaner
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/43#pullrequestreview-1280349522" expanded>

**Review Status:** COMMENTED

The quality of the code is of excellent quality! Looking forward to see what your project has in store
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/167#discussion_r1093982562" expanded>

Using x as an iterator is rather confusing, would it be better if you used i, j, k standards?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/167#discussion_r1093983227" expanded>

Would it be better if you declared the line -------- as a global variable? I think it would reduce repeated codes!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/167#discussion_r1093983795" expanded>

I like how you structured your if else statements and naming standards, makes it easier to read and understand.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/167#discussion_r1093984724" expanded>

I like your logo! The formatting of the code makes it easier to see the logo.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/167#pullrequestreview-1280251978" expanded>

**Review Status:** COMMENTED

Good job on your project so far minus a few slip ups! Looking forward to review your project again.
</panel>

</panel>

<panel type="info" header="### 136. POOB..SHMI `@PoobalanAatmikaLakshmi` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/129#discussion_r1094066625" expanded>

Good job on making your case statement readable with proper indentation!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/129#discussion_r1094099042" expanded>

I think your main method can be shorter by printing the greeting in another method perhaps? 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/129#discussion_r1094126758" expanded>

Good job on having a single level of abstraction most of the time! 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/129#discussion_r1094129201" expanded>

Good job on your naming!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/129#pullrequestreview-1280379168" expanded>

**Review Status:** COMMENTED

Overall your code is really well segmented!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/148#discussion_r1094057706" expanded>

Good job on using camelCase for all your variable naming!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/148#discussion_r1094060305" expanded>

Good job on not having indentation for case statements 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/148#discussion_r1094061901" expanded>

Good job on wrapping your for loops with curly braces although it is a single statement! 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/148#discussion_r1094063139" expanded>

Good job on using plural name compileItems to represent a collection of objects! 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/148#pullrequestreview-1280371333" expanded>

**Review Status:** COMMENTED

Overall your code is really good!
</panel>

</panel>

<panel type="info" header="### 137. TIAN..XING `@tsx0314` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/40#discussion_r1092779710" expanded>

I think perhaps you can avoid deep-nesting
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/40#discussion_r1092785028" expanded>

I like how you name all constants with capital letter words.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/40#discussion_r1092787327" expanded>

I like how you use verbs to start a method and also use camelCase
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/40#discussion_r1092787866" expanded>

I like how you pay attention to the coding format
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/40#pullrequestreview-1278452535" expanded>

**Review Status:** APPROVED

Overall I found your code is easy to read and follows the coding standard but there are places where the nesting is too deep. You may consider breaking it down into smaller parts.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/95#discussion_r1092946035" expanded>

the code is easy to read but perhaps you may try to avoid deep nesting!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/95#discussion_r1092955911" expanded>

You may put these functions within their respective Class!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/95#discussion_r1092957451" expanded>

I like how you pay attention to using camelCase!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/95#discussion_r1092981045" expanded>

I like the naming of constant variables with all capital letters 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/95#pullrequestreview-1278697839" expanded>

**Review Status:** APPROVED

Overall is good! The code is easy to read and I like the namings and the layout. However, you may consider moving the methods within the Duke class into other classes as well to make the code clearer!
</panel>

</panel>

<panel type="info" header="### 138. GOH ..XUAN `@yixuann02` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/22#discussion_r1094066065" expanded>

Perhaps you could consider using switch and case for these if-else statements.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/22#discussion_r1094066811" expanded>

Try to avoid deep nesting by splitting it into different methods
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/22#discussion_r1094071361" expanded>

Good job using multiple methods to make the main readable
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/22#discussion_r1094073408" expanded>

You did a good job with keeping most of the methods short and readable
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/22#pullrequestreview-1280378653" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/212#discussion_r1094049834" expanded>

Perhaps you could list the imported classes explicitly
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/212#discussion_r1094055249" expanded>

```suggestion
public class Duke {
```
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/212#discussion_r1094059330" expanded>

Perhaps you can change your constant names to be all uppercase using underscore to separate words
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/212#discussion_r1094062448" expanded>

I think you did a good job indenting wrapped lines.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/212#pullrequestreview-1280364530" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 139. TAY ..YUAN `@TayJiunYuan` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/64#discussion_r1094060932" expanded>

Perhaps use a more specific term rather than "words"
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/64#discussion_r1094061546" expanded>

Perhaps comment what this for loop does so that it is easier to follow.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/64#discussion_r1094063921" expanded>

Perhaps keep the line spacings consistent, ie. there are line spacings in some files but none in others.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/64#discussion_r1094065306" expanded>

Perhaps use currentTask instead of task as it is confusing between the object task and class Task.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/64#pullrequestreview-1280374116" expanded>

**Review Status:** COMMENTED

Overall readable and organised code, good job!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/109#discussion_r1093982928" expanded>

The variable name keyword is a little vague, perhaps change it to something that indicate what this variable holds?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/109#discussion_r1093984462" expanded>

Perhaps it may be easier to see each function if you added a new line in between, but it is personal preference.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/109#discussion_r1093985690" expanded>

Perhaps add a new line after the imports
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/109#discussion_r1093986538" expanded>

Perhaps change the start and end variable names to something more specific, like startTime.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/109#pullrequestreview-1280253706" expanded>

**Review Status:** COMMENTED

Overall, good use of coding standards with little to no violations. Very readable and easy to follow.
</panel>

</panel>

<panel type="info" header="### 140. JAVI.. MYN `@javienneyeo` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/30#discussion_r1094143809" expanded>

good that the indentation is correct, like there is no indentation for case clauses
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/30#discussion_r1094144515" expanded>

good that the naming conventions are correctly followed
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/30#discussion_r1094147963" expanded>

good that curly brackets are used despite having only one statement
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/30#discussion_r1094149540" expanded>

good that k&r style brackets are used
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/30#pullrequestreview-1280479596" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/144#discussion_r1094156268" expanded>

good that the methods are named in a way that it is easy to know what they do
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/144#discussion_r1094157793" expanded>

this method is a little long, exceeding more than 30 lines of code
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/144#discussion_r1094159079" expanded>

good that the code is easily readable
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/144#discussion_r1094161598" expanded>

good that the methods and variables are named properly that clearly shows the intent of it
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/144#pullrequestreview-1280497233" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 141. IRVI..BOER `@irving11119` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/145#discussion_r1094054142" expanded>

Perhaps you could include full documentation (following the Javadoc comments standard) for your class methods beyond just using inline comments.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/145#discussion_r1094055120" expanded>

Should this method be named `setIsDone` since it is a setter for the `isDone` class variable?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/145#discussion_r1094058720" expanded>

I like how you chose explicitly which package from `java.util` rather than using a generic import. 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/145#discussion_r1094062050" expanded>

I think you did a good job at following the naming conventions for variable, class and method names.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/145#pullrequestreview-1280368257" expanded>

**Review Status:** COMMENTED

I think your code quality overall is fairly decent and you follow naming conventions well. However, do consider adding in documentation for your methods based on the Javadoc comments standards. 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/192#discussion_r1094070451" expanded>

Perhaps you can consider how to abstract your main method into various different methods as currently it is rather lengthy (Greater than 30 LOC).
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/192#discussion_r1094073063" expanded>

You might want to consider declaring these variables as constants instead as they are they do not need to change.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/192#discussion_r1094074578" expanded>

Perhaps you could include a default branch for your switch block so in the case where your command is not caught by any of the case statements, your code will still function.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/192#discussion_r1094077463" expanded>

I think you did a good job at making your method names simple yet descriptive. This makes it easy to follow the program flow. 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/192#pullrequestreview-1280382716" expanded>

**Review Status:** COMMENTED

I think your code quality is fairly decent. However, you can look at abstracting your main method using other methods or classes to make it shorter. Also you should be careful of your lack of a default statement for your switch case as it might create exceptions which your program might not be able to handle.
</panel>

</panel>

<panel type="info" header="### 142. OH Y..LSON `@WilsonOh` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/83#discussion_r1092787743" expanded>

Use camelCase naming instead of snake_case for variables.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/83#discussion_r1092789632" expanded>

Inconsistent naming; breakingPoint uses camelCase while breakingPoint_1 is in mixed casing.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/83#discussion_r1092789854" expanded>

Correct naming style for constants.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/83#discussion_r1092792145" expanded>

Proper indent width and bracket style.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/83#pullrequestreview-1278463899" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/94#discussion_r1092797417" expanded>

Good naming for boolean value, shows purpose of the variable clearly.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/94#discussion_r1092798182" expanded>

Good use of constants.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/94#discussion_r1092799271" expanded>

There's some repetition here i.e. printDivider() -&gt; sysout something -&gt; printDivider(). Might be good to extract this pattern out to a method.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/94#discussion_r1092799579" expanded>

Clear and readable method names which does exactly what the name suggests.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/94#pullrequestreview-1278477702" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 143. JU C.. CAN `@Ju-Can` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/42#discussion_r1094080584" expanded>

Good use of comments to explain the inputs and outputs of the Class
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/42#discussion_r1094087329" expanded>

Printing of separation line is used multiple times. It would be better to define the line as a static final literal for reusability.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/42#discussion_r1094089218" expanded>

Good use of error catching.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/42#discussion_r1094091856" expanded>

Instead of comments, it may be better to consider adding information to the variable name itself eg. startTime for more readability.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/42#pullrequestreview-1280392591" expanded>

**Review Status:** COMMENTED

In general the code follows good coding quality.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/97#discussion_r1094069257" expanded>

It may be a good practice to avoid magic number / literal and rename as static literal instead.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/97#discussion_r1094071754" expanded>

Naming of variable 'i' can be confusing to readers. May be better to choose names that describe the variable in more detail.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/97#discussion_r1094074375" expanded>

What exactly 'index' is referring to can be confusing. More description would be helpful
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/97#discussion_r1094078540" expanded>

nested conditions may not be intuitive to readers
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/97#pullrequestreview-1280381558" expanded>

**Review Status:** COMMENTED

In general the code follows good coding standard. Minor naming issues related to code quality.
</panel>

</panel>

<panel type="info" header="### 144. ONG .. KAI `@ong-ck` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/54#discussion_r1094146043" expanded>

I think this is a very clean way to print the start messages, and keeps the main method clean
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/54#discussion_r1094147539" expanded>

This is a good name for the method, it explains the method's use very well
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/54#discussion_r1094148803" expanded>

Good use of the plural word to name an array
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/54#discussion_r1094152035" expanded>

Good K&R style brackets for your if-else statements!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/54#pullrequestreview-1280482953" expanded>

**Review Status:** COMMENTED

On overall, I think your code is generally very easy to read and is rather clean. There are many instances of good code standards found in your code. Good job!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/79#discussion_r1094158328" expanded>

Good use of an interface!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/79#discussion_r1094161208" expanded>

Perhaps it might be good to delete the dead code here
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/79#discussion_r1094161745" expanded>

Good use of a ternary operator to keep the code clean!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/79#discussion_r1094162422" expanded>

Good use of switch statements to prevent nesting too deep
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/79#pullrequestreview-1280500277" expanded>

**Review Status:** COMMENTED

On overall, I think you code quality is of a very good standard and have many instances of good and clean code. Good job!
</panel>

</panel>

<panel type="info" header="### 145. LIU ..AOGE `@xiaoge26` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/18#discussion_r1094054517" expanded>

Perhaps you may want to remove the extra blank lines.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/18#discussion_r1094058051" expanded>

Your code is very neat! I like how you formatted the if-else statements.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/18#discussion_r1094060963" expanded>

No coding standard violation! Good job on naming the variables using camelCase :D
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/18#discussion_r1094061889" expanded>

Maybe you can change the class name to TransformString.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/18#pullrequestreview-1280368576" expanded>

**Review Status:** COMMENTED

Overall, a very good job! Only one coding standard violation was spotted!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/156#discussion_r1094070834" expanded>

I like how you name your methods. They are easy to read and understand!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/156#discussion_r1094073397" expanded>

Perhaps you can also name the method as setDone() or setUndone().
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/156#discussion_r1094075822" expanded>

You may want to move the else clause up to the previous line to comply with the coding standard.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/156#discussion_r1094080091" expanded>

Your code has a consistent and reasonable level of abstraction. I like it!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/156#pullrequestreview-1280383075" expanded>

**Review Status:** COMMENTED

Overall, a great job! The code quality is quite good. It would be better if the if-else statements can be reformatted.
</panel>

</panel>

<panel type="info" header="### 146. SEBA..ANTO `@SebastianSoewanto` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/11#discussion_r1093713034" expanded>

else if block could be placed in the same line as above 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/11#discussion_r1093715015" expanded>

concise use of java class
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/11#discussion_r1093719279" expanded>

comments can be indented above the line relative to its position
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/11#discussion_r1093721359" expanded>

good import of classes
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/11#pullrequestreview-1279840090" expanded>

**Review Status:** COMMENTED

Overall nice and neat layout. Good Job!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/36#discussion_r1092786513" expanded>

Very neat format and naming style 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/36#discussion_r1092787591" expanded>

very concise use of ternary operator
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/36#discussion_r1092788524" expanded>

Good implementation of class
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/36#discussion_r1092791584" expanded>

Suggest to include the comment together above to explain the function together 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/36#pullrequestreview-1278462123" expanded>

**Review Status:** COMMENTED

Good job on the overall organization of your code!
</panel>

</panel>

<panel type="info" header="### 147. KIM .. WON `@coregano` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/5#discussion_r1094369819" expanded>

Slight inconsistency in the use of assignment operators (=) throughout the code.
I recommend following the standard set by Intellij. 
By using the command Ctrl + Alt + L, you can instantly standardise the formatting throughout your code.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/5#discussion_r1094374797" expanded>

This line is rather long and may be difficult to read and debug. Maybe by calling a method to check for this boolean statement, it will help to shorten and simplify the code, making it more readable. 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/5#discussion_r1094382546" expanded>

I recommend using K&R style brackets (aka [Egyptian style]) for your loop statements, as instructed by professor Akshay.
I recommend that you follow the coding convention list 
(https://se-education.org/guides/conventions/java/basic.html) 
and setting your IDE's code style to match what is recommended so as to have an easier time formatting your code.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/5#discussion_r1094400626" expanded>

I have realised that your "event" and "deadline" codes do not check if the input has the keywords "from" + "to", and "by" respectively. I believe that this may lead to certain cases where it incorrectly processes inputs from the user. 
As such, I recommend using string methods such as String.matches() or String.indexOf() so as to check for the relevant keywords, and I believe that this would greatly strengthen your code's ability to handle edge cases/ different inputs.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/5#pullrequestreview-1280819423" expanded>

**Review Status:** COMMENTED

Code is generally well written with proper naming conventions done. 
Slight issues in code formatting, such as spacing and bracket style.
Handling of edge cases could be improved.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/74#discussion_r1094412505" expanded>

I realised that your "mark" and "unmark" commands do not check if the string after whitespace is convertable to type Integer. I believe that this may bring up an error if the user were to input in a command "mark qwerty", as "qwerty" cannot be passed into the method Integer.parseInt(). I recommend using a method to check for the formatting of the command first, such as String.matches() or even a try-catch statement. 
I believe that this would greatly strengthen the ability of your code to handle such edge cases.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/74#discussion_r1094418270" expanded>

I recommend executing the command String.trim() before using String.split(), as it would account for cases where the user has inputted whitespace(s) before the actual non-whitespace text. 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/74#discussion_r1094421438" expanded>

I recommend standardising between input.equals() and input.equalsIgnoreCase() for bye and other commands, so as to make the code easier to understand and debug incase an error arises during testing.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/74#discussion_r1094425872" expanded>

Using two resizable arrays may affect runtime and make it harder to code as there needs to be constant linkage between the two items in each array. Although it may seem simple now, this will become much harder to maintain when you have more methods being implemented into your code in the future, such as deleting and moving items along the list. Hence, I believe that creating a separate class Task may benefit the code and yourself greatly.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/74#pullrequestreview-1280881605" expanded>

**Review Status:** COMMENTED

Well-written and clean code with high readability. 
Could be improved on the handling of edge cases.
</panel>

</panel>

<panel type="info" header="### 148. TAN .. LIN `@T-Wan-Lin` (16 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/85#discussion_r1094070074" expanded>

Your main method is very short and succinct! Keep it up!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/85#discussion_r1094070648" expanded>

Perhaps you could provide some documentation to summarise the role of this method for better readability
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/85#discussion_r1094071064" expanded>

Perhaps you could have a more descriptive variable name like "placeholder' to describe the role of this variable better.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/85#discussion_r1094071604" expanded>

Good job, there are little violations in the classes!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/85#pullrequestreview-1280376995" expanded>

**Review Status:** COMMENTED

Perhaps you can have a more descriptive name for the variable "tempPos" to reflect its role in the code.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/85#pullrequestreview-1280379037" expanded>

**Review Status:** COMMENTED

Perhaps you can have a more descriptive name for the variable "tempPos" to reflect its role in the code.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/85#pullrequestreview-1280379692" expanded>

**Review Status:** COMMENTED

Perhaps you can have a more descriptive name for the variable "tempPos" to reflect its role in the code.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/85#pullrequestreview-1280382338" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#discussion_r1094053323" expanded>

Instead of naming this boolean as 'marked', try to use a more descriptive name to sound more like a boolean. For example, you could rename it as 'isMarked'.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#discussion_r1094056563" expanded>

Good job on following the naming standard for Java packages! Keep it up!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#discussion_r1094058149" expanded>

Good job on following the K&R style brackets! Keep it up!
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#discussion_r1094059596" expanded>

Perhaps you could shift this else statement up by one line to follow coding standards
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#pullrequestreview-1280367540" expanded>

**Review Status:** COMMENTED

Instead of naming this boolean as 'marked', try to use a more descriptive name to sound more like a boolean. For example, you could rename it as 'isMarked'.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#pullrequestreview-1280370235" expanded>

**Review Status:** COMMENTED

Good job on following the naming standard for Java packages! Keep it up!
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#pullrequestreview-1280371693" expanded>

**Review Status:** COMMENTED

Good job on following the naming standard for Java packages! Keep it up!
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/162#pullrequestreview-1280372985" expanded>

**Review Status:** COMMENTED

Perhaps you could shift this else statement up by one line to follow coding standards
</panel>

</panel>

<panel type="info" header="### 149. GRAC..G YU `@GraceZhuXY` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/84#discussion_r1093983435" expanded>

Great use of constants instead of magic numbers!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/84#discussion_r1093984852" expanded>

it's nice that the unknown command is the last case, which makes the happy path prominent
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/84#discussion_r1093985306" expanded>

I think the method names are already descriptive enough 👍, these comments (for printf too) may be redundant
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/84#discussion_r1093986135" expanded>

the loops have simple indentation which makes them readable and easy to follow!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/84#pullrequestreview-1280255884" expanded>

**Review Status:** COMMENTED

Amazing work! 👍
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/131#discussion_r1093976026" expanded>

It might be better to use the variable name "isDone" instead of "done" (if it does not clash with your other booleans)
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/131#discussion_r1093978804" expanded>

Your function names are very easy to understand 👍
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/131#discussion_r1093979159" expanded>

Your line lengths are kept short (well within the soft limit of 110 chars), nice!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/131#discussion_r1093981754" expanded>

all your loops and conditionals follow the coding standards, which makes it smooth to read 👍
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/131#pullrequestreview-1280223807" expanded>

**Review Status:** COMMENTED

Great job!
</panel>

</panel>

<panel type="info" header="### 150. TAN ..I XI `@tzixi` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/58#discussion_r1092865689" expanded>

I think it might be better to use ArrayList here
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/58#discussion_r1092866333" expanded>

Good job using the limit of 2 to split the input into "command" and "description"
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/58#discussion_r1092867073" expanded>

Good use of camelcase naming convention for get method
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/58#discussion_r1092868223" expanded>

I like the placing of methods before the switch cases to make the switch cases more readable
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/58#pullrequestreview-1278579190" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/111#discussion_r1092860860" expanded>

I think using ArrayList might be better here
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/111#discussion_r1092861317" expanded>

I like the camelcase naming convention
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/111#discussion_r1092862305" expanded>

I think it might be better to combine into one line eg: System.out.println(HORIZONTAL_LINE + "\ncomment\n" + HORIZONTAL_LINE)
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/111#discussion_r1092863865" expanded>

This could include the brackets so that you dont need to put the brackets on line 53, eg: isDone ? "[X]" : "[  ]"
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/111#pullrequestreview-1278572315" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 151. RICH..AWAN `@Richardtok` (16 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/37#discussion_r1094147588" expanded>

You could have made a class for Task. Why did you do it this way instead of making a class?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/37#discussion_r1094148118" expanded>

Why did you choose to do it this way, why not make a class for todo?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/37#discussion_r1094153606" expanded>

WHy did you do it this way why not create a class for event?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/37#discussion_r1094156820" expanded>

I like what you have done as the description of what the bot can do is very clear!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/37#pullrequestreview-1280485209" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/37#pullrequestreview-1280485976" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/37#pullrequestreview-1280494115" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/37#pullrequestreview-1280498049" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/97#discussion_r1094446529" expanded>

Why not make the whole print into a single line to keep it clear?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/97#discussion_r1094447827" expanded>

The use of the word I in this context is confusing as the readers would not know what i is representing
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/97#discussion_r1094449305" expanded>

I like that for new events you use new class for readability of the main code
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/97#discussion_r1094454163" expanded>

The coding standard is good
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/97#pullrequestreview-1280932400" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/97#pullrequestreview-1280934837" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/97#pullrequestreview-1280936625" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/97#pullrequestreview-1280942788" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 152. NAM ..GJUN `@namsengi11` (16 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/93#discussion_r1095373906" expanded>

Good job using uppercase for constants, but you can also use underscores to show spaces
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/93#discussion_r1095374627" expanded>

nice descriptive variable names
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/93#discussion_r1095374944" expanded>

nice comments explaining whats happening in the methods
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/93#discussion_r1095375983" expanded>

good use of brackets even for a one line if
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/93#pullrequestreview-1282310180" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/93#pullrequestreview-1282311011" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/93#pullrequestreview-1282311441" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/93#pullrequestreview-1282312852" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/186#discussion_r1095378875" expanded>

you should camelCase
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/186#discussion_r1095379104" expanded>

good job commenting what is happening
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/186#discussion_r1095379427" expanded>

you should be using .nextLine() instead
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/186#discussion_r1095380036" expanded>

you can use arrays to keep track of the tasks
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/186#pullrequestreview-1282317111" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/186#pullrequestreview-1282317375" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/186#pullrequestreview-1282317877" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/186#pullrequestreview-1282318762" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 153. YU S..CHEN `@sistine-yu` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/6#discussion_r1095404017" expanded>

it's a nice try to name the command string variable
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/6#discussion_r1095404990" expanded>

maybe there's no need to create a null Task object first
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/6#discussion_r1095407217" expanded>

it's nice to handle the unrecognized cases
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/6#discussion_r1095408780" expanded>

maybe try to separate the TodoTask as well to make it more organized
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/6#pullrequestreview-1282354134" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/15#discussion_r1095378871" expanded>

maybe you can use switch/case
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/15#discussion_r1095385913" expanded>

maybe no need to set it as static because you will change it later
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/15#discussion_r1095401870" expanded>

try to catch the exceptions if the input doesn't follow the correct format
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/15#discussion_r1095410795" expanded>

try to avoid chunks of codes inside main function, can create different methods and make the main function shorter and clearer~
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/15#pullrequestreview-1282313803" expanded>

**Review Status:** COMMENTED

The codes are functional and conforms aligns closely to the coding standards. But maybe you can create more methods to make the codes more neat and readable!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/15#pullrequestreview-1282317104" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 154. LIAN..G-YU `@MichelleLiang0116` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/64#discussion_r1094048144" expanded>

Probably should consider case sensitive.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/64#discussion_r1094048710" expanded>

Can add default to avoid improper input.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/64#discussion_r1094051094" expanded>

Good to use constant variable for reuse
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/64#discussion_r1094053108" expanded>

Good to use setType.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/64#pullrequestreview-1280363050" expanded>

**Review Status:** COMMENTED

Overall is good
Using constant variable and more convenient command.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/177#discussion_r1093981252" expanded>

Try to avoid using constant, probably can use replace or substring command.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/177#discussion_r1093981539" expanded>

Try to avoid using constant, probably can use replace or substring command.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/177#discussion_r1093981876" expanded>

Try to avoid using constant, probably can use index of or substring command.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/177#discussion_r1093982759" expanded>

Probably consider case sensitive problem.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/177#pullrequestreview-1280246289" expanded>

**Review Status:** COMMENTED

Overall is good.
Just try not to use constant in order to be more flexible.
</panel>

</panel>

<panel type="info" header="### 155. GERO..AUME `@guillaume-grn` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/144#discussion_r1094151550" expanded>

desc is not super explicit
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/144#discussion_r1094154705" expanded>

camelCase standard : it should be "exit"
```suggestion
    public static void exit() {
```
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/144#discussion_r1094161420" expanded>

Same as above
```suggestion
    public static void greet() {
```
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/144#discussion_r1094165113" expanded>

Suggestion : Maybe you could adapt the method name because boolean methods should be named to sound like booleans.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/144#pullrequestreview-1280479100" expanded>

**Review Status:** COMMENTED

Overall the standards are respected and the format is also very good.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/167#discussion_r1094171823" expanded>

Maybe use i instead of y to improve reading.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/167#discussion_r1094172487" expanded>

```suggestion
        for (int y = 0; y < listCount; y ++) {
```
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/167#discussion_r1094173874" expanded>

Format is good : tou don't mix methods and commands.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/167#discussion_r1094174725" expanded>

Maybe you should not name your String variable statusChar to avoid confusion with the Character class.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/167#pullrequestreview-1280521106" expanded>

**Review Status:** COMMENTED

The format is perfect and overall the standards are respected.
</panel>

</panel>

<panel type="info" header="### 156. KALK..KAUR `@gurmankalkat` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#discussion_r1095334315" expanded>

might be worth defining 100 as a variable to avoid magic number (maybe maxNumTasks)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#discussion_r1095336722" expanded>

maybe try making Integer.parseInt(words[1]) - 1 into its own variable to make code a little more readable 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#discussion_r1095340967" expanded>

can refactor code by extracting method 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#discussion_r1095347369" expanded>

nice job logically structuring the code in the loop!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#pullrequestreview-1282253785" expanded>

**Review Status:** COMMENTED

Overall, great job on naming and structure. Some slight organization and readability issues.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/214#discussion_r1095324099" expanded>

nice job making clear method and variable names!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/214#discussion_r1095326686" expanded>

Use K&R style brackets (as done in the exitLine method)
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/214#discussion_r1095327116" expanded>

change the form of the if/else statements to match the coding standard:

if (condition) {
    statements;
} else if (condition) {
    statements;
} else {
    statements;
}
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/214#discussion_r1095329376" expanded>

where/how is this used?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/214#pullrequestreview-1282209152" expanded>

**Review Status:** COMMENTED

Overall, great job structuring the code. Some minor style issues.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/214#pullrequestreview-1282239623" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 157. RAYD..XUAN `@raydent30` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/7#discussion_r1095302935" expanded>

maybe you can consider using enums?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/7#discussion_r1095303516" expanded>

code looks really clean!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/7#discussion_r1095305760" expanded>

good use of constants!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/7#discussion_r1095306168" expanded>

good use of different functions!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/7#pullrequestreview-1282209841" expanded>

**Review Status:** COMMENTED

The code is really well done! It gave me some ideas to learn from :)
You can consider using enums for the switch statement.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/208#discussion_r1095310338" expanded>

Good code readability with the else-if statements!  
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/208#discussion_r1095311137" expanded>

"Arrow Head" code, maybe you can consider  avoiding deep nesting?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/208#discussion_r1095311543" expanded>

A lot of complex strings/formulas, maybe consider splitting them up?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/208#discussion_r1095312465" expanded>

A lot of "magic numbers" involved. Maybe can consider using constants instead?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/208#pullrequestreview-1282220294" expanded>

**Review Status:** COMMENTED

Good job on your code!
Could use some reformating.
</panel>

</panel>

<panel type="info" header="### 158. PINT..AVID `@marekpinto` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/38#discussion_r1093986082" expanded>

This part is a little complicated and difficult to read, I'd recommend adding more spacing and comments to improve code quality.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/38#discussion_r1094025332" expanded>

Should you add an explicit //Fallthrough comment here to clarify that you intentionally left out the break statement?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/38#discussion_r1094027553" expanded>

I would recommend adding a Javadoc comment in front of your methods to clarify what they do and what parameters they take.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/38#discussion_r1094029251" expanded>

I like how you abstracted your code into many different methods, it makes it a lot more readable!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/38#pullrequestreview-1280267423" expanded>

**Review Status:** COMMENTED

Overall very readable code of good quality!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/175#discussion_r1093979273" expanded>

I like how you set the number of tasks as a constant variable so it can be set in a single place, instead of just using 100 everywhere.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/175#discussion_r1093979737" expanded>

Any reason why you decided to indent these lines like this?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/175#discussion_r1093981973" expanded>

I would recommend adding Javadoc comments before each method in order to convey the purpose of the method.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/175#discussion_r1093983129" expanded>

Try to keep each line under 120 characters.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/175#pullrequestreview-1280238047" expanded>

**Review Status:** COMMENTED

Looks good! Just added a couple small changes.
</panel>

</panel>

<panel type="info" header="### 159. SEAN..IAYI `@sansders` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/35#discussion_r1093934254" expanded>

Comments can be clearer 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/35#discussion_r1093935664" expanded>

Very clean main method!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/35#discussion_r1093940366" expanded>

Can probably include this in .gitignore
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/35#discussion_r1093942737" expanded>

Perhaps you can change this variable name to be a plural form of a different variable name
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/35#pullrequestreview-1280162398" expanded>

**Review Status:** COMMENTED

Looks great overall! All the best for the rest of the mod!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/142#discussion_r1093923464" expanded>

Would probably be better to name this as `storedValues` instead
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/142#discussion_r1093924700" expanded>

Need to add whitespace at the start of the comment, and begin with comment with `Stores` instead of `store`
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/142#discussion_r1093925384" expanded>

Need to change every other comment to adhere to the proper coding standard
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/142#discussion_r1093927207" expanded>

The main method looks good and clean 👍
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/142#pullrequestreview-1280147728" expanded>

**Review Status:** COMMENTED

Overall, very clean code!
</panel>

</panel>

<panel type="info" header="### 160. ZENG..CKIE `@Jjzeng123` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/30#discussion_r1093932986" expanded>

readability is good, well done
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/30#discussion_r1093933110" expanded>

good job on keeping the method short and readable
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/30#discussion_r1093933334" expanded>

good job on keeping the expressions simple
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/30#discussion_r1093934021" expanded>

good job naming the classes clearly
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/30#pullrequestreview-1280160501" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/84#discussion_r1093927611" expanded>

consider standardizing the format of brackets across all the files, like while (true){ vs while(true) { and while (true) {
use egyptian style brackets as mentioned in the course website
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/84#discussion_r1093928917" expanded>

good job on indentations done correctly
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/84#discussion_r1093929265" expanded>

good job on observing the correct layout for switch and case statements
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/84#discussion_r1093930147" expanded>

avoid importing the entire package (idk if this applies to your own class?), import specific modules from each package
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/84#pullrequestreview-1280153040" expanded>

**Review Status:** COMMENTED

no major issues, just some inconsistency in the bracket formatting and some packages were imported fully
</panel>

</panel>

<panel type="info" header="### 161. THIO..KIAT `@Thiolk` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/177#discussion_r1093931771" expanded>

Perhaps you could consider keeping the space between the "()" and "{" consistent?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/177#discussion_r1093932340" expanded>

Maybe you could consider adding a default branch in the case statements?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/177#discussion_r1093932893" expanded>

Any reason why you included the extra empty line at the end of the for loop?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/177#discussion_r1093934152" expanded>

Perhaps you could include some spaces between the " in the println statments to improve the readability?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/177#discussion_r1093934884" expanded>

Should you avoid the use of magic numbers and replace the number with a named constant instead?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/177#pullrequestreview-1280158893" expanded>

**Review Status:** COMMENTED

Overall, the code was done to a high standard and was easily readable though there are certain sections that could be improved slightly to keep the style of your code more consistent
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/211#discussion_r1093925305" expanded>

Should there be a spacing between the curly brackets and the "else if" and the "else"?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/211#discussion_r1093936718" expanded>

Perhaps you could consider writing your variable name in full?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/211#discussion_r1093942281" expanded>

Good job in ensuring that the character count of each line should not exceed 120 characters.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/211#pullrequestreview-1280150166" expanded>

**Review Status:** COMMENTED

Overall, the code quality is great although you could consider using switch statements and shortening the print statements to improve the readability of the code.
</panel>

</panel>

<panel type="info" header="### 162. KAEM..NGYU `@KN-CY` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/42#discussion_r1093921486" expanded>

Could consider removing this comment as it's a bit unnecessary.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/42#discussion_r1093923664" expanded>

Good job following convention for if else statements
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/42#discussion_r1093924336" expanded>

Good job following naming convention for boolean variable.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/42#discussion_r1093925527" expanded>

Good job attaching array specifier to type rather than attaching to variable.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/42#pullrequestreview-1280144992" expanded>

**Review Status:** COMMENTED

Overall good job following the coding standards.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/81#discussion_r1093933763" expanded>

Could consider extracting each of these case for more abstraction
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/81#discussion_r1093934511" expanded>

Can consider removing extra blank lines.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/81#discussion_r1093936370" expanded>

Method names should be in camelCase.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/81#discussion_r1093937333" expanded>

Good job providing abstraction for the various types of string parsing.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/81#pullrequestreview-1280161600" expanded>

**Review Status:** COMMENTED

Overall code is readable, of good quality, and follows most standards. But could possibly be improved as commented.
</panel>

</panel>

<panel type="info" header="### 163. SAIN.. ZAW `@saintzaw` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/28#discussion_r1093944255" expanded>

Perhaps you can consider changing the method name to something more descriptive, I am not very clear on what this is for.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/28#discussion_r1093945625" expanded>

I think the brackets after case "list" : and other cases are not necessary, removing the brackets might make it look neater
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/28#discussion_r1093948879" expanded>

Your main method looks neat with the same level of abstraction, it's satisfying to see.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/28#discussion_r1093951402" expanded>

I like this, really creative way of saying goodbye! 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/28#pullrequestreview-1280175812" expanded>

**Review Status:** COMMENTED

I think you've done a great job so far! Keep it up :)
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/85#discussion_r1093928721" expanded>

Perhaps you can consider changing the name representing the collection of tasks from list to tasks since "plural form should be used on names representing a collection of objects." 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/85#discussion_r1093933250" expanded>

You can try to make your methods look more uniform by leaving a space in between the (int currentTaskNum) and { 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/85#discussion_r1093935145" expanded>

I think you did a great job on the naming of variables and methods, they comply with the coding standard.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/85#discussion_r1093938330" expanded>

Perhaps you can consider changing the method name to setUndone() since "Setter methods for boolean variables must be of the form: void setFound(boolean isFound);" 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/85#pullrequestreview-1280154841" expanded>

**Review Status:** COMMENTED

I think you did a really great job here! I couldn't really find coding standard violations and I found your code to be pretty clear and concise. Keep it up :)
</panel>

</panel>

<panel type="info" header="### 164. ANTH.. YIP `@anthea-pr0g` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/96#discussion_r1093932363" expanded>

Good Job on using camelCase consistently throughout your code for variable names. 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/96#discussion_r1093934532" expanded>

Could this comment be clearer? ex. what words? 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/96#discussion_r1093935763" expanded>

Good work on keeping the line length no longer than 120 characters throughout your code. And indenting by 8 spaces for wrapped lines. 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/96#discussion_r1093937555" expanded>

Good job on keeping the indentation for case the same as the switch statements.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/96#pullrequestreview-1280159652" expanded>

**Review Status:** COMMENTED

Overall everything looks neat and well done. Good Work! 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/138#discussion_r1093943258" expanded>

Good job on naming it appropriately and being neat. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/138#discussion_r1093945687" expanded>

the else could be placed in the next line instead for better readability.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/138#discussion_r1093952402" expanded>

The name HELP could be more specific: what help It is providing/need help from
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/138#discussion_r1093954745" expanded>

You could consider having a getStatusIcon method in your task.java and simplify your printTask code for Todos Deadline and Events code 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/138#pullrequestreview-1280174575" expanded>

**Review Status:** COMMENTED

 Overall, Great work and I love the character faces! :)
</panel>

</panel>

<panel type="info" header="### 165. LEE .. HAN `@ltzehan` (9 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/169#discussion_r1095308969" expanded>

I think you misspelt "description" here
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/169#discussion_r1095309409" expanded>

Could call this `tasks` too, but I like the naming `taskList` more (don't tell the TAs)
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/169#discussion_r1095309655" expanded>

I like the naming -- much more descriptive than something like just `mark`
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/169#discussion_r1095310171" expanded>

Just nitpicking, but I think the name should just be `splitDescription`
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/169#pullrequestreview-1282218311" expanded>

**Review Status:** COMMENTED

Nice code!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/199#discussion_r1095306304" expanded>

Like your naming for the ArrayList!


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/199#discussion_r1095307051" expanded>

Just nitpicking, but would be nice if there was a space after this :&hat;)
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/199#discussion_r1095307381" expanded>

I think it would be better to use a more descriptive name -- not sure what `org` means here
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/199#pullrequestreview-1282214591" expanded>

**Review Status:** COMMENTED

Nice, just nitpicking
</panel>

</panel>

<panel type="info" header="### 166. LOH .. HOE `@lohjooh` (9 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/102#discussion_r1094162501" expanded>

I like your naming for your methods, they are clear and readable.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/102#discussion_r1094177151" expanded>

Consider making the logo and other constant variables a final variable
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/102#discussion_r1094178831" expanded>

Good job avoiding deep nesting of the if-else statements, making the code more readable
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/102#pullrequestreview-1280506397" expanded>

**Review Status:** COMMENTED

Good job keeping the code neat and readable!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/156#discussion_r1094146192" expanded>

Great to see that the names are verbs and the names makes the function of each method easy to understand
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/156#discussion_r1094150234" expanded>

I suggest that you should move up the else to be besides the braces
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/156#discussion_r1094153779" expanded>

Good job in following the coding conventions by using "i" as an iterator variable
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/156#discussion_r1094157422" expanded>

You did a good job in following the K&R style brackets
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/156#pullrequestreview-1280483186" expanded>

**Review Status:** COMMENTED

Looks good overall, very neat. 
Be careful for your if-else bracket formatting.
</panel>

</panel>

<panel type="info" header="### 167. CHEN.. HAN `@ZIZI-czh` (9 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/87#discussion_r1094186863" expanded>

Maybe you want to change "io" to a clearer word or add in description for it?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/87#discussion_r1094193882" expanded>

Maybe you want to replace 's' with a meaningful word? Based on java coding standard, for boolean, the declared variable will start with "is", e.g: isDone
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/87#discussion_r1094199049" expanded>

Based on java coding standard, all the final variables should in capital letter
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/87#pullrequestreview-1280543537" expanded>

**Review Status:** COMMENTED

Overall, the coding styles are good and most of them follow the java standard. However, there are some minor points you may be careful. 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/117#discussion_r1094215617" expanded>

You may want to delete these empty lines so that the codes look like neater?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/117#discussion_r1094217808" expanded>

Maybe you can consider replace sc with another meaning variable?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/117#discussion_r1094226383" expanded>

I like your code style as it is clear and neat!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/117#discussion_r1094229675" expanded>

Maybe you can try to move your else one line up. For example, else in line 97 move up to line 96.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/117#pullrequestreview-1280585736" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 168. MUTH..AVYA `@11-Navya` (9 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/14#discussion_r1093309828" expanded>

Good formatting and sectioning of code 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/14#discussion_r1093313711" expanded>

Goof formatting of code for neater presentation 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/14#discussion_r1093316380" expanded>

Good 👍  
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/14#pullrequestreview-1279240733" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/121#discussion_r1092760253" expanded>

Good modification of Code to make the code neater 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/121#discussion_r1092762226" expanded>

Standardise the space between different class methods 
Ex: between dukeCommandList and printEvent is more than the space between the printEvent and printDeadline
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/121#discussion_r1093300703" expanded>

Good code formatting 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/121#discussion_r1093304107" expanded>

Suggestion: Leave space between initialising variables and class methods for neater presentation 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/121#pullrequestreview-1278424908" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 169. BAEK..GYUN `@L0Z1K` (9 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/120#discussion_r1094017190" expanded>

Indentation for wrapped lines should be 8 spaces (i.e. twice the normal indentation of 4 spaces) more than the parent line. For example,

```Java
setText("Long line split"
        + "into two parts.");
```
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/120#discussion_r1094017334" expanded>

Indentation for wrapped lines should be 8 spaces (i.e. twice the normal indentation of 4 spaces) more than the parent line. For example,

```Java
setText("Long line split"
        + "into two parts.");
```
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/120#discussion_r1094019289" expanded>

I think comment in L11 can present `getStatusIcon()` function. So how about moving the comment to the above of function. For example, 

```Java
// bla bla
public String getStatusIcon() {

}
```
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/120#pullrequestreview-1280336006" expanded>

**Review Status:** COMMENTED

I commented about Java coding standards. Thank you.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/168#discussion_r1094021956" expanded>

How about changing the function name to `setTaskDone()`? because it is used for **setting** the `isDone` variable.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/168#discussion_r1094022821" expanded>

I think we should use camelCase instead of snake_case. How about changing the parameter name to `taskNumber`?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/168#discussion_r1094023458" expanded>

You can use the setter of the Task Class for setting isDone to true.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/168#discussion_r1094023655" expanded>

You can also use the setter of the Task Class for setting isDone to false.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/168#pullrequestreview-1280339659" expanded>

**Review Status:** COMMENTED

I commented about some code quality. Thank you.
</panel>

</panel>

<panel type="info" header="### 170. LEE ..GJUN `@0nandon` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/68#discussion_r1095303172" expanded>

Good job for separating your code in to several functions.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/68#discussion_r1095304408" expanded>

```suggestion
public static void inputIsMark(String userInput){
```
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/68#discussion_r1095304811" expanded>

When you declare function or input, It is more better to user lower case in the first letter of the name.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/68#discussion_r1095309969" expanded>

```suggestion
public static void addPrintTask(){
```
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/68#discussion_r1095310698" expanded>

```suggestion
import java.util.Scanner;

public class Rolex {
```
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/68#discussion_r1095320133" expanded>

'switch' is more better than if-else statement in this case since there are various cases you want to separate.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/68#discussion_r1095327043" expanded>

```suggestion
}else if(UserInput.startsWith("unmark")){
```
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/68#pullrequestreview-1282210165" expanded>

**Review Status:** COMMENTED

I think code is quite clean, especially for separating every code module into multiple functions. But in my knowledge, first letter of the function, input, variables, etc is better to be in lower case. Otherwise, I think the code is well structured.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/68#pullrequestreview-1282219729" expanded>

**Review Status:** COMMENTED

In my knowledge, underline should be only used in the test methods.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/68#pullrequestreview-1282220789" expanded>

**Review Status:** COMMENTED

It is better to put single line between the import packages and class you declared.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/68#pullrequestreview-1282234231" expanded>

**Review Status:** COMMENTED

If there are numerous cases you want to separate, 'switch' could be your answer rather than if-else.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/68#pullrequestreview-1282243862" expanded>

**Review Status:** COMMENTED

format of the if-else statement should be like below:

if(...){
    ...
} else if(...){
    ...
} 

</panel>

</panel>

<panel type="info" header="### 171. LIU ..YANG `@liuziyang020319` (9 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/41#discussion_r1095380334" expanded>

Maybe the loops don't follow the coding standard, I think "for( int i=0; i &gt; userTextCount; i++) {" can be better.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/41#discussion_r1095382050" expanded>

Maybe you can use methods to handle different situations, so that the abstraction of the code will be better..
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/41#pullrequestreview-1282319141" expanded>

**Review Status:** COMMENTED

a good robot, follow the coding standard and code quality guidelines!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/201#discussion_r1095372976" expanded>

Maybe use isExit to replace exit can imply a boolean
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/201#discussion_r1095374197" expanded>

Maybe V\variable names need to be in camelCase.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/201#discussion_r1095374453" expanded>

Maybe variable names need to be in camelCase.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/201#discussion_r1095374851" expanded>

Maybe variable names must be in camelCase, same problem.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/201#discussion_r1095375496" expanded>

Maybe the size of the ArrayList should be a magic number.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/201#pullrequestreview-1282308988" expanded>

**Review Status:** COMMENTED

Most the codes follow the coding standard
</panel>

</panel>

<panel type="info" header="### 172. GOH .. YAO `@chokyao` (9 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/51#discussion_r1093948230" expanded>

Perhaps could consider a slightly more meaningful name such as taskCount
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/51#discussion_r1093951918" expanded>

Maybe can consider abstracting this part out into a separate method so that the whole getEventDetails method will have the same level of abstraction
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/51#discussion_r1093955468" expanded>

Great use of methods to abstract out certain actions!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/51#discussion_r1093956914" expanded>

Very clear about what to do in each switch case.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/51#pullrequestreview-1280181260" expanded>

**Review Status:** COMMENTED

Overall, I like how neat your code is and it complies with the recommended coding standards. Keep it up!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/161#discussion_r1093928914" expanded>

Perhaps could use common iterator variables names such as i, j ,k etc instead
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/161#discussion_r1093932531" expanded>

Perhaps could consider a more intuitive variable name for the array?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/161#discussion_r1093933689" expanded>

Perhaps could use a more meaningful variable name that is specific to the item that is being counted
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/161#pullrequestreview-1280155072" expanded>

**Review Status:** COMMENTED

I like how most of the code complied with the coding standards other than a few slip-ups. 
</panel>

</panel>

<panel type="info" header="### 173. LEE ..RIEL `@azriellee` (9 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/8#discussion_r1093925091" expanded>

use camelCase naming convention (e.g. userInput)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/8#discussion_r1093927897" expanded>

in the lines that follow, extract the lines out as constants
line 33 'else' should be after the bracket
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/8#discussion_r1093928738" expanded>

else if should come immediately after curly bracket
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/8#discussion_r1093929417" expanded>

these lines are too long, should be extracted out
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/8#pullrequestreview-1280149941" expanded>

**Review Status:** COMMENTED

Other classes are ok, but main class should be extracted out to be neater in general. all the best!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#discussion_r1093933203" expanded>

this can be refactored
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#discussion_r1093935890" expanded>

can also be refactored
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#discussion_r1093936107" expanded>

please refactor this too
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/165#pullrequestreview-1280160802" expanded>

**Review Status:** COMMENTED

(Coding quality) Overall code is neat and clean, logic flows well and is very understandable. However more refactoring can be done instead of putting everything under main
</panel>

</panel>

<panel type="info" header="### 174. OONG..ARED `@jaredoong` (8 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/66#discussion_r1095307327" expanded>

Good use of inheritance from the Task class
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/66#discussion_r1095308711" expanded>

This could be deep nesting, might be good to use guard clauses instead 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/66#discussion_r1095310805" expanded>

I'm not too sure where this is used, but maybe this could be omitted since doneStatus is dependent on isDone. The function getDoneStatus() seems to not this function too.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/66#pullrequestreview-1282215991" expanded>

**Review Status:** COMMENTED

Good readability, just minor possible edits
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#discussion_r1095301549" expanded>

The boolean could be named to show that it is a boolean, such as "isDone"
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#discussion_r1095302958" expanded>

Interesting way to differentiate Duke which is good. However, one possible way to make it user-friendly to all users would be to include the English translation
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#discussion_r1095303680" expanded>

Clear naming, good job!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#pullrequestreview-1282207989" expanded>

**Review Status:** COMMENTED

Good code for most parts, just minor portion on naming standards and making the code understandable by a international audience
</panel>

</panel>

<panel type="info" header="### 175. CHEN..NXIN `@wenxin-c` (8 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/78#discussion_r1094019535" expanded>

Nice use of constants:D
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/78#discussion_r1094020894" expanded>

Good abstraction into different command methods. It is neat and readable. 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/78#discussion_r1094085358" expanded>

Nice check of the capacity of array to catch errors:D
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/78#discussion_r1094089481" expanded>

Good use of try catch for catch possible errors. 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/78#pullrequestreview-1280337812" expanded>

**Review Status:** COMMENTED

Overall good work. To further improve the code quality and readability, the code can be further extracted into classes. Instead of writing all the command methods inside Duke class, they can be extracted into a command manager class. The task methods can also be extracted into a task manager class. As such, Duke class can be kept concise, increasing the readability of the code. 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/110#discussion_r1094012666" expanded>

Good abstraction of getter and setter. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/110#discussion_r1094016106" expanded>

Good logic, but the code can be further abstracted into different classes, for example, a command manager class to manage commands instead of putting everything in main:D
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/110#pullrequestreview-1280332559" expanded>

**Review Status:** COMMENTED

Overall good work!! Further abstractions can be added to improve the readability of the code:D
</panel>

</panel>

<panel type="info" header="### 176. DIVA..SHRI `@manushridiv` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/151#discussion_r1094051949" expanded>

code is very neat, strings can be declared in a single or fewer lines but this is more readable.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/151#discussion_r1094054795" expanded>

indentation is good and the variables name declaration is good quality.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/151#discussion_r1094055258" expanded>

Do not need to declare additional variables for strings, can directly print instead. 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/151#discussion_r1094056450" expanded>

too many declarations of variables, making the code too lengthy. Not necessary to declare whitespace character for whitespace strings and brackets.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/151#discussion_r1094056898" expanded>

Neat and readable, well done.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/151#discussion_r1094067454" expanded>

Unnecessary declarations for the string characters, can be condensed into a single line.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/151#pullrequestreview-1280366309" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/151#pullrequestreview-1280368805" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/151#pullrequestreview-1280369215" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/151#pullrequestreview-1280370140" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/151#pullrequestreview-1280370543" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/151#pullrequestreview-1280379875" expanded>

**Review Status:** COMMENTED

Looks good overall and the code is readable, classes clearly defined.

Can be improved by removing additional declarations which clutters the code too much.
</panel>

</panel>

<panel type="info" header="### 177. YAN ..AIYA `@skyanzy` (8 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/109#discussion_r1094347283" expanded>

good job in following the coding standard of switch
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/109#discussion_r1094350596" expanded>

perhaps verbs are better for method names
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/109#discussion_r1094352713" expanded>

good job in following naming standard
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/109#pullrequestreview-1280786107" expanded>

**Review Status:** COMMENTED

Well done! your code is very clear and readable. Naming is clear and easy to understand
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/200#discussion_r1093978366" expanded>

good job in importing classes explicitly
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/200#discussion_r1093979950" expanded>

good job in using string.equalsIgnoreCase when comparing strings 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/200#discussion_r1093982748" expanded>

good job in separating your output string to make your code look neat
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/200#pullrequestreview-1280234366" expanded>

**Review Status:** COMMENTED

Good job! you did really well in following java coding standards! well done in making sure that no line exceeds 120 characters
</panel>

</panel>

<panel type="info" header="### 178. NG Y.. FEI `@ollayf` (8 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/30#discussion_r1094146753" expanded>

If this var is a constant, consider using HORIZONTAL_LINE
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/30#discussion_r1094147888" expanded>

sick use of split!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/30#discussion_r1094149278" expanded>

As many before have mentioned before, simple and good use of variable naming. Coding Standard is GREAT!! :)
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/30#pullrequestreview-1280483978" expanded>

**Review Status:** COMMENTED

Very good Coding Standard. More (including myself) should learn from your example!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/188#discussion_r1094156515" expanded>

perhaps there could be other ways to do this that are more readable and less susceptible to mistakes. For example, using the &gt;string instance>.split function. 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/188#discussion_r1094157510" expanded>

It's still ok... but again would be better if you used string.split function
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/188#discussion_r1094158227" expanded>

Good use of imports and splitting into different files!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/188#pullrequestreview-1280497610" expanded>

**Review Status:** COMMENTED

Not bad! You can even use the different stuff learnt from coding exercises

</panel>

</panel>

<panel type="info" header="### 179. HRIT..ENON `@hrithie` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#discussion_r1095381553" expanded>

 Perhaps you could name the status variable to make it sound like a boolean with is/can at the start. 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#discussion_r1095382288" expanded>

I like the creativity of using another language for Duke to communicate. However, it is not very user-friendly, especially in a Singaporean context. 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#discussion_r1095383636" expanded>

Great naming conventions! It makes your code very readable. 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#discussion_r1095386456" expanded>

This is an interesting way of coding the loop
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#discussion_r1095390479" expanded>

This portion of code could be made to be more readable by making it into a variable on its own!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#discussion_r1095392516" expanded>

Brilliant! This portion of code is very readable. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#pullrequestreview-1282320842" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#pullrequestreview-1282322017" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#pullrequestreview-1282324111" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#pullrequestreview-1282328261" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#pullrequestreview-1282334564" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/179#pullrequestreview-1282337389" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 180. CHON.. RUI `@chongyongrui` (8 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/125#discussion_r1092865127" expanded>

I like how you extracted the print divider to a separate function to make your code much neater 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/125#discussion_r1092867167" expanded>

Perhaps you could put all your constants into a separate class? It could make your code neater.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/125#discussion_r1092867973" expanded>

I like how you use constants to replace magic numbers.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/125#pullrequestreview-1278578386" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/158#discussion_r1092857481" expanded>

I like how you changed the name of the Boolean variable name to something that sounds natural, and an alternative could have been "isActionCommand"
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/158#discussion_r1092858386" expanded>

I feel that you can use a constant variable to replace "100" as it is a magic number
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/158#discussion_r1092860537" expanded>

I like the use of switch statements instead of if-else statements as your code is neat and clear
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/158#pullrequestreview-1278567512" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 181. YANG..MING `@stephenkyang` (8 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/14#discussion_r1092863819" expanded>

One suggestion is to avoid .* imports.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/14#discussion_r1092865207" expanded>

Good job using variables instead of magic constants
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/14#discussion_r1092866123" expanded>

Good job using inheritence and overriding functions as needed
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/14#discussion_r1092866716" expanded>

Good job with creating the Greetings class for modularization!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/14#pullrequestreview-1278576436" expanded>

**Review Status:** COMMENTED

Overall LGTM, no real changes for this PR
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/99#discussion_r1092860202" expanded>

One suggestion would be to make it clear what the counter is counting
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/99#discussion_r1092861759" expanded>

One suggestion is to remove ternary operators to improve readability.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/99#pullrequestreview-1278571367" expanded>

**Review Status:** COMMENTED

Overall looks great! Some minor changes for readability but should be easy to fix.
</panel>

</panel>

<panel type="info" header="### 182. MUHA..UJAI `@adzikrafi` (7 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/141#discussion_r1092752275" expanded>

It would be better to use switch-case instead of if-else since there are multiple cases
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/141#discussion_r1092752771" expanded>

consider adding a printMessage method here to print a message that acknowledges a task has been created since it would be reused in the subclass of the task (todo, deadline, event)
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/141#discussion_r1092754238" expanded>

The method markDone and markUndone can be combined into a single method called setMark(boolean status) where it sets the value of isDone to equal to status, which make the code more efficient
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/141#discussion_r1092757603" expanded>

good job on making the code looks tidy, proper indentation and spacing, the naming of the variable is also proper, and the code is very intuitive and easy to read
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/141#discussion_r1092762293" expanded>

I like that you are using uncapitalized letter for variable but use capitalized letter to seperate the words in the variable. good job
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/141#discussion_r1092762480" expanded>

proper naming of the array, good
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/141#pullrequestreview-1278414221" expanded>

**Review Status:** COMMENTED

PR review Muhammad Rafi Adzikra Sujai
</panel>

</panel>

<panel type="info" header="### 183. LYU ..NGYU `@Zemdalk` (8 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/137#discussion_r1095374940" expanded>

Perhaps using camelCase for variable `list_index` is better?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/137#discussion_r1095376876" expanded>

I like the way you use `ArrayList` to manage tasks.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/137#discussion_r1095378819" expanded>

I argee with @TopGun2001 basically. And maybe it's better to extract your codes inside these `if-else` statements and form several functions apart from `main` function? This would make `main` function not too long maybe.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/137#discussion_r1095380446" expanded>

Also I really like the way you use function `printList` to print the list.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/137#pullrequestreview-1282311426" expanded>

**Review Status:** COMMENTED

Looks good. I just give some personal suggestions on naming and functions
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/214#discussion_r1095385940" expanded>

Personally, maybe you can replace the number `9` with a constant to avoid "magic numbers"?

> Like `private static final int DEADLINE_LABEL = 9;`?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/214#discussion_r1095388661" expanded>

I like the way you use `StringBuffer` to operate on these strings, it's really useful.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/214#pullrequestreview-1282327520" expanded>

**Review Status:** COMMENTED

Your indentation is really good. `StringBuffer` class is really useful, I like the way you use it to deal with strings. Maybe you can replace some "magic numbers" with constants to make your code more readable? Just some personal ideas.
</panel>

</panel>

<panel type="info" header="### 184. MATT.. JIE `@matthew-liu-zhenjie` (6 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/126#discussion_r1095375279" expanded>

I really like the use of an array of strings to implement a switch case to process the user's command. It looks great! 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/126#discussion_r1095381138" expanded>

Nice use of SLAP. Good job! 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/126#discussion_r1095383455" expanded>

Perhaps (id-1) could be put inside the method? Could help with readability.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/126#discussion_r1095383973" expanded>

Perhaps you could refactor this into a single method
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/126#discussion_r1095390169" expanded>

Good use of a class to group the printing outputs
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/126#pullrequestreview-1282311910" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 185. LIM .. YAO `@LimHongYao` (7 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/7#discussion_r1095380716" expanded>

very good use of functions, good picture of what each line of code does
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/7#pullrequestreview-1282319719" expanded>

**Review Status:** COMMENTED

this looks like something we can find from an answer key. great job!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/172#discussion_r1095372961" expanded>

maybe you can have an alternate naming for `task` since 6/8 words are some variation of "task"
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/172#discussion_r1095373733" expanded>

maybe `welcomeMessage` is a better name? Since it does not seem to have any other function
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/172#discussion_r1095374180" expanded>

good handling of out of bounds!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/172#discussion_r1095375489" expanded>

is this an override from` Task` ? Potentially buggy otherwise as you might call the wrong `getIcon()` i think
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/172#pullrequestreview-1282308957" expanded>

**Review Status:** COMMENTED

gj bro quite neat but you might want to use more explicit naming
</panel>

</panel>

<panel type="info" header="### 186. YEK ..OLAS `@nichyjt` (7 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/9#discussion_r1094019537" expanded>

There are some inconsistencies between the access modifiers between the subclasses for the Task feature. Some are set as private (e.g. Event) while others are set as protected (s.a. this file). I am unsure if there is a particular intent for this, but if there is none perhaps it would be better practice to standardise the access modifiers across subclasses.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/9#discussion_r1094080134" expanded>

For the subclasses for Task, there are minor space formatting issues for curly braces. If they come after parentheses "()", there should be a space between it and the opening curly brace.

[Reference for this format](https://se-education.org/guides/conventions/java/basic.html#layout)! 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/9#discussion_r1094082581" expanded>

I like how there are comments given thoughout the program. I think to improve on this good practice one minor change can be made.

It might be better to leave [comments in their own lines](https://se-education.org/guides/conventions/java/basic.html#comments) with the same indentation level. 
Although the comments are short, giving them their own lines may be better practice to improve readability in the long run!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/9#pullrequestreview-1280335487" expanded>

**Review Status:** COMMENTED

Overall, the code is well factored and follows the SLAP principle well. Apart from minor nits with respect to formatting, your code adheres to good Coding Standards. Good job!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/184#discussion_r1094100394" expanded>

Perhaps this if statement can be refactored out to the bottom as a "default" case. Further, the condition expression is quite long! 

In the code below, checks have already been accounted for:
`list, mark, unmark`.

Since all 3 commands have been checked already, the condition evaluated in this line:  
`if (!(line.equals("list") || line.startsWith("mark") || line.startsWith("unmark"))`  

Is implicitly satisfied from line 58 onwards. So, you can consider factoring out the logic for the addition of a new Task to line 58!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/184#discussion_r1094106832" expanded>

The logic here makes sense and accounts for invalid input, good job! 

Perhaps it is possible to build on this logic to reduce the nesting and [make the execution path even clearer](https://nus-cs2113-ay2223s2.github.io/website/se-book-adapted/chapters/codeQuality.html#make-the-happy-path-prominent). 

I think that you can consider refactoring the error check for `listNum` as a guard clause and then doing the `isDone` check.

Possible pseudocode:
```java
// Check for listNum validity
if(listNum < 0 || listNum >= item) {
    // Handle case where item does not exist
}
// Check for done status
if(list[listNum.isDone != status) {
    // Do something
}else{
    // Do something else
}


```


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/184#pullrequestreview-1280416641" expanded>

**Review Status:** COMMENTED

The code flows logically and is easy to read. There are proper checks for invalid input implemented, which is well thought of!

To build upon this, there are some refactors commented that can be done to further improve readability and the structure of the code that you can consider adopting!
</panel>

</panel>

<panel type="info" header="### 187. ZHOU..UIQI `@Stella1585` (6 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/190#discussion_r1092856312" expanded>

(not coding standard related but) Since you are using contains and not equals, do you think contains(unmark) is necessary?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/190#discussion_r1092859911" expanded>

this is a variable so camel case should be used, also maybe a better variable name can be used as this array contains both the command and the index.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/190#discussion_r1092862046" expanded>

plural form should be used for collection of objects, so perhaps using names such as tasks would be better
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/190#discussion_r1092877936" expanded>

for your function .get, perhaps be clearer about what you are getting, such using as getStatus or getName.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/190#discussion_r1092881234" expanded>

any reason why you did not continue with else if?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/190#pullrequestreview-1278565852" expanded>

**Review Status:** COMMENTED

Looks good, you followed the coding standards quite well. Overall, you can try to find more suitable variable names that helps to get your intention across. Also the nesting is quite deep for the mark/unmark section. Lastly you can try extracting methods from main as it is quite long.
</panel>

</panel>

<panel type="info" header="### 188. RYAN.. TAN `@Thunderdragon221` (6 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/56#discussion_r1092789670" expanded>

noticed a lot of these line prints, maybe extract these into the while loop?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/56#discussion_r1092792008" expanded>

maybe use if-else instead for clarity?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/56#discussion_r1092792386" expanded>

I like your method naming, keep it up!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/56#discussion_r1092793505" expanded>

maybe a slightly clearer name can be given for "divider1"?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/56#discussion_r1092794034" expanded>

I like your clean handling of tasks
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/56#pullrequestreview-1278466550" expanded>

**Review Status:** COMMENTED

Very good adherence to good coding standards and practices, but maybe certain repetitive pieces of code can be extracted out into their respective functions. Overall well done!
</panel>

</panel>

<panel type="info" header="### 189. DOU ..IHAO `@douph810975` (7 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/40#discussion_r1092877928" expanded>

I like you if-else layout here
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/40#discussion_r1092882618" expanded>

I like the naming of constant variables with all capital letters and using underscores to separate words.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/40#discussion_r1092885366" expanded>

I like how you differentiate "mark" and "unmark" here.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/40#pullrequestreview-1278597269" expanded>

**Review Status:** COMMENTED

Overall is good! I like all the namings and layouts of the code. Btw, I want to know why you moved hello and greeting out.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/71#discussion_r1092860023" expanded>

Perhaps a clearer variable name here? such as start or begin, instead of by.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/71#discussion_r1092862009" expanded>

I like the functions here to help you to print the messages. The name format is also good.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/71#pullrequestreview-1278571094" expanded>

**Review Status:** COMMENTED

I like your namings and layouts. Good job!
</panel>

</panel>

<panel type="info" header="### 190. VAN ..SEPH `@SpeciLiam` (7 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/103#discussion_r1095380113" expanded>

It might be good practice to do break break statements regardless of  if you are able to just exit the methiod
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/103#pullrequestreview-1282318849" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/176#discussion_r1095373871" expanded>

There's a lot of extra spacing, you could potentially get rid of them.

Liam Van
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/176#discussion_r1095374814" expanded>

Inconsistent spacing at end of curly bracket and start of curly bracket  
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/176#discussion_r1095375207" expanded>

You shouldn't have to pass as param because it is a final constant
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/176#discussion_r1095376337" expanded>

For multi line println I believe the successive lines need to be more indented to make it look more seamless 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/176#pullrequestreview-1282310105" expanded>

**Review Status:** COMMENTED

Liam Van Review 
</panel>

</panel>

<panel type="info" header="### 191. LEE ..SENN `@Ansenn` (5 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/161#discussion_r1093980873" expanded>

Perhaps the logo could make Duke more user friendly and nice
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/161#discussion_r1093981428" expanded>

Good use of curly braces for if-else statements 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/161#discussion_r1093982662" expanded>

Perhaps having index and strIndex as similar names may be confusing to some people, so can consider using other variable names
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/161#discussion_r1093983563" expanded>

Good work adhering to coding standards!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/161#pullrequestreview-1280244746" expanded>

**Review Status:** COMMENTED

Keep up the good work!
</panel>

</panel>

<panel type="info" header="### 192. GARL..ANYA `@SaiChaitanya13` (5 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/4#discussion_r1092866052" expanded>

I like that you stored the different commands in an array
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/4#discussion_r1092867664" expanded>

I like that you check for duplicate keywords.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/4#discussion_r1092869155" expanded>

I like that you consistently use camelCase for the whole project.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/4#discussion_r1092871850" expanded>

Perhaps you could split the code into separate classes due to the length of the main class, for better code quality.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/4#pullrequestreview-1278579711" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 193. FAN ..XIAN `@FanZixian` (5 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/170#discussion_r1094069898" expanded>

In line 2 and 3, regarding the coding standard, the final string should be in capital letters.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/170#discussion_r1094069945" expanded>

In line 11, regarding the coding standard, the { should be put in the same line of "public".
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/170#discussion_r1094070009" expanded>

Regarding the coding quanlity, comments should be given regarding -1, otherwise, it is not meaningful.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/170#discussion_r1094070043" expanded>

For some messages like "[T]", regarding the coding quanlity, it is better to be put in an enum class or in a final string list.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/170#pullrequestreview-1280382135" expanded>

**Review Status:** COMMENTED

3. In line 45 of class Limey, regarding the coding quanlity, comments should be given for return -1, otherwise, it is not meaningful.
4. For some messages like "[T]", regarding the coding quanlity, it is better to be put in an enum class or in a final string list.
</panel>

</panel>

<panel type="info" header="### 194. YAO ..O HE `@Sherlock-YH` (5 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/92#discussion_r1094054381" expanded>

I like the ways you put the Constants into one package
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/92#discussion_r1094058260" expanded>

I like the way you import packages
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/92#pullrequestreview-1280368442" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/140#discussion_r1094067246" expanded>

Maybe can put some simple descriptions about what these integers mean
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/140#pullrequestreview-1280379691" expanded>

**Review Status:** COMMENTED

OVERALL GOOD JOB
</panel>

</panel>

<panel type="info" header="### 195. LU B..YUAN `@notbingsu` (4 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/93#discussion_r1095310749" expanded>

from and to variables and user inputs use the same name, potentially confusing
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/93#discussion_r1095311546" expanded>

unmarkAsDone or markAsUndone preferred
unmarkAsNotDone double negative is misleading
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/93#discussion_r1095311983" expanded>

can consider using arrayList to handle variable amount of inputs
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/93#pullrequestreview-1282220857" expanded>

**Review Status:** COMMENTED

Very nice work with inheritance and extension of task class to subclasses
</panel>

</panel>

<panel type="info" header="### 196. LEON..PANG `@YatPang` (3 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/208#discussion_r1095379964" expanded>

Try not to use magic numbers. Can consider using an aptly named variable.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/208#discussion_r1095383981" expanded>

Can consider using switch case instead of if else to decide what to do based on the first word entered
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/208#pullrequestreview-1282318654" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 197. AUNG..AING `@Aung-Phone-Naing` (3 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/57#discussion_r1095378782" expanded>

Good use of protected access-modifier to ensure no other classes can directly access and modify it.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/57#discussion_r1095379645" expanded>

Good practice to use inheritance from Task class and then overriding for Deadline and Todo classes respectively for printing different types of outputs.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2223S2/ip/pull/57#pullrequestreview-1282316973" expanded>

**Review Status:** COMMENTED

Overall I think you did a great job with the practices!
</panel>

</panel>

<panel type="info" header="### 198. ONG ..MIAH `@miahjerry` (0 comments)"  collapsed>

n/a
</panel>

<panel type="info" header="### 199. SAMU.. WEE `@Samueltansw` (0 comments)"  collapsed>

n/a
</panel>

<panel type="info" header="### 200. VISH..SHNU `@vishnuvk47` (0 comments)"  collapsed>

n/a
</panel>

<panel type="info" header="### 201. LEE ..OSES `@moseslee9012` (0 comments)"  collapsed>

n/a
</panel>

<panel type="info" header="### 202. MUHA..HANI `@AkmalHanis` (0 comments)"  collapsed>

n/a
</panel>

<panel type="info" header="### 203. BUI .. NAM `@arsdorintbp2003` (0 comments)"  collapsed>

n/a
</panel>

<panel type="info" header="### 204. OUY ..RETH `@victorouy` (0 comments)"  collapsed>

n/a
</panel>

<panel type="info" header="### 205. NG Y..JIAN `@ngyongjian` (0 comments)"  collapsed>

n/a
</panel>
