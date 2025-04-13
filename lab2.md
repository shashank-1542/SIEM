<h1>lab 2<h1/></h1><br />
<h2> Detection Anomaly and visulising it for soc analyst </h2> <br />
<h2> Lab 2.1 </h2> <br />
<h3>DNS Dash Board Creation for Finding Adversary</h3> <br />
<h4>1.In this made a visualization for detecting internal IP accessing external Domain</h4> <br />  
  
![image](https://github.com/user-attachments/assets/3fc5e6d1-779d-4a85-8e7a-bd4730457eb2)
 <br />
<h4>2.In this Visualizing Query Type of Domain</h4><br />

![image](https://github.com/user-attachments/assets/7d50936e-473b-424f-95a8-6f0201fc062f) <br />
<h4>3.In this Found Domain frequency in Table Visualization</h4> <br />

![image](https://github.com/user-attachments/assets/74e13049-69c2-4dac-a864-4281c7e4fcd4)<br />
<h4>4.Fuzzy Search (Levenshtein search) 1 change vs Exact Match</h4><br />

![image](https://github.com/user-attachments/assets/7aac1777-a28d-4673-85b2-92b6682c677f)<br />
![image](https://github.com/user-attachments/assets/d0aa8986-371d-4cc4-b204-1a8738b4d8fc)<br />
<h4>5.Phishing Matching if similar is found(result of above Query more than one) Than red color otherwise GREEN</h4> <br />

![image](https://github.com/user-attachments/assets/0c3d99cb-422c-4c5e-a477-e47bee1ac6f2)<br />
<h4>6. Making Dashboard for Defender to visually detect any issue</h4><br />

![image](https://github.com/user-attachments/assets/f7f64fff-624d-4972-8622-13b74bacbf6c)<br />


<h2> Lab 2.2</h2> <br />
<h3>Working on IDS log and enrichment </h3> <br />
<h4>1.Parsing out all details</h4> <br />

![image](https://github.com/user-attachments/assets/7badc100-9b43-4362-bfb7-05576ceec25f) <br />
<h4>2.Using geoip filter to get more context to the ALERT</h4> <br />

![image](https://github.com/user-attachments/assets/7e94ff55-ae0f-4770-9420-d5c16cd7920f)<br />
<h4>3.Further DNS reverlookup from internal DNS resolved log for proper data...As sometimes lookup give wrong answers as in other pic for google[.]com</h4> <br />

![image](https://github.com/user-attachments/assets/e7215bf8-ccd6-439d-a7d7-6a8e029a74f2)<br />
![image](https://github.com/user-attachments/assets/73b08fba-6751-4e08-b13c-a19a0ab5e931)<br />
<h4>4.Using ENDPOINT log for more information enrichment and .... also got to detect pdf file that was downloaded...probably a phishing attack.</h4> <br />

![image](https://github.com/user-attachments/assets/8eeb7a7c-aa34-4338-b7ed-02f0082a6bf9)<br />


<h2>Lab2.3</h2> <br />
<h3>Analyzing HTTP by creating Dashboard for different type of attacks detection</h3>
<h4>1. Host name and IP corroboration</h4> <br />

![image](https://github.com/user-attachments/assets/57c67bbf-e1f9-4947-9574-ecefbd3b8b3b) <br />
<h4>2.Dashboard created on diff type of visulization</h4> <br />

![image](https://github.com/user-attachments/assets/6bdfb072-46c6-404e-b560-50d20d171ddc) <br />
<h4>3.Analyzing Naked IP connection (Just say part of defense in Depth) ...  we will filter out COMMON ASN and analyze left one</h4> <br />

![image](https://github.com/user-attachments/assets/38bfca6f-1c3a-42a7-a2f2-a6d73cc44a39) <br />
<h4>4.Checking GOOGLE ASN as can not be ignored</h4> <br />

![image](https://github.com/user-attachments/assets/6ff921de-9d27-409f-b68d-2f23cf1f8527)<br />
<h4>5.Finally We got all the Virtual Host we need to analyse and which Internal IP we need to analyze.</h4> <br />

![image](https://github.com/user-attachments/assets/ef9a8c94-48ea-4e9c-b87c-1d982e6b28f7) <br />








                                                                                                                     >










