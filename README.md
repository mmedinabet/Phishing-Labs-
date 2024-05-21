<h1>Comprehensive Email Phishing and Attachment Analysis for SOC Analysts</h1> 

Scenario: As a Level 1 SOC Analyst, you have been tasked with analyzing suspicious emails and malicious attachments forwarded by your coworkers. Your objective is to gather details from each email and attachment to implement appropriate rules and prevent colleagues from receiving spam/phishing emails and mitigate potential security risks.

Task:Access the provided resources for each scenario and investigate the emails and attachments. Answer the questions based on your findings.

![Screenshot 2024-05-21 3 29 49 PM](https://github.com/mmedinabet/Phishing-Labs-/assets/142737434/edf78f12-ada5-46e2-babb-150b91374aa0)


<h1> Scenario 1: Suspicious Email Analysis: </h1>
Access the email messages provided in the lab environment.

![Screenshot 2024-05-21 3 30 16 PM](https://github.com/mmedinabet/Phishing-Labs-/assets/142737434/660d9499-035a-4c63-9866-508d5c467c63)

Analyze the email headers and bodies thoroughly with Mail Header Analysis, Message Header Analysis and Google Admin Toolbox Messageheader:

![Screenshot 2024-05-21 3 34 38 PM](https://github.com/mmedinabet/Phishing-Labs-/assets/142737434/af5b2428-2b4f-4693-be23-e5a3aadff11c)

![Screenshot 2024-05-21 3 38 14 PM](https://github.com/mmedinabet/Phishing-Labs-/assets/142737434/c14899ae-b015-4a1a-9e28-61b2126f1baa)

![Screenshot 2024-05-21 3 39 06 PM](https://github.com/mmedinabet/Phishing-Labs-/assets/142737434/fecbf511-7bc6-41e9-b311-98a5b1664da2)

Answer the following questions:
1. What brand was this email tailored to impersonate?

   Answer:netflix
   
2. What is the From email address?
   
   Answer:GQ47wazXe1xYVBrkeDg-JOg7ODDQwWdR@JOg7ODDQwWdR yVkCaBkTNp.gogolecloud.com
   
3. What is the originating IP? Defang the IP address.

   Answer:209[.]85[.]167[.]226

4. From what you can gather, what do you think will be a domain of interest? Defang the domain.

   Answer:etekno[.]xyz
   
5. What is the shortened URL? Defang the URL.

   Answer: hxxps[://]t[.]co/yuxfZm8KPg?amp=1



<h1> Scenario 2: Malicious Attachment Analysis </h1>

Access the provided link to Any Run for the analysis of a malicious attachment.

![Screenshot 2024-05-21 4 05 38 PM](https://github.com/mmedinabet/Phishing-Labs-/assets/142737434/4da9a427-ee9d-45a0-8450-7c7bb7f1ef6a)

![Screenshot 2024-05-21 4 05 59 PM](https://github.com/mmedinabet/Phishing-Labs-/assets/142737434/33c11c35-b8c9-4231-a330-e73c3163c51e)

Review the analysis report provided by Any Run.

Answer the following questions:

1. What does AnyRun classify this email as?

   Answer: Suspicious activity
   
2. What is the name of the file (Excel, PDF, etc.)?

   Answer: Payment-updateid.pdf
   
3. What is the SHA 256 hash for the file?

   Answer: CC6F1A04B10BCB168AEEC8D870B97BD7C20FC161E8310B5BCE1AF8ED420E2C24
   
4. What IP addresses are listed as malicious? Defang the IP addresses &

![Screenshot 2024-05-21 4 16 55 PM](https://github.com/mmedinabet/Phishing-Labs-/assets/142737434/11dbe10a-3f31-47bd-aaec-ac7d404eb759)

   Answer: 2[.]16[.]107[.]24,2[.]16[.]107[.]83

5. What Windows process was flagged as Potentially Bad Traffic?

![Screenshot 2024-05-21 4 17 46 PM](https://github.com/mmedinabet/Phishing-Labs-/assets/142737434/2c911b06-b831-4d7c-9d01-02119b8cc298)

   Answer: svchost.exe

   
<h1> Scenario 3: Malicious Attachment Analysis </h1>

Access the provided link to Any Run for the analysis of another malicious attachment.

![Screenshot 2024-05-21 4 28 56 PM](https://github.com/mmedinabet/Phishing-Labs-/assets/142737434/88867642-b7e3-4198-bbdb-f64731f6e9e1)

Review the analysis report provided by Any Run.

![Screenshot 2024-05-21 4 29 18 PM](https://github.com/mmedinabet/Phishing-Labs-/assets/142737434/1de8dfff-03a1-4ac7-a5ee-2d74ffb1eaa6)

Answer the following questions:

1. What is this analysis classified as?

   Answer:Malicious activity
   
3. What is the name of the file (Excel, PDF, etc.)?

   Answer:CBJ200620039539.xlsx
   
5. What is the SHA 256 hash for the file?

   Answer: 5f94a66e0ce78d17afc2dd27fc17b44b3ffc13ac5f42d3ad6a5dcfb36715f3eb
   
7. What domains are listed as malicious? Defang the URLs & submit answers in alphabetical order.

![Screenshot 2024-05-21 4 31 02 PM](https://github.com/mmedinabet/Phishing-Labs-/assets/142737434/37034cf8-f143-443c-9627-0cef6f6ed245)

   Answer: biz9holdings[.]com, findresults[.]site, ww38[.]findresults[.]site
   
9. What IP addresses are listed as malicious? Defang the IP addresses & submit answers from lowest to highest.

   Answer: 75[.]2[.]11[.]242, 103[.]224[.]182[.]251, 204[.]11[.]56[.]48
   
11. What vulnerability does this malicious attachment attempt to exploit?

![Screenshot 2024-05-21 4 31 56 PM](https://github.com/mmedinabet/Phishing-Labs-/assets/142737434/475012ce-ee1e-4764-897e-7b6c4cc91fa3)

   Answer: CVE-2017–11882

<h1> Conclusion </h1>

In conclusion, the comprehensive analysis of suspicious emails and malicious attachments in this lab has provided valuable insights for SOC analysts. Through thorough examination of email headers, message bodies, and attachment analysis reports, significant indicators of phishing attempts and potential security threats have been identified.

The analysis of suspicious emails revealed attempts to impersonate well-known brands like Netflix, utilizing tactics such as defanged URLs to obscure malicious links. Further investigation uncovered originating IPs, domains of interest, and shortened URLs, aiding in the understanding of potential attack vectors and threat actors' tactics.

Moreover, the examination of malicious attachments using tools like Any Run showcased their classification and provided crucial details such as file names, SHA 256 hashes, and indicators of compromise like malicious IP addresses and flagged Windows processes. Notably, vulnerabilities targeted by malicious attachments, such as CVE-2017–11882, were identified, highlighting the importance of timely patching and security awareness.

By leveraging these findings, SOC analysts can enhance their defense mechanisms, implement appropriate rules, and mitigate security risks effectively. Continuous monitoring and analysis of email communications and attachments remain vital in safeguarding organizational assets against evolving threats in the cybersecurity landscape.   
