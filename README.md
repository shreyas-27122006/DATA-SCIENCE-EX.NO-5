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
~~~
import matplotlib.pyplot as plt
import numpy as np 
x=np.arange(10,20)
y=np.arange(21,31)
a=np.arange(45,55)
b=np.arange(55,65)
plt.scatter(x,y,c='g')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')

y=x*x
plt.plot(x,y,'r*',linestyle='solid',linewidth=3, markersize=10)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
plt.show()

plt.subplot(3,3,1)
plt.plot(x,y,'r--')
plt.subplot(3,3,2)
plt.plot(x,y,'g*--')
plt.subplot(3,3,3)
plt.plot(x,y,'bo')
plt.subplot(3,3,4)
plt.plot(a,b,'go')
plt.show()

x = np.arange(0,10) 
y = 3 * x + 5 
plt.title("Matplotlib demo") 
plt.xlabel("x axis caption") 
plt.ylabel("y axis caption") 
plt.plot(x,y) 
plt.show()

np.pi
x = np.arange(0, 4 * np.pi, 0.1) 
y = np.sin(x) 
plt.title("cosine wave form") 

# Plot the points using matplotlib 
plt.plot(x, y) 
plt.show()

x = np.arange(0, 5 * np.pi, 0.1) 
y_sin = np.sin(x) 
y_cos = np.cos(x)  
   
# Set up a subplot grid that has height 2 and width 1, 
# and set the first such subplot as active. 
plt.subplot(2, 1, 1)
   
# Make the first plot 
plt.plot(x, y_sin,'r--') 
plt.title('Sine')  
   
# Set the second subplot as active, and make the second plot. 
plt.subplot(2, 1, 2) 
plt.plot(x, y_cos,'g--') 
plt.title('Cosine')  
   
# Show the figure. 
plt.show()

x = [2,4,6] 
y = [4,8,10]  

x2 = [1,3,5] 
y2 = [2,6,8] 
plt.bar(x, y) 
plt.bar(x2, y2, color = 'g') 
plt.title('Bar graph') 
plt.ylabel('Y axis') 
plt.xlabel('X axis')  

plt.show()

a = np.array([22,87,5,43,56,73,55,54,11,20,51,5,79,31,27]) 
plt.hist(a) 
plt.title("histogram") 
plt.show()

data = [np.random.normal(0, std, 100) for std in range(1, 4)]

# rectangular box plot
plt.boxplot(data,vert=True,patch_artist=False);  
plt.show()

data = [np.random.normal(0, std, 100) for std in range(1, 6)]

# rectangular box plot
plt.boxplot(data,vert=True,patch_artist=True);
plt.show()

data

labels = 'Python', 'C++', 'Ruby', 'Java'
sizes = [200, 130, 245, 210]
colors = ['red', 'cyan', 'yellow', 'lightskyblue']
explode = (0.4, 0, 0, 0)  # explode 1st slice

# Plot
plt.pie(sizes, explode=explode, labels=labels, colors=colors,
autopct='%1.1f%%', shadow=False)

plt.axis('equal')
plt.show()
~~~
<img width="871" height="694" alt="image" src="https://github.com/user-attachments/assets/c2393c11-13a0-42c1-ae9b-5015b78106bd" />
<img width="879" height="700" alt="image" src="https://github.com/user-attachments/assets/7a1f1ce6-9541-467f-98a6-98f1b8f33681" />
<img width="857" height="434" alt="image" src="https://github.com/user-attachments/assets/ef2695f3-ce3b-4915-aafa-407fb9f77b7c" />
<img width="877" height="697" alt="image" src="https://github.com/user-attachments/assets/b225ce97-838c-41ee-86cd-6773cccd47a8" />
<img width="873" height="644" alt="image" src="https://github.com/user-attachments/assets/02907774-b0f8-4f98-b7ac-a8584277b93c" />
<img width="861" height="669" alt="image" src="https://github.com/user-attachments/assets/464e2f75-6a58-4325-b92d-fd0202c18fcb" />
<img width="870" height="695" alt="image" src="https://github.com/user-attachments/assets/619a9f2d-81c8-4410-ab83-a4a9e802228b" />
<img width="845" height="668" alt="image" src="https://github.com/user-attachments/assets/0f09d0d9-da70-49a9-8547-a55283e908ec" />
<img width="834" height="635" alt="image" src="https://github.com/user-attachments/assets/b6276474-6fac-4959-bc5a-b59f2f6012dc" />
<img width="860" height="633" alt="image" src="https://github.com/user-attachments/assets/54c961c3-14a0-424b-b0bf-5de05d60de64" />
<img width="901" height="754" alt="image" src="https://github.com/user-attachments/assets/cb112a57-c956-4851-8e29-947da1e8a324" />
<img width="824" height="156" alt="image" src="https://github.com/user-attachments/assets/3bef8ebe-e6c6-48a9-9a88-527187d5d3bd" />
<img width="792" height="591" alt="image" src="https://github.com/user-attachments/assets/e1de51b4-6c52-4aa3-93bd-915bb0084218" />


# Result:
Thus, the program is executed successfully.
