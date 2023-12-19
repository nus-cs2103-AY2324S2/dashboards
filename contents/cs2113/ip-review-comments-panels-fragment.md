
<panel type="info" header="### 1. YANG..TIAN `@skylee03` (84 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/68#discussion_r1318399790" expanded>

Try to avoid complicated expressions.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/68#discussion_r1318400668" expanded>

Try to avoid long methods. You can try to extract part of the code into other methods.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/68#discussion_r1318402318" expanded>

It would be better to have a space after "while".
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/68#discussion_r1318408371" expanded>

Strings are usually (and by default) initialized to `null`. It's weird to initialize it to a string that contains a space.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/68#pullrequestreview-1615111269" expanded>

**Review Status:** COMMENTED

The code quality is very high!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318352017" expanded>

```suggestion
public class Deadline extends Task {
```
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318353681" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318354022" expanded>

```suggestion
    public Deadline(String description, String deadline) {
```
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318354105" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318355715" expanded>

```suggestion
    public void show() {
```
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318355921" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318357233" expanded>

```suggestion
        } else {
```
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318357926" expanded>

According to our coding standards, it is recommended to write the else branch like this.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318358312" expanded>

```suggestion
        if (isDone) {
```
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318358444" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions. It is also suggested to add a space after `if`.
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318360864" expanded>

```suggestion
    public static void printLine() {
```
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318361398" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318361650" expanded>

```suggestion
    public static void main(String[] args) {
```
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318361724" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318365823" expanded>

```suggestion
            } else if (keyword.equals("mark")) {
```
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318365910" expanded>

According to our coding standards, it is recommended to write the else branch like this.
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318367320" expanded>

```suggestion
                } catch (NumberFormatException e){
```
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318367796" expanded>

According to our coding standards, it is recommended to write a try-catch statement like this.
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318369746" expanded>

```suggestion
            } else if (keyword.equals("todo")) {
```
</panel>

<panel  header="**25 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318370169" expanded>

According to our coding standards, it is recommended to write the else branch like this.

</panel>

<panel  header="**26 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318370905" expanded>

```suggestion
            } else if (keyword.equals("deadline")) {
```
</panel>

<panel  header="**27 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318370985" expanded>

According to our coding standards, it is recommended to write the else branch like this.
</panel>

<panel  header="**28 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318371328" expanded>

```suggestion
            }  else if (keyword.equals("event")) {
```
</panel>

<panel  header="**29 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318371415" expanded>

According to our coding standards, it is recommended to write the else branch like this.
</panel>

<panel  header="**30 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318371856" expanded>

```suggestion
            } else {
```
</panel>

<panel  header="**31 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318371937" expanded>

According to our coding standards, it is recommended to write the else branch like this.
</panel>

<panel  header="**32 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318372328" expanded>

```suggestion
        } else {
```
</panel>

<panel  header="**33 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318372465" expanded>

According to our coding standards, it is recommended to write the else branch like this.
</panel>

<panel  header="**34 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318372937" expanded>

```suggestion
        } else {
```
</panel>

<panel  header="**35 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318373023" expanded>

According to our coding standards, it is recommended to write the else branch like this.
</panel>

<panel  header="**36 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318373365" expanded>

```suggestion
        } else {
```
</panel>

<panel  header="**37 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318373454" expanded>

According to our coding standards, it is recommended to write the else branch like this.
</panel>

<panel  header="**38 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318374252" expanded>

```suggestion
public class Event extends Task {
```
</panel>

<panel  header="**39 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318374350" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**40 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318374520" expanded>

```suggestion
    public Event(String description, String start, String end) {
```
</panel>

<panel  header="**41 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318374599" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**42 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318374843" expanded>

```suggestion
public class Task {
```
</panel>

<panel  header="**43 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318374924" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**44 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318375086" expanded>

```suggestion
    public Task(String description) {
```
</panel>

<panel  header="**45 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318375165" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**46 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318375293" expanded>

```suggestion
    public void show() {
```
</panel>

<panel  header="**47 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318375368" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**48 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318375549" expanded>

```suggestion
        if (isDone) {
```
</panel>

<panel  header="**49 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318375673" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**50 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318375838" expanded>

```suggestion
    public void mark() {
```
</panel>

<panel  header="**51 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318375902" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**52 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318376076" expanded>

```suggestion
    public void unmark() {
```
</panel>

<panel  header="**53 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318376164" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**54 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318376490" expanded>

```suggestion
public class ToDo extends Task {
    public ToDo(String description) {
```
</panel>

<panel  header="**55 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318376577" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**56 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318376748" expanded>

```suggestion
    public void show() {
```
</panel>

<panel  header="**57 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318376814" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**58 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318377042" expanded>

```suggestion
        if (isDone) {
```
</panel>

<panel  header="**59 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318377107" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**60 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318378318" expanded>

```suggestion
        while (true) {
```
</panel>

<panel  header="**61 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318378572" expanded>

It is suggested to add a space after `while`.
</panel>

<panel  header="**62 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318378883" expanded>

```suggestion
            if (response.equals("bye")) {
```
</panel>

<panel  header="**63 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318379000" expanded>

It is suggested to add a space after `if`.
</panel>

<panel  header="**64 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318379426" expanded>

```suggestion
                if (words.length != 2) {
```
</panel>

<panel  header="**65 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318379623" expanded>

It is suggested to add a space after `if`.
</panel>

<panel  header="**66 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318380631" expanded>

```suggestion
                try {
                    int markIndex = Integer.parseInt(words[1]);

                    if (markIndex < 1 || markIndex > numTasks) {
```
</panel>

<panel  header="**67 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318380732" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**68 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318381336" expanded>

```suggestion
                try {
```
</panel>

<panel  header="**69 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318381406" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**70 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318381908" expanded>

```suggestion
                    if (markIndex < 1 || markIndex > numTasks) {
```
</panel>

<panel  header="**71 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318382041" expanded>

It is suggested to add a space after `if`.
</panel>

<panel  header="**72 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318382607" expanded>

```suggestion
                } catch (NumberFormatException e) {
```
</panel>

<panel  header="**73 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318382667" expanded>

According to our coding standards, it is recommended to write a try-catch statement like this.
</panel>

<panel  header="**74 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318382984" expanded>

```suggestion
                if (words.length != 2) {
```
</panel>

<panel  header="**75 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318383074" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**76 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318383598" expanded>

```suggestion
            } else if (keyword.equals("unmark")) {
```
</panel>

<panel  header="**77 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318383683" expanded>

According to our coding standards, it is recommended to write the else branch like this.
</panel>

<panel  header="**78 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318384557" expanded>

```suggestion
    public void show() {
        System.out.print("[D][");
        if (isDone) {
```
</panel>

<panel  header="**79 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318384620" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**80 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318386169" expanded>

```suggestion
    static private Task[] tasks = new Task[100];
```
</panel>

<panel  header="**81 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318386289" expanded>

Plural form should be used on names representing a collection of objects.
</panel>

<panel  header="**82 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318387033" expanded>

```suggestion
                try {
```
</panel>

<panel  header="**83 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#discussion_r1318387105" expanded>

Adding a space before the curly bracket is more consistent with our coding conventions.
</panel>

<panel  header="**84 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/78#pullrequestreview-1615018193" expanded>

**Review Status:** COMMENTED

Aside from violating coding guidelines a bit, well done!
</panel>

</panel>

<panel type="info" header="### 2. BENJ..MING `@bnjm2000` (30 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/13#discussion_r1316948014" expanded>

"[X" + "] " can be combined.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/13#discussion_r1316948733" expanded>

great customisations
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/13#discussion_r1316952593" expanded>

should be indented
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/13#discussion_r1316952933" expanded>

should be indented
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/13#discussion_r1316953928" expanded>

great optimisation
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/13#discussion_r1316954557" expanded>

consider printing in multiple lines for better code readability
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/13#pullrequestreview-1612817279" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/43#discussion_r1316681440" expanded>

Should be using "this.isDone = done"
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/43#discussion_r1316681484" expanded>

Can input parameters based on the command.
What if I input "mark 1 false"?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/43#pullrequestreview-1612355463" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/48#discussion_r1316920312" expanded>

Good use of static variable and naming
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/48#discussion_r1316929042" expanded>

