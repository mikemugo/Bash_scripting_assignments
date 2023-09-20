> # **ASSIGNMENT**

 > ## **Lets create another loop that and implement the break statement**
>
` #Start of for loop

for a in 1 2 3 4 5 6 7 8 9 10

do

        # if a is equal to 5 break the loop
        
        if [ $a == 5 ]
        
        then
        
                break
                
        fi
        
        # Print the value
        
        echo "Iteration no $a"
        
done`


 > ## **Can you try this same loop but implement the continue statement**
>
       `for a in 1 2 3 4 5 6 7 8 9 10
 
       do

        # if a is equal to 5 break the loop
        
        if [ $a == 5 ]
        
        then
        
                continue
                
        fi
        
        # Print the value
        
        echo "Iteration no $a"

        done `      
> # ** Write a for loop that echoes numbers 0 to 9**
>
> `for a in {0..9}; do echo "Iteration no $a"
> done`
>
>  #**Answer**
>
Iteration no 0

Iteration no 1

Iteration no 2

Iteration no 3

Iteration no 4

Iteration no 5

Iteration no 6

Iteration no 7

Iteration no 8

Iteration no 9

> # **Grep Assignemnt**
>  Cd to the directory /exercise-data/writing
> 
>Create a for loop that you will use on the LittleWomen.txt
> 
>The loop should count the names "Jo" , "Meg", "Beth", "Amy"
> 
>And prints the output on the screen
> 
