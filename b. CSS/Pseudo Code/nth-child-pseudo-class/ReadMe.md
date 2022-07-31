# :nth-child pseudo class

use :nth-child pseudo class is like 

```li:nth-child(1){
    code here
}
```

* :nth-child(1)
select list element number 1

* :nth-child(5)
select list element number 5

* :nth-child(odd)
select list odd element

* :nth-child(even)
select list even element

* :nth-child(1n)
select all list element

* :nth-child(2n)
select all even element

* :nth-child(An+B) -- 
(2n+1) = 2 x 0 + 1 = 1, Select 1st element
(3n+1) = 3 x 1 + 1 = 4, Select 4th element
(4n+2) = 4 x 1 + 2 = 6, Select 6th element
and so on

* :nth-child(n+5)
select element from 5th, total 5, like
0+5 = 5
1+5 = 6
2+5 = 7
and so on

* :nth-child(-n+5)
select first 5 element, like
-0+5 = 5th
-1+5 = 4th
-2+4 = 3rd
and so on

* :nth-last-child(3)
select last 3rd element

1. Video Resource [video](https://www.youtube.com/watch?v=fg7GEN7PbWs)

