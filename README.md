# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

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
## Developed By:Lokesh N
## Reg No:212222100023
 ```
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label='line1')
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label='line2')
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/d0cc5228-1f6d-46fd-8534-5f6b0aa504fa)


```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')
plt.show()
```
![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/af07ce91-3aa1-48d0-b2ed-129fa71aa104)


```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```
![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/a0e967d6-7470-45e9-9729-e42143c739b3)


```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
```
![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/616c8bb5-df90-41f5-aefa-c52840ff646f)


```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.926,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896, ]

```
```
plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title('Crop Yields in Kanto')
plt.legend(['Apples','Oranges']);
```

![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/36de3aca-1c73-4abb-af48-50152e0fc919)

```
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yield of Oranges (tons per hectare)");
```
![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/a56e18dc-29db-49c6-bb55-7642fd1148b8)


```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/f87bf947-4a95-44f9-b3c9-af8e29fe7707)


```
y
```
![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/0744027d-36c2-4d09-8e76-71057747ef78)


```
plt.scatter(x,y,c='r')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/b86bd570-63dd-4f51-94fa-0c22ea09901c)


```
y=x*x
y
```
![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/3e21403a-da69-45d8-97ac-883d7b37344b)


```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```
![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/3584ab48-a4ab-4740-b5bf-8f4f85f360bb)


```
np.pi
```
![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/44e1b689-07ad-488d-9096-18a6e2167ade)



```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```

![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/092cee88-0e0f-4acd-b486-112400d2cdf8)

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')
```
![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/9c0676e1-9ce8-4146-ad19-ce3279c86b86)

```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')

plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
```
![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/ba2b0f9e-aee8-4ed8-8762-afcf7a5c20fd)

```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart!')
plt.show()
```
![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/78f799cd-5887-4170-9fb5-eb977e721f5b)

```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```
![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/90eb4b6f-df5a-4c7b-9d17-6e166ec806d1)


```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.title('My histogram')
plt.show()
```
![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/0711e35a-5a9f-45bb-bdf9-43f34f5890a8)

```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/d9a2b4ac-2632-4ea4-a694-a4f6de7031e2)

```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/d5696301-c18f-43d8-9d51-e25233a46c04)

```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```

![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/bbdb53b5-9821-4849-a19b-c53386c13519)

```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
```
![image](https://github.com/lokeshnarayanan/EXNO-5-DS/assets/119393019/d13784fe-b205-4428-9110-f0ea16b1086d)




# Result:
 Thus, The implementation of data visualisation using matplotlib has been successfully verified!
