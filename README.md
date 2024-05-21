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
Review the analysis report provided by Any Run.

Answer the following questions:

1. What does AnyRun classify this email as?

   Answer: Suspicious activity
   
2. What is the name of the file (Excel, PDF, etc.)?

   Answer: Payment-updateid.pdf
   
3. What is the SHA 256 hash for the file?

   Answer: CC6F1A04B10BCB168AEEC8D870B97BD7C20FC161E8310B5BCE1AF8ED420E2C24
   
4. What IP addresses are listed as malicious? Defang the IP addresses &

   Answer: 2[.]16[.]107[.]24,2[.]16[.]107[.]83

5. What Windows process was flagged as Potentially Bad Traffic?

   Answer: svchost.exe

   
<h1> Scenario 3: Malicious Attachment Analysis </h1>

Access the provided link to Any Run for the analysis of another malicious attachment.
Review the analysis report provided by Any Run.

Answer the following questions:

1. What is this analysis classified as?

   Answer:Malicious activity
   
3. What is the name of the file (Excel, PDF, etc.)?

   Answer:CBJ200620039539.xlsx
   
5. What is the SHA 256 hash for the file?

   Answer: 5f94a66e0ce78d17afc2dd27fc17b44b3ffc13ac5f42d3ad6a5dcfb36715f3eb
   
7. What domains are listed as malicious? Defang the URLs & submit answers in alphabetical order.

   Answer: biz9holdings[.]com, findresults[.]site, ww38[.]findresults[.]site
   
9. What IP addresses are listed as malicious? Defang the IP addresses & submit answers from lowest to highest.

   Answer: 75[.]2[.]11[.]242, 103[.]224[.]182[.]251, 204[.]11[.]56[.]48
   
11. What vulnerability does this malicious attachment attempt to exploit?

   Answer: CVE-2017–11882
   
