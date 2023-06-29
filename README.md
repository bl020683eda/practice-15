# practice-15
 function сalc(operation,a,b)
{ 
  
  switch(operation) 
            {
    case 'add':
    x = a+b;
    break;
    case 'multi':
    x = a*b;
    break;
    case 'subtract':
    x = a-b;
    break;
       default:
    console.log ('Good bay');
             }
             console.log(x); 
                     
       return(x); 
 }
let operation = 'multi';
let a=1;
let b=2;
let x;
сalc(operation,a,b);

