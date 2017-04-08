# aws\\\


您的密钥必须不公开可见，SSH 才能工作。如果需要，请使用此命令：
chmod 400 free.pem
通过其 公有 DNS 连接到您的实例:
ec2-54-202-43-181.us-west-2.compute.amazonaws.com
示例：
ssh -i "free.pem" ec2-user@ec2-54-202-43-181.us-west-2.compute.amazonaws.com


