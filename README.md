# dirb

Dirb is a command line based tool to brute force any directory based on wordlists. It looks for existing (and/or hidden) Web Objects. It basically works by launching a dictionary-based attack against a web server and analyzing the response. DIRB main purpose is to help in professional web application auditing. It works by launching a dictionary based attack against a web server and analysing the HTTP request and see the HTTP response code of each request.

The tool “Dirb” is in-built in Kali Linux, therefore, Open the terminal and type following command to start brute force directory attack.

# Using Dirb:

Step 1 — Open Terminal

Step 2 — Start Dirb

Once we have a terminal open, go ahead and type dirb to get the help screen.

     Kali:-  dirb
     
![pasted image 0](https://user-images.githubusercontent.com/106522935/202938340-977c2e6b-bdb0-438b-bd4b-3baf766efcfe.png)

Testing for Special Vulnerable list

We can use DIRB to test for specific vulnerable objects within specific types of web technologies. Each web technology has different vulnerabilities. They are NOT all the same. DIRB can help us look for specific vulnerable objects specific to the particular technology.

In terminal:

     cd /usr/share/wordlists/dirb

     ls –la

     cd  vulns/

     ls -la
     
![pasted image 0 (1)](https://user-images.githubusercontent.com/106522935/202938483-8e885c8d-f486-4b3a-bf76-50721b45e4fd.png)

Using the common.txt file, the DIRB returns the enumerated directories found within the target URL .
