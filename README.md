# Syntax-Tree-Generator <img height="52" width="52" src = "https://cdn-icons-png.flaticon.com/512/6537/6537185.png">


```A syntax tree is a tree in which each leaf node represents an operand, while each inside node represents an operator. The Parse Tree is abbreviated as the syntax tree. The syntax tree is usually used when representing a program in a tree structure.```.

<hr>
<br>
<br>

## How to run it <img height="52" width="52" src = "https://user-images.githubusercontent.com/92999481/166147080-e3baac9b-3d24-439d-aa7b-4eec7a59edc2.png">

**```[1]```**
The program will be downloaded first by clicking on the green "Code" button and selecting "Downlad as ZIP" or you can copy the source code directly from the ** main.py ** file to an IDE (such as ** PyCharm **) or text editor (such as ** Visual Studio Code **; in this case, you will need to install extensions that allow Python code to run). This program takes an expression as an argument and returns its abstract syntax using binary trees.

**```[2]```** 
Input requirements:
In sentence analysis, there should be no spaces between elements. Also, conventions for logical connectors will have to be used because C ++ encoding does not recognize Unicode symbols.

  ##### Conventions due to C ++ character encoding
     ! it's a denial
     / e disjunction
     ~ It's an implication
     = is equivalent
     &, ^, * are conjunctions
     
*Avoiding conventions leads to errors*


#### [ EXAMPLES ]

      (((P⇔Q)∨S)⇒T) becomes (((P=Q)/S)~T)
      ((P⇔Q)∧((¬Q)∧(¬P))) becomes ((P=Q)&((!Q)&(!P)))
      ((P⇔Q)∨((¬Q)∨P)) becomes ((P=Q)/((!Q)/P))


![5](https://user-images.githubusercontent.com/92999481/146649965-96d34a61-4a97-4e06-89f9-7c43cd5cbc71.png)

![6](https://user-images.githubusercontent.com/92999481/146649968-8b29b9a2-96e6-49ed-9002-f4fca7978126.png)

   ![Screenshot 2021-12-18 184416](https://user-images.githubusercontent.com/92999481/146649043-75d01c9c-7004-4bc8-936b-fb05f8552b36.png)
   ![2](https://user-images.githubusercontent.com/92999481/146649142-ac6d1c03-a1ee-4cc8-992d-01a389660d69.png)
   ![3](https://user-images.githubusercontent.com/92999481/146649159-3724df66-dad4-414c-b079-fdc6cbdc0252.png)
