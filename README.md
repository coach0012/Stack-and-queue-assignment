# STACK QUESTION
#  UR pushes ["Assignment1", "Assignment2", "Assignment3"].Undo one. Which is top?
UR= []
UR.append('assignment 1')
UR.append('assignment 2')
UR.append('assignment 3')
UR.pop()
print(UR)
print('1.The top will be ' + UR[-1])
# In Irembo, push ["Step1", "Step2", "Step3"]. Undo 2.Which is left?
irembo=[]
irembo.append('step1')
irembo.append('step2')
irembo.append('step3')
irembo.pop()
irembo.pop()
print('2.The left will be ' ,irembo)
#  Push ["1", "2", "3", "4"], pop twice. Which is top?
Push=[]
Push.append('1')
Push.append('2')
Push.append('3')
Push.append('4')
Push.pop()
Push.pop()
print(Push)
print('3.The bottom will be ' + Push[-1])
# QUEUE QUESTION
from collections import deque
# At RRA, 5 clients queue. After 1 served, who is next?
RRA= deque(['1','2','3','4','5'])
RRA.popleft()
print(RRA)
next=RRA[0]
print('1.the next will be ' + next[-1])
# At Airtel, 6 customers queue. Who is last?
airtel= deque(['1','2','3','4','5','6'])
print('2.The last is  '+ airtel[-1])
