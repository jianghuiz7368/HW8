# HW8
Name: Jiang Hui Zheng
ID: 116588223

Part A Test Cases:

Test 1: shape=0 (Triangle), Size=3
Input: 0, 3
Expected Output:
```
*
**
***
```

Test 2: shape=1 (Square), Size=10
- Input: 1, 4
Expected Output:
```
**********
**********
**********
**********
**********
**********
**********
**********
**********
**********
```
Actual Output:
```
**********
**********
**********
**********
**********
**********
**********
**********
**********
**********
```
- Test Pass


Test 3: shape=2 (Pyramid), Size=4
- Input: 2, 4
- Expected Output:
```
   *
  * *
 * * *
* * * *
```
Actual Output:
```
   *
  * *
 * * *
* * * *
```
Test Pass

Test 4: shape=0 (Triangle), Size=1
Input: 0, 1
Expected Output:
```
*
```
Actual Output:
```
*
```
Test Pass

Test 5: shape=1 (Square), Size=1
Input: 1, 1
Expected Output:
```
*
```
Actual Output:
```
*
```

Test pass

Part B Test Cases

Test 1: num=2

A[1]=6
B[1]=7
A[2]=1
B[2]=2

Expected Output:
6 7|2 1|

Actual Output:
6 7|2 1|

Test passed

Test 2: num = 2

A[1]=1
B[1]=1
A[2]=12
B[2]=2

Expected Output: 1 1|2 12|

Actual Output:1 1|2 12|

Test passed

Test 3:
num=2,

A[1]=-1
B[1]=-3
A[2]=-5
B[2]=-3

Expected Output: -3 -1|-3 -5|

Actual Output: -3 -1|-3 -5|

Test 4:
num = 10
A[1]=11
B[1]=12
A[2]=13
B[2]=14
A[3]=15
B[3]=16
A[4]=17
B[4]=18
A[5]=19
B[5]=20
A[6]=1
B[6]=2
A[7]=3
B[7]=4
A[8]=5
B[8]=6
A[9]=7
B[9]=8
A[10]=9
B[10]=10
Expected Output: 12 11|14 13|16 15|18 17|20 19|2 1|4 3|6 5|8 7|10 9|

Actual Output: 12 11|14 13|16 15|18 17|20 19|2 1|4 3|6 5|8 7|10 9|

Test Pass

Test 5:
num=1
A[1]=8
B[1]=6
Expected Output: 6 8|
Actual Output: 6 8|
Test Pass

Part C Test Cases

Test 1: 
Array: {1,1,4,5,6,7,8,6,6,5}
Expected Output: 
```
Sorted Array: 8 7 6 6 6 5 5 4 1 1 
```
Actual Output:
```
Sorted Array: 8 7 6 6 6 5 5 4 1 1 
```
Test Pass

Test 2:
Array: {0,0,0,0,0,0,0,0,0,0}
Expected Output:
```
Sorted Array: 0,0,0,0,0,0,0,0,0,0
```
Actual Output:Sorted Array: 0,0,0,0,0,0,0,0,0,0
Test Passed

Test 3:
Array: {-1,-2,-3,-4,-5,-6,-7,-8,-9,-10 }

Expected Output: 
```
Sorted Array: -1,-2,-3,-4,-5,-6,-7,-8,-9,-10 
```

Actual Output: 
```
Sorted Array: -1,-2,-3,-4,-5,-6,-7,-8,-9,-10 
```
Test passed

Test 4:
Array: {-10,-9,-8,-7,-6,-5,-4,-3,-2,-1 }
Expected output: 
```
Sorted Array: -1 -2 -3 -4 -5 -6 -7 -8 -9 -10 
```
Actual Output: 
```
Sorted Array: -1 -2 -3 -4 -5 -6 -7 -8 -9 -10 
```
Test Passed

Test 5:
Array: {4,4,3,3,3,2,2,1,1,100}
Expected Output: 
```
Sorted Array: 100 4 4 3 3 3 2 2 1 1
```
Actual Output: 
```
Sorted Array: 100 4 4 3 3 3 2 2 1 1
```
Test Passed

Part D Test Cases

Test 1:

A=  
    0 0 0 0 
	 0 0 0 0 
	 0 0 0 0 
	 0 0 0 0 

B=  
    1 0 0 0  
	 0 1 0 0 
	 0 0 1 0 
	 0 0 0 1 

Expected Output:
```
0 0 0 0
0 0 0 0
0 0 0 0
0 0 0 0
```

Actual Output:
```
0 0 0 0 
0 0 0 0 
0 0 0 0 
0 0 0 0 
```
- Test Passed

Test 2:

A = 
    2 0 0 0
    0 2 0 0
    0 0 2 0
    0 0 0 2

B = 
    1 2  3  4
    5 6  7  8
    9 10 11 12
    13 14 15 16

Expected Output:
```
2 4 6 8
10 12 14 16
18 20 22 24
26 28 30 32
```

Actual Output:
```
2 4 6 8
10 12 14 16
18 20 22 24
26 28 30 32
```
Test passed
Test 3:

A = 
    1 0 0 0
    0 1 0 0
    0 0 1 0
    0 0 0 1

B = 
    1 0 0 0
    0 1 0 0
    0 0 1 0
    0 0 0 1
    
Expected Output:
```
1 0 0 0
0 1 0 0
0 0 1 0
0 0 0 1
```
Test passed

Test 4:

A =  
     1 0 0 0 
	  2 0 0 0 
	  3 0 0 0 
	  4 0 0 0

B =  
    1 2 3 4  
	  5 1 0 0 
	  0 0 1 0 
	  0 0 0 1 

Expected Output:
```
1 2 3 4 
2 4 6 8 
3 6 9 12 
4 8 12 16 
```

Actual Output:
```
1 2 3 4 
2 4 6 8 
3 6 9 12 
4 8 12 16 
```
Test passed

Test 5:

A = 
    1 2 3 4
    1 2 3 4
    1 2 3 4
    1 2 3 4

B = 
    1 1 1 1
    2 2 2 2
    3 3 3 3
    4 4 4 4

Expected Output:
```
30 30 30 30
30 30 30 30
30 30 30 30
30 30 30 30
```

Actual output:
```
30 30 30 30
30 30 30 30
30 30 30 30
30 30 30 30
```
Test Passed
