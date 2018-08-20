# ftk
script to make a simple forensic toolkit - mkftk</br>
creates a basic linux forensic toolkit based on the binary list provided by the file BINLIST</br>
[usage] mkftk BINLIST</br>

<p>
  This is just for my own learning purposes on shell scripting and Digital Forensics. Feel free to use it and modify it to your needs but if you are looking for something more suitable and sophisticated take a look into the following link <a href="http://malwarefieldguide.com/LinuxChapter1.html">Chapter 1 Malware Incident Response (as excerpted in Linux Malware Incident Response: A Practitioner's Guide to Forensic Collection and Examination of Volatile Data)<a>.
</p>
<p>
  The script creates a directory structure with ROOT as root directory and folders /bin and /lib within.<br>
  It will then copy the defined binaries to /bin and the associated dynamic link libraries to /lib.<br>
  After that it will create an iso image based on the ROOT folder and an archive file for later usage.<br>
  In addition it will calculate the md5,sha1 and sha256 hashes of the iso image and the archive file and save the values in the hashes text file.<br>
</p>
<p>
  Feel free to modify the script to your needs!
</p>
Best
