<h2>Android Activity Lifecycle</h2>

Android Deviced depend mainly on activity. 
One view could be imaged as one activity.


Explaination:
- When we first start up the app Activity A loads and other remain closed as there is no need of them to be initiated to save the memory <br><br>
<div align=center>![Activity1 C1](http://i.imgur.com/z9045NT.png)</div> <br><br>
we can see that the activity 1 oads without other activity even touch.
There is a counter on whenever the activity is loaded the counter increases. 
The total count is one when intitialized and keeps on increasing whenever the activity loads up.
- When Activity 2 is loaded, activity 1 is stopped and the counter of the app is started with 1<br><br>
<div align=center>![Activity2 C1](http://i.imgur.com/10Hnpn6.png)
</div><br><br>
- With some more dialogue or activity switching we can raise the counter of the app by 1. Here is an example of activity 1 goes to 3 count when its been initialized 3 times.
<br><br><div align=center>![](http://i.imgur.com/KRLK2f8.png)</div> <br><br>
- Same goes to other activyt as well.  Here are the following screenshots 
<br><br><div align=center>![](http://i.imgur.com/TizKpSQ.png)</div> <br><br>
<div align=center>![](http://i.imgur.com/s24TAID.png)</div> <br><br>
- A dialogue box will also have the same property![](http://i.imgur.com/HLoHPX5.png)


