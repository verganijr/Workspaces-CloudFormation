# Workspaces-CloudFormation

### The main goal of this project is to provision a workspace to a AWS Directory Services user (AD Connector or Managed AD).

#### This template requires to fill the parameters below:

#### - WorkSpace Bundle (Bundle identification)
#### - WorkSpace Directory (AD Connector or Managed AD DirectoryId)
#### - WorkSpace Owner (login user of this domain)
#### - Root Volume Encryption Enabled (True ou False)
#### - User Volume Encryption Enabled (True ou False)
#### - Encryption Key Arn (Encryption key ARN to be used to encrypt Root Volume and/or User Volume)
#### - Running Mode (ALWAYS_ON ou AUTO_STOP) 
