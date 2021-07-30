# Workspaces-CloudFormation

### Esse projeto tem por objetivo provisionar uma workspace para um usuário Windows disponível via AWS Directory Services (AD Connector ou Managed AD).

### O template solicita o preenchimento das seguintes informações:

### - WorkSpace Bundle (Identificação do Bundle)
### - WorkSpace Directory (DirectoryId do AD Connector ou Managed AD)
### - WorkSpace Owner (usuário pertencente a esse domínio)
### - Root Volume Encryption Enabled (True ou False)
### - User Volume Encryption Enabled (True ou False)
### - Encryption Key Arn (ARN da encryption key que se deseja utilizar para encriptar o Root Volume e/ou User Volume)
### - Running Mode (ALWAYS_ON ou AUTO_STOP) 
