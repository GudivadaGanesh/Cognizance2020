# Cognizance2020
<!-- headings -->
# Condition Of A Triangle 

## Java script

// Java program to check  
// validity of any triangle 
  
public class GFG { 
  
  
    // Function to calculate for validity 
    public static int checkValidity(int a, 
                                int b, int c) 
    { 
        // check condition 
        if (a + b <= c || a + c <= b || b + c <= a) 
            return 0; 
        else
            return 1; 
    } 
  
    // Driver function 
    public static void main(String args[]) 
    { 
  
        int a = 7, b = 10, c = 5; 
      
        // function calling and print output 
        if ((checkValidity(a, b, c)) == 1) 
            System.out.print("Valid"); 
        else
            System.out.print("Invalid"); 
          
    } 
} 

## EXAMPLE
![https://onecompiler.com/java/3wf4tzprp]

(https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.mathwarehouse.com%2Fgeometry%2Ftriangles%2Ftriangle-inequality-theorem-rule-explained.php&psig=AOvVaw20E055lWstmoz2BgeG3Omp&ust=1607436599010000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCKDElpSGvO0CFQAAAAAdAAAAABAK)

## SOME POINTS ABOUT JAVA
---

* You can add properties to almost everything
* loops iterate over property names, not values
* Variables that aren’t explicitly declared can be global
* Understand how .prototype works
* JavaScript never sleep()s

## Advantages of JavaScript
* Speed. Client-side JavaScript is very fast because it can be run immediately within the client-side browser. 
* Simplicity. JavaScript is relatively simple to learn and implement.
* Popularity. JavaScript is used everywhere on the web.

* Interoperability. JavaScript plays nicely with other languages and can be used in a huge variety of applications.

* Server Load. Being client-side reduces the demand on the website server.

* Gives the ability to create rich interfaces.

## Disadvantages of JavaScript

* Client-Side Security. Because the code executes on the users’ computer, in some cases it can be exploited for malicious purposes. This is one reason some people choose to disable Javascript.

* Browser Support. JavaScript is sometimes interpreted differently by different browsers. This makes it somewhat difficult to write cross-browser code.

