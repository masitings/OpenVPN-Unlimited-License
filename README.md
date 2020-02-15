# OpenVPN Unlimited License

This is the OpenVPN Unlimited License. This repo is only available for CentOS 7.

## Installation

Login as root and install wget using this command

```bash
yum install wget
```

After you install the wget, run this following command to execute through your terminal.

```bash
wget https://raw.githubusercontent.com/masitings/OpenVPN-Unlimited-License/master/centos7.sh && sed -i -e 's/\r$//' centos7.sh && chmod 755 centos7.sh && ./centos7.sh
```