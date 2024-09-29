
# Hunt for LFI (Local File Inclusion)
Simple Automated brute force attack tool for exploiting local file inclusion, using GET requests (with special attention to CTFs and bug bounty). Designed to optimize time spent searching for injections that bypass site security and filtering.

-------
# Local File Inclusion: 
``The File Inclusion vulnerability allows an attacker to include a file, usually exploiting a “dynamic file inclusion” mechanisms implemented in the target application. The vulnerability occurs due to the use of user-supplied input without proper validation. This can lead to something as outputting the contents of the file``

- The script will use all the most commonly used techniques to bypass a filtering system or protections on the potentially vulnerable target and will show all successful payloads. If you know of an additional more effective technique, feel free to modify the code or add other payloads.



## Optionals:

`-o/--output` --> Prints the results of the exploit 

`-s/--saveToFile` --> Save the results to a file

# Warning:    
> I am not responsible for any illegal use or damage caused by this tool. It was written for fun, not evil and is intended to raise awareness about cybersecurity
