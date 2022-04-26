//C PROGRAMING FUNCTION FOR FINDING AREA OF RECTANGLE



#include<stdio.h>
//function declaration
float findarea(float 1,float b);
int main()
{
  float length,width,result;
  printf("enter the length and width of the rectangle");
  scanf("%f %f",&length,&width);
  
  result=findarea(length,width);//function calling
  printf("Area of rectangle=%.2f\n",result);
  return 0;
  }
  //function to find area of rectangle
  //function definition
  float findarea (float 1,float b)
  {
    float area;
    area =1*b;
    return area ;//return stastement
    }

  {
    float area;
    area =1*b;
    return area ;//return stastement
    }

    area =1*b;
    return area ;//return stastement
    }



//DESCRIPTION OF FOUR PILLARS OF JAVA ACCORDING TO ABOVE C PROGRAM

Inhertance;
In inheritance, you can create a new class that is inherited by another class. So the new class we can refer to as a child class or subclass and the class which already exists refer to a parent or superclass. One object acquires all the behaviors and properties of a parent object, and when you inherit a child class from a parent class you can reuse fields and methods of that class.From the function this pillar is expressed as follows;

float findarea(float 1,float b);//act as parent

int main()
{

return 0;
}

 float findarea (float 1,float b)//act as child
  {
    float area;
    area =1*b;
    return area ;//return stastement
 }


A real-world example of inheritance is all the properties of the father inherited by his son.
Advantages: Code reusability; Application performance is enhanced.


Polymorphism;
Simply we can define this concept as this, “having many forms”. We can simply explain this concept using a person because a person can be many things at the same time. He can be a father, an employer, a husband, etc.This pillar expressed as follows


float findarea(float 1,float b);
int main()
{
  float length,width,result;
  printf("enter the length and width of the rectangle");
  scanf("%f %f",&length,&width);
  
  result=findarea(length,width);//function calling
  printf("Area of rectangle=%.2f\n",result);
  return 0;
  }
  

3.Encapsulation
Encapsulation is also known as “data hiding”. This will wrap the code and data into a single unit and be better for unit testing.From the function of c programing the pillar expressed as follow

float findarea(float 1,float b);
int main()
{
  float length,width,result;
  printf("enter the length and width of the rectangle");
  scanf("%f %f",&length,&width);
  
  result=findarea(length,width);//function calling
  printf("Area of rectangle=%.2f\n",result);
  return 0;
  }
  
//function to find area of rectangle
  //function definition
  float findarea (float 1,float b)
  {
    float area;
    area =1*b;
    return area ;//return stastement
    }

  {
    float area;
    area =1*b;
    return area ;//return stastement
    }

    area =1*b;
    return area ;//return stastement
    }

Advantages: Security; Code reusability



4.Abstraction
Abstraction is used to hide the implementation and it will show only the functionality to the user.According to our function ,the following sytanx will appear to user;

 printf("enter the length and width of the rectangle");
 scanf("%f %f",&length,&width);
  
  result=findarea(length,width);//function calling
  printf("Area of rectangle=%.2f\n",result);


Advantages: Code reusability; Enhancement is easy; Maintainability; Security


