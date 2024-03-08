# CFG Lab

## Student 1: Chems-Eddine Saidi - 40192094

###Calculator App
Step1: Draw CFG

![image](https://github.com/SOEN345-WINTER2024/cfg-graph-lab-ChemsCode/assets/90106593/e7e7720d-6857-459a-a53d-2d53048d06f8)


####Step2: TR + Test Paths for NCS

TRs = { 1, 2, 3, 4,5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19}

Test Paths = 
[1, 2, 19],
[1, 3, 19],
[1, 4, 19],
[1, 5, 19],
[1, 6, 19],
[1, 7, 19],
[1, 8, 19],
[1, 9, 19],
[1, 10, 19],
[1, 11, 19],
[1, 12, 13, 18, 19],
[1, 12, 13, 14, 15, 14, 18, 19],
[1, 12, 13, 15, 16, 15, 18, 19],
[1, 12, 13, 14, 15, 16, 17, 16, 18, 19],
[1, 12, 13, 15, 16, 17, 16, 15, 14, 18, 19]


####Step3: TR + Test Paths for EC
TRs = {
  (1, 2), (2, 19), (1, 3), (3, 19), (1, 4), (4, 19), (1, 5), (5, 19), 
  (1, 6), (6, 19), (1, 7), (7, 19), (1, 8), (8, 19), (1, 9), (9, 19), 
  (1, 10), (10, 19), (1, 11), (11, 19), (1, 12), (12, 13), (13, 14), 
  (14, 15), (15, 14), (15, 16), (16, 15), (16, 17), (17, 16), (13, 18), 
  (14, 18), (15, 18), (16, 18), (17, 18), (18, 19)
}


Test Paths = 
[1, 2, 19],
[1, 3, 19],
[1, 4, 19],
[1, 5, 19],
[1, 6, 19],
[1, 7, 19],
[1, 8, 19],
[1, 9, 19],
[1, 10, 19],
[1, 11, 19],
[1, 12, 13, 18, 19],
[1, 12, 13, 14, 15, 14, 18, 19],
[1, 12, 13, 15, 16, 15, 18, 19],
[1, 12, 13, 14, 15, 16, 17, 16, 18, 19],
[1, 12, 13, 15, 16, 17, 16, 15, 14, 18, 19]

####Step4: TR + Test Paths for EPC
TRs ={
  [1, 2, 19], 
  [1, 3, 19], 
  [1, 4, 19], 
  [1, 5, 19], 
  [1, 6, 19], 
  [1, 7, 19], 
  [1, 8, 19], 
  [1, 9, 19], 
  [1, 10, 19], 
  [1, 11, 19], 
  [1, 12, 13], 
  [12, 13, 14], [12, 13, 15], [12, 13, 16], [12, 13, 17],
  [13, 14, 18], [13, 15, 18], [13, 16, 18], [13, 17, 18],
  [14, 18, 19], [15, 18, 19], [16, 18, 19], [17, 18, 19],
}


Test Paths = 
[1, 2, 19],
[1, 3, 19],
[1, 4, 19],
[1, 5, 19],
[1, 6, 19],
[1, 7, 19],
[1, 8, 19],
[1, 9, 19],
[1, 10, 19],
[1, 11, 19],
[1, 12, 13, 18, 19],
[1, 12, 13, 14, 15, 14, 18, 19],
[1, 12, 13, 15, 16, 15, 18, 19],
[1, 12, 13, 14, 15, 16, 17, 16, 18, 19],
[1, 12, 13, 15, 16, 17, 16, 15, 14, 18, 19]

####Step5: Draw the EFG graph for the Calculator App 

![image](https://github.com/SOEN345-WINTER2024/cfg-graph-lab-ChemsCode/assets/90106593/1d630b1a-3ced-4d7f-bd65-5e445ec26899)



###My App

![image](https://github.com/SOEN345-WINTER2024/cfg-graph-lab-ChemsCode/assets/90106593/1a3b24c8-8a72-46ad-892d-868a292ff9b4)


####Step1: Draw CFG

![image](https://github.com/SOEN345-WINTER2024/cfg-graph-lab-ChemsCode/assets/90106593/d54493d2-13e5-4592-90f1-b7904f716d67)


Step2: TR + Test Paths for NC
TR = {1 ,2 ,3 ,4}

Test Paths = [1, 2, 4], [1, 2, 4]
Step3: TR + Test Paths for EC
TR = { (1, 2), (1, 3), (2,4), (3, 4) }

Test Paths = [1, 2, 4], [1, 2, 4]
Step4: TR + Test Paths for EPC
TR = { [1, 2, 4, [1, 3, 4] }

Test Paths = [1, 2, 4], [1, 2, 4]
Step5: Draw the EFG graph

![image](https://github.com/SOEN345-WINTER2024/cfg-graph-lab-ChemsCode/assets/90106593/54c0094d-4a54-4d48-9fbe-c7c04fe9d75f)






