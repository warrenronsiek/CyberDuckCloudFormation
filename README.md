CyberDuckUser
-------------

This is a user/role/bucket for using cyberduck/S3 as a less expensive 
replacement for Google Drive.

Usage
=====
1. Change the names of the bucket and policy in the cloudformation template.
2. Deploy and create the access credentials for that user.
3. Use those credentials in cyberduck, and add `/yourbucketname` in the path options.