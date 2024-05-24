To complete this **optional** activity, you must follow the step-by-step instructions and receive at least 75%, or 4.6 out of 6 points, on the questions that follow. Once you have answered the questions, review the feedback statements. You can learn more about the graded and practice items in the [course overview](https://www.coursera.org/learn/detection-and-response/supplement/DUzXu/course-6-overview).

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/MP5NTCmfROmYaxeHDJqyNw_1177d6594b6a4da198cbb28148c3f1f1_3cv9BP1l4bftjWYdBl1VHbPAiwH7LgnKSy3FMnjDnVQM-mnf8klNZs4IIVallQd7oX7lLSEgxOOCBiWLSTTsbD5HwvJHMYf_ZmHwzG3Bjhu7qzs7rDg4YmJ6O-wbbLGJ5WPofkI3bCiV7_w35AgFX3_c7EA0QZvgKWx2DBQUGV66flINJOM0kDIs24Yfpg?expiry=1716681600000&hmac=RQthllK4XIKYvScxf_7PBEXam7IBEo8TxxM6RPjScvQ)

## Activity Overview

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/mRH6g7syTgumyldVSTymww_c43dd0cd05dc42159187f2be5e8734f1_zPkTxkMZ66bYSQloGXynuo0DpBC4Raepg1CiNiFaNWiDb7dqa2cpJdjL5gQcJSPHmSxMkePc-Jk69mzkvlAb8Fc5nGleH_a_4W-8mYK7pSaNiR7r0X27Zpmn34JLjUzRPAXFl0FcfjsUCBCTU1bZZwRo4Zwqo_jB6-Pz9K-9PWp3AJt59h-pPISFxMlIqw?expiry=1716681600000&hmac=jbtpvhsJB42Nks2QRz1ziCbzL0WT8R5QY8c21eHSnlk)

In this activity, you will use Chronicle, a cloud-native tool, to investigate a security incident involving phishing and answer a series of questions.

You've learned about how SIEM tools like Chronicle provide a platform for collecting, analyzing, and reporting on data from different data sources. As a security analyst, you'll use SIEM tools to identify and respond to security incidents.

**Please note that this activity is optional and will not affect your completion of the course.**

## Scenario

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/2GGFJm4MTHqgHXFOjexFTA_baa9b5d8942845589f41dbaf5085f8f1_Y07_d7_-yfWiHVTvaCdQK89qH9A77Pp_6dyfWAK68fRpOCjkMHBpCW1hmHDWcYWyOdM7-06_fZrYbB7jhFJiX34_pjkT4oZ6mf7RFQv9lJBv2AHx4ZrkNlKzsNA4wr8wq2Xr2S6kLtyWAhBMAPnLFAIPJkP5a6soaKkd7xDSPzSLC-pztN4NX1cN9Ke-DA?expiry=1716681600000&hmac=smvkf3QJkxOslyHBORpBNWDOIdmO3Mg9KQqeU8RUNW8)

Review the following scenario. Then complete the step-by-step instructions.

You are a security analyst at a financial services company. You receive an alert that an employee received a phishing email in their inbox. You review the alert and identify a suspicious domain name contained in the email's body: signin.office365x24.com. You need to determine whether any other employees have received phishing emails containing this domain and whether they have visited the domain. You will use Chronicle to investigate this domain.

_**Note**_: _Use the incident handler's journal you started in_ [_a previous activity_](https://www.coursera.org/learn/detection-and-response/exam/ghRgc/portfolio-activity-document-an-incident-with-an-incident-handlers-journal) _to take notes during the activity and keep track of your findings._

## Step-By-Step Instructions

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/Czt9antsSySI6ILzwzhEZQ_81938dd056be4298909008f2333b4ff1_Y07_d7_-yfWiHVTvaCdQK89qH9A77Pp_6dyfWAK68fRpOCjkMHBpCW1hmHDWcYWyOdM7-06_fZrYbB7jhFJiX34_pjkT4oZ6mf7RFQv9lJBv2AHx4ZrkNlKzsNA4wr8wq2Xr2S6kLtyWAhBMAPnLFAIPJkP5a6soaKkd7xDSPzSLC-pztN4NX1cN9Ke-DA?expiry=1716681600000&hmac=qBRvEWL_OgeWMGAEi-j3XIi9MYPMYJKvgJpfX7xvZIM)

Follow the instructions and answer the series of questions to complete the activity.

### Step 1: Launch Chronicle

