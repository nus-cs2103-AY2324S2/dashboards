%%[This page was last updated on Nov 15 2023]%% [**<span class="text-warning">:octicon-eye:</span> indicates those _watching_ the forum** (kudos :+1:)]


<panel type="info" header="### 1. YANG..TIAN `@skylee03` (30 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Week 12 Quiz Q16 Bare Plural**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/52" expanded>

The question is:

> IDEs have built-in static analysis capabilities.

In this sentence, "IDEs" is a [bare plural](https://en.wikipedia.org/wiki/Bare_nouns) introduced by a null quantifier. Therefore, it has at least three different interpretations:

1. $[{}_\text{Q.ALL}\varnothing]$ IDEs have built-in static analysis capabilities. (Universal)
1. $[{}_\text{Q.MOST}\varnothing]$ IDEs have built-in static analysis capabilities. (Generic)
1. $[{}_\text{Q.SOME}\varnothing]$ IDEs have built-in static analysis capabilities. (Existential)

Which interpretation should we adopt when answering question 16?
</panel>

<panel  header="**2. :fas-info-circle: Accidentally uploaded files that shouldnt be tracked**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/43" expanded>

In this case, we know we can remove them from history commits using `git filter-branch`, but I don't know if doing so will confuse the automated script. Are we advised that we should only delete them in a new commit instead of modifying the history commits?
</panel>

<panel  header="**3. :fas-info-circle: Does SRP require single responsibility of methods?**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/41" expanded>

For the question:

> As per SRP, a method should have only one responsibility. (Week 9 Quiz Part II Q16)

The standard answer is:

> False. The SRP is about classes, not methods.

However, in our [supplementary reading](https://code.tutsplus.com/solid-part-1-the-single-responsibility-principle--net-36074t), the author reasoned about SRP and came to the following conclusion:

> (To ensure that SRP is respected,) when we design our software we should:
> 1. Find and define the actors.
> 1. Identify the responsibilities that serve those actors.
> 1. Group our **functions** and classes so that each has only one allocated responsibility.

The author seems to believe that the single responsibility of functions (i.e., methods) is one of the necessary conditions to ensure SRP is followed. I am wondering that, in other words, does SRP require single responsibility for methods?


</panel>

<panel  header="**4. :fas-info-circle: Accessibility vs Visibility**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/36" expanded>

In Week 8 Quiz, the first question is:

> In the following class diagram, the ‘+’ and ‘-’ signs to indicate _accessibility_ of the attributes and the methods.
> ![image](https://github.com/nus-cs2113-AY2324S1/forum/assets/24489025/d3c1e96e-fa06-4bd0-84fe-bdf0545252b9)

And the standard answer is:

> False. It’s called _visibility_, not _accessibility_.

I'm wondering if there are any differences between the two terms. As far as I know, they are often used interchangeably, and [The Java® Language Specification](https://docs.oracle.com/javase/specs/jls/se21/html/jls-6.html#jls-6.6) uses the term "accessibility".

</panel>

<panel  header="**5. :fas-info-circle: Quiz Early-Submission Window**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/34" expanded>

What is an early-submission window? I submitted my Week 7 Quiz answer at 22 Sep 19:44, but according to the [participation dashboard](https://nus-cs2113-ay2324s1.github.io/dashboards/contents/participation.html), it is not within the early-submission window.
</panel>

<panel  header="**6. :fas-info-circle: Week 7 Quiz Q4**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/33" expanded>

The question is:

> SLAP stands for Single Level of Abstraction Per method.

I think the answer is "false", because according to the [textbook](https://nus-cs2113-ay2324s1.github.io/website/se-book-adapted/chapters/codeQuality.html#slap-hard), "SLAP" stands for "Single Level of Abstraction Principle".

However, the expected answer is "true", and the explanation is:

> As per the textbook.

But when I used the textbook's search function to search for "Single Level of Abstraction Per method", no exact match was found.
</panel>

<panel  header="**7. :fas-info-circle: [iP] Do we still need to support adding ordinary tasks?**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/16" expanded>

In Week 4, we added support for tracking three types of tasks: ToDos, Events, and Deadlines. However, we are not required to remove the old way of adding ordinary tasks. Therefore, when the user's command is `blah`, we should create a task called `blah`.
In `Level-5` of Week 5, we are asked to handle such input as an exception. Does this mean we need to remove the old way of adding ordinary tasks?
</panel>

<panel  header="**8. :fas-info-circle: Accidentally Finalized My Coding Exercise**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/4" expanded>

After attempted Q1, I found nowhere to proceed to the next question, so I finally clicked the "Finalize Submission" button by mistake. Now I can't move on to other questions.
</panel>

<panel  header="**9. :fas-info-circle: JDK Version**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/2" expanded>

When configuring projects for the course, can we use a newer version of SDK instead, but set the language level to 11?
![image](https://github.com/nus-cs2113-AY2324S1/forum/assets/24489025/73036e9a-5875-4631-a9f2-cebd46c2bc7b)

</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/1#issuecomment-1679098291" expanded>

Not a bug report but a small suggestion:

"IntelliJ"s are almost always spelled as "Intellij", and "GitHub"s are sometimes spelled as "Github". Since the occurrences of "SourceTree" have been changed to "Sourcetree" as compared to earlier versions of the course website, I think "IntelliJ" and "GitHub" should be in their correct capitalization as well.

"Intellij IDE" in [Week 1 Admin](https://nus-cs2113-ay2324s1.github.io/website/schedule/week1/admin.html#tool-intellij-ide) or in `website/admin/tools.md` should be "IntelliJ IDEA".
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/9#issuecomment-1697481192" expanded>

Due to Sep 1 being declared as Polling Day and a public holiday, we will not have any tutorial or lecture on that day.

Akshay will work separately with the Friday teams offline on some administrative matters.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/12#issuecomment-1698626728" expanded>

Try `git push --tags`.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/13#issuecomment-1701193587" expanded>

You can find all the standards and conventions that we need in our course [here](https://nus-cs2113-ay2324s1.github.io/website/admin/standardsAndConventions.html).
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/14#issuecomment-1705432400" expanded>

The teacher has not issued an invitation yet. We should only be able to join an organization after receiving an invitation.
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/17#issuecomment-1715317067" expanded>

The infrastructure for Teammates submission of the project direction is not ready yet; Akshay will announce once they are ready to accept the submission.
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/21#issuecomment-1733503296" expanded>

You should select "master" at "Branch".
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/27#issuecomment-1751765160" expanded>

I don't know what your input issue is, but I just tested your program on Linux. I tried adding some tasks and restarting your program, and the files can be loaded normally.
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/27#issuecomment-1751765708" expanded>

![image](https://github.com/nus-cs2113-AY2324S1/forum/assets/24489025/dbdf5b89-c467-409d-8cf2-64d5ec7493b4)

</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/27#issuecomment-1751770632" expanded>

I think this exception is actually thrown by `nextLine()`. This problem occurs if the input stream has no new content but you still try to read from it. I'm not sure in what situation you encountered this problem, but at least I reproduced this problem in two cases:

1. Reads commands from a file, which does not contain `bye`.
2. Type &gt;kbd>Ctrl&gt;/kbd> + &gt;kbd>D&gt;/kbd> (or &gt;kbd>Ctrl&gt;/kbd> + &gt;kbd>Z&gt;/kbd> on Windows) at the command line to send an EOF character.

Generally, you don't need to worry about the above two special situations. If you really want to deal with this problem, you can use `hasNextLine()` to check whether the scanner has next line.
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/27#issuecomment-1751773553" expanded>

![image](https://github.com/nus-cs2113-AY2324S1/forum/assets/24489025/9ae2c3bf-e4da-4a9d-bf14-8cd4f78667e1)

</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/28#issuecomment-1751787910" expanded>

Your project works on my Windows device.
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/28#issuecomment-1751789452" expanded>

I just tested it under Linux and found that it doesn't create and read files properly. The error message is as follows:
```
Exception in thread "main" java.nio.file.NoSuchFileException: data/taskList.txt
	at java.base/sun.nio.fs.UnixException.translateToIOException(UnixException.java:92)
	at java.base/sun.nio.fs.UnixException.rethrowAsIOException(UnixException.java:111)
	at java.base/sun.nio.fs.UnixException.rethrowAsIOException(UnixException.java:116)
	at java.base/sun.nio.fs.UnixFileAttributeViews$Basic.readAttributes(UnixFileAttributeViews.java:55)
	at java.base/sun.nio.fs.UnixFileSystemProvider.readAttributes(UnixFileSystemProvider.java:149)
	at java.base/sun.nio.fs.LinuxFileSystemProvider.readAttributes(LinuxFileSystemProvider.java:99)
	at java.base/java.nio.file.Files.readAttributes(Files.java:1764)
	at java.base/java.nio.file.Files.size(Files.java:2381)
	at fileIO.FileIO.clearData(FileIO.java:71)
	at fileIO.FileIO.outputFileInitialization(FileIO.java:35)
	at Oriento.Oriento.main(Oriento.java:29)
```

You need to change all `"\\"` to `"/"` in the file paths in `FileIO.java`. The former only works on Windows, while the latter works on all platforms.
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/28#issuecomment-1751900339" expanded>

I just re-tested the latest version under Linux and now it creates and reads files properly.

```
mtyang@academy11:~/Documents$ java -jar ip.jar
Hello! I'm Oriento.
What can I help you?
todo fdskjsdf
Got it. I've added this task:
[T][ ] fdskjsdf
Now you have 1 tasks in the list.
================================================
list
1. [T][ ] fdskjsdf
================================================
bye
Bye. Hope to see you again soon!
================================================
mtyang@academy11:~/Documents$ java -jar ip.jar
Hello! I'm Oriento.
What can I help you?
list
1. [T][ ] fdskjsdf
================================================
bye
Bye. Hope to see you again soon!
================================================
```
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/33#issuecomment-1758050490" expanded>

I checked the historical version of the course website and found that in [AY 2020-21](https://nus-cs2113-ay2021s1.github.io/website/se-book-adapted/chapters/codeQuality.html#slap-hard), it was indeed "Single Level of Abstraction Per method". However, as @ianyong [pointed out](https://github.com/se-edu/se-book/issues/101) its difference with the original expression in _The Productive Programmer_, the textbook for subsequent semesters has changed the expression to "Single Level of Abstraction Principle". I think the answer to the quiz should also be updated accordingly.
</panel>

<panel  header="**25 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/38#issuecomment-1763287965" expanded>

The breeder of the cat might be the same person keeping the cat, but might also be another person. If it is the former case, there are two association with opposite directions between the two **objects** in the **object diagram**, but in the **class diagram**, since this situation does not necessarily happen, we cannot treat it as a bidirectional association.
</panel>

<panel  header="**26 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/38#issuecomment-1763289524" expanded>

In other words, class diagrams must be compatible with all possible situations.
</panel>

<panel  header="**27 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/38#issuecomment-1763405212" expanded>

> > If it is the former case, there are two association with opposite directions between the two objects in the object diagram, but in the class diagram, since this situation does not necessarily happen, we cannot treat it as a bidirectional association.
> 
> I still feel confused by this statement you have mentioned as the textbook mentioned the former case (pet and owner) the class association is bidirectional

I guess the author of the textbook wants to use the semantics in natural language to help us understand the concept of "bidirectional association". In linguistics, _converses_ are defined as "words which describe a relation between two entities from alternate viewpoints". For example, "pet" and "owner" can be regarded as a pair of _converses_, while "pet" and "breeder" cannot.

In fact, we are using UML to specify our programs, rather than drawing UML from the program code. The two pieces of code in your screenshot are completely equivalent. They do not place any restrictions on the referenced objects.


</panel>

<panel  header="**28 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/36#issuecomment-1765568369" expanded>

I see. 

> As per the text: ![image](https://user-images.githubusercontent.com/1023494/275692516-5daca9cf-b8d8-4a17-a6e4-4a5f466a3561.png)
> 
> Some people do use it interchangeably; from UML perspective, visibility is more appropriate.

So "accessibility" and "visibility" refer to the same thing, except that the former is a Java term and the latter is a UML term?
</panel>

<panel  header="**29 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/38#issuecomment-1773747875" expanded>

> > I guess the author of the textbook wants to use the semantics in natural language to help us understand the concept of "bidirectional association". In linguistics, _converses_ are defined as "words which describe a relation between two entities from alternate viewpoints". For example, "pet" and "owner" can be regarded as a pair of _converses_, while "pet" and "breeder" cannot.
> 
> I understand the purpose of using the entity names of the respective pairs but I still feel that my initial question has not been answered... I think the main thing I am confused about is when do we use a bidirectional arrow and when do we use two unidirectional arrows?

```
class A {
    B b;
    //...
}

class B {
    A a;
    //...
}

A a;
B b;
```

Bidirectional arrow: if the references are not `null`, then "`a.b.a == a` and `b.a.b == b`" must hold.
Two unidirectional arrows: if the references are not `null`, then "`a.b.a == a` and `b.a.b == b`" may not hold.
</panel>

<panel  header="**30 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/57#issuecomment-1807626346" expanded>

If you are using [PlantUML](https://plantuml.com/), you can generate images in `.svg` format instead of `.png` format.
</panel>

</panel>


<panel type="info" header="### 2. NG Z..I YI `@ziyi105` (20 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Does anyone know how to increase the resolution of diagrams?**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/57" expanded>

n/a
</panel>

<panel  header="**2. :fas-info-circle: What if the tester maliciously edit the data file and report it as a bug?**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/53" expanded>

How can the developers proof innocent in this case?
</panel>

<panel  header="**3. :fas-info-circle: Clarification on week 9 quiz**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/37" expanded>

![image](https://github.com/nus-cs2113-AY2324S1/forum/assets/82555990/e035307d-18f4-4b5e-b950-3468088d020c)

what does the "or" means? Do we consider the left one or the right one
</panel>

<panel  header="**4. :fas-info-circle: May I know who is marking my IP? My github is ziyi105**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/35" expanded>

I realised I wrote the JavaDoc comments wrongly. I am editing it now, could you review my ip tomorrow instead?
</panel>

<panel  header="**5. :fas-info-circle: Peer Evaluation Last Question, no command given**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/31" expanded>

![image](https://github.com/nus-cs2113-AY2324S1/forum/assets/82555990/341a3b68-f7c2-4286-885a-91a73ef55f7b)
For this question, are we supposed to input nothing?
</panel>

<panel  header="**6. :fas-info-circle: Forgot to branch out level 9 and A-JavaDoc**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/24" expanded>

What should I do in this case :(  I tagged my commits for level 9 and A-JavaDoc already
</panel>

<panel  header="**7. :fas-info-circle: A-JavaDoc, most of my public methods are self-explanatory**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/22" expanded>

in that case, do I still need to add comments? If I don't will the marking script mark me down?
</panel>

<panel  header="**8. :fas-info-circle: runtest.bat not working as expected**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/19" expanded>

I have already crtl v ctrl c my actual output on EXPECTED.TXT, but for some reason I can never get the "no differences encountered" output. Anybody has any idea why?

![image](https://github.com/nus-cs2113-AY2324S1/forum/assets/82555990/878d51e3-e907-49a7-8940-cf8296e61bc9)

</panel>

<panel  header="**9. :fas-info-circle: Tag and branch show in github but not on ip dashboard**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/18" expanded>

As per title, I can find all my tags and branches in github but on ip dashboard it is still marked as not done
![image](https://github.com/nus-cs2113-AY2324S1/forum/assets/82555990/0628c6fd-f3d8-4b3a-892c-a592ed616170)

![image](https://github.com/nus-cs2113-AY2324S1/forum/assets/82555990/fc5af073-5bd1-4100-a5b0-d4477cb3059e)

</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/18#issuecomment-1718777018" expanded>

I see, thank you!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/19#issuecomment-1722113931" expanded>

Hi Prof, I changed all System.out.print() and "\n" to System.out.println() according to your instruction and it's finally working! Thank you
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/22#issuecomment-1738365440" expanded>

Does commenting in the method count?
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/22#issuecomment-1738402040" expanded>

Most of my method names are very straight forward, like addTodo(), getSize(), readFile(), run(), printHelloMessage(), if i comment on them isnt that repeating the obvious?
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/22#issuecomment-1738643118" expanded>

alright, thank you!
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/24#issuecomment-1741764825" expanded>

Ok thank you!
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/31#issuecomment-1754302145" expanded>

hmm it doesnt, but the command is foo 2 right? I can see it on the second peer review survey
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/53#issuecomment-1799133183" expanded>

Noted! But if the tester edit it on purpose such that it affects the output, how can the developers prove innocence?
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/53#issuecomment-1801079680" expanded>

If the tester add something in the data text file with correct formatting (e.g., add a new book A) after he exists the session, he restarts the application and list out a list of books which now contains bookA, and he reports it as a bug claiming that he didn't add book A in the previous session. Is this scenario possible and do we need to handle that? 
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/53#issuecomment-1801142255" expanded>

I see, thanks for the clarification prof!
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/57#issuecomment-1807878251" expanded>

OMG thanks!!
</panel>

</panel>


<panel type="info" header="### 3. STAN..JAYA `@StanleyW00` (14 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Creating JavaDoc**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/56" expanded>

For making javadoc in our code, do we have to make one for tests as well?
</panel>

<panel  header="**2. :fas-info-circle: `Assertions` task in tp dashboard**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/40" expanded>

I noticed that in the dashboard my `Assertions` task is not completed despite using `assertEquals` in my code. It says does not detect any asserts. May I ask what are the requirements for this task?
</panel>

<panel  header="**3. :fas-info-circle: Test IP jar file for Mac or Linux**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/27" expanded>

Hello,  I have an issue regarding getting input for Mac and Linux for my project and I have modified my code.I have used Windows and I am wondering if anyone willing do a smoke test with my project to see if there's still a problem regarding inputting.

[https://github.com/StanleyW00/ip](url)
</panel>

<panel  header="**4. :fas-info-circle: Level-8, Replacing String with LocalDate**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/23" expanded>

I'm wondering for this level, do we replace the variables holding from, to, and by, from string to localdate, so that it only accepts a specific date and time format?
</panel>

<panel  header="**5. :fas-info-circle: Blank input for Individual Project Level-1**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/8" expanded>

For level-1, if we input a blank string, e.g. pressing enter only, should we print this kind of input as well or check if the input is blank?
</panel>

<panel  header="**6. :fas-info-circle: Weekly Programming Exercises Coding Standards**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/5" expanded>

In the programming exercises, are the coding standards graded as well?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/5#issuecomment-1684173831" expanded>

I have read the Grade Breakdown section from the website and I have found my answer.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/5#issuecomment-1697535788" expanded>

From what I seen, It's not. However, I think it is a good habit to follow them.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/23#issuecomment-1740176906" expanded>

I'm thinking of making somekind of indicator to specify which type to use when creating a deadline or an event. I believe that the former is simpler and I think it should be faster to implement.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/23#issuecomment-1740224710" expanded>

Ahhh okay then. Anyway, thank you for answering, prof!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/27#issuecomment-1751766376" expanded>

Thanks for testing my program! Regarding the problem, I was informed that my program has `java.util.NoSuchElementException` error for Mac and Linux. I noticed that the line that was referred to is where I tried to trim while calling the nextline method during inputting.

At least, I know that my program works on Linux.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/27#issuecomment-1751900636" expanded>

I have added the part where it checks using `hasNextLine()`. See if it is fixes the problem that you mentioned.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/40#issuecomment-1766257557" expanded>

Oh nvm, I found out that you need to use `assert` in the functioning code as well.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/56#issuecomment-1807366589" expanded>

I see. Thank you prof!
</panel>

</panel>


<panel type="info" header="### 4. PUA ..RICK `@wwweert123` (12 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Use of GSON and FMP**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/49" expanded>

## Library

1. GSON https://github.com/google/gson
2. Financial Modeling https://site.financialmodelingprep.com/

## Purpose

1. Serialize Java objects to JSON for easy saving
2. Request Stock prices

## License

1. Apache 2.0 License
2. https://site.financialmodelingprep.com/developer/docs/terms-of-service

</panel>

<panel  header="**2. :fas-info-circle: Tp Github CI fails sometimes**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/45" expanded>


![Screenshot 2023-10-26 191135](https://github.com/nus-cs2113-AY2324S1/forum/assets/93811746/9c48d42e-5b5b-4d13-b92b-d9f7041e3cc6)
Our groups tP's github CI for macOS fails some of the time due to this error. However when I rerun the failed job. It would pass. Does anyone knows whats wrong
</panel>

<panel  header="**3. :fas-info-circle: Use of Third party libraries for tP**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/39" expanded>

## Library

1. JSON Simple https://code.google.com/archive/p/json-simple/
2. apache commons langs https://mvnrepository.com/artifact/org.apache.commons/commons-lang3
3. Xchart https://mvnrepository.com/artifact/org.knowm.xchart/xchart/3.2.2
4. Alpha Vantage https://www.alphavantage.co/

## Purpose

1. Used for parsing request to Stock API into JSON object in java code for easy access
2. Used for padding of UI outputs using string.leftpad and string.rightpad
3. Used for generating different kinds of visualization (piecharts, bargraphs) for financial planner application to categorize expenses and income
4. API endpoint for getting updated stock prices for user to track the stocks that they are interested in in the application watchlist

## License

1. [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)
2. https://www.apache.org/licenses/
3. Apache 2.0 open source license
4. https://www.alphavantage.co/terms_of_service/

</panel>

<panel  header="**4. :fas-info-circle: Not enough javadoc comments**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/32" expanded>

"At least half of public methods/classes have Javadoc comments." Does this mean I have to write comments for both methods and classes? 

If so, I realized that I have not written enough javadoc header comments (I think) after I have looked at the peer evaluation. I have written javadoc comments for my methods only. Is it ok if I add on javadoc comments in the latest commit in my iP
</panel>

<panel  header="**5. :fas-info-circle: Accidentally Fast forward merge branch level 6**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/20" expanded>

Just now, I was following the instructions for iP and i created a branch for both level 6 and level 7 and completed the activities for them. Then I merged branch level 6 to master. I only realized that I have merged branch level 6 with fast forward only after I have merged branch level 7 to master and solved all the merge conflicts. Will this be a problem? 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/20#issuecomment-1723106727" expanded>

Thanks prof! Do you mean you find you after the lecture on Friday?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/20#issuecomment-1725087117" expanded>

Hi Prof, it seems that the script did detect my branch-Level-6 merge with fast forward for some reason and my iP dashboard is now green for that entry. I think alls good now. Thanks prof!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/32#issuecomment-1755526980" expanded>

Alright thanks prof!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/39#issuecomment-1765772882" expanded>

Alright thank you prof! For alpha vantage, they provide free academic access (higher volume) to their data for students (eg. Taking part in hackathon, doing school projects). However, they need evidence of our student status. Is it possible for you help me to confirm my student status?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/39#issuecomment-1767643183" expanded>

Hi prof did you reply me on my school email? I cant seem to find it... 😅
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/49#issuecomment-1788592904" expanded>

Thanks prof. I have emailed them. However it is written on the website here 
![Screenshot 2023-11-01 163027](https://github.com/nus-cs2113-AY2324S1/forum/assets/93811746/51c6c283-f5b3-42b8-8c5e-2533672799ea)
https://site.financialmodelingprep.com/developer/docs
I think as long as I referenced it in the CLI application, it should be fine?
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/52#issuecomment-1793499800" expanded>

Should be existential or generic
</panel>

</panel>


<panel type="info" header="### 5. JASO.. JIE `@sRanay` (5 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Submission for documentation**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/55" expanded>

Is the submission due on Tue, Nov 14 13:00 or Mon, Nov 13 23:59?
![image](https://github.com/nus-cs2113-AY2324S1/forum/assets/33816512/7c1265bd-c844-40d7-89f3-f3a636579e56)

</panel>

<panel  header="**2. :fas-info-circle: Request permission to use Apache Commons IO for tP**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/47" expanded>

## Library

[Apache Commons IO](https://mvnrepository.com/artifact/commons-io/commons-io)

## Purpose

1. To use it to compare File content for JUnit Test for storage component 

## License

1. [Apache License](https://www.apache.org/licenses/LICENSE-2.0)
2. [https://www.apache.org/licenses/](https://www.apache.org/licenses/)

</panel>

<panel  header="**3. :fas-info-circle: Use of third party library for tP**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/44" expanded>

## Library

1. [OpenCSV](https://mvnrepository.com/artifact/com.opencsv/opencsv)

## Purpose

1. Use OpenCSV library to store data into CSV File.
2. Uses the library to load the data from CSV File into the program.

## License

1. [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)
3. [https://www.apache.org/licenses/](https://www.apache.org/licenses/)

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/55#issuecomment-1805021736" expanded>

sry for asking again, but is it 14 Nov, 1pm or 15 Nov, 1pm because the website shows this now.
![image](https://github.com/nus-cs2113-AY2324S1/forum/assets/33816512/e3188a9e-ba98-4b36-8d95-606f491549e7)

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/55#issuecomment-1805468278" expanded>

yes, it is fixed.
</panel>

</panel>


<panel type="info" header="### 6. TOH ..HENG `@yicheng-toh` (5 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: How do we proceed with ip evaluation if there are no jar file.**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/30" expanded>

The student does not have a jar file nor a UG. The code is not updated for a couple of weeks. How do I go about doing the evaluation?

Thank you for your clarification.
</panel>

<panel  header="**2. :fas-info-circle: Is there a settings for github for review before merging pull request.**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/29" expanded>

Hi,

For the tp, during the tutorial exercise, I realised that I have accidentally merged my pull request to the team repo without waiting for any reviewers. Would it have any effect on the tp.

Moving forward, can I check if there is a way to prevent one from merging one's own pull request to the team repo. I would want to impose it on my account to prevent such situation from happening.

Thank you for your assistance and clarification.
</panel>

<panel  header="**3. :fas-info-circle: Missed out requirements on increment 0 but completed increment 1,2,3**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/11" expanded>

Hi,

I have done level 1,2,3 increment but I have realised I have forgotten to rename my bot (a requirement for increment 0). How do I proceed. Can I change it on increment 3, or do I need to somehow backtrack and edit on increment 0 and then merge it. Or is it too late?

Thanks for advice.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/1#issuecomment-1685162322" expanded>

![image](https://github.com/nus-cs2113-AY2324S1/forum/assets/75836313/d99e8708-bdfb-43e9-a125-3e4450f089cc)
Should the example be '!false' and '!true' instead? 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/30#issuecomment-1757537561" expanded>

IP evaluated.
</panel>

</panel>


<panel type="info" header="### 7. DEXT..G EN `@DextheChik3n` (5 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Unclear about navigability for class diagrams**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/38" expanded>

https://nus-cs2113-ay2324s1.github.io/website/schedule/week8/topics.html#design-modelling-modelling-structure-class-diagrams-basic

under the section OOP: Associations → Navigability, about the note on "two unidirectional associations in opposite directions do not add up to a single bidirectional association". I don't fully understand the example of the two unidirectional associations.

Does it mean that because the breeder Person object will always be different in relation to the pet Cat object, it is not a bidirectional association?

![image](https://github.com/nus-cs2113-AY2324S1/forum/assets/35828587/9364b6d7-54b3-49cd-8ca1-587aa2f25edd)

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/18#issuecomment-1718762364" expanded>

the ip dashboard thingy updates once everyday so u can check tomorrow and it will prolly turn green
there's a text to show when the dashboard was last updated above the table there
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/38#issuecomment-1763390219" expanded>

> If it is the former case, there are two association with opposite directions between the two objects in the object diagram, but in the class diagram, since this situation does not necessarily happen, we cannot treat it as a bidirectional association.

I still feel confused by this statement you have mentioned as the textbook mentioned the former case (pet and owner) the class association is bidirectional
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/38#issuecomment-1773736798" expanded>

> I guess the author of the textbook wants to use the semantics in natural language to help us understand the concept of "bidirectional association". In linguistics, _converses_ are defined as "words which describe a relation between two entities from alternate viewpoints". For example, "pet" and "owner" can be regarded as a pair of _converses_, while "pet" and "breeder" cannot.

I understand the purpose of using the entity names of the respective pairs but I still feel that my initial question has not been answered... I think the main thing I am confused about is when do we use a bidirectional arrow and when do we use two unidirectional arrows?


</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/38#issuecomment-1782702644" expanded>

oooh ok I get it now, thank you prof Akshay and Ming Tian for the help! 🙏 
</panel>

</panel>


<panel type="info" header="### 8. WEMH..ELIN `@wendelinwemhoener` (5 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: CATcher is stuck on login page**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/42" expanded>

After following the steps on https://nus-cs2113-ay2324s1.github.io/website/schedule/week10/project.html to file a bug report using CATcher, CATcher is stuck on the login page and simply shows this spinner: 
![image](https://github.com/nus-cs2113-AY2324S1/forum/assets/49584216/20696f24-a74a-4595-9745-a59fdabe180c)
Nothing happens; even after multiple minutes. What should I do?

</panel>

<panel  header="**2. :fas-info-circle: Did not receive TEAMMATES submission link**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/17" expanded>

The course websites said that we should receive a TEAMMATES submission link. I haven't.

Also, when I try the recovery link provided on the course website, I get this email:
```
Hello,

You are receiving this email because a request to resend TEAMMATES links associated with the email address e1125438@u.nus.edu was made on [TEAMMATES](https://teammatesv4.appspot.com/).

Sorry, we could not find any links since no session in TEAMMATES is associated with this email address.

You can [try again](https://teammatesv4.appspot.com/web/front/help/session-links-recovery) with a different email address or contact your course instructor(s) to check whether this email address is the one used to enroll you in TEAMMATES.

Technical help regarding TEAMMATES: Email TEAMMATES support team at teammates@comp.nus.edu.sg.

Regards,
TEAMMATES Team.
```
Thus, I can't log into TEAMMATES and conduct the preliminary peer evaluation.

What should I do now?
</panel>

<panel  header="**3. :fas-info-circle: I cannot join the course organization**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/14" expanded>

According to https://nus-cs2113-ay2324s1.github.io/website/schedule/week4/admin.html#1-accept-github-invitation-from-the-course-organization-counted-for-participation, we are supposed to join the cs2113-AY2324S1 Github Organization. 
However, I did not receive an invitation email and the invitation link on the course website (https://github.com/orgs/nus-cs2113-AY2324S1/invitation) also doesn't work.
How am I supposed to join the Github Organization in this case?
</panel>

<panel  header="**4. :fas-info-circle: Will there be a lecture (and tutorial) this Friday?**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/9" expanded>

Friday (1 Sept) is Polling Day. Will there still be a lecture on Friday?
Also, what about the tutorial: If I am in a tutorial that is on Friday, will it take place or should I go to a tutorial on another day?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/5#issuecomment-1694697020" expanded>

So are they graded or not?
</panel>

</panel>


<panel type="info" header="### 9. TIAN..AYAN `@J-Y-Yan` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Ask for help to run jar file**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/28" expanded>

Hello, can anyone help me run my jar file on your machine? I am afraid the teaching team cannot run my file.

Please refer to the following link for the file:
https://drive.google.com/file/d/1wxOmkzPWCbn3q7VeQW6uB_LjxpJJjWoa/view?usp=sharing

Thanks for your help!!! I need to ensure the validity of the file before launching it.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/28#issuecomment-1751788373" expanded>

Thank you!!! it's great to hear from you.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/28#issuecomment-1751899111" expanded>

Thank you so much! I have just corrected this issue.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/28#issuecomment-1751900931" expanded>

Great! Thanks a lot for your support.
</panel>

</panel>


<panel type="info" header="### 10. BENJ..MING `@bnjm2000` (4 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: CATcher dashboard update**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/48" expanded>

Hi, I had some issues with setting up CATcher last week. Not gonna lie, totally forgot about it until I received an email to set it up. I managed to get it set up with dummy issues yesterday. I would like to ask if it would show up updated on the individual tp dashboard or the participation dashboard that it was completed or if it would no longer be updated after the week is over. If yes, may I know what I did wrong that it is not updated to completed? If not, is there any way for me to know if I have done it correctly?
</panel>

<panel  header="**2. :fas-info-circle: Week 7 Tutorial: Unable to run Duke**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/25" expanded>

Had trouble following the tutorial as I was unable to run Duke.java after forking and cloning to my local machine. Upon opening in IntelliJ, I get an error message of tp: failed and I do not have the option of running Duke

I am running a 2022 Mac M2 Max with MacOS 13.2 (maybe that has something to do with it)

Anyone facing the same issue? Any help would be appreciated. TIA!

<img width="1512" alt="tp failed" src="https://github.com/nus-cs2113-AY2324S1/forum/assets/142559789/ebbe1953-bfa8-4d87-aef8-f19751954e1c">


<img width="1400" alt="Duke" src="https://github.com/nus-cs2113-AY2324S1/forum/assets/142559789/67b4c63c-6be7-4a00-a8e2-5c1adede2185">


</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/25#issuecomment-1751191442" expanded>

This worked, thank you both so much for your assistance! I can finially upload my screenshots, hope they can still be counted :")
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/48#issuecomment-1792287646" expanded>

Resolved the issue, I misread the instructions and thought "from the application" referred to the mobile GitHub application. Resolved the issue by creating new issues from the CATcher application.
</panel>

</panel>


<panel type="info" header="### 11. ROHI..THAN `@rohitcube` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Permission to use fuzzy wuzzy external library**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/50" expanded>

## Library

[fuzzywuzzy](https://github.com/xdrop/fuzzywuzzy)

## Purpose

Make the 'search modules' feature better for the user by implementing fuzzy sort, so that minor misspelling still returns the closest modules that can be found in the NUSMods API. E.g. 'search Machien Learning' will return modules with keywords 'Machine Learning' instead of no modules being returned. 

## License

GNU General Public License v2.0

</panel>

<panel  header="**2. :fas-info-circle: Request permission to use Jackson Databind library**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/46" expanded>

## Library

[Jackson Databind](https://mvnrepository.com/artifact/com.fasterxml.jackson.core/jackson-databind)

## Purpose

Our aim is to parse the JSON data obtained from the NUSMods API.

## License

Apache 2.0 (https://github.com/FasterXML/jackson-databind) / (https://camel.apache.org/components/3.14.x/dataformats/json-jackson-dataformat.html)

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/46#issuecomment-1783809165" expanded>

(CS2113-T17-4)
</panel>

</panel>


<panel type="info" header="### 12. XU J..CHEN `@aaronxujiachen` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Does anyone know where I can find the coding standards?**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/13" expanded>

I browsed through CS2113 website but cannot find the details:(
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/13#issuecomment-1701201075" expanded>

> You can find all the standards and conventions that we need in our course [here](https://nus-cs2113-ay2324s1.github.io/website/admin/standardsAndConventions.html).

Thank you soooo much!
</panel>

</panel>


<panel type="info" header="### 13. EE H.. ZHI `@Hongzhii` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: jar file not available under GitHub releases**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/26" expanded>

I was sent an automated email last night saying that my jar file was not available under my releases. However, when I checked the link myself I can see the jar file submitted. Is there a particular format that the GitHub release should be in? 

I have attached a screenshot of the GitHub releases page below.

<img width="1188" alt="Screenshot 2023-10-07 at 9 34 06 AM" src="https://github.com/nus-cs2113-AY2324S1/forum/assets/97496506/827968b6-ca7c-4bf3-9c06-9f207e8f029a">

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/26#issuecomment-1751655408" expanded>

It seems that the previous release was visible only when I was logged into GitHub (was not visible when accessing the link in incognito). I created a second release and it seems to have fixed the issue. Is my release visible now?
</panel>

</panel>


<panel type="info" header="### 14. HUAN..LING `@vvhuiling` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: My code passed Main.main(args) (Verify), but it failed Main.main(args)**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/15" expanded>

What could be the possible reasons for this, and will it affect my grade？
</panel>

<panel  header="**2. :fas-info-circle: Can I commit 2 increments with one commit massega？**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/7" expanded>

for example, I write:"Refactor: Rename main class; Add greeting and exit functionality"
</panel>

</panel>


<panel type="info" header="### 15. LEE ..GMIN `@woodenclock` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Not sure how to enable the pages**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/21" expanded>

![image](https://github.com/nus-cs2113-AY2324S1/forum/assets/69474977/bc3f5d8d-8b82-46d8-8e0e-e9b63367258b)
I am not too sure how to set the 'Source' as Master??
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/4#issuecomment-1685307827" expanded>

Me too, I faced the same problem, and only solved the first question.
Is there a way to revert my submission?
</panel>

</panel>


<panel type="info" header="### 16. LIM ..HING `@limyuhching` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Quiz 12 is not on Canvas**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/51" expanded>

Hi Prof, I cant seem to find Quiz 12 on Canvas Quizzes. 
</panel>

</panel>


<panel type="info" header="### 17. OU N..IANG `@onx001` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Week 1 lecture conflicting information**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/3" expanded>

On the GitHub page, it states that the first lecture is online. However, on Canvas, it states that the first lecture is in person. May I know which is it? Thank you!
</panel>

</panel>


<panel type="info" header="### 18. OH K.. WEI `@ken-ruster` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Tags not showing up on github**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/12" expanded>

After I pushed my commits to the remote repository, despite the tags from Level-0 to Level-3 existing on my local repository, only the Level-0 tag shows up on GitHub when I click on "tags". Is there anything I can do to rectify this?
</panel>

</panel>


<panel type="info" header="### 19. CHUA..HENG `@Cazh1` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Can hashing be implemented to detect tampering of saved text file?**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/54" expanded>

Current implementation is that hashing is used to detect tampering by tester. Once tampering is detected, the user is warned to either revert the change or existing data will be overwritten by the new instance of the application. Does this violate the constraint laid out by https://nus-cs2113-ay2324s1.github.io/website/admin/tp-constraints.html#constraint-human-editable-file? 
If this violates the constraint, what implementation of hashing would be more desirable? 
</panel>

</panel>


<panel type="info" header="### 20. LIM ..SHUA `@lckjosh` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Accidentally reset my answer on Coursemology**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/10" expanded>

When attempting Week 3's coding exercises I had completed all of them, and Coursemology showed the 10 question circles as green. After finalising my submission, the circle of question 1 changed to red. It appears that my answer for question 1 was reset. I had previously answered it correctly before and I can see my previous submission under "Past Answers". My grade in coursemology is now 9/10. Is there any way to rectify this?
</panel>

</panel>


<panel type="info" header="### 21. CHUN..XUAN `@spaceman03` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/4#issuecomment-1684685342" expanded>

I faced the same issue as OP too.
</panel>

</panel>


<panel type="info" header="### 22. LI H..AOYU `@Haoyuli2002` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: How to access Coursemology**" popup-url="https://github.com/nus-cs2113-AY2324S1/forum/issues/6" expanded>

Hey guys, 
This course is assigned for me this Tuesday so I don't know how to get access to the Coursemology. 
I have already watched the recording of the first lecture, yet I still don't know what to do.
Thanks in advance
</panel>

</panel>
