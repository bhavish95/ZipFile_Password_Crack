# ZipFile_Password_Crack

![img2](https://github.com/bhavish95/ZipFile_Password_Crack/assets/111994995/aece2ace-6e85-4480-b81a-150b45e21075)

# Objective- Crack the password of attached file using John the Ripper(just like Fcrackzip) : a) using automatic password generation b) using word dictionary.

# John the Ripper
John the Ripper, often abbreviated as "John," is a widely used open-source password cracking software program. Its primary purpose is to help system administrators and security professionals test the strength of passwords on a system by attempting to crack them. John the Ripper is designed to work with various password hash algorithms and is known for its speed and efficiency in cracking passwords.

#  features of John the Ripper

**1.Password Hash Support:** It can handle various password hash formats, including Unix-based password hashes (e.g., DES, MD5, SHA-1, and SHA-256), Windows LM and NTLM hashes, and more.

**2.Wordlist and Rules:** John the Ripper uses wordlists and rulesets to generate potential password candidates for cracking. You can customize these lists and rules to improve the cracking process.

**3.Performance Optimization:** It's optimized for speed and can take advantage of multiple CPU cores and SIMD (Single Instruction, Multiple Data) instructions to accelerate the cracking process.

**4.Community Support:** Being open-source, John the Ripper has a community of users and developers who contribute to its ongoing development and maintenance.

# Requirements To Perform Password Crack
**1.Operating System:** John the Ripper is compatible with various operating systems, including Linux, Unix, Windows, and macOS. You'll need a compatible system to run it.

**2.Installation:** You'll need to install John the Ripper on your system. Installation methods can vary depending on your operating system. You can often find installation instructions and packages on the official John the Ripper website or through package managers.

**3.Access Permissions:** Depending on your system's configuration, you might need administrative or root access to perform password cracking, especially if you're working with system password hashes.

**4.Wordlists:** John the Ripper relies on wordlists to generate potential password candidates. You'll need to have access to one or more wordlists, which can be customized to suit your needs. Some common wordlists include "rockyou.txt" and "common_passwords.txt," but you can create your own or find others online.

**5.Rulesets:** To enhance the cracking process, John the Ripper can use rulesets to apply transformations to wordlist entries. You can create custom rulesets or use existing ones to increase your chances of cracking passwords.

**6.Password Hashes:** You'll need access to the password hashes you want to crack. These can be obtained from various sources, such as password dumps, system configuration files, or through legitimate security testing.

**7.Ethical and Legal Considerations:** Ensure you have proper authorization to use John the Ripper on the target system. Unauthorized password cracking is illegal and unethical. It's important to use this tool for legitimate security testing, such as auditing the security of your own systems or systems for which you have explicit permission.

**8.Documentation and Resources:** Familiarize yourself with the official documentation and resources available for John the Ripper. Understanding how to use the tool effectively and responsibly is crucial.

**9.Security Awareness:** Password cracking tools like John the Ripper can potentially expose sensitive information. Exercise caution and handle any cracked passwords or data responsibly and securely.

# Hands-On

**Step 1-** first we store the zip file in linux Vm. Then by using zip2john we canvert zip file into hash.txt

![image](https://github.com/bhavish95/ZipFile_Password_Crack/assets/111994995/b926f4fe-4983-4aa2-938b-bf820b161a1f)

**Step2-** now we can use john hash1.txt file to crack them

![image](https://github.com/bhavish95/ZipFile_Password_Crack/assets/111994995/fd2220b1-5f14-4336-abd7-04c288079663)
![image](https://github.com/bhavish95/ZipFile_Password_Crack/assets/111994995/28cadd79-3276-4ac4-988c-85726eab4356)
![image](https://github.com/bhavish95/ZipFile_Password_Crack/assets/111994995/c83d6590-f0de-43bf-aac8-59f28ca635f9)
![image](https://github.com/bhavish95/ZipFile_Password_Crack/assets/111994995/593cbbf4-4c63-4f4d-a1cf-d0ccdc38d700)

**Finally we get the Password of the Zipfile = CSF446**
