<h1>lab 1<h1/></h1><br />
<h2>General SIEM architecture analysis<h2/>
<h2>Lab 1.1</h2>
<h3>General flow of log form Logstash->ElasticSearch->Kibana<h3 />
<h4>1)View log on terminal </h4><br />
![image](https://github.com/user-attachments/assets/d8d2f36b-4190-4053-8410-6dc884f045f7) <br />
<h4>2)Send log to ElasticSearch </h4><br />
![image](https://github.com/user-attachments/assets/8f8a31d4-00a9-470e-83bf-35b5a0171e88)<br />
<h4>3)ElasticSearch to kibana </h4><br />
![image](https://github.com/user-attachments/assets/a02ec37d-c1f8-40d9-8236-2a41c9fb5cd3)<br />


<h3>General flow of log form Logstash->BUFFER->ElasticSearch->Kibana<h3 />
<h4>Logstash->BUFFER(RabbitMQ) </h4><br />
![image](https://github.com/user-attachments/assets/0551bd89-c8fe-4842-8406-93d219a31edb) <br />
<h4>BUFFER(RabbitMQ)->ElasticSearch </h4><br />
![image](https://github.com/user-attachments/assets/60c3aa94-cad8-4d5b-9958-173e6e817861)<br />
<h4>Visulaize data from Elastic Search to kibana</h4><br />
![image](https://github.com/user-attachments/assets/ebbfd747-0147-469e-bd4e-b3cc015d8131)<br />

<h4>Using Elastic Alert(elasticalert-test-rule)</h4>
![image](https://github.com/user-attachments/assets/09fd0620-5f5e-42f1-82ad-2febaadfade9)<br />

<h2>Lab 1.2</h2><br />
<h3>Making Custom Config File to change the output according to usage</h3> <br />
<h4>Taking input as file and gave output on terminal<br /></h4>
![image](https://github.com/user-attachments/assets/c31725f6-a180-4ab7-a395-93106af94915)<br />
<h4>Can also work also on custom log( created a log with name as message <br /></h4>
![image](https://github.com/user-attachments/assets/7a5ea13d-fd10-480a-90bc-ba401ac17256)<br />
<h4>Sending log via nx-log usign UDP port 1055<br /></h4>
![image](https://github.com/user-attachments/assets/61604ab2-e310-40de-8f25-1fc91d98a68b)<br />
![image](https://github.com/user-attachments/assets/4dec6c37-0394-4c14-b6fb-2c44abebd676)<br />
<h4>Sending log via nx-log usign TCP port 1056<br /></h4>
![image](https://github.com/user-attachments/assets/3c4d88ea-1ca6-4eb6-8375-e7036c382cb3)<br />
<h4>Sending to Elastic Search on output and not on Terminal<br /></h4>
![image](https://github.com/user-attachments/assets/b581c506-8472-4b73-b15a-184eaa716df4)<br />
![image](https://github.com/user-attachments/assets/ba69f4b4-43ec-46bb-a815-555c5db4a916)<br/>



<h2>Lab 1.3</h2><br />
<h3>Filtering and How it is supposed to be DONE</h3> <br />
<h4>Grok failure and rectifing to get production running (for syslog messages)</h4><br />
![image](https://github.com/user-attachments/assets/684dad4d-ee1d-403e-9c9f-aa5a6d255960)<br />
![image](https://github.com/user-attachments/assets/e47d17b1-26cc-4d92-a265-cb0286d55521)<br />
<h4>Parsing out from message field to get some important message</h4> <br />
![image](https://github.com/user-attachments/assets/19cac64f-b4a1-468c-b376-9a8144437745)<br />
<h4>Using grok( as conditional statement) to parse out logon success</h4> <br />
![image](https://github.com/user-attachments/assets/c1348ece-d03e-44a7-b8c5-aaba133b7bd6)<br />
<h4>Log ingestion time should be changed to when event happened</h4> <br />
![image](https://github.com/user-attachments/assets/fe0435db-5ad2-4c1b-924c-93c4b6e33b97)<br />
![image](https://github.com/user-attachments/assets/d800ce68-64f6-4c28-92aa-44a752978900)<br />
<h4>Detecting Brute Force</h4> <br />
![image](https://github.com/user-attachments/assets/03516071-aaae-40e1-acf6-6ecdb0b9bd88)<br />


<h2>Lab 1.4</h2><br />
<h3>In this we will make alert for few case</h3> <br />
<h4>Alert for Log cleared</h4><br />
![image](https://github.com/user-attachments/assets/351247b9-45bd-41c3-b632-ace5996734b6)<br />
<h4>Brute force detection</h4><br />
![image](https://github.com/user-attachments/assets/6853d326-0147-4fc6-90c5-c20843d8efae)<br />
<h4>Alert for new service created and this one send to ElasticSearch for storage</h4> <br />
![image](https://github.com/user-attachments/assets/ef01443c-d9d5-4274-8b84-e5eb3c1b85fc)<br />


