leave a space between listTasks() and {
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/48#discussion_r1316933074" expanded>

good use of switch statement
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/48#discussion_r1316935854" expanded>

use "this.isDone" in setter methods
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/48#pullrequestreview-1612773341" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/49#discussion_r1317028691" expanded>

Use this.isDone for setter methods
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/49#discussion_r1317029706" expanded>

maybe check for "bye" input here
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/49#discussion_r1317031323" expanded>

else statement should be right after close bracket
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/49#discussion_r1317032550" expanded>

good job checking for invalid inputs
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/49#discussion_r1317032874" expanded>

else if statement should be right after "}"
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/49#pullrequestreview-1612934141" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/58#discussion_r1316738605" expanded>

"else" statement should be right after "}"
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/58#discussion_r1316739150" expanded>

should be "this.isMarked = true;" since it is a boolean variable
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/58#discussion_r1316741694" expanded>

avoid [arrowhead style code](https://blog.codinghorror.com/flattening-arrow-code/)
</panel>

<panel  header="**25 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/58#discussion_r1316742094" expanded>

awesome customisation
</panel>

<panel  header="**26 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/58#pullrequestreview-1612471068" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**27 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/62#discussion_r1316744929" expanded>

Maybe can check "bye" condition here
</panel>

<panel  header="**28 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/62#discussion_r1316745281" expanded>

good job checking for invalid inputs
</panel>

<panel  header="**29 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/62#discussion_r1316746704" expanded>

Creative way to parse in boolean variables
</panel>

<panel  header="**30 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/62#pullrequestreview-1612484256" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 3. YEON..JEHO `@ICubE-` (23 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/7#discussion_r1316715740" expanded>

I love your program's name :D
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/7#discussion_r1316716142" expanded>

It would be good to insert blank line to separate variables and methods.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/7#discussion_r1316719361" expanded>

I think this code isn't used. Please don't leave dummy code.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/7#discussion_r1316719797" expanded>

A constant variable name has to be uppercased.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/7#discussion_r1316720928" expanded>

Class name would be good to written not in plural.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/7#discussion_r1316721197" expanded>

I think this code isn't used.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/7#discussion_r1316725117" expanded>

Task class has two parts. Static parts managing all tasks, instance parts of individual tasks.
It would be good to separate two parts to individual class.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/7#discussion_r1316977799" expanded>

I mean, blank line between line 3 and line 4.
You did well, no space between method name and parenthesis.

Below is what I meant.
```
private String date;
// Blank line
public Deadlines(String description, String date) {
```

It's kinda related to code quality, not coding standard. Not necessary, but good for readability.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/7#discussion_r1316990023" expanded>

The class of your code is for single task, so the name of it should be singular.
If the class was related to multiple tasks, (e.g. list of tasks) then the name of class should be plural.
Similar as variable names.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/7#discussion_r1317000461" expanded>

It's up to you, but yes, I suggest to do it.
Also, if you don't mind, trying to reduce similar codes will make your code more clear!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/7#pullrequestreview-1612420038" expanded>

**Review Status:** COMMENTED

I recommend you to divide your Task class into two parts; task manager and task itself.
You can use child class and override methods. (Todo, Deadline, Event)
Also, please remove dummy code.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/7#pullrequestreview-1612863046" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/7#pullrequestreview-1612877429" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/7#pullrequestreview-1612891179" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/46#discussion_r1316711897" expanded>

It will be better to insert spaces beside plus.
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/46#discussion_r1316712234" expanded>

It will be better to insert spaces beside plus.
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/46#discussion_r1316712448" expanded>

It will be better to insert spaces beside minus.
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/46#discussion_r1316712836" expanded>

It will be better to insert spaces beside minus.
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/46#discussion_r1316712846" expanded>

It will be better to insert spaces beside plus and minus.
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/46#discussion_r1316713433" expanded>

It will be better to insert spaces beside plus and minus.
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/46#discussion_r1316713497" expanded>

It will be better to insert spaces beside plus.
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/46#discussion_r1316713560" expanded>

It will be better to insert spaces beside minus.
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/46#pullrequestreview-1612412716" expanded>

**Review Status:** COMMENTED

I like your code with fine coding standard! Inserting spaces beside the plus and minus would make it better.
</panel>

</panel>

<panel type="info" header="### 4. TOH ..HENG `@yicheng-toh` (20 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/22#discussion_r1318372260" expanded>

- I like how you divided these long statements into multiple lines for readability.


</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/22#discussion_r1318401435" expanded>

Perhaps the else statement could be on the same line as the closing bracket from the previous if statement?
```suggestion
        }else if (text.equals("deadline")){
```
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/22#discussion_r1318404016" expanded>

Should the number of spacing be reduced?

```suggestion
                    Arrays.toString(answer[j].markAsDone) + " " + answer[j].toBeDone
                    + " (from: " + answer[j].startTime
                    + " to: "+ answer[j].endTime + ")");
```
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/22#discussion_r1318404540" expanded>

Perhaps the else statement could be on the same line as the closing bracket from the previous if statement?
```suggestion
        }else if (answer[j].taskType[0] == "E"){
```
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/22#discussion_r1318650883" expanded>

Perhaps you could standardise the naming for these variables since they are similar, using noun for the variables.
```suggestion
    markCommand = "mark";
    unmarkCommand = "unmark";
```
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/22#pullrequestreview-1615056955" expanded>

**Review Status:** COMMENTED

Looks good!
Perhaps can consider the minor changes suggested.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#discussion_r1318707101" expanded>

You could consider giving verb-like names for the method.
```suggestion
    public boolean checkIsDone() {
```
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#discussion_r1318711835" expanded>

I like how you create new lines with correct indentations when the code gets too long.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#discussion_r1318713173" expanded>

I like how you add spaces to separate different actions in the main method.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#discussion_r1318719568" expanded>

Perhaps you could make this more concise. There are some of this instance in later part of the code.
```suggestion
    public String toString() {
        return "[D]" + super.toString() + "(by:" + by + ")";
    }
```
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#discussion_r1318722225" expanded>

I like the use of 'this' to differentiate between class variables and function inputs.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#pullrequestreview-1615595431" expanded>

**Review Status:** COMMENTED

Looks good!
Do watch out for areas of code that could be more concise.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/67#discussion_r1318690979" expanded>

You might want to add some spaces between the package and the class.
```suggestion
package PACKAGE_NAME;

public class DeadlineTask {
}
```
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/67#discussion_r1318697762" expanded>

I like how you handle invalid inputs for the switch case.
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/67#discussion_r1318701463" expanded>

Perhaps you could consider creating a separate method for the switch case
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/67#pullrequestreview-1615570227" expanded>

**Review Status:** COMMENTED

Code mostly follows required standard and quality.
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/79#discussion_r1318433698" expanded>

I like how you use switch statements for the various instructions. This makes your code very neat.
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/79#discussion_r1318438574" expanded>

Perhaps the method could sound more verb-like?

```suggestion
    public boolean checkIsDone() {
```
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/79#discussion_r1318666049" expanded>

Good use of enum for the various tasks!
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/79#pullrequestreview-1615163258" expanded>

**Review Status:** COMMENTED

Looks good and neat!
</panel>

</panel>

<panel type="info" header="### 5. NIHA..IAJI `@nihalzp` (18 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/20#discussion_r1318352950" expanded>

```suggestion
     public static boolean isMark(String input) {
        if (input.length() >= 4) {
            if ("mark".equalsIgnoreCase(input.substring(0,4))) {
                return true;
            }
```
Consider appropriate adding spaces to make code more readable. I noticed the same issue appear throughout the code as well.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/20#discussion_r1318357664" expanded>

```suggestion
        bool isValidLen = (input.length()>=6);
        return (isValidLen && "unmark".equalsIgnoreCase(input.substring(0,6)))
```
Maybe consider not having nested conditional if not necessary
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/20#discussion_r1318358273" expanded>

Same as previous comment. I noticed this suggested improvement in other places as well.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/20#discussion_r1318361175" expanded>

Consider using a more descriptive name for code readability 
```suggestion
     public static boolean isMarkCommand(String input) {
```
I have noticed the same issue in other places too.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/20#discussion_r1318362626" expanded>

Consider splitting it into multiple parts; current form is bit hard to read and understand.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/20#discussion_r1318363021" expanded>

Add appropriate space.
```suggestion
                tasks[taskCount] = new Deadline(taskName, deadline);
```
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/20#discussion_r1318364024" expanded>

Since there are lots of cases, consider using `switch` statement for better code readability.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/20#discussion_r1318365791" expanded>

Consider creating separate files for each of the classes.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/20#discussion_r1318367805" expanded>

```suggestion
    @Override
    public String toString(){
```
Add the decorator to add more semantic meaning that this method is overriding the parent class method.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/20#pullrequestreview-1615020765" expanded>

**Review Status:** COMMENTED

Apart from some minor stylistic, quality issues, the code looks good.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/25#discussion_r1318373326" expanded>

Consider using `switch` statement instead of if-else as there are lots of cases to consider
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/25#discussion_r1318374722" expanded>

Since this line is repeated numerous times throughout the code, it feel it would be better if there were a function that does this job.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/25#discussion_r1318376972" expanded>

Consider using `System.out.printf` to print statement with lots of variable; this will lead to cleaner code; I have noticed the same issue in other places as well.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/25#discussion_r1318379276" expanded>

```suggestion
    public String getType() {
        return "[0]";
    }
```
The subclass overridden methods, return string with "[]"; consider using it here as well to make code look consistent. Also, make use to add space before braces.
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/25#discussion_r1318382691" expanded>

```suggestion
import java.util.Scanner;

public class Sun {
```
I feel add a blank line between import and Class definition would make code easier to read and understand.
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/25#discussion_r1318386871" expanded>

Since this a constant value, maybe make it `final static String LOGO`?
```suggestion
        final static String LOGO = " ____               \n"
                    + "| ___| _   _  ______ \n"
                    + "| \\__ | | | || /--\\ |\n"
                    + " \\___|| |_| || |  | |\n"
                    + "/____/ \\__,_||_|  |_|\n";
```
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/25#discussion_r1318389217" expanded>

This line is printed inside every if-else, maybe consider moving it outside the the whole conditional block? Also same for line 23.
```suggestion
                    System.out.println("____________________________________________________________");
```
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/25#pullrequestreview-1615058479" expanded>

**Review Status:** COMMENTED

Code seems very structured and clean. Nice job. There are some minor code quality issues but apart from that LGTM.
</panel>

</panel>

<panel type="info" header="### 6. LIOW..ELLE `@janelleenqi` (14 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/56#discussion_r1318365325" expanded>

you can choose to combine this to become a setter method like "void setFound(boolean isFound);"

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/56#discussion_r1318367509" expanded>

GOOD JOB for following the naming conventions (PascalCase for class and camelCase for variables)!!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/56#discussion_r1318371575" expanded>

Wow! Good job keeping long lines short by using line wrapping!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/56#discussion_r1318375661" expanded>

you did well by explicitly commenting on the purpose of functions you added!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/56#discussion_r1318377212" expanded>

i love your instructional introduction for easier usage by your users!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/56#discussion_r1318380125" expanded>

```suggestion
            int index = 0;
```
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/56#discussion_r1318380587" expanded>

consider adding spaces to ensure consistency
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/56#pullrequestreview-1615046320" expanded>

**Review Status:** COMMENTED

Good job! Your code was organised and very readable!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/70#discussion_r1318389229" expanded>

you can consider spacing out (added new lines between) your functions for better readability
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/70#discussion_r1318390489" expanded>

having a new file for each class can keep your code more organised (abstraction)
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/70#discussion_r1318391802" expanded>

you can consider combining this to become a setter method like "void setFound(boolean isFound);"
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/70#discussion_r1318392713" expanded>

You did well in following the naming conventions (PascalCase for class and camelCase for variables)!!
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/70#discussion_r1318397069" expanded>

Great job in explicitly commenting on the purpose of functions you added!
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/70#pullrequestreview-1615084413" expanded>

**Review Status:** COMMENTED

Overall, GOOD JOB! There are some minor changes you can make for readability and organisation (using a switch statement sounds good!). You did well commenting each function and following the naming conventions!
</panel>

</panel>

<panel type="info" header="### 7. LIN ..ZHAO `@marklin2234` (17 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#discussion_r1316713210" expanded>

add space
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#discussion_r1316713575" expanded>

Why do we need a getter function for a public variable?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#discussion_r1316714314" expanded>

Instead of incrementing numberOfTasks in the constructor of every child class, simply increment it in the constructor of Task since the super() will call the parent constructor anyways.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#discussion_r1316715127" expanded>

nitpick: can just use \n instead of System.lineSeparator()
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#discussion_r1316715463" expanded>

avoid magic numbers
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#discussion_r1316716020" expanded>

DRY. Maybe make a function that handles the "-------" and call that function instead.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#discussion_r1316717056" expanded>

Its probably better to handle this output message within their respective classes. (Similar to your toString override).
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#discussion_r1316720605" expanded>

This else if statement is not necessary. by the time this section runs, previous else ifs will ensure that it will not start with "mark", "unmark" and "bye".
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#discussion_r1316721021" expanded>

what is this id doing, it is not used anywhere?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#discussion_r1316725425" expanded>

You shouldn't need to type cast here because of polymorphism. 
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#pullrequestreview-1612414796" expanded>

**Review Status:** CHANGES_REQUESTED


</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#pullrequestreview-1612433750" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#pullrequestreview-1612435222" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#pullrequestreview-1612445590" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/59#discussion_r1316721409" expanded>

Don't need the this here.
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/59#discussion_r1316723056" expanded>

You repeat the Utils.printDivider() function very often, perhaps you can create a wrapper function to handle this for you.
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/59#pullrequestreview-1612436415" expanded>

**Review Status:** COMMENTED

LGTM!
</panel>

</panel>

<panel type="info" header="### 8. TAN ..THAN `@Jonoans` (14 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/30#discussion_r1316718750" expanded>

Might have missed a space here!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/30#discussion_r1316719821" expanded>

Indentation here may be different from other lines of similar nature i.e. line 74 - 79 has another level of indentation
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/30#discussion_r1316721410" expanded>

It may be more readable to move this into a variable by itself :D
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/30#discussion_r1316724158" expanded>

Maybe for static strings, can be defined as const / final variable
For the "Now your list is sparkling with...", could also be declared as a final string with "%s" format specifier
- Can use String.format()
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/30#pullrequestreview-1612427630" expanded>

**Review Status:** COMMENTED

Overall the code looks really neat tbh!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/71#discussion_r1316725310" expanded>

Variable could be renamed to conform to coding standards for boolean
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/71#discussion_r1316725754" expanded>

Consider using ALL_CAPS SNAKE_CASE variable for constants
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/71#discussion_r1316726806" expanded>

Strings like this could be defined as a constant variable in the program!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/71#discussion_r1316727097" expanded>

Maybe the arg could be renamed to name
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/71#discussion_r1316728591" expanded>

Missing a space here between while and (running)!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/71#discussion_r1316728791" expanded>

Missing a space here between switch and (type)!
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/71#discussion_r1316738873" expanded>

Can try to avoid long methods if possible, but tbh in your case it may not be easy to reduce the line count for this method any further :D
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/71#pullrequestreview-1612445383" expanded>

**Review Status:** COMMENTED

Your code is quite well organised, though I think there are some minor things you might have missed for coding standard violations!
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/71#pullrequestreview-1612472946" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 9. MAN ..HENG `@spinoandraptos` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/8#discussion_r1316728040" expanded>

indentation would be good for the case statements
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/8#discussion_r1316729316" expanded>

i+1 is technically a  magic number, will be good to show it is task index
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/8#discussion_r1316734855" expanded>

taskId -1 magic number
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/8#discussion_r1316735050" expanded>

good catch! error handling is well considered 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/8#pullrequestreview-1612449828" expanded>

**Review Status:** COMMENTED

nice!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/73#discussion_r1316715947" expanded>

type is ambiguous, can be mistaken as a verb, recommend to use taskType
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/73#discussion_r1316718663" expanded>

number is ambiguous, recommend to use taskNumber 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/73#discussion_r1316719841" expanded>

noun should not be named with a verb in it, recommend to combine with previous line and use taskNumber as previously mentioned
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/73#discussion_r1316720625" expanded>

using -1 magical number, would be good to define what the -1 means
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/73#discussion_r1316721047" expanded>

variable name can be mistaken as an action, recommend to use unmarkedTaskNo
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/73#discussion_r1316723140" expanded>

unnecessary spaces for start and ends of brackets 
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/73#discussion_r1316723941" expanded>

curly bracket should start on a newline 
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/73#pullrequestreview-1612420372" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 10. KHER..ALAN `@Brian030601` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/13#discussion_r1319332977" expanded>

Size for what? Maybe rename it as todoListSize
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/13#discussion_r1319333693" expanded>

Deep nesting issue here. Try narrowing the code down to one if conditionals
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/13#discussion_r1319334497" expanded>

This is some amazing work.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/13#discussion_r1319334792" expanded>

Too much coding in one line
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/13#discussion_r1319335571" expanded>

Agreed here. Should correct the naming
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/13#discussion_r1319336915" expanded>

consider adding comments here and there
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/13#pullrequestreview-1616645384" expanded>

**Review Status:** COMMENTED

Hey, overall, your program looks great. It follows the code quality guidelines. There are some minor issues, but they can be taken care of. Great work.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/18#discussion_r1319320325" expanded>

Instead of manually typing your BotName, you should create a final string variable and save it for future use. It can be like: public final string BOT_NAME = TUM.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/18#discussion_r1319325855" expanded>

Line #23 is quite long. Maybe you should break it up into separate line.
```suggestion
                    System.out.println("     " + (i+1) + ".[" + taskList.get(i).getStatusIcon() + "] " 
                    + taskList.get(i).getDescription());
```
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/18#discussion_r1319326856" expanded>

You should find a different solution here. Conditionals inside conditionals could be confusing and hard to interpret in the future.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/18#discussion_r1319327684" expanded>

```suggestion
        Scanner in = new Scanner(System.in);
        String line = in.nextLine();
```
Could be more effective
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/18#discussion_r1319329589" expanded>

Appreciate that you are adding a comment, but other lines need comments too
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/18#pullrequestreview-1616629094" expanded>

**Review Status:** COMMENTED

Overall, your code was organized and easy to follow. There are some miner coding standard issues that needs to be fixed. Except those, things look neat and great. Good job.
</panel>

</panel>

<panel type="info" header="### 11. JOAN..LING `@JoanneJo` (13 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/7#discussion_r1317068357" expanded>

Should the variable name be in all uppercase if it is a constant value? I noticed this constant in another class too.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/7#discussion_r1317074205" expanded>

Perhaps can wrap the lines to keep it at less than 120 characters?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/7#discussion_r1317084850" expanded>

Would it be better to rename the boolean variable to sound like a boolean?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/7#discussion_r1317096009" expanded>

I like how neat the if-else statement is!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/7#discussion_r1317105315" expanded>

I think it is suggested to have white spaces between the operators? I noticed this is some other lines too.
```suggestion
        System.out.println("Now you have " + (listCount + 1) + " task(s) in the list.");
```
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/7#pullrequestreview-1612996823" expanded>

**Review Status:** COMMENTED

The code looks great overall with minor issues
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/59#discussion_r1317162093" expanded>

I think the variable should be in plural form to represent a collection of commands?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/59#discussion_r1317164296" expanded>

Would be better to have a space before the "else" to standardise the form.
```suggestion
            } else {
```
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/59#discussion_r1317173638" expanded>

Is getIsDone() necessary? Perhaps can use task.isDone directly.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/59#discussion_r1317177086" expanded>

Perhaps can take note of the spacing? I noticed the spacing is inconsistent in other parts too.
```suggestion
    public static void printDivider() {
```
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/59#discussion_r1317180260" expanded>

Should the variable names be all uppercase if it is a constant?
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/59#discussion_r1317188141" expanded>

Maybe can leave a blank line between declaration of variables and methods?
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/59#pullrequestreview-1613137377" expanded>

**Review Status:** COMMENTED

Good work with the code. Just a few nits to consider.
</panel>

</panel>

<panel type="info" header="### 12. NG L..IXON `@NgLixuanNixon` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#discussion_r1316712476" expanded>

Maybe can consider added a utility function to print this divider so you dont need to type out so long every time, and it will make it a bit neater.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#discussion_r1316715877" expanded>

Use indexFrom to fit into coding standards
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#discussion_r1316715992" expanded>

Use indexTo here as well
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#discussion_r1316717998" expanded>

good use of text wrapping to make your code neater
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#discussion_r1316719183" expanded>

Overall keeps to the coding standard done very well, Good job!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#pullrequestreview-1612413530" expanded>

**Review Status:** COMMENTED

Very good use of coding standards, keep up the good work!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/57#discussion_r1316728019" expanded>

try using multiple files instead of clumping everything here.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/57#discussion_r1316730763" expanded>

can consider creating a final variable called parts[1] instead of just putting it there as it will be clearer for code reading
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/57#discussion_r1316731691" expanded>

think can change the naming of line into input as it is clearer
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/57#discussion_r1316734887" expanded>

Good consideration if the task number falls outside the bound
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/57#discussion_r1316736580" expanded>

All these if case executions can be created as a method like "printList, unmark, mark" which will include all the printing so that your overall input if else block can be neater and more readable
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/57#pullrequestreview-1612449803" expanded>

**Review Status:** COMMENTED

Overall ideas are good but need to start coding in a more OOP style 
</panel>

</panel>

<panel type="info" header="### 13. ROHI..THAN `@rohitcube` (20 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/32#discussion_r1318366020" expanded>

This block extracts the description for a Todo task. It first sets description to the entire input line. If the line starts with "todo", it extracts the description by removing the first 5 characters (length of "todo"). 

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/32#discussion_r1318373287" expanded>

Consider using a switch statement instead of an 'if else'. This can make the code more concise and readable in cases like this where multiple branches depend on the value of a single variable.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/32#discussion_r1318375178" expanded>

I noticed the same issue in the other methods. Consider refactoring the addTodo, addEvent, and addDeadline methods. The repeated code for adding tasks could be extracted into a separate method for better maintainability.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/32#discussion_r1318377018" expanded>

Overall, code is well-structured and organized. It effectively interacts with the user and provides clear feedback. The methods are appropriate, enhancing readability and maintainability. However, additional error handling for unexpected user input could be considered to enhance user experience.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/32#discussion_r1318380470" expanded>

Nice use of super() to call the constructor of the superclass (Task) with the 'description' argument. This ensures that the 'description' field is properly initialized.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/32#pullrequestreview-1615047362" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/32#pullrequestreview-1615058421" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/32#pullrequestreview-1615061285" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/32#pullrequestreview-1615064036" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/32#pullrequestreview-1615069453" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/80#discussion_r1318385960" expanded>

Very clear naming of the methods. Makes it readable and easy to understand. 
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/80#discussion_r1318387825" expanded>

Is it better to handle the exception more gracefully rather than printing the stack trace and breaking the switch block? For example, could we log the error and send a user-friendly message instead?
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/80#discussion_r1318388059" expanded>

Could it be clearer to use Arrays.copyOfRange() here? It might make the code more readable.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/80#discussion_r1318390681" expanded>

Would it be more efficient to store the result of bot.getTasks().get(index - 1) in a variable before sending it as a message? This way, we wouldn't need to retrieve it twice.
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/80#discussion_r1318392112" expanded>

Hi Zhengdao! Hope your health got better over the holidays!
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/80#pullrequestreview-1615077900" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/80#pullrequestreview-1615081136" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/80#pullrequestreview-1615081672" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/80#pullrequestreview-1615087867" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/80#pullrequestreview-1615091199" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 14. HOO ..HONG `@hooami` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/2#discussion_r1316730060" expanded>

Might not be a good idea upload a binary to your repo
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/2#discussion_r1316735105" expanded>

Avoid long methods >30 LOC
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/2#discussion_r1316744266" expanded>

Use more specific exceptions rather than catching any exception
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/2#discussion_r1316746840" expanded>

Avoid catching all exception
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/2#discussion_r1316746925" expanded>

Avoid catching all exception
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/2#discussion_r1316746963" expanded>

Avoid catching all exception
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/2#pullrequestreview-1612453417" expanded>

**Review Status:** COMMENTED

Great code!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/33#discussion_r1316718933" expanded>

Class name should be written in PascalCase (NotChatGPT)
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/33#discussion_r1316719004" expanded>

Class name should be written in PascalCase (CommandResponse)
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/33#discussion_r1316719230" expanded>

Class name should be written in PascalCase (IntroMessage)
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/33#discussion_r1316723417" expanded>

Indentation for wrapped lines should be 8 spaces (i.e. twice the normal indentation of 4 spaces) more than the parent line.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/33#pullrequestreview-1612428404" expanded>

**Review Status:** COMMENTED

Hi your code looks pretty good! :)
</panel>

</panel>

<panel type="info" header="### 15. CHEU..YUEN `@KenCheung18` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/20#discussion_r1318380942" expanded>

It's good to check the length so if some similar string typed in your program can still identify the correct command
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/20#discussion_r1318382787" expanded>

For toString you can call the superclass function toString()
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/20#discussion_r1318386973" expanded>

Since this is a loop so you can put userInput outside the if statement
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/20#discussion_r1318388697" expanded>

Can improve this because this is not neccessary the 6th substring
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/20#discussion_r1318392111" expanded>

taskCount can put to task.java since this is a task static int
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/20#pullrequestreview-1615070156" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/37#discussion_r1318356349" expanded>

Good job, separating the string to multiple line is easier to read
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/37#discussion_r1318362073" expanded>

The name of String can change so it's easier to understand
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/37#discussion_r1318368186" expanded>

There is no indentation for case in Java coding standard
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/37#discussion_r1318369414" expanded>

This is good that following the java coding standard to only import the package needed

</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/37#discussion_r1318370995" expanded>

can write some comment to make it easier to understand
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/37#pullrequestreview-1615029488" expanded>

**Review Status:** COMMENTED

Good job
</panel>

</panel>

<panel type="info" header="### 16. BANG..EONG `@junhyeong0411` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/13#discussion_r1319315837" expanded>

Need to remove indent (4 spaces)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/13#discussion_r1319316418" expanded>

Should be indented
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/13#discussion_r1319318885" expanded>

Good indentation
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/13#discussion_r1319319875" expanded>

good camelCase
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/13#discussion_r1319321003" expanded>

boolean variables should be named to sounds like booleans (is~~, has~~...)
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/13#pullrequestreview-1616623266" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/18#discussion_r1319325700" expanded>

To make it obvious, the name "line" can be changed like "InputLine" or "userInputLine"

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/18#discussion_r1319325876" expanded>

How about using String format?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/18#discussion_r1319326241" expanded>

I think if printing line is modulized, it will be better to read
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/18#discussion_r1319326651" expanded>

Good optimization
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/18#discussion_r1319327462" expanded>

Good abstraction
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/18#pullrequestreview-1616635807" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 17. LIEN..TING `@lctxct` (12 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/24#discussion_r1316680523" expanded>

Since these are constants, I think the names should be in uppercase? 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/24#discussion_r1316682827" expanded>

Similarly, I think these should be uppercase also since they are constants? :o 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/24#discussion_r1316683697" expanded>

The scanner is appropriately named. 👍✨
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/24#discussion_r1316686711" expanded>

Great job with the indentation down here. 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/24#pullrequestreview-1612353185" expanded>

**Review Status:** COMMENTED

Good work with the PR overall, I had a really hard time trying to find code quality violations. I think the main thing to take note of is to uppercase constant names. 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/66#discussion_r1316703846" expanded>

The number of indentations here exceed the threshold level mentioned in the code quality guide, perhaps you could move the code for the status response stuff out of the loop. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/66#discussion_r1316706806" expanded>

Could consider changing the name here since `updateTask` seems to be more general and could be referring to updating of the task name. Maybe something like `updateTaskStatus` would be more appropriate. 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/66#discussion_r1316708110" expanded>

Name could be a bit misleading since it might suggest to a reader that you're adding a message to a task? Maybe can change to `getAddedMessage`  or something like that. 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/66#discussion_r1316708633" expanded>

Name could be a bit misleading since it might suggest to a reader that you're adding a message to a task? Maybe can change to `getAddedMessage` or something like that.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/66#discussion_r1316708711" expanded>

Name could be a bit misleading since it might suggest to a reader that you're adding a message to a task? Maybe can change to `getAddedMessage` or something like that.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/66#discussion_r1316708932" expanded>

Name could be a bit misleading since it might suggest to a reader that you're adding a message to a task? Maybe can change to `getAddedMessage` or something like that.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/66#pullrequestreview-1612398882" expanded>

**Review Status:** COMMENTED

Good job, naming was done well and the code was easy to read. 
</panel>

</panel>

<panel type="info" header="### 18. CHAN..DICT `@BenedictChannn` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/24#discussion_r1316728944" expanded>

Is this appropriate? 
Consider initializing your scanner object in the main class.
Is there a need to make your scanner object final?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/24#discussion_r1316735088" expanded>

Is this necessary?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/24#discussion_r1316739322" expanded>

Consider naming the unicode to provide more information.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/24#discussion_r1316740613" expanded>

Would it be more appropriate to inline this line and line 50?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/24#pullrequestreview-1612451230" expanded>

**Review Status:** COMMENTED

Great Job! Consider some minor changes to your code
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/71#discussion_r1316714348" expanded>

Consider changing the variable name to sound like Booleans (e.g. isRunning)
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/71#discussion_r1316716576" expanded>

Should there be a break statement here?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/71#discussion_r1316718066" expanded>

Consider renaming the Boolean variable to isDone

</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/71#discussion_r1316718695" expanded>

Consider giving a more meaningful name to this variable
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/71#discussion_r1316720998" expanded>

Consider making your variable final if your logo will not change (Since your variable is all capitalized)
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/71#pullrequestreview-1612417772" expanded>

**Review Status:** COMMENTED

Remember to look through and refactor your code
</panel>

</panel>

<panel type="info" header="### 19. PUA ..RICK `@wwweert123` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/21#discussion_r1318367163" expanded>

Try to avoid deep nesting
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/21#discussion_r1318368355" expanded>

Avoid magic number "7" Put it as a named constant
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/21#discussion_r1318370076" expanded>

Main method is a bit too long. Try to abstract the functions out to other methods
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/21#discussion_r1318372065" expanded>

Code is structured logically. Good job!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/21#pullrequestreview-1615049035" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/77#discussion_r1318356768" expanded>

Good job! Use of camelCase
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/77#discussion_r1318357919" expanded>

Can use capital letters for constant eg. GREET
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/77#discussion_r1318359160" expanded>

Remember to add spacing for if else class statements eg. if (something) { 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/77#discussion_r1318362879" expanded>

Good job! names representing packages are in lower case
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/77#discussion_r1318364596" expanded>

Good job use of PascalCase for classes
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/77#pullrequestreview-1615030256" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 20. CHAN..IANG `@ChoonSiang` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/4#discussion_r1316716557" expanded>

Maybe camelcase your function name?
```suggestion
    public static void displayClosingMessage(){
```
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/4#discussion_r1316717039" expanded>

Maybe make your variable sound like boolean?
```suggestion
    private boolean isDone;
```
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/4#discussion_r1316720024" expanded>

Try to follow the standard not to indent case clause. Similar issues in your other switch case statements.
```suggestion
        switch (taskType){
        case TODO:
            String toDoDescription = input.split("todo")[1].strip();
            newTaskList[allTasks.length] = new ToDo(toDoDescription);
            break;
        case DEADLINE:
            String[] deadlineDetails = input.split("deadline")[1].strip().split("/");
            String deadlineDescription = deadlineDetails[0].strip();
            String deadlineTiming = deadlineDetails[1].strip().split("by")[1].strip();;
            newTaskList[allTasks.length] = new Deadline(deadlineDescription, deadlineTiming);
            break;
        case EVENT:
            String[] eventDetails = input.split("event")[1].strip().split("/");
            String eventDescription = eventDetails[0].strip();
            String eventStartTiming = eventDetails[1].strip().split("from")[1].strip();
            String eventEndTiming = eventDetails[2].strip().split("to")[1].strip();;
            newTaskList[allTasks.length] = new Event(eventDescription, eventStartTiming, eventEndTiming);
            break;
        }
```
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/4#discussion_r1316721377" expanded>

Try to keep line to be shorter than 120 characters. Similar issues can be found in other long lines.

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/4#pullrequestreview-1612421318" expanded>

**Review Status:** COMMENTED

LGTM. Only some cosmetic issues.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/23#discussion_r1316729447" expanded>

May want to make this final as this string will not be changed. Similar issue in other string literal
```suggestion
        final String solidLine = "\n------------------------------------------------------------------------------------------------------------------------------\n";
```
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/23#discussion_r1316731299" expanded>

Try to keep your line of code shorter than 120 characters.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/23#discussion_r1316735891" expanded>

Try to avoid long method (Main method is around 70 lines)
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/23#discussion_r1316742007" expanded>

Constant name should be in caps.
```suggestion
    private final String SOLIDLINE= "\n------------------------------------------------------------------------------------------------------------------------------\n";
```
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/23#discussion_r1316746442" expanded>

Try to avoid reusing variable that has a different purpose, instead create another variable for it for clarity purpose
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/23#pullrequestreview-1612452357" expanded>

**Review Status:** COMMENTED

Looks good generally. Some cosmetic and quality to improve
</panel>

</panel>

<panel type="info" header="### 21. EE H.. ZHI `@Hongzhii` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/54#discussion_r1318360768" expanded>

should the variable be marked as private instead of protected? it is the final class in the inheritance chain
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/54#discussion_r1318363789" expanded>

would it be better to initialise in the constructor instead of when declared?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/54#discussion_r1318365102" expanded>

would it be better to use .split(" ") and store the response in an array of strings instead of using indexOf? Might make the code more readable and easier to debug
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/54#discussion_r1318366440" expanded>

should you catch an exception where the user does not pass an integer? (Number format exception)
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/54#discussion_r1318368275" expanded>

Why use .contains instead of .equals? what if user input is "unmarked" or some other string that contains the word "unmark" within it?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/54#discussion_r1318370280" expanded>

Why is an empty string returned? Would it be better to use an else if block and modify a single "response" variable that is initialised at the start of the method?

eg.

String response = "Default response";

if(case 1){
    response  = "case 1";
}
else if(case 2){
    response = "case 2";
}

etc.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/54#pullrequestreview-1615039276" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/81#discussion_r1318353220" expanded>

should you catch the exception during the input phase? Check if 0 &gt; user input index &gt; num of items + 1
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/81#discussion_r1318355707" expanded>

what types of errors are expected? can the exception catch be more specific?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/81#discussion_r1318358631" expanded>

should this variable be marked as private instead of protected? its the final class in the inheritance chain
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/81#pullrequestreview-1615021486" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 22. TIAN..AYAN `@J-Y-Yan` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/16#discussion_r1319318315" expanded>

perheps using the name "setDone" would be more concise
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/16#discussion_r1319319542" expanded>

same suggestions as following, like for the method "setUnmarkAsDone"
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/16#discussion_r1319321145" expanded>

Maybe try not to use the double negative phrase. I would suggest to use "setNotDone" or "setUnDone".
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/16#discussion_r1319321785" expanded>

I guess "printNewTask" instead of recent task will fit with the content.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/16#discussion_r1319327748" expanded>

May I know if you are trying to add a general task object? But I think the "todo" abjects already take over a general task object
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/16#pullrequestreview-1616626450" expanded>

**Review Status:** COMMENTED

LGTM. In general, the indentation is very precise. The code looks concise and clear overall.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/58#discussion_r1319333755" expanded>

I like your welcome message. Very interesting.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/58#discussion_r1319335024" expanded>

I guess using the name "input" will be concise.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/58#discussion_r1319337286" expanded>

Maybe you could improve the error message, such as "there is no task at the kth position".
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/58#discussion_r1319338923" expanded>

Using "getMark", "getStatus" could be more precise as a getter function.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/58#pullrequestreview-1616646333" expanded>

**Review Status:** COMMENTED

LGTM. The indentation is precise. Maybe the naming of variable or method can be improved. The code overall is very readable with lots of comments. I like his customized setting of robots.
</panel>

</panel>

<panel type="info" header="### 23. CERV..DEAN `@CerIsaiah` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/22#discussion_r1318379770" expanded>

answer as a variable could be made more clear as too its function
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/22#discussion_r1318381286" expanded>

Maybe you can add comments above the functions regarding their purpose? Not necessary though for some
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/22#discussion_r1318382087" expanded>

Im a big fan of how you put this function together instead of all in the main
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/22#discussion_r1318383540" expanded>

Is there any way you can shorten the length of the print string?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/22#discussion_r1318384419" expanded>

Curious on why you decided to make the echo a class function
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/22#pullrequestreview-1615068391" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/68#discussion_r1318366449" expanded>

Could you rename this line as a variable, seeing as you use it later in your code?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/68#discussion_r1318368348" expanded>

I like the setter method being used
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/68#discussion_r1318371878" expanded>

Maybe making some variables statement could make this less verbose
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/68#discussion_r1318372373" expanded>

I like the use of functions here!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/68#pullrequestreview-1615047983" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 24. LI S..UANG `@lisizhuang-0121` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/3#discussion_r1316716810" expanded>

The main function is slightly long, perhaps could split up the cases into different functions
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/3#discussion_r1316718079" expanded>

Maybe we could use a string for printing rather than a for loop.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/3#discussion_r1316718685" expanded>

Perhaps could try not to use magic literal (6).
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/3#discussion_r1316722061" expanded>

Boolean could be named as isDone instead of done
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/3#discussion_r1316723118" expanded>

The comment does not really explain the function (returning whether task is done should be for function getDone).
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/3#pullrequestreview-1612421713" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/38#discussion_r1316728201" expanded>

Good error message for the users.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/38#discussion_r1316729193" expanded>

Magic numbers for the substring index.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/38#discussion_r1316729327" expanded>

Magic number for substring index here
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/38#discussion_r1316730066" expanded>

Magic numbers for the substring index.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/38#pullrequestreview-1612450081" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 25. JASO.. JIE `@sRanay` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/28#discussion_r1316722022" expanded>

Good use of switch
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/28#discussion_r1316723981" expanded>

Maybe can use a final variable instead for the divider instead of typing out the full line
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/28#discussion_r1316725631" expanded>

Maybe can change to break instead
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/28#discussion_r1316726288" expanded>

There should be a space after the ()
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/28#pullrequestreview-1612438283" expanded>

**Review Status:** COMMENTED

Overall the code is good, keep it up
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/40#discussion_r1316716606" expanded>

Good implementation to check for edge cases but maybe can use try catch
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/40#discussion_r1316716805" expanded>

Good use creating printLines function to print the divider
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/40#discussion_r1316717234" expanded>

Good use to check for the command
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/40#discussion_r1316717997" expanded>

Good implementation for create markDone and markNotDone
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/40#pullrequestreview-1612420417" expanded>

**Review Status:** COMMENTED

Overall the code is good, keep it up
</panel>

</panel>

<panel type="info" header="### 26. ZHU ..NGXI `@Cheezeblokz` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/43#discussion_r1319321950" expanded>

```suggestion
                int itemNumber = Integer.parseInt(input.split(" ")[1]);
                taskStore = markItem(taskStore, itemNumber);
```
Can dumb down for reader, add extra line to store the integer.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/43#discussion_r1319325361" expanded>

"mark" case throws error for non-integer 2nd input. Possible to add a condition to catch invalid inputs.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/43#discussion_r1319326326" expanded>

Nice demarcation and extraction of tasks! Less complexity in the main code.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/43#discussion_r1319329432" expanded>

Possible to combine these 2 functions, repeated lines of code.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/43#pullrequestreview-1616631177" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/76#discussion_r1319332156" expanded>

Confusing variable name, use noun for variables.
```suggestion
    protected String userName;
```
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/76#discussion_r1319333335" expanded>

Unspecific variable naming.
```suggestion
            String userCommand = scanner.nextLine();
            String[] userInputParts = userCommand.split(" ");
```
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/76#discussion_r1319334526" expanded>

Good use of inheritance in implementation of toString().
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/76#discussion_r1319337211" expanded>

Comment could be more specific, and dumb downed for the reader instead of for own purpose.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/76#pullrequestreview-1616644295" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 27. XU J..CHEN `@aaronxujiachen` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/12#discussion_r1318353819" expanded>

Clear and succinct comment!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/12#discussion_r1318355837" expanded>

Good choice to use spacing between cases, looks very neat!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/12#discussion_r1318359021" expanded>

Indentations and brackets are used properly, good job!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/12#discussion_r1318360648" expanded>

Good way to manage printing of long sentences!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/12#pullrequestreview-1615023030" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/80#discussion_r1318366690" expanded>

I like the naming of the robot!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/80#discussion_r1318369684" expanded>

Good use of try-catch function!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/80#discussion_r1318370486" expanded>

Good use of switch-case statements!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/80#discussion_r1318372146" expanded>

Good use of constructor！
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/80#pullrequestreview-1615048349" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 28. LEE ..RYAN `@bljhty` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/44#discussion_r1318366415" expanded>

Indentation can be better
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/44#discussion_r1318367536" expanded>

Follows the standard coding practices for boolean functions
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/44#discussion_r1318368265" expanded>

Proper naming for Class 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/44#discussion_r1318368881" expanded>

Good practices for comments and follows the standard coding practices
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/44#pullrequestreview-1615047934" expanded>

**Review Status:** COMMENTED

overall code follows the standard coding practices
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/56#discussion_r1318376156" expanded>

may be able to refactor the echo function to prevent code duplication
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/56#discussion_r1318377660" expanded>

may want to consider changing the name input to userInput
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/56#discussion_r1318379410" expanded>

may want to replace the naming items to taskList
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/56#discussion_r1318381553" expanded>

May like to rename this
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/56#pullrequestreview-1615062817" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 29. NG Z..I YI `@ziyi105` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/27#discussion_r1318384641" expanded>

Perhaps add a blank line before this statement to separate different groups of statements
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/27#discussion_r1318392433" expanded>

Any reason why you use the same variable name for two different things?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/27#discussion_r1318393188" expanded>

same issue as above
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/27#discussion_r1318396776" expanded>

Maybe using taskCount for the variable name would be clearer for this context?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/27#pullrequestreview-1615075893" expanded>

**Review Status:** COMMENTED

Overall LGTM. I noticed you reused a lot of variable names, is that intentional? Perhaps you can use more spaces/indentations in between statements to make your code more readable
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/32#discussion_r1318360820" expanded>

Good use of indentations for if-else statement
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/32#discussion_r1318366657" expanded>

Perhaps can combine these two methods into one setter method?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/32#discussion_r1318367943" expanded>

I like how intuitive your variable names are
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/32#discussion_r1318372585" expanded>

Perhaps consider using a clearer variable name here such as input?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/32#pullrequestreview-1615039339" expanded>

**Review Status:** COMMENTED

Looks good overall, I like how you abstracted out the methods and encapsulated most of the variables.
</panel>

</panel>

<panel type="info" header="### 30. GUAN..XIAO `@StevenGX12` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/9#discussion_r1316716411" expanded>

Good definitions of constants to be used later
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/9#discussion_r1316717934" expanded>

Can define this error message in a function/variable so that these 3 lines won't be repeated in all subsequent try-catch blocks.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/9#discussion_r1316720348" expanded>

Perhaps can change this name because splitCommand can sound like a verb used to name a function
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/9#pullrequestreview-1612421110" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/40#discussion_r1316725377" expanded>

good use of this function instead of typing out a long string
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/40#discussion_r1316726071" expanded>

Perhaps it's better to use switch statements to check for the command instead
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/40#discussion_r1316726964" expanded>

good practice 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/40#discussion_r1316729109" expanded>

Refactor code to separate file
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/40#discussion_r1316729768" expanded>

Perhaps would be better and neater if all the command handling is defined in separate functions elsewhere ans simply invoked here
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/40#pullrequestreview-1612445506" expanded>

**Review Status:** COMMENTED

Keep up the effort
</panel>

</panel>

<panel type="info" header="### 31. OU N..IANG `@onx001` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/34#discussion_r1318377994" expanded>

Should you specify command strings here?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/34#discussion_r1318378315" expanded>

I like how you only imported what you needed
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/34#discussion_r1318379081" expanded>

Is there a reason why it is called manager?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/34#discussion_r1318379322" expanded>

I like how clear the names are.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/34#pullrequestreview-1615065523" expanded>

**Review Status:** COMMENTED

Overall, I liked how clear it is and the amount of whitespace.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/86#discussion_r1318356833" expanded>

Consider incorporating these lines with the logo to avoid repeating "System.out.println".
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/86#discussion_r1318362551" expanded>

Consider adding whitespaces to improve readability.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/86#discussion_r1318365299" expanded>

Consider splitting this line into shorter chunks.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/86#discussion_r1318367059" expanded>

Any reason why you chose nested loops?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/86#pullrequestreview-1615030369" expanded>

**Review Status:** COMMENTED

I like the naming conventions used, they were clear and concise. Any reason why you chose to omit javadocs and whitespaces?
</panel>

</panel>

<panel type="info" header="### 32. TONG..HONG `@TongZhengHong` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/45#discussion_r1318374372" expanded>

Consider using classes for each command so that each command's execution will be separated for better readability and scalability
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/45#discussion_r1318377127" expanded>

Consider separating the guard clause so that the main implementation is clearer
```suggestion
                if (index > numOfItems || index <= 0) {
                        continue;
                }
                // Mark the selected task
```
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/45#discussion_r1318380132" expanded>

`numberOfTasks` is not used in the main Duke class
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/45#discussion_r1318382112" expanded>

Rename `getTotalNumberOfBicycles` functions to `getTotalNumberOfTasks`
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/45#pullrequestreview-1615060122" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/75#discussion_r1318354069" expanded>

Consider using a more descriptive name such as `taskList` instead of `theList`
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/75#discussion_r1318356599" expanded>

Consider declaring static final constants for each command (e.g. bye, list, mark) so that they can be easily referenced and updated for future use
```suggestion
private static final String BYE_COMMAND = "bye";
        while (!echo.equals("bye")) {
```
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/75#discussion_r1318359614" expanded>

Good job for using good coding standards in this file! Descriptive names are used for functions and variables
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/75#discussion_r1318365518" expanded>

Can consider making some changes to the following variables:
- `echo` should be renamed to `userInputString` instead since your default command is now adding a new task
- `userInput` should contain the scanner keyword such as `inputScanner` to better signify that it is the scanner object
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/75#pullrequestreview-1615023785" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 33. OH K.. WEI `@ken-ruster` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/61#discussion_r1318356144" expanded>

Add lines between cases for easier reading
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/61#discussion_r1318364241" expanded>

Consider moving this verbose code into a separate function
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/61#discussion_r1318364736" expanded>

Move this code into another function as well
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/61#discussion_r1318369149" expanded>

Change name to be more consistent to get/setter standards
```suggestion
    public boolean getDone() {
```
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/61#pullrequestreview-1615028981" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/74#discussion_r1318372052" expanded>

Consider using a constant / final variable to represent the line divider
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/74#discussion_r1318373600" expanded>

Consider moving code in cases to another function to reduce verbosity
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/74#discussion_r1318377154" expanded>

May cause an unintended program behaviour, consider setting the loop conditional to while the command is not bye
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/74#discussion_r1318378625" expanded>

Shift this to outside the loop and the condition becomes the loop condition
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/74#pullrequestreview-1615056630" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 34. TEO .. ZHI `@TeoHaoZhi` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#discussion_r1318367875" expanded>

Good naming convention of method name
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#discussion_r1318369066" expanded>

Good use of indentation of 4 spaces
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#discussion_r1318369881" expanded>

Good use of if-else formatting
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#discussion_r1318371311" expanded>

Good seperation to next line to not go over line char limit
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#pullrequestreview-1615050140" expanded>

**Review Status:** COMMENTED

Code is readable, everything looks good to me
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/79#discussion_r1318351047" expanded>

Good following of spacing requirements
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/79#discussion_r1318352068" expanded>

Good and clear use of switch statements
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/79#discussion_r1318353987" expanded>

Good use of if-statements, no nesting errors
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/79#discussion_r1318362058" expanded>

Good following of  naming of method conventions
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/79#pullrequestreview-1615015894" expanded>

**Review Status:** COMMENTED

Overall code is easy to read, little to no standard coding violations. Everything looks good to me
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/79#pullrequestreview-1615041228" expanded>

**Review Status:** COMMENTED

Missed out 1 comment previously, everything looks good to me
</panel>

</panel>

<panel type="info" header="### 35. NEO .. WEI `@NeoMinWei` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/50#discussion_r1318369672" expanded>

Missing space between bracket and else, should be } else {
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/50#discussion_r1318370866" expanded>

main method is quite long
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/50#discussion_r1318372048" expanded>

missing space between if condition and opening bracket, such as: ("/to")) {
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/50#discussion_r1318373236" expanded>

Good job on commenting with matching indentation to referencing code
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/50#pullrequestreview-1615052907" expanded>

**Review Status:** COMMENTED

Very good
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/84#discussion_r1318355442" expanded>

Should this variable name sound more like a boolean? for example: isDone
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/84#discussion_r1318359243" expanded>

Good job on leaving comments with same indentation
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/84#discussion_r1318363166" expanded>

Should this else be on the previous line? eg: } else {
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/84#discussion_r1318364870" expanded>

Good job on format of try-catch statements
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/84#pullrequestreview-1615027146" expanded>

**Review Status:** COMMENTED

Very good
</panel>

</panel>

<panel type="info" header="### 36. TANG..NICE `@ShaniceTang` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/10#discussion_r1318368983" expanded>

Good job! 
I like that your methods are clear and well named :)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/10#discussion_r1318370853" expanded>

Nice!
I like how you have clear indications of parameters :D
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/10#discussion_r1318380659" expanded>

I like how you add braces even though there's only one line in the if-else block
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/10#discussion_r1318383080" expanded>

Wow! I like that you used a ternary operator instead of a regular if-else block 👍 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/10#pullrequestreview-1615051798" expanded>

**Review Status:** COMMENTED

Overall I found your code is very neat and follows the coding guidelines closely. It is very easy to read and follow through. Great job! 💯 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/63#discussion_r1318401254" expanded>

Nice!
I like that you use recursion :)
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/63#discussion_r1318410815" expanded>

Could this array be named "items" instead?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/63#discussion_r1318411251" expanded>

I like that your main method is short and neat :D
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/63#discussion_r1318411923" expanded>

I like that you use else-if instead of nesting 👍 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/63#pullrequestreview-1615115123" expanded>

**Review Status:** COMMENTED

Overall, your coding quality is very well done and your code is readable! Great job! 💯 
</panel>

</panel>

<panel type="info" header="### 37. SAUN.. MIN `@NaychiMin` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/45#discussion_r1318369847" expanded>

Should the name of the array be 'storageArrays' instead of 'storageArray' as the plural form should be used on names representing a collection of objects? :)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/45#discussion_r1318375082" expanded>

