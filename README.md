# DECODER2TO4
# Truth Table and Circuit Diagram
![image](https://github.com/RESMIRNAIR/DECODER2TO4/assets/154305926/e565d523-f8b2-4e01-8888-0eed4d07ec24)
VERILOG CODE 
`````````````
module decoder1(a,y);
input [2:0]a;
output[7:0]y; and(y[0],~a[2],~a[1],~a[0]);
and(y[1],~a[2],~a[1],a[0]);
and(y[2],~a[2],a[1],~a[0]);
and(y[3],~a[2],a[1],a[0]);
and(y[4],a[2],~a[1],~a[0]);
and(y[5],a[2],~a[1],a[0]);
and(y[6],a[2],a[1],~a[0]);
and(y[7],a[2],a[1],a[0]); 
endmodule 

 `````````````
OUTPUT 


![image](https://github.com/YEMANTHKUMAR/DECODER2TO4/assets/160569469/74cbb5e2-b3a6-4858-badb-ba87ef3601bb)
