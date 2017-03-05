# 100 Days Of Code - Log

### Day 0: January 2, 2017, Monday

**Today's Progress**: Read the blog post, did some reading on Android Studio, came up with some project ideas.

**Thoughts**: Very nervous to commit to 100 days of code.

**Link(s) to work**

1. [Blog post](https://medium.freecodecamp.com/start-2017-with-the-100daysofcode-improved-and-updated-18ce604b237b#.kqfg6syur)

2. [Android Studio page](https://developer.android.com/studio/index.html)

### Day 1: January 3, 2017, Tuesday

**Today's Progress**: Installed Android Studio, imported my Android app "KitchenMaster" project, troubleshot import problems, learned basics of adding search feature to Android apps.

**Thoughts**: Why is it that instead of CODING you spend most of the time COPING with software installs?! Moving from Eclipse to Android Studio is totally killing me....

**Link(s) to work**

1. [Initial commit of KitchenMaster App](https://github.com/ConnieZ/KitchenMaster)

2. [Android Searching Functionality Tutorial](https://developer.android.com/training/search/index.html)

### Day 2: January 4, 2017, Wednesday

**Today's Progress**: Had to reorganize the app code for Android Studio and re-write some pieces. Got it to work on an emulator, but it's so outdated the action bar (menu) stopped working (even though on my 4.4 Android phone the app works fine, must be the support libraries...). Learned about ActionBar and ToolBar, which one to use and how.  

**Thoughts**: I wish Android libraries were more backwards compatible out of the box without messing with support libraries.

**Link(s) to work**

1. [Updated version of the KitchenMaster App](https://github.com/ConnieZ/KitchenMaster)

2. [Android ActionBar and ToolBar Tutorial](https://developer.android.com/training/appbar/setting-up.html)

### Day 3: January 5, 2017, Thursday

**Today's Progress**: Had to pause working on my KitchenMaster app in favor of learning how to convert a ListActivity into an AppCompatActivity. I managed that by using a test project, which I called "White Wine List". Had to read a ton and troubleshoot a kilo.

**Thoughts**: I learned a lot about how Views work in Android apps, troubleshooting is the best teacher.

**Link(s) to work**

1. [Original source code](https://www.mkyong.com/android/android-listview-example/)

2. [My White Wine List App based on that example](https://github.com/ConnieZ/ListViewApp)

### Day 4: January 6, 2017, Friday

**Today's Progress**: On my beautiful "White Wine List" App, I added a ToolBar and a SearchView, to enable searching for wine types. Spent more than an hour due to research and troubleshooting.

**Thoughts**: Android guides don't make it easy to learn, it appears. StackOverflow rules in that respect.

**Link(s) to work**

1. [See three last commits to White Wine List App](https://github.com/ConnieZ/ListViewApp)

### Day 5: January 7, 2017, Saturday

**Today's Progress**: On my beautiful "White Wine List" App, on my ToolBar there's now a functional Search button and a "Add New" button, which I'll have to implement. I made search work, but still haven't been able to make the results of the search show up. I also implemented a database backend based on a text file that gets loaded into a virtual SQL table. I learned about Content Providers a bit, which I didn't intend to, but had to in order to implement db and search...

**Thoughts**: It's getting a little frustrating: every time I sit down for an hour of code, I end up spending way more than that just to make a real accomplishment for the day, but Java is not cooperating.

**Link(s) to work**

1. [See three last commits to White Wine List App](https://github.com/ConnieZ/ListViewApp)

### Day 6: January 8, 2017, Sunday

**Today's Progress**: On my beautiful "White Wine List" App, search widget now works and returns results, athough they lack style, so look ugly. Piled through tutorials on how to implement returning results from search

**Thoughts**: I wish at least one of the tutorials I found was complete and bug-free.

**Link(s) to work**

1. [See last commit to White Wine List App](https://github.com/ConnieZ/ListViewApp)
2. [Tutorial most helpful for search and returning results](https://inducesmile.com/android/android-search-dialog-implementation-example/)

### Day 7: January 9, 2017, Monday

**Today's Progress**: On my beautiful "White Wine List" App, played around with style and layouts. Watched coursera videos about Intents for Android.

**Thoughts**: Today was a little bit more relaxing.

**Link(s) to work**

1. [See last commit to White Wine List App](https://github.com/ConnieZ/ListViewApp)
2. [Coursera class](https://www.coursera.org/learn/androidapps)

### Day 8: January 10, 2017, Tuesday

**Today's Progress**: On my beautiful "White Wine List" App, I figured out how to display multiple columns with a custom adapter class. Implemented that and made some slight style changes to improve viewing.

**Thoughts**: Feeling pretty confident with displaying results in views.

**Link(s) to work**

1. [See last commit to White Wine List App](https://github.com/ConnieZ/ListViewApp)
2. [Best help in custom adapter development](http://stackoverflow.com/questions/11678909/use-array-adapter-with-more-views-in-row-in-listview)


### Day 9: January 11, 2017, Wednesday

**Today's Progress**: Broke my beautiful "White Wine List" App a bit while adding a wider dataset. Will need to fix tomorrow.

**Thoughts**: Why db's are always a headache?

**Link(s) to work**

1. [See last commit to White Wine List App](https://github.com/ConnieZ/ListViewApp)

### Day 10: January 12, 2017, Thursday

**Today's Progress**: Tried fixing today. Made the "White Wine List" App a bit more robust, but had to revert back the wider data, cause it just won't work. Will shift gears tomorrow and focus on the KitchenMaster app instead.

**Thoughts**: Why db's are always a headache?

**Link(s) to work**

1. [See last commit to White Wine List App](https://github.com/ConnieZ/ListViewApp)

### Day 11: January 13, 2017, Friday

**Today's Progress**: Made some real progress with my KitcheMaster app, it has a couple new classes responsible for item management and display of lists. Added some initial data to the database to display on start. Still more work to do.

**Thoughts**: Feeling pretty satisfied with my progress today.

**Link(s) to work**

1. [See last commit to KitcheMaster App](https://github.com/ConnieZ/KitchenMaster/commit/a63ec005f6593dde5227e2d6890eb6ac056ee2c2)

### Day 12: January 14, 2017, Saturday

**Today's Progress**: On the KitchenMaster app made display of quanitites work, added the ability to add new items. Still having trouble with clicking on items

**Thoughts**: Feeling pretty satisfied with my progress today.

**Link(s) to work**

1. [See last commit to KitcheMaster App](https://github.com/ConnieZ/KitchenMaster/commit/aae3ce03a114d23a7fc88216367656fcc98c6ac8)

### Day 13: January 15, 2017, Sunday

**Today's Progress**: On the KitchenMaster app, I fixed the onClickListener capability, and added the search icon. Will continue working on search tomorrow.

**Thoughts**: Wow, so much headache over just the wrong data type...

**Link(s) to work**

1. [See last commit to KitcheMaster App](https://github.com/ConnieZ/KitchenMaster/commit/000fb8f1ea5eb71381ba26e48a6d3038fe764e27)

### Day 14: January 16, 2017, Monday

**Today's Progress**: On the KitchenMaster app, I added search widget, searchableactivity and searchable xml. But clicking enter on the entered data still doesn't work.

**Thoughts**: Why is search so complicated, Android?

**Link(s) to work**

1. [See last commit to KitcheMaster App](https://github.com/ConnieZ/KitchenMaster/commit/8e5addf6100b28e81d0f438cef263d3f28f9b03c)

### Day 15: January 17, 2017, Tuesday

**Today's Progress**: On the KitchenMaster app, I tried to fix search widget, but it just wouldn't budge, I'm doing everything right from the tutorials and stackoverflow, but it just won't work.

**Thoughts**: Why is search so complicated, Android?

**Link(s) to work**

1. [See last commit to KitcheMaster App](https://github.com/ConnieZ/KitchenMaster/commit/273e624ddfc3e0237ffb3ef81f80942ab0ecc784)

### Day 16: January 18, 2017, Wednesday

**Today's Progress**: On the KitchenMaster app, I enabled the Shopping List functionality and context menu. Will have to still fix search.

**Thoughts**: Why is search so complicated, Android?

**Link(s) to work**

1. [See last commit to KitcheMaster App](https://github.com/ConnieZ/KitchenMaster/commit/7d472e5e9375eff548eeabfbda0cf7a504c58074)


### Day 17: January 19, 2017, Thursday

**Today's Progress**: On the KitchenMaster app, I finally fixed search widget, it now responds to queries and displays results. I also made the "Add Item" activity more robust - empty entries won't be stored in the database.

**Thoughts**: OMG, just not having the full path to searchable activity is what screwed me over earlier.

**Link(s) to work**

1. [See last commit to KitcheMaster App](https://github.com/ConnieZ/KitchenMaster/commit/858f5e85f8bb3acf895d392e584381b2952f62f3)
2. [The most helpful source in getting search to work today](http://stackoverflow.com/questions/17311434/search-dialog-is-not-called-onsearchrequested)


### Day 18: January 20, 2017, Friday

** Today's Progress**: On the KitchenMaster app, I made search work in the main activity, returning results to the same page basically in the same format. I also fixed shopping list bug, where the results didn't get refreshed on returning back to main activity.

**Thoughts**: Very excited to be almost done with this project and be able to move on.

**Link(s) to work**

1. [See last commit to KitcheMaster App](https://github.com/ConnieZ/KitchenMaster/commit/f694f43eac347e6a4cbff673dac2dd5a37f286c7)
2. [The most helpful source in getting search to work today](http://stackoverflow.com/questions/24928906/android-how-to-return-to-same-activity-after-search-is-done-in-a-single-activity)

### Day 19: January 21, 2017, Saturday

** Today's Progress**: For a change I did an Android coursera class assignment focused on intents.

**Thoughts**: Felt different to solve a problem, I didn't think of.

**Link(s) to work**

1. [Assignment Solutions to Coursera Android Class](https://github.com/ConnieZ/myAndroidAppDevSpecialization/tree/master/Android_App_Components/week2)

### Day 20: January 22, 2017, Sunday

** Today's Progress**: Worked some more on the Android class assignment. Also in preparation for a machine learning project, I made the delay_predictor app more robust.

**Thoughts**: Learning every day is cool!

**Link(s) to work**

1. [Commit to Assignment Solutions to Coursera Android Class](https://github.com/ConnieZ/myAndroidAppDevSpecialization/commit/3d2494df795a97254d8c1ad3d68b3982614164a0)
2. [Delay_predictor app commit](https://github.com/ConnieZ/delay_predictor/commit/e624bde24e8d17d3f456aef53fe123c081901344)

### Day 21: January 23, 2017, Monday

** Today's Progress**: Worked on the delay_predictor app - added a decision tree algorithm, and made the sampling and filtering of datasets more robust. Will work on visualization next.

**Thoughts**: Learning every day is cool!

**Link(s) to work**

1. [Delay_predictor app commit](https://github.com/ConnieZ/delay_predictor/commit/d1e3d65f8b8c70cd24d66e35058f9b45d6784e1a)

### Day 22: January 24, 2017, Tuesday

** Today's Progress**: Worked on the delay_predictor app - added another decision tree algorithm, this one for C4.5 methodology, and got quite different results than from tree package.

**Thoughts**: Hmm, need to learn about criteria for decision tree choices.

**Link(s) to work**

1. [Delay_predictor app commit](https://github.com/ConnieZ/delay_predictor/commit/4a1ef51db3bb6a5cba4493d2e3e0e389632b313b)
2. [Tutorial on trees](http://blog.revolutionanalytics.com/2013/06/plotting-classification-and-regression-trees-with-plotrpart.html)

### Day 23: January 25, 2017, Wednesday

** Today's Progress**: Worked on the delay_predictor app - modified the UI to use ShinyDashboard package. Added decision tree analysis to the UI.

**Thoughts**: Hmm, need to learn about criteria for decision tree choices.

**Link(s) to work**

1. [Delay_predictor app commit](https://github.com/ConnieZ/delay_predictor/commit/522b9783fdd9b77cb14ec6041ef812b7e90fd3b7)


### Day 24: January 26, 2017, Thursday

** Today's Progress**: Worked on the delay_predictor app - added a new Decision tree from Rweka package. Fixed some bugs. Fought a losing battle with SparkR on Jupyter.

**Thoughts**: How do you transform data (not model) of SparkR dataframes?

**Link(s) to work**

1. [Delay_predictor app commit](https://github.com/ConnieZ/delay_predictor/commit/f65e2b5062de5afe87b2c1027cddd73e8f0a6ac4)

### Day 25: January 27, 2017, Friday

** Today's Progress**: Worked on the delay_predictor app - added a CPART decision tree from rpart package. In light of discoveries, new chart shows mean departure delay based on Hour of departure.

**Thoughts**: Wow, decision trees are all lining up, but different packages give different levels of complexity.

**Link(s) to work**

1. [Delay_predictor app commit](https://github.com/ConnieZ/delay_predictor/commit/4824aae767abeb978ff96ccbfbfdfc42f4ece1d9)


### Day 26: January 28, 2017, Saturday

** Today's Progress**: Stretched my brain with some algorithms in freeCodeCamp.

**Thoughts**: Thought I would relax, but actually had some trouble with those algorithms, I guess I'm overthinking them.

**Link(s) to work**

1. [Public FreeCodeCamp profile and progress](https://www.freecodecamp.com/conniez)



### Day 27: January 29, 2017, Sunday

** Today's Progress**: Roman Numerals Converter is kicking my ass. I couldn't actually finish it today. Will continue tomorrow.

**Thoughts**: Thought I would relax, but actually had some trouble with those algorithms, I guess I'm overthinking them.

**Link(s) to work**

1. [The challenge]: (https://www.freecodecamp.com/challenges/roman-numeral-converter)


### Day 28: January 30, 2017, Monday

** Today's Progress**: Back to working on KitchenMaster app - preventing duplicates in db, making code more readable. Also worked on decision trees - C4.5 in Rweka is quite annoying.

**Thoughts**: Keeping up with Android upgrades is like keeping up with the Kardashians - super frustrating and makes you feel dumb.

**Link(s) to work**

1. [KitchenMaster latest commit]: (https://github.com/ConnieZ/KitchenMaster/commit/ea7ae5d6d47ce2849a6d92172707378d63b2bf6b)


### Day 29: January 31, 2017, Tuesday

** Today's Progress**: Back to working on KitchenMaster app - implemented loading of initial data from txt file, so won't need to manually enter all the data into phone when upgrading. Added logo to action bar. Will look into preventing SQLiteConnection leaks.

**Thoughts**: Feeling pretty good about today's progress.

**Link(s) to work**

1. [KitchenMaster latest commit]: (https://github.com/ConnieZ/KitchenMaster/commit/d65e636555fe4382c2410d55392677643b4a898b)

### Day 30: February 1, 2017, Wednesday

** Today's Progress**: Back to working on KitchenMaster app - eliminated SQLite db Connection leaks, fixed the layout bug in ShoppingList activity, added over a 100 default items, streamlined code and converted SL activity to AppCompactActivity.

**Thoughts**: Feeling pretty good about today's progress.

**Link(s) to work**

1. [KitchenMaster commit 1]: (https://github.com/ConnieZ/KitchenMaster/commit/a57786d711393a63427532ac28f07abb8db3f7f8)
2. [KitchenMaster commit 2]: (https://github.com/ConnieZ/KitchenMaster/commit/9316a1737f6a08ed93c1ae78eb69028900fca3c2)


### Day 31: February 2, 2017, Thursday

** Today's Progress**: Took some more freecodecamp challenges, learning array functions in JavaScript.

**Thoughts**: Having fun, especially with map and reduce.

**Link(s) to work**

1. [KitchenMaster commit 1]:(https://www.freecodecamp.com/conniez)

### Day 32: February 3, 2017, Friday

** Today's Progress**: 4 more array challenges in JavaScript.

**Thoughts**: Having fun, especially with map and reduce.

**Link(s) to work**

1. [KitchenMaster commit 1]:(https://www.freecodecamp.com/conniez)


### Day 33: February 4, 2017, Saturday

** Today's Progress**: 5 more algorithm challenges in JavaScript.

**Thoughts**: Having fun, especially with map and reduce.

**Link(s) to work**

1. [KitchenMaster commit 1]:(https://www.freecodecamp.com/conniez)


### Day 34: February 5, 2017, Sunday

** Today's Progress**: Taking advantage of the challenge to prep for Java exam - spent 3 hours on Java OCA Exam practice.

**Thoughts**: Still some topics present difficulties, will share the code of practice in a separate repo soon.

**Link(s) to work**

1. [Link to Practice Test site]:(http://sybextestbanks.wiley.com/)



### Day 35: February 6, 2017, Monday

** Today's Progress**: Working on some of the trickier Java concepts based on OCA practice test results.

**Thoughts**: Bottom line - pay close attention to the code.

**Link(s) to work**

1. [Link to Practice Code Commit]:(https://github.com/ConnieZ/JavaExamPrep/commit/784699998c418540bd9fbf9c33ff9361bc6fad9c)



### Day 36: February 7, 2017, Tuesday

** Today's Progress**: Continued working on some of the trickier Java concepts based on OCA practice test results.

**Thoughts**: Bottom line - pay close attention to the code.

**Link(s) to work**

1. [Link to latest Practice Code Commit]:(https://github.com/ConnieZ/JavaExamPrep/commit/1cefa1dd40ee19568cca964beece1dbce96df9f5)


### Day 37: February 8, 2017, Wednesday

** Today's Progress**: Continued working on some of the trickier Java concepts based on OCA practice test results.

**Thoughts**: Bottom line - pay close attention to the code.

**Link(s) to work**

1. [Link to latest Practice Code Commit]:(https://github.com/ConnieZ/JavaExamPrep/commit/7e0db8ca8610f2da4585d7af9eab4f3fe52ba3c1)



### Day 38: February 9, 2017, Thursday

** Today's Progress**: Mostly solved freecodecamp JavaScript challenges, but also continued working on some of the trickier Java concepts based on OCA practice test results.

**Thoughts**: One basic challenge left in freecodecamp, bottom line - pay close attention to the code.

**Link(s) to work**

1. [Link to latest Practice Code Commit]:(https://github.com/ConnieZ/JavaExamPrep/commit/83eca760f70fd39a523ceec1cbeb97ba93fb0096)
2. [Challenges solved today on freecodecamp]:(https://www.freecodecamp.com/conniez)


### Day 39: February 10, 2017, Friday

** Today's Progress**: Continued working on some of the trickier Java concepts based on OCA practice test results.

**Thoughts**: Done with the training, time to take the practice test again.

**Link(s) to work**

1. [Link to latest Practice Code Commit]:(https://github.com/ConnieZ/JavaExamPrep/commit/92e1f1ab223649a05504e50382f42dee61a7d7b5)

### Day 40: February 11, 2017, Saturday

** Today's Progress**: In my delay_predictor, I added C5.0 tree algorithm, and pruned C5.0 tree. Prettified the UI slightly.

**Thoughts**: So far 4 tree algorithms agree that scheduled Departure Hour is one of the most important factors in flights being delayed.

**Link(s) to work**

1. [Link to latest Commit]:(https://github.com/ConnieZ/delay_predictor/commit/4780c8fcc777bd06969beb2c717bdab79d441bb0)

### Day 41: February 12, 2017, Sunday

** Today's Progress**: In my KitchenMaster, changed database data model, refactored code to fit that. I reached Level 4 on codingame.com.

**Thoughts**: Had a blast on codingame.com.

**Link(s) to work**

1. [Link to latest Commit]:(https://github.com/ConnieZ/KitchenMaster/commit/a19d79216136f1aae0d42890018ef8047e31df6b)


### Day 42: February 13, 2017, Monday

** Today's Progress**: I created a practice app to learn Android Fragments.

**Thoughts**: A little confused by Fragments.

**Link(s) to work**

1. [Link to latest Commit]:(https://github.com/ConnieZ/FragmentApplicationAndroid/commit/fbd74377be23dc4fb8363ef56a1c2ba3725a0f72)


### Day 43: February 14, 2017, Tuesday

** Today's Progress**: Did some more Java review for OCA, practed tricky String, StringBuilder, arrays, casting rules.

**Thoughts**: I would really like to pass the OCA exam at the end of the 100DaysOfCode challenge.

**Link(s) to work**

1. [Link to latest Commit]:(https://github.com/ConnieZ/JavaExamPrep/commit/415ca91c53952b8904420b8ca77c6972360ed439)


### Day 44: February 15, 2017, Wednesday

** Today's Progress**: Practiced Java by solving puzzles on CodinGame.

**Thoughts**: I would really like to pass the OCA exam at the end of the 100DaysOfCode challenge.

**Link(s) to work**

1. [Link to CodinGame profile]:(https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)


### Day 45: February 16, 2017, Thursday

** Today's Progress**: Did some more Java review for OCA, practed tricky access modifier, inheritance, overriding and overloading rules.

**Thoughts**: I would really like to pass the OCA exam at the end of the 100DaysOfCode challenge.

**Link(s) to work**

1. [Link to latest Commit]:(https://github.com/ConnieZ/JavaExamPrep/commit/13eb3f4d1db7240b2f9cc81a601e8a546426ca49)


### Day 46: February 17, 2017, Friday

** Today's Progress**: Continued Java review for OCA, practed tricky access modifier, inheritance, overriding and overloading rules.

**Thoughts**: I would really like to pass the OCA exam at the end of the 100DaysOfCode challenge.

**Link(s) to work**

1. [Link to latest Commit]:(https://github.com/ConnieZ/JavaExamPrep/commit/ab5cce55cee2b754c474d7d6f3c2f84ce8a38361)



### Day 47: February 18, 2017, Saturday

** Today's Progress**: Played my first clash of code on CodinGame, solved some puzzles.

**Thoughts**: They are not getting easier...

**Link(s) to work**

1. [Link to CodinGame profile]:(https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)


### Day 48: February 19, 2017, Sunday

** Today's Progress**: Reviewing arrays and arrayLists for Java exam.

**Thoughts**: Apparently you can't instantiate a variable outside a method, unless it's combined with declaration...

**Link(s) to work**

1. [Link to latest commit]:(https://github.com/ConnieZ/JavaExamPrep/commit/5fe8de0d4384ba364e82fa326449594f46c195f2)

### Day 49: February 20, 2017, Monday

** Today's Progress**: Continued reviewing arrays and arrayLists for Java exam.

**Thoughts**: Correction, turns out you can remove int from ArrayList, by using Integer wrapper class. Hey, you learn sth new every day :)

**Link(s) to work**

1. [Link to latest commit]:(https://github.com/ConnieZ/JavaExamPrep/commit/d84fb3d9d51d9165a50832c629d337ba91ca2781)
2. [Link to a Jupyter Notebooks repo]:(https://github.com/ConnieZ/Data_Science_with_SparkR)


### Day 50: February 21, 2017, Tuesday

** Today's Progress**: Continued reviewing arrays and arrayLists for Java exam.

**Thoughts**: Wow, I'm half-way through the challenge!

**Link(s) to work**

1. [Link to latest commit]:(https://github.com/ConnieZ/JavaExamPrep/commit/b59379495264d4015168de766a37536416b009b0)


### Day 51: February 22, 2017, Wednesday

** Today's Progress**: Learning Date and Time API in Java 8.

**Thoughts**: Wow, I'm half-way through the challenge!

**Link(s) to work**

1. [Link to latest commit]:(https://github.com/ConnieZ/JavaExamPrep/commit/f349e6ccb5fe472fcc90b15035691f8de82f2e9f)



### Day 52: February 23, 2017, Thursday

** Today's Progress**: Continued learning Date and Time API in Java 8.

**Thoughts**: 

**Link(s) to work**

1. [Link to latest commit]:(https://github.com/ConnieZ/JavaExamPrep/commit/fe1ced0757d8beb5e8ab05cf8db49de7013e9c34)

### Day 53: February 24, 2017, Friday

** Today's Progress**: Finished reviewing Date and Time API in Java 8. Solved Caesar Cipher challenge on freecodecamp.

**Thoughts**: 

**Link(s) to work**

1. [Link to latest commit]:(https://github.com/ConnieZ/JavaExamPrep/commit/7941b5a5ce6744ca7284b4e4d9bba704bebe398e)
2. [Link to freecodecamp profile]:(https://www.freecodecamp.com/conniez)


### Day 54: February 25, 2017, Saturday

** Today's Progress**: Learned bot programming through a starship race on codingame.com

**Thoughts**: It's pretty fascinating to learn multiplayer game programming.

**Link(s) to work**

1. [Link to codingame profile]:(https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)


### Day 55: February 26, 2017, Sunday

** Today's Progress**: Performed bot programming as part of Ghost in the Cell contest at codingame.com

**Thoughts**: Took me hours to get out of lowest Leage, now I'm Wood 2 League, and not the last one.

**Link(s) to work**

1. [Link to codingame profile]:(https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)
2. [Link to contest]:(https://www.codingame.com/contests/ghost-in-the-cell)


### Day 56: February 27, 2017, Monday

** Today's Progress**: Significantly improved my code for bot programming as part of Ghost in the Cell contest at codingame.com

**Thoughts**: I'm finally in Wood 1 League, and closer to the top!

**Link(s) to work**

1. [Link to codingame profile]:(https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)
2. [Link to contest]:(https://www.codingame.com/contests/ghost-in-the-cell)


### Day 57: February 28, 2017, Tuesday

** Today's Progress**: Improved my code for bot programming as part of Ghost in the Cell contest at codingame.com

**Thoughts**: I made it to the Bronze League, Woot Woot!

**Link(s) to work**

1. [Link to codingame profile]:(https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)
2. [Link to contest]:(https://www.codingame.com/contests/ghost-in-the-cell)



### Day 58: March 1, 2017, Wednesday

** Today's Progress**: Improved my code for bot programming as part of Ghost in the Cell contest at codingame.com

**Thoughts**: Still in the Bronze League, but getting higher to the top!

**Link(s) to work**

1. [Link to codingame profile]:(https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)
2. [Link to contest]:(https://www.codingame.com/contests/ghost-in-the-cell)


### Day 59: March 2, 2017, Thursday

** Today's Progress**: While working on the contest, I learned Comparator, comparing objects by attribute. Improved my code for bot programming as part of Ghost in the Cell contest at codingame.com

**Thoughts**: Still in the Bronze League, but getting higher to the top, highest today was 48 out of 1463!

**Link(s) to work**

1. [Commit to java practice repo]:(https://github.com/ConnieZ/JavaExamPrep/commit/37e98950fa64735463c89f6408e013ea04f49d28)
2. [Link to codingame profile]:(https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)
3. [Link to contest]:(https://www.codingame.com/contests/ghost-in-the-cell)


### Day 60: March 3, 2017, Friday

** Today's Progress**: Learned how to extend, save, push and load Docker images. Improved my code for bot programming as part of Ghost in the Cell contest at codingame.com

**Thoughts**: Still in the Bronze League, but getting higher to the top, highest today was 48 out of 1463!

**Link(s) to work**

1. [Commit Docker stacks]:(https://github.com/ConnieZ/docker-stacks/commit/9291b20f298b622b3cb9719c6314417893c98d84)
2. [Link to codingame profile]:(https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)
3. [Link to contest]:(https://www.codingame.com/contests/ghost-in-the-cell)


### Day 61: March 4, 2017, Saturday

** Today's Progress**: Submitted my last improvement to bot algorithm in Ghost in the Cell contest at codingame.com

**Thoughts**: Still in the Bronze League, highest today was 29 out of 1463! Ranking 95 in the US.

**Link(s) to work**

1. [Replay of my algorithm]:(https://www.codingame.com/replay/193645882)
2. [Link to codingame profile]:(https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)
3. [Link to contest]:(https://www.codingame.com/contests/ghost-in-the-cell)
