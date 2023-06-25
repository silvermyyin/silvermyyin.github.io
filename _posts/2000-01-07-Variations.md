---
title: <font size=10 face="courier New" color=darkblue>V. Variations</font>
---
We want to assume that one of the islanders is **color-blind**. Suppose the total people is four. **L** represents blue and **R** represents brown. Then there are three situations:
 <font size=6 color=black>1. The color-blinded person has <font size=6 color=brown>brown</font> eyes:</font>

If the color-blinded person has blue eyes, he will be not able to see the eye colors of anyone else. It does not bother the deduction of two blue-eyed people. So just like the normal situation, all the **m** blue-eyed people will suicide at **Day m**.

<font size=6 color=black>2. The color-blinded person has <font size=6 color=blue>blue</font> eyes and more than one blue-eyed islanders:</font>

Suppose there are three blue-eyed people. The normal blue-eyed person will see two blue-eyed and one brown-eyed people. His deduction will be like: "If those two is the only two with blue eyes, then I have brown eyes. That case, they will suicide on Day 2. If not, then that means I also have blue eyes, and we have to suicide on **Day 3**." On the Day 1 and Day 2 no one suicides.It is because the blue-eyed person is waiting for the other one to suicide. On the Day 3, he sees that the other blue-eyed person is still on the island, so he realizes that he has blue eyes too. Therefore, the two normal blue-eyed person suicides on **Day 3**.

The brown-eyed islander will see three blue-eyed islanders. His deduction will be like: "If those three people are the only ones with blue eyes, then I have brown eyes. That case, they will suicide on Day 3. If not, more than three people have blue eyes and I am one of them" On the Day 1 and Day 2, no one suicides. On the Day 3, he see only two of the three blue-eyed people has left, while the other one is still on the island. Now he will feel quite confused, as it contradicts his assumption. As for the color-blinded person, when he knows two people suicide on the **Day 3**, he would think there are three people who has blue eyes and he realize he is the third one and suicides on the **Day 4**.

The Kriple model of this typical variation is shown in **Fig. 5-9** from prior to the announcement to **Day 3**. We use Mesa to illustrate the variation of number of states in Kripke model (**Fig. 10**) and number of alive islanders day by day (**Fig.11**).

Therefore in general, if there are more than one blue-eyed people (suppose the total number is **m**), all the normal blue-eyed people (**m-1**) will suicide at **Day m**, the color-blinded one will suicide the next day. 

<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);width: 40%;
    height: 40%;" 
    src="img/v-initial.jpg">   <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);width: 40%;
    height: 40%;" 
    src="img/v-day_0.jpg">   <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);width: 50%;
    height: 50%;" 
    src="img/v-day_1.jpg">   <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);width: 30%;
    height: 30%;" 
    src="img/v-day_2.jpg">   <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);width: 40%;
    height: 40%;" 
    src="img/v-day_3.jpg">
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;"><strong>Fig.5-9 : ( top to down, left to right ) Kripke model with three blue-eyed people and one of them is color-blinded</strong></div>
</center>

<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);width: 45%;
    height: 45%;" 
    src="img/blind_1x3_states.png">   <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);width: 45%;
    height: 45%;" 
    src="img/blind_1x3_agents.png"> 
     <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;"><strong>Fig.10-11 (left to right)</strong></div>
</center>

<font size=6 color=black>3. The color-blinded person is the only islander who has <font size=6 color=blue>blue</font> eyes:</font>

We still set the total number of islanders to 4. In this situation, all the three brown islanders will see one blue-eyed person and two brown-eyed. Each brown-eyed islander will think " if the blue-eyed person does not suicide on **Day 1** then I should be in blue-eyed. " However, since the blue-eyed person cannot deduct his own eye color based on the behavior of others, he will not suicide on Day 1. On the **Day 2**, the brown-eyed people see the only blue-eyed person has not suicided, they will mistakenly think they have blue eyes and then suicide. The color-blinded blue-eyed person knows them suicide and realize he is blue-eyed. Therefore he will suicide on **Day 3**. 

The Kriple model of this typical variation is shown in **Fig. 12-15** from prior to the announcement to **Day 2**. We use Mesa to illustrate the variation of number of states in Kripke model (**Fig. 16**) and number of alive islanders day by day (**Fig.17**).

Therefore in general, if there is only one blue-eyed people who is exactly the color-blinded one, then all the brown-eyed people will suicide at **Day 2**, the color-blinded one will suicide the next day.

<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);width: 40%;
    height: 40%;" 
    src="img/vv-initial.jpg">   <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);width: 40%;
    height: 40%;" 
    src="img/vv-day_0.jpg">   <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);width: 50%;
    height: 50%;" 
    src="img/vv-day_1.jpg">   <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);width: 30%;
    height: 30%;" 
    src="img/vv-day_2.jpg">   
    <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;"><strong>Fig.12-15 : ( top to down, left to right ) Kripke model with one blue-eyed people who is color-blinded</strong></div>
</center>
<font size=4></font>

<center>
    <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);width: 45%;
    height: 45%;" 
    src="img/blind_3x1_states.png">   <img style="border-radius: 0.3125em;
    box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);width: 45%;
    height: 45%;" 
    src="img/blind_3x1_agents.png"> 
     <br>
    <div style="color:orange; border-bottom: 1px solid #d9d9d9;
    display: inline-block;
    color: #999;
    padding: 2px;"><strong>Fig.16-17 (left to right)</strong></div>
</center>




