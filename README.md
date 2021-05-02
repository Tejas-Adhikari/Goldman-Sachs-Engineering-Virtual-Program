# Goldman-Sachs-Engineering-Virtual-Program
This is a Goldman Sachs Engineering Virtual Program for Cracking leaked password database
<!-- PROJECT LOGO -->
<br />


  <h3 align="center">Cracking leaked password database</h3>

  <p align="center">
    This is a Goldman Sachs Engineering Virtual Program for Cracking leaked password database. :bowtie:
    <br />
    <a href="https://hashcat.net/hashcat/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents :closed_book:</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

![picture-5](https://res.cloudinary.com/tejas2298/image/upload/v1619969392/Goldman%20sachs%20crack%20password/goldman_sachs_crack_password_eq6es7.png)

This is a Goldman Sachs Engineering Virtual Program for Cracking leaked password database
Following questions were asked for the completion of task:
:large_blue_diamond: What type of hashing algorithm was used to protect passwords?\
:large_blue_diamond: What level of protection does the mechanism offer for passwords?\
:large_blue_diamond: What controls could be implemented to make cracking much harder for the hacker in the event of a password database leaking again?\
:large_blue_diamond: What can you tell about the organization’s password policy (e.g. password length, key space, etc.)?\
:large_blue_diamond: What would you change in the password policy to make breaking the passwords harder?\


<!-- GETTING STARTED -->

## Getting Started



### Prerequisites

Software requirements:

:large_blue_diamond: ['Kali linux'](https://www.kali.org/downloads/)\
:large_blue_diamond: Hashcat(Pre-installed in Kali linux)

For more instructions on Installing the above, This ['Youtube-video'](https://www.youtube.com/watch?v=r0IZ3P4YriE&ab_channel=TechGeeks) might be helpful.\
Also, these websites will guide you in executing commands.\
1.  ['Website-1'](https://hackingvision.com/2020/03/22/cracking-password-hashes-hashcat/).
2.  ['Website-2'](https://resources.infosecinstitute.com/topic/hashcat-tutorial-beginners/).

<!-- USAGE EXAMPLES -->

## Usage

1. Type the following command in the terminal of kali linux
:large_blue_diamond: hashcat --help
2.  locate rockyou.txt.gz, and hashes.txt and paste them in a single folder.
3.  After copying both the files(rockyou.txt.gz and hashes.txt) go to that folder by executing cd command in the terminal.
4.  Execute the following command to generate the passwords in a text file.
:large_blue_diamond: hashcat -m 0 hashes.txt -o passwords1.txt rockyou.txt
5. If the command is properly executed a passwords1.txt file will be created in the folder where both(rockyou.txt.gz and hashesh.txt) files are saved.
  
<!-- CONTACT -->

## Contact

Name - Tejas Adhikari\
Email - tejas.adhikari@somaiya.edu / adhikari.tejas3@gmail.com\
LinkedIN Profile- [![LinkedIn][linkedin-shield]][linkedin-url]

Project Link: [https://github.com/Tejas-Adhikari/Goldman-Sachs-Engineering-Virtual-Program.git)

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/tejas-adhikari-4ba530168/
