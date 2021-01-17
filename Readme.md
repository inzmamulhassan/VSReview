My Core Qaulity Beliefs:

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than right now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.

My Laravel Development Principles:


Refector code into smaller chunks rather that a few monolithic files, 
ie 4000 lines controller is bad practic, 
Horse for Corses (Seperation of concerns)
Ideally Controller should be close to http controller with business logic coming from services
Reuseable global functions should be in helpers.php,
DB quries should be in Repositories and Modals
I am big fan of php trats which is similar to dependency injection in Java Spring or JS in general
Make business logic trats ie. File.php deals with business logic with files management,
As for as code formating is concerned, I usually follow PSR-2, 
I have no hard and fast rules on formating, my whole point is that whole team should one standard whatever it is,


Code Review:
1 - Overall Code decent to me, it's nice and clean good use of repository which I am big fan of.
2 - Due to use of repository the contorller is nice and managable there is no long scrolls and irrelevant functions
3 - There are 3 things we can obviously improve upon,
    (1) - Role Management is could have be been handled differently, 
    depending upon the requirments a suitable role management tools could have used
    (2) - Best practice is to get the data from database, which we can use in code base rather that from files.
    Config and ENV file is kick the project not a data storage.
4 - As I don't have in depth of the App architecture so I will make some assumptions and try to write code acccording to those assumptions. My code might not for current architecture, my approach might not be best suited for current architecture but my assumption is that is not the point of this excercise anyway. So let's begin coding.
    