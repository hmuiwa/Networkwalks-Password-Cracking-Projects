# Networkwalks-Password-Cracking-Projects
# Module 1: Password Cracking with John the Ripper (JTR)

## Introduction

This practical exercise focused on using John the Ripper (JTR) and Johnny GUI to recover the password of a password-protected PDF document. I learned how to extract a PDF hash, save it in a text file, load it into Johnny, and perform a password-cracking attack.

## Tools Used

- John the Ripper
- Johnny GUI
- Online PDF Hash Extractor
- Notepad
- Windows PC / Kali Linux

## Practical Steps

1. Downloaded and installed John the Ripper.
2. Downloaded and installed Johnny GUI.
3. Configured Johnny to use the `john.exe` executable.
4. Downloaded the password-protected PDF file.
5. Extracted the PDF hash using an online hash extractor.
6. Copied the complete hash into Notepad and saved it as `hash1.txt`.
7. Opened Johnny and loaded the hash file.
8. Started a new password-cracking attack.
9. Retrieved the recovered password.
10. Used the password to open the protected PDF and verify the result.

## Challenges and How I Resolved Them

One challenge was extracting the correct PDF hash and ensuring that it was saved in the required format. I also had to configure Johnny correctly by locating the `john.exe` file in the John the Ripper installation directory. I resolved these issues by carefully checking the hash format and verifying the executable path before starting the attack.

## Conclusion

This exercise introduced me to John the Ripper and Johnny GUI as practical password security testing tools. I gained experience extracting PDF hashes, configuring cracking software, and recovering passwords. It also demonstrated the importance of using strong passwords to protect sensitive documents.



# Module 2: Password Cracking with Networkwalks Tools

## Introduction

This practical exercise involved recovering the password of an encrypted PDF document using Networkwalks online Hash Calculator and Password Cracker. The main objective was to understand how a password hash can be extracted from a protected PDF and used in a password-cracking process.

## Tools Used

- Networkwalks Hash Calculator
- Networkwalks Password Cracker
- Web Browser
- Windows PC / Kali Linux

## Practical Steps

1. Downloaded the encrypted PDF file named `My Locked PDF1.pdf`.
2. Opened the Networkwalks Hash Calculator.
3. Uploaded the protected PDF to extract its hash.
4. Copied the complete hash beginning with `$pdf$`.
5. Opened the Networkwalks Password Cracker.
6. Pasted the extracted hash and initiated the attack.
7. Waited for the tool to recover the password.
8. Used the recovered password to open the original PDF.
9. Verified that the document opened successfully.

## Challenges and How I Resolved Them

The main challenge was ensuring that the complete PDF hash was copied correctly. Since the hash contains several characters, missing part of it could affect the cracking process. I resolved this by carefully copying the entire hash, including the `$pdf$` prefix, before submitting it to the Password Cracker.

## Conclusion

This exercise provided practical exposure to browser-based password-cracking tools. I learned how to extract a PDF hash, submit it for password recovery, and verify the recovered password. The exercise reinforced the importance of strong and unique passwords in protecting sensitive information.
