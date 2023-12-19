%%[This page was last updated on 2023-11-16 @00:09]%%


<panel type="info" header="### 1. YANG..TIAN `@skylee03` (130 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/17#discussion_r1352845066" expanded>

```suggestion
```
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/17#discussion_r1352845304" expanded>

```suggestion
```
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/17#discussion_r1352845700" expanded>

```suggestion
```
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/17#discussion_r1352845924" expanded>

```suggestion
```
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/17#discussion_r1352846195" expanded>

```suggestion
```
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/17#discussion_r1352846696" expanded>

```suggestion
```
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/17#discussion_r1352847139" expanded>

```suggestion
```
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/17#discussion_r1352848078" expanded>

```suggestion
```
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/17#discussion_r1352848232" expanded>

```suggestion
```
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/17#discussion_r1352848721" expanded>

```suggestion
```
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/18#discussion_r1354865376" expanded>

```suggestion
```
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/18#discussion_r1354867152" expanded>

According to the [coding standard](https://se-education.org/guides/conventions/java/basic.html#comments), we are recommended to use American spelling.
```suggestion
    void setTargetValue_initializeCommonArgs_expectArgs() {
```
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/18#discussion_r1354867406" expanded>

According to the [coding standard](https://se-education.org/guides/conventions/java/basic.html#comments), we are recommended to use American spelling.
```suggestion
    void getTargetValue_initializeCommonArgs_expectArgs() {
```
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/18#discussion_r1354948387" expanded>

According to the [coding standard](https://se-education.org/guides/conventions/java/basic.html#comments), we are recommended to use American spelling.
```suggestion
    void getCurrentValue_initializeCommonArgs_expectZero() {
```
</panel>

<panel  header="**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/18#discussion_r1356392104" expanded>

I think this is a good suggestion: it won't hurt to re-assign `isGoalAchieved` to its current value, and it in fact can simplify the code logic.

I think changing the code to the following will simplify the code, but I'm not sure whether doing so will reduce readability:

```suggestion
        setIsGoalAchieved(currentValue >= targetValue);
```
</panel>

<panel  header="**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/19#discussion_r1357696013" expanded>

Good use of `enum`!
</panel>

<panel  header="**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/19#discussion_r1357700967" expanded>

```suggestion
        return this.getMovingTime() * 60 / laps;
```
</panel>

<panel  header="**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/19#discussion_r1357706555" expanded>

`assertEquals(double expected, double actual)` is deprecated. Use `assertEquals(double expected, double actual, double epsilon)` instead.
```suggestion
        assertEquals(40.0 / 9.0, averagePace, 0.001);
```
</panel>

<panel  header="**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/19#discussion_r1357708216" expanded>

Good use of `@BeforeEach`!
</panel>

<panel  header="**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/19#discussion_r1357782875" expanded>

According to the [Markdown coding standard](https://se-education.org/guides/conventions/markdown.html), we should use `*` instead of `+` or `-`, and use blank lines to separate headings, but compliance with the standard is optional.
```suggestion
## Quick Start

* Ensure you have the required runtime environment installed on your computer. 
* Download the latest AthletiCLI from the official repository. 
* Copy the downloaded file to a folder you want to designate as the home for AthletiCLI. 
* Open a command terminal, cd into the folder where you copied the file, and run java -jar AthletiCLI.jar

## Features

**Notes about Command Format**
* Words in UPPER_CASE are parameters provided by the user.
* Parameters can be in any order.
* Parameters enclosed in square brackets [] are optional.
```
</panel>

<panel  header="**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/19#discussion_r1357785487" expanded>

It seems strange to convert an `int` value to `float` and then assigning it to a `double` variable, but it doesn’t hurt here.
```suggestion
        double dist = (double) this.getDistance();
        double time = (double) this.getMovingTime();
```
</panel>

<panel  header="**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/20#discussion_r1358595827" expanded>

```suggestion
        setIsGoalAchieved(currentValue >= targetValue);
```
</panel>

<panel  header="**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/20#discussion_r1358597846" expanded>

```suggestion
```
</panel>

<panel  header="**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/20#discussion_r1358598047" expanded>

```suggestion
```
</panel>

<panel  header="**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/20#discussion_r1358598590" expanded>

```suggestion
```
</panel>

<panel  header="**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359345567" expanded>

This file is not part of our project. Please untrack it and add it into `.gitignore`.
</panel>

<panel  header="**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359345727" expanded>

```suggestion
        Sleep oldSleep = sleepList.get(index - 1);
        sleepList.remove(index - 1);
```
</panel>

<panel  header="**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359345762" expanded>

```suggestion
        Sleep newSleep = new Sleep(from, to);
        sleepList.set(index - 1, newSleep);
```
</panel>

<panel  header="**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359345787" expanded>

```suggestion
        Sleep oldSleep = sleepList.get(index - 1);
```
</panel>

<panel  header="**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359345845" expanded>

```suggestion
 * To be implemented in future version of AthletiCLI.
```
</panel>

<panel  header="**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359345906" expanded>

```suggestion
 * To be implemented in future version of AthletiCLI.
```
</panel>

<panel  header="**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359345926" expanded>

```suggestion
 * To be implemented in future version of AthletiCLI.
```
</panel>

<panel  header="**33 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359345940" expanded>

```suggestion
 * To be implemented in future version of AthletiCLI.
```
</panel>

<panel  header="**34 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359345984" expanded>

```suggestion
            output.append((i + 1) + ". " + this.get(i).toString() + "\n");
```
</panel>

<panel  header="**35 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359346092" expanded>

```suggestion
        case CommandName.COMMAND_SLEEP_ADD:
            return parseSleepAdd(commandArgs);
        case CommandName.COMMAND_SLEEP_LIST:
            return new ListSleepCommand();
        case CommandName.COMMAND_SLEEP_EDIT:
            return parseSleepEdit(commandArgs);
        case CommandName.COMMAND_SLEEP_DELETE:
            return parseSleepDelete(commandArgs);
```
</panel>

<panel  header="**36 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359346332" expanded>

```suggestion
```
</panel>

<panel  header="**37 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359346374" expanded>

```suggestion
```
</panel>

<panel  header="**38 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359346439" expanded>

```suggestion
```
</panel>

<panel  header="**39 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359346498" expanded>

```suggestion

```
</panel>

<panel  header="**40 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359346542" expanded>

```suggestion
```
</panel>

<panel  header="**41 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359346549" expanded>

```suggestion
```
</panel>

<panel  header="**42 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359347676" expanded>

Completely removing this file from the git log requires editing the previous commit. However, I remember that the teacher advised us not to do this, because he used a script to check our repo and editing previous commits would bring risks. Maybe we can ignore this issue for now and I'll try to remove the file once this PR is merged.
</panel>

<panel  header="**43 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/31#discussion_r1359864020" expanded>

I found some violations of the [Markdown coding standard](https://se-education.org/guides/conventions/markdown.html), e.g., not using blank lines to separate headings, but since it's optional, I think it's okay not to change it.
</panel>

<panel  header="**44 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/35#discussion_r1359902468" expanded>

```suggestion
```
</panel>

<panel  header="**45 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/35#discussion_r1359902624" expanded>

```suggestion
```
</panel>

<panel  header="**46 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/35#discussion_r1359902832" expanded>

According to our User Guide, the command should be named `edit-diet-goal`.
```suggestion
    public static final String COMMAND_DIET_GOAL_EDIT = "edit-diet-goal";
```
</panel>

<panel  header="**47 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/35#discussion_r1359903339" expanded>

Are they debug output?
</panel>

<panel  header="**48 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/35#discussion_r1359903697" expanded>

Is it better to define them as static constants?
</panel>

<panel  header="**49 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/35#discussion_r1359903756" expanded>

```suggestion
    void parseDietGoalSet_oneValidGoal_oneGoalInList() {
```
</panel>

<panel  header="**50 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/35#discussion_r1359904024" expanded>

You can use `assertDoesNotThrow` instead!
</panel>

<panel  header="**51 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/35#discussion_r1359904093" expanded>

```suggestion
```
</panel>

<panel  header="**52 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/35#discussion_r1359904159" expanded>

```suggestion
            } else {
```
</panel>

<panel  header="**53 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/35#discussion_r1359904170" expanded>

```suggestion
            if (commandArgs.contains(" ")) {
```
</panel>

<panel  header="**54 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/35#discussion_r1359904229" expanded>

```suggestion
        for (int k = 0; k < userNewDietGoals.size(); k++) {
```
</panel>

<panel  header="**55 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/35#discussion_r1359910407" expanded>

“Market” seems like a typo.
According to our [coding standard](https://se-education.org/guides/conventions/java/basic.html), constant names must be all uppercase using underscore to separate words.
```suggestion
    private static final String CALORIES_MARKER = "calories";
    private static final String PROTEIN_MARKER = "protein";
    private static final String CARB_MARKER = "carb";
    private static final String FAT_MARKER = "fat";
```


</panel>

<panel  header="**56 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/39#discussion_r1360154514" expanded>

```suggestion
        for (DietGoal userUpdatedDietGoal : userUpdatedDietGoals) {
            for (DietGoal currentDietGoal: currentDietGoals) {
                if (!userUpdatedDietGoal.getNutrients().equals(currentDietGoal.getNutrients())) {
```
</panel>

<panel  header="**57 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/39#discussion_r1360157987" expanded>

Maybe `fail()` would be more appropriate here?
</panel>

<panel  header="**58 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/48#discussion_r1361440927" expanded>

```suggestion
    public static final String COMMAND_DIET_GOAL_DELETE = "delete-diet-goal";
```
</panel>

<panel  header="**59 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/48#discussion_r1361441548" expanded>

```suggestion
            int deleteIndex = Integer.parseInt(deleteIndexString.trim());
```
</panel>

<panel  header="**60 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/48#discussion_r1361469050" expanded>

```suggestion
        logger.log(Level.FINE, "Executing delete command for diet goals");
```
</panel>

<panel  header="**61 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/48#discussion_r1361469139" expanded>

```suggestion
            logger.log(Level.FINE, String.format("Diet goals %s has been successfully removed",
                    dietGoalRemoved.getNutrients()));
```
</panel>

<panel  header="**62 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/76#discussion_r1366534024" expanded>

A very meaningful assertion!
</panel>

<panel  header="**63 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/76#discussion_r1366535076" expanded>

Since it is not a constant, maybe it is better to call it `logger` instead of `LOGGER`?
</panel>

<panel  header="**64 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/76#discussion_r1366536850" expanded>

I think these two assertions are of little significance, because we have just checked them with `if`.
</panel>

<panel  header="**65 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/76#discussion_r1366537905" expanded>

`size()` is a function provided by the Java standard library and will not return a negative number unless an error occurs in the standard library.
</panel>

<panel  header="**66 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/81#discussion_r1367840401" expanded>

```suggestion
        if (commandArgs.isEmpty()) {
```
</panel>

<panel  header="**67 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/81#discussion_r1367840417" expanded>

```suggestion
                if (recordedNutrients.contains(nutrient)) {
```
</panel>

<panel  header="**68 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/83#discussion_r1367847622" expanded>

```suggestion
        return VERIFIED_NUTRIENTS.contains(nutrient);
```
</panel>

<panel  header="**69 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/83#discussion_r1367848147" expanded>

Suggestion: create unmodifiable set with `Set.of` introduced in Java 9.
```suggestion
    public static final Set<String> VERIFIED_NUTRIENTS = Set.of("fats", "carb", "protein", "calories");
```
</panel>

<panel  header="**70 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/89#discussion_r1369620140" expanded>

```suggestion
        return "Distance: " + String.format(Locale.ENGLISH, "%.2f", distanceInKm)
```
</panel>

<panel  header="**71 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/89#discussion_r1369620423" expanded>

```suggestion
        return String.format(Locale.ENGLISH, "%.2f", this.averageSpeed) + " km/h";
```
</panel>

<panel  header="**72 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/92#discussion_r1369623749" expanded>

Great use of `Comparator`!
</panel>

<panel  header="**73 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/89#discussion_r1371327403" expanded>

We should have added it to `.gitignore`... 😢
</panel>

<panel  header="**74 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/106#discussion_r1372779539" expanded>

Great use of `HashMap`!
</panel>

<panel  header="**75 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/106#discussion_r1372782313" expanded>

Great use of `Pattern`!
</panel>

<panel  header="**76 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/106#discussion_r1372784999" expanded>

```suggestion
        assertArrayEquals(expected, actual);
```
</panel>

<panel  header="**77 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/106#discussion_r1372785418" expanded>

```suggestion
        assertArrayEquals(expected, actual);
```
</panel>

<panel  header="**78 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/106#discussion_r1372785789" expanded>

```suggestion
        assertArrayEquals(expected, actual);
```
</panel>

<panel  header="**79 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/106#discussion_r1372786057" expanded>

```suggestion
        assertArrayEquals(expected, actual);
```
</panel>

<panel  header="**80 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/106#discussion_r1372786374" expanded>

```suggestion
        assertArrayEquals(expected, actual);
```
</panel>

<panel  header="**81 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/106#discussion_r1372786643" expanded>

```suggestion
        assertArrayEquals(expected, actual);
```
</panel>

<panel  header="**82 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/106#discussion_r1372786925" expanded>

```suggestion
        assertArrayEquals(expected, actual);
```
</panel>

<panel  header="**83 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/113#discussion_r1374046732" expanded>

> I made this one static @skylee03 as this was easier to adapt to my existing code. Please let me know if it should not be static. Then I will adjust my code accordingly

I think it's OK, but the JavaDoc also needs to be modified.
</panel>

<panel  header="**84 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/113#discussion_r1374047606" expanded>

Great use of `Class&gt;?>`!
</panel>

<panel  header="**85 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/113#discussion_r1374048661" expanded>

```suggestion
```
</panel>

<panel  header="**86 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/113#discussion_r1374048937" expanded>

Great use of `LocalDateTime.now()`!
</panel>

<panel  header="**87 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/113#discussion_r1374049926" expanded>

```suggestion
     * @param date     The date to be matched.
     * @param timespan The timespan of the goal.
     * @return         Whether the date is between the timespan.
```
</panel>

<panel  header="**88 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/118#discussion_r1375446016" expanded>

```suggestion
            if (!commandArgsString.contains(" ")){
```
</panel>

<panel  header="**89 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/138#discussion_r1378950193" expanded>

Great use of `final`!
</panel>

<panel  header="**90 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/138#discussion_r1378953645" expanded>

It takes good care of the sleeping habits of actual users!
</panel>

<panel  header="**91 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/139#discussion_r1379485803" expanded>

We should use `-->` instead of `->` for `message`.
</panel>

<panel  header="**92 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/139#discussion_r1379485851" expanded>

We should use `-->` instead of `->` for `message`.
</panel>

<panel  header="**93 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/139#discussion_r1379486347" expanded>

We should use `-->` instead of `->` for `activities`.
</panel>

<panel  header="**94 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/139#discussion_r1379488419" expanded>

According to the [textbook](https://nus-cs2113-ay2324s1.github.io/website/schedule/week10/topics.html#w10-2-sequence-diagrams-intermediate-level), method calls to `static` (i.e., class-level) methods are received by the class itself, not an instance of that class. You can use `&gt;&gt;class>>` to show that a participant is the class itself.
</panel>

<panel  header="**95 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/139#discussion_r1379488632" expanded>

According to the [textbook](https://nus-cs2113-ay2324s1.github.io/website/schedule/week10/topics.html#w10-2-sequence-diagrams-intermediate-level), method calls to `static` (i.e., class-level) methods are received by the class itself, not an instance of that class. You can use `&gt;&gt;class>>` to show that a participant is the class itself.
</panel>

<panel  header="**96 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/229#discussion_r1382362515" expanded>

```suggestion
            } else {
```
</panel>

<panel  header="**97 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/229#discussion_r1382362890" expanded>

Great use of stub!
</panel>

<panel  header="**98 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/245#discussion_r1384377362" expanded>

Great use of guard clause!
</panel>

<panel  header="**99 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/245#discussion_r1384379473" expanded>

Great SLAP!
</panel>

<panel  header="**100 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/246#discussion_r1384570524" expanded>

```suggestion
```

We have already included the title in the YAML block.
</panel>

<panel  header="**101 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/246#discussion_r1384572387" expanded>

```suggestion
## Table of Contents
{\:toc}
```

We can use `{\:toc}` to generate the TOC automatically.
</panel>

<panel  header="**102 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/250#discussion_r1385202402" expanded>

```suggestion
    /**
     * Constructs a sleep goal.
     * @param timeSpan    The time span of the sleep goal.
     * @param goalType    The goal type of the sleep goal.
     * @param targetValue The target value of the sleep goal in minutes. (Used if goalType is DURATION)
     * @param targetTime  The target time of the sleep goal. (Used if goalType is STARTTIME or ENDTIME)
     */
    public SleepGoal(GoalType goalType, TimeSpan timeSpan, int target) {
        super(timeSpan);
        this.target = target;
        this.goalType = goalType;
    }
```
Write `timeSpan` instead of `timespan` to be consistent with #120.
</panel>

<panel  header="**103 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/253#discussion_r1387433308" expanded>

To set the feature image, we can set the `feature_image` in the YAML block.
(See docs/README.md for example.)
</panel>

<panel  header="**104 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/253#discussion_r1387434682" expanded>

```suggestion
title: User Guide
```

We need to maintain consistency in capitalization, i.e., `AthletiCLI` instead of `AthletiCLi`.

Also, I don't think "AthletiCLI" needs to be included in the title. ([AB3 Example](https://se-education.org/addressbook-level3/UserGuide.html))
</panel>

<panel  header="**105 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/253#discussion_r1387435001" expanded>

If we need to add pictures, it is best to add them to other pages as well.
</panel>

<panel  header="**106 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/253#discussion_r1387435524" expanded>

Great use of emojis!
</panel>

<panel  header="**107 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/265#discussion_r1390147269" expanded>

```suggestion
     * @return                  The parsed Integer index.
```

`@return` field does not need to have a name like `@param`.
</panel>

<panel  header="**108 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/265#discussion_r1390147366" expanded>

```suggestion
     * @return                  The parsed ActivityChanges object.
```
</panel>

<panel  header="**109 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/265#discussion_r1390147548" expanded>

```suggestion
     * @return                  The parsed ActivityChanges object.
```
</panel>

<panel  header="**110 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/265#discussion_r1390147817" expanded>

```suggestion
     * @return                  The parsed ActivityChanges object.
```
</panel>

<panel  header="**111 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/265#discussion_r1390148061" expanded>

```suggestion
     * @return          The String position index of the next separator.
```
</panel>

<panel  header="**112 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/265#discussion_r1390148092" expanded>

```suggestion
     * @return       The parsed Integer index.
```
</panel>

<panel  header="**113 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/265#discussion_r1390148130" expanded>

```suggestion
     * @return         Whether the user wants the detailed view.
```
</panel>

<panel  header="**114 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/265#discussion_r1390148287" expanded>

```suggestion
     * @return                  An object representing the activity.
```
</panel>

<panel  header="**115 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/271#discussion_r1390230648" expanded>

```suggestion
Do note that for sleep commands, the order of the parameters is fixed, and are all non-optional.
```
</panel>

<panel  header="**116 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/271#discussion_r1390230799" expanded>

```suggestion
**Order of parameters is fixed, and are all non-optional.**
```
</panel>

<panel  header="**117 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/282#discussion_r1390350146" expanded>

```suggestion
6. `Data`: Manages the current state of the activity list.
7. `ActivityList`: Maintains the list of all activities added to the application.
```
</panel>

<panel  header="**118 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/282#discussion_r1390351686" expanded>

```suggestion
> extensions of the activity types and allows for a more modular design. This design and most of the methods can be 
```
</panel>

<panel  header="**119 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/282#discussion_r1390352472" expanded>

```suggestion
Usage Scenario and Process Flow:
```
</panel>

<panel  header="**120 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/288#discussion_r1390374558" expanded>

```suggestion
You can record your diet by specifying calorie, protein, carbohydrate, and fat intake.
```

</panel>

<panel  header="**121 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/296#discussion_r1390388721" expanded>

```suggestion
    /**
     * Parses the raw user input the sleep index and returns the corresponding index.
     * 
     * @param commandArgs The raw user input containing the arguments.
     * @return The index of the sleep to be edited.
     * @throws AthletiException If the index is invalid.
     */
```
</panel>

<panel  header="**122 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/296#discussion_r1390388802" expanded>

```suggestion
    /**
     * Parses the raw user input for a sleep goal and returns the corresponding sleep goal object.
     * 
     * @param commandArgs The raw user input containing the arguments.
     * @return An object representing the sleep goal.
     * @throws AthletiException If the sleep goal is invalid.
     */
```
</panel>

<panel  header="**123 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/296#discussion_r1390388861" expanded>

```suggestion
    /**
     * Parses the raw user input for a sleep goal index and returns the corresponding index.
     * 
     * @param type The string representing the type of the sleep goal.
     * @return The type of the sleep goal.
     * @throws AthletiException If the type is invalid.
     */
```
</panel>

<panel  header="**124 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/296#discussion_r1390388879" expanded>

```suggestion
    /**
     * Parses the raw user input for a sleep goal period and returns the corresponding period.
     * 
     * @param period The string representing the period of the sleep goal.
     * @return The period of the sleep goal.
     * @throws AthletiException If the period is invalid.
     */
```
</panel>

<panel  header="**125 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/296#discussion_r1390388905" expanded>

```suggestion
    /**
     * Parses the raw user input for a sleep goal target and returns the corresponding target.
     * 
     * @param target The string representing the target of the sleep goal.
     * @return The target of the sleep goal.
     * @throws AthletiException If the target is invalid.
     */
```
</panel>

<panel  header="**126 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/322#discussion_r1390620689" expanded>

```suggestion
This is only implemented due to  [skylee03 (Ming-Tian)](./skylee03.html)'s outstanding effort in convincing the team.
```
</panel>

<panel  header="**127 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/327#discussion_r1390653568" expanded>

```suggestion
        if (dietGoals.isEmpty()) {
```
</panel>

<panel  header="**128 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/327#discussion_r1390653701" expanded>

```suggestion
                if (!isSameTimeSpan) {
```
</panel>

<panel  header="**129 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/348#discussion_r1391400278" expanded>

```suggestion
* CARB: Your target value for carbohydrate intake, in terms of milligrams. The target value must be a positive integer up to the value 999999.
```
</panel>

<panel  header="**130 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/359#discussion_r1391486229" expanded>

```suggestion
In particular to demonstrate all parser classes, the following sequence diagram shows how the `edit-sleep` command works:
```

</panel>

<panel  header="**131 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/79#discussion_r1367837391" expanded>

This is not a plain text file, so the `.txt` extension should be avoided.
```suggestion
    public static final String PATH_SAVE = "./data/athleticli.bin";
```
</panel>

<panel  header="**132 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/79#discussion_r1367837443" expanded>

Should we give the user feedback when load fails?
</panel>

<panel  header="**133 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/88#discussion_r1368457965" expanded>

> Unsure if the catch block here is intended as my understanding is that AthletiException will be caught by main AtheliCLI class to have the error message printed out.

My bad. Originally, some exceptions were handled here, but later I improved the implementation of `FindCommand` to make it dependent on other find commands and then changed the exceptions in the `catch` block to `AthletiException` accordingly. I did not realize that actually I can just remove the entire `try` statement. 🤯
</panel>

<panel  header="**134 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/95#discussion_r1371625433" expanded>

> Should this have **Data data** as a parameter or where do we best examine the data against the target value?

Yes. I forgot to consider how they can access `data`.

The disadvantage of passing `data` as a parameter is that this method will have access to all data, but I failed to come up with a better way (passing in the corresponding `ArrayList` is not a good solution, because it will force us to cast the elements in it to the corresponding class).

So we might follow your suggestion and stick to what we did with the `execute` methods and pass in the entire `data` as a parameter, which is also easy to implement.
</panel>

<panel  header="**135 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/95#discussion_r1371626195" expanded>

I will fix this as soon as possible.
</panel>

<panel  header="**136 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/133#discussion_r1378600480" expanded>

Yes. According to our implementation, it is destroyed after the feedback messages are printed. Since the message printing is not reflected in this diagram, I would not mark the destruction of `SaveCommand`.
</panel>

<panel  header="**137 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/133#discussion_r1378602971" expanded>

According to our [textbook](https://nus-cs2113-ay2324s1.github.io/website/schedule/week10/topics.html#tools-uml-sequence-diagrams-reference-frames),
> Reference frames help you to break complicated sequence diagrams into multiple parts or simply to omit details you are not interested in showing.

Since I'm not interested in showing the details of "save other lists", I think I can simply omit the corresponding `sd` block.
</panel>

<panel  header="**138 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/247#discussion_r1384762618" expanded>

https://kramdown.gettalong.org/converter/html.html
</panel>

<panel  header="**139 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/19#issuecomment-1760987989" expanded>

LGTM!
</panel>

<panel  header="**140 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/43#issuecomment-1764732037" expanded>

The assert messages will be string literals because they are not what needs to be shown to the user.
</panel>

<panel  header="**141 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/43#issuecomment-1764747281" expanded>

Since most potential errors are already handled using exceptions, I will mainly add assertions for null arguments in public methods.
</panel>

<panel  header="**142 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/45#issuecomment-1764783951" expanded>

In `run()`, the following events should be recorded:

* [INFO] Entering the program
* [INFO] Parsing and running a command
* [WARNING] Catching an exception
* [INFO] Exiting the program
</panel>

<panel  header="**143 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/61#issuecomment-1768734903" expanded>

Fixed in #66.
</panel>

<panel  header="**144 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/79#issuecomment-1773994092" expanded>

> LGTM
> 
> Should we let the user do the saves or should the entries be saved after execution of commands?

Data is only saved when executing the `save` command or the `bye` command. I'm not implementing an autosave feature because I don't want to have too many unnecessary file IO. Although the resources consumed on file IO are insignificant given our limited data size, for larger projects we should strictly avoid doing so.
</panel>

<panel  header="**145 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/79#issuecomment-1773994464" expanded>

Currently, as long as the program exits normally using the `bye` command, the data will be automatically saved.

However, in the case of other exits, data is not saved automatically. This problem can be solved using `addShutdownHook`.
</panel>

<panel  header="**146 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/105#issuecomment-1780592005" expanded>

> Should we let individual people move their section to the userguide.md so that everyone get credit?

Yes. Since RepoSense is not smart enough, we need to let the original authors move the parts they are responsible for separately.

I'll temporarily store the contents of `UserGuide.md` in another file. This way you can regain the records by moving them to the correct file.
</panel>

<panel  header="**147 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/105#issuecomment-1780611205" expanded>

> > Should we let individual people move their section to the userguide.md so that everyone get credit?
> 
> Yes. Since RepoSense is not smart enough, we need to let the original authors move the parts they are responsible for separately.
> 
> I'll temporarily store the contents of `UserGuide.md` in another file. This way you can regain the records by moving them to the correct file.

I moved them to `UserGuideTmp.md`.
</panel>

<panel  header="**148 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/103#issuecomment-1780624612" expanded>

Update: I have move them to `UserGuideTmp.md`. This way you can regain the contribution records by moving them to `UserGuide.md`.
</panel>

<panel  header="**149 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/115#issuecomment-1782667473" expanded>

A labor-saving idea:
* Reuse the format of `add*` commands in the UI to reduce the workload of implementing the parser.
</panel>

<panel  header="**150 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/115#issuecomment-1782721598" expanded>

We need to implement `unparse()` methods to synthesis a parsable string from instances of `Activity`, `Sleep`, `Diet`, `ActivityGoal`, `SleepGoal`, `DietGoal`.
</panel>

<panel  header="**151 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/116#issuecomment-1784071228" expanded>

> Code wise, LGTM! Regarding storage, for dietGoalList, I have used one of the list instance as a temporary holder to store intermediate goals.
> 
> I would like to know if this temporary holder will be saved as I would not want them to?

Are you referring to `userNewDietGoals` and `userUpdatedDietGoals`?

They will not be saved bacause [only the lists in `data` will be saved](https://github.com/AY2324S1-CS2113-T17-1/tp/pull/116/files#diff-8661b41de4489932c613bd541c13dc62b435b7c28f9cb8739b3739c4258e649e).

We only need to ensure that when executing `save()`, the lists in `data` are what we want to save.
</panel>

<panel  header="**152 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/139#issuecomment-1789995210" expanded>

`ActivityGoalEvaluation.puml` is updated, but the corresponding `ActivityGoalEvaluation.svg` is not.
</panel>

<panel  header="**153 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/147#issuecomment-1790184416" expanded>

According to the [textbook](https://se-education.org/guides/conventions/markdown.html), we are suggested to use `*` instead of `-` for bullet-points. 😵‍💫
</panel>

<panel  header="**154 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/280#issuecomment-1806999356" expanded>

- https://github.com/AY2324S1-CS2113-T17-1/tp/pull/271#pullrequestreview-1726067176

Line 663/732:
- "non optional" should be "non-optional".
- Bold text should be used instead of heading.
</panel>

<panel  header="**155 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/295#issuecomment-1807094483" expanded>

For the following error message:
```
____________________________________________________________
 OOPS!!! The target value of an activity goal must be a positive integer!
____________________________________________________________

```

Actually, 0 is also an acceptable value for target.
</panel>

<panel  header="**156 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/295#issuecomment-1807095623" expanded>

In the `Summary of Commands` section of the UG, the duration format shoule be updated.
</panel>

<panel  header="**157 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/288#issuecomment-1807152303" expanded>

LGTM!
</panel>

<panel  header="**158 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/331#issuecomment-1807629704" expanded>

The deadline for DG is 2023-11-14 13:00.
</panel>

<panel  header="**159 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/331#issuecomment-1807671669" expanded>

> Is this mandatory and what is the expectation (how many test scenarios?)

https://nus-cs2113-ay2324s1.github.io/website/admin/tp-deliverables.html#deliverable-developer-guide-dg
![image](https://github.com/AY2324S1-CS2113-T17-1/tp/assets/24489025/246e414f-82e9-40ed-a853-5a9a1c8b3971)

</panel>

<panel  header="**160 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/340#issuecomment-1808273348" expanded>

> However, it failed one test case, how can I rectify it?

We are testing invalid input. If we use the correct separator (`fat`), we will get the correct value (`4`).
</panel>

<panel  header="**161 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/352#issuecomment-1808490970" expanded>

> LGTM!

But I think the correct anchor should be `#activity-management`.
</panel>

<panel  header="**162 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/352#issuecomment-1808496805" expanded>

> > > LGTM!
> > 
> > 
> > But I think the correct anchor should be `#activity-management`.
> 
> There are two activity-management headlines in UG and DG, I am trying to reference the first one of each document. But I have no idea whether this works

I tried but this did not work.
</panel>

<panel  header="**163 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/352#issuecomment-1808501405" expanded>

You can specify the HTML id using the [syntax of kramdown](https://kramdown.gettalong.org/syntax.html#specifying-a-header-id).

```markdown
### Activity Management activity-management-1}
### Activity Management activity-management-2}
```
</panel>

<panel  header="**164 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/348#issuecomment-1808588827" expanded>

Should we also change `calorie` to `calories` in Line 298 of UG?
</panel>

<panel  header="**165 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/issues/134#issuecomment-1792769726" expanded>

- Fixed in #115
</panel>

<panel  header="**166 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/115#issuecomment-1792772276" expanded>

- Fixes #134
</panel>

<panel  header="**167 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/issues/124#issuecomment-1792782494" expanded>

- Duplicated: #117
</panel>

<panel  header="**168 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/issues/131#issuecomment-1792783661" expanded>

- Duplicated: #117
</panel>

<panel  header="**169 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/issues/138#issuecomment-1792784369" expanded>

- Duplicated: #117
</panel>

<panel  header="**170 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/issues/141#issuecomment-1792816558" expanded>

I encountered the same problem. Fortunately, level 4 has been removed in
- #115
</panel>

<panel  header="**171 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/issues/146#issuecomment-1792824941" expanded>

You can try modifying `data/ChessMaster.txt` to get to this scenario.
</panel>

<panel  header="**172 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/issues/145#issuecomment-1792827059" expanded>

- Duplicated with #141
- Solved in #115 
</panel>

<panel  header="**173 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/issues/143#issuecomment-1792828615" expanded>

- Duplicated with #119
</panel>

<panel  header="**174 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/issues/125#issuecomment-1793417779" expanded>

I just learned that most chess games on computers use this to do castling. It can somehow be considered a "standard", so this issue is not actually a real documentation bug.

However, for those who have never played chess games on a computer, this may not be intuitive, so it is recommended that you add relevant instructions in the UG.
</panel>

</panel>


<panel type="info" header="### 2. DEXT..G EN `@DextheChik3n` (87 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/34#discussion_r1359833258" expanded>

Remember to not use the * wildcard after adding the JUnit tests, the same goes for DishTest.java and IngredientTest.java.
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/32#discussion_r1359835228" expanded>

Create Javadoc for ParserTest class pleeease
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/36#discussion_r1359849579" expanded>

can you put the semicolon in line 8 instead of putting it in the next line?
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/36#discussion_r1359851061" expanded>

I feel that this is not necessary for now.... in my opinion when we start implementing error handling we then include the necessary code if not we might forget about this method in the future so I feel that you can remove this for now :/
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/39#discussion_r1360086375" expanded>

I feel that the ListCommand class should be split into 2 classes for list menu and list ingredients of dish
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/39#discussion_r1360087075" expanded>

rename this to AddDishCommand as well
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/39#discussion_r1360087268" expanded>

Rename this class to DeleteDishCommand
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/47#discussion_r1360990385" expanded>

need to add space after Command
```suggestion
public class ListIngredientCommand extends Command {
```
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/47#discussion_r1360991205" expanded>

remove redundant semicolon

```suggestion
    }
```
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/49#discussion_r1361110609" expanded>

take note of the spacing
```suggestion
        for(int i = 0; i < menu.getSize(); i++) {
```
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/49#discussion_r1361113427" expanded>

rename class using `methodBeingTested_conditionBeingTested_expectedOutcome`
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/51#discussion_r1361526602" expanded>

change the command word to match what we stated in user guide
```suggestion
    public static final String COMMAND_WORD = "list_ingredients";
```
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/51#discussion_r1361526796" expanded>

change the command word to match what we stated in user guide
```suggestion
    public static final String COMMAND_WORD = "list_menu";
```
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/51#discussion_r1361527103" expanded>

can you change it so that it does not use of asterisk in import statement :/
</panel>

<panel  header="**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/54#discussion_r1361751951" expanded>

Perhaps add white space after bracket pleasee
```suggestion
    public ListIngredientCommand(int listIndex) {
```
</panel>

<panel  header="**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/64#discussion_r1363110212" expanded>

Perhaps the addition operator should be in the next line, the coding standard states that you break before an operator.
e.g.
```
setText("Long line split"
        + "into two parts.");
```

</panel>

<panel  header="**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/70#discussion_r1363987346" expanded>

Perhaps the addition operation should be in the next line
</panel>

<panel  header="**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/70#discussion_r1363988002" expanded>

I feel that you should add a whitespace after minus operator
```suggestion
        return sb.substring(0, sb.length() - 1);
```
</panel>

<panel  header="**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/75#discussion_r1364058711" expanded>

Perhaps remove this duplicate import statement Thank you
</panel>

<panel  header="**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/98#discussion_r1368189926" expanded>

Perhaps add whitespace in between operators
```suggestion
            String indexNum = String.valueOf(i + 1);
```
</panel>

<panel  header="**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/98#discussion_r1368191662" expanded>

Sorries I don't really get what does this javadoc mean? maybe you could remove it since I feel that the method is self-explanatory or elaborate more about the method if it's not trivial.
</panel>

<panel  header="**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/98#discussion_r1368192598" expanded>

in addition perhaps if the comment is a single line, write in the format of `/** comments */`
</panel>

<panel  header="**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/98#discussion_r1368193728" expanded>

for single line comments, perhaps change them in the format of `/** comments */`
</panel>

<panel  header="**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/98#discussion_r1368197272" expanded>

Could you also help to change the indentation for this line to be 8 spaces more than the parent line? similar to what you have done below
</panel>

<panel  header="**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/98#discussion_r1368221587" expanded>

okies understoods
</panel>

<panel  header="**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/95#discussion_r1368789879" expanded>

could you perhaps add a white space after the comma?

```suggestion
        ingredients.add(new Ingredient("chicken", 100, "g"));
```
</panel>

<panel  header="**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/95#discussion_r1368805497" expanded>

for this variable, perhaps have the plus operator in the next line, according to coding standards the break should be before the operator, same for line 40
</panel>

<panel  header="**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/95#discussion_r1368815685" expanded>

e.g. 
`String expectedOutput = "Chicken Rice Ingredients: \n"`
`    + "Rice - 1cup\n"`
</panel>

<panel  header="**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/104#discussion_r1369584314" expanded>

May I know the reason for storing just a Dish object? I thought that an Order would consist of multiple Dish objects, perhaps change the `Dish orderedDish` to `ArrayList&gt;Dish> orderedDishes`?
</panel>

<panel  header="**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/104#discussion_r1369590050" expanded>

In addition, after implementing the change to the ArrayList of Dishes, you could create a method to calculate the totalOrderCost
</panel>

<panel  header="**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/113#discussion_r1371003017" expanded>

Perhaps getDishFromId call to menu Class should be added? which is before number 2
and also setPrice and showEditPriceMessages should include the parameters passed in the methods?
e.g. setPrice(newPrice: float) and showEditPriceMessages(dish.toString(): String)
</panel>

<panel  header="**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/113#discussion_r1371004104" expanded>

Perhaps have the arguments written as:

```suggestion
Parser -&gt; Parser: prepareCommand(requiredArguments: String)
```
</panel>

<panel  header="**33 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/113#discussion_r1371004526" expanded>

Perhaps this should be
```suggestion
Main -&gt; Parser: parseCommand(fullUserInput:String)
```
</panel>

<panel  header="**34 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/113#discussion_r1371005931" expanded>

wait sorry change of thought, I'm not sure what this should be written because different prepareCommands take in different types of arguments
</panel>

<panel  header="**35 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/119#discussion_r1371519815" expanded>

perhaps change the indentation for lines 28 & 29
```suggestion
            ingredient = pantry.addIngredientToStock(ingredient.getName(),
                    ingredient.getQty(),
                    ingredient.getUnit());
```
</panel>

<panel  header="**36 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/119#discussion_r1371526350" expanded>

perhaps you could just use the `INGREDIENT_ARGUEMENT_STRING` regex instead of create a new regex since they both are the same regex
</panel>

<panel  header="**37 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/119#discussion_r1371528112" expanded>

perhaps change the indentation of these lines to have 8 white spaces from parent line 

</panel>

<panel  header="**38 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/119#discussion_r1371729447" expanded>

Oh oops I am sorry, I understand your intentions now
</panel>

<panel  header="**39 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/143#discussion_r1375258040" expanded>

Can I clarify why is IOException is thrown in main? then where is the exception caught?
</panel>

<panel  header="**40 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/143#discussion_r1375258622" expanded>

perhaps in the next PR for implementing error handling for file storage, have the try-catch in `CafeCtrl()` to catch the `FileNotFoundException` 
</panel>

<panel  header="**41 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/143#discussion_r1375275598" expanded>

its ok you can do it in the next PR, I think leave it as it is for now so that the rest can start working on it if they plan to do it tomorrow
</panel>

<panel  header="**42 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/161#discussion_r1376545211" expanded>

you can remove this line
</panel>

<panel  header="**43 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/161#discussion_r1376549160" expanded>

If you are planning to only chope the Pantry constructor remove ur GitHub tag for the bottom one

here's an explanation found on the CS2113 website:
![image](https://github.com/AY2324S1-CS2113-T17-2/tp/assets/35828587/7ee5f9f4-7da9-4a87-8e9b-6b49d6565f2c)


```suggestion
    //@@author
```
</panel>

<panel  header="**44 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/161#discussion_r1376549772" expanded>

remove this line
</panel>

<panel  header="**45 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/161#discussion_r1376551264" expanded>

Perhaps add a whitespace after for loop conditional
```suggestion
        for(String dishString : textLines) {
```
</panel>

<panel  header="**46 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/172#discussion_r1377584580" expanded>

Perhaps line 15 the space should be 8 spaces from line 14?
```suggestion
    Command parseCommand(Menu menu, String userInput, Ui ui,
            Pantry pantry, Sales sales, CurrentDate currentDate);
```
</panel>

<panel  header="**47 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/172#discussion_r1377587926" expanded>

Shouldn't line 85 be 8 whitespaces from the previous parent line 84?
```suggestion
    public Command parseCommand(Menu menu, String userInput, Ui UI,
            Pantry pantry, Sales sales, CurrentDate currentDate) {
```
</panel>

<panel  header="**48 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/190#discussion_r1378375135" expanded>

Perhaps add a whitespace here
```suggestion
public class ShowSalesCommand extends Command {

```
</panel>

<panel  header="**49 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/190#discussion_r1378402413" expanded>

Perhaps add a whitespace after the `Command` word
```suggestion
public class ShowSalesByDayCommand extends Command {

```
</panel>

<panel  header="**50 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/190#discussion_r1378403633" expanded>

May I clarify why was this commented out? if it is not used perhaps you could just delete this
</panel>

<panel  header="**51 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/190#discussion_r1378406818" expanded>

Perhaps use a guard clause to make the happy path more prominent

```suggestion
        if (orderList.isEmpty()) {
            ui.showToUser("No orders for this day.");
            return;   
        }
        
        for (Order order : getOrderList()) {
                aggregateOrder(order, aggregatedOrders);
        }
        
        for (Order aggregatedOrder : aggregatedOrders) {
                ui.showToUser(String.format(HEADER_FORMAT,
                        aggregatedOrder.getDishName(),
                        aggregatedOrder.getQuantity(),
                        aggregatedOrder.totalOrderCost()));
        }
        
        ui.showToUser("Total for day: $" + dollarValue.format(calculateTotalCost(aggregatedOrders)));
```
</panel>

<panel  header="**52 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/190#discussion_r1378407870" expanded>

Perhaps use a guard clause here as well to make happy path more prominent

e.g.
```
if (!order.getIsComplete()) {
    return;
}
...
```

</panel>

<panel  header="**53 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/190#discussion_r1378413854" expanded>

Perhaps add whitespace between operands
```suggestion
            if(finalQuantity < 0) {

```
</panel>

<panel  header="**54 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/190#discussion_r1378413982" expanded>

Perhaps add a whitespace after parameters
```suggestion
    public boolean isDishCooked(ArrayList<Ingredient> dishIngredients) {

```
</panel>

<panel  header="**55 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/190#discussion_r1378439077" expanded>

Perhaps help to add a whitespace here also
```suggestion
    public ArrayList<Ingredient> retrieveIngredientsForDish(String orderedDish) {

```
</panel>

<panel  header="**56 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/190#discussion_r1378439423" expanded>

Perhaps add a whitespace here 
```suggestion
    public void printSaleByDay(Ui ui, Menu menu, int day) {
```
</panel>

<panel  header="**57 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/190#discussion_r1378440631" expanded>

Perhaps ensure previous line is 8 whitespaces away
</panel>

<panel  header="**58 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/190#discussion_r1378444611" expanded>

Perhaps add the "+" operator in the next line
</panel>

<panel  header="**59 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/190#discussion_r1378444796" expanded>

Perhaps add the "+" operator in the next line
</panel>

<panel  header="**60 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/193#discussion_r1378465540" expanded>

Perhaps add your github username here
</panel>

<panel  header="**61 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/202#discussion_r1378743925" expanded>

Perhaps you want to change inside the for loops to prevent arrowhead code
</panel>

<panel  header="**62 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/204#discussion_r1378823993" expanded>

good that you changed the name to the correct format
</panel>

<panel  header="**63 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/221#discussion_r1381111792" expanded>

wow thank u for adding the table of contents!! would be useful for navigating the DG
</panel>

<panel  header="**64 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/221#discussion_r1381112098" expanded>

Nice.... command table looks like it is formatted properly in the github website
</panel>

<panel  header="**65 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/219#discussion_r1382508746" expanded>

I noticed that this regex still accepts more than 2 d.p. numbers,
![image](https://github.com/AY2324S1-CS2113-T17-2/tp/assets/35828587/a000166b-1ab2-43f3-be00-d455dd4a1e47)

I remember you said you plan to round it up to 2 d.p. , can I check if this was implemented in this PR?  if not, another suggestion I can give is to use this regex (inspired from my add dish regex) which can reject inputs more than 2 d.p. but can allow the user to enter prices up to 2 d.p. (e.g. price/2 OR price/2.0 OR price/2.01 OR price/.01)

`"index/([0-9]*) price/([0-9]*\\.[0-9]{0,2}|[0-9]+)$"`


</panel>

<panel  header="**66 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/219#discussion_r1382509133" expanded>

If you do use my regex remember to do extensive testing :P
</panel>

<panel  header="**67 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/263#discussion_r1382509517" expanded>

perhaps use more variable to make this statement more understandable
</panel>

<panel  header="**68 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/273#discussion_r1384282907" expanded>

could you perhaps add a newline before this statement to show clear sections for set up and testing
</panel>

<panel  header="**69 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/273#discussion_r1384286435" expanded>

Also, would this assert statement get triggered whenever the application is launch for the first time?
</panel>

<panel  header="**70 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/273#discussion_r1384287843" expanded>

oh sorry misunderstood that the sales is a array of order list not an array of orders
</panel>

<panel  header="**71 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/279#discussion_r1385956037" expanded>

Perhaps remove this commented line if it is not used?
</panel>

<panel  header="**72 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/279#discussion_r1385956337" expanded>

perhaps you could replace the "1" to prevent magic number?
</panel>

<panel  header="**73 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/279#discussion_r1385957009" expanded>

you could assign "1" as like int DAY_DISPLAY_OFFSET
</panel>

<panel  header="**74 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/290#discussion_r1386038924" expanded>

can I clarify why are there the merge conflict tags?
</panel>

<panel  header="**75 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/290#discussion_r1386040344" expanded>

Perhaps assign the numbers to a variable to avoid magic numbers
</panel>

<panel  header="**76 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/290#discussion_r1386050951" expanded>

Perhaps you could use my repeated ingredient checking function in the parser cLASS
</panel>

<panel  header="**77 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/331#discussion_r1390401567" expanded>

good that you remembered to break before an operator 👍 
</panel>

<panel  header="**78 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/336#discussion_r1390453983" expanded>

yes very good I was hoping someone would delete this unused code 👍 
</panel>

<panel  header="**79 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/350#discussion_r1390638753" expanded>

perhaps add whitespace
```suggestion
            if (formattedMenuDishName.equalsIgnoreCase(formattedDishName)) {
```
</panel>

<panel  header="**80 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/350#discussion_r1390639256" expanded>

perhaps you could have the newline after the comma
```suggestion
                aggregatedOrders.add(new Order(order.getOrderedDish(), order.getQuantity(), order.getTotalOrderCost(),
                        true));
```
</panel>

<panel  header="**81 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/345#discussion_r1390678929" expanded>

is there any more to be added? if not perhaps can delete this line
</panel>

<panel  header="**82 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/351#discussion_r1390685175" expanded>

perhaps you could name these variables with something more meaningful such as:
```suggestion
    private static final int MIN_ORDER_LIST_SIZE = 0;
    private static final int DAY_BASE_NUMBER = 0;
    private static final int DAY_OFFSET = 1;
    private static final int ORDER_LIST_SIZE_OFFSET = 1;
```
</panel>

<panel  header="**83 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/351#discussion_r1390686580" expanded>

perhaps you want to create variable for `(Ingredient) obj).name` to simplify this statement
</panel>

<panel  header="**84 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/350#discussion_r1390791443" expanded>

Perhaps you want to introduce a variable to simplify this statement, e.g.

```suggestion
                Order newOrderedDish = new Order(order.getOrderedDish(), order.getQuantity(), order.getTotalOrderCost();
                aggregatedOrders.add(newOrderedDish, true));
```

you can change the variable name if it doesn't make sense
</panel>

<panel  header="**85 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/350#discussion_r1390792003" expanded>

similar issue to the one mentioned above, perhaps introduce variables
</panel>

<panel  header="**86 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/350#discussion_r1390794154" expanded>

perhaps remove the whitespace as the github user tag should be one word
```suggestion
    //@@author ShaniceTang
```
</panel>

<panel  header="**87 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/391#discussion_r1391290651" expanded>

perhaps you should remove the extra double slashes in the regex
```suggestion
    private static final String BUY_INGREDIENT_ARGUMENT_STRING = "(ingredient/[A-Za-z0-9\\s]+ qty/.+"
            + "(?:, ingredient/[A-Za-z0-9\\s]+ qty/.+)*)";
```
</panel>

<panel  header="**88 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/57#discussion_r1362157549" expanded>

Sorry I was suppose to declare the CafeCtrl constructor as private... I'm going to change that now thank you!
</panel>

<panel  header="**89 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/57#discussion_r1362162990" expanded>

oops thank you for catching that
</panel>

<panel  header="**90 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/57#discussion_r1362194273" expanded>

Ok i changed it to include a isExit() method for Command and ExitCommand class
</panel>

<panel  header="**91 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/103#discussion_r1368628874" expanded>

ok that is a good idea! I have already made the changes
</panel>

<panel  header="**92 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/192#discussion_r1378713645" expanded>

so should I just put it all in Parser class?
</panel>

<panel  header="**93 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/39#issuecomment-1763699564" expanded>

I think you also need to comment out all the import statements in the test files
</panel>

<panel  header="**94 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/38#issuecomment-1766023508" expanded>

Also need to edit the main in order to start the application
</panel>

<panel  header="**95 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/40#issuecomment-1766524600" expanded>

This has been resolved by PR #38. Closing this PR.
</panel>

<panel  header="**96 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/71#issuecomment-1768594136" expanded>

Found no problems relating to coding standards so it looks good to me!
</panel>

<panel  header="**97 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/106#issuecomment-1776462350" expanded>

I feel that perhaps you should rename the PR to be more specific, e.g. Implement parser support for addOrder command
</panel>

<panel  header="**98 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/104#issuecomment-1776502981" expanded>

closing this PR as the order class has already been created in PR #86 
</panel>

<panel  header="**99 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/110#issuecomment-1778328293" expanded>

Have you tested to see if all of V1.0 features are working as intended?
</panel>

<panel  header="**100 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/113#issuecomment-1778335768" expanded>

Perhaps the UMLs should be changed after the implementation of PR #110 
</panel>

<panel  header="**101 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/122#issuecomment-1779227205" expanded>

closing this PR, issue is fixed in PR #119 
</panel>

<panel  header="**102 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/119#issuecomment-1779247132" expanded>

Fixes #121 
</panel>

<panel  header="**103 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/178#issuecomment-1787569900" expanded>

Perhaps also limit the ingredient name also
</panel>

<panel  header="**104 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/179#issuecomment-1787582920" expanded>

re-creating pull request to change the branch name 
</panel>

<panel  header="**105 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/194#issuecomment-1788940999" expanded>

issue has been fixed in PR #201 
</panel>

<panel  header="**106 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/214#issuecomment-1789140284" expanded>

Fixes #209 
</panel>

<panel  header="**107 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/208#issuecomment-1789145578" expanded>

Fixes #187 
</panel>

<panel  header="**108 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/187#issuecomment-1789146387" expanded>

issue resolved in PR #208 
</panel>

<panel  header="**109 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/204#issuecomment-1790779416" expanded>

Fixes #185 
</panel>

<panel  header="**110 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/185#issuecomment-1790780644" expanded>

Issue has been resolved in PR #204 
</panel>

<panel  header="**111 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/116#issuecomment-1790785943" expanded>

Architecture Diagram has been created to show relationships between classes in PR #208 
</panel>

<panel  header="**112 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/257#issuecomment-1794319680" expanded>

Already specified in UG
</panel>

<panel  header="**113 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/256#issuecomment-1794325142" expanded>

changing command name for better clarity, double check user guide website if the formatting is correct
</panel>

<panel  header="**114 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/251#issuecomment-1794336608" expanded>

add in user guide we only accept the dish price as &gt; $1000000
</panel>

<panel  header="**115 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/247#issuecomment-1794342566" expanded>

update regex
</panel>

<panel  header="**116 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/240#issuecomment-1794370130" expanded>

add in user guide, only saves data when bye command is used, we won't save data if force exit is used
</panel>

<panel  header="**117 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/227#issuecomment-1794378699" expanded>

have a min ingredient of min 1 for quantity
</panel>

<panel  header="**118 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/227#issuecomment-1794379356" expanded>

min price also should set
</panel>

<panel  header="**119 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/224#issuecomment-1797449766" expanded>

I don't really understand what the bug is supposed to be because the actual screenshot is the same as his actual
but I will try it to make it more clear in the UG that the input format for ingredient qty should have either g/ml
</panel>

<panel  header="**120 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/239#issuecomment-1797946696" expanded>

In the user guide it is already stated:

![image](https://github.com/AY2324S1-CS2113-T17-2/tp/assets/35828587/47f644a3-cec2-4e2f-9b2b-773844cdd50a)

</panel>

<panel  header="**121 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/247#issuecomment-1797947791" expanded>

In the user guide, it is already stated:
![image](https://github.com/AY2324S1-CS2113-T17-2/tp/assets/35828587/45c42ecf-a5ef-464f-ae89-4602e54d2b61)

</panel>

<panel  header="**122 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/253#issuecomment-1798002100" expanded>

ok will update the UG and also print a specified error message if the user inputs a number more than 2 d.p.
</panel>

<panel  header="**123 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/248#issuecomment-1798344985" expanded>

I think logically it is already implied that inputting dish name is alphanumeric
</panel>

<panel  header="**124 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/316#issuecomment-1806628400" expanded>

![image](https://github.com/AY2324S1-CS2113-T17-2/tp/assets/35828587/bed295cf-e138-42a0-82bc-f394331684ed)

</panel>

<panel  header="**125 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/301#issuecomment-1806785444" expanded>

To clarify, as of 11/11/23 19:03, the application will reject negative ingredient quantity and print out a generic error message. However, @ziyi105 has already created a function for reading the ingredient quantity in parseIngredients function in Parser class.
I will edit the regex to take in all types of characters in order to print the custom error handling message.
</panel>

<panel  header="**126 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/331#issuecomment-1807116120" expanded>

maybe perhaps you want to edit the typos in the PR :P
</panel>

<panel  header="**127 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/228#issuecomment-1807182748" expanded>

Issue has already been resolved
</panel>

<panel  header="**128 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/229#issuecomment-1807183174" expanded>

Issue has been resolved by implementing error handling in the `Encoder` and  `Decoder` classes to check for user tempering with the text files
</panel>

<panel  header="**129 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/327#issuecomment-1807193918" expanded>

Checked all three functionalities and have tested and ensured that the case sensitivity is handled
</panel>

<panel  header="**130 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/334#issuecomment-1807439712" expanded>

Seems like the PR #341 didn't seem to fix it
</panel>

<panel  header="**131 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/372#issuecomment-1808093669" expanded>

So when we display the dish name or ingredient name we just display it as all lowercase?
</panel>

<panel  header="**132 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/358#issuecomment-1808109686" expanded>

need to change picture that clearly displays my face D:
</panel>

<panel  header="**133 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/371#issuecomment-1808380800" expanded>

Oh ok i see what's wrong... I think its something to do with my parseIngredient function in the Parser class
</panel>

</panel>


<panel type="info" header="### 3. CHUA..RYAN `@ryan1604` (86 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/111#discussion_r1371181076" expanded>

Next time can change to use * instead of - to follow markdown coding standard
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/115#discussion_r1373083353" expanded>

I like the ordering of test methods
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/115#discussion_r1373083806" expanded>

Thanks for the quick bug fix!:D
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/116#discussion_r1373180422" expanded>

I like the clear method names!
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/116#discussion_r1373181936" expanded>

Maybe add a comment here to explain what this condition means?
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/116#discussion_r1373187299" expanded>

The fetchFMPStockPrices method seems to be getting a little long, maybe some lines can be extracted into another method.
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/118#discussion_r1375232757" expanded>

I like that we can add descriptions now
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/118#discussion_r1375234525" expanded>

Maybe can add spaces between methods to make the code more readable?
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/118#discussion_r1375234805" expanded>

I think can extract the if-else block in both cases "I" and "E" into the hasDescription method and just make it getDescription?
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/122#discussion_r1375279770" expanded>

The colour coding looks nice!
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/122#discussion_r1375279811" expanded>

```suggestion
 +<u>displayChart(chartType: String, cashFlowByCat: Map, type: String)<u>
```
missing space?
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/124#discussion_r1375379949" expanded>

Thanks for adding link:D
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/124#discussion_r1375379999" expanded>

Very nice
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/125#discussion_r1375393269" expanded>

Code looks cleaner. Good job!
</panel>

<panel  header="**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/125#discussion_r1375393855" expanded>

Do we still need the toUpperCase method if its alr in uppercase
</panel>

<panel  header="**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/127#discussion_r1375416729" expanded>

Instead of deleting future cashflow, maybe can just check if the date is after current time and throw an exception in getEntry
</panel>

<panel  header="**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/127#discussion_r1375422976" expanded>

missing try catch for date?
</panel>

<panel  header="**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/127#discussion_r1375423114" expanded>

can the addrecurringcashflow be done in the income/expense class instead? eg. when making new income/expense object, the recurring is checked in the constructor
</panel>

<panel  header="**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/127#discussion_r1375424331" expanded>

i think its to indicate explicityly that case "I" and "E" have the same body
</panel>

<panel  header="**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/129#discussion_r1375579765" expanded>

`list recurrence`**
</panel>

<panel  header="**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/129#discussion_r1375580107" expanded>

Download**, neo chatbot?
</panel>

<panel  header="**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/128#discussion_r1375581619" expanded>

Gj
</panel>

<panel  header="**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/130#discussion_r1377059010" expanded>

Good info
</panel>

<panel  header="**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/130#discussion_r1377059058" expanded>

Nice details!
</panel>

<panel  header="**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/130#discussion_r1377059182" expanded>

Comment can be removed if not needed
</panel>

<panel  header="**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/130#discussion_r1377124426" expanded>

all good then
</panel>

<panel  header="**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/134#discussion_r1377813670" expanded>

```suggestion
        ui.showMessage(reminderList.list.toString());
```
No need another getInstance() here i think
</panel>

<panel  header="**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/134#discussion_r1377815309" expanded>

```suggestion
        if (index > ReminderList.getInstance().list.size()+1){
```

</panel>

<panel  header="**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/134#discussion_r1377815689" expanded>

```suggestion
        if (rawCommand.args.size() == 1) {
```
</panel>

<panel  header="**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/134#discussion_r1377817125" expanded>

Should there be a ":" after Goal? Same thing for reminder
</panel>

<panel  header="**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/135#discussion_r1377828861" expanded>

show*
</panel>

<panel  header="**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/135#discussion_r1377843917" expanded>

Not sure the point of this method
</panel>

<panel  header="**33 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/135#discussion_r1377844705" expanded>

Good job renaming to clearer names
</panel>

<panel  header="**34 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/135#discussion_r1377846716" expanded>

Why add this method?
</panel>

<panel  header="**35 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/135#discussion_r1377854283" expanded>

Can consider omitting less important details in both class diagrams
</panel>

<panel  header="**36 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/135#discussion_r1378505364" expanded>

Both same
</panel>

<panel  header="**37 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/142#discussion_r1378873728" expanded>

I like the details, good job!
</panel>

<panel  header="**38 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/141#discussion_r1378876437" expanded>

Nice addition
</panel>

<panel  header="**39 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/142#discussion_r1378878549" expanded>

Can delete the space here
</panel>

<panel  header="**40 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/143#discussion_r1378893006" expanded>

```suggestion
        if (rawCommand.args.size() == 1) {
```
</panel>

<panel  header="**41 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/143#discussion_r1378897169" expanded>

Can add functions to save and load goal and reminder from storage
</panel>

<panel  header="**42 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/143#discussion_r1378901005" expanded>

Thank you
</panel>

<panel  header="**43 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/150#discussion_r1380056638" expanded>

Thanks for the quick fixes
</panel>

<panel  header="**44 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/151#discussion_r1380931464" expanded>

Redundant break statement?
</panel>

<panel  header="**45 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/151#discussion_r1380931504" expanded>

also here
</panel>

<panel  header="**46 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/192#discussion_r1382406273" expanded>

I think displaying one cashflow for all the list features is enough to prevent UG from getting too long
</panel>

<panel  header="**47 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/192#discussion_r1382409764" expanded>

Good safeguards
</panel>

<panel  header="**48 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/192#discussion_r1382409800" expanded>

Nice details!
</panel>

<panel  header="**49 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/193#discussion_r1382412436" expanded>

Should it be "Why is it saying"*
</panel>

<panel  header="**50 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/193#discussion_r1382412543" expanded>

variable name should be fiveMin
</panel>

<panel  header="**51 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/193#discussion_r1382412699" expanded>

might want to use showMessage method for cyan text
</panel>

<panel  header="**52 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/193#discussion_r1382412936" expanded>

This too 
</panel>

<panel  header="**53 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/193#discussion_r1382413096" expanded>

More detailed error message. Nice
</panel>

<panel  header="**54 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/193#discussion_r1382422913" expanded>

mb showmessage in this method no need since it alr got own colour
</panel>

<panel  header="**55 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/194#discussion_r1384348681" expanded>

Very extensive testing 👍 
</panel>

<panel  header="**56 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385811018" expanded>

Remove comment if not needed
</panel>

<panel  header="**57 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385812649" expanded>

spacing
</panel>

<panel  header="**58 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385812700" expanded>

spacing

</panel>

<panel  header="**59 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385812780" expanded>

spacing

</panel>

<panel  header="**60 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385815037" expanded>

is it necessary to be in another line?
</panel>

<panel  header="**61 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385815317" expanded>

is it necessary to be in another line?
</panel>

<panel  header="**62 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385815359" expanded>

is it necessary to be in another line?
</panel>

<panel  header="**63 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385815681" expanded>

is it necessary to be in another line?
</panel>

<panel  header="**64 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385816126" expanded>

i think there is an option recurring option for this? check with min wei
</panel>

<panel  header="**65 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385817172" expanded>

is it necessary to be in another line?
</panel>

<panel  header="**66 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385817921" expanded>

is it necessary to be in another line?
</panel>

<panel  header="**67 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385818082" expanded>

is it necessary to be in another line?

</panel>

<panel  header="**68 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385830215" expanded>

should be [income/exspense/recurring] and string can be in one line
</panel>

<panel  header="**69 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385830815" expanded>

is it necessary to be in another line?
</panel>

<panel  header="**70 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385830875" expanded>

is it necessary to be in another line?
</panel>

<panel  header="**71 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385831100" expanded>

is it necessary to be in another line?
</panel>

<panel  header="**72 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385831146" expanded>

is it necessary to be in another line?
</panel>

<panel  header="**73 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385832458" expanded>

might want to follow textbook way of making singleton
</panel>

<panel  header="**74 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/197#discussion_r1386895153" expanded>

lets the user*
</panel>

<panel  header="**75 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/197#discussion_r1386895621" expanded>

Capitalise "a"
</panel>

<panel  header="**76 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/197#discussion_r1386895940" expanded>

Want to add this too?
</panel>

<panel  header="**77 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/198#discussion_r1388752625" expanded>

Can change format to follow cashflow eg. dd/MM/yyyy
</panel>

<panel  header="**78 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/198#discussion_r1388753502" expanded>

format for here too

</panel>

<panel  header="**79 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/201#discussion_r1388897614" expanded>

eg.!
</panel>

<panel  header="**80 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/206#discussion_r1390183955" expanded>

good find

</panel>

<panel  header="**81 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/207#discussion_r1390184326" expanded>

why remove emoji D:
</panel>

<panel  header="**82 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/211#discussion_r1390344219" expanded>

I think for consistency its better for either all methods to have activations bars or none at all
</panel>

<panel  header="**83 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/211#discussion_r1390344239" expanded>

here too
</panel>

<panel  header="**84 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/212#discussion_r1390364382" expanded>

can import the package then just use Logger logger instead
</panel>

<panel  header="**85 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/214#discussion_r1390420057" expanded>

"the same to income" u mean?
</panel>

<panel  header="**86 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/212#discussion_r1390528905" expanded>

Didnt change the second part
</panel>

<panel  header="**87 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/110#discussion_r1371181498" expanded>

welcome:D
</panel>

<panel  header="**88 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/110#discussion_r1371181634" expanded>

noted will change in future prs
</panel>

<panel  header="**89 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/101#discussion_r1371183798" expanded>

i put file path in parameter for junit testing:D
</panel>

<panel  header="**90 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/101#discussion_r1371184295" expanded>

ok will note for the future
</panel>

<panel  header="**91 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/101#discussion_r1371185689" expanded>

it is in the method:)
</panel>

<panel  header="**92 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/114#discussion_r1372452955" expanded>

thanks for reminding i missed that
</panel>

<panel  header="**93 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/114#discussion_r1373965505" expanded>

added
</panel>

<panel  header="**94 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/114#discussion_r1373965530" expanded>

changed!
</panel>

<panel  header="**95 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/114#discussion_r1373965556" expanded>

fixed
</panel>

<panel  header="**96 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/119#discussion_r1375235299" expanded>

💀 i changed it to the second one
</panel>

<panel  header="**97 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/119#discussion_r1375362760" expanded>

added!
</panel>

<panel  header="**98 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/131#discussion_r1377329325" expanded>

no 
</panel>

<panel  header="**99 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/132#discussion_r1377355442" expanded>

added to loadbudget in loaddata
</panel>

<panel  header="**100 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/196#discussion_r1385807859" expanded>

Thats all under model:)
</panel>

<panel  header="**101 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/215#discussion_r1390436591" expanded>

other incorrect commands for tester to come up with
</panel>

<panel  header="**102 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/215#discussion_r1390436668" expanded>

1 billion net worth 💪 
</panel>

<panel  header="**103 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/215#discussion_r1390436699" expanded>

thanks!
</panel>

<panel  header="**104 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/57#issuecomment-1763279236" expanded>

dont merge yet
</panel>

<panel  header="**105 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/58#issuecomment-1763279955" expanded>

dont merge yet

</panel>

<panel  header="**106 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/55#issuecomment-1763654579" expanded>

Closed as completed via #70 
</panel>

<panel  header="**107 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/57#issuecomment-1763790964" expanded>

Some changes made:

- Add budget function
- Update budget function
- Automatically update current budget(if there is one) when new expense is added
- Remove redundant get() and size() in cashFlowList
- Remove redundant "NAME" from command prefix
</panel>

<panel  header="**108 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/58#issuecomment-1765621497" expanded>

> Very good in abstracting out the Ui elements However, the code in lines 37 and 49 are STILL DEEPLY NESTED

I believe 2-3 layers of nesting is fine
</panel>

<panel  header="**109 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/58#issuecomment-1765621687" expanded>

> LGTM, Maybe in the AddCashFlowCommand, you can create a method in UI to print the remaining budget or the exceeded budget instead of using showMessage

Good idea! I will look into it
</panel>

<panel  header="**110 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/91#issuecomment-1765622034" expanded>

> Looks good to me! However, I believe that we should standardise how we write our logging message and the level of severity across the different features

I agree. We should discuss how to standardise it soon.
</panel>

<panel  header="**111 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/28#issuecomment-1765820886" expanded>

Closed as completed via #88 
</panel>

<panel  header="**112 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/112#issuecomment-1777319851" expanded>

Completed in #110 
</panel>

<panel  header="**113 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/122#issuecomment-1783990734" expanded>

Unrelated but can help to hyperlink the links in the DG?
![image](https://github.com/AY2324S1-CS2113-T18-2/tp/assets/94791461/676a85cb-b14d-4aa4-82f8-3e8829dcd036)

</panel>

<panel  header="**114 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/65#issuecomment-1784019173" expanded>

Completed via #97
</panel>

<panel  header="**115 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/144#issuecomment-1789155926" expanded>

Cloed as fixed in #142 
</panel>

<panel  header="**116 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/149#issuecomment-1791754904" expanded>

Closed as clarified in tutorial
</panel>

<panel  header="**117 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/75#issuecomment-1791840163" expanded>

Closed as fixed in #151 
</panel>

<panel  header="**118 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/139#issuecomment-1791840275" expanded>

Closed as fixed in #151 
</panel>

<panel  header="**119 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/170#issuecomment-1792788417" expanded>

Can anyone see this
</panel>

<panel  header="**120 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/166#issuecomment-1793321266" expanded>

Closed as object not deleted
</panel>

<panel  header="**121 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/171#issuecomment-1793322232" expanded>

maybe dont need
</panel>

<panel  header="**122 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/175#issuecomment-1793323158" expanded>

Program is not intended to be exited with ctrl + c. Warning mentioned in UG.
</panel>

<panel  header="**123 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/179#issuecomment-1793323477" expanded>

Closed as duplicate
</panel>

<panel  header="**124 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/183#issuecomment-1793324027" expanded>

see how u want do
</panel>

<panel  header="**125 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/185#issuecomment-1793324243" expanded>

Closed as duplicate
</panel>

<panel  header="**126 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/186#issuecomment-1793324490" expanded>

Closed as duplicate
</panel>

<panel  header="**127 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/190#issuecomment-1793325153" expanded>

Will be fixed with #184 
</panel>

<panel  header="**128 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/164#issuecomment-1793326855" expanded>

Will be fixed with #162 
</panel>

<panel  header="**129 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/175#issuecomment-1793399829" expanded>

Closed as reason mentioned above.
</panel>

<panel  header="**130 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/148#issuecomment-1794141965" expanded>

Closed as completed via #192 and #193
</panel>

<panel  header="**131 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/170#issuecomment-1800851816" expanded>

Closed
</panel>

<panel  header="**132 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/155#issuecomment-1803847320" expanded>

Closed as completed in #197 
</panel>

<panel  header="**133 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/156#issuecomment-1803848228" expanded>

Closed as completed in #197 
</panel>

<panel  header="**134 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/161#issuecomment-1803849780" expanded>

Closed as completed in #197

</panel>

<panel  header="**135 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/187#issuecomment-1803852106" expanded>

Closed
</panel>

</panel>


<panel type="info" header="### 4. NEO .. WEI `@NeoMinWei` (85 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/104#discussion_r1371149420" expanded>

maybe can add comments on what the values mean?
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/113#discussion_r1371150254" expanded>

cool fixes
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/110#discussion_r1371151038" expanded>

The brackets of abstract not changed in the png.
The closing bracket is ] instead of }
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/108#discussion_r1371151731" expanded>

thanks for adding acknowledgements with similar formats
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/107#discussion_r1371152239" expanded>

very prompt bug fix, excellent work ethic
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/101#discussion_r1371154797" expanded>

maybe some logging can be added here
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/98#discussion_r1371155188" expanded>

thanks for changing the log level to warning to match the rest of code
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/95#discussion_r1371155607" expanded>

good bug fix
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/94#discussion_r1371156515" expanded>

thanks for removing commented out code, makes the overall code neater
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/93#discussion_r1371157254" expanded>

good use of logging
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/91#discussion_r1371157959" expanded>

thanks for standardising this log when default case is reached
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/89#discussion_r1371158657" expanded>

thanks for keeping this method
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/88#discussion_r1371159321" expanded>

good job on keeping the code length short
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/70#discussion_r1371160360" expanded>

thanks for your help on the exceptions
</panel>

<panel  header="**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/69#discussion_r1371161194" expanded>

good job on using hashmaps
</panel>

<panel  header="**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/58#discussion_r1371162041" expanded>

good job on using rounding function to make the value more accurate when displayed in 2d.p.
</panel>

<panel  header="**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/114#discussion_r1371926354" expanded>

is there a neater way of writing this, maybe split into steps
</panel>

<panel  header="**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/114#discussion_r1371927507" expanded>

can logging be added here if default case is not meant to be reached
</panel>

<panel  header="**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/115#discussion_r1373299967" expanded>

why is there a space here
</panel>

<panel  header="**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/115#discussion_r1373300434" expanded>

good use of ordering
</panel>

<panel  header="**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/116#discussion_r1373301583" expanded>

good use of getter and setters
</panel>

<panel  header="**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/116#discussion_r1373302486" expanded>

consider adding log here
</panel>

<panel  header="**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/116#discussion_r1373304893" expanded>

good use of creating new string variables and combining them in a single system output
</panel>

<panel  header="**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/117#discussion_r1375211593" expanded>

maybe can add a parsertest class in the future to ensure that it is bug free
</panel>

<panel  header="**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/119#discussion_r1375234778" expanded>

"exited" !!!!!!!!!
or "crashes or exits" !!!!
</panel>

<panel  header="**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/122#discussion_r1375283555" expanded>

what is &gt;"u"> at the end of methods?
the previous format is more legible imo
</panel>

<panel  header="**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/122#discussion_r1375364918" expanded>

the prev colour scheme easier to read
</panel>

<panel  header="**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/124#discussion_r1375384481" expanded>

bar char
</panel>

<panel  header="**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/124#discussion_r1375384563" expanded>

maybe can put on what exchange the watchlist is displaying
</panel>

<panel  header="**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/124#discussion_r1375384686" expanded>

very cool in adding the links
</panel>

<panel  header="**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/125#discussion_r1375395027" expanded>

good use of getters and setters
</panel>

<panel  header="**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/128#discussion_r1375483607" expanded>

remove commented code if necessary
</panel>

<panel  header="**33 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/128#discussion_r1375483821" expanded>

Plese
</panel>

<panel  header="**34 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/130#discussion_r1377213173" expanded>

These
</panel>

<panel  header="**35 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/130#discussion_r1377213645" expanded>

cool notes
</panel>

<panel  header="**36 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/130#discussion_r1377215208" expanded>

cute face
</panel>

<panel  header="**37 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/131#discussion_r1377215912" expanded>

nice addition
</panel>

<panel  header="**38 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/131#discussion_r1377218047" expanded>

need javadoc for private methods also?
</panel>

<panel  header="**39 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/132#discussion_r1377221317" expanded>

can consider using LocalDate.now instead of using public currentDate from the financialplanner
</panel>

<panel  header="**40 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/132#discussion_r1377224251" expanded>

possible to add exceptions if the currentDate is before savedDate
</panel>

<panel  header="**41 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/134#discussion_r1377722708" expanded>

possible to add logging in this constructor
</panel>

<panel  header="**42 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/134#discussion_r1377724197" expanded>

```suggestion
        Ui.getInstance().showMessage("You have deleted " + ReminderList.getInstance().list.get(index-1));
```

</panel>

<panel  header="**43 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/134#discussion_r1377727480" expanded>

```suggestion
        if (index > ReminderList.getInstance().list.size()+1){
```
</panel>

<panel  header="**44 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/134#discussion_r1377728008" expanded>

```suggestion
        if (index > ReminderList.getInstance().list.size()+1){
```
</panel>

<panel  header="**45 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/134#discussion_r1377728416" expanded>

```suggestion
        if (rawCommand.args.size() == 1) {
```
</panel>

<panel  header="**46 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/134#discussion_r1377730583" expanded>

should there be spacing between package and imports
</panel>

<panel  header="**47 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/134#discussion_r1377732724" expanded>

maybe can make reminderlist and ui members in the class so don't have to keep using getInstance
</panel>

<panel  header="**48 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/141#discussion_r1378868937" expanded>

nice images
</panel>

<panel  header="**49 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/142#discussion_r1378870733" expanded>

why not import the entire parser class instead
</panel>

<panel  header="**50 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/142#discussion_r1378872711" expanded>

can make ui a member instead of using getInstance all the time
</panel>

<panel  header="**51 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/142#discussion_r1378874074" expanded>

would it be better to make helpcommand a singleton?
</panel>

<panel  header="**52 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/143#discussion_r1378875880" expanded>

```suggestion
        if (rawCommand.args.size() == 1) {
```
</panel>

<panel  header="**53 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/143#discussion_r1378876161" expanded>

```suggestion
        if (index > WishList.getInstance().list.size() + 1){
```
</panel>

<panel  header="**54 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/143#discussion_r1378876524" expanded>

```suggestion
        Ui.getInstance().showMessage("You have achieved " + goal + System.lineSeparator() + "Congratulations!");
```
</panel>

<panel  header="**55 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/143#discussion_r1378881912" expanded>

can the goal be one of the expensetypes? ie. buy car would be under 'others'. so goal shouldnt be one of the types
</panel>

<panel  header="**56 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/151#discussion_r1380406300" expanded>

Nice use of ? and :
</panel>

<panel  header="**57 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/151#discussion_r1380407204" expanded>

logging can be added here when default case is reached. level severe
</panel>

<panel  header="**58 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/191#discussion_r1382540192" expanded>

add a final return for the execute() so the bar does not continue off the diagram
</panel>

<panel  header="**59 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/193#discussion_r1382540542" expanded>

```suggestion
- Note: Watchlist feature requires a stable internet connection
```
</panel>

<panel  header="**60 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/193#discussion_r1382540673" expanded>

nice addition
</panel>

<panel  header="**61 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/193#discussion_r1382540808" expanded>

nice emoji
</panel>

<panel  header="**62 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385243127" expanded>

is this the correct spacing? should the spacing be 8 spaces?
</panel>

<panel  header="**63 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385248876" expanded>

should /t TYPE be in &gt;> brackets instead since its required
</panel>

<panel  header="**64 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385250573" expanded>

please check spacing here as well
</panel>

<panel  header="**65 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385251370" expanded>

please check spacing for here
</panel>

<panel  header="**66 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385251573" expanded>

check spacing here
</panel>

<panel  header="**67 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385251813" expanded>

spacing
</panel>

<panel  header="**68 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1385251927" expanded>

spacing
</panel>

<panel  header="**69 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/196#discussion_r1385254528" expanded>

storage quite hard to see
</panel>

<panel  header="**70 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/196#discussion_r1385256551" expanded>

is targeted*
</panel>

<panel  header="**71 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#discussion_r1386108497" expanded>

delete [income/expense] &gt;index> [/r]
</panel>

<panel  header="**72 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/197#discussion_r1386875968" expanded>

good details
</panel>

<panel  header="**73 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/197#discussion_r1386878037" expanded>

nice hard work
</panel>

<panel  header="**74 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/198#discussion_r1388839705" expanded>

possible to change this to dd/MM/yyyy to standardise dates
</panel>

<panel  header="**75 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/202#discussion_r1388939388" expanded>

Nicely done
</panel>

<panel  header="**76 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/206#discussion_r1390183489" expanded>

There is still a Left Days portion below the status
</panel>

<panel  header="**77 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/208#discussion_r1390219430" expanded>

Good extensive testing
</panel>

<panel  header="**78 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/208#discussion_r1390219663" expanded>

good fix
</panel>

<panel  header="**79 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/212#discussion_r1390376672" expanded>

nice testing
</panel>

<panel  header="**80 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/211#discussion_r1390376997" expanded>

delete this if not needed
</panel>

<panel  header="**81 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/214#discussion_r1390418251" expanded>

should this be ###WatchList Feature instead
</panel>

<panel  header="**82 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/215#discussion_r1390437168" expanded>

string can be numbers also, be more specific
</panel>

<panel  header="**83 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/217#discussion_r1390856177" expanded>

nice
</panel>

<panel  header="**84 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/221#discussion_r1391208457" expanded>

nicely done
</panel>

<panel  header="**85 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/222#discussion_r1391258022" expanded>

nice catch
</panel>

<panel  header="**86 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/111#discussion_r1371150566" expanded>

very good suggestion, will consider
</panel>

<panel  header="**87 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/103#discussion_r1371152989" expanded>

thanks!
</panel>

<panel  header="**88 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/127#discussion_r1375442131" expanded>

no
</panel>

<panel  header="**89 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/127#discussion_r1375442170" expanded>

yes
</panel>

<panel  header="**90 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/127#discussion_r1375442192" expanded>

no
</panel>

<panel  header="**91 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/135#discussion_r1378471468" expanded>

key to success
</panel>

<panel  header="**92 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/135#discussion_r1378472889" expanded>

how
</panel>

<panel  header="**93 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/135#discussion_r1378473156" expanded>

from where
</panel>

<panel  header="**94 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/192#discussion_r1382541008" expanded>

trim everywhere
</panel>

<panel  header="**95 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/70#issuecomment-1763439903" expanded>

LGTM, just need fix the CLI and update text-ui-test file
</panel>

<panel  header="**96 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/64#issuecomment-1774049147" expanded>

Duplicate of #20 and #21 
</panel>

<panel  header="**97 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/134#issuecomment-1787438458" expanded>

> > LGTM, how do u want to change the parser?
> 
> I haven't added the command to parser to avoid conflict. After all features implemented, I will add these commands to parser.

ok
</panel>

<panel  header="**98 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/142#issuecomment-1789090175" expanded>

Make sure to close issue #144 once u merge
</panel>

</panel>


<panel type="info" header="### 5. CHAR..G YU `@charkty` (81 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/14#discussion_r1361573588" expanded>

Is there a need to extend the ArrayList&gt;Recipe>? This is because we are already initialising recipes as an ArrayList and ArrayList itself has functions that we can use. Is the extending part for clarity purposes? Should we remove it or leave it?
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/14#discussion_r1361643888" expanded>

Should this be addRecipe(Recipe recipe) instead?
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/25#discussion_r1363236141" expanded>

Clear and concise. Can rename function to listRecipes to standardise with listIngredients, thank you.
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/33#discussion_r1364927026" expanded>

Would it be better if you create 2 variables - invalidCommand and invalidDetails - and give them user like input to pass through the parser?
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/46#discussion_r1365233410" expanded>

Good that you extracted out the print statements into Ui
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/44#discussion_r1365241654" expanded>

i agree because ingredient parser should be handling it and it already does
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/44#discussion_r1365247655" expanded>

since the above parseIngredientTitle() is removed, you pass the formatted parameters needed (in this case is ingredientTitle) directly in the parameter of this function 
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/44#discussion_r1365257013" expanded>

maybe can check if command is a bye command for the do while loop, but i like that you extracted out a bye command though, it gives consistency in our code
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/51#discussion_r1367609879" expanded>

nice implementation of the isExitCommand
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/51#discussion_r1367610045" expanded>

very clear constructor
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/52#discussion_r1369665468" expanded>

good use of static method
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/59#discussion_r1371221295" expanded>

very clear code. good that it was implemented in the command class and that the command class calls the parsers.
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/59#discussion_r1371221662" expanded>

nice naming.
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/59#discussion_r1371223595" expanded>

good use of overriding method
</panel>

<panel  header="**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/59#discussion_r1371225460" expanded>

Good use of abbreviation. When is it used though? If it is not used is it necessary? Is it for clarity because user input is in that format?
</panel>

<panel  header="**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/59#discussion_r1371232378" expanded>

what is the command to edit the quantity?
</panel>

<panel  header="**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/60#discussion_r1371241516" expanded>

good reuse of parseIngredient method
</panel>

<panel  header="**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/60#discussion_r1371244009" expanded>

should remove this line because edit function shouldn't be adding an ingredeint if there is an error
</panel>

<panel  header="**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/60#discussion_r1371245391" expanded>

can consider creating a ingredientExist() function in ingredientList
</panel>

<panel  header="**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/60#discussion_r1371247797" expanded>

i think we should implement such that we only change the quantity and the unit of the ingredient, rather than the name also. This is because you check if the name of an ingredient exist in your EditIngredient command.
</panel>

<panel  header="**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/60#discussion_r1371248276" expanded>

very clean mapping. good job!
</panel>

<panel  header="**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/60#discussion_r1371253484" expanded>

but a comma before QUANTITY
</panel>

<panel  header="**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/65#discussion_r1372597476" expanded>

can start from i=0 for the for loop, then just need to use steps[i]
</panel>

<panel  header="**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/65#discussion_r1372598292" expanded>

toAdd shouldnt have "r/", if it does, should be removed i parser class. Hence, dont need Recipe.Parser.parseRecipeTitle(...)
</panel>

<panel  header="**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/65#discussion_r1372599053" expanded>

same as above comments&hat;
</panel>

<panel  header="**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/65#discussion_r1372599983" expanded>

i think the or symbol is "||", one line is for bitwise 
</panel>

<panel  header="**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/65#discussion_r1372602255" expanded>

can add a new line for each function called. 
![image](https://github.com/AY2324S1-CS2113-F11-2/tp/assets/72329348/c491c105-7660-41e4-9e5a-89f1799606b4)

and can change recipe1 name to filteredRecipe

</panel>

<panel  header="**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/96#discussion_r1375648643" expanded>

Nice that there is an alternative that will prompt user to input steps or ingredients when missing
</panel>

<panel  header="**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/96#discussion_r1375649259" expanded>

Can remove ByIndex because of method overloading 
</panel>

<panel  header="**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/96#discussion_r1375649761" expanded>

can remove "WithInvalidInput" in your naming
</panel>

<panel  header="**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/101#discussion_r1377201285" expanded>

neat setup
</panel>

<panel  header="**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/101#discussion_r1377349511" expanded>

maybe can rename to addIngredientToList
</panel>

<panel  header="**33 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/101#discussion_r1377360487" expanded>

when initialising, can handle situations where if file cannot be found or if directory cannot be found
</panel>

<panel  header="**34 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/104#discussion_r1378302575" expanded>

I like how you added these methods in exception
</panel>

<panel  header="**35 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/104#discussion_r1379018617" expanded>

I like how your sequence diagrams used here are very simplified and clear, only putting in relevant details. 
</panel>

<panel  header="**36 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/104#discussion_r1379020823" expanded>

The light green color could be changed to a darker background to increase readability.
</panel>

<panel  header="**37 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/104#discussion_r1379026364" expanded>

Should the try and catach of FileNotFoundException be in the storage instead? This can make the main code cleaner and shorter. For the main code (EssenMakanan), maybe it's better to only handle EssenException.
</panel>

<panel  header="**38 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/104#discussion_r1379028795" expanded>

Your methods in this class have very intuitive naming!
</panel>

<panel  header="**39 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/104#discussion_r1379030173" expanded>

I like your coverage of exceptions!
</panel>

<panel  header="**40 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/104#discussion_r1379496608" expanded>

I think it would be better to handle in the storage class so that you don't need to catch an error here
</panel>

<panel  header="**41 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/104#discussion_r1379497132" expanded>

I think it is better to handle file not found exception here, dont need to throw error
</panel>

<panel  header="**42 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/107#discussion_r1379614139" expanded>

I like that you made the duration optional and that you have a flag for the duration
</panel>

<panel  header="**43 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/107#discussion_r1379615266" expanded>

I like that you included all the different formats of time.
</panel>

<panel  header="**44 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/107#discussion_r1379616477" expanded>

is this method necessary? Since it already take the recipe as a param, then it can directly call recipe.viewTimeLine() for whichever code that calls listRecipeSteps.
</panel>

<panel  header="**45 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/107#discussion_r1379646227" expanded>

nice! you could consider adding invalid inputs as well
</panel>

<panel  header="**46 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/109#discussion_r1379951497" expanded>

Neat addition of the new variables
</panel>

<panel  header="**47 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/109#discussion_r1379954962" expanded>

"EMPTY" is a good alternative to just a blank!
</panel>

<panel  header="**48 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/109#discussion_r1379961107" expanded>

I like the use of "||" and "|"
</panel>

<panel  header="**49 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/111#discussion_r1380212736" expanded>

Good use of split using "/" instead of "i/", "s/" etc. Gives a lot of flexibility.
</panel>

<panel  header="**50 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/112#discussion_r1380261387" expanded>

Nice catching and handling of exception in storage class
</panel>

<panel  header="**51 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/115#discussion_r1380279994" expanded>

Nice handling of exception, helps to fix the bug
</panel>

<panel  header="**52 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/120#discussion_r1380949813" expanded>

Nice splitting it into 2 lines, makes your table less lengthy
</panel>

<panel  header="**53 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/120#discussion_r1380950334" expanded>

You may want to state the different tags available or refer the user to another section. 
</panel>

<panel  header="**54 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/120#discussion_r1380950659" expanded>

Very clear steps
</panel>

<panel  header="**55 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/213#discussion_r1384734181" expanded>

Good add of assertion!
</panel>

<panel  header="**56 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/213#discussion_r1384735150" expanded>

format the line properly: if (eachStep.length() > 0 && eachStep.contains("d/")) {
</panel>

<panel  header="**57 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/213#discussion_r1384738657" expanded>

nice error handling, I like your messages.
</panel>

<panel  header="**58 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/213#discussion_r1384739441" expanded>

Nice handling of exception when any one of the flags are missing
</panel>

<panel  header="**59 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/213#discussion_r1384741700" expanded>

I like your test cases! Good job!
</panel>

<panel  header="**60 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/228#discussion_r1387940233" expanded>

I like your implementation of endsWith(".0"), a very smart method! 
</panel>

<panel  header="**61 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/228#discussion_r1387943076" expanded>

Will it be better to put this under else? So that you dont have to use return; and maybe it would be clearer that you are handling 2 different cases.
</panel>

<panel  header="**62 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/228#discussion_r1387943940" expanded>

Good handling of cases!
</panel>

<panel  header="**63 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/228#discussion_r1387944843" expanded>

Does this comment value add to your clear if statement?
</panel>

<panel  header="**64 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/235#discussion_r1388817417" expanded>

Do the comments value add?
</panel>

<panel  header="**65 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/235#discussion_r1388817616" expanded>

Good use of assertion to ensure that step is initialised.
</panel>

<panel  header="**66 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/241#discussion_r1389128796" expanded>

The case of when s/ is empty is properly handled. However, is the case of when there is no string attached behind edit i/RECIPE_TITLE handled? #190 
</panel>

<panel  header="**67 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/241#discussion_r1389130886" expanded>

This works and solves #159! But is recipeTitle.isEmpty() more appropriate for strings? 
</panel>

<panel  header="**68 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/241#discussion_r1389132935" expanded>

Do you need to use detail.trim() to remove the trailing and leading whitespaces in order to solve #176 ?
</panel>

<panel  header="**69 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/241#discussion_r1389137066" expanded>

Very concise handling of the first part of #151 ! However, did you miss out on error messages for when recipe list is empty and the user types view r/1? An error message should be printed in that case too.
</panel>

<panel  header="**70 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/244#discussion_r1389321756" expanded>

I like that you tested for an invalid case.
</panel>

<panel  header="**71 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/239#discussion_r1389325506" expanded>

Would it be better to do if(!ingredient.isEmpty()){...} so that everything is handled within the if statement?
</panel>

<panel  header="**72 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/239#discussion_r1389328835" expanded>

I like the consistency in this if statement where Single Level of Abstraction Principle is used!
</panel>

<panel  header="**73 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/239#discussion_r1389329890" expanded>

Would it be better to name it printNegativeQuantityErrorMessage ?
</panel>

<panel  header="**74 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/239#discussion_r1389330438" expanded>

I like your consideration of errors thrown!
</panel>

<panel  header="**75 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/248#discussion_r1390080945" expanded>

Should this be checked in parser instead? 
</panel>

<panel  header="**76 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/248#discussion_r1390081103" expanded>

Good coverage of test cases
</panel>

<panel  header="**77 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/241#discussion_r1390320662" expanded>

#151 handled!
</panel>

<panel  header="**78 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/266#discussion_r1390610951" expanded>

Good addition of space, resolves UG formatting issue
</panel>

<panel  header="**79 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/266#discussion_r1390611337" expanded>

Good link to the check command. Shows user the relation between the commands.
</panel>

<panel  header="**80 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/280#discussion_r1391942593" expanded>

There is an extra L in Charlyn.
</panel>

<panel  header="**81 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/303#discussion_r1392913311" expanded>

good use of table of contents
</panel>

<panel  header="**82 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/19#discussion_r1361648885" expanded>

good point, will change the name
</panel>

<panel  header="**83 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/19#discussion_r1361658776" expanded>

yes, will change it
</panel>

<panel  header="**84 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/203#issuecomment-1797879540" expanded>

Same as #208
</panel>

<panel  header="**85 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/202#issuecomment-1797880699" expanded>

Delete milk is a wrong format so it will not delete. Not a bug.
</panel>

<panel  header="**86 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/200#issuecomment-1797881468" expanded>

It is a valid user input.
</panel>

<panel  header="**87 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/198#issuecomment-1797883096" expanded>

Same as #208 
</panel>

<panel  header="**88 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/188#issuecomment-1797892382" expanded>

Same as #196
</panel>

<panel  header="**89 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/184#issuecomment-1797894367" expanded>

Close with issue #108
</panel>

<panel  header="**90 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/182#issuecomment-1797894982" expanded>

Close with #211 
</panel>

<panel  header="**91 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/181#issuecomment-1797896194" expanded>

Close with #209 
</panel>

<panel  header="**92 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/180#issuecomment-1797897642" expanded>

Closes with #193
</panel>

<panel  header="**93 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/170#issuecomment-1797904554" expanded>

Close with #174 
</panel>

<panel  header="**94 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/166#issuecomment-1797908593" expanded>

Close with #173
</panel>

<panel  header="**95 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/164#issuecomment-1797910483" expanded>

Closes with #174
</panel>

<panel  header="**96 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/161#issuecomment-1797912425" expanded>

Closes with #173 
</panel>

<panel  header="**97 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/157#issuecomment-1797917112" expanded>

Closes with #179
</panel>

<panel  header="**98 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/147#issuecomment-1797925545" expanded>

Close with #172 
</panel>

</panel>


<panel type="info" header="### 6. PUA ..RICK `@wwweert123` (74 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/111#discussion_r1371108428" expanded>

Maybe can include a screenshot of an example output here!
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/110#discussion_r1371109683" expanded>

Thanks for changing the typo error here
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/103#discussion_r1371110234" expanded>

Good use of assertions!
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/101#discussion_r1371110852" expanded>

Maybe file_path can be stored in the storage class?
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/101#discussion_r1371111354" expanded>

maybe extract this method further into showMonthlyBudget in UI?
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/114#discussion_r1372990190" expanded>

Thanks for helping me change the path!
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/114#discussion_r1372992618" expanded>

Wow, this line look very long. Maybe can separate out and store values in variables for readability
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/114#discussion_r1372995683" expanded>

For budget sequence diagram, you might want to add : for objects of classes or add &gt;&gt;class>> if you are interacting with class static methods
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/117#discussion_r1375247114" expanded>

Good use of negative testing
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/117#discussion_r1375247425" expanded>

Good unit testing involving exceptionhandling
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/117#discussion_r1375247623" expanded>

Nice ordering of test cases
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/118#discussion_r1375267356" expanded>

Nice formatting
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/118#discussion_r1375267571" expanded>

Remember to check for when description is "" exception
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/118#discussion_r1375267643" expanded>

What is meant by cahsflow without category
</panel>

<panel  header="**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/118#discussion_r1375267847" expanded>

Looks a little messy. Might want to use java built in serialize
</panel>

<panel  header="**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/118#discussion_r1375267872" expanded>

Wow. Adding investments as well!
</panel>

<panel  header="**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/119#discussion_r1375268828" expanded>

Good clarification of our design consideration
</panel>

<panel  header="**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/119#discussion_r1375268935" expanded>

UserGuide looks very good!

Shall we add a table of contents?
</panel>

<panel  header="**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/119#discussion_r1375268967" expanded>

👍 
</panel>

<panel  header="**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/127#discussion_r1375420441" expanded>

Good use of constructor overloading
</panel>

<panel  header="**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/127#discussion_r1375420780" expanded>

What does this mean? Should I be removed
</panel>

<panel  header="**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/127#discussion_r1375421435" expanded>

"Detected erroneous cashflow entries. " maybe?
</panel>

<panel  header="**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/127#discussion_r1375422765" expanded>

wow. You manage to get the logic to work! Impreessisve
</panel>

<panel  header="**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/127#discussion_r1375424514" expanded>

Oh i see
</panel>

<panel  header="**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/129#discussion_r1375925356" expanded>

Looks good
</panel>

<panel  header="**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/129#discussion_r1375925621" expanded>

Thanks for this
</panel>

<panel  header="**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/129#discussion_r1375925908" expanded>

Wow! very comprehensive
</panel>

<panel  header="**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/129#discussion_r1375927171" expanded>

👍 
</panel>

<panel  header="**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/131#discussion_r1377533110" expanded>

Nice
</panel>

<panel  header="**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/131#discussion_r1377536134" expanded>

I dont think javadocs for getters and setters are necessary :(((
</panel>

<panel  header="**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/131#discussion_r1377536484" expanded>

Very good comments 💯 
</panel>

<panel  header="**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/131#discussion_r1377536870" expanded>

👍 
</panel>

<panel  header="**33 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/132#discussion_r1377540147" expanded>

Nice addition
</panel>

<panel  header="**34 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/135#discussion_r1378384360" expanded>

obtained from the system (?)
</panel>

<panel  header="**35 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/135#discussion_r1378385272" expanded>

This can be phrased better i think
</panel>

<panel  header="**36 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/135#discussion_r1378386716" expanded>

Is there suppose to be a dependency on the enum?
</panel>

<panel  header="**37 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/135#discussion_r1378387524" expanded>

array list naming convention probably tempCashflows 
</panel>

<panel  header="**38 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/135#discussion_r1378533610" expanded>

tempCashflowList -&gt; tempCashflows
</panel>

<panel  header="**39 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/191#discussion_r1382403807" expanded>

Thanks for clarifying
</panel>

<panel  header="**40 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/191#discussion_r1382404173" expanded>

Thanks for adding the correct link
</panel>

<panel  header="**41 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/191#discussion_r1382404374" expanded>

Good use of notes
</panel>

<panel  header="**42 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/191#discussion_r1382405060" expanded>

👍 
</panel>

<panel  header="**43 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/191#discussion_r1382405158" expanded>

Nice Cyan
</panel>

<panel  header="**44 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/192#discussion_r1382406111" expanded>

Sounds weird maybe 
Total Balance, Income balance, and Expense balance are different entities where the latter two do not have the same limitations
</panel>

<panel  header="**45 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/192#discussion_r1382406247" expanded>

Looks neater!
</panel>

<panel  header="**46 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/192#discussion_r1382406511" expanded>

Should tell the user to re-add another expense as this expense would not be recorded 
</panel>

<panel  header="**47 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/192#discussion_r1382406539" expanded>

Same for this
</panel>

<panel  header="**48 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/192#discussion_r1382406573" expanded>

Trim in raw command?
</panel>

<panel  header="**49 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/192#discussion_r1382407125" expanded>

Tell the user to re enter maybe
</panel>

<panel  header="**50 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/196#discussion_r1385281539" expanded>

Thanks!
</panel>

<panel  header="**51 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/196#discussion_r1385282057" expanded>

Nice however the colours are a little too bright
</panel>

<panel  header="**52 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/196#discussion_r1385282971" expanded>

Do you want to add our important classes such as cashflowlist?
</panel>

<panel  header="**53 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/196#discussion_r1385283173" expanded>

Thankyou!
</panel>

<panel  header="**54 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/194#discussion_r1385290920" expanded>

Wow upz
</panel>

<panel  header="**55 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/194#discussion_r1385291271" expanded>

Nice testing
</panel>

<panel  header="**56 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/201#discussion_r1389337032" expanded>

Thanks!
</panel>

<panel  header="**57 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/201#discussion_r1389337188" expanded>

Nice!
</panel>

<panel  header="**58 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/202#discussion_r1389337828" expanded>

Upz
</panel>

<panel  header="**59 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/202#discussion_r1389337997" expanded>

Nice!
</panel>

<panel  header="**60 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/210#discussion_r1390342056" expanded>

Nice 👍 
</panel>

<panel  header="**61 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/210#discussion_r1390342157" expanded>

Good clarity 👍 
</panel>

<panel  header="**62 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/210#discussion_r1390342486" expanded>

👍 
</panel>

<panel  header="**63 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/209#discussion_r1390342702" expanded>

Nice Clarity 👍 
</panel>

<panel  header="**64 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/209#discussion_r1390342887" expanded>

👍 
</panel>

<panel  header="**65 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/209#discussion_r1390343086" expanded>

Nice testing
</panel>

<panel  header="**66 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/213#discussion_r1390406430" expanded>

Very nice. I will do this as well
</panel>

<panel  header="**67 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/213#discussion_r1390428780" expanded>

Please hellp me change my header
</panel>

<panel  header="**68 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/215#discussion_r1390434748" expanded>

LeGoat 
</panel>

<panel  header="**69 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/215#discussion_r1390434911" expanded>

what is ...
</panel>

<panel  header="**70 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/215#discussion_r1390435171" expanded>

Nice
</panel>

<panel  header="**71 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/216#discussion_r1390850100" expanded>

Nice
</panel>

<panel  header="**72 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/216#discussion_r1390850243" expanded>

Thanks
</panel>

<panel  header="**73 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/221#discussion_r1391209648" expanded>

curry >
</panel>

<panel  header="**74 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/223#discussion_r1391263747" expanded>

good
</panel>

<panel  header="**75 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/115#discussion_r1374167167" expanded>

where got space stop farming comments
</panel>

<panel  header="**76 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/122#discussion_r1375358441" expanded>

Do you mean that I should not include the methods etc.?
</panel>

<panel  header="**77 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/122#discussion_r1375365495" expanded>

No wayyyy
</panel>

<panel  header="**78 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/124#discussion_r1375386824" expanded>

thanks for seeing my mistakes!
</panel>

<panel  header="**79 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/124#discussion_r1375386837" expanded>

NP
</panel>

<panel  header="**80 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/124#discussion_r1375386884" expanded>

yes it should be included in the output already
</panel>

<panel  header="**81 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/124#discussion_r1375386892" expanded>

Thank you!
</panel>

<panel  header="**82 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/125#discussion_r1375423550" expanded>

The saved file might be meddled with
</panel>

<panel  header="**83 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/130#discussion_r1377089667" expanded>

Remove Liao i thought
</panel>

<panel  header="**84 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/207#discussion_r1390184355" expanded>

doesnt work on terminal
</panel>

<panel  header="**85 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/214#discussion_r1390422906" expanded>

help me change i merge liao
</panel>

<panel  header="**86 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/33#issuecomment-1752434653" expanded>

Gonna merge
</panel>

<panel  header="**87 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/70#issuecomment-1763440272" expanded>

LGTM
</panel>

<panel  header="**88 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/41#issuecomment-1763873827" expanded>

done in #70 
</panel>

<panel  header="**89 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/105#issuecomment-1778455224" expanded>

fixed by #108 
</panel>

<panel  header="**90 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/81#issuecomment-1784026263" expanded>

Need to check for empty income and expenses 
</panel>

<panel  header="**91 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/36#issuecomment-1784026426" expanded>

Need to check for errors in request. Requesting errors (404, not array returned, empty request, API limit). File corruption
</panel>

<panel  header="**92 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/36#issuecomment-1784158122" expanded>

Need to check for corrupted file (option to fix it)
</panel>

<panel  header="**93 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/170#issuecomment-1793445452" expanded>

Cant

</panel>

</panel>


<panel type="info" header="### 7. LEOW.. JIE `@kaijie0102` (54 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/18#discussion_r1361421961" expanded>

Did you modify toString() of Recipe class as well?
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/19#discussion_r1361632991" expanded>

maybe spelling out in full would be clearer? some might misinterpret as "quality"
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/19#discussion_r1361635583" expanded>

should quantity be int instead?
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/19#discussion_r1361637322" expanded>

should parameter be Ingredient object instead? 
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/21#discussion_r1361814962" expanded>

I like your name for the test. It is very clear and informative
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/21#discussion_r1361817106" expanded>

I think your code is really neat and clean
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/44#discussion_r1365172899" expanded>

is the isExit attribute the best way to end a function? Should we just check if the command is "bye" instead?
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/44#discussion_r1365175516" expanded>

perhaps we could remove the word "currently"?
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/44#discussion_r1365176485" expanded>

I like how you solved the "output message when the program ends"
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/44#discussion_r1365179193" expanded>

i feel like the isExit is an overly complicated way to check if we should end the program
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/44#discussion_r1365180096" expanded>

thanks for adding in the logs part!
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/44#discussion_r1365182009" expanded>

i like how clean it is!
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/44#discussion_r1365183015" expanded>

is this still necessary? i notice you removed this part from the AddRecipeCommand as well
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/42#discussion_r1365200868" expanded>

i like how you change all the methods to static to prevent unnecessary creation of Ui object
</panel>

<panel  header="**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/42#discussion_r1365201513" expanded>

i like this method. very clean
</panel>

<panel  header="**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/63#discussion_r1372609237" expanded>

is & the same as &&? I think logical & and not bitwise wise & should be used
</panel>

<panel  header="**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/63#discussion_r1372609794" expanded>

I like the use of constant here
</panel>

<panel  header="**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/63#discussion_r1372610180" expanded>

looks exactly like what we discussed. good job!
</panel>

<panel  header="**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/74#discussion_r1373147640" expanded>

does id mean index + 1? I think might be better to have all as "index"
</panel>

<panel  header="**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/74#discussion_r1373148432" expanded>

I like that it is clean way to check if they are deleting by name or index
</panel>

<panel  header="**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/73#discussion_r1373189495" expanded>

i like that this section is very clean
</panel>

<panel  header="**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/73#discussion_r1373190473" expanded>

i like how the names are intuitive for readers
</panel>

<panel  header="**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/103#discussion_r1377719005" expanded>

i like that you gave examples

</panel>

<panel  header="**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/103#discussion_r1377719950" expanded>

i like the new format
</panel>

<panel  header="**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/102#discussion_r1377722664" expanded>

i like how clean your code is
</panel>

<panel  header="**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/102#discussion_r1377724395" expanded>

I like how intuitive your variable names are
</panel>

<panel  header="**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/102#discussion_r1377726353" expanded>

i like how you took into account ingredients of same name but different qty
</panel>

<panel  header="**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/102#discussion_r1377727283" expanded>

can it be a constant? 

final String ZERO = "0"
</panel>

<panel  header="**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/118#discussion_r1381081077" expanded>

i like how you changed to a "positive" tone
</panel>

<panel  header="**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/118#discussion_r1381083022" expanded>

listing out the tags was great, made it more intuitive for users
</panel>

<panel  header="**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/127#discussion_r1384230867" expanded>

I like how you added a copy to indicate a duplicate
</panel>

<panel  header="**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/127#discussion_r1384232268" expanded>

should this be in the DuplicateRecipeCommand test?
</panel>

<panel  header="**33 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/212#discussion_r1384703288" expanded>

i like the overriding of equals, very useful
</panel>

<panel  header="**34 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/212#discussion_r1384703562" expanded>

same here, i like the equals overriding
</panel>

<panel  header="**35 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/212#discussion_r1384704068" expanded>

great that you only print message when needed
</panel>

<panel  header="**36 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/214#discussion_r1384776196" expanded>

great that now data is saved after every command!
</panel>

<panel  header="**37 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/227#discussion_r1387922523" expanded>

I like how you checked that units are the same here
</panel>

<panel  header="**38 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/227#discussion_r1387923491" expanded>

consider changing to `catch(EssenFormatException | EssenOutOfRangeException e)`
</panel>

<panel  header="**39 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/227#discussion_r1387925981" expanded>

since u have the "if" guard clause that throws and error, line 56 might not need to be in `else`?
</panel>

<panel  header="**40 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/238#discussion_r1388819395" expanded>

i like that its very clear!
</panel>

<panel  header="**41 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/242#discussion_r1389196225" expanded>

great use of assertions among others
</panel>

<panel  header="**42 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/242#discussion_r1389196474" expanded>

I like the newer, more intuitive naming!
</panel>

<panel  header="**43 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/242#discussion_r1389197103" expanded>

tests look good
</panel>

<panel  header="**44 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/247#discussion_r1389369584" expanded>

l like how you combined the test cases
</panel>

<panel  header="**45 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/245#discussion_r1389379681" expanded>

Thanks for making the name more intuitive!
</panel>

<panel  header="**46 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/249#discussion_r1389602726" expanded>

should this be `exception.handleException`? 
if yes, then maybe can combine with the `EssenShortcutException` branch
</panel>

<panel  header="**47 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/249#discussion_r1389604795" expanded>

would combining all the exceptions into one branch be neater? 
`EssenOutOfRange | EssenShortcut | EssenFormat e`
</panel>

<panel  header="**48 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/249#discussion_r1389605246" expanded>

super neat, i really like the use of abstraction here

</panel>

<panel  header="**49 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/249#discussion_r1389605798" expanded>

very neat guard clauses
</panel>

<panel  header="**50 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/252#discussion_r1390318883" expanded>

great way to handle exceptions! i like it

</panel>

<panel  header="**51 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/252#discussion_r1390318987" expanded>

would it be safer to check if ingredientQuantity is parsable? Perhaps in a try catch `NumberFormatException`
</panel>

<panel  header="**52 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/252#discussion_r1390319022" expanded>

should we be keeping the exceptions to our Essen exceptions only?
</panel>

<panel  header="**53 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/279#discussion_r1391942468" expanded>

I like your explanations here!
</panel>

<panel  header="**54 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/279#discussion_r1391942741" expanded>

I like how you split up our user stories into the different versions
</panel>

<panel  header="**55 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/228#discussion_r1387952639" expanded>

good point
</panel>

<panel  header="**56 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/228#discussion_r1387955887" expanded>

ok will remove
</panel>

<panel  header="**57 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/250#discussion_r1390315600" expanded>

yes, i uncommented it in the next iteration
</panel>

<panel  header="**58 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/250#discussion_r1390316148" expanded>

will do so after functional codes are done
</panel>

<panel  header="**59 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/18#issuecomment-1765531584" expanded>

LGTM
</panel>

<panel  header="**60 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/29#issuecomment-1767809178" expanded>

please hold and do not approve while i fix the bug

</panel>

<panel  header="**61 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/186#issuecomment-1797126525" expanded>

Command not in documentation, he might be referring to "help" command
</panel>

<panel  header="**62 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/197#issuecomment-1797127513" expanded>

should be able to close with #210 
</panel>

<panel  header="**63 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/185#issuecomment-1797129218" expanded>

same issue as #193 
</panel>

<panel  header="**64 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/177#issuecomment-1797135074" expanded>

same issue as #192 
</panel>

<panel  header="**65 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/205#issuecomment-1797878446" expanded>

Fixed by #211
</panel>

<panel  header="**66 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/201#issuecomment-1797881122" expanded>

Same as #211 
</panel>

<panel  header="**67 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/196#issuecomment-1797884066" expanded>

Require new line 
</panel>

<panel  header="**68 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/194#issuecomment-1797886735" expanded>

User required to add ingredients to inventory, not just to recipe
</panel>

<panel  header="**69 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/192#issuecomment-1797888262" expanded>

Same as #210
</panel>

<panel  header="**70 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/183#issuecomment-1797894625" expanded>

Fixed by #108 
</panel>

<panel  header="**71 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/178#issuecomment-1797900366" expanded>

Generic error handling
</panel>

<panel  header="**72 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/172#issuecomment-1797903342" expanded>

Get rid of this
</panel>

<panel  header="**73 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/167#issuecomment-1797909158" expanded>

Will be fixed by #195 
</panel>

<panel  header="**74 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/163#issuecomment-1797910836" expanded>

Closes with #174 
</panel>

<panel  header="**75 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/160#issuecomment-1797913040" expanded>

Fixed by #174 
</panel>

<panel  header="**76 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/156#issuecomment-1797917701" expanded>

Closes #127 
</panel>

<panel  header="**77 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/155#issuecomment-1797919315" expanded>

Fixed by #174 
</panel>

<panel  header="**78 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/154#issuecomment-1797920380" expanded>

Fixed by #173 
</panel>

<panel  header="**79 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/153#issuecomment-1797920732" expanded>

Fixed by #173 
</panel>

<panel  header="**80 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/152#issuecomment-1797920939" expanded>

Fixed by #174 
</panel>

<panel  header="**81 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/150#issuecomment-1797923286" expanded>

Closed by #173 
</panel>

<panel  header="**82 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/149#issuecomment-1797924053" expanded>

Closed by #158 
</panel>

<panel  header="**83 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/146#issuecomment-1797927078" expanded>

Closes with #158 
</panel>

<panel  header="**84 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/145#issuecomment-1797927396" expanded>

Closes by #158 
</panel>

<panel  header="**85 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/142#issuecomment-1797929424" expanded>

Fixed by #123 
</panel>

<panel  header="**86 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/138#issuecomment-1797931021" expanded>

Fixed by #148 
</panel>

<panel  header="**87 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/133#issuecomment-1797933452" expanded>

Not sure how to replicate 
</panel>

<panel  header="**88 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/131#issuecomment-1797934280" expanded>

Fixed by #137 
</panel>

<panel  header="**89 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/128#issuecomment-1797936747" expanded>

Fixed by #151 
</panel>

<panel  header="**90 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/207#issuecomment-1798276465" expanded>

fixed by #213 
</panel>

<panel  header="**91 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/208#issuecomment-1798277496" expanded>

fixed by #213 

</panel>

<panel  header="**92 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/206#issuecomment-1798278269" expanded>

fixed by #213 

</panel>

<panel  header="**93 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/191#issuecomment-1798280900" expanded>

will be fixed by #174 
</panel>

<panel  header="**94 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/119#issuecomment-1798281766" expanded>

same as #174 

</panel>

<panel  header="**95 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/108#issuecomment-1798282665" expanded>

fixed by #213 

</panel>

<panel  header="**96 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/123#issuecomment-1798283529" expanded>

fixed by #213 
</panel>

<panel  header="**97 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/193#issuecomment-1798321538" expanded>

fixed by #158 

</panel>

<panel  header="**98 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/217#issuecomment-1798353772" expanded>

Special PR
</panel>

<panel  header="**99 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/211#issuecomment-1803406011" expanded>

fixed by #226 
</panel>

<panel  header="**100 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/99#issuecomment-1805568688" expanded>

fixed
</panel>

<panel  header="**101 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/246#issuecomment-1806641611" expanded>

fixed
</panel>

<panel  header="**102 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/224#issuecomment-1807156995" expanded>

fixed by #250 
</panel>

<panel  header="**103 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/257#issuecomment-1807428175" expanded>

closed by #263 
</panel>

<panel  header="**104 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/135#issuecomment-1807428432" expanded>

closed by #259 

</panel>

<panel  header="**105 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/175#issuecomment-1808144886" expanded>

fixed
</panel>

<panel  header="**106 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/151#issuecomment-1808150602" expanded>

fixed
</panel>

<panel  header="**107 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/221#issuecomment-1808159492" expanded>

fixed
</panel>

<panel  header="**108 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/223#issuecomment-1808160505" expanded>

fixed
</panel>

<panel  header="**109 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/253#issuecomment-1809527919" expanded>

Redundant feature
</panel>

<panel  header="**110 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/222#issuecomment-1809528072" expanded>

fixed
</panel>

<panel  header="**111 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/126#issuecomment-1809528425" expanded>

Addressed
</panel>

</panel>


<panel type="info" header="### 8. NG Z..I YI `@ziyi105` (47 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/40#discussion_r1360142869" expanded>

Is this intended?
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/57#discussion_r1362172457" expanded>

Perhaps you should avoid using instanceof?
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/57#discussion_r1362175853" expanded>

Maybe you can have one empty line here to make a distinction between attributes and method
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/58#discussion_r1362351824" expanded>

Perhaps you can return an error here? Or you could catch index out of bound exception and print out the showDeleteMessage. If I understand it correctly, the final menu.removeDish(index) statement will still be executed even if the index is invalid
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/95#discussion_r1367918280" expanded>

Perhaps this should be in Parser class instead for better cohesion?
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/95#discussion_r1367918316" expanded>

Perhaps this should be in Parser class instead for better cohesion?
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/95#discussion_r1367920604" expanded>

Since the main purpose of this method is to check whether the ingredient exists or not, perhaps you could create a different method called checkIngredientExists()

In your addIngredientToStock(), maybe you could do something like checkIngredientExist() ? updateIngredientQty() : create new ingredient and update the quantity




</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/95#discussion_r1367920942" expanded>

Perhaps you could modify this method to replace addIngredientToStock() as per my comment above?
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/95#discussion_r1367921952" expanded>

Perhaps you could use the setQuantity() method in Ingredient class to update the quantity?
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/95#discussion_r1367922274" expanded>

Perhaps we should standardise the attribute name to be quantity instead of qty?
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/95#discussion_r1367922860" expanded>

Perhaps you could rename this to addQuantity() for better clarification on whether this method increases or decreases the stock?
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/96#discussion_r1367926137" expanded>

Is there any reason why you create a new ui instance instead of using the ui from Main?
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/96#discussion_r1367927263" expanded>

Perhaps you can rename it to getNumOfCookableDish() for better clarity?
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/96#discussion_r1367927853" expanded>

Perhaps you could extract the part related to ui in this method and create a method in ui class
</panel>

<panel  header="**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/96#discussion_r1367928915" expanded>

Perhaps this should be in Ui as it deals with user interface? 

checkDishAvailability() could lead the developers to think that it will return a boolean
</panel>

<panel  header="**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/96#discussion_r1367929126" expanded>

Perhaps there is a better way to name this method? same reason as above
</panel>

<panel  header="**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/103#discussion_r1368481112" expanded>

Perhaps you could make it return the modified ingredients as it would be useful for JUnit test and debugging in the future
</panel>

<panel  header="**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/95#discussion_r1368761150" expanded>

Perhaps renaming it to addIngredientQuantity for better clarity
</panel>

<panel  header="**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/95#discussion_r1368764180" expanded>

Perhaps you should follow this format for single line comment?
</panel>

<panel  header="**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/95#discussion_r1368767043" expanded>

very clear now! Good Job :)

Perhaps in the next version you could add error handling for invalid index, but we can keep it like this for now!
</panel>

<panel  header="**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/95#discussion_r1368768580" expanded>

Perhaps you should follow the indentation format you used in line 68
</panel>

<panel  header="**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/106#discussion_r1369473405" expanded>

Perhaps adding empty lines between methods?
</panel>

<panel  header="**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/106#discussion_r1369473706" expanded>

Perhaps add string constant to avoid magic string?
</panel>

<panel  header="**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/106#discussion_r1369473965" expanded>

is this for debugging?
</panel>

<panel  header="**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/106#discussion_r1369475261" expanded>

Perhaps you can move this method to Menu? This method seems more like menu's responsibility rather than parser's
</panel>

<panel  header="**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/106#discussion_r1369476069" expanded>

Perhaps you should just pass the order to Order class and let the chef handle this as it would be more cohesive
</panel>

<panel  header="**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/106#discussion_r1369476505" expanded>

Perhaps you should let order class handle this instead?
</panel>

<panel  header="**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/106#discussion_r1369477531" expanded>

Perhaps you could simply pass in Order(dishName, dishQty) and let Order class calculate / retrieve the usedIngerdientList and totalOrderCost as they seem to be more of Order's responsibility rather than parser's? 
</panel>

<panel  header="**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/131#discussion_r1374296405" expanded>

Is there a string constant for this in the Message class? If yes, perhaps you could just use it to avoid magic stirng
</panel>

<panel  header="**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/153#discussion_r1375587408" expanded>

Perhaps remove the extra line
</panel>

<panel  header="**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/167#discussion_r1376964852" expanded>

Is there any reason why you underlined scanner since it is not a static method?
</panel>

<panel  header="**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/167#discussion_r1376965634" expanded>

Perhaps you can add explanation about the association. E.g., CafeCtrl executes Command
</panel>

<panel  header="**33 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/170#discussion_r1376975827" expanded>

perhaps you could remove the comment
</panel>

<panel  header="**34 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/175#discussion_r1377040528" expanded>

Perhaps when you move someone else's code you should help them add author tag also
</panel>

<panel  header="**35 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/175#discussion_r1377041508" expanded>

Dont you have offset value stored as a constant in Ui?
</panel>

<panel  header="**36 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/175#discussion_r1377043138" expanded>

Where is index param used in this method? Is it is not used, perhaps you could remove the param

</panel>

<panel  header="**37 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/175#discussion_r1377044209" expanded>

Is there any reason why you call this method here? It doesnt return or modify anything hence i am not sure what it the purpose of calling it (correct me if i am wrong).
</panel>

<panel  header="**38 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/175#discussion_r1377044650" expanded>

Perhaps you should format it according to coding standard
</panel>

<panel  header="**39 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/167#discussion_r1377099924" expanded>

hmm CafeCtrl calls execute() in command class, so we can explain their association as CafeCtrl executes Command, and maybe you can add execute beside the arrow pointing from CafeCtrl to Command?

</panel>

<panel  header="**40 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/181#discussion_r1377925201" expanded>

Below is just my own opinion, take it as a grain of salt cuz i am not very good at uml also haha.
Personally I think we can omit some private/irrelevant methods in class diagram to make the whole diagram more simplified and easy to understand. In your diagram, for example, I think you can leave out the private methods in Storage class such as saveMenu, savePantry and saveOrder since they are all under saveAll.
</panel>

<panel  header="**41 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/192#discussion_r1378702067" expanded>

Perhaps you should let Parser.java implement the method instead. By doing so, it would be more convenient for us to do testing for other classes that depend on Parser.java as we can simply implement a dummy parsePricetoFloat method that will return a fixed value that is always correct. With this dummy method, we can make sure that the test result is independent of the implementation of parser class.
</panel>

<panel  header="**42 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/192#discussion_r1378702668" expanded>

same as above, you could specify the method here but perhaps implement it in the child class
</panel>

<panel  header="**43 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/192#discussion_r1378709518" expanded>

Maybe you should move this testing methods back to ParserTest.java
</panel>

<panel  header="**44 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/343#discussion_r1390518005" expanded>

Perhaps in step 3 you could provide more info by using dishName:String?
</panel>

<panel  header="**45 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/343#discussion_r1390518274" expanded>

is there any reason why there is a ":" before dishIngredients in step 5? 
</panel>

<panel  header="**46 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/343#discussion_r1390518760" expanded>

is there any reason why there is ":" before usedIngredientFromStock in step 9
</panel>

<panel  header="**47 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/343#discussion_r1390520037" expanded>

Perhaps you should use the primitive "boolean" instead of "Boolean" here?
</panel>

<panel  header="**48 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/98#discussion_r1368212935" expanded>

This is title of the section, all the methods under this section are related to preparing command
</panel>

<panel  header="**49 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/113#discussion_r1371004588" expanded>

Is it necessary to include so all the details tho? I feel that it would confuse the reader
</panel>

<panel  header="**50 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/143#discussion_r1375270560" expanded>

I am planning to implement it in the next PR (cuz I no time to do it yet) so that you all can use the skeleton file to implement your encoding and decoding while waiting for my next PR
</panel>

<panel  header="**51 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/143#discussion_r1375270578" expanded>

Okies
</panel>

<panel  header="**52 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/143#discussion_r1375270730" expanded>

or do you think i should just implement it first? I can do it by tmr night
</panel>

<panel  header="**53 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/219#discussion_r1382519049" expanded>

I implemented the round up feature in dish feature, so no matter how many dps are provided by the user the app will automatically update to 2dp
</panel>

<panel  header="**54 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/313#discussion_r1390080440" expanded>

it is used when i call assertEquals to compare two lists of ingredients! Java will use this overridden method to compare the ingredient object instead of the original equals method from the Object class which only compares the reference of the object.
</panel>

<panel  header="**55 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/345#discussion_r1390688991" expanded>

I will delete this line in my latest PR!
</panel>

<panel  header="**56 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/113#issuecomment-1778340586" expanded>

> Perhaps the UMLs should be changed after the implementation of PR #110



> Perhaps the UMLs should be changed after the implementation of PR #110

May I know which part of the UML you're referring to?

</panel>

<panel  header="**57 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/253#issuecomment-1793505187" expanded>

@DextheChik3n  Should we remove `The PRICE must be a positive 2 decimal place number.` from the UG and simply mention that any price value with more than 2 dp will be rounded up?
</panel>

<panel  header="**58 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/231#issuecomment-1793509974" expanded>

#251  similar bug @DextheChik3n 
</panel>

<panel  header="**59 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/224#issuecomment-1793510543" expanded>

@AY2324S1-CS2113-T17-2/developers  our app doesnt allow anything other than ml or g right? If so we can close this bug
</panel>

<panel  header="**60 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/253#issuecomment-1794414398" expanded>

I will edit my edit_price to only accept 2 dp instead of rounding up as price should only have two dp 
</panel>

<panel  header="**61 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/268#issuecomment-1797932580" expanded>

Somehow it's working now
</panel>

<panel  header="**62 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/328#issuecomment-1807054562" expanded>

orders and menu files are completely empty
</panel>

<panel  header="**63 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/328#issuecomment-1807054818" expanded>

![image](https://github.com/AY2324S1-CS2113-T17-2/tp/assets/82555990/8f7d4917-b7e0-4bb9-a868-54859635c688)
existing means the file has been created, empty means there is nothing in the file
</panel>

<panel  header="**64 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/323#issuecomment-1807382950" expanded>

I see, I will modify my error message accordingly, thanks!
</panel>

<panel  header="**65 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/349#issuecomment-1807444066" expanded>

Thanks for the clarification!
</panel>

<panel  header="**66 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/346#issuecomment-1807483990" expanded>

![image](https://github.com/AY2324S1-CS2113-T17-2/tp/assets/82555990/349920ce-fecf-45ce-bd5b-a5bf18a55292)

My conversation with @Cazh1 
I will help @NaychiMin  and @ShaniceTang  add a new line after the error msg for decoder
</panel>

<panel  header="**67 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/346#issuecomment-1807535601" expanded>

ohh that's a good idea, thanks Shanice!
</panel>

<panel  header="**68 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/376#issuecomment-1808246453" expanded>

Ohh I meant the "Available Dishes: 8", maybe changing it to "Number of Available Dishes Left: 8" would be more informative?
</panel>

<panel  header="**69 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/366#issuecomment-1808278677" expanded>

will fix this in my latest PR, thanks for bring this up!
</panel>

<panel  header="**70 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/379#issuecomment-1808297752" expanded>

The hash string is being decoded as a normal data text now. Do you think this can be counted as a bug? Or we can argue that since they edited the text file using the wrong format the app cannot differentiate which one is hash string which one is data alr
</panel>

<panel  header="**71 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/379#issuecomment-1808351505" expanded>

Thanks for your input, i guess can't do anything about it now since we dont have much time left. I will just add this under UG known issues
</panel>

</panel>


<panel type="info" header="### 9. TONG..HONG `@TongZhengHong` (47 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/68#discussion_r1371144437" expanded>

`ShowMoveCommand` objects should be executed during the `execute` method. 
The `execute` method in Command has the current `board` object so you can use that to call the `showAvailableMoves` method. 
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/68#discussion_r1371144854" expanded>

This is not needed since all execution of showMoveCommand is done in the command class itself
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/68#discussion_r1371146245" expanded>

Minor change for readability, cast `row[j].toStringAvailable()` into another variable
```java
String validMoveString = row[j].toStringAvailable()
rowString.append(validMoveString)
```
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/68#discussion_r1371147648" expanded>

This can be removed as well
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/68#discussion_r1371147701" expanded>

Consider changing this name to maybe: `toStringAvailableDest`
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/68#discussion_r1371149389" expanded>

- Execute `board.showAvailableMoves` here. So the board with available moves will show first before the return text
- Can have a line saying the type of piece the user is planning to move 
    - e.g. `You are moving Queen at a8. Here are the available moves: `
- Would be a good idea to tell the user the coordinates one can go to in text form
    - e.g. `a2, a3, b4, b5, b6...`
- You can pass in `String[]` into `CommandResult` for multi-line texts and each entry in the array will be printed on a new line
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/68#discussion_r1371350959" expanded>

Return the list of available coordinates together with CommandResult by adding the results of `displayAvailableCoordinates` to `displayString`

```java
pieceCoordinateStrings = piece.displayAvailableCoordinates(board);
String[] displayStrings = {
    String.format(SHOW_MOVE_MESSAGE, ...),
    pieceCoordinateStrings
}
return new CommandResult(displayStrings);
```
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/85#discussion_r1373740623" expanded>

Nice diagram!
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/85#discussion_r1373741400" expanded>

Good use of additional note and XYZ command
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/91#discussion_r1375642116" expanded>

Consider creating an instance of `HelpCommand` and executing it instead of duplicating the help messages.
```java
HelpCommand startingHelp = new HelpCommand();
startingHelp.execute(board);
```
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/91#discussion_r1375642422" expanded>

No need to test for IO redirection moving forward since it is removed from CI checks! :)
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/91#discussion_r1376528575" expanded>

Will ignore this since HelpCommand prints "looks like you need help" at the start
- Moving forward, will abstract out help messages to manage repeated strings
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/93#discussion_r1377130054" expanded>

Can consider making `maxDepth` a final static variable in `MiniMax` class
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/93#discussion_r1377131031" expanded>

Can consider making use of the `isOffsetWithinBoard` method in the `Coordinate` class to check for boundary
</panel>

<panel  header="**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/93#discussion_r1377132096" expanded>

Can consider making use of the `addOffsetToCoordinate` method in the `Coordinate` class to apply offset with boundary checking
</panel>

<panel  header="**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/104#discussion_r1379686406" expanded>

Should use the ChessPiece children classes' static variables for the exact representation. e.g.
```java
String.format("\"%s\" represents a white rook.", Rook.ROOK_WHITE);
```
</panel>

<panel  header="**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/104#discussion_r1379688508" expanded>

We should put all the game-related settings on 1 line separated by a delimiter in future.
`PlayerColor | Difficulty | Turn`
But not needed in this PR, for future updates
</panel>

<panel  header="**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/104#discussion_r1379689523" expanded>

Can consider using the ChessPiece children classes' static variables for the exact representation here as well. 
</panel>

<panel  header="**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/104#discussion_r1379693371" expanded>

Is `LegendCommand` and `LEGEND_COMMAND_STRING` a better name to keep it short? 
</panel>

<panel  header="**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/111#discussion_r1379997883" expanded>

Would be good to extract this out to another function in this class for readability
e.g. `checkValidPieces`
</panel>

<panel  header="**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/111#discussion_r1380000492" expanded>

Consider having a boolean variable to explain what this check is. 
```java
boolean bothKingsPresent = isBlackKingPresent && isWhiteKingPresent;
if (!bothKingsPresent) {
    ... 
```
</panel>

<panel  header="**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/111#discussion_r1380001436" expanded>

Consider renaming the variables for readability:
- `blackPieceNum`, `whitePieceNum`
- `isBlackKingPresent`, `isWhiteKingPresent`
</panel>

<panel  header="**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/112#discussion_r1380279507" expanded>

Use method `parsePlayerColor` method to convert from string to Color object
```java
Color playerColor = Parser.parsePlayerColor(currentColorString);
```
</panel>

<panel  header="**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/112#discussion_r1380287793" expanded>

Use the enum conversion here. 
```java
fileWriter.write(currentColor.name());
```
</panel>

<panel  header="**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/112#discussion_r1380290260" expanded>

Might consider using `currentTurnColor` instead
</panel>

<panel  header="**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/112#discussion_r1380305481" expanded>

I just realised that if the color was editted to EMPTY, there would be an error in the game so we got to include a check for empty color in `parsePlayerColor` method. (Since the a player color can never be empty)
1. In Color.java, create a `isEmpty` method
2. Check that the converted color is not empty:
```java
try {
    Color color = Color.valueOf(inputColorString);
    if (color.isEmpty()) {
        throws new ParseColorException();
    }
    return color;
} catch (IllegalArgumentException e) {
    throw new ParseColorException();
}
```
</panel>

<panel  header="**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/155#discussion_r1383028956" expanded>

Looks like this method is not referenced anywhere... help double confirm and delete if so
</panel>

<panel  header="**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/155#discussion_r1383035122" expanded>

Make sure text wraps before the end of the divider length
</panel>

<panel  header="**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/155#discussion_r1383035446" expanded>

Make texts wrap before end of divider
</panel>

<panel  header="**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/155#discussion_r1383038448" expanded>

Add empty line between each item for clarity (Ensure that they are on separate lines in preview)

ALSO help me delete the extra empty line at **line 72**
</panel>

<panel  header="**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/158#discussion_r1385369472" expanded>

Can try overwriting the `equals` method?
</panel>

<panel  header="**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/158#discussion_r1385380981" expanded>

Might want to make 'p' a public static final variable to be only declared once
e.g. `PROMOTE_MOVE_STRING`
</panel>

<panel  header="**33 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/158#discussion_r1385382861" expanded>

Is this the same as `parseMove` without the `MoveOpponentPieceException` check?
If so, we can just use the normal parseMove
</panel>

<panel  header="**34 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/158#discussion_r1385386230" expanded>

Remove unused `otherPos` variable
</panel>

<panel  header="**35 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/158#discussion_r1385391579" expanded>

Would be good to declare the public static final moves delimiter variable once to prevent any future errors 
e.g. `MOVES_DELIMITER`
</panel>

<panel  header="**36 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/158#discussion_r1385401928" expanded>

Change this delimiter to `\\s+` just in case the user changes the storage file to have multiple spaces
</panel>

<panel  header="**37 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/158#discussion_r1385408597" expanded>

Create the new board local to the `executeSavedMoves` function, not from the `ChessMaster` class. 

This is the same comment as the one in ChessMaster, just a reminder
</panel>

<panel  header="**38 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/158#discussion_r1385411289" expanded>

Should create the a new board to compare to in the `executeSavedMoves` function and let `existingBoard` (from storage) to be used for loading previous game
</panel>

<panel  header="**39 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/158#discussion_r1385413694" expanded>

Good idea using `PromoteMove` to handle promote!
</panel>

<panel  header="**40 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/164#discussion_r1387021715" expanded>

Please help me add a javadoc here and explicitly show what the boolean represents (just chatgpt)
</panel>

<panel  header="**41 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/164#discussion_r1387022536" expanded>

Help me rename the function to `isAbort` instead of `isAbortCommand`. Same for `isRestart` to keep things short and sweet
</panel>

<panel  header="**42 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/164#discussion_r1387025511" expanded>

Just return directly to keep the logic short
`return hasEnded || RestartCommand.isRestart(command);`
</panel>

<panel  header="**43 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/164#discussion_r1387025939" expanded>

Remove empty lines here
</panel>

<panel  header="**44 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/164#discussion_r1387029176" expanded>

Do a guard clause here for better control logic flow
```java
if (!restartMidGame) {
    shouldRestart = false;
    continue;
}
boolean shouldRestartGame = shouldRestartGame();
...
```
</panel>

<panel  header="**45 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/164#discussion_r1387033507" expanded>

I think you need to assign this to the `shouldRestart` variable right?
```java
if (restartMidGame) {
    shouldRestart = shouldRestartGame();
    if (shouldRestart) {
        loadNewGame();
    }
}
```

</panel>

<panel  header="**46 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/164#discussion_r1387511326" expanded>

Typo here `EXIT_COMMAND_STRING`
</panel>

<panel  header="**47 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/164#discussion_r1387513386" expanded>

Include what the `run` function does as well, something like this:
```java
/**
 * Manages the main gameplay loop of Chess Master.
 *
 * This code segment orchestrates the primary gameplay loop of Chess Master, which encompasses player turns, move handling, and the management of the game state. It starts by displaying the initial game setup, including the chessboard, and then enters a loop where players take turns making moves. If a player enters a valid move, the chessboard is updated, and the game progresses. If an exception is encountered during this process, an error message is displayed to the user. The loop continues until the game ends or specific commands are issued to abort, restart, or exit the game.
 *
 * @return true if the game has ended, either through checkmate or a specific command; false if the game is still ongoing.
 */
```
</panel>

<panel  header="**48 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/88#discussion_r1375409819" expanded>

I am not sure who did `parseCommand` so I'm ending the tag at `parseChessPiece`.
</panel>

<panel  header="**49 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/issues/77#issuecomment-1783746963" expanded>

Not needed since there are not many commands in the main menu other than loading the storage file and restarting the next game.
</panel>

<panel  header="**50 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/issues/132#issuecomment-1793470178" expanded>

- Duplicate of #119 
</panel>

<panel  header="**51 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/issues/135#issuecomment-1793470359" expanded>

- Duplicate of #120 
</panel>

<panel  header="**52 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/issues/121#issuecomment-1793470976" expanded>

- Duplicate of #122 
</panel>

<panel  header="**53 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/issues/128#issuecomment-1793471087" expanded>

- Duplicate of #122 
</panel>

<panel  header="**54 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/issues/126#issuecomment-1793472132" expanded>

- Duplicate of #133 
</panel>

<panel  header="**55 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/issues/123#issuecomment-1793481277" expanded>

- Duplicate of #140 
</panel>

<panel  header="**56 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/issues/139#issuecomment-1793484914" expanded>

- Duplicate of #144 
</panel>

</panel>


<panel type="info" header="### 10. PAPP..NIEL `@danielpappa` (36 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/33#discussion_r1361672394" expanded>

Maybe we could also consider the case where the user mistakenly starts off the input with a space as in " viewIncome"?
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/33#discussion_r1361678123" expanded>

I don't think we are allowed to use any slang, singlish or similar...
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/33#discussion_r1361679753" expanded>

Could parse() maybe throw a CashLehParsingException?
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/33#discussion_r1361688230" expanded>

Could maybe be handled more efficiently using streams.
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/33#discussion_r1361694254" expanded>

Could maybe define int expenseIndexToDelete = expenseIndex - 1;
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/33#discussion_r1361696712" expanded>

Could maybe define int incomeIndexToDelete = incomeIndex - 1;
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/33#discussion_r1361704496" expanded>

Could maybe show the amount first followed by the description and also add a "-" before the amount so that the user immediately sees that he/she is indeed shown the expenses.
e.g. "- $1,200: Monthly Rent for October"
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/33#discussion_r1361707036" expanded>

Could maybe show the amount first followed by the description and also add a "+" before the amount so that the user immediately sees that he/she is indeed shown the incomes.
e.g. "+ $2,500: Monthly Salary for October"
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/33#discussion_r1361708418" expanded>

Great idea of creating this abstract class! Allows for much cleaner code, more OOC and also more uniform code.
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/33#discussion_r1361710047" expanded>

Maybe in v2.0 we could also add currency, dates, type (enumeration containing e.g. salary, interest etc.) and whether the transaction is recurring or not
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/34#discussion_r1362349773" expanded>

Very good JUnit testing! Implements all necessary test cases so far for the parser class, well done!
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/34#discussion_r1362351170" expanded>

I think I already commented on this line in the Parser class, but I believe we should not use slang/singlish in our code's answers (even though that requirement could also only be interpreted as being limited to actual code and not string outputs...)
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/44#discussion_r1363837115" expanded>

Very nice way of handling input data!
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/44#discussion_r1363839210" expanded>

Very nice way of parsing input data!
</panel>

<panel  header="**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/44#discussion_r1363842260" expanded>

Should maybe avoid using singlish in output...
</panel>

<panel  header="**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/44#discussion_r1363846108" expanded>

Great idea!
</panel>

<panel  header="**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/32#discussion_r1365526062" expanded>

Great thinking and nice implementation.
</panel>

<panel  header="**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/32#discussion_r1365533421" expanded>

Great coding!
</panel>

<panel  header="**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/47#discussion_r1368822224" expanded>

Maybe could add education or travel
</panel>

<panel  header="**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/63#discussion_r1376327042" expanded>

Great implementation
</panel>

<panel  header="**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/62#discussion_r1376333858" expanded>

Good refactoring to avoid magic literals
</panel>

<panel  header="**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/64#discussion_r1376937649" expanded>

Is this a non-functional requirement?
</panel>

<panel  header="**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/64#discussion_r1376938744" expanded>

Think this is a typo: *reset password right?
</panel>

<panel  header="**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/64#discussion_r1376939956" expanded>

Think it should be /data/name.txt file instead of AddressBook home folder
</panel>

<panel  header="**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/64#discussion_r1376941211" expanded>

Great diagram, very intuitive and clean! Only thing I am wondering is, whether we could add an arrow from the parser to the package of Transaction overall or the Command class in the lower left corner
</panel>

<panel  header="**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/64#discussion_r1376942512" expanded>

Nice and intuitive diagram. Maybe we could remove the class boxes on the bottom as they are repetitive and it would make the diagram more neat and simple.
</panel>

<panel  header="**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/66#discussion_r1377180994" expanded>

Very nice and easy to read description 
</panel>

<panel  header="**28 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/66#discussion_r1377186873" expanded>

Shouldn't there be an alt box (switch statement) within the already present alt box for [transaction format is valid], to distinguish between transaction types (incomes and expenses)?
</panel>

<panel  header="**29 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/73#discussion_r1382320534" expanded>

Really improved the logic and the overall order of the code base.
</panel>

<panel  header="**30 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/108#discussion_r1382902720" expanded>

Maybe we could insert a line break before displaying the link, in order to increase its visibility and make it easier to copy.
</panel>

<panel  header="**31 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/108#discussion_r1382904984" expanded>

Shouldn't this say "Please enter a positive income amount?"?
</panel>

<panel  header="**32 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/109#discussion_r1382914912" expanded>

Nice way of handling too large numbers! Maybe consider setting the MAX_AMT to 9999999.99 as it is a double
</panel>

<panel  header="**33 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/113#discussion_r1384864107" expanded>

Maybe we should all also add a profile picture, to make this page look more professional
</panel>

<panel  header="**34 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/112#discussion_r1384868411" expanded>

Maybe we should also all add a profile picture to make this page look more professional
</panel>

<panel  header="**35 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/117#discussion_r1391080183" expanded>

Nice way of handling this. Maybe in the next version we could create a separate file containing all the logging information
</panel>

<panel  header="**36 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/118#discussion_r1391189663" expanded>

Nice way of disabling logging. Maybe in the next version we can also create a .txt file containing all the logging information separately.
</panel>

<panel  header="**37 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/46#discussion_r1367647649" expanded>

What do you mean? The absolute value is there so that the user cannot put a negative budget. The argument for setBudget is of type Budget and not double.
</panel>

<panel  header="**38 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/issues/50#issuecomment-1785349776" expanded>

I would leave it like this yes. I think you should still be able to use the app without a budget just like in v 1.0
</panel>

<panel  header="**39 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/issues/85#issuecomment-1797721299" expanded>

The budget is intended to be kept separate from the net cash on hand. In your example, you set a budget of 1,000 and have a current cash on hand of 1,447.5. Following your expense of 100, you are still running a budget surplus of (1,347.5 - 1,000) = 347.5.
</panel>

</panel>


<panel type="info" header="### 11. NIHA..IAJI `@nihalzp` (27 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/18#discussion_r1356377752" expanded>

Should we simplify the logic and always set depending on the currentValue?
```suggestion
        if (currentValue >= targetValue) {
            setIsGoalAchieved(true);
        } else {
            setIsGoalAchieved(false);
        }
```
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/18#discussion_r1356383028" expanded>

Good job on using StringBuilder which is good for performance 
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359432009" expanded>

In activity,  we used `LocalDateTime` for datetime. Should we use `LocalDateTime` for all our datetime tracking to be consistent?
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/51#discussion_r1362348920" expanded>

To be consistent with other part of the code, I think we should throw an exception instead.
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/51#discussion_r1362350924" expanded>

Similar to the delete sleep execute, I think we should also have a check here for index validity and preferably throw an error.
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/51#discussion_r1362355091" expanded>

```suggestion
    /**
     * Lists all the sleep records in the sleep list.
     *
     * @param data The current data containing the sleep list.
     * @return The message which will be shown to the user.
     */
```
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/51#discussion_r1362355648" expanded>

```suggestion
    /**
     * Constructor for Sleep.
     *
     * @param from Start time of the sleep.
     * @param to End time of the sleep.
     */
```
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/51#discussion_r1362356189" expanded>

```suggestion
    /**
     * toString method for Sleep.
     *
     * @return String representation of the sleep record.
     */
```
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/51#discussion_r1362356542" expanded>

```suggestion
    /**
     * toString method for SleepList.
     *
     * @return String representation of the sleep list.
     */
```
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/67#discussion_r1363984663" expanded>

```suggestion
* `set-diet-goal calories/CALORIES protein/PROTEIN carb/CARBS fat/FAT`
```
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/67#discussion_r1363984951" expanded>

```suggestion
* CARB: Your target value for carbohydrate intake, in terms of milligrams.
```
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/67#discussion_r1363988263" expanded>

```suggestion
* `set-diet-goal calories/500 protein/20 carb/50 fat/10`
```
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/67#discussion_r1363992120" expanded>

```suggestion
* `edit-diet-goal calories/CALORIES protein/PROTEIN carb/CARBS fat/FAT`
```
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/67#discussion_r1363992395" expanded>

```suggestion
* `edit-diet-goal calories/5000 protein/200 carb/500 fat/100`
```
</panel>

<panel  header="**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/76#discussion_r1366555565" expanded>

```suggestion
        LOGGER.info("Added sleep: " + newSleep.toString());
        LOGGER.fine("Sleep list: " + sleepList.toString());
```
</panel>

<panel  header="**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/76#discussion_r1366556910" expanded>

```suggestion
        assert accessIndex >= 0 : "Index cannot be less than 1";
```
By "index" if we are referring to the index given to the `DeleteSleepCommand` function.
</panel>

<panel  header="**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/76#discussion_r1366557601" expanded>

```suggestion
        assert accessIndex < sleepList.size() : "Index cannot be more than the number of recorded sleeps";
```
</panel>

<panel  header="**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/76#discussion_r1366557986" expanded>

```suggestion
        LOGGER.fine("Deleted sleep: " + oldSleep.toString());
```
</panel>

<panel  header="**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/100#discussion_r1371989840" expanded>

Good job on using the singleton pattern
</panel>

<panel  header="**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/282#discussion_r1390351565" expanded>

If possible, we should have one junit test for this function for future dates.
</panel>

<panel  header="**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/282#discussion_r1390351750" expanded>

Same as before
</panel>

<panel  header="**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/302#discussion_r1390431037" expanded>

Good job on RepoSense specific link
</panel>

<panel  header="**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/302#discussion_r1390431231" expanded>

Maybe can mention the goal utilities as well.
</panel>

<panel  header="**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/314#discussion_r1390599325" expanded>

```suggestion
```
</panel>

<panel  header="**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/322#discussion_r1390618464" expanded>

We have added picture in the other part of the UG. Should we be consistent here as well?
</panel>

<panel  header="**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/322#discussion_r1390619295" expanded>

```suggestion
* Provided full scale testing for diet goal functionalities.
```
</panel>

<panel  header="**27 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/340#discussion_r1391193915" expanded>

```suggestion
        String invalidInput = "2 calorie/1 proteins/2 carbs/3 fats/4 date/2023-10-06";
```
Quick fix for the issue.
</panel>

<panel  header="**28 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/31#discussion_r1359865089" expanded>

Thanks for pointing it out. I have added a commit to resolve the issue.
</panel>

<panel  header="**29 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/31#discussion_r1359871183" expanded>

True. However, the current way is convenient to send personalised error messages.
</panel>

<panel  header="**30 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/31#discussion_r1359871893" expanded>

Good idea. We can open an issue for it.
</panel>

<panel  header="**31 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/31#discussion_r1359873372" expanded>

Good idea. Resolved.
</panel>

<panel  header="**32 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/263#discussion_r1389546274" expanded>

Yes good idea and this feature was proposed and on the bucket list last week. I only got the chance to implement it now.
</panel>

<panel  header="**33 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/288#discussion_r1390394095" expanded>

Explicitly mentioning this "0000" could makes things unnecessarily detailed since in practice, no user is going to use this year. We can mention that it needs to be a valid date.
</panel>

<panel  header="**34 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/288#discussion_r1390394526" expanded>

I feel this should be okay. The updated error message would read:

`The datetime must be valid and in the format yyyy-MM-dd HH:mm!`

Year 0000 is not valid datetime, which is conveyed by the new updated message.

</panel>

<panel  header="**35 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/288#discussion_r1390427873" expanded>

Good idea. I think then the UG will look consistent across different features.
</panel>

<panel  header="**36 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/20#issuecomment-1762549419" expanded>

Thanks for suggestions. I have amended them.
</panel>

<panel  header="**37 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/70#issuecomment-1772184269" expanded>

To understand clearly, for each of the add-diet command, do we also require the user to input the time?
</panel>

<panel  header="**38 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/200#issuecomment-1806804539" expanded>

The issue in command format. The correct format is: "find-diet 2021-09-01". There should be no date/ flag.
</panel>

<panel  header="**39 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/287#issuecomment-1807070732" expanded>

Only the first argument and value will be accepted; it is possible to do the extra check and not allow duplicate marker; but I think it does not affect usability.
</panel>

<panel  header="**40 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/275#issuecomment-1807103868" expanded>

All saving and editing files are working properly!
</panel>

<panel  header="**41 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/293#issuecomment-1807112193" expanded>

It is fixed by the previous pull request.
</panel>

<panel  header="**42 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/292#issuecomment-1807141747" expanded>

I have updated the message to use the word "events" instead of "activities".
</panel>

<panel  header="**43 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/291#issuecomment-1807141970" expanded>

This problem seemed universal to all datetime parsing. I have made changes to throw error when hhmmss is given instead of hhmm.
</panel>

<panel  header="**44 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/290#issuecomment-1807142252" expanded>

I have used "\t" to align all the diets (taking inspiration from diet goals list).
</panel>

<panel  header="**45 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/287#issuecomment-1807142405" expanded>

I have added extra checks to disallow duplicate arguments and throw an error.
</panel>

<panel  header="**46 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/288#issuecomment-1807150458" expanded>

> Also can you open a new PR for the other bug fixes, this is getting hard to review otherwise 😂

It is a good idea; I feel this will require significant time investment since many bug fixes are built on top of each other.  However, each bug fix is contain usually within a single commit; thus it is possible to review the new bug fixes by looking at the individual commit changes.
</panel>

<panel  header="**47 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/312#issuecomment-1807430594" expanded>

Having the extra [prefix] is going to make implementation complicated. For example, without the extra [prefix], the implementation is as simple as clean as:
<img width="492" alt="Screenshot 2023-11-13 at 11 40 45 AM" src="https://github.com/AY2324S1-CS2113-T17-1/tp/assets/81457724/947e964e-e3a6-47d0-8116-a2ff49b2889a">

</panel>

<panel  header="**48 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/313#issuecomment-1807432700" expanded>

![image](https://github.com/AY2324S1-CS2113-T17-1/tp/assets/81457724/ebecdd94-75a8-4179-b8b7-5b34d3b0d582)
Seems like `delete-activity-goal` is working as intended.
</panel>

<panel  header="**49 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/318#issuecomment-1807443660" expanded>

![image](https://github.com/AY2324S1-CS2113-T17-1/tp/assets/81457724/7c76e01f-ed24-4259-8d92-944fac1917a2)
Also for the `delete-diet-goal index` as well.
</panel>

<panel  header="**50 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/319#issuecomment-1807492885" expanded>

Good point. However, as far as I know, fat can be noun as well.

![image](https://github.com/AY2324S1-CS2113-T17-1/tp/assets/81457724/1a00f26c-9967-4ccd-856d-f4ddf993a21a)

I am on the side of `fat` since we have used singular nouns for `protein` and `carb`.
</panel>

<panel  header="**51 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/326#issuecomment-1807498407" expanded>

Yes, same behaviour can be observed for `find-activity`, `find-sleep` as well.
</panel>

<panel  header="**52 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/328#issuecomment-1807555946" expanded>

Thank you very much for pointing it out. I am fixing it in the next PR.
</panel>

<panel  header="**53 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/340#issuecomment-1808266419" expanded>

> However, it failed one test case, how can I rectify it?

Seems like one of my function's test case failed. Merge it; I will fix it in my upcoming PR.
</panel>

</panel>


<panel type="info" header="### 12. WOLT..LIUS `@AlWo223` (26 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359344902" expanded>

Good exception handling! You could use the Message class to separate the user notifications from the parser logic.
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359345184" expanded>

Consider using BeforeEach to reduce code redundancy, otherwise nice testing of different cases 
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359345277" expanded>

Great naming according to Coding Standards 
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/76#discussion_r1367632996" expanded>

This follows the naming convention for test methods very well! 
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/76#discussion_r1367633100" expanded>

Very comprehensive text-ui-testing! 
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/77#discussion_r1367744627" expanded>

Great use of map!
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/95#discussion_r1371294744" expanded>

Nice use of enum! We could add DAILY in a later iteration (especially for diet goals it is more convenient to track and plan your daily habits)
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/95#discussion_r1371462333" expanded>

Should this have **Data data** as a parameter or where do we best examine the data against the target value?
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/109#discussion_r1373406951" expanded>

Very helpful for filtering the lists! 
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/280#discussion_r1390321754" expanded>

Redundant information, we could delete that line (see Notes about Command Format, line 24)
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/280#discussion_r1390321850" expanded>

```suggestion
* PERIOD: The period for which you want to set a goal. It must be one of the following: `daily, weekly, monthly, yearly`. Only sleeps that are recorded within the period from the current time will be counted towards the goal.
```
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/280#discussion_r1390322053" expanded>

hh:mm format would be more user-friendly here. This way, the user has to calculate the minutes each time. Probably out of scope for the final submission.
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/280#discussion_r1390322423" expanded>

Can we omit this parameter? If the user can not specify any other type, this might be counted as "complicated command format" flaw
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/280#discussion_r1390322672" expanded>

I think we need a stronger justification here. It might more likely be a hint for the user to report this feature flaw.
</panel>

<panel  header="**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/288#discussion_r1390372553" expanded>

```suggestion
You can set goals for specific sports by defining the target distance or duration over various periods. The goals can track your daily, weekly, monthly, or yearly progress.
```
I think it's good to mention the periods here so that the user better understands the feature.
</panel>

<panel  header="**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/288#discussion_r1390372904" expanded>

```suggestion
* TARGET: The target value. It must be a positive number. For distance, in meters. For duration, in
  minutes.
```
Need to mention positive number criteria and the () seem unnecessary.
</panel>

<panel  header="**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/288#discussion_r1390373057" expanded>

I prefer the previous version, which tries to explain the goal a bit better 
</panel>

<panel  header="**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/288#discussion_r1390373656" expanded>

There is a space bug in the first line of the list. We had the same one for activity-goal-list once.
</panel>

<panel  header="**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/288#discussion_r1390373952" expanded>

Can you specify this boundary / exception in the UG as well?
</panel>

<panel  header="**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/288#discussion_r1390374008" expanded>

Nice use of date time features! I suggest to create a more specific exception message for this case, as the input format is actually valid but the boundary is not.
</panel>

<panel  header="**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/288#discussion_r1390374250" expanded>

Great separation of message and parameter!
</panel>

<panel  header="**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/288#discussion_r1390423889" expanded>

Should we show an example for all the list commands? We need to keep it as short as possible — just some thought.
</panel>

<panel  header="**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/288#discussion_r1390425097" expanded>

My bad, thought there is a year 0, so invalid is fine!
</panel>

<panel  header="**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/288#discussion_r1390425202" expanded>

Yep that's good
</panel>

<panel  header="**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/288#discussion_r1390425516" expanded>

```suggestion
* `edit-activity-goal sport/swimming type/duration period/monthly target/60` Adjusts the goal of swimming duration to 1 hour 
```
Something like that to clarify that we are actually changing the target value and not filtering by this
</panel>

<panel  header="**26 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/306#discussion_r1390442203" expanded>

Good implementation of the overlap check!
</panel>

<panel  header="**27 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/19#discussion_r1357766883" expanded>

That's very helpful, thank you!
</panel>

<panel  header="**28 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/113#discussion_r1373547177" expanded>

I made this one static @skylee03 as this was easier to adapt to my existing code. Please let me know if it should not be static. Then I will adjust my code accordingly
</panel>

<panel  header="**29 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/139#discussion_r1379536678" expanded>

Thank you, good to know!
</panel>

<panel  header="**30 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/92#issuecomment-1790074606" expanded>

implements activity part of #69 
</panel>

<panel  header="**31 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/113#issuecomment-1790075601" expanded>

implements activity part of #73 
</panel>

<panel  header="**32 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/125#issuecomment-1790076703" expanded>

puts activity part of UG in correct file #103 
</panel>

<panel  header="**33 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/223#issuecomment-1793431589" expanded>

Assigning this issue to Dylan as sleep-related
</panel>

<panel  header="**34 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/157#issuecomment-1793439350" expanded>

Implements activity part of save functionality #227 
</panel>

<panel  header="**35 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/212#issuecomment-1793452302" expanded>

Closed as not planned since distance should be 0.00 km, user input was only 1 meter
</panel>

<panel  header="**36 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/204#issuecomment-1793638753" expanded>

This bug is the result of the "laps/" instruction listed in the UG. Need to update UG to prevent misleading user.
</panel>

<panel  header="**37 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/237#issuecomment-1793638932" expanded>

Updates swim command instructions in UG, closes #204 
</panel>

<panel  header="**38 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/202#issuecomment-1793640476" expanded>

Works as expected, the goal only tracks progress in the current week. I will emphasise this in the UG.
</panel>

<panel  header="**39 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/237#issuecomment-1793640740" expanded>

Emphasises periodicity of activity goals in UG, closes #202 
</panel>

<panel  header="**40 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/190#issuecomment-1793679579" expanded>

Closed as duplicate of #198 
</panel>

<panel  header="**41 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/172#issuecomment-1793680424" expanded>

Tester used incorrect add-swim command. There is no _elevation/_ in swimming
</panel>

<panel  header="**42 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/193#issuecomment-1793686777" expanded>

Closed, as duplicate of #198 
</panel>

<panel  header="**43 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/192#issuecomment-1793687436" expanded>

Closed, duplicate of #202 (works as expected)
</panel>

<panel  header="**44 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/201#issuecomment-1793676212" expanded>

There is no need to distinguish the arguments, since there is no use case for setting a goal with detailed seconds. For convenience, minutes is the chosen metrics.
</panel>

<panel  header="**45 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/159#issuecomment-1793720887" expanded>

duplicate of #198 
</panel>

<panel  header="**46 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/195#issuecomment-1793786327" expanded>

Can not reproduce, maybe system specific error?
</panel>

<panel  header="**47 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/176#issuecomment-1793793076" expanded>

Duplicate of #178 (no data loss, only shown in condensed view)
</panel>

<panel  header="**48 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/178#issuecomment-1793793290" expanded>

No data loss, only condensed view. I will add some clarification in UG to prevent misunderstanding
</panel>

<panel  header="**49 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/164#issuecomment-1793797312" expanded>

Duplicate of #178 (no data loss, just condensed view)
</panel>

<panel  header="**50 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/72#issuecomment-1803846339" expanded>

Not planned
</panel>

<panel  header="**51 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/55#issuecomment-1803848999" expanded>

Not planned
</panel>

<panel  header="**52 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/56#issuecomment-1803855143" expanded>

Solved by #237 
</panel>

<panel  header="**53 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/141#issuecomment-1803859960" expanded>

Not planned
</panel>

<panel  header="**54 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/265#issuecomment-1806708578" expanded>

I have done some major refactoring and optimization in ActivityParser as well, would be great if you can review these changes as well
</panel>

<panel  header="**55 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/241#issuecomment-1806719852" expanded>

#265 
</panel>

<panel  header="**56 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/177#issuecomment-1806867174" expanded>

This is not a bug and would require too many changes. Close this issue as not planned to prevent new bugs and to focus on other things
</panel>

<panel  header="**57 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/288#issuecomment-1807149239" expanded>

Also can you open a new PR for the other bug fixes, this is getting hard to review otherwise 😂
</panel>

<panel  header="**58 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/313#issuecomment-1807393957" expanded>

Works for me, can you try to reproduce the commands you used?
</panel>

<panel  header="**59 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/312#issuecomment-1807399965" expanded>

This is required for activity as the various activity types Swim, Run, etc. need to be parsed differently. Feel free to follow this format for standardisation reasons but I guess it does not really have any benefit for your implementations.
</panel>

<panel  header="**60 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/329#issuecomment-1807624470" expanded>

Also I recommend not to write something like "justify", "absence". Try to be more confident and make it clear that sleep goals are normally not stopped but rather adjusted. I guess every human has a target value for how much sleep they are trying to get.
</panel>

<panel  header="**61 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/331#issuecomment-1807662312" expanded>

Is this mandatory and what is the expectation (how many test scenarios?)
</panel>

<panel  header="**62 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/295#issuecomment-1808453831" expanded>

Fixed the last two. The first one would require some changes to parsing functionality, which is too risky at this stage ig
</panel>

<panel  header="**63 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/352#issuecomment-1808494166" expanded>

> > LGTM!
> 
> But I think the correct anchor should be `#activity-management`.

There are two activity-management headlines in UG and DG, I am trying to reference the first one of each document. But I have no idea whether this works 
</panel>

<panel  header="**64 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/352#issuecomment-1808500284" expanded>

> > > > LGTM!
> > > 
> > > 
> > > But I think the correct anchor should be `#activity-management`.
> > 
> > 
> > There are two activity-management headlines in UG and DG, I am trying to reference the first one of each document. But I have no idea whether this works
> 
> I tried but this did not work.

Maybe like this?
```
<a name="activity-management-1"></a>
### ActivityManagement
<a name="activity-management-2"></a>
### ActivityManagement
```

</panel>

<panel  header="**65 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/352#issuecomment-1808515137" expanded>

Just inspected the html docs and realised there are no duplicates 🙃 For DG the relevant section is actually called activity-management-in-AtheltiCLI and in UG there is a "-" placeholder for emoji included. This should fix it 
</panel>

</panel>


<panel type="info" header="### 13. TOH ..CHUN `@mcmc101001` (25 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/30#discussion_r1360718735" expanded>

I would suggest renaming this to printIncomes as this method does not return, but instead prints
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/30#discussion_r1360721086" expanded>

I think that we should change the implementation such that the statements are passed into the parser, as not all commands need both statements to function
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/30#discussion_r1360723644" expanded>

I think that this method should be renamed to printExpenses as it returns voic and prints text instead
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/30#discussion_r1360726765" expanded>

I think that we should change how the Ui class is used. It should not be initialised in the expense class. Perhaps we can change the methods it contain to static methods to prevent this unnecessary initialisation
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/46#discussion_r1367174293" expanded>

for the print multiple text function, each line is represented by an element in the array, sowe can refactor this to avoid the tab and new line characters

printMultipleText( new String[] { line 1, line 2});
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/46#discussion_r1367176410" expanded>

should the budget set be converted to the absolute value for consistency with the getBudget function
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/46#discussion_r1367182992" expanded>

Perhaps we can call this method in setBudget as well, as we probably want to ensure that the budget percentage is modified whenever budget is changed
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/46#discussion_r1367751923" expanded>

right understood!
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/47#discussion_r1368791417" expanded>

should remove otherwise it might introduce additional lines when logging is disabled
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/47#discussion_r1368798704" expanded>

i would suggest adding some javadoc comments to explain this as it serves more like an autocomplete feature
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/47#discussion_r1368799149" expanded>

pls remove the print statements
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/47#discussion_r1368803182" expanded>

I think the boolean expression within can be simplified using de morgan's, the current implementation is a bit hard to understand logically
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/52#discussion_r1370306274" expanded>

i think we can use a optional type and initialise it as null instead of using -1 as a magic number
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/52#discussion_r1370311098" expanded>

the initial list can be empty right, not clear why this assertion is true
</panel>

<panel  header="**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/52#discussion_r1370344654" expanded>

i feel that there is too much nesting, perhaps we can always add a comma at the end, and then remove the final comma
</panel>

<panel  header="**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/52#discussion_r1370351703" expanded>

im unsure why there is expenseCategory involved in the code for incomeCatgeories
</panel>

<panel  header="**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/52#discussion_r1370360101" expanded>

oh wait is it because it can be empty but not null
</panel>

<panel  header="**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/52#discussion_r1371269750" expanded>

should change to optionalDouble for more strict typing
</panel>

<panel  header="**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/52#discussion_r1371270537" expanded>

Likewise for this OptionalDOuble
</panel>

<panel  header="**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/63#discussion_r1376108526" expanded>

i think this parts need better explanation, where does the number 3 come from?
</panel>

<panel  header="**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/63#discussion_r1376110042" expanded>

good explaination!
</panel>

<panel  header="**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/66#discussion_r1377163658" expanded>

i think we can draw dotted lines back from the user's file to the respective callers so that the diagram's arrows flow
</panel>

<panel  header="**23 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/107#discussion_r1382571346" expanded>

should this be `java -jar CashLeh.jar ` instead?
</panel>

<panel  header="**24 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/107#discussion_r1382571387" expanded>

good catch!
</panel>

<panel  header="**25 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/114#discussion_r1386457711" expanded>

i don't think need docs as everyone else does not
</panel>

<panel  header="**26 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/55#discussion_r1374355655" expanded>

i dont think assertions are supposed to be false
</panel>

<panel  header="**27 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/issues/6#issuecomment-1743144029" expanded>

Add a link to the user guide
</panel>

<panel  header="**28 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/issues/50#issuecomment-1779588705" expanded>

I think it is
</panel>

<panel  header="**29 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/issues/71#issuecomment-1792550342" expanded>

already handled!
</panel>

<panel  header="**30 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/issues/90#issuecomment-1793733839" expanded>

Can be a niche use case, particular when involving currency conversion, thus we can deem it not a bug
</panel>

<panel  header="**31 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/issues/106#issuecomment-1793734091" expanded>

fixed
</panel>

<panel  header="**32 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/issues/101#issuecomment-1793735035" expanded>

fixed!
</panel>

<panel  header="**33 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/issues/93#issuecomment-1793738555" expanded>

Regarding punctuation, not a bug as this grants users more flexibility to name things instead of taking away the freedom for them
</panel>

<panel  header="**34 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/issues/85#issuecomment-1793740782" expanded>

This is the intended behaviour, as you rightly mentioned, the budget is kept separate from cash at hand.
</panel>

<panel  header="**35 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/issues/82#issuecomment-1793741367" expanded>

fixed!
</panel>

<panel  header="**36 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/issues/80#issuecomment-1793741555" expanded>

Intended behaviour
</panel>

<panel  header="**37 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/issues/77#issuecomment-1793741919" expanded>

UG says "It accepts a range of formats, `dd/mm/yyyy` is recommended." does not mean all formats are accepted.
</panel>

<panel  header="**38 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/issues/76#issuecomment-1793742381" expanded>

User guide link changed
</panel>

<panel  header="**39 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/issues/97#issuecomment-1794209097" expanded>

don't think it is a very significant issue
</panel>

<panel  header="**40 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/issues/90#issuecomment-1794418743" expanded>

For example, Bahraini dinar uses 3dp
</panel>

<panel  header="**41 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/issues/95#issuecomment-1794788630" expanded>

Think bug shows up as ctrl-D on some devices, I had this problem, fixed in PR linked
</panel>

<panel  header="**42 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/issues/39#issuecomment-1805858559" expanded>

will not implement
</panel>

<panel  header="**43 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/117#issuecomment-1808263293" expanded>

Pushed a new PR with better implementation
</panel>

</panel>


<panel type="info" header="### 14. DYLA..TIAN `@DaDevChia` (22 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/31#discussion_r1359863949" expanded>

Good use of abstraction, but we can use 1 parseInt method for all parse(diet) methods to reduce redundancy, no need for 3 duplicate methods 
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/31#discussion_r1359864286" expanded>

Good use of String constants, but might be preferable to factor the String markers to a separate class to allow for easier changes to be made
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/31#discussion_r1359865000" expanded>

Would be preferable to rearrange this to the top of this method signature such that the exception checker can use index > size for better readability
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/31#discussion_r1359865238" expanded>

Some AthletiExceptions can still be factored out as string constants in messages class
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/31#discussion_r1359865352" expanded>

Great use of abstractions to perform check for missing arguments
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/31#discussion_r1359868899" expanded>

Great check to test for exceptions thrown as well!
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/35#discussion_r1359911556" expanded>

Suggest to use a set interface to implement duplicate checking for better time complexity and less nested (less than 2 layers of nesting) and readable method
```suggestion
   public String[] execute(Data data) throws AthletiException {
    DietGoalList currentDietGoals = data.getDietGoals();
    Set<String> currentDietGoalsNutrients = new HashSet<>();

    // Populate the set with current diet goal nutrients
    for (DietGoal dietGoal : currentDietGoals) {
        currentDietGoalsNutrients.add(dietGoal.getNutrients());
    }

    // Check against user new diet goals
    for (DietGoal userDietGoal : userNewDietGoals) {
        String userNewNutrient = userDietGoal.getNutrients();
        if (currentDietGoalsNutrients.contains(userNewNutrient)) {
            throw new AthletiException(String.format(Message.MESSAGE_DIETGOAL_ALREADY_EXISTED, userNewNutrient));
        }
    }

    // Add new diet goals to current diet goals
    currentDietGoals.addAll(userNewDietGoals);
    
    return new String[]{"These are your goals:\n", currentDietGoals.toString()};
}

```
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/35#discussion_r1359911772" expanded>

Good the separate the marker constants, but it would be better to separate them to its own class for better modularity
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/35#discussion_r1359912337" expanded>

Better to use guard clauses to "show the happy path" more clearly, usage of else if statements is also not required in this case
```suggestion
                if (targetValue == 0) {
                    throw new AthletiException(Message.MESSAGE_DIETGOAL_TARGET_VALUE_NOT_POSITIVE_INT);
                } 
                if (!verifyValidNutrients(nutrient)) {
                        throw new AthletiException(Message.MESSAGE_DIETGOAL_INVALID_NUTRIENT);
                } 
                DietGoal dietGoal = new DietGoal(nutrient, targetValue);
                dietGoals.add(dietGoal);
```
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/59#discussion_r1363088422" expanded>

```suggestion
            throw new AthletiException(Message.MESSAGE_ACTIVITY_INDEX_OUT_OF_BOUNDS);
```
Spelling error.
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/59#discussion_r1363091557" expanded>

```suggestion
            throw new AthletiException(Message.MESSAGE_ACTIVITY_INDEX_OUT_OF_BOUNDS);
```
Spelling error.
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/59#discussion_r1363104086" expanded>

Great use of named constants for better maintainability and readability, also prevents bugs in the future when parameters are changed
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/59#discussion_r1363117041" expanded>

One suggestion is to change activity keywords to `add-activity`, `add-cycle`, etc to standardize the commands across the board. 
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/60#discussion_r1363144349" expanded>

One suggestion would be to move the markers to the newly created parameters class.
</panel>

<panel  header="**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/88#discussion_r1368411242" expanded>

Unsure if the catch block here is intended as my understanding is that AthletiException will be caught by main AtheliCLI class to have the error message printed out.
</panel>

<panel  header="**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/118#discussion_r1375491379" expanded>

If the string isn't a valid integer, this will throw a `NumberFormatException`. Consider wrapping this in a try-catch block and throwing a user-friendly AthletiException if an invalid number is provided.
</panel>

<panel  header="**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/247#discussion_r1385133518" expanded>

LGTM!
</panel>

<panel  header="**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/263#discussion_r1389541304" expanded>

Good feature, but lets not introduce any more new commands and features after the feature freeze, as that would create more testing required.
</panel>

<panel  header="**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/263#discussion_r1389542891" expanded>

Good to have a rejex checker to capture the date and time!
</panel>

<panel  header="**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/308#discussion_r1390456741" expanded>

Just to check is there an answer to this question here?
</panel>

<panel  header="**21 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/339#discussion_r1391149345" expanded>

Good job adding javadocs to all the test cases for better clarity!
</panel>

<panel  header="**22 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/339#discussion_r1391154167" expanded>

Good to list out the general test cases that can be used!
</panel>

<panel  header="**23 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359476873" expanded>

Thanks! Will be implemented in the next cycle.
</panel>

<panel  header="**24 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359476977" expanded>

Made the commit, good catch!
</panel>

<panel  header="**25 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359477299" expanded>

Yes good suggestion!
</panel>

<panel  header="**26 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359477585" expanded>

Yes will be implemented on the next iteration
</panel>

<panel  header="**27 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359478587" expanded>

Will be implemented in the next iteration
</panel>

<panel  header="**28 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359478638" expanded>

Thanks!
</panel>

<panel  header="**29 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/21#discussion_r1359478842" expanded>

Apologies for this, will fix it in a future commit, updated the issues tab as well
</panel>

<panel  header="**30 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/51#discussion_r1362635100" expanded>

Thanks for the bug catch, will definitely add that as well.
</panel>

<panel  header="**31 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/51#discussion_r1362647129" expanded>

Yes agreed will refactor this code to throw the corresponding Out of Bounds exception.
</panel>

<panel  header="**32 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/138#discussion_r1378969793" expanded>

Thanks!
</panel>

<panel  header="**33 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/250#discussion_r1385262087" expanded>

Thanks for the good spot!
</panel>

<panel  header="**34 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/280#discussion_r1390330970" expanded>

Yes good point made, deleted these lines.
</panel>

<panel  header="**35 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/280#discussion_r1390331045" expanded>

Good suggestion, but would require some reworking and testing so wont add that feature for the submission.
</panel>

<panel  header="**36 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/280#discussion_r1390331833" expanded>

I think that is possible, but I would keep the parameter for clarity purposes and such that future versions can extend to other goal types as well.
</panel>

<panel  header="**37 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/280#discussion_r1390331893" expanded>

Added a new justification for this

1. **Diversity of Diet Goals:** The Diet section likely encompasses a wider range of goals compared to Sleep and Activity. With such variability, users might frequently need to delete diet goals, making a delete function more essential in this section.

2. **Stability of Sleep and Activity Goals:** Goals related to sleep and activity are generally more consistent and less variable over time. This stability reduces the immediate need for a delete feature, as users are less likely to remove these goals frequently.

3. **Focused Development Resources:** Given limited development resources and time, the team prioritized implementing the delete feature for the Diet section, where it was deemed most necessary due to the larger volume and variability of goals.

4. **Planned for Future Implementation:** The absence of this feature in the current version for Sleep and Activity does not indicate it will never be implemented. It is planned for a future update, aligning with a phased development approach.
</panel>

<panel  header="**38 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/359#discussion_r1391525599" expanded>

apologies just restored the misc commands

</panel>

<panel  header="**39 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/8#issuecomment-1753454850" expanded>

LGTM!
</panel>

<panel  header="**40 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/69#issuecomment-1774111661" expanded>

Part 1: Implement individual functions for find
Deadline: by this tutorial
find-sleep DATE 
find-run DATE
find-activity DATE
find-diet DATE

return:
You ate: ? on this date:

Part 2: Integrate all to a find function
Deadline by Sun after this tutorial
Integrate all:

find DATE

return:
You ate:
You slept:You ran:
</panel>

<panel  header="**41 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/125#issuecomment-1785843159" expanded>

Looks good to me!
</panel>

<panel  header="**42 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/183#issuecomment-1799026098" expanded>

find-sleep command should not include date/
</panel>

<panel  header="**43 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/213#issuecomment-1799031693" expanded>

Implement check for dates that are too long ago and throw error
</panel>

<panel  header="**44 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/217#issuecomment-1799053134" expanded>

Implement checking feature to indicate rejection of long sleeping periods and make it throw athleticli exception
</panel>

<panel  header="**45 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/220#issuecomment-1799121366" expanded>

Add check to indicate sleep of 0 min for extremely short duration sleeps
</panel>

<panel  header="**46 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/223#issuecomment-1799124107" expanded>

Same as #217 
</panel>

<panel  header="**47 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/226#issuecomment-1799129067" expanded>

Same as #183 
</panel>

<panel  header="**48 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/179#issuecomment-1806010601" expanded>

Update UG to state that for sleep specifically you are not allowed to swap parameter orders
</panel>

<panel  header="**49 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/179#issuecomment-1806010885" expanded>

for start and end time
</panel>

<panel  header="**50 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/300#issuecomment-1807167578" expanded>

That would be out of scope to implement for now (requires timeline checkers and extensive checker), activity would also need to follow the same overlap checking logic if implemented.
</panel>

<panel  header="**51 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/299#issuecomment-1807180473" expanded>

Find-sleep returns all matching entries on the date itself, just that it considers all sleeps with start time before 6am to be before.
</panel>

<panel  header="**52 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/315#issuecomment-1807569153" expanded>

Not in scope
</panel>

<panel  header="**53 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/362#issuecomment-1809443717" expanded>

> LGTM, though it might be better to place the goal delete note in the Sleep section. Then the tester is not confronted directly with this :) 

I think thats a good point, but cant quite find a good place to fit it inside the Sleep section without disrupting flow.
</panel>

</panel>


<panel type="info" header="### 15. STAN..JAYA `@StanleyW00` (20 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/59#discussion_r1371220625" expanded>

Nice that you updated the help text
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/59#discussion_r1371230652" expanded>

May I ask does this mean that you can add more than 1 ingredient at once?
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/60#discussion_r1371238713" expanded>

Perhaps in the future, we can change the message
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/60#discussion_r1371243590" expanded>

Quite nice way to edit the properties of ingredients
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/80#discussion_r1374485165" expanded>

I like that you put several test for testing out delete ingredient command
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/80#discussion_r1374485403" expanded>

I like that you put several test for testing out delete recipe command

</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/92#discussion_r1375272769" expanded>

I like your coverage of the tests
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/106#discussion_r1378391509" expanded>

I like the fact that you calculate the total duration.
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/106#discussion_r1378391696" expanded>

I like that you find a way to sort by time
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/107#discussion_r1379629855" expanded>

I think `eachStep.length()>0` should be `eachStep.length() > 0` for easier readability.
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/107#discussion_r1379630321" expanded>

I like that you considered more than one way of inputting the time for each step.
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/114#discussion_r1380257503" expanded>

I think that you should make it `allToAdd.length == (1)`
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/122#discussion_r1381672093" expanded>

Nice coverage of tests
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/215#discussion_r1384777946" expanded>

```suggestion
    public void addRecipeCommand_multipleTitles_formatException() {
```
I suggest that the method name should be this.
</panel>

<panel  header="**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/215#discussion_r1384782305" expanded>

Nice way of checking if the user want to overwrite
</panel>

<panel  header="**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/231#discussion_r1388028797" expanded>

I like that you update the ingredient if the ingredient has already existed in the list.
</panel>

<panel  header="**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/231#discussion_r1388029596" expanded>

Nice way to make it more intuitive.
</panel>

<panel  header="**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/239#discussion_r1388895979" expanded>

Should this part be abstracted so it is not too nested?
</panel>

<panel  header="**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/250#discussion_r1390201690" expanded>

Is this test going to be used?
</panel>

<panel  header="**20 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/250#discussion_r1390201873" expanded>

Perhaps you should abstract some of the lines. The logic looks good.
</panel>

<panel  header="**21 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/127#discussion_r1384271586" expanded>

Sure, i will move it
</panel>

<panel  header="**22 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/252#discussion_r1390319644" expanded>

this will trigger essen exception after throwing it
</panel>

<panel  header="**23 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/199#issuecomment-1797883021" expanded>

Tester does not create recipe, so it makes sense the `recipe.txt` is empty.
</panel>

<panel  header="**24 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/169#issuecomment-1797905917" expanded>

Make live update after each change
</panel>

<panel  header="**25 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/195#issuecomment-1797925151" expanded>

Same issues already addressed.
</panel>

</panel>


<panel type="info" header="### 16. CHAN..DICT `@BenedictChannn` (19 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/34#discussion_r1362361574" expanded>

I think it's fine since the messages are fit for our context.
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/31#discussion_r1363160643" expanded>

Nice!
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/31#discussion_r1363165654" expanded>

Would it be better if we rename this to getNumberOfExpenses?
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/31#discussion_r1363166031" expanded>

Would it be better if we rename this to getSumOfExpenses

</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/31#discussion_r1363168386" expanded>

Would renaming this to getNumberOfIncomes be better

</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/31#discussion_r1363178301" expanded>

I'm not sure if this is needed or is in the right place to include this
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/52#discussion_r1370343599" expanded>

Would it be better to just put this in your first if statement? like check for amount inside the first if statement instead of having to repeat the description check again
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/52#discussion_r1370345878" expanded>

Same thing here I guess
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/52#discussion_r1370351513" expanded>

Same thing here
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/52#discussion_r1370358275" expanded>

Would it be better to rename transactionType to be filterType or filterBy?
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/51#discussion_r1370361456" expanded>

Should we mention the category also?
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/55#discussion_r1374351092" expanded>

When will this assertion be false ah? When somehow accidentally the string got more than one ":optional"?
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/67#discussion_r1377337190" expanded>

I think there is some spacing issue for the second horizontal line?
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/67#discussion_r1377338516" expanded>

Can probably mention that the financial statement displayed will be sorted by date
</panel>

<panel  header="**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/67#discussion_r1377340375" expanded>

Can we make use of the AMT_KEYWORD and DATE_KEYWORD?
</panel>

<panel  header="**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/108#discussion_r1382895902" expanded>

Maybe can rephrase to "Please enter the absolute amount" because positive expense may sound a bit confusing?
</panel>

<panel  header="**17 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/111#discussion_r1383649121" expanded>

Might need to delete the "docs/" part for the link to work. I had to delete mine
</panel>

<panel  header="**18 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/114#discussion_r1384872671" expanded>

Clear elaboration
</panel>

<panel  header="**19 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/114#discussion_r1384875543" expanded>

I believe "maintain" is more appropriate
</panel>

<panel  header="**20 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/63#discussion_r1376299348" expanded>

Thanks for pointing that out!
</panel>

<panel  header="**21 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/issues/95#issuecomment-1794032808" expanded>

Ctrl + C terminates the program immediately but does not produce the above error messages. Will fix the termination issue
</panel>

<panel  header="**22 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/issues/102#issuecomment-1794163104" expanded>

This is likely due to the size of the screen that you are using to view this. Will change the max description length
</panel>

<panel  header="**23 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/110#issuecomment-1794873400" expanded>

> LGTM! Although I am unsure why there is an empty Benedict.txt committed in data folder, should have been gitignored

Oops
</panel>

</panel>


<panel type="info" header="### 17. LIOW..ELLE `@janelleenqi` (16 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/152#discussion_r1385461326" expanded>

I think it would be a good idea to avoid magic numbers. You can do this instead!
<img width="516" alt="image" src="https://github.com/AY2324S1-CS2113-T17-4/tp/assets/110933149/da237ab5-3929-4a61-afba-6c203f32b36c">

</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/152#discussion_r1385467394" expanded>

Structuring a code logically can make it easier for you and other developers to understand your code, and increase its readability! Empty lines can do a lot....
![image](https://github.com/AY2324S1-CS2113-T17-4/tp/assets/110933149/a1a76d38-2551-44f0-a81c-a0ef852b6700)


</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/152#discussion_r1385468187" expanded>

love your attention to detail!
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/152#discussion_r1385473845" expanded>

Specifying what the code is supposed to do can help other developers compare your comments to the implementation to verify whether your implementation is correct! Explaining the rationale for your current implementation would also add in their understanding!
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/157#discussion_r1385984452" expanded>

love your variable namings here! they show the variable's purpose clearly and makes it easy to understand the purpose of this function!
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/157#discussion_r1385987158" expanded>

i think it would be good to name testArray as expectedArray to clearly indicate which array is the expected result. I would suggest adding lines between the expected array and the array from shiftModule, for readability!
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/157#discussion_r1385989984" expanded>

I would recommend adding static variables here like "shiftArgWordsNum" or something, to avoid using magic numbers!
<img width="491" alt="image" src="https://github.com/AY2324S1-CS2113-T17-4/tp/assets/110933149/8ad1190e-d97e-48ef-abbc-4f626c6e9e1e">

</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/157#discussion_r1385991141" expanded>

i think your comments here make it very clear what you are trying to do which is very helpful for other developers :D
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/157#discussion_r1385993889" expanded>

I would recommend refactoring this function as it is 80-100 loc currently. Here's the code quality advice for these situations! 
<img width="703" alt="image" src="https://github.com/AY2324S1-CS2113-T17-4/tp/assets/110933149/642829c5-bfff-41f9-b9e3-8b9f6fa1da21">

</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/38#discussion_r1387387422" expanded>

It would be better to be more specific in your variable naming to show its purpose!
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/38#discussion_r1387389597" expanded>

i would recommend clear naming for this too!
`public boolean modInputIsValid(String[] words, ModuleList plannedModules){`
This would allow the boolean output to be easily understood!
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/38#discussion_r1387390054" expanded>

Good job with starting to refactor your functions!
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/155#discussion_r1387406449" expanded>

Good choice of variable naming here!
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/155#discussion_r1387406848" expanded>

YESS! no magic numbers magic strings!
</panel>

<panel  header="**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/155#discussion_r1387414071" expanded>

not exactly about code quality but you could do
`/* `
`unused code`
`*/ `
Just need to make sure the indentation of /* and */ is as required
</panel>

<panel  header="**16 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/155#discussion_r1387421303" expanded>

good explanations! personally, i think removing "we" can shorten the comments so they can understand faster!
`// get the prerequisite modules of the module, locate prerequisite modules, check if its completed`
`//if not completed, throw error`
</panel>

<panel  header="**17 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/43#issuecomment-1784095519" expanded>

Unable to get ═ and ─ to work. Tests are still required.
</panel>

<panel  header="**18 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/130#issuecomment-1793771760" expanded>

fixes #126 
</panel>

<panel  header="**19 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/154#issuecomment-1798720037" expanded>

Complete feature does not check prereq yet, Planner feature needs a lot of work done
</panel>

<panel  header="**20 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/issues/109#issuecomment-1802461648" expanded>

fixed.
</panel>

<panel  header="**21 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/issues/117#issuecomment-1802462309" expanded>

fixed
</panel>

<panel  header="**22 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/174#issuecomment-1803140599" expanded>

100th!!
</panel>

</panel>


<panel type="info" header="### 18. RYAN.. RUI `@ryanlohyr` (15 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/52#discussion_r1378739846" expanded>

I dont think you should make the start function throw an error
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/52#discussion_r1378740568" expanded>

(should change) can your functions not throw the error outside of the function? so catch the error inside the function itself(can text me if u dont know what I mean regarding this)

(good to have)can all these code be attracted into another function? 
like how i abtract the function computePace in the file
**_rationale_**  to make the switch statement less clunky and more clean to see the other switch statements 
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/152#discussion_r1384667225" expanded>

Explanation on what these numbers will be good, if they are default values , you could state what they mean in the documenatinon of the function 
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/152#discussion_r1384669502" expanded>

I think for this boolean function, checkValidTime is okay, but I think `isValidTime` will be more appropriate? Thoughts?
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/152#discussion_r1384671650" expanded>

so does checkValidTime return true or false if the time is valid? From the code implementation it seems that true is for invalid times. But could that cause confusion for a developer using this function?
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/154#discussion_r1385175550" expanded>

For functions we can try structuring it using happy path principle? So
```
void function(){
   if(fail){
       return;
   }
   happy path;
 
}
```
I think it'll help with readability, thoughts? 
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/154#discussion_r1385176023" expanded>

Love this Class, very nice

</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/154#discussion_r1385177906" expanded>

I think this should try to follow happy path as well? so we catch the out of bounds at the start as well 
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/166#discussion_r1387530977" expanded>

By parsing the command using indexOf('/time'), if the user inputs a valid command without a /time, it would output 'invalid command'. Which will be misleading to the user
```
if (!command.equals("LECTURE") &&
                     !command.equals("TUTORIAL") &&
                     !command.equals("LAB")) {
                 System.out.println("Not a valid command. Please try again!");
                 return;
             }
```

Recommended way to do it 

```
userInput = in.nextLine().trim().replace("\r", "");
String[] wordArray = userInput.split(" ");
String command = wordArray[0].toUpperCase();
```
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/166#discussion_r1387532539" expanded>

will be commenting on both parserTimeForModify and parserDurationForModify for this comment

With the current implementation, you throw an index out of bounds error inside the aforementioned functions, which is ideally suppose is suppose to trigger ur error print statement  
`System.out.println("Not a valid duration. Please try again!");`.

However, it doesnt, it only triggers the print statements if the input is an invalid number, but if it is empty/not a number, it doesnt trigger ur error statement butt instead just throw an OutOfBounds exception as seen on line 136 of this file. 


Both functions should be refactored where invalid number/empty/not a number all triggers the same error message
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/166#discussion_r1387546442" expanded>

parsing of day should be validated in the same as the above &hat; if statements. Did not change this for you yet, but parserDayForModify should be moved up, and only if the day is valid as well, then you enter the switch statement.
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/185#discussion_r1389554720" expanded>

initialiseUser function seems to pile up with a lot of logic(do,while and try catches) which may decrease readability. Maybe we could attract out the different stages in initialiseUser to improve readability?
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/185#discussion_r1389555704" expanded>

Excellent function, with clear logical progression and commenting which prevents the user from tripping up when reading the code. A five year old could read loadSchedule and understand. Nice work
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/185#discussion_r1389556726" expanded>

Love how u abtract this function out 
</panel>

<panel  header="**15 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/185#discussion_r1389557449" expanded>

great use of exceptions
</panel>

<panel  header="**16 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/issues/58#issuecomment-1789192686" expanded>

public void determinePrereq(String module, String major){
        ArrayList&gt;String> prereq = getModulePrereqBasedOnCourse(module, major);
        JSONObject moduleInfo =  getFullModuleInfo(module);
        
        if(moduleInfo == null){
            return;
        }
        
        view.displayMessage(Objects.requireNonNullElseGet(prereq, () -&gt; "Module " + module +
                " has no prerequisites."));
    }

refactor this code to make getModulePreReqBasedon course Throw an error to be watched in determinePreReq
</panel>

<panel  header="**17 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/166#issuecomment-1805944151" expanded>

Overall great work, however some functions could be structured to have more like a "story book" like flow where the reader can have a natural progression of whats going on. Something like the below be a good example
![IMAGE 2023-11-10 23:28:01](https://github.com/AY2324S1-CS2113-T17-4/tp/assets/82641258/2e5c6138-df83-435b-b065-e1b2fbd92f5a)

</panel>

</panel>


<panel type="info" header="### 19. TAN ..THAN `@Jonoans` (14 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/28#discussion_r1361783124" expanded>

Is this intended :|
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/43#discussion_r1367933130" expanded>

Would isAdding or something along those lines be a better for the context
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/78#discussion_r1376357793" expanded>

Missing saveGoal()
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/78#discussion_r1376364962" expanded>

Missing DATE_PATTERN
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/85#discussion_r1382505285" expanded>

Editing the goal of a transaction should perform a lookup for the new goal, it should not edit the description of the existing goal referenced by the Transaction.

This will result in the ability to have multiple goals with the same name, which is not an allowed behaviour.
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/85#discussion_r1382505853" expanded>

Category should be editable too I believe
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/144#discussion_r1386271729" expanded>

Goals and categories are not case-sensitive for other parts of the program. Maybe equalsIgnoreCase would be better?
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/144#discussion_r1386272245" expanded>

There is also a function that does case-insensitive search for goals and categories (StateManager -&gt; getCategoryIndex and getGoalIndex). Maybe it is easier to use that?
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/144#discussion_r1386272996" expanded>

Maybe case-insensitive comparison would be good here
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/144#discussion_r1386273309" expanded>

getCategoryIndex from StateManager might be helpful here, returns -1 if not found.
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/143#discussion_r1388168984" expanded>

Missing space between "unable" and "to"
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/143#discussion_r1388171959" expanded>

If we pass "uncategorised" as value to the add parameter, the error should no longer be UNCATEGORISED_ERROR - "to delete it"
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/143#discussion_r1388872303" expanded>

Add same check for AddExpenseCommand, otherwise "uncategorised" category will be created.
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/166#discussion_r1390754848" expanded>

did you mean "list"?
</panel>

<panel  header="**15 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/9#issuecomment-1763157689" expanded>

Yet to implement adding of expenses and removal commands - do not merge yet :D
</panel>

<panel  header="**16 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/issues/48#issuecomment-1777556897" expanded>

Update transaction list with recurred transactions on program load
</panel>

<panel  header="**17 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/issues/118#issuecomment-1805081088" expanded>

Recurring transactions are generated automatically when the next recurrence dates are reached. The above statement does not reflect the program's functionalities accurately
</panel>

<panel  header="**18 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/issues/126#issuecomment-1805081848" expanded>

Duplicate with #115 
</panel>

</panel>


<panel type="info" header="### 20. CHUA..HENG `@Cazh1` (14 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/57#discussion_r1362145218" expanded>

Perhaps you meant public constructor?
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/57#discussion_r1362146493" expanded>

Noticed missing spacing before curly bracket {
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/57#discussion_r1362149573" expanded>

Perhaps you can consider using a final static String instead of "magic String"?
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/296#discussion_r1387848693" expanded>

perhaps a more appropriate name would be "isRestockHeaderDisplayed"?
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/296#discussion_r1387855235" expanded>

perhaps it would be better to extract this into a method in Ui and prevent "magic Strings"
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/296#discussion_r1387856852" expanded>

Perhaps you should use the Strings stored in Messages.java instead of "magic strings"
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/296#discussion_r1387857908" expanded>

Perhaps you should use the Strings stored in Messages.java instead of "magic strings"
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/296#discussion_r1387858667" expanded>

Perhaps you should use the Strings stored in Messages.java instead of "magic strings"
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/296#discussion_r1387864974" expanded>

Is this space necessary?
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/296#discussion_r1387903219" expanded>

Are the days supposed to match?
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/296#discussion_r1387904981" expanded>

Noticed you missed spacings between aggregatedOrder.getQuantity() == 0
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/296#discussion_r1387906599" expanded>

Magic String
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/321#discussion_r1390334682" expanded>

Perhaps the line is unnecessary as the next author tag is present?
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/321#discussion_r1390349462" expanded>

Perhaps the logic behind this method would cause logical flaws.
If an order was completed yesterday at $2.50, any changes to the price afterwards would cause the already completed order to be flagged as invalid as the price then would not match the most updated price
</panel>

<panel  header="**15 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/167#discussion_r1377096107" expanded>

Please elaborate on how to add this explanation
</panel>

<panel  header="**16 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/328#issuecomment-1807054473" expanded>

Hi, can you please include the starting states of the save text files?
</panel>

<panel  header="**17 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/328#issuecomment-1807056810" expanded>

Thank you. I believe I found the error and rectified in my PR.
</panel>

<panel  header="**18 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/379#issuecomment-1808308791" expanded>

Yes once they edit the string is it hard to differentiate between a very long data or very long hash string. It would be risky to assume one over the other.
Regardless there is a string added to notify users that we found changes to what was supposed to be the hash string
![image](https://github.com/AY2324S1-CS2113-T17-2/tp/assets/82131563/7f2221c6-2494-4098-8844-cf810380626f)

</panel>

</panel>


<panel type="info" header="### 21. OH K.. WEI `@ken-ruster` (13 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/73#discussion_r1371558151" expanded>

Consider wrapping to new line to prevent checkstyle picking this up as being too long if it is
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/73#discussion_r1371560207" expanded>

Consider replacing with `isUpright = (this.playerColor == color)`
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/86#discussion_r1374002757" expanded>

Very comprehensive sequence diagram!
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/86#discussion_r1374004105" expanded>

Instead of doing a hidden connection to File, you could consider removing File from the parameters of Storage and unhide the hidden arrow
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/87#discussion_r1374119628" expanded>

Very comprehensive explanation!
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/87#discussion_r1374120585" expanded>

Great diagrams with color coding!
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/88#discussion_r1374717186" expanded>

Need to fill in author for this fn?
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/98#discussion_r1378586047" expanded>

Good renaming!
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/98#discussion_r1378586430" expanded>

Good use of assertions!
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/171#discussion_r1388910828" expanded>

Very nicely made logo!
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/171#discussion_r1388911479" expanded>

Perhaps consider adding basic installation instructions? Like copy paste the quickstart guide from the UG
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/179#discussion_r1390361040" expanded>

Good use of examples to explain en passant!
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/179#discussion_r1390361112" expanded>

Good use of assert
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/158#discussion_r1385869902" expanded>

The moveopponentpiece exception check is important to remove, otherwise its unable to execute the CPU moves
</panel>

<panel  header="**15 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/158#discussion_r1385877424" expanded>

Because im comparing a ChessBoard to a loaded 2D tile array so idt equals would be a good idea
</panel>

<panel  header="**16 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/158#discussion_r1385881129" expanded>

Not a final variable since the number of moves will change as the game goes on
</panel>

<panel  header="**17 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/158#discussion_r1385883166" expanded>

I was planning on creating the board to be played on based on the moves, this is correct. The board loaded from the file (in the form of ChessTile[][]) is used to check the validity of the current board after it has been loaded.
</panel>

<panel  header="**18 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/158#discussion_r1386118140" expanded>

Also btw java doesn't support overloading operators apparently

</panel>

</panel>


<panel type="info" header="### 22. CHUN..XUAN `@spaceman03` (11 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/22#discussion_r1361540114" expanded>

Can remove unrelated methods
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/22#discussion_r1361540347" expanded>

No need isMarked attribute for Transaction class
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/22#discussion_r1361540799" expanded>

Can remove unrelated methods
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/22#discussion_r1361541613" expanded>

Perhaps can rename 'taskDecoder' to 'transactionDecoder'
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/36#discussion_r1367917686" expanded>

Code is longer than 120 characters which violates the coding standard, perhaps can use 2 lines for the code
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/58#discussion_r1375430204" expanded>

Is this chunk of code to be refactored afterwards?
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/58#discussion_r1375430338" expanded>

Nice to see that you included more JUnit tests!
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/74#discussion_r1378458143" expanded>

I think there is a missing space after the "else"
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/74#discussion_r1378458313" expanded>

Missing space after "else"
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/77#discussion_r1378864051" expanded>

Perhaps you could add a newline between the 2 methods
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/77#discussion_r1378899612" expanded>

Nice to see that you have created a separate file to store the budget. 😃 
</panel>

<panel  header="**12 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/31#issuecomment-1767733777" expanded>

Great!
</panel>

<panel  header="**13 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/issues/88#issuecomment-1793624740" expanded>

Perhaps we could restrict the user to input values smaller than 100,000. So that it will show an error message when user inputs a very large number.
</panel>

<panel  header="**14 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/issues/90#issuecomment-1793629066" expanded>

Restrict users to input only positive values
</panel>

<panel  header="**15 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/issues/93#issuecomment-1793630426" expanded>

Perhaps we should display only certain length of description
</panel>

<panel  header="**16 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/issues/94#issuecomment-1793630647" expanded>

Restrict users to input only positive values for allowances and expenses
</panel>

<panel  header="**17 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/issues/102#issuecomment-1793632889" expanded>

Duplicate issue
</panel>

<panel  header="**18 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/issues/117#issuecomment-1793633464" expanded>

Duplicate issue
</panel>

<panel  header="**19 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/issues/118#issuecomment-1793633927" expanded>

Duplicate issue
</panel>

<panel  header="**20 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/issues/125#issuecomment-1793651214" expanded>

Duplicate issue
</panel>

<panel  header="**21 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/issues/123#issuecomment-1793652139" expanded>

Perhaps we could print a confirmation message rather than the list message
</panel>

<panel  header="**22 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/issues/95#issuecomment-1793667195" expanded>

Rent is a category for expense and not allowance, I suspect the user misunderstood it as an allowance category.
Perhaps we should update our UG to provide more details.
</panel>

<panel  header="**23 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/136#issuecomment-1798147142" expanded>

Closes #95 
</panel>

<panel  header="**24 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/136#issuecomment-1798154633" expanded>

Closes #105
</panel>

<panel  header="**25 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/136#issuecomment-1798382995" expanded>

Closes #110 
</panel>

<panel  header="**26 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/164#issuecomment-1807701956" expanded>

Closes #126 
</panel>

<panel  header="**27 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/issues/84#issuecomment-1809456632" expanded>

Added instructions in UG to avoid such situations.
</panel>

<panel  header="**28 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/issues/86#issuecomment-1809456792" expanded>

Added instructions in UG to avoid such situations.
</panel>

</panel>


<panel type="info" header="### 23. TOH ..HENG `@yicheng-toh` (9 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/44#discussion_r1361460286" expanded>

Good use of error messages here.
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/59#discussion_r1362968136" expanded>

Perhaps we can import the java.util.logging.Level and use Level.INFO here.
```suggestion
        logger.log(Level.INFO, "Editing activity at index " + index);
```
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/59#discussion_r1362968731" expanded>

```suggestion
import java.util.logging.Level;
```
Perhaps, add a import statement here so that there is no need to write the package name for subsequent uses.
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/59#discussion_r1362969754" expanded>

Should the variable be defined here or in the constructor?
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/79#discussion_r1367832264" expanded>

```suggestion
     * Saves data and returns the bye message to be shown to the user.
```
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/133#discussion_r1378587469" expanded>

For ref, it means that there are other image that would explain the 'save other list' right?
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/133#discussion_r1378592897" expanded>

The data extends after the return arrow. Does it mean that it still active after returning to SaveCommand?
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/307#discussion_r1390452835" expanded>

Perhaps using guard clause would be better?
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/307#discussion_r1390452919" expanded>

Could this be in guard clause too?
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/35#discussion_r1359913996" expanded>

For this, would changing the underlying structure for diet goals be better?
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/35#discussion_r1359914998" expanded>

Created issue #38 
</panel>

<panel  header="**12 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/39#discussion_r1360174778" expanded>

Ok I will change them to fail() in the next pull request
</panel>

<panel  header="**13 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/118#discussion_r1375530998" expanded>

Hi, thanks for the suggestion.
There is an outer function that deals with the number format exception that is calling this function.
This function is created due to refactoring.
</panel>

<panel  header="**14 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/308#discussion_r1390549203" expanded>

No. I think I will be asking skylee...
</panel>

<panel  header="**15 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/19#issuecomment-1760907887" expanded>

LGTM. Do take note of the magic numbers '6' and '9' and magic strings used in the repo. 
</panel>

<panel  header="**16 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/48#issuecomment-1765951968" expanded>

We should try to standardise on how to use the logger and what each level means.
</panel>

<panel  header="**17 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/60#issuecomment-1767689053" expanded>

> LGTM, added suggestion to bring the marker parameters to the newly created parameters class.

Raised issue #38 to address it in the next milestone.
</panel>

<panel  header="**18 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/53#issuecomment-1774004594" expanded>

Fixed with PR #81 
</panel>

<panel  header="**19 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/73#issuecomment-1776724677" expanded>

Can I confirm:
1. We will have a abstract goal class for all sleep/activity/diet goals to inherit from
2. The command to set goals will be changed
3.  The -weekof variable is compulsory. and it would be indicated by the '-' which is not found in other commands.
4. The date input is strictly dd-mm-yyyy.
</panel>

<panel  header="**20 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/37#issuecomment-1784264900" expanded>

There is no need to do this optimisation as the array list is of small size and the optimisation could not really be observed.
</panel>

<panel  header="**21 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/136#issuecomment-1788803057" expanded>

Implementation:
Healthy goal and unhealthy diet goals will inherit from abstract class diet goals
due to shifting window goals, unhealthy diet goals will never be achieved.
In place of isAchieved function, unhealthy diet goals will have isStillAchieved function.

Things to take note:
There could not be instance of healthy diet goal and unhealthy diet goal at the same time.
e.g. healthy fats goal for daily means that there would not be unhealthy fats goal for weekly.
affects set diet goal command and edit diet goal command.

New command/flag would be needed for this operation. likely with a unhealthy flag.



</panel>

<panel  header="**22 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/222#issuecomment-1793271855" expanded>

Hi, thanks for your feedback. However, the command to list diet goal is list-diet-goal.
The list diet command is for the meals that you have logged.
</panel>

<panel  header="**23 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/219#issuecomment-1793273031" expanded>

As per error message, diet goal for carb is not present. This is due to the lack of the example. refer to issue #221 
</panel>

<panel  header="**24 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/216#issuecomment-1793273538" expanded>

This is expected. Our app only support one diet goal of the same type. It does not make sense to have diet goal of 100 then the same diet goal or 200. 
</panel>

<panel  header="**25 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/206#issuecomment-1793273827" expanded>

No. we only support integer. Round off your value to the integer. 

</panel>

<panel  header="**26 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/205#issuecomment-1793274290" expanded>

it is not list-diet-goals but list-diet-goal
</panel>

<panel  header="**27 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/203#issuecomment-1793274481" expanded>

similar to issue #221 
</panel>

<panel  header="**28 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/188#issuecomment-1793275804" expanded>

Look at the example command. It says list-diet-goal
</panel>

<panel  header="**29 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/162#issuecomment-1793277355" expanded>

![image](https://github.com/AY2324S1-CS2113-T17-1/tp/assets/75836313/64c3e751-6770-4c78-812b-f371b28af199)
It is mentioned that at least one is supported!
</panel>

<panel  header="**30 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/203#issuecomment-1793277502" expanded>

Repeated
</panel>

<panel  header="**31 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/203#issuecomment-1793386353" expanded>

It is below the sleep user guide. You clearly did not read properly!
</panel>

<panel  header="**32 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/221#issuecomment-1793409698" expanded>

The example is found at the bottom of the UG.
Mentioned in pull request #231 
</panel>

<panel  header="**33 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/206#issuecomment-1793409750" expanded>


Mentioned in pull request #231 
</panel>

<panel  header="**34 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/216#issuecomment-1793409821" expanded>

This is intended. wrong severity raised. go away.
It is a YOU problem. You did not read the user guide properly.
</panel>

<panel  header="**35 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/222#issuecomment-1793409994" expanded>

This is a YOU problem. You did not read the user guide properly. GO AWAY!
</panel>

<panel  header="**36 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/219#issuecomment-1793410326" expanded>

THIS IS  A YOU PROBLEM. PLEASE READ THE USER GUIDE PROPERLY!
But appreciate you putting severity low instead of the nonsensical medium by other testers.
</panel>

<panel  header="**37 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/203#issuecomment-1793411261" expanded>

The example is found at the bottom of the UG. 
Mentioned in pull request #231 
</panel>

<panel  header="**38 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/205#issuecomment-1793411440" expanded>

This is mentioned in the example code. And how you dare raised a medium severity when you choose to take the code not from the examples!!!!!!!!!!
Mentioned in pull request #231 
</panel>

<panel  header="**39 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/162#issuecomment-1793411979" expanded>

Please read the userguide properly!!!! HOW DARE YOU HAVE THE GUTS TO PUT A FREAKING MEDIUM PRIORITY WHEN IT IS A YOU PROBLEM!!!!
Mentioned in pull request #231 
</panel>

<panel  header="**40 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/227#issuecomment-1793426869" expanded>

To include parsing and unparsing of data.
</panel>

<panel  header="**41 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/218#issuecomment-1793428596" expanded>

Same as issue #227 
</panel>

<panel  header="**42 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/215#issuecomment-1793428941" expanded>

Same as #227 
</panel>

<panel  header="**43 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/213#issuecomment-1793429113" expanded>

Similar to #217 
</panel>

<panel  header="**44 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/207#issuecomment-1793429903" expanded>

Similar to issue #211 
</panel>

<panel  header="**45 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/209#issuecomment-1793430048" expanded>

Similar to issue #227 
</panel>

<panel  header="**46 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/200#issuecomment-1793430666" expanded>

Same as #211 for diet
</panel>

<panel  header="**47 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/173#issuecomment-1793431305" expanded>

Same as issue #227 
</panel>

<panel  header="**48 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/191#issuecomment-1793432122" expanded>

Maybe indicate that all arguments are necessary and give an example where one can set the value to 0 if diet does not contain any of the nutrient
</panel>

<panel  header="**49 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/190#issuecomment-1793432436" expanded>

Same as issue #198 
</panel>

<panel  header="**50 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/187#issuecomment-1793432815" expanded>

Same as issue #227 
</panel>

<panel  header="**51 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/185#issuecomment-1793433304" expanded>

Same as #194. Tag you again because there is suggestion given. 
</panel>

<panel  header="**52 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/184#issuecomment-1793433472" expanded>

Erm... did the file get saved?
</panel>

<panel  header="**53 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/183#issuecomment-1793433771" expanded>

Same as #226 
</panel>

<panel  header="**54 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/181#issuecomment-1793433859" expanded>

Same as #194 
</panel>

<panel  header="**55 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/177#issuecomment-1793434425" expanded>

This is working as expected. WE ARE BEING KIND FOR CARELESS PPL LIKE YOU TO RUN OUR APP!
</panel>

<panel  header="**56 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/174#issuecomment-1793434762" expanded>

See how you want to deal with this tester....
</panel>

<panel  header="**57 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/172#issuecomment-1793434880" expanded>

Similar to issue #198
</panel>

<panel  header="**58 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/171#issuecomment-1793435163" expanded>

I think it would be sufficient to indicate in the UG. Those who swim that long are likely dead.
</panel>

<panel  header="**59 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/168#issuecomment-1793435871" expanded>

Same as issue #186 
</panel>

<panel  header="**60 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/167#issuecomment-1793435960" expanded>

Same as issue #227 
</panel>

<panel  header="**61 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/165#issuecomment-1793436415" expanded>

Same as issue #186 
</panel>

<panel  header="**62 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/163#issuecomment-1793436762" expanded>

I think it is because of the space. Maybe mention in the UG or edit the code?
</panel>

<panel  header="**63 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/160#issuecomment-1793436934" expanded>

We cannot let anything crash the app. Need to catch this, unfortunately.
</panel>

<panel  header="**64 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/217#issuecomment-1793439094" expanded>

Those who sleep so long are likely in a coma or in some freezing chamber. You may update UG to reflect it.
</panel>

<panel  header="**65 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/220#issuecomment-1793439379" expanded>

You can update the UG to reflect minimum time. A blink is not considered a sleep anyways.
</panel>

<panel  header="**66 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/182#issuecomment-1793439740" expanded>

It does not crash should be fine. If it is difficult to code it out, mention it in the UG that the format must be strictly followed.
</panel>

<panel  header="**67 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/240#issuecomment-1793645356" expanded>

The issue with this is due to the fact that the goal is sliding while the diet is fixed. Yesterday, my goal is achieved for daily goal because of the next meal entry.  However, that meal is not relevant today.

Therefore, if there are no edits on the input, the next trigger will happen in 6 days due to the weekly goal.
</panel>

<panel  header="**68 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/144#issuecomment-1797807115" expanded>

Completed by #239 
</panel>

<panel  header="**69 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/240#issuecomment-1800861202" expanded>

To remove the tests from the text ui
</panel>

<panel  header="**70 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/175#issuecomment-1803033177" expanded>

This is fixed at #255 
</panel>

<panel  header="**71 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/257#issuecomment-1803233442" expanded>

Good point. Let me update it too!
</panel>

<panel  header="**72 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/252#issuecomment-1806759357" expanded>

Nope not going to implement this.
</panel>

<panel  header="**73 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/240#issuecomment-1806780331" expanded>

Updated in pull request #268 
</panel>

<panel  header="**74 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/134#issuecomment-1806780649" expanded>

This is not needed since the way diet goal is parsed is different from how activity goals are parsed.
</panel>

<panel  header="**75 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/286#issuecomment-1807075179" expanded>

Not found on latest version
</panel>

<panel  header="**76 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/289#issuecomment-1807075231" expanded>

Not found in latest version
</panel>

<panel  header="**77 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/287#issuecomment-1807075298" expanded>

Perhaps you could include it in the UG?
</panel>

<panel  header="**78 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/312#issuecomment-1807353775" expanded>

so 
diet => [Diet]
activity => [Activity]
sleep => [Sleep]?
Then their corresponding goals too?
</panel>

<panel  header="**79 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/318#issuecomment-1807459964" expanded>

It is indicated in the UG that it only takes on an integer.
</panel>

<panel  header="**80 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/319#issuecomment-1807460382" expanded>

fats is a noun and fat is an adjective. so I  believe the use of fats makes more sense.
</panel>

<panel  header="**81 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/324#issuecomment-1807463942" expanded>

Edit function only adjusts target value, it does not change the type of diet goal
</panel>

<panel  header="**82 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/pull/340#issuecomment-1808259943" expanded>

However, it failed one test case, how can I rectify it?
</panel>

<panel  header="**83 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-1/tp/issues/350#issuecomment-1808544126" expanded>

Addressed by #353 
</panel>

</panel>


<panel type="info" header="### 24. YEON..JEHO `@ICubE-` (8 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/pull/47#discussion_r1362420713" expanded>

I think you should rollback this.
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/pull/75#discussion_r1366387552" expanded>

You should use exception, not assertion, for user error.
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/pull/158#discussion_r1382338825" expanded>

Can you change this not to use magic literals?
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/pull/158#discussion_r1382339216" expanded>

Try to handle incorrect gender input. I think inputs like "Q" or "NoGender" should be rejected.
Also no magic literals, plz.
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/pull/256#discussion_r1387623531" expanded>

Can you change this method not to refer Ui? String parameter for this method.
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/pull/256#discussion_r1387624366" expanded>

Receive input from user here, and give it to userprofile.profileSettings as a parameter.
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/pull/256#discussion_r1387624952" expanded>

Maybe a new method in Ui for userprofile input?
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/pull/256#discussion_r1387640525" expanded>

Sry for one more comment, can you insert this loop in startProfile? Also making isValidInput as local variable.
</panel>

<panel  header="**9 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/pull/25#issuecomment-1760655837" expanded>

I don't see any files changed. Is this PR correct?
</panel>

<panel  header="**10 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/pull/30#issuecomment-1763702050" expanded>

Please merge PR only if CI test passes.
</panel>

<panel  header="**11 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/pull/34#issuecomment-1764702052" expanded>

Implements #9, #10, #16.
</panel>

<panel  header="**12 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/41#issuecomment-1766062425" expanded>

Done for my codes.
</panel>

<panel  header="**13 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/pull/49#issuecomment-1767542174" expanded>

Implementes #12.
</panel>

<panel  header="**14 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/pull/47#issuecomment-1767543067" expanded>

Implements #11, #17.
</panel>

<panel  header="**15 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/11#issuecomment-1767543678" expanded>

Done by @farissirraj.
</panel>

<panel  header="**16 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/40#issuecomment-1767938155" expanded>

Done: Handle erroneous input and provide help for AddMealCommand (by @NgLixuanNixon)
Done: Provide help for DeleteMealCommand (by @ICubE-)

NOT done: Handle erroneous input for DeleteMealCommand
Will open new issue (#58) and close this issue.
</panel>

<panel  header="**17 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/82#issuecomment-1772131984" expanded>

What about storing all the input that user has given? (like meals and workouts)
</panel>

<panel  header="**18 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/82#issuecomment-1772135052" expanded>

> Sure, should we add on those in v2.1 or just do it for v2.0 as well.

I guess v2.1 is really not for adding features, so we should decide whether to implement on v2.0 or not.
</panel>

<panel  header="**19 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/82#issuecomment-1772139411" expanded>


> Ok, possible to save profile data, and meals and workouts in two separate files? So when loading the file contents in it will be easier. One would load to userprofile the other to the meals and workouts list

Cool. You can separate meals and workouts too.
</panel>

<panel  header="**20 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/pull/85#issuecomment-1772292297" expanded>

@J0shuaLeong Let me know if you want to implement TODO stuffs that I made.
</panel>

<panel  header="**21 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/152#issuecomment-1790151972" expanded>

https://docs.oracle.com/javase%2F7%2Fdocs%2Fapi%2F%2F/java/util/Scanner.html#nextLine()
https://docs.oracle.com/javase%2F7%2Fdocs%2Fapi%2F%2F/java/util/NoSuchElementException.html
</panel>

<panel  header="**22 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/pull/158#issuecomment-1793370892" expanded>

Oh, also plz change UG, too.
</panel>

<panel  header="**23 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/164#issuecomment-1793409525" expanded>

Duplicate of #162 
</panel>

<panel  header="**24 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/163#issuecomment-1793409753" expanded>

Duplicate of #162 
</panel>

<panel  header="**25 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/165#issuecomment-1793409801" expanded>

Duplicate of #161 
</panel>

<panel  header="**26 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/176#issuecomment-1793410583" expanded>

Duplicate of #162 
</panel>

<panel  header="**27 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/173#issuecomment-1793410983" expanded>

Duplicate of #166 and #169 
</panel>

<panel  header="**28 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/178#issuecomment-1793411178" expanded>

Duplicate of #174 
</panel>

<panel  header="**29 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/179#issuecomment-1793411317" expanded>

Duplicate of #174 
</panel>

<panel  header="**30 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/181#issuecomment-1793411518" expanded>

Duplicate of #174 
</panel>

<panel  header="**31 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/184#issuecomment-1793411799" expanded>

Duplicate of #174 
</panel>

<panel  header="**32 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/187#issuecomment-1793412091" expanded>

Duplicate of #188 
</panel>

<panel  header="**33 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/191#issuecomment-1793412297" expanded>

Duplicate of #188 
</panel>

<panel  header="**34 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/193#issuecomment-1793412485" expanded>

Duplicate of #177 
</panel>

<panel  header="**35 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/197#issuecomment-1793412771" expanded>

Duplicate of #188 
</panel>

<panel  header="**36 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/201#issuecomment-1793413048" expanded>

Duplicate of #174 
</panel>

<panel  header="**37 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/202#issuecomment-1793413928" expanded>

Duplicate of #195 
</panel>

<panel  header="**38 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/205#issuecomment-1793414075" expanded>

Duplicate of #195 
</panel>

<panel  header="**39 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/206#issuecomment-1793414243" expanded>

Duplicate of #174 
</panel>

<panel  header="**40 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/207#issuecomment-1793414415" expanded>

Duplicate of #188 
</panel>

<panel  header="**41 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/218#issuecomment-1793415307" expanded>

Duplicate of #188 
</panel>

<panel  header="**42 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/159#issuecomment-1793415516" expanded>

Duplicate of #161 
</panel>

<panel  header="**43 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/175#issuecomment-1795010821" expanded>

Duplicate of #168 
</panel>

<panel  header="**44 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/190#issuecomment-1795013109" expanded>

Duplicate of #168 
</panel>

<panel  header="**45 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/199#issuecomment-1795016744" expanded>

Duplicate of #168 
</panel>

<panel  header="**46 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/210#issuecomment-1795018492" expanded>

Duplicate of #168 
</panel>

<panel  header="**47 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/214#issuecomment-1795019207" expanded>

Duplicate of #168 
</panel>

<panel  header="**48 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/217#issuecomment-1795019928" expanded>

Duplicate of #168 
</panel>

<panel  header="**49 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/168#issuecomment-1795335879" expanded>

Already solved
</panel>

<panel  header="**50 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/pull/228#issuecomment-1797824318" expanded>

Please update UG.
</panel>

<panel  header="**51 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/203#issuecomment-1797865104" expanded>

Duplicate of #195 
</panel>

<panel  header="**52 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/209#issuecomment-1797865896" expanded>

Duplicate of #171 
</panel>

</panel>


<panel type="info" header="### 25. LOKE.. XIA `@yingx9` (8 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/22#discussion_r1359348489" expanded>

I checked what "Exception in thread "main" java.util.NoSuchElementException: No line found" means. I think you need to  do something like while (myScanner.hasNextLine()) then return nextLine(). If not you'll get an error for the test cases. Maybe can refer to this [link](https://stackoverflow.com/questions/7209110/java-util-nosuchelementexception-no-line-found)
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/38#discussion_r1360282679" expanded>

Your output has no line divider " "____________________________________________________________"  but your expecting a line divider.
![image](https://github.com/AY2324S1-CS2113T-W11-1/tp/assets/84222810/4855b7c8-0bcf-4e0b-800f-75d0f1e389cd)

</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/38#discussion_r1360334514" expanded>

Do you want to extract this to a new class like TestUtils then put this code as a method which returns the output, so all the test methods can use this to get the output message. If not this code repeats a lot
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/38#discussion_r1360335571" expanded>

Also I want to use this part for my testing too 👀 
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/69#discussion_r1370213989" expanded>

Actually for CS2113T we are still targeting system librarians specifically. The general librarians is just for CS2101 side 
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/69#discussion_r1370225286" expanded>

The target user and value proposition is last time we submitted:

Target User:
System librarians who prefer CLI over GUI and are responsible for inventory, event management, and assisting patrons.

Value Proposition:
SysLib CLI is a robust command-line tool designed for system librarians to efficiently handle inventory, events, and patron assistance. With quick command-based actions, they can manage library's resources and events seamlessly. Simplify administrative tasks, so they can focus on serving patrons better.

anyway u can change it whenever you do another update to the guide
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/166#discussion_r1387794662" expanded>

![image](https://github.com/AY2324S1-CS2113T-W11-1/tp/assets/84222810/31969718-24e9-4e3b-91a5-6c74d2d126c5)

I think its better to make the grey activation bar the same colour as the Storage activation bar, since its calling its own method 
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/166#discussion_r1387796789" expanded>

![image](https://github.com/AY2324S1-CS2113T-W11-1/tp/assets/84222810/2342eee6-d372-4a3e-8a05-a6c2d4427844)

![image](https://github.com/AY2324S1-CS2113T-W11-1/tp/assets/84222810/c950130b-848f-45e8-8c44-c920d576594c)


If you move the order from Scanner, Resource, Event to Resource, Event, Scanner you might be able to fix the overlapping methods and stuff. To look neater
</panel>

<panel  header="**9 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/17#issuecomment-1762748196" expanded>

Closing PR due to conflicts
</panel>

<panel  header="**10 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/18#issuecomment-1762786932" expanded>

Closing due to conflicts.
</panel>

<panel  header="**11 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/27#issuecomment-1762891845" expanded>

Looks great, no issues!
</panel>

<panel  header="**12 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/28#issuecomment-1762892925" expanded>

Nice!
</panel>

<panel  header="**13 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/30#issuecomment-1762920759" expanded>

Good code!
</panel>

<panel  header="**14 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/32#issuecomment-1763290661" expanded>

No issues with the code!
</panel>

<panel  header="**15 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/38#issuecomment-1764469333" expanded>

All looks good now!
</panel>

<panel  header="**16 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/42#issuecomment-1764925710" expanded>

Looks good! 
</panel>

<panel  header="**17 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/44#issuecomment-1766101790" expanded>

No issues found!
</panel>

<panel  header="**18 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/54#issuecomment-1766637051" expanded>

Looks spectacular!
</panel>

<panel  header="**19 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/47#issuecomment-1770186811" expanded>

Looks good, nice use of validation!
</panel>

<panel  header="**20 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/68#issuecomment-1777250054" expanded>

Looks good!
</panel>

<panel  header="**21 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/69#issuecomment-1777251019" expanded>

Nice update to developer guide 
</panel>

<panel  header="**22 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/74#issuecomment-1780497349" expanded>

Looks good!
</panel>

<panel  header="**23 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/76#issuecomment-1780566862" expanded>

Nice addition to the DG!
</panel>

<panel  header="**24 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/77#issuecomment-1782466534" expanded>

Great details!
</panel>

<panel  header="**25 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/88#issuecomment-1786895610" expanded>

Nice, no issues! Just remember Javadoc comments for methods need to start likes "Matches..." "Checks"... but those are easy fixes 
</panel>

<panel  header="**26 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/93#issuecomment-1787213976" expanded>

Don't merge please (its not going to pass the checks anyway)
</panel>

<panel  header="**27 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/90#issuecomment-1787249574" expanded>

Good fixes!
</panel>

<panel  header="**28 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/104#issuecomment-1790136598" expanded>

Great diagram!
</panel>

<panel  header="**29 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/105#issuecomment-1790140164" expanded>

Great code! LGTM
</panel>

<panel  header="**30 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/108#issuecomment-1790160469" expanded>

Nice change!
</panel>

<panel  header="**31 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/109#issuecomment-1790592394" expanded>

Good additions!
</panel>

<panel  header="**32 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/112#issuecomment-1792303977" expanded>

Great addition!
</panel>

<panel  header="**33 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/118#issuecomment-1793325426" expanded>

My getReceivedDate again...run the ./runtest.bat and replace the EXPECTED.txt with the results should pass the checks 

Its cause its gets the current System date...Maybe I should change that lol 
</panel>

<panel  header="**34 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/118#issuecomment-1793351315" expanded>

Ok, no issues now!
</panel>

<panel  header="**35 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/135#issuecomment-1793436692" expanded>

Nice fix!
</panel>

<panel  header="**36 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/138#issuecomment-1793646521" expanded>

Great change!
</panel>

<panel  header="**37 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/139#issuecomment-1793655052" expanded>

Nice addition!
</panel>

<panel  header="**38 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/142#issuecomment-1793765502" expanded>

Good bug fix!
</panel>

<panel  header="**39 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/150#issuecomment-1797928715" expanded>

Great diagram!
</panel>

<panel  header="**40 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/151#issuecomment-1798065052" expanded>

Great use of list!
</panel>

<panel  header="**41 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/152#issuecomment-1798362252" expanded>

Great update!
</panel>

<panel  header="**42 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/154#issuecomment-1799253058" expanded>

Nice, no issues!
</panel>

<panel  header="**43 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/155#issuecomment-1799254341" expanded>

Nice feature addition!
</panel>

<panel  header="**44 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/158#issuecomment-1803179975" expanded>

Nice use of logging!
</panel>

<panel  header="**45 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/160#issuecomment-1803376346" expanded>

Nice addition!
</panel>

<panel  header="**46 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/166#issuecomment-1803584020" expanded>

Nice additions to DG!
</panel>

<panel  header="**47 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/170#issuecomment-1805175805" expanded>

Nice PPP!
</panel>

<panel  header="**48 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/171#issuecomment-1805672073" expanded>

Great fix!
</panel>

<panel  header="**49 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/173#issuecomment-1806698720" expanded>

Great addition to UG!
</panel>

<panel  header="**50 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/174#issuecomment-1806698786" expanded>

Nice update to DG!
</panel>

<panel  header="**51 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/175#issuecomment-1806988617" expanded>

Nice addition of Message class!
</panel>

<panel  header="**52 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/178#issuecomment-1807096977" expanded>

Great additions!
</panel>

<panel  header="**53 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/181#issuecomment-1807148571" expanded>

Great diagram!
</panel>

<panel  header="**54 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/186#issuecomment-1807169847" expanded>

Nice diagram!
</panel>

<panel  header="**55 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/188#issuecomment-1807409108" expanded>

Good documentation!
</panel>

<panel  header="**56 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/191#issuecomment-1807536668" expanded>

Great additions!
</panel>

<panel  header="**57 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/194#issuecomment-1807631367" expanded>

Nice documentation!
</panel>

<panel  header="**58 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/196#issuecomment-1807685828" expanded>

Nice change!
</panel>

<panel  header="**59 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/192#issuecomment-1807687302" expanded>

Great addititons!
</panel>

<panel  header="**60 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/200#issuecomment-1808096835" expanded>

Nice!
</panel>

<panel  header="**61 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/199#issuecomment-1808102291" expanded>

Nice update!
</panel>

<panel  header="**62 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/202#issuecomment-1808233869" expanded>

Great tests!
</panel>

<panel  header="**63 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/204#issuecomment-1808336754" expanded>

Great!
</panel>

<panel  header="**64 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/205#issuecomment-1808393890" expanded>

Nice bug catch!
</panel>

<panel  header="**65 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/207#issuecomment-1808482819" expanded>

Great!
</panel>

<panel  header="**66 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/215#issuecomment-1809466681" expanded>

Nice!
</panel>

</panel>


<panel type="info" header="### 26. TANG..NICE `@ShaniceTang` (6 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/283#discussion_r1388337363" expanded>

Maybe add a whitespace here? :)

```suggestion
    public Menu loadMenu() {
```
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/283#discussion_r1388339521" expanded>

Maybe add a whitespace here too? :)

```suggestion
public class CorruptedDataException extends Exception {
```
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/322#discussion_r1390345276" expanded>

Perhaps you could pass the throwable for a more descriptive log message?
```suggestion
            logger.log(Level.WARNING, "Invalid dish index type!", e);
```
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/322#discussion_r1390345455" expanded>

Perhaps you could pass in the exception thrown here too?
```suggestion
            logger.log(Level.WARNING, "Invalid price!", e);
```
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/324#discussion_r1390349165" expanded>

Would it be better to write this as a single line?
```suggestion
        return encodedStringArrayList.isEmpty();
```
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/364#discussion_r1391098802" expanded>

Ooo I didn't know you could do that
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/119#discussion_r1371725022" expanded>

The regex I used is able to take in multiple ingredients while the regex you suggested only takes in one ingredient
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/175#discussion_r1377166850" expanded>

Perhaps you misunderstood, it was a grayed out and unused variable that I removed
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/175#discussion_r1377170201" expanded>

Perhaps you misunderstood, this function is for building the string of bought ingredients every iteration and it would be messy to not abstract it out.
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/175#discussion_r1377173518" expanded>

Perhaps you have missed its usage in the if condition
</panel>

<panel  header="**11 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/361#discussion_r1390924156" expanded>

Noted! I have made the changes :)
</panel>

<panel  header="**12 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/349#issuecomment-1807443399" expanded>

Ah oops my bad, I must have forgotten about it. The class is not needed I will delete it.
</panel>

<panel  header="**13 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/346#issuecomment-1807515908" expanded>

Could we use printLine() rather than a new line? It might be a clearer divider. 

Thank you @ziyi105 for helping us add! :D
</panel>

<panel  header="**14 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/360#issuecomment-1807890468" expanded>

Links still broken, reopening issue.
</panel>

<panel  header="**15 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/371#issuecomment-1808366267" expanded>

Hellos I've changed my buy ingredient regex to accept negative quantity. Maybe there is some mix up with the error handling in parseIngredients?
![image](https://github.com/AY2324S1-CS2113-T17-2/tp/assets/110757597/7842b983-4d45-49df-88b3-fa790f0e386f)

</panel>

</panel>


<panel type="info" header="### 27. CHAN..IANG `@ChoonSiang` (5 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/11#discussion_r1360500360" expanded>

Remove unused commented code
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/32#discussion_r1362142688" expanded>

The command should be 'bye'
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/32#discussion_r1362143242" expanded>

Likewise, command should be 'bye'
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/137#discussion_r1384727449" expanded>

Can remove proposed since it is already implemented?
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/137#discussion_r1384728977" expanded>

Would it be better to remove Implemented?
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/82#discussion_r1377284143" expanded>

Ok. Changed to a lighter colour.
</panel>

<panel  header="**7 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/issues/124#issuecomment-1798337419" expanded>

Not a bug. What if the user just so happens to have 2 subscriptions for the same service? Then it should not be counted as duplicated.
</panel>

<panel  header="**8 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/issues/123#issuecomment-1798341422" expanded>

Unable to reproduce the crash
</panel>

<panel  header="**9 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/issues/100#issuecomment-1798344596" expanded>

User is not using the arguments properly. "/amount" instead of "/ amount". There should be no space in between / and the argument name.
</panel>

<panel  header="**10 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/issues/106#issuecomment-1798347050" expanded>

As stated in UG that additional supplied arguments will be ignored.
</panel>

</panel>


<panel type="info" header="### 28. WOO ..NING `@WooKaiNing` (5 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/33#discussion_r1362113555" expanded>

Should we consider making input case sensitive to enhance user experience (for future implementation)? For instance, input "addIncome", "ADDINCOME", "AddIncome" can all be recognised as the same command regardless of capitalization?
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/33#discussion_r1362161003" expanded>

Agree that this might be a good implementation! Alternatively, if we do not want to represent the amount as "-" or "+", we could maybe include "(E)" or "(I)" respectively before the description to indicate whether it is an income/expense?
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/46#discussion_r1368088461" expanded>

since getProgress == 0 indicates that full amount of budget is available for spending, won't budgetProgress.getProgress() &gt; 0.25 indicate that there's still substantial amount remaining?

should it be budgetProgress.getProgress() > 0.75 instead for the warning to be issued...?
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/68#discussion_r1377839944" expanded>

trivial error: typo in word "budget"
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/68#discussion_r1377843017" expanded>

may want to give slightly more details on what "good cushion" is ie. percentage of budget progress before warning is triggered?
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/52#discussion_r1370493216" expanded>

paiseh this method not required i forgot to remove
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/52#discussion_r1370494335" expanded>

yup that was what i thought, but is it valid though? should i js remove the assertion
</panel>

<panel  header="**8 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/32#issuecomment-1769859216" expanded>

Implemented CurrentDateUpdater class to dynamically update EXPECTED.TXT file with current date (for input in INPUT.TXT where date is not specified). However, this somehow only works for Java CI / build (ubuntu-latest) (pull_request) and Java CI / build (macos-latest) (pull_request).

Hence, modified input.txt to only include expense/income input with specified date for now, will need to further refine code such that runtest.bat() works too.

</panel>

<panel  header="**9 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/32#issuecomment-1770993653" expanded>

Fixes #45 
</panel>

</panel>


<panel type="info" header="### 29. SAUN.. MIN `@NaychiMin` (4 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/313#discussion_r1390071375" expanded>

May I clarify where this new Overriden function of 'equals' is used? It does not seem to be used in any of the changes you made in this PR either unless I missed it while looking through :) Perhaps you may want to take it out if it is not used. 
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/313#discussion_r1390081102" expanded>

Okay, thank you for pointing that out!
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/344#discussion_r1390552831" expanded>

```suggestion
    public static final String SAVE_FILE_FORMAT_ORDERS = "Format for Orders.txt: \n"
            + "{Order Day} | {Dish Name} | {Dish Order Qty} | {Dish Price} | {Order Complete Status}";
```
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/361#discussion_r1390920233" expanded>

Just a suggestion! Maybe you should standardise it with your other error texts as such "menu.txt: Missing ingredients, this dish will be removed -&gt; "; 
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/170#discussion_r1377032393" expanded>

Removed! Thank you :)
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/296#discussion_r1387869771" expanded>

thank you for pointing this out!
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/296#discussion_r1387873085" expanded>

Initially, I felt like it would be easier to visualise the expected output for the junit test if it was displayed as such but I agree with what you brought up. Thank you!
</panel>

<panel  header="**8 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/296#discussion_r1387877661" expanded>

Thank you for reminding me!
</panel>

<panel  header="**9 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/321#discussion_r1390360143" expanded>

Thank you for highlighting this feature flaw! I have made the necessary changes!
</panel>

<panel  header="**10 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/pull/321#discussion_r1390360160" expanded>

Okay noted. Changes made.
</panel>

<panel  header="**11 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/323#issuecomment-1807296417" expanded>

Yep, I was thinking the same too! I have implemented it in PR #321 and was merged into the main branch last night :) 
</panel>

<panel  header="**12 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/376#issuecomment-1808234317" expanded>

Thank you for bringing this up! However, I feel that the current message might be more informative for the user as it entails what is listed below and the significance of listing it ("for the next order"). Would changing dishes to "each dish" make it slightly clearer?
"Listed below are the availability of each dish for the next order!"
</panel>

<panel  header="**13 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-2/tp/issues/376#issuecomment-1808282262" expanded>

Okay! Thank you for the clarification!
</panel>

</panel>


<panel type="info" header="### 30. ONG .. KIT `@choonkit-nus` (3 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/45#discussion_r1369197123" expanded>

Nice, these expense categories are likely common for students to use :)
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/45#discussion_r1369200011" expanded>

Good use of exception to catch the case where use entered an unknown category which results in an error message prompt that guides the user on the proper usage too :D
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/45#discussion_r1369206533" expanded>

Since there's a new "category" field for transactions, perhaps there is a need to modify the help command message to reflect the expected use of this too.
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/36#discussion_r1367919278" expanded>

Ok edited, hopefully it works now!
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/77#discussion_r1378880588" expanded>

Oh ok, will edit it to make it more readable!
</panel>

<panel  header="**6 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/issues/121#issuecomment-1804287337" expanded>

Updated the budget feature to only accept float value that doesn't exceed 2 d.p. 

In the Parser.java file, the parseBudget() method now checks and ensure that the user entered float amount does not exceed the 2 d.p. which now then rejects these small floating point values.
</panel>

<panel  header="**7 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/issues/88#issuecomment-1804344892" expanded>

Added a check to the parseAllowance(), parseExpense() and parseBudget() methods in Parser.java to ensure that the following conditions are met for the user entered amount. The allowance, expense and budget amount is positive, less than 100000, and has at most two decimal places. This ensures that arbitrary large or small float amounts are rejected and not used. Hence, solving this issue.
</panel>

<panel  header="**8 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/issues/113#issuecomment-1804345098" expanded>

This is potentially a result of utilizing arbitrary large float amounts for transactions. Added a check to the parseAllowance(), parseExpense() and parseBudget() methods in Parser.java to ensure that the following conditions are met for the user entered amount. The allowance, expense and budget amount is positive, less than 100000, and has at most two decimal places. This ensures that arbitrary large or small float amounts are rejected and not used.
</panel>

<panel  header="**9 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/issues/119#issuecomment-1804345175" expanded>

This is potentially a result of utilizing arbitrary large float amounts for transactions. Added a check to the parseAllowance(), parseExpense() and parseBudget() methods in Parser.java to ensure that the following conditions are met for the user entered amount. The allowance, expense and budget amount is positive, less than 100000, and has at most two decimal places. This ensures that arbitrary large or small float amounts are rejected and not used.
</panel>

<panel  header="**10 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/issues/94#issuecomment-1804359346" expanded>

Updated the parseAllowance(), parseExpense() methods in Parser.java to ensure that the allowance and expense amounts are positive. Hence, solving this issue.
</panel>

<panel  header="**11 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/issues/101#issuecomment-1804453280" expanded>

Floating-point values (which are used for the allowance and expense amount) can be represented using scientific E-notation. In E-notation, a number is represented by digits, followed by an e or an E, followed by the number of times to multiply it by 10. 
For example, 3.125e7 represents 31250000. This value is derived by converting the e-notation to a calculation: 3.125 * 10&hat;7.
Conversely, 0.00000000000000003 can be written as 3e-17. Here, 10 is raised to the -17 power.

However, I have added a check to the parseAllowance(), parseExpense() and parseBudget() methods in Parser.java to ensure that the following conditions are met for the user entered amount. The allowance, expense and budget amount is positive, less than 100000, and has at most two decimal places. This ensures that arbitrary large or small float amounts are rejected and not used. Therefore, addressing this issue.
</panel>

<panel  header="**12 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/issues/107#issuecomment-1804507001" expanded>

Added a check to the parseBudget() method in Parser.java to ensure that the following conditions are met for the user entered amount. The budget amount is positive, less than 100000, and has at most two decimal places. This ensures that arbitrary large or small float amounts are rejected and not used. Hence, solving this issue.
</panel>

<panel  header="**13 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/issues/111#issuecomment-1804512977" expanded>

This issue potentially resulted from an incorrect transactionList count where the count is not incremented when it reads in the transactions from the nuscents.txt file. Fixed the issue to ensure that when these transactions are loaded from the file, it increases the count too.
</panel>

<panel  header="**14 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/141#issuecomment-1804538593" expanded>

The code edits in this branch added a check to the parseAllowance(), parseExpense() and parseBudget() methods in Parser.java to ensure that the following conditions are met for the user entered amount. The allowance, expense and budget amount is positive, less than 100000, and has at most two decimal places. This ensures that arbitrary large or small float amounts are rejected and not used.

In addition, this branch fixes a separate bug related to the incorrect transactionList count too
</panel>

</panel>


<panel type="info" header="### 31. OU N..IANG `@onx001` (3 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/184#discussion_r1390721136" expanded>

Does initialising as ArrayStringList&gt;String> throw an error?
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/182#discussion_r1390722811" expanded>

Loading captured pieces does not work with existing games.
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/182#discussion_r1390723250" expanded>

Well abstracted with SLAP principles.
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/181#discussion_r1390421463" expanded>

Here, the isCheckmated function searches for any available moves. A stalemate can also occur when there are no available moves for either party, even though neither might be technically in check.
</panel>

<panel  header="**5 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/issues/31#issuecomment-1770525418" expanded>

Use the getPieceAtCoordinate function to get destination piece from ChessBoard object
Check for empty piece
Create function that implements colour checking logic and for destination validation
</panel>

<panel  header="**6 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/issues/64#issuecomment-1781191291" expanded>

#79 
</panel>

<panel  header="**7 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/79#issuecomment-1781193242" expanded>

#64 
</panel>

<panel  header="**8 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/issues/136#issuecomment-1807632095" expanded>

Solved as invalid move. No specific message shown as general exception is thrown.
</panel>

</panel>


<panel type="info" header="### 32. LIM ..SHUA `@lckjosh` (3 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/24#discussion_r1361859495" expanded>

I like this! Very smart!
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/74#discussion_r1378449419" expanded>

Is this check necessary? From what I understand this check should already be done in Parser.java
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/74#discussion_r1378449844" expanded>

Perhaps you could follow the format of the other commands, that is, return new EditCommand(parseEdit(arguments))
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/58#discussion_r1375431054" expanded>

Currently there's this one edge case where filtering by OTHERS only filters expenses and not allowances under the OTHERS category, this is just a quick fix.

Suggestions welcomed!

</panel>

<panel  header="**5 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/30#issuecomment-1767713074" expanded>

LGTM
</panel>

<panel  header="**6 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/47#issuecomment-1779740558" expanded>

Fixes #44 
</panel>

<panel  header="**7 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/77#issuecomment-1789115652" expanded>

LGTM!

</panel>

<panel  header="**8 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-4/tp/pull/145#issuecomment-1807012648" expanded>

Fixes #122 
</panel>

</panel>


<panel type="info" header="### 33. JASO.. JIE `@sRanay` (2 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/82#discussion_r1377121972" expanded>

The box maybe can use a lighter colour, very hard to see with current color
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/85#discussion_r1379529649" expanded>

You are missing out on the goal commands
![image](https://github.com/AY2324S1-CS2113-W12-3/tp/assets/33816512/cd1a6027-740c-47a7-ae0c-7936a7f85258)

</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/78#discussion_r1376469785" expanded>

Fixed
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/78#discussion_r1376469984" expanded>

Fixed
</panel>

</panel>


<panel type="info" header="### 34. SHAN..XUAN `@Xuan127` (2 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/49#discussion_r1370135767" expanded>

can write some commments / javadoc
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-2/tp/pull/111#discussion_r1384810549" expanded>

Should be uour own name
</panel>

</panel>


<panel type="info" header="### 35. DHAN..IKSH `@antrikshdhand` (2 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/181#discussion_r1390420041" expanded>

So it only draws the game if _both_ players are checkmated at the same time? Will this condition ever be true? To be honest I'm not entirely sure how you would define stalemate – I thought it was when one player isn't in checkmate but can't make any moves.
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/181#discussion_r1390421737" expanded>

Sounds good.
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/171#discussion_r1389338248" expanded>

I've gone ahead and added these now, along with a link to the UG.
</panel>

<panel  header="**4 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/159#issuecomment-1797122920" expanded>

Not sure why the tests aren't passing on CI here as all the tests are passing locally – I will follow this up soon.
</panel>

<panel  header="**5 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/159#issuecomment-1798840239" expanded>

### End-to-end tests contain a bug

Only one test can be conducted at a time. Multiple tests seem to be linked in some way (likely `Storage`) which causes the entire test suite to hang. Opened #162.

I have commented out some code so that there is only one test in the test suite. Will fix this bug in a later PR.
</panel>

<panel  header="**6 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-1/tp/pull/165#issuecomment-1802544728" expanded>

This PR also removes the dreaded `HistoryTest.java` from the codebase.
</panel>

</panel>


<panel type="info" header="### 36. SCHN..ILLE `@martinschnder` (2 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/pull/113#discussion_r1375413596" expanded>

You could perhaps avoid throwing exception in the main method
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/pull/113#discussion_r1375413659" expanded>

great !
</panel>

<panel  header="**3 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/177#issuecomment-1793683123" expanded>

response.Accepted - Martin

Fixed by modifying the delete command behaviour
</panel>

<panel  header="**4 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/205#issuecomment-1793684365" expanded>

bug fixed by catching the exception
</panel>

<panel  header="**5 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/188#issuecomment-1793687764" expanded>

Fix the issue by using lowercase in all keys
</panel>

<panel  header="**6 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/204#issuecomment-1793687970" expanded>

Already fixed
</panel>

<panel  header="**7 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/173#issuecomment-1793688258" expanded>

added positive integer verification
</panel>

<panel  header="**8 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/148#issuecomment-1793688415" expanded>

fixed !
</panel>

<panel  header="**9 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/137#issuecomment-1793690161" expanded>

added name verification to increment quantity but we should handle expiry date and serial number
</panel>

<panel  header="**10 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/193#issuecomment-1793690889" expanded>

Fixed !
</panel>

<panel  header="**11 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/192#issuecomment-1793691704" expanded>

Fixed by adding white space verification
</panel>

<panel  header="**12 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/207#issuecomment-1793691971" expanded>

Fixed by checking the quantity
</panel>

<panel  header="**13 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/202#issuecomment-1793692574" expanded>

Solved by implementing name verification !
</panel>

<panel  header="**14 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/190#issuecomment-1793692747" expanded>

Added exception handling !
</panel>

<panel  header="**15 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/195#issuecomment-1793696493" expanded>

Fixed !
</panel>

<panel  header="**16 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/156#issuecomment-1793696762" expanded>

Fixed by update delete command regex 
</panel>

<panel  header="**17 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/154#issuecomment-1793697095" expanded>

Updated userguide to match actual behaviour
</panel>

<panel  header="**18 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/152#issuecomment-1793697237" expanded>

Fixed by adding name verification in add command
</panel>

<panel  header="**19 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/136#issuecomment-1793697468" expanded>

Fixed by triming all the fields
</panel>

<panel  header="**20 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/201#issuecomment-1797947092" expanded>

added distinction 
</panel>

<panel  header="**21 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/199#issuecomment-1797947509" expanded>

fixed by checking the current quantity in cart
</panel>

<panel  header="**22 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/194#issuecomment-1797948857" expanded>

Fixed by verifying the quantity
</panel>

<panel  header="**23 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/160#issuecomment-1797949763" expanded>

Fixed by updating the regex
</panel>

<panel  header="**24 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/157#issuecomment-1797950207" expanded>

Fixed by ensuring that the serial number is unique
</panel>

<panel  header="**25 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/159#issuecomment-1797950734" expanded>

Fixed
</panel>

<panel  header="**26 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/137#issuecomment-1797951370" expanded>

Fixed!
</panel>

</panel>


<panel type="info" header="### 37. LIM ..HING `@limyuhching` (1 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-3/tp/pull/86#discussion_r1368752815" expanded>

This can perhaps be omitted as line 135 will handle the exception
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-3/tp/issues/150#issuecomment-1794182028" expanded>

Resolved
</panel>

</panel>


<panel type="info" header="### 38. HOO ..HONG `@hooami` (1 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on others PR)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/pull/148#discussion_r1385957865" expanded>

Typo in 'specified' and 'triggered'
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/issues/111#issuecomment-1798556268" expanded>

Functionality added with 'list goal'
</panel>

<panel  header="**3 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/issues/110#issuecomment-1803974721" expanded>

Issue is due to user's JVM locale being set differently. As most users would likely not encounter this, would add a note to UG but will not change output example
</panel>

<panel  header="**4 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/issues/101#issuecomment-1805230015" expanded>

Fixed in #136 
</panel>

<panel  header="**5 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/issues/116#issuecomment-1805418989" expanded>

Resolved in #143 
</panel>

<panel  header="**6 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/issues/115#issuecomment-1805419124" expanded>

Resolved in #143 
</panel>

<panel  header="**7 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/issues/113#issuecomment-1805420105" expanded>

Resolved in #143 
</panel>

<panel  header="**8 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/issues/108#issuecomment-1805420611" expanded>

Resolved in #143 
</panel>

<panel  header="**9 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/issues/98#issuecomment-1805421129" expanded>

Resolved in #143 
</panel>

<panel  header="**10 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-3/tp/issues/99#issuecomment-1807573151" expanded>

Fixed in #161 
</panel>

</panel>


<panel type="info" header="### 39. ZHU ..NGXI `@Cheezeblokz` (0 comments)"  collapsed>


<panel  header="**1 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/pull/70#issuecomment-1790581579" expanded>

Discarded to modify code.
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/pull/72#issuecomment-1790603142" expanded>

Closed to update code.
</panel>

</panel>


<panel type="info" header="### 40. LEE ..RYAN `@bljhty` (0 comments)"  collapsed>


<panel  header="**1 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-3/tp/issues/157#issuecomment-1793434595" expanded>

It has already been specified in out user guide that commands are case insensitive
</panel>

</panel>


<panel type="info" header="### 41. NG L..IXON `@NgLixuanNixon` (0 comments)"  collapsed>


<panel  header="**1 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/68#issuecomment-1779209557" expanded>

done
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/208#issuecomment-1808046944" expanded>

Used in caloriebalance
</panel>

</panel>


<panel type="info" header="### 42. FARI..RRAJ `@farissirraj` (0 comments)"  collapsed>


<panel  header="**1 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/69#issuecomment-1777612051" expanded>

Done for workouts
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/248#issuecomment-1799263542" expanded>

I have done this on my side. Kindly verify if it is working for you too.
</panel>

<panel  header="**3 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/247#issuecomment-1801000383" expanded>

Done
</panel>

</panel>


<panel type="info" header="### 43. TEO .. ZHI `@TeoHaoZhi` (0 comments)"  collapsed>


<panel  header="**1 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/18#issuecomment-1751779105" expanded>

Added basic classes, can be improved and specified further
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/pull/30#issuecomment-1752333175" expanded>

LGTM! Classes look more OOP now
</panel>

<panel  header="**3 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/pull/52#issuecomment-1765701419" expanded>

Have to pass the checkstyle tests first in order to pass CI tests as to adhere to coding conventions
</panel>

<panel  header="**4 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/pull/66#issuecomment-1772029983" expanded>

LGTM
</panel>

<panel  header="**5 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/pull/85#issuecomment-1779306041" expanded>

Check UML, activation bars missing
</panel>

<panel  header="**6 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/pull/88#issuecomment-1781165214" expanded>

CheckStyle error, fix before launching a PR
</panel>

<panel  header="**7 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/pull/92#issuecomment-1781231601" expanded>

Check self invocation, check activation bar
</panel>

<panel  header="**8 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/191#issuecomment-1793370075" expanded>

Save command is a feature, not quite sure what tester means by program saves data after each command. No example given,

response.IssueUnclear
</panel>

<panel  header="**9 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/198#issuecomment-1793370706" expanded>

response.Accepted - Hao Zhi

Fixed by removing expected outcome from user guide.
</panel>

<panel  header="**10 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/186#issuecomment-1793372668" expanded>

reponse.Rejected - Hao Zhi

Nitpicking, even if appropriate severity should be low.

Nonetheless how to execute file has been added into userguide as requested
</panel>

<panel  header="**11 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/182#issuecomment-1793374925" expanded>

reponse.Accepted- Hao Zhi

feels like nitpicking, but accepted and fixed with trim() nonetheless
</panel>

<panel  header="**12 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/179#issuecomment-1793375115" expanded>

response.Accepted - Hao Zhi

feels like nitpicking, nonetheless fixed with trim()
</panel>

<panel  header="**13 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/178#issuecomment-1793377388" expanded>

reponse.rejected - Hao Zhi

Spacebar is a legitamate character in making a string, nonetheless issue fixed with trim()
</panel>

<panel  header="**14 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/175#issuecomment-1793377850" expanded>

response.rejected- Hao Zhi

Duplicate issue with logging in with space character, nonetheless fixed with trim()
</panel>

<panel  header="**15 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/170#issuecomment-1793378176" expanded>

response.Rejected- Hao Zhi

Nitpicking, an invalid command format is invalid, follow the userguide instructions 
</panel>

<panel  header="**16 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/143#issuecomment-1793386628" expanded>

response.Accepted - Hao Zhi

Fixed 
</panel>

<panel  header="**17 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/138#issuecomment-1793387616" expanded>

response.rejected - Hao Zhi

Being able to register a new user from an existing user is a intended feature, logging in another user is intended as well.

However info will be added into user guide to be clearer
</panel>

<panel  header="**18 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/151#issuecomment-1793388651" expanded>

response.rejected - Hao Zhi

Nitpicking, follow the instructions on screen 
</panel>

<panel  header="**19 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/149#issuecomment-1793388942" expanded>

reponse.Accepted - Hao Zhi

Our mistake of not updating user guide

Fixed with relevant updates
</panel>

<panel  header="**20 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/161#issuecomment-1793389612" expanded>

response.Accepted- Hao Zhi

Our mistake, User guide has been updated to rectify
</panel>

<panel  header="**21 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/162#issuecomment-1793390094" expanded>

response.rejected - Hao Zhi

Same druglist appears for everyone as it is all being tracked by the system
</panel>

<panel  header="**22 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/158#issuecomment-1793392020" expanded>

reponse.rejected- Hao Zhi

Nitpicking, will mask away input in future iterations

Nonetheless issue will be mentioned in user guide
</panel>

<panel  header="**23 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/147#issuecomment-1793392478" expanded>

response.accepted - Hao Zhi

Mistake on our part, rectified by adding relevant portion into user guide
</panel>

<panel  header="**24 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/145#issuecomment-1793394398" expanded>

response.accepted - Hao Zhi

Added table of contents to user guide
</panel>

<panel  header="**25 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/146#issuecomment-1793394773" expanded>

response.rejected - Hao Zhi

The features section is to show all available features while usage is to show how they are used
</panel>

<panel  header="**26 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/141#issuecomment-1793397284" expanded>

response.accept - Hao Zhi

Mistake on our part for not considering how this would break the system, consideration has been added into the code
</panel>

<panel  header="**27 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/144#issuecomment-1793398534" expanded>

response.accept - Hao Zhi

Duplicate with issue #149 
</panel>

<panel  header="**28 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/142#issuecomment-1793399025" expanded>

response.accept- Hao Zhi

Thank you for the feedback, changes has been made
</panel>

<panel  header="**29 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/139#issuecomment-1793399176" expanded>

response.accepted - Hao Zhi

Mistake on our part, changes have been made
</panel>

<panel  header="**30 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/140#issuecomment-1793399509" expanded>

response.rejected - Hao Zhi

Does not break user experience
</panel>

<panel  header="**31 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/171#issuecomment-1793467887" expanded>

response.accepted - Hao Zhi

Our mistake of not passing files correctly from txt file back into the inventory

Issue has been fixed with correct parsing
</panel>

<panel  header="**32 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/169#issuecomment-1793468298" expanded>

response.Accepted- Hao Zhi

duplicate of issue #171 
</panel>

<panel  header="**33 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/168#issuecomment-1793468469" expanded>

response.accept - Hao Zhi

Duplicate of #171 
</panel>

<panel  header="**34 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/163#issuecomment-1793468712" expanded>

response.accepetd - Hao Zhi

Duplicate of issue #171 
</panel>

<panel  header="**35 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/135#issuecomment-1793469223" expanded>

response.accepted - Hao Zhi

Duplicate of issue #144 
</panel>

<panel  header="**36 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/206#issuecomment-1798330996" expanded>

Cntrl C not a valid bug, checked with prof
</panel>

<panel  header="**37 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/166#issuecomment-1803184276" expanded>

Is this a valid bug?
</panel>

</panel>


<panel type="info" header="### 44. LI S..UANG `@lisizhuang-0121` (0 comments)"  collapsed>


<panel  header="**1 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/75#issuecomment-1779092197" expanded>

Will create skeleton functions and separate issues.
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/75#issuecomment-1779215559" expanded>

Marked as closed, use individual issues for different commands.
</panel>

<panel  header="**3 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/83#issuecomment-1779291047" expanded>

Find command is moved, but we still need to rewrite the tests
</panel>

<panel  header="**4 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/73#issuecomment-1782283364" expanded>

Problem has been fixed.
</panel>

<panel  header="**5 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/58#issuecomment-1782285432" expanded>

Finish before releasing (by wednesday)
</panel>

<panel  header="**6 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/105#issuecomment-1785654656" expanded>

@spinoandraptos I guess we could use functions to display a standard set of Strings instead of having repeated println statements of the same string
</panel>

<panel  header="**7 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/pull/131#issuecomment-1785673984" expanded>

checks passed, merged
</panel>

<panel  header="**8 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/98#issuecomment-1785678892" expanded>

Duplicate task
</panel>

<panel  header="**9 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/143#issuecomment-1788454408" expanded>

Low priority, probably will not implement
</panel>

<panel  header="**10 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/144#issuecomment-1788455037" expanded>

Probably will not do.
</panel>

<panel  header="**11 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/145#issuecomment-1788455485" expanded>

Can do if there is time.
</panel>

<panel  header="**12 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/142#issuecomment-1788455921" expanded>

Probably won't do.
</panel>

<panel  header="**13 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/160#issuecomment-1792845570" expanded>

This is a duplicate issue with #162 
We will focus on issue number 162.
</panel>

<panel  header="**14 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/167#issuecomment-1792849655" expanded>

This is a duplicate issue with #166 
Will focus on issue 166 instead.
</panel>

<panel  header="**15 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/149#issuecomment-1792878866" expanded>

![image](https://github.com/AY2324S1-CS2113-W12-1/tp/assets/81349298/df57af30-ff3f-4530-b03a-6031fb32b0f5)

launch-able would be the correct word as suggested by Intellij's built in formatter. 
</panel>

<panel  header="**16 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/152#issuecomment-1792881410" expanded>

Finding by module is a feature, the description for find command in the UG will be updated.
</panel>

<panel  header="**17 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/158#issuecomment-1792909352" expanded>

This would be an intended behavior of the program.
Should the command be a single-word command, any arguments will be ignored.
We would add a section in UG on command semantics in case of any doubts.
</panel>

<panel  header="**18 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/163#issuecomment-1792911777" expanded>

This is a duplicate issue as #162 
We will focus on issue number 162 instead.
</panel>

<panel  header="**19 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/164#issuecomment-1792912532" expanded>

This is a duplicate issue as #162 
We will focus on issue 162 instead.
</panel>

<panel  header="**20 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/161#issuecomment-1792915402" expanded>

This is a duplicate issue as #168 as shuffle command would not return any feedback regardless of any circumstances due to its construction.
We would work on issue 168 instead.
</panel>

<panel  header="**21 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/170#issuecomment-1792917827" expanded>

This is a duplicate command as #151 as we have generalized searching of questions or answers to /description
We would work on issue 151 instead.
</panel>

<panel  header="**22 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/171#issuecomment-1792919037" expanded>

This is a duplicate issue as #151 , as we have generalized searching by question/answer to use /description keyword.
We would focus on issue 151 instead.
</panel>

<panel  header="**23 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/176#issuecomment-1792936387" expanded>

This is a duplicate issue as #168 .
We will focus on issue 168 instead.
</panel>

<panel  header="**24 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/177#issuecomment-1792938382" expanded>

This is an intended feature, we will update the user guide to better illustrate the semantics and intended behavior.
As list is a single-word command without any arguments, any arguments entered will be ignored.
</panel>

<panel  header="**25 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/183#issuecomment-1792939547" expanded>


This is an intended feature, we will update the user guide to better illustrate the semantics and intended behavior.
As shuffle is a single-word command without any arguments, any arguments entered will be ignored.

</panel>

<panel  header="**26 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/180#issuecomment-1792951369" expanded>

This is a duplicate issue as #159 
We will focus on issue 159 instead.
</panel>

<panel  header="**27 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/172#issuecomment-1792984758" expanded>

This is a duplicate issue as #153 
We will focus on issue 153 instead.
</panel>

<panel  header="**28 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/220#issuecomment-1801921141" expanded>

Ensure that there are no flaws in the UG and the users can follow them without any issues during the PE
</panel>

</panel>


<panel type="info" header="### 45. LEON..SHUA `@J0shuaLeong` (0 comments)"  collapsed>


<panel  header="**1 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/82#issuecomment-1772133069" expanded>

> What about storing all the input that user has given? (like meals and workouts)

Sure, should we add on those in v2.1 or just do it for v2.0 as well.
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/82#issuecomment-1772137262" expanded>

> > Sure, should we add on those in v2.1 or just do it for v2.0 as well.
> 
> I guess v2.1 is really not for adding features, so we should decide whether to implement on v2.0 or not.

Ok, possible to save profile data, and meals and workouts in two separate files? So when loading the file contents in it will be easier. One would load to userprofile the other to the meals and workouts list
</panel>

<panel  header="**3 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/82#issuecomment-1772140025" expanded>

> > Ok, possible to save profile data, and meals and workouts in two separate files? So when loading the file contents in it will be easier. One would load to userprofile the other to the meals and workouts list
> 
> Cool. You can separate meals and workouts too.

Sure! Thanks
</panel>

<panel  header="**4 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/63#issuecomment-1772141160" expanded>

Completed but may require further optimisation
</panel>

<panel  header="**5 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/pull/85#issuecomment-1772369393" expanded>

> @J0shuaLeong Let me know if you want to implement TODO stuffs that I made.

Sure!
</panel>

<panel  header="**6 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/172#issuecomment-1797816568" expanded>

The user guide specifies the format. Please follow the given format. Using other format will of course not be allowed, for that is how the application is made.
</panel>

<panel  header="**7 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/248#issuecomment-1801323507" expanded>

> I have done this on my side. Kindly verify if it is working for you too.

yup looks good. But i will combine them into one file for storage.
</panel>

<panel  header="**8 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/229#issuecomment-1807159056" expanded>

Fixed in #270 
</panel>

<panel  header="**9 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/153#issuecomment-1807159351" expanded>

Fixed in PR #270 
</panel>

<panel  header="**10 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/issues/200#issuecomment-1808147232" expanded>

If the user guide tells you format is bmi, it is best to adhere. Updated UG to mention a note to users that all caps command is not accepted.
</panel>

<panel  header="**11 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/pull/275#issuecomment-1808155509" expanded>

PR #226
</panel>

<panel  header="**12 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/pull/277#issuecomment-1808377463" expanded>

Sequence Diagrams added in this PR was done by @NgLixuanNixon 
</panel>

<panel  header="**13 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-4/tp/pull/276#issuecomment-1809433003" expanded>

This PR has been closed as PR #277 is merging the same code.
</panel>

</panel>


<panel type="info" header="### 46. JAME.. JEY `@James-Hong-Jey` (0 comments)"  collapsed>


<panel  header="**1 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/184#issuecomment-1800852640" expanded>

There are no predetermined modules to be considered "valid" or "invalid", it is finding no questions under the module klfajs which is the expected behaviour. 
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/174#issuecomment-1801172367" expanded>

The storage is not meant to be read by the user, and it is designed to have a different format that is easier to parse and subsequently display. 
</panel>

<panel  header="**3 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/178#issuecomment-1801173541" expanded>

Empty answers are allowed for users that just want to see the answer.
</panel>

</panel>


<panel type="info" header="### 47. ROHI..THAN `@rohitcube` (0 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/52#discussion_r1378770951" expanded>

my bad idk it merged with my one and not the master
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/152#discussion_r1384706024" expanded>

Removed this function as I realized the weekly schedule view would never be shown if one of the parameters (lecture, tutorial, lab) for the modules is not entered by the user. You're right, it returns true when invalid, I'll be more careful of naming conventions. 
</panel>

<panel  header="**3 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/159#issuecomment-1800862536" expanded>

Just found a bug where the 'timetable modify' does not work as intended, if recommend is called after it instead of before it. Will fix 
</panel>

<panel  header="**4 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-4/tp/pull/175#issuecomment-1803292032" expanded>

User guide is not very clear in this merge, I'll fix it for timetable after I have done the integration tests.
</panel>

</panel>


<panel type="info" header="### 48. MAN ..HENG `@spinoandraptos` (0 comments)"  collapsed>


<panel  header="**1 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/pull/96#issuecomment-1781324343" expanded>

Closes #81 
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/107#issuecomment-1783849313" expanded>

Closed by latest PR
</panel>

<panel  header="**3 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/105#issuecomment-1784036437" expanded>

Deep nesting: categorise by module,
Shorter: StartCommand and EditCommand
</panel>

<panel  header="**4 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-W12-1/tp/issues/105#issuecomment-1784036553" expanded>

@kohnh may I know what you are referring to for "Try not to repeat yourself by abstracting parts of your code especially the string literals"?
</panel>

</panel>


<panel type="info" header="### 49. REN ..GDAO `@YFshadaow` (0 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/142#discussion_r1378877627" expanded>

Because the style check does not allow wildcard imports lol

</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/142#discussion_r1378879631" expanded>

True, can save resource waste due to instantiation
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/142#discussion_r1378880001" expanded>

Possible
</panel>

<panel  header="**4 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/195#issuecomment-1799064316" expanded>

The reason I do these modifications are:
  - Intuitively it's a good approach to split the command name and usage into each command class
  - To avoid chunky text blocks in one class
</panel>

<panel  header="**5 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/issues/174#issuecomment-1804016486" expanded>


![image](https://github.com/AY2324S1-CS2113-T18-2/tp/assets/55742825/ffd4035a-339c-4556-8b4d-e49294cb0f23)
Bug not reproducable. 
The reporter might keyed in special characters that displays as a blank space.
</panel>

</panel>


<panel type="info" header="### 50. KARI..ARAN `@karishma-t` (0 comments)"  collapsed>


<panel  header="**1 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/196#issuecomment-1801885715" expanded>

Description meant to catalogue information about drugs, existing or not in inventory - made clearer in UG.
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T17-3/tp/issues/180#issuecomment-1801890131" expanded>

Meant to catalogue supply list of vendors, so drugs can be ordered from vendor supply list even if not in inventory - made clearer in UG
</panel>

</panel>


<panel type="info" header="### 51. WEMH..ELIN `@wendelinwemhoener` (0 comments)"  collapsed>


<panel  header="**1 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/pull/33#issuecomment-1770918807" expanded>

Please resolve the merge issues in Duke.java and also run the automated CI tests
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/39#issuecomment-1772005294" expanded>

After my refactoring to unify calendar and flashcard functionality, this behavior was changed and thus the bug doesn't apply anymore.
</panel>

<panel  header="**3 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/pull/57#issuecomment-1780404880" expanded>

The CI tests still aren't passing.
</panel>

<panel  header="**4 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/84#issuecomment-1803619167" expanded>

Fixed
</panel>

<panel  header="**5 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/86#issuecomment-1803620146" expanded>

Fixed
</panel>

<panel  header="**6 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/89#issuecomment-1803807226" expanded>

fixed
</panel>

<panel  header="**7 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/91#issuecomment-1803814720" expanded>

fixed
</panel>

<panel  header="**8 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/92#issuecomment-1803817609" expanded>

fixed
</panel>

<panel  header="**9 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/94#issuecomment-1803826068" expanded>

I've added an explanation about this to the UG


</panel>

<panel  header="**10 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/95#issuecomment-1803826918" expanded>

fixed 
</panel>

<panel  header="**11 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/114#issuecomment-1804030364" expanded>

fixed
</panel>

<panel  header="**12 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/103#issuecomment-1804033528" expanded>

fixed formatting error
</panel>

<panel  header="**13 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/100#issuecomment-1806865566" expanded>

fixed
</panel>

<panel  header="**14 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/101#issuecomment-1806865773" expanded>

fixed
</panel>

<panel  header="**15 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/106#issuecomment-1806865839" expanded>

fixed
</panel>

<panel  header="**16 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/111#issuecomment-1806865997" expanded>

fixed
</panel>

<panel  header="**17 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/112#issuecomment-1806866229" expanded>

fixed
</panel>

<panel  header="**18 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/113#issuecomment-1806867158" expanded>

fixed
</panel>

</panel>


<panel type="info" header="### 52. TIAN..AYAN `@J-Y-Yan` (0 comments)"  collapsed>


<panel  header="**1 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/12#issuecomment-1768578594" expanded>

- add class IncorrectFormationException which extends Exception class
- change the association of IllegalValueException as childen class of IncorrectFormatException
- add new constructor for command class with input parameter UserInput
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/12#issuecomment-1768582170" expanded>

create add goal method and delete goal method from a goal list
</panel>

<panel  header="**3 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/71#issuecomment-1804319686" expanded>

Solved.
</panel>

<panel  header="**4 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/79#issuecomment-1806668581" expanded>

Done.
</panel>

<panel  header="**5 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/89#issuecomment-1806770348" expanded>

![image](https://github.com/AY2324S1-CS2113-F11-1/tp/assets/142566176/b8df4069-064d-41e8-8284-c44f070a546a)

</panel>

<panel  header="**6 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/89#issuecomment-1806770492" expanded>

as reported by IDE
</panel>

<panel  header="**7 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/80#issuecomment-1806831689" expanded>

Done
</panel>

<panel  header="**8 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/78#issuecomment-1806831740" expanded>

Done
</panel>

<panel  header="**9 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/55#issuecomment-1806832392" expanded>

Solved. Thanks for comments.
</panel>

<panel  header="**10 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/53#issuecomment-1806832464" expanded>

Solved.
</panel>

<panel  header="**11 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/77#issuecomment-1806835892" expanded>

Done
</panel>

<panel  header="**12 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/47#issuecomment-1806836100" expanded>

Done.
</panel>

<panel  header="**13 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/47#issuecomment-1806836286" expanded>

Help for goal and exercise log related function has been initialized
</panel>

<panel  header="**14 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/46#issuecomment-1806836742" expanded>

duplicated feedback. Plz don't give meaningless comments and waste time
</panel>

<panel  header="**15 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/42#issuecomment-1806836916" expanded>

Why I don't know that we have such command???
</panel>

<panel  header="**16 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/59#issuecomment-1806837233" expanded>

As stated in user guides, edit function is simply "remove" and "add new data"
</panel>

<panel  header="**17 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/59#issuecomment-1806837913" expanded>

We will not consider adding an edit function as it is meaningless if some keep editing some records. We won't encourage this. We also believed that a rational user will not need to edit data frequently. However, thanks a lot from your comment. We will consider to improve goal function such as giving prompts on reasonable calories consumtion.
</panel>

<panel  header="**18 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/86#issuecomment-1806838022" expanded>

I have corrected the date class
</panel>

<panel  header="**19 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/86#issuecomment-1806838273" expanded>

But there are still errors in Datetime class.
</panel>

<panel  header="**20 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/17#issuecomment-1806838545" expanded>

Done.
</panel>

<panel  header="**21 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/89#issuecomment-1806838676" expanded>

close this issue if you think there is no need to change it.
</panel>

</panel>


<panel type="info" header="### 53. SHI ..CHEN `@hshiah` (0 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/134#discussion_r1377832678" expanded>

This part I follow the expense, which is without a ":".
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/143#discussion_r1378885494" expanded>

Make sense.
</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/143#discussion_r1378900152" expanded>

Sure, I will do it in v2.1 as enhancement.
</panel>

<panel  header="**4 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/70#issuecomment-1763440707" expanded>

LGTM
</panel>

<panel  header="**5 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-T18-2/tp/pull/134#issuecomment-1787403095" expanded>

> LGTM, how do u want to change the parser?

I haven't added the command to parser to avoid conflict.
After all features implemented, I will add these commands to parser.
</panel>

</panel>


<panel type="info" header="### 54. BANG..EONG `@junhyeong0411` (0 comments)"  collapsed>


<panel  header="**1 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/pull/29#issuecomment-1770843856" expanded>

Do I have to make deleting in v1?
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/pull/34#issuecomment-1771160148" expanded>

For flashcard commands, there is no "Enter your command" line. We have to resolve it.
</panel>

</panel>


<panel type="info" header="### 55. LI H..AOYU `@Haoyuli2002` (0 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/25#discussion_r1363519805" expanded>

I have renamed the name of this function, thanks for your advice :D
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/65#discussion_r1372735708" expanded>

Actually, toAdd contains "r/", you may refer this screenshot
<img width="615" alt="Screenshot 2023-10-26 at 15 48 34" src="https://github.com/AY2324S1-CS2113-F11-2/tp/assets/139958049/89664aba-bf48-4b34-9d79-ae7dfb77cfae">

</panel>

<panel  header="**3 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/65#discussion_r1372736023" expanded>

modified! Thanks for the notice
</panel>

<panel  header="**4 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/65#discussion_r1372736162" expanded>

Modified, it's more readable now :D
</panel>

<panel  header="**5 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/241#discussion_r1389156513" expanded>

Thanks, will modify later
</panel>

<panel  header="**6 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/241#discussion_r1389156633" expanded>

No, we have already used the white space to split the string, so for example "edit /r bread     n/flavor"
will be split into the array ["bread", "", "", "", "", "", "n/flavor"], I just want to delete this empty string in this case
</panel>

<panel  header="**7 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/241#discussion_r1389156812" expanded>

Will check later
</panel>

<panel  header="**8 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/pull/63#issuecomment-1779124669" expanded>

I modified the parser so that the program can add a recipe with its steps together, eg add r/bread s/step 1 instructions s/step 2 instructions 

</panel>

<panel  header="**9 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/194#issuecomment-1805076549" expanded>

but in this case, he didn't add the ingredients to the inventory explicitly, he just added a fish into the recipe meaning that this recipe needs a fish, but it doesn't mean that we have a fish in our inventory right now.
However, since there are no ingredients in our inventory right now, we print "The Inventory of Ingredients is empty now" on the console. 
</panel>

<panel  header="**10 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/190#issuecomment-1805077055" expanded>

I think this issue has already been solved
</panel>

<panel  header="**11 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/179#issuecomment-1805087128" expanded>

<img width="653" alt="Screenshot 2023-11-10 at 12 53 00" src="https://github.com/AY2324S1-CS2113-F11-2/tp/assets/139958049/b5aefc6f-613c-433b-865e-ed860200b574">
Done, this issue is not we don't give the description of how we would like to edit our step. So, in this case, someone split the input by using "," into an array,  hence there's only one string "s/2", so when we try to call the second index of the array it will fail. But now it works, I will print the error message and tell user what to do
</panel>

<panel  header="**12 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/129#issuecomment-1805091639" expanded>

<img width="399" alt="Screenshot 2023-11-10 at 13 02 33" src="https://github.com/AY2324S1-CS2113-F11-2/tp/assets/139958049/b402d327-a25c-47c3-bb10-32c08fd58a1c">
should works now, so you can just edit your ingredients by giving the name of your ingredients
</panel>

<panel  header="**13 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/151#issuecomment-1805094538" expanded>

<img width="645" alt="Screenshot 2023-11-10 at 13 05 30" src="https://github.com/AY2324S1-CS2113-F11-2/tp/assets/139958049/108d22d4-1bef-4f3f-953d-97b05c2c28f3">
works now
</panel>

<panel  header="**14 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/176#issuecomment-1805095495" expanded>

<img width="547" alt="Screenshot 2023-11-10 at 12 35 28" src="https://github.com/AY2324S1-CS2113-F11-2/tp/assets/139958049/29a873ce-d1a5-48d1-a32b-f43ac48f9b90">

It works now, so I remove the white spaces to ensure there's no such exception.
</panel>

<panel  header="**15 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-2/tp/issues/159#issuecomment-1805096302" expanded>

Seems that it has already been solved
![Uploading Screenshot 2023-11-10 at 12.53.00.png…]()

</panel>

</panel>


<panel type="info" header="### 56. HUAN..AMES `@Remy9926` (0 comments)"  collapsed>


<panel  header="**1 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/issues/7#issuecomment-1760702569" expanded>

Input + output passes now
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-1/tp/pull/10#issuecomment-1763353536" expanded>

LGTM
</panel>

</panel>


<panel type="info" header="### 57. KHER..ALAN `@Brian030601` (0 comments)"  collapsed>


<panel  header="**1 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/23#issuecomment-1770571455" expanded>

Calendar functions are added
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/61#issuecomment-1790388545" expanded>

Updated DG
</panel>

<panel  header="**3 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/68#issuecomment-1790411896" expanded>

Added
</panel>

<panel  header="**4 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/75#issuecomment-1790628751" expanded>

Updated
</panel>

<panel  header="**5 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113-F11-3/tp/issues/105#issuecomment-1794558646" expanded>

There is exit program available
</panel>

</panel>


<panel type="info" header="### 58. LEE ..GMIN `@woodenclock` (0 comments)"  collapsed>


<panel  header="**1 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/3#issuecomment-1752698512" expanded>

We first need to create the Entry Class first
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/1#issuecomment-1762850330" expanded>

This is a simple add-on to the "teams" folder in "docs" for my portfolio
</panel>

<panel  header="**3 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/1#issuecomment-1762850473" expanded>

I have also filled up the AboutUs.md page to include my photo, name, github address and address to my portfolio
</panel>

<panel  header="**4 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/2#issuecomment-1762850643" expanded>

Renamed Duke to WildWatch, since our project name is WildWatch
</panel>

<panel  header="**5 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/4#issuecomment-1762850777" expanded>

Successfully changed name of project from Duke to WildWatch
</panel>

<panel  header="**6 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/6#issuecomment-1762850990" expanded>

Create BootUp.java that handles the necessary outputs required for when WildWatch is run.
This includes things like our WildWatch Logo, and Welcome Message.
</panel>

<panel  header="**7 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/5#issuecomment-1762851266" expanded>

Tried to create BootUp.java with our project Logo, but failed to pass check.
Troubleshooting, might close this PR and considering of making a new one.

</panel>

<panel  header="**8 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/6#issuecomment-1762851482" expanded>

Fail check was because the Logo was too long and exceeded the 120 word per line limit
</panel>

<panel  header="**9 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/12#issuecomment-1762851715" expanded>

Update project structure to merge master and bootup branches.
Update BootUp.java to conform to coding standards and quality.
</panel>

<panel  header="**10 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/13#issuecomment-1763265416" expanded>

This is the fundamental class that will be storing the entries of animals in the wildlife reserve
</panel>

<panel  header="**11 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/14#issuecomment-1763265662" expanded>

Test using JUnit for WildWatch class which is the program's main method
</panel>

<panel  header="**12 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/15#issuecomment-1763265746" expanded>

Create EntryList class that holds an arraylist of entries.
This allows for entries to be easily added, removed, retrieved
</panel>

<panel  header="**13 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/18#issuecomment-1763265804" expanded>

Update welcome logo to be smaller, so that it will fit within the 120 character limit
</panel>

<panel  header="**14 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/19#issuecomment-1763265884" expanded>

Create Ui class that handles the input and output interaction with the user
</panel>

<panel  header="**15 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/24#issuecomment-1763265988" expanded>

Create DataHandler class that validates if the input date is valid.
</panel>

<panel  header="**16 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/24#issuecomment-1763266071" expanded>

More enhancements planned in future to allow more forms of date inputs.
</panel>

<panel  header="**17 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/24#issuecomment-1763266150" expanded>

Standardize all the various data input into dd-MM-yy or other standard format to be confirmed
</panel>

<panel  header="**18 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/26#issuecomment-1763266280" expanded>

JUnit testing for DataHandler.java
Testing to see if the DateHandler correctly identifies the correct and wrong formats of date input
and throws the exceptions appropriately when wrong format of date is input
</panel>

<panel  header="**19 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/30#issuecomment-1763266369" expanded>

Create Delete command that will delete the selcted Entry in the EntryList.
</panel>

<panel  header="**20 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/29#issuecomment-1763272783" expanded>

Update docs/team for github and portfolio
</panel>

<panel  header="**21 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/7#issuecomment-1763342872" expanded>

We can go with this first, and maybe add others along the way
</panel>

<panel  header="**22 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/32#issuecomment-1763723239" expanded>

Looks good to merge!
All checks have been passed too
</panel>

<panel  header="**23 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/34#issuecomment-1764028020" expanded>

Add assertions and logging for Parser.java & ErrorHandler.java
</panel>

<panel  header="**24 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/37#issuecomment-1767682763" expanded>

LGTM, good work on fixing the bug
</panel>

<panel  header="**25 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/43#issuecomment-1774054282" expanded>

As a clerk working in a zoo, I want the list of entries I type into WildWatch to be saved and retrieved later.
I don't want the data to be erased when I close the program.
FileHandler class manages the writing and retreiving of information to and from file
</panel>

<panel  header="**26 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/44#issuecomment-1779190851" expanded>

Yup, the less coupling we have, the more modular the program will be and it will ultimately mean an increase in testability
</panel>

<panel  header="**27 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/44#issuecomment-1779191113" expanded>

LGTM
</panel>

<panel  header="**28 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/45#issuecomment-1779388521" expanded>

Create FindCommand Operation
</panel>

<panel  header="**29 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/31#issuecomment-1780968194" expanded>

The help page looks good, made a few adjustments for better visibility.
LGTM
</panel>

<panel  header="**30 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/82#issuecomment-1783784815" expanded>

I closed the issue opened by Cai Ting and made a duplicate, due to the following reason:
The issue has to be created in that week to be counted as contribution for that week.
(Why liddat???😭)

![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/7716c717-590f-4c54-8b86-52cde585cfe9)
</panel>

<panel  header="**31 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/82#issuecomment-1783785063" expanded>

![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/0c1b9e7a-bda4-4410-8c29-67fa14df1005)
This is for Week 11 btw, do take note!
</panel>

<panel  header="**32 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/83#issuecomment-1783785847" expanded>

This would allow the users to check if their JVM is compatible with our WildWatch.jar
</panel>

<panel  header="**33 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/83#issuecomment-1783786798" expanded>

Changed the Quick Start section a little as well, the automatic numbering of the list is so ridiculous!!!

![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/e07564cb-31d1-4111-bc7f-2d0c5a22f787)

</panel>

<panel  header="**34 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/83#issuecomment-1783787161" expanded>

The link seems to work!
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/dcb14bca-5b8b-4285-82ce-1ce7e145e875)
It brings the user to this page: https://www.java.com/en/download/help/version_manual.html

</panel>

<panel  header="**35 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/75#issuecomment-1783787793" expanded>

Ms Vivian commented that the Help should not be at the top.
Which is why we're moving it down
</panel>

<panel  header="**36 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/75#issuecomment-1783788004" expanded>

Thank you Jeremy!
</panel>

<panel  header="**37 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/66#issuecomment-1783788160" expanded>

Oops, accidentally clicked on close
</panel>

<panel  header="**38 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/94#issuecomment-1784005468" expanded>

I closed the issue opened by Cai Ting and made a duplicate, due to the following reason:
The issue has to be created in that week to be counted as contribution for that week.
(Why liddat???😭)
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/67fcc4c2-865b-4204-ae06-6035152c01de)

</panel>

<panel  header="**39 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/66#issuecomment-1784021139" expanded>

![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/275b8077-34e2-4cb9-a066-af98504729da)
Target audience is mentioned
Purpose is stated
</panel>

<panel  header="**40 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/94#issuecomment-1784021322" expanded>

![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/24cd39b2-489c-4dde-a08f-47425d86ea44)
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/ff27044d-aeb5-4873-87d3-b3678f306765)
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/44a2cb1a-034b-4bb9-aac9-c9cd4700d1ac)
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/51c3cf17-6b60-43ae-806c-a47623a2cf5f)
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/ae071775-09bd-400b-a481-8f1496f8630c)


</panel>

<panel  header="**41 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/94#issuecomment-1784021378" expanded>

Added visuals.
For the pending commands, not yet
</panel>

<panel  header="**42 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/67#issuecomment-1784025244" expanded>

Introduction has been made according to the rubrics
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/f99fc3a0-0179-4066-bb93-e908f043852a)
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/c2f6e899-2fda-44b6-b8e5-2248bebbee61)

</panel>

<panel  header="**43 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/74#issuecomment-1784026996" expanded>

![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/7c68e303-83de-4445-a1ee-be860e4ced1a)

</panel>

<panel  header="**44 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/74#issuecomment-1784027028" expanded>

Added the Glossary Section
</panel>

<panel  header="**45 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/68#issuecomment-1784027216" expanded>

![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/44d3e545-0e89-4260-885b-c1eb4d3b1060)
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/0bde392c-e00b-4ef6-9670-7ccd4e48c704)

</panel>

<panel  header="**46 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/68#issuecomment-1784027302" expanded>

Added a way for users to check their Java version
</panel>

<panel  header="**47 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/69#issuecomment-1784027399" expanded>

![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/f2e6b305-a4cf-40ef-a1dd-1887f8001209)

</panel>

<panel  header="**48 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/69#issuecomment-1784027475" expanded>

Added the How to use the User Guide section!
</panel>

<panel  header="**49 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/55#issuecomment-1784029296" expanded>

This issue was remade in Week 11
</panel>

<panel  header="**50 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/76#issuecomment-1784029354" expanded>

This issue was remade in Week 11
</panel>

<panel  header="**51 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/71#issuecomment-1784029468" expanded>

LGTM!!
Good job
</panel>

<panel  header="**52 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/105#issuecomment-1787109066" expanded>

Fixed several bugs after the recent updates.
</panel>

<panel  header="**53 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/80#issuecomment-1787114530" expanded>

Thank you Muzfirah.
I have made the appropriate changes according to your review.
</panel>

<panel  header="**54 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/54#issuecomment-1791056385" expanded>

LGTM.
Will be closing this issue, as we're wrapping up and releasing v2.0
</panel>

<panel  header="**55 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/94#issuecomment-1791057454" expanded>

LGTM.
Will be closing this issue, as we're wrapping up and releasing v2.0
</panel>

<panel  header="**56 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/116#issuecomment-1791084392" expanded>

Done, changed accordingly.
</panel>

<panel  header="**57 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/115#issuecomment-1791085819" expanded>

![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/19c013b5-6f94-4152-9dc0-1cec33578624)
Yup, right now, if the date exceeds max, it will just put max, but will fix in the future
</panel>

<panel  header="**58 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/132#issuecomment-1793374380" expanded>

Oops, changed the diagram but forgot to change the descriptions
</panel>

<panel  header="**59 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/133#issuecomment-1793374603" expanded>

Yup, will work on this 
</panel>

<panel  header="**60 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/38#issuecomment-1793498241" expanded>

As we continue to improve the WildWatch, the help page needs to be properly updated
</panel>

<panel  header="**61 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/84#issuecomment-1793498618" expanded>

Nice feature!
This would make our product more usable, since the user can now look at the prompter to see if he/she can type.
</panel>

<panel  header="**62 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/85#issuecomment-1793498899" expanded>

Big change from the  Foundation Code.
Kudos for the major update!
The Parser classes were revolutionary.
Will make my own parsers for the major update
</panel>

<panel  header="**63 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/86#issuecomment-1793499066" expanded>

Nice, you have remove the "magic numbers and words".
The code is now more readable
</panel>

<panel  header="**64 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/136#issuecomment-1793739523" expanded>

Fix bug: [PE-D][Tester B] List function executed whenever with leading 'list' #136
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/0d6a1940-029d-4232-a5e8-74a7f28ef02d)
</panel>

<panel  header="**65 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/93#issuecomment-1793743744" expanded>

![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/5d2c77af-74e1-49e6-bb8a-ab5953d7b4b7)

</panel>

<panel  header="**66 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/99#issuecomment-1793749212" expanded>

Yup, added the EditCommandParser class
</panel>

<panel  header="**67 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/141#issuecomment-1793754582" expanded>

The add command has been fixed
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/fddb9513-f856-4891-90cc-ea1a31924302)

</panel>

<panel  header="**68 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/141#issuecomment-1793755829" expanded>

The edit command has been fixed
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/d1de106b-4981-4bf7-888b-8bdb6aa212f4)

</panel>

<panel  header="**69 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/173#issuecomment-1793756312" expanded>

Standardized to capitalized letter as mentioned here
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/dbb95074-a708-4494-8895-0f8cb4fb630b)

</panel>

<panel  header="**70 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/115#issuecomment-1793765336" expanded>

Improved isDateValid to identify invalid dates, which takes into account the leap day, days in different months.
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/948dc325-222b-4a8e-9fe9-d0bfbbc87b8c)

</panel>

<panel  header="**71 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/1#issuecomment-1798636209" expanded>

I have updated the README page as well!
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/bbcc3778-8ade-49b2-9b0f-5710035eb7b5)

</panel>

<panel  header="**72 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/82#issuecomment-1798770812" expanded>

Given the tight schedule at hand, I'm not sure if this would be possible...
</panel>

<panel  header="**73 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/144#issuecomment-1798784359" expanded>

I will fix this error.
Working on it.
</panel>

<panel  header="**74 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/144#issuecomment-1798794782" expanded>

Yup, fixed the bug.
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/f2422b00-427e-491f-93a0-d4cd552b10e1)

</panel>

<panel  header="**75 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/148#issuecomment-1798805392" expanded>

As it is a duplicate, will be closing this issue
</panel>

<panel  header="**76 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/151#issuecomment-1798995643" expanded>

Fix bug: [PE-D][Tester B] Failed to further validate yes/no choice for delete function #151
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/d5dc5720-eef8-4077-815b-1932db3d70d3)

</panel>

<panel  header="**77 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/167#issuecomment-1799032879" expanded>

Yup, made it clear in the UG
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/7c578d9f-6a6e-4818-b859-8e57237abfe6)

</panel>

<panel  header="**78 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/190#issuecomment-1799034194" expanded>

@lctxct for #167, do you want to make the Name part optional?????
</panel>

<panel  header="**79 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/168#issuecomment-1799036573" expanded>

We are not implementing these additional details to the program in the upcoming iteration.
</panel>

<panel  header="**80 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/159#issuecomment-1799039911" expanded>

Ummm...., I don't think that is a good idea, cuz that will mean we have multiple entries for a single animal, which defeats the purpose of WildWatch
</panel>

<panel  header="**81 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/159#issuecomment-1799041346" expanded>

@lctxct do you want to enhance it?
</panel>

<panel  header="**82 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/40#issuecomment-1799046922" expanded>

Duplicate of #135 
</panel>

<panel  header="**83 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/162#issuecomment-1799051877" expanded>

@lctxct this is a big problem, what do we do?
</panel>

<panel  header="**84 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/162#issuecomment-1799052919" expanded>

we should have used DD-MM-YYYY instead
</panel>

<panel  header="**85 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/206#issuecomment-1801285465" expanded>

Yup, fixed appropriately.
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/b763e244-0aa8-40de-92d3-704b06a1d971)

</panel>

<panel  header="**86 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/205#issuecomment-1801287519" expanded>

You mean for the Quick Start?
To show the start up process?
</panel>

<panel  header="**87 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/162#issuecomment-1801698403" expanded>

Actually changing to `DD-MM-YYYY` is not so big of a change
</panel>

<panel  header="**88 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/162#issuecomment-1801726428" expanded>

Yup fixed it.
Now the date is officially DD-MM-YYYY
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/08d461df-8715-4f2e-ac50-6521e5d501bb)

</panel>

<panel  header="**89 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/165#issuecomment-1801897488" expanded>

I don't think we should be restricting the dates to the current day.
There could be animals planned to arrive in the future???
</panel>

<panel  header="**90 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/161#issuecomment-1801898283" expanded>

@imaginarys96  Please make the necessary changes
</panel>

<panel  header="**91 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/158#issuecomment-1801920112" expanded>

Fixed this bug.
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/e2f6da7f-3e35-4537-97ef-0cbdbb368f01)

</panel>

<panel  header="**92 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/212#issuecomment-1803162617" expanded>

Fixed this bug.
</panel>

<panel  header="**93 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/166#issuecomment-1803946488" expanded>

I think this just needs a bit of tweaking the add command???
Edit: I take back what I said, it's gonna take quite a bit of change.
</panel>

<panel  header="**94 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/166#issuecomment-1804020292" expanded>

I think we just state in the UG that the order of the arguments are fixed.
</panel>

<panel  header="**95 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/41#issuecomment-1804030365" expanded>

Looks like the AboutUs.md has been updated!
Well done!!
</panel>

<panel  header="**96 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/82#issuecomment-1804031458" expanded>

This improvement to be implemented in future updates.
</panel>

<panel  header="**97 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/155#issuecomment-1804033133" expanded>

Yup, was thinking the same, we already have the find command, but I guess this could be a good add-on
</panel>

<panel  header="**98 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/204#issuecomment-1804061613" expanded>

Just realised, I can only test it out after merging :)
</panel>

<panel  header="**99 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/204#issuecomment-1804070919" expanded>

Upon testing, looks good
</panel>

<panel  header="**100 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/207#issuecomment-1804073297" expanded>

LGTM, will test it out upon merging
</panel>

<panel  header="**101 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/207#issuecomment-1804118532" expanded>

Is this the final output you wanted?
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/3fc75fc4-d503-42e9-a9ae-bb419b9c7976)

</panel>

<panel  header="**102 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/61#issuecomment-1805229490" expanded>

This would likely not be feature in v2.1.
Maybe future iterations will have this feature
</panel>

<panel  header="**103 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/57#issuecomment-1805229724" expanded>

Is there enough time for this?
</panel>

<panel  header="**104 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/57#issuecomment-1805230047" expanded>

      I think this feature can be implemented in the future iterations.
</panel>

<panel  header="**105 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/205#issuecomment-1806772575" expanded>

Yup added into UG
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/9309285c-ed59-447d-a64f-3712c0a49f4e)

</panel>

<panel  header="**106 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/205#issuecomment-1806772786" expanded>

Added these for opening of command prompt
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/70333e7c-da6b-421d-b531-5f30d7db20ca)
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/7fd7c1a7-8c0d-42e0-835c-cad4b712f884)

</panel>

<panel  header="**107 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/191#issuecomment-1806775236" expanded>

For #155, it has been fixed.
But needs to improve on the case-sensitivity
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/11014a9a-a398-4516-8112-694e1469120b)

</panel>

<panel  header="**108 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/191#issuecomment-1806799461" expanded>

Fixed it!
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/6dbc1783-6e2a-41c4-aecc-cdf6bb6c29cb)

</panel>

<panel  header="**109 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/135#issuecomment-1806799578" expanded>

Team members are to add appropriate diagrams where appropriate
</panel>

<panel  header="**110 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/160#issuecomment-1806825063" expanded>

Added appropriate help page.
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/d9c54f4b-8aea-4dd8-9f74-d610e8533bbc)

</panel>

<panel  header="**111 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/189#issuecomment-1806825339" expanded>

Fixed the last issue
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/14c8f9e9-93f4-4bc6-a969-05248ebfce9e)

</panel>

<panel  header="**112 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/166#issuecomment-1806825617" expanded>

Yup, stated in UG
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/08b61d37-1479-485b-93aa-4042f727c880)

