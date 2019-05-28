# Basic_Q_Learning
Implementation of basic Q learning。  
![image](https://github.com/TangLaoDA/Basic_Q_Learning/blob/master/image/1.png)  
As you can see from the picture above，the goal of the agent is to walk from room 2 to room 5.  
We can convert the room structure into a map，it is shown below  
![image](https://github.com/TangLaoDA/Basic_Q_Learning/blob/master/image/2.png)  
We can add rewards to the path，it is shown below  
![image](https://github.com/TangLaoDA/Basic_Q_Learning/blob/master/image/3.png)  
We can construct an environmental reward matrix when programming，it is shown below  
![image](https://github.com/TangLaoDA/Basic_Q_Learning/blob/master/image/4.png)  
We also need to construct a Q matrix，its initial state is as follows  
![image](https://github.com/TangLaoDA/Basic_Q_Learning/blob/master/image/5.png)  
After many cycles of training，it converges to the following state  
![image](https://github.com/TangLaoDA/Basic_Q_Learning/blob/master/image/6.png)  
When you reach this state, you can go to room 5 according to a route that Q matrix looks for，just fllow the max Q value.    
I implemented two versions，if you want to exchange ideas with me，you can add me to WeChat:zggcdbd.  
