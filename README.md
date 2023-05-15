# UE5-Game-Project


Woking on the locomotion system. For start created a Legacy(Blend Space 1D) and named the variable "speed" and it is set 500 (which is the maximum walking speded).

Animations added: MM_walk_inPLace, MM_Walk_Fwd, MM_Run_Fwd (in the following order).

Created a AnimationBP, and placed a state machine in it(called Locomotion). This machine will handle the different states of the character. 

Created the Locomotion state machine that will handle the transition from Ilde - Walk/Run - Stop - Idle. Stored it an a Chached slot.

Created a Main State Machine that will handle all the other State Machines. 

Changed the animation for the Character Mesh. 

Added the Jumping and Landing animation, and started using 'Automatic Rule Based on Sequence' option which will do the animation transfers based on priority. (Still very new will have to look into it more)