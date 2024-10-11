# SWE_2021_41_2024_2_week_6
---
## Week 4 Assignment
* Link of you repository
  
> https://github.com/hecarimday/SWE_2021_41_2024_2_week_4
* Description of your code
To write this code, I first considered the cases where a number would not be a happy number. Initially, I thought that all numbers would inevitably be happy numbers, but after calculating them by hand, I realized that unhappy numbers enter an infinite loop by repeating the same digits.

Therefore, I implemented a process where the input number is taken, and the sum of the squares of its digits is calculated and stored in a set called look. This way, each time a new number is generated, I can check if it is already in the set. If it exists, I consider it to have entered an infinite loop and return False.

On the other hand, if the number reaches 1 without entering an infinite loop, it is considered a happy number, and I return True.
---
## Week 5 Assignment
> ```bash
> docker exec ossp-container cat /etc/os-release
> ```
>* Explanation of commandline and your output
>  
>>  This is a command that outputs the contents of the /etc/os-release file inside a Docker container named ossp-container, which contains the version and distribution information of the Linux operating system.
>```bash
>PRETTY_NAME="Ubuntu 24.04.1 LTS"
>NAME="Ubuntu"
>VERSION_ID="24.04"
>VERSION="24.04.1 LTS (Noble Numbat)"
>VERSION_CODENAME=noble
>ID=ubuntu
>ID_LIKE=debian
>HOME_URL="https://www.ubuntu.com/"
>SUPPORT_URL="https://help.ubuntu.com/"
>BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
>PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
>UBUNTU_CODENAME=noble
>LOGO=ubuntu-logo
>```

> ```bash
> docker exec ossp-container git --version
> ```
>* Explanation of commandline and your output
>  
>>  This is a command that checks whether Git is installed in the Docker container named ossp-container, and if it is installed, it outputs the version information.
>  
>```bash
>git version 2.43.0
>```


> ```bash
> docker exec ossp-container python3 --version
> ```
>* Explanation of commandline and your output
>  
>>  This is a command that checks whether Python 3 is installed in the Docker container named ossp-container, and if it is installed, it outputs the version information.
>  
> ```bash
> Python 3.12.3
> ```

> ```bash
> docker inspect --format="{{ .HostConfig.Binds }}" ossp-container
> ```
>* Explanation of commandline and your output
>
>> This is a command that outputs the information about the files or directories bound to the host in the Docker container named ossp-container.
> 
> ```bash
> [./ossp_host_dir:/mnt/ossp_container_dir]
> ```

