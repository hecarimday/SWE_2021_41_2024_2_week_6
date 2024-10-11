# SWE_2021_41_2024_2_week_6
---
## Week 4 Assignment
* Link of you repository
  
> https://github.com/hecarimday/SWE_2021_41_2024_2_week_4
* Description of your code 
---
## Week 5 Assignment
> ```bash
> docker exec ossp-container cat /etc/os-release
> ```
>* Explanation of commandline and your output
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
>```bash
>git version 2.43.0
>```


> ```bash
> docker exec ossp-container python3 --version
> ```
>* Explanation of commandline and your output
> ```bash
> Python 3.12.3
> ```

> ```bash
> docker inspect --format="{{ .HostConfig.Binds }}" ossp-container
> ```
>* Explanation of commandline and your output
> ```bash
> [./ossp_host_dir:/mnt/ossp_container_dir]
> ```
