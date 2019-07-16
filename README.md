# update-linux-server
Script for Linux server batch update

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Prerequisites](#prerequisites)
* [Usage](#usage)
* [Acknowledgements](#acknowledgements)

<!-- ABOUT THE PROJECT -->
## About The Project

Sometimes I need to update several Linux server at once and the server using various OS type. Following script simplify this process by using a small script to automate the processexample steps.

## Prerequisites

* Set password-less ssh login (or by using public key) for each server
* Copy linux-update.sh to each server (script using /srv/vavai for example path)
* Fill in list-server.txt with list of server name or IP

<!-- USAGE EXAMPLES -->
## Usage

```
./update-all-server.sh
```

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* https://serverfault.com/questions/3331/how-do-i-find-out-what-version-of-linux-is-running