Should this be named as setStatus() because it acts as a setter and by convention the method that sets a variable named something is called setSomething? :)
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/45#discussion_r1318380774" expanded>

I like how you added an additional check and an error message for the users! :)
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/45#discussion_r1318383040" expanded>

I like how you used a ternary operator instead of a traditional if-else block! 👍 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/45#pullrequestreview-1615053173" expanded>

**Review Status:** COMMENTED

Overall, I think your coding standards are quite good for the most part except in a few places where there were a few very minor coding standard violations but keep up the good work! 💯 

</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/70#discussion_r1318405499" expanded>

Any reason for separating it on different lines? It's a rather short line :)
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/70#discussion_r1318409653" expanded>

Perhaps there might be a better more suggestive naming of the variable?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/70#discussion_r1318410502" expanded>

I like how you added comments for easier readability! 👍 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/70#discussion_r1318411207" expanded>

Good job on always having proper naming of functions, classes and variables! 👍 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/70#pullrequestreview-1615119851" expanded>

**Review Status:** COMMENTED

Overall, your coding quality is very good, just small minor suggestions, not errors! Keep it up! 💯 
</panel>

</panel>

<panel type="info" header="### 38. JAME.. JEY `@James-Hong-Jey` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/8#discussion_r1316718264" expanded>

