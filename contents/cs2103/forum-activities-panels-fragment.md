%%[This page was last updated on Apr 14 2023]%% [**<span class="text-warning">:octicon-eye:</span> indicates those _watching_ the forum** (kudos :+1:)]


<panel type="info" header="### 1. HING..DICT `@hingen` (88 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Omitting some dependencies and classes from a class diagram**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/321" expanded>

Hello. I'm editing the Model class diagram at the moment as my team made significant changes to it. After including all dependencies and classes, the diagram has gotten way too complex. By stripping out some dependencies and classes, I'm able to make the diagram much simpler and still capture the general flow of how the main classes of the package depend on each other (which is what I'm trying to communicate).

I'm wondering are we allowed to omit some dependencies and classes from a class diagram? Would it still be a class diagram or would it be something else (e.g. architecture diagram)?

For example, in the following diagram, can I exclude the components of the `Person` class? Or perhaps, can I remove the "filtered" association between `ModelManager` and `Person`?

![image](https://user-images.githubusercontent.com/31367001/229738568-215a6f4d-5880-4b12-b768-a591791c0319.png)



</panel>

<panel  header="**2. :fas-info-circle: Which documents to update?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/316" expanded>

Hello, may I know if we have to update all documents in the `docs` folder?

Currently, my team is only updating the User Guide, Developer Guide, and other guides linked to by these 2 guides. Wondering if other documentation like the ones in the `tutorials` directory need to be updated as well? Or are they optional?
</panel>

<panel  header="**3. :fas-info-circle: Can we omit the creation of an object in a sequence diagram?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/315" expanded>

Hello. I was editing the developer documentation when I realised that the sequence diagram `ArchitectureSequenceDiagram.png` specifies an argument `p` in the method call `deletePerson(p)`. However, `p` is never defined anywhere.

Intuitively, as developers who have a rough understanding of the code base, we can infer that `p` is the `Person` object that is to be deleted. However, I feel it can be rather ambiguous for a developer new to the code base. Perhaps a name like `person` or `personToDelete` would be more intuitive.

My question is, in a sequence diagram, can we omit details such as object creation?

If so, are there any conditions to be met? For example, the argument name and/or context surrounding the sequence diagram must be intuitive enough for the developer to infer the meaning of the arguments.

Screenshot:
![image](https://user-images.githubusercontent.com/31367001/229447491-f124a58d-b763-481b-ad8d-f7f7ae4fa849.png)

</panel>

<panel  header="**4. :fas-info-circle: 💡 Fix Intellij IDEA Checkstyle import order errors**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/108" expanded>

The import order specified in `checkstyle.xml` provided in the [tutorial](https://se-education.org/guides/tutorials/checkstyle.html) doesn't match the default import order of Intellij IDEA.

To change the import order of checkstyle, change the code in the following section of  `checkstyle.xml`:
```xml
<module name="CustomImportOrder">
    &gt;!-- some stuff -->
</module>
```

The following import order should work for those using the default Intellij IDEA import order:
```xml
<module name="CustomImportOrder">
    <property name="customImportOrderRules"
        value="STATIC###THIRD_PARTY_PACKAGE###STANDARD_JAVA_PACKAGE"/>
    <property name="thirdPartyPackageRegExp" value="&hat;(org|com|duke|javafx)\."/>
    <property name="sortImportsInGroupAlphabetically" value="true"/>
</module>
```

You can find more info about checkstyle import order checks [here](https://checkstyle.sourceforge.io/apidocs/com/puppycrawl/tools/checkstyle/checks/imports/CustomImportOrderCheck.html).

Alternatively, refer [here](https://se-education.org/guides/tutorials/intellijCodeStyle.html#tweak-import-order) for a guide on changing the import order of Intellij IDEA (might come in handy during Tp)

Edit: Fix import order errors when `org.junit` is imported
</panel>

<panel  header="**5. :fas-info-circle: Can I move Duke.java into a package?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/13" expanded>

Currently, I've placed `Duke.java` in the `duke` package but I realize that `./text-ui-test/runtest.sh` assumes that `Duke.java` is not in a package.

I've modified `runtest.sh` to support having `Duke.java` in the `duke` package but am wondering if this will cause any issue with grading later on.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/2#issuecomment-1381439304" expanded>

As others have pointed out, this is how it has been defined in OOP. However, perhaps you can look at it in another way. Think of "is-a" as "can be treated as".

So let's say we have a class `Engineer` and an interface `Person` and `Engineer` implements `Person`. Then we can thus treat `Engineer` as a `Person` meaning anything we can do on a `Person` object (the methods and properties we expect to exist) can be done on an `Engineer` object as well.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/3#issuecomment-1381960107" expanded>

In general, not specific to any language
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/7#issuecomment-1383296561" expanded>

As the message implies, seems like GitHub has removed password authentication. A post was made on their developer blog [here](https://developer.github.com/changes/2020-02-14-deprecating-password-auth/) (although they seem to have officially removed it later than in the timeline specified)

The recommended replacement seems to be Personal Access Token. Personally, I prefer using SSH. You can refer to this guide [here](https://www.awordfromnet.com/how-to-connect-github-with-sourcetree/) on how to setup SSH with SourceTree and GitHub (scroll down to the "Method 2: Connect with SSH Key" section)
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/13#issuecomment-1384929409" expanded>

> @hingen You can modify `runtest.sh` as you wish.

Noted! Thank you prof
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/11#issuecomment-1384980083" expanded>

> From a project requirements point of view, the answer for this case is "do what makes sense from the user point of view". What behavior makes sense from the user's POV, in this case?

I'm also of the opinion that the program should not stop. Since the current task list does not save to secondary storage, it seems unforgiving if the user loses his entire task list if he just types one command incorrectly.

> Separately, can an Exception be used even when the expected behavior is printing an error message?

For me, I want my error messages printed in a different way from normal output messages and using a custom exception is one way I achieve it. Although it could definitely be achieved via other means. Perhaps throwing an exception could be a way of stating explicitly that an error has occurred for whoever reads the code base in the future?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/11#issuecomment-1384987335" expanded>

Have you tried using a try-catch block?
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/11#issuecomment-1385051046" expanded>

@Tempura-Person  How about having `DukeException` extend `Exception` and give `DukeException` an `errorMessage` property that you set in the constructor. So whenever an error occurs, you throw a `DukeException` with an error message specific to the error. You can then handle the error by just printing out `errorMessage`.

If you feel that using `DukeException` is not specific, you can always extend `DukeException` (e.g. `DukeEmptyDescriptionException`) with each derived class having a preset `errorMessage`. You can then have different errors throw different exceptions all derived from `DukeException`. That way your catch block will only have to catch `DukeException` and print out whatever is stored in `errorMessage`.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/11#issuecomment-1385085133" expanded>

@Tempura-Person Looks about right. If you nest your switch block inside another try-catch block which catches `DukeException`, it shouldn't terminate the program

Something like this:
```java
while (true) {
        // some other code
        try {
            // your switch code block
        } catch (DukeException e) {
            System.out.println(e.errorMessage);
            continue;
        }
        // some other code
}
```

Also, probably would be good if you move the code for each command into it's own method or class. Else, you're going to have one massive method that is hard to read and debug with a lot of nesting (lots of tabs).
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/15#issuecomment-1385168674" expanded>

`input.txt` should contain each command, line-by-line, in the order you want to feed it to the program.
For example:
```
todo lorem ipsum
mark 1
bye
```
This would be the same as running the program and inputting the command `todo lorem ipsum`, then after the program has taken the command and printed the output, you enter the line `mark 1`, and so on. Note that empty lines in `input.txt` will be inputted as is. That is it is treated the same as if you entered nothing and just press enter.

`EXPECTED.txt` is what you expect the output of the program to be given the input that you put in via `input.txt`.
So from the above example input, the expected output could be this (or something else depending on your program):
```
    ____________________________________________________________
     Hello from
      ____        _        
     |  _ \ _   _| | _____ 
     | | | | | | | |/ / _ \
     | |_| | |_| |   <  __/
     |____/ \__,_|_|\_\___|
     
     What can I do for you?
    ____________________________________________________________

    ____________________________________________________________
     Got it. I've added this task:
       [T][ ] lorem ipsum
     Now you have 1 tasks in the list.
    ____________________________________________________________

    ____________________________________________________________
     Nice! I've marked this task as done:
       [T][X] lorem ipsum
    ____________________________________________________________

    ____________________________________________________________
     Bye. Hope to see you again soon!
    ____________________________________________________________
```

When you run the script, an `ACTUAL.txt` file will be produced that is the actual output of the program given `input.txt`. The script will then attempt to compare the contents of `EXPECTED.txt` and `ACTUAL.txt`. If they match, then your test will pass, else it fails.
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/15#issuecomment-1385189450" expanded>

To create `EXPECTED.txt`, make sure you have an empty or placeholder `EXPECTED.txt` then run the test script. The test will fail but you would get an `ACTUAL.txt` file from it. Look through `ACTUAL.txt`. If you deem that it's output is correct, then delete your current `EXPECTED.txt` and rename `ACTUAL.txt` to `EXPECTED.txt`.
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/28#issuecomment-1396683901" expanded>

Did you perhaps write your input.txt in Windows? If so, could be an issue with difference in line ending. Try rewriting your input.txt using vim
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/15#issuecomment-1396864939" expanded>

> cmd.exe /c runtest.bat 'javac' is not recognized as an internal or external command, operable program or batch file. ********** BUILD FAILURE **********
> 
> Process finished with exit code 1

Can you try opening a command prompt and running `javac --version`?
If you get a `'javac' is not recognized as an internal or external command`, then most likely your environment variables were not set up correctly. 
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/15#issuecomment-1396873244" expanded>

> Hi there,
> 
> Step 3 of the automation needs me to "Update the javac and java commands in the script to match the name/location of your main class."
> 
> how exactly do we do that? I assume its this line in the runtest.bat file that has to be "updated"? many thanks.
> 
> ` javac -cp ..\src\main\java -Xlint:none -d ..\bin ..\src\main\java\*.java`

I believe this is only applicable if you move your `Duke.java` into a package. So let's say, `Duke.java` is in the `duke` package, then you will have to update the command to be
 ` javac -cp ..\src\main\java -Xlint:none -d ..\bin ..\src\main\java\duke\*.java`

Also, on a side note, probably better to create a new GitHub issue for each problem you face. Else this issue thread is going to get extremely messy with a mixture of comments addressing the different problems.
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/15#issuecomment-1396877746" expanded>

> ![image](https://user-images.githubusercontent.com/92144641/213438810-50d33fac-a320-4ac7-aa7f-6d8087158f75.png) oh, uh... is this cause for concern?

Could you try using a normal command prompt instead of Windows Powershell? As in, use cmd, not powershell. This seems to be the recommendation on the [CS2103 site](https://nus-cs2103-ay2223s2.github.io/website/se-book-adapted/chapters/testing.html#automated-testing-of-cli-apps)
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/15#issuecomment-1396889147" expanded>

Just want to check to be 100% sure, but have you installed java11?

If so, then your environment path variable is likely not configured properly. Perhaps try watching this [video](https://youtu.be/RBuZHg6eyIs). Skip to 3:00 in the video.
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/29#issuecomment-1396932923" expanded>

Perhaps add a `bye` as the last line of your `input.txt`. I suspect what might have happened is that your entire `input.txt` has been read but since your program is still running, it attempts to read the next token which doesn't exist
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/29#issuecomment-1396952662" expanded>

Looked through your code and found the issue, this is the same as issue #28. Create Scanner object outside the while loop, do not create it multiple times. Refer to #28 for more info.
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/31#issuecomment-1398208562" expanded>

Was thinking perhaps start from the current working directory then slowly traverse the parents looking for a directory which contains a directory named `src` since we know for a fact that the project root folder has a directory named `src`.

```java
Path path = Path.of(System.getProperty("user.dir")); // Get the path to the current working directory

while (true) {
    File dir = path.toFile();

    boolean isFound = false;
    for (File file : dir.listFiles()) {
        if (file.getName().equals("src")) { // Check if this directory contains a file/directory named 'src'
            isFound = true;
            break;
        }
    }

    if (isFound) {
        break;
    }

    path = path.getParent(); // Move to the next parent
}

Path savePath = Paths.get(path.toString(), "data", "duke.txt");

System.out.println(savePath);
```

But the solution isn't perfect as it might fail if the current working directory is an ancestor of the project root directory or if you have multiple files/directories named `src` in your project.

An alternative solution would be to perhaps save to the user's home directory which can be obtained using `System.getProperty("home.dir")`. I know some standalone Linux apps do this. Not sure what is the convention for Windows and Mac.
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/31#issuecomment-1398254353" expanded>

> Only the developers will have such a folder. Users of the product will not have such a folder.

Ah I see, my bad, I did not take into account that the users may not have the `src` folder since it's not necessary for deployment.

If we're discussing deployment scenarios, then, perhaps write to a file in `System.getProperty("home.dir")`. Since it is the user's home directory, it should be a directory that the user has write access to (or at least for most users). It also has the benefit that the app will run fine even if the user runs the app from a working directory which he/she does not have write access to (example `/`).
</panel>

<panel  header="**25 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/37#issuecomment-1399206979" expanded>

Just speaking from past school project experience.

Is force push bad? Personally don't think so but there's a time and place for it and it should be used with caution. Force push allows you to overwrite the git history on the remote. If not careful, you could:
* cause your teammates local repo history to become out of sync with the remote (this can usually be remedied with proper application of the merge command on your teammates side provided they are familiar with how to fix it as it can be pretty complicated depending on what history you overwrote)
* overwrite and delete your teammates commits, especially if you force push a commit to a branch multiple devs are working on (e.g. merge commit to master branch)

Should you force push every single one of your commits?
* If you're the only one working on the repo, probably fine but you risk accidentally deleting commits and it's also not good practice (the overwritten commits are usually still accessible on your local repo as commits that belong to no branch)
* If you're working on a repo with a team, 100% not for the second negative implication stated above
</panel>

<panel  header="**26 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/41#issuecomment-1399655062" expanded>

> However, in practice, given that re-running all commands is efficient, there don't seem to be a lot of drawbacks to creating the task list from scratch.

If the approach is to append any command that the user enters into the save file, I wonder if it could lead to a large save file over time. Hypothetically, if a user were to use the app for several years, could the save file get very big leading to higher start-up times and also larger storage usage?

For tasks that have already been deleted, the save file would still store the command for creating and deleting the task which would be redundant data. Perhaps `delete` commands should not be appended into the save file but rather remove their corresponding `add` command from the save file.
</panel>

<panel  header="**27 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/54#issuecomment-1401466647" expanded>

It would appear that what `SimpleDateFormat::parse(String)` is doing is that it reads `2/12/2019` as year=2, month=12, day=2019. Of course, December does not have 2019 days so month and year get incremented instead.

Here's some simple code to illustrate what is going on: 
```java
String input = "1/01/32";

DateFormat inFormat = new SimpleDateFormat("yyyy/MM/dd");
Date date = inFormat.parse(input);

DateFormat outFormat = new SimpleDateFormat("dd/MM/yyyy HHmm");
System.out.println(outFormat.format(date));

// Output is: 01/02/0001 0000
```
In this case, the date parsed is year=1, month=1, day=32. But January only has 31 days, so the resulting date becomes 1 Feb 0001. 

This is just speculation since I don't know how `Date` works exactly but perhaps `SimpleDateFormat::parse(String)` simply calculates the date as milliseconds since January 1, 1970 and stores it as a long, without doing any error checking for whether the day exceeds the number of days in the month.

If you would like something with stricter error checking, perhaps consider using the newer `DateTimeFormatter` class instead. Example below:
```java
String input1 = "1/01/32";
String input2 = "0001/01/32";
String input3 = "0001/02/01";

String format = "yyyy/MM/dd";
DateTimeFormatter formatter = DateTimeFormatter.ofPattern(format);

try {
    formatter.parse(input1);
} catch (DateTimeParseException e) {
    System.out.println("DateTimeParseException thrown");
}

try {
    formatter.parse(input2);
} catch (DateTimeParseException e) {
    System.out.println("DateTimeParseException thrown");
}

DateTimeFormatter outFormatter = DateTimeFormatter.ofPattern("dd/MM/yyyy");
System.out.println(outFormatter.format(formatter.parse(input3)));

// Output is:
// DateTimeParseException thrown
// DateTimeParseException thrown
// 01/02/0001
```
</panel>

<panel  header="**28 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/57#issuecomment-1402868308" expanded>

Hi @valerietanhx, I'm unable to recreate your issue using the current code in your repo. Could you post the output from running `runtest.sh` or `runtest.bat`? Since error messages will not be written to `ACTUAL.txt`, would be helpful to see the output of the bash/batch scripts.
</panel>

<panel  header="**29 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/58#issuecomment-1402985957" expanded>

You have to open the `build.gradle` file and set the `application.mainClassName` to refer to your main class name. In the `add-gradle-support` branch, the main class name would be `Duke`. In your branch, it would be `<the_package_containing_Duke.java>.Duke`

```gradle
// some configs

application {
    mainClassName = "Duke" // originally set to "seedu.duke.Duke" on the add-graddle-support branch
}

// some configs
```
</panel>

<panel  header="**30 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/60#issuecomment-1403077257" expanded>

@seadragon2000341 
![image](https://user-images.githubusercontent.com/31367001/214478812-cecd165f-707a-47bb-8bc2-b2bd71709d44.png)

Did you miss out any steps from the [gradle tutorial](https://se-education.org/guides/tutorials/gradle.html)?
</panel>

<panel  header="**31 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/60#issuecomment-1403116519" expanded>

Should be fine. The error message is not from your duke code but from gradle. An `org.gradle.api.BuildCancelledException` was thrown by gradle because you forced the program to terminate. If you exit duke normally (e.g. using a `bye` command), you won't get the error.

If you want to see more information about the error, just click `Run with --stacktrace` in the error message, wait for duke to start, then press stop. You'll see the full error message outputted by gradle.
</panel>

<panel  header="**32 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/57#issuecomment-1403129030" expanded>

I think the `dos2unix` error is likely unrelated. The command should only matter if you created `EXPECTED.txt` in Windows but you're trying to run `runtest.sh` from Mac or Linux. The command is likely there to fix any inconsistencies in line endings and other differences between DOS (Windows) and Unix like (Mac and Linux) OS.

I can't recreate the issue using the code in your repo so I can only speculate. Did you perhaps forget to delete `&gt;project_root>/text-ui-test/data`?

Since you're likely running `runtest.sh` from within the `&gt;project_root>/text-ui-test` directory, duke doesn't save to `&gt;project_root>/data` but to `&gt;project_root>/text-ui-test/data` instead.
</panel>

<panel  header="**33 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/62#issuecomment-1403341855" expanded>

Might be related to #29 which is a combination of 2 issues

Try the following:
1. Make sure that `Scanner` object is created only once throughout the execution of the app (that is do not create it inside a while loop)
2. In your `input.txt`, add a new line after bye (so there should be one blank line at the end of the file)
</panel>

<panel  header="**34 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/62#issuecomment-1403375605" expanded>

`runtest.bat` is suppose to handle that for you. It uses the `FC` command which is for comparing files. Look at your command prompt output for the details. If I'm not wrong, you should see a `FC: no differences encountered` if `ACTUAL.txt` and `EXPECTED.txt` contain the same content.

I'm on Linux using `runtest.sh` so I'm not sure what is the exact output of `runtest.bat`. Perhaps someone on Windows would be able to comment on this
</panel>

<panel  header="**35 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/64#issuecomment-1404429152" expanded>

I like @daitenshionyan's way of testing.

However, I feel that we should avoid interacting with the file system if possible during a unit test. My reason is:
1. A unit test should run fast and interacting with file system is slow (when there are a large number of tests, speed can start to feel significant)
2. File system is dependent on the execution environment and thus environment specific issues might occur (e.g. a developer creates a file of the same name but locks it's permission to read-only, in which case the test might fail from having not enough permission which is a file system issue, not an issue with the code being tested)

Perhaps an alternative could be to use a `ByteArrayOutputStream` object.
```java
// For redirecting System.out
ByteArrayOutputStream outputStream = new ByteArrayOutputStream();
System.setOut(new PrintStream(outputStream));

// For reading the contents that were written to System.out
String actual = outputStream.toString()
```
</panel>

<panel  header="**36 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/66#issuecomment-1404448198" expanded>

If you specify your input file path as `./data/duke.txt` in your code, then it's likely that when you run `runtest.sh`, the data file used is in `&gt;project_root>/text-ui-test/data/duke.txt` as you are executing `runtest.sh` from the `text-ui-test` directory. Perhaps you could place the data file to be use for testing in that directory instead?
</panel>

<panel  header="**37 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/71#issuecomment-1406043023" expanded>

I like the above 2 suggestions. Just want to add another alternative suggestion into the mix, that is use another thread to write to the save file.

I think by handling write operations on another thread, the responsiveness of the app can be maintained and also, we can write after every change to the task list thereby minimising data loss from app crashes. Using multithreading could lead to more complexity in the code base though.

If you're interested, Java provides an [AsynchronousFileChannel](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/nio/channels/AsynchronousFileChannel.html) class for handling reads and writes for files asynchronously on separate threads. Here's a [guide](https://www.baeldung.com/java-nio2-async-file-channel) on how to use it.
</panel>

<panel  header="**38 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/79#issuecomment-1407212293" expanded>

Looking around on forums, it seems that it could be caused by a rogue gradle process running in the background or a gradle task not cleaning up after itself properly upon exiting leading to some `.lock` files being left behind.

Perhaps you could try:
1.  Restarting your computer to get rid of any rogue gradle processes. 
2. If it still does not work, push all your local changes to your remote repo, then clone the remote repo to a new local directory. This will get rid of the files mentioned in your `.gitignore` such as the `.gradle` directory and thus allow you to generate a new `.gradle` directory which would hopefully fix the issue if it was caused by a gradle task not properly cleaning up after itself.
</panel>

<panel  header="**39 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/86#issuecomment-1407586711" expanded>

Don't think Java supports nested methods. If you want to do something like that, you would have to use a lambda expression
```java
// Declaration
Runnable messagePrinter = () -&gt; {
    pw.println(sb.toString());
    pw.flush();
    sb.setLength(0);
};

// Call
messagePrinter.run()
```

Some additional info about lambda can be found here:
[Guide for Java lambda expressions](https://www.w3schools.com/java/java_lambda.asp)
[List of functional interfaces that can be used with lambda](https://www.educative.io/answers/a-list-of-all-the-functional-interfaces-in-java)

This is just my opinion, but I don't really like using lambdas in such a manner. I feel that it adds unnecessary nesting which can make code difficult to read and also has a tendency to make one method contain multiple layers of abstraction (which would violate the module's java coding standards). 

Perhaps consider:
1. Making variables like `pw` and `sb` class level variables (static variables) so that you would be able to use them in other class level methods inside the `main` class
2. Pass `pw` and `sb` as parameters into the `printMessage` method
</panel>

<panel  header="**40 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/88#issuecomment-1407601701" expanded>

> there is no such branch that exists in my local repo

Technically, the `add-gradle-support` branch is in the local repo just named as `remotes/origin/add-gradle-support`. When a remote repo is cloned to a local machine, all the branches get cloned along with it. Not sure how it works on Sourcetree (perhaps someone else can comment on this) but in Git CLI, you can list out these remote branches by running this command:
```
git branch -a
```
Example output:
```
* master
  remotes/origin/HEAD -&gt; origin/master
  remotes/origin/add-gradle-support
  remotes/origin/master
```

When you switch to a branch on your local repo, Git creates a branch with the same name but without the `remote/origin/` part. When commits are made locally, they are made to the local branch and not the remote branch (the one with `remote/origin/` in it's name). I assume this is Git's way of differentiating the commits that exist on your local repo and commits that exist on the remote repo as well as the state of the branch.
</panel>

<panel  header="**41 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/89#issuecomment-1407669854" expanded>

@0x787af25e, may I know what is your full `build.gradle` file?

> I am able to successfully build with Gradle.

Also, may I check what you mean by successfully build? To build the app using gradle, the command should be `gradlew build`. The `gradlew` command only displays information about gradle, it doesn't actually build your app.
</panel>

<panel  header="**42 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/89#issuecomment-1407672850" expanded>

I see, I'm guessing that this was generated using `gradle init`?

Perhaps, instead of initialising gradle from scratch, try merging the `add-gradle-support` branch into `master`. This should get you the correct `build.gradle` file which should contain a lot more settings then the one you currently have. Can refer to the guide [here](https://se-education.org/guides/tutorials/gradle.html).

![image](https://user-images.githubusercontent.com/31367001/215331316-65a758d5-b8e2-439f-b1b6-1b7c8ac41993.png)

</panel>

<panel  header="**43 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/92#issuecomment-1407674421" expanded>

I went with your former design for the same reasons you stated. Just want to add that the former also reduces the chances of user error. I think it helps in preventing a situation where the user is unintentionally misled into deleting the wrong task. 
</panel>

<panel  header="**44 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/93#issuecomment-1407806314" expanded>

Hi @MrTwit99. This is line 56 of your `Duke.java`:
```java
fileTasks = getFileContents("data/storage.txt", "data");
```

Java interprets `data/storage.txt` as a relative path (treats it the same as `./data/storage.txt`. This means that the actual full path is dependent on where the app is run from. Previously, you've likely always ran it from your `<project_root>` directory and hence the path is resolved to `<project_root>\data\storage.txt`.

In the screenshot provided, you are now attempting to run the app from `C:\Users\<name>` hence the path now resolves to `C:\Users\<name>\data\storage.txt` which does not exist.

Since it is not viable to always assume that `./data/storage.txt` always exist, it is better to create it at the start of the app if it is detected to not be there. This is also one of the requirements of the project.
![image](https://user-images.githubusercontent.com/31367001/215362766-54d654de-6cc3-4193-a076-5a3bb386cb79.png)

Also note that the project allows you to make the following assumptions:
![image](https://user-images.githubusercontent.com/31367001/215362841-8385bd0f-3744-4b5c-88a6-0c94990e0430.png)

</panel>

<panel  header="**45 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/92#issuecomment-1407881550" expanded>

> @rockman007372 The numbers in a items listing is meant to be the positions in that list, and hence, will always be 1, 2, 3, ... (i.e., dynamically generated for the current list of items). So, `delete 2` means 'delete the item at position 2 in the most recent listing'.

Hi prof @damithc , may I know the intended behaviour for the following scenarios?

Scenario 1: Deleting same index with find filter
Example commands:
```
todo lorem ipsum
todo hello
todo hello world
find hello
delete 1
delete 1
```
Is the expected result that `todo hello` and `todo hello world` are deleted? Or should the second `delete 1` result in an error?

Scenario 2: Deleting same index without filter
Example commands:
```
todo lorem ipsum
todo hello
todo hello world
delete 1
delete 1
```
Is the expected result that `todo lorem ipsum` and `todo hello` are deleted? Or should the second `delete 1` result in an error?

</panel>

<panel  header="**46 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/98#issuecomment-1409550960" expanded>

I experienced the same issue and solved it in the same way that @gohyongjing described
Not sure how widespread this is but I think it would be good to include as a note in the JavaFX tutorial, especially at part 2 ["Designing the Layout"](https://se-education.org/guides/tutorials/javaFxPart2.html#designing-the-layout) where the sample code sort of implies that the main method should be place inside the `Duke` class which extends `Application`
</panel>

<panel  header="**47 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/101#issuecomment-1409731722" expanded>

> I was not able to assign the methods given, as there is no drop down

Hi @anunayajoshi, not too sure what you mean by this. Forgive me if I interpret your question incorrectly.

If the goal is to assign a method to be called when some event occurs (e.g. when the send button is pressed), you can do the following:
1. Specify the name of the method to call under the appropriate event in Scene Builder
![image](https://user-images.githubusercontent.com/31367001/215661645-b51a844f-71da-4c56-a599-8e7308fb4509.png)

2. Create a method within your controller with the same name
```java
public class MainWindow extends AnchorPane {
    // some code

    @FXML
    private void handleUserInput() {
        // code to run when the event occurs
    }

    // some code
}
```

Scene Builder is oblivious of your code and is only aware of what is in the fxml file thus it cannot produce a dropdown menu for your methods if that is what you're trying to do. 
</panel>

<panel  header="**48 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/99#issuecomment-1409738210" expanded>

> Also, when the program closes, users will not be able to read the bot's reply to the bye command making it even more redundant.

I implemented my `bye` command to request from the user an additional line of input before closing using `Platform.exit()`. I think this is also a useful way to show any error messages before closing should the program run into any issues it cannot remedy (e.g. unable to read/create save data file when the app launches).
</panel>

<panel  header="**49 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/99#issuecomment-1409761967" expanded>

> Will the user become unhappy that s/he has to perform two steps to close the application, and chose to just close the Window manually instead?

I implemented it such that the second input can just be an empty line. My original thought was that if a user did not care about seeing the exit message, they could just press enter twice.

However, now that I think about it, perhaps that isn't the best approach as users likely wouldn't care whether there is an exit message. I'll likely remove the extra input for the `bye` command but still keep it around for when the app encounters an issue it cannot remedy as I think it's better for the user to see the error message before the app closes.

Thanks for pointing that out!
</panel>

<panel  header="**50 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/102#issuecomment-1409829287" expanded>

Try opening `DialogBox.fxml` in Scene Builder and change the min width and height of label to `USE_PREF_SIZE`

![image](https://user-images.githubusercontent.com/31367001/215681573-53eb1aa8-0a4c-45cb-969e-90d873150a36.png)

</panel>

<panel  header="**51 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/102#issuecomment-1409885090" expanded>

In my `DialogBox.fxml`, I forced my HBox width to a fix value (590 in my case because I set my ScrollPane width in `MainWindow.fxml` to 590). Perhaps you can try setting it to a fix value as well.

![image](https://user-images.githubusercontent.com/31367001/215692074-acc433e1-d6f2-4176-b26c-89cd9fb818a0.png)

I'm not sure if my exact settings would be helpful as I've tweaked my `DialogBox.fxml` since I made my previous comment in order to fix an issue where the label exceeds the width of the window if a line of the text is too long. If you still want to reference my fxml files, I've already pushed all my commits to my repo, can look at them there.
</panel>

<panel  header="**52 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/103#issuecomment-1409896406" expanded>

might be related to #102 
</panel>

<panel  header="**53 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1409930777" expanded>

Hello, this is my current GUI, still a WIP

![image](https://user-images.githubusercontent.com/31367001/215701634-4edcd086-9733-4c29-8655-15948bcd858c.png)

</panel>

<panel  header="**54 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/105#issuecomment-1409949725" expanded>

Might be related to #102, consider trying what was mentioned in my comment [here](https://github.com/nus-cs2103-AY2223S2/forum/issues/102#issuecomment-1409829287)
</panel>

<panel  header="**55 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/106#issuecomment-1410064250" expanded>

Your import order isn't in violation of the module's java coding standard, it's just that it doesn't match the order specified in the `checkstyle.xml` file you are using.

To change the import order of checkstyle, change the code in the following section of  `checkstyle.xml`:
```xml
<module name="CustomImportOrder">
    &gt;!-- some stuff -->
</module>
```

Looking at your current import style, it seems you group `duke` and `java` packages together so this import order might work for you:
```xml
<module name="CustomImportOrder">
    <property name="customImportOrderRules"
        value="STATIC###SPECIAL_IMPORTS###THIRD_PARTY_PACKAGE###STANDARD_JAVA_PACKAGE"/>
    <property name="specialImportsRegExp" value="&hat;org\."/>
    <property name="thirdPartyPackageRegExp" value="&hat;com\."/>
    <property name="standardPackageRegExp" value="&hat;(duke|java)\."/>
    <property name="sortImportsInGroupAlphabetically" value="true"/>
</module>
```

You're likely going to have to modify it when you start bringing in `javafx` packages. You can find more info about checkstyle import order checks [here](https://checkstyle.sourceforge.io/apidocs/com/puppycrawl/tools/checkstyle/checks/imports/CustomImportOrderCheck.html).
</panel>

<panel  header="**56 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/107#issuecomment-1410086268" expanded>

could you provide your `build.gradle` file?
</panel>

<panel  header="**57 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/107#issuecomment-1410147387" expanded>

Not sure if this will fix it but in your `build.gradle`, change `duke.Duke` to `duke.Launcher`

```
application {
    mainClassName = "duke.Launcher"
}
```
</panel>

<panel  header="**58 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/107#issuecomment-1410148707" expanded>

if it doesn't could you provide your Java version? That is what is your output if you run `java --version`?
</panel>

<panel  header="**59 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/107#issuecomment-1410151175" expanded>

welp that's probably the issue haha
</panel>

<panel  header="**60 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/107#issuecomment-1410278983" expanded>

Honestly not too sure how to fix this issue, maybe someone else can chime in.

In the meantime, maybe can try the following one at a time and see if they work:
1. If you haven't done so, restart your computer after installing jdk11
2. Push all your changes to your remote and clone to a separate directory (to clean out any files that are generated by gradle and intellij idea)
</panel>

<panel  header="**61 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/115#issuecomment-1411367069" expanded>

If I'm interpreting your question correctly, I think this question was sort of (but not fully) discussed in #99, maybe looking through the comments there would help a bit. The last [comment](https://github.com/nus-cs2103-AY2223S2/forum/issues/99#issuecomment-1410420911) in the post seems similar to what you're trying to accomplish
</panel>

<panel  header="**62 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/112#issuecomment-1411413277" expanded>

> I think the issue is that you are inside your duke directory.
> 
> Try navigating to the IP directory. The gradlew file is probably located there.

I think @Guo-KeCheng is probably right but the command provided is for Linux and Mac. If I'm not wrong, the command on Windows should be:
```
gradlew.bat checkstyleMain checkstyleTest
```
</panel>

<panel  header="**63 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/120#issuecomment-1412147399" expanded>

As prof @damithc has mentioned, don't delete `.idea` again.

`.idea` is a directory that Intellij IDEA uses to store data specific to your project that it needs. So certain changes you make to your project such as setting the JDK to use as well as data on the version control used and build automation tool used is saved in it. Intellij IDEA needs the `.idea` directory to function correctly.

When you add gradle to your project, you delete `.idea` so that Intellij IDEA can generate a new `.idea` directory which is up-to-date with the changes (the files in `.idea` directory are now setup such that it is aware that gradle is being used for your project).

Hence, after you delete `.idea`, close the project, and reopen the project, don't delete `.idea` again. Do remember to setup the JDK version being used again though since that setting was deleted when the old `.idea` directory was deleted (in case you need the guide for setting your JDK version, [here](https://www.jetbrains.com/help/idea/sdk.html#set-up-jdk) it is.
</panel>

<panel  header="**64 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/120#issuecomment-1412153823" expanded>

On a side note, not sure if your repo changes are the most up-to-date but if it is, you might want to change the mainClassName in the `build.gradle` file.
```
application {
    mainClassName = "<name_of_package_containing_Duke.java>.Duke"
}
```

In your case, since you didn't place `Duke.java` in any package, it should probably be:
```
application {
    mainClassName = "Duke"
}
```
Remember to update later when you move `Duke.java` into a package.
</panel>

<panel  header="**65 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/121#issuecomment-1412914726" expanded>

Seems like you're experiencing multiple issues with different causes:

> `Error: JavaFX runtime components are missing, and are required to run this application`

Likely caused by placing the `main` method inside a class which extends `Application`. Can be resolved by creating a different class (e.g. `Launcher`) which contains the `main` method as you have already done.

> However, I still keep being unable to import the symbols as shown in the image below.

Perhaps try pressing the reload all gradle projects button
![image](https://user-images.githubusercontent.com/31367001/216192577-c1566e4e-71b6-45db-8eac-1b3f1e133bfa.png)

If all else fails, push all your code to your remote repo and clone to a different local directory. Hopefully when all the files in `.gitignore` are generated again, your issue would be resolved.

> but I keep getting the following error message when I attempt to run the Launcher class:
> ![image](https://user-images.githubusercontent.com/40803540/216087177-7597acd1-9833-46a2-8792-6fb6232edeef.png)

Likely caused by not having a default constructor in the `Duke` class. `Application.launch` requires that the class specified has a default constructor as that will be the constructor use to create the object. Try adding a constructor in `Duke` that doesn't take in any parameters and just have it call `super()`.

```java
public Duke() {
    super();
}
```
</panel>

<panel  header="**66 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/113#issuecomment-1413108130" expanded>

> so I assumed setting the controller to DialogBox meant it now has a controller class. Is this not equivalent?

Not super familiar with JavaFX but perhaps you can think of it this way.

You are able to set the controller object dynamically at runtime using code. That is what the `fxmlLoader.setRoot(this);` line in the `DialogBox` class constructor is for. This means that you are not constraint to having to use a class named `DialogBox` every time, all you need is a class that inherits from the same Node type as the root in the `DialogBox.fxml` file (in this case it is `HBox`).

Why is this useful? The first thing that comes to mind is reusability. If I have a generic `fxml` that I want to reuse for many different scenarios, I now can.
</panel>

<panel  header="**67 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/125#issuecomment-1413145732" expanded>

Yup, seems like this is normal. If you look at the `addressbook-level3` code base, there is an explanation for it in the `Main.java` [file](https://github.com/se-edu/addressbook-level3/blob/master/src/main/java/seedu/address/Main.java).
</panel>

<panel  header="**68 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/132#issuecomment-1415733003" expanded>

Hi @homuntan02, this was mentioned in CS2103 Week 5

> If there is no default action, you can use the `default` branch to detect errors (i.e. if execution reached the `default` branch, raise a suitable error)

Essentially, if there is nothing to do in the default case, use it as an error checking tool. Should the default case ever be reached, then a bug has most likely occurred in the code. By throwing an exception, and most likely causing the program to crash, it would make it much easier when debugging.

If there is no default case, then there's a chance the code would just execute as per normal even when a bug occurs leading to none of the switch cases matching. This would make it much harder to debug as a user might experience strange behaviour and the dev will most likely have to spend more time digging through the code to try to find the cause.

Read more [here](https://nus-cs2103-ay2223s2.github.io/website/schedule/week5/topics.html#implementation-code-quality-error-prone-practices-basic-use-the-default-branch)
</panel>

<panel  header="**69 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/136#issuecomment-1416626237" expanded>

![image](https://user-images.githubusercontent.com/31367001/216741214-4c52569a-8895-487f-a783-d3c2fcee3ee3.png)

A bit confused on what you're asking. According to your image, there is a separate branch for `master` and `branch-A-Assertions` (according to the parts highlighted in red).

Forgive me if I misinterpret but perhaps what you're asking is why there is no split in the graph on the left (the blue line doesn't split into a different colour). That's because there isn't a need to. The graph on the left is merely a visual tool to make it clear which commit is on which branch.

In this case, since `master` has no commits made to it after the branching point, the graph doesn't split as the user can clearly make out which commits belong to `master` and which belongs to `branch-A-Assertions` purely base on the labels highlighted in red.

If both branches have commits made to them after the branching point, then the graph would split so as to make it clear which commit is on which branch.
</panel>

<panel  header="**70 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/136#issuecomment-1416641936" expanded>

> I was also wondering why some of the blue circles are solid circles but one of them is hollow?

> ![image](https://user-images.githubusercontent.com/31367001/216741214-4c52569a-8895-487f-a783-d3c2fcee3ee3.png)

If you're referring to what I circled in green, that's just to indicate to you which commit you are currently on (the state of all your files in the project directory will match this commit). If I'm not wrong, in sourcetree you can double click a commit to go to it. This is called a git `checkout`.

If you make changes to your files, the hollow circle will move to a new entry in the graph called "Uncommited change". This isn't a commit but just sourcetree's way of telling you that the state of your current files are different from the commit that you were previously on.
</panel>

<panel  header="**71 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/143#issuecomment-1418375280" expanded>

Hard to give an exact solution as I think the "best" way depends on the exact scenario.

Personally, in most situations, I avoid the problem entirely by having each of my case blocks simply call a method that handles that specific case. I find that it keeps the method short, helps in maintaining SLAP, and also makes it easier for me to find the relevant code when I need to.

```java
void bar() {
    switch (foo) {
    case 1:
        handleCase1();
    case 2:
        handleCase2();
    default:
        // <some code>
}

void handleCase1() {
    int bar = 1;
    // <code for case 1>
}

void handleCase2() {
    int bar = 2;
    // <code for case 2>
}
```

Alternatively, sometimes, I prefer extracting the switch block into it's own method:
```java
void bar(Foo foo) {
    int baz = bar(foo);
    // <some code>
}

int bar(Foo foo) {
    switch (foo) {
    case 1:
        return 1;
    case 2:
        return 2;
    default:
        // <some code>
}
```
</panel>

<panel  header="**72 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/151#issuecomment-1423845999" expanded>

1st error, probably change `Willy` to `willy`. The convention we are using is to use all lowercase for java packages. Do remember to rename the `Willy` directory as well.

2nd error, check if you have some additional spaces after `/**`. If so, remove them. If you're using Intellij IDEA, there is a setting that you can use to auto remove trailing whitespaces in your files. Can take a look [here](https://se-education.org/guides/tutorials/intellijCodeStyle.html#tweak-auto-remove-trailing-spaces) if you're interested.
</panel>

<panel  header="**73 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/154#issuecomment-1424049350" expanded>

Likely caused by this part of your `build.gradle`
```
application {
    mainClassName = "seedu.duke.Main"
}
```

Perhaps, try changing `seedu.duke.Main` to `<package_name>.Main` where `<package_name>` is the name of the package containing your `Main` class.

Looking at your code, it should probably be:
```
application {
    mainClassName = "duke.Main"
}
```
</panel>

<panel  header="**74 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/152#issuecomment-1424062331" expanded>

For me, I use it to check for whether the assumptions I made are fulfilled. When coding there are a lot of times where I make assumptions about the arguments I pass to my methods. For example:
```java
private void foo(String str) {
    return str.split(" ");
}
```

In this `foo(String)` method, there is an assumption that `str` is not null. Hence an assertion could be use to ensure `str` is not null. 

It helps in identifying errors and also, personally, I think of it as a good way to make it explicit the assumptions my method makes (especially for private methods where I don't write JavaDocs for).
</panel>

<panel  header="**75 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/152#issuecomment-1424198493" expanded>

> for our chatbot if the string input come from user，wouldn't it be too risky to use assertion as all the assertion will be disable during production environment

Agreed, if we're handling user inputs, then exceptions should probably be used instead. The example I gave is just some arbitrary method meant to make the point that we often make assumptions in our code. It isn't a method I'd call with any kind of user input (at least not before running through some method to validate the input).

Perhaps, some might think that there's no point in having assertions in such cases by the following logic: "If the method does not take user input, then I have full control of the method arguments, thus I can always make sure that the arguments I pass in are always valid (fulfills the method's assumptions)."

But what's to say that someone else who takes over the code base is aware of these assumptions. And what's to say that the author of the code may not one day accidentally make a mistake and call the method without having the assumptions be fulfilled.

The goal of assertion, or at least the way I see it, is 2 folds:
1. It serves as a kind of "documentation", making it explicit what assumptions you have made so that another programmer or maybe even future you (as in the author of the code) would be able to remember the assumptions
2. It is for you to detect errors and also pinpoint the culprit line of code much more easily when you're doing unit testing, integration testing, UI testing, or manual testing. They should definitely not be enabled in the production build.

But yeah, just my opinion. Always happy to hear other's thoughts and perhaps also disagreements
</panel>

<panel  header="**76 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/162#issuecomment-1426770166" expanded>

Hi, trying to understand the issue here. If the issue is that you want to undo a local merge, that is revert the `branch-A-CodeQuality` branch to the commit before it merged into master branch, perhaps consider resetting your branch to the commit that `origin/branch-A-CodeQuality` is at.

To do so on sourcetree, perhaps look at the guide [here](https://confluence.atlassian.com/sourcetreekb/reset-branch-to-a-commit-788730897.html).
</panel>

<panel  header="**77 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/161#issuecomment-1426781757" expanded>

Perhaps instead of creating a new `DialogBox`, you could consider having the `label` of `DialogBox.fxml` scale with the input. Not sure if [this](https://github.com/nus-cs2103-AY2223S2/forum/issues/102#issuecomment-1409829287) would allow you to do so since the way to do it depends on how your `fxml` is structured.
</panel>

<panel  header="**78 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/178#issuecomment-1427905705" expanded>

If the code works when your friend clones from your repo, how about pushing all your local changes to your remote repo, deleting the local repo, and clone your remote repo to a different local directory?
</panel>

<panel  header="**79 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/179#issuecomment-1427953978" expanded>

Interesting, I'm running Linux on bare metal and have not gotten this issue. Base on the issue, I think a possible cause is that you're using a wayland window system while JavaFX is looking for an x11 window system. Perhaps try switching to x11 by following this [guide](https://beebom.com/how-switch-between-wayland-xorg-ubuntu/)?

If it doesn't work, may I know more info about your setup? Are you running Ubuntu within a virtual machine or on bare metal? And just to be sure, are you running Ubuntu with a desktop environment or just on terminal?
</panel>

<panel  header="**80 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/179#issuecomment-1427997328" expanded>

Just tested on an Ubuntu 22.04 virtual machine. Was able to recreate the issue when running using wayland. The issue does not occur after switching to xorg.

![image](https://user-images.githubusercontent.com/31367001/218480285-c8914e13-701b-4ee9-99d4-c65cd2a660c3.png)

From what I gather, there isn't much you can do with regards to your code or build settings. The issue has to be solved by the user.
</panel>

<panel  header="**81 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/180#issuecomment-1429763086" expanded>

Hi @seadragon2000341, in the `gradle.yml` file's codecov step, there is a line that is `fail_ci_if_error: false`. This should make it such that even if codecov fails, the Github Action result should still be successful as long as the other steps pass.

Could you perhaps check if the step that failed is indeed the codecov step? You can do so by going to the page for the specific pull request and open the "Checks" tab.
![image](https://user-images.githubusercontent.com/31367001/218754476-c2d8da65-b233-4f7d-9553-6a13a37bba78.png)

</panel>

<panel  header="**82 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/186#issuecomment-1430650844" expanded>

I'm getting the same issue with the help window of AB3, it eventually resizes correctly if I open and close it multiple times. I'm also using KDE plasma (albeit on arch instead of manjaro) but haven't experience the issue with my IP.

Perhaps you could try setting the minWidth and minHeight of the stage?

Something like this:
```java
stage.setMinWidth(400.0);
stage.setMinHeight(600.0);
stage.setResizable(false);
```
</panel>

<panel  header="**83 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/196#issuecomment-1433124942" expanded>

Likely not a warning you need to be worried about. It's caused by a mismatch in the JavaFX version specified by your fxml files (version 19) and the JavaFX version that is actually running the application (version 11). Not sure why it doesn't show up for ZuluJDK 11.

I think it's an warning that is save to ignore as long as you don't face any incompatibility issues caused by the version mismatch.

If you want to get rid of the warning, simply open each of your fxml files in a text editor and change the line:
```fxml
<fx:root ... xmlns="http://javafx.com/javafx/19" xmlns:fx="http://javafx.com/fxml/1">
```
to
```fxml
<fx:root ... xmlns="http://javafx.com/javafx" xmlns:fx="http://javafx.com/fxml">
```
</panel>

<panel  header="**84 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/214#issuecomment-1436406188" expanded>

The error message seems to imply that your jar file was not compiled using Java 11. Could you run a `java --version` on your laptop to check if you have installed Java 11 and not some other version? If you're using IntelliJ, perhaps also check that your project is using the correct jdk.
</panel>

<panel  header="**85 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/315#issuecomment-1493889414" expanded>

> the example you gave doesn't concern object creation, right?

My bad, my phrasing was poorly done. My intention was to ask if we need to specify where the objects are obtained from, be it through a method call (such as the case for `p`) or through a call to a constructor.

Either way, your answer addresses my issue. Thanks!
</panel>

<panel  header="**86 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/320#issuecomment-1495654304" expanded>

Probably unlikely, but I've encountered similar issues in the past when I use git on a directory that is being synced by some application (e.g. onedrive, google drive).
</panel>

<panel  header="**87 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/320#issuecomment-1496047614" expanded>

Does it perhaps occur when you're doing a `git merge`?

For example, your teammate updated  the `master` branch so you merge the updated `master` branch into your `feature-branch`. However, your teammate made some changes which overwrites your changes. If your `feature-branch` is very far behind on commits from the `master` branch, sometimes, git doesn't detect such changes as merge conflicts.
</panel>

<panel  header="**88 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/337#issuecomment-1498291552" expanded>

Hi, as the one that originally reported this issue during the PE-D, your fix works great.

![image](https://user-images.githubusercontent.com/31367001/230237376-8cab8682-fd3d-4f0f-8476-6a3c7a30e780.png)
</panel>

</panel>


<panel type="info" header="### 2. LEON..ZHEN `@Tempura-Person` (48 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Feature Freeze - Is fixing typos and incorrect commands in help messages allowed?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/339" expanded>

![image](https://user-images.githubusercontent.com/92144641/230271535-007c14cb-1498-4157-a917-23a031b8a342.png)

Above, is the command success message of one of the functions in our app.
It mentions 'students' (which comes from an unchanged, early iteration) even though students are never mentioned in our User Guide.
The intended fix is to change all mentions of 'students' to 'athletes'. This is to prevent users from questioning what a 'student' means in the context of our app, as they were never mentioned.

Are updating these error messages allowed?
</panel>

<panel  header="**2. :fas-info-circle: Feature Freeze - Changing command name**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/313" expanded>

Below are some of the existing user commands that 'add' things in our app:

- `add`
adds an athlete to the athlete list
- `add-tag`
adds a tag to an athlete
- `create-session`
adds a session to the session list
- `student-add`
adds a student to a session

One bug report we received from the PE-D was that the naming for these commands are inconsistent and may cause confusion, preventing users from using the app properly.
We agree with this notion and intend to standardize the names for these commands as such:

- `add`
- `add-tag`
- `add-session`
- `add-student`

We will NOT change the method signature or functionality of the commands.
All we are intending to change are the names and the names only.

May I ask if this is acceptable in the v1.4 Feature Freeze?
Thank you.
</panel>

<panel  header="**3. :fas-info-circle: Changing name of tP on tP Teams List**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/233" expanded>

Hello, i am speaking on behalf of team CS2103T-W13-2 as a member.

We have decided to change our tP name to SportSync (previously, it was Unibook)
This was because we decided that the new name better describes the functionality of the product and its value to the end user.

However, the tP name on the tP Teams List is still logged under 'Unibook'.
Is there a way to change it to SportSync? Would this cause any unforeseen problems to the logging of our code progress?
</panel>

<panel  header="**4. :fas-info-circle: tutorial-adding-command PR not tracked?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/226" expanded>

Hi, i've checked the tp progress boards and i noticed that the item !Tutorial has not been marked as done despite me having sent the PR to my team's repo several days ago.

![image](https://user-images.githubusercontent.com/92144641/221397821-91d02c9f-fdc4-4c16-a8cb-25599f3d347d.png)

The proof of me having done the tutorial 2 pull request is below:
https://github.com/AY2223S2-CS2103T-W13-2/tp/pull/1

Why is this the case?
</panel>

<panel  header="**5. :fas-info-circle: Accessing .txt file in resources folder**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/172" expanded>

![image](https://user-images.githubusercontent.com/92144641/218317252-ad14ebf4-8036-476f-bc1e-469d922ac391.png)

Hi there, i've implemented the D-Trivia extension in Week 5, and i realized that it won't work when exported to a jar file because it relies on facts.txt, which contains all the facts that the extension needs to access.

I can't place facts.txt in the data folder where i keep my save, since that won't be bundled into the jar file upon building.
I can only place it in the resources folder. However, I am unable to access the file itself through the usual methods.
I have tried "resources/facts/facts.txt" too.

```

  /**
     * Loads facts from the facts/facts.txt file into the facts ArrayList.
     * @throws DukeException Thrown if the facts/facts.txt file is not found.
     */
    public void loadFacts() throws DukeException {
        File dukeFactsPath = new File("facts/facts.txt");
        ......
```

How do i access the facts.txt file in my resources folder so I can read it?
</panel>

<panel  header="**6. :fas-info-circle: How to resize height of DialogBox to fit content?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/102" expanded>

![image](https://user-images.githubusercontent.com/92144641/215677456-b3823e45-297b-44e1-8b8e-54450ba58079.png)

Hi there, I have managed to fit a GUI onto the Duke logic, but when the Label in the DialogBox gets too long, it shows the rest as ellipsis.
May I know how to fix this?
I have tried searching online, but to no avail.
</panel>

<panel  header="**7. :fas-info-circle: JavaFX Tutorial Issue Regarding DialogBox.java**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/95" expanded>

Hi there, I am currently on Part 4 of the JavaFX tutorial (that i am doing on a separate project folder so as to preserve my current IP)
and i am having trouble with understanding what they meant under the header "Using FXML in our application".

It says, "For our custom DialogBox, we did not define a controller so let's create a controller for it."
However, DialogBox.java was already created back in Part 3, under the header "Iteration 2 – Adding Dialog Boxes"

I am confused if I am doing this right, as the method signature for the new DialogBox.java is incompatible with the old one.
![image](https://user-images.githubusercontent.com/92144641/215427805-c11f4a69-3d42-4e79-bbea-0b705d8f56bf.png)


This is how it differs between the two: (this is in MainWindow.java)
![image](https://user-images.githubusercontent.com/92144641/215428583-a7f22332-72b1-4002-9f1b-69f5c3d90056.png)

</panel>

<panel  header="**8. :fas-info-circle: Saving error when exporting iP to jar file**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/47" expanded>

![image](https://user-images.githubusercontent.com/92144641/213984953-ab8e5f6f-f2ca-4715-8eb2-8caf721f7b92.png)

as suggested by the instructions below, i exported my iP into a jar file using intelliJ's build artifacts function.
The whole thing functions properly besides the 'bye' command (which does not terminate the process) and the autosave feature failing to work (as i set up an error message to display if it happens)

![image](https://user-images.githubusercontent.com/92144641/213984998-976e77a5-acc3-43ca-b27f-da17f760f97a.png)

These bugs seem to be exclusive to the exported jar file (the project still works fine within intelliJ) and i don't know how to fix them properly.
</panel>

<panel  header="**9. :fas-info-circle: Cannot resolve symbol java after installing Gradle**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/43" expanded>

![image](https://user-images.githubusercontent.com/92144641/213956548-9ebc4767-e50e-4ff3-9fa7-6da2684b1da5.png)

after following the steps in the Gradle tutorial on the site, (scenario 2, then scenario 1)
![image](https://user-images.githubusercontent.com/92144641/213956612-b5fff2c8-fa74-4618-a7ea-d320f07756ef.png)

I can't seem to be able to run my code as usual, nor is it detecting java in the code.
How can i fix this?
</panel>

<panel  header="**10. :fas-info-circle: Issue With Duke Automated Testing**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/29" expanded>

Hi there,

I have started on setting up the automated testing for Duke and it seems to be working funny.

When i enter my commands manually, they work just fine and produce the intended output.
![image](https://user-images.githubusercontent.com/92144641/213445536-5e8b446a-4d49-457e-bd6f-cacd7e966b82.png)

but when i try to use runtest.bat on the same commands, it gives a NoSuchElementException.
![image](https://user-images.githubusercontent.com/92144641/213445634-d0666bfa-3777-4378-ab96-931fb69e0ed4.png)

what seems to be going wrong, here?

</panel>

<panel  header="**11. :fas-info-circle: Automated Duke Testing Query**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/15" expanded>

Hi there,

Sorry for opening yet another query so soon, but I feel that the instructions given in the page here, for automating the Duke testing using runtest.bat, are a little hard to understand for me.

https://se-education.org/guides/tutorials/textUiTesting.html

Step 4 and 5 in particular are confusing, where we need to set up the EXPECTED.txt and input.txt files with the outputs and commands. I have no idea how they are supposed to be formatted. (especially since my Duke messages have borders around them)

Could there be an example EXPECTED.txt and input.txt file for us to see and get a better idea of how to format the text inside?
</panel>

<panel  header="**12. :fas-info-circle: Clarification on Error Handling Requirements**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/11" expanded>

Hi all,

I'm on Level-5 of Duke and I have implemented the error handling such that if an error is detected, Duke throws a DukeException and the whole program is terminated. 

I would like to clarify if we need to terminate the program if an error is detected.

If not, and an error message should simply be printed instead, does this mean that we don't need to throw a DukeException if an error is detected? 

Thank you.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/11#issuecomment-1384983929" expanded>

I can't think of how i can throw a DukeException yet also not terminate the program at the same time.
I have reverted all my exception throws to just print statements.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/11#issuecomment-1385034884" expanded>

I considered that, but i have different error messages depending on what type of exception it is.
I can't make DukeException extend one of these types of exceptions otherwise i feel it would defeat the purpose of creating DukeException to begin with.
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/11#issuecomment-1385064596" expanded>

It was throwing the exception that terminated the program, in my case (though I have doubts, myself)

```
case ("mark"):
                    try {
                        String MarkString = UserScan.nextLine().strip();
                        // ERROR: mark format is anything other than [ mark <insert integer> ]
                        if (MarkString.length()==0) {
                            throw new DukeException("\n" + border + "[ERROR]\nUh, mark command format is used wrongly.\nCorrect format is as follows:\n" +
                                    "[ mark <insert INTEGER> ]\n" + border);
                        }
                        int MarkInput = Integer.parseInt(MarkString) - 1;
                        TaskList.get(MarkInput).MarkDone();
                        System.out.println(border + "Okay, the following task is marked as done!\n");
                        System.out.println((MarkInput+1 + ". ") + TaskList.get(MarkInput).toString() + "\n" + border);
                        break;
                    }
                    // ERROR: mark is NOT paired with an integer (e.g. unmark two, unmark 2.3)
                    catch (NumberFormatException | InputMismatchException err) {
                        throw new DukeException("\n" + border + "[ERROR]\nUh, mark can only be used with an INTEGER. (e.g. 1, 2...)\n" + border);
                    }
                    // ERROR: mark target does not exist (e.g. task number is out of bounds)
                    catch (IndexOutOfBoundsException err) {
                        throw new DukeException("\n" + border + "[ERROR]\nUh, you can only mark task numbers that exist.\nYou have "
                                + TaskList.size() + " task(s) in your list.\n" + border);
                    }
```
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/11#issuecomment-1385128392" expanded>

> @Tempura-Person Looks about right. If you nest your switch block inside another try-catch block which catches `DukeException`, it shouldn't terminate the program
> 
> Something like this:
> 
```java
> while (true) {
>         // some other code
>         try {
>             // your switch code block
>         } catch (DukeException e) {
>             System.out.println(e.errorMessage);
>             continue;
>         }
>         // some other code
> }
```
> 
> Also, probably would be good if you move the code for each command into it's own method or class. Else, you're going to have one massive method that is hard to read and debug with a lot of nesting (lots of tabs).

Thank you for that suggestion, I tried it and it worked properly.
Though the error message displays in the normal way and not the red font error messages normally print in, at least i feel like DukeException is useful now.

![image](https://user-images.githubusercontent.com/92144641/212867398-9bf3efd5-565d-4e0a-912a-6533f1dbaac8.png)

</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/15#issuecomment-1396857128" expanded>

Hi there,

Step 3 of the automation needs me to 
"Update the javac and java commands in the script to match the name/location of your main class."

how exactly do we do that?
I assume its this line in the runtest.bat file that has to be "updated"?
many thanks.

'
javac  -cp ..\src\main\java -Xlint:none -d ..\bin ..\src\main\java\*.java'
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/15#issuecomment-1396858947" expanded>

Another thing, the following error pops up if i try to run runtest.bat as is:

cmd.exe /c runtest.bat
'javac' is not recognized as an internal or external command,
operable program or batch file.
********** BUILD FAILURE **********

Process finished with exit code 1

what exactly is this?

</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/15#issuecomment-1396873672" expanded>

![image](https://user-images.githubusercontent.com/92144641/213438810-50d33fac-a320-4ac7-aa7f-6d8087158f75.png)
oh, uh...
is this cause for concern?
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/15#issuecomment-1396879820" expanded>

ah, yep.
![image](https://user-images.githubusercontent.com/92144641/213439441-7c8d5275-bddf-4121-b9fb-850f445c5793.png)

</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/29#issuecomment-1396934987" expanded>

![image](https://user-images.githubusercontent.com/92144641/213448410-beb3726d-a0cc-4385-8ac2-bcff4f2bb234.png)

seems that neither are it?

for context, i left my file still as Duke.java, i didnt put it in a package, nor did i change anything in the runtest.bat file. 
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/15#issuecomment-1396979265" expanded>

Alright, so it was apparently that i did NOT install JDK.
oops.
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/29#issuecomment-1396982734" expanded>

![image](https://user-images.githubusercontent.com/92144641/213455750-51c06686-5423-497b-b6b3-657596017e20.png)
huh, strange.
it seems to only read up to 'delete 2', it doesnt even print out my 'bye' message before terminating itself?
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/29#issuecomment-1397837007" expanded>

Thanks, I removed the error case entirely for the moment, now it works.
</panel>

<panel  header="**25 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/43#issuecomment-1399736735" expanded>

For context, i have tried some fixes from the internet such as:

1. File > Invalidate Caches and Restart
2.  Delete the .idea file and open the ip project again

to no avail.
</panel>

<panel  header="**26 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/43#issuecomment-1399750228" expanded>

![image](https://user-images.githubusercontent.com/92144641/213961283-8f3a8af1-23d0-432f-8f71-1e8e54df92d2.png)

no luck, i've tried cloning it over to the same directory (next to ip) under a different name (ip2)
and even on the D drive under a different name. same problem persists.
</panel>

<panel  header="**27 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/43#issuecomment-1399769033" expanded>

> Are you able to run Gradle commands in the terminal e.g., `gradlew run` ?

![image](https://user-images.githubusercontent.com/92144641/213963970-6979fa66-69e8-4752-8f0b-8500648cba55.png)

it seems that it does
</panel>

<panel  header="**28 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/43#issuecomment-1399802138" expanded>

> > ![image](https://user-images.githubusercontent.com/92144641/213963970-6979fa66-69e8-4752-8f0b-8500648cba55.png)
> > it seems that it does
> 
> Seems this one failed. Was the code working before you added Gradle?
> 
> If you can build/run/test using Gradle commands in the terminal, the problem could be something to do with Intellij. Perhaps you can clone the initial upstream repo https://github.com/nus-cs2103-AY2223S2/ip and try to set it up in Intellij (without Gradle) to see if it still works.
![image](https://user-images.githubusercontent.com/92144641/213967881-ea1f5886-fa41-4edb-b66e-05dbeabfd5e2.png)

my code was fully working, up till i merged the origin/add-gradle-support commit on sourcetree and followed the gradle setup tutorial.
</panel>

<panel  header="**29 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/43#issuecomment-1399804990" expanded>

Strange, i checked out to the commit just before i merged the gradle branch in, and now java isnt detected there, either.
What did the merge damage, exactly?

![image](https://user-images.githubusercontent.com/92144641/213968289-3c4c0202-28f4-48e4-adcf-592b76bbceef.png)

</panel>

<panel  header="**30 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/43#issuecomment-1399806833" expanded>

![image](https://user-images.githubusercontent.com/92144641/213968553-db80689f-0ffd-4b0c-919b-d3218e74d328.png)

</panel>

<panel  header="**31 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/43#issuecomment-1399811605" expanded>

![image](https://user-images.githubusercontent.com/92144641/213969228-db6377ff-dab8-41b4-92c6-7f511d48f505.png)

i changed these, and also invalidated caches with all boxes ticked.
yeah... 
</panel>

<panel  header="**32 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/43#issuecomment-1399832055" expanded>

![image](https://user-images.githubusercontent.com/92144641/213972412-9dba2436-311d-48bb-abdb-9bf8891e0fe1.png)

thank you for suggesting the jdk/sdk fix, i assumed they were corrupted too, so i just deleted the entire jdk file manually and reinstalled it. now it recognises java.
</panel>

<panel  header="**33 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/47#issuecomment-1399913129" expanded>

for some context:
![image](https://user-images.githubusercontent.com/92144641/213985657-8d4a1df3-a202-4129-a693-4a2206a11531.png)
how 'bye' works is that all user input is handled by the Parser class.

The Parser class has a loopEnd boolean that signals when the 'bye' command has been entered, before updating it to true.

![image](https://user-images.githubusercontent.com/92144641/213986122-69c50601-3e67-4f2a-b362-1fa24dece312.png)

At the end of every command of user input, the main method (in the Duke class) updates to be the same as loopEnd in the Parser class, so when loopEnd in Parser is true, the loop to accept user input also stops in the main method.
</panel>

<panel  header="**34 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/47#issuecomment-1399914393" expanded>

as for the autosave, it is also handled by Parser automatically every time a command is handled.
![image](https://user-images.githubusercontent.com/92144641/213986302-8d89a894-a189-48a7-8d7e-3e37c803b300.png)

![image](https://user-images.githubusercontent.com/92144641/213986248-4137b496-3785-44fe-8df0-ab584e88bf57.png)

i assume the error is because the filepath "data/duke.txt" cannot be accessed, but isn't this already a relative filepath?
</panel>

<panel  header="**35 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/47#issuecomment-1400003309" expanded>

that did it, i didnt check if the file and directory existed first time around, now it works in .bat autotesting and the exported .jar file.
Thanks!
</panel>

<panel  header="**36 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/95#issuecomment-1408467266" expanded>

I'm guessing after setting up FXML, the Duke.java made through the tutorial is no longer needed and i can simply attach my existing Duke.java in my actual IP onto it?

</panel>

<panel  header="**37 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/102#issuecomment-1409867393" expanded>

Strangely enough, it will seem alright as long as the command response isnt too large,
after which the thing glitches out.
For reference, what are your SceneBuilder size settings for the DialogBox?
I am using your Label size settings right now as reference.
![image](https://user-images.githubusercontent.com/92144641/215688716-41c37791-5d89-42da-9e39-4f1617e0b824.png)

</panel>

<panel  header="**38 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/99#issuecomment-1409904112" expanded>

in which case, it should be ok if my bye command does nothing, as long as Duke saves my tasklist properly after every command?
</panel>

<panel  header="**39 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/172#issuecomment-1427387694" expanded>

Hi all, I've tried implementing getResourceAsStream() from the tutorial sent by Guanzhou03 and I have been finding great difficulty.

below are the methods i have implemented to load an ArrayList&gt;String> with facts from the facts.txt file.

    'public void loadFacts() throws DukeException {
        InputStream dukeFactStream = new Trivia().getFileFromResourceAsStream();
        transferFactsFromStream(dukeFactStream);
    }'
    
    'private InputStream getFileFromResourceAsStream() throws DukeException {
        Ui ui = new Ui();
        ClassLoader classLoader = getClass().getClassLoader();
        InputStream inputStream = classLoader.getResourceAsStream("/facts/facts.txt");
        if (inputStream == null) {
            throw new DukeException(ui.formatLogicError("I can't find facts.txt!"));
        } else {
            return inputStream;
        }
    }'
    
    'private void transferFactsFromStream(InputStream is) throws DukeException {
        Ui ui = new Ui();
        try {
            InputStreamReader streamReader = new InputStreamReader(is, StandardCharsets.UTF_8);
            BufferedReader factReader = new BufferedReader(streamReader);
            String factLine = factReader.readLine();
            while (!factLine.equals("")) {
                this.facts.add(factLine);
                factLine = factReader.readLine();
            }
        } catch (IOException ex) {
            throw new DukeException(ui.formatLogicError("error getting facts from facts.txt!"));
        }
    }'
    
when i call loadFacts(), it gives me a very long StackOverflow error. I am not sure why this is the case.
![image](https://user-images.githubusercontent.com/92144641/218381287-e6a60d95-2276-4676-87e9-a3c2241d8c45.png)

it points to the line in loadFacts() (line 31):
'InputStream dukeFactStream = new Trivia().getFileFromResourceAsStream();'

any idea why this is the case?
</panel>

<panel  header="**40 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/172#issuecomment-1427395062" expanded>

i have considered that it may be the while loop in transferFactsFromStream(), but i removed that and the error still persists regardless.

There are no other loops regarding the Trivia function
</panel>

<panel  header="**41 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/172#issuecomment-1427409741" expanded>

https://github.com/Tempura-Person/ip/tree/TestBranch_Trivia

here it is, any help is much appreciated! 
note, my goal for changing all this code is to make sure the fact command works in the GUI when exported to a jar file.

To test, type in
" fact "
in the Duke GUI.
</panel>

<panel  header="**42 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/172#issuecomment-1427430441" expanded>

@teekaytai I tried out your suggestions, but now the GUI simply defaults to not being able to find the facts.txt file.
Somehow, the inputStream is null.

![image](https://user-images.githubusercontent.com/92144641/218389217-b298bf05-1040-4b88-bbf3-c4eb86eb8b17.png)

for reference, this is the filepath to facts.txt in resources.
![image](https://user-images.githubusercontent.com/92144641/218389273-7afd773b-4ed7-48c6-b898-45caaedd4763.png)

</panel>

<panel  header="**43 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/172#issuecomment-1427526183" expanded>

Thanks, it started working again with your tips!
</panel>

<panel  header="**44 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/226#issuecomment-1445291597" expanded>

ok, i am creating the pull request directly from the branch now.
will it still detect it if i close the pull request immediately after?
</panel>

<panel  header="**45 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/226#issuecomment-1445563201" expanded>

Hi, i checked the tp progress dashboard again and the tutorial has been counted,
but the v1.1 PRs one has still not been checked. this is confusing as i have already done several PRs and have assigned them to milestone v1.1.
i do not know where i have gone wrong.



</panel>

<panel  header="**46 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/226#issuecomment-1445569037" expanded>

ah, i see. i should probably start branching.
</panel>

<panel  header="**47 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/313#issuecomment-1493568121" expanded>

thank you sir, noted.
</panel>

<panel  header="**48 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/339#issuecomment-1498726370" expanded>

thank you, noted.
</panel>

</panel>


<panel type="info" header="### 3. FRAN.. YIK `@francisyzy` (47 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: EditCommand FeatureFlaw or Bug**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/333" expanded>

Hi Prof, when doing further testing on my work, I've encounter a bug and not sure if it would be classified as a featureFlaw.

When editing the 'patient', the patient must show up in the filtered list or else it would show that it cannot be found. It is not intended.

This is our [UG](https://github.com/AY2223S2-CS2103-F11-3/tp/blob/d69ba11cbd28baaf74d45260fb5d35fd86fc30c0/docs/UserGuide.md#edit---edit-a-patient) before the feature freeze.  It shows that the user can edit the patient using the ID and did not mention that the patient must show up in the filtered list.

I had to fix a [similar bug](https://github.com/AY2223S2-CS2103-F11-3/tp/issues/195) for a different related command but did not catch this bug before PE-D.

Would like to check if I am able to fix this BUG or file it under [planned enhancement](https://nus-cs2103-ay2223s2.github.io/website/schedule/week12/project.html#:~:text=Using%20%27Planned%20Enhancements%27%20DG%20section%20to%20counter%20known%20feature%20flaws)
</panel>

<panel  header="**2. :fas-info-circle: Importance of Proper RepoSense**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/268" expanded>

From the module website, it says that we should keep track of authorship of code. This may cause additional rigor if we have to use @@author tags everywhere. How important is this component, should we just use git history for tagging instead?

https://nus-cs2103-ay2223s2.github.io/website/admin/tools.html#tool-reposense-for-authorship-tracking
</panel>

<panel  header="**3. :fas-info-circle: CS2103 website redirect broke**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/248" expanded>

https://www.comp.nus.edu.sg/~cs2103

![image](https://user-images.githubusercontent.com/24467184/224309047-c256f397-3eb6-4e2d-8952-f52d8bf01225.jpeg)
</panel>

<panel  header="**4. :fas-info-circle: Possible for Teammates tP links to be sent earlier?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/135" expanded>

Hi Prof @damithc,

Is it possible for you to send out tP teammates submission links earlier in the week? Our group meets during the weekend and it would be beneficial to know what are the exact submission requirements that the module requires before we do the meeting.

Thanks!
</panel>

<panel  header="**5. :fas-info-circle: [iP] Level-7 file pathing**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/31" expanded>

Any good idea on how to store Duke data file into `[project_root]/data/duke.txt` properly? 

There will be a few differences in running the project either via runtest.sh and running from bash. 
The working directory will either be in `[project_root]/text-ui-test` or `[project_root]/src..../`

What is the best practice of getting a constant working directory, so that the data file can be saved in `[project_root]/data/duke.txt`.


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/32#issuecomment-1398021907" expanded>

Would like to check if you're referring to this https://nus-cs2103-ay2223s2.github.io/website/admin/ip-w3.html#a-packages? Seems like its something to be done for iP in Week 3
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/65#issuecomment-1406135563" expanded>

I used enums as String constants, below are a few examples of what I did:
```java
public enum Views {
    LINE_STRING("____________________________________________________________"),
    WELCOME_STRING("Hello! I'm Duke\n      What can I do for u?"),
    END_STRING("Bye. Hope to see you again soon!"),
    EMPTY_LIST_STRING("Hey, the list is empty!"),
...
```
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/68#issuecomment-1407312403" expanded>

Not too sure but you can try use sdkman to install java via comandline. https://sdkman.io/install
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/91#issuecomment-1407680136" expanded>

Is this a good [checkstyle.xml](https://github.com/se-edu/addressbook-level3/blob/master/config/checkstyle/checkstyle.xml) to use? I've used it for my check styles
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/100#issuecomment-1409671974" expanded>

I had the same error and I fixed it by changing my `Duke.java` to something like this:

```java
    /**
     * Default constructor for Duke
     */
    public Duke() {
        ui = new Ui();
```

and the main method to something like this:
```java
    public static void main(String[] args) {
        Application.launch(Duke.class, args);
    }
```
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/94#issuecomment-1409675486" expanded>

I think the grading script marks it as merged if there are no commits ahead of master. Seems like you have 2 commits ahead of master. ![215638925-65bcbbfd-aba5-41ea-bd5f-572defa054b7](https://user-images.githubusercontent.com/24467184/215652553-025c7b8f-812f-436b-9b22-52ac293a579b.png)

When I merged my code using rebase, there were commits ahead of master and my branches were not marked as merged, I had to fiddle around with those commits and force push those branches. 

</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/109#issuecomment-1410276932" expanded>

Just remember to update your gradle.build files and text-ui-test!
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/112#issuecomment-1411339862" expanded>

Have you tried restarting the IDE? Because my friend had a problem with dependencies not installing until he restarted that. 
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/131#issuecomment-1416074235" expanded>

- What is your development environment? Ie Windows/Mac/Linux? 
- Have you checked your java version?
- Does exporting a jar file and running it produce a GUI?
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/80#issuecomment-1416075890" expanded>

Do close the issue if it is resolved!
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/138#issuecomment-1416674751" expanded>

You may try to push your changes to GitHub, afterwards delete your local folder and clone your own repo again? To be safe, I would backup the local folder first before attempting this to ensure I do not delete any important files.
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/132#issuecomment-1420551792" expanded>

Hello! It appears that your issue has been resolved 😄

Would you be able to close this issue as completed? This will help us keep the repository organized and up-to-date.

If you think that your question is still not answered, feel free to add a comment to clarify what you would like to know.

Thanks!
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/135#issuecomment-1420558638" expanded>

Dear Prof, we were not aware that it was required to be written in 50 words and we wrote it in point form instead. I think including the format of submission can reduce the confusion faced by future teams!

Thanks!
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/147#issuecomment-1421991191" expanded>

Have you tried another set of images? Sometimes the image is actually `.jpeg` but it's labeled as `.png` and java might not render it properly.
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/149#issuecomment-1422537119" expanded>

Similar issues:
https://github.com/nus-cs2103-AY2223S2/forum/issues/68
https://github.com/nus-cs2103-AY2223S2/forum/issues/78

Try and see if those solutions will help with Mac Java issues
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/152#issuecomment-1424107028" expanded>

Would like to ask if it is a good idea to use assert this way

```java
try {
       assert tasks.size() != 0 : "Hey, the list is empty!";
} catch (AssertionError e) {
       ui.showError(e);
}
```

Edit: never mind I read the stack overflow link above and don’t think its a good idea to use assertions. should use exceptions.
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/159#issuecomment-1425470322" expanded>

See: https://github.com/nus-cs2103-AY2223S2/forum/issues/137#issuecomment-1416647054
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/162#issuecomment-1426779831" expanded>

If your GitHub commits are all correct and you have no new changes that you want to keep in your local Git history, a quick way to solve it is to delete your local and clone again from Git. 
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/184#issuecomment-1429199168" expanded>

I believe u need to add `minHeight="-Infinity"` to your label tag in your `DialogBox.fxml`

Something like this. 

https://github.com/francisyzy/ip/blame/a42cfc1b490ed9dacc07ef92d20e1ab4f93c08aa/src/main/resources/view/DialogBox.fxml


</panel>

<panel  header="**25 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/183#issuecomment-1429680553" expanded>

Relevant xkcd
![xkcd](https://imgs.xkcd.com/comics/wisdom_of_the_ancients.png)

but no I don’t face this issue. would be better to write down how u solve it so that incase others face this issue, the solution would be there
</panel>

<panel  header="**26 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/189#issuecomment-1431369858" expanded>

#149 is similar but closed his issue. Not sure what steps he took to solve his issue (if any). You can try attach your duke here as an zip for other Mac users to try it out.
</panel>

<panel  header="**27 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/188#issuecomment-1431381290" expanded>

I face the same issue and I think its a Mac security issue. Downloading a file from a 'reputable' source such as GitHub will let gatekeeper prompt you and open it whereas a file with no source is more suspicious. 
</panel>

<panel  header="**28 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/201#issuecomment-1434229085" expanded>

Looking @ your [build.gradle](https://github.com/zm-l/ip/blob/master/build.gradle), I think there is a mismatch between the JavaFX version. Not sure if that is causing your compile problem. See also: #198

Just saw your update. Can you try compiling in your Ubuntu? It should work if its compiled and ran on the same machine. I think your other machine's Java is too recent. Need to switch back to an older version of SDK. If it is a unix based system, can use this utility to manage your java versions: http://sdkman.io
</panel>

<panel  header="**29 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/201#issuecomment-1434272015" expanded>

I think it might be a mismatch in java version at the system level? Whats the output from `java --version` when running it in terminal?
</panel>

<panel  header="**30 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/204#issuecomment-1434559602" expanded>

Try change 

```
application {
    mainClassName = "Munch"
}
```
To
```

application {
    mainClassName = "Munch.Launcher"
}

```

I had the same issue. It had to do with that chunk in build.gradle
</panel>

<panel  header="**31 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/204#issuecomment-1434626474" expanded>

Do u think it might be due to capitalization? From what I see in your repo, munich is lower caps right?
</panel>

<panel  header="**32 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/206#issuecomment-1434952237" expanded>

Remember to close the issue!
</panel>

<panel  header="**33 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/214#issuecomment-1437425877" expanded>

Similar issue: https://github.com/nus-cs2103-AY2223S2/forum/issues/216

Need to uninstall the wrong java and install the right java.
</panel>

<panel  header="**34 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/204#issuecomment-1437429994" expanded>

I see that you've released your AOT.jar. I've downloaded it and it ran ok on my Mac, don’t have the class not found exception anymore.
</panel>

<panel  header="**35 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/221#issuecomment-1438639750" expanded>

Have you tried other SDKs? Can use http://sdkman.io/ to switch SDKs easily
</panel>

<panel  header="**36 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/223#issuecomment-1444340212" expanded>

I have deleted some branches in my own tP fork, should I recreate it?
</panel>

<panel  header="**37 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/214#issuecomment-1445157459" expanded>

![image](https://user-images.githubusercontent.com/24467184/221369333-c4c0d887-929e-4373-909f-b281e908ba08.png)
tested on a Mac and it seems to launch fine. Let me test on windows and update this comment

works fine on windows too!
![IMAGE 2023-02-26 00:53:16](https://user-images.githubusercontent.com/24467184/221369425-fd93afca-42c4-4106-8060-c2ff8ae010e8.jpg)


</panel>

<panel  header="**38 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/247#issuecomment-1462319637" expanded>

Are we allowed to use tools to generate UML diagrams? If so how should we credit it?
</panel>

<panel  header="**39 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/268#issuecomment-1475339310" expanded>

Nice try ChatGPT

![Screenshot 2023-03-20 at 1 45 15 AM](https://user-images.githubusercontent.com/24467184/226196207-210460f4-e243-4191-8bd6-b34c9271afb5.png)
![image](https://user-images.githubusercontent.com/24467184/226196225-68ded6d4-df99-4c7a-8f01-55f8cc2060dc.png)

</panel>

<panel  header="**40 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/268#issuecomment-1475347933" expanded>

Thanks prof! Will close the issue in a couple of days so that people can see this question!
</panel>

<panel  header="**41 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/301#issuecomment-1491426468" expanded>

I faced this problem just now after installing PlantUML as they messed up my `java --version`.

I used https://sdkman.io to install java quickly using the following java version: `sdk install java 11.0.18.fx-zulu`
</panel>

<panel  header="**42 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/302#issuecomment-1491427496" expanded>

Try the solution here https://github.com/nus-cs2103-AY2223S2/forum/issues/301#issuecomment-1491426468 to see if it helps
</panel>

<panel  header="**43 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/302#issuecomment-1493809309" expanded>

Hey @ajjajjajjajj does the solution work?
</panel>

<panel  header="**44 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/333#issuecomment-1497124631" expanded>

Intended behaviour: would be the patient can be edited when the patient list is filtered (patient does not show up in the current view).

Actual behaviour: will throw a `CommandException` if the patient is not currently in the filtered list. `The patient index provided is invalid`

Intended:
<img width="727" alt="image" src="https://user-images.githubusercontent.com/24467184/230027251-69616fff-a161-4888-8c90-b4d368ba95d7.png">
Actual:
<img width="639" alt="image" src="https://user-images.githubusercontent.com/24467184/230027830-3c14f8ac-56a2-4645-b23f-d1d07b41c896.png">


Screenshot of the relevant UG section before feature freeze:
<img width="1107" alt="image" src="https://user-images.githubusercontent.com/24467184/230026943-fd26efaf-a450-49a3-ad46-c773d3c275c0.png">

</panel>

<panel  header="**45 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/333#issuecomment-1497249382" expanded>

@damithc Thanks for catching the error message error. It should say PATIENT_ID instead of INDEX
</panel>

<panel  header="**46 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/333#issuecomment-1497390516" expanded>

Thanks prof for the clarification!
</panel>

<panel  header="**47 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/375#issuecomment-1508313538" expanded>

I don’t think there is a limitation during part 1 to report on functionality bugs only. I spotted some documentation bug but I just noted it down during part 1 instead of reporting it directly due to time constrains in part 1.

![image](https://user-images.githubusercontent.com/24467184/232023157-3a4bc5ca-e1b4-4a67-9d54-a70f486b5c11.png)

But I agree with you, swapping part 1 and 2 will allow the student to spend more time understanding the product via the documentation before trying out the app. However, it is hard for the teaching team to restrict you from testing the `jar` file in documentation bug phase as you can find their release on Github directly if they don't bundle it with the documents.

</panel>

</panel>


<panel type="info" header="### 4. AI B..I BO `@BoAi01` (46 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Missing command: functionality bug, feature flaw, or documentation bug?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/318" expanded>

In our UG, we claimed that we have `exit` command. However, in PE, the `exit` command was not working. Do we consider this as a functionality bug (command not working), feature flaw (not having an `exit` command), or documentation bug (`exit` command should not appear on UG)?

And are we allowed to make the corresponding change in v1.4?
</panel>

<panel  header="**2. :fas-info-circle: coding style: lambda expression**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/197" expanded>

I encountered this error in checkStyle: 
<img width="955" alt="Screenshot 2023-02-17 at 9 23 50 AM" src="https://user-images.githubusercontent.com/53465243/219525633-c4d739ca-bff1-444c-ba47-e2685b507a9d.png">

For the convenience of reproduction, here is the code segment:
```
@Test
public void testParseCommand() {
    assertThrows(NotRecognizedCommandDukeException.class, (
            ) -&gt; Parser.parseCommand("test", false));
    assertThrows(NotRecognizedCommandDukeException.class,
            () -&gt; Parser.parseCommand("unknown", false));
    assertDoesNotThrow(() -&gt; Parser.parseCommand("todo test", false));
    assertDoesNotThrow(() -&gt; Parser.parseCommand("deadline test /by 2022-10-22", false));
}
```

Specifically, the error is that the `(` in the lambda expression should stay on the first line, but why does this improve readability? It seems nicer to put the complete lambda expression on the new line instead.

PS. I am using the check style file from the AB-3 address book, which is supposed to the standard. 
</panel>

<panel  header="**3. :fas-info-circle: 💡 Tip on dealing with inconsistency between GitHub file preview and GitHub Page**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/177" expanded>

GitHub README file preview and GitHub Page use different Markdown processors, i.e., kramdown and GFM respectively, thus the rendering may not be the same. Take the following Markdown code for a table as an example:
```
| Action              |                        Format                        |                                        Examples |
|:--------------------|:----------------------------------------------------:|------------------------------------------------:|
| List tasks          |                         list                         |                                            list |
| Add a todo task     |                   todo [task name]                   |                                       todo task |
| Add a deadline task |       deadline [task name] /by [deadline date]       |                     deadline task /by 2023-2-14 |
| Add an event        | event [event name] /from [start date] /to [end date] | event recess week /from 2023-2-20 /to 2023-2-26 |
| Find a task         |                 find [keyword 1] ...                 |                                find recess 2022 |
| delete a task       |                    delete [index]                    |                                       delete 10 |
```
In README preview, it looks like following
| Action              |                        Format                        |                                        Examples |
|:--------------------|:----------------------------------------------------:|------------------------------------------------:|
| List tasks          |                         list                         |                                            list |
| Add a todo task     |                   todo [task name]                   |                                       todo task |
| Add a deadline task |       deadline [task name] /by [deadline date]       |                     deadline task /by 2023-2-14 |
| Add an event        | event [event name] /from [start date] /to [end date] | event recess week /from 2023-2-20 /to 2023-2-26 |
| Find a task         |                 find [keyword 1] ...                 |                                find recess 2022 |
| delete a task       |                    delete [index]                    |                                       delete 10 |

However, on GitHub Page, it renders like below
<img width="999" alt="Screenshot 2023-02-13 at 4 54 14 PM" src="https://user-images.githubusercontent.com/53465243/218413278-2008dc5f-dd91-471d-9a08-db186765732e.png">

The solution is to change the Markdown processor for GitHub Page. Do these steps:
1. create a file `_config.yml` in the `docs` folder
2. write this single line and push it to the remote repo: `markdown: GFM`
3. ~~Go to `settings` again, unpublish the page, and wait for it to automatically publishes itself~~ Wait a few minutes for the website to update itself (updated 14 Feb, thanks to @eugenetangkj )
4. Access the GitHub Page and check it renders properly

Some further reading, if you are interested:
1. An example of a complete `_config.yml` file (not need in our case): [here](https://github.com/daattali/beautiful-jekyll/blob/master/_config.yml)
2. Official guide on how to change the Markdown processor: [here](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/setting-a-markdown-processor-for-your-github-pages-site-using-jekyll)

Hope this helps those who wish to use tables in their user guide. : )


</panel>

<panel  header="**4. :fas-info-circle: [ip] Number of JUnit test cases needed**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/168" expanded>

If I recall correctly, we only need to test public methods. But among them, some are not easy to be tested, e.g., due to dependencies on other classes or other methods, which makes Junit testing not straightforward. Is there a hard requirement on the proportion of the code that must be covered by JUnit test cases? 

</panel>

<panel  header="**5. :fas-info-circle: Exit GUI gracefully**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/115" expanded>

My current way of exiting from the GUI is to add the following lines at the start of the `handleUserInput` method 
```
private void handleUserInput() {
    if (duke.isExited()) {
        Platform.exit();
    }
    // ... things to do if the program has not exited
}
```
The effect is, after entering "bye", Duke will print out the final message, but the GUI only closes when the user enters the **next** command. However, ideally, we would like the GUI window to close **some time after** it reponds to our "bye" input. 

I tried using`TimeUnit.MINUTES.sleep(1);` and `Platform.exit();` at the end of `handleUserInput`, but it turns out that, the GUI will exit directly without printing out the last message, possibly because we cannot end the program inside `handleUserInput` method. Then what is the solution?
</panel>

<panel  header="**6. :fas-info-circle: Level 7: Record commands vs record task list state**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/41" expanded>

In `Level-7`, we are asked to load the data when `Duke` starts up, then the question is what representation we should use to save the task list. If we were to save the task list in the example given (attached below), we would need to implement another parser to deal with the text data, which is a bit redundant. 

```
T | 1 | read book
D | 0 | return book | June 6th
E | 0 | project meeting | Aug 6th 2-4pm
T | 1 | join sports club
```

Thus, what about we directly save all history commands, and re-run all commands when starting up? This way we can use the same string parser for processing user input and the data file.

Some preliminary thought: In principle, the file should save the state of the task list, instead of the procedure of creating the task list. However, in practice, given that re-running all commands is efficient, there don't seem to be a lot of drawbacks to creating the task list from scratch. 
</panel>

<panel  header="**7. :fas-info-circle: Errors while pushing a branch to a remote repo**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/21" expanded>

I am following the guide of pushing a branch to a remote repo [here](https://nus-cs2103-ay2223s2.github.io/website/schedule/week3/topics.html#W3-1), attached below. 

<img width="710" alt="Screenshot 2023-01-19 at 9 08 59 AM" src="https://user-images.githubusercontent.com/53465243/213331962-63755c37-4e10-4220-ac4d-59c4a10f5fc0.png">

Below is my `Sourcetree` configuration (M1 Mac) for pushing
<img width="1057" alt="Screenshot 2023-01-19 at 9 10 34 AM" src="https://user-images.githubusercontent.com/53465243/213332118-57825625-882c-4c61-8f32-d43699566a3f.png">

After clicking `OK`, it shows the following error
<img width="1054" alt="Screenshot 2023-01-19 at 9 10 57 AM" src="https://user-images.githubusercontent.com/53465243/213332159-e795b11d-996f-47e5-890a-8a2e0648bd1f.png">

What does the error mean? 
</panel>

<panel  header="**8. :fas-info-circle: For IP, do we have to implement different levels in sequence?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/8" expanded>

For example, for this week's IP, can we implement the level-5 and the level-6 first, and leave A-TextUiTesting to the last?

I understand that it might be preferable if we could implement different levels in sequence, but I am wondering if the progress tracker can capture not-in-order commits. 
</panel>

<panel  header="**9. :fas-info-circle: When will participation dashboard start updating?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/6" expanded>

[Participation dashboard](https://nus-cs2103-ay2223s2.github.io/dashboards/contents/participation.html) 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/2#issuecomment-1381437220" expanded>

I think so. The "is-a" relationship in the interface case is more loosely defined than that for class inheritance. But in both cases, inheritance implies that the class has functionalities that the parent class/interface prescribes.  
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/1#issuecomment-1381448173" expanded>

I am running on M1 macOS 13.0.1 and it looks fine as well. 
```
openjdk version "11.0.17" 2022-10-18 LTS
OpenJDK Runtime Environment Zulu11.60+19-CA (build 11.0.17+8-LTS)
OpenJDK 64-Bit Server VM Zulu11.60+19-CA (build 11.0.17+8-LTS, mixed mode)
```

However, mine is `Zulu11.60,` which is slightly different from the `Zulu11.50` specified in our course website (attached below)
```
openjdk 11.0.__ ____-__-__ LTS
OpenJDK Runtime Environment Zulu11.50+19-CA (build 11.0.__+_-LTS)
OpenJDK 64-Bit Server VM Zulu11.__+__-CA (build 11.0.__+_-LTS, mixed mode)
```

This should be a problem, I suppose? 
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/5#issuecomment-1383037336" expanded>

Agree, it is a hidden file. See this question for more details: 
```
https://stackoverflow.com/questions/11197249/show-system-files-show-git-ignore-in-osx
```
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/6#issuecomment-1383104140" expanded>

Issue resolved. Thank you!
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/8#issuecomment-1384817907" expanded>

Thank you for the prompt reply!
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/12#issuecomment-1384913724" expanded>

> > Hello prof thank you for the response, but what if the commit does not satidfy the earlier requirements? For example, "blah" would be considered as a valid input as we should echo it according to Level 1; but in Level 5, it is considered as an error.
> 
> @yitong241 That's fine. When a later requirement overrides an earlier requirement, only the later requirement needs to be satisfied.

Great. I was wondering about this too. 
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/11#issuecomment-1384935740" expanded>

> Good question @Tempura-Person From a project requirements point of view, the answer for this case is "do what makes sense from the user point of view". What behavior makes sense from the user's POV, in this case? That's a good question for a discussion here.

For this question, I think the program should not stop when a user-side error occurs (e.g., wrong commands). Instead, the program can let the user try again. 

> Separately, can an Exception be used even when the expected behavior is printing an error message? That's another good question for a discussion.

I am less sure about this one. To achieve the function of printing out an error message, we certainly do not have to use an Exception. But it seems that using an exception better separates normal function code from error-handling code. So it would be a better abstraction design. 
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/15#issuecomment-1385292079" expanded>

I agree with the above example. 

To add on, `input.txt` should contain exactly the strings that go into `System.in` (e.g., input to the `Scanner` read from keyboard), and `EXPECTED.txt` should contain exactly the string that should go out from `System.out` (i.e., printed values). These are standard I/O streams. See [here](https://www.javatpoint.com/linux-input-output-redirection) for more information about I/O steams and redirection. 
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/21#issuecomment-1396417731" expanded>

Thank you for the suggestion!

I figured out that the error was because the remote repo is not my fork but the original repo. Repeating these operations on my fork works fine.  
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/24#issuecomment-1396419244" expanded>

I guess not, since it is indicated as "if applicable" in the instruction.

I think `enums` can be used to include all possible commands (e.g., `list`, `mark`), though the benefit is marginal for now. 
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/25#issuecomment-1396476853" expanded>

In `runtest.sh`, the command`diff` is used to compare `ACTUAL.TXT` and `EXPECTED-UNIX.TXT` (line 30). It only returns true if the two text files are exactly the same (i.e., character by character), I think.

More info about `diff` can be found [here](https://man7.org/linux/man-pages/man1/diff.1.html)

Hope this helps!
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/48#issuecomment-1404597286" expanded>

Need to create a directory called `config`, copy over the config files, and modify `build.gradle` accordingly. 
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/84#issuecomment-1407523318" expanded>

Agree with @Junyi00. Should make sure the class files begin with `package &gt;package name>`, and when the class is used somewhere, `import &gt;package>.&gt;class name>` is present in that file.  
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/84#issuecomment-1407540963" expanded>

The error says package `duke.exception` does not exit. Probably you need to check whether there is indeed such a package. Feel free to post the first few lines of your file for us to take a look. 
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/108#issuecomment-1410215006" expanded>

It works well on my side. Thanks! 
</panel>

<panel  header="**25 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/115#issuecomment-1411368961" expanded>

@hingen Great, thanks for pointing out!
</panel>

<panel  header="**26 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/41#issuecomment-1413140427" expanded>

Thank you all for the input! I think there are different approaches with pros and cons. It is our design choice which one to use. 

I will close the issue for now. 
</panel>

<panel  header="**27 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/136#issuecomment-1416615548" expanded>

I can see your `ip` repo has a branch named `branch-A-assertions`. Did you push to this branch instead of the `master` branch? 
</panel>

<panel  header="**28 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/71#issuecomment-1416621766" expanded>

For me, I save the file only at the end of the program. We can probably assume that the user knows the record will be saved only if the program exits gracefully. In other words, a `bye` command here resembles `:wq` in vim. : )

This also gives the user a choice of exiting with saving the history. 
</panel>

<panel  header="**29 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/143#issuecomment-1418469390" expanded>

Here is one side comment: It may not be good to use braces in switch structure, as switch is normally intended for switching between short statements. If there are many lines of code in each case, it might be better to use if-else instead, and in this case we are free to declare new variables. 
</panel>

<panel  header="**30 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/114#issuecomment-1424938351" expanded>

I use varargs for my `find` command. Specifically, it can take an arbitrary number of arguments, and it searches for potential matches in two cases:
1. Strong match: task string contains **all** input strings
2. Weak match: task string contains **at least one** input string

I implemented this for my `BCD-Extension` (week 5 task), i.e., `C-BetterSearch`. 
</panel>

<panel  header="**31 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/156#issuecomment-1424945373" expanded>

Just share a tip on avoiding if-else or switch statements, if that is desirable:
The following can directly instantiate a command object without branching
```
Class<?> c = Class.forName("command." + stringToCommandClassMap.get(command.split(" ")[0]));
Constructor<?> cons = c.getConstructor(String.class, boolean.class);
object = cons.newInstance(command, !suppressPrint);
``` 
where `stringToCommandClassMap` is a Hashmap that stores the pairs <user command keyword, command class name>, `cons.newInstance` calls the constructor, and `object` is a command class object which has an `execute` method. 
</panel>

<panel  header="**32 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/154#issuecomment-1424948806" expanded>

I am not sure if Java version would lead to such an issue, but I have been using the Azul build of OpenJDK 11 version as suggested [here](https://nus-cs2103-ay2223s2.github.io/website/admin/programmingLanguages.html#programming-language) and I have not encountered any version-related issues so far. 

P.S. I am using an M1 mac. 
</panel>

<panel  header="**33 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/152#issuecomment-1424952165" expanded>

@damithc @hingen Thank you for the great suggestions! The clarification is very clear. 
</panel>

<panel  header="**34 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1426955161" expanded>

A simple GUI modified from the template with error message highlight

<img src="https://user-images.githubusercontent.com/53465243/218296747-1eb5661e-f990-4aae-955a-758f0ad34787.jpg" width=50% height=50%>
</panel>

<panel  header="**35 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/168#issuecomment-1426959080" expanded>

@damithc  Thank you for the prompt reply!

Does this requirement also apply to `A-MoreTesting`?
</panel>

<panel  header="**36 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/168#issuecomment-1426959798" expanded>

Noted. I think my testing has covered more than half of the public methods. Should be good then. 

Thank you!
</panel>

<panel  header="**37 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/173#issuecomment-1427198980" expanded>

In the Gradle error message, there are options to show full stack traces, which might be helpful. Just click the options and it will re-run the program. 
</panel>

<panel  header="**38 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/177#issuecomment-1429067327" expanded>

> GitHub pages automatically refreshed itself after pushing to the remote repo

I didn't notice this. Thanks for pointing out!
</panel>

<panel  header="**39 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/177#issuecomment-1429073745" expanded>

@damithc I have updated the original post. Thanks for the suggestion!
</panel>

<panel  header="**40 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/197#issuecomment-1441947905" expanded>

Noted with thanks!
</panel>

<panel  header="**41 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/177#issuecomment-1455114689" expanded>

Closing this issue, since IP has been submitted. 
</panel>

<panel  header="**42 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/259#issuecomment-1469271309" expanded>

For our team, we refactored the code base to abstract out common things. This was majorly done by @wxxedu. 
Having different command classes and storage classes seems unavoidable, but parsers and other utils can be abstracted out. Doing refactoring significantly help later modifications in our case. 
</panel>

<panel  header="**43 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/269#issuecomment-1482798300" expanded>

> they lack the structural knowledge of the codebase

I think this is spot on. LLMs (Large-Langauge Models) do not have the context about the high-level system architecture, thus it is only capable of producing short snippets (relatively compared to SE projects). Manual efforts are needed to adapt LLMs' outputs for the purpose of specific projects at hand. It's unlikely that we can get LLMs to generate code at scale. 

> I use ChatGPT as a "search engine" that helps me check APIs 

I use it in exactly the same way. It sometimes works better than StackOverflow, as it only displays the most likely implementation of a certain functionality (in contrast, Google has many answers but many of them are just noise). I turn to GPT first if I think the function I want to implement is common and routine. 
</panel>

<panel  header="**44 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/197#issuecomment-1495224082" expanded>

One update on the coding style for lambda expression:
Our teammates have decided to move from the original style specified by the default style file
```
assertThrows(
                CommandException.class, (
                    ) -&gt; deleteCommand.execute(model)
        );
```
to the following
```
assertThrows(
                CommandException.class,
                () -&gt; deleteCommand.execute(model)
        );
```
Alternatively, the following is also acceptable
```
assertThrows(
                CommandException.class, () ->
                        deleteCommand.execute(model)
        );
```

We feel that it's more aesthetic to let the left and right paratheses stay on the same line. : )


</panel>

<panel  header="**45 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/197#issuecomment-1495224157" expanded>

To achieve this, we just need one simple modification on `checkstyle.xml`:
Change the following
```
<module name="SeparatorWrap">
      &gt;!-- Checks that the ",", "]", "[", "...", ";", "(" is at the previous end of line in a line wrap. -->
      <property name="tokens" value="COMMA, RBRACK, ARRAY_DECLARATOR, ELLIPSIS, SEMI, LPAREN"/>
      <property name="option" value="eol"/>
    </module>
```
to this
```
<module name="SeparatorWrap">
      &gt;!-- Checks that the ",", "]", "[", "...", ";" is at the previous end of line in a line wrap. -->
      <property name="tokens" value="COMMA, RBRACK, ARRAY_DECLARATOR, ELLIPSIS, SEMI"/>
      <property name="option" value="eol"/>
    </module>
```
which is at around the 340th line in the file. 

</panel>

<panel  header="**46 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/318#issuecomment-1495413959" expanded>

It's UG bug then. Noted with thanks!
</panel>

</panel>


<panel type="info" header="### 5. TAN ..HAUN `@EvitanRelta` (35 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Canvas demo video submission has no name**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/369" expanded>

The video file that i uploaded was named `[CS2103T-W12-2][TeachMeSenpai].mp4`. But after uploading, it's name was stripped from the Canvas assignment page.

There doesn't seem to be any way to add a name on the `tP Demo Video` Canvas assignment.

Is that ok?

![image](https://user-images.githubusercontent.com/35413456/231221343-d55ea327-7fd5-4d8f-baf5-8b57c992f7ad.png)

This is what it looks like when i click `Submission details`:

![image](https://user-images.githubusercontent.com/35413456/231222233-86c7c46b-b84d-4a98-a448-8c6bfda94e74.png)


</panel>

<panel  header="**2. :fas-info-circle: What to do if we accidentally fixed a flaw?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/336" expanded>

If we've already accidentally fixed a flaw, what do we do?

Do we remove it?
</panel>

<panel  header="**3. :fas-info-circle: Will we be penalised on PE for feature flaws?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/325" expanded>

or will we be only penalised for bugs?
</panel>

<panel  header="**4. :fas-info-circle: Making minor Ui change to fix a bug**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/317" expanded>

We have a command `remark INDEX` which opens a popup for user to edit the "remark" field of the `Person`.  
However, while the popup is open, the user can still type commands, which can cause unexpected behaviour, as shown below:

![able to enter command while popup](https://user-images.githubusercontent.com/35413456/229692673-a2a9b97e-5722-438d-bca9-8c7156e63518.gif)

While this is clearly a **&gt;ins>bug&gt;/ins>** _(not a flaw)_, the fix we're planning is to disable the command line inputbox while the popup is open _(which is a Ui change)_. 

Is it allowed?
</panel>

<panel  header="**5. :fas-info-circle: Question on code reuse policy**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/288" expanded>

Snippet from W12 ["Policy on reuse"](https://nus-cs2103-ay2223s2.github.io/website/schedule/week12/admin.html#policy-on-reuse):

> # Policy on reuse
> ...
> - You are allowed to reuse work from external sources, subject to following conditions:
>   - In case of reusing more than a short code snippet (e.g., reusing an entire library or an entire feature), the work comes from a source of 'good standing' (such as an established open source project). <ins>**_This means you cannot reuse a significant portion of codebase written by a friend or a past student._**</ins> But you may reuse/adapt small code snippets from any source such as stackoverflow.

<br>

With regards to the underlined part, I have the following questions:

1. How much is considered "significant" _(and thus not allowed to be reused)_? 
   Is copying a single `.java` file with ~250 lines "significant"?

2. If it is significant, what if a **SIGNIFICANT** part of the copied code is later then changed/refactored/bug-fixing to suit our needs?  
   In this case:
   1. are we then allowed to reuse said code?
   2. how do we mark code that's written by the source authors, and code that's modified/added by us?
   3. are we then credited for the modifications that we did to the code? Or will we not be credit AT ALL for the ENTIRE code _(modified or not)_?

4. _(unrelated to the 2 qns above)_ What if we copied code, commit it, then made major changes to it?  
   _(such that the copied code is in the Git history)_
  
   Do we credit the source as if we [read the code to understand the approach and implemented it ourselves][adapted]:
   ```java
   //Solution below adapted from https://stackoverflow.com/a/16252290
   {Your implementation of the reused solution here ...}
   ```
   
   Or credit it the same way as [copy-pasted a non-trivial code block with minor modifications][copy w minor]:
   ```java
   //@@author {yourGithubUsername}-reused
   ```

5. Will we be credited reused code that we [read the code to understand the approach and implemented it ourselves][adapted]?  
   _(ie. code that we've been "inspired by" and that's been changed significantly from the source code)_
   
   Because I'm afraid that if we spend significant effort improving/fixing/adapting, we'll end up with basically no code contribution if we get no coding credit for modifying reused code _(although I guess we get reuse credit? not sure how that will affect our grade)_

[adapted]: https://nus-cs2103-ay2223s2.github.io/website/schedule/week12/admin.html#giving-credit-for-reused-work:~:text=If%20you%20read%20the%20code%20to%20understand%20the%20approach%20and%20implemented%20it%20yourself%2C%20mention%20it%20as%20a%20comment
[copy w minor]: https://nus-cs2103-ay2223s2.github.io/website/schedule/week12/admin.html#giving-credit-for-reused-work:~:text=If%20you%20copy%2Dpasted%20a%20non%2Dtrivial%20code%20block%20(possibly%20with%20minor%20modifications%20renaming%2C%20layout%20changes%2C%20changes%20to%20comments%2C%20etc.)%2C%20also%20mark%20the%20code%20block%20as%20reused%20code
</panel>

<panel  header="**6. :fas-info-circle: Red `DG Draft` task on tp progress dashboard despite updating DG b4 lecture**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/280" expanded>

My `DG Draft` task in my tp progress dashboard is red:

![image](https://user-images.githubusercontent.com/35413456/227763386-a18a6ac4-a31c-4855-b3fa-413dfc7af6af.png)

Despite add lines in our DG at commit https://github.com/AY2223S2-CS2103T-W12-2/tp/commit/882389b3788fb8d42755a2b1de2255aae9392f9e, which was done at `Mar 24, 2023, 1:39 PM`, before the 2pm Friday lecture.

Since there's no specified deadline the DG updating task *(as shown below)*, I assume the harddeadline was Mar 24, 2pm right?

![image](https://user-images.githubusercontent.com/35413456/227763533-19a57cd5-1e48-4634-8c78-e913fdc3ace4.png)

</panel>

<panel  header="**7. :fas-info-circle: Am I the only one feeling overwhelmed by the tps codebase?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/259" expanded>

I'm just trying to morph the person tagging feature into an optional "Education Level" tag, where each person has can have 1 specified education level *(eg. `P6` or `Sec 2`)*

But something as simple as that requires changing not only the `Person` class, but:
- 2 command classes (ie. `AddCommand` & `EditCommand`)
- 2 command-parser classes *(ie. `AddCommandParser` & `EditCommandParser`)*,
- Storage classes like `JavaAdaptedPerson`, `JavaAdaptedTag`
- utils classes like `CliSyntax`, `ParserUtils`

Not to mention removing any references to the old tagging feature in all testing classes and their utils:
- `SampleDataUtil`
- `LogicManagerTest`
- `CommandTestUtil`
- `EditCommandTest`
- etc.

And not to mention the shear amount of UML diagrams we'll need to change in the future.

How are we suppose to do anything at this rate?  
I can't take this anymore
</panel>

<panel  header="**8. :fas-info-circle: Unable to load images, `getResourceAsStream` returning null**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/171" expanded>

I'm trying to implement the [JavaFX tutorial part 3] but after implementing the images, I keep getting this error when running:

[JavaFX tutorial part 3]: https://se-education.org/guides/tutorials/javaFxPart3.html


```bash
$  cd c:\\Users\\shaun\\Desktop\\repositories\\ip ; /usr/bin/env C:\\Program\ Files\\Java\\jdk-11.0.14\\bin\\java.exe @C:\\Users\\shaun\\AppData\\Local\\Temp\\cp_ecd2bo7vr45zarn5s3muqg0w1.argfile duke.Launcher
Exception in Application constructor
Exception in thread "main" java.lang.RuntimeException: Unable to construct Application instance: class duke.Duke
        at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:890)
        at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195)
        at java.base/java.lang.Thread.run(Thread.java:834)
Caused by: java.lang.reflect.InvocationTargetException
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance0(Native Method)
        at java.base/jdk.internal.reflect.NativeConstructorAccessorImpl.newInstance(NativeConstructorAccessorImpl.java:62)
        at java.base/jdk.internal.reflect.DelegatingConstructorAccessorImpl.newInstance(DelegatingConstructorAccessorImpl.java:45)
        at java.base/java.lang.reflect.Constructor.newInstance(Constructor.java:490)
        at com.sun.javafx.application.LauncherImpl.lambda$launchApplication1$8(LauncherImpl.java:802)
        at com.sun.javafx.application.PlatformImpl.lambda$runAndWait$12(PlatformImpl.java:455)
        at com.sun.javafx.application.PlatformImpl.lambda$runLater$10(PlatformImpl.java:428)
        at java.base/java.security.AccessController.doPrivileged(Native Method)
        at com.sun.javafx.application.PlatformImpl.lambda$runLater$11(PlatformImpl.java:427)
        at com.sun.glass.ui.InvokeLaterDispatcher$Future.run(InvokeLaterDispatcher.java:96)
        at com.sun.glass.ui.win.WinApplication._runLoop(Native Method)
        at com.sun.glass.ui.win.WinApplication.lambda$runLoop$3(WinApplication.java:174)
        ... 1 more
Caused by: java.lang.NullPointerException: Input stream must not be null
        at javafx.scene.image.Image.validateInputStream(Image.java:1117)
        at javafx.scene.image.Image.<init>(Image.java:701)
        at duke.Duke.<init>(Duke.java:33)
        ... 13 more
```

<br>

The offending line (ie. `Duke.java:33`) is this:

```java
31: ...
32: public class Duke extends Application {
33:     private Image user = new Image(this.getClass().getResourceAsStream("/images/DaUser.png"));
34:     private Image duke = new Image(this.getClass().getResourceAsStream("/images/DaDuke.png"));
35:     ...
```

<br>

This is my folder structure, where the images is in `src/resources/images` as per the JavaFX tutorial:

![image](https://user-images.githubusercontent.com/35413456/218317102-b136410c-ebd6-4081-b434-7feae0143752.png)

<br>

_PS: don't mind the red highlighted files, its just the checkstyle acting up_
</panel>

<panel  header="**9. :fas-info-circle: Breaking up long code lines**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/82" expanded>

How should the below code be formatted?  
Specifically, how much indent, whether the first element should be on the same line, and where should the closing bracket/brace be.

```java
String[] values = new String[]{ "D", .isDone ? "1" : "0", this.description.toString(), this.endTime.toString() };
```

Based on the [coding standard], i assume it should be:
- 8-space indents
- 1st element (ie. `"D"`) on the same line
- closing bracket/brace at the back of the last line

```java
String[] values = new String[]{ "D", 
        this.isDone ? "1" : "0", 
        this.description.toString(), 
        this.endTime.toString() };
```

But how about egyptian-styled brackets/braces:

```java
String[] values = new String[]{
        "D", 
        this.isDone ? "1" : "0", 
        this.description.toString(), 
        this.endTime.toString()
};
```

[coding standard]: https://se-education.org/guides/conventions/java/basic.html

---

Additionally, how bout the below code? Which one is acceptable?

```java
assertEquals(
        TaskDeadlineTest.getTestTask(),
        TaskDeadlineTest.getTestTask());
```

```java
assertEquals(TaskDeadlineTest.getTestTask(),
        TaskDeadlineTest.getTestTask());
```
</panel>

<panel  header="**10. :fas-info-circle: Using code linters & formatters**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/61" expanded>

To aid in following the code standard, are we allowed to use: 
- Linters, which highlights any coding-standard violations  
  _(eg. Sonarlint)_ 
- and/or formatters, which auto-formats and fixes coding-standard violations  
  _(eg. Eclipse's java formatter)_

The main concern is since formatters auto-corrects any violations, we might not learn the coding-standard.  
Which isn't a problem for projects _(in fact I think formatters are a great way to enforce coding-standards)_  
BUT, I'm afraid that we might be tested on those coding-standards in quizes/tests/exams/practicals.
</panel>

<panel  header="**11. :fas-info-circle: Accidentally starting another Quiz attempt**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/30" expanded>

I've finished Quiz 2 already, but accidentally started another attempt (which i have not filled in nor submitted)

Can i just leave it unsubmitted? Or will that attempt be autosubmitted on the deadline, and give me 0 marks since its not filled in, and its the latest attempt?
</panel>

<panel  header="**12. :fas-info-circle: Use Gits lightweight tag or annotated tag?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/27" expanded>

The [week 2 project page] didn't explicitly specify whether to use lightweight or annotated tags.

But since it didn't ask for the `-a` flag when doing `git tag` (eg. `git tag -a Level-1`),  
I'm assuming its lightweight?

The problem is if the tags were annotated, they could easily be pushed using `git push --follow-tags`.  
But this doesnt work for lightweights.

So I was wondering if we could use annotated tags instead of lightweights?  
And more importantly: &gt;ins>**Will it mess up the grader script?**&gt;/ins>

[week 2 project page]: https://nus-cs2103-ay2223s2.github.io/website/schedule/week2/project.html#:~:text=git%20tag%20the%20commit%20with%20the%20exact%20increment%20ID%20e.g.%2C%20Level%2D2%2C%20A%2DTextUiTesting

> Edit: I just found out that u could push all tags via: `git push --tags`.  
> But i still would like to know if annotated ones are allowed just in case.
</panel>

<panel  header="**13. :fas-info-circle: Should we add the `A-Collections` tag together with/after `Level 6` tag?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/26" expanded>

`A-Collections` extension from `Level-6` asks us to use collections for our tasks. But I've used `ArrayList` since `Level-2`.  
So should I tag the commit at `Level-2`?  
Or should I tag it at `Level-6` to follow the given order, as per @damithc in #8:
> @BoAi01 Yes, try to follow the given order as much as possible. No, we don't penalize if you don't follow the order.


</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/23#issuecomment-1396527884" expanded>

I also used switch statements like u [@rmj1405](https://github.com/rmj1405), and also used hashmaps to separate the parameters from the `list`, `mark`, `delete` keywords like [@daitenshionyan](https://github.com/daitenshionyan).

I took it a step further, and off-loaded all these parsing of the commands to a class itself _(ie. `Command` class in the code snippet below)_, so that the `Duke.main` method is as clean as possible. Also, by moving the command-parsing-logic elsewhere, this adhere to the [SLAP recommendation](https://nus-cs2103-ay2223s2.github.io/website/se-book-adapted/chapters/codeQuality.html#slap-hard).

IMO, [@rmj1405](https://github.com/rmj1405) if u managed to combine the 2 switch-statements u have, into a single switch-statement, and abstract each command's out like what u did with `taskManager.checkTask`, `taskManager.deleteTask`, etc., it'll already be pretty clean.

```java
public static void main(String[] args) {
    // ... misc code

    Scanner scanner = new Scanner(System.in);
    TaskList tasks = new TaskList();
    
    while (true) {
        String input = scanner.nextLine();
        Command command = new Command(input);
    
        try {
            switch (command.keyword) {
                case "event":
                    Duke.addEvent(command, tasks);
                    break;
                case "mark":
                    Duke.mark(command, tasks);
                    break;
                case "list":
                    Duke.list(command, tasks);
                    break;
                
                // ... other keywords/commands
                
                default:
                    throw new DukeInvalidCommandException();
            }
        } catch (DukeException e) {
            // Handle exceptions.
        }
    }
    // ... misc code
}

private static void addEvent(Command command, TaskList tasks) throws DukeInvalidArgumentException {
    // ... error handling

    Task task = new TaskEvent(
        description, 
        command.argumentHashMapThing.get("from"), 
        command.argumentHashMapThing.get("to")
    );
    tasks.add(task);

    // ... misc code
}
```


</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/20#issuecomment-1396557797" expanded>

With respect to @rexcyrio's `if-else` code above, I abstracted the code for each command to its own method  
so that the `Duke.main` method focuses on directing which command to which method:

_(I also posted a `switch` version of this code at: [Issue #23](https://github.com/nus-cs2103-AY2223S2/forum/issues/23#issuecomment-1396527884) if u wanna check that out)_

```java
public static void main(String[] args) {
    // ... misc code
    
    while (true) {
        String input = scanner.nextLine();
    
        try {
            if (command.equals("list")) {
                Duke.list(yourArguments);
            } else if (command.equals("bye")) {
                Duke.quit(yourArguments);
            } else if (command.equals("todo")) {
                Duke.addTodo(yourArguments);
            } else if (....) {
                // ....
            } else {
                // Unrecognised command.
                throw new DukeInvalidCommandException();
            }
        } catch (DukeException e) {
            // Handle exceptions.
        }
    }
    
    // ... misc code
}
```

<br>

And in each command's method, they check and throw their own exceptions, which are caught in `Duke.main` code above.

```java
private static void mark(YourArgument yourArguments) throws DukeInvalidArgumentException {
        if (/* Command has no index given. */) {
            throw new DukeInvalidArgumentException("No task index given.");
        }
        
        // ... misc code
    }
}
```

<br>

As for alternatives to if-else checking for errors, I used a mix of if-else and `Optional` to validate the data like so:

```java
private static void mark(YourArgument yourArguments) throws DukeInvalidArgumentException {
        if (/* Command has no index given. */) {
            throw new DukeInvalidArgumentException("No task index given.");
        }
        
        // ... misc code
        
        int taskIndex = Optional.of(command.body)
            .filter(isNumeric)
            .map(body -&gt; Integer.parseInt(body) - 1)
            .filter(i -&gt; i >= 0)
            .orElseThrow(() -&gt; new DukeInvalidArgumentException(
                "Invalid task index. Index needs to be a positive integer."
            ));
        Task task = Optional.of(taskIndex)
            .filter(...)
            ...
        
        task.markAsDone();
        
        // ... misc code
    }
}
```

<br>

IMO, `Optional` is more ~~concise~~ <ins>cleaner</ins> for checking data **WHILE** getting the data:

```java
// Using Optional.
int taskIndex = Optional.of(command.body)
    .filter(isNumeric)
    .map(body -&gt; Integer.parseInt(body) - 1)
    .filter(i -&gt; i >= 0)
    .orElseThrow(() -&gt; new DukeInvalidArgumentException("...");


// Equivalent, but with if-else.
if (!isNumeric(command.body)) {
    throw new DukeInvalidArgumentException("...");
}
int taskIndex = Integer.parseInt(command.body) - 1;
if (taskIndex < 0) {
    throw new DukeInvalidArgumentException("...");
}
```
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/26#issuecomment-1396886058" expanded>

Ok thanks!
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/29#issuecomment-1396925385" expanded>

Try:
1. remove the last empty line (line 3 in ur pic) from input.txt
2. try manually entering nothing (and press enter) to see if it breaks

my guess is that ur code has no handling for empty commands. and that last empty line is an empty command that breaks the code.
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/27#issuecomment-1396934634" expanded>

ok thanks!
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/29#issuecomment-1396943584" expanded>

whats the line that causes this error?
as well as the surrounding lines of code for context.
im assuming its a `scanner.next()`?
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/63#issuecomment-1406211792" expanded>

I also had same problem. Apparently, it was cause my PC's `JAVA_HOME` enviromental variable wasn't set.

>## Edit:
> Looking at the `gradlew.bat` script, it seems that if `JAVA_HOME` isn't set, it will fall back on whatever version ur commandline java is set to. U can check what version that is be entering `java --version` in ur commandline.
>
> Mines apparently set to JDK17, which is probably what's causing the problems:
>
> ![image](https://user-images.githubusercontent.com/35413456/215050004-7260ecce-e6b7-4d7a-8b01-593597ff6d17.png)


@WilliamHaiweiGu, try entering `echo %JAVA_HOME%` into ur command-line. What does it output?

It should output a JDK11 path like: `C:\Program Files\Java\jdk-11.0.14`

If it doesn't, then try setting it with these steps: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_ANALYSIS,_EDITION_FOR_OLAP/c4341f1ce3324d9d9309163567effc1b/eca795926fdb101497906a7cb0e91070.html?version=4.2.7
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/84#issuecomment-1407580189" expanded>

> My code works fine when I run it on IntelliJ, but when I try to compile it, I run into these errors.

@cyiting, how are u compiling it?

If ure trying to run the `runtest.bat` (idk about `runtest.sh` cuz im on windows), u'll need to fix the compilation path in the `runtest.bat` file.

Specifically this line, which only compiles the files in the `./src/main/java` dir, but not its sub-dir like `./src/main/java/duke`, `./src/main/java/duke/exception`, etc.
```bash
javac  -cp ..\src\main\java -Xlint:none -d ..\bin ..\src\main\java\*.java
```

It should be replaced with something like:
```bash
javac  -cp ..\src\main\java -Xlint:none -d ..\bin ..\src\main\java\duke\*.java ..\src\main\java\duke\exception\*.java ..\src\main\java\duke\YOUR_SUB_PACKAGE_DIR\*.java
```
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/78#issuecomment-1407581120" expanded>

> Wow thanks so much.super appreciate it... I found it in ~/Library/Java/JavaVirtualMachines and deleted all versions which solved the problem! Thanks!!

@ChangGittyHub, rmb to close the issue since it's solved 👌

</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/138#issuecomment-1423667222" expanded>

Based on ur Git/SourceTree graph, it looks like you've fetched the `A-Enums` tag from their repo.  
It doesn't seem like u pulled/fetched any branches.

Then:

1. As @francisyzy suggested, using ur file explorer, you should &gt;ins>**FIRST copy your entire repo folder**&gt;/ins> to back it up.

2. I'm not too sure what GUI app u're using, 
   but u should be able to right-click Jun Da's `A-Enums` and delete it.

3. That's should fix the problem in ur screenshot. 
   But do post more info/pictures if u actually clone/pull/fetched more then just that `A-Enums` tag.
</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/171#issuecomment-1427100824" expanded>

> import javafx.scene.image.Image; import javafx.scene.image.ImageView;
> 
> Did u add these imports in Main.java?

yup i did
</panel>

<panel  header="**25 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/171#issuecomment-1427315815" expanded>

> @EvitanRelta While waiting for inputs from others, you can push the code to a branch and share here so that other can try to replicate the problem.

Alright, i've pushed it to [my repo]'s master branch.

[my repo]: https://github.com/EvitanRelta/ip
</panel>

<panel  header="**26 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/171#issuecomment-1427327017" expanded>

> If you are using VSCode, try running through Gradle.
> 
> I face Exceptions when I run through `Launcher.java` but works through `run` in Gradle.

Ayyy thanks, it worked!  
It gave an error when running `Launcher.java` via VSCode, but it did when i did it via commandline `./gradlew run`.
</panel>

<panel  header="**27 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/181#issuecomment-1429490987" expanded>

## Separating commits into different branches

If you're asking how to separate commits from the master branch, into their separate branches, u can use `git cherry-pick`. Specifically:

- From ur Git-graph / SourceTree, and figure out which commit do u wanna separate them at.
  As in, which commit do u want to be the root/base where the branches start branching-off from.

- Checkout to that commit via: `git checkout [ROOT_COMMIT]` or via SourceTree

- Create one of the branches _(lets call it `BRANCH-A`)_ at that commit: `git checkout -b BRANCH_A`

- From ur Git-graph / SourceTree, figure out which commits should belong to `BRANCH-A`,  
  then, while on `BRANCH-A` cherry-pick every one of those commits off the `master` branch:   
  `git cherry-pick [COMMIT_HASH]` or via SourceTree (idk how to use SourceTree, but i think u can right-click > `cherry-pick commit` or something similar)
  
- Congrats! You've just separated `BRANCH-A` 's commits from the `master` branch

- Do the same for the other branches.

&gt;br>

PS: Separating changes in a commit is much harder tho. lmk if u're trying to separate changes in a commit

&gt;hr>

&gt;br>

But based on ur Git-graph seems like u managed to separate them already.   
Nice

![image](https://user-images.githubusercontent.com/35413456/218705962-1d54da6b-5a96-4607-965f-e0ad0879137b.png)

</panel>

<panel  header="**28 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/184#issuecomment-1429496554" expanded>

@jayhee3 rmb to close the issue if it's resolved :&hat;)
</panel>

<panel  header="**29 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/203#issuecomment-1434542053" expanded>

> I am experiencing issues executing my jar file as it does not contain the dependencies.

I'm assuming when u run the jar file, u get the error: `JavaFX runtime components are missing, and are required to run this application`? If so, it's likely similar to Issue #160.

I took a look at ur repo, and in ur `build.gradle` file, this was defined:

```bash
application {
    mainClassName = "seedu.duke.Duke"
}
```

Which I'm presuming was copied from the JavaFX tutorial. There's 2 things to address:
- The `seedu` in `seedu.duke.Duke` from the tutorial is just a placeholder package name, don't copy that.
- Instead of setting `Duke` in the `mainClassName`, it should be `Launcher` since the app needs to run the `Launcher::main` method, not `Duke::main`.

tdlr, just update ur `build.gradle` it to:

```bash
application {
    mainClassName = "duke.Launcher"
}
```
</panel>

<panel  header="**30 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/219#issuecomment-1436926242" expanded>

could u take a screen shot of ur SourceTree/Git Graph at where ur `A-JavaDoc` tag is?
</panel>

<panel  header="**31 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/280#issuecomment-1484084306" expanded>

> @EvitanRelta Was this commit already merged to the master branch by the deadline? Only commits in the master branch are checked by our scripts.

@damithc Yup! Here's the Git graph of our tp's repo _(ie. upstream remote not my fork)_. The DG-update commit and merge commit are highlighted:

![image](https://user-images.githubusercontent.com/35413456/227776030-bc8d6e1f-3c17-425b-9e4d-dda364087e43.png)

</panel>

<panel  header="**32 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/280#issuecomment-1484141185" expanded>

> See https://nus-cs2103-ay2223s2.github.io/website/admin/tools.html#tool-reposense-for-authorship-tracking on how to override the auto-detected authorship

But will adding `@@author` tags after the deadline allow the time sensitive `DG Draft` tag to detect it though?
</panel>

<panel  header="**33 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/288#issuecomment-1487801978" expanded>

@damithc 

> Parts that were significantly adapted, cite the original source and explain the extent to which the code was modified.

So does that mean we are allowed to reuse large copied code (eg. ~250 lines) AS LONG AS we heavily modify said code?

By "cite the original source and explain the extent to which the code was modified",  are you referring to:
```java
//@@author USER-reused
// Adapted from https://stackoverflow.com/a/16252290
// with heavy modification to...
```
or are you referring to:
```
//Solution below adapted from https://stackoverflow.com/a/16252290
```
<br>

---

> Reuse needs to be cited accurately for ethical and legal reasons, and also for future reference (if a future dev wants to take a look at the original code). In addition, it need to be factored in estimating the effort (reusing and adapting requires effort too -- it's just a matter of estimating how much).

So will we be credited reused code that we either heavily modify, or read the code to understand the approach and implemented it ourselves?

Grade wise, how does code contributions in the form of such "heavily modified/adapted reused code" compare against original code written by us?

For example:
If ALL of a student's code contributions are reused code, such that all those reused code are heavily modified/adapted, how does his grade compare against a student that has only written original code?
</panel>

<panel  header="**34 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/288#issuecomment-1488344080" expanded>

@damithc Alright, I think that clarifies most of my doubts. Thanks! :D

> The level of reuse needs to be factored in when estimating the effort.

Last qns, what do u mean my "needs to be factored in when estimating"?

Does it mean:  
"the effort used in reusing code will be factored in our overall effort, thus effort spend modifying code is still accounted for in the overall effort"?

Or does it mean:  
"when our efforts are estimated, the contributions from reused code are deducted, and thus not accounted for in the overall effort"
</panel>

<panel  header="**35 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/288#issuecomment-1494313500" expanded>

@damithc 

Ok, for this question, I'm not worried about grades but, 
should I still use the `@@author USER-reused` tag if after modifying the reused code, 95% of the code has been recoded and 90% of the logic/feature ended up different?

Because I ended up overhauling/refactoring/adding-new-features/bug-fixing the source code, so much that it's almost unrecognisable from the source. And it feels wrong to credit it as being done by the source authors _(instead of "adapted")_.

Should I change the `@@author USER-reused` tag to `//Solution below adapted from URL` instead?

For reference, here's my modified version of the code, and the reused-code source:

**My reused code:**
https://github.com/AY2223S2-CS2103T-W12-2/tp/blob/master/src/main/java/seedu/address/logic/commands/AutocompleteEngine.java

**Source code:**
https://github.com/AY2223S1-CS2103T-T12-2/tp/blob/master/src/main/java/swift/logic/commands/CommandSuggestor.java


</panel>

</panel>


<panel type="info" header="### 6. LIM ..HAWN `@seadragon2000341` (24 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Bug severity labels for documentation bugs**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/356" expanded>

How do we decide what bug severity labels to assign for documentation bugs? The rubrics are not that clear with respect to documentation bugs. 

Based on the rubrics, since documentation bugs are "unlikely to affect normal operations of the product" (rubrics for severity.low) - does that mean documentation bugs would only a maximum severity of sevrity.low?
![image](https://user-images.githubusercontent.com/78403168/230756580-53c9f5ea-a8d1-485e-9963-a3e2634b2b57.png)

</panel>

<panel  header="**2. :fas-info-circle: What happens after branch merge with master**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/223" expanded>

Based on the forking workflow, we do our work on a branch, push to fork and then merge with master branch on upstream. So after we do all these, do we still need to keep the branch in our local repo/origin?
</panel>

<panel  header="**3. :fas-info-circle: Setting up CodeCov**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/180" expanded>

Hello,

I have trouble completing step 3 and 4 below.
For step3, I can't seem to find a way to add to github action workflow.
For step 4, I'm not too sure what they mean by "committing changes in step 2", as well as "ran CI/CD pipeline - are there any specific things that needs to be done in step 4?

Appreciate the help. Thank you!
![image](https://user-images.githubusercontent.com/78403168/218486190-9b012e5c-0ba7-44b1-adfe-f352436195ca.png)

</panel>

<panel  header="**4. :fas-info-circle: IP: Unable to set up github.io webpage**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/176" expanded>

Hello,

I cant seem to set up the github.io webpage

Here are my current configurations
![image](https://user-images.githubusercontent.com/78403168/218366326-6b14d312-8c17-4a93-902a-75b13c514db2.png)

However, when I navigate to https://seadragon2000341.github.io/ip/, it shows me erorr 404.

It has been a couple of hours so Im wondering whether there is anything wrong with the configurations?
</panel>

<panel  header="**5. :fas-info-circle: tP Team Repo Setup: Point 6 Create team PR**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/163" expanded>

Hey all,

For tP Team Repo Setup: Point 6 Create team PR, im unable to create a PR unless there are some changes made. So does this mean we have to "force" to do some changes before making PR?

Thanks!
</panel>

<panel  header="**6. :fas-info-circle: Did not do Level-10 on branch**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/137" expanded>

I did Level-10 on master, so it was not reflected in the IP progress dashboard. Is the best way to rectify this to create a Level-10 branch (with dummy changes) and merge it with master?
</panel>

<panel  header="**7. :fas-info-circle: Why doesnt source tree create branch?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/136" expanded>

I have committed some changes on branch-A-assertions. I thought that source tree would create a separate branch from master but it did not?
![image](https://user-images.githubusercontent.com/78403168/216741024-e8fb7e2d-381b-4f38-99d6-03ada1a278b3.png)

</panel>

<panel  header="**8. :fas-info-circle: Issue with Gradle CLI**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/83" expanded>

When I run gradle CLI, it gives me the following error.

![image](https://user-images.githubusercontent.com/78403168/215267541-4ff5de27-eb46-424a-8382-b5e00e21eed0.png)

I suspect its because my cli version is java 18, so I have to downgrade it somehow. But I am confused here because my Intellij is using SDK 11, and I only have a JDK 18 in C:/Program Files/java so I'm not sure how to set the env variable to jdk 11?

Thank you for your help!

![image](https://user-images.githubusercontent.com/78403168/215267753-9a474823-0d62-453c-b545-2e5e26897436.png)
</panel>

<panel  header="**9. :fas-info-circle: Branch and Push**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/67" expanded>

"Pushing the master branch does not automatically take the b1 branch along with it just because it is already merged to the master branch"
So if I do not push the b1 branch, I will not be able to see that branch on github? (eg. i cannot see the commits I made on that branch)
</panel>

<panel  header="**10. :fas-info-circle: Run junit on methods that return void**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/64" expanded>

How should we run junit tests on methods that return void? (eg. list method that prints out list of tasks)
Since we cannot assertEquals("somestring", list())
</panel>

<panel  header="**11. :fas-info-circle: No tasks in Gradle**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/60" expanded>

Hello everyone,

When I click on the elephant gradle button in Intellij, I can not see any tasks. Is this supposed to be the case?
![image](https://user-images.githubusercontent.com/78403168/214477874-962f133e-2d86-48f2-8a9c-dcddb943d155.png)

</panel>

<panel  header="**12. :fas-info-circle: Junit Test**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/49" expanded>

Are the test cases supposed to be run on individual class methods? Or are we suppose to run Duke and feed it inputs, and compare actual output to the expected
</panel>

<panel  header="**13. :fas-info-circle: Level 7 Branching**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/42" expanded>

After I completed Level 7, I did not commit changes to that branch before creating a new branch for Level 8. So when I did git merge branch-level-7 in the end, all the changes from branch-level-8 were also pushed along with it. Is there a way I can rectify this?
</panel>

<panel  header="**14. :fas-info-circle: The output path is not specified for module ip**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/4" expanded>

Hi all, I got this error when trying to run Duke.java on intelliJ "The output path is not specified for module ip". Im not sure what should be set for the compiler output path?
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/4#issuecomment-1382721884" expanded>

yep but Im not too sure which file I should set to?
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/60#issuecomment-1403089065" expanded>

Ah yes, it works now. I just had to redo the whole thing. Thanks!
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/60#issuecomment-1403089396" expanded>

One more qns - whenever I run Duke and press stop, the following error message occurs. Is this supposed to be normal?
![image](https://user-images.githubusercontent.com/78403168/214481446-d1908b13-e91c-4254-a5db-38a520552701.png)

</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/83#issuecomment-1407560895" expanded>

@jefrai this was really helpful! Thank you! :)
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/136#issuecomment-1416635764" expanded>

thank you @hingen ! answered my qns nicely :)
I was also wondering why some of the blue circles are solid circles but one of them is hollow?
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/136#issuecomment-1416644042" expanded>

Thank you all!
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/176#issuecomment-1427333377" expanded>

Ok it suddenly worked
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/180#issuecomment-1429752867" expanded>

@damithc Hi Prof,

Ok I managed to get codecov to work. But all the pull requests my team members make to the tp repo failed the codecov checks. Is this normal?

![image](https://user-images.githubusercontent.com/78403168/218752979-99e58cdc-ff8a-4d20-80af-f25ded253299.png)

</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/180#issuecomment-1429785226" expanded>

Hi @Hingen, thanks for your help

I cant seem to find gradle.yml anywhere in the repo

Gradle.yml settings seem good
![image](https://user-images.githubusercontent.com/78403168/218758092-576e4995-3dd7-4c9a-abab-0d8822de1493.png)

One of my friend's failed this check. I failed run-repository wide-tests
![image](https://user-images.githubusercontent.com/78403168/218758615-83e38197-2af4-4d5b-8ff2-4d08a1ef675a.png)

</panel>

<panel  header="**24 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/180#issuecomment-1432328054" expanded>

Is it a concern if the checks don't pass? For example, the screenshot in your previous comment @damithc 
</panel>

</panel>


<panel type="info" header="### 7. FRED.. HUI `@FredericChow00` (23 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Unable to load jar files**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/284" expanded>

~~Hi prof,~~

I am getting this error 

`Could not save data to file: java.nio.file.AccessDeniedException: C:\WINDOWS\system32\data` when I am trying to enter a command for another jar file application that I downloaded.

 you know why that may be so?
</panel>

<panel  header="**2. :fas-info-circle: v1.1 milestone not detected in tP Progress**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/234" expanded>

Hi prof,

my team W14-4 has completed all v1.1 milestones and closed all issues as well as the milestone itself but we are not sure why the tracker isnt detecting it.

Are you able to help us out on this?

</panel>

<panel  header="**3. :fas-info-circle: Advice on how to split up long replies by Duke**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/161" expanded>

Initially I tried to tackle this issue by tracking the number of lines that Duke replies and if the number of lines goes over a certian threshold, then I create a new dialogueContainer.

But that seems to not work in some cases. I feel like I should judge when to create a new dialogueContainer based on how long the replies are (like the height?) instead of how many sentences but I'm not sure how to do that

Any advice?
</panel>

<panel  header="**4. :fas-info-circle: Question regarding assertions**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/148" expanded>

When my program meets an assertion that is supposed to be true (but is false), is my GUI supposed to terminate immediately? Or is the user supposed to see the message that is accompanied by the AssertionError? Currently I am only receiving the AssertionError on my console
</panel>

<panel  header="**5. :fas-info-circle: Cyclic Dependency vs Bidirectional Navigability**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/119" expanded>

Hi all,

In the lecture notes, it seems like bidirectional navigability are accepted but does this not mean that there is a cyclic dependency between the 2 classes which is generally discouraged?

Also, just wanted to clarify the difference between bidirectional navigability and 2 uni-directional navigability pointing to each other between 2 classes. Lecture notes say that they are differnet but it would be great if someone could provide an example to show the differences!
</panel>

<panel  header="**6. :fas-info-circle: Error when running gradlew for checkstyle**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/112" expanded>

![image](https://user-images.githubusercontent.com/108938188/215792007-793e5630-e3f7-4641-a789-7ad86aaca623.png)

I received this error when trying to run gradlew. This seems like I haven't installed gradlew correclty (?)

I have already updated my build.gradle files to include the relevant plugins and also included the checkstyle and suppression files
</panel>

<panel  header="**7. :fas-info-circle: ip Progress Tracker not detecting branch**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/94" expanded>

Hi all,

I took a look at the ip progress tracker and realized that my branch-level-8 was not detected (even though I have already pushed it) although all other branches that i pushed were detected. May I know if what are some possible reasons for this issue? 

I pushed all these branches a few days ago so it should not be because that the list is not updated
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/2#issuecomment-1381438847" expanded>

Hmmm I think what u explained about the relationship between interfaces and classes is correct but the "Is-A" relationship is just a standard way of describing OOP concepts between child and parent classes/interfaces. So instead of "can-do" you can just view it as "is-a" because i dont think there's an official "can-do" terminology.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/94#issuecomment-1409625223" expanded>

@damithc Hi Prof, 

![image](https://user-images.githubusercontent.com/108938188/215639122-b8e78176-61f0-49d4-9678-23b823b01962.png)

![image](https://user-images.githubusercontent.com/108938188/215638925-65bcbbfd-aba5-41ea-bd5f-572defa054b7.png)

It seems that for me my brnaches are active in my fork though, although it is still not getting picked up by the website tracker

</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/94#issuecomment-1409861635" expanded>

@damithc @francisyzy yup it's resolved now.

Thanks for the help! 
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/119#issuecomment-1411654001" expanded>

Upon further readings, it seems like bidirectional navigability are referring to the 2 classes having properties that are referencing to each other and that would be ok but cyclic dependency is more of passing the object as parameters in methods.

So does this mean that it would not be good to pass practice to pass in B as parameter to a method in A, while at the same timing passing in A to a method in B, but having the other class as a property would be ok because that is bidirectional navigability?
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/119#issuecomment-1411684396" expanded>

@damithc Thank you for the clarification!
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/119#issuecomment-1411849063" expanded>

Here are my preliminary answers (not sure if they are correct):

1. Since if navigable then associative, and if associative then dependent. So if bi-directional navigable then it's bi-dependent. Question is whether bi-dependent is equivalent to being cyclic dependent (Kind of the same question as Q4 which suggests that they are not the same thing). So my answer is no?

2. From lecture notes, it seems to be ok 

3. Not encouraged

4. No. Because two classes that have a bidirectional relationship suggests that Foo has a property that is specific to a particular Bar object and Bar has a property that is specific to the same Foo object (for the bottom picture). The top picture suggests that the two classes have 2 uni directional relationship which means that Foo has a property of type Bar (but can be any Bar object) and Bar has a property of type Foo (but can be any Foo object). 

So this means that while cyclic dependency is not encouraged, there are some cases where bi-directional navigability/association/dependenct is ok (for example Husband-Wife classes)



</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1413089665" expanded>

![image](https://user-images.githubusercontent.com/108938188/216222071-a02d0a5a-75e6-439b-bf28-424470e55188.png)

Followed the tutorial and did some minor aesthetics adjustments
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/112#issuecomment-1414564761" expanded>

@kayyenl this worked thank you so much!
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/119#issuecomment-1416698313" expanded>

@damithc hi prof, seems like there isn't much follow up on this. 

May I check if there are any misconceptions in my above answer?
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/119#issuecomment-1416739682" expanded>

@damithc Ok thanks prof!
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/148#issuecomment-1421943782" expanded>

> @FredericChow00 that should be good enough, as it is the default Java behavior. After all, the assertion failure can happen even before the GUI is started up.

Got it thanks prof!
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/159#issuecomment-1425432175" expanded>

I did the same too... I just literally created the new level 10 branch on the spot and pushed it to my fork haha.

Not sure if I should've done it diffferently though


</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/161#issuecomment-1426678861" expanded>

@damithc 

For the 4th task, theres more to the event "study" but it doesnt complete because the dialogueContainer is too small.
I'm trying to find a way such that the extra words would spill into the next dialogueContainer

![image](https://user-images.githubusercontent.com/108938188/218251697-4660a4f6-4948-4535-81da-b8b05fde28e0.png)

</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/284#issuecomment-1484654529" expanded>

@damithc i created an empty folder and place the jar file inside it
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/284#issuecomment-1484666021" expanded>

@damithc 
![image](https://user-images.githubusercontent.com/108938188/227875438-f8c0905b-8470-45fd-9aa8-65bab53e1570.png)

the test2 folder currently resides in my Desktop directory. I used the `help` command here as an exampe but I am getting this error for every command that I make.
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/284#issuecomment-1484687827" expanded>

@damithc ah i see ok that solved the issue. thank you!
</panel>

</panel>


<panel type="info" header="### 8. GOH ..N YI `@Junyi00` (23 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/7#issuecomment-1383228202" expanded>

I believe one of the recommended forms of authentication is through the use of **Personal Access Token**, which is described [here](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token). It can be created [here](https://github.com/settings/tokens). 
However, u should look up instructions on storing the created credential on your local machine since it differs for different OSs.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/18#issuecomment-1387159987" expanded>

If you're using IntelliJ, you can start a terminal instance (there's a terminal tab at the bottom on the default layout). From there, navigate to `text-ui-test` folder, and just run batch files like `runtest.bat`
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/28#issuecomment-1396743928" expanded>

@yitong241 I believe the issue resides [here](https://github.com/yitong241/ip/blob/f14b3fd7e7c5f6c4abac27bab95df656b0790edb/src/main/java/Tasks/Monitor.java#L54-L57)

```java
// Monitor.java
public String getCommand() {
    Scanner sc = new Scanner(System.in);
    return sc.nextLine();
}
```

Typically only a single scanner instance should be reading from the input stream. I am not sure why in this instance of UI testing only then this is problematic...
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/27#issuecomment-1396788067" expanded>

@EvitanRelta I am using annotated tags and the iP dashboard seems to detect them as well.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/37#issuecomment-1399280565" expanded>

I faced a similar issue. However to avoid any form of _force pushing_, I deleted the tags both remotely and locally, recreate it with the right commit and push the new tag.

While it essentially produces the same result if done carefully, I prefer the safer (while more troublesome) route as to avoid any potential side effect of force pushing anything at all.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/41#issuecomment-1399875125" expanded>

I feel that the approach of storing user command history could lead to more complexity in the codebase. 

The system needs to behave exactly the same as when the user command was made in that save file. If the system requirement changes and the old data cannot be purged, the codebase needs to accommodate for the old behaviour when it is loading the save file. Eg. Previously, deadline command does not enforce parameters to be date. However after certain iterations, non-date complying parameters are rejected. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/79#issuecomment-1406650382" expanded>

Running the gradle task with the options `--stacktrace` and/or `--debug` could be helpful to understand the root cause of the problem. You could try to do so and update here with its outputs.

My guess would be that there is some permission issue accessing your files, maybe some `.lock` files exist is preventing gradle from accessing them.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/84#issuecomment-1407460228" expanded>

It's hard to tell without looking at the new structure of your codebase and/or the code itself. However, I would guess that the `cannot find symbol` problem occurs because you are missing import statements for classes like `Ui` and `Storage` as they now exists in another package (where previously they exists in the same package).
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/84#issuecomment-1407581454" expanded>

@cyiting I would suggest that if u're not willing to push a 'dirty' commit into your master branch, you could consider branching out and pushing it. It would be easier for others to understand and learn what happened. 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/85#issuecomment-1408400790" expanded>

A quick trick that worked me was to click `Reload All Gradle Projects` in the Gradle toolbar.  
This should parse the `build.gradle` file and install the necessary dependencies.

<img width="257" alt="image" src="https://user-images.githubusercontent.com/54541329/215457289-10d4e947-e1cf-49c2-99ba-03f23f987e7e.png">

</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/107#issuecomment-1410098325" expanded>

> could you provide your `build.gradle` file?

Just to add on, I believe in this situation, pushing your current codebase as a separate branch for us to see or try locally would give you a better response. (you can then delete it later once u resolve it or just merge into master after)

</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/107#issuecomment-1410292660" expanded>

Same here, I can compile and run your application successfully. This could suggest that your JavaFX dependencies have been installed wrongly.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/110#issuecomment-1410328959" expanded>

Any chance your file name for `suppressions.xml` has a typo?
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/118#issuecomment-1411697264" expanded>

Your JavaFX installation seems to be slightly different from the [given guide](https://se-education.org/guides/tutorials/javaFxPart1.html#setting-up-java-fx) and so is your targeted JavaFX version. Following the official installation fixed this issue.

Also, an additional bug in `MainWindow.java`, your images are not in the `images` folder. 
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/129#issuecomment-1414156596" expanded>

I believe @hingen has addressed this by suggesting a fix here #108 
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/131#issuecomment-1415472503" expanded>

Pushing your branch for others to test your setup would be helpful here!
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/144#issuecomment-1419456601" expanded>

Are you using a personal access token for authentication? If so, the problem could be that your personal access token does not have this option enabled:

<img width="673" alt="image" src="https://user-images.githubusercontent.com/54541329/217041636-a8c16314-dea5-47db-9194-97e83bee4d72.png">

Enabling this should allow you to push `gradle.yml` that updates the GitHub action workflows
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/146#issuecomment-1421356997" expanded>

Referencing your `build.gradle` file, it seems that the property`mainClassName` is not correctly configured to point towards your `Launcher` class.

```gradle
application {
    mainClassName = "seedu.duke.Duke"
}
```

Updating the property to point towards the `Launcher` class instead could be the fix for this issue.
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/154#issuecomment-1424485348" expanded>

I believe the correct configuration should be `duke.Launcher`. Nonetheless, I believe this error could mean you are using the wrong JDK version?
</panel>

<panel  header="**20 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/189#issuecomment-1431306604" expanded>

There are similar closed issues, these could be helpful
#68, #78 
</panel>

<panel  header="**21 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/191#issuecomment-1432277496" expanded>

On top of removing the release, you have to remove the ‘A-Release’ tag. I believe the behaviour you are seeing is due to reusing the old A-Release tag which is tied to that particular commit from when you first created it.
</panel>

<panel  header="**22 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/192#issuecomment-1432660577" expanded>

Looking at your current implementation, it is already using relative pathing. I believe you just lack the check for file existence and consequently create the data file/folders if they are missing, which is what @yyj-02 have mentioned above.
</panel>

<panel  header="**23 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/195#issuecomment-1432703963" expanded>

I believe your push is stopped because the remote repository has a different commit history compared to your local repository. Hence, pulling here would be necessary to update your local repository. 
Pulling in this case should not overwrite any changes you have made locally. If there are no conflicting changes, the pull should be seamless. In the event that there are conflicting changes, you would have to address them like you have practiced so during merging branches.
</panel>

</panel>


<panel type="info" header="### 9. WEI .. JIE `@SPWwj` (19 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/11#issuecomment-1384992448" expanded>

@Tempura-Person You may place your code in while loop and catch the exception using try-catch
` try {doSomeThing();} catch (DukException e) {}`
The exceptions which are handle by the try-catch will not terminate the program. Thus, the loop will continue.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/11#issuecomment-1385080344" expanded>

This is what my understanding for DukeException: 
DukeException handle the scenario what we can expect.
The confusion here is "if we can expect the situation, we can just handle it without throwing the exception e.g if statement.
But let think about the following scenario.
./input/getUserInput.java // expect DukeException, but without the method that you want to handle this exception. 
./Duke.java // your main program, contain the method that you want to handle the duke exception.
you may use propagation feature of the Exception to help you handle the exception.

> 
To prevent terminating your program you need to catch the "throw new DukeException" somewhere in your code (e.g. `public void main()`).

You may catch all exception by just `catch(Exception e)  `

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/47#issuecomment-1399987282" expanded>

try 
1.check if directory exist if not mkdir
2.check if file exist if not create files

do allow to print the original exception msg as it will give you more info during debugging.
hope this can help :）
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1409941102" expanded>

Hi, this GUI belong to the JavaFX tutorial 
<img width="305" alt="image" src="https://user-images.githubusercontent.com/30100720/215703075-70c034c0-4c9f-4d6d-8fba-c302e04d821a.png">

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/107#issuecomment-1410290827" expanded>


> I'm have switched and am running on openjdk version 11, but the problem persists <img alt="image" width="639" src="https://user-images.githubusercontent.com/96757889/215749673-2a055a5f-539a-4d69-b631-73cc1bfca4c6.png">

Hi I have run your code on my IDE and it work fine.
Just to give some suggest on the setup of IDE environemnt:
1. Make sure you have choose the correct SDK in the project structure
<img width="770" alt="image" src="https://user-images.githubusercontent.com/30100720/215764461-2f50394d-256f-4147-9723-d2e973d42c91.png">
2. After you edit on your gradle file you may try to do a reload on your project by click this button
<img width="772" alt="image" src="https://user-images.githubusercontent.com/30100720/215764999-efedcf71-40bc-40bb-8aee-c983cb78adc2.png">


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/122#issuecomment-1412319186" expanded>

Create a default constructor for your lele.class. 

Just a suggestion that since you not using any code in lele.class you can create a separate class to handle gui and only call the lele when necessary.

You may look at my code for reference. ：）
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/146#issuecomment-1422189929" expanded>

> @ARPspoofing Could I just clarify with you on the steps you took to create the JAR file again?
> 
> Is it File > Project Structure > Artifacts > + > JAR > From modules with dependencies > Main class = Launcher (duke) > Build Artifacts?
> 
> Or do I need to select JavaFX application instead of JAR?

Do not build from intelliJ.
Use gradle.
Output jar will appear in the ~ip/build/libs
<img width="755" alt="shadowJar" src="https://user-images.githubusercontent.com/30100720/217470177-a12b63ff-e8bf-4ed1-9cc3-f1d9a14c10dd.png">

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/153#issuecomment-1423804206" expanded>

Hi you may refer to this post for solutions: [Java Stream with exception handling ](https://dzone.com/articles/exception-handling-in-java-streams)
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/152#issuecomment-1423840380" expanded>

Assertions handle programmer's mistake.
First thing come into my mind is to use on the dependency class.
You may refer to my Parser.class.
Not a good design as I need to call specific functions before I can get the correct output.
However the assertion is quite useful in this situation as it can ensure I use my class correctly.
In addition, the exception is inappropriate to handle whether developer has use the function correctly.
Thus actually I should remove some of exceptions in my parser class XD.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/152#issuecomment-1424141503" expanded>

> For me, I use it to check for whether the assumptions I made are fulfilled. When coding there are a lot of times where I make assumptions about the arguments I pass to my methods. For example:
> 
> '''java
> 
> private void foo(String str) {
> 
>     return str.split(" ");
> 
> }
> 
> '''
> 
> 
> 
> In this `foo(String)` method, there is an assumption that `str` is not null. Hence an assertion could be use to ensure `str` is not null. 
> 
> 
> 
> It helps in identifying errors and also, personally, I think of it as a good way to make it explicit the assumptions my method makes (especially for private methods where I don't write JavaDocs for).

for our chatbot if the string input come from user，wouldn't it be too risky to use assertion as all the assertion will be disable during production environment🤔
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/152#issuecomment-1424143708" expanded>

> Personally i used my assertions to check for things like making sure that the size of my tasklist is more than -1 and generally checking that i havent messed up any of my own code

But the situation for -1 size list will never happen 😂
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/151#issuecomment-1425169865" expanded>

The problem is caused by the name of your directory folder `Willy`.
Thus, your package name violates the check style convention.
Solution basically to rename your Willy folder using refactor function in IntelliJ Idea to `willy`.
![image](https://user-images.githubusercontent.com/30100720/218003333-7d2a6f06-d709-45fb-91c7-50128c2b6b0a.png)

Just a suggestion to check your treat Checkstyles error as warnings.
This allows you to run your app even you have style error.
Further it is good habits to resolve all the warnings.
![image](https://user-images.githubusercontent.com/30100720/218002704-b0ae92e4-a6af-4abd-b355-fe26e015c50e.png)

</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/158#issuecomment-1425415869" expanded>

Hi the correct configuration is:
'
application {
    mainClassName = "Duke.Duke"
}
'
The mainClassName is defines as the pakage name follow by the class name.
Your package name is: 'Duke'
Your class name is also: 'Duke'
the the full qualifier name should be 'Duke.Duke.'

Just a small suggestion that you might want to change your Duke directory folder to duke or something else that start with small letter, else you will encounter checkstyle error if you use the checkstyle plugin.

</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/158#issuecomment-1425479148" expanded>

> @SPWwj Hiii thank you for the kind reply! I just tried this and the same error occurs, but I will change the directory name to duke then :)

My bad did not pay attention to your screenshot 😅 .
I check your github repo and from your screenshot you have move your `Duke.class `outside of `Duke `package.
Thus your Fully qualified Name should be `Duke ` only
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/169#issuecomment-1426995367" expanded>

> But this will create a file Duke.txt directly under ip/build/libs, right beside duke.jar. While it works, I cannot include any sample data with this method.

I guess you want to implement the junit test?
you might want to run the test by right click the ` Test.class` show in the screenshot below.
The reason `Duke.txt ` is create inside `ip/build/libs` is because your are running the actual jar file using shadowJar.
Since the path is just `Duke.txt`. your txt file will be place at the same directory as your application jar.
Not really sure the resource directory is correct location to store your txt file as your relative path might change if you move your jar to other location.
<img width="962" alt="image" src="https://user-images.githubusercontent.com/30100720/218305195-5f13ba7b-40af-47a0-8c96-e4e27b505b70.png">

</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/169#issuecomment-1426996102" expanded>

```java
> this.getClass().getResourceAsStream("data/Duke.txt");
```
> 


Perhap you could refer to this post for write to resource folder.
`https://stackoverflow.com/questions/8513729/create-file-in-resources-source-folder-in-java-programmatically`
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/161#issuecomment-1427034867" expanded>

One alternative way is to use `dialog.setMinHeight();` to adjust the dialog text to the require height.
We can create two attributes to calculate the height width and height limit:
- `private static final int LINE_LIMIT = 45;`
- `private static final int LINE_HEIGHT = 30;`

Next just create a helper function to format the text:
` formatInput(String input) `
Then we can dynamically configure the dialogbox attritrube in its contructor.
`dialog.setMinHeight(dialogBoxInput.getLineNumber() * LINE_HEIGHT);`
You may refer to my code for more info.




</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/296#issuecomment-1489849393" expanded>

Try this: ' model.getFilteredPersonList().sort((p1, p2) -&gt; p1.getBirthday().compareTo(p2.getBirthday()));
'
</panel>

<panel  header="**19 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/296#issuecomment-1490407857" expanded>

> sometimes

It look like a state issue, since sometime is working correctly and involved multiple components.
Maybe you could provide us your code snippet by pushing the code to a branch, it is helpfull if we know how you:
- apply your filterlist or internalList.
- bind the list to ui component.
</panel>

</panel>


<panel type="info" header="### 10. LEE ..HENG `@jiasheng59` (18 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Question about `ObservableList<T>` behaviour**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/294" expanded>

Is it correct saying that `ObservableList` won't be able to detect changes in `T` itself? Instead the list will only get notified when there's change to the list itself (as compared to the change of internal attribute of `T`). If it's the case, what if we want to detect changes to the attribute of `T`, meanwhile also detect the change to the entire list, will the change to the internal attribute of `T` cascade to the `ObservableList` wrapping around it?
</panel>

<panel  header="**2. :fas-info-circle: Update iP after 23:59 of 17/2/2023**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/207" expanded>

Hi, I would like to further improve my GUI and I have already published a release v0.2 (because I don't want to be penalized for submitting beyond hard deadline).

However, it seems like we still have the 3-day of deadline extension for iP. I'm not sure whether we are allowed to make any changes to my existing code right now. Will be any form of penalty (whether it is iP's mark or any bonus component of this module if there's any) for those who still modify their code within these 3-day extension? 

Thanks in advance!
</panel>

<panel  header="**3. :fas-info-circle: Week 4 Quiz**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/96" expanded>

Does the 's' in the word associations matter in this question? In other words, if there can't be more than one association between two Person objects, we should choose true or false?

![week 4 quiz](https://user-images.githubusercontent.com/96868229/215472529-6cec29bb-8b73-42d5-872a-8545c46c4637.png)

</panel>

<panel  header="**4. :fas-info-circle: Trade-off between handlings all possible errors and writing elegant code**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/20" expanded>

I found that when you're trying to handle all possible errors, the code will quickly become messy and nested with a lot of if-else statement. I haven't had an elegant way to detect all these errors arising from invalid input command for the CLI apps. Does anyone have any idea or suggestion when making trade-off between these two factors? 

Would like to discuss with my fellow classmates below :)
</panel>

<panel  header="**5. :fas-info-circle: Week 1 Quiz - Question 5**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/3" expanded>

![image](https://user-images.githubusercontent.com/96868229/212346458-c0b7d765-cea9-4066-8391-4edbd758684b.png)

Is it referring to Java or all programming languages in general?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/14#issuecomment-1385274763" expanded>

Even if the score is not shown, students can still do trial-and-error by trying different combinations of answers in multiple attempts in order to get higher (or full) marks. 

Since it's meant for students to check their understanding, I think there's no harm showing the score of an attempt. Moreover, showing score immediately will give students more timely feedback imho.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/173#issuecomment-1434387071" expanded>

I usually debug by using the CLI version of my application (I still keep the CLI's logic and related components in my code). I realize the errors thrown while using gradle are usually not shown in full sentence and it doesn't show which lines are involved. So I prefer to use the CLI version. In fact, you can make use of junit test also since common errors like ArrayIndexOutOfBound, NullPointerException usually involve only one or few methods.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/207#issuecomment-1434878379" expanded>

Thanks!

*I will leave this issue open for 1-day so that everyone can see.*
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/214#issuecomment-1436405820" expanded>

I tried to launch your application (downloaded from your release v0.2), I got the same error you mentioned above.
<img width="960" alt="error" src="https://user-images.githubusercontent.com/96868229/220029908-4b7fd063-90b6-48a0-a971-2e1e94cb349d.png">

</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/214#issuecomment-1436406544" expanded>

May I know if you are using Gradle to create the jar file?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/237#issuecomment-1453068079" expanded>

It seems that the "expected" or "advised" way of dividing the work is dividing by features (enhancement), as such, you will work on some (if not all) components of the project for the particular enhancement you're in charge of.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/230#issuecomment-1453348379" expanded>

I don't quite understand what issue you are facing, but I did some search on "re-open" a pull request.

I found that reopening a merged pull request is impossible (at least for 13 years ago). 
https://stackoverflow.com/questions/12674304/github-reopening-a-merged-pull-request

but there's a button named "revert" might be of help to create a new PR in order to revert the changes of that previous PR.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/239#issuecomment-1454813105" expanded>

From my point of view, it depends on your purpose of using exception and the ease of dealing with more possible exceptions in future. Exception is either shown to user or developer, if it's supposed to be shown to user, e.g. for the purpose of telling user which action is not allowed, then using the former one might be clearer in the sense of telling user what exactly went wrong (As a user, I'll be happier to receive the warning like "Hey, deleting task index beyond existing list is not allowed" instead of "Hey, invalid input"). On the other hand, if it's for debugging purpose of current / future developer, I think it's better to make the exception clear in conveying the situation that causes the exception for the ease of fixing bugs.

Of course, the trade-off is now the code becomes much longer and may even look unnecessary to have so many exceptions (`MissingIndexException`, `MissingDatesException`, `MissingDescriptionException`) just to deal with one type of error (for instance, `MissingArgumentException`). 

Whether you should spend time enhancing your existing feature or organizing your exception handling logic (which is kind of related to your code quality), I believe you have (and are given) the flexibility to decide, at least in this module.
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/247#issuecomment-1460008541" expanded>

@wxxedu I just want to make a comment on your last paragraph, in fact, keeping UML as a documentation tool is rather easy (as compared to using a as a design tool) given that there're many tools that automate the process of converting code to UML diagram.

See https://medium.com/nerd-for-tech/how-to-generate-uml-diagrams-from-your-existing-code-814d27bd1537
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/272#issuecomment-1479576131" expanded>

I think as long as the imported method name doesn't conflict with any method name within the class, it's fine to use import static... I also wonder when will one choose one over another 🤔 
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/272#issuecomment-1479581409" expanded>

The reason I can think of is that import static could be used as a shorthand for constants and methods that are used many times within the class you are working with. 
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/294#issuecomment-1489103419" expanded>

Yes, I think this could be the only approach. What I tried before is to make the attribute of T to be an `ObservableValue / Property`, e.g. `SimpleIntegerProperty` and see whether the change to the attribute will cascade to the list. But the GUI doesn't reflect the change automatically, but only changes when I explicitly click on the cell. (It's a bit strange)

Even when I use `FilteredList`, and set a trivial `Predicate` like `p -&gt; true` to it, the GUI still doesn't reflect the change automatically.

So what I did in the end is to remove and add as what @VietAnh1010  suggested. Does anyone have any idea on this matter?
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/296#issuecomment-1490506147" expanded>

I don't think `FilteredList` is intended to update for sorted, but `SortedList` definitely supports update in UI once you set `setComparator` to the list.
</panel>

</panel>


<panel type="info" header="### 11. WANG..XUAN `@wxxedu` (18 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: 💎 UML Adoption & Some Thoughts**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/247" expanded>

Just saw this article online: [https://oro.open.ac.uk/35805/8/UML%20in%20practice%208.pdf](https://oro.open.ac.uk/35805/8/UML%20in%20practice%208.pdf)

Disclaimer: I am biased against the usage of UML. 

This article got me thinking: what's the point of UML? 

To dive a little deeper into this conversation: what is UML modeling? More specifically, should UML be a design tool, or should it be a documentation tool?

Let's first consider UML as a design tool. If it is used as a design tool, then we will need to consider the granularity at which we design. One such example is whether we should include private/public access modifiers. I would like to argue that if we do take such things into consideration, we are thinking about the implementation details of the software, but not the behaviors/features, hence this could not be considered Agile. 

Therefore, if we were to use modeling methods like UML to design software, we should not be considered things like private/public methods. We should mainly be focusing on the **interactions** between different components operating in this system. Only modeling the interactions does not need such a complicated system like UML. 

The difference between tests and UMLs, as I perceive, however, is that UML, by nature, is loosely coupled with the codebase, despite that UML designs are often very coupled with the codebase. Drawing UMLs requires you to consider the interfaces and behaviors, but there is no way to enforce this. This will be very bug-prone. Let's consider the case with multiplicity. It is the assumption of a UML diagram that the programmer will follow the multiplicity specified. Let's consider a design specifying the multiplicity as 0..1. Designing a diagram that has a field that may have a multiplicity of 0 (`null`), is a very bad idea already, as it has been commonly agreed upon that the creation of `null` is a billion dollar mistake. What is even worse is that UMLs cannot enforce this, i.e. UMLs rely on the programmer reading the diagram to know the multiplicity, which, unlike testing, would not let you pass if the specified behavior is not satisfied.

Then let's consider UML as a documentation tool. Because of the loosely connected nature of the codebase, it is very hard to keep updating the UML diagram. Say if you have a rename of one of the items, you will need to go and open your UML tool and then rename that as well... 
</panel>

<panel  header="**2. :fas-info-circle: Request to use Mockito for unit testing**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/202" expanded>

## Library

[Mockito](https://site.mockito.org/)

## Purpose

We plan to use this for creating mocks and fakes for unit testing in our project.

## License

[MIT License](https://github.com/mockito/mockito/blob/main/LICENSE)

Website: [website](https://github.com/mockito/mockito)
</panel>

<panel  header="**3. :fas-info-circle: Wildcard Imports**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/69" expanded>

In the first tutorial, we were shown some style violations. One of them is wildcard imports. However, my IDEA seems to always merge these imports to a wildcard import. I am wondering if it would be ok to just leave it as is, or should I just disable the auto-formatting of the IDE. Thanks!
</panel>

<panel  header="**4. :fas-info-circle: 💎 More abstractions**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/33" expanded>

Hey guys I am back, keep over-engineering things. 

Building on top of [my response to issue #23](https://github.com/nus-cs2103-AY2223S2/forum/issues/23#issuecomment-1397393999), there are a few things that I wish could be better, one of them is that currently for my output, I used `System.out.println`. While there is no real issue with such an approach, it would not be as flexible as I would like it to be, in that:

1. What if I were to change the output? Say, if I were to change the output to writing to a file? Or how about a gui?

1. With `System.out.println`, it is quite hard to conduct unit tests, at least I don’t know how. Maybe I will have to mess with the output streams? (I am not a Java expert, and my past experiences have mostly been working with Dart / Flutter) *Also, I hate bash scripts. You cannot have empty spaces around the assignment operator, what?*

# Writable

Clearly, the way to solve this problem is through **abstraction**. Hence, I have created a new Interface called `Writable`. 

```java
public interface Writable {
	void write(Object object);

	void writeln(Object object);
}
```

Now, with this, I can put a field called Writable in the classes that I wish to write. For example, the `Echo` class from [[here](https://www.notion.so/On-my-design-of-Project-Duke-9860c58274714de3a50a076250a21e59)](https://www.notion.so/On-my-design-of-Project-Duke-9860c58274714de3a50a076250a21e59). 

```java
public class Echo implements IdentifiableExecutable {
	public Echo(Writable writable) {
		this.writable = writable;
	}
	
	private final Writable writable;

	@Override 
	public String getId() {
		return "echo";
	}

	@Override
  public ExitStatus execute(String[] tokens) {
    System.out.println(String.join(" ", tokens));
    // after this, I would want it to skip the current execution loop.
    return ExitStatus.finishCurrentIteration;
  }
}
```

Now, I can replace all occurrences of `System.out.println` with `writable.writeln`. 

## SystemOut

Since `Writable` is only an interface, I do still need concrete implementations. I would want to create an implementation that wraps around the `System.out.println`. Hence I just call it `SystemOut`: 

```java
class SystemOut implements Writable {
	@Override 
	public String write(Object object) {
		System.out.print(object.toString());
	}

	@Override 
	public String write(Object object) {
		System.out.print(object.toString());
	}
}
```

This way, in the instantiation of my `Echo` class, I could just pass in a new `SystemOut` instance. 

# Clean Architecture

Now, with the `System.out.println` removed from our code, I have successful abstracted away a very “specific” feature from the core of my application logic. With that, I can do some reorganization of the files according to the clean architecture proposed by uncle bob: 

[Clean Coder Blog](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)

![image](https://user-images.githubusercontent.com/36021591/213646529-aaa8c3e4-99cf-4d6a-915e-605645110802.png)

Essentially, I want to put the application logic at the core of our app, and make sure that no dependencies of the outer rings can be found inside the app. More specifically, I created a folder called presentation, which shall contain the class `SystemOut` and the `DukeEventLoop`. The other classes, such as `Writable`, `Executable`, `EventLoop` (super class of `DukeEventLoop`), shall be placed inside the entities folder, and the implementations of `Executable`'s, i.e. `Echo`, `Bye`, `TaskManager`, got renamed to `EchoUsecase`, `ByeUsecase`, and `TaskManagerUsecase`, and shall be put inside the usecases folder. I grouped the usecases and the entites folder into a larger folder called domain. Ideally, regardless of how you changed the presentation or the database, you should not change the domain folder. 

# Factories

Using the Writable interface has mostly solved the second problem, 

because now I can write a mock writable class that verifies the behaviors of my code.

## Factory Methods for Instantiation

However, it still failed to fully addresss the first problem. The matter is that if I pass in a new `SystemOut` instance every time I instantiate a new class, if I were to switch to a different implementation of the Writable interface, it would still require me to go out and search for all the `SystemOut` occurences, and swap them by hand. The most ideal way, however, is to use a factory to generate new `SystemOut` instances. This way, if I were to change the SystemOut to a new implementation, say `WriteToFile`, then I would only need to change the instantiation in the factory. All the other code gets kept! 

```java
// ideally:
Writable getWritable() {
	return new SystemOut();
}
// and replace all the new SystemOut with invocations of getWritable().
```

However, there are two issues with this approach: 

1. Java does not support top level functions, so it has became a problem as to where to put this `getWritable` method. To me, the `Writable` class seems to be a place where this makes the most logical sense. However, since `Writable` is considered an entity, as described in the clean architecture, we cannot have dependencies outside of it. (For the Writable class to create a new `SystemOut` instance, we will have to import the file for `SystemOut`, which violates the dependency rule of clean architecture). 
2. If we have 10 more similar classes with features, we would have to write 10 similar functions, which is in a sense, code duplication. 

## Singletons

Also, observing from the characteristics of the `Writable`, we can also find one thing: we do not need many instantiations of the `Writable` object: having only one object would be good enough for us, and having many could potentially waste some resources. Therefore, in the end, we would want:

1. A factory that can provide an instance of any class to our liking;
2. The instance that it provided, regardless of when it was called, is exactly the same instance, i.e. we want to create singletons for the sake of saving resources and having a single source of truth for some stateful instances. 

```java
/**
 * The utilities class for handling the registering singletons. To use it, call
 * <code>Singletons.registerSingleton(Hello.class, new Hello());</code>
 * This way, it can provide a new layer of abstraction, and if any concrete
 * implementations were to change, any code calling <code>Singletons.get</code>
 * would not need to be changed, unless, or course, you directly call the
 * class itself.
 */
public class Singletons {
    /**
     * The dependencies stored in this dependencies section.
     */
    static private final Map<Class<?>, Object> singletons = new HashMap<>();

    /**
     * The dependency suppliers, used for lazy registration.
     */
    static private final Map<Class<?>, Supplier<?>> lazySingletons =
            new HashMap<>();

    /**
     * Registers a class as a singleton, therefore, it would only be created
     * once.
     * @param cls the class of the object.
     * @param object the object itself.
     * @param <T> the type of the object.
     */
    static public <T> void registerSingleton(Class<T> cls,
                                             T object) {
        if (singletons.containsKey(cls) || lazySingletons.containsKey(cls)) {
            return;
        }
        singletons.put(cls, object);
    }

    /**
     * Registers a class as a lazy singleton. A lazy singleton will only get
     * instantiated if it was used.
     * @param cls the class of the object
     * @param supplier the lazy singleton of the object.
     * @param <T> the type of the object.
     */
    static public <T> void registerLazySingleton(Class<T> cls,
                                                 Supplier<T> supplier) {
        if (singletons.containsKey(cls) || lazySingletons.containsKey(cls)) {
            return;
        }
        lazySingletons.put(cls, supplier);
    }

    /**
     * Gets an instance of the specified class.
     * @param cls the class of the class.
     * @return the object that has been registered for this class.
     * @param <T> the type of the object.
     */
    static public <T> T get(Class<T> cls) {
        if (singletons.containsKey(cls)) {
            return cls.cast(singletons.get(cls));
        } else if (lazySingletons.containsKey(cls)) {
            final T object = cls.cast(lazySingletons.get(cls).get());
            singletons.put(cls, object);
            lazySingletons.remove(cls);
            return object;
        }
        throw new RuntimeException("Dependency for " + cls.getName() + " has " +
                "not been injected.");
    }
}
```

There are a few notes here:

- I am not a Java developer, and I don't know what is the common practice for this in Java, so take this with a grain of salt.
- The Class of the type is used as the key.
- I allow for registering of both singletons and lazy singletons, and the latter one is lazily evaluated. Once evaluated, it would be put inside the singletons set, and the corresponding supplier would be removed from the lazySingletons set.
- The reason that I throw a `RuntimeException` instead of a checked exception in the last method is that this could only be wrong if the developer forgot to register the corresponding dependency, and it can be fixed programmatically. Hence, it should not be checked.

This way, in the Duke class, I could write a static method called `configureDependencies()`: 

```java
private static void configureDependencies() {
	Singletons.registerLazySingleton(Writable.class,
		() -&gt; new SystemOut());
	// ...
}
```

and call this line before executing the rest of the code. 

Therefore, I could replace all the occurrences of instantiating a new `Writable` with this:

```java
Singletons.get(Writable.class);
```
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/23#issuecomment-1397393999" expanded>

My approach is kinda very wild. It may not be a good approach, and I over-engineered by quite a lot.

That said, I quite like it. So if you are interested, can have a look at the full code [[here](https://github.com/wxxedu/ip)](https://github.com/wxxedu/ip). (what I have written here is not exactly the same as what I have wrote in the actual code, as I have cleaned up things quite a bit there. That said, most of the idea is here.)

# Rationale

For me, I didn't use any `if`'s for this. The reason is that `if` and `switch` states are kind of hard to manage, especially if you want to add a feature later on. Every time you add a feature, you need to go through your files, and find out the locations where you used conditions to check. In most cases that I can think of, however, this shouldn’t be a problem (because you will most likely only have one top level keyword, i.e. delete, add, etc.). I was, however, kind of worried that if we were to do second-level instructions, and potentially 3 levels. For example, I was thinking:

```
task add hello world
```

where the first would indicate what module you are using, the second would be indicating the command that you are executing, and from the third word, it would be the actual message send to that command. 

Obviously, this approach isn’t very “iterative,” i.e. we should only be building the minimal to get the app started. But hey, I like over-engineering things… so…

One other disadvantage of using the `if` or `switch` statements is that they that would not provide any logical grouping for the different features. I do not want the mixing of different features. Ideally, on the very top level, I only want to use some very common interfaces and use  minimal code — so that, in the case that I want to rewrite some code for a specific feature, I would not have to interact with code for another feature at all. **This means that I want as much separation between different modules as possible**. 

# Basic Interfaces

## Executable

One thing that was pretty obvious to me from the very beginning is that everything looks like a “command,” hence abstracting them as a “command” sort of makes sense. However, since we don’t really need to have any predefined features for the “command,” it is more like an interface. Hence, I created the “Executable” interface, which defines the function `execute`.

```java
public interface Executable {
    ExitStatus execute(String[] tokens);
}
```

Let’s just leave the `ExitStatus` here, it’s a enum, it’s … a bit complicated and I don’t quite like it.

The input is firstly divided by the `" "` into different segments, which I call tokens, and then for any executable, it shall be able to execute on the tokens. This way, if we were to have second level subcommands as mentioned before, all we needed to do is to throw away the first item of the tokens, and then pass done the executables.

## IdentifiableExecutable

It would then became obvious that there are two types of commands: the commands that would be activated when no keywords are passed in, and the commands that would be activated when you pass in some keywords. For example, in the first task, we were asked to echo the command passed in:

```
> I love you.
I love you.
```

And for some tasks, like `bye` and `list`, where we were asked to identify what it is, and execute it accordingly. Hence, I defined another interface called `Identifiable` which has a getter for the id, the id being the keyword that’s needed for activating this command. Originally I was going to call it `Keywordable`, `Keyable`, etc. but they just sounded wrong lmao. 

```java
public interface Identifiable {
    public String getId();
}
```

And I created an interface extending both `Identifiable` and `Executable`, and called it `IdentifiableExecutable`. Maybe I could just put the `getId` into the `IdentifiableExecutable` and ignore the `Identifiable` interface all by itself, but I just did it this way. 

```java
public interface IdentifiableExecutable extends Identifiable, Executable {}
```

## NestableExecutableObject

Since my goal was to have the ease to support for nestable commands later one, we would need a tree-like structure. (I didn’t do this abstraction right away, it was while I was writing a more concrete class I realized that I could abstract this feature out). 

Firstly, this structure must be an `Executable`, so that when we call execute on the root tree, it would traverse down the execution, and we could use a set of unified interfaces for that.

Secondly, this structure would be able support both types of `Executable`'s as its children, i.e. it should be able to call `IdentifiableExecutable` if the `getId()` result of the instance matches the first token that’s passed in. To do this, I created a HashMap and a List inside this object:

```java
public class NestableExecutableObject implements Executable {
    // ... 
    private ArrayList<Executable> postExecutables;
    private HashMap<String, IdentifiableExecutable> identifiedExecutables;
    // ...
}
```

As their names do suggest, we should first handle the `identifiedExecutables`, after which we can deal with the `postExecutables`. And … since we are already complicating things to this extent, why not just add a preExecutables as well.

```java
public class NestableExecutableObject implements Executable {
    // ... 
    private ArrayList<Executable> preExecutables;
    private ArrayList<Executable> postExecutables;
    private HashMap<String, IdentifiableExecutable> identifiedExecutables;
    // ...
}
```

Further, we need “setters” for this executable fields as well. The word “register” sounds very cool to me, so I wrote three “setters”: 

```java
public class NestableExecutableObject implements Executable {
    // ...
    void registerPreExecutable(Executable executable) {
        // code to add the executable to the preExecutables
    }
    void registerPostExecutable(Executable executable) {
        // code to add the executable to the preExecutables
    }
    void registerIdentifiedExecutable(IdentifiableExecutable executable) {
        final String key = executable.getId();
        // put the key, executable into the identifiedExecutable hashmap
    }
    // ...
}
```

And, it would be very reasonable, for any command, to run through the `preExecutables` first, then the `identifiedExecutables` whose key matched the first token of the tokens (remember our `Executable` interface?), and lastly, the `postExecutables`.

## ExitStatus

Now we have a problem: after running an executable for a single command (tokens array), there may be cases where it want a second executable to run using the same command, or it would simply want this command to be thrown away and read for the next command. To solve this, I let the return type of the `Executable` interface be a enum called `ExitStatus`:

```java
public enum ExitStatus {
    finishCurrentIteration,
    terminate,
    continueExecute;
}
```

- `finishCurrentIteration`: any command after this in this iteration of the event loop shall be skipped;
- `terminate`: the whole application shall be terminated;
- `continueExecute`: the event loop can continue to running executables using the same tokens.

Hence, with all that, the code for execute in the `NestableExecutableObject` is as follows:

```java
class NestableExecutableObject implements Executable {
    // ...
    // this is abstracted out to avoid code duplication to run the 
    // preExecutables list and the postExecutable list
    private ExitStatus runExecutablesList(
        List<Executable> executables, String[] tokens
    ) {
        ExitStatus status = ExitStatus.continueExecute;
        for (Executable executable: executables) {
        status = executable.execute(tokens);
            if (status != ExitStatus.continueExecute) {
                return status;
            }
        }
        return status;
    }
	
    // the execute status
    @Override
    public ExitStatus execute(String[] tokens) {
        ExitStatus status = runExecutablesList(preExecutables, tokens);
        if (status != ExitStatus.continueExecute) {
            return status;
        }
        if (!identifiedExecutables.isEmpty()) {
            final Executable executable = identifiedExecutables.get(tokens[0]);
            if (executable != null) {
                // TokenUtilities is a helper class that I wrote to avoid code 
                // duplication.
                final String[] newTokens = TokenUtilities.instance.removeFirst(tokens);
                status = executable.execute(tokens);
                if (status != ExitStatus.continueExecute) {
                    return status;
                }
            }
        }
        return runExecutablesList(postExecutables, tokens);
    }
    // ...
}
```

## EventLoop

At this point, I’ve mentioned the event loop several times. The event loop shall be in charge of looping through and execute the root node (which is an executable), and terminate whenever the root node returns `ExitStatus.terminate` enum.

Hence:

```java
public abstract class EventLoop {
    // ...
    private final Executable rootExecutable;
    public abstract String[] getTokens();
    public void run() {
        ExitStatus status = ExitStatus.continueExecute;
        while (true) {
            status = rootExecutable.execute(getTokens());
            if (status == ExitStatus.terminate) {
                break;
            }
        }
    }
}
```

And I wrote a concrete class, DukeEventLoop, extending this class which gives a concrete implementation of `getTokens()`. The `getTokens()` reads from java’s `Scanner` and splits up the line into an array of tokens. 

## Simple Applications:

Now it would be very simple for us to implement some features like echoing: 

```java
public class Echo implements Executable {
    @Override
    public ExitStatus execute(String[] tokens) {
        System.out.println(String.join(" ", tokens));
        // after this, we would want it to skip the current execution loop.
        return ExitStatus.finishCurrentIteration;
    }
}
```

To add this feature:

```java
final Executable root = new NestableExecutableObject();

final Executable echo = new Echo();
root.registerPostExecutable(echo);

final EventLoop eventLoop = new DukeEventLoop();
eventLoop.run();
```

With this approach, we could also very easily make `Echo` an `IdentifiableExecutable`, i.e. only to execute if, say, the keyword contains echo.

```java
public class Echo implements IdentifiableExecutable {
    @Override 
    public String getId() {
        return "echo";
    }

    @Override
    public ExitStatus execute(String[] tokens) {
        System.out.println(String.join(" ", tokens));
        // after this, we would want it to skip the current execution loop.
        return ExitStatus.finishCurrentIteration;
    }
}
```

```java
final Executable echo = new Echo();
root.registerIdentifiedExecutable(echo);
// > echo hello
// hello
```

Of course, if we were to register echo to the `postExecutables` list, it would still behave the very same as before. 

# Stateful Commands

One thing that is common with the Echo and perhaps, Bye, is that **they do not have states**. The same `Executable`, when being executed 1000 times, would give you the same result for the 1000 times. This is not true however, when you are managing the tasks. 

## TaskManager

When you are managing tasks, you need to have states (i.e. the list of tasks). Furthermore, the state has to be shared among different Executables. If I were to create an Executable called delete and call it 10 times,  it should be able to delete the corresponding tasks from the same list of tasks. 

To do this, I created a class called `TaskManager` to maintain the state as a List of Tasks. 

```java
public class TaskManager {
    private List<Task> tasks;
}
```

And to create the Executable that helps manage the different state transitions, I used anonymous classes. For example, if I were to add a task to the task manager:

### Anonymous Classes

```java
public class TaskManager {
    // ...
    public IdentifiableExecutable getAddTaskExecutable() {
        return new IdentifiableExecutable() {
            @Override
            public String getId() {
                return "add";
            }
            @Override
            public ExitStatus execute(String[] tokens) {
                final Task task = Task.fromTokens(tokens);
                addTask(task);
                System.out.println("added: " + task);
                return ExitStatus.finishCurrentIteration;
            }
        };
    }
	// ...
}
```

And to use it:

```java
final TaskManager manager = new TaskManager();
root.registerIdentifiedExecutable(manager.getAddTaskExecutable());
```

With this approach, you would only need to create an anonymous class for each of usecase that you have, i.e. list the tasks, adding the tasks, etc. 

# ExecutableRegisterable

There is one last issue that I wish to fix, and that is about registering the `Executable`s with the classes. For some very simple stateless `Executable`’s, it would be just a one liner:

```java
root.registerIdentifiedExecutable(new Echo());
```

However, this would not be the same case with something as complicated as a `TaskManager`:

```java
final TaskManager manager = new TaskManager();
root.registerIdentifiedExecutable(manager.getAddTaskExecutable());
root.registerIdentifiedExecutable(manager.getDeleteTaskExecutable());
// ...
```

If you have say 10 functions, then you will have to do this for 10 times. Furthermore, it would be easy for you to get it wrong, say registering an `IdentifiedExecutable` as a post executable, which will always get executed if no match was found in the hashmap. Essentially, I think this is bad because **this requires you to know the internal workings** of the TaskManager class. In a way, requiring users to do this violates the “show not tell” rule from CS2030S. So, I created the `ExecutableRegisterable` interface:

```java
public interface ExecutableRegisterable {
    void register(NestableExecutableObject nestable);
}
```

implemented it in the `TaskManager`, marked all the getExecutable-alike functions in the `TaskManager` as **private**, and now, I would only have to do this:

```java
final ExecutableRegisterable manager = new TaskManager();
manager.register(root);
```

This way, regardless of how I mess with the code outside of the task manager, I would not make any mistakes as long as the register function works as expected — which should be a concern of the TaskManager but not anywhere else in the code.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/20#issuecomment-1397912852" expanded>

I quite like @salty-flower's design. My design is very similar in nature, with the difference that the `canTake` is replaced with another interface called Identifiable, and I used a hashmap to map to the specific command (executable). For more details, can check [this post](https://github.com/nus-cs2103-AY2223S2/forum/issues/23#issuecomment-1397393999).
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/32#issuecomment-1398037161" expanded>

I think it's ok? I have already done so. 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/69#issuecomment-1406022018" expanded>

Got it, thanks! I was using IDEA's auto formatting. 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/65#issuecomment-1407434909" expanded>

Same here as @Zxun2. One example for me is that I abstracted each command into a separate class called command, and after exiting the command, there would be an `ExitStatus`. It would be quite painful to be dealing with, say, numbers here, which would require me to look up a table to understand what a number indicates, and it would also allow many more different cases than my need. Hence, using a enum would make sense.

I'd say that in general, it's when there are only a handful of different states, it would make more sense to use Enums -- and they are always better than hard-coding the strings as well. 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/111#issuecomment-1410395844" expanded>

Hi! The same problem happened to me as well. ~~I managed to fix it using the guide on JFX itself.~~

~~https://openjfx.io/openjfx-docs/#gradle~~

~~I think it's quite clear there in the guide, so can just follow it.~~

---

Edit, I think you can check #87, because the link that i provided uses java 17 i think. 

</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/87#issuecomment-1410407760" expanded>

Thanks so much for this. I managed to fix this issue on my mac, but I didn't really know what happened. Reading your post has made it very clear for me. 
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/112#issuecomment-1410528327" expanded>

Hi! Have you tried running 
```sh
gradle wrapper
```
Because it appears to me that your gradlew file has not been generated. :-)
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1410544168" expanded>

<img width="712" alt="java--2023_01_31-23_10_48@2x" src="https://user-images.githubusercontent.com/36021591/215798648-cae713b0-8f00-4766-9448-ce21de57df15.png">

Mine is pretty generic, with a few modifications to make the icons appear smaller and added a few paddings. 
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/108#issuecomment-1455104639" expanded>

For me I changed Intellij's ordering:

![IntelliJ IDEA-Settings-2023_03_05-22_15_18](https://user-images.githubusercontent.com/36021591/222965880-6f5f5f0c-0bf2-40b2-be66-ac738a6637f7.png)

</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/247#issuecomment-1475172331" expanded>

Thanks so much. I now have a more balanced view of UML. I think I wasn't being very clear here:

> We should mainly focus on the interactions between different components operating in this system.

My thinking is that public/private is more like an implementation detail, hence they should not be of importance when we try to see the whole system, i.e. the structure/interactions. I do see many similar patterns in UML. 

Regardless, I think that many of the problems that I had with UMLs have now been cleared. Thanks so much for that. 
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/269#issuecomment-1482715663" expanded>

I would like to share a bit about my story with Copilot. My friend joined Copilot beta before me, and once we were doing some online coding sessions together, I realized that he wasn't using it. I asked him why, and he said that he found the code generated to be not so reliable. I don't use Copilot now also. After the release of ChatGPT though, I did use it quite frequently, especially for checking new APIs.

I have several issues with Copilot that prevented me from using it:

1. User experience issues: the copilot would disable the snippets/autocomplete features of the IDE, despite sometimes I would like to see these things. Also, sometimes I would like to press the tab key, and this in Copilot would mean using the suggestion provided, which often turns out not to be what I wanted.
2. Bad code: I often find myself, after pressing many tabs, ending up with a bunch of code that doesn't really make sense. I felt a reduction in the quality of the code that I wrote. While when Copilot works, it works quite nicely, there are so many cases when it doesn't work. Also, writing the code has never been the part that takes a longer time, but rather finding the bug and making sure that the code is correct. Further, Copilot does not seem to have a big picture ahead of it. The code that it produces lacks a "taste" (I don't know what better word to describe it). 
3. Distraction: there are a lot of times when I started writing code, I would see that Copilot suggesting me a long block of code. Then, I will need to go and read through what it suggested, which distracts me from my own train of thought. 

I use ChatGPT as a "search engine" that helps me check APIs and gives me concrete examples of how certain APIs are used. It reduces the distraction of Github Copilot, and it is much faster than searching via Google. There are also many occasions when the APIs are poorly documented, and ChatGPT helps greatly with that. Further, because I generally don't use the code generated by ChatGPT, I feel more control over the code that's written. 

I may not hold the popular opinion, but I don't believe, at least at the current stage, that AI can write good code. Perhaps they can write OK code, but I don't think that the code written by AI would be production ready in any sense. 
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/269#issuecomment-1482719859" expanded>

It's more sort of like that Copilot/ChatGPT can get an algorithm implemented / an API correctly invoked, but they lack the structural knowledge of the codebase, and they don't know how to structure your code such that it is nice and clean. 
</panel>

<panel  header="**18 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/269#issuecomment-1483691673" expanded>

Just to be a bit more specific, the issue that I found with Copilot is that it tends to cause a lot of code duplication. When two chunks of code have very similar logic, it would just fill out the second part, without considering extracting the shared parts. Another problem that I found with Copilot is that it tends to create unnecessary features. 
</panel>

</panel>


<panel type="info" header="### 12. ANG ..KANG `@Irminrics` (17 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Smoke Testing TP for Linux**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/337" expanded>

Hi all, 

Could any Linux user help to conduct a smoke test on the JAR file for my tp? During the PE Dry Run, there were issues with the JavaFX's UI in the Linux environment with our JAR file. Unfortunately, as there are no Linux users within my team, we are unable to debug and test the application in question.

I would be grateful if anyone could provide any insights and testing for this issue. Preferably, the operating system used would be Arch Linux with KDE-Plasma version 5.27.3-1. However, any other Linux distro would be welcomed as well. Additionally, if there are any issues encountered during the testing process, it would be appreciated if screenshots could be provided for reference.

Thank you all in advance!

JAR File link: https://github.com/AY2223S2-CS2103-W16-3/tp/releases/tag/v1.3

</panel>

<panel  header="**2. :fas-info-circle: Password for Lecture Recording**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/250" expanded>

There seems to be a password set for the today's lecture recording. Anyone knows the password?
</panel>

<panel  header="**3. :fas-info-circle: Testing of UI for JavaFX**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/240" expanded>

I have managed to done up some UI using JavaFX and it appears that codecov requires me to test those codes. I check the test files given in AB3 and it seems like they did not test much of the UI to begin with. Does anyone have any advice on how to work on this?
</panel>

<panel  header="**4. :fas-info-circle: JAR file generated by Gradle and ShadowJar not working**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/165" expanded>

![image](https://user-images.githubusercontent.com/33411270/218277206-c080e8b4-ddd6-4187-9910-024fb58ed73c.png)

Although I successfully build gradle with shadowjar. It seems like the jar file produced in /builds/lib/ is not working properly. Running the jar file on the terminal does not do anything while clicking on the jar file on the explorer only creates the /data directory for task list storage without any GUI.

Has anyone else encountered this issue? Thanks in advance!
</panel>

<panel  header="**5. :fas-info-circle: Issue with JavaFX Label Ellipsis**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/123" expanded>

Hi! I faced a few issue with ellipsis and truncated string with labels. I also noticed there are several issues raised regarding this. I have followed the solution provided in #102 and it solved most of the problem. However, one issue I am still facing is how the last line of my output is not shown. 

As you can see from the picture, it appears that the height is already dynamic except for the fact that the last line is always hidden/truncated. Would appreciate any help and advise on this! Thanks!

![image](https://user-images.githubusercontent.com/33411270/216099216-d95971c6-4c5e-4c4a-92c6-9880c183562a.png)

</panel>

<panel  header="**6. :fas-info-circle: Where did you use varargs?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/114" expanded>

Those of you who used varargs, where did you use them? Having learned about it in Week 4, I'd like to give it a go, but I haven't found a suitable use case yet. I was thinking, perhaps, it could be used for the find command, which can allow the program to take in multiple keywords simultaneously?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/1#issuecomment-1382748808" expanded>

I'm using the M1 Mac and encountered this issue earlier as well but solved it eventually.

> 
> (base) leyaozhu@Les-MacBook-Air Downloads % java -version java version "11.0.17" 2022-10-18 LTS Java(TM) SE Runtime Environment 18.9 (build 11.0.17+10-LTS-269) Java HotSpot(TM) 64-Bit Server VM 18.9 (build 11.0.17+10-LTS-269, mixed mode)
> 

I got a similar result doing checking the java version on the terminal and if you are seeing this, it is highly likely you have  existing JDKs in your mac and have not uninstalled them. Follow the instructions given by the [video ](https://www.youtube.com/watch?v=wwV_L3lKYYw&ab_channel=ProgrammingKnowledge2) that was provided to us to uninstall the other JDKs and ensure that you see Zulu11 after performing a `java --version`. This fix the problem for me. 

Hope it helps anyone out there!


</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/114#issuecomment-1411294067" expanded>

Thanks all! I got a good idea of how to implement it into my IP now.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/123#issuecomment-1416252774" expanded>

Thanks! I implemented this too but apparently what caused my error was my usage of custom font and font size for the text in the label. Hope this thread would help someone out there!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/165#issuecomment-1426872181" expanded>

Solved it by changing the application main class name in build.gradle! 
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/240#issuecomment-1455005430" expanded>

@damithc Thanks for the prompt reply prof! However, the codecov cause the CI status to fail in my PR, and according to the tp workflow given to us, we are not supposed to merge any failed CI into the master branch? Is there any workaround for this?
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/240#issuecomment-1455005846" expanded>

Got it! Thanks prof :)
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/250#issuecomment-1464074407" expanded>

Thanks for the prompt reply prof :)
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/337#issuecomment-1497757577" expanded>

Hi @immanuelhume,
There was initially a problem with the UI but I did some changes so I need to check if it work now. Seems to be working from your screenshot except the fact that the command bar and result display box is a little small.

Thanks for helping me to test it! I appreciate it a lot! I'll leave this thread here to see if the UI is working on other Linux distro.

</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/337#issuecomment-1498468184" expanded>

Hi @hingen,

Thank you for testing and the insights you have shared through email!

With this, I'll close this thread now since it seems to be working for at least 2 people using Linux. Thanks all!
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/337#issuecomment-1498519591" expanded>

Thank you @Beebeeoii! Appreciate it!
</panel>

<panel  header="**17 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/367#issuecomment-1502794520" expanded>

I have similar issues on my mac as well. My guess is this might be due to the square brackets in the jar file.
</panel>

</panel>


<panel type="info" header="### 13. NI S..GHAN `@SHni99` (16 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Cannot see answer for readiness quiz**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/372" expanded>

![image](https://user-images.githubusercontent.com/96757889/231538942-ff588e0d-7e88-4c99-9ad4-fc8941750659.png)

Mentioned that the answers will be shown after I have submitted the quiz but turned out otherwise.
</panel>

<panel  header="**2. :fas-info-circle: Cannot load javafx library**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/301" expanded>

Hi,
I am facing an issue when testing out the jar.file just now. 
I am using mac os terminal to run the jar command

![image](https://user-images.githubusercontent.com/96757889/229047662-5bfb778b-f0bf-4cfa-83bf-64b1c937503d.png)
</panel>

<panel  header="**3. :fas-info-circle: [Technical issue] Unable to start daemon after installing javaFx to build.gradle**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/107" expanded>

The following error does not allow me to continue and I had tried for the past few hours.

<img width="1353" alt="image" src="https://user-images.githubusercontent.com/96757889/215720012-0b64c54a-8573-4ad0-8790-f48ad848efb0.png">

</panel>

<panel  header="**4. :fas-info-circle: iP progress dashboard failed to detect branch-Level-7 and tag #8**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/73" expanded>

<img width="983" alt="Screenshot 2023-01-27 at 11 53 16 AM" src="https://user-images.githubusercontent.com/96757889/215006174-8dafa071-4a5e-4baf-a9e3-5a5c95d381c4.png">

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/73#issuecomment-1405983976" expanded>

<img width="1178" alt="image" src="https://user-images.githubusercontent.com/96757889/215006292-b3cbbe38-b014-48ce-b451-edc0c00afd78.png">
### Tag 8
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/73#issuecomment-1405984355" expanded>

<img width="945" alt="image" src="https://user-images.githubusercontent.com/96757889/215006353-f3efcf86-3ce7-4a9e-a019-f3120df7c513.png">
### Evidence of branch-Level-7
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/73#issuecomment-1406016836" expanded>

> @SHni99 That branch doesn't seem to be merged to the master branch yet.
> 
> ![image](https://user-images.githubusercontent.com/1673303/215007299-13fe179c-8eca-4aa9-b865-033776b7287e.png)

Thank you for replying
Prof, can I merge the branch with my latest master branch now?
Also,  the dashboard could not detect tag #8 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/107#issuecomment-1410050843" expanded>

I have gotten this issue "*Caused by: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found*" also
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/107#issuecomment-1410137405" expanded>

> could you provide your `build.gradle` file?

I have pushed 'branch-Level-10' onto [branch-Level-10](https://github.com/SHni99/ip/tree/branch-Level-10)
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/107#issuecomment-1410144214" expanded>

Had followed the instructions on [JavaFx](https://se-education.org/guides/tutorials/javaFxPart1.html).
Faced with the same error:
<img width="810" alt="image" src="https://user-images.githubusercontent.com/96757889/215740452-dbcc0c4c-ccdb-44cd-a927-e2d27cc76800.png">

</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/107#issuecomment-1410150417" expanded>

ah its jdk 18, but i remember i changed to jdk 11 😢 
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/107#issuecomment-1410201412" expanded>

I'm have switched and am running on openjdk version 11, but the problem persists
<img width="639" alt="image" src="https://user-images.githubusercontent.com/96757889/215749673-2a055a5f-539a-4d69-b631-73cc1bfca4c6.png">

</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/107#issuecomment-1410444232" expanded>

Thanks for the help everyone, it has been resolved 👍 
Problem was caused due to wrong installation of javaFx using Gradle, therefore I have tried to install javaFx lib without using Gradle and it worked
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/301#issuecomment-1491487834" expanded>

Thanks Profs, it worked after I have set my java  environment version to zulu jdk 11, which I followed the simplest method using [sdkman](https://sdkman.io/) as recommended by Francis. 
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/302#issuecomment-1491673356" expanded>

Hi @ajjajjajjajj, 
If you have existing Openjdk, delete it by following [here](https://www.youtube.com/watch?v=wwV_L3lKYYw&ab_channel=ProgrammingKnowledge2)
Afterwards, in your mac terminal run `curl -s "https://get.sdkman.io" | bash` then `sdk install java 11.0.18.fx-zulu`
When finished, you will see the changes when you run `java --version`
Credits to @francisyzy for the help
</panel>

<panel  header="**16 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/372#issuecomment-1506232495" expanded>

Hi prof, I have submitted another one and is able to see the answers. Thank you.
</panel>

</panel>


<panel type="info" header="### 14. TITU.. WEI `@tituswe` (15 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Testing GUI**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/252" expanded>

I am unable to pass codecov because I made changes to the MainWindow.java file. 

Previously, the controller classes in the ui component were not covered by tests.

But upon editing the files, codecov starts to give me warnings when I make pull requests.

Im having trouble with testing MainWindow.java because it requires me to initiate a full setup of the application and launch the GUI upon running the testfile.

Does anyone have an efficient way to test the ui component? Or is there a different way I can remove the ui component from codecov?

<img width="1054" alt="Screenshot 2023-03-12 at 3 09 48 PM" src="https://user-images.githubusercontent.com/97359862/224529878-91a84e5a-632d-4b63-8bc6-60ded0248a40.png">

</panel>

<panel  header="**2. :fas-info-circle: EditCommandTest cases failing on assertEquals inside CommandUtilTest#assertCommandSuccess**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/249" expanded>

# IntelliJ Version
IntelliJ IDEA 2022.3.1 (Community Edition)
Build #IC-223.8214.52, built on December 20, 2022
Runtime version: 17.0.5+1-b653.23 aarch64
VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o.
macOS 12.6.3
GC: G1 Young Generation, G1 Old Generation
Memory: 1024M
Cores: 8
Metal Rendering is ON
Non-Bundled Plugins:
    com.vermouthx.xcode-theme (1.6.1)
    IdeaVIM (2.1.0)
    CheckStyle-IDEA (5.76.0)

Kotlin: 223-1.7.21-release-272-IJ8214.52

## Reference Image
![IMAGE 2023-03-10 21:22:19](https://user-images.githubusercontent.com/97359862/224326861-38dde689-7ee3-4fd9-8c3d-d985d46eaa74.jpg)

# Problem
I made some edits to my team's `CommandResult` whereby I store the target `Client` of each command as a field as opposed to the previous version of `CommandResult` where the `Client` was formatted into the `feedbackToUser` field.

## Before:
```
public class CommandResult {

    private final String feedbackToUser;

    /** Help information should be shown to the user. */
    private final boolean showHelp;

    /** The application should exit. */
    private final boolean exit;

    /**
     * Constructs a {@code CommandResult} with the specified fields.
     */
    public CommandResult(String feedbackToUser, boolean showHelp, boolean exit) {
        this.feedbackToUser = requireNonNull(feedbackToUser);
        this.showHelp = showHelp;
        this.exit = exit;
    }
```

```
    @Override
    public boolean equals(Object other) {
        if (other == this) {
            return true;
        }

        // instanceof handles nulls
        if (!(other instanceof CommandResult)) {
            return false;
        }

        CommandResult otherCommandResult = (CommandResult) other;
        return feedbackToUser.equals(otherCommandResult.feedbackToUser)
                && showHelp == otherCommandResult.showHelp
                && exit == otherCommandResult.exit;
    }
```

## After:
```
public class CommandResult {

    private final String feedbackToUser;

    private final Client targetClient;

    /**
     * Selects a particular client
     */
    private final boolean select;

    /**
     * Help information should be shown to the user.
     */
    private final boolean showHelp;

    /**
     * The application should exit.
     */
    private final boolean exit;

    /**
     * Constructs a {@code CommandResult} with the specified fields.
     */
    public CommandResult(String feedbackToUser, Client targetClient, boolean select, boolean showHelp, boolean exit) {
        this.feedbackToUser = requireNonNull(feedbackToUser);
        this.targetClient = targetClient;
        this.select = select;
        this.showHelp = showHelp;
        this.exit = exit;
    }
```

```
    @Override
    public boolean equals(Object other) {
        if (other == this) {
            return true;
        }

        // instanceof handles nulls
        if (!(other instanceof CommandResult)) {
            return false;
        }

        CommandResult otherCommandResult = (CommandResult) other;
        return feedbackToUser.equals(otherCommandResult.feedbackToUser)
                && targetClient == otherCommandResult.targetClient
                && select == otherCommandResult.select
                && showHelp == otherCommandResult.showHelp
                && exit == otherCommandResult.exit;
    }
```

# Details
As you can see from the screenshot attached, inside the debug console the parameters being compared in the `assertEquals(...)` are all the same, yet the test cases fail specific to the `EditCommandTest` file.

I get the following:
![Screenshot 2023-03-10 at 9 29 20 PM](https://user-images.githubusercontent.com/97359862/224328346-4f6fec03-4b66-4f74-bf39-b3ea27f2dcd8.png)

Would anyone know what cld be possibly wrong? Do feel free to post more questions for me to clarify. Thank you!


</panel>

<panel  header="**3. :fas-info-circle: Error in online textbook:   UML → Sequence Diagrams → Minimal Notation**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/164" expanded>

Just for clarity, as this might be a very obvious question, is there a slight error in the sequence diagram shown below?

![Screenshot 2023-02-12 at 2 01 20 AM](https://user-images.githubusercontent.com/97359862/218273834-f0bc2a6d-0f59-4ba5-a2cd-dfd456b2d3f4.png)

I believe that the return value should be a dashed arrow line pointing left.

Thank you in advance for the clarification!
</panel>

<panel  header="**4. :fas-info-circle: push command on CLI not working**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/7" expanded>

Under section W2.4e push: Uploading data to other repos, I followed the instructions as per activity.

Upon entering the command `git push origin master`, and entering my GitHub username and password, I am shown the following error message: 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/tituswe/samplerepo-things.git/'

Could someone explain why this is happening? Thank you.

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/142#issuecomment-1418256284" expanded>

> 

Yes I know a few others who have ran into the issue because of this. 

Do the following steps to check:

**Check Version**
You can check by running 

`java --version`

in your terminal and your output should be as follows:

`openjdk version "11.0.17" 2022-10-18 LTS`
`OpenJDK Runtime Environment Zulu11.60+19-CA (build 11.0.17+8-LTS)`
`OpenJDK 64-Bit Server VM Zulu11.60+19-CA (build 11.0.17+8-LTS, mixed mode)`

should you not see that you are using the Azul build then download it [here](https://www.azul.com/downloads/?version=java-11-lts&os=macos&architecture=arm-64-bit&package=jdk-fx)

**Check Location**
Then run 

`whereis java`

and your output should be `/usr/bin/java`

**Set `JAVA_HOME`** 
run

`nano ~/.bash_profile`

and add the following lines to the file:

`export JAVA_HOME=/Library/Java/JavaVirtualMachines/zulu-11.jdk/Contents/Home`
`export JDK_HOME=$JAVA_HOME`
`export PATH=$PATH:$JAVA_HOME/bin`

save and exit the file then run

`source ~/.bash_profile` 

to reload the changes.

**Check**
run

`echo $JAVA_HOME`

you should see output

`/Library/Java/JavaVirtualMachines/zulu-11.jdk/Contents/Home`

**END**

Hope this helps!!!


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/164#issuecomment-1426844782" expanded>

@damithc Oh okay thanks prof! I just realized that the function call was _get minefield info_... Thanks for the clarification!!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/194#issuecomment-1433128351" expanded>

Hi, i'm also facing a similar problem... running the command in command line will execute the jar file and the application runs, however when I try to double click the application icon nothing happens.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/194#issuecomment-1433149197" expanded>

@damithc I'm using macOS
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/194#issuecomment-1433169180" expanded>

@glyfy I managed to figure out the problem, originally in my `build.gradle` file I had my shadowJar archiveBaseName the same name as my package. Not sure why it caused a problem tho... 

My original set up:

```
application {
    mainClassName = "saturday.Launcher"
}

shadowJar {
    archiveBaseName = "saturday"
    archiveClassifier = null
}
```

Fixed set up:
```
application {
    mainClassName = "saturday.Launcher"
}

shadowJar {
    archiveBaseName = "Saturday"
    archiveClassifier = null
}
```

Not sure if you have the same situation but this fix worked for me!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/198#issuecomment-1434118805" expanded>

Hello @tricixg, 

You should install the Azul build of the the JDK, and make sure that your JDK and gradle versions are compatible! Not entirely sure but JDK 11 and gradle 6.2 may not work the best with each other. Here are the recommended setups!

<img width="832" alt="Screenshot 2023-02-17 at 1 20 16 PM" src="https://user-images.githubusercontent.com/97359862/219556341-161daa93-9f83-4dc5-8de4-7700c0decccb.png">

</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/227#issuecomment-1445395950" expanded>

I believe that if two components share the same data format/communication protocol, this implies that they are highly likely to work together in a programme. 

I get that there is the possibility of there being rare cases where two components share the same data format but are not coupled. But I guess in your average software programme if two components have data structured in the same way it his highly likely that they share some sort of dependency.

I would say that its not **necessary** that two components with the same data format implies coupling, but I can understand the high likelihood of it.

Hope someone can clarify!!
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/249#issuecomment-1463810044" expanded>

** I have confirmed that the issue is with the assertEquals statement on line 82 in the first attached image. Commenting out the line passes the testcases that are failing
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/249#issuecomment-1464081172" expanded>

Sorry all, I have fixed the bug... it was just an issue with checking Client#equals(). Haha :')
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/251#issuecomment-1465110535" expanded>

@damithc Hi prof, in the original version of AB3 that all the teams forked, the UI component was not covered by tests (i.e. the controller classes such as MainWindow.java). I made changes to MainWindow.java and now I start getting warnings by codecov that the methods in that class is not covered by tests. 

Is it possible for us to suppress the warnings where appropriate? Or do we just ignore the codecov?

I have also started a new issue on testing GUI to discuss this question in detail.
</panel>

<panel  header="**15 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/252#issuecomment-1465125637" expanded>

@eugenetangkj @damithc Okay great ill go check out how AB4 does the UI testing! Thanks for the advice :-)
</panel>

</panel>


<panel type="info" header="### 15. EUGE..GJIE `@eugenetangkj` (14 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Naming Conventions for Files**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/361" expanded>

Hello! I have resubmitted a file on Canvas for my PPP, but I think Canvas automatically adds a version number at the end. For example, my file name was in the format of `[TEAM_ID][Your full Name as Given in Canvas]PPP`, but after reuploading the file, the name of the file shown on Canvas became `[TEAM_ID][Your full Name as Given in Canvas]PPP-1`.

May I check if there is any action required on my side to circumvent this issue? Thank you!
</panel>

<panel  header="**2. :fas-info-circle: UI Truncation**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/322" expanded>

Hello! Sorry, I would like to ask another question regarding the feature freeze. Currently, we have a field called `CompanyName` which we specify the limit to be 50 characters.

However, on devices of smaller sizes (e.g. 14 inch laptop), inputing a value of 50 characters leads to the value to be truncated on our UI, and cannot be shown fully even when the window is maximised.

![image](https://user-images.githubusercontent.com/86542359/229742668-18797be7-ffd5-4dbd-80bc-68a04347a6cb.png)


May I check if we are allowed to fix the truncation issue? This is because inputing a value of 50 characters is within the specifications of our product, and instead of changing the limit of 50 characters (which is more of a feature change), we feel that fixing the overflow issue is more closely-related to a bug fix.

Thank you!
</panel>

<panel  header="**3. :fas-info-circle: Changing Display Messages**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/319" expanded>

Hello! Currently, for our team's commands involving indexes, we have the following 3 messages:
1.  Negative Index or 0 -&gt; `The index provided is invalid.`
2.  Positive index greater than size of list -&gt; `The index provided is out of range.`
3.  Integer overflow (both positive and negative) -&gt; `Invalid command format!`

Can I check will it be considered a breach of the feature freeze if we were to change the message for integer overflow? Our team is planning to change the message for integer overflow (negative) to be `The index provided is invalid.` and integer overflow (positive) to be `The index provided is out of range.`.

If we are not allowed to change it, then could we just specify in our user guide that the requirements of an index is an integer, state the range of what an integer should be, so if the user enters outside of this range, then it is valid to display `Invalid command format!`?

</panel>

<panel  header="**4. :fas-info-circle: Stuck on Job is about to start running on the hosted runner**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/254" expanded>

Hi, I recently followed the GUI tests that AB4 has, to conduct testing for my team's updates to the GUI. However, I encountered an issue of being stuck at the `ubuntu-latest` CI build, where on GitHub, it would be stuck at `Build and check with Gradle`, having no progress in doing the required checks. There is no problem for `macos-latest` and `windows-latest` where the builds managed to successfully complete.

Loading:
![image](https://user-images.githubusercontent.com/86542359/224614809-4b73f917-e4d4-4876-9d5c-d13670844c86.png)


Log message:
![image](https://user-images.githubusercontent.com/86542359/224614004-2693d2c6-6ce2-461f-b320-55473b9d0816.png)


I thought that it might be a problem with my `build.gradle` file but the `ubuntu-latest` build managed to complete when I push only my changes to `build.gradle` without my GUI unit tests. Hence, the problem might be with my GUI unit tests, but I am not sure whether that would be the case because all tests managed to complete successfully locally and the CI builds for `macos-latest` and `windows-latest` were complete.

Could I kindly seek some advice on this issue? Thank you!


</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/45#issuecomment-1399911840" expanded>

Hi! I am a fellow student, and based on my understanding, the tags should be added after merging. In other words,

1. Work on Level 7 in a branch named branch-level-7.
2. Switch back to master, and create a new branch named branch-level-8 to work on Level 8.
3. Switch back to master. Merge branch-level-7. This merge will create a merge commit in master, and tag this commit as "Level-7". Push this commit to your fork.
4. In master, merge branch-level 8. This merge will again create a merge commit in master, and tag this commit as "Level-8".

Do correct me if my understanding is incorrect. Thanks!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/99#issuecomment-1410420911" expanded>

In the `handleUserInput` method, I checked if the input given by the user is "bye". If so, I made use of a `PauseTransition` object to close the stage after a specified duration. While the duration is still ongoing, the exit message will be processed and I prevented user input by using the `setDisable` method on `userInput` and `sendButton`. Then, after the duration, the application closes itself. Here's a useful StackOverflow [post](https://stackoverflow.com/questions/27334455/how-to-close-a-stage-after-a-certain-amount-of-time-javafx) that helped me.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/177#issuecomment-1429016296" expanded>

Hi @BoAi01, thank you for the detailed write-up above! It helped me to correctly render the table on GitHub pages. On a small note, my GitHub pages automatically refreshed itself after pushing to the remote repo so I think there is no need to unpublish the page and the changes would be automatically published. 😄 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/252#issuecomment-1465117430" expanded>

Hi, I saw some test classes from [Address Book Level 4](https://github.com/se-edu/addressbook-level4/tree/master/src/test/java/seedu/address/ui) such as `GuiUnitTest` and `UiPartTest` that utilise the [TestFx](https://github.com/TestFX/TestFX) library to do GUI testing. I think they might be useful for you, but may I also confirm whether we are allowed to use and adapt them as long as reuse credit is given?
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/254#issuecomment-1465691818" expanded>

Hi Prof @damithc, thank you for your reply! I managed to resolve it with the help of a method in `GuiUnitTest` from a past [CS2103T project](https://github.com/AY2223S1-CS2103T-W17-4/tp). I have given credit for the method accordingly in my code as well. Appreciate the guidance!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/266#issuecomment-1477626215" expanded>

I faced the same problem too! Might be a version issue. I think the problem is the package `Storage` and the interface `Storage` are both referred to `as Storage`, that's why the arrows are not pointing correctly. I just renamed the interface to `StorageInterface` and the arrows point correctly.  Referring to `StorageClassDiagram.puml`, I changed line 14 to `Class "&gt;&gt;interface>>\nStorage" as StorageInterface`.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/266#issuecomment-1479706375" expanded>

HI @jerome-neo, did you change lines 28, 30, 34 and 35 as well?
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/319#issuecomment-1495559934" expanded>

Alright, thanks for the clarifications Prof! It really helped.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/322#issuecomment-1495668040" expanded>

Alright, thanks prof for the answer!
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/361#issuecomment-1501310511" expanded>

Okay, thanks for the reply Prof! Appreciate it.
</panel>

</panel>


<panel type="info" header="### 16. YEO .. JUE `@MrTwit99` (14 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: JavaFX error The handle is invalid**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/185" expanded>

Hi everyone,

I'm not sure what's causing the error for my JAR file but whenever i type the `bye` command, it always show me this error message.
![image](https://user-images.githubusercontent.com/97277438/218824854-8959ed0d-95a1-4a98-852c-6b2d4ecc51c8.png)

This error message does not happen when I run manually via my IDE as shown below.
![image](https://user-images.githubusercontent.com/97277438/218825016-dc625fb1-9139-46ef-b1ab-d18b4cc5a161.png)

Despite this error, my application does close as expected. AKA when i try to hit the next enter button, it will automatically close just as I set it to be. But I'm not sure if its now closing due to the error. 
Also, it is not printing my `bye` message hence the issue.

Notes:
I did create my JAR file via build.gradle > gradle runShadow
I tried running gradle shadowJar too
I did recreate my JAR file after all my implementations
</panel>

<panel  header="**2. :fas-info-circle: Regarding Week 5 Jar File**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/146" expanded>

Supposed I created the JAR file with JavaFX libraries successfully, is the JAR file supposed to show the GUI when i run the following command?

```ruby
java -jar XX.jar
```

Or is this suppose to only show the CLI since it is on Command Prompt when the JAR file is being executed. Not sure if there's any error in my JAR file creation, it is 11MB > 5MB so i suppose quite likely my JavaFX files are inside. I will upload my JAR file with JavaFX libraries onto my release for referencing.
</panel>

<panel  header="**3. :fas-info-circle: Regarding A-Jar / JAR file**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/93" expanded>

I managed to create the JAR file by following the steps shown in the video in this website: https://se-education.org/guides/tutorials/jar.html

However, as I try to run my Duke via the command java -jar (absolute file path), my Duke managed to startup but its file reading and writing capabilities are disabled. I suppose the issue here is the JAR file does not contain my file / shifted my file location hence causing this issue. Anyone else facing this issue and any tips on fixing this? 

![image](https://user-images.githubusercontent.com/97277438/215357790-cd43d733-2eb6-4b4c-808d-6ebad422e1e3.png)


</panel>

<panel  header="**4. :fas-info-circle: Regarding Java Coding Standards**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/86" expanded>

Is it alright if I add a method within the main method and halfway through the code and not at the start or end of the code? 
Or would it be better if i move the method to the end of the main method instead? 
Main reason as to why my method is within the main method as I want to make use of some of the functions: PrintWriter and StringBuilder.

An image is shown below as to what I'm trying to describe.
![image](https://user-images.githubusercontent.com/97277438/215311026-8bcb4bad-b9b7-4d59-bc21-98c1df867ce5.png)

</panel>

<panel  header="**5. :fas-info-circle: Regarding Weekly Quiz Score**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/39" expanded>

Hi Prof, I noticed the option for us to view our Weekly Quiz score has been disabled.

Would it be possible for you to enable it once again? This would allow us to know if we have met the minimum requirement of 70% correct and reattempt should we not hit the requirement. 

</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/86#issuecomment-1407587103" expanded>

Thanks a lot @hingen! I think that helps with my issue!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/93#issuecomment-1408080910" expanded>

Thanks @hingen and prof!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/146#issuecomment-1421405194" expanded>

@Junyi00 
Thanks for the help but unfortunately, it did not manage to solve this issue. Still no GUI being opened.

my `build.gradle` file currently looks like this after the change:
```ruby
application {
    mainClassName = "seedu.duke.Launcher"
}
```
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/146#issuecomment-1422166216" expanded>

Alright, thanks!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/146#issuecomment-1422182721" expanded>

@ARPspoofing Could I just clarify with you on the steps you took to create the JAR file again?

Is it File > Project Structure > Artifacts > + > JAR > From modules with dependencies > Main class = Launcher (duke) > Build Artifacts? 

Or do I need to select JavaFX application instead of JAR?
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/146#issuecomment-1422191464" expanded>

Oh! I was wondering what they meant by building via gradle. Thanks!
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/160#issuecomment-1426652739" expanded>

Hi @shittake,

Here is something I realized while looking at your code.

![image](https://user-images.githubusercontent.com/97277438/218247125-1bac5078-00cf-40b5-b711-2d0313191a23.png)

Under your `build.gradle`, I believe you are giving the program the wrong file for mainClassName as shown here.

I believe in your case, your ``mainClassName`` should be ``Launcher`` instead of ``Duke`` as Launcher.java is the one starting your program / GUI? You might want to test again after changing that line.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/185#issuecomment-1430864062" expanded>

Alright, thanks prof!

I have created a new branch "branch-InvalidHandleError" which can be accessed via this [link](https://github.com/MrTwit99/ip/tree/branch-InvalidHandleError)

I suspect the issue is probably at [duke.java](https://github.com/MrTwit99/ip/blob/branch-InvalidHandleError/src/main/java/duke/Duke.java)'s getResponse(). I'm not sure if there's any other thing to do to close the GUI but how i implemented the termination of Duke is via these two lines:
```java
Platform.exit();
System.exit(0);
```
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/185#issuecomment-1433174026" expanded>

i guess the issue lies with java version, thanks all!
</panel>

</panel>


<panel type="info" header="### 17. HMUU.. MOE `@HmuuMyatMoe` (14 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Planned enhancement for more than 1 feature with the same flaw**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/362" expanded>

If we have, for instance, 2 different features (add task with deadline, add person with phone number) with the same flaw,

e.g., Our validity checks for the parameters of these different add commands are not very comprehensive (e.g., when checking for deadline, we allow deadlines like `01/01/1000` and when checking for phone numbers, we allow phone numbers to be more than 8 digits like `911111111111111`)

So, our planned enhancement for both of these feature flaws would be to improve the validity checks. 
When we write about this enhancement in the planned enhancement section, are we allowed to combine them together as one enhancement (Making all the validity checks more comprehensive)? 
Or, would they be considered 2 different enhancements (one being improving validity check for deadlines, and another being improving validity check for phone numbers)? Thank you!
</panel>

<panel  header="**2. :fas-info-circle: Checking for duplicate person is case sensitive**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/338" expanded>

When we checked for duplicate persons in our application, the search is case sensitive so `Amy` will not be considered to be the same person as `amy`. (We did not state in our error message or UG that the search is case sensitive)

Since people will most likely consider `Amy` and `amy` to be the same person, may we ask if this is a bug that we can fix (by making the search case insensitive so that `Amy` and `amy` will be considered duplicates? Thank you!
</panel>

<panel  header="**3. :fas-info-circle: Changing error message**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/331" expanded>

May I confirm that the following can be considered a wrong error messages and is thus a bug that can be fixed?
(We initially intended for %s to be format specifiers, but somewhere in the code, we simply printed out the message with "%s" and forgot to use String.format to replace the %s)

![image](https://user-images.githubusercontent.com/88267136/229959453-37f43e7f-441b-4126-a2d3-1e9f1109b65e.png)
![image](https://user-images.githubusercontent.com/88267136/229960092-107097af-6ed3-456b-a6a8-f378e47b4c52.png)


</panel>

<panel  header="**4. :fas-info-circle: UI bug**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/326" expanded>

In our PE dry run, we received a report that our UI was not intuitive enough. (Especially the numbers circled)
Can I confirm that it **IS** a violation of the feature freeze if we were to fix it to make it more intuitive, for instance, showing "Quantity: 2" instead of just "2"? Rather, we should just be clarifying what the numbers mean in the UG? Thank you!

![image](https://user-images.githubusercontent.com/88267136/229823718-59e85d55-900f-4f8e-b467-128007b0e505.png)

</panel>

<panel  header="**5. :fas-info-circle: Questions on bug fixes vs feature freeze**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/324" expanded>

For our application, we have an "Add supplier" feature where the user is able to add a supplier's email.

When checking for validity of the email, we only checked for the email to have a local part @ domain name (so abc@abc and abc@abc.com were both considered valid). We did not state that ".com" was compulsory in both our error message and our user guide. However, we received feedback from our PE Dry run tester that this was a functionality bug. 

While it is common for emails to have a ".com" behind, in this case, would it be more of a feature flaw instead of a bug?

Or would it fall under the following category as a type of bug that we can fix? Thank you!

![image](https://user-images.githubusercontent.com/88267136/229813032-382cacde-8b83-4e8b-8b8b-efeb514d2daa.png)

</panel>

<panel  header="**6. :fas-info-circle: Requesting for smoke test on Linux**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/225" expanded>

Would appreciate any help from Linux users to help smoke test [this ](https://github.com/HmuuMyatMoe/ip/releases/tag/A-Release)jar file with the usual method of navigating to the directory and using the command `java -jar botanic.jar`. Thank you!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/225#issuecomment-1445288314" expanded>

@Lava-Iris @jeremykhoo-NUS Thank you for your help!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/324#issuecomment-1496023947" expanded>

We also had a similar issue with the checking of a supplier's phone number where we only checked and made sure that the phone number was at least 3 digits. Our error message for phone number validity check did state that the phone number should have "at least 3 digits" but it is not specified in the UG. We received 2 functionality bug reports that
1. Allowing for 3 digits phone numbers was a functionality bug
2. Allowing for phone numbers more than 8 digits was a functionality bug

It is indeed common for phone numbers to be 8 digits so would it also be considered a bug under the following category which we be allowed to fix (make it so that only phone numbers that are exactly 8 digits are accepted)? Thank you!
![image](https://user-images.githubusercontent.com/88267136/229816291-bae640d1-d122-4fa6-887c-a15ad6231ad1.png)

</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/324#issuecomment-1496063302" expanded>

Thank you, prof! In this case, would it suffice to specify the validity requirements of the inputs in our UG?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/324#issuecomment-1496085337" expanded>

Thank you!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/326#issuecomment-1496093737" expanded>

Thank you!
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/331#issuecomment-1496976391" expanded>

Thank you!
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/338#issuecomment-1499068189" expanded>

Thank you prof!
</panel>

<panel  header="**14 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/362#issuecomment-1501628942" expanded>

Thank you prof!
</panel>

</panel>


<panel type="info" header="### 18. YONG.. JIE `@daitenshionyan` (13 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Feature freeze - fixing ID not resetting**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/314" expanded>

Currently for our application when the user clears the data, the ID does not reset to 1. So when the user adds another data it will continue from the last ID before the data was cleared. It was not mentioned in the UG that ID will be resetted but we feel that this is an assumed behaviour. My team an I would like to confirm if fixing this will violate feature freeze.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/23#issuecomment-1396449103" expanded>

Hello! I am unsure about the ideal way to implement this as well but here is what I am using. I think it reduces quite a significant amount of if-else checks.

A method that separates the command and arguments from the user input. The command will extracted and the arguments will be converted to a HashMap instead of a list. This way the command logic can just get whatever arguments it needs from the keywords and if it doesnt exist it can throw an exception that can be handled later on. With this, only the execution logic needs to be implemented.

```java
        String inputString = "";
        String command = "";

        try (Scanner scanner = new Scanner(rawInput)) {
            if (scanner.hasNext()) {
                command = scanner.getNext();
                if (scanner.hasNext()) {
                    inputString = scanner.nextLine().strip();
                }
            }
        }

        try {
            // convert to hash map
            HashMap<String, String> inputMap = parse(inputString);
            // execution
            switch(command) {
                case "deadline":
                    String by = Optional.ofNullable(inputMap.get("by"))
                        .orElseThrow(() -&gt; new SomeSyntaxException("Missing by"));
                    // more logic
                    break;
                 // rest of the commands
                default:
                    // handle invalid commands
            }
        } catch (SomeSyntaxException syntaxEx) {
            // handle syntax errors
        } catch (SomeExecutionException executionEx) {
            // handle execution exeptions eg. index out of bounds
        }
```
By using a HashMap the user can enter the arguments in whatever order they want so long as the parameters are there (eg. `event /from mon /to fri` and `event /to fri /from mon` are the same). But all extra arguments (eg `todo qwer /qwer qwer`) will be ignored unless there are checks for them which might result in a lot of repeated code.

I broke the command execution logic in to separate classes to avoid a big switch block.

Hope this helps!!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/31#issuecomment-1398437962" expanded>

I was thinking of creating a file utility class containing this static method that is used to create the save directory. It returns `true` only if the directory exists when it returns.

```java
public static boolean mkdirs(Path path) {
    if (path.toFile().exists()) {
        return true;
    }
    return path.toFile().mkdirs();
}
```

So reading and writing will be something like this:

```java
String dirPathString = "save_data";
String filePathString = "/test.txt";
String content = "abcd";
try {
    if (!FileUtils.mkdirs(Paths.get(dirPathString))) {
        throw new IOException("Failed to create file");
    }
    // method to write file
    FileUtils.writeFile(Paths.get(dirPathString, filePathString), content);
    // method to read file
    System.out.println(FileUtils.readFile(Paths.get(dirPathString, filePathString)));
} catch (IOException ioEx) {
    ioEx.printStackTrace();
}
```
The directory path here is relative to where the program is running and there is no need to find the root directory. This works for me but I also do not know if this is the best approach and would like to get some feedback.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/64#issuecomment-1403800644" expanded>

I am not sure if we should be using JUnit to test printing methods but I think it is possible to do so by redirecting `System.out` print stream to a file and then checking that file contents.

```java
@Test
public void test() {
    Path outputPath = Paths.get("output.txt");

    // delete old file
    if (outputPath.toFile().exists()) {
        outputPath.toFile().delete();
    }

    // test
    try {
        System.setOut(new PrintStream(Paths.get("output.txt").toFile()));
        // testing method
        System.out.println("hello");
    } catch (FileNotFoundException fnfEx) {
        fail(fnfEx);
    }

    // check file
    try {
        String actual = new String(Files.readAllBytes(outputPath)).replaceAll("\r", "");
        String expected = "hello\n";
        assertEquals(expected, actual);
    } catch (IOException ioEx) {
        fail(ioEx);
    }
}
```
This is somewhat similar to what runtest.bat / runtest.sh does and think we should use that instead from testing printing stuff.

As for testing other void methods I guess we can create a stub class that overrides the class of what that method is working on and let that method work on that stub. Afterwards check if the state is what we want.

These are just my opinions and please do correct me if I am wrong and would like to hear your opinions as well as I am quite unsure about this too haha.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1410173327" expanded>

I wanted to try shaping the bubbles
![SS](https://user-images.githubusercontent.com/100074448/215744411-16b7a428-5394-44fc-89c1-9bd440e20bb4.PNG)

</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/118#issuecomment-1411725816" expanded>

Other than the images not being in `images` folder that @Junyi00 mentioned, the `duke` class field was not yet initialised when the `initialize()` method is called somewhere in the loader.

By only tweeking your code a bit to something like this in `MainWindow` I was able to get the window to show!!

```java
// changed path to remove images
private Image userImage = new Image(this.getClass().getResourceAsStream("/DaUser.png"));
private Image dukeImage = new Image(this.getClass().getResourceAsStream("/DaDuke.png"));

@FXML
public void initialize() {
    /* new addition here >>>>> */ this.duke = new Duke();
    scrollPane.vvalueProperty().bind(dialogContainer.heightProperty());
    dialogContainer.getChildren().addAll(
            DialogBox.getDukeDialog(this.duke.showWelcomeMessage(), dukeImage)
    );
}
```
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/141#issuecomment-1416719493" expanded>

After creating the stylesheet you will have to set that component to use the stylesheet. This is the setting for that in Scene Builder:
![image](https://user-images.githubusercontent.com/100074448/216761684-fc95107c-f288-4bb0-95c3-db9b459cbad9.png)
Make sure to add it to the root node (the `AnchorPane` in your screenshot).

Alternatively, you can also add it at runtime by adding this in the start method of your class that extends `Application`:

```java
@Override
public void start() {
    // ...
    Scene scene = new Scene(root);
    scene.getStylesheets().add(this.getClass().getResource(PATH_CSS).toString());
    // ...
}
```

`PATH_CSS` is the path to the .css file.

---

In the stylesheet, to change the thumb color, just add the following lines:

```css
.scroll-bar .thumb {
    -fx-background-color : /* color */;
}
```

If you want to remove the arrows, adding this does the job:

```css
.scroll-bar .increment-button,
.scroll-bar .decrement-button,
.scroll-bar .increment-arrow,
.scroll-bar .decrement-arrow {
    -fx-background-color : transparent;
    -fx-shape : " ";
    -fx-padding : 0.0;
}
```

You might have to change the colors of the track to to get the desired scroll bar that you want. Here is what I am using for reference on the effects:

```css
.scroll-bar .track {
    -fx-background-color : rgb(187, 213, 212);
    -fx-border-color: transparent;
}

.scroll-bar .increment-button,
.scroll-bar .decrement-button,
.scroll-bar .increment-arrow,
.scroll-bar .decrement-arrow {
    -fx-background-color : transparent;
    -fx-shape : " ";
    -fx-padding : 0.0;
}

.scroll-bar .thumb {
    -fx-background-color : rgb(188, 165, 192);
    -fx-background-radius : 5.0;
}
```

Result:
![image](https://user-images.githubusercontent.com/100074448/216762286-79677def-ca7c-4b27-a4d5-037e859ec25d.png)

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/174#issuecomment-1427881406" expanded>

Hello I have looked through your code and I think the only issue is that the `initialise` method is supposed to be spelled as `initialize` (**Z** instead of **S**). This is in line 35 of `MainWindow`. I was able to get the auto scrolling to work by changing that.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/256#issuecomment-1468475317" expanded>

`assertFalse(AB1 == AB2)` should compare the references.

However I think a combination of both would be better. One to compare if they are different references and the other to check if they have the same state.
```java
assertFalse(AB1 == AB2)
assertEquals(AB1, AB2)
```
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/262#issuecomment-1474022036" expanded>

Try this:
```java
import static java.util.Objects.requireNonNull;
import static seedu.address.logic.parser.CliSyntax.PREFIX_NAME;
import static seedu.address.logic.parser.CliSyntax.PREFIX_NRIC;
import static seedu.address.logic.parser.CliSyntax.PREFIX_STATUS

import java.util.function.Predicate;

import seedu.address.commons.core.Messages;
import seedu.address.model.Model;
```

I think the checkstyle wants us to put static imports at the top.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/314#issuecomment-1493735499" expanded>

@damithc The application delibrately does not adjust the remaining items. So the items will still be 1, 3 and 4 and the next will be 5 if 2 is deleted. The ID is like a serial number to identify the data instead of an index position.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/314#issuecomment-1493914113" expanded>

I realised I did not answer the last part of the question. The IDs not resetting is both an app-wide decision and a bug in the implementation of clear (which the intended behaviour was not documented in the UG).

After typing this out I realised that it seems much more like a feature flaw rather than a bug and will not change it.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/314#issuecomment-1494036355" expanded>

Thank you prof!! The situation is as you have described.
</panel>

</panel>


<panel type="info" header="### 19. ANDR..IKAI `@4ndrelim` (13 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: PPP Deadline**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/348" expanded>

> This task is time-sensitive. If done later than the [deadline](https://nus-cs2103-ay2223s2.github.io/website/admin/weeklySchedule.html#:~:text=for%20exact%20dates.-,Deadline%20for%20weekly%20tasks,-The%20soft%20deadline), it will not be counted as 'done' (i.e., no grace period). Reason: This is 'an early draft'; if done late, it is the 'final version' already.

I did not notice the deadline for drafting the PPP. I'm wondering if there is any penalty for missing the draft or can it be compensated with the final version?
</panel>

<panel  header="**2. :fas-info-circle: Coding Standard For Switch Statements**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/130" expanded>

The recommended form for switch statements is:
```
switch (condition) {
case ABC:
    statements;
case DEF:
    statements;
}
```
But if i wish to have a separate scope for each case statement, then the code would look something like the following:
```
switch (condition) {
case ABC: {
    statements;
}
case DEF: {
    statements;
}
}
```
Here, the closing curly braces for the last case statement is on the same level as that of the switch statement which is unpleasant to look at. I'm wondering if this in case, its fine to deviate from the coding standard (since it is just a guide) to improve readability. 
</panel>

<panel  header="**3. :fas-info-circle: Grading scripts detecting case-insensitive branch/tag names?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/53" expanded>

Hi, as i was updating my tag/branch names to align with the advised ones, i noticed branches with the same spelling but different case are treated the same (e.g 'branch-level-7' is the same as 'branch-Level-7'). 

A quick google search suggests that while git is case-sensitive, our filesystem may not be. So i'm wondering if the grading scripts would be able to detect the branches/tags regardless of case.
</panel>

<panel  header="**4. :fas-info-circle: Strict adherence to naming of increments?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/50" expanded>

I understand there will be a grading script to detect our branches and tags, suppose there is some deviation from the advised name e.g 'Level-7' instead of 'branch-level-7', will this cause issues later on with the script?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/50#issuecomment-1400492109" expanded>

Alright, so to resolve this, i simply create a new branch with the correct name, merge the incorrectly named branch into the correctly named one, without having to mess with master branch?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/50#issuecomment-1400618838" expanded>

thank you!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/53#issuecomment-1401507523" expanded>

okay thank you!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/78#issuecomment-1406818534" expanded>

@ChangGittyHub Hi, i actually had the same issue on my mac. I had both openjdk 11.0.11 (From CS2040S) and java 17..0.1 which was the default before i switched to java 11. 

On my terminal, i simply did `export JAVA_HOME='/usr/libexec/java_home -v 11.0'` and the switch was done. Naturally, you must have java 11 installed for the command to work. This [link](https://medium.com/@devkosal/switching-java-jdk-versions-on-macos-80bc868e686a) is a comprehensive but succinct guide to what i've described above, including how to check if you have the right version installed.

If you need more help, perhaps can check out this [link](https://stackoverflow.com/questions/21964709/how-to-set-or-change-the-default-java-jdk-version-on-macos) as well. It says pretty much the same thing, with some additional errors users may face.

Edit: Some issues with having backticks in backticks, note that `/usr/libexec/java_home -v 11.0` should be encapsulated in backticks instead of quotations.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/130#issuecomment-1415029630" expanded>

I see, will avoid in future instances, thanks prof! But if my existing code is similar to the latter, would it be fine leaving as such without incurring any penalty?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/130#issuecomment-1416250999" expanded>

okay thanks prof!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/198#issuecomment-1434185538" expanded>

Hi, you may want to remove the openJDK version and install Java Azul version 11 as recommended by the guideline instead. I was previously using openJDK and everything was going fine (including the GUI portion, was able to run the steps in the advisory as well) so i thought it would work out fine. Yet, i faced similar issues with building the gradle and javafx and simply couldn't find a fix for it. Eventually i decided to just remove my existing version of java and replaced it with Azul. Below are links and tutorial i used to remove my openJDK and swap to Azul in case you decide to do so as well.

[Removing existing java](https://www.youtube.com/watch?v=wwV_L3lKYYw)
[How to change / set default java](https://stackoverflow.com/questions/21964709/how-to-set-or-change-the-default-java-jdk-version-on-macos) (i used this because i had java 17 installed as well)

All the best!
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/310#issuecomment-1493565312" expanded>

Hi prof, 

> If the case sensitivity of a feature does not follow the real world, it is considered a feature flaw. The best you can do in v1.4 is to document this behaviour clearly in the UG.

so as long as we clearly acknowledge our current limitations in the UG, we won't be penalized for it? Because i'm sure issues like this will arise again in the actual PE.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/348#issuecomment-1500798738" expanded>

thank you
</panel>

</panel>


<panel type="info" header="### 20. AN C..YANG `@anchengyang` (13 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Error initializing QuantumRenderer: no suitable pipeline found java.lang.RuntimeException:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/215" expanded>

![image](https://user-images.githubusercontent.com/65301406/220041203-39904c6d-0455-4d9a-9794-c554c0e44edb.png)

Is anyone facing the same problem? Not quite sure what the error is.
</panel>

<panel  header="**2. :fas-info-circle: How to fix javafx.fxml.LoadException**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/118" expanded>

![image](https://user-images.githubusercontent.com/65301406/215972745-043feb9a-33e4-4276-8d48-63332db95bc1.png)
How can I fix this error?
My MainWindow.java file is the same as the one in the tutorial part 4 [here](https://se-education.org/guides/tutorials/javaFxPart4.html#using-controllers)

My code currently looks like [this](https://github.com/anchengyang/ip/tree/branch-Level-10) with the error
</panel>

<panel  header="**3. :fas-info-circle: CheckStyle for import statements**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/106" expanded>

Attached is the checkstyle error that I am getting. Does anyone know why?
![image](https://user-images.githubusercontent.com/65301406/215716109-3b941962-8b0b-45ed-875a-ccc62c63a5e6.png)

This is my code for TaskList.java
![image](https://user-images.githubusercontent.com/65301406/215716289-03bebd4b-537a-42f8-b79e-0635ffda706a.png)

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/41#issuecomment-1399537295" expanded>

If we save as serialized objects, must we save the object after every command or must we save the object only when the user types in the bye command to quit?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/106#issuecomment-1411359754" expanded>

Thanks @wz2k and @hingen 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/118#issuecomment-1413057943" expanded>

thanks so much @daitenshionyan @Junyi00 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/215#issuecomment-1439410572" expanded>

@damithc I'm not sure if the issue for mine is resolved because when I run my application it works fine. This error was from the smoke testing bot and I don't know how to achieve this error or what is causing it.

My code can be found [here](https://github.com/anchengyang/ip)

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/215#issuecomment-1439420590" expanded>

@damithc im using windows actually
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/215#issuecomment-1439433524" expanded>

@gohyongjing thanks for downloading and helping me to check!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/215#issuecomment-1439450674" expanded>

> Are you building the project from gradle in WSL2? That might be what's causing the issue because I faced the same errors but it worked fine once I switched to building the project from windows.

ohh but currently i build the project on windows in intellij. According to @damithc its failing the linux one
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/215#issuecomment-1439452658" expanded>

> > I'm using windows, and the jar file seems to work properly for my computer
> 
> The JAR passed the smoke test on Windows and Mac. The error is specific to Linux.

How can I resolve this issue?
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/215#issuecomment-1439513956" expanded>

> I have your v1.1 release (from 11 mins ago). I run Arch Linux. it is working on Arch Linux

Wah thank you sir so I guess the issue is fixed now

@szejiancheng What i changed can be found [here](https://github.com/anchengyang/ip/commit/c94962c958fd671c439a8a0632e6dbcdd4d3b33a)
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/215#issuecomment-1439569612" expanded>

> woah @anchengyang just to be clear, you removed the javafx dependency in your build.gradle file and that solved the problem?

That and I also added the other stuff in dependencies to make sure the javafx is on version 11 and can run on linux, windows and mac. I think? Because previously the javafx {} was version 19 I think cos I followed some random tutorial online.
</panel>

</panel>


<panel type="info" header="### 21. ARKA..AUNG `@arkarsg` (13 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Fixing bug in Ui by refactoring Ui implementation**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/328" expanded>

Our application has multiple tabs for different views implemented by TabPane which has a StackPane containing a ListView (ie multiple tabs of how AB was implemented, put simply).

We have the following command `tab t/TAB` which switches to view to `TAB` that works as intended. However, this breaks when user uses mouse followed by `tab` command or vice versa, where different StackPanes overlap.

Example of “bug” with overlapping views when users use a mix of CLI and mouse-click:
![Screenshot 2023-04-04 at 11 52 39 PM](https://user-images.githubusercontent.com/84555527/229848222-565a1ad9-f61a-4a00-827d-93fb13c93622.png)

I suspect that this unintended behaviour maybe due to our implementation where `TabPane extends UiPart&gt;Region>` while `Tab` is declared within the `TabPane` (without its own fxml file), causing `Tab` to have a different Controller vs TabPane’s controller from `T extends UiPart&gt;Region>`.

I would like to clarify if this is considered a bug or a feature flaw, and which of the following “fix” should be recommended:
1. Clearly state in the UG to only use CLI command.
2. State in the UG and set tab as unclickable (technically a Ui change?)
3. Refactor Tab to extend `UiPart&gt;Region>` (with additional fxml files) so that both mouse click and CLI command is handled with the same Controller.

</panel>

<panel  header="**2. :fas-info-circle: Auto-scroll on long inputs with JavaFX**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/174" expanded>

I have been making some minor UI changes for GUI and I faced the following issue.

### Issue
When there are long chunks of text displayed on the GUI, `ScrollPane` does not snap to the bottom.
#### Before
![Screenshot 2023-02-13 at 12 29 04 AM](https://user-images.githubusercontent.com/84555527/218323581-3d3c3c36-f07a-4265-ae24-dc6706362077.png)

#### After
![Screenshot 2023-02-13 at 12 29 34 AM](https://user-images.githubusercontent.com/84555527/218323603-b03f38d2-681a-4f83-8408-95e437409eeb.png)

The _after_ screenshot is immediately after I have typed in another command, as you can see from the `Image` of `userDialog`. 
Note: scroll bar was set to not show in this example.

### Expected Behaviour
For `ScrollPane` to immediately snap to the bottom of `DukeDialog`, so that user does not have to scroll down after every response.

### What I have tried
In `MainWindow`, the following is present, as per the tutorial:
``` java
scrollPane.vvalueProperty().bind(dialogContainer.heightProperty());
```

Following some posts on StackOverflow, I have also tried hardcoding the height property to `1.0d` but this does not work either.
I have also tried changing `max_height` and `pref_height` attributes via sceneBuilder.

### MainWindow FXML
``` fxml
<?xml version="1.0" encoding="UTF-8"?>

<?import javafx.geometry.Insets?>
<?import javafx.geometry.Point3D?>
<?import javafx.scene.control.Button?>
<?import javafx.scene.control.ScrollPane?>
<?import javafx.scene.control.TextField?>
<?import javafx.scene.layout.AnchorPane?>
<?import javafx.scene.layout.VBox?>
<?import javafx.scene.text.Font?>

<AnchorPane maxHeight="-Infinity" maxWidth="-Infinity" minHeight="-Infinity" minWidth="-Infinity" prefHeight="600.0" prefWidth="400.0" xmlns="http://javafx.com/javafx/19" xmlns:fx="http://javafx.com/fxml/1" fx:controller="duke.gui.MainWindow">
  <children>
    <TextField fx:id="userInput" layoutY="558.0" onAction="#handleUserInput" prefHeight="41.0" prefWidth="310.0" promptText="The Duke is listening..." style="-fx-background-radius: 10; -fx-background-insets: 5; -fx-min-height: 40; -fx-padding: 10;" AnchorPane.bottomAnchor="1.0">
         <font>
            <Font name="Menlo Regular" size="13.0" />
         </font>
      </TextField>
    <Button fx:id="sendButton" alignment="CENTER" contentDisplay="CENTER" layoutX="310.0" layoutY="562.0" mnemonicParsing="false" onAction="#handleUserInput" prefHeight="33.0" prefWidth="86.0" style="-fx-background-radius: 15; -fx-background-color: #3D5A80;" text="Send" textAlignment="CENTER" textFill="WHITE">
         <font>
            <Font name="Menlo Regular" size="13.0" />
         </font>
      </Button>
    <ScrollPane fx:id="scrollPane" hbarPolicy="NEVER" hvalue="1.0" prefHeight="559.0" prefWidth="400.0" vbarPolicy="NEVER" vvalue="1.0">
      <content>
        <VBox fx:id="dialogContainer" fillWidth="false">
         </VBox>
      </content>
    </ScrollPane>
  </children>
</AnchorPane>
```

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/6#issuecomment-1383103778" expanded>

At the bottom of the [link](https://nus-cs2103-ay2223s2.github.io/website/admin/participation.html#where-to-find-your-participation-marks-progress), it states that it will start tracking from week 3 onwards 👍
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/18#issuecomment-1387148935" expanded>

For Shell scripts `.sh` files, you can try `chmod +x sample.sh` followed by `./sample.sh`

.bat should be similar too
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/20#issuecomment-1400392876" expanded>

Since we are refactoring some parts of our codes this week, I'd like to share some changes that I made to handle errors and be clean(er). Initially, I was using a switch-case block nested in a try-catch block. Something like this:

``` java     
try {
            switch (...) {
                case "list":
                    showAll();
                    break;
                case "todo":
                    addTodo(...);
                    break;
                    // other cases not included
                default:
                    throw new InvalidCommandException("Invalid Command! Try: " +
                                                    "[list, todo, deadline, event, mark/unmark]");
            }
        } catch (InvalidCommandException e) {
            System.out.println(e.errorMessage);
        }
```

Other exceptions are abstracted away in the methods themselves. However, if we want to grow in our features, the switch-case/ if-else block would grow. I found a relatively simple solution to handle this with a HashMap with the Consumer interface from `java.util.function`.

```java

       private static Map<String, Consumer<String[]>> COMMANDS = new HashMap<>();

        private void populateCommands() {
                COMMANDS.put("todo", (tokens) -&gt; addTodo(tokens));
                // ...
        }

       // in main (or in your handler)
       try {
                COMMANDS.get(cmd).accept(cmdString);
        } catch (NullPointerException e) {
                // handle it
        }
```
In my example, Consumer takes in a `String[]` because this is how I parsed my command inputs. It can be different.

For me, I find it cleaner without over-engineering it. Currently, I only have a simple driver and a handler. It's also easier to add a feature (one liner in `populateCommands` and the method itself).

Reference: [StackOverflow](https://stackoverflow.com/questions/47287222/store-and-call-method-from-a-hashmap), [my repo](https://github.com/arkarsg/ip/blob/master/src/main/java/MyDuke.java)

</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/41#issuecomment-1401476356" expanded>

I feel that there are some merits in storing the commands of the user. For example, in Terminal, we can access previous command lines. Storing commands (maybe with temp files) would easily support this feature although it may not be in the design scope of this module.

Currently, my approach is to save at the end of the session (immediately after the user types "bye") with the Serializable interface. Initially, I thought of serialising each task and then loading it. However, I realised that an even simpler alternative is to seralize the entire Task ArrayList (or other similar implementation). Then, we just need to simply assign the ArrayList that is loaded for a new Duke session.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/71#issuecomment-1405960990" expanded>

If we consider user experience a priority, a very common design approach is `save on command` or `auto-save`.
`Save on command` gives users the most flexibility as they decide when to save. It is also more time efficient than saving after every change. (I guess this is also similar to `commit`)

However, from user stories of Adobe software or Microsoft office, it is very painful for users to lose their progress when it crashes without a recent save. Therefore, I also suggested `auto-save` where the TaskList is saved after a certain period on the clock.


</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/81#issuecomment-1407559239" expanded>

> As the others mentioned above, I handled only the required cases as it would be very difficult to flexibly accept different formats (Such as `1-2-2000`: without a fixed format, we would not know if it is `1st Feb` or `2nd Jan`). I only accepted `yyyy-mm-dd tttt` and `yyyy-mm-dd tt:tt` and made a check for whether the colon exists in the time.
> 
> I also considered to allow users to pass in their own required format such as `deadline homework /by 01-02-2024 /format dd-mm-yyyy` but this seems to be too verbose, even for fast typists.
> 
> I think the most flexibilty we could give is to also accept dates with the month format `mmm`, such as `jan`, `feb` etc, which could be done by manually checking

There is `java.time.format.DateTimeFormatter`. Following that I have

```  java
DateTimeFormatter IN_FORMT = DateTimeFormatter.ofPattern("dd/MM/yyyy hhmm");
DateTimeFormatter OUT_FORMT = DateTimeFormatter.ofPattern("dd LLL, hh:mma");
...
// then to parse
LoacalDateTime deadline = LocalDateTime.parse(deadline, IN_FORMAT);

// to output
deadline.format(OUT_FORMAT);
```
I used this to display a more readable line. In my case, it is displaying `"02 Feb, 11:30am"` for the input `02/02/2023 1130`.

You might need to read the documentation to see what abbreviation to use (ie LLL instead of MMM).
I am sure the `IN_FORMAT` can be changed to accept `"02 Feb 2023, 11.30am"` as well for ease of typing/ readability and let `LocalDateTime` parse rather than checking each month.

</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1423526983" expanded>

![Screenshot 2023-02-09 at 10 23 45 AM](https://user-images.githubusercontent.com/84555527/217701365-7bc546ca-a03e-44bc-8510-27d88ffd6e9e.png)


Simple implementation with minor touch ups and padded dialogs (eyeball'ed).
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/171#issuecomment-1427078175" expanded>

If you are using VSCode, try running through Gradle.

I face Exceptions when I run through `Launcher.java` but works through `run` in Gradle.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/174#issuecomment-1428034371" expanded>

Interesting! It works now. Thank you.
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/185#issuecomment-1430914285" expanded>

I tried your `jar` file and has the behaviours as follows:

### Creates a data file
<img width="740" alt="Screenshot 2023-02-15 at 4 05 44 PM" src="https://user-images.githubusercontent.com/84555527/218968836-54add578-fb0e-4999-882a-bc5798ca9fc6.png">

### Shows quit message instead of `The handle is invalid`
![image](https://user-images.githubusercontent.com/84555527/218969090-14213310-7c50-4b72-97b8-428a38c8111a.png)

I also realised that some commands are still being printed on `System.out.println`

`The handle is invalid` is usually thrown by `IOException` so maybe that can be a start.
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/328#issuecomment-1496254828" expanded>

Thank you Prof for the quick reply!
</panel>

</panel>


<panel type="info" header="### 22. TAN ..SEAN `@seanfirefox` (13 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Declaration of code reuse in Canvas Quiz**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/357" expanded>

Asking for my teammates about the declaration of code reuse:

I have reused code from AB4, so I checked the option for 
```
I reused some content and gave credit to the original source in all cases of such reuse, as required by the module policies.
```
However, my teammates did not reuse code, so do they still check the option above?

Also, does using external libraries like `Joda-Time` consider as reused code as well such that the above option needs to be checked?
</panel>

<panel  header="**2. :fas-info-circle: Question about referencing code reuse (Follow-up from #350)**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/354" expanded>

I have copied and edited over multiple files from [AB4](https://github.com/se-edu/addressbook-level4) for GUI tests. Other than referencing `AB4` in the `DG`, `index.md` and declaring in the Canvas survey, I have also added it in the `JavaDocs` as shown below.

Is this enough referencing? 
![image](https://user-images.githubusercontent.com/35872524/230740456-6cc2f53f-1718-4db7-a670-c8853afbd78e.png)

</panel>

<panel  header="**3. :fas-info-circle: Anyone tried to do GUI tests and encountered Illegal Reflective access errors**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/350" expanded>

I attempted to use the GUI tests from [AB4](https://github.com/se-edu/addressbook-level4) and encountered illegal reflective access errors, presumably from [testfx](https://github.com/TestFX/TestFX/issues/553).

![image](https://user-images.githubusercontent.com/35872524/230708539-5fe4660e-9abf-4a2f-ac48-c72aa4de02c1.png)

Anyone knows a workaround it? I have tried to set in `build.gradle` to allow this to pass but without any success.

```
test {
    useJUnitPlatform()
    finalizedBy jacocoTestReport
    systemProperties = [
            'testfx.robot': 'glass',
            'testfx.headless': 'true',
            'prism.order': 'sw',
            'prism.text': 't2k',
    ]
    jvmArgs = [
            '--add-opens', 'javafx.graphics/javafx.scene=ALL-UNNAMED',
            '--add-opens', 'javafx.controls/javafx.scene.control=ALL-UNNAMED'
    ]
}
```
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/204#issuecomment-1436032115" expanded>

Hi! For my Mac, somehow the java version from Azul was unable to compile the .jar file, and had the exact same error as you.
Instead, I used the `liberica` version that can be downloaded using Intellij.
You can go to `Project Structure > Project > SDK > Add SDK > Download JDK` and try.

<img width="513" alt="Screenshot 2023-02-20 at 10 45 45 AM" src="https://user-images.githubusercontent.com/35872524/219997826-4d6c1519-3d72-48a8-a4fd-38efad8fda84.png">

Hope this helps if the Azul version is not working.

If it still does not work, you can try swapping to all the different java versions provided by Intellij and test one by one, which was how I found the `liberica` version to be working for my Mac M1.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/229#issuecomment-1449163695" expanded>

@Zhongli5712 your duke.jar works on Arch Linux, just that the `Type your command` appears as a editable text rather than a hint. Not sure if that was intended.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/229#issuecomment-1449218392" expanded>

No problem. By editable text I mean that I can delete the `Type your command` text. If you want to show something indicating where to type, maybe you can try [hints](https://stackoverflow.com/questions/34069030/how-to-add-hint-text-in-a-textfield-in-javafx) instead.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/298#issuecomment-1491170845" expanded>

I have encountered the same problem too. Might be Github server issues.
![image](https://user-images.githubusercontent.com/35872524/229001264-811fc32d-7893-4322-b178-a161d6f0d539.png)

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/320#issuecomment-1495876539" expanded>

2 possible factors to consider other than hingen's response:

1. Did you possibly leave out your code when doing merge conflicts? It can be easy to miss clicking the :heavy_check_mark:  button instead of the :x:  button when on Intellij if you do merges by using `git merge master` from the master from your own fork.
2. Did you branch out from another branch when calling `git checkout -b new-branch` instead of master? Not sure if that could result in unintended consequences but making changes on the original branch can cause changes to spill over to newer branch.

Also, did you try to call `git log` to see if your previous commits have disappeared from your local when you encounter this problem? 

Another way is to check your PR and see if the previous commits are registering and if your later commits have somehow deleted your work too.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/350#issuecomment-1500899976" expanded>

Never mind, I have resolved it by upgrading all `testfx` and `monocle` dependencies to the latest versions.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/350#issuecomment-1500968594" expanded>

Just for more sharing, I used testFxVersion `4.0.16-alpha` and used the `monocle` version below.
```
testImplementation group: 'org.testfx', name: 'openjfx-monocle', version: 'jdk-12.0.1+2'
```

Also ended up with the below code for my `build.gradle`.
```
test {
    useJUnitPlatform()
    finalizedBy jacocoTestReport
    jvmArgs "-Dheadless=${project.hasProperty('headless') ? project.headless : false}"
    systemProperties = [
            'testfx.robot': 'glass',
            'testfx.headless': 'true',
            'prism.order': 'sw',
            'prism.text': 't2k',
    ]
}
```
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/354#issuecomment-1501046301" expanded>

Thanks for the clarification! 
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/357#issuecomment-1501075302" expanded>

@damithc Prof, so for using 3rd party libraries, is it everyone who uses an object from it needs to declare reuse or only the person who imports it needs to declare reuse in Canvas? 
</panel>

<panel  header="**13 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/357#issuecomment-1501085099" expanded>

Thanks for the clarification.
</panel>

</panel>


<panel type="info" header="### 23. ZHU .. YAO `@ZhuLeYao` (12 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: CS2103 disappeared from canvas**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/371" expanded>

How do we submit tp video or is this a glitch on canvas' side?
</panel>

<panel  header="**2. :fas-info-circle: Why is my forking and tracking not detected on ip progress board?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/224" expanded>

<img width="248" alt="Screenshot 2023-02-23 at 11 24 29 PM" src="https://user-images.githubusercontent.com/87946521/220951236-1c8ee703-9567-4b53-b743-a2c5cbc252da.png">

</panel>

<panel  header="**3. :fas-info-circle: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/220" expanded>

I am facing errors similar to #215 but this is already happening during the tutorial. 
However, the error only mentions  "Caused by: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found"

I followed the tutorial for gradle and set up accordingly. I have also done the following:
1. changed my build.gradle application mainClassName to "duke.main.Launcher"
2. run > configurations > application changed build and run main class to duke.main.Launcher
3. removed main method from duke.java

StackOverflow mentioned either the modular path is pointed wrongly or I have the wrong javaFX downloaded e.g. 32bit or bit. However, I am using gradle so I did not download any javaFx and I believe my above is changing the modular path correctly. 

Thanks in advance.

</panel>

<panel  header="**4. :fas-info-circle: Editing commit message after pushing**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/157" expanded>

It is not my latest commit but it is my latest commit of another branch. Will it be a good idea to check out the branch of the message I want to edit, go under the repository and select interactive rebase? Will the edit cause me to just rebase this branch onto itself or will my latest commit in other branches be rebased into this branch too? Also there is a noop message when I select interactive rebase, not sure what it means
</panel>

<panel  header="**5. :fas-info-circle: Checking if environment is compatible using addressbook.jar on Mac**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/1" expanded>

Mac terminal showed this in the first 4 lines.

Loading library prism_es2 from resource failed: java.lang.UnsatisfiedLinkError: Can't load library: /Users/leyaozhu/.openjfx/cache/11/libprism_es2.dylib
java.lang.UnsatisfiedLinkError: Can't load library: /Users/leyaozhu/.openjfx/cache/11/libprism_es2.dylib

Does this mean my OS is incompatible?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/1#issuecomment-1378677171" expanded>

Yes, I have switched to the correct Java version. 

(base) leyaozhu@Les-MacBook-Air Downloads % java -version
java version "11.0.17" 2022-10-18 LTS
Java(TM) SE Runtime Environment 18.9 (build 11.0.17+10-LTS-269)
Java HotSpot(TM) 64-Bit Server VM 18.9 (build 11.0.17+10-LTS-269, mixed mode)

As the instructions mentioned that the advisory is applicable only if unreadable, I am unsure if the failures also mean that the advisory is applicable to me.

</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/1#issuecomment-1378711597" expanded>

Yep, after I run it in terminal 

(base) leyaozhu@Les-MacBook-Air Downloads % java -jar addressbook.jar

And I get the following for the first 4 lines

Loading library prism_es2 from resource failed: java.lang.UnsatisfiedLinkError: Can't load library: /Users/leyaozhu/.openjfx/cache/11/libprism_es2.dylib
java.lang.UnsatisfiedLinkError: Can't load library: /Users/leyaozhu/.openjfx/cache/11/libprism_es2.dylib

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/1#issuecomment-1378936408" expanded>

okay thank you!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/157#issuecomment-1426962178" expanded>

Thank you so much! Based on your first paragraph, I tried git commit amend instead as I realised it works for the latest commit of the branch too instead of the latest commit of the entire repo. Read up on the tutorial too and it was useful!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/220#issuecomment-1437891315" expanded>

@damithc 
- I am using macOS Ventura version 13.0.1
- Does this mean whether I am using Intellij or terminal commands? If so, I am running the application on Intellij, specifically the launcher file.

Here is my build.gradle:

```java
plugins {
    id 'java'
    id 'application'
    id 'com.github.johnrengelman.shadow' version '5.1.0'
}

repositories {
    mavenCentral()
}

dependencies {
    String javaFxVersion = '11'

    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'linux'

    testImplementation group: 'org.junit.jupiter', name: 'junit-jupiter-api', version: '5.5.0'
    testRuntimeOnly group: 'org.junit.jupiter', name: 'junit-jupiter-engine', version: '5.5.0'
}

test {
    useJUnitPlatform()

    testLogging {
        events "passed", "skipped", "failed"

        showExceptions true
        exceptionFormat "full"
        showCauses true
        showStackTraces true
        showStandardStreams = false
    }
}

application {
    mainClassName = "duke.main.Launcher"
}

shadowJar {
    archiveBaseName = "duke"
    archiveClassifier = null
}

run{
    standardInput = System.in
}
```

Here is my Duke.java:
```java
package duke.main;

import java.io.*;

import javafx.application.Application;
import javafx.scene.Scene;
import javafx.scene.control.Label;
import javafx.stage.Stage;

/**
 * Runs the app.
 */
public class Duke extends Application {
    private Storage storage;
    private TaskList tasks;
    private Ui ui;
    private static final String filePath = "data/tasks.txt";

    /**
     * Initialises Storage, TaskList and Ui.
     * Previous tasks are loaded up.
     * Loading error will be shown if file cannot be found/ generated.
     *
     * @param filePath file path of text file containing tasks.
     */
    public Duke(String filePath) {
        ui = new Ui();
        storage = new Storage(filePath);
        try {
            tasks = new TaskList(storage.loadTxtFile());
        } catch (IOException e) {
            ui.showLoadingError(e.getMessage());
            tasks = new TaskList();
        }
    }

    //public static void main(String[] args) {
    //    new Duke("data/tasks.txt").run();
    //}

    /**
     * Runs the app.
     */
    public void run() {

        ui.printGreetingMessage();

        boolean saidBye = false;
        while (!saidBye) {
            String command = ui.getCommand();
            Parser parser = new Parser();
            parser.parse(command, ui, tasks, storage);
        }
    }

    @Override
    public void start(Stage stage) {
        Label helloWorld = new Label("Hello World!"); // Creating a new Label control
        Scene scene = new Scene(helloWorld); // Setting the scene to be our Label

        stage.setScene(scene); // Setting the stage to show our screen
        stage.show(); // Render the stage.
    }

}
```

Here is my Launcher.java:
```java
package duke.main;

import javafx.application.Application;
/**
 * A launcher class to workaround classpath issues.
 */
public class Launcher {
    public static void main(String[] args) {
        Application.launch(Duke.class, args);
    }
}
```


</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/220#issuecomment-1437950445" expanded>

The issue is settled but I would like to share the method.

Previously, I had brought up the issue in #1 of an error in my terminal instead of an unreadable GUI, which I thought was a different issue. The address book.jar works now according to the instructions. I have changed in intellij to zulu 11.0.18 for the below settings:
1. project structure
2. run>edit configurations
3. settings for maven runner
4. settings for gradle

However, now there is the error of "Caused by: java.lang.NoSuchMethodException: duke.main.Duke.<init>()"

<img width="1311" alt="Screenshot 2023-02-21 at 2 54 39 PM" src="https://user-images.githubusercontent.com/87946521/220270165-467a055c-2e06-4245-87ac-d581af562c74.png">

<img width="1318" alt="Screenshot 2023-02-21 at 2 54 30 PM" src="https://user-images.githubusercontent.com/87946521/220270200-25048fa0-7eb5-4ca7-9563-9acbfed4d83d.png">

<img width="1040" alt="Screenshot 2023-02-21 at 2 53 03 PM" src="https://user-images.githubusercontent.com/87946521/220270326-eeffe7eb-71ac-4beb-9123-4d305f802342.png">
<img width="939" alt="Screenshot 2023-02-21 at 2 53 40 PM" src="https://user-images.githubusercontent.com/87946521/220270332-33fb62e1-c5bb-40b4-b13c-268302c65b56.png">

From here, I saw past cs2103 forums that someone solved this by adding another duke constructor
public Duke() { }

This solved the issue finally even though I already had a Duke constructor.

Thank you @damithc for your help.


</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/371#issuecomment-1506444699" expanded>

Yes, the submission is successful. Thank you
</panel>

</panel>


<panel type="info" header="### 24. LO H.. YIN `@lhy-hoyin` (12 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Import vs Import Static**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/272" expanded>

Is there a preference/rule/standard on when to use `import xxx` vs when to use `import static xxx.yyy`?

For example, in [`AddCommandTest`](https://github.com/nus-cs2103-AY2223S2/tp/blob/master/src/test/java/seedu/address/logic/commands/AddCommandTest.java)
``` java
import static java.util.Objects.requireNonNull;
import static org.junit.jupiter.api.Assertions.assertEquals;
import static org.junit.jupiter.api.Assertions.assertFalse;
import static org.junit.jupiter.api.Assertions.assertTrue;
import static seedu.address.testutil.Assert.assertThrows;

import java.nio.file.Path;
import java.util.ArrayList;
import java.util.Arrays;
import java.util.function.Predicate;

// more imports below

public class AddCommandTest {

    @Test
    public void constructor_nullPerson_throwsNullPointerException() {
        assertThrows(NullPointerException.class, () -&gt; new AddCommand(null));
    }

    // more tests

}
```

I believe that if `import seedu.address.testutil.Assert` is used instead, then the test would look like this
```java
@Test
    public void constructor_nullPerson_throwsNullPointerException() {
        Assert.assertThrows(NullPointerException.class, () -&gt; new AddCommand(null));
    }
```
</panel>

<panel  header="**2. :fas-info-circle: Removal of previously implemented Extras**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/70" expanded>

I am currently refactoring my code and had made it such that my previously implemented `A-Enums` has been "un-implemented".  Which of the following should I do?

(A) Remove the `A-Enums` tag from my repo.
Reasoning: I no longer have this implemented in my current code.

(B) Leave the `A-Enums` tag as it is.
Reasoning: My previous commits will be able to show that I have learnt and knows how to use enums. (Implementation can be seen via commit history.)

</panel>

<panel  header="**3. :fas-info-circle: Switch case Fallthrough comment**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/34" expanded>

In the [Java Coding Standard](https://se-education.org/guides/conventions/java/intermediate.html), under [Layout](https://se-education.org/guides/conventions/java/intermediate.html#layout) (switch case), it mentioned
> The explicit `//Fallthrough` comment should be included whenever there is a case statement without a break statement.

using the example of
```java
switch (condition) {
case ABC:
    statements;
    // Fallthrough
case DEF:
    statements;
    break;
...
}
```

Currently. in my code, im doing this
```java
switch (condition) {
case ABC:
case DEF:
    statements;
    break;
}
```

Is it really necessary for `//Fallthrough` when it is obviously falling through, since there are no statements between `case ABC:` and `case DEF:`?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/5#issuecomment-1383336079" expanded>

> 

I believe that the `.gitignore` file is in the **same directory** as the `.git` folder, rather than being inside the `.git` folder.

Think of the following structure:
```
...\MyRepo\.git\...
...\MyRepo\.gitignore

...\MyRepo\README.md
...\MyRepo\CONTRIBUTORS.md
...\MyRepo\text-ui-test\...
...\MyRepo\src\...
...\MyRepo\bin\...
...\MyRepo\...
```
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/34#issuecomment-1398208942" expanded>

In case you are wondering why I have 2 cases without any statements in-between, I am currently doing this
```java
switch (currentState ) {
case MARK:
case UNMARK:
     ... ... // very similar code for mark and unmark

    if (currentState == State.MARK)
        System.out.println("Nice I've marked the task(s) as done:");
    else 
        System.out.println("OK, I've marked the task(s) as not done yet:");
    ... ... // very more similar code
}
```
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/34#issuecomment-1398211322" expanded>

And to adhere to the coding styling, would it be alright for me to do 
``` java
case ABC: //Fallthrough
case DEF:
    ...
 ```
 instead of
``` java
case ABC: 
    //Fallthrough
case DEF:
    ...
 ```
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/69#issuecomment-1405047473" expanded>

You should probably disable the auto-formatting. Otherwise, when the IDE does it for you, it becomes you that violate the coding standard stated out for this module. 

If you know how to, could you indicate which IDE you are using? And the steps to disable the auto-formatting?
I believe this would also help others that are facing the same issue as you.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/71#issuecomment-1405940537" expanded>

Initially I was thinking that there might be a situation where the user want to exit without saving. (But "saving" whenever tasklist changes makes this impossible.) 
Now that I think about it, perhaps we can have different save files. 

> For example, we can have a `save.txt` (when user saves manually, or upon exiting) along with a `auto-save.txt` (saves whenever the tasklist is modified).

To point to the issue of inefficiency (if the tasklist is very huge and would take very long to save all the tasks), we can consider using `auto-save.txt` to store "how it change" instead of "what it looks like after its changed." This means that regardless of how big the tasklist is, it will merely take a small amount time to write how the user changed the tasklist (e.g. add new task, delete task, etc).
> Inspiration: how Git/Github works (recording the changes instead of recording the multiple version of code)
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/47#issuecomment-1406076026" expanded>

Hello! It appears that your issue have been resolved :D
Perhaps @Tempura-Person can mark this issue as `Close as completed`. Thank you!
(But it you think your question is still not answered, perhaps you can reiterate what you would like to clarify.)
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/31#issuecomment-1406087572" expanded>

I have a similar method too, which creates and writes to directories/files that are relative to where the `JAR` file is.
Another point I like about it is that I don't have to worry if the directory exists, Since it also create them for me.

```java
private void writeToFile(String filePath, String fileContent) {
    try {
        Path f = Paths.get(filePath);
        Files.createDirectories(f.getParent()); // Create directory (if not exist)
        if (!Files.exists(f)) {
            Files.createFile(f); // Create non-existing file
        }
        Files.writeString(f, fileContent); // Write to file
    } catch (IOException e) {
        throw new RuntimeException(e);
    }
}
```
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/109#issuecomment-1411423918" expanded>

Hello! It appears that your issue have been resolved 😄

Perhaps @ezeAng  can mark this issue as Close as completed. Thank you!

(But it you think your question is still not answered, perhaps you can reiterate what you would like to clarify.)
</panel>

<panel  header="**12 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/114#issuecomment-1411433262" expanded>

I know that @Irminrics have closed this issue, but I wanted to throw in my view since it seems slightly different from the the rest of the suggested usage.

So what I did was similar to how `public static void main(String ... args)` designed to be used. Essentially, it allows the end user to pass parameter when launching the application. What I did was to use to to allow user to set some flags to "control" the behavior of the program initialization.

```java
public static void main(String ... args) {
    // Process varargs for flags
    ArrayList<Flag> flags = processVarArgs(args);

    if (!flags.contains(Flag.SOME_CUSTOM_FLAG)) {
        // Do something as accordingly
    }

    // ...
}
```

What you use for the flags depends on how your Duke is implemented, and how you (intend) to use it. For me, I intend to make it such that it can have separate `TaskList` (e.g. to allow user to categorize their tasks). So I could have a ``--open "tasklist-name" flag to automatically open that the save file for that specific `TaskList`.
</panel>

</panel>


<panel type="info" header="### 25. ERIC..QUAN `@shittake` (11 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Product User Guide and Screenshot not Displayed**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/211" expanded>

Hi everyone,

As per the screenshot below, I believe I had followed all the instructions required for submission. However, it has been more than 24 hours and I still do not see my Ui.png and screenshot displayed. Did anyone face a similar issue and has it resolved? Thank you!

![image](https://user-images.githubusercontent.com/40803540/219947248-e75ce95a-3f7e-4f1b-8ed6-04779dda8a69.png)

</panel>

<panel  header="**2. :fas-info-circle: JavaFX not bundled into .jar file created**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/160" expanded>

Hi everyone, 

I have followed the instructions in both [here](https://se-education.org/guides/tutorials/gradle.html#creating-a-jar-file) and in [here](https://openjfx.io/openjfx-docs/#gradle), but I am still not able to run my .jar file due to the same error `JavaFX runtime components are missing, and are required to run this application`. I understand this means that my JavaFX libraries are not bundled inside, but I am unsure what else I can do. I will really appreciate if someone who has faced a similar issue who can enlighten me on this, thanks!

I also have the error message: `Project : => no module-info.java found` every time I run my program locally. I'm not sure if this is a related issue, or a completely different issue.

Here is my [github repository](https://github.com/shittake/ip). Thanks in advance!
</panel>

<panel  header="**3. :fas-info-circle: Issues when trying to import javafx**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/121" expanded>

I am trying to setup javafx inside my code currently, and keep facing the following issue where I cannot import any of the symbols. Initially, it kept giving the error message `Error: JavaFX runtime components are missing, and are required to run this application` which I managed to fix by following the instructions under the "If you are not using Gradle" section. However, I still keep being unable to import the symbols as shown in the image below. Is anyone else facing a similar issue too?
![image](https://user-images.githubusercontent.com/40803540/216086257-aac526d9-7f4f-475c-b6a9-56d657e4c52c.png)


Additionally, I tried copying the code from the tutorial as shown:
``` java
import javafx.application.Application;

/** 
 * A launcher class to workaround classpath issues.
 */
public class Launcher {
    public static void main(String[] args) {
        Application.launch(Duke.class, args);
    }
}
```
but I keep getting the following error message when I attempt to run the Launcher class:
![image](https://user-images.githubusercontent.com/40803540/216087177-7597acd1-9833-46a2-8792-6fb6232edeef.png)

As I followed the tutorial sequentially, I think the error could come from not being able to import the `Application` module in the first place as mentioned above. Any help would be appreciated, thanks!
</panel>

<panel  header="**4. :fas-info-circle: Execution failed and CreateProcess Error after merging branch with Gradle**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/46" expanded>

After merging the branch with Gradle, closing the IDEA project and deleting the .idea folder, before opening up the project again as mentioned in https://se-education.org/guides/tutorials/gradle.html, I firstly faced the issue where it says that my Duke class is outside the scope of my root. This was resolved when I did Files -&gt; Project Structure -&gt; right click on src to make it a source in Intellij. 

Now, I can right click the Duke class and run Duke.main() as per done previously, but I get a few more errors that I am unable to resolve. The first is that "A problem occurred starting process 'command '//wsl$/Ubuntu/usr/lib/jvm/java-11-openjdk-amd64/bin/java'' while the second is that "CreateProcess error=193, %1 is not a valid Win32 application". By Googling it, it seems that there is some incompatibility between the Windows version and the program. This only appeared after I tried merging the branch with Gradle in it. Any help will be appreciated!

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/46#issuecomment-1400025100" expanded>

I'm not too sure what that means - as shown in the screenshot, I click on the "Run Duke.main()" as per what I have done previously and only got this error after merging the branch  with Gradle, and deleting the .idea folder. Not too sure if deleting the .idea folder could have resulted in such issues.
![image](https://user-images.githubusercontent.com/40803540/214004395-fccc2db2-0aa8-4c88-9f8f-dc2a2715944b.png)

As of now, the error messages I get is:
![image](https://user-images.githubusercontent.com/40803540/214004760-f1cbb1c4-2af1-40e3-9b98-f04570b38bfb.png)

and 

![image](https://user-images.githubusercontent.com/40803540/214004782-c5312b3f-ee86-42c3-8224-c7c6cab49d27.png)

Wonder if anyone else face(d) the same issue too? Thank you.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/46#issuecomment-1402038704" expanded>

Thanks for your reply. I have managed to resolve this issue. For those who are facing similar issues, this is the workflow that I followed:
1. Delete my entire project folder, and re-clone from the github repository
2. Import the project once again in Intellij, and merge the branch with the gradle support
3. In Intellij, click File --> Project Settings --> Project --> Select the appropriate SDK
4. In Intellij, File --> Project Settings --> Modules --> Right-click src folder and select it as a source. Under src --> main --> java, right-click this java folder and select it as a source as well.

Issue is settled after performing the above. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/64#issuecomment-1403755329" expanded>

For me, I added a method that returns the contents of the list of tasks when called that is already tested beforehand to ensure that it is working. Then when I am trying to test if my addTask method is working, I call it on an empty list, before using assertEquals with the method that returns the contents of the list of tasks to check the new contents of my list. Since I am only testing if I am properly adding tasks to my list, I believe we can use other methods that do not return void to test the ones that do return void. Correct me if there are better ways to do it.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/81#issuecomment-1407555747" expanded>

For me, I informed the user of the only formats that are accepted by my bot, and refused to accept the date in any format other than YYYY-MM-DD or DD-MM-YYYY (with an error message provided). In future iterations though, I am planning to expand it such that other delimiters are accepted as well such as YYYY/MM/DD or YYYY MM DD. 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/121#issuecomment-1413760148" expanded>

@hingen  Thank you for your help, having a default constructor in the `Duke` class did resolve the issue. For the first issue, I have no idea how, but when I came back to it after shutting down my laptop, it worked. Thanks!
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/160#issuecomment-1426655854" expanded>

Thank you for your replies! My Java version is 11.0.17 after running `java -version`.  Thanks @MrTwit99 for pointing that out - it now works well. 
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/211#issuecomment-1435980840" expanded>

@IsabelChong thank you, that worked!
</panel>

</panel>


<panel type="info" header="### 26. MUHA..HEER `@ARPspoofing` (11 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/31#issuecomment-1398077018" expanded>

I am not a TA but what I did was to check the current working directory and then append a fixed file path if the working directory is different from /data. I am not sure if this is the correct approach, but it seems to be working for me if I run from different folders. 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/41#issuecomment-1399662570" expanded>

> If the approach is to append any command that the user enters into the save file, I wonder if it could lead to a large save file over time. Hypothetically, if a user were to use the app for several years, could the save file get very big leading to lower start-up times and also larger storage usage?
> 

This was my thought as well. So I decided to save into a way that can reuse the same parser instead of creating an entirely new parser. Also, I think it is quite strange to store multiple mark and unmark commands when it can essentially be one line. But I kind of modified the example way of storing to better suit by parser


</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/67#issuecomment-1406302593" expanded>

If I am not wrong, you can create multiple branches locally. But once you merge that newly created local branch, it will only be a commit. You have to let the remote also know that you created a new branch, and one possible way is to push the newly created local branch. Another way is to manually create in github, iirc. 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/95#issuecomment-1408418577" expanded>

@Tempura-Person in part 3, DialogBox created is not a controller. It is just another class that extends HBox. In part 4, you will need to change the DialogBox created. The change will be adding fxml functions that "controls" the fxml file. The old DialogBox does not have any capabilities to "control" the fxml file. So, I guess you are right that the DialogBox is already created, but now got to edit it to further control the fxml file. 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/114#issuecomment-1411232549" expanded>

I used it to add multiple tasks and delete multiple tasks. Seems to be useful for the user to be able to do so. 

`TaskList&gt;T> addMultipleTasks(Task... newTask) {...} `
`TaskList&gt;T> removeMultipleTasks(int... index) {...}`

</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1417208852" expanded>

This is my GUI 
<img width="364" alt="Screenshot 2023-02-05 at 5 28 17 PM" src="https://user-images.githubusercontent.com/67105732/216811436-1e06854d-6c46-4cce-b2af-a65b1918e9e5.png">

</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/146#issuecomment-1421676487" expanded>

@MrTwit99 it is because you have no seedu package in your directory. Change it to just duke.Launcher and it should work. I tested it and the jar file launches the GUI

'
application {
    mainClassName = "duke.Launcher"
}
'

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/154#issuecomment-1425018257" expanded>

Perhaps you could try the --status command to see which Daemon is giving problem and stop it using --stop? It seems that is the one causing the issue 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/146#issuecomment-1425019736" expanded>

@MrTwit99 yeap like what @SPWwj said, I did not build using intelliJ. But it seems that your issue is already resolved :)
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/231#issuecomment-1449100936" expanded>

<img width="409" alt="Screenshot 2023-03-01 at 7 51 19 AM" src="https://user-images.githubusercontent.com/67105732/222009483-bd77b58d-732a-489f-913a-c1f871b65f8d.png">
<img width="399" alt="Screenshot 2023-03-01 at 7 51 30 AM" src="https://user-images.githubusercontent.com/67105732/222009495-f004ea70-e304-41c6-830b-b2544dbd2de5.png">
<img width="401" alt="Screenshot 2023-03-01 at 7 51 43 AM" src="https://user-images.githubusercontent.com/67105732/222009516-cf7037ad-db6b-4bed-8270-83bf8abe1d27.png">

Everything looks alright!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/359#issuecomment-1501550749" expanded>

I encountered this problem as well and removing the space before {\:toc} solved it just like @Beebeeoii mentioned
</panel>

</panel>


<panel type="info" header="### 27. QIU ..NHUI `@QQH0828` (11 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: When commit the changes, somehow it will automatically convert back to the previous version**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/320" expanded>

I changed some parts of the codes, and I committed them, it will be okay.
But if I change something else and try to commit again, then some of the changes in the previous commit will show on the source tree also, and it somehow converts back to the first version.

For example, 
if I change a method name from `addPerson` to `addMoney` in the `Person` class, and I commit it, it will reflect in the codes.
Then I change something else, maybe UG, and then I want to commit it.
I found that sometimes the staged files will also have `Person` class, and it shows the changes from `addMoney` to `addPerson`. 

If I did not check properly, these changes are gone, and I need to redo them again.
I realized this problem because I think I countered this issue several times. But I still cannot figure out why. 
</panel>

<panel  header="**2. :fas-info-circle: Question about how to sort the ObservableList<T> based on the date property of T**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/296" expanded>

I have tried several ways to try to sort ObservableList&gt;T> based on the date property of T, but sometimes it is not working perfectly on the GUI, so I want to ask is there any simply way to implement it?

For example, if there is a birthday property on a person, I want to sort Observablelist&gt;Person> based on the birthday, and the person with a later birthday will be shown in the first index position in the list.

BTW, I just want to make sure that we cannot make a copy of Observablelist that is initialized by final.  
</panel>

<panel  header="**3. :fas-info-circle: The reason of  using the name for `ReadOnlyAddressBook` interface**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/291" expanded>

Hi, prof and peers,
May I ask that the reason of `ReadOnlyAddressBook` interface is used by this name is because `AddressBook` is the project name or is it a name used for storing all the person's details (readability)? My teammates and I are thinking about this question, and we have different thoughts. Regarding the UML diagram below
![image](https://user-images.githubusercontent.com/122513302/228414523-661fc961-0447-4dea-b8e1-a2493e3c88d4.png)
Model -&gt; AddressBook and UserPrefs; AddressBook -&gt; person's details.

Some of us think we should change `AddressBook` to our own project name, and some of us think should keep it.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/236#issuecomment-1453378705" expanded>

Hi @fahim-tazz, I'm your classmate at the same batch! Overall, your product works fine on my Windows 10 (both using command prompt and double-clicking the JAR file), Good job!

Here is the screenshot when I smoke-tested your product
![image](https://user-images.githubusercontent.com/122513302/222705291-8cd03259-23a0-4e19-8f27-89eedbfc0fe0.png)

Here is the text file after closing the application:
![image](https://user-images.githubusercontent.com/122513302/222705555-fa1b41b1-147b-490b-9bcc-62bf3055652a.png)

I have a few suggestions hopefully can help you improve your IP:

Firstly, maybe you can have one more command which is 'help', just simply show the command instructions, so the tester knows what can be tested and familiar with the command format such as datetime format. For example, I am not sure the datetime format at first, so I needed to try one time at least to know.  

Secondly, I noticed that the data will be saved only after the application closed. In order to not lost any data, maybe can save the data when there is a change instead of after the application closed.

Overall, I feel you did a good job with all functions work fine and your own personality! 😄


</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/291#issuecomment-1489821288" expanded>

Thanks, prof!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/296#issuecomment-1490080692" expanded>

What I did is that I straightaway sorted in that observabllelist, something like 
`internalList.sort(Comparator.comparing(Person::getBirthday));`
`FXCollections.reverse(internaList);`
Hence, I can directly get the sorted list, and it is still observablelist.
But sometimes it is not shown on the GUI  list correctly. However, it is shown on the other component correctly, such as chart.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/296#issuecomment-1495561399" expanded>

I solved this issue by using stream.limit.collect and convert back to the observablelist.
Thanks for discussion.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/320#issuecomment-1496013421" expanded>

> @QQH0828 Just to get more details, are you also using branches while doing these changes?

Hi, prof. Thank you for reading.
Yes, I was using branches while doing these changes. Basically, I was doing the changes in the same branches and did not switch to other branches.
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/320#issuecomment-1496019122" expanded>

> Probably unlikely, but I've encountered similar issues in the past when I use git on a directory that is being synced by some application (e.g. onedrive, google drive).

I also have no idea about it. 
And I just countered this issue again.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/320#issuecomment-1496026041" expanded>

> 2 possible factors to consider other than hingen's response:
> 
> 1. Did you possibly leave out your code when doing merge conflicts? It can be easy to miss clicking the ✔️  button instead of the ❌  button when on Intellij if you do merges by using `git merge master` from the master from your own fork.
> 2. Did you branch out from another branch when calling `git checkout -b new-branch` instead of master? Not sure if that could result in unintended consequences but making changes on the original branch can cause changes to spill over to newer branch.
> 
> Also, did you try to call `git log` to see if your previous commits have disappeared from your local when you encounter this problem?
> 
> Another way is to check your PR and see if the previous commits are registering and if your later commits have somehow deleted your work too.

Thanks for giving the suggestions.
I am checking the previous result in the source tree and it looks fine.
I think I did not branch out from another branch, since I always create a new branch from master only.
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/320#issuecomment-1497196624" expanded>

> Does it perhaps occur when you're doing a `git merge`?
> 
> For example, your teammate updated the `master` branch so you merge the updated `master` branch into your `feature-branch`. However, your teammate made some changes which overwrites your changes. If your `feature-branch` is very far behind on commits from the `master` branch, sometimes, git doesn't detect such changes as merge conflicts.

I have this issue even my teammates do not touch the master st all.
</panel>

</panel>


<panel type="info" header="### 28. TANG..CHUN `@alextang809` (11 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Corrupted fonts in AB3, on Mac**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/68" expanded>

I'm on a macOS 13.1. I've:
- downloaded `addressbook.jar`
- ran via the macOS terminal the command: `java -jar addressbook.jar` 
- and this was the GUI that popped up:

<img width="955" alt="Screenshot 2023-01-26 at 5 48 30 PM" src="https://user-images.githubusercontent.com/62707493/214806499-e24a4c26-ab9d-47be-a7f8-9a06efb42fca.png">

</panel>

<panel  header="**2. :fas-info-circle: Help with Permission denied (publickey). fatal: Could not read from remote repository.**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/19" expanded>

I had everything working with the Sourcetree app and git remote. But when I try to push my local changes, it fails and then gives the following prompt:
<img width="586" alt="Screenshot 2023-01-18 at 11 06 05 PM" src="https://user-images.githubusercontent.com/62707493/213207446-f9a0af1d-4155-4bc8-aeb2-9b51aa86aa11.png">

I am wondering if it is caused by my account settings in Sourcetree, as there is a warning regarding the account settings.
<img width="877" alt="Screenshot 2023-01-18 at 11 06 24 PM" src="https://user-images.githubusercontent.com/62707493/213207739-d0c7402a-f66d-4d51-8c6a-22a164205ef4.png">

And then I tried to address this issue by generating a ssh key. However it gives me another error.
<img width="465" alt="Screenshot 2023-01-18 at 11 09 14 PM" src="https://user-images.githubusercontent.com/62707493/213208056-dc698bf0-a4ef-4168-869b-f9875645fba8.png">
<img width="467" alt="Screenshot 2023-01-18 at 11 09 22 PM" src="https://user-images.githubusercontent.com/62707493/213208066-a025f7a5-9703-4809-909a-d89dece177a6.png">
I feel this issue is a bit beyond my scope at this moment because after checking the problem online, some article indicates that the problem is related to the OS.

Below is a answer from:
https://community.atlassian.com/t5/Bitbucket-questions/Help-with-quot-Permission-denied-publickey-fatal-Could-not-read/qaq-p/786747

_"Sierra or High Sierra? This is a remarkably common problem that users of those two specific revisions of macOS have, due to changes in the OS's handling of SSH identities. I suspect that most of the "related content" linked here is this exact issue.

Go to the Terminal and run `ssh-add -l` - your key should be listed there. If it isn't, run `ssh-add /path/to/key` (using the actual path to the private key, of course) and try again."_




</panel>

<panel  header="**3. :fas-info-circle: Are we supposed to directly push code from local repo to master branch?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/17" expanded>

When I was doing ip for this week locally at my IDE, I can see editing histories in SourceTree. But I am worrying that if directly push all the changes to my master branch, is it considered a not-so-good coding behavior?
</panel>

<panel  header="**4. :fas-info-circle: Issue while creating remote repo from source tree**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/9" expanded>

I have set up my personal access token and granted access to all repo. Also I can see my repo from Sourcetree locally. But when I try to create a remote repo, it appears to show the error msg below.

<img width="472" alt="Screenshot 2023-01-17 at 12 33 11 AM" src="https://user-images.githubusercontent.com/62707493/212728076-996fb0ce-39ea-41fd-afcd-7ffd33dc0b03.png">

Has anyone encountered the same issue and figured out how to solve it?

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/9#issuecomment-1385677349" expanded>

<img width="811" alt="Screenshot 2023-01-18 at 12 14 13 AM" src="https://user-images.githubusercontent.com/62707493/212952698-c1746595-3c61-42ea-93d7-4f4f55212a68.png">

I am following the step 2, initialize a repository. And I have found out where's my problem now.

I should create a local repo rather than a remote repo. Question solved, thank you for the time!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/17#issuecomment-1387108775" expanded>

like should we create separate branches corresponding to level 1 to level 5? and push changes to those branches first. And push them to the master branch later.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/17#issuecomment-1387120587" expanded>

thx for your timely reply prof!!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/19#issuecomment-1387285652" expanded>

<img width="391" alt="Screenshot 2023-01-18 at 11 45 55 PM" src="https://user-images.githubusercontent.com/62707493/213218746-06449230-add2-4863-ab36-bea13e389063.png">
the same issue appeared. Where should I get the public key from? As I cannot save my SSH in account setting from Sourcetree and the prompt is couldn't connect to github with my cresidentials. I may have encountered more than one issue, I guess
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/19#issuecomment-1387322354" expanded>

Thanks! I am now able to push changes to git.
However, may I ask if the SSH warning in Sourcetree account setting matters?
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/19#issuecomment-1387335737" expanded>

Finished!
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/68#issuecomment-1405024159" expanded>

I have accidentally removed Java virtual machine in my Java folder. Does it matter?
<img width="334" alt="Screenshot 2023-01-26 at 9 40 34 PM" src="https://user-images.githubusercontent.com/62707493/214850179-2140b347-8b2a-49b0-985d-b6628135a98c.png">


</panel>

</panel>


<panel type="info" header="### 29. LU C..ENYU `@adam07018` (11 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: InvocationTargetException when sorting ObservableList<User>**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/285" expanded>

Hello everyone. I am trying to implement sort feature for tp. I get stuck when I try to sort **ObservableList&gt;User>** in a command class

1. I wrap ObservableList in sortedList 

> `SortedList&gt;User> lastShownList = new SortedList&gt;>(model.getFilteredUserList());;`

2. Sort user based on their user name in lexicographical order. 

> `lastShownList.sort(Comparator.comparing(User::toString));`

However, after executing step 2, it jumps out **InvocationTargetException**  in **FXML Loader#Method Handler**

Does anyone have any thoughts why this happen? Please give any possible suggestions!
</panel>

<panel  header="**2. :fas-info-circle: AssertNotEquals for comparing reference (not value)**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/256" expanded>

Basically, I use a clone method to **deep copy** the Addressbook. 

For example, **AB2 = AB1.clone()**; AB2 and AB1 has **same userList but they got different reference**.

Thus, If I write **AssertNotEquals(AB1, AB2)**, it should pass test.

 However, I found out that there is a **equal method overloaded in Addressbook class** which make my **AssertNotEquals** fail. 
 Because equal method in Addressbook will return true if their userList are same. 

```
public boolean equals(Object other) {
return other == this // short circuit if same object
                || (other instanceof AddressBook // instanceof handles nulls
                && clients.equals(((AddressBook) other).clients));
}
```
Is there anyway to bypass the overload equal and let test method (use the java object equal) **directly compare their reference**? 

</panel>

<panel  header="**3. :fas-info-circle: Asking for suggestion: Where can I use assert in code**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/152" expanded>

I am very confused like where can I use assert? User input is different thus I shouldn't make assumption and assert anything right?

The only way I think about is to assert output string. Does it work in javaFX environment?
</panel>

<panel  header="**4. :fas-info-circle: On MacOs, where is the .gitignore file located?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/5" expanded>

Doing week 2 reading and now I am at w2.3f. I created temp.txt and ignore the file as instructed.

However,  I can't locate the .gitignore file. Is there any way to find it? I am using Mac.
<img width="769" alt="screenshot" src="https://user-images.githubusercontent.com/62133038/212508721-1a1c57e1-453e-4415-917b-65969b43df70.png">

Update: the folder itself is a hidden folder.  So I am actually showing hidden file already
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/5#issuecomment-1383043625" expanded>

> .gitignore is a hidden file, so you need to reveal hidden files to see it. For Mac OS I think the command to see hidden files is Command + Shift + . (that's a full stop at the end) @adam07018

Yah but the whole file .git is a hidden folder and I am showing hidden file already. That is why i am quite confused
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/5#issuecomment-1383393119" expanded>

Oh my bad. Actually just select add ignore entry to this repository and it will work. Previously I put it as global ignore list.
<img width="527" alt="截屏2023-01-16 10 44 31" src="https://user-images.githubusercontent.com/62133038/212587679-72d6968f-85d9-4e2d-a219-a2d8735869f1.png">
BTW, vim and ls -a works all fine. Thanks all for helping and contributing.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/142#issuecomment-1418959430" expanded>

Will there be same error if you do 100% same as the javafx tutorial?
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/136#issuecomment-1418961836" expanded>

I think it's because you don't have another branch going the other way. If you try to create a new branch based on master, it and commit, it will show like you expected
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/132#issuecomment-1418963499" expanded>

I will return immediately or return default value. Worst is to throw exception if default case is impossible
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/256#issuecomment-1470108884" expanded>

Answer is found
</panel>

<panel  header="**11 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/285#issuecomment-1488756569" expanded>

@damithc SFLR Prof.

I just deep copy every user into a new list. I guess there are some restrictions in javaFX. Which stops me from directly make change on ObservableList.

But with javaFX it works, it's weird.
</panel>

</panel>


<panel type="info" header="### 30. LYND.. HNG `@lyndonlim27` (10 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Is changes to input allowed**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/327" expanded>

Hi. Currently, for one of my features, users can only enter in alphanumeric inputs. However, I would like to ask if we are allowed to change it such that users can enter in alphanumeric + whitespace or is this not allowed(due to feature freeze).
</panel>

<panel  header="**2. :fas-info-circle: Sequence diagram**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/281" expanded>

For sequence diagram, if the length of an operation is too long due to a lengthy command, is it okay to split it into two lines or is it incorrect? 

Reason is so that the sequence diagram would not be too wide and small

For example 

Instead of this: 
<img width="684" alt="image" src="https://user-images.githubusercontent.com/80683209/227769476-83853dd7-e8d9-4d73-878b-5dc483b74bf6.png">

Do this: 
<img width="456" alt="image" src="https://user-images.githubusercontent.com/80683209/227769493-e85bea81-d2d2-46bd-9319-5ca5632a865e.png">
</panel>

<panel  header="**3. :fas-info-circle: Scrollbar thumb colour**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/141" expanded>

Hi, I have been trying to figure out how to change the colour of the scrollbar thumb but it seems there's no option for it.
I tried adding in stylesheet (CSS) but it doesnt change anything. 

<img width="1916" alt="image" src="https://user-images.githubusercontent.com/80683209/216760187-d94b2d3a-b857-430c-baf7-570eb27f6950.png">

</panel>

<panel  header="**4. :fas-info-circle: Special characters in Java**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/52" expanded>

<img width="1382" alt="image" src="https://user-images.githubusercontent.com/80683209/214111133-1c7a234f-57c4-4cb4-8872-1b94c18f68df.png">

I have been trying to figure out why I had trouble splitting a string with "|" and found out I needed to \\ it. But why when I check if it contains "|" it works as intended?  So when do I need to \\ it.

Thanks!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/141#issuecomment-1416725870" expanded>

Thank you so much! It works now. Because I added the stylesheet to my scroll pane instead of the anchor pane.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/52#issuecomment-1416726067" expanded>

Thank you so much!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/142#issuecomment-1417785220" expanded>

Hi,

Not sure if this is correct but do check if you are running Azul build of OpenJDK 11
I have tried to find issues similar to this and what I have found so far is this might be caused by using the wrong java version. 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/281#issuecomment-1484102832" expanded>

Thank you!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/327#issuecomment-1496103146" expanded>

Currently, it is just inconvenient for users as they have to concatenate text for e.g "CloseFriends" instead of "Close friends"
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/327#issuecomment-1496126887" expanded>

Okay. Thank you prof!
</panel>

</panel>


<panel type="info" header="### 31. JAMI.. LIN `@jamieeeleow` (10 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: iP Peer Evaluation**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/243" expanded>

Hello, may I know what is the procedure if the person I am supposed to peer review has not released their JAR file yet? Thank you.
</panel>

<panel  header="**2. :fas-info-circle: Hardcoded file path**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/192" expanded>

Hello, may I know how to solve hardcoded file path. I have my jar file in an empty folder and it works other than finding the storage file for the hard disk to store the tasks.

How do I go about it and not hardcode the file path? 
Or is it normal to have this hardcoded file path issue? Because I remember from Level-7: Save in week 3 project, it did say that 'You may hard-code the file name and location e.g., ```[project_root]/data/duke.txt```'

</panel>

<panel  header="**3. :fas-info-circle: GUI not appearing when running the program**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/131" expanded>

I followed the instructions given in the JavaFX tutorial and my program ran and worked in the terminal but no GUI appeared.
This was what was shown in the terminal from the command ./gradlew run

```
> Configure project :
Project : => no module-info.java found

> Task :compileJava UP-TO-DATE
> Task :processResources UP-TO-DATE
> Task :classes UP-TO-DATE

> Task :Launcher.main()
```

</panel>

<panel  header="**4. :fas-info-circle: Reading hard disk data file using Gradle**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/75" expanded>

Hello, when I run my code using Gradle, it is unable to read the hard disk date file where the tasks are being stored. The data file is currently in a data folder in the project root. May I know if I need to change the location of the file so that it can be read when running Gradle? Thank you
</panel>

<panel  header="**5. :fas-info-circle: Automating the testing of text UIs after implementing Level-7**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/66" expanded>

Before implementing Level-7 of saving data, my text-ui-test was able to pass the runbash.sh test. However, after adding a data storage file in [project-root]/data/duke.txt, I think my input file was unable to read and access the file resulting in it printing an empty list.

May I know how to get the data read and printed? Thank you!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/131#issuecomment-1416739726" expanded>

> * What is your development environment? Ie Windows/Mac/Linux?
> * Have you checked your java version?
> * Does exporting a jar file and running it produce a GUI?

Im using Mac, and running java 11. I've tried exporting a jar file and running it (following the same instructions as that of addressbook.jar) and the program runs in the terminal but still does not produce a GUI
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/131#issuecomment-1416802048" expanded>

> > Pushing your branch for others to test your setup would be helpful here!
> 
> Yup, that could give others a better chance of reproducing the issue and finding a solution.

Yup I have pushed my branch
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/131#issuecomment-1422599753" expanded>

> Hi @jamieeeleow
> 
> I've cloned your git repo and looked through your code, and here's what I think is happening:
> 
> 1. The Gradle `run` script is called
> 2. The `main` function in the `Launcher` class is called
> 3. A new `Main` object is instantiated
> 4. Since each `Main` object has a `private Leo leo = new Leo("/data/leo.txt")`, a new `Leo` object is also instantiated
> 5. The public constructor for the `Leo` class is called
> 6. `parser.readCommand()` is called
> 7. The code `String command = scanner.nextLine()` will prevent the execution of any other code as it waits for new user input in the terminal
> 
> Point 7 is what I think is causing the GUI to not appear.
> 
> When I commented out the `parser.readCommand()` line in the public `Leo` constructor, the GUI appears as expected with the "Hello World!" text.
> 
> Hope this helps!

Thank you for looking through my code, I managed to get the GUI to appear with your help 😄 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/192#issuecomment-1433018859" expanded>

@yyj-02 @Junyi00 

I managed to do it yay 😄 Thank you for your help!! 
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/243#issuecomment-1458400039" expanded>

Okay! Thank you
</panel>

</panel>


<panel type="info" header="### 32. TAJW..AHIM `@fahim-tazz` (10 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Help with smoke testing**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/236" expanded>

Sorry for this last minute request, but could anyone smoke test my jar file on Linux and/or Windows?

You can unzip and run it with ```java -jar chad.jar```. 
[chad.jar.zip](https://github.com/nus-cs2103-AY2223S2/forum/files/10872051/chad.jar.zip)


</panel>

<panel  header="**2. :fas-info-circle: Should README.md on the root folder of the repo be changed?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/218" expanded>

The `README.md` file on the root folder shows the original Duke Project Template readme. Should I change it to show my User Guide, my PR description, or leave it as is?
</panel>

<panel  header="**3. :fas-info-circle: Terminal outputs errors while running GUI. Will that be considered poor implementation?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/209" expanded>

I have a working GUI, but when trying to delete an index that does not exist, the terminal shows IndexOutOfBounds Exception. This does not break the GUI (it just display anything, and you can enter a different index to continue), the user can still use it properly. Will this impact grading? 
</panel>

<panel  header="**4. :fas-info-circle: [ip] Put past commits into a branch**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/181" expanded>

I have several commits in my master branch that were supposed to go into their separate branches. 

How can I put those past commits in separate branches according to the iP instructions (without undoing all my subsequent work)?

PS. I am using Sourcetree.
</panel>

<panel  header="**5. :fas-info-circle: [tP] Software Complexity Expectations for Evolve vs Morph**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/116" expanded>

Prof @damithc, before my team decides on whether to Morph or Evolve AB3 for our tP, I would like to know, is there any difference in expected complexity of features? 
I.e. for Morph, since we are starting from scratch, will you be expecting less complex features, compared to Evolve where we are building on existing software, so we can build more complex functionality?

P.S. I understand we should not be worried about features yet, but we just wanted to gauge the workload for each direction.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/181#issuecomment-1428144594" expanded>

Found a duplicate issue [here.](https://github.com/nus-cs2103-AY2223S2/forum/issues/167)
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/209#issuecomment-1435822594" expanded>

Understood, Prof. Was asking because users aren't supposed to see terminal output, but I understand this project is not just about User Experience.
Thank you.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/194#issuecomment-1436563212" expanded>

@WesleyBLDC For me running the jar file via terminal creates the data file perfectly. But running it by double-clicking doesn't (the opposite of what you said). Any ideas how to fix this?
![SCR-20230220-nby](https://user-images.githubusercontent.com/86123134/220057154-8152c30c-1724-47b4-8b1f-a85a0f4de9d0.png)


</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/218#issuecomment-1436747862" expanded>

Understood Prof, thank you.
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/236#issuecomment-1453520200" expanded>

@notle1706 @RussellDash332 @Guanzhou03 @domlimm @QQH0828 Thank you all so much! Literally a life saver because I was running too close to the deadline.

Also thanks for the suggestions guys, I'll try and fix those issues.

</panel>

</panel>


<panel type="info" header="### 33. NGUY..NGOC `@RubyNguyen07` (10 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Unable to use checkstyle with Gradle**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/110" expanded>

Hello, I have created two files checkstyle.xml and suppressions.xml in the ./config/checkstyle folder. I also have included the checkstyle plugin in the build.gradle file and set the tool version to '10.2'. However, when I try to run "./gradlew checkstyleMain", there will be the following error: 

> Unable to create Root Module: config {rootDir}/ip/config/checkstyle/checkstyle.xml}, classpath {/ip/build/classes/java/main:/{rootDir}/ip/build/resources/main}.

Did any of you run into the same issue?

</panel>

<panel  header="**2. :fas-info-circle: Unable to run java -jar addressbook.jar on M1**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/59" expanded>

Hello! I have installed Java 11 and follow the instructions on this [page](https://nus-cs2103-ay2223s2.github.io/website/admin/programmingLanguages.html) but I am still running into the error below when I run java -jar addressbook.jar. Do you guys have any idea why? Thanks! 

> Loading library prism_es2 from resource failed: java.lang.UnsatisfiedLinkError: Can't load library: /Users/rubynguyen/.openjfx/cache/11/libprism_es2.dylib
java.lang.UnsatisfiedLinkError: Can't load library: /Users/rubynguyen/.openjfx/cache/11/libprism_es2.dylib
	at java.base/java.lang.ClassLoader.loadLibrary(ClassLoader.java:2633)
	at java.base/java.lang.Runtime.load0(Runtime.java:768)
	at java.base/java.lang.System.load(System.java:1837)
	at com.sun.glass.utils.NativeLibLoader.installLibraryFromResource(NativeLibLoader.java:205)
	at com.sun.glass.utils.NativeLibLoader.loadLibraryFromResource(NativeLibLoader.java:185)
	at com.sun.glass.utils.NativeLibLoader.loadLibraryInternal(NativeLibLoader.java:157)
	at com.sun.glass.utils.NativeLibLoader.loadLibrary(NativeLibLoader.java:52)
	at com.sun.prism.es2.ES2Pipeline.lambda$static$0(ES2Pipeline.java:68)
	at java.base/java.security.AccessController.doPrivileged(Native Method)
	at com.sun.prism.es2.ES2Pipeline.&gt;clinit>(ES2Pipeline.java:50)
	at java.base/java.lang.Class.forName0(Native Method)
	at java.base/java.lang.Class.forName(Class.java:315)
	at com.sun.prism.GraphicsPipeline.createPipeline(GraphicsPipeline.java:187)
	at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.init(QuantumRenderer.java:91)
	at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.run(QuantumRenderer.java:124)
	at java.base/java.lang.Thread.run(Thread.java:829)
Loading library prism_sw from resource failed: java.lang.UnsatisfiedLinkError: Can't load library: /Users/rubynguyen/.openjfx/cache/11/libprism_sw.dylib
java.lang.UnsatisfiedLinkError: Can't load library: /Users/rubynguyen/.openjfx/cache/11/libprism_sw.dylib
	at java.base/java.lang.ClassLoader.loadLibrary(ClassLoader.java:2633)
	at java.base/java.lang.Runtime.load0(Runtime.java:768)
	at java.base/java.lang.System.load(System.java:1837)
	at com.sun.glass.utils.NativeLibLoader.installLibraryFromResource(NativeLibLoader.java:205)
	at com.sun.glass.utils.NativeLibLoader.loadLibraryFromResource(NativeLibLoader.java:185)
	at com.sun.glass.utils.NativeLibLoader.loadLibraryInternal(NativeLibLoader.java:157)
	at com.sun.glass.utils.NativeLibLoader.loadLibrary(NativeLibLoader.java:52)
	at com.sun.prism.sw.SWPipeline.lambda$static$0(SWPipeline.java:42)
	at java.base/java.security.AccessController.doPrivileged(Native Method)
	at com.sun.prism.sw.SWPipeline.&gt;clinit>(SWPipeline.java:41)
	at java.base/java.lang.Class.forName0(Native Method)
	at java.base/java.lang.Class.forName(Class.java:315)
	at com.sun.prism.GraphicsPipeline.createPipeline(GraphicsPipeline.java:187)
	at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.init(QuantumRenderer.java:91)
	at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.run(QuantumRenderer.java:124)
	at java.base/java.lang.Thread.run(Thread.java:829)
Graphics Device initialization failed for :  es2, sw
Error initializing QuantumRenderer: no suitable pipeline found
java.lang.RuntimeException: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found
	at com.sun.javafx.tk.quantum.QuantumRenderer.getInstance(QuantumRenderer.java:280)
	at com.sun.javafx.tk.quantum.QuantumToolkit.init(QuantumToolkit.java:222)
	at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:260)
	at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:267)
	at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158)
	at com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658)
	at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678)
	at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195)
	at java.base/java.lang.Thread.run(Thread.java:829)
Caused by: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found
	at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.init(QuantumRenderer.java:94)
	at com.sun.javafx.tk.quantum.QuantumRenderer$PipelineRunnable.run(QuantumRenderer.java:124)
	... 1 more
Exception in thread "main" java.lang.RuntimeException: No toolkit found
	at com.sun.javafx.tk.Toolkit.getToolkit(Toolkit.java:272)
	at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:267)
	at com.sun.javafx.application.PlatformImpl.startup(PlatformImpl.java:158)
	at com.sun.javafx.application.LauncherImpl.startToolkit(LauncherImpl.java:658)
	at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:678)
	at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195)
	at java.base/java.lang.Thread.run(Thread.java:829)
</panel>

<panel  header="**3. :fas-info-circle: iP A-Enums: Is this increment optional?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/24" expanded>

Hello, I am wondering whether not implementing A-Enums will affect grading because for now I could not see any benefits of using Java enums in my code. 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/24#issuecomment-1396422037" expanded>

@BoAi01 Yes thats what I thought too :) Thanks for your comment! 
@damithc Okay I got it, thanks! 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/59#issuecomment-1403069646" expanded>

@damithc Hi, I have tried the methods to resolve as in the issue but the problem persists 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/59#issuecomment-1403085592" expanded>

@damithc I have solved the issue, thanks! I still do not know why after I removed all the versions, after a while there is another version (it did not show on folder JavaVirtualMachines at first). 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/78#issuecomment-1406645591" expanded>

@ChangGittyHub Hello, in my case i did a few random things and the openjdk version (that did not exist before) suddenly popped up. Then i deleted that version and it worked. After that I did some research and I think you could try cd into the /Library/Java directory then type "sudo rm -fr JavaVirtualMachines/*" to delete all Java versions.  Let me know if it works! 
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/109#issuecomment-1410270836" expanded>

@ezeAng yes, from what I read then you are even encouraged to create a new name and personality for your bot! 
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/110#issuecomment-1410358170" expanded>

@Junyi00 nopee i double checked both filenames
</panel>

<panel  header="**10 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/110#issuecomment-1410588334" expanded>

I just checked again, it turned out it is because this URI "https://checkstyle.org/dtds/configuration_1_3.dtd" is not resolved. It works now, thanks!
</panel>

</panel>


<panel type="info" header="### 34. HAN ..NLEY `@hansstanley` (9 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Request to use CalendarFX**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/205" expanded>

## Library

[CalendarFX](https://dlsc.com/products/calendarfx/)

## Purpose

We plan to use this to display temporal information in a calendar view.

## License

[Apache License 2.0](https://github.com/dlsc-software-consulting-gmbh/CalendarFX/blob/master-11/LICENSE)

</panel>

<panel  header="**2. :fas-info-circle: Display full text instead of ellipsis in Label for GUI**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/105" expanded>

When the text in `Label`s, which I use to display chat messages, becomes too long, it becomes truncated with ellipsis. Here is a screenshot:

<img width="512" alt="Screenshot 2023-01-31 at 16 13 40" src="https://user-images.githubusercontent.com/20805849/215703544-d2ecb1ed-64b2-45f3-bfc6-2b624efb8005.png">

Is there a way for a `Label` to show the full text? For context, the node hierarchy to a `Label` is `AnchorPane -&gt; ScrollPane -&gt; VBox -&gt; HBox -&gt; Label`.

Here is a snippet of the main window's `.fxml`:

```fxml
<AnchorPane maxHeight="-Infinity" maxWidth="-Infinity" minHeight="80.0" minWidth="400.0" prefHeight="600.0"
            prefWidth="400.0" xmlns="http://javafx.com/javafx/8.0.171" xmlns:fx="http://javafx.com/fxml/1"
            fx:controller="jarvis.ui.layout.MainWindow">
    <ScrollPane fx:id="scrollPane" hbarPolicy="NEVER" hvalue="1.0" prefHeight="560.0" prefWidth="400.0" vvalue="1.0">
        <VBox fx:id="chatContainer" prefHeight="560.0" prefWidth="380.0"/>
    </ScrollPane>
    <TextField fx:id="userInput" onAction="#handleUserInput" prefHeight="40.0" prefWidth="320.0"
               AnchorPane.bottomAnchor="1.0" AnchorPane.leftAnchor="1.0"/>
    <Button fx:id="sendButton" mnemonicParsing="false" onAction="#handleUserInput"
            prefHeight="40.0" prefWidth="80.0" text="Enter"
            AnchorPane.bottomAnchor="1.0" AnchorPane.rightAnchor="1.0"/>
</AnchorPane>
```

And here is a snippet of the message box's `.fxml`:

```fxml
<fx:root alignment="TOP_RIGHT" maxHeight="Infinity" maxWidth="Infinity" prefWidth="380.0"
         type="javafx.scene.layout.HBox" xmlns="http://javafx.com/javafx/8.0.171" xmlns:fx="http://javafx.com/fxml/1">
    <padding>
        <Insets bottom="15.0" left="5.0" right="5.0" top="15.0"/>
    </padding>
    <Label fx:id="messageText" text="Label" wrapText="true">
        <padding>
            <Insets left="5.0" right="5.0"/>
        </padding>
    </Label>
    <Circle fx:id="displayPicture" radius="25.0"/>
</fx:root>
```

Thanks!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/1#issuecomment-1380491839" expanded>

JavaFX only [added M1 support in version 17](https://gluonhq.com/javafx-for-apple-m1/), might be an incompatibility issue for your 11.0.17.

The suggested Zulu 11 works for me on M1 macOS 13.1 though
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/47#issuecomment-1399941907" expanded>

Check if you have handled the case where the folder doesn't exist, as the .jar file likely won't have a /data folder in the directory it is situated.

From the module website:
> Your code must handle the case where the data file doesn't exist at the start. Reason: when someone else takes your Duke and runs it for the first time, the required file might not exist in their computer. Similarly, if you expect the data file to be in as specific folder (e.g., ./data/), you must also handle the folder-does-not-exist-yet case.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/65#issuecomment-1404439665" expanded>

Just as an example, enums can be used to store the command action words like "bye", "list", "todo", etc. as a field.

```java
public enum FirstWord {
    BYE("bye"),
    LIST("list"),
    // ...

    private final String word;

    FirstWord(String word) {
        this.word = word;
    }
}
```

In addition to consolidating the possible commands, you can add methods that convert strings into the enum, [seen here](https://stackoverflow.com/questions/604424/how-to-get-an-enum-value-from-a-string-value-in-java). If you use a `Map` to store Commands, the enum can also be used as the key.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/76#issuecomment-1406713877" expanded>

@heeeyi 

Alternatively, as you'll see in the [JavaFX tutorial part 4](https://se-education.org/guides/tutorials/javaFxPart4.html), you can create a `Main` class that extends `Application`, and create an instance of `Duke` in `Main`, for e.g.

```java
public class Main extends Application {
    private Duke duke = new Duke("data.txt");
    // ...
}
```

Then the `Launcher` class becomes

```java
public class Launcher {
    public static void main(String[] args) {
        Application.launch(Main.class, args);
    }
}
```
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/105#issuecomment-1409984083" expanded>

@hingen You're right, my bad thanks
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/123#issuecomment-1412923184" expanded>

@Irminrics I added `minHeight="-Infinity"` to my `Label`, like so:

```fxml
<Label fx:id="messageText" text="Label" wrapText="true" minHeight="-Infinity">
    ...
</Label>
```

Here's a comparison with and without `minHeight="-Infinity"`:

> Without `minHeight="-Infinity"`

<img width="512" alt="Screenshot 2023-02-02 at 07 55 40" src="https://user-images.githubusercontent.com/20805849/216195086-2a61c28b-584c-40f2-a4bc-2bd1cfb8b429.png">

> With `minHeight="-Infinity"`

<img width="512" alt="Screenshot 2023-02-02 at 07 56 30" src="https://user-images.githubusercontent.com/20805849/216195305-2b564bec-a8c9-4e63-8a4c-faf358101196.png">

Hope this helps!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1436336353" expanded>

<img width="512" alt="GUI screenshot" src="https://user-images.githubusercontent.com/20805849/220013945-68fb15b2-c7b0-4fa2-aab1-15753636c2b2.png">

</panel>

</panel>


<panel type="info" header="### 35. LAU ..MING `@zm-l` (9 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: How to compile in a less recent Java Runtime**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/201" expanded>

My project structure was at SDK 11 and my program could launch. However I try run in my Ubuntu which only has Java 11, the following error occurs:

```
Error: LinkageError occurred while loading main class duke.Launcher
        java.lang.UnsupportedClassVersionError: duke/Launcher has been compiled by a more recent version of the Java Runtime (class file version 61.0), this version of the Java Runtime only recognizes class file versions up to 55.0
```
Running in my Powershell works as its java version is 17
May I know how to compile in a less recent Java Runtime?

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/15#issuecomment-1396920002" expanded>

For me I reinstalled Java as I previously have JRE only not JDK, I think you can check in the "c:\program files\java\".
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/30#issuecomment-1397028637" expanded>

@damithc May I ask if the "highest score" is highest number of corrects in the quiz or is it inclusive of the points you earned?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/30#issuecomment-1397036378" expanded>

@damithc Sorry I mean inclusive of the early submission points.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/201#issuecomment-1434256112" expanded>

@francisyzy Thanks for the suggestion. I have changed all JavaFX version including those in `build.gradle` and all the FXML files to 11.

The ubuntu I used to run is just a WSL but with different java version than my main machine. The confusing part is I have the project SDK at version 11 and the program runs fine, but ubuntu recognize the class file version as 61 which is at Java 17. Hence I suppose that's why my main machine runs fine.

I have also checked the Gradle JVM which is set at SDK 11.

Not too sure which mistakes causes it to compiles to a higher class file version.


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/201#issuecomment-1434272641" expanded>

Powershell is 17, Ubuntu is 11

</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/201#issuecomment-1434282979" expanded>

@damithc Hi prof, I tried `./gradlew clean` before running `./gradlew clean shadowJar`. But when running `java -jar duke.jar`, the class file version is still incorrect.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/201#issuecomment-1434304115" expanded>

Uninstalling later version of Java works. Thanks!
</panel>

<panel  header="**9 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/360#issuecomment-1501194236" expanded>

Based on what I tried, you can consider writing the entire table in html based on: https://stackoverflow.com/questions/19950648/how-to-write-lists-inside-a-markdown-table
</panel>

</panel>


<panel type="info" header="### 36. CHEW..KIAT `@nerdyboy98` (8 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Master branch falling behind after merging PR**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/162" expanded>

So I have been following the steps on the course website and realised the "master" branch was behind after completing the following steps:
1) Create pull request on github to merge A-CodeQuality to master
2) Approve the pull request (ticking create merge commit also)
3) Pulled the master branch to local repo by selecting "master" as the branch to pull

Asked my tp group about it and they had no idea as well. So I was wondering if this is normal and am I supposed to right-click on the master branch and select "merge master into current branch" to bring the master branch to the top? Thanks in advance!

![image](https://user-images.githubusercontent.com/110829473/218248971-49f28866-0df2-45f6-9ba4-d3ba303385ef.png)

</panel>

<panel  header="**2. :fas-info-circle: Wrong sequence of tagging causing Push error**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/80" expanded>

The Level-7 and Level-8 increments required us merge with the master branch before tagging but I tagged Level-7 (without merging) and Pushed to the remote Repo. Now I'm facing this problem where it says the "Level-7" already exists when I try to Push my local repo (with Level-7 and Level-8 already merged and tagged after merging) to the remote repo. Anybody have any idea how to resolve this issue? Not sure if this will affect the grading script as well. Thanks in advance!

Edit: I removed the removed the "Level-7" tag from the branch-level-7 and tagged the commit after merging Level-7 increment, which I then encountered this error when Pushing

![image](https://user-images.githubusercontent.com/110829473/215111283-55d4dabd-29f9-40c1-911a-372b53413646.png)


</panel>

<panel  header="**3. :fas-info-circle: runtest.bat not reading the next input**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/62" expanded>

I got my runtest.bat to finally run but somehow the file isn't reading my next input line. As seen from the image attached, the batch file runs the first input "todo borrow book" properly but afterwards it was unable to take the next input "bye" and this causes the terminal throws a NoSuchElementException error. Can anybody comment on what can I do to allow my runtest.bat to read the subsequent input line? Thanks in advance! Attached as well is my runtest.bat configuration.

![image](https://user-images.githubusercontent.com/110829473/214524503-2f7444e4-9247-4543-b611-bef96c743d5a.png)
![image](https://user-images.githubusercontent.com/110829473/214525360-c1f52275-6534-4125-86bb-49787f6dfd8e.png)


</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/62#issuecomment-1403365911" expanded>

> 

ahh thanks alot, that solved my problem. Also is there a way to know if the ACTUAL output is same as the EXPECTED output? Or do I have to manually observe whats shown in the terminal :o
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/80#issuecomment-1406594923" expanded>

Ahh ok it worked! Thanks prof!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/80#issuecomment-1413139421" expanded>

> @nerdyboy98 Is the issue resolved?

yup resolved already
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/162#issuecomment-1426686592" expanded>

Hi prof, yup I had mistakenly did point number 3 and I went into master branch before pulling master branch. Now it seems that I have two A-CodeQuality branches with one having the "origin/" suffix as seen in the second image with Show Remote Branches ticked.
Is there any way to revert the wrong pull mentioned?

without "Show Remote Branches" ticked
![image](https://user-images.githubusercontent.com/110829473/218252736-3383312d-f857-4763-909e-fa1abead92df.png)

with "Show Remote Branches" ticked
![image](https://user-images.githubusercontent.com/110829473/218252631-413bff82-e878-46df-9abf-d922eca3c3bc.png)

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/162#issuecomment-1426787069" expanded>

@hingen ok I did what you mentioned I think its sorted already, thanks for the help guys!
</panel>

</panel>


<panel type="info" header="### 37. LI Y..XUAN `@CarrieLi1015` (8 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: .jar file follow the naming convention, cannot open without using  **" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/367" expanded>

We just found out that for mac, if following in the school naming convention, like [CS2103][name].jar. The file cannot be opened.

For example, java -jar [CS2103][name].jar could not open the .jar file. One way to open it is using java -jar '[CS2103][name].jar', another is to use java -jar *.jar

Since we are not sure if it is cause by zsh set up or it is a general issue for all mac users. May we ask if we will be penalised by this? As we did not specific it inside UG and for those who does not know this might not be able to open our .jar file.

Or is it possible to make an announcement that for mac user, need to wrap the .jar file name with ' ' or use *.jar in order to open it?
</panel>

<panel  header="**2. :fas-info-circle: Default window size**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/290" expanded>

Hello prof and peers.
May I ask if it is ok for us to adjust the DEFAULT_HEIGHT and DEFAULT_WIDTH under the GuiSettings?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/206#issuecomment-1434855996" expanded>

Hello prof, I have faced similar issue here. Followed the steps given but the github page is not live.

<img width="730" alt="Screenshot 2023-02-18 at 12 06 25 AM" src="https://user-images.githubusercontent.com/97392685/219705022-58bf4047-4586-4b28-9e40-cbd9e7559fc8.png">

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/206#issuecomment-1434896474" expanded>

> 

Thank you prof! The problem is solved!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/290#issuecomment-1487772491" expanded>

Thank you for your reply prof! The application window size is adjustable, but still we need to set a reasonable minima height and width (cannot be too large) as people using different sizes laptop. Which means, it might be the best if we could detect the screen size when the application is launched, and set application size based on that?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/290#issuecomment-1487891338" expanded>

Noted! Thank you so much prof!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/367#issuecomment-1502798513" expanded>

Hi prof, we just checked our file with a few other mac users. Some of them can open without using ' ', some of them cannot. We are not sure whether it is due to different mac model (so different shell version, I think zsh will have problem but bash will not [Terminal version](https://support.apple.com/en-us/HT208050)).

<img width="1106" alt="Screenshot 2023-04-11 at 3 10 43 PM" src="https://user-images.githubusercontent.com/97392685/231084364-fa84a7e4-a503-4a14-b438-ee3172ef21ee.png">
name wrap inside ' ' can work.
<img width="894" alt="Screenshot 2023-04-11 at 3 12 14 PM" src="https://user-images.githubusercontent.com/97392685/231084479-a3e9ba5b-21c6-42cc-b82a-6cb8649e0698.png">
After remove the square bracket can work, might because square bracket is Regex expression in Unix?

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/367#issuecomment-1505590493" expanded>

> @CarrieLi1015 I've updated PE instructions to encourage everyone to use double quotes around the jar file name, as follows:
> 
> ![image](https://user-images.githubusercontent.com/1673303/231467325-939fa31f-e8d6-4910-9466-1fb199fafbef.png)
> 
> To confirm, the above works in your shell, right?

Yes it works on my shell. Thank you prof!
</panel>

</panel>


<panel type="info" header="### 38. ANUN..OSHI `@anunayajoshi` (8 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: JAR file Missing Email despite having done release on Github**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/299" expanded>

Hello, my team T09-4 has uploaded the jar file but got an email saying it is missing. Could we get help to verify @damithc , as the deadline is 12pm. 

![image](https://user-images.githubusercontent.com/47421902/229014096-d1b2968e-757f-43b5-8e72-e997bac0dc4c.png)

</panel>

<panel  header="**2. :fas-info-circle: What is the recommended way to split the work amongst our teammates?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/237" expanded>

Hello, 

We have been facing some struggles trying to split up the work for the team project. 
I read from one of the forums that we should split the work based on user stories and user tasks, so each person is given 1 feature to implement. 

However, we felt that that would lead to a lot of merge conflicts and issues down the road. We tried to split it so that each person is in charge of UI, Logic, Model, Storage classes, so that we do not clash too much with each other's codebase, and helps to abstract out how each class needs from each other. That came with its own issues as to implement a single feature required small changes from all teammates, and could potentially slow down progress. Additionally, doing as such meant that those in charge of the Logic and Model could not visually see the changes and test it until the UI was added for it. 

As such, I'm unsure how other teams are delegating the work such that we can collaborate together seamlessly. 

Could anyone share any advise?
 
</panel>

<panel  header="**3. :fas-info-circle: Cannot access Controller methods from SceneBuilder**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/101" expanded>

Remember to give sufficient details e.g.,
* Your development environment (IntelliJ version, Java version, OS, ...)
* Relevant code, error message, stack trace
* Relevant code snippet (an example given below), or link to the relevant code on your GitHub repo

Hello, I have a JavaFXML file in a "resources" folder, which I believe is under gradle. 
I also have a Controller class that is under my main/java/duke package. 
I would like to link these two together, and was unable to do so under SceneBuilder, so I changed my fxml file as follows to include `fx:controller="duke.Controller"`

This allowed me to see the controller under the "Controller tab" within SceneBuilder but I was not able to assign the methods given, as there is no drop down. 

If it matters, here's my start method to know that my filepath is correct. My GUI functions normally, but it is just that the controller methods do not show up. 

```java
@Override
    public void start(Stage stage) throws Exception {
        Parent root = FXMLLoader.load(getClass().getResource("/sample.fxml"));
        Scene scene = new Scene(root);
        stage.setScene(scene);
        stage.show();
    }
```

Hope someone could advise!

</panel>

<panel  header="**4. :fas-info-circle: Level 7 and Level 8 Parallel Branching**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/40" expanded>

Hello, So I am working on Level 7 and Level 8 of the IP. And we are told to work on them on parallel, and only merge after both are done. I have completed Level 7, and changed to a new branch for Level-8, but the code still remains the same. Are we supposed to git add , and commit the code within level 7 first, and then change the branch, or is the code meant to be unchanged when changing the branch. If the code doesn't change, the benefits of branching doesn't really make sense to me. 
</panel>

<panel  header="**5. :fas-info-circle: Will the post-lecture quiz marks be released only after the quiz is over?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/14" expanded>

For the week 1 pre-lecture quiz, we were able to see our marks after completing the quiz. 

We are not able to see it for week 2, and it states that "Correct answers and your score will be released within 1-2 days after the due date."

Is that intentional or do we need to wait for a while before we can see our marks, to check if we got above 70%?

Thank you!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/40#issuecomment-1399474076" expanded>

Thank you for the clarification @damithc !
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/49#issuecomment-1401518486" expanded>

I think JUnit is able to simulate "running Duke and feeding the inputs as well", and does the work of comparing the output to expected. I can create "new Duke" within the test case itself and it can compare the outputs like when we used text-ui-test.

But it's better to test out the smaller components of Duke instead of Duke itself, as there are a lot of different parts working together and it'll make it easier to find where the fault is.

</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1413035073" expanded>

![image](https://user-images.githubusercontent.com/47421902/216211095-a6138a30-e91d-4fce-a5a9-194ee92f5257.png)

I managed to deal with overflow by changing the min height attribute within Scene Builder to "USE_PREF_SIZE"

I also used a Circle to clip my ImageView with the sizing of (45,45,45). 
Im struggling with dealing with the padding and making the text centered to the image if its short, but when its long, it can use the entire space. When I try to center it, the entire text simply shifts down which makes it look rather odd. 

</panel>

</panel>


<panel type="info" header="### 39. GLEN.. LIM `@glyfy` (8 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Question on canvas submission of tP**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/343" expanded>

Can I check is it ok for one person to submit on behalf of the whole team on canvas. For the PPP, does he submit all group members md files?

</panel>

<panel  header="**2. :fas-info-circle: Should we remove the proposed undo/redo feature in our tps DG?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/276" expanded>

n/a
</panel>

<panel  header="**3. :fas-info-circle: Running jar file with Java Platform SE Binary fails to create data folder**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/194" expanded>

However, running it in command line with the command `java -jar your_jar_file.jar` results in data folder being created. Anyone know why this is happening?

</panel>

<panel  header="**4. :fas-info-circle: Clarification about branch creation for week5 iP tasks**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/166" expanded>

Hi can I check the branches A-Assertions, A-CodeQuality, A-Streams are branching off from the master branch at the same point as the level-10 branch?
Therefore at the point that I am branching them off the changes in Level-10 branch have not been implemented yet? 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/194#issuecomment-1434118105" expanded>

My jar file seems to run fine on my friend's computers. This could be an issue with running the jar using Java Platform SE Binary application.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/166#issuecomment-1434121166" expanded>

Yes it has been resolved. I now understand that after starting branch and incrementing I was supposed to merge it back to master.
Thank you.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/343#issuecomment-1500364262" expanded>

Ok thank you for the clarification prof!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/276#issuecomment-1501148421" expanded>

Thanks prof
</panel>

</panel>


<panel type="info" header="### 40. THEN..RONG `@thennant` (8 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Adding extension for BCD**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/155" expanded>

Hi can i check for adding extension-BCD, by extension does it means adding it as a new task type (like the user will enter a new command and the task executes it) or the extension is supposed to be extending off an existing task type and does the job automatically or are we free to decide this ourselves?
</panel>

<panel  header="**2. :fas-info-circle: JavaFX missing components**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/125" expanded>

Error message from running Crystal:
![image](https://user-images.githubusercontent.com/97217532/216232089-c88e6ebd-c6bd-441c-93dd-a29e1442fe15.png)

Build.gradle:
![image](https://user-images.githubusercontent.com/97217532/216232328-b899f920-dd7e-48bf-b5ad-cb08ab56cb0f.png)

The gui from running launcher class:
![image](https://user-images.githubusercontent.com/97217532/216232800-59a8e10d-ffbc-4fbd-832f-91a9ade0627d.png)

Hi, i am having issues with the javafx installation. I have added the necessary plugins, javafx version and modules as well as dependencies to the build.gradle. Upon running my Crystal class (the Duke class), it says missing javafx components. However, i am able to run my launcher class with the gui window popping up. Is this a normal thing or do i need to install the missing components and if so how do I go about that? Thanks.
</panel>

<panel  header="**3. :fas-info-circle: Forgot to tick the box when merging branch with master**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/55" expanded>

![image](https://user-images.githubusercontent.com/97217532/214226920-393d6ec2-2ca0-4da7-ba2c-8411133c746c.png)

I forgot to tick the little box at the corner when merging my branch with the master, is that an issue? Do i have to unmerge the branch and merge it again? Or can i just merge the branch with the master again?
</panel>

<panel  header="**4. :fas-info-circle: Code reads date wrongly**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/54" expanded>


![image](https://user-images.githubusercontent.com/97217532/214221317-a6060900-006e-4865-8c77-a14573a2052c.png)
![image](https://user-images.githubusercontent.com/97217532/214221934-8462d2a6-43a3-4f80-a234-7bda8225d9a1.png)

My code outputs the date correctly when the deadline date is given in the year/month/day format but for some reason, it still gives a date when the deadline date is given in the day/month/year format. Any ideas on how to get it to only recognize the year/month/day format only?

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/55#issuecomment-1401505519" expanded>

Ok thanks prof!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/54#issuecomment-1407379364" expanded>

ok thank you!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/125#issuecomment-1416777940" expanded>

ok thanks!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/155#issuecomment-1424377739" expanded>

ok tks!
</panel>

</panel>


<panel type="info" header="### 41. KONG..HEYI `@heeeyi` (8 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Gradle CI workflow dependency library is down**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/292" expanded>

Hi I have recent push on Github, which was failed reporting error "Could not HEAD &gt;a gradle jar dependency>". Received status code 503 from server: Service unavailable. This is the screenshot: 

![image](https://user-images.githubusercontent.com/97591125/228540677-96a68b9d-6be3-4efb-a1a9-09a5304d7c01.png)

When I tried to follow the link for the last failed jar file, the webpage shows 404 error. Therefore, this resource is genuinely missing. In this case, how are we suppose to do our CI/CD workflow check, or should we just bypass it?

![image](https://user-images.githubusercontent.com/97591125/228540962-ef6823f1-05e8-4a69-a863-595330d5e8e6.png)

</panel>

<panel  header="**2. :fas-info-circle: Query about resolving the link in xml check style file**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/117" expanded>

Hi I encountered the same issue to #110, and in the end, the root cause of the issue turned out to be “the URL https://checkstyle.org/dtds/configuration_1_3.dtd is not resolved”. May I ask how can this URL be resolved? Will be so appreciated if anyone could help in pointing out what exactly I need to do, thanks so much!

![05809396-13C8-470C-A55D-EFD55D0D6C46](https://user-images.githubusercontent.com/97591125/215967714-ef96ad83-aee7-4e92-8cd1-158c0850fe68.jpeg)


</panel>

<panel  header="**3. :fas-info-circle: Issue of Duke GUI truncating the input**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/103" expanded>

Hi I am adding a GUI for my Duke, strictly following the JavaFX tutorial provided in the class.

However, I found that for both my input and Duke response, if they are too long, the GUI will not be able to completely show them, but instead show them in a truncated fashion, i.e. "something something..." towards the end. The long message will only be completely shown if there are no other dialog box behind it.

Here are the screenshots:

(No dialog box behind, show complete message)
![013120231526](https://user-images.githubusercontent.com/97591125/215694640-0751ff15-ab68-4823-90d8-3e9562396159.JPG)

(Has other dialog box, or reaching the end, truncated)
![013120231525](https://user-images.githubusercontent.com/97591125/215694803-71f2ce8b-1f08-4419-bd7b-d707781a14a6.JPG)

Does anyone know how to resolve this? 


</panel>

<panel  header="**4. :fas-info-circle: Query about Application.launch() in using JavaFX**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/76" expanded>

Hi I have been studying about JavaFX following strictly to this tutorial. https://se-education.org/guides/tutorials/javaFxPart1.html

I found that following Tutorial 1, when I stried to add the start() method to my own Duke engine and use Launcher to launch it, the program always complains about "Unable to construct Applicaiton instance". This is the code for the launcher:

public class Launcher {
    public static void main(String[] args) {
        Application.launch(Duke.class, args);
    }
}

I did some self-research and found out the cause is that the only constructor I have for Duke is Duke(String filepath), while the Application.launch() code for Launcher assumes a constructor Duke(). Indeed, when I added a dummy Duke() to the code, the issue resolves. However, I am not sure if this is the optimal way, since the dummy Duke() is not supposed to be in the project.

My question: How can I tell Application.launch() to take Duke(String filePath) instead of Duke() when creating instance? Or is there any other way around?

![屏幕截图(1435)](https://user-images.githubusercontent.com/97591125/215042791-38666769-3331-46d6-87a8-981dfa090150.png)


</panel>

<panel  header="**5. :fas-info-circle: Checkstyle not found after merged add-gradle-support**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/48" expanded>

Hi I am currently doing the A-Gradle task, and has been following the tutorial provided in https://se-education.org/guides/tutorials/gradle.html.

However, when I tried to follow the tutorial in the "Checkstyle" section, namely the one at https://se-education.org/guides/tutorials/checkstyle.html, I found that the files config/checkstyle/checkstyle.xml and config/checkstyle/suppressions.xml not present in the project, nor was the directory ./config/checkstyle/ present. 

I checked the build.gradle file, and found that the plugin for checkstyle was not there. I have tried with running other gradle tasks such as clean and test, which had no issues.

I wonder if this is normal, and how could I add the checkstyle plugin to my project? Is it necessary?

I will be appreciated if anyone can help! Attached is my screenshot of the project folder and the build.gradle file.

![屏幕截图(1429)](https://user-images.githubusercontent.com/97591125/213987624-54414ed2-f481-4434-b8da-f37171c20bc1.png)


</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/48#issuecomment-1399926136" expanded>

Yes I see...however, I cannot see the files config/checkstyle/checkstyle.xml & config/checkstyle/suppressions.xml anywhere, which seems to be the pre-requisite of any possible setup of checkstyle. Where can we find these files, or will they be provided separately by then?
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/117#issuecomment-1411569391" expanded>

Self-response:

I found that the issue are actually two-fold:
(1) To resolve the URL, hover the mouse over the red unresolved link until it shows "fetch external resources". After successful fetch, the link will turn green
(2) Property "scope" does not exist, please check the documentation
The problematic line is at the line 387 of checkstyle.xml, `&gt;property name="scope" value="public"/>`. When I follows the method of this tutorial, https://github.com/jshiell/checkstyle-idea/issues/525 and change the line to `&gt;property name="accessModifiers" value="public, protected"/>`, the issue is resolved.

Not sure if this is the best way though, or even the expected way.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1417758292" expanded>

Not be the best but just want to share as well :)

![屏幕截图(1445)](https://user-images.githubusercontent.com/97591125/216819775-be7f3f91-65ef-4b83-86e1-99dc40bf827e.png)

</panel>

</panel>


<panel type="info" header="### 42. SUN ..TONG `@yitong241` (8 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Question about where to add the tag**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/45" expanded>

Hello!
For the tags to Level 7 and Level8, should them be added to branch-level-7 and branch-Level-8 or the master brach after merging with branch-level-7 and branch-Level-8?
</panel>

<panel  header="**2. :fas-info-circle: Issue with text ui test**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/28" expanded>

Hello, my runtest.sh only reads the first line of input.txt, may I know what I can do to fix it?




</panel>

<panel  header="**3. :fas-info-circle: Issue with committing after finishing everything**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/12" expanded>

Hello prof, I only committed after I finished till level 6, is there anything I can do to fix this?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/12#issuecomment-1384893469" expanded>

Hello prof thank you for the response, but what if the commit does not satidfy the earlier requirements? For example, "blah" would be considered as a valid input as we should echo it according to Level 1; but in Level 5, it is considered as an error.


</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/12#issuecomment-1384987679" expanded>

thanks a lot prof!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/28#issuecomment-1396700316" expanded>

hi prof you can check my "ip" repo, i tried with some cases, only the first line of input.txt will be read.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/28#issuecomment-1396763687" expanded>

thx! @Junyi00 and @damithc! I think I know where the problem is!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/45#issuecomment-1399976860" expanded>

Thx all!
</panel>

</panel>


<panel type="info" header="### 43. NICH..ALIM `@daytona65` (8 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Irreparable Checkstyle errors**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/262" expanded>

I have tried alot of things so please help.
My import statements:
![image](https://user-images.githubusercontent.com/74140641/225933091-b659bf75-d66a-4e36-994e-90ce3fc670fd.png)

My error:
![image](https://user-images.githubusercontent.com/74140641/225933174-79d96bc5-d119-4671-9e66-937e4c683123.png)

How to fix? have tried rearranging the statements in every imaginable way possible
</panel>

<panel  header="**2. :fas-info-circle: Java compiler in java 17 and not 11**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/216" expanded>

'Error: LinkageError occurred while loading main class GUI.Launcher
 java.lang.UnsupportedClassVersionError: GUI/Launcher has been compiled by a more recent version of the Java Runtime (class file version 61.0), this version of the Java Runtime only recognizes class file versions up to 55.0'

- Sent my .jar file to a few friends and all of them got this error above. 
- Searching the problem online shows that my .jar was compiled with Java 17
- I ran javac --version and found I am running java 17.0.1, even though both my project SDK and gradle JVM are Java 11. 
- How do I change this back to Java 11
</panel>

<panel  header="**3. :fas-info-circle: Grading Script not detecting my tags**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/213" expanded>

I've already pushed A-UserGuide tags, user guide is up on my site, and Ui.png is visible in the showcase site since yesterday. 
In addition I have other optional tags like A-BetterGui, A-Personality and A-MoreErrorHandling. 
I have these tags on my other branches, not my master branch.
Any clue why the dashboard doesn't seem to update? Thanks!

![image](https://user-images.githubusercontent.com/74140641/220002204-eae3782e-7ade-4701-a091-d59a1b988cd5.png)

</panel>

<panel  header="**4. :fas-info-circle: Gradle sync failed: zip END header not found**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/178" expanded>

My last commit was working perfectly, but when I reopened it today, I was met with this error emssage:

![image](https://user-images.githubusercontent.com/74140641/218437177-784b4537-dac6-41cb-9266-2633c8cbe7f3.png)

However, when I got my friend to clone from my repo, my code works fine.

I have tried:
- deleting my gradle files
- invalidating cache
- deleting idea folder
- deleting .gradle folder
- reinstalling Intellij

and whatever I could find online on this issue.

As far as I know, I did not do anything to modify my code after making that last commit and it even works on my friend's computer. So I really have no idea why it cannot run on mine. Any help is appreciated, thanks!

Here is the link to my repo if you'd like to try it out:
https://github.com/daytona65/ip
</panel>

<panel  header="**5. :fas-info-circle: Issue with creating JavaFX project in Gradle**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/175" expanded>

I am unable to create a new JavaFX project with Gradle, I created a new project just to do the JavaFX tutorial but I keep getting this error immediately:
![image](https://user-images.githubusercontent.com/74140641/218363942-9fdfe95d-be33-470f-bfba-cc3d2aadfcac.png)

The import statements for javafx also don't seem to work:
![image](https://user-images.githubusercontent.com/74140641/218364367-785cad11-38dc-4db8-8e5c-ddaf7c173674.png)

The build.gradle file seems to be greyed out as well:
![image](https://user-images.githubusercontent.com/74140641/218364622-1f46680f-8604-4ffc-a8f0-e4997d53ae89.png)



</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/178#issuecomment-1429066167" expanded>

Alright just an update:

Tested this error by cloning the original Duke repo then immediately merging the add-gradle-support branch and the error came up immediately.

In the end this solution from stackoverflow solved it:

![image](https://user-images.githubusercontent.com/74140641/218633156-3ecae199-8bf4-4360-833d-e680d22d7add.png)

An additional error came up: [Error:Unknown host services.gradle.org. You may need to adjust the proxy settings in Gradle]

Fixed it by going to File > Settings > Appearance and Behaviour > System & Settings > HTPP Proxy and unchecking No Proxy, and checking Auto Proxy
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/216#issuecomment-1436538092" expanded>

Resolved by uninstalling Java 17 and installing Java 11 on my system.
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/262#issuecomment-1474876437" expanded>

Thanks daitenshionyan! seems like that works
</panel>

</panel>


<panel type="info" header="### 44. SHEN..ENZI `@shenchenzizoe` (8 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Issues showing sorted personList in UI**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/242" expanded>

Have anyone tried to implement a sort function for the tp?
For our team project, we plan to add a sort function so that contacts can be listed in order (for example, by name alphabetically).
However, the original AB3 is using an ObservableList to manage Persons, which can not be modified. The current "list" and "find" functions are achieved by using a filteredList, which is a subset of the ObservableList. We can set a predicate to filter out the result we want, but the order of Persons can not be changed. We tried to pass a new sortedList into that filteredList, which is finally being proceeded to UI. Nevertheless, it does not work as it seems that the filteredList must be part of the ObservableList, passing other values into it causes issues to ModelManager and affects other functions like "find". 
Does anyone have suggestions about how to solve this? 
Should we change the whole data structure of the ObservableList? Should we write new UI functions so we can pass other lists into it (because for now AB3 only uses the the single ObservableList for UI)?
Would really appreciate any relative guidance and suggestions!:heart:
</panel>

<panel  header="**2. :fas-info-circle: Published UG and Ui.png tag in ip dashboard not updated**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/206" expanded>

I have pushed my UG days ago, but the "Published UG" tag in admin task did not turn green. The A-UserGuide one is updated though. I also posted my Ui.png today before the update time, it is not updated either. 
Is there a difference between A-UserGuide and Published UG? Should I modify anything?

Here is link to my ip repository [branch](https://github.com/shenchenzizoe/ip)

Here's what's showing on my ip progress bar:
<img width="593" alt="image" src="https://user-images.githubusercontent.com/97273558/219697112-60d18320-2159-4727-aa88-c8fe0ac63848.png">


</panel>

<panel  header="**3. :fas-info-circle: Issues building gradle**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/158" expanded>

Has someone encountered similar gradle building issues before? After I installed the gradle, it keeps throwing the error "Could not find or load main class worker.org.gradle.process.internal.worker.GradleWorkerMain" when I click the "build".  However, for the functions like "clean" and "shadowJar", it works fine. I thought it might be a path problem, so I changed mainClassName and archive base name in build.gradle several times, but I haven't figure out the right one. Other things I tried including adding new path to local environment, and running "gradle —stop" and rebuilding, none of them works.
The following are the list of my ip directories and my build.gradle content.  I have been dealing with it for hours and can really use some help :<< (save me!
<img width="310" alt="image" src="https://user-images.githubusercontent.com/97273558/218030113-83a96572-e779-4df7-8c9b-04ec7b0e5113.png">
<img width="760" alt="image" src="https://user-images.githubusercontent.com/97273558/218030375-4a15e10b-ea6f-4f6d-864d-9846f256b2ff.png">
<img width="883" alt="image" src="https://user-images.githubusercontent.com/97273558/218030433-a88312ba-757b-49ec-9de5-71d8ae399f2b.png">


</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/158#issuecomment-1425471085" expanded>

@SPWwj Hiii thank you for the kind reply! I just tried this and the same error occurs, but I will change the directory name to duke then :)
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/158#issuecomment-1426597024" expanded>

Thank you for the suggestions Prof! I have just removed other folders in src/main/java as well as changed folder structures referring to others'. For now I kind of can't find any more differences but the building function still does not work...still trying hard to figure it out
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/158#issuecomment-1427183621" expanded>

hii! I tried .\gradlw clean as well as .\gradlew stop, but the build function (by clicking the button under gradle list) still does not work. However I am able to run my code on gradle. I can also build jar file with it, so I suppose the issue might not matter for now? 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/206#issuecomment-1435446393" expanded>

Thanks Prof! mine is also solved!
</panel>

<panel  header="**8 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/242#issuecomment-1456996829" expanded>

Solved this issue for the current stage. The method I implemented is described in the following link:
https://github.com/AY2223S2-CS2103T-W11-4/tp/issues/49
</panel>

</panel>


<panel type="info" header="### 45. JOEL..O YU `@joellow88` (7 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Using UI during command execution**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/282" expanded>

The design of AB3 is such that the UI components calls `executeCommand(String command)`, which is passed and executed by the Logic component. This works fine for the most part, however, this design also means that Logic has no knowledge of Ui. For most commands this works fine, however, I'm currrently facing a problem where I need to access the Ui elements during execution of a command.

 The only similar command already in AB3 is `help` command - however, `help` command uses a workaround where the CommandResult object generated indicates that the command is a `help` command, which is then checked by the Ui.  This doesn't work for me as I need to access the Ui elements before the CommandResult object is created.

Below is a small sample of what I am trying to do.
```java
public class MainWindow extends UiPart<Stage> {
    private Stage primaryStage;
    //other code

    public Stage getPrimaryStage() { return primaryStage; }
    
    //Calls LogicManager#execute(String)
    private CommandResult executeCommand(String commandText) {...} 
    
}

public class LogicManager implements Logic {
    //other code

    //Has no knowledge of the Ui components that called it
    public CommandResult execute(String commandText) {
        //other code
        
        //Need to access MainWindow#getPrimaryStage() here
        
        //other code
        return new CommandResult(MESSAGE_SUCCESS);
    }
}
```

Of course, a simple solution would be to pass the `primaryStage` as a parameter to the `MainWindow#executeCommand()` function. However, that goes against the architecture of AB3 and for most of the commands, it also does not make sense to pass the primaryStage as an argument to `execute()`.
![ArchitectureDiagram](https://user-images.githubusercontent.com/65859436/227834156-328b6c1f-9ee3-4720-8b8f-2cbc9594914d.png)

I was wondering if anyone has faced a similar issue and if there are any previous solutions to this problem.

Thank you!



</panel>

<panel  header="**2. :fas-info-circle: Code quality - always possible to avoid long methods?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/156" expanded>

From the textbook, 

> Be wary when a method is longer than the computer screen, and take corrective action when it goes beyond 30 LOC (lines of code). The bigger the haystack, the harder it is to find a needle.

I understand the intention behind this code quality guideline. However, I wonder whether there are cases in which having long methods are unavoidable and this guideline has to be disregarded. Or is it always possible to refactor long methods into a few shorter ones?

In my IP, I encountered some situations that I believe having long methods are unavoidable. Would like to know what others did to handle it, or if you would similarly violate the guideline.

**1. Switch case statements**
In a `handleCommand()` method, the different commands are checked using a switch-case statement. If the number of cases is large, would that necessitate an overly long `handleCommand()` method?

**2. JavaFX start method**
The `start()` method is called to start the GUI, and many of the required properties of the nodes on screen are defined there. If there are  many such properties or many such nodes, the `start()` method would easily go beyond the 30 lines guideline.
</panel>

<panel  header="**3. :fas-info-circle: Why is auto-updating of pull request the default behaviour?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/51" expanded>

I refer to the textbook paragraph 

> Textbook → Git & GitHub → Creating PRs 

> You can update the PR along the way too. Suppose PR reviewers suggested a certain improvement to your proposed code. To update your PR as per the suggestion, you can simply modify the code in your local repo, commit the updated code to the same master branch, and push to your fork as you did earlier. The PR will auto-update accordingly.

From what I understand, this means that after we create a pull request, any new changes we push to our fork will be automatically included in the pull request. 

To me, this seem undesirable as pull requests are created once we are relatively confident of our code and ready to merge it with the upstream repo. Meanwhile, pushing code into our fork affects only our own remote repo, so the code may still be in development and not ready yet.

By having a PR update automatically when pushing into our remote repo, we will not be able to push any more code into our own remote repo, unless we are also confident that it is ready to merge with the upstream repo. This defeats the point of having our own remote repo in the first place. 

Would appreciate some clarifications as to whether my understanding of this auto-updating behaviour is correct, and whether there is a way to disable it.

Thanks!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/75#issuecomment-1406121523" expanded>

You shouldn't need to, how are you specifying the file path to where tasks are being stored?

I used the following code to check the current directory Duke is running in.
```
private static void printCurrentWorkingDirectory() {
        String userDirectory = Paths.get("")
                .toAbsolutePath()
                .toString();
        System.out.println(userDirectory);
    }
```

From there, you should be able to specify a relative path to the data file where your tasks are stored.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/120#issuecomment-1414188503" expanded>

> Thanks prof and @hingen for helping out ! I have changed the mainClassName to Duke and set the JDK version to jdk-11 already. However, when i run the Duke, upon the command "bye" the program exits and shows this error.
> 
> ![image](https://user-images.githubusercontent.com/77615600/216375417-99d214e7-98fa-49af-8644-6c919cef30b2.png)
> 
> Appreciate if you can help me out once again. Thank you !

I don't think this is a problem with gradle or the .idea folder anymore. Looking at your code, it seems that your save() function does not account for the case that the file specified does not exist. Can you check to see whether the duke.txt exists in the path you specified? If you have already created duke.txt, you might also want to check if the program runs in the ip directory or the parent folder of the ip directory. If it was the first case, then manually adding `File.separator + "ip"` is redundant.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/282#issuecomment-1484749412" expanded>

I am trying to use JavaFX [FileChooser](https://openjfx.io/javadoc/20/javafx.graphics/javafx/stage/FileChooser.html) object to allow the user to select a file using the OS's default file explorer. To use this, I need to pass the `primaryStage` object into `FileChooser#showOpenDialog(Window ownerWindow)`. However, I have no way of accessing the primaryStage object from within the Logic module.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/282#issuecomment-1485259496" expanded>

Thank you Prof! I have come up with a solution that is working so far.

My solution was to call `MainWindow#execute()` as per normal. However, if the command requires additional Ui input, a `UiInputRequiredException` will be raised. This will be caught in the `MainWindow#execute()` method, and handled by showing the `FileChooser`. The chosen file path will be converted to a string and fed back into the `MainWindow#execute()` method. 

I'm not sure whether this is a 'recommended' use of exceptions, but the solution seems to be working so far, and it solves the original problem of not having access to Ui in the Logic component. Hopefully this is helpful to anyone who is facing the same issue as me.


</panel>

</panel>


<panel type="info" header="### 46. SUM .. YEE `@sumhungyee` (7 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Randomising test cases, is this fine?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/295" expanded>

Hey @damithc prof, I'm implementing an undo/redo functionality for my tp and I'm basically storing denguehotspottracker objects in a modified stack. For my test cases i create a few randomised denguehotspottracker objects (random number of random people) and place them into the stack. I then perform undo, redo and save to try to break the system. (So this part is deterministic.) Is this an okay way of testing?

Basically my idea is I'm testing the data structure, so i think it should be fine if the dht's are random?
</panel>

<panel  header="**2. :fas-info-circle: Problem with FXCollections.observableArrayList(), setAll in uniquepersonlist.java**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/289" expanded>

![image](https://user-images.githubusercontent.com/113227987/228273908-1350ad89-a5d2-47e4-9858-427bb617659c.png)
persons is a type List\&gt;Person\>, internalList is of type ObservableList\&gt;Person\>
setAll clears the list instead of setting everything. somehow only does this for persons not integers  pls send help prof!  :( @damithc 

</panel>

<panel  header="**3. :fas-info-circle: Help: As per the tP progress dashboard, you have not yet merged any PRs that follow the strict forking workflow (i.e., in the past two iterations and the current iteration so far).**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/270" expanded>

I accidentally merged my master branch instead of creating new branches to be merged, and I think as a result these are not detected by the system, even though I have already tagged the milestones. Can I have some help? I think v1.2 milestones have closed as well.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/270#issuecomment-1476724740" expanded>

thanks a lot prof
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/289#issuecomment-1487068925" expanded>

```
public void setPersons(List<Person> persons) {
        requireAllNonNull(persons);

        ObservableList<Person> test = FXCollections.observableArrayList();
        Person p = new Person(new Name("a"), new Postal("111111"), new Date("2000-01-01"), new Age("11"),  getVariantSet("DENV1"));
        test.setAll(List.<Person>of(p));
        System.out.println(test);
        test.setAll(List.<Person>of(p));
        System.out.println(test);

        if (!personsAreUnique(persons)) {
            throw new DuplicatePersonException();
        }

        System.out.println("UNIQUEPLIST: " + persons);
        System.out.println("in: " + this.internalList);
        this.internalList.setAll(persons);
        System.out.println(this.internalList);
    }
```
    Thanks prof. Also, somehow when changing from ObservableList<Integer> to ObservableList<Person> the test code (above) works now, but the main setAll code still fails
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/289#issuecomment-1487102354" expanded>

Resolved. Issue was persons is mutable. Replaced with List.copyOf(persons)
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/295#issuecomment-1489046543" expanded>

@damithc  Thanks for replying prof. I personally felt at that time that it was better to test more generally, because whenever i perform a change to the ab3 (my mistake, i said dht) and save it to the stack, the change could come in the form of a delete or edit, or something else. But what i really want is to save previous iterations of my ab3, whatever the change results from delete, edit or something else.

So creating random ab3s really makes the problem clear, that no matter what changes have been made, I'm saving them in the stack.

Also there isn't a lot of dummy data to go around :/
</panel>

</panel>


<panel type="info" header="### 47. LIM ..DWIN `@9fc70c892` (7 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Feedback - Proposal : Swap Phase 1s Part 1 and Part 2 for future iterations for PE testing**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/375" expanded>

I don't know if this is the correct place to put feedback and I realize that a large part of this is due to me, student error, not reading instructions clearly, I had assumed that reporting of UG is not allowed in Part 1 thinking "or else what is the point of part 2?".

I understand the rational behind ordering part 1 and 2 this way. It is meant for you to test the program as if you are a first time user (under the scenario of a controlled test, which is done in real world testing) and to test if it works as intended, and not test if you are someone with understanding of what is going on behind it (which is primarily done by developers).

**Rationale for this proposal**
1. Instructions say:
`Test based on the Developer Guide (Appendix named Instructions for Manual Testing) and the User Guide`

But **if there is no Instructions for Manual Testing** (or minimal, such as -in my case; all it says is "run using `java - jar`") in the DG, then student will have to resort to browsing through UG to retrieve all the commands needed to test. This can/will cause them to be focused on UG errors if there are any.

2. So that students have a better idea of what the application is about. 

if there are any other individuals who would like to discuss this particular thought, feel free to comment below
</panel>

<panel  header="**2. :fas-info-circle: I recall one of the lectures discussing about Google**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/145" expanded>

where in the lecture it was discussed about the success and failures of software engineering.

While it's a good video to take a break from work, but don't fall into the YouTube marathon rabbit hole :p

> It's a fun ride: but in 2010, Google gave it a million dollars as a potential "future of transit" - [Tom Scott](https://www.youtube.com/@TomScottGo).

Here is the link to the video: [Google gave the Shweeb $1,000,000.](https://www.youtube.com/watch?v=7qNOtgrIjO4)
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/22#issuecomment-1396386300" expanded>

I'm not a TA but, while it is true that you can handle errors purely using if else statements, I think the idea is to get you to - if you have never done it before; create custom exceptions.

At right now I believe it's only a "recommendation" rather than a "must" to implement. But creating it now at this early stage would allow you to carry it forward to future stages of this IP, rather than having to _redo_ all the previous week's work to implement error handling (if needed, I actually haven't peered into the abyss).

Here is a scenario you might find custom exceptions useful:
Other people using your code, and your code implementation is not visible to them. 

Throwing `java.lang.NumberFormatException.forInputString` may not very be obvious to other programmers that there is something wrong with their input rather than your code. Throwing `DukeAPIException.Invalid.Input` may be better. 

Or maybe you want to catch internal exceptions like `SensitiveInternalProgram.Invalid.CallBackToCore(Sensitive msg)` and converting it into `PublicFacingProgram.System.Failure(Unable to process, sorry for inconvenience)`.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/99#issuecomment-1409605989" expanded>

It is possible but you need to consider how to save if you have your Duke to save upon exit.

But what other ways are there? Clicking on top right/left hand side? Typing a different command? Alt F4?

Regarding second point 

You can get around the user not being able to read bye message by introducing some delay perhaps.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/99#issuecomment-1409607003" expanded>

Now if your question is "is it against grading criteria", then sorry I am not able to answer your question (I'm not TA). But there is a need for safe exit if you wish to write tasks to file 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/98#issuecomment-1409611241" expanded>

Another way of getting the similar error message as OP is to fill in the necessary things into Gradle settings, but not refreshing Gradle build itself (e.g. Gradle didn't install dep)

Note: writing this because @gohyongjing is not OP but has found the solution for the problem that they faced of the same category.

</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/375#issuecomment-1508322267" expanded>

> I don’t think there is a limitation during part 1 to report on functionality bugs only. I spotted some documentation bug but I just noted it down during part 1 instead of reporting it directly due to time constrains in part 1.

Yeah, thats the student error part on my behalf of not reading the "terms and conditions" clearly. After all, these two information is pretty close to each other. I realized that after submitting. 

Though, is there really a need to restrict the testing of `jar`?
</panel>

</panel>


<panel type="info" header="### 48. DO H..UONG `@dohaduong` (7 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1414868242" expanded>

Here's mine followed the tutorial
![image](https://user-images.githubusercontent.com/110105565/216510380-16df8fc2-cc99-42cb-9431-7d250a5b0926.png)

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/259#issuecomment-1477481073" expanded>

Yeap! I agree one change could lead to so many other modifications, but I think we would be able to slowly get used to the code base eventually :)
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/264#issuecomment-1477483852" expanded>

Thank you!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/272#issuecomment-1482238759" expanded>

agree, i think import static is mostly used to access static members (constants, etc) of other classes/interfaces, so it's up to you which one you prefer
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/267#issuecomment-1482240524" expanded>

I was confused about this part too, cuz seems like both ways work. Theoretically, would there be any difference/issue if we swap the order?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/247#issuecomment-1482242510" expanded>

thanks for sharing, the article is very interesting! 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/267#issuecomment-1484022880" expanded>

> [<img alt="@damithc" width="40" height="40" src="https://avatars.githubusercontent.com/u/1673303?s=80&amp;u=1732a87200a4da87271fefb1f5ebaa20a482f286&amp;v=4">](/damithc)
> Member
> ###
> ** [damithc](/damithc) ** commented [Mar 24, 2023](#issuecomment-1482664295)

Oh, I see, thank you prof for the clarification!
</panel>

</panel>


<panel type="info" header="### 49. LIU ..IXIN `@JamesLiuZX` (7 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/152#issuecomment-1423917049" expanded>

1. Assertions in Java are mainly used to help you debug during the development phase, such as checking the state/value of an object, or validity of arguments, passed for example into your Parser class. It should be as much as necessary to help you debug your core logic in where interactions between objects are involved, such as Parser and Storage. 

2. Assertions cannot be used to test graphical components such as JavaFX, as assertions are intended to test program logic and the state of variables, rather than the behavior or appearance of graphical elements. To test graphical components, you would typically use a testing framework that is specifically designed for that purpose, such as TestFX. 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/155#issuecomment-1424364701" expanded>

Hi, I think it depends on the exact extension you choose. For example for `C-Help`, it likely requires adding a new 'help' command to display a help page; while for `C-FriendlierSyntax`, it involves modifying existing commands. So it is up to you and based on which exact one you choose. 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/157#issuecomment-1425136715" expanded>

Hi, if its the latest commit in branch B that you want to edit, normally I'd just `git reset HEAD `and recommit the changes with the updated committed message then push. 

In response to your question, AFAIK it only affects the branch that you run interactive rebase on. Where rebase plays back the latest n commits, interactive replay gives you the chance to edit the individual commits, by editing the interactive rebase script. You can achieve this by changing the `pick` to `edit`. 

For example, if these are your latest commits and you want to change the latest one, 
```
310154e Update README formatting and add blame
f7f3f6d Change my name a bit 
```
This should be your script:
```
edit 310154e Update README formatting and add blame
pick f7f3f6d Change my name a bit
```
You can refer to this[ tutorial](https://git-scm.com/book/en/v2/Git-Tools-Rewriting-History#:~:text=The%20interactive%20rebase%20gives%20you,first%20one%20it%20will%20replay.) for more information. 
What `noop `(no operation) essentially means is that you either did not edit the commits, or when you rebase a branch that's ahead in commits to a branch that's behind in commits, e.g. when you rebase `master` onto `branchA`.

In your case it should be the former and you can try editing the script in the manner shown in the tutorial.

Let me know if you need any further clarification. Cheers :)

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/167#issuecomment-1426944692" expanded>

Hi, for git tagging a previous commit, you can use
`git tag -a tagname commitId -m "Message here"`
You can refer to [here](https://stackoverflow.com/questions/4404172/how-to-tag-an-older-commit-in-git) for the example.

For branching a previous commit, you can `git branch` a new branch with the new branch name and commitid, as seen [here](https://stackoverflow.com/questions/2816715/branch-from-a-previous-commit-using-git#:~:text=First%2C%20checkout%20the%20branch%20that,name%20then%20create%20a%20branch!) 

Hope that helps!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/158#issuecomment-1426945587" expanded>

Hi, it could be a problem with the gradle cache. Perhaps you could try emptying the `.gradle/caches` after running `./gradlew --stop`. 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/156#issuecomment-1426948131" expanded>

Hi. Just to add on a little further, there are fewer than 10 commands in our program, so a switch statement is fine as it is relatively readable and not exceedingly long. In the future when there are more tasks, like what @BoAi01 said we can use a Hashmap to map the commands to the methods. We can also store the commands in another package under duke.

Regarding the second point, I think for the rule of 30, code refactoring mainly serves to break down the complexity of the method into smaller manageable chunks, so it's more about making the logic less complex and more concise instead of reducing LOC. If there are many variables and components that you have to define regardless, then the 30 LOCs serves more as a guideline like what @damithc mentioned. 

Hope that helps. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/87#issuecomment-1426948784" expanded>

Thanks for the help @SeeuSim. I used JavaFX 11 instead of 17 and it works too! If anyone else is facing difficulty with this problem, this line from the textbook fixed it for me.
`Set the JAVA_HOME/JDK_HOME system variables to point to /Library/Java/JavaVirtualMachines/zulu-11.jdk/Contents/Home`
Since our devices come pre-installed with a Java version that is not 11, for the program to work we have to make sure we either uninstall it cleanly (from personal experience is hard), or point the JDK towards the downloaded Azul version.

Cheers and thanks Seeu Sim for the solution!
</panel>

</panel>


<panel type="info" header="### 50. PANG.. WEI `@pangrwa` (7 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: User Guide [Invalid YML front matter]**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/300" expanded>

![Screenshot 2023-03-31 at 12 40 21 PM](https://user-images.githubusercontent.com/76247607/229024158-8037970f-d1f3-48ad-8e36-26578c9c9ef9.png)

I am not sure why the GitHub pages are not updated accordingly to the markdown file that we have in Github. This seems to be the error but we are not sure what is the problem. Is there anything we can do about it?
</panel>

<panel  header="**2. :fas-info-circle: _config.yml file**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/235" expanded>

Can I check if it's okay to change the markdown inside the .yml file? 

<img width="397" alt="Screenshot 2023-03-02 at 12 20 46 PM" src="https://user-images.githubusercontent.com/76247607/222330378-47f7d888-9a16-4872-b900-5e002f157bcc.png">

In this case from kramdown to GFM like I did. 
</panel>

<panel  header="**3. :fas-info-circle: Unsure why my Launcher.main() is taking very long to run**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/142" expanded>

The application will still pop up after I run `Launcher.java` but I'm not sure what's with the lines of red code in the command line. Does anyone know what this mean?

<img width="1431" alt="Screenshot 2023-02-05 at 12 09 17 AM" src="https://user-images.githubusercontent.com/76247607/216777629-55c2d0ec-d122-4100-a38d-976d570da44e.png">

</panel>

<panel  header="**4. :fas-info-circle: merging add-gradle-support into main branch**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/88" expanded>

For A-Gradle, I know that we have to merge the add-gradle-support into the master branch. Can I ask why` git merge add-graddle-support` will work even though there is no such branch that exists in my local repo? Although it exists in the remote repo, but how can I identify that it exists somewhere in my local repo? 
</panel>

<panel  header="**5. :fas-info-circle: Level-8 LocalDate object parsing of dates**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/81" expanded>

Teach Duke how to understand dates and times. For example, if the command is `deadline return book /by 2/12/2019 1800`, Duke should understand `2/12/2019 1800` as 2nd of December 2019, 6pm, instead of treating it as just a String.

`LocalDate d1 = LocalDate.parse("2019-12-01");`: Since parse takes in this format. 
Do we have to change the format of the date given to us? I also wish to ask if there is another date format randomly given by a user, how can we make our code as flexible as possible to parse in different kinds of format of the date?  
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/142#issuecomment-1416795568" expanded>

Is it because that my program is running? I notice that it's fine after I switch off the program. 
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/300#issuecomment-1491319300" expanded>

We have fixed it, it's because we didn't put the title!
</panel>

</panel>


<panel type="info" header="### 51. LEE .. WEI `@Beebeeoii` (7 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Window not showing on Linux KDE**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/186" expanded>

**Running: Manjaro KDE**

I am encountering an issue when if I have `stage.setResizable(false);` for my window, the window does not show up properly. Only a line is shown as shown below.

![image](https://user-images.githubusercontent.com/55170539/218907418-cec1732b-579a-4eb7-8d1d-55eb46d9d928.png)

This, however, works fine on macOS and Windows. There are no error messages. Not sure if anyone found any tricks to resolve this.

**Note:**
I have also tried launching AB3 (which shows up normally since the main window is resizable). However, the help window (which is not resizable) is also suffering from this issue.

## Some relevant issues:
https://github.com/nus-cs2103-AY2021S1/forum/issues/229
https://github.com/javafxports/openjdk-jfx/issues/222


</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/1#issuecomment-1379073072" expanded>

i am running on M1 macOS 13.0.1 and it seems to work fine for me.

```zsh
java -version
﻿﻿﻿openjdk version "11.0.17" 2022-10-18 LTS
OpenJDK Runtime Environment Zulu11.60+19-CA (build 11.0.17+8-LTS)
OpenJDK 64-Bit Server VM Zulu11.60+19-CA (build 11.0.17+8-LTS, mixed mode)
```

maybe can try other Java JDK builds like [the one suggested in the webpage](https://www.azul.com/downloads/?version=java-11-lts&os=macos&architecture=arm-64-bit&package=jdk-fx) if the issue persists
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/19#issuecomment-1387242949" expanded>

just sanity check, did you add the ssh key to your github account? could you try executing `ssh -T git@github.com` in terminal, you should get a response similar to:
```
Hi Beebeeoii! You've successfully authenticated, but GitHub does not provide shell access.
```
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/19#issuecomment-1387308327" expanded>

by default the public and private keys should be stored in `~/.ssh`. from your screenshot above, you should have the files `alextang809-GitHub.pub` and `alextang809-GitHub` in the directory `~/.ssh`.

could you try logging into github, navigate to Settings -&gt; SSH and GPG Keys. If you have yet to add your SSH key here, copy the contents from the `.pub` file and create a new SSH key 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/186#issuecomment-1430674271" expanded>

thanks this works like a charm !
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/337#issuecomment-1498478892" expanded>

tested on Manjaro. looks okay!

![image](https://user-images.githubusercontent.com/55170539/230272532-ba2ff47d-f40d-406b-a7fd-e9522688a3b3.png)

</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/359#issuecomment-1501235197" expanded>

could you try without the spacing before `{\:toc}`, so something like:

```
- Table of Contents
{\:toc}
```
</panel>

</panel>


<panel type="info" header="### 52. HAO ..ZEYU `@PROGRAMMERHAO` (7 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Unable to push to master after adding Ui.png on github and local refactoring**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/195" expanded>

Hello I just made some commits directly on github to update the user guide and the Ui.png, following the instructions on the product website.

Now my sourceTree indicates that I have 5 pull updates. 

<img width="86" alt="image" src="https://user-images.githubusercontent.com/88484192/219306260-171fa6a4-38b7-429d-975d-9188d322f9b4.png">

However, after uploading my Ui.png I made some changes to my code locally and wish to push the code to the fork again. This time the sourceTree failed to push to the fork. May I ask if I need to pull first before pushing? Will my local changes be overwritten if I pull now? (By the way local changes have been committed)

The picture below is my error page when pushing
<img width="862" alt="image" src="https://user-images.githubusercontent.com/88484192/219306832-b1ed0bdb-4534-4bc2-bf82-dead8f04f108.png">
<img width="861" alt="image" src="https://user-images.githubusercontent.com/88484192/219306913-c41fbca2-cc2f-439b-8569-f346e902d05a.png">

Thanks for helping!

</panel>

<panel  header="**2. :fas-info-circle: Error while running Duke using JavaFX**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/100" expanded>

Sorry for troubling, but I have another issue while using javaFX. When I tried to call duke from the launcher like this:
```
public class Launch{

    public static void main(String[] args) {
        Application.launch(Duke.class, args);
    }

}
```

I got an error saying: java.lang.NoSuchMethodException: duke.Duke.<init>()

My Duke looks as follows:

```
public Duke(String filePath) {
        ...
}

...
 
public void start(Stage stage) {

        //The container for the content of the chat to scroll.
        scrollPane = new ScrollPane();
        dialogContainer = new VBox();
        scrollPane.setContent(dialogContainer);
        userInput = new TextField();
        sendButton = new Button("Send");
        AnchorPane mainLayout = new AnchorPane();
        mainLayout.getChildren().addAll(scrollPane, userInput, sendButton);
        scene = new Scene(mainLayout);
        stage.setScene(scene);
        stage.show();

} 


public static void main(String[] args) {
        new Duke("data/duke.txt").run();
 }
```

However, this issue does not happen when I create another Test.java file to put start method in like this:
```
public class Test extends Application {

    public void start(Stage stage) {
        Label helloWorld = new Label("Hello World!"); // Creating a new Label control
        Scene scene = new Scene(helloWorld); // Setting the scene to be our Label

        stage.setScene(scene); // Setting the stage to show our screen
        stage.show(); // Render the stage.
    }

}
```
Could anyone help me with this? Thank you so much!
</panel>

<panel  header="**3. :fas-info-circle: JavaFX runtime components are missing**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/98" expanded>

When I tried to follow the tutorial and setup javaFX, I get a "JavaFX runtime components are missing, and are required to run this application" error, what could have gone wrong?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/98#issuecomment-1409621573" expanded>

Thank you guys for helping! It indeed turned out that the problem was caused by not running main in another class, as what @gohyongjing described. Really apppreciated!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/100#issuecomment-1409696941" expanded>

Thank you so much for helping!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/185#issuecomment-1431068620" expanded>

Hi! I downloaded the jar file and discovered the same thing. It is working fine.

<img width="687" alt="image" src="https://user-images.githubusercontent.com/88484192/218997331-51903f36-c359-4afa-a1d9-0935f0cdc48a.png">

</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/195#issuecomment-1432705503" expanded>

@Junyi00 Thank you so much for your comprehensive answer! Really appreciated.
</panel>

</panel>


<panel type="info" header="### 53. CHON..ABEL `@IsabelChong` (7 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Releasing a new JAR file after v0.2**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/212" expanded>

I want to release a new JAR file. Here is a snippet of the instruction in the email sent:

<img width="1010" alt="image" src="https://user-images.githubusercontent.com/71481877/219948676-1c30f850-e5f4-44f5-8434-444626c3cfda.png">

Since we already have a `v0.2` tagged with `A-Release`, do we release our new file as `v0.3`?

Also, there seems to be a need to tag this release. Can I just tag it as `v0.3` as well?
</panel>

<panel  header="**2. :fas-info-circle: JavaFX: Classes Loaded from Unnamed Module**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/127" expanded>

I'm now at `Level-10` doing the part on "1. learning JavaFX basics" and have completed the [JavaFX tutorial @SE-EDU/guides](https://se-education.org/guides/tutorials/javaFx.html). 

After running `Launcher.java`, I always get this error below, but the basic GUI does start up.

 <img width="765" alt="image" src="https://user-images.githubusercontent.com/71481877/216247417-f3925c4b-a1bd-4671-bc27-5ef1e738b65d.png">


Searching online led me to [stackoverflow](https://stackoverflow.com/questions/67854139/javafx-warning-unsupported-javafx-configuration-classes-were-loaded-from-unna) but I'm not sure where I am supposed to make sense out of it in my code. Below is a snipshot of the solution given:
<img width="668" alt="image" src="https://user-images.githubusercontent.com/71481877/216248310-8159f0a7-7255-42e0-85ce-b3aacad03b0e.png">


Anyone knows why and what this error is coming up?


</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/206#issuecomment-1434823660" expanded>

Hi! In regards to the Published-UG, I believe it meant the enabling of github pages to the correct source. I tried accessing your [page](http://shenchenzizoe.github.io/ip) and it does not exist.

<img width="617" alt="image" src="https://user-images.githubusercontent.com/71481877/219699039-13fedf3b-c18b-4837-8922-4de6c59c8f18.png">


Have you done the following steps under [A-UserGuide](https://nus-cs2103-ay2223s2.github.io/website/schedule/week6/project.html)?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/211#issuecomment-1435978134" expanded>

Hi! Here's a relevant issue #206 which you can look into.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/212#issuecomment-1435981847" expanded>

Alright thanks prof!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/225#issuecomment-1443386847" expanded>

I would also really appreciate it if someone could help me test as well! Thought it would be better to not split it into several issues.

You can download my file [here](https://github.com/IsabelChong/ip/releases/download/v0.3/berry.jar). Similarly, just navigate to the directory and run `java -jar berry.jar`.

Thank you!
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/225#issuecomment-1445004131" expanded>

@Lava-Iris Thanks for letting me know, and I'm glad that it is running without any issues!

It's great to hear that you find the UI cute as well. I just added in two of my favourite characters~
</panel>

</panel>


<panel type="info" header="### 54. ZHAN.. JIE `@salty-flower` (7 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: iP Level-5: Exception as Control Flow?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/22" expanded>

I am bit confused by the description. 
If we are to print error messages for the invalid inputs specified, then these type of error cases are *known* (or, *expected*); I could handle them just like other commands (my design: match with Regex, then respond).
If I am to raise exceptions and then catch, wouldn't that be using exceptions as control flow mechanism (which we are told to avoid in CS2030S)🤔
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/5#issuecomment-1383356574" expanded>

I prefer `ls -a` too. Or even just `vim .gitignore` - trust me, it won't be very painful to edit a plain text file with vim :)
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/20#issuecomment-1396600270" expanded>

I would like to share my design and get comments here too :). First of all, I introduced an interface named `ICommand` when implementing `Level-1`.
```java
public interface ICommand {
    boolean canTake(String s); // Is that my business?
    void take(String s); // Respond to it!
}
```
And in my dispatcher, there is an `ArrayList` to store all the `ICommand` objects. It basically iterate through the `ArrayList` (_you can take meh? if can do it lah, if cannot then lemme ask the next one lor_). Before that, I check if that's a exit command - `bye`, and if no one takes that, fall back to a default handler. Here you go:
```java
if (Objects.equals(expr, "")) return;
if (CommandHelper.checkAndRun(exitHandler, expr)) {
    toExit.run();
    return;
}
if (CommandHelper.checkAndRun(handlerRegistry, expr) ||
        CommandHelper.checkAndRun(errorRegistry, expr)) {
    return;
}
this.defaultHandler.take(expr);
```
And the dispatcher provides a method to register _command_ s (I use the name _handler_ as well when `Level-5` comes. Do inform me if you have a better name in mind xD)
```java
dispatcher.setDefaultHandler(new HThrowException());
dispatcher.registerCommand(new HAddTask(ts));
...
dispatcher.registerError(new ETodoEmptyDescription());
...
dispatcher.setExitHandler(new HBye());
```
So yeah, in order to add a new command, I need to implement another `ICommand` class and add one line of `dispatcher.registerCommand(new HNewCommand());`. Error cases can be added in the exact same way, thus I raised the question "why I need exceptions" in #22 .
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/247#issuecomment-1459615528" expanded>

Wow! Interesting article 🤔
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/281#issuecomment-1484084246" expanded>

Good question🤔 curious too
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/269#issuecomment-1488452103" expanded>

To add on, these days [**Cursor**](https://www.cursor.so/) looks promising too. Free alternative to Copilot, huh.
</panel>

<panel  header="**7 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/349#issuecomment-1500816530" expanded>

According to [W12 tP Info Page](https://nus-cs2103-ay2223s2.github.io/website/admin/tp-w12.html), it states that:
> Allowed in the v1.4 milestone:
> 
> fixing bugs (but not feature flaws)
> improving documentation
> improving code quality
> improving tests
> removing features

So I guess such bug fixes should be acceptable? 🤔
</panel>

</panel>


<panel type="info" header="### 55. JERO.. NEO `@jerome-neo` (6 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: PlantUML not rendering same image as original DG**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/266" expanded>

Following the steps to install `Graphviz` for Windows and MacOS in IntelliJ, the resulting diagram for `StorageClassDiagram.puml`  did not look like the one in the developer's guide in both operating systems.

The image attached shows the rendered diagram. The file `StorageClassDiagram.puml` was never modified.

![StorageClassDiagram](https://user-images.githubusercontent.com/83827415/226192717-2754d774-9e50-4be9-b2f8-c06b7842d12d.png)

Any help/advice is appreciated, thank you!

</panel>

<panel  header="**2. :fas-info-circle: Gradle stopped working suddenly**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/79" expanded>

I'm running duke on Intellij and have managed to integrate the Gradle support before. Just recently, I was running my Duke.java file again and this error suddenly popped up.

```
An exception occurred applying plugin request [id: 'com.github.johnrengelman.shadow', version: '5.1.0']
> Failed to apply plugin [class 'com.github.jengelman.gradle.plugins.shadow.ShadowBasePlugin']
   > Could not create service of type OutputFilesRepository using ExecutionGradleServices.createOutputFilesRepository().

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output. Run with --scan to get full insights.
```
Does anyone know what could be the reason for this error? 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/79#issuecomment-1407295425" expanded>

Thank you all for your input and explanations! It seems that restarting my computer resolved the issue.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/266#issuecomment-1475927968" expanded>

My temporary get around for this issue is to run the files on Visual Studio Code with the extension, [PlantUML](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml). This renders `StorageClassDiagram.puml` properly.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/266#issuecomment-1479645295" expanded>

Thank you all for the suggestions! Unfortunately, changing line 14 did not work for me. I'll try downgrading IntelliJ and PlantUML.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/266#issuecomment-1479734402" expanded>

Yes, that works! Thanks for saving me all that trouble @eugenetangkj, forgot about the rest of references to `Storage`.
</panel>

</panel>


<panel type="info" header="### 56. TAN ..ERIE `@valerietanhx` (6 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Is refactoring allowed in v1.4?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/351" expanded>

Hi! My team is looking to refactor a part of our code to improve readability on our end. There will be no change in features on the user side; the refactoring only changes the path taken by user input internally. Would this be acceptable for v1.4? My thinking is that it falls under code quality, so it shouldn't be an issue, but wanted to make sure!
</panel>

<panel  header="**2. :fas-info-circle: text-ui-test no longer working**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/57" expanded>

Hello! For some reason, it seems my input.txt is no longer being read, and my ACTUAL.TXT doesn't contain anything else other than the lines initially printed when Duke is first started up. I've included screenshots of my EXPECTED_UNIX.TXT, input.txt, and ACTUAL.TXT. It seems nothing is being read at all...

I'm not sure when this behaviour started; am wondering if this has to do with Level 7 and loading data in from the hard drive, or if it's another issue I should be concerned about :O Any input (haha) would be appreciated!!

Edit: if it helps, I've only done up till Level 8 for now.

<img width="700" alt="Screenshot 2023-01-25 at 1 06 40 AM" src="https://user-images.githubusercontent.com/110474344/214359955-8ad2ebec-e802-431e-be24-853494ab879a.png">
<img width="494" alt="Screenshot 2023-01-25 at 1 06 36 AM" src="https://user-images.githubusercontent.com/110474344/214359967-1a71d4cb-0350-4129-ac53-d8c4e686fafe.png">
<img width="719" alt="Screenshot 2023-01-25 at 1 06 31 AM" src="https://user-images.githubusercontent.com/110474344/214359975-6c94a6a6-8d3e-442d-a94f-c669587fa5d4.png">

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/57#issuecomment-1403091013" expanded>

Hello! @hingen it seems `runtest.sh` results in `ArrayIndexOutOfBoundsException: Index 4 out of bounds for length 4` when trying to load my data from the file saved in the hard drive. The weird thing is that the error doesn't occur if I'm just rerunning Duke normally outside of the test (i.e. the data gets read correctly). Also, even if I've deleted the old data (so it's a "fresh start" for Duke), the exact same error occurs when I try `runtest.sh`, even though the only time I have a `[4]` across all my different files is when trying to load old data.

Currently, the list of tasks is saved in the following format in the text file:
_event 28/1/2023 1700 28/1/2023 1800
project meeting_

i.e. [task type] [date] [time] [date] [time]
[desc]

Additionally, not sure if this is related, but I also have a `dos2unix: command not found` error :O it's been showing all this while if I'm not wrong and the test has been running fine till now though :")

<img width="858" alt="Screenshot 2023-01-25 at 12 42 12 PM" src="https://user-images.githubusercontent.com/110474344/214481590-c29cc013-3dc8-4636-b90e-510de7d780de.png">

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/57#issuecomment-1406062457" expanded>

Hello!! @hingen turned out to be right; I forgot to delete `&gt;project_root>/text-ui-test/data` :") Thanks for pointing it out!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/298#issuecomment-1491170958" expanded>

Hi! A few of our team members are also experiencing this, though we're not sure how to fix it :")
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/351#issuecomment-1500829067" expanded>

Alright, thank you!! :)
</panel>

</panel>


<panel type="info" header="### 57. CHU ..TING `@cyiting` (6 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Code does not compile after organising classes into packages**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/84" expanded>

![Screenshot 2023-01-29 at 2 13 24 AM](https://user-images.githubusercontent.com/75712959/215283876-72e5a7d7-ce8d-4cc1-89df-19380fa84b8e.png)

Hi, I have organised my classes into packages. My code works fine when I run it on IntelliJ, but when I try to compile it, I run into these errors.

Why is this so, and how can I solve this? Thank you all for responding!
</panel>

<panel  header="**2. :fas-info-circle: Clarification on Weekly Quiz Early Submission Deadline**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/35" expanded>

Hi, from what I know, the course website states that the early submission deadline is within 4 days of the lecture i.e on Monday. 

I submitted the week 2 lecture quiz on Monday this week. But the participation dashboard reflects that I did not do so within the early-submission window. Can I just clarify when the deadline is again?
</panel>

<panel  header="**3. :fas-info-circle: Cloned ip repo does not show up in SourceTree**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/10" expanded>

Hello, I have cloned the ip repository (using CLI) according to the steps on the course website. I can open/view the project on IntelliJ, but on SourceTree, it shows up under "Remote" instead of "Local". Is there a way to fix this? Or should I delete the repo and try again?
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/10#issuecomment-1384794499" expanded>

Okay, thank you!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/84#issuecomment-1407536352" expanded>

@Junyi00 @BoAi01 Thank you for your replies, but `Ui`, `Storage` and  `Duke` exist in the same package and I have already imported `duke.exception` in my class files. Any idea why this still happens?
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/84#issuecomment-1408034667" expanded>

Thank you all for your inputs.
</panel>

</panel>


<panel type="info" header="### 58. JERE..MING `@jeremykhoo-NUS` (6 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: A-JavaDoc tag not detected**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/219" expanded>

![javadoc](https://user-images.githubusercontent.com/73585045/220073634-c660dac1-0227-4394-9138-f4057e3cbf21.png)
I had committed the A-JavaDoc tag a week ago
![ip tracker](https://user-images.githubusercontent.com/73585045/220073927-5c5b8f4f-2150-4535-8429-a863320281a2.png)
but it doesnt show up in tracker 

@ganeshniyer

</panel>

<panel  header="**2. :fas-info-circle: Where would you use enums?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/65" expanded>

In week 2 the last extension was to add enums, I know its "if-applicable", but I'm just curious if any of your guys implementation uses enums. I don't see where you would use enums that? would it be for the different keywords that the user gives? "delete" "mark" "unmark" and so on? or the different types of tasks "todo" "deadline "event"....
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/65#issuecomment-1410404745" expanded>

wow thanks guys. I actually found it useful to use enums to ignore caps on the commands. since enums can hold methods
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/215#issuecomment-1439505941" expanded>

I have your v1.1 release (from 11 mins ago). I run Arch Linux. it is working on Arch Linux
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/222#issuecomment-1441275128" expanded>

![smoke test](https://user-images.githubusercontent.com/73585045/220836410-55d5f0de-527c-478c-9429-3f6daf1ced5b.png)
runs on native Arch Linux
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/225#issuecomment-1445025975" expanded>

Both run fine on Native arch linux
</panel>

</panel>


<panel type="info" header="### 59. VIGN..ARAN `@vigonometry` (6 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Runtime error stating JavaFX API is version 19.0**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/196" expanded>

System Details: Macbook Pro
Processor: Apple M1 Pro (ARM)
OS: Ventura 13.1

Despite only having one JavaVirtualMachine (i.e. the recommended ZuluJDK11), when my friend (Windows 11, AMD) ran my released jar file [here](https://github.com/vigonometry/ip/releases/tag/A-Release) for smoke tests, he receives an error stating that:

> Loading FXML document with JavaFX API of version 19 by JavaFX runtime version of 11.

![photo_2023-02-16_20-07-28](https://user-images.githubusercontent.com/88077703/219375595-c27ec334-0440-4e27-ab85-636ebe6f5b41.jpg)

Would really appreciate some help regarding this matter
</panel>

<panel  header="**2. :fas-info-circle: Use of self-created packages to neaten codebase**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/32" expanded>

Hi teaching team, is it all right for us to move our core functions to classes within a package to neaten our code base and make debugging easier?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/32#issuecomment-1398603799" expanded>

Apologies for the delayed response. I'd moved some of my task classes to a package for week 2 but was not aware that it was a task for week 3. 

Thanks for your help!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1431036931" expanded>

![Screenshot 2023-02-15 at 5 50 00 PM](https://user-images.githubusercontent.com/88077703/218993157-9043f139-b5f6-4c6e-88ce-86ef293e12be.jpg)

Simple GUI using the FXML tutorial, inspired by the Argentinian jersey with few CSS mods :))
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/196#issuecomment-1433372384" expanded>

> 

Much appreciated, will attempt to use this.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/198#issuecomment-1434110056" expanded>

I used `./gradlew build clean && ./gradlew build` to rebuild the project.
You may wish to refer to @jmestxr and set the javaFxVersion to 11

Additionally in your FXML files you should change the headers from `&gt;fx:root...xmlns="http://javafx.com/javafx/19" xmlns:fx="http://javafx.com/fxml/1">` to `&gt;fx:root...xmlns="http://javafx.com/javafx/" xmlns:fx="http://javafx.com/fxml/1">`.

I use an ARM processor too, you're recommended to install the Azul build as indicated in the warning.
</panel>

</panel>


<panel type="info" header="### 60. LEE .. XUN `@Zxun2` (6 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/15#issuecomment-1387481840" expanded>

> To create `EXPECTED.txt`, make sure you have an empty or placeholder `EXPECTED.txt` then run the test script. The test will fail but you would get an `ACTUAL.txt` file from it. Look through `ACTUAL.txt`. If you deem that it's output is correct, then delete your current `EXPECTED.txt` and rename `ACTUAL.txt` to `EXPECTED.txt`.

Another tip: if you are using Intellij, you can click on `ACTUAL.TXT` and right-click on "Compare with..." to produce a visual plot of the difference between `ACTUAL.TXT` and `EXPECTED.TXT`. To make it even easier, there's an option for you to accept the changes in the `ACTUAL.TXT` file. 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/33#issuecomment-1399272031" expanded>

This is really insightful and interesting. Thanks for sharing! @wxxedu 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/48#issuecomment-1399933987" expanded>

> Where can we find these files, or will they be provided separately by then?

You can create the directories and copy the files [here](https://github.com/se-edu/addressbook-level3/tree/master/config/checkstyle) over!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/51#issuecomment-1401350780" expanded>

@ExtraShotLatte These are definitely some valid points! It can make it easier to fix small mistakes and keep reviewers informed of progress without having to send multiple pull requests.

As for the question about different iterations of the same feature, I believe that two main ways that you can go about doing it. Some prefer to work on different iterations of a feature in different branches, while others prefer to work on different iterations in the same branch.

If you prefer to work on different iterations in different branches, you can create a new branch for each iteration, make your changes, and create a new pull request for each one. This can help keep the codebase organized and make it easier to review and merge each iteration separately.

If you prefer to work on different iterations in the same branch, you can do so by making use of the `git stash` command to temporarily store your changes, make it easy to switch between different feature's implementations or different versions of the same feature. In this case, it's also important to clearly label and document your different iterations and versions, such as by adding comments or commit messages that explain what changes were made in each iteration. 

Let me know if I miss out anything!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/65#issuecomment-1406021894" expanded>

My general rule of thumb is to use enums where using a regular data type like int or string would not provide the same level of type safety or readability. Furthermore, enums can also have methods and other properties associated with them, making them more powerful than simple constants.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1410059794" expanded>

Probably not the best in terms of UX (having a landing page), but I wanted to explore a multi-page application. The bot is Silco from LoL.

| Landing | Main view |
| ------------- | ------------- |
| ![image](https://user-images.githubusercontent.com/63457492/215726030-7378c1bc-9856-4dc5-899e-7e4777863f4e.png)  | ![image](https://user-images.githubusercontent.com/63457492/215725875-00d6f32a-7e6a-4196-85c1-e8e37d372dab.png)  |






</panel>

</panel>


<panel type="info" header="### 61. TAN .. ZHE `@wz2k` (6 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Issue with continuous integration**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/170" expanded>

After setting up the workflow, there I have encountered an issue when building

![image](https://user-images.githubusercontent.com/87819279/218303100-b8c971a3-0f93-4848-92f9-0d4b950601d2.png)
```
Run ./gradlew check
Error: Could not find or load main class org.gradle.wrapper.GradleWrapperMain
Caused by: java.lang.ClassNotFoundException: org.gradle.wrapper.GradleWrapperMain
Error: Process completed with exit code 1.
```

I have fixed the issue by deleting the gradle wrapper files ```gradle-wrapper.jar``` and ```gradle-wrapper.properties``` which was provided by the gradle branch that we had to merged and regenerating new versions of them.
I noticed after regenerating that the distribution url has changed from 'https\://services.gradle.org/distributions/gradle-6.2-bin.zip' to 'https\://services.gradle.org/distributions/gradle-7.5.1-bin.zip'

I am wondering if such version issues will affect grading.
</panel>

<panel  header="**2. :fas-info-circle: Different way of ending the program with GUI**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/99" expanded>

Is it possible to not have the 'bye' command after switching to GUI? With a GUI, users can simply close the program without typing. Also, when the program closes, users will not be able to read the bot's reply to the bye command making it even more redundant.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/99#issuecomment-1409710391" expanded>

Thanks for the replies. I have handled the saving but I am concerned on the part of it being in the grading criteria.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/106#issuecomment-1410032281" expanded>

The java imports should be above the duke imports.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/106#issuecomment-1410035536" expanded>

You can refer to [https://se-education.org/guides/tutorials/intellijCodeStyle.html](https://se-education.org/guides/tutorials/intellijCodeStyle.html) to set import ordering in your settings
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/170#issuecomment-1427023287" expanded>

Thanks for the reply
</panel>

</panel>


<panel type="info" header="### 62. STAN.. JUN `@StanleyNeoh` (6 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Bug related to modifying data file**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/312" expanded>

Hello, we received a bug that is related to the behaviour of our application when the data file has been modified and unreadable. The current behaviour is that it will ignore the data file and start with an empty application which the tester says it is a bug as his data is lost.

My question is if unintended behaviour stemming from editing the data file is considered a valid bug, and if so what can we do to fix it?
</panel>

<panel  header="**2. :fas-info-circle: UML sequence diagram ref without and sd**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/293" expanded>

Hello.

I am currently trying to draw a UML sequence diagram to show many if-else statements, similar to what you may see in a Command pattern.

![EventHandling](https://user-images.githubusercontent.com/95394480/228607161-986b06af-6f97-47eb-8de3-5cc79319cff1.png)

Is it okay to use refs without a sd for every ref? 

Thank you in advance
 
</panel>

<panel  header="**3. :fas-info-circle: Questions about JavaFX**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/267" expanded>

![image](https://user-images.githubusercontent.com/95394480/226194714-9c5a8937-54dd-4237-b4d1-6bb7cbf38021.png)
Hello there, why should we execute the show method before we fill out the content of the stage regarding JavaFX? The above code snippet is taken from [UiManager.java](https://github.com/nus-cs2103-AY2223S2/tp/blob/master/src/main/java/seedu/address/ui/UiManager.java#L44)
</panel>

<panel  header="**4. :fas-info-circle: Unable to run add-gradle-support branch on CLI**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/58" expanded>

Hello! I am attempting to integrate Gradle into my iP and am experimenting on the unmodified add-gradle-support branch with CLI. However, when I try to run the branch with `gradlew run`, There is a build error.

```java
~\CS2103T\ip>gradlew run

> Task :run FAILED
Error: Could not find or load main class seedu.duke.Duke
Caused by: java.lang.ClassNotFoundException: seedu.duke.Duke

FAILURE: Build failed with an exception.

* What went wrong:
Execution failed for task ':run'.
> Process 'command 'C:\Program Files\Java\jdk-11.0.17\bin\java.exe'' finished with non-zero exit value 1

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output. Run with --scan to get full insights.

* Get more help at https://help.gradle.org

BUILD FAILED in 1s
2 actionable tasks: 1 executed, 1 up-to-date

~\CS2103T\ip>
```

May I know what I am doing wrong and how I can resolve this? Thank you in advance!

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/267#issuecomment-1477206327" expanded>

I swapped the order between the 2 statements, and so far it doesn't seem to have any visible change, but I am not sure if it will introduce any bugs.
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/293#issuecomment-1489525608" expanded>

@damithc Thank you
</panel>

</panel>


<panel type="info" header="### 63. SZE ..HENG `@szejiancheng` (6 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Requesting for smoke testing on Linux!**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/222" expanded>

Requesting any kind Linux users to help smoke test [this ](https://github.com/szejiancheng/ip/releases/tag/v0.3)jar file, the usual method of opening applies using the command `java -jar duke.jar` after navigating to the directory.

This is to check if the error detailed in #215 still exists after the fixes recommended by @anchengyang
</panel>

<panel  header="**2. :fas-info-circle: How do you guys debug code when run from gradle?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/173" expanded>

Currently encountering a bunch of unhelpful errors when attempting to run my code through gradle. Just wondering what others were doing when debugging with really unhelpful gradle stacktraces occupying most of the terminal.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/173#issuecomment-1435905481" expanded>

Followed @jiasheng59's advice! Closed!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/215#issuecomment-1439511144" expanded>

Encountering this problem as well! Do update when you've found the solution!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/215#issuecomment-1439543751" expanded>

woah @anchengyang just to be clear, you removed the javafx dependency in your build.gradle file and that solved the problem? 
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/222#issuecomment-1441298229" expanded>

Thank you all, closed
</panel>

</panel>


<panel type="info" header="### 64. TAN ..OMUN `@homuntan02` (6 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Deadline for IP**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/200" expanded>

Hi, the website says that the deadline for the ip is today (17 Feb 2023) however the email states that we will automatically get a 3 day extension if not submitted by then. However, in issue#199, Prof mentioned that the hard deadline is today. Can I confirm that this extension wont penalise our grades as mentioned in the email?
</panel>

<panel  header="**2. :fas-info-circle: CheckStyle for switchcases**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/132" expanded>

For switch case check style, they mentioned the need for a default case. What do I do if I don’t have a default?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/132#issuecomment-1420114127" expanded>

> Hi @homuntan02, this was mentioned in CS2103 Week 5
> 
> > If there is no default action, you can use the `default` branch to detect errors (i.e. if execution reached the `default` branch, raise a suitable error)
> 
> Essentially, if there is nothing to do in the default case, use it as an error checking tool. Should the default case ever be reached, then a bug has most likely occurred in the code. By throwing an exception, and most likely causing the program to crash, it would make it much easier when debugging.
> 
> If there is no default case, then there's a chance the code would just execute as per normal even when a bug occurs leading to none of the switch cases matching. This would make it much harder to debug as a user might experience strange behaviour and the dev will most likely have to spend more time digging through the code to try to find the cause.
> 
> Read more [here](https://nus-cs2103-ay2223s2.github.io/website/schedule/week5/topics.html#implementation-code-quality-error-prone-practices-basic-use-the-default-branch)

Ah that helps a lot thanks!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/175#issuecomment-1427609034" expanded>

Hi daytona65, 
I also had similar issues and it was resolved after trying prof's first suggestion "File -&gt; Invalidate caches".
Hope it resolves your issues too.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/200#issuecomment-1434134091" expanded>

![image](https://user-images.githubusercontent.com/64577613/219559657-c869e5a5-af60-4119-81f1-53bc29e67b25.png)

</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/200#issuecomment-1434639111" expanded>

thank you prof @damithc!
</panel>

</panel>


<panel type="info" header="### 65. CHRI..YANG `@potty10` (6 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Include implementation in planned enhancement**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/342" expanded>

 Should we include implementation in planned enhancement? 

For example, suppose we have a feature flaw and we want to write an enhancement to solve this problem, but we need to change a method in file A. Must we write how we intend to change this method and/or include screenshots of the planned change in code?
</panel>

<panel  header="**2. :fas-info-circle: Fixing wrong update of UI during feature freeze**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/297" expanded>

Hi,

Let's say I have a command that changes a part of the UI differently in various situation (Example, show A or B). However, during testing, we found that it showed A instead of B. Is fixing it considered violating the feature ~~flaw~~ freeze? We will not be changing the UI A and B itself.

During feature freeze, assume that we have to remove a feature. This will cause feature B to change UI in a different way as advertised. Will this be considered violating feature freeze?
</panel>

<panel  header="**3. :fas-info-circle: Feature freeze question**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/287" expanded>

I understand that I cannot change any features after this week due to feature freeze.

However, is it ok if I remove features? 
</panel>

<panel  header="**4. :fas-info-circle: Citation of SE EDU tutorial**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/190" expanded>

I copied some code for my GUI from [https://se-education.org/guides/tutorials/javaFxPart4.html](https://se-education.org/guides/tutorials/javaFxPart4.html). Do I still need to cite using the format below?
```
persons = getList()
//@@author johndoe-reused
//Reused from https://stackoverflow.com/a/34646172
// with minor modifications
Collections.sort(persons, new Comparator<CustomData>() {
    @Override
    public int compare(CustomData lhs, CustomData rhs) {
        return lhs.customInt > rhs.customInt ? -1 : 0;
    }
});
//@@author
return persons;
```
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/287#issuecomment-1486826384" expanded>

Thank you!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/297#issuecomment-1496894742" expanded>

Thank you!
</panel>

</panel>


<panel type="info" header="### 66. RITI..OSHI `@rmj1405` (6 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: How to resolve iP Level-10 Error: java.lang.NoSuchMethodException: Duke.<init>()💡**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/133" expanded>

I followed the JavaFX tutorial but was faced with `java.lang.NoSuchMethodException: Duke.&gt;init>()` in `Launcher.java` after adding some modifications to my code structure. This issue can be solved by simply **adding a default constructor in your Duke class**. Hope this helps anyone facing this issue!

''' java
 public Duke() {}
</panel>

<panel  header="**2. :fas-info-circle: Clarification on if checkstyle.xml fully follows the modules Java codestyle**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/91" expanded>

Hi, I have installed the checkstyle and it now shows a violation for creating spaces between imports. The image is not uploading so I have reproduced it below to illustrate the issue. The module's java codestyle documentation does not provide any explicit rules on import spacing hence, I would like to enquire if this checkstyle violation should just be ignored or if it is fully reprenstative of the module codestyle and every violation the checkstyle points out should be strictly followed. Thank you!

```Java
//my current imports 
import task.TaskManager;

import ui.WelcomeUI;

import util.DukeException;
import util.FileManager;

import java.util.Scanner; 

//what checkstyle wants
import task.TaskManager;
import ui.WelcomeUI;
import util.DukeException;
import util.FileManager;
import java.util.Scanner; 

```
</panel>

<panel  header="**3. :fas-info-circle: Good practices and suggestions on structuring code to be clean and concise**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/23" expanded>

Hi everyone,

I have abstracted the main logic for my chatbot into a `run()` method in a `ChatBot` class, and my approach to handling user queries is breaking the input down to a string array with _**{keyword}whitespace{command}**_ format which has resulted in me having a main if-else loop dependent on if its only a _keyword_ like "list" or _keyword and command_ like "uncheck 2" or "todo homework". However, within each condition I also have a switch statement for each keyword(uncheck, delete, etc) and my `run()` method has become quite long.

I am aware that I could possibly abstract each condition in the if-else into a separate class and shorten the method, but I am curious about other ways you have structured your main logic to be more clean and concise as well as any alternatives to using switch statements. I would love to hear your suggestions and ideas on improving code structure when there are many cases as in this chatbot! Thank you!

Attached is a snippet of my code for reference
```
else if(len == 2) {
      //cases: check 1, uncheck 2, event project meeting, etc
      //format: keyword{whitespace}command

      String fst = inputArr[0];
      String snd = inputArr[1];
      Boolean isNum = taskManager.isNumeric(snd);

      //if snd is numeric : cases are check/uncheck etc
      if(isNum) {
          int index = Integer.parseInt(snd) - 1;
          switch(fst) {
              case "check":
                  taskManager.checkTask(index);
                  break;
              case "uncheck":
                  taskManager.uncheckTask(index);
                  break;
              case "delete":
                  taskManager.deleteTask(index);
                  break;
              default:
                  System.out.println("I haven't learnt this command yet!\n" +
                          "Type menu to see the commands I know.");
                  break;
          }
      } else { //snd is a string input
          switch(fst) {
              case "todo":
                  ToDos todo = new ToDos(snd);
                  taskManager.addTaskToList(todo);
                  break;
              case "event":
```


</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/23#issuecomment-1399465953" expanded>

Thank you so much for the detailed responses!! I'm glad to have learnt about different approaches to this task :)
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/91#issuecomment-1407912999" expanded>

> @rmj1405 Checkstyle from where did you get the Checkstyle configuration file?


Hi prof, I used the one from the tP! Noted the point that we can edit the checkstyle. Thank you!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/133#issuecomment-1415622509" expanded>

> Thank you man. I spent an hour trying to figure out the solution

Happy to help! I was stuck for quite a while too 🥲
</panel>

</panel>


<panel type="info" header="### 67. LAVA..SHRA `@Lava-Iris` (6 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: A-TextUiTesting test failing**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/25" expanded>

I'm trying to do the A-TextUiTesting task and my test result fails every time. I'm working on Ubuntu (running runtest.sh). I tried to copy the actual.txt to the expected.txt and it still gives the following error:

```bash
dos2unix: converting file ACTUAL.TXT to Unix format...
dos2unix: converting file EXPECTED-UNIX.TXT to Unix format...
1,2c1,2
< Welcome to Lavender Network! 
< I'm Iris, your favourite teenage chatbot. 
---
> Welcome to Lavender Network!
> I'm Iris, your favourite teenage chatbot.
13c13
< A task marked with a X is done. To close me, type "bye". 
---
> A task marked with a X is done. To close me, type "bye".
Test result: FAILED
```

They both look the same to me, so I don't know why the error is coming (and it's only coming in the first and last output)

Background: 

Before this, I was getting 
```bash
dos2unix: Binary symbol 0x1B found at line 1
dos2unix: Skipping binary file ACTUAL.TXT
dos2unix: Binary symbol 0x1B found at line 1
dos2unix: Skipping binary file EXPECTED-UNIX.TXT
1,2c1,2
< Welcome to Lavender Network! 
< I'm Iris, your favourite teenage chatbot. 
---
> Welcome to Lavender Network!
> I'm Iris, your favourite teenage chatbot.
13c13
< A task marked with a X is done. To close me, type "bye". 
---
> A task marked with a X is done. To close me, type "bye".
Test result: FAILED
```

I searched online and added -f for the dos2unix command. Apart from that, I've only changed the filepaths in the.sh file
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/25#issuecomment-1396473919" expanded>

Update: I figured out what made the lines different from everything else.

Everywhere else, my code was "blah blah.\n" but only for these 3 lines, I had a space before the newline ("blah blah. \n")

I removed the space before the newline and it passed the test!

Can anyone tell me what just happened? Why did a space before the newline fail the tests?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/129#issuecomment-1414147063" expanded>

Oh I got the same errors. It went away when I put the java io (and any external import statements) before the duke import statements. 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/143#issuecomment-1418423344" expanded>

If the two cases are entirely separate, i.e., you don't need to check for case 2 after it checks true for case 1, you can add a break after the case statement. Otherwise, the switch will keep checking and executing the code for case 2, case 3 and so on even after case 1 is true.
```
switch (foo) {
case 1:
    int bar = 1;
    /* ... */
    break;
case 2:
   int bar = 2;
    /* ... */
    break;
default:
    /*...*/
}
```
should do the trick.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/225#issuecomment-1444972748" expanded>

@HmuuMyatMoe Just tested your jar file. It's working without any issues on Linux. 

P.S. Your UI is super cute!!!!
</panel>

<panel  header="**6 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/225#issuecomment-1444973407" expanded>

@IsabelChong your jar file is executing without any issues on Linux. 

P.S. How do you guys come up with such cute UIs?
</panel>

</panel>


<panel type="info" header="### 68. JULI..ARJO `@junlee1991` (5 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: CodeCov/patch/project**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/251" expanded>

i'm checking the PR: https://github.com/nus-cs2103-AY2223S2/tp/pull/69 

<img width="674" alt="image" src="https://user-images.githubusercontent.com/77482097/224522066-afc180c7-7c29-477f-99ad-d88ea635c6bb.png">

Any hints how to make the codeCov/project / patch turn into a green tick? 

The logs say Added lines #L93 - L94 were not covered by tests. any way to suppress warning? 

</panel>

<panel  header="**2. :fas-info-circle: Linkage Error**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/214" expanded>


<img width="454" alt="image" src="https://user-images.githubusercontent.com/77482097/220020968-57453645-3eed-4ccb-809c-f9dfeba414bb.png">

Error: LinkageError occurred while loading main class duke.Launcher java.lang.UnsupportedClassVersionError: duke/Launcher has been compiled by a more recent version of the Java Runtime (class file version 56.0), this version of the Java Runtime only recognizes class file versions up to 55.0 

My jar works on my laptop but i received an email that my smoke test fails. Any idea how to fix? 

</panel>

<panel  header="**3. :fas-info-circle: Checkstyle import statement**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/129" expanded>

![image](https://user-images.githubusercontent.com/77482097/216384338-778f077b-6f90-4fcf-b1fe-cb932bf33e9c.png)

This checkstyle error baffles me. When i remove the import statement, no errors from checkstyle but the code wont work.




</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/214#issuecomment-1437402853" expanded>

Upon running `java --version`
java version "15.0.1" 2020-10-20

yes i used gradle to create the jar file. shadow clean command i believe

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/214#issuecomment-1438989365" expanded>

ok i've applied the necessary fix. May i know if the issue still persists?

[Here](https://github.com/junlee1991/ip/releases/tag/A-Release2) is my latest release. 
</panel>

</panel>


<panel type="info" header="### 69. LEE .. YEN `@kayyenl` (5 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Trying to run checkstyleMain and checkstyleTest: Unable to create Root Module**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/128" expanded>

Hi guys! While trying to run gradlew, I faced this certain issue. 

![image](https://user-images.githubusercontent.com/99934242/216327989-382c83e6-c7c5-4438-b0c1-e0a5cff70b4f.png)

* What went wrong:
Execution failed for task ':checkstyleMain'.
> Unable to create Root Module: config {C:\Users\65912\Desktop\CS2103\ip\config\checkstyle\checkstyle.xml}, classpath {C:\Users\65912\Desktop\CS2103\ip\build\classes\java\main;C:\Users
\65912\Desktop\CS2103\ip\build\resources\main}.

I had tried running it once with a config file inside iP, ip > config , with the suppressions and checkstyle xml files in it, but the same error occurs. I removed the config file and ran it again, but am still facing the same error. Anyone else faced this issue before? Do let me know if I am doing something wrong. Thank you so much!
</panel>

<panel  header="**2. :fas-info-circle: Running the runtest.bat file**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/18" expanded>

Hi everyone.

I have a small problem at stage A-TextUiTesting. Specifically, I'm not too sure how to run the runtime.bat file, since there is no option to run it on the IDE. Is this file supposed to be run on the CLI by some command? Do let me know if I am misunderstanding the task or something. Thanks so much!


</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/18#issuecomment-1387253722" expanded>

Alright, it seems like I went with @Junyi00 's one and it worked. Thanks so much everyone!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/112#issuecomment-1413665483" expanded>

Just wanted to add to this, was having the same problem as the poster. 

for the Windows cmd terminal (or the integrated terminal within IntelliJ), using 

```
./gradlew.bat checkstyleMain checkstyleTest 
```

was the command that worked for me. 👍 

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/128#issuecomment-1413757108" expanded>

I realized the issue: Although I did store the files under config, I did not store suppressions and checkstyle.xml files under another checkstyle folder. Problem solved!
</panel>

</panel>


<panel type="info" header="### 70. TOH ..N YI `@toh-xinyi` (5 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Changing sample data as it is not in line with our product**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/366" expanded>

In #303, it is stated we are only allowed to change if there are errors in the sample data,
But, are we able to change it if there are no exact errors but the tags in the sample data does not match our product at the moment? Are we able to just change the tags to match with our product as it might be misleading to users? e.g. current tags: 'friends' and 'colleagues' but our application is for keeping track of a tutor's students, so we would like to change the tags to 'primary', 'secondary', etc.
</panel>

<panel  header="**2. :fas-info-circle: Am I able to change my response for Canvas tP code reuse declaration survey**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/363" expanded>

I selected the wrong option and submitted the survey... Is there any way for my to change my selected option
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/161#issuecomment-1427028125" expanded>

You can try setting the Min. height of the `Dialog Box` to `USE_PREF_SIZE`
![image](https://user-images.githubusercontent.com/121878184/218312552-3d876a24-3a43-4fd5-81f3-cfd7f0bb922c.png)
After doing that, for mine, the ellipses are gone and the remaining text shows. :)
Good luck!!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/363#issuecomment-1501922882" expanded>

Thank you prof!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/366#issuecomment-1501948417" expanded>

@damithc Noted, thank you prof!
</panel>

</panel>


<panel type="info" header="### 71. WESL..CRUZ `@wesleybldc` (5 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Cannot run with GUI - Unable to construct Application instance: class willy.WillyApp**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/183" expanded>

Remember to give sufficient details e.g.,
* Your development environment (IntelliJ version, Java version, OS, ...)
* Relevant code, error message, stack trace
* Relevant code snippet (an example given below), or link to the relevant code on your GitHub repo

I have tried running it on IntelliJ and VSCode. My previous branches were working, when I initially did the GUI it was working but suddenly when I tried to test now it is not working. Even after rolling back to previous branches/commits, it is giving me this same error. Im not sure if its related to my java pathway issue as I randomly chose someone's project and tried to run it and it works (so it does not seem like it is my machine).

also, someone had a similar issue: https://github.com/nus-cs2103-AY2223S2/forum/issues/122
but it did not work for me. 

here is link to my repo: https://github.com/WesleyBLDC/ip/tree/master/src/main/java/willy

wesley@Wesleys-MacBook-Air ip %  cd /Users/wesley/Documents/GitHub/ip ; /usr/bin/env /Library/Java/JavaVirtualMachines/zulu-11.jdk/Contents/Home/bin/java @/var/folders/wc/sdprkyqd26g3f8h16_j4y4940000gn/T/cp_4yagd2nysv1kneeg9cmywxdjv.argfile willy.L
auncher 
Exception in Application constructor
Exception in thread "main" java.lang.RuntimeException: Unable to construct Application instance: class willy.WillyApp
        at javafx.graphics/com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:891)
        at javafx.graphics/com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:196)
        at java.base/java.lang.Thread.run(Thread.java:829)
Caused by: java.lang.NoSuchMethodException: willy.WillyApp.&gt;init>()
        at java.base/java.lang.Class.getConstructor0(Class.java:3349)
        at java.base/java.lang.Class.getConstructor(Class.java:2151)
        at javafx.graphics/com.sun.javafx.application.LauncherImpl.lambda$launchApplication1$8(LauncherImpl.java:802)
        at javafx.graphics/com.sun.javafx.application.PlatformImpl.lambda$runAndWait$12(PlatformImpl.java:484)
        at javafx.graphics/com.sun.javafx.application.PlatformImpl.lambda$runLater$10(PlatformImpl.java:457)
        at java.base/java.security.AccessController.doPrivileged(Native Method)
        at javafx.graphics/com.sun.javafx.application.PlatformImpl.lambda$runLater$11(PlatformImpl.java:456)
        at javafx.graphics/com.sun.glass.ui.InvokeLaterDispatcher$Future.run(InvokeLaterDispatcher.java:96)

</panel>

<panel  header="**2. :fas-info-circle: Checkstyle IntelliJ giving error that cannot be resolved - does notm**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/151" expanded>

Remember to give sufficient details e.g.,
* Your development environment (IntelliJ version, Java version, OS, ...)
* Relevant code, error message, stack trace
* Relevant code snippet (an example given below), or link to the relevant code on your GitHub repo

Using IntelliJ with Java 11, with the same checkstyle file template provided in the cs2103 repo.

I get these two errors that I cannot resolve on the checkstyle, 

1) Name "Willy.ui" must match pattern....
2) Line matches the illegal pattern...

The exact error is in the screenshot.

May anyone advise what I can do? Or shall I ignore this?



:bulb
<img width="863" alt="SCR-20230209-l5pedited" src="https://user-images.githubusercontent.com/28299779/217744103-52931ba4-0e8c-4b2d-b125-7ceb5b6354ac.png">
: You can use [Markdown](https://guides.github.com/features/mastering-markdown/) to format your text

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/151#issuecomment-1426970993" expanded>

Thanks everyone for your help.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/183#issuecomment-1428598633" expanded>

Hmm was able to make it work after changing a small thing and running it on intellij...
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/194#issuecomment-1434177396" expanded>

In terms of storage file creation, 

if you run the jar file using terminal, it will not create the storage file as there it is locally stored on the terminal.

if you run the jar file by double-clicking, if your storage code is working correctly then it will create a local file directory within the same folder it was ran in.

So I recommend testing both ways.

For error handling, run launcher it on intellij and see if the terminal gives any errors. 
</panel>

</panel>


<panel type="info" header="### 72. LEE ..EFAN `@rexcyrio` (5 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: tP feature was present in the v1.3 JAR file but was not tested during PED due to UG being out of sync**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/306" expanded>

Tester A: @Yufannnn
Tester B: @homuntan02
Tester C: @jinnieshin
Tester D: @zrei

At 1:47pm, [https://github.com/AY2223S2-CS2103T-W10-3/tp/pull/105](https://github.com/AY2223S2-CS2103T-W10-3/tp/pull/105) was closed -- the `find` command in the UG was updated to say that it performs a full text search on all fields of a contact (instead of just the name field), and the command history feature was also added to the UG. Both of these features were already present in the v1.3 JAR file.

![vivaldi_T69n9rfuRK](https://user-images.githubusercontent.com/76687125/229328958-88adc5a3-d826-427e-aa7b-19c82ac3c1f5.png)

![vivaldi_7hzy1PjcsA](https://user-images.githubusercontent.com/76687125/229328968-f3685691-b99c-4086-9f4d-28b4328244dc.png)

At 1:48pm, the GitHub pages deployment for UG was updated ([https://github.com/AY2223S2-CS2103T-W10-3/tp/deployments/activity_log?environment=github-pages](https://github.com/AY2223S2-CS2103T-W10-3/tp/deployments/activity_log?environment=github-pages))

&gt;br>

One of our peer reviewers got the updated UG (it shows the updated `find` command in the screenshot)

- see [https://github.com/AY2223S2-CS2103T-W10-3/tp/issues/122](https://github.com/AY2223S2-CS2103T-W10-3/tp/issues/122)

&gt;br>

Unfortunately, it seems like two of our peer reviewers had loaded the page before [https://github.com/AY2223S2-CS2103T-W10-3/tp/pull/105](https://github.com/AY2223S2-CS2103T-W10-3/tp/pull/105) was deployed at 1:48pm, and got the "old" version of the UG

- see [https://github.com/AY2223S2-CS2103T-W10-3/tp/issues/107](https://github.com/AY2223S2-CS2103T-W10-3/tp/issues/107)
- see [https://github.com/AY2223S2-CS2103T-W10-3/tp/issues/128](https://github.com/AY2223S2-CS2103T-W10-3/tp/issues/128)

&gt;br>

(I'm not sure which version of the UG Tester B got -- there was no mention of this problem in Tester B's bug reports to us, so I can only assume he got the updated UG)

---

My questions:
- can my team keep the updated full-text find feature in our tP?
- can my team keep the command history feature in our tP?

&gt;br>

I ask this as I'm not sure whether it conflicts with the idea of v1.4:

![image](https://user-images.githubusercontent.com/76687125/229329414-65aa83ff-31fb-434a-88f7-c3e5b41a2651.png)

Tagging my teammates:
@niekis
@jugheadjones10
@minosx31
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/20#issuecomment-1396326000" expanded>

Hi @jiasheng59

Presuming that the code looks something like the following:

```java
if (command.equals("list")) {
    // handle `list` command
} else if (command.equals("bye")) {
    // handle `bye` command
} else if (command.equals("todo")) {
    // handle `todo` command

/* handling other commands through more else-if statements here */

} else {
    System.out.println("Unknown command");
}
```

Here are some suggestions:

1. Instead of handling each command "inline", the code can be abstracted out into another function / method (maybe on your `TaskList` class?) to prevent heavily nested `if-else` statements.
2. When invalid inputs are detected, the code can `throw` an `Exception` that will be caught by the callee. This way, the control flow will be easier to manage. There has also been some fruitful discussion over at [issue #11](https://github.com/nus-cs2103-AY2223S2/forum/issues/11) with regards to this issue -- in particular, I think [this comment by @hingen](https://github.com/nus-cs2103-AY2223S2/forum/issues/11#issuecomment-1385051046) is very insightful.

Hope this helps!

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/131#issuecomment-1416895604" expanded>

Hi @jamieeeleow

I've cloned your git repo and looked through your code, and here's what I think is happening:

1. The Gradle `run` script is called
1. The `main` function in the `Launcher` class is called
1. A new `Main` object is instantiated
1. Since each `Main` object has a `private Leo leo = new Leo("/data/leo.txt")`, a new `Leo` object is also instantiated
1. The public constructor for the `Leo` class is called
1. `parser.readCommand()` is called
1. The code `String command = scanner.nextLine()` will prevent the execution of any other code as it waits for new user input in the terminal

Point 7 is what I think is causing the GUI to not appear.

When I commented out the `parser.readCommand()` line in the public `Leo` constructor, the GUI appears as expected with the "Hello World!" text.

Hope this helps!

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/262#issuecomment-1474550442" expanded>

You can also try [configuring IntelliJ's import order to better match the checkstyle](https://se-education.org/guides/tutorials/intellijCodeStyle.html#tweak-import-order).
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/306#issuecomment-1493494057" expanded>

Okay thank you prof!
</panel>

</panel>


<panel type="info" header="### 73. GOH ..JING `@gohyongjing` (5 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/81#issuecomment-1407553634" expanded>

As the others mentioned above, I handled only the required cases as it would be very difficult to flexibly accept different formats (Such as `1-2-2000`: without a fixed format, we would not know if it is `1st Feb` or `2nd Jan`). I only accepted `yyyy-mm-dd tttt` and `yyyy-mm-dd tt:tt` and made a check for whether the colon exists in the time.

I also considered to allow users to pass in their own required format such as `deadline homework /by 01-02-2024 /format dd-mm-yyyy` but this seems to be too verbose, even for fast typists.

I think the most flexibilty we could give is to also accept dates with the month format `mmm`, such as `jan`, `feb` etc, which could be done by manually checking
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/95#issuecomment-1408598512" expanded>

I faced similar issue in the part 4 of the tutorial, and i figured out that the tutorial is incomplete. The tutorial doesnt show what to do with `Duke.java` after refactoring the other files with fxml.

As mentioned above by others, you should ***replace*** the entire `DialogBox.java` with their `DialogBox.java` controller, as well as removing all lines in `Duke.java`, except for `Duke`'s `getResponse` function (which should have its access modifier changed from `private` to `public`).

```java
package org.example;

public class Duke {
    public String getResponse(String input) {
        return "Duke heard: " + input;
    }
}
```
I also completed this tutorial in a separate repo, and you can have a look at it if you want:  https://github.com/gohyongjing/javaFxHelloWorld

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/98#issuecomment-1408873864" expanded>

I also received the error because i tried to place the main() function inside my app and launch it directly.
```java
// Duke.java

public class Duke extends Application {

    // Bad, causes error
    public static void main(String[] args) {
        Application.launch(Duke.class, args);
    }

    public void start(Stage stage) {
        ...
    }
}
```
I moved the main function to a separate launcher.java file and it ran without issues.
```java
// Launcher.java

public class Launcher {
    
    // Good, no error
    public static void main(String[] args) {
        Application.launch(Duke.class, args);
    }
}

// Duke.java

public class Duke extends Application {

    public void start(Stage stage) {
        ...
    }
}

```

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1410090708" expanded>

My GUI following the tutorial 
![image](https://user-images.githubusercontent.com/39022090/215731565-69ee7ae3-533f-4fb8-85ca-1083f0711640.png)

</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/215#issuecomment-1439431380" expanded>

I'm using windows, and the jar file seems to work properly for my computer
![image](https://user-images.githubusercontent.com/39022090/220523910-0e659624-281f-48d2-8314-f83cb4f6683c.png)

</panel>

</panel>


<panel type="info" header="### 74. LI J..UNYI `@immanuelhume` (5 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Links in PDF output**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/332" expanded>

Some parts of the DG link to other parts of the website. For example, in the screenshot from AB3's docs below, the *Setting up and getting started* section is hosted as a separate page.

<img width="421" alt="image" src="https://user-images.githubusercontent.com/47441677/230005347-96607c27-d0d1-4e05-bfa3-11711314db20.png">

I would like to clarify:

1. In the final PDF, should these remain as hyperlinks to the docs webpage? Or should we "inline" these sections into the DG?
1. If the sections remain as hyperlinks, are mistakes in their content (on the web page) penalizable in PE?
</panel>

<panel  header="**2. :fas-info-circle: UG/DG pdf conversion**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/283" expanded>

The module website suggests [using gchrome](https://se-education.org/guides/tutorials/savingPdf.html) to generate the pdf. I wonder if this is a hard requirement? Or is it okay if

1. we try other conversion methods?
1. closer to the deadline, temporarily use a slightly modified version of the .md file to try and get better conversion results?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/114#issuecomment-1411217494" expanded>

I created a bunch of delegates for `printf` on `Ui` instances, to produce an API similar to logging libraries.

```java
ui.info(String fmt, Object... args);
ui.error(String fmt, Object... args);
// etc etc, as needed
```
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/113#issuecomment-1411221980" expanded>

The guide says

> Let’s repeat the process for DialogBox. The main difference here is that DialogBox checks Use fx:root construct and does not define a controller class.

Which means there shouldn't be any controller class set for DialogBox. Instead, the fx:root checkbox should be checked. So your initial fxml file was correct.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/337#issuecomment-1497742393" expanded>

ur team's app looks fine on my laptop (arch, i3wm)

specifically what issues r u referring to?

<img width="963" alt="image" src="https://user-images.githubusercontent.com/47441677/230137231-7ffad960-d95e-4711-b248-5baa188dff90.png">

</panel>

</panel>


<panel type="info" header="### 75. DARR..IANG `@ChangGittyHub` (5 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: corrupted font when I run AB3 code, but no font problem with addressbook.jar**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/221" expanded>

I have no font issue with the addressbook.jar file that we had to test weeks before, however, I have an issue of corrupted fonts when I run the tp code that I forked and clone into my computer.
I checked if my mac has the right version using java --version and it is correct as shown below.
Not sure what is causing this issue, appreciate any help I can get! Thank you

#AB3 addressbook.jar
![IMAGE 2023-02-21 17:40:07](https://user-images.githubusercontent.com/82028822/220307474-00cc8df3-49d3-4285-8e75-e1e5c930635a.jpg)

#AB3 tp code
![IMAGE 2023-02-21 17:33:29](https://user-images.githubusercontent.com/82028822/220305833-5e8f8b26-a371-4db6-b42e-ee8d62b31cef.jpg)
![IMAGE 2023-02-21 17:36:53](https://user-images.githubusercontent.com/82028822/220306617-b9449336-4a47-4786-9ba1-9a1509129caa.jpg)

</panel>

<panel  header="**2. :fas-info-circle: GUI Text issue gibberish**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/189" expanded>

Hi!! I need help. This is my GUI does anyone know how to fix this text issue? my java version is java 11 and my addressbook.jar works when I open it.I can read the words but my GUI is not readable.Apprecaite any help I can get!

<img width="474" alt="Screen Shot 2023-02-15 at 7 48 58 PM" src="https://user-images.githubusercontent.com/82028822/219019525-81357f50-3198-42dc-a432-58253c702210.png">

</panel>

<panel  header="**3. :fas-info-circle: Fixing corrupted fonts in AB3 - Unable to find and delete Java 17.0.1 on my mac**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/78" expanded>

java --version indicated I have java 17.0.1 on my computer
So I downloaded zulu 11 and followed the video to delete java 17.0.1 on my mac but I could not find java 17.0.1 under JavaVirtualMachine folder as shown in my screenshot.
Anyone knows how I can find and delete java 17.0.1 on my mac?

<img width="496" alt="Screen Shot 2023-01-27 at 9 16 55 PM" src="https://user-images.githubusercontent.com/82028822/215096009-3dc4b854-bafb-4f75-82ba-85266839db69.png">
<img width="530" alt="Screen Shot 2023-01-27 at 9 18 49 PM" src="https://user-images.githubusercontent.com/82028822/215096430-13cfe315-3e7d-4abd-8a7e-3739f3bf0286.png">

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/78#issuecomment-1407450808" expanded>

Wow thanks so much.super appreciate it... I found it in ~/Library/Java/JavaVirtualMachines and deleted all versions which solved the problem! Thanks!!
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/189#issuecomment-1433174825" expanded>

Thank you for the help! my com did not support the given font so I changed it to a different font instead thank you!
</panel>

</panel>


<panel type="info" header="### 76. TAN ..INUS `@linustws` (5 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Scene Builder not showing that DialogBox.java is the controller class for DialogBox.fxml**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/113" expanded>

Hi, I have finished the JavaFxPart4 tutorial about controller classes, and have updated the controller class for DialogBox.fxml to be DialogBox.java as specified. However, this change is not reflected in Scene Builder under the controller class. It still shows that it does not define a controller class as shown below.
<img width="306" alt="image" src="https://user-images.githubusercontent.com/97421565/215816684-da623840-9590-471d-8aae-361f563c0eeb.png">
I then added the `fx:controller="duke.DialogBox"` in the DialogBox.fxml, and this managed to reflect the change in Scene Builder. However, when running the launcher, after typing an input, there was this error: javafx.fxml.LoadException: Controller value already specified. I removed the `fxmlLoader.setController(this);` and `fxmlLoader.setRoot(this);` statements in DialogBox.java as I thought that the 2 ways to set a controller: 1. using the fx:controller attribute, and 2. using fxmlLoader.setController(this) were causing a conflict and hence the exception. I removed both statements and I received another error: javafx.fxml.LoadException: in my DialogBox.fxml and showed something about URI not registered.
<img width="1041" alt="image" src="https://user-images.githubusercontent.com/97421565/215820130-e1bc3766-ca90-4e50-9c81-bff7605ab216.png">
Is there a way to fix this error and yet display that DialogBox.fxml has its own controller class in Scene Builder?

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/41#issuecomment-1399528280" expanded>

Are we allowed to not save the task list like the example given, but maybe as a bunch of jibberish, as long as the 'list' command correctly displays the list as it updates? I'm thinking of using the serializable interface.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/48#issuecomment-1401872554" expanded>

@heeeyi I also had to add id 'checkstyle' in plugins and this block of code:
checkstyle {
    toolVersion = '10.2'
}
for it to work.

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/113#issuecomment-1411475444" expanded>

I see. It's the later part that says 

> For our custom DialogBox, we did not define a controller so let's create a controller for it.

and

> When we create a new instance of DialogBox, we set both the controller and root Node to DialogBox. From this point onwards we can interact with DialogBox as we have in the previous tutorials.

so I assumed setting the controller to DialogBox meant it now has a controller class. Is this not equivalent?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/113#issuecomment-1413115599" expanded>

> > so I assumed setting the controller to DialogBox meant it now has a controller class. Is this not equivalent?
> 
> Not super familiar with JavaFX but perhaps you can think of it this way.
> 
> You are able to set the controller object dynamically at runtime using code. That is what the `fxmlLoader.setRoot(this);` line in the `DialogBox` class constructor is for. This means that you are not constraint to having to use a class named `DialogBox` every time, all you need is a class that inherits from the same Node type as the root in the `DialogBox.fxml` file (in this case it is `HBox`).
> 
> Why is this useful? The first thing that comes to mind is reusability. If I have a generic `fxml` that I want to reuse for many different scenarios, I now can.

Thanks! I didn't think that controllers can be changed dynamically. I guess the setController method allows that whereas the fx:controller method only sets the controller at the start of runtime.
</panel>

</panel>


<panel type="info" header="### 77. SEOW..LVIN `@swxk19` (5 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Question about omitting methods in sequence diagram**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/353" expanded>

Say I have the following scenario of nested calls where `one()` calls `two()` which calls `three()` which calls `four()`
<img width="135" alt="image" src="https://user-images.githubusercontent.com/45385178/230737034-76c77285-2df2-4011-baf0-909ef893d674.png">

but in my particular scenario, i only want to show `one()` and `four()`, as `two()` and `three()` are irrelevant and doesn't add much value in this specific scenario. Would it then be acceptable to show the diagram as this? :
<img width="121" alt="image" src="https://user-images.githubusercontent.com/45385178/230737149-f3361dc0-38d6-49c6-a7db-640a0fce358b.png">

</panel>

<panel  header="**2. :fas-info-circle: Difference between submission of v1.4 and wrapping up milestone**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/352" expanded>

Submission of v1.4 is on 10/4 but wrapping up the milestone for v1.4 is on 12/4. May I understand what's the difference between these 2 deadlines? Why is completing the milestone after the submission and what kinds of changes are we allowed to do after the submission on 10/4?
</panel>

<panel  header="**3. :fas-info-circle: How to catch/handle runtime errors in JavaFX**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/134" expanded>

I'm running my program with `./gradlew run`, and it seems like runtime errors, such as `NullPoniterException`, doesn't show up anywhere for me to catch.

Here, I purposefully invoked a `NullPointerException` in my program, but it doesn't show in the terminal accordingly. 
<img width="799" alt="image" src="https://user-images.githubusercontent.com/45385178/216582404-7d759be9-af69-4818-8454-29be551b2653.png">

I've tried using `try-catch` blocks as well, which doesn't seem to catch these errors either. 
How would I go about detecting errors like these?

</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/134#issuecomment-1415704813" expanded>

I realise now I'm not reading the terminal output clearly enough, the terminal output does show runtime errors, after lots of scrolling. 

But why do runtime errors bypass the `try-catch` block? (I specified this block in my `handleUserInput` method)
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/134#issuecomment-1415713613" expanded>

Ok, it was just a very careless mistake. My `try` block just wasn't encompassing where the error was actually coming from
</panel>

</panel>


<panel type="info" header="### 78. LOW ..FENG `@PeanutButters93` (5 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: unreported exception error when implementing streams**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/153" expanded>

I have an issue trying to implement streams. This is my code:

```java
    public void loadFromStorage() throws FileNotFoundException, InvalidFormatException {
        storage.retrieveContents()
                .stream()
                .map(row -&gt; Task.factoryMethod( //This is the method that throws InvalidFormatException
                        row.charAt(1),
                        row.charAt(4),
                        row.substring(7),
                        parser))
                .forEach(x -&gt; tasks.add(x));
    }
```
And I am having this error
```java
error: unreported exception InvalidFormatException; must be caught or declared to be thrown
                .map(row -&gt; Task.factoryMethod(
    }
```
Instead of streams, i was using a for loop and it worked fine. Now, my compiler does not seem to recognise my InvalidFormatException  is being thrown (it is greyed out). Does anyone know how to solve this issue?

</panel>

<panel  header="**2. :fas-info-circle: Scoping in Switch Statements**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/143" expanded>

The following code gives me an error
```
switch (foo) {
case 1:
    int bar = 1;
    /* ... */
case 2:
    int bar = 2;
    /* ... */
}
```
```
variable bar is already defined in method main(String[])
```
To circumvent it, I declared the variable outside the switch statement, but now it is not in the least possible scope
```
int bar;
switch (foo) {
case 1:
    bar = 1;
    /* ... */
case 2:
    bar = 2;
    /* ... */
}
```

After reading #130, I realized I could write it like this with braces, but it does not look very clean
```
switch (foo) {
case 1: {
    int bar = 1;
    /* ... */
}
case 2: {
    int bar = 2;
    /* ... */
}
}
```

I often run across this problem when doing regex and need to access the Matcher object twice so I have to give it a name. Which is the better option? or is there an alternative?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/143#issuecomment-1418517906" expanded>

Thanks for all the advice everyone.
I think extracting the cases to separate function seems to be the most elegant and is what I'll use.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/153#issuecomment-1423858848" expanded>

Thanks for the swift reply! It slipped my mind that streams don't work with checkedExceptions. I've extracted out the lambda function and threw a runtime exception instead - as suggested in the post.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/153#issuecomment-1431379265" expanded>

Thanks for the reminder! I must have accidentally unchecked the close with comment button.
</panel>

</panel>


<panel type="info" header="### 79. WONG.. YAO `@ExtraShotLatte` (5 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/31#issuecomment-1400728653" expanded>

Hello @daitenshionyan and OP!

I have a similar approach to daitenshionyan. I implemented this using the package from `org.apache.commons.io.FileUtils` which it's documentation can be found [here](https://commons.apache.org/proper/commons-io/javadocs/api-2.5/index.html?org/apache/commons/io/FileUtils.html#:~:text=Makes%20a%20directory%2C%20including%20any%20necessary%20but%20nonexistent%20parent%20directories.).

I tried to use the `write` method in the package. Writing to the file inside `~/data/test.txt` (the data directory was not created prior) cause the directory `data` to be created as well (to my pleasant surprise). Am not sure if there is a benefit to creating the directory first before using `FileUtils` to create the file directly. In my own testing, `FileUtils` did not touch the original files that was already present in the directory.

However, I noted that [this requirement about Cross-Platform File Paths in Java](https://www.sghill.net/2014/how-do-i-make-cross-platform-file-paths-in-java/) may come in handy for inter-platform compatibility of the software we are writing, since both Windows and other OS uses a different way to handle and specify directory.
![image](https://user-images.githubusercontent.com/58366602/214108985-3e10da69-5eb3-4ac9-827b-df0586c76803.png)


```java
String home = System.getProperty("user.home");
java.nio.file.Path path;
File newFile;

path = java.nio.file.Paths.get(home, "data", s);
newFile = new File(path.toString());
FileUtils.write(newFile, "Test\ning");
```

seems to create the test file just fine without any issues, it even adds the `data` parent directory for me! :D
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/51#issuecomment-1400750192" expanded>

I also thought about the same thing! However, I think it makes sense because of the following (in my own opinion):

1.  Different features are supposed to be done in different branches. By creating a PR, typically you are contributing ready to be implemented feature to the upstream repo, hence, you can create multiple PR (based on different branches) if you do have multiple features' implementation you intend to contribute.
2. After creating a PR, you may have caught small mistakes that could be an oversight during your initial developer testing. By having new commits of the branch automatically updating to the latest version you have, you can fix these before the PR review takes place (and not send multiple PR request).
3. After creating a PR, a peer or senior developer may look through the code and can potentially give comments or suggestions to the code. By having the commits automatically be included in the PR, it seems a little neater as the PR reviewer can just look at newer commits and approve the PR based on the further contributions.

However, this also led me to think, should v1.1, v1.2, v1.3 (different iterations) of the same feature (but done at different point of time) be on the same branch if the branch automatically updates when you make new commits? I imagine a scenario where I want to work on v1.2 of the same project (same feature) after completing v1.1 but I cannot because I'm waiting for PR to be reviewed and approved :/

If I understood any of the concepts wrongly, but please feel free to correct me if I do! 

Cheers :)
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/52#issuecomment-1400761090" expanded>

Based on my understanding from [Java 11 API](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/lang/String.html), the method `contains` takes in `CharSequence` but the method `split` takes in a `String regex`.

I looked up [this](https://www.w3schools.com/java/java_regex.asp) and found out that the character `|` has a special meaning in regex:

Find a match for any one of the patterns separated by | as in: cat|dog|fish

I believe this is the main reason why you would need the `\\|` for the split method but not need it for the `contains` method, as one expects a char sequence and one expects a String regex!

Hope this helps! Do correct me if there I made a mistake :)
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/142#issuecomment-1417699492" expanded>

Hi Rui Wei!

I tried looking into the issue (which don't really understand either, maybe others will have some idea?). 

`HIToolbox` is actually Apple's Human Interface (HI) Toolbox, a framework to handle UI. While I have no idea what is causing this error, finding related issues through Apple's [forums](https://discussions.apple.com/thread/677675) seems to suggest to me something along the lines of not handle User event or draw properly. 

[This post](https://developer.apple.com/forums/thread/724360) posted on Apple's forum two days ago seemed to be related, but no solution as well.

[This post](https://stackoverflow.com/questions/74609260/r-warnings-errors-in-a-fresh-install) on stackoverflow suggested success with setting the Menu Bar from "Never" back to "In Full Screen Only". Can you give this a try and report back? 😄 

Maybe someone who is more well versed with development on macOS can chip in?
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1417708064" expanded>

I adopted the principle of

> Make It Work, Make It Right, Make It Fast!

Am on the making it work part now 😄 

![image](https://user-images.githubusercontent.com/58366602/216818769-982eedfe-7ab8-4ebf-914f-b3c6e7dc8518.png)

</panel>

</panel>


<panel type="info" header="### 80. YEOH.. JIE `@yyj-02` (5 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/80#issuecomment-1407614079" expanded>

You can follow the guide [here](https://devconnected.com/how-to-delete-local-and-remote-tags-on-git/):

1. Delete the tag locally `git tag -d Level-7`
2. Delete the tag remotely `git push --delete origin Level-7`
3. Create your new tags and push them

(You can use `git log` to find the commit id)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/92#issuecomment-1407672828" expanded>

Hi @rockman007372 , I am not a TA but in my opinion, returning `(1. ... 2. ...)` would be a better design choice from a UI standpoint, it feels more intuitive for the user. If they need to know the correct index to delete the task, they can use the `list` command instead.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/156#issuecomment-1427201173" expanded>

In my opinion, I feel that as long as the code is easily readable and understandable, it is fine. The purpose of having good code quality is such that developers in the future can modify your code easily, which I think your code has fulfilled. However, in the case where there are more commands, i.e. `find`, `on`, ..., what we can do is categorise the commands into groups of commands according to their functionality. We can use nested routes, e.g. `add/event`, `add/deadline`, `search/on`, `search/find`, etc. With this format, we can use `switch ... case` for the first part of the route first and `switch ... case` the second part in another class. Hope this helps.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/193#issuecomment-1432598966" expanded>

![image](https://user-images.githubusercontent.com/82926691/219287448-5c0318b8-30b4-4c6a-ab62-f4920cd36d7b.png)
Try clicking this elephant with the refresh icon 🐘🔃 or use `Ctrl+Shift+O` to load gradle change.
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/192#issuecomment-1432603036" expanded>

How I will approach this is I will take in the `filepath` as an input string. And I will use `new File(filepath).getParentFile().mkdirs()` to create the directories if they don't exist. Lastly, do a check if the file exists with `new File(filepath).exists()`. And if it doesn't exist, create it with `new File(filepath).createNewFile()`. @jamieeeleow 
</panel>

</panel>


<panel type="info" header="### 81. TING.. XIN `@tyx021` (5 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: PE Readiness Quiz result**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/370" expanded>

Hi, I noticed that it was mentioned in the quiz:

> "Please ensure you know the correct answer to every question in this quiz."

However, after I have submitted the quiz, canvas is showing neither the correct answer / how many questions I got it right. How am I supposed to know "I know the correct answer" before PE since the canvas quiz is due on the day of PE?
</panel>

<panel  header="**2. :fas-info-circle: Week 11 Quiz Question 41**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/279" expanded>

> Question 41
> A platform comes with a runtime.

Is there a typo here? What does "comes with a runtime" here means? 🤔 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/208#issuecomment-1435517732" expanded>

Try this? https://github.com/nus-cs2103-AY2223S2/forum/issues/102#issuecomment-1409829287
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/279#issuecomment-1484153008" expanded>

I see, thank you prof :)
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/370#issuecomment-1504543185" expanded>

I can see the answer now :)
</panel>

</panel>


<panel type="info" header="### 82. CARM.. ANG `@cmang12` (5 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Encounter exception when building with gradle**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/154" expanded>

Hello, I tried to run gradle but it threw an error. 

![image](https://user-images.githubusercontent.com/85399634/217794098-0012ee32-039c-4b23-a4ae-1378534d1763.png)

My build.gradle file looks like this:
```
plugins {
    id 'checkstyle' 
    id 'java'
    id 'application'
    id 'com.github.johnrengelman.shadow' version '5.1.0'
}
```
```
dependencies {
    testImplementation group: 'org.junit.jupiter', name: 'junit-jupiter-api', version: '5.5.0'
    testRuntimeOnly group: 'org.junit.jupiter', name: 'junit-jupiter-engine', version: '5.5.0'

    String javaFxVersion = '11'

    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'linux'
}

application {
    mainClassName = "seedu.duke.Main"
}

shadowJar {
    archiveBaseName = "duke"
    archiveClassifier = null
}
```
Does anyone know what's wrong? Thank you! 




</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/154#issuecomment-1424475520" expanded>

Hmm it still doesn't work. I also tried duke.Launcher, it showed this: 
![image](https://user-images.githubusercontent.com/85399634/217877148-21d4ac29-4602-444e-a3f2-91c15dec2afe.png)

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/154#issuecomment-1424491974" expanded>

I checked my project structure and I'm using JDK 11. Also, inside the gradle-wrapper.properties file, the distribution url is: distributionUrl=https\://services.gradle.org/distributions/gradle-6.2-bin.zip, 
if it matters. 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/154#issuecomment-1425158827" expanded>

Hi everyone thank you for the suggestions, I changed the application path and restarted my IDE. Still, running gradle through terminal doesn't work. However, I ran shadowJar through the gradle tab and the build was successful. Is this a JDK compatibility issue? 
</panel>

<panel  header="**5 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/154#issuecomment-1425998855" expanded>

Ah I see the problem now, thanks everyone! 
</panel>

</panel>


<panel type="info" header="### 83. ANG .. JIE `@ajjajjajjajj` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Running into font issues with JDK 11 (macOS Big Sur)**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/302" expanded>

Opening the jar file provided for the PE dry run resulted in the font looking like this:

<img width="739" alt="Screenshot 2023-03-31 at 3 08 46 PM" src="https://user-images.githubusercontent.com/86147552/229048659-7adc8d61-05af-410f-8e6c-5ddd857e5b51.png">

I have tried uninstalling other JDK versions on the machine (Intel macOS Big Sur) and reinstalling JDK 11 (as linked in the CS2103 website). This is the output when I run `/usr/libexec/java_home -V` in the terminal:

<img width="858" alt="Screenshot 2023-03-31 at 3 07 47 PM" src="https://user-images.githubusercontent.com/86147552/229048429-92a3d2fd-8dd0-4dd4-b4ba-8a225e18acfa.png">

I have also tried running the jar file via `java -jar filename.jar` and received the same result.
Any advice on how to resolve this text encoding issue will be much appreciated. 
</panel>

<panel  header="**2. :fas-info-circle: Default tasks with .jar file**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/182" expanded>

For the final submission, we're required to create a .jar file using Gradle, and submit just the .jar.

While I was doing this, I found that my default tasks will not be carried over. This is because my `data/` folder containing the text file for storage is located in the project's root directory, and is independent of the Java files. When I add new tasks in the standalone .jar application, a new data folder is created wherever the .jar file is.

I've tried moving the `data/` folder into `src/main/`, but when the .jar is built, the storage text file is empty, and is separate from the .jar file anyway.

The only solution I can come up with to this is to write a separate class to create default tasks when the .jar is launched. But this will result in the default tasks to be loaded in each time, and writing a new class to circumvent the text file storage method doesn't seem appropriate. 

Does anyone have any alternative suggestions for this? Or should I just not bother having default tasks for the final submission?

Thanks!

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/81#issuecomment-1407560571" expanded>


> I personally do not know of any way to specify datetime objects in arbitrary formats beyond using `DateTimeFormatter` (example [here](https://mkyong.com/java8/java-8-how-to-format-localdatetime/)). Perhaps you could use `try catch` blocks to account for a few common formats, then handle unrecognised formats as you feel make sense.

I did it this way as well, and this felt like the best compromise between flexibility and making full use of DateTime. You can define the formats statically and try all of them while creating the Task. It makes it easier to incorporate extra features in the future that require using DateTime too.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/182#issuecomment-1429069168" expanded>

> What is the behaviour of your code when a save file doesn’t exist? Perhaps you can add your template tasks during the creation of a new save file.

Currently it just creates a folder with an empty text file. This sounds like a sensible solution though. Thank you!
</panel>

</panel>


<panel type="info" header="### 84. LUM ..KIAT `@weekiat-douze` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Is it ok to omit arguments for method invocation in sequence diagrams?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/253" expanded>

<img width="708" alt="sequence" src="https://user-images.githubusercontent.com/58362911/224536236-8bf243c8-c7f0-4b94-862d-10f5180b915d.png">

The example here is also not in the method() format. Is there any restrictions when drawing invocations in sequence diagram?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/161#issuecomment-1426777783" expanded>

Hi, I believe it's because one of the dialog views have a fixed height. You can try to set it to "computed" via SceneBuilder if I'm not wrong. 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/253#issuecomment-1465144507" expanded>

@damithc 
I see. Then would it be wrong if arguments are excluded in the pseudo code? 
For example, Week 8 Tutorial, 
addPerson() instead of addPerson(p) or Person() instead of Person("Adam", "friend")
```
PersonList personList = new PersonList();
while (hasRoom) {
    Person p = new Person("Adam", "friend");
    personList.addPerson(p);
}

```
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/253#issuecomment-1465149011" expanded>

I see, understood. Thank you!
</panel>

</panel>


<panel type="info" header="### 85. HAIQ..AFFI `@Acerizm` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: My PED is not tracked for some reason**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/305" expanded>

I checked my status for participation for PED and it was recorded that I did not participate but I did. Did I do something wrong? Catcher created a repo of the issues that I raised at https://github.com/Acerizm/ped/issues

</panel>

<panel  header="**2. :fas-info-circle: Level-7: Using Serialization/Deserialization to save/load data**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/90" expanded>

Would serializing and deserializing objects to store into our .txt file acceptable for Level-7? The reason being that it is much simpler to store and retrieve objects like our `taskList` of type `List<Task>` but our data stored in the `data\.txt` will not be human readable.

## Serializing list of task to save in `.txt` file
```java
/*
* Save tasks to the .txt file while using serialization
*/
public  static  void  saveTasks(List<Task> taskList) {
    String  filePath  =  "data"  +  File.separator  +  ".txt";
    try (ObjectOutputStream  save  =  new  ObjectOutputStream(new FileOutputStream(filePath))) {
        save.writeObject(taskList);
    } catch (Exception  e) {
        System.out.println("Cannot save");
    }
}
```
## Deserializing list of task from `.txt` file
```java
/*
* Load tasks from .txt file while using deserialization
*/
public  static  List<Task> loadTasks() {
    String  filePath  =  "data"  +  File.separator  +  ".txt";
    try (ObjectInputStream  load  =  new  ObjectInputStream(new FileInputStream(filePath))) {
        List<Task> taskList  = (List<Task>) load.readObject();
        return  taskList;
    } catch(Exception  e) {
	System.out.println("file is mssing!");
	return new ArrayList<Task>();
    }
}
```
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/90#issuecomment-1407608837" expanded>

@damithc Thank you Prof!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/305#issuecomment-1492997806" expanded>

Sorry prof I got confused with the week my bad! 
</panel>

</panel>


<panel type="info" header="### 86. SAMU..GASU `@axmszr` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Possible typo in Checkstyle Guide**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/77" expanded>

Hello! The guide at https://se-education.org/guides/tutorials/checkstyle.html suggests to use `//CODESTYLE.OFF: RuleName` and `//CODESTYLE.ON: RuleName` to suppress a rule for a portion of code. However, when I tried it, it only worked when I replaced "`CODESTYLE`" with "`CHECKSTYLE`".

Could I ask if this is an error on the site, or if `CODESTYLE` does something different that I missed? Thanks!
</panel>

<panel  header="**2. :fas-info-circle: Force-pushing existing tags (Sourcetree)**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/37" expanded>

Hello! I've been having a couple issues with pushing existing tags to my remote (GitHub) repo when I've re-assigned them to a newer commit:
![image](https://user-images.githubusercontent.com/72402917/213848361-5b201cf4-e9b4-4566-b2bc-f06b0f8f81ca.png)
![image](https://user-images.githubusercontent.com/72402917/213848391-996ea119-6f80-47d5-bdfc-1d1282f6eab5.png)

I understand that it doesn't like pushing such 'moved' tags, and it works perfectly fine when I force push via the terminal with something like `git push origin -f Temp-Test`.

However, when I try enabling Force Push on Sourcetree (with Safe Force Push `--force-with-lease`) in order to automatically push these tags, I run into this issue:
![image](https://user-images.githubusercontent.com/72402917/213848593-6476624b-f917-4b30-9c3b-7293679ab54c.png)

Turning off the "Use Safe Force Push" option fixes this, and I plan to keep my settings this way for the time being:
![image](https://user-images.githubusercontent.com/72402917/213848666-0f28980a-932c-48e8-b30b-c3b476b77f7d.png)

Could I ask if this is safe, or if it is bad practice? I'm not sure what complications this may lead to in tP or more complex projects, and stackoverflow isn't really giving me advice I understand :P

Thank you!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/37#issuecomment-1399432871" expanded>

Thank you @hingen for the information; I'll definitely keep that in mind moving forward! Fortunately I haven't run into issues with git history or deleted commits yet in the iP, but I'll likely avoid force-pushing altogether for the upcoming tP.
And thanks @Junyi00 for the suggestion! I will follow that safer route if there is any risk involved.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/77#issuecomment-1407418324" expanded>

Thank you Prof!
</panel>

</panel>


<panel type="info" header="### 87. TRAN..HANG `@lennoxtr` (4 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Changing Error Message in v1.4**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/364" expanded>

Is it possible for us to change the error message for v1.4 if what is shown to the user is wrong (such as an error message about exporting file when user is importing)

Thank you!

</panel>

<panel  header="**2. :fas-info-circle: Question regarding changing export file format**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/307" expanded>

In our group's program, we allow the user to enter commands to export the current data to a file and import the data from a file.

The export command was missed out in the user guide documentation, but the intended behavior is such that if the user exports to a file that is not in JSON format, the program would throws an error. The current behavior, however, allows the user to export to a file that is not in JSON format, and then throws an error when the user import that file as it could not be read. Will this be considered a bug?
</panel>

<panel  header="**3. :fas-info-circle: Execution of commands causes User Input Box to be out of focus**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/263" expanded>

**Description:**
After executing a command, the user's "Enter Command" box becomes out of focus and the user has to click the box to input commands again

**Steps for reproducing**

tag CS2040 /tags fun, hard

**Expected result**
User should still be able to type commands in the "Enter Command" box

**Actual result**
User has to click the "Enter Command" box again to provide input

**Other details**
None

**Error output**
None



</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/263#issuecomment-1474772170" expanded>

Wrong repo
</panel>

</panel>


<panel type="info" header="### 88. WANG..EFAN `@Nafeij` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Are we allowed to revert the repo to an older commit as a basis for our tp?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/187" expanded>

For direction 2 (Morphing)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/74#issuecomment-1406057347" expanded>

Try the following steps:

1. In Sourcetree, navigate `Settings (Repository settings) ->Remotes -&gt; Select Origin -&gt;  Edit`
2. Set URL/Path in the following format:  `https://&gt;TOKEN>@&gt;GIT_URL>.git`

P.S> Next time, [please provide more details :)](https://github.com/nus-cs2103-AY2223S2/forum/blob/master/.github/ISSUE_TEMPLATE/help.md). Also, when posting an error or stack trace, please Copy-Paste it as text instead of a screenshot so that it is searchable.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/76#issuecomment-1406532217" expanded>

@heeeyi
The JavaFX runtime instantiates an instance of your Application subclass using reflection. It does this by assuming and using the public no-arg constructor of the class. Since it's baked into the base class's design, there are no two ways about it: you need a `public Duke()` constructor.
However, I understand your concerns about code quality w.r.t just supplying a dummy constructor. Perhaps you could put the empty constructor to use by calling the overloaded constructor with a default value?

``` java
public static final DEFAULT_PATH = "data.txt";
...
public Duke() {
    this(DEFAULT_PATH);
}
```
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/187#issuecomment-1432499957" expanded>

Thanks Prof!
</panel>

</panel>


<panel type="info" header="### 89. GUO ..LONG `@gyulong1` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Question regarding wrong error message displayed**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/329" expanded>

Hi Prof, we have a typo in the error message that is displayed to our users where it says "more than one" instead of "one or more". However, the behaviour is described correctly in our User Guide. 

Would changing the error message be considered fixing a bug since a misleading error message is shown or a feature enhancement since normal user usage is not affected by the bug?
</panel>

<panel  header="**2. :fas-info-circle: Question regarding what bug fixes are allowed**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/323" expanded>

Hi Profs,

We currently have a profile picture feature and the intended behaviour is to show a default profile picture for new employees. 
However, we did not realise that the default picture does not appear in the .jar version, so no picture appears instead.
This leads to some graphical bugs, like the wrong employee's image being displayed.

To fix this, we can either fix the default picture implementation or implement show no picture at all for new employees.

Would we be allowed to implement the default picture as a bug fix?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/323#issuecomment-1496284914" expanded>

Thanks prof!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/329#issuecomment-1496326536" expanded>

Thanks prof!
</panel>

</panel>


<panel type="info" header="### 90. JEFF..HEAN `@jefrai` (4 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/83#issuecomment-1407463153" expanded>

Yep, sounds like a similar issue to #63.

On the Project Structure menu in the second screenshot, clicking 'Edit' (or 'SDKs' on the left) should show the path of the JDK used by IntelliJ for the project.
For me it looks like `C:\Users\username\.jdks\jdk-11.0.18`. Try copying your own path and setting it as the JAVA_HOME env var.

E.g. for Powershell:
```
$env:JAVA_HOME='C:\Users\username\.jdks\jdk-11.0.18'
```
For cmd:
```
set JAVA_HOME=C:\Users\username\.jdks\jdk-11.0.18
```

See if gradlew commands work after that - if that fixes it, you can also consider setting JAVA_HOME permanently, but remember to change it back if you have anything that uses other JDK versions.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/161#issuecomment-1426838793" expanded>

It's difficult for the program to tell exactly which words are cut off - JavaFX doesn't provide a way to retrieve that info from its nodes. Instead, you might want to make the whole GUI resizable so that the user can drag it horizontally to see longer messages:

Try to resize your GUI as it is - some nodes should follow the new borders nicely, while others will stay stuck in their original positions.

![0Capture](https://user-images.githubusercontent.com/30693850/218272619-06b048fe-aef3-4f53-b672-999a4812dda9.PNG)

Select the stuck nodes in SceneBuilder, and bind their sides to the appropriate borders of the `AnchorPane`:

![2Capture](https://user-images.githubusercontent.com/30693850/218272815-146511ab-aec8-4efd-85e9-cd6825c0af82.png)

Some nodes in `DialogBox` might need to have their heights and widths changed as well. Once all nodes scale correctly, the GUI should be able to expand and display longer text.

![3Capture](https://user-images.githubusercontent.com/30693850/218273303-7b841efd-877d-47b2-8cb3-1e559ffc08a7.PNG)

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/22#issuecomment-1426854483" expanded>

I'd agree that exceptions are best used when the following two conditions apply:

1. The situation you are trying to catch is an undesirable (but foreseen) deviation from the ideal outcome
(i.e. _exceptional_ outcome)
    - The results of an ideal outcome should be handled (and ought to be _easy to handle_) using normal code.
2. You want to expose this exceptional outcome to the caller code to handle, instead of absorbing it within the method itself
    - If you intend to recover within the method, it's typically cleaner to use `if`-statements (especially guard clauses), rather than `throw`ing an exception only to immediately `catch` it.

In the IP context, point 2 didn't hold for many projects at the time this question was asked - parsing, executing commands, and other logic was often all being done in the same method, so tracking errors would be better handled using booleans and other variables.

However, after week 3 and `A-MoreOOP`, parsing and command execution was separated into individual classes. It then made sense for `Parser` and `*Command` to pass back their errors by throwing exceptions to their main calling method.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1434949598" expanded>

I decided to split off the task list into its own panel:

![miki](https://user-images.githubusercontent.com/30693850/219717434-a4974406-beb8-4752-8bf6-487bfb58f0e3.PNG)

</panel>

</panel>


<panel type="info" header="### 91. LIN ..HIEH `@euph00` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: runtest.bat: FC is not a recognised command**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/44" expanded>

I have attempted to run runtest.bat by `./runtest.bat` from my command line (powershell, windows 11) while in the directory text-ui-test and it works fine until the last line where file compare is invoked. It seems to insist that 
`FC is not recognised as in internal or external command, operable program or batch file`
which got me a bit confused. It is not much of an issue as I am able to work around it and the runtest.sh bash script works for me no issues. Just curious how I would fix this issue or what I am doing wrong.

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/44#issuecomment-1403015609" expanded>

@RichDom2185 thanks for the suggestion, that works properly now. I was under the impression that ps and cmd were functionally identical except ps supports scripting in powershell as well. Thanks for the help and sorry for noob mistake
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/81#issuecomment-1407552537" expanded>

Personally I restricted my bot to only accept a strict formatting of date and would prompt the user to re-input if improperly formatted, though I do agree with @XylusChen in that the approach of saving an unrecognised format as a String could be a good alternative. However, I wanted conformity to allow events to be filtered, searched and sorted by date cleanly.

I personally do not know of any way to specify datetime objects in arbitrary formats beyond using `DateTimeFormatter` (example [here](https://mkyong.com/java8/java-8-how-to-format-localdatetime/)). Perhaps you could use `try catch` blocks to account for a few common formats, then handle unrecognised formats as you feel make sense.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/139#issuecomment-1416766186" expanded>

Thanks for this issue, got really confused right off the bat while I was watching the lecture recording just now. Also thanks to profs for responding on a Saturday afternoon/night.
</panel>

</panel>


<panel type="info" header="### 92. CHOW..GLAS `@Douglch` (4 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Made a typo in PPP**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/373" expanded>

Hello Profs, I just realised I made a typo on my PPP where I wrote `edit` instead of `update` in the Update section as well as the `find` part which does not exist in the Managing Clients section and in other sections, written by my groupmates instead. Is there any additional steps I need to take in terms of notifying someone?
![image](https://user-images.githubusercontent.com/48470532/231628286-d8ada3ba-e663-4922-a10f-80876f356ea4.png)

</panel>

<panel  header="**2. :fas-info-circle: Cannot run Launcher.java when following Tutorial 1**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/122" expanded>

Intellij Version: 2022.3.1
Java version: 11.0.14.1
OS: Windows
Github branch: [branch-Level-10](https://github.com/Douglch/ip/tree/branch-Level-10)

I followed the instructions for tutorial 1 for JavaFX, adding the appropriate lines and imports to my main class accordingly as well as in the Launcher.java class created. However, I kept faced the issue below when I tried running Launcher.java for the final step of the tutorial. 
The execution below was ran with --stacktrace.

```> Task :Launcher.main() FAILED
Exception in Application constructor
Exception in thread "main" java.lang.RuntimeException: Unable to construct Application instance: class lele.Lele
	at com.sun.javafx.application.LauncherImpl.launchApplication1(LauncherImpl.java:890)
	at com.sun.javafx.application.LauncherImpl.lambda$launchApplication$2(LauncherImpl.java:195)
	at java.base/java.lang.Thread.run(Thread.java:829)
Caused by: java.lang.NoSuchMethodException: lele.Lele.<init>()
	at java.base/java.lang.Class.getConstructor0(Class.java:3349)
	at java.base/java.lang.Class.getConstructor(Class.java:2151)
	at com.sun.javafx.application.LauncherImpl.lambda$launchApplication1$8(LauncherImpl.java:801)
	at com.sun.javafx.application.PlatformImpl.lambda$runAndWait$12(PlatformImpl.java:455)
	at com.sun.javafx.application.PlatformImpl.lambda$runLater$10(PlatformImpl.java:428)
	at java.base/java.security.AccessController.doPrivileged(Native Method)
	at com.sun.javafx.application.PlatformImpl.lambda$runLater$11(PlatformImpl.java:427)
	at com.sun.glass.ui.InvokeLaterDispatcher$Future.run(InvokeLaterDispatcher.java:96)
	at com.sun.glass.ui.win.WinApplication._runLoop(Native Method)
	at com.sun.glass.ui.win.WinApplication.lambda$runLoop$3(WinApplication.java:174)
	... 1 more

FAILURE: Build failed with an exception.
```


</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/122#issuecomment-1412359691" expanded>

Damn bruh you the 🐐,  thank you :)
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/373#issuecomment-1506306023" expanded>

Noted, thank you!
</panel>

</panel>


<panel type="info" header="### 93. RYAN..JIAN `@ryanchua00` (4 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Multiple warnings on terminal regarding mismatch in fxml versions**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/334" expanded>

Hi Profs, 

I'm unsure if this is a functionality bug. Whenever we start the application, we receive many warnings regarding mismatched JavaFX API version and JavaFX runtime version. This was flagged to us as a functionality bug during the PED. I feel like it isn't a feature flaw as there isn't a missing component or poor design at play here. Would we be allowed to fix it?

Thanks!

![image](https://user-images.githubusercontent.com/62086995/230095978-cc73ec84-60a5-4f35-b97c-cbab63f0a4b9.png)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/143#issuecomment-1418375218" expanded>

I often run into the same dilemma, and declare the variable outside the switch statement. Funnily enough, [Oracle docs](https://docs.oracle.com/javase/tutorial/java/nutsandbolts/switch.html) also declares the variable outside the statement.
Would the fall through condition help in your case? 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/296#issuecomment-1489980592" expanded>

A [SortedList](https://docs.oracle.com/javase/9/docs/api/javafx/collections/transformation/SortedList.html), similar to FilteredList, can be used to wrap the Observablelist to sort by property.

Originally in ModelManager, FilteredList wraps ObservableList to allow for filtering. A SortedList can wrap the original ObservableList in similar way.




</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/334#issuecomment-1498443573" expanded>

Thanks prof!
</panel>

</panel>


<panel type="info" header="### 94. YAM ..NARD `@LeonardYam` (4 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Gradle and I/O testing**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/38" expanded>

#36 Related to this

Hi all 

As my code relies on an external library, I wanted to check if it is acceptable to use Gradle to manage dependencies. (since it seems to be the suggested best practice over adding external .jar files)

In addition, using Gradle means that I am unable to use javac for the automated I/O test. Thus, I wish to clarify if the following script is also acceptable.

```
# Removing previous test output ...

# Uses gradle shadowJar to build
cd ..
./gradlew clean shadowJar
if ! [ -d "./build" ]
then
    echo "********** BUILD FAILURE **********"
    exit 1
fi

# Go back to test directory
cd text-ui-test
# run the program, feed commands from input.txt file and redirect the output to the ACTUAL.TXT
java -cp "../build/libs/ip-1.0-SNAPSHOT-all.jar:../build/classes/java/main" Main < input.txt > ACTUAL.TXT

# Comparing input and ouput files ...
```
</panel>

<panel  header="**2. :fas-info-circle: Request for Apache Commons library**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/36" expanded>

## Library

[Apache Commons Lang](https://commons.apache.org/proper/commons-lang/)

## Purpose

Using StringUtils.countMatches to count the number of occurrences of a substring in a given string - used to validate inputs

## License

Released under Apache License 2.0
https://www.apache.org/licenses/

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/38#issuecomment-1399241581" expanded>

Alright, thanks Prof!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/79#issuecomment-1406684728" expanded>

There might be an issue with your build.gradle file - what does it look like?

There should be a plugin like so in your build.gradle file

``` 
plugins {
    id 'com.github.johnrengel.......'
}
``` 
</panel>

</panel>


<panel type="info" header="### 95. BENJ..N EN `@benjamin-wee` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Mistakenly did Level-10 on master**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/159" expanded>

I did my GUI implementation on master and did not do it on a separate branch by mistake. I have already pushed my changes and moved on to week 5 increments. May I ask if there is any way to resolve this? Thank you!
</panel>

<panel  header="**2. :fas-info-circle: Unable to get the images to appear on my GUI**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/147" expanded>

I followed the code for tutorial 4 on Using JavaFX and FXML completely, and the other features of my GUI are working completely fine, but I am simply unable to get my images to load on the GUI.

The code that I used to initialise the images is attached below:
<img width="853" alt="Screenshot 2023-02-08 at 8 02 26 AM" src="https://user-images.githubusercontent.com/77018967/217395269-0603fb38-ac32-4c0f-b6e7-9e3adeb4cb8e.png">


The following is my project directory
<img width="321" alt="Screenshot 2023-02-08 at 8 02 51 AM" src="https://user-images.githubusercontent.com/77018967/217395369-d2085a40-2c9a-41a5-a2b1-e2f1d21d66b6.png">


Has anyone else faced a similar issue and know how to fix this? Thank you!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/147#issuecomment-1422176178" expanded>

> Have you tried another set of images? Sometimes the image is actually `.jpeg` but it's labeled as `.png` and java might not render it properly.

Turns out this was the issue! I actually downloaded a .webp image and converted it to png to be used and maybe that's why it didn't work. I just tried downloading a png image from the sort to be used and my gui works fine now! Thank you so much for your help!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/159#issuecomment-1425502497" expanded>

> See: [#137 (comment)](https://github.com/nus-cs2103-AY2223S2/forum/issues/137#issuecomment-1416647054)

thank you so much!
</panel>

</panel>


<panel type="info" header="### 96. CLEV..YONG `@clevon-w` (4 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: iP deadline**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/199" expanded>

![image](https://user-images.githubusercontent.com/88370247/219552903-c1cc00a9-cb21-4037-a980-6f7f26c9e22c.png)
This is a pretty dumb question but what does this mean? So when is the deadline of the iP and is there a hard deadline for it? If there is a hard deadline, when is it?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/94#issuecomment-1408105187" expanded>

@gremmyz I am facing the same issue as @FredericChow00 but I did merge my `branch-Level-8` with the `master` branch.
Like @FredericChow00, all other branches were detected except for `branch-Level-8` as shown in the images below.

![image](https://user-images.githubusercontent.com/88370247/215411501-695868ab-639a-4e7e-a146-a0bf3de000b3.png)
<img width="363" alt="image" src="https://user-images.githubusercontent.com/88370247/215411584-bd2d1d74-e99c-4cca-91b5-fc8b39d7d92f.png">

Any help from anyone would be deeply appreciated!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/193#issuecomment-1432610599" expanded>

> ![image](https://user-images.githubusercontent.com/82926691/219287448-5c0318b8-30b4-4c6a-ab62-f4920cd36d7b.png) Try clicking this elephant with the refresh icon 🐘🔃 or use `Ctrl+Shift+O` to load gradle change.

Yep this works for me! Thanks for the help!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/199#issuecomment-1434113787" expanded>

thanks prof
</panel>

</panel>


<panel type="info" header="### 97. MERR.. JIE `@Merrickneo` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: [A-CI] unable to push my changes to GitHub**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/144" expanded>

Followed the instructions listed for A-CI but I am unable to push my changes to Github for some reason.
 [https://se-education.org/guides/tutorials/githubActions.html](https://se-education.org/guides/tutorials/githubActions.html)

The error message is attached here.
<img width="551" alt="Screenshot 2023-02-07 at 12 51 13 AM" src="https://user-images.githubusercontent.com/71166759/217033993-405203e9-3196-4800-a5c1-cee58fd2a83f.png">

My directory is attached here as well
<img width="1285" alt="Screenshot 2023-02-07 at 12 57 25 AM" src="https://user-images.githubusercontent.com/71166759/217035026-026e3ae2-b7cf-44d5-93dc-064fccb1b764.png">

I think it has got to do with the "OAuth scope" of GitHub but I'm not sure of how to address this. Would appreciate any help on the matter!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/5#issuecomment-1383142637" expanded>

I normally just make use of `ls -a` to review hidden files. If my IDE doesn't show the .gitignore file, I'll just make use of vim to access the file and make edits to it.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/144#issuecomment-1420105218" expanded>

Created a new PAT and it worked! Thanks, everyone 👍 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/163#issuecomment-1429691079" expanded>

For my group, we just edited the README.md file. After pushing to GitHub, we were able to do the Pull Request. Hope this helps!
</panel>

</panel>


<panel type="info" header="### 98. KRIS..VEEN `@praveenkrishna0512` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: What are the requirements for testing GUI?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/346" expanded>

n/a
</panel>

<panel  header="**2. :fas-info-circle: Regarding Recommendation-CLI-First**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/265" expanded>

My team is wondering if selecting GUI Regions in the app (ie. a mouse input to click) violates the recommendation to have the application be tailored to be CLI-First.

In essence, do the following examples violate the recommendations?
- If the user wants to view a contact in the AddressBook, but they have to scroll through a list to do so.
- If the user wants to select a contact in the AddressBook to view more details, but they have to click on the ListView object to do so.

Appreciate any help!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/265#issuecomment-1476136600" expanded>

Alright thank you!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/346#issuecomment-1500331823" expanded>

thank you!
</panel>

</panel>


<panel type="info" header="### 99. GONG.. JUN `@0x787af25e` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: jar file runs on Windows but not Linux**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/179" expanded>

I have created the final jar file, and on the second smoke test involving asking team members running other operating systems to run my jar file, an unexpected error has occurred. 

![image](https://user-images.githubusercontent.com/74492257/218466049-1370d467-09d8-43cb-af4d-97068f81a5b4.png)

The host operating system is Ubuntu 22.04, and it is able to run other iP jar files.
</panel>

<panel  header="**2. :fas-info-circle: Issue with Gradle setup**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/89" expanded>

I am facing problems after installing Gradle, where new changes to my program are ignored. When I type in code, these new lines of code are not executed; the debugger also stops at lines that are empty as those lines were populated with code before I added in new lines of code.

My 'build.gradle' file:
'
plugins {
    id 'java'
    id 'application'
}
'
I am able to successfully build with Gradle.
![image](https://user-images.githubusercontent.com/74492257/215315004-94a2ba76-7f86-451e-a081-f760daf52db0.png)

I am running OpenJDK 17.0.3.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/89#issuecomment-1407668963" expanded>

![image](https://user-images.githubusercontent.com/74492257/215330369-b9ce62e5-a391-4c79-9fc3-446e844f633b.png)
Issue still persists after switching over to Java version 11. 
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/89#issuecomment-1407671178" expanded>

![image](https://user-images.githubusercontent.com/74492257/215331043-8e43a9d8-3c3e-4bec-9119-69b249fb26c3.png)
This is all there is, as mentioned above.
</panel>

</panel>


<panel type="info" header="### 100. NG J..YUAN `@jnjy` (4 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: IP Code Dashboard not updated**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/97" expanded>

Hi,

I went to check my IP code dashboard and found out that some of my tags and commits are not updated in the dashboard. I double checked if I have successfully merged and pushed it with the IP Progress Dashboard as well as SourceTree. It seems that I have successfully merged and pushed the code. Below are the problems that I am facing:

- For the two images below, Tag `Level-9` is present in my Progress Dashboard but not shown in code Dashboard.

![image](https://user-images.githubusercontent.com/87219903/215494191-3c061ff3-bf27-475a-96b0-33fa5a82eaa8.png)

![image](https://user-images.githubusercontent.com/87219903/215494340-e1e88ab8-6b4c-4561-8316-a1ec163af2a5.png)



- The next two images show the mismatch in my GitHub commits and the code dashboard. Commits seem to not be updated on the code dashboard as well.

![image](https://user-images.githubusercontent.com/87219903/215495242-86f76893-51a7-48ba-be94-7708ceef3de1.png)

![image](https://user-images.githubusercontent.com/87219903/215495399-e812d324-c63c-4e30-a6c5-dd1d95e4f817.png)




May I ask what could I be missing on here?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/52#issuecomment-1401366672" expanded>

Thanks OP for the question!

Adding on to Sean’s answer, the java split() function takes in regex and | is the logical `OR` expression. In order to split word using the indicated character `|`, you would need to use the escape character `\`. However, since `\` is also a meta character in String literal, you would need another `\` to escape it. Hence, you would need `\\|` as mentioned by Sean. An alternative way to split is to use `split(Pattern.quote(‘|’))`. I have attached the function definition below for your reference.

![image](https://user-images.githubusercontent.com/87219903/214209662-c13762af-ed78-4e5b-b98b-0f16f8adfe4d.jpeg)

`Contains()` method simply searches char sequences in the given string and `|` is in the given string.

You may reference to the image below as which characters require the escape sequence.

![image](https://user-images.githubusercontent.com/87219903/214209968-4385850c-8ad8-4b7f-bdac-771c2bd39f05.jpeg)


</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/82#issuecomment-1407446977" expanded>

Hi OP, I would like to share a link on [Oracle Convention](https://www.oracle.com/java/technologies/javase/codeconventions-indentation.html) in addition to the [Google Java Style Guide](https://google.github.io/styleguide/javaguide.html) provided in the coding standard guide.  Hope this will be helpful! 

Also, I personally would prefer to follow the coding standard which led to me choosing this option:
```
assertEquals(TaskDeadlineTest.getTestTask(),
        TaskDeadlineTest.getTestTask());
```

Reason being that Egyption Style braces may be very confusing if there is a really long method with nested braces involved. An example (might not be the best) I can think of would be:

```
# option A
new A(
        veryLongParam1,
        new B(
	        veryLongParam2, 
		veryLongParam3, 
		veryLongParam4))
```
vs
```
# option B
new A(veryLongParam1,
	new B(veryLongParam2, 
		veryLongParam3, 
		veryLongParam4))
```
Option B seems clearer and more intuitive to me as compared to option A. Would like to know what OP thinks about this though!
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/97#issuecomment-1409849752" expanded>

Thanks Prof for clarifying!
</panel>

</panel>


<panel type="info" header="### 101. SHIR..UPTA `@shirsho-12` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: TP Re-opening PR**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/230" expanded>

I'd created a pull request for the TP but had named it incorrectly. The NUS SE-Bot stated this
" Your team org is named incorrectly. It should be AY2223S2-CS2103T-W09-2
If that is the case, you can reopen this PR after renaming the org with the correct name. "

How do I re-open this pull request? Or do I just create a new PR?
</panel>

<panel  header="**2. :fas-info-circle: A class implementing an interface results in an is-a relationship, just like in class inheritance**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/2" expanded>

I am confused about the statement here. While both are instances of is-a relationships, are they both really similar?

In class inheritance, a subclass inherits properties and methods from its parent class, and it creates an "is-a" relationship between the subclass and the parent class. This means that an object of the subclass is considered to be an object of the parent class as well.

But when a class implements an interface, it is not inheriting properties and methods, instead, it is promising to provide an implementation for all the methods defined in the interface. The class is not inheriting any properties or methods from the interface, but it is providing an implementation for them. This creates an "is-a" relationship between the class and the interface, which means that the class is considered to be an implementation of the interface.

In a sense, class inheritance is a standard is-a relationship, but interfaces are more of a "can-do" relationship. 

Is my understanding here correct?
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/2#issuecomment-1384819453" expanded>

> @shirsho-12 Is the issue resolved? If so, you can close this issue. If no, post more details so that others can follow up.

Alright prof, apologies for not closing sooner.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/43#issuecomment-1399796784" expanded>

If gradlew run doesn't work can you try running ./gradlew, PowerShell doesn't work without the ./ As far as I know
</panel>

</panel>


<panel type="info" header="### 102. GU H..IWEI `@WilliamHaiweiGu` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Are org.apache.commons libraries considered third-party?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/368" expanded>

[Apache Commons](https://commons.apache.org) has many Java libraries. Considering its formalness and wide usage, I never thought about this but are Apache Commons libraries considered third-party?

If so, can I add it to the acknowledgment section of my TP docs right now? Thank you!
</panel>

<panel  header="**2. :fas-info-circle: Gradle cannot build/run/clean using command line.**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/63" expanded>

So I just merged add-gradle-support branch into master branch.
The code can build & run using IJ's built-in tools.
The code can also build, run, and clean successfully by double clicking the task in gradle panel:
![image](https://user-images.githubusercontent.com/55661715/214570576-4dca09f1-98cf-40cc-a7af-ba2ca11efc85.png)
But when I tried to run these into terminal:
`gradlew build` failed with java.lang.NoClassDefFoundError: Could not initialize class org.codehaus.groovy.vmplugin.v7.Java7.
`gradlew run` and `gradlew clean` also failed with java.lang.NoClassDefFoundError: Could not initialize class org.codehaus.groovy.runtime.InvokerHelper.
How do we build/run/clean gradle using command line? Thank you!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/63#issuecomment-1403628560" expanded>

> @WilliamHaiweiGu It might help if you also describe the steps you took to incorporate Gradle into the project. Just merge the branch only or did you do any additional steps?

I also changed the gradle.build file so that `application.mainClassName` and `shadowJar.archiveBaseName` are both the class with `main` method.
[build.gradle.txt](https://github.com/nus-cs2103-AY2223S2/forum/files/10499723/build.gradle.txt)
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/63#issuecomment-1406332265" expanded>

> I also had same problem. Apparently, it was cause my PC's `JAVA_HOME` enviromental variable wasn't set.
> 
> > ## Edit:
> > Looking at the `gradlew.bat` script, it seems that if `JAVA_HOME` isn't set, it will fall back on whatever version ur commandline java is set to. U can check what version that is be entering `java --version` in ur commandline.
> > Mines apparently set to JDK17, which is probably what's causing the problems:
> > ![image](https://user-images.githubusercontent.com/35413456/215050004-7260ecce-e6b7-4d7a-8b01-593597ff6d17.png)
> 
> @WilliamHaiweiGu, try entering `echo %JAVA_HOME%` into ur command-line. What does it output?
> 
> It should output a JDK11 path like: `C:\Program Files\Java\jdk-11.0.14`
> 
> If it doesn't, then try setting it with these steps: https://help.sap.com/docs/SAP_BUSINESSOBJECTS_ANALYSIS,_EDITION_FOR_OLAP/c4341f1ce3324d9d9309163567effc1b/eca795926fdb101497906a7cb0e91070.html?version=4.2.7

This solved my issue. TSM!
</panel>

</panel>


<panel type="info" header="### 103. RISH..LKAR `@mmaimer33` (4 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Can we use something like Miro for DG diagram?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/308" expanded>

The requirements for diagrams for the Developer Guide say that whatever method we use needs to be able to be version-controlled. Would it be acceptable to use an online tool like [Miro](https://miro.com) to create them and then download and replace the local files as necessary?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/40#issuecomment-1399448703" expanded>

> Are we supposed to git add , and commit the code within level 7 first, and then change the branch, or is the code meant to be unchanged when changing the branch.

From the assignment it looks like we have to merge the branches only after both their implementation is complete, so the starting code would remain the same when working on either. Committing the code to each branch without merging would be wise, but would not affect other branches.

I think this requirement exists to help us appreciate how branches can be used. Level-7 and level-8 are unrelated and can use the same base code to build on. Because of this, in theory, there could be two people different people working on each aspect at the same time, and branches enable this by giving each a separate copy of the code to prevent interference. Any conflict resolution only needs to happen during merging that way.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/308#issuecomment-1493367178" expanded>

They could do it online: follow a link, make a copy of the diagram, and download it to update the file in the project.
</panel>

<panel  header="**4 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/308#issuecomment-1493475504" expanded>

Alright, thank you prof!
</panel>

</panel>


<panel type="info" header="### 104. MARK..G YU `@markusyeo` (3 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: 💎Update RSA-SSH host keys for Github**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/277" expanded>

If you're using RSA-SSH to connect to Github via CLI, you might need to update your keys as Github has refreshed them due to an accidental exposure of their host keys.

https://github.blog/2023-03-23-we-updated-our-rsa-ssh-host-key/

You may follow the instructions in the blog post as to how you can update them.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/34#issuecomment-1398254005" expanded>

It is interesting case that we us Java 11 which has not yet implemented the enhanced switch features that is implemented from Java 12/13 onwards. The enhanced witch introduces the possibility of having multiple values for each case which will reduce the need for fallthrough between cases which we use prior.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/359#issuecomment-1501323701" expanded>

Hello, I've encountered the issue before and typically it requires looking through the entire markdown file and making sure that your formatting is perfect!

Some issues that led me to not have the TOC generated are:
- Incorrect markdown syntaxing:
  - Did not leave space before and after headers or subheaders
  - Did not close or have incorrect html syntaxing
</panel>

</panel>


<panel type="info" header="### 105. NICH..HONG `@Nicklelodeon` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: JAR file is corrupted and cannot be opened**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/188" expanded>

Hi, I'm using an M1 Mac and I'm trying to run the smoke tests on my JAR file. I've tried sending my JAR file through telegram, but when I download the JAR file and double click it to run it, it tells me that the file is damaged and can't be opened. 
However, I can run the downloaded file on terminal through the command java -jar duke.java. Is this supposed to be the default way to run JAR files (i.e through terminal), or should I be able to run the JAR file by double clicking it? 
The duke.jar file in my build/libs folder (which I get directly from gradlew shadowJar) is able to run when double clicked.

Appreciate any advice given!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/188#issuecomment-1430869542" expanded>

Ok sure, thank you prof! Attached below is my JAR file in a zip folder.  
[duke.jar.zip](https://github.com/nus-cs2103-AY2223S2/forum/files/10740296/duke.jar.zip)

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/188#issuecomment-1430874137" expanded>

I tried downloading the file I uploaded here and it works. Thank you! 
</panel>

</panel>


<panel type="info" header="### 106. TAN ..VERN `@elvern18` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: .idea folder keeps reappearing**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/120" expanded>

Level: A-Gradle

was following the Gradle tutorial to set up Gradle. Deleted .idea folder but it keeps reappearing for some reason, and I am unable to run Duke anymore (Project JDK not defined error appears, but even after setting JDK 11, still unable to run) 

![image](https://user-images.githubusercontent.com/77615600/216054608-a8e5b457-bb17-4c6a-9ab9-652a92a76408.png)

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/120#issuecomment-1413974372" expanded>

Thanks prof and @hingen for helping out ! I have changed the mainClassName to Duke and set the JDK version to jdk-11 already. However, when i run the Duke, upon the command "bye" the program exits and shows this error.

![image](https://user-images.githubusercontent.com/77615600/216375417-99d214e7-98fa-49af-8644-6c919cef30b2.png)



Appreciate if you can help me out once again. Thank you ! 
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/120#issuecomment-1414407857" expanded>

Oh yes it works now, didnt have this problem in the other levels. Thank you ! @joellow88 
</panel>

</panel>


<panel type="info" header="### 107. ONG ..LVIN `@Mehvin` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Codecov suddenly not working**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/255" expanded>

Codecov has always worked, however it suddenly didnt work/appear on my latest pull request, [here](https://github.com/AY2223S2-CS2103-W16-1/tp/pull/66)

On the codecov dashboard, the error seems to be Missing Head Commit as seen below:
![image](https://user-images.githubusercontent.com/19343031/224634945-58442055-8614-43ac-a7fd-06e0319d0670.png)

Anyone faced similar problems before and know the fix?


</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/81#issuecomment-1407551531" expanded>

@pangrwa You can definitely try to be more flexible and allow different formats of date/time. However, what I did was to be restrictive but also at the same time check and inform users of invalid formats (in the form of an error message).
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/255#issuecomment-1465786829" expanded>

Rerunning the CI works, CodeCov ran too now. Thanks!
</panel>

</panel>


<panel type="info" header="### 108. GUO ..HENG `@Guo-KeCheng` (3 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/112#issuecomment-1411179036" expanded>

I think the issue is that you are inside your duke directory. 

Try navigating to the IP directory. The gradlew file is probably located there. 

From there you can try running 

```
// Linux or Mac
./gradlew checkstyleMain checkstyleTest


// Windows
gradlew.bat checkstyleMain checkstyleTest
```

Let me know if you manage to solve the issue.

p.s. Thank you @hingen for pointing out the command
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/147#issuecomment-1421704964" expanded>

Hi @benjamin-wee , I also had this issue when I did my GUI but I solved it by adding the 'images' directory. But from your screenshot, it looks like you did that already. 

Could you try using an absolute path from the root? 




</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/152#issuecomment-1423929163" expanded>

Assertion can be used:
- to check for things that are unlikely to happen unless there is something wrong in your code
- state things that you know are definitely true

Personally, I used it inside my switch-case
```
switch(input) {
case A:

case B:

default:
    assert false: "Should not reach here"; // Will not reach here
}
```

Here is a link I referred to before that you might find useful:
https://stackoverflow.com/questions/1957645/when-to-use-an-assertion-and-when-to-use-an-exception

</panel>

</panel>


<panel type="info" header="### 109. TANG..KUAN `@bokuanT` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Is this validity check considered to be fixing a bug that might make our app unusable?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/335" expanded>

Our app contains graphs where the axes are limited. Any values outside of this range cannot be displayed:

![image](https://user-images.githubusercontent.com/97268566/230099324-e4b07f00-35a8-4859-beb7-f83c9033ee08.png)

If we add validity checks for these values to fall only within the range (we allow any values currently), is this a bug fix?

</panel>

<panel  header="**2. :fas-info-circle: Github remote team repo has server error 500**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/298" expanded>

When trying to open my team's GitHub repo page, I get this error page:

![image](https://user-images.githubusercontent.com/97268566/228999768-c5adf1b1-0209-4453-912c-edbdf674209c.png)

I am using windows and chrome. I have tried clearing my browser cache and cookies, using another browser (opera), and accessing the page through my phone but I still get this error page. My teammates can access the page fine.

Another note was that I could access my team's Github page while I was logged out, but the same error appeared after logging into GitHub.

Has anyone else experienced this before or knows how to fix this?

</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/335#issuecomment-1497542148" expanded>

The following are some possible cases where a value falls out range:

![image](https://user-images.githubusercontent.com/97268566/230103449-55ced636-7834-42df-aa8c-f8f25ec84c2e.png)

Ammonia (top left) has 3 values above the limit of our y axis (4). There are 3 readings with values [5,6,7]

Temperature (top right) has the first value in range, second above the limit and the third below the limit, with values [25,800,-1]

pH (bottom) has the first and third value in the limit and the second value below the limit, with values [2,-5,7]

</panel>

</panel>


<panel type="info" header="### 110. WILL..XUAN `@WillCWX` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Clarifying Java standard for JavaDoc inheritance**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/124" expanded>

## Background

![image](https://user-images.githubusercontent.com/55905659/216220655-f4b7111f-e576-404b-bc2d-fc93c927919b.png)

It is understood that the JavaDocs of the overriden methods may be inherited only if they apply directly to the overriding methods. Hence, if they only apply partially, the Java coding standard recommends the following: 
![image](https://user-images.githubusercontent.com/55905659/216220538-18d1fc1d-70e4-44da-a665-122051a3143f.png)

The use of the `@inheritDoc` tag is suggested for reusing the header content but no recommendation is given for reusing other content (like `@param` and `@return`). I assume this is because JavaDocs are automatically inherited for any non-overriden `@` tags as I am able to see them in both my IDE and in the JavaDocs built by gradle. 

## The issue

However, code reviewers cannot see this on github and cannot tell if the inherited descriptions are apt. [This happened to me](https://github.com/nus-cs2103-AY2223S2/ip/pull/49#pullrequestreview-1274853912). 
- I would like to clarify if this is the intended way for non-header comments in JavaDocs to be inherited. 
- Some better ways to communicate JavaDoc inheritance in non-IDE environments may also be suggested, 

Thanks.

## Example of inherited JavaDoc

<details>
<summary>Example Code</summary>

```
/**
 * SuperClass example
 */
public class SuperClass {
    /**
     * This header only appears in superclass method
     *
     * Both the header and this comment can appear in the subclass if the tag is used.
     *
     * @param notUsed This param appears both in super and subclass methods
     * @return True, always
     */
    public boolean hasSuperClassMethod(int notUsed) {
        return true;
    }
}

/**
 * SubClass Example
 */
public class SubClass extends SuperClass {
    /**
     * Subclass overriding method header.
     * Prints "hello"
     */
    @Override
    public boolean hasSuperClassMethod(int notUsed) {
        System.out.println("hello");
        return true;
    }
}

 ```

 </details>
<details>
<summary>Resulting JavaDoc </summary>

SuperClass
![image](https://user-images.githubusercontent.com/55905659/216227246-558e9945-8b86-40ad-b268-f625d0ba8ab2.png)


SubClass
![image](https://user-images.githubusercontent.com/55905659/216227166-a6e42787-a0b2-40a6-9e0b-585532b2b13a.png)

</details>
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/29#issuecomment-1397220048" expanded>

 I have also looked through your code and the issue seems to be in `case "bye":` , specifically the `UserScanner.nextLine().length()` and how it interacts with your `input.txt`. (it reads up to `list` and has an issue with `bye` btw)

If you took a look at the top of the test, you would see a `java.util.NoSuchElementException: No line found` exception. This is because your `UserScanner.nextLine().length()` caused Duke to look for the next line but there were no next lines in your input.

Normally this would not be an issue as our own inputs have a newline character, `\n` that will not be picked up by `.next()` but will be picked up by `.nextLine()` for `.nextLine()` to terminate. 
> Input: `bye\n`
> `.next()` produces `"bye"` stopping at `\n`
>`.nextLine()` continues at `\n` and terminates as it sees the newline character, producing `""`

However, when you take a look at `input.txt`, you will see that your last command `bye` is the last line and hence, does not have a `\n` newline character! This causes the automated testing to fail even though typing your own `bye` command would still succeed.  

> Input: `bye`
> `.next()` produces `"bye"` stopping
>`.nextLine()` continues and is unable to terminate as does not see a newline character. 
> This reaches the EOF and causes an error

(windows uses \r\n as a line separator which .nextLine() also detects but the point still stands)
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/57#issuecomment-1404814292" expanded>

Hello @valerietanhx ,
I also cannot replicate your issue on both windows and ubuntu linux, it seems that this is a mac specific error. I am unsure if this information will be helpful to others but could you specify the version of macOS you are using? (also apple m1/m2 or intel chip)

It does conclusively appear that the `loadData` method is causing the error. Could you add in another `if else` in line 29 such that the "event' condition is also accounted for and allows us to debug the situation where line[0] is not a task type?
```
                .... if (line[0].equals("event")) { // event
                    tasks.add(new Event(sc.nextLine(), line[1], line[2], line[3], line[4]));
                } else {
                    // this should not run!
                    System.out.println("Error! This should not run!");
                    for (int i = 0; i < line.length; i++) {
                        System.out.println(line[i]);
                    }
                }
```

Hopefully this should print out what line was read that caused the error.
Do update us on the result of debugging using this method.
</panel>

</panel>


<panel type="info" header="### 111. ANG ..YUZE `@YZmunchmunch` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Unable to open JAR file on any laptop.**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/204" expanded>

I am using openJDK version 11.0.18, runtime environment Zulu11, and gradle version 7.6. I am able to build my jar file on intellij by running shadowJar, but when I am trying to open the jar file in terminal, this runtime error seems to occur. (JAR file name: AOT)

This is the error that i faced:
<img width="1172" alt="Screenshot 2023-02-17 at 8 02 31 PM" src="https://user-images.githubusercontent.com/86197080/219649730-18e4bde8-7d5c-4870-818b-551d2f1abb10.png">

Attach below is my build.gradle's plugins and dependencies

<img width="929" alt="Screenshot 2023-02-17 at 8 05 16 PM" src="https://user-images.githubusercontent.com/86197080/219650075-db8e73b8-b24d-4bd2-9354-b55d177ce62a.png">


es. Am i missing any code here? Seems that shadowJar works but opening the jar file seems to be an issue.



</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/204#issuecomment-1434623496" expanded>

@francisyzy 
I tried making the above changes, but the error is
<img width="465" alt="Screenshot 2023-02-17 at 9 01 31 PM" src="https://user-images.githubusercontent.com/86197080/219659859-b0bbed52-3023-49cc-997c-a4984ea3de6e.png">

I sent my JAR file to 2 of my friends, one who is using windows, one using another mac m1. The windows one could work, the JAR file could be opened and my project could be run, but the mac one had the same issue with me. Thank you for your help tho.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/204#issuecomment-1436767361" expanded>

Hi, thanks for the help @chunzkok, however after implementing these methods, i am still facing the same problem. May i seek @damithc and @benedictchuajj 's assistance? Thank you!
</panel>

</panel>


<panel type="info" header="### 112. LIM .. HAO `@JunHao247` (3 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: error initializing QuantumRenderer no suitable pipeline found**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/241" expanded>

Hello, below are the versions of my intellij, Java and macOS. My java files are detected for individual project, however for the tP, after forking, I am unable to run the Main class. This issue arises in the screenshot below. Any help?

IntelliJ version: 2022.3.2
Java version: 
openjdk 11.0.18 2023-01-17 LTS
OpenJDK Runtime Environment Zulu11.62+17-CA (build 11.0.18+10-LTS)
OpenJDK 64-Bit Server VM Zulu11.62+17-CA (build 11.0.18+10-LTS, mixed mode)
macOS: Ventura 13.1 
Chip: Apple M1.

![photo_2023-03-07 00 18 31](https://user-images.githubusercontent.com/122423527/223168777-3bec4cd2-53db-45fa-ae5a-ec7460f1e09a.jpeg)


</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/121#issuecomment-1412361054" expanded>

@shittake Are you using Apple Silicon Macbook? I had the exact same problem and managed to solve it using the following link: https://nus-cs2103-ay2223s2.github.io/website/admin/programmingLanguages.html

Download and install the Azul build of OpenJDK 11 version, it supports fat JAR files and allows Apple Silicon Mac users to import javafx
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/241#issuecomment-1457467443" expanded>

@damithc Thank you for the replies, have also updated the title to match the problem. After updating my laptop, the issue has been solved, with regards to running the command at the project root folder, the following shows up:
openjdk 11.0.18 2023-01-17 LTS
OpenJDK Runtime Environment Zulu11.62+17-CA (build 11.0.18+10-LTS)
OpenJDK 64-Bit Server VM Zulu11.62+17-CA (build 11.0.18+10-LTS, mixed mode)

I will now close the issue, thank you so much!
</panel>

</panel>


<panel type="info" header="### 113. TAN ..N DA `@jundatan` (3 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/109#issuecomment-1410232704" expanded>

Don't think there is a restriction on what class names you must use. Just need to follow the coding standard guidelines and make sure the class name makes sense.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/114#issuecomment-1410815406" expanded>

Hey! There are numerous ways to use the var-args. It is a method that takes in variable number of arguments. Hence, the name var-args. If you find any methods that require to take in a variable amount of arguments, that will be a suitable place to use it! Just like what @dfordarius said, there is no harm in trying with it. 😃

Edit:

```java
public String checkDescription(String... str) throws DukeException {
     ...
}
```
I have used it for mainly UI messages where i feel there is a need for extra text. Eg, sometimes you do not need the extra text in your UI messages methods and sometimes you want them to be added in.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/150#issuecomment-1422499917" expanded>

I think you can pull the merged into your local repo and tag them and push it to github.
</panel>

</panel>


<panel type="info" header="### 114. HEE ..YUAN `@jayhee3` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Dynamic GUI - How to prevent longer response messages from being cut off?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/184" expanded>

Is there a way to configure the layout settings on Scene Builder such that longer response messages by the bot are not cut off, either via an ellipsis (...) or completely discarded? An example is shown in the screenshot below. 

<img width="400" alt="Screenshot 2023-02-14 at 11 28 09 AM" src="https://user-images.githubusercontent.com/95480800/218632031-212949e1-c9d5-4cd3-b08c-b13f771ce6d9.png">


</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/184#issuecomment-1429232822" expanded>

> I believe u need to add `minHeight="-Infinity"` to your label tag in your `DialogBox.fxml`
> 
> Something like this.
> 
> https://github.com/francisyzy/ip/blame/a42cfc1b490ed9dacc07ef92d20e1ab4f93c08aa/src/main/resources/view/DialogBox.fxml

This is exactly what i am looking for. Thank you very much!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/264#issuecomment-1475257797" expanded>

Thank you for sharing!
</panel>

</panel>


<panel type="info" header="### 115. GLOR..NHUI `@glozxi` (3 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/4#issuecomment-1382711419" expanded>

I think the compiler output path is the `out` folder of the project folder `ip`. You can set it in `File > Project Structure > Project > Compiler output`.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/4#issuecomment-1382727684" expanded>

My setting:
![2023-01-14 20_27_19-Project Structure](https://user-images.githubusercontent.com/82697998/212471592-7bbee3f4-8a93-4e4f-b38d-6131119b5fb9.png)
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/222#issuecomment-1441143854" expanded>

It works on Ubuntu 20.04 in VirtualBox.
![2023-02-23 10_28_10-CS2106-2010-VM  Running  - Oracle VM VirtualBox](https://user-images.githubusercontent.com/82697998/220808585-bee0741d-3cd9-4d92-8204-5ddaa55dfd34.png)

</panel>

</panel>


<panel type="info" header="### 116. GOH ..ICIA `@tricixg` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Jar file does not run on Windows & Linux (JavaFX Dependencies)**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/198" expanded>

I am using M1 Mac with gradle 6.2 and openjdk version "11.0.18" 2023-01-17 LTS

As seen in the screenshot below, I think my problem is that when I refresh my gradle dependencies only the mac dependencies are "installed" as seen on the left under "external libraries". 

However, i can't seem to fix the issue and install the Linux and win dependencies. 

I have tried :
1. refreshing gradle dependancies 
2. cleaning my project by running `./gradlew clean` in the terminal, and then rebuilding it by running `./gradlew build.`

<img width="1440" alt="Screenshot 2023-02-17 at 10 42 06 AM" src="https://user-images.githubusercontent.com/64681919/219536218-8c3827c0-83b0-4f9d-b973-483575492191.png">


Ideally i think my external libraries should look like this.
![photo_2023-02-17 10 51 49](https://user-images.githubusercontent.com/64681919/219537647-5aef7dea-a4d0-4c7e-81cf-7c8e798988be.jpeg)

</panel>

<panel  header="**2. :fas-info-circle: Messed up git tagging & branching**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/167" expanded>

When completing week 3's task that required parallel branching. I did not use branches and committed them straight to master. After trying to rectify the branching my code for tags A-JavaDoc, A-CodingStandard and Level-9 were all the same. Will this affect the IP grading in the future? if so how can I rectify this
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/198#issuecomment-1434460291" expanded>

> Hello, I'm also using M1 mac and I took a look at your build.gradle file. Just a guess, maybe you could **remove this block of code** from your **build.gradle** file:
> 
```
> javafx {
>     version = "19"
>     modules = [ 'javafx.controls' ]
> }
```
> 
> and **replace** `String javaFxVersion = '19'` in
> 
```
> dependencies {
>     testImplementation group: 'org.junit.jupiter', name: 'junit-jupiter-api', version: '5.5.0'
>     testRuntimeOnly group: 'org.junit.jupiter', name: 'junit-jupiter-engine', version: '5.5.0'
> 
>     String javaFxVersion = '19'
>     ...
> } 
```
> 
> to **`String javaFxVersion = '11'`**.
> 
> Hope this might work.

this worked for me Thankyou!
</panel>

</panel>


<panel type="info" header="### 117. CHIA..SHUA `@ChickenChiang` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Must you always categorise classes with similar functionality/ behaviour together?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/286" expanded>

For our tP we are adding a Team, UniqueTeamList, and TeamTag class to the addressbook. Their behaviour is similar to that of the pre-existing Person, UniquePersonList, and Tag classes. 

Just because they behave similarly do we have to make it such that they both extend the same parent class/ implement the same interface? 
- Team class mirrors Person class
- UniqueTeamList mirrors UniquePersonList
- TeamTag mirrors Tag

Does this violate any coding standards, or is it sufficient to mention that they behave similarly in the DeveloperGuide and in the comments? I can't seem to find any coding priciples that it would violate in the textbook. My thinking is that it is not necessary as they are divided into their respective packages i.e. team package and person package.

Thanks in advance!
</panel>

<panel  header="**2. :fas-info-circle: Better exceptions: how far down should you split your exceptions?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/239" expanded>

_Sorry for the poor wording in the title I can't seem to find the right words, I believe my examples will clarify it_

Currently I have a single `MissingArgumentException` that handles the following issues:
- Missing **index** in user input for `mark`, `unmark`, `delete`, etc.
- Missing **dates**  in user input for `event`, `deadline`
- Missing **description**  in user input for `todo`, `event`, `deadline`

If any of the above issues are found when creating parsing the user input, I throw a `new MissingArgumentException(String Message)`, where the message corresponds to the issue. For example:

```java
private static ToDoCommand buildToDoCommand(String[] words, String userInput)
            throws MissingArgumentException {
        if (words.length < 2) {
            throw new MissingArgumentException(Messages.MESSAGE_DESCRIPTION_MISSING); // &gt;-- Look here!
        }
        return new ToDoCommand(userInput.substring(5));
    }
```
Would it be better to create exceptions for each of the three issues mentioned instead? 

```java
private static ToDoCommand buildToDoCommand(String[] words, String userInput)
            throws MissingArgumentException {
        if (words.length < 2) {
            throw new MissingDescriptionException(); // &gt;-- Look here!
            // the exception will have the error message within it's class, and nothing needs to be passed as and argument
        }
        return new ToDoCommand(userInput.substring(5));
    }
```
Which method is better? And if the second method is chosen, will there come a point where there are too many exceptions in our project?

Would love to hear your thoughts, thanks in advance!
</panel>

<panel  header="**3. :fas-info-circle: How to handle issue creation for tasks with sub-tasks assigned to different members?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/232" expanded>

### Is it recommended to generate an issue for each subtask? 
### For example in Week 7's tP task we have multiple people editing the AboutUs file, should we create a sub-task for each person? 
#### Say multiple members are creating a feature X in a project:
   - Person 1 is working on function A for feature X
   - Person 2 is working on function B for feature X
Should we create issue 'Implement feature X' and add sub-issues 'Implement function A for feature X' and 'implement function B for feature X' ? 

The example is as shown below:
![photo_2023-03-01_21-09-19](https://user-images.githubusercontent.com/96032660/222149320-bce37c77-5f50-4456-ad1c-1a17aa67b3d6.jpg)

</panel>

</panel>


<panel type="info" header="### 118. LIM .. RUI `@zrei` (3 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Requesting Permission to use a third-party Library: PrettyTime**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/309" expanded>

## Library

[PrettyTime](https://github.com/ocpsoft/prettytime)

## Purpose

Apologies for not requesting permission sooner, it slipped my mind. This is a library my group used in v1.3 for Natural Language Processing of date and time inputs so we could parse user inputs like "tomorrow".

## License

[Apache 2.0](https://github.com/ocpsoft/prettytime/blob/master/LICENSE) 

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/67#issuecomment-1404767090" expanded>

If you have merged the b1 branch into the master branch locally and pushed the master branch, you will be able to see the commits you made in the b1 branch appear in the master branch on remote, but you will not be able to see the b1 branch.

When you merge b1 into master, the commits made in b1 are added into master. So when you push master, these new commits are pushed to the remote repository and therefore can be seen.

Do correct me if I've made any mistake!
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1410371669" expanded>

This is mine! Put a border on the text, rounded the edges and changed the image depending on the response.

<img width="400" alt="Screenshot 2023-01-31 at 9 33 06 PM" src="https://user-images.githubusercontent.com/88964793/215774447-30c63b99-d180-43aa-a68d-dd60b6038e22.png">

</panel>

</panel>


<panel type="info" header="### 119. KALA..SHAN `@kalarisng` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: should DG include all features?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/345" expanded>

should our DG include the implementation of all commands available in the user guide (under implementation section)?
</panel>

<panel  header="**2. :fas-info-circle: GUI not in English?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/149" expanded>

hi, does anyone know why the GUI did not appear in English?
<img width="1269" alt="Screenshot 2023-02-08 at 4 35 47 PM" src="https://user-images.githubusercontent.com/97084261/217508541-a1cf43f7-72f6-4dfd-9758-6d74ce166f3c.png">


</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/149#issuecomment-1422649543" expanded>

> Similar issues: #68 #78
> 
> Try and see if those solutions will help with Mac Java issues

addressbook.jar returns a version with the correct form
<img width="742" alt="Screenshot 2023-02-08 at 10 00 35 PM" src="https://user-images.githubusercontent.com/97084261/217551123-2c99d3ba-021f-46a6-a120-22d70be24b00.png">

however, launching the GUI is still giving me the wrong font. the error is as such:
<img width="1314" alt="Screenshot 2023-02-08 at 9 54 55 PM" src="https://user-images.githubusercontent.com/97084261/217551271-5966e3e8-fd62-4d1a-ad64-b8a84eb5e931.png">
</panel>

</panel>


<panel type="info" header="### 120. TRAN..GHIA `@rockman007372` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Level-9: Do we include the correct index of the filtered tasks?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/92" expanded>

```
find book
    ____________________________________________________________
     Here are the matching tasks in your list:
     1.[T][X] read book
     2.[D][X] return book (by: June 6th)
    ____________________________________________________________
```

Given the above example, I am not exactly sure if we are to return the task with its corresponding task index to the user, or return the tasks in chronological order. For instance, the former design would look like this:

```
find book
    ____________________________________________________________
     Here are the matching tasks in your list:
     3.[T][X] read book
     6.[D][X] return book (by: June 6th)
    ____________________________________________________________
```

I feel like the former is the better design choice since users can operate on the task using the correct index. 
</panel>

<panel  header="**2. :fas-info-circle: Level-7: Save the task list after each modification or at the end of the program?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/71" expanded>

I was wondering which option in the title is more suitable. I can think of some preliminary pros and cons:

Saving the task list after each modification of the list:
* Pros: Can save the list even if the program crashes midway.
* Cons: Less time efficient? But may not matter in practice.

Saving at the end:
* Pros: More time efficient
* Cons: List may not be saved if program crashes suddenly.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/92#issuecomment-1407682831" expanded>

> @rockman007372 The numbers in a items listing is meant to be the positions in that list, and hence, will always be 1, 2, 3, ... (i.e., dynamically generated for the current list of items). So, `delete 2` means 'delete the item at position 2 in the most recent listing'.

Thank you for your reply @damithc ! May I clarify the following:

After I call `find book` and receive a list of matching tasks, then call `delete 2`, will the 2nd task in the most recent listing be removed despite it having a different position in the actual Arraylist? 
</panel>

</panel>


<panel type="info" header="### 121. NIU ..QIAN `@NBQian` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Error when running JavaFX on Mac**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/111" expanded>

while attempting Level-10, my program was able to run as expected on Windows, but when putting the same ip folder on my M1 mac and trying to run it, it gives the following error:
'
Caused by: java.lang.RuntimeException: Error initializing QuantumRenderer: no suitable pipeline found
'
here are my Launcher.java and my build.gradle:
'''java
package duke;

import duke.Duke;
import javafx.application.Application;

/**
 * A launcher class to workaround classpath issues.
 */
public class Launcher {
    public static void main(String[] args) {
        Application.launch(Main.class, args);
    }
}
'''
'''gradle
plugins {
    id 'java'
    id 'application'
    id 'com.github.johnrengelman.shadow' version '5.1.0'
    id 'checkstyle'
}

checkstyle {
    toolVersion = '10.2'
}

repositories {
    mavenCentral()
}

dependencies {
    testImplementation group: 'org.junit.jupiter', name: 'junit-jupiter-api', version: '5.5.0'
    testRuntimeOnly group: 'org.junit.jupiter', name: 'junit-jupiter-engine', version: '5.5.0'
    String javaFxVersion = '11'

    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-base', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-controls', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-fxml', version: javaFxVersion, classifier: 'linux'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'win'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'mac'
    implementation group: 'org.openjfx', name: 'javafx-graphics', version: javaFxVersion, classifier: 'linux'
}

test {
    useJUnitPlatform()

    testLogging {
        events "passed", "skipped", "failed"

        showExceptions true
        exceptionFormat "full"
        showCauses true
        showStackTraces true
        showStandardStreams = false
    }
}

application {
    mainClassName = "Duke"
}

shadowJar {
    archiveBaseName = "duke"
    archiveClassifier = null
}

run{
    standardInput = System.in
}

'''

the two folders on my windows pc and m1 mac are completely the same. Could anyone help me?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/111#issuecomment-1410524382" expanded>

The issue was resolved after I followed https://nus-cs2103-ay2223s2.github.io/website/admin/programmingLanguages.html . Thanks.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/185#issuecomment-1431125606" expanded>

Seems like it depends on the java version you are using. I have the same error message when using java 11.0.17, but it works fine for java 11.0.18.
</panel>

</panel>


<panel type="info" header="### 122. TRUO..UONG `@Zhongli5712` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Requesting for help for smoke testing on Linux**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/229" expanded>

Can anyone smoke test my [duke.jar](https://github.com/Zhongli5712/ip/releases/tag/Linux-Compatible-codeupdated) on Linux? I really appreciate your help! Thanks in advance :satisfied:

To run the file: run with command line '''java -jar duke.jar'''
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/229#issuecomment-1449171052" expanded>

> @Zhongli5712 your duke.jar works on Arch Linux, just that the `Type your command` appears as a editable text rather than a hint. Not sure if that was intended.

Hi Sean thank you for helping me! For the "Type your command" editable, that's intended as you can type directly without having to delete it so I thought it would be useful to have something indicating where to type command. I think I will try to fade the phrase instead.
</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/229#issuecomment-1449261979" expanded>

> No problem. By editable text I mean that I can delete the `Type your command` text. If you want to show something indicating where to type, maybe you can try [hints](https://stackoverflow.com/questions/34069030/how-to-add-hint-text-in-a-textfield-in-javafx) instead.

I will try this. Thanks for the recommendation!
</panel>

</panel>


<panel type="info" header="### 123. JOY ..G RU `@joyngjr` (3 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: UG/DG pdf submission**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/358" expanded>

If our UG/DG utilises collapsible sections to make it neater, are we allowed to mark out which sections are collapsible after we expand it and convert it to pdf? It isn't really obvious which parts belong to the collapsed section once we convert the documents to pdf.
</panel>

<panel  header="**2. :fas-info-circle: How to update source code in releases?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/191" expanded>

Hello,

I made some changes to my code after releasing v0.2 and updated the jar file in my v0.2 release. However, I realised that the source code that is attached with it is not updated. I tried deleting the release and creating a new one, but git somehow generates my old source code. May I know what I should do?

<img width="1213" alt="image" src="https://user-images.githubusercontent.com/97519138/219217405-8741e43d-4693-4894-b6f3-e25227f5ed26.png">


</panel>

<panel  header="**3 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/358#issuecomment-1501130233" expanded>

@damithc Hi prof, we added the collapsible section for UG because user-friendliness is a grading criteria under CS2101, and we didn't want our UG to look too cluttered. For DG, we added the collapsible section because we wanted to add in some auxiliary information which does not really fit in with the main part of the DG, but we thought could help developers in understanding our algorithm. 

Even though the feature is not available in the PDF format, can we retain it since it helps with the organisation of content?
</panel>

</panel>


<panel type="info" header="### 124. ANG ..KIEL `@ezeAng` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Renaming Duke Class?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/109" expanded>

Can I rename Duke class to my own bot name? Must the main bot class be named Duke specifically or can we name it anything we like?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/109#issuecomment-1410515602" expanded>

Thanks!
</panel>

</panel>


<panel type="info" header="### 125. RYAN..XUAN `@RyanQiu1` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Help with smoke testing on mac**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/231" expanded>

Can anyone smoke test my [TheTaskMechanic.jar](https://github.com/RyanQiu1/ip/releases/download/A-Release/TheTaskMechanic.jar) on Mac? Thank you very much!

run with command line java -jar TheTaskMechanic.jar


</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/231#issuecomment-1449263995" expanded>

@ARPspoofing Thank you!
</panel>

</panel>


<panel type="info" header="### 126. TAY ..YING `@jjiayyingtt` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Unable to push due to authentication error**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/74" expanded>

I have used personal authentication token to add my account on sourcetree. But when I try to push, I am still getting the same error. 
![image](https://user-images.githubusercontent.com/89056416/215010611-112667a6-5768-4042-8ff9-bd4a701cbeae.png)

I've also looked online but can't seem to find a solution. 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/74#issuecomment-1406094213" expanded>

> 

That worked, thank you :) I'll also take note of my forum posts in the future!
</panel>

</panel>


<panel type="info" header="### 127. JOY ..TONG `@joytqt-1202` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Feature Flaw or Bug?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/344" expanded>

I have an unmark command that works for multiple objects as well as single events. 

Upon further testing, it was realised that the error output is not the same...

___For Single Events___
`unmark vid` on an already unmarked `vid` would let the user know that no changes were made because the video was already unmarked

___For Multiple Events___
`unmark vid1, vid2` when `vid1` or `vid2` or both are already unmarked would tell the user that the command was **successful** (which technically is not wrong)

___For its opposite command `mark`___
`mark vid` and `mark vid1, vid2` will let the user know that the videos were already marked

*Question* 
Is the issue for `unmark` on multiple events considered a feature flaw or a bug? 
Can I fix it in this iteration?

Thanks!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/344#issuecomment-1500107943" expanded>

okay! thank you!
</panel>

</panel>


<panel type="info" header="### 128. LIM ..ENUS `@venuslimm` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: How do we read multiplicity?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/139" expanded>

During yesterday's lecture, I think the way multiplicity was read for Canvas questions 1 and 2 contradicted with what was indicated in the textbook. 

Textbook definition of Multiplicity:
![image](https://user-images.githubusercontent.com/50315976/216754834-2e8b54f2-939b-41bc-8394-739e984c6915.png)

Question 1 stated that one or more Bar can be associated with a Foo, instead of one or more Foo are associated with 1 Bar.
![image](https://user-images.githubusercontent.com/50315976/216755020-437b7f43-98a5-4e88-9c7d-c963d26d4a4c.png)

Question 2 stated that a Bar should be connected to at least 1 Foo, instead of a Foo should be connected to at least 1 Bar.
![image](https://user-images.githubusercontent.com/50315976/216755059-e2605845-6994-4c94-b63a-32aee14e0a46.png)

May I know which is the correct way to read multiplicity?

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/139#issuecomment-1416895482" expanded>

Thanks profs for the response!
</panel>

</panel>


<panel type="info" header="### 129. GWYN..LING `@gwynethguo` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Apache PDFBox**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/273" expanded>

## Library

[Apache PDFBox](https://pdfbox.apache.org/)

## Purpose

To generate PDF files for the users (for students' progress reports).


## License

[Apache](https://www.apache.org/licenses/LICENSE-2.0)

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/161#issuecomment-1427022574" expanded>

I have just encountered this problem. Try to use `TextFlow` instead of `Label`. If you still encounter problems regarding this, you can see the commits that I have pushed for A-BetterGui increment.
</panel>

</panel>


<panel type="info" header="### 130. TAN ..AMES `@jmestxr` (2 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/95#issuecomment-1408448245" expanded>

Yep, just replace your DialogBox.java created back in part 3 with the new one suggested in part 4 of the tutorial. DialogBox.java in part 3 builds the user interface dynamically through Java code. However this process of building UI can quickly become tedious and your code becomes difficult to read/maintain. 

That’s why part 4 suggests to use FXML which has a more appropriate and easy-to-read syntax for building components. You can later style your components easily with css and load the css file on the FXML file. DialogBox.java in part 4 loads the DialogBox.fxml file and display the components (created in the FXML file) on the scene.

Hope this helps.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/198#issuecomment-1434092528" expanded>

Hello, I'm also using M1 mac and I took a look at your build.gradle file. Just a guess, maybe you could **remove this block of code** from your **build.gradle** file:

```
javafx {
    version = "19"
    modules = [ 'javafx.controls' ]
}
```

and **replace** `String javaFxVersion = '19'` in 

```
dependencies {
    testImplementation group: 'org.junit.jupiter', name: 'junit-jupiter-api', version: '5.5.0'
    testRuntimeOnly group: 'org.junit.jupiter', name: 'junit-jupiter-engine', version: '5.5.0'

    String javaFxVersion = '19'
    ...
} 
```

to **`String javaFxVersion = '11'`**.

Hope this might work.

</panel>

</panel>


<panel type="info" header="### 131. KIM .. JIN `@jugheadjones10` (2 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/5#issuecomment-1383035659" expanded>

.gitignore is a hidden file, so you need to reveal hidden files to see it. For Mac OS I think the command to see hidden files is Command + Shift + . (that's a full stop at the end) @adam07018 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/220#issuecomment-1444978976" expanded>

@ZhuLeYao Thanks a lot for sharing this solution. Saved me many hours :)
</panel>

</panel>


<panel type="info" header="### 132. BAHA..ED S `@tariq-droid` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: 💎 my GUI following the tutorial**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/140" expanded>

![Duke GUI](https://user-images.githubusercontent.com/82088609/216757045-2d4e1e9a-06b5-45f5-8983-9a2d911e6c64.png)

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/133#issuecomment-1415603398" expanded>

Thank you man. I spent an hour trying to figure out the solution
</panel>

</panel>


<panel type="info" header="### 133. SOO .. KIT `@wengkit1` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: JavaFX dependency issue**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/85" expanded>

I'm using the community version of intelliJ. And I am having trouble using the javaFX packages.
I've done the relevant setup steps with the build gradle file but my when I try to compile my Ui class it does not seem to recognise the javaFX packages that were downloaded, despite being added to my dependencies.
Attached is my build.gradle file and the relevant error messages.
Also to note is that, intelliJ does not highlight any import issues with the imports for the relevant javaFX tools.
 
<img width="1470" alt="image" src="https://user-images.githubusercontent.com/90920273/215287677-0c66cb8f-3343-435a-b2a3-2217d9d04ebc.png">
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/85#issuecomment-1410799785" expanded>

Thanks for the help, turns out it was a rather silly mistake. When I run from command line on mac, the default version is open-jdk 19 which does not have javafx. I did not think i had the problem as I had previously removed the two jdks and used zulu build on mac, but somehow or rather, when i access the directory on command line, the two jdks are still there. 
It was a problem with my java_home variable. Thanks I learnt alot. But could someone explain why that happens? 
</panel>

</panel>


<panel type="info" header="### 134. KANG.. RAN `@kyueran` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: How to have separate classes Instructor and Coordinator for the first screenshot?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/258" expanded>

<img width="924" alt="Screenshot 2023-03-15 at 9 27 46 AM" src="https://user-images.githubusercontent.com/83756825/225184199-68d4d9c0-6a2b-45a4-b5f9-4f40baf0335b.png">
<img width="916" alt="Screenshot 2023-03-15 at 9 27 52 AM" src="https://user-images.githubusercontent.com/83756825/225184216-0e4b3148-a0c2-4c10-8049-40700c80d905.png">

May I ask in the first screenshot it says there can be a solution with a separate Instructor and Coordinator class. But from the second screenshot it shows that if we have two separate classes we face the problem of having duplicate person as a coordinator and instructor (Tom in this case) which is not allowed. How can we have a solution with separate Instructor and Coordinator classes while avoiding this problem?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/266#issuecomment-1477310179" expanded>

I faced the same problem with IntelliJ IDEA 2022.3.3 (Ultimate Edition) with v1.2023.2 PlantUML.

I fixed it by changing to IntelliJ IDEA 2021.3.1 (Community Edition) with v1.2022.12 PlantUML.

You need to download the PlantUML for the old version of intellij cos the old version of PlantUML is not compatible with the new version of IntelliJ. This v1.2022.12 PlantUML version is automatically downloaded for IntelliJ IDEA 2021.3.1 (Community Edition).
</panel>

</panel>


<panel type="info" header="### 135. TAN ..SELL `@russelltankaimin` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Request to use Joda-Time library.**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/261" expanded>

## Library

[Joda-Time](https://www.joda.org/joda-time/index.html)

## Purpose

It is easier to use compared to java's in-built LocalTime for my team's scheduler feature.

## License

Apache License, Version 2.0
[Link to Lisence Page](https://www.joda.org/joda-time/licenses.html)
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1409986610" expanded>

This is what I did. The bot is actually "Yoda" who works in the Jedi Archives before being a master in the Jedi Council.

<img width="386" alt="Screenshot 2023-01-31 at 4 47 36 PM" src="https://user-images.githubusercontent.com/50812868/215714055-25fe8ab4-efad-40f3-8913-3678931e1c9d.png">

</panel>

</panel>


<panel type="info" header="### 136. HUAN..ZHOU `@huangzz125` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Git: Revert cloning of others repo**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/138" expanded>

<img width="1165" alt="image" src="https://user-images.githubusercontent.com/77564512/216751913-fd0b4a89-91bd-43b2-8a67-12213908daa3.png">

I have accidentally cloned Tan Jun Da's repo when I was trying to review his PR, I am not sure how I can undo this. Any help will be appreciated. Thanks!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/138#issuecomment-1423698771" expanded>

Initially, I tried removing that tag locally by running `git tag -d A-Enums` but it still results in that tag re-appearing on both my Sourcetree and when I run `git tag -l` on terminal a few seconds after it was successfully deleted (`Deleted tag 'A-Enums' (was 5ab0c61)` was displayed). So, I thought that the tag on my remote somehow. 

I could not remember what I did that caused that tag to end up being kept track by my Git but does this mean that I have pulled it and pushed it to my own remote?

So, I ran `git push --delete origin A-Enums` on top of the command to delete the tag locally. Now, the tag is completely deleted.

Thanks @EvitanRelta , point 2 worked perfectly. Thanks Prof @damithc and other friends for your kind help.
</panel>

</panel>


<panel type="info" header="### 137. BENN.. JIE `@Bentimate` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Bug or Feature Flaw that causes other features to malfunction**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/347" expanded>

Currently, our TP's delete command supports deletion of multiple index at once, and an undo command which allows users to undo the previous command.

correct case:
![good](https://user-images.githubusercontent.com/81696093/230634070-f71e9c59-baca-4a46-9c97-3c308b924928.JPG)

However, we have a problem where if the user enters duplicated index, the program will take the first index it sees and deletes it, but the command output box will not be cleared. This is due to not accounting for duplicates in the code.
wrong case:
![bad](https://user-images.githubusercontent.com/81696093/230634370-f6273e21-1752-489c-a3cf-72865d0fbf17.JPG)

This also causes the undo command to break and unable to be used properly.

This seems like a feature flaw, but this also causes other features to malfunction. Can this then be treated as a bug, or can we only mention this in the planned enhancement?

Here are some possible fixes, unsure if they are allowed:
1. Throw new error messages to disallow duplicate index
2. Allow duplicate index, but command output will be changed
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/347#issuecomment-1500407974" expanded>

Thanks prof!


</panel>

</panel>


<panel type="info" header="### 138. CHEN..YANG `@XylusChen` (2 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/81#issuecomment-1407551608" expanded>

What I did was to try parsing the inputs into LocalDate (or LocalTime) object. If this operation is not successful, I will simply save the date as a String like before. I think there are too many variations as to how one can input a "date" value and it would be impossible to account for all of them. 

I feel like it's acceptable to expect a strict format from the user. In existing calender apps (Apple's calender) for example, we can only add String descriptions for our event descriptions but not for dates, where we choose from a given drop-down menu (which is similar to "demanding" a fix form of input for dates and times). 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/114#issuecomment-1410841605" expanded>

Hi! I used var-args for my find command too! Specifially, I used a String type var-args parameter for the constructor of my FindCommand class. 

```
public FindCommand(String ... keywords) {
    ...
}
```

Like you mentioned, this allows users to search for tasks using multiple keywords, instead of just one keyword/phrase. Depending on how you want to implement the find command, you can return only tasks that matched all keywords or all tasks that matched with at least one keyword, or do both (will probably have to create another command for this to discern the distinct *find* behaviour). 👍 

Would be adviseable to inform users how your find command works so they won't be confused by the output.
</panel>

</panel>


<panel type="info" header="### 139. SEE .. XUN `@swx0` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Question on feature freeze**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/303" expanded>

Are we allowed to modify default data shown to users during feature freeze? 
If not, are we allowed to delete some parts of the default data?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/303#issuecomment-1501174308" expanded>

Thanks prof!
</panel>

</panel>


<panel type="info" header="### 140. ONG ..YANG `@lywich` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Question regarding AB3 authorship when it comes to refactoring**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/355" expanded>

In the context of code reuse, how do we handle refactored code from the original AB3 being attributed to a member because they refactored a file. For example, "person" from AB3 (and all reference to "person") was changed to something else. Will this be a problem when it comes to code reuse as the module website said not to take credit for existing AB3 code unless significant modification was made?
</panel>

<panel  header="**2. :fas-info-circle: Question regarding Do not merge PRs failing CI**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/217" expanded>

![image](https://user-images.githubusercontent.com/89989103/220052448-0b0cce48-fb48-4871-9600-f8db6018188d.png)

Came across this under week 8 -&gt; project -&gt; Add the first functionality increment -&gt; workflow. 

I would like to ask how strict should we adhere to this requirement? For context, my commit has failed the CI due to code coverage. This was largely due to changes to the codebase that included renaming and deletion of class/testcase. Otherwise, everything was fine. The DevOps guide says to take action if the code coverage drops below desired levels but it is said on the week 8 project tab that we are "required to follow" the workflow.

Is it alright to merge anyway if we have analyzed the codecov report and determined that the change in coverage was due to the deletion of unwanted classes? 

</panel>

</panel>


<panel type="info" header="### 141. MA Y..NXIN `@mayuanxin1234` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Week 8 Quiz part 1**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/238" expanded>

The scores are still muted and we cant see the answers immediately?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/238#issuecomment-1453589294" expanded>

Yes thanks prof
</panel>

</panel>


<panel type="info" header="### 142. KOH .. XUN `@kohkaixun` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Future design tweaks in PPP**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/340" expanded>

If I had already written the implementation for a bug that was flagged during the PE but was then informed that it would violate the feature freeze and it was not merged as a result, would it still be alright to include it in my PPP?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/340#issuecomment-1499099996" expanded>

Alright, thank you Prof!
</panel>

</panel>


<panel type="info" header="### 143. CHUA..HONG `@runoutofit` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Jar file does not have dependencies**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/203" expanded>

I am using Intellij on windows, OpenJDK ver11.0.13 and gradle ver 6.2.

I am experiencing issues executing my jar file as it does not contain the dependencies.
I have attached a screenshot below in case my explanation is unclear.
![image](https://user-images.githubusercontent.com/97612129/219614556-6059616d-831d-4150-a5c0-401b7bb0b2c7.png)
By right the dependencies i have listed in my build.gradle file will appear there but currently it is empty. Any idea how to add the dependencies? I have tried running build dependents thus far but nothing changed.


</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/203#issuecomment-1434858120" expanded>

i changed the mainClassName locally already. The first jar file i built worked on my computer but not on others, but subsequent builds of my Jar file failed to run on my computer as well.
</panel>

</panel>


<panel type="info" header="### 144. KIAN..NETH `@kennethk-1201` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Implementing list inside table in markdown**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/360" expanded>

I would like to have a list inside a table cell for my UG. I tried using HTML but it ended up displaying the raw text for my table on Github pages.

Is there a way to have a list (eg. bullet points) inside a table cell in the UG?

</panel>

<panel  header="**2. :fas-info-circle: Unable to display Table of Contents in my markdown file**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/359" expanded>

I put in the following label:
```
- Table of Contents
  {\:toc}
```

But the table of contents is not shown on my Github pages, does anyone know how to solve this issue?
</panel>

</panel>


<panel type="info" header="### 145. BRYA.. ONG `@bryansendeavour` (2 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/133#issuecomment-1416777134" expanded>

Life saver!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/161#issuecomment-1427339645" expanded>

Personally for Label I set USE_COMPUTED_SIZE for all as shown
<img width="650" alt="Screenshot 2023-02-13 at 12 49 57 PM" src="https://user-images.githubusercontent.com/97509884/218373371-68eec4af-b0f8-446f-9e38-665f763e7b4f.png">

this is the way long texts are shown
<img width="395" alt="Screenshot 2023-02-13 at 12 52 10 PM" src="https://user-images.githubusercontent.com/97509884/218373532-67c71cfb-e8e5-425d-9ca2-842cd95973c0.png">

</panel>

</panel>


<panel type="info" header="### 146. KELV..CHUA `@chuakid` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Could not find or load main class duke.Launcher**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/126" expanded>

Development environment
* IntelliJ 2022.3.1
* Windows 11

I am having issues running the program through IntelliJ. **The program runs fine when I use gradle's `run` script** but when I run the program through IntelliJ's runner, it gives me an error.
```
Error: Could not find or load main class duke.Launcher
Caused by: java.lang.ClassNotFoundException: duke.Launcher
```

My duke.Launcher class is as follows:
```java
package duke;

import javafx.application.Application;

/**
 * Entry point
 */
class Launcher {
    public static void main(String[] args) {
        Application.launch(Main.class, args);
    }
}
```

Even more peculiar is that this error pops up even when I run the main method directly through the little green arrow next to the method itself.

![image](https://user-images.githubusercontent.com/12196891/216234431-adb29ae0-8056-46fc-b41a-45e442b5a40f.png)

</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/126#issuecomment-1414797836" expanded>

Deleting the .idea folder and then reimporting resolved the issue! Thanks for the help @Hongyi6328 and @damithc 
</panel>

</panel>


<panel type="info" header="### 147. TEO ..SLEY `@Bisceto` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Requesting for help for smoke testing on Linux**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/228" expanded>

Sorry to create a new issue for this since the other issue regarding linux smoke testing was closed. Would greatly appreciate any users on linux to help me test my [jar](https://github.com/Bisceto/ip/releases/tag/A-Release_2) file!

Same method of running the command `java -jar duke.jar` in an empty directory.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/228#issuecomment-1445843747" expanded>

@cheeheng Thank you for your help! I'll leave this issue up until tomorrow in case anybody wants to request for help for smoke testing as well.
</panel>

</panel>


<panel type="info" header="### 148. FUN ..LEON `@niekis` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Requesting Permission to use a third-party Library: Opencsv**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/271" expanded>

## Library

[Opencsv](https://opencsv.sourceforge.net/)

## Purpose

Used in parsing CSV file inputs from the user

## License

[Apache](https://commons.apache.org/proper/commons-csv/)

</panel>

<panel  header="**2. :fas-info-circle: Camelcase or all-caps for constants within methods?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/210" expanded>

![image](https://user-images.githubusercontent.com/96820906/219944439-4daaeff8-4529-4b12-8c64-c6bdad373653.png)

This was how I initially saved the string constant. However checkstyle flags this since it is not a static constant.

![6ec8215f-d69a-483c-979d-07606b1e4049](https://user-images.githubusercontent.com/96820906/219944529-c93f77a0-71a5-4781-a370-43711d3d43ad.png)

I personally feel that this constant should be constained within the scope of the method. So perhaps leaving it in camelcase could be the correct option. Am I right? 
I'm also thinking it might be better to override the checkstyle instead.
</panel>

</panel>


<panel type="info" header="### 149. LIM .. YAN `@Jiayan-Lim` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Is redefine constraint for user input allowed in v1.4?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/341" expanded>

Currently, in our software, we allow users to input numbers and special characters like (), +, - for phone numbers. But there is a bug where the user can input all special characters without any number
![image](https://user-images.githubusercontent.com/122262028/230315732-884060c8-4776-4966-bd54-f35c04179529.png)
Is this considered a feature flaw or bug?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/341#issuecomment-1498703481" expanded>

Thanks prof for quick reply
</panel>

</panel>


<panel type="info" header="### 150. NG J..A YI `@gremmyz` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/94#issuecomment-1407995999" expanded>

@FredericChow00 I took a look at a similar issue raised earlier (Issue #73), and it could be that your branch-level-8 hasn't been merged with the master branch?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1409962110" expanded>

My current GUI (based on the one in the JavaFX tutorial):

![image](https://user-images.githubusercontent.com/92777033/215709200-e5bd6fa8-b95b-4e2f-943d-32ab65ae07a3.png)

</panel>

</panel>


<panel type="info" header="### 151. SEAN.. KAI `@SeanChinJunKai` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Changing methods name**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/365" expanded>

Are we allowed to change name of methods for instance getAddressBook to getPatientRecords?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/365#issuecomment-1501833060" expanded>

thanks prof!
</panel>

</panel>


<panel type="info" header="### 152. GUO ..OKUN `@bokung` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Dialog Box shrinks and cuts off content when scrollpane expands**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/208" expanded>

I think my issue is best described with pictures. 


Normally, when content doesn't overflow and require scrollpane to expand, everything works as expected.
![Screenshot (112)](https://user-images.githubusercontent.com/97655028/219843986-e4c81895-adb5-4586-a96a-e289c2125429.png)



However, when i input more stuff and cause the scrollpane to expand, the dialog boxes start to shrink and the content gets cut off. Here instead of having 6 items theres only 4, the other 2 could not fit in the dialog box. This gets worse if i have even more content.
![Screenshot (113)](https://user-images.githubusercontent.com/97655028/219844094-01ed91a7-001c-4fd9-8e18-bcdfb8fdb298.png)


Here are the fxml files for my dialog box and main window
```java
<?xml version="1.0" encoding="UTF-8"?>

<?import javafx.geometry.Insets?>
<?import javafx.scene.control.Label?>
<?import javafx.scene.image.ImageView?>
<?import javafx.scene.layout.HBox?>
<?import javafx.scene.text.Font?>

<fx:root maxWidth="1.7976931348623157E308" prefWidth="400.0" style="-fx-background-color: #444653; -fx-border-color: #31363C;" type="javafx.scene.layout.HBox" xmlns="http://javafx.com/javafx/19" xmlns:fx="http://javafx.com/fxml/1">
  <children>
    <ImageView fx:id="displayPicture" fitHeight="25.0" fitWidth="25.0" nodeOrientation="RIGHT_TO_LEFT" pickOnBounds="true" preserveRatio="true" translateX="7.0" />
    <Label fx:id="text" text="Hello" textFill="WHITE" wrapText="true">
         <padding>
            <Insets left="20.0" />
         </padding>
         <font>
            <Font name="Menlo Regular" size="12.0" />
         </font></Label>
  </children>
  <padding>
    <Insets bottom="15.0" left="5.0" right="5.0" top="15.0" />
  </padding>
</fx:root>
```

```
<?xml version="1.0" encoding="UTF-8"?>

<?import javafx.scene.control.Button?>
<?import javafx.scene.control.ScrollPane?>
<?import javafx.scene.control.TextField?>
<?import javafx.scene.effect.ColorAdjust?>
<?import javafx.scene.image.Image?>
<?import javafx.scene.image.ImageView?>
<?import javafx.scene.layout.AnchorPane?>
<?import javafx.scene.layout.HBox?>
<?import javafx.scene.layout.VBox?>
<?import javafx.scene.text.Font?>

<AnchorPane maxHeight="-Infinity" maxWidth="-Infinity" minHeight="-Infinity" minWidth="-Infinity" prefHeight="600.0" prefWidth="400.0" stylesheets="@Application.css" xmlns="http://javafx.com/javafx/19" xmlns:fx="http://javafx.com/fxml/1" fx:controller="uwuke.view.MainWindow">
  <children>
    <ScrollPane fx:id="scrollPane" hbarPolicy="NEVER" hvalue="1.0" pannable="true" prefHeight="557.0" prefWidth="400.0" style="-fx-background-color: #343540;" vbarPolicy="NEVER" vvalue="1.0">
      <content>
        <VBox fx:id="dialogContainer" prefHeight="555.0" prefWidth="398.0" style="-fx-background-color: #343540;" />
      </content>
    </ScrollPane>
      <HBox layoutY="553.0" prefHeight="48.0" prefWidth="388.0" style="-fx-background-color: #343540;">
         <children>
          <TextField fx:id="userInput" maxHeight="-Infinity" maxWidth="-Infinity" minHeight="-Infinity" minWidth="-Infinity" onAction="#handleUserInput" prefHeight="48.0" prefWidth="321.0" promptText="e.g. deadline Sleep /by 17/2/2023 2359" style="-fx-background-color: #40414E;" stylesheets="@Application.css">
               <font>
                  <Font name="Menlo Regular" size="12.0" />
               </font>
            </TextField>
          <Button fx:id="sendButton" alignment="CENTER" mnemonicParsing="false" onAction="#handleUserInput" prefHeight="48.0" prefWidth="65.0">
               <graphic>
                  <ImageView fitHeight="16.0" fitWidth="18.0" pickOnBounds="true" rotate="-41.4" scaleX="1.5" scaleY="1.5" scaleZ="1.5">
                     <image>
                        <Image url="@../images/send.png" />
                     </image>
                     <effect>
                        <ColorAdjust brightness="0.57" />
                     </effect>
                  </ImageView>
               </graphic></Button>
         </children>
      </HBox>
  </children>
</AnchorPane>
```

Any help would be greatly appreciated!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/208#issuecomment-1435630913" expanded>

Thank you! 
</panel>

</panel>


<panel type="info" header="### 153. SHIN.. JIN `@jinnieshin` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: Is it better to extract out a long switch-case statement to another method/class?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/56" expanded>

I have been using switch-case to implement different commands then I realised that this makes my main function super messy. Is it usually more recommended to extract out such switch-case statements outside to keep the code neat? If yes, would it better to make it a method in the same class or create another class to handle the commands?
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/56#issuecomment-1401702440" expanded>

Just realised that the solution appears in A-MoreOOP &hat;&hat;;
</panel>

</panel>


<panel type="info" header="### 154. CHIN.. SAI `@cjyothika` (2 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Why does option F indicate coupling between A and B?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/227" expanded>

![image](https://user-images.githubusercontent.com/59786385/221419007-cb0c560b-be4a-4ecc-8045-ddd34eecc4d0.png)

Could it be possible that option F indicates the coupling of A and B with another component instead?

![image](https://user-images.githubusercontent.com/59786385/221419168-3bae46ff-1cf5-4db5-88e1-e6910a285216.png)

I know it's written here (as shown above) but why is the last statement so? 
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/227#issuecomment-1446152057" expanded>

I see. Thank you for the explanation @damithc and @tituswe!
</panel>

</panel>


<panel type="info" header="### 155. LENG..STIN `@ScorpiusSigma` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/28#issuecomment-1396682383" expanded>

Do you have new lines between your inputs? Be sure to remove them
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/298#issuecomment-1491171923" expanded>

This is a server error from github. You can get an updates on the situation here

https://www.githubstatus.com/incidents/rmc0cpn9sn8w
</panel>

</panel>


<panel type="info" header="### 156. NGUY.. ANH `@VietAnh1010` (2 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/179#issuecomment-1427993740" expanded>

I guess that you are running your program in WSL.

To solve this:
- Make sure that your WSL is WSL 2. GUI apps **cannot** run in WSL 1.
- Check whether gtk is running using version 3 or not by adding `-Djdk.gtk.verbose=true` to the JVM arguments.
- If your WSL does not have gtk, or gtk is running with version 3, you need to install gtk version 2. It seems like JavaFX 11 does not work with gtk version 3.
- Run your app using gtk version 2 by adding `-Djdk.gtk.version=2`.

You can read this [thread](https://github.com/bisq-network/bisq/issues/2279) for more information about this error.
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/294#issuecomment-1489081959" expanded>

You can try to:

- Make a copy of T
- Modify this new copy
- Insert this new copy into the same position as the old T

The downside of this approach is that you have to know the index of the T you are going to update.
```java
T oldT = list.get(index);
T newT = copy(oldT);
// modify newT
list.set(index, newT);
```

If you don't want to create new object, you may try:
```java
T t = list.get(index);
// modify t
list.set(t);
```
Although I haven't tested this approach yet.
</panel>

</panel>


<panel type="info" header="### 157. LUO ..XIZI `@lxz333` (2 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/1#issuecomment-1399884867" expanded>

I also met this problem and I'm using M2 Mac.
The reason it didn't work for me at first was because beside the suggested Zulu11, I also have another OpenJdk11 installed in my mac. It was hidden in another path so I carelessly ignored that. Therefore I believe that uninstalling all the other jdk and only keeping the Zulu 11 will help!
</panel>

<panel  header="**2 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1429986803" expanded>

My GUI:)
<img width="485" alt="image" src="https://user-images.githubusercontent.com/104611360/218791529-94221fc8-7bdd-4d6f-8eb4-016c0a1fa8b3.png">


</panel>

</panel>


<panel type="info" header="### 158. SHI ..IAAO `@ShiJiaAo` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/292#issuecomment-1488561852" expanded>

I was getting the same issue too. Looks like it's a gradle problem and I believe you can check the status here:
https://status.gradle.com/

It seems like these timeouts are random. I just kept redoing the test and it worked eventually.
</panel>

</panel>


<panel type="info" header="### 159. OSKA.. LIN `@Skeltons` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/68#issuecomment-1404805985" expanded>

Hi, according to the CS2103 website if you are on mac and you do not run the jar with Java 11, the text may end up garbled/unreadable.
https://nus-cs2103-ay2223s2.github.io/website/admin/programmingLanguages.html
</panel>

</panel>


<panel type="info" header="### 160. AERO..SHEN `@Tohtoroo` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Mistakes were made**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/374" expanded>

n/a
</panel>

</panel>


<panel type="info" header="### 161. MAX .. JUN `@slackernoob` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/248#issuecomment-1463740594" expanded>

Redirect not working for me too, but you can still access the website through this [link](https://nus-cs2103-ay2223s2.github.io/website/index.html)!

</panel>

</panel>


<panel type="info" header="### 162. KELV.. MUN `@nusE0726844` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Java Coding Standard and Previous Commits**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/72" expanded>

Will the commits and previously committed code in week 2 be subjected to the Java Coding Standard and Commits standard or would it only apply to the last commit
</panel>

</panel>


<panel type="info" header="### 163. CHIN..N AN `@ChinJunAn` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: ControlsFX**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/275" expanded>

## Library

[ControlsFx](https://github.com/controlsfx/controlsfx)

## Purpose

Allow notifications to pop up during certain events

## License

[BSD-3-Clause license](https://github.com/controlsfx/controlsfx/blob/master/license.txt)

</panel>

</panel>


<panel type="info" header="### 164. CHEN..DIAH `@jedidiahC` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1435602933" expanded>

![Ui](https://user-images.githubusercontent.com/1849067/219854871-bc18d7d3-f0f8-478f-89ea-25db8d4269f4.png)

</panel>

</panel>


<panel type="info" header="### 165. CHEN..HENG `@c0j0s` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/63#issuecomment-1403677229" expanded>

What java version are you using? I encounter this error when I was using java 16 previously. I switched back to java 11 and gradle works fine afterwards.
</panel>

</panel>


<panel type="info" header="### 166. QUEK..RIAN `@astraxq` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/171#issuecomment-1427071337" expanded>

I came across this issue too in VSCode, I cleared the workspace cache and it worked as per normal perhaps this can help.  
</panel>

</panel>


<panel type="info" header="### 167. LEE .. JUN `@evanpy` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1416783372" expanded>

Pretty standard but it'll do!

![image](https://user-images.githubusercontent.com/38004268/216775959-73c660ec-c472-44cc-bbf4-643acb4a600d.png)

</panel>

</panel>


<panel type="info" header="### 168. LEE .. WEE `@shaowi` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Change directory name**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/304" expanded>

<img width="228" alt="image" src="https://user-images.githubusercontent.com/66897775/229295244-99f47f6d-f061-4744-a479-d82b294eab0f.png">

Can we modify the address to our own app's name at this stage?

Will it affect Reposense when renaming is done on a huge bulk of files due to this change?
</panel>

</panel>


<panel type="info" header="### 169. JOHN.. KIT `@Johnchiahk` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/171#issuecomment-1427069961" expanded>

import javafx.scene.image.Image;
import javafx.scene.image.ImageView;

Did u add these imports in Main.java?
</panel>

</panel>


<panel type="info" header="### 170. TSEN..N YU `@cydtseng` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1416696050" expanded>

Here's my GUI for Duke after following the tutorial!

![gui_prelim](https://user-images.githubusercontent.com/63691277/216757186-932c2226-df41-47de-99af-ccc5aa111ff4.png)

</panel>

</panel>


<panel type="info" header="### 171. ANG ..YANG `@AngJunYang` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: UML Class diagrams for Event-driven architectural style?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/278" expanded>

Unrelated to tp/dg, but was reading about Event-driven architectural style, and got curious how we would represent these in any of the UML diagrams we know.
 
Since the parties responding to the event trigger may not be known, or may only be assigned at runtime, it doesn't seem too easy to be able to make a diagram for it.

How would one go about trying to represent these in Class diagrams, Object diagrams etc..?
</panel>

</panel>


<panel type="info" header="### 172. DILL.. WEE `@dillongoh` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/182#issuecomment-1429067310" expanded>

What is the behaviour of your code when a save file doesn’t exist? Perhaps you can add your template tasks during the creation of a new save file. 
</panel>

</panel>


<panel type="info" header="### 173. TABR..LAVI `@TabrizPlv` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/161#issuecomment-1427039980" expanded>

It appears that you are using another `DialogBox` to account for lists that are too long. However, instead of creating another `DialogBox` you can actually scale the height of your `Label` so that it will stretch to fit events that are too long in length.
The approach to this is similar to the one mentioned by @toh-xinyi, but we apply it to the `Label` instead.
Refer to the Layout properties

![image](https://user-images.githubusercontent.com/85736132/218315227-d6ac8cc1-e1d8-4ff2-8ef1-8e084f3298eb.png)

</panel>

</panel>


<panel type="info" header="### 174. AFIQ..AHRI `@afiqzu` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/221#issuecomment-1443230486" expanded>

Hi, I had the same issue so I trawled through past semester's forums and found a fix! Just update your build.grade file and change

'
String javaFxVersion = '11'
'
to
'
String javaFxVersion = '16'
'

under dependencies.

Hope it works for you!

Reference:
https://github.com/nus-cs2103-AY2122S1/forum/issues/112


</panel>

</panel>


<panel type="info" header="### 175. XU B..OJIE `@bojie3` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/112#issuecomment-1411300128" expanded>

Maybe you can try to run the command using Gradle execute task.

![image](https://user-images.githubusercontent.com/95684564/215920301-1261dd0e-3a31-4961-9b85-5934f6a29545.png)

Click the gradle icon and the Execute Gradle Task icon.

![image](https://user-images.githubusercontent.com/95684564/215920417-bbd8008c-4c1d-4fc2-b618-e763669baaff.png)

Then you can try to run the command there, worked for me. 
</panel>

</panel>


<panel type="info" header="### 176. CHAI..XUAN `@jiexuanc` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/78#issuecomment-1406675031" expanded>

@ChangGittyHub The JDK might be in ~/Library/Java/JavaVirtualMachines instead of /Library/Java/JavaVirtualMachines
</panel>

</panel>


<panel type="info" header="### 177. ALSO.. JIE `@alson001` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/117#issuecomment-1417746155" expanded>

Please close this issue for the bot to stop pinging random people. 
</panel>

</panel>


<panel type="info" header="### 178. OWEN..UHAN `@owen-yap` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/215#issuecomment-1439439289" expanded>

Are you building the project from gradle in WSL2? That might be what's causing the issue because I faced the same errors but it worked fine once I switched to building the project from windows.
</panel>

</panel>


<panel type="info" header="### 179. LIM ..HENG `@zhengsterz` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/152#issuecomment-1423975792" expanded>

Personally i used my assertions to check for things like making sure that the size of my tasklist is more than -1 and generally checking that i havent messed up any of my own code
</panel>

</panel>


<panel type="info" header="### 180. JONA..KIAT `@Creationsv2` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/266#issuecomment-1479764381" expanded>

Can confirm that changing the Package name works. Similar problem in other diagrams such as ModelClassDiagram.puml as well.
</panel>

</panel>


<panel type="info" header="### 181. JAVO.. KAI `@JavonTeo` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/171#issuecomment-1427090717" expanded>

If it still doesn't work, perhaps you could try editing the filepath
</panel>

</panel>


<panel type="info" header="### 182. BRYA..IANO `@junianob` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/80#issuecomment-1407658126" expanded>

You can also manually delete tags on Github  by navigating to repo name > tags > delete

![image](https://user-images.githubusercontent.com/5424422/215327900-92956e44-6bc7-45dc-8bbe-e96252c4b3ce.png)

</panel>

</panel>


<panel type="info" header="### 183. LIAO..QUES `@jugsliao` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/171#issuecomment-1427081115" expanded>

Not sure if this helps but sometimes my errors disappear when I close and open intelliJ and run the launcher again. 
</panel>

</panel>


<panel type="info" header="### 184. ANG ..XUAN `@abenx162` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Restricting input/output file formats allowed?**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/330" expanded>

Hi Profs,

Our app has a feature that is intended to import/export from only .csv files, as recorded in our UG. However, we discovered that our import/export features currently also work perfectly fine with other file formats too, like .txt or .xlsx.
Would we be allowed to add a check to ensure that the import/export file format must be .csv?
Since it is effectively removing the "feature" of importing/exporting non-csv file formats.

Thank you!
</panel>

</panel>


<panel type="info" header="### 185. DARI.. ZHI `@NappySprout` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/204#issuecomment-1436564121" expanded>

@chunzkok Thanks for the advice on running with a different java version it really helped! I was just wondering will you still pass the smoke test even if you use a different java version?
</panel>

</panel>


<panel type="info" header="### 186. KOK .. ZHI `@chunzkok` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/204#issuecomment-1435837745" expanded>

Hi! I was also facing this issue when my friend @WilliamHaiweiGu pointed me to the [relevant course page](https://nus-cs2103-ay2223s2.github.io/website/admin/programmingLanguages.html). Hope this works for you too!

In short, this is what I did:
1. Visit the [Azul website](https://www.azul.com/downloads/?version=java-11-lts&os=macos&architecture=arm-64-bit&package=jdk-fx), scroll down and download the .zip version
    - (you may wish to choose the `.dmg` file for the installer, I chose the `.zip` file as I didn't want to run Java 11 for all the other Java applications on my machine 💀 ) 
2. Unzip the file (or run the `.dmg`)
3. Use the `java` binary located under `<extraction-directory>/bin/` to run the jar file. (or just use `java` directly if you installed using the `.dmg` file, but you may have to check that it is referencing the correct java binary by following the steps in the mentioned course page)
    - example usage: `<extraction-directory>/bin/java -jar AOT.jar`

In case your command is extremely long like mine due to the extraction directory name, you can consider giving it an alias to make it easier to test these jar files:
1. Open `~/.zshrc` (can use `vim` or `nano` or your favourite text editor)
2. Add the following line (you can replace `java11` with any name you want):
    ```
    alias java11="<extraction-directory>/bin/java"
   ```
3. Restart your terminal, or reload the config file by entering
    ```
    source ~/.zshrc
    ```
5. Now you can run jar files using `java11 -jar AOT.jar`! 


</panel>

</panel>


<panel type="info" header="### 187. IZZ ..ZLEY `@mynameizzhafeez` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1410286062" expanded>

I dealt with long responses by splitting them up after x number of lines. Apart from that, I stayed with the default design.

![Screenshot 2023-01-31 at 8 45 42 PM](https://user-images.githubusercontent.com/37770501/215763580-249f4166-ff9e-49e3-b91e-72c5b1c993a0.png)

</panel>

</panel>


<panel type="info" header="### 188. GAN ..I YI `@ruiyigan` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/113#issuecomment-1413110575" expanded>

I think @hingen provided a great answer. I believe these are just the two ways to set a controller for an FXML file. More can be found here: https://jenkov.com/tutorials/javafx/fxml.html#:~:text=There%20are%20two%20ways%20to,to%20load%20the%20FXML%20document.

</panel>

</panel>


<panel type="info" header="### 189. DARI.. WEE `@dfordarius` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/114#issuecomment-1410765262" expanded>

Hello, there are many possible ways to use the varargs, and you are definitely thinking in the right direction! I also used it to find multiple keywords. Just try it out theres no harm in doing so, jia you! 😄 

This was how i did it 

```
public findTaskMatchingKeywords(String ... keywords) {
      ...
}
```
</panel>

</panel>


<panel type="info" header="### 190. WANG..FENG `@SFCoding123` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Will like to check if can use this external API.**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/260" expanded>

## Library

[pdfBox](https://www.apache.org/dyn/closer.lua/pdfbox/3.0.0-alpha3/pdfbox-app-3.0.0-alpha3.jar)

## Purpose

{Intended to display PDF file that the user has uploaded}

## License

{Apache 2.0 https://www.apache.org/licenses/LICENSE-2.0}

@damithc 

</panel>

</panel>


<panel type="info" header="### 191. HUAN.. HAO `@huanghao1998` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/78#issuecomment-1406976199" expanded>

@ChangGittyHub Hi, I have found this [link](https://stackoverflow.com/questions/18144660/what-is-path-of-jdk-on-mac) which might be useful. 
```
/usr/libexec/java_home
```
Running this command might indicate where ur JDK located at. 

Hope it is helpful to you!
</panel>

</panel>


<panel type="info" header="### 192. CHIA..HONG `@chia-yh` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/91#issuecomment-1407650874" expanded>

Hi, I noticed that for me, Intellij tends to automatically add a tab(4 spaces) in between when creating spaces, you could try and see if thats the issue that it's flagging?
</panel>

</panel>


<panel type="info" header="### 193. ANG ..ANDA `@panpannnnn` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Unable to import javafx**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/193" expanded>

I have followed the javafx guide to import javafx but it still gives me the "Cannot resolve symbol javafx" error
![image](https://user-images.githubusercontent.com/85011179/219287006-bf5b052a-33ab-412b-85b2-9d5ff6b1bf62.png)

</panel>

</panel>


<panel type="info" header="### 194. LI X..TONG `@Emrysil` (1 posts) <span class=text-warning>:octicon-eye:</span>"  collapsed>


<panel  header="**1. :fas-info-circle: JAR file cannot write data into hard disk**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/169" expanded>


I have created a data/Duke.txt file under ip/src/main/java/resources to store the data on the task list.  However, while it is possible to read data with :
``` java
this.getClass().getResourceAsStream("data/Duke.txt");
```
I cannot seem to write into the same file. Is there any way to get around this? Or should I try to save the data to a different location? Previously I have also tried to save data as such:
```java
File file = new File("Duke.txt");
FileWriter fw = new FileWriter(file);
// writing task list data into file
```
But this will create a file Duke.txt directly under ip/build/libs, right beside duke.jar. While it works, I cannot include any sample data with this method.
Anyone has a solution to this?
</panel>

</panel>


<panel type="info" header="### 195. ONG .. SIM `@SeeuSim` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: 💎Level-10 JavaFX Setup for Apple Silicon Mac Users**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/87" expanded>

Hi all, 

Was attempting to set-up the Gradle packages for `Level-10`, when I ran into some issues when I followed the module website's [guide](https://se-education.org/guides/tutorials/javaFxPart1.html).

After installing the dependencies as per the above, I faced this error when running the `build` package:
```shell
Error initializing QuantumRenderer: no suitable pipeline found
```

As it turns out, JavaFX 11 has no official support for Apple Silicon architecture (as per this [link](https://repo1.maven.org/maven2/org/openjfx/javafx-graphics/11.0.2/)) Here are 2 ***fixes***:

## Recommended Fix

I've attempted to use the JDK 11 supplied by Azul, and it has solved the issue. You may use the [guide](https://se-education.org/guides/tutorials/javaFxPart1.html) above &hat;, and download the JDK from [here](https://www.azul.com/downloads/?version=java-11-lts&os=macos&architecture=arm-64-bit&package=jdk-fx#download-openjdk) and use it in IntelliJ. Azul bundles a JavaFX 11 version with its JDK, hence it should not have too many issues.

For reference, I previously used the JDK 11 supplied by Amazon Coretto 😭.

## JavaFX 17 Fix

I'm not sure if JavaFX 17 is allowed to be used in this module, but if it is, you may use this guide.
I've tried to upgrade to the next LTS version of JavaFX, JavaFX 17, and it has solved the issue.

Here's how I reconfigured `build.gradle` to install the dependencies instead: (You may add these lines to your `build.gradle`)
```gradle
plugins {
    ..
    id 'org.openjfx.javafxplugin' version '0.0.11'
}

javafx {
    version = "17.0.2"
    modules = [ 'javafx.base', 'javafx.controls', 'javafx.fxml', 'javafx.graphics' ]
}
```

You may also reference this StackOverflow [issue](https://stackoverflow.com/questions/71622429/is-it-possible-to-run-javafx-with-java-11-on-m1-mac) if you have other issues pertaining to this.

Hope this helps!
</panel>

</panel>


<panel type="info" header="### 196. WANG..CHEN `@zichen-3974` (1 posts) "  collapsed>


<panel  header="**1 :fas-comment:**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/104#issuecomment-1417265678" expanded>

Here's my GUI :)

<img width="328" alt="GUI" src="https://user-images.githubusercontent.com/97385559/216812107-b322d5bc-6e4a-4bc0-bd84-07221e17abee.png">
</panel>

</panel>


<panel type="info" header="### 197. ONG ..RYAN `@bryanongjx` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: are we allowed to implement sanity checks for v1.4**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/349" expanded>

In our PED, some reviewers brought up the bug whereby the users are able to:
1. key in strings like "this is        a  test" with multiple whitespaces in between words to break the duplicate constraint. (sorry github issues has auto trimmed my whitespaces so you cant see it)
2. key in numbers with super long decimal places like 1.4845193285

we wish to fix these issues by:
1. trimming the user input to remove the white spaces "this    is  a  test" -&gt; "this is a test"
2. only allowing users to key in numbers to max 1d.p

are we allowed to fix these 2 issues in v1.4? thank you!
</panel>

</panel>


<panel type="info" header="### 198. ARKO..HURI `@redHat-arko` (1 posts) "  collapsed>


<panel  header="**1. :fas-info-circle: Reuqest to use CalendarFX**" popup-url="https://github.com/nus-cs2103-AY2223S2/forum/issues/274" expanded>

## Library

[CalendarFX](https://github.com/dlsc-software-consulting-gmbh/CalendarFX)

## Purpose

To show a calendar view of appointments in the UI.

## License

[Apache-2.0 license](https://github.com/dlsc-software-consulting-gmbh/CalendarFX/blob/master-11/LICENSE)

</panel>

</panel>
