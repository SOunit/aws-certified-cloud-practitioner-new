# security group

- is firewall to EC2 instance

  - check inbound / outbound connection

- sample
  - access to EC2 from local
    - inbound
      - check IP address
    - outbound
      - any response is ok by default

# good to know

- can be attached to multiple instances
- belongs to region / VPC
  - when switch to another region, you have to create security group
- security group is OUTSIDE of EC2 instance
- recommended to create 1 separate security group for SSH
  - SSH is complex and recommended to separate
- if access is timeout, it's security group issue
- connection refused, application error or not launched
- all inbound traffic is blocked by default
- all outbound traffic is allowed by default

# classic port

- 22
  - SSH(Secure SHell)
- 21
  - FTP(File Transfer Protocol)
- 22
  - SFTP(Secure File Transfer Protocol)
- 80
  - HTTP
- 443
  - HTTPS
- 3389
  - RDP(Remote Desktop Protocol)
    - log into a Window instance