Technically* a magic number, even if it is intuitive as bound checking
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/8#discussion_r1316719962" expanded>

For switch cases, put the result on a new line
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/8#discussion_r1316721415" expanded>

Should be an informative boolean name i.e. isDone
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/8#discussion_r1316722333" expanded>

more informative variable names i.e. startDate
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/8#pullrequestreview-1612425603" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/11#discussion_r1316728229" expanded>

Not allowed to list if statements without curly braces
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/11#discussion_r1316736638" expanded>

Minor Nit: Technically -1 can be considered a magic number
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/11#discussion_r1316738037" expanded>

Define these as final variables instead of string literals
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/11#discussion_r1316738535" expanded>

Repeat code
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/11#pullrequestreview-1612450140" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 39. RYAN.. RUI `@ryanlohyr` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/53#discussion_r1318375090" expanded>

agree, correct naming is really important as readability and maintainability is important in a codebase.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/53#discussion_r1318377100" expanded>

Additionally we can use String.format to make the print statement neater and more readable.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/53#discussion_r1318378726" expanded>

There is significant code duplication in the "mark" and "unmark" cases. You can refactor this code to eliminate redundancy by extracting the common logic into a separate method. This will make the code more maintainable and less error-prone.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/53#discussion_r1318380079" expanded>