</panel>

<panel  header="**113 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/166#issuecomment-1806825786" expanded>

![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/69474977/8179f6a9-1351-4023-95ad-00fb15702364)

</panel>

<panel  header="**114 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/219#issuecomment-1807012616" expanded>

Do finish this by Tuesday, as I'll be submitting it on Tuesday night
</panel>

</panel>


<panel type="info" header="### 59. YANG..REMY `@imaginarys96` (0 comments)"  collapsed>


<panel  header="**1 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/7#issuecomment-1762958481" expanded>

Did we fix the format for the `add` command yet in any document?
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/7#issuecomment-1762958927" expanded>

> Did we fix the format for the `add` command yet in any document?

Found it

```
Adds a new wildlife. 

Format: add D/DATE S/SPECIES N/NAME R/REMARKS
DATE should be in the format DD-MM-YY

Note: More than 1 species may be specified in one go if multiple new animals are added to the reserve on the same day. A new set of (species, name, remarks) should be specified for each addition. 

Examples:

add D/02-03-23 S/Annam Leaf Turtle N/Ariel R/Injured left flipper
add D/10-11-20 S/Bali Myna N/Myna_1 R/ S/Malayan Water Monitor N/Monitor_1 R/Aggressive
```
</panel>

<panel  header="**3 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/60#issuecomment-1783756001" expanded>

