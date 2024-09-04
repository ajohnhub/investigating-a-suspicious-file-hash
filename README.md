<h1>Mock Suspicious File Hash Investigation</h1>

<h2>Description</h2>
This project simulates the process of a Level One Security Operations Center (SOC) analyst investigating a suspicious hash file within a financial company. The investigation focuses on identifying potential threats, understanding the context of the suspicious file, and determining the appropriate response to mitigate any risks to the organization. This project is designed to provide a hands-on experience in threat detection and incident response within a financial sector environment.
<br />


<h2>Utilties Used </h2>

- <b>VirusTotal</b> 

<h2>Investiagtion walk-through:</h2>

<p align="center">
Scenario: <br/>
<img width="869" alt="step1" src="https://github.com/user-attachments/assets/bfd2e218-0e37-4180-b1f4-7a7b153fba34">
<br />
<br />
Review the details of the alerts:  <br/>
<img width="485" alt="mock email" src="https://github.com/user-attachments/assets/f06ec8e1-5d50-413e-8331-648f4ac5b1b7">
<img width="613" alt="step2" src="https://github.com/user-attachments/assets/c28e2c16-66db-4565-a375-55c9562f2fe0">
<br />
<br />
Enter the SHA256 file has into the search box and press enter: <br/>
<img width="925" alt="step3" src="https://github.com/user-attachments/assets/823d5a27-200f-486e-bd93-7d8731d7ef47">
<br />
<br />
Analyze and examine the VirusTotal report by exploring the Detection, Details, Relations, Behavior, and Community Tabs:  <br/>
<img width="1434" alt="step4" src="https://github.com/user-attachments/assets/c27aed35-aaee-42ef-bf8f-ef35775ea3d8">
<img width="1429" alt="step5" src="https://github.com/user-attachments/assets/94ae96a7-b388-4744-a6e5-7e6f4b73c438">
<img width="1430" alt="step6" src="https://github.com/user-attachments/assets/aa900abe-0422-4612-8982-f098fee23629">
<img width="1433" alt="step7" src="https://github.com/user-attachments/assets/273d3d70-448e-4947-b0fa-6e6220e3670c">
<img width="1433" alt="step8" src="https://github.com/user-attachments/assets/1cf308f7-cd68-4ba5-99e4-2771bbbdcd92">
<br />
<br />
Determine whether the file is malicous by reviewing the Vendors' ratio, Community Score, and Security Vendors analysis (under the Detection tab):  <br/>
<img width="913" alt="step9" src="https://github.com/user-attachments/assets/5c4d637d-a980-4b3b-a9ca-164888ae72f7">
<img width="928" alt="step10" src="https://github.com/user-attachments/assets/d7177d99-73c5-44ce-9774-6cd844364bf9">
<img width="673" alt="step11" src="https://github.com/user-attachments/assets/8c52a985-8069-4631-ae6e-36063a1ae110">
<br />
<br />
Update and Escalate alert ticket based on findings:  <br/>
<img width="473" alt="alert ticket" src="https://github.com/user-attachments/assets/ee0a9d18-9e70-419e-97f4-b9116f75229a">
<br />
<br />
Document your investigation in your Incident Handlers Journal:  <br/>
<img width="497" alt="step14" src="https://github.com/user-attachments/assets/76d20cbc-3c6a-45e7-a2ea-4c05fe6eaf82">
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