Could use string.format for this line to make it more readable
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/53#pullrequestreview-1615061198" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/70#discussion_r1318365041" expanded>

Could this be refactored into a function? As we repeat it twice 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/70#discussion_r1318366611" expanded>

could this be refactored into a switch statement for better readability?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/70#discussion_r1318367930" expanded>

The code is relatively concise, but it might benefit from some additional comments or variable names to make it more self-explanatory. For example, you could define variables with more descriptive names for the split values.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/70#discussion_r1318370705" expanded>

The code uses string concatenation to build the final string for the object's representation. While this approach works, it can be a bit less readable, especially when dealing with multiple string elements. Consider using String.format() for  improved readability and performance.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/70#pullrequestreview-1615045807" expanded>

**Review Status:** COMMENTED

Overall great job but some improvements to work on:)
</panel>

</panel>

<panel type="info" header="### 40. SHAN..XUAN `@Xuan127` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/33#discussion_r1316725230" expanded>

Have methods that are not specified but good to have, good job.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/33#discussion_r1316725796" expanded>

User input class, good to have
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/33#discussion_r1316727237" expanded>

good to have a class for introMessage
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/33#discussion_r1316728104" expanded>

good to have a boolean for state of bot
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/33#pullrequestreview-1612445275" expanded>

**Review Status:** COMMENTED