reordered `help` in the user guide
</panel>

<panel  header="**4 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/62#issuecomment-1783991670" expanded>

Added the `edit` command . 
Format: `edit I/<INDEX> D/<DATE> S/<SPECIES> N/<NAME> R/<REMARKS>`
`<date>` should be in the format **DD-MM-YY**
`<INDEX>` is required. The other arguments are optional.

Example:
```
edit I/1 D/02-03-24 S/Annam Leaf Turtle N/Ariel R/Injured left flipper
____________________________________________________________
The following entry has been edited:
Date: [02-04-2024] | Species: [Annam Leaf Turtle] | Name: [Javier] | Remark: [Injured right flipper]
____________________________________________________________
```
```
edit I/1 S/Green Leaf Turtle
____________________________________________________________
The following entry has been edited:
Date: [02-03-2023] | Species: [Green Leaf Turtle] | Name: [Ariel] | Remark: [Injured left flipper]
____________________________________________________________
```
</panel>

<panel  header="**5 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/90#issuecomment-1783991896" expanded>

Updated user guide in commit fa22d1545a218794419f1d0a67cec37502a5d8bd
</panel>

<panel  header="**6 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/53#issuecomment-1783994941" expanded>

Also need to include `edit`, `summary` commands. May be better to update it in one go towards the end.
</panel>

