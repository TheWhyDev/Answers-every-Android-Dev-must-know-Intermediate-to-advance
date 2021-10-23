# Intermediate-Android-Questions
Will be adding intermediate to advance level android/Kotlin/Java/OOPS questions with answers.

Questions/Answers


**Q : what is a context or Why does Android require context ? (e.g. why even a toast requires a context?)**

**A** : 
Based on Official documentations: 

    "Context is an interface to global information about an application environment. This is an abstract class whose implementation is provided by the Android system. It allows access to application-specific resources and classes, as well as up-calls for application-level operations such as launching activities, broadcasting and receiving intents, etc."

In toast, if you pass the resource directly, the toast class uses the context to get that resource.

Make sure you use the right context at right place other wise it may lead to memory leaks

For e.g. if you want to pass context to singleton class, pass application context to it rather than an activities.

for more info on which one to use where- checkout https://blog.mindorks.com/understanding-context-in-android-application-330913e32514

Also would highly recommend that you go through the official documentation as well. 

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : Can we define function inside a function in kotlin, if yes, how to call the inner function?**

**A :** 

 Yes, Kotlin supports nested functions but the scope of those nested functions is confined to the parent functions
   
 "Kotlin allows you to nest functions, one within another. We can declare and use a function within another function.
  When you declare a function within another function, the nested functions, visibility will stay exclusively within the 
  parent function and cannot be accessed from outside."
    
    fun main(args: Array<String>) { 
    fun nested():String { 
        return "String from nested function" 
    } 
    println("Nested Output: ${nested()}") 
    } 
    
  Resource : https://www.oreilly.com/library/view/functional-kotlin/9781788476485/6725edd3-33dc-41d3-8b0d-fcab12de7898.xhtml

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : How is the main thread in android always alive? why doesn't it die after completing execution?**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : In how many ways can you perform IPC in android?**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : What is reflection?**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : How and why should we use Android keystore?**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : Why network calls consume battery?**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : Why data class can not be abstract, open, sealed, or inner?**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : why we can not add a var/val property in a secondary constructor**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : how using the "throws"(exception) keyword makes the code robust**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : How to convert list to Map**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : what is "race condition" in multi threading**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : what is a "backing field" in Kotlin**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : what is Concurrency Design pattern**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : what is Blocking Queue**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : Flow vs callBackflow vs channels**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : Loosely coupled vs tightly coupled code android**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : What is young generation memory**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : Threads,Handler,looper,handler thread and it's interaction with UI**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : ART vs DVM**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : How to make multiple api calls and then wait for result from all of them and then update the ui?**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : How to stop/discard/cancel api calls?**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : Difference between internal storage and external storage**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : What is iterator and what is iterator design pattern?**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : What is Proxy design pattern?**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**Q : What is iterator and what is iterator design pattern?**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : What are class loaders?**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : What are weak references?**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : What is process death?**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : What is DSL (Domain specific language?**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : What is a value class in kotlin?**

**A : ANSWER HERE (will add soon)**

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Q : Changes introduced over various api levels android?**

**A** : https://developer.android.com/studio/releases/platforms

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------





