Great code standard overall, however the commits do not have message.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/57#discussion_r1316713615" expanded>

Why is the Task class not in a separate package?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/57#discussion_r1316714463" expanded>

Is 'parts' the most intuitive variable name? Perhaps change it to something that suggests it is related to the input
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/57#discussion_r1316716636" expanded>

Should you be able to access attributes of Task in Main? If Task is in a different package you will not be able to edit its attributes after refactoring. Maybe consider creating setter and getter methods.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/57#discussion_r1316717856" expanded>

is 'status' a suitable name for a String object?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/57#pullrequestreview-1612415780" expanded>

**Review Status:** COMMENTED

Remember to refactor your code
</panel>

</panel>

<panel type="info" header="### 41. LIM ..SHUA `@lckjosh` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/19#discussion_r1318368369" expanded>

I like that the greeting and farewell are in caps to indicate that they are constants!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/19#discussion_r1318369490" expanded>

Perhaps a switch statement might be useful here.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/19#discussion_r1318371299" expanded>

I like that you created a separate method to print the output with the lines!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/19#discussion_r1318372314" expanded>

Good job following the OO principles of inheritance!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/19#pullrequestreview-1615050892" expanded>

**Review Status:** COMMENTED

LGTM, keep up the good work!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/25#discussion_r1318353895" expanded>

Perhaps standardising the space between ) and { on line 5 would make things look neater. I noticed this across multiple files as well.
```suggestion
    public Event(String description, String start, String end) {
        super(description);
        this.start = start;
        this.end = end;
    }
```
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/25#discussion_r1318356168" expanded>

Good job following OO principles! I like it!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/25#discussion_r1318359447" expanded>

Maybe a space after 'do' would look nicer
```suggestion
        do {
```
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/25#discussion_r1318359944" expanded>

Maybe a space after } would look neater
```suggestion
                } else if (command.startsWith("deadline ")){
```
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/25#pullrequestreview-1615023233" expanded>

**Review Status:** COMMENTED

Overall it looks good! Just a few nits to fix.
</panel>

</panel>

<panel type="info" header="### 42. STAN..JAYA `@StanleyW00` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/43#discussion_r1319323827" expanded>

I like that you use methods for each function.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/43#discussion_r1319324575" expanded>

Perhaps you could make a method for mark and unmark a task in Task class rather than doing all in the same file.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/43#discussion_r1319325336" expanded>

Perhaps you could move the rest of the methods to above the main method.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/43#discussion_r1319326218" expanded>

I like that you use no more than 3 identations.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/43#pullrequestreview-1616633520" expanded>

**Review Status:** COMMENTED

Overall, your code is neat and readable.
Just need some few tweaks
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/76#discussion_r1319316636" expanded>

Perhaps the variable names should be renamed specifically to task in order to avoid confusion in the future.

```suggestion
        Task[] tasks = new Task[100];
        int tasksCount = 0;
```
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/76#discussion_r1319319119" expanded>

Perhaps these methods should be renamed to represent verbs.

```suggestion
    public void markAsDone(){
        this.isDone = true;
    }

    public void unmarkAsDone(){
        this.isDone = false;
    }
```
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/76#discussion_r1319319670" expanded>

I like that you checked whether the task position is there or not.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/76#discussion_r1319321746" expanded>

I like that you put the example inputs for each type of tasks.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/76#pullrequestreview-1616624283" expanded>

**Review Status:** COMMENTED

Looks nice.
Just need to fix some of the names.
</panel>

</panel>

<panel type="info" header="### 43. PAPP..NIEL `@danielpappa` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/11#discussion_r1316716505" expanded>

Consider checking that the case statements are aligned with the switch statement.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/11#discussion_r1316718493" expanded>

Consider refactoring the if statements, maybe by creating a boolean variable, or a method
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/11#discussion_r1316720795" expanded>

Consider adding curly brackets to the if statement to improve code readability and make it more concise
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/11#discussion_r1316721154" expanded>

Consider adding curly brackets to all if statements within the switch statement even though they immediately return
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/11#pullrequestreview-1612421212" expanded>

**Review Status:** COMMENTED

Very good implementation, clear and clean code
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/35#discussion_r1316724435" expanded>

Consider simplifying this code by using a switch statement
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/35#discussion_r1316725106" expanded>

This if loop is very deeply nested and I would also recommend using a single boolean value with a clear text
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/35#discussion_r1316729347" expanded>

Nice way of handling the generator, good abstraction level
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/35#discussion_r1316730190" expanded>

Consider changing both the variable name of value and number to add more meaning to the variable; 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/35#pullrequestreview-1612444163" expanded>

**Review Status:** COMMENTED

Pretty neat and concise code
</panel>

</panel>

<panel type="info" header="### 44. WEMH..ELIN `@wendelinwemhoener` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/48#discussion_r1319308202" expanded>

What do you think about putting your code in a package (because the coding standard mandates it)?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/48#discussion_r1319308727" expanded>

What do you think about removing the empty lines so that your Javadoc comment abides by the coding standard?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/48#discussion_r1319310535" expanded>

What do you think about putting the while loop in a separate method so this one isn't so long?

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/48#discussion_r1319311795" expanded>

What do you think about leaving spaces before and after operators?
```suggestion
        for (int i = 0; i < numberOfTask; i++) {
```
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/48#discussion_r1319313123" expanded>

What do you think about renaming this method to something like "unmark"? The name "unmarkStatusIcon" implies that the unmarking only applies to the status icon, but it applies to the entire task
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/48#pullrequestreview-1616613668" expanded>

**Review Status:** COMMENTED

Overall, you did a good job and largely abided by the coding standard.

I suggest that you delete the empty lines from your Javadoc and split up your main method so that it isn't too long and hard to understand.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/62#discussion_r1319294609" expanded>

What do you think about refactoring this into an "if - else if - else" statement instead of having a separate "if" statement and another "if - else" statement?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/62#discussion_r1319295690" expanded>

I love that you factored this out into a separate method!
However, what do you think about adding a small Javadoc comment? It took me a bit to figure out how exactly the HashMap you return is structured, and I think that just documenting this in a small comment might make it easier for future contributors
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/62#discussion_r1319298519" expanded>