<panel  header="**7 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/53#issuecomment-1788634190" expanded>

`help` command has been updated to show a short version by default.
`help full` will show the full version
`help COMMAND` i.e. `help add` will show the help message for the specified command

</panel>

<panel  header="**8 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/137#issuecomment-1793762409" expanded>

fixed in commit 2d091add18b4a02eb73a20675005cbf43aee651c
</panel>

<panel  header="**9 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/145#issuecomment-1793762490" expanded>

fixed in 2d091add18b4a02eb73a20675005cbf43aee651c
</panel>

<panel  header="**10 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/172#issuecomment-1793762547" expanded>

fixed in 2d091add18b4a02eb73a20675005cbf43aee651c
</panel>

<panel  header="**11 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/153#issuecomment-1793762630" expanded>

fixed in 2d091add18b4a02eb73a20675005cbf43aee651c
</panel>

<panel  header="**12 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/191#issuecomment-1793763538" expanded>

first issue fixed in 2d091add18b4a02eb73a20675005cbf43aee651c (checks if species exist when running `summary` command)
</panel>

<panel  header="**13 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/144#issuecomment-1793764493" expanded>

don't think this is an issue. maybe we can just close this one ?
</panel>

<panel  header="**14 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/156#issuecomment-1798350678" expanded>

