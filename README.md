# WEEK 03 CYBERSECURITY INTERNSHIP REPORT

**Name:** kelvin Chitauro
**Batch:** B084  
**Program:** NetworkWalks Cybersecurity Internship  
**Week:** 03  
**Project:** Password Cracking (PM1 and PM2)

## 1. Introduction

During Week 03 of my NetworkWalks Cybersecurity Internship, I focused on learning and practising password cracking techniques. The practical sessions introduced me to different tools used by cybersecurity professionals to recover passwords from protected PDF documents.

I completed two practical activities. The first involved using John the Ripper (JTR) together with its graphical interface, Johnny. The second involved using NetworkWalks' online Hash Calculator and Password Cracker tools. Through these exercises, I gained practical experience in extracting password hashes, performing dictionary attacks and verifying recovered passwords.

## 2. Objectives

The main objectives of the practical sessions were to:

- Understand how password-protected PDF documents are secured.
- Learn how to extract password hashes from PDF files.
- Gain experience using John the Ripper and Johnny GUI.
- Practise password cracking using dictionary-based techniques.
- Explore NetworkWalks' online password-cracking tools.
- Understand the importance of using strong and unique passwords.

## 3. PM1 – Password Cracking Using John the Ripper and Johnny GUI

### Tools Used

- John the Ripper 1.9.0 Jumbo (Windows 64-bit)
- Johnny GUI 2.2
- Online PDF Hash Extractor (OnlineHashCrack)

**Target File:** `My Locked PDF1.pdf` (267 KB)

### Practical Activities Performed

**Step 1: Downloading and preparing the tools**

I started by downloading the provided password-protected PDF file together with John the Ripper and Johnny GUI. I prepared the tools and target document for the practical exercise.

**Step 2: Configuring Johnny GUI**

After installing and opening Johnny, I configured it to locate the John the Ripper executable. This allowed the graphical interface to communicate with the password-cracking engine.

**Step 3: Extracting the PDF hash**

I used an online PDF hash extraction tool to retrieve the password hash from the protected document. The extracted hash was required before attempting to recover the original password.

**Step 4: Loading the extracted hash**

I imported the extracted hash into Johnny GUI and confirmed that it was successfully loaded and ready for testing.

**Step 5: Performing the password-cracking attack**

I initiated the password-cracking process using the available dictionary-based approach. John the Ripper tested possible password combinations against the extracted hash until it identified a matching password.

**Step 6: Verifying the recovered password**

After the attack was completed successfully, I obtained the password `good-luck`. I then used it to open the protected PDF document and confirmed that the password was correct.

### Result

The password was successfully recovered using John the Ripper and Johnny GUI.

**Recovered Password:** `good-luck`

## 4. PM2 – Password Cracking Using NetworkWalks Online Tools

### Tools Used

- NetworkWalks Hash Calculator
- NetworkWalks Password Cracker

**Target File:** `My Locked PDF1 (for NW Tools Lab WK3-PM2).pdf` (66 KB)

### Practical Activities Performed

**Step 1: Identifying the target document**

I began by locating and confirming the PDF document provided for the second practical exercise. This document was used as the target for testing NetworkWalks' online password-cracking tools.

**Step 2: Extracting the password hash**

I accessed the NetworkWalks Hash Calculator and used it to extract the password hash from the protected PDF document. This provided the hash required for the next stage.

**Step 3: Submitting the hash for cracking**

I copied the extracted hash and pasted it into the NetworkWalks Password Cracker tool. I checked that the hash had been entered correctly before proceeding.

**Step 4: Running the password-cracking process**

I started the cracking process using the online tool. The system tested possible passwords against the supplied hash to identify the correct password.

**Step 5: Recovering the password**

The password-cracking operation completed successfully and revealed the password `good-luck`.

**Step 6: Testing the recovered password**

To confirm the result, I opened the protected PDF document and entered the recovered password. The document opened successfully, confirming that the cracking process had worked.

### Result

The NetworkWalks online tools successfully recovered the password and demonstrated how hash extraction and password testing can be performed through a web-based platform.

**Recovered Password:** `good-luck`

## 5. Skills and Knowledge Acquired

Through these practical exercises, I developed a better understanding of password security and the techniques used to assess password strength. I gained hands-on experience with John the Ripper, Johnny GUI and NetworkWalks' online security tools.

I also learned how password hashes are extracted from protected PDF files and how dictionary attacks can be used to identify weak passwords. Additionally, I improved my ability to configure security tools, manage extracted hash values and verify the results of a password-cracking exercise.

## 6. Challenges Encountered

The practical sessions required proper configuration of the cracking tools and accurate extraction of the PDF password hashes. Ensuring that the correct hash was loaded into the appropriate tool was an important part of the process. I also had to understand how the different interfaces worked before successfully initiating the attacks.

Working through these steps improved my confidence in using password-security assessment tools.

## 7. Conclusion

Week 03 provided valuable practical experience in password security assessment. I successfully completed both password-cracking exercises using John the Ripper with Johnny GUI and NetworkWalks' online Hash Calculator and Password Cracker.

Both approaches successfully recovered the password `good-luck`, and I verified the results by opening the protected PDF documents. The exercises helped me understand how weak passwords can be exposed through dictionary attacks and why individuals and organisations should use long, complex and unique passwords to protect sensitive information.

Overall, this week's activities strengthened my practical knowledge of password security, hash extraction and ethical password-cracking techniques.# B084F-W3-Networkwalks-Password-Cracking-using-NW-and-JTR

Evidence
<img width="960" height="496" alt="q4" src="https://github.com/user-attachments/assets/9ae092d0-3bdf-4fdf-886b-92d0e2bb14bb" />
<img width="956" height="408" alt="q6" src="https://github.com/user-attachments/assets/55943f90-9d8f-42ab-aa7d-db35f793a01c" />
<img width="931" height="422" alt="q8" src="https://github.com/user-attachments/assets/ba0a9239-484e-4850-81c8-8c0b5120d20b" />
<img width="729" height="401" alt="q9" src="https://github.com/user-attachments/assets/b0e55f5f-3654-4237-8b53-a0abca9ccd10" />
<img width="953" height="410" alt="q12" src="https://github.com/user-attachments/assets/bded8012-fc52-45aa-96c4-3ffe09174c11" />