That line seems a bit long (although in the GitHub Web Interface I unfortunately can't see its exact length); what do you think about breaking it into two lines?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/62#pullrequestreview-1616591774" expanded>

**Review Status:** COMMENTED

Overall, I really like your pull request.

You abided by the coding standard and structured your code in a readable and modular way.

Maybe consider adding Javadoc comments to your more complex methods: I know that it is somewhat annoying at first, but it can really help in the long term and makes it easier for other people to understand what is going on.
</panel>

</panel>

<panel type="info" header="### 45. CHUN..XUAN `@spaceman03` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/19#discussion_r1318362046" expanded>

Good job. I like how you followed the indentation standard for wrapped lines, making the code more readable.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/19#discussion_r1318367606" expanded>

Well done. This naming of boolean abides the coding standards.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/19#discussion_r1318368933" expanded>

Good job. I like how you used uppercase for naming constants.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/19#discussion_r1318369969" expanded>

Your if-else statement is very neat and follows the coding standards. Well done!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/19#pullrequestreview-1615041209" expanded>

**Review Status:** COMMENTED

Good job! Your code does not violate any coding standards.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/72#discussion_r1318379526" expanded>

Should this be changed to a boolean instead of a number to avoid magic number? 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/72#discussion_r1318380721" expanded>

Should this be changed to return 'false' instead of 0 to avoid magic number?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/72#discussion_r1318383483" expanded>

Should this be separated into two lines to follow the coding standards?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/72#discussion_r1318389615" expanded>

Good job. I like how you named this method, which follows the coding standard.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/72#pullrequestreview-1615067979" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 46. LI H..AOYU `@Haoyuli2002` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/49#discussion_r1319318028" expanded>

I think that "else" should directly follow the curly braces
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/49#discussion_r1319319394" expanded>

Same issue,  "else if" should directly follow the curly braces
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/49#discussion_r1319319666" expanded>

Nice done for handling the edge cases!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/49#discussion_r1319320977" expanded>

Nice to have error handling!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/49#pullrequestreview-1616626147" expanded>

**Review Status:** COMMENTED

Overall I found your code is already very readable since you have used some comments for coding and error-handling statements. However, some small issues like the location of else statements should be noticed.
After all, well done.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/54#discussion_r1319324592" expanded>

you can merge these two line into one
```suggestion       
     records[recordsNum++] = task;
```
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/54#discussion_r1319325286" expanded>

Would be better to use System.lineSeperator() rather than "/n", but it still works
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/54#discussion_r1319325682" expanded>

no space between class name and “{”
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/54#discussion_r1319326216" expanded>

What if the beginning time does not start with "/from"
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/54#pullrequestreview-1616634455" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 47. HUAN..LING `@vvhuiling` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/52#discussion_r1318300054" expanded>

Should we add a space between the method name and "{" ? I noticed the same issue in several other places too.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/52#discussion_r1318302404" expanded>

Instead of taskName, perhaps a more intuitive variable name here? for example: taskDescription 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/52#discussion_r1318353303" expanded>

Perhaps use plural form of object as variable name here? eg. Task[] tasks = new Task[100];
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/52#discussion_r1318356496" expanded>

I like how you assign substrings of taskname to meaningful variables! make this bit of code easy to understand.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/52#pullrequestreview-1614926278" expanded>

**Review Status:** COMMENTED

Good job! Overall, I found your code easy to read for the most part except very few naming and layout issues. Consider to fix them if that makes sense.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/77#discussion_r1318368572" expanded>

Perhaps spilt the code into 2 lines evenly? first line looks a bit to long for me. I noticed the same issue in several other places too.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/77#discussion_r1318375606" expanded>

I have some confusion regarding these strings. Can you provide some clarification on their meaning?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/77#discussion_r1318379599" expanded>

Perhaps encapsulate some of its functionalities into separate methods so that this while loop can be more concise.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/77#discussion_r1318382485" expanded>

Since this line is used only once, should it be extracted out and just print it directly when needed? 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/77#pullrequestreview-1615051181" expanded>

**Review Status:** COMMENTED

Overall, I found your code easy to read for the most part except main class appears to be a bit packed. Perhaps we can add some blank lines to improve readability. And perhaps encapsulate some of its functionalities if that make sense!
</panel>

</panel>

<panel type="info" header="### 48. LOKE.. XIA `@yingx9` (10 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/30#discussion_r1316772374" expanded>

To add on Jonoan's comment, you might also want to break the expression into steps as per the [coding quality guide (Avoid complicated expression) if applicable! ](https://nus-cs2113-ay2324s1.github.io/website/se-book-adapted/chapters/codeQuality.html#guideline-maximize-readability)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/30#discussion_r1316774228" expanded>

For your deadline, todo, and event, it seems like theres some repeating code to add to list and print (lines 72-77). Perhaps you can extract this into a method
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/30#discussion_r1316781716" expanded>

Maybe you could rename it as texts since its an array holding multiple strings?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/30#discussion_r1316784373" expanded>

Nice use of a method to simplify code!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/30#pullrequestreview-1612535249" expanded>

**Review Status:** COMMENTED

Overall well-written code with small possible changes
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/39#discussion_r1316679470" expanded>

Maybe leave a space between (int length) and { like "printList(int length) {" to keep your format consistent? Noticed this spacing in your Deadline, Todo, and Event class too
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/39#discussion_r1316763157" expanded>

Nice that your method is named to sound like a boolean!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/39#discussion_r1316765052" expanded>

Seems like line 27 is >120 characters, perhaps you should wrap it? 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/39#discussion_r1316765518" expanded>

Your indentations for switch case is great!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/39#pullrequestreview-1612351246" expanded>

**Review Status:** COMMENTED

Overall great code according to coding standards with minor issues!
</panel>

</panel>

<panel type="info" header="### 49. LIM ..HING `@limyuhching` (9 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/10#discussion_r1318379222" expanded>

Very neat use of if-else statement and relevant methods
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/10#discussion_r1318383476" expanded>

Very clean use of ternary operator
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/10#discussion_r1318414727" expanded>

Very clear naming of methods and variables 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/10#pullrequestreview-1615066159" expanded>

**Review Status:** COMMENTED

Overall very clear and concise code. Variable and methods naming were spot on!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/67#discussion_r1318365237" expanded>

Good use of camelCase for method
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/67#discussion_r1318366896" expanded>

Good use of @Override to show overriding of parent's method
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/67#discussion_r1318368054" expanded>

Good use of plurality for naming "parts"
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/67#discussion_r1318369477" expanded>

Right use of indentation for switch case 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/67#pullrequestreview-1615046173" expanded>

**Review Status:** COMMENTED

Good work! Keep it up!
</panel>

</panel>

<panel type="info" header="### 50. SEBA..HUNG `@SebasFok` (9 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/65#discussion_r1318369873" expanded>

Could the line be stored in a string variable so that it could be used more easily elsewhere when formatting?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/65#discussion_r1318372145" expanded>

I like how you considered the case when the list is empty so that the user knows that his input was read.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/65#discussion_r1318374429" expanded>

I like how you broke the sentence up into multiple parts such that it is easy to modify it in the future. There is also good use of white spaces to make make the sentence clear to the reader.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/65#discussion_r1318379146" expanded>

Could the if else statements be changed to switch statements for better readability? This could make each branch easier to find and edit in the future.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/65#pullrequestreview-1615053232" expanded>

**Review Status:** COMMENTED

Looks good! Very clear comments used to allow readers to understand your train of thought
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/75#discussion_r1318395793" expanded>

Could potentially use a switch if possible to make the code more readable. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/75#discussion_r1318398776" expanded>

Perhaps the counter variable could be more descriptive to allow the reader to understand what it is counting.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/75#discussion_r1318402355" expanded>

I like your use of descriptive names to make the code clear and concise.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/75#pullrequestreview-1615101223" expanded>

**Review Status:** COMMENTED

Clear code and good use of white space to make the code clean and easy to read. Good job!
</panel>

</panel>

<panel type="info" header="### 51. CHON..BARA `@Barbaracwx` (16 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#discussion_r1318794183" expanded>

maybe you can add some comments to know what the function is doing for better readability :)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#discussion_r1318797774" expanded>

I think you did a good job by following the naming conventions like PascalCase for class and CamelCase for variables!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#discussion_r1318801411" expanded>

maybe you can have switch statements instead of if-else statements to make it easier to read and understand? So that each of the statements can be easier to find and edited in the future
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#discussion_r1318803104" expanded>

the entire code has very clear naming of all the methods which makes it easy to read and understand
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#discussion_r1318806552" expanded>

i like how you broke up the different functions up like the list, add todo, add deadline, add event up into different functions which made it easier to read and understand what each function does!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#pullrequestreview-1615733441" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#pullrequestreview-1615738539" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#pullrequestreview-1615744067" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#pullrequestreview-1615746699" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#pullrequestreview-1615752032" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/36#pullrequestreview-1615788297" expanded>

**Review Status:** COMMENTED

Looks good overall!
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/84#discussion_r1318847799" expanded>

maybe you can break the code up into different functions for better readability
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/84#discussion_r1318850290" expanded>

maybe you can add some comments to make it easier to read and understand :)
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/84#pullrequestreview-1615814036" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/84#pullrequestreview-1615817804" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/84#pullrequestreview-1615818553" expanded>

**Review Status:** COMMENTED

Good job on the code!
</panel>

</panel>

<panel type="info" header="### 52. HUAN..AMES `@Remy9926` (11 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/49#discussion_r1319345972" expanded>

This comment here is a little unncessary as it isn't too difficult for someone reading your code to understand what is going on here.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/49#discussion_r1319347870" expanded>

Separate your instance variables from your constructor with one line of whitespace.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/49#pullrequestreview-1616662277" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/49#pullrequestreview-1616664806" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/82#discussion_r1319316431" expanded>

Add the "final" modifier to prevent BOT_NAME from being changed at all throughout your program's runtime.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/82#discussion_r1319319126" expanded>

Some of these comments are redundant as it is already made clear in your program what they are made to do
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/82#discussion_r1319319243" expanded>

Here is another example
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/82#discussion_r1319319274" expanded>

As well as this
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/82#discussion_r1319319339" expanded>

This one as well
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/82#pullrequestreview-1616624009" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/82#pullrequestreview-1616627530" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 53. REFA..ITAY `@itayrefaely` (9 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/9#discussion_r1316722082" expanded>

Elegant and relevant!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/9#discussion_r1316723192" expanded>

I like how you used a toString method to print a task.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/9#discussion_r1316725723" expanded>

I like the way you implemented this! Next level.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/9#discussion_r1316726987" expanded>

Very elegant. I like how each case has a separate method. Every part does only what it's supposed to do.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/9#discussion_r1316732241" expanded>

Nice efficient use of constants, but maybe would be better to define them in a separate file?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/9#pullrequestreview-1612438552" expanded>

**Review Status:** COMMENTED

In general, I think your code is very elegant and has good and clean indentation making it very readable. Seems like you keep in mind the SOLID coding concepts. I really like how every method and every part of your code does only what it's supposed to do. Finally, the use here of constants such as "LINE_DIVIDER" and the exception handling are very efficient and nice to see.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/29#discussion_r1316718774" expanded>

Shouldn't the ArrayList "currentTask" be called "currentTasks"? As it holds all of the user's added tasks.
Also, can make it a little shorter by changing to "curTasks".
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/29#discussion_r1316719405" expanded>

I like this class, seems very clean.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/29#pullrequestreview-1612427697" expanded>

**Review Status:** COMMENTED

Regarding coding standards, I think your code is very much aligned.
In general looks very elegant.
</panel>

</panel>

<panel type="info" header="### 54. VELU..LAJI `@000verflow` (9 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/2#discussion_r1316682781" expanded>

Should this be isCompleted instead?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/2#discussion_r1316687371" expanded>

Good job using all caps for constants.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/2#discussion_r1316694664" expanded>

Good job on using appropriate indentation for case clause.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/2#discussion_r1316694891" expanded>

Appropriate use of try-catch statement.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/2#pullrequestreview-1612358206" expanded>

**Review Status:** COMMENTED

Good job on following code standards and quality. Perhaps a more intuitive variable name for some portions.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/5#discussion_r1316681958" expanded>

Appropriate use of indentation for the wrapped lines.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/5#discussion_r1316698010" expanded>

Perhaps declare a constant to use for the size.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/5#discussion_r1316925062" expanded>

Perhaps not hardcode location of the integer parameter
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/5#pullrequestreview-1612356393" expanded>

**Review Status:** COMMENTED

Some minor issues with quality of code, could try to fix/improve upon.
</panel>

</panel>

<panel type="info" header="### 55. CHUA..RYAN `@ryan1604` (8 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/27#discussion_r1318353365" expanded>

Should this be protected/private String eventTime and public Event?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/27#discussion_r1318358340" expanded>

Should this be in a single line (eg } else if (..) { ) with spacing? Same for the other if else statements
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/27#discussion_r1318359812" expanded>

Should it be public Todo instead?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/27#discussion_r1318361690" expanded>

Overall followed coding standards well
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/27#pullrequestreview-1615021888" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/37#discussion_r1318372752" expanded>

I think there shouldn't be indentation for case
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/37#discussion_r1318374966" expanded>

I think method can have a better name?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/37#pullrequestreview-1615057620" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 56. AZFA..ANDI `@azfarulmatin` (14 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/6#discussion_r1318404300" expanded>

Great use of naming to explain the function!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/6#discussion_r1318406109" expanded>

Good use of default branch!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/6#pullrequestreview-1615117977" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/6#pullrequestreview-1615120695" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/6#pullrequestreview-1615123611" expanded>

**Review Status:** COMMENTED

Overall very good! no deep nesting, no magic numbers, and good code structure.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/53#discussion_r1318364083" expanded>

You can consider combining the print function to make it neater.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/53#discussion_r1318367085" expanded>

Good naming method!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/53#discussion_r1318390780" expanded>

Good use of plural form!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/53#discussion_r1318395053" expanded>

 Good K&R style brackets!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/53#pullrequestreview-1615044243" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/53#pullrequestreview-1615048942" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/53#pullrequestreview-1615088110" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/53#pullrequestreview-1615099412" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/53#pullrequestreview-1615103547" expanded>

**Review Status:** COMMENTED

Overall very good coding standard! Very good naming standards.
</panel>

</panel>

<panel type="info" header="### 57. WOO ..NING `@WooKaiNing` (8 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/15#discussion_r1316721027" expanded>

line is slightly too long, may want to consider using line wrapping. same for the other print lines in the code
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/15#discussion_r1316724291" expanded>

may want to consider inserting the comment after this line instead, to avoid the comment from breaking logical structure of the program
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/15#pullrequestreview-1612435248" expanded>

**Review Status:** COMMENTED

coding standard is well followed and the naming for all methods and variables are done well, following the requirements as specified in the standard guidelines
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/29#discussion_r1316727930" expanded>

may want to change class name and file name to Chat0PT instead, since "Duke" name is no longer used
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/29#discussion_r1316731842" expanded>

deep nesting used here, may want to consider extracting some parts out 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/29#discussion_r1316742251" expanded>

may want to write it as task instead of tasks, since this class is referring to a single task?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/29#discussion_r1316742673" expanded>

as this is not a constant, may want to consider using private instead of private final?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/29#pullrequestreview-1612449684" expanded>

**Review Status:** COMMENTED

naming for all methods and variables are done well, following the requirements as specified in the standard guidelines

overall code is clean and readable as well!
</panel>

</panel>

<panel type="info" header="### 58. KARI..ARAN `@karishma-t` (8 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/60#discussion_r1318402641" expanded>

good use of encapsulation and methods of sufficient-length
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/60#discussion_r1318405921" expanded>

sufficiently comprehensible comments
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/60#pullrequestreview-1615116324" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/63#discussion_r1318377893" expanded>

Can consider adding javadoc comments for each method for greater clarity. 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/63#discussion_r1318386186" expanded>

Good use of naming standards, e.g camelCase
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/63#discussion_r1318389730" expanded>

Good layout structure
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/63#discussion_r1318392665" expanded>

indentations just require one more space
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/63#pullrequestreview-1615053598" expanded>

**Review Status:** COMMENTED

lgtm! good use of encapsulation
</panel>

</panel>

<panel type="info" header="### 59. LEE ..GMIN `@woodenclock` (9 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#discussion_r1316682293" expanded>

This seems to be the 4th layer in the method.
Indented too far in, maybe consider extracting this part
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#discussion_r1316682869" expanded>

Indented too far in, maybe consider extracting this part
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#discussion_r1316697987" expanded>

The while loop is too long, maybe extract individual methods out?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#pullrequestreview-1612357493" expanded>

**Review Status:** COMMENTED

Overall good code quality.
Requies Extraction to "pull out" methods in the "while loop" which is too long, which has been indented too far in.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/47#pullrequestreview-1612387359" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/66#discussion_r1316677635" expanded>

Good use of the if-else structure, as stated in the coding standards
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/66#discussion_r1316678400" expanded>

Appropriate use of indentation for the wrapped lines
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/66#discussion_r1316679411" expanded>

Appropriate use of indentation for the wrapped lines
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/66#pullrequestreview-1612347221" expanded>

**Review Status:** COMMENTED

LGTM,
Appropriate use of indentation for the wrapped lines.
Good use of the if-else structure, as stated in the coding standards.
</panel>

</panel>

<panel type="info" header="### 60. DEXT..G EN `@DextheChik3n` (7 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/54#discussion_r1318362589" expanded>

There is an extra space between return and ;
```suggestion
            return;
```
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/54#discussion_r1318364328" expanded>

Add space between Task and curly bracket
```suggestion
public class ToDo extends Task {
```
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/54#pullrequestreview-1615041976" expanded>

**Review Status:** COMMENTED

All the variable, method and class names are well named.
Some minor comestic changes were suggested
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/79#discussion_r1318371298" expanded>

command handling is well-organised using a switch case which makes it easier to troubleshoot.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/79#discussion_r1318373791" expanded>

Perhaps you could use a more clear method name such as printByeMessage?
```suggestion
    public static void printByeMessage() {
```
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/79#discussion_r1318379663" expanded>

Maybe you can use a better variable name for the index like indexAfterBy? so that it is more clearer when you revisit the code
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/79#pullrequestreview-1615055385" expanded>

**Review Status:** COMMENTED

I really like how you structure your code! I just made some suggestions to the variable name to make your code more clear to understand
</panel>

</panel>

<panel type="info" header="### 61. FARI..RRAJ `@farissirraj` (6 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/28#discussion_r1316713112" expanded>

Perhaps you could add a function to fetch the task type (Event, Deadline etc.) from the Task object so that you don't have to hard code it here.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/28#discussion_r1316714439" expanded>

Leave a space like so: `this.isDone = true`

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/28#discussion_r1316718338" expanded>

Leave a space after the `getDescription()` and `{`
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/28#discussion_r1316718918" expanded>

Good use of K&R style brackets!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/28#discussion_r1316720276" expanded>

You could perhaps make this line printing as a separate function so that it declutters the code later on.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/28#pullrequestreview-1612414649" expanded>

**Review Status:** COMMENTED

- Overall coding standards are well followed.
- Just make sure that the commit messages start with capital case and follow an imperative tone.
</panel>

</panel>

<panel type="info" header="### 62. DYLA..TIAN `@DaDevChia` (7 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/52#discussion_r1318359677" expanded>

```suggestion
        String LOGO = "  ____  _____   ___    _____ _____ __    __   ___   __   __\n"
```
Constants are recommended to be in ALL CAPS
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/52#discussion_r1318363203" expanded>

Readability could be improved through including comments
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/52#discussion_r1318368516" expanded>

Switch statement can be used for improved readability
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/52#pullrequestreview-1615037532" expanded>

**Review Status:** COMMENTED

Changed naming for constants to be in ALL CAPS, more comments would be helpful for readability
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/61#discussion_r1318355568" expanded>

```suggestion
    final private static String PYTHONASCIIART =
```

Constants are recommended to be in ALL CAPS
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/61#discussion_r1318356042" expanded>

```suggestion
    final private static String PYTHONEMOJI = "\uD83D\uDC0D";
```

Constants are recommended to be in ALL CAPS
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/61#pullrequestreview-1615021850" expanded>

**Review Status:** COMMENTED

Looks good, made some changes to the naming of constants to be in APP CAPS
</panel>

</panel>

<panel type="info" header="### 63. LEOW.. JIE `@kaijie0102` (7 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/16#discussion_r1319319872" expanded>

Following conventions very clearly: to use all capital letters, seperated by underscores for CONSTANTS
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/16#discussion_r1319321992" expanded>

Good Job: all names representing methods are verbs and written in camel case
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/16#pullrequestreview-1616628480" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/58#discussion_r1319325284" expanded>

Consider using a switch-case block to improve readability.
switch(userInput){
case "list":
case "bye":
.
.
.
}
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/58#discussion_r1319328493" expanded>

I can see that you are  going for a "toggle method" that goes from marked to unmarked and unmarked to marked.
Consider making method name less confusing.

Alternatively have another method called unsetMarked()
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/58#discussion_r1319329373" expanded>

consider changing a trivial function to a constant

PARTITION = "_______________________"
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/58#pullrequestreview-1616635310" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 64. TRIC..PING `@TriciaBK` (7 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/60#discussion_r1318376612" expanded>

naming "arrOfInput" can be clearer to indicate that it stores the split of the input
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/60#discussion_r1318378493" expanded>

try-catch statementfollows coding standard 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/60#pullrequestreview-1615063473" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/86#discussion_r1318368116" expanded>

Try to avoid arrowhead style convention. Perhaps you could have the marking and unmarking of task as a separate method.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/86#discussion_r1318382353" expanded>

You should probably store the different classes in different files
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/86#discussion_r1318382895" expanded>

Avoid long methods - could consider having different methods outside of the main method
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/86#pullrequestreview-1615050512" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 65. WOLT..LIUS `@AlWo223` (7 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/6#discussion_r1318358198" expanded>

I like that you are following the coding standard for constants by using uppercase with underscores.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/6#discussion_r1318362725" expanded>

Would it be better to use a switch statement here for handling the different commands?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/6#discussion_r1318370517" expanded>

This code is very well written and following the standards! Nice work!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/6#pullrequestreview-1615033839" expanded>

**Review Status:** COMMENTED

Very well-written code! I have only suggested a small change.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/81#discussion_r1318381145" expanded>

Should you use a switch() statement instead of multiple if else?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/81#discussion_r1318382547" expanded>

Is there a reason why you don't use toLowerCase() for this specific command?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/81#pullrequestreview-1615070445" expanded>

**Review Status:** COMMENTED

Nice work, I have only suggested a small change to improve coding style
</panel>

</panel>

<panel type="info" header="### 66. WU X..NGYU `@DavinciDelta` (8 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/14#discussion_r1316717192" expanded>

I like the use of camelCasing and the boolean variables have great names! but the setDescription seems to be redundant as of right now, maybe use it for the constructor?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/14#discussion_r1316718599" expanded>

I like that the switch statements have the correct formatting and indentation! but switch case in a while looks very confusing, maybe put the switch in another java class?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/14#discussion_r1316719721" expanded>

I like the indentations!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/14#pullrequestreview-1612422375" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/14#pullrequestreview-1612427164" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/31#discussion_r1316731673" expanded>

i like the use of switch case to avoid deep nesting!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/31#discussion_r1316733513" expanded>

I feel that this method length seems to be unnecessarily long, perhaps you could try to shorten it?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/31#pullrequestreview-1612456029" expanded>

**Review Status:** COMMENTED

good code and great use of HashMap, this allows adding in future commands more conveniently!
</panel>

</panel>

<panel type="info" header="### 67. TOH ..CHUN `@mcmc101001` (5 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/38#discussion_r1316713619" expanded>

I would suggest leaving more spaces between your conditionals and loops (especially from line 32 to 75)

if () {

instead of 

if(){
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/38#discussion_r1316716429" expanded>

you could consider using a void setDone(boolean isDone) to abstract these two methods to one
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/38#discussion_r1316720176" expanded>

consider adding a space after the brackets in markAsUndone for consistency
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/38#discussion_r1316721093" expanded>

Consider abstracting out all the System.out.println methods as it is very lengthy
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/38#pullrequestreview-1612415793" expanded>

**Review Status:** COMMENTED

remember to refactor your code!
</panel>

</panel>

<panel type="info" header="### 68. CHUA..HENG `@Cazh1` (6 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/12#discussion_r1318399981" expanded>

Perhaps a more detailed variable name such as "logoMessage"
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/12#discussion_r1318405026" expanded>

Noticed that there was indentation for case clauses.
```suggestion
        switch (commandArray[0]) { // Check first word of input for command

            /**Checks for command keywords
             * and executes corresponding methods
             * from TaskList class if found.
             */

        case Constants.endCommand:
```
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/12#pullrequestreview-1615111802" expanded>

**Review Status:** COMMENTED

Code looks very neat. Noticed some spacing errors
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/50#discussion_r1318369710" expanded>

Perhaps the comment can be "Returns "X" if the task is marked, " " if the task is unmarked".
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/50#discussion_r1318395603" expanded>

Noticed missing space between ) and {
```suggestion
    public static void markUnmarkTask(String command) {
```
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/50#pullrequestreview-1615052952" expanded>

**Review Status:** COMMENTED

Overall code looks good. Noticed some spacing errors. Good job!
</panel>

</panel>

<panel type="info" header="### 69. LEON..SHUA `@J0shuaLeong` (6 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/31#discussion_r1316713728" expanded>

Nice to see constants follows the standard
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/31#discussion_r1316716755" expanded>

According to the coding standard, even if there is only one statement in an if block, should be within {} and on a new line.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/31#discussion_r1316720754" expanded>

Very neat and well written code!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/31#pullrequestreview-1612415947" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/71#discussion_r1316724061" expanded>

Would recommend to add horizontal lines for each output
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/71#pullrequestreview-1612443622" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 70. ZHAN..EVIN `@kevinz420` (6 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/10#discussion_r1319318851" expanded>

a lot of this parsing (/field value format) is shared among all three types of tasks. perhaps you could make a more generic helper function that returns the field value mappings given any raw input in this format?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/10#discussion_r1319319659" expanded>

you assume that all inputs are given correctly and formatted as it is expected. what if the user mistypes or gives a wrongly formatted input? id add some error handling to ensure your program doesn't crash during unexpected input events
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/10#pullrequestreview-1616627237" expanded>

**Review Status:** COMMENTED

Overall clean, modular code with clearly named variables that adhere to the coding standard. I could tell you put a lot of emphasis on code reusability and made lots of helper functions that are multi purpose. LGTM!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/48#discussion_r1319316137" expanded>

maybe rename this variable to be more clear? when i see `taskNumber` i could think it means # of tasks (your numOfTasks) or any other general concept. i don't immediately think you mean the task being mark/unmarked.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/48#discussion_r1319316751" expanded>

looks like you are using the same code in multiple places here. maybe turn the parsing into its own separate function or refactor your code so that you are not copy pasting the same line into different places
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/48#pullrequestreview-1616623626" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 71. FENG..GYAO `@MrOPPA1` (6 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/51#discussion_r1319338064" expanded>

It's really cool to use a funciton to print a horizontal line and i love the design of using the function of "repeat".
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/51#discussion_r1319339349" expanded>

maybe u can define a variable(protected String for example) in the base class Task(suppose to call it "type"),and in the toString function of Task just use "["+type+"]",and change the type in the constructer of each class~
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/51#pullrequestreview-1616651893" expanded>

**Review Status:** COMMENTED


</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/62#discussion_r1319335732" expanded>

I appreciate your standard coding format, but maybe u can split a long line into some short line to make it more easy to read and understand the meaning of the parameters or the added string.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/62#discussion_r1319336216" expanded>

And the way u name the variables and functions is really cool that I can easily figure out what they are used for.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/62#pullrequestreview-1616648954" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 72. TANG..N EN `@tangzhenen` (5 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/5#discussion_r1316678432" expanded>

Add spaces between each plus sign 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/5#discussion_r1316678786" expanded>

add spacing before and after the plus sign
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/5#discussion_r1316679671" expanded>

add a blank line here
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/5#discussion_r1316682328" expanded>

add spacing after }
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/5#pullrequestreview-1612348702" expanded>

**Review Status:** COMMENTED

generally quite good and follows the coding standard
</panel>

</panel>

<panel type="info" header="### 73. YANG..REMY `@imaginarys96` (5 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/23#discussion_r1316949503" expanded>

Indentation is off
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/23#discussion_r1316949896" expanded>

Short functions under 30 lines.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/23#discussion_r1316955548" expanded>

Consider updating the comment as there now more functionalities than just "Add, List"
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/23#discussion_r1316956250" expanded>

Make it a constant and capitalize the variable name.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/23#pullrequestreview-1612821129" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 74. ONG .. KIT `@choonkit-nus` (4 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/52#discussion_r1318365648" expanded>

Good use of getDescription accessor method together that can be invoked by objects of the Task class, which are typed in camel case too
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/52#discussion_r1318370077" expanded>

Nice, the @Override annotation to indicate that the child class method is over-writing its base class method
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/52#discussion_r1318376126" expanded>

Great and proper naming convention for addToList method, it is clear, direct, and in-line with what the method does
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/52#pullrequestreview-1615046805" expanded>

**Review Status:** COMMENTED


</panel>

</panel>

<panel type="info" header="### 75. REN ..GDAO `@YFshadaow` (4 comments)"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/27#discussion_r1318375580" expanded>

This might result in unexpected behaviour if user types command such as :
  todo unmark some task
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/27#pullrequestreview-1615061934" expanded>

**Review Status:** COMMENTED

Good job! Overall clean code.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/34#discussion_r1318363320" expanded>

If statement can possibly be replaced by a switch statement. (but not necessarily)
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/ip/pull/34#pullrequestreview-1615043119" expanded>

**Review Status:** COMMENTED

Good job! Code is generally clean.
</panel>

</panel>

<panel type="info" header="### 76. ZHAN..TONG `@Zhang-Zhitong` (0 comments)"  collapsed>

n/a
</panel>

<panel type="info" header="### 77. YEO .. HAN `@yeo-menghan` (0 comments)"  collapsed>

n/a
</panel>

<panel type="info" header="### 78. CHAR..G YU `@charkty` (0 comments)"  collapsed>

n/a
</panel>

<panel type="info" header="### 79. SHI ..CHEN `@hshiah` (0 comments)"  collapsed>

n/a
</panel>

<panel type="info" header="### 80. DHAN..IKSH `@antrikshdhand` (0 comments)"  collapsed>

n/a
</panel>

<panel type="info" header="### 81. SCHN..ILLE `@martinschnder` (0 comments)"  collapsed>

n/a
</panel>