resolved in 75355ac7c270ef78df951420c0eb6f4eb70023c0
</panel>

<panel  header="**15 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/189#issuecomment-1798351385" expanded>

first and third issue are the same. resolved in 75355ac7c270ef78df951420c0eb6f4eb70023c0
</panel>

<panel  header="**16 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/171#issuecomment-1801304575" expanded>

this was resolved by zhen en . can see that the `bye` command has been added. 
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/74832982/0f5e4e40-6445-4d86-8698-3c8347103833)

</panel>

<panel  header="**17 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/155#issuecomment-1801308691" expanded>

actually, i think our `find` command does the same thing but since its modified already then we can just stick with that i guess
</panel>

<panel  header="**18 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/161#issuecomment-1803162416" expanded>

added in 75355ac7c270ef78df951420c0eb6f4eb70023c0
</panel>

</panel>


<panel type="info" header="### 60. LIEN..TING `@lctxct` (0 comments)"  collapsed>


<panel  header="**1 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/81#issuecomment-1789420505" expanded>

Saw this a little late so I think the file is gone 😅, but hopefully it was fixed? Thank you!
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/50#issuecomment-1790191479" expanded>

Nothing to test. :(
</panel>

<panel  header="**3 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/56#issuecomment-1790193082" expanded>

Might be too late for this, can open again if more features required though. 
</panel>

<panel  header="**4 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/72#issuecomment-1790623189" expanded>

This seems to be done? 
</panel>

<panel  header="**5 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/59#issuecomment-1790623766" expanded>

Could be a bit weird
</panel>

<panel  header="**6 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/152#issuecomment-1793693293" expanded>

Closed by https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/182.
</panel>

<panel  header="**7 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/157#issuecomment-1793693634" expanded>

Closed by https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/182. 
</panel>

<panel  header="**8 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/146#issuecomment-1793695452" expanded>

Closed by https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/186.
</panel>

<panel  header="**9 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/169#issuecomment-1793709600" expanded>

Resolved by https://github.com/AY2324S1-CS2113T-W11-2/tp/pull/187.
</panel>

<panel  header="**10 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/170#issuecomment-1793712373" expanded>

https://support.microsoft.com/en-us/office/how-to-correct-a-error-bf801d0a-2a6e-44bd-a70e-0f780ae8f11e
> Microsoft Excel might show ##### in cells when a column isn’t wide enough to show all of the cell contents. Formulas that return dates and times as negative values can also show as #####.
</panel>

<panel  header="**11 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/166#issuecomment-1793713627" expanded>

Duplicate of https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/148
</panel>

<panel  header="**12 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/174#issuecomment-1793713971" expanded>

Feature not a bug to allow for flexibility when specifying species/names.
</panel>

<panel  header="**13 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/139#issuecomment-1793718817" expanded>

We don't police this and allow users to specify a later date if they want.
</panel>

<panel  header="**14 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/147#issuecomment-1793719118" expanded>

Duplicate of https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/115
</panel>

<panel  header="**15 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/148#issuecomment-1793719203" expanded>

Duplicate of https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/166
</panel>

<panel  header="**16 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/159#issuecomment-1793720064" expanded>

We allow this just in case users want to add multiple remarks for animal in the same day? 
</panel>

<panel  header="**17 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/165#issuecomment-1793720671" expanded>

We allow this as a feature? 
Duplicate of https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/139
</panel>

<panel  header="**18 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/175#issuecomment-1793722393" expanded>

Duplicate of https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/158
</panel>

<panel  header="**19 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/190#issuecomment-1801103787" expanded>

> @lctxct for #167, do you want to make the Name part optional?????

Since we won't be allowing duplicate entries (as per https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/159), we need Name to be specified to perform the check. So it's better to not make it optional. 
</panel>

<panel  header="**20 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/134#issuecomment-1801119951" expanded>

Updated! Sequence diagram now looks like this. 

![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/70379887/e99c761f-4725-465f-9e82-592469dfb399)

</panel>

<panel  header="**21 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/162#issuecomment-1801220922" expanded>

Hmm...I suppose we can still change to use `DD-MM-YYYY`? Else we can also just specify in the UG or somewhere that we only accept 2000+, or we can just close this issue and pretend it doesnt exist 👀
</panel>

<panel  header="**22 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/155#issuecomment-1801223415" expanded>

~Sure, will modify the `summary` command to accept `summary <species>`.~ Just realized it already does that... 

Currently: 
![image](https://github.com/AY2324S1-CS2113T-W11-2/tp/assets/70379887/661b3ca0-adeb-4a84-ba3c-8cd996dae0b6)

Will modify it to do something like: 
```
____________________________________________________________
>>> summary Annam Leaf Turtle
____________________________________________________________
Here is the data for the Annam Leaf Turtle, grouped by their names
Ariel - (1)
Date: [02-03-2024] | Species: [Annam Leaf Turtle] | Name: [Ariel] | Remark: [Injured left flipper]
--------------------------------------------------------------
John - (1)
Date: [02-03-2024] | Species: [Annam Leaf Turtle] | Name: [John] | Remark: [Injured right flipper]
____________________________________________________________
```
</panel>

<panel  header="**23 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-2/tp/issues/205#issuecomment-1801302670" expanded>

I actually meant instructions on how to open command prompt, but I realized that's quite system specific...nvm...
</panel>

</panel>


<panel type="info" header="### 61. BENJ..MING `@bnjm2000` (0 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/38#discussion_r1360293162" expanded>

I have already made that change...
<img width="1430" alt="Screenshot 2023-10-16 at 4 16 54 PM" src="https://github.com/AY2324S1-CS2113T-W11-1/tp/assets/142559789/47a45b54-07df-4616-868a-2850c0e435d7">

</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/29#issuecomment-1762891613" expanded>

Nice, looks good to merge.
</panel>

<panel  header="**3 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/31#issuecomment-1763230031" expanded>

Great code, looks good to merge.

</panel>

<panel  header="**4 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/39#issuecomment-1764001500" expanded>

Looks good!
</panel>

<panel  header="**5 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/40#issuecomment-1764295320" expanded>

Nice code!
</panel>

<panel  header="**6 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/41#issuecomment-1764579754" expanded>

You could probably code your way out of a paper bag!
</panel>

<panel  header="**7 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/45#issuecomment-1766122697" expanded>

Your cat definitely did not go across the keyboard to write this. 
</panel>

<panel  header="**8 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/46#issuecomment-1766197424" expanded>

If your code were a piece of furniture, it would be a closet. Well organised, neat and modular. 
</panel>

<panel  header="**9 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/51#issuecomment-1766588586" expanded>

I've seen poetry less elegant than your code.
</panel>

<panel  header="**10 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/53#issuecomment-1766608312" expanded>

Your code is like a fine wine, improving with every merge.
</panel>

<panel  header="**11 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/75#issuecomment-1780556676" expanded>

This code is like a well-oiled machine, smooth and efficient.
</panel>

<panel  header="**12 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/85#issuecomment-1784177597" expanded>

This code is like a fine wine - it gets better with age.
</panel>

<panel  header="**13 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/86#issuecomment-1785046368" expanded>

Your code is so elegant, it's practically wearing a tuxedo.
</panel>

<panel  header="**14 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/93#issuecomment-1787217756" expanded>

You can set it as a draft PR so the option to merge is greyed out.
</panel>

<panel  header="**15 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/94#issuecomment-1787366842" expanded>

I'd trust your code with my firstborn. It's that reliable.
</panel>

<panel  header="**16 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/97#issuecomment-1787462782" expanded>

I had to put on sunglasses to review your code - it's blindingly good.
</panel>

<panel  header="**17 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/99#issuecomment-1787487141" expanded>

This code is not just good to merge, it is great to merge. &gt;3
</panel>

<panel  header="**18 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/98#issuecomment-1787538721" expanded>

Your code's so clean, even Marie Kondo would be proud!
</panel>

<panel  header="**19 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/104#issuecomment-1790136366" expanded>

Your code has "merge" written all over it. 
</panel>

<panel  header="**20 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/146#issuecomment-1795198217" expanded>

My keyboard got chills just by looking at your code.
</panel>

<panel  header="**21 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/190#issuecomment-1807576106" expanded>

Your code is like a well-executed magic trick – it leaves me in awe every time.
</panel>

<panel  header="**22 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/198#issuecomment-1808088607" expanded>

I've seen art in museums less organized than your code.
</panel>

<panel  header="**23 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/201#issuecomment-1808205672" expanded>

Your commits are like a well-written conclusion to a novel – tying up loose those loose ends!
</panel>

<panel  header="**24 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/210#issuecomment-1808607874" expanded>

Your commits are like a magic spell – they make the codebase better with a wave of your keyboard
</panel>

<panel  header="**25 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/208#issuecomment-1808613507" expanded>

Thanks to these commits, our GitHub activity graph puts the Festival of Lights to shame. Happy Deepavali!
</panel>

<panel  header="**26 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/214#issuecomment-1808877536" expanded>

I've seen fewer conflicts in your merges than Dijkstra's algorithm
</panel>

<panel  header="**27 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/219#issuecomment-1809482805" expanded>

Are your commits Bob the Builder? Cuz they fix everything.
</panel>

<panel  header="**28 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/220#issuecomment-1809522446" expanded>

Nothing makes a person more productive than the last minute
</panel>

</panel>


<panel type="info" header="### 62. WU X..NGYU `@DavinciDelta` (0 comments)"  collapsed>


<panel  header="**1 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/19#issuecomment-1762786423" expanded>

Yes this is good no problems!
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/65#issuecomment-1774310535" expanded>

Good test case. Perhaps we could do a generic getInfo function for resources to get all the information
</panel>

<panel  header="**3 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/66#issuecomment-1776522855" expanded>

nice, a good step forward!
</panel>

<panel  header="**4 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/issues/73#issuecomment-1787500416" expanded>

Removed aliasing and improved parsing
</panel>

<panel  header="**5 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/111#issuecomment-1791951998" expanded>

Looks good, good update to UG!
</panel>

<panel  header="**6 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/148#issuecomment-1795035914" expanded>

Good update!
</panel>

<panel  header="**7 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/168#issuecomment-1805049194" expanded>

A good fix to AddCommand!
</panel>

<panel  header="**8 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/184#issuecomment-1807161852" expanded>

Good and informative diagrams!
</panel>

<panel  header="**9 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/182#issuecomment-1807162496" expanded>

Good fix and name updates!
</panel>

<panel  header="**10 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/180#issuecomment-1807162637" expanded>

Good work on your PPP
</panel>

<panel  header="**11 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/189#issuecomment-1807468041" expanded>

Good update
</panel>

<panel  header="**12 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/195#issuecomment-1807683061" expanded>

Good update to storage!
</panel>

<panel  header="**13 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/203#issuecomment-1808322136" expanded>

Good update for readme!
</panel>

<panel  header="**14 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/206#issuecomment-1808460887" expanded>

Good format fix!
</panel>

</panel>


<panel type="info" header="### 63. JOAN..LING `@JoanneJo` (0 comments)"  collapsed>


<panel  header="**1 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/24#issuecomment-1762823246" expanded>

Looks good!
</panel>

<panel  header="**2 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/35#issuecomment-1763699418" expanded>

Looks good!
</panel>

<panel  header="**3 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/49#issuecomment-1766463090" expanded>

Looks good to merge!
</panel>

<panel  header="**4 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/50#issuecomment-1766516221" expanded>

No issues!
</panel>

<panel  header="**5 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/55#issuecomment-1771989432" expanded>

Very neat!
</panel>

<panel  header="**6 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/71#issuecomment-1779950850" expanded>

Looks nice!
</panel>

<panel  header="**7 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/87#issuecomment-1785522795" expanded>

Smooth like butter!
</panel>

<panel  header="**8 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/110#issuecomment-1791913800" expanded>

Nice update!
</panel>

<panel  header="**9 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/103#issuecomment-1791960022" expanded>

Looks good, nice update to the documentations!
</panel>

<panel  header="**10 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/136#issuecomment-1793504158" expanded>

Beautiful upgrade!
</panel>

<panel  header="**11 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/146#issuecomment-1794745398" expanded>

Removed limitations for number of genres.
</panel>

<panel  header="**12 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/147#issuecomment-1795075681" expanded>

Looks good!
</panel>

<panel  header="**13 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/156#issuecomment-1801315615" expanded>

Nice update!
</panel>

<panel  header="**14 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/159#issuecomment-1803192803" expanded>

PPP looking good!
</panel>

<panel  header="**15 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/161#issuecomment-1803470014" expanded>

Nice addition!
</panel>

<panel  header="**16 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/162#issuecomment-1803471829" expanded>

Great update!
</panel>

<panel  header="**17 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/164#issuecomment-1804001420" expanded>

Cool addition!
</panel>

<panel  header="**18 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/169#issuecomment-1805172878" expanded>

PPP looking good!
</panel>

<panel  header="**19 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/172#issuecomment-1805943241" expanded>

Great addition!
</panel>

<panel  header="**20 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/issues/121#issuecomment-1806260938" expanded>

ID is not an input argument in v2.1.
</panel>

<panel  header="**21 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/issues/122#issuecomment-1806270707" expanded>

ID is not an input argument in v2.1. Negative ISBN fixed.
</panel>

<panel  header="**22 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/187#issuecomment-1807203711" expanded>

Looks good!
</panel>

<panel  header="**23 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/211#issuecomment-1809273198" expanded>

Great effort! Looks good!
</panel>

<panel  header="**24 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/213#issuecomment-1809274414" expanded>

Good catch!
</panel>

<panel  header="**25 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/220#issuecomment-1809510157" expanded>

Nice!
</panel>

</panel>


<panel type="info" header="### 64. VELU..LAJI `@000verflow` (0 comments)"  collapsed>


<panel  header="**1 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/22#discussion_r1359348530" expanded>

Fixed the bug, thank you for the review!
</panel>

<panel  header="**2 :octicon-git-pull-request::octicon-comment:** (commented on own PR)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/166#discussion_r1387799869" expanded>

Thanks for the inputs, ill make the changes.
</panel>

<panel  header="**3 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/16#issuecomment-1762743062" expanded>

LGTM
</panel>

<panel  header="**4 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/25#issuecomment-1762856432" expanded>

LGTM
</panel>

<panel  header="**5 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/22#issuecomment-1763269521" expanded>

fixes #20
</panel>

<panel  header="**6 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/33#issuecomment-1763341731" expanded>

LGTM
</panel>

<panel  header="**7 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/34#issuecomment-1763405256" expanded>

LGTM
</panel>

<panel  header="**8 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/84#issuecomment-1784056095" expanded>

LGTM!
</panel>

<panel  header="**9 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/89#issuecomment-1787056746" expanded>

LGTM
</panel>

<panel  header="**10 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/95#issuecomment-1787339096" expanded>

fixes #92 
</panel>

<panel  header="**11 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/100#issuecomment-1787490951" expanded>

LGTM
</panel>

<panel  header="**12 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/102#issuecomment-1789073634" expanded>

looks good!
</panel>

<panel  header="**13 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/107#issuecomment-1790221588" expanded>

Nicely done.
</panel>

<panel  header="**14 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/118#issuecomment-1793348037" expanded>

I did copy the ACTUAL.txt, but may the github's server wasn't in the same timezone as us, so it failed on the github side.
</panel>

<panel  header="**15 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/118#issuecomment-1793348509" expanded>

Yea my hypothesis was right, I rerun now and it works.
</panel>

<panel  header="**16 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/issues/124#issuecomment-1793357086" expanded>

Resolved in 2.1
</panel>

<panel  header="**17 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/issues/114#issuecomment-1793357129" expanded>

Fixed
</panel>

<panel  header="**18 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/issues/81#issuecomment-1793357159" expanded>

Fixed
</panel>

<panel  header="**19 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/133#issuecomment-1793367395" expanded>

Looks good!
</panel>

<panel  header="**20 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/134#issuecomment-1793404175" expanded>

Nice updates!
</panel>

<panel  header="**21 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/137#issuecomment-1793635585" expanded>

Nice addition !
</panel>

<panel  header="**22 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/140#issuecomment-1793667916" expanded>

Nice changes!
</panel>

<panel  header="**23 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/140#issuecomment-1793680718" expanded>

Looks good
</panel>

<panel  header="**24 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/143#issuecomment-1793994540" expanded>

Nice changes
</panel>

<panel  header="**25 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/151#issuecomment-1798063863" expanded>

fixes #92 
fixes #106 
</panel>

<panel  header="**26 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/issues/119#issuecomment-1798066626" expanded>

Been fixed
</panel>

<panel  header="**27 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/153#issuecomment-1798532278" expanded>

Nice!
</panel>

<panel  header="**28 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/176#issuecomment-1807101623" expanded>

Nice changes
</panel>

<panel  header="**29 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/185#issuecomment-1807162687" expanded>

Nice changes
</panel>

<panel  header="**30 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/pull/183#issuecomment-1807164399" expanded>

Nice changes!
</panel>

<panel  header="**31 :octicon-comment:** (other comment)" popup-url="https://github.com/AY2324S1-CS2113T-W11-1/tp/issues/209#issuecomment-1808574424" expanded>

Fixed, bug with mkdir function for mac os
</panel>

</panel>
