# volume changing experiment

Can I change volume target from initial volume?  
initial volume = 1  


volume\_decrease.fe  
target volume = 0.5
``` evolver
Enter command: gogo
  5. area:  3.25983366127884 energy:  3.25983366127884  scale: 0.211981
  4. area:  3.22061576840430 energy:  3.22061576840430  scale: 0.226369
  3. area:  3.22066883150590 energy:  3.22066883150590  scale: 0.204664
  2. area:  3.22066885453331 energy:  3.22066885453331  scale: 0.204150
  1. area:  3.22066885453331 energy:  3.22066885453331  scale: 0.00000
Vertices: 50  Edges: 144  Facets: 96  Bodies: 1  Facetedges: 288
Element memory: 45 KB, or 0 MB
Total data memory: 1651 KB, or 1 MB.
  5. area:  3.10070185170683 energy:  3.10070185170683  scale: 0.251747
  4. area:  3.09355675004724 energy:  3.09355675004724  scale: 0.206577
  3. area:  3.09269432641109 energy:  3.09269432641109  scale: 0.268828
  2. area:  3.09207200321339 energy:  3.09207200321339  scale: 0.391154
  1. area:  3.09153026977696 energy:  3.09153026977696  scale: 0.268962
  1. area:  3.09144703478932 energy:  3.09144703478932
Vertices: 194  Edges: 576  Facets: 384  Bodies: 1  Facetedges: 1152
Element memory: 180 KB, or 0 MB
Total data memory: 1673 KB, or 1 MB.
  5. area:  3.05984171594693 energy:  3.05984171594693  scale: 0.232306
  4. area:  3.05871588105256 energy:  3.05871588105256  scale: 0.188942
  3. area:  3.05842904116787 energy:  3.05842904116787  scale: 0.325973
  2. area:  3.05828261215903 energy:  3.05828261215903  scale: 0.224071
  1. area:  3.05819084407378 energy:  3.05819084407378  scale: 0.335191
  1. area:  3.05811829754650 energy:  3.05811829754650
Enter command: v

Body          target volume           actual volume          pressure
  1                     0.5       0.500000000001838  4.07598271985488
``` 

volume\_increase.fe  
target volume = 1.5
volume\_increase.fe
``` evolver
Enter command: gogo
  5. area:  6.69933316612264 energy:  6.69933316612264  scale: 0.144486
  4. area:  6.69926112958230 energy:  6.69926112958230  scale: 0.205350
  3. area:  6.69926118372185 energy:  6.69926118372185  scale: 0.204102
  2. area:  6.69926118372185 energy:  6.69926118372185  scale: 0.408204
  1. area:  6.69926118372185 energy:  6.69926118372185  scale: 0.204102
Vertices: 50  Edges: 144  Facets: 96  Bodies: 1  Facetedges: 288
Element memory: 45 KB, or 0 MB
Total data memory: 1650 KB, or 1 MB.
  5. area:  6.44925208029697 energy:  6.44925208029697  scale: 0.257701
  4. area:  6.43479919301204 energy:  6.43479919301204  scale: 0.197888
  3. area:  6.43301644015782 energy:  6.43301644015782  scale: 0.287136
  2. area:  6.43174593868540 energy:  6.43174593868540  scale: 0.368852
  1. area:  6.43064050060872 energy:  6.43064050060872  scale: 0.280535
  1. area:  6.43044898014526 energy:  6.43044898014526
Vertices: 194  Edges: 576  Facets: 384  Bodies: 1  Facetedges: 1152
Element memory: 180 KB, or 0 MB
Total data memory: 1672 KB, or 1 MB.
  5. area:  6.36471703435303 energy:  6.36471703435303  scale: 0.232211
  4. area:  6.36237740835996 energy:  6.36237740835996  scale: 0.189052
  3. area:  6.36178228311935 energy:  6.36178228311935  scale: 0.325450
  2. area:  6.36147833656452 energy:  6.36147833656452  scale: 0.224320
  1. area:  6.36128777808095 energy:  6.36128777808095  scale: 0.334693
  1. area:  6.36113703505374 energy:  6.36113703505374
Enter command: v

Body          target volume           actual volume          pressure
  1                     1.5        1.50000000000552  2.82612752698111
``` 

In this simple example, both volume increase and decrease work.  
