# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY
# Name:Iswarya P
# Reg no:212223230082
# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:

```import matplotlib.pyplot as plt
x_val = [0,1,2,3,4,5]
y_val = [0,1,4,9,16,25]
plt.plot(x_val,y_val)
plt.show()
```
![image](https://github.com/Iswarya0580/EXNO-5-DS/assets/149989171/f70f3175-bc7c-48d7-b416-2b8001fca6da)
```
import matplotlib.pyplot as plt
x = [1,2,3]
y = [2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph')
plt.show()
```
![image](https://github.com/Iswarya0580/EXNO-5-DS/assets/149989171/65f69c71-5528-4958-aba6-bd3c1e856dc8)
```
import matplotlib.pyplot as plt
x1 = [1,2,3]
y1 = [2,5,3]
plt.plot(x1,y1,label = 'line 1')
x2 = [1,2,3]
y2 = [3,1,6]
plt.plot(x2,y2,label = 'line 2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title("Two lines on the same graph")
plt.legend()
plt.show()
```
![image](https://github.com/Iswarya0580/EXNO-5-DS/assets/149989171/c7fc7e7e-06eb-4e88-811a-8268b0211992)
```
import matplotlib.pyplot as plt
import numpy as np
x = [1,2,3,4,5]
y1 = [10,12,14,16,18]
y2 = [5,7,9,11,13]
y3 = [2,4,6,8,10]
plt.fill_between(x,y1,color = 'blue')
plt.fill_between(x,y2,color = 'orange')
```
![image](https://github.com/Iswarya0580/EXNO-5-DS/assets/149989171/357424dc-a59e-4d87-986d-9290400438e8)
```
plt.stackplot(x,y1,y2,y3,labels = ['line1','line2','line3'])
plt.legend(loc = 'upper left')
plt.title('Stacked line charts')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.show()
```
![image](https://github.com/Iswarya0580/EXNO-5-DS/assets/149989171/c9678a3c-fad5-44d3-98b4-e5d1b6838ae7)
```
import numpy as np
import matplotlib.pyplot as plt
val = [2,4,7,3]
names = ['A','B','C','D']
plt.bar(names, val,color = 'purple')
plt.show()
```
![image](https://github.com/Iswarya0580/EXNO-5-DS/assets/149989171/3b860fcc-657a-42e9-ae97-105a96478425)
```
import matplotlib.pyplot as plt
import numpy as np
ages = [2,6,4,12,13,12,16,18,18,19,26,24,39,34,45,42,54,56,90,56,86,79]
range = (0,100)
bins = 10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('no of people')
plt.title('histogram')
plt.show()
```
![image](https://github.com/Iswarya0580/EXNO-5-DS/assets/149989171/30748792-949f-4002-a86c-0b9e958e42ab)
```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
![image](https://github.com/Iswarya0580/EXNO-5-DS/assets/149989171/835d8bf8-09df-4c14-8ab5-a9e87a9f6914)
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel("data")
ax.set_ylabel("values")
ax.set_title("box plot")
```
![image](https://github.com/Iswarya0580/EXNO-5-DS/assets/149989171/0c09356d-3190-4e6f-850d-ef9af80244f4)
```
import matplotlib.pyplot as plt
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels = slices,colors=colors,startangle=90,shadow = True,explode = (0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
![image](https://github.com/Iswarya0580/EXNO-5-DS/assets/149989171/9e41a24d-3064-4a69-b8c6-c6c471136cd1)

# Result:
Thus, We have successfullu performed Data Visualization using matplot python library for the given datas.
