# Sequence_detector
This is a sequence detector done using verilog where each bit is given one after other and also this is done using the concept of finite state machines where different states are used for state transition 
Here I used  states s0,s1 ,s2,s3,s4 
And the test input sequence is 1011
for the first time the state s0 checks whether the input is 1 if yes then moves to next state s1 , in this state it checks whether the next state is 0 then it moves to s2 or else it stays in s1
then it checks whether the next state is 1 if true then moves to next state or resets to s0 
later checks the next is 0 ,if true then moves to next state else moves to s2
and the logic continues
![Screenshot 2025-05-26 111431](https://github.com/user-attachments/assets/69bde36c-a33c-4645-b029-209047d09cd2)
