CSE 332/ EEE 336/ ETE 336**  Computer Organization and Architecture 

**Lab Manual ![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.001.png)**

**Department of Electrical and Computer Engineering** 

**School of Engineering and Physical Sciences** 

**North South University, Bashundhara, Dhaka-1229, Bangladesh \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_** 

**E**  **xperiment No: 1** 

**E**  **xperiment Name: Design of a 2-bit Logic unit. ![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.002.png)**

**Introd**  **uction:** 

**In this experiment you will construct a 2-bit logic unit which is actually a part of an ALU.** 

**This  logic  unit  will  have  4  micro-operations  which  are  AND,  OR,  XOR  and  NOT operations. Logic micro operations are very useful for manipulating individual bits or a portion of a word stored in a register. They can be used to change bit values, delete a group of bits or insert a new set of bits in a register. As we are going to design a 2-bit logic unit, we will have two outputs which is one output for each of the 2 bits.** 

**Equipments:** 

**T**  **rainer board** 

**IC 7404,7408,7432,7486, 74F153 Wires for connection.** 

**Truth Table:** 

**Co**  **mplete the Truth Table according to your theoretical knowledge.** 

`      `**A1     A0   B1  B0   AND1  AND0    OR1    OR0    XOR1   XOR0    NOT NOT ![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.003.png)**

**A1 A0** 

**0  0  0  0**   ![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.004.png)**0  0  0  1 0 ![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.005.png) 0  1  0 0 ![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.006.png) 0  1  1 0 ![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.007.png) 1  0  0 0 ![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.008.png) 1  0  1 0 ![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.009.png) 1  1  0 0 ![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.010.png) 1  1  1 1 ![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.011.png) 0  0  0 ![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.012.png)![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.013.png)**

**CSE 332/ EEE 336/ ETE 336  Computer Organization and Architecture** 

**1  0  0  1 1 ![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.014.png)![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.015.png) 0  1  0 1 ![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.016.png) 0  1  1 1 ![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.017.png) 1  0  0 1 ![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.018.png) 1  0  1 1 ![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.019.png) 1  1  0 1 ![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.020.png) 1  1  1 ![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.021.png)![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.022.png)**

**Logic Diagram:** 

![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.023.png)

**CSE 332/ EEE 336/ ETE 336 Computer Organization and Architecture** 

**Procedure: (hardware)** 

1) **Place the ICs on the trainer board.** 
1) **Connect Vcc and ground to the respective pins of IC.** 
1) **Connect the inputs with the switches and the outputs with LEDs.** 
1) **Apply various combinations of inputs and observe the outputs.** 
1) **Verify the experimental outputs with the Truth Table.** 

**Assignment/Task:** 

1. **Implement the circuit in Logisim. Submit logisim (.circ) file + the screenshots of the circuits within the given time by your lab instructor.**  
1. **Prepare and submit the lab report by the end of the class individually. In the report, you have to include the *Screenshot* of the circuit as a Circuit Diagram. The screenshot must contain your name and ID along with the circuit.**  

**\*\*Plagiarism and late submission will not be acceptable.** 


**Pin configuration of ICs:** 

**CSE 332/ EEE 336/ ETE 336 Computer Organization and Architecture** 

![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.024.jpeg)

**CSE 332/ EEE 336/ ETE 336 Computer Organization and Architecture** 

![](Aspose.Words.2175e2da-5121-4d52-8248-c5c20b982edb.025.jpeg)
