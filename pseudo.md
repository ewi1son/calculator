!NO EVAL

#### MVC
### classes ?
class Calculator{
    constructor(){

    }
}
class "button"{
    constructor(){
        
    }
}
## Model
- Numarr [] holds all the inputs
- numarr[0] will be the total and initial input will go into index 0;
- Maybe arr for operators?
- array to hold all symbols. Use to assign ids and icon
    - [ C, +-, %, ...]
    # details
        - no more than one decimal
        - can't divide by zero
        - 

## View
- Header
- Bootstrap to show calculator buttons and text field
- Container
    - Row
        - text field col-12
        - 16 col-3 for c to +
        - Col-6 for 0
        -  col-3 for . and =
- Two states for C and AC

## Controller
- Inputs pushed Numarr[ ] 
- Check if decimal has been used and disallow if it has
- make sure you cant add lots of zeros at the beginning
- Have eventlisteners to see what operator was selected then send arr[0] and arr[length-1] to that logic
    - [2, 2]
    - Arr[0] += Arr[0] + arr[arr.length-1] = 4
    - Arr[0] += Arr[0]  / arr[arr.length-1] = 1

## General
    input
    push to array 
    array is rawdata
    ex [2, +, 2, =] -> [2] + [2] = 
    number until operator, then break

