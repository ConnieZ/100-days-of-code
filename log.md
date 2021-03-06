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

1. [The challenge](https://www.freecodecamp.com/challenges/roman-numeral-converter)


### Day 28: January 30, 2017, Monday

** Today's Progress**: Back to working on KitchenMaster app - preventing duplicates in db, making code more readable. Also worked on decision trees - C4.5 in Rweka is quite annoying.

**Thoughts**: Keeping up with Android upgrades is like keeping up with the Kardashians - super frustrating and makes you feel dumb.

**Link(s) to work**

1. [KitchenMaster latest commit](https://github.com/ConnieZ/KitchenMaster/commit/ea7ae5d6d47ce2849a6d92172707378d63b2bf6b)


### Day 29: January 31, 2017, Tuesday

** Today's Progress**: Back to working on KitchenMaster app - implemented loading of initial data from txt file, so won't need to manually enter all the data into phone when upgrading. Added logo to action bar. Will look into preventing SQLiteConnection leaks.

**Thoughts**: Feeling pretty good about today's progress.

**Link(s) to work**

1. [KitchenMaster latest commit](https://github.com/ConnieZ/KitchenMaster/commit/d65e636555fe4382c2410d55392677643b4a898b)

### Day 30: February 1, 2017, Wednesday

** Today's Progress**: Back to working on KitchenMaster app - eliminated SQLite db Connection leaks, fixed the layout bug in ShoppingList activity, added over a 100 default items, streamlined code and converted SL activity to AppCompactActivity.

**Thoughts**: Feeling pretty good about today's progress.

**Link(s) to work**

1. [KitchenMaster commit 1](https://github.com/ConnieZ/KitchenMaster/commit/a57786d711393a63427532ac28f07abb8db3f7f8)
2. [KitchenMaster commit 2](https://github.com/ConnieZ/KitchenMaster/commit/9316a1737f6a08ed93c1ae78eb69028900fca3c2)


### Day 31: February 2, 2017, Thursday

** Today's Progress**: Took some more freecodecamp challenges, learning array functions in JavaScript.

**Thoughts**: Having fun, especially with map and reduce.

**Link(s) to work**

1. [KitchenMaster commit 1](https://www.freecodecamp.com/conniez)

### Day 32: February 3, 2017, Friday

** Today's Progress**: 4 more array challenges in JavaScript.

**Thoughts**: Having fun, especially with map and reduce.

**Link(s) to work**

1. [KitchenMaster commit 1](https://www.freecodecamp.com/conniez)


### Day 33: February 4, 2017, Saturday

** Today's Progress**: 5 more algorithm challenges in JavaScript.

**Thoughts**: Having fun, especially with map and reduce.

**Link(s) to work**

1. [KitchenMaster commit 1](https://www.freecodecamp.com/conniez)


### Day 34: February 5, 2017, Sunday

** Today's Progress**: Taking advantage of the challenge to prep for Java exam - spent 3 hours on Java OCA Exam practice.

**Thoughts**: Still some topics present difficulties, will share the code of practice in a separate repo soon.

**Link(s) to work**

1. [Link to Practice Test site](http://sybextestbanks.wiley.com/)



### Day 35: February 6, 2017, Monday

** Today's Progress**: Working on some of the trickier Java concepts based on OCA practice test results.

**Thoughts**: Bottom line - pay close attention to the code.

**Link(s) to work**

1. [Link to Practice Code Commit](https://github.com/ConnieZ/JavaExamPrep/commit/784699998c418540bd9fbf9c33ff9361bc6fad9c)



### Day 36: February 7, 2017, Tuesday

** Today's Progress**: Continued working on some of the trickier Java concepts based on OCA practice test results.

**Thoughts**: Bottom line - pay close attention to the code.

**Link(s) to work**

1. [Link to latest Practice Code Commit](https://github.com/ConnieZ/JavaExamPrep/commit/1cefa1dd40ee19568cca964beece1dbce96df9f5)


### Day 37: February 8, 2017, Wednesday

** Today's Progress**: Continued working on some of the trickier Java concepts based on OCA practice test results.

**Thoughts**: Bottom line - pay close attention to the code.

**Link(s) to work**

1. [Link to latest Practice Code Commit](https://github.com/ConnieZ/JavaExamPrep/commit/7e0db8ca8610f2da4585d7af9eab4f3fe52ba3c1)



### Day 38: February 9, 2017, Thursday

** Today's Progress**: Mostly solved freecodecamp JavaScript challenges, but also continued working on some of the trickier Java concepts based on OCA practice test results.

**Thoughts**: One basic challenge left in freecodecamp, bottom line - pay close attention to the code.

**Link(s) to work**

1. [Link to latest Practice Code Commit](https://github.com/ConnieZ/JavaExamPrep/commit/83eca760f70fd39a523ceec1cbeb97ba93fb0096)
2. [Challenges solved today on freecodecamp](https://www.freecodecamp.com/conniez)


### Day 39: February 10, 2017, Friday

** Today's Progress**: Continued working on some of the trickier Java concepts based on OCA practice test results.

**Thoughts**: Done with the training, time to take the practice test again.

**Link(s) to work**

1. [Link to latest Practice Code Commit](https://github.com/ConnieZ/JavaExamPrep/commit/92e1f1ab223649a05504e50382f42dee61a7d7b5)

### Day 40: February 11, 2017, Saturday

** Today's Progress**: In my delay_predictor, I added C5.0 tree algorithm, and pruned C5.0 tree. Prettified the UI slightly.

**Thoughts**: So far 4 tree algorithms agree that scheduled Departure Hour is one of the most important factors in flights being delayed.

**Link(s) to work**

1. [Link to latest Commit](https://github.com/ConnieZ/delay_predictor/commit/4780c8fcc777bd06969beb2c717bdab79d441bb0)

### Day 41: February 12, 2017, Sunday

** Today's Progress**: In my KitchenMaster, changed database data model, refactored code to fit that. I reached Level 4 on codingame.com.

**Thoughts**: Had a blast on codingame.com.

**Link(s) to work**

1. [Link to latest Commit](https://github.com/ConnieZ/KitchenMaster/commit/a19d79216136f1aae0d42890018ef8047e31df6b)


### Day 42: February 13, 2017, Monday

** Today's Progress**: I created a practice app to learn Android Fragments.

**Thoughts**: A little confused by Fragments.

**Link(s) to work**

1. [Link to latest Commit](https://github.com/ConnieZ/FragmentApplicationAndroid/commit/fbd74377be23dc4fb8363ef56a1c2ba3725a0f72)


### Day 43: February 14, 2017, Tuesday

** Today's Progress**: Did some more Java review for OCA, practed tricky String, StringBuilder, arrays, casting rules.

**Thoughts**: I would really like to pass the OCA exam at the end of the 100DaysOfCode challenge.

**Link(s) to work**

1. [Link to latest Commit](https://github.com/ConnieZ/JavaExamPrep/commit/415ca91c53952b8904420b8ca77c6972360ed439)


### Day 44: February 15, 2017, Wednesday

** Today's Progress**: Practiced Java by solving puzzles on CodinGame.

**Thoughts**: I would really like to pass the OCA exam at the end of the 100DaysOfCode challenge.

**Link(s) to work**

1. [Link to CodinGame profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)


### Day 45: February 16, 2017, Thursday

** Today's Progress**: Did some more Java review for OCA, practed tricky access modifier, inheritance, overriding and overloading rules.

**Thoughts**: I would really like to pass the OCA exam at the end of the 100DaysOfCode challenge.

**Link(s) to work**

1. [Link to latest Commit](https://github.com/ConnieZ/JavaExamPrep/commit/13eb3f4d1db7240b2f9cc81a601e8a546426ca49)


### Day 46: February 17, 2017, Friday

** Today's Progress**: Continued Java review for OCA, practed tricky access modifier, inheritance, overriding and overloading rules.

**Thoughts**: I would really like to pass the OCA exam at the end of the 100DaysOfCode challenge.

**Link(s) to work**

1. [Link to latest Commit](https://github.com/ConnieZ/JavaExamPrep/commit/ab5cce55cee2b754c474d7d6f3c2f84ce8a38361)



### Day 47: February 18, 2017, Saturday

** Today's Progress**: Played my first clash of code on CodinGame, solved some puzzles.

**Thoughts**: They are not getting easier...

**Link(s) to work**

1. [Link to CodinGame profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)


### Day 48: February 19, 2017, Sunday

** Today's Progress**: Reviewing arrays and arrayLists for Java exam.

**Thoughts**: Apparently you can't instantiate a variable outside a method, unless it's combined with declaration...

**Link(s) to work**

1. [Link to latest commit](https://github.com/ConnieZ/JavaExamPrep/commit/5fe8de0d4384ba364e82fa326449594f46c195f2)

### Day 49: February 20, 2017, Monday

** Today's Progress**: Continued reviewing arrays and arrayLists for Java exam.

**Thoughts**: Correction, turns out you can remove int from ArrayList, by using Integer wrapper class. Hey, you learn sth new every day :)

**Link(s) to work**

1. [Link to latest commit](https://github.com/ConnieZ/JavaExamPrep/commit/d84fb3d9d51d9165a50832c629d337ba91ca2781)
2. [Link to a Jupyter Notebooks repo](https://github.com/ConnieZ/Data_Science_with_SparkR)


### Day 50: February 21, 2017, Tuesday

** Today's Progress**: Continued reviewing arrays and arrayLists for Java exam.

**Thoughts**: Wow, I'm half-way through the challenge!

**Link(s) to work**

1. [Link to latest commit](https://github.com/ConnieZ/JavaExamPrep/commit/b59379495264d4015168de766a37536416b009b0)


### Day 51: February 22, 2017, Wednesday

** Today's Progress**: Learning Date and Time API in Java 8.

**Thoughts**: Wow, I'm half-way through the challenge!

**Link(s) to work**

1. [Link to latest commit](https://github.com/ConnieZ/JavaExamPrep/commit/f349e6ccb5fe472fcc90b15035691f8de82f2e9f)



### Day 52: February 23, 2017, Thursday

** Today's Progress**: Continued learning Date and Time API in Java 8.

**Thoughts**: 

**Link(s) to work**

1. [Link to latest commit](https://github.com/ConnieZ/JavaExamPrep/commit/fe1ced0757d8beb5e8ab05cf8db49de7013e9c34)

### Day 53: February 24, 2017, Friday

** Today's Progress**: Finished reviewing Date and Time API in Java 8. Solved Caesar Cipher challenge on freecodecamp.

**Thoughts**: 

**Link(s) to work**

1. [Link to latest commit](https://github.com/ConnieZ/JavaExamPrep/commit/7941b5a5ce6744ca7284b4e4d9bba704bebe398e)
2. [Link to freecodecamp profile](https://www.freecodecamp.com/conniez)


### Day 54: February 25, 2017, Saturday

** Today's Progress**: Learned bot programming through a starship race on codingame.com

**Thoughts**: It's pretty fascinating to learn multiplayer game programming.

**Link(s) to work**

1. [Link to codingame profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)


### Day 55: February 26, 2017, Sunday

** Today's Progress**: Performed bot programming as part of Ghost in the Cell contest at codingame.com

**Thoughts**: Took me hours to get out of lowest Leage, now I'm Wood 2 League, and not the last one.

**Link(s) to work**

1. [Link to codingame profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)
2. [Link to contest](https://www.codingame.com/contests/ghost-in-the-cell)


### Day 56: February 27, 2017, Monday

** Today's Progress**: Significantly improved my code for bot programming as part of Ghost in the Cell contest at codingame.com

**Thoughts**: I'm finally in Wood 1 League, and closer to the top!

**Link(s) to work**

1. [Link to codingame profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)
2. [Link to contest](https://www.codingame.com/contests/ghost-in-the-cell)


### Day 57: February 28, 2017, Tuesday

** Today's Progress**: Improved my code for bot programming as part of Ghost in the Cell contest at codingame.com

**Thoughts**: I made it to the Bronze League, Woot Woot!

**Link(s) to work**

1. [Link to codingame profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)
2. [Link to contest](https://www.codingame.com/contests/ghost-in-the-cell)



### Day 58: March 1, 2017, Wednesday

** Today's Progress**: Improved my code for bot programming as part of Ghost in the Cell contest at codingame.com

**Thoughts**: Still in the Bronze League, but getting higher to the top!

**Link(s) to work**

1. [Link to codingame profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)
2. [Link to contest](https://www.codingame.com/contests/ghost-in-the-cell)


### Day 59: March 2, 2017, Thursday

** Today's Progress**: While working on the contest, I learned Comparator, comparing objects by attribute. Improved my code for bot programming as part of Ghost in the Cell contest at codingame.com

**Thoughts**: Still in the Bronze League, but getting higher to the top, highest today was 48 out of 1463!

**Link(s) to work**

1. [Commit to java practice repo](https://github.com/ConnieZ/JavaExamPrep/commit/37e98950fa64735463c89f6408e013ea04f49d28)
2. [Link to codingame profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)
3. [Link to contest](https://www.codingame.com/contests/ghost-in-the-cell)


### Day 60: March 3, 2017, Friday

** Today's Progress**: Learned how to extend, save, push and load Docker images. Improved my code for bot programming as part of Ghost in the Cell contest at codingame.com

**Thoughts**: Still in the Bronze League, but getting higher to the top, highest today was 48 out of 1463!

**Link(s) to work**

1. [Commit Docker stacks](https://github.com/ConnieZ/docker-stacks/commit/9291b20f298b622b3cb9719c6314417893c98d84)
2. [Link to codingame profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)
3. [Link to contest](https://www.codingame.com/contests/ghost-in-the-cell)


### Day 61: March 4, 2017, Saturday

** Today's Progress**: Submitted my last improvement to bot algorithm in Ghost in the Cell contest at codingame.com

**Thoughts**: Finally made it into Silver League, highest today was 555 out of ~650 ! Ranking 88 in the US.

**Link(s) to work**

1. [Replay of my algorithm](https://www.codingame.com/replay/193645882)
2. [Link to codingame profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)
3. [Link to contest](https://www.codingame.com/contests/ghost-in-the-cell)



### Day 62: March 5, 2017, Sunday

** Today's Progress**: Solved some more puzzles on codingame.com

**Thoughts**: ASCII can be fun!

**Link(s) to work**

1. [Link to codingame profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)


### Day 63: March 6, 2017, Monday

** Today's Progress**: Solved some more puzzles on codingame.com - helped Marvin and his clones in "Don't Panic" puzzle.

**Thoughts**: 

**Link(s) to work**

1. [Link to codingame profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)


### Day 64: March 7, 2017, Tuesday

** Today's Progress**: Solved some more puzzles on codingame.com - Encoded messages using Chuck Norris' method. Did some reviewing of methods theory in Java.

**Thoughts**: 

**Link(s) to work**

1. [Link to codingame profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)


### Day 65: March 8, 2017, Wednesday

** Today's Progress**: Submitted as solution to the Code Golf version of Don't Panic.

**Thoughts**: Couldn't do much, because I was feeling sick, so worked to my best ability.

**Link(s) to work**

1. [Link to codingame profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)


### Day 66: March 9, 2017, Thursday

** Today's Progress**: Improved my solution to the Code Golf version of Don't Panic. Started working on "There is no spoon" puzzle in codingame.com

**Thoughts**: Still couldn't do much, because I was feeling sick, so worked to my best ability.

**Link(s) to work**

1. [Link to codingame profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)


### Day 67: March 10, 2017, Friday

** Today's Progress**: Solved "There is no spoon" puzzle in codingame.com and submitted a Code Golf solution to Temperatures. 

**Thoughts**: Excited to be a Crafter! No longer a rookie.

**Link(s) to work**

1. [Link to codingame profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)


### Day 68: March 11, 2017, Saturday

** Today's Progress**: Back to Java theory - reviewing methods today, access modifiers, specifiers, etc. 

**Thoughts**: 

**Link(s) to work**

1. [Link to latest commmit](https://github.com/ConnieZ/JavaExamPrep/commit/a15cad4fd2ecd8375824142f4829e4ccac6bc764)



### Day 69: March 12, 2017, Sunday

** Today's Progress**: Continued Java theory review for the OCA exam - reviewing methods again, access modifiers, specifiers, etc. 

**Thoughts**: 

**Link(s) to work**

1. [Link to latest commmit](https://github.com/ConnieZ/JavaExamPrep/commit/b82e199c19a40b5c1122649647d1191f225c6f24)


### Day 70: March 13, 2017, Monday

** Today's Progress**: Continued Java theory review for the OCA exam - reviewing methods again, overloading, autoboxing, passing by value, etc. 

**Thoughts**: 

**Link(s) to work**

1. [Link to latest commmit](https://github.com/ConnieZ/JavaExamPrep/commit/7cc20bc2b9ab71776ed4dabc30b09242653a9cac)


### Day 71: March 14, 2017, Tuesday

** Today's Progress**: I added another algorithm to my Delay Predictor - Artificial Neural Networks with neuralnet package in R. Still figuring out how to run predictions with it.

**Thoughts**: 

**Link(s) to work**

1. [Link to latest commmit](https://github.com/ConnieZ/delay_predictor/commit/b0774ab83369326cf5d5a461e1fe577221d5ea8d)


### Day 72: March 15, 2017, Wednesday

** Today's Progress**: Worked on solving the Mayan Calculations puzzle on codingame.com.

**Thoughts**: 

**Link(s) to work**

1. [Link to profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)


### Day 73: March 16, 2017, Thursday

** Today's Progress**: Continued Java theory review for the OCA exam - reviewing methods again, overloading and constructors. 

**Thoughts**: 

**Link(s) to work**

1. [Link to latest commmit](https://github.com/ConnieZ/JavaExamPrep/commit/06e3b8f2e6a627c2b8f6779236d81702b5488ed5)


### Day 74: March 17, 2017, Friday

** Today's Progress**: Worked more on solving the Mayan Calculations puzzle on codingame.com. Reviewed base number conversions, passed 4 test cases now (improvement from 1).

**Thoughts**: Very interesting puzzle!

**Link(s) to work**

1. [Link to profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)



### Day 75: March 18, 2017, Saturday

** Today's Progress**: Scored 100% on the Mayan Calculations puzzle on codingame.com. Passed all the test cases, even those that people struggle with most (community completion score is only 82%).

**Thoughts**: Feels like a great accomplishment and got me to level 9!

**Link(s) to work**

1. [Link to profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)


### Day 76: March 19, 2017, Sunday

** Today's Progress**: Back to Java practice for OCA exam - took the review test and practiced the areas where I made mistakes.

**Thoughts**: Hate memorizing things. 

**Link(s) to work**

1. [Link to latest commit](https://github.com/ConnieZ/JavaExamPrep/commit/7051030a755244419af6f476f0478ac5001601fe)



### Day 77: March 20, 2017, Monday

** Today's Progress**: More Java practice for OCA exam - constructors and order of initialization.

**Thoughts**:  

**Link(s) to work**

1. [Link to latest commit](https://github.com/ConnieZ/JavaExamPrep/commit/ea14bb0e7700bb02ba68267240409db1f45d73f1)


### Day 78: March 21, 2017, Tuesday

** Today's Progress**: Learned about Manhattan distance, in other words, Taxicab geometry while solving cabling puzzle on codingame.com.

**Thoughts**: Wow, complex math is fun with a purpose, but still complex.

**Link(s) to work**

1. [Link to profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)



### Day 79: March 22, 2017, Wednesday

** Today's Progress**: Reviewed encapsulation, JavaBeans naming conventions and immutability tricks.

**Thoughts**: Passing by reference is super tricky.

**Link(s) to work**

1. [Link to latest commit](https://github.com/ConnieZ/JavaExamPrep/commit/977740423eea95f005a71def2e43650b9a17e9b5)


### Day 80: March 23, 2017, Thursday

** Today's Progress**: Worked more on the network cabling puzzle on codingame.com.

**Thoughts**: I got it to pass more test cases, still failing some.

**Link(s) to work**

1. [Link to profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281)


### Day 81: March 24, 2017, Friday

** Today's Progress**: Worked more on the network cabling puzzle on codingame.com, but this time I also learned using lambdas with streams by way of map reduce API. It was very neat to use them.

**Thoughts**: I got it to pass 7 out of 9 test cases, but after submitting the code my completion was only 58%. More work needs to be done.

**Link(s) to work**

1. [Link to profile](https://www.codingame.com/profile/dc9f2e8fb626b88377fb26426ccdf9be1639281) 
2. [Link to latest commit](https://github.com/ConnieZ/JavaExamPrep/commit/a2855a9fb89438999895e2d4f3fb3e9cd7246f63)


### Day 82: March 25, 2017, Saturday

** Today's Progress**: Backlogging for Saturday - worked on my KitchenMaster app, finalizing code and comments in preparation for deployment to phone.

**Thoughts**: 

**Link(s) to work**

1. [Link to latest commit](https://github.com/ConnieZ/KitchenMaster/commit/731255c132f4487a2dbaf10aed8a6d26a196527d)


### Day 83: March 26, 2017, Sunday

** Today's Progress**: Analyzing stock market losses with a puzzle on codingame.com.

**Thoughts**: 

**Link(s) to work**

1. [Link to puzzle](https://www.codingame.com/training/medium/stock-exchange-losses)


### Day 84: March 27, 2017, Monday

** Today's Progress**: Practiced writing lambdas some more.

**Thoughts**: Some things still seem tricky

**Link(s) to work**

1. [Link to latest commit](https://github.com/ConnieZ/JavaExamPrep/commit/9f82e707546926cc19529b198d0a2ef686e9484f)


### Day 85: March 28, 2017, Tuesday

** Today's Progress**: Practiced the weak areas from practice test in Java on methods and lambdas.

**Thoughts**: Some things still seem tricky

**Link(s) to work**

1. [Link to latest commit](https://github.com/ConnieZ/JavaExamPrep/commit/f96d95ab6642abbd0409b591cd507a77e56feff7)


### Day 86: March 29, 2017, Wednesday

** Today's Progress**: Continued review and practice of the weak areas from test in Java on methods and lambdas.

**Thoughts**: Some things still seem tricky

**Link(s) to work**

1. [Link to latest commit](https://github.com/ConnieZ/JavaExamPrep/commit/e6f6fb434dba4c94d5d0b007edd7314e400a81ef)


### Day 87: March 30, 2017, Thursday

** Today's Progress**: Reviewed and practiced class creation and inheritance rules in Java. 

**Thoughts**: Had to code in the airport and on the plane and didn't have the opportunity to commit online on the actual day.

**Link(s) to work**

1. [Link to latest commit](https://github.com/ConnieZ/JavaExamPrep/commit/c0443f85c05a2ec28fcbd5b3dfbe1051e8d3b3f6)


### Day 88: March 31, 2017, Friday

** Today's Progress**: Finally got 100% on the network cabling puzzle - only needed to fix the code calculating median from array of values.

**Thoughts**: Very excited

**Link(s) to work**

1. [Link puzzle](https://www.codingame.com/training/medium/network-cabling)


### Day 89: April 1, 2017, Saturday

** Today's Progress**: Solved the Stock Exchange puzzle and started exploring breadth first search (BFS) for another puzzle on codingame.

**Thoughts**: Very excited

**Link(s) to work**

1. [Link puzzle](https://www.codingame.com/training/medium/stock-exchange-losses)


### Day 90: April 2, 2017, Sunday

** Today's Progress**: Worked on another puzzle on codingame.

**Thoughts**: Very excited for the upcoming contest.

**Link(s) to work**

1. [Link puzzle](https://www.codingame.com/training/medium/skynet-revolution-episode-1)


### Day 91: April 3, 2017, Monday

** Today's Progress**: Learned the Graph data structure thanks to Coursera course, and that allowed me to finish the Skynet puzzle with a 100% score.

**Thoughts**: Done!

**Link(s) to work**

1. [Link puzzle](https://www.codingame.com/training/medium/skynet-revolution-episode-1)
2. [Link to course](https://www.coursera.org/learn/advanced-data-structures/home/info)

### Day 92: April 4, 2017, Tuesday

** Today's Progress**: In order to solve the second episode of Skynet puzzle I had to rack my brain, trying to write a pathfinding algorithm in Java.

**Thoughts**: What a challenge!

**Link(s) to work**

1. [Link puzzle](https://www.codingame.com/training/hard/skynet-revolution-episode-2)

### Day 93: April 5, 2017, Wednesday

** Today's Progress**: Still working on learning BFS, DFS, Dijkstra, and Java classes to solve this pathfinding puzzle on codingame.com.

**Thoughts**: What a challenge!

**Link(s) to work**
1. [Link puzzle](https://www.codingame.com/training/hard/skynet-revolution-episode-2)
2. [Link to course](https://www.coursera.org/learn/advanced-data-structures)


### Day 94: April 6, 2017, Thursday

** Today's Progress**: Another day of still working on learning BFS, DFS, Dijkstra, and Java classes to solve this pathfinding puzzle on codingame.com.

**Thoughts**: What a challenge!

**Link(s) to work**
1. [Link puzzle](https://www.codingame.com/training/hard/skynet-revolution-episode-2)
2. [Link to course](https://www.coursera.org/learn/advanced-data-structures)



### Day 95: April 7, 2017, Friday

** Today's Progress**: I solved the puzzle with 66% success in test cases, but the last 2 I still fail due to the tricky double exit gateways.

**Thoughts**: What a challenge!

**Link(s) to work**
1. [Link puzzle](https://www.codingame.com/training/hard/skynet-revolution-episode-2)


### Days 96-97: April 8-9, 2017, Saturday-Sunday

** Today's Progress**: I spent more time on heuristics for the pathfinding puzzle to make smart moves ahead of time. 

**Thoughts**: It' really hard to make the AI work the way a chess-player would.

**Link(s) to work**
1. [Link puzzle](https://www.codingame.com/training/hard/skynet-revolution-episode-2)


### Day 98: April 10, 2017, Monday

** Today's Progress**: I spent more time on heuristics for the pathfinding puzzle to make smart moves ahead of time, and now my best score is 83%. I was able to pass all IDE tests, but the last 3 validation tests would then fail.

**Thoughts**: It' really hard to make the AI work the way a chess-player would.

**Link(s) to work**
1. [Link puzzle](https://www.codingame.com/training/hard/skynet-revolution-episode-2)


### Day 99: April 11, 2017, Tuesday

** Today's Progress**: I made my code work in Eclipse for pathfinding algorithm, so now I can run a variety of test cases. Also, I did some live coding at a data science workshop in R with Jupyter Notebooks.

**Thoughts**: Getting closer to the truth...

**Link(s) to work**
1. [Link puzzle](https://www.codingame.com/training/hard/skynet-revolution-episode-2)


### Day 100: April 12, 2017, Wednesday

** Today's Progress**: I ran my algorithm in Eclipse and found out that my algo doesn't find the shortest path... Learning Dijkstra algorithm now to make it happen.

**Thoughts**: Getting closer to the truth...

**Link(s) to work**
1. [Link puzzle](https://www.codingame.com/training/hard/skynet-revolution-episode-2)
2. [Link to tutorial](https://www.coursera.org/learn/advanced-data-structures/lecture/2ctyF/core-dijkstras-algorithm)
