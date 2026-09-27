# ***Florida Man On The Run***

<p align="center">
  <a href="https://yrgo.itch.io/florida-man-on-the-run">Website</a>
</p>

<img src="images/h5gYZb.png"/>


## Overview
Worked as **System/Gameplay programmer**  
In development between: *November -25 -> January -26*

Florida Man On The Run is a skate game reimagined with a comical spin on the "Florida man" meme. The protagonist travels down a Florida inspired level in a shopping cart while trying to achieve the highest score possible doing skate tricks. 
The scenery is created to put the player in fun, comical situations with absurd tricks and chaos like elements.

---

<table>
  <tr>
    <td ><img src="images/2fWUgo.jpg"/></td>
    <td ><img src="images/aDJkOS.jpg"/></td>
  </tr>
</table>

---

## My Contributions
---


**System programmer**
---
During development we needed a way to place rails to do basic skateboard tricks on. It was a tedious process to manually set up each rail sprite and connect them on a parent object with a singular collider.

I developed an editor script allowing our level designer to use Unity's splines to quickly draw the shape of the entire rail section he wanted to implement, and by the press of a button, generate a parent object, place the sprites accordingly and perfectly align a collider to the entire section.

I also set up a quest system. Utilizing Unity's scriptable object to quickly make different type of quests suited for each level. This system also presents the quests to the player at the beginning of each level, as well as notifying the player how he did when the level concluded.

--- 


**Gameplay programmer**
---
Florida man uses a state machine to handle physics changes when wall riding and to keep track of the players tricks and inputs. I set this state machine up and implemented some of it's states. Among others I've written the code for grinding on rails. 

We needed a way to attach and detach from the rails' collider that felt smooth and intuitive. After a lot of small changes and tweaks I managed a result I was happy with.

---

**Other**
---
I also had a hand in developing levels. Using the aforementioned tool for creating rails I could introduce different route's to finish levels as well as loops. Resulting in increased replayability and more game depth for the players.

---