Click the link to launch [Chronicle](http://goo.gle/chroniclelab).

On the Chronicle home page, you’ll find the current date and time, a search bar, and details about the total number of log entries. There are already a significant number of log events ingested into the Chronicle instance.

![Chronicle's home page](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/Gioj8h7hQAmyDpjKFAYz0w_8a1793ac2a5446b49b321145540672f1_Chronicle-Homepage.png?expiry=1716681600000&hmac=nz79Uvpb9dpRdrIXO5dlXoijJXVqD538Los__2kXBeM)

_**Note**__: Chronicle supports Google Chrome. You may experience limited functionality if you use  browsers like Firefox, Edge, or Safari. For the best experience using Chronicle,_ [_install the latest version of Chrome_](https://www.google.com/chrome/)_._

### Step 2: Perform a domain search

To begin, complete these steps to perform a domain search for the domain contained in the phishing email. Then, search for events using information like hostnames, domains, IP addresses, URLs, email addresses, usernames, and file hashes. 

1. In the search bar, type signin.office365x24.com and click **Search**. Under **DOMAINS**, signin.office365x24.com will be listed. This tells you that the domain exists in the ingested data. 
    
2. Click signin.office365x24.com to complete the search.
    
3. Click Go to Legacy View to use the original chronicle interface.
    

_*Note: These instructions are to be updated for the new Chronicle interface_

### Step 3: Evaluate the search results

After performing a domain search, you'll be in the domain view. Evaluate the search results and observe the following:

1. **VT CONTEXT**: This section provides the VirusTotal information available for the domain. 
    
2. **WHOIS**: This section provides a summary of information about the domain using WHOIS, a free and publicly available directory that includes information about registered domain names, such as the name and contact information of the domain owner. In cybersecurity, this information is helpful in assessing a domain's reputation and determining the origin of malicious websites. 
    
3. **Prevalence**: This section provides a graph which outlines the historical prevalence of the domain. This can be helpful when you need to determine whether the domain has been accessed previously. Usually, less prevalent domains may indicate a greater threat. 
    
4. **RESOLVED IPS**: This insight card provides additional context about the domain, such as the IP address that maps to signin.office365x24.com, which is 40.100.174.34. Clicking on this IP will run a new search for the IP address in Chronicle. Insight cards can be helpful in expanding the domain investigation and further investigating an indicator to determine whether there is a broader compromise.
    
5. **SIBLING DOMAINS**: This insight card provides additional context about the domain. Sibling domains share a common top or parent domain. For example, here the sibling domain is listed as login.office365x24.com, which shares the same top domain office365x24.com with the domain you're investigating: signin.office365x24.com.
    
6. **ET INTELLIGENCE REP LIST**: This insight card includes additional context on the domain. It provides threat intelligence information, such as other known threats related to the domains using ProofPoint's Emerging Threats (ET) Intelligence Rep List.
    
7. Click **TIMELINE**. This tab provides information about the events and interactions made with this domain. Click **EXPAND ALL** to reveal the details about the HTTP requests made including GET and POST requests.  A GET request retrieves data from a server while a POST request submits data to a server.
    
8. Click **ASSETS**. This tab provides a list of the assets that have accessed the domain.
    

![Chronicle's search results in domain view](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/261J6kxXR624_AUWLVq2Tw_e115e68ccecf4494b1ac9342cfdfe5f1_Chronicle-search-results.png?expiry=1716681600000&hmac=ptSaHGNdOVsnX17o4RGTaq8_DYK7ZAfQ3O2vozNHtfM)

### Step 4: Investigate the threat intelligence data

Now that you've retrieved results for the domain name, the next step is to determine whether the domain is malicious. Chronicle provides quick access to threat intelligence data from the search results that you can use to help your investigation. Follow these steps to analyze the threat intelligence data and use your incident handler's journal to record interesting data:

1. Click on **VT CONTEXT** to analyze the available VirusTotal information about this domain. There is no VirusTotal information about this domain. To exit the VT CONTEXT window, click the **X**.
    
2. By **Top Private Domain,** click office365x24.com to access the domain view for office365x24.com. Click **VT CONTEXT** to assess the VirusTotal information about this domain. In the pop up, you can observe that one vendor has flagged this domain as malicious. Exit the VT CONTEXT window. Click the back button in your browser to go back to the domain view for the signin.office365x24.com search.
    
3. Click on the **ET INTELLIGENCE REP LIST** insight card to expand it, if needed. Take note of the category.
    

### Step 5: Investigate the affected assets and events

Information about the events and assets relating to the domain are separated into the two tabs: **TIMELINE** and **ASSETS**. **TIMELINE** shows the timeline of events that includes when each asset accessed the domain. **ASSETS** list hostnames, IP addresses, MAC addresses, or devices that have accessed the domain.

Investigate the affected assets and events by exploring the tabs:

1. **ASSETS**: There are several different assets that have accessed the domain, along with the date and time of access. Using your incident handler's journal, record the name and number of assets that have accessed the domain. 
    
2. **TIMELINE**: Click **EXPAND ALL** to reveal the details about the HTTP requests made, including GET and POST requests. The POST information is especially useful because it means that data was sent to the domain. It also suggests a possible successful phish. Using your incident handler's journal, take note of the POST requests to the /login.php page. For more details about the connections, open the raw log viewer by clicking the open icon.
    

![Chronicle's raw log viewer](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/e5EK_E9TTzSjKoKe7vzkZA_ed1c2c0de1c94904b18c02d4908937f1_Chronicle-raw-log-viewer.png?expiry=1716681600000&hmac=zvITijm-1wMq1CFPsJTXLGuJRnMG12xSSuMY1KlSGXM)

### Step 6: Investigate the resolved IP address

So far, you have collected information about the domain's reputation using threat intelligence, and you've identified the assets and events associated with the domain. Based on this information, it's clear that this domain is suspicious and most likely malicious. But before you can confirm that it is malicious, there's one last thing to investigate.

Attackers sometimes reuse infrastructure for multiple attacks. In these cases, multiple domain names resolve to the same IP address.

Investigate the IP address found under the **RESOLVED IPS** insight card to identify if the signin.office365x24.com domain uses another domain. Follow these steps: 

1. Under **RESOLVED IPS**, click the IP address 40.100.174.34.
    
2. Evaluate the search results for this IP address and use your incident handler's journal to take note of the following:
    
    1. **TIMELINE**: Take note of the additional POST request. A new POST suggests that an asset may have been phished.
        
    2. **ASSETS**: Take note of the additional affected assets.
        
    3. **DOMAINS**: Take note of the additional domains associated with this IP address.
        

### Step 7: Answer questions about the domain investigation

Use the notes you've taken in your incident handler's journal and the Chronicle search results to answer the following questions about the investigation. Be sure to query the correct domain listed in each question.
### Question 1
#### According to the available ET Intelligence Rep List, how is signin.office365x24.com categorized?

* [x] Drop site for logs or stolen credentials
* Command and control server
* Spam site
* Phishing site
### Question 2
#### Which assets accessed the signin.office365x24.com domain? Select three answers.

* [x] coral-alvarez-pc
* [x] roger-spence-pc
* thomas-garcia-pc
* [x] emil-palmer-pc
### Question 3
#### Which IP address does the signin.office365x24.com domain resolve to?

* 10.0.0.222
* [x] 40.100.174.34
* 10.0.29.22
* 45.32.8.8
### Question 4
#### How many POST requests were made to the IP address 40.100.174.34?

* [x] 3
* 8
* 1
* 11
### Question 5
#### Some POST requests were made to signin.office365x24.com. What is the target URL of the web page that the POST requests were made to?

* http://accounts-gooqle.com/login.php
* http://office365x24.com/login.exe
* [x] http://signin.office365x24.com/login.php
* http://accounts-gooqle.com/login.txt
### Question 6
#### Which domains does the IP address 40.100.174.34 resolve to? Select two answers.

* cloud2.xdnscloud.com
* [x] signin.office365x24.com
* euw.adserver.snapads.com
* [x] signin.accounts-gooqle.com
## Key takeaways

In this activity, you used Chronicle to investigate a suspicious domain used in a phishing email. Using Chronicle's domain search, you were able to:

- Access threat intelligence reports on the domain
    
- Identify the assets that accessed the domain
    
- Evaluate the HTTP events associated with the domain
    
- Identify which assets submitted login information to the domain
    
- Identify additional domains 
    

After investigation, you determined that the suspicious domain has been involved in phishing campaigns. You also determined that multiple assets might have been impacted by the phishing campaign as logs showed that login information was submitted to the suspicious domain via POST requests. Finally, you identified two additional domains related to the suspicious domain by examining the resolved IP address. 

If you would like to explore more investigations, check out the chat bot feature on Chronicle's home page.