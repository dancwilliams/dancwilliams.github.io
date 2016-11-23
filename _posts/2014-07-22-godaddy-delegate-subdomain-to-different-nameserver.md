---
layout: post
title: Cisco IOS SSL VPN with AD/RADIUS Authentication
excerpt_separator: <!--more-->
--- 

1.  Access your GoDaddy domain manager
2.  Select your domain
3.  Select the “DNS Zone File” Tab
4.  Select “Add Record”
<!--more-->
5.  Create a new “Nameserver” entry. See capture below. The “host” will be you’re the subdomain you want to point. Use the proper nameserver naming format or GoDaddy will kick an error.[![5](/images/5.png)]
6.  If you do not have a FQDN for your nameserver you will want to create an A record pointing to its IP:[![6](/images/6.png)]

### THANKS!

I would like to that [Glen Kemp](https://twitter.com/ssl_boy) who began discussing this topic with me. I thought I should put this up even though GoDaddy clearly supports this procedure in their [Support Forums](http://support.godaddy.com/help/article/680/managing-dns-for-your-domain-names?pc_split_value=4).
