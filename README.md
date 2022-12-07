# **Simulation Based Methodology ![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.001.png)of Trojan Detection**
Supervisor - Dr. Binod Kumar

Team Members

Ramresh Meena (B19EE070) Himanshu Raj (B19EE038)

**Presentation Date- 09/07/2022           2022-23, Semester - Summer [EEN3010]**
# Motivation![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.001.png)
- Increasing complexity of ICs, Leads to increase in outsourcing the design and fabrication make it vulnerable to malicious activities and alteration(H.T).
- H.T , as a backdoor in design.
- Backdoors can leak private information as well as enable chance for other possible attack.

Threat to Security and Sovereignty of Nation

It can leak the information so it is a  serious threat to military and intelligence agencies, even for every government functionaries that have sensitive information also leaking some sensitive information can lead internal tension or make  any nation unstable. 

Indian government Initiative:   C2S, involving more youth intelligentsia in this field. 
# **Deliverables![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.001.png)**
Development of simulation -based methodology for trojan detection & Documentation. 

- Taking different some original circuitries and write test bench and simulate it .
- Insert Trojan  in Original circuitries write test bench and simulate it for detecting trojan .

In both cases Analyse code coverage and Effect of Trojan on Original circuitries performance and make documentation .

IIT Jodhpur
# **Hardware Trojan Insertion and Its impact on Circuit**
![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.002.png)

IIT Jodhpur ➔ Hardware Trojans come in a wide range of forms and sizes, as well as a wide range ![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.001.png)

of usefulness. 


# **Work Done And Results**

|**Design**|**Code Coverage (Trojan Free)**|**Code Coverage (TIn but not Triggered)**|**Code Coverage (TIn but Triggered)**|
| - | :- | :- | :- |
|RS232-T100|94.45%|93.57%|94.06%|
|RS232-T200|94.45%|88.55%||
|RS232-T300|94.45%|92.35%||
|RS232-T400|94.45%|81.36%||
|RS232-T500|94.45%|79.99%||
|RS232-T600|94.45%|72.53%||
|RS232-T700|94.45%|51.58%||
|RS232-T800|94.45%|43.05%||
|RS232-900|94.45%|43.05%||
|RC6|100%|99.80%|99.99%|
|Spi\_master|66.68%|58.50%||
|syncRAM|79.27%|73.80%|78.57%|
|Det\_1011|95.18%|94.55%||
IIT Jodhpur

# **Result (RS232 Trojan Free)**

IIT Jodhpur![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.001.png)![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.003.png)![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.004.png)
**When HT was not triggered**

Results (RS232 Trojan Inserted Design)![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.001.png)

![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.005.png)

IIT Jodhpur![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.006.png)
**When HT was not triggered**

Results![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.001.png)

![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.007.png)

IIT Jodhpur

Code coverage = 93.57%



# **When HT was triggered**
Results![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.001.png)

![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.008.png)

IIT Jodhpur ![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.009.png)

code coverage = 94.06%

Code Coverage Report when the trojan was not triggered(RS232)![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.001.png)

![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.010.png)

Code Coverage Report when the trojan was triggered(RS232)![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.001.png)

![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.011.png)

RC6 Code Coverage Report (RC6) - Not triggered

IIT Jodhpur
RC6 Code Coverage Report (RC6) - Triggered

IIT Jodhpur![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.001.png)![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.012.png)![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.013.png)

Code Coverage Report (synRAM) –Self Triggered

IIT Jodhpur![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.001.png)![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.014.png)![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.015.png)![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.016.png)

Code Coverage Report (synRAM) –Self Triggered
# **Conclusión**
- Code Coverage is more when HT was triggered as compared to when it was not triggered.![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.001.png)
- But when HT is triggered it affects some functionality of circuit.
- The numbers on both the reports are very close and so the detection of more advanced HT will become difficult.
- We can’t only rely on Code Coverage Analysis and FSM for detection of trojan detection, because of increase in complexity in design of circuits and trojans .

IIT Jodhpur![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.001.png)![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.017.png)![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.018.png)![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.019.png)
# **Thanks!![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.020.png)![](Aspose.Words.827ee45f-f291-4475-a3c8-3577dde860e7.021.png)**


