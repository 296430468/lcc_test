BUG_Author:
Lcc

Affected version:

JumpServer 社区版 GPLv3
v3.8.0

Vendor:
https://www.jumpserver.org/

Software:

https://github.com/jumpserver/jumpserver/


Description:
    Bypass command filtering in jumpserver rights management. When setting the command filtering function, columns such as eval, ls, or other commands. 
Normally, the system blocks authorized users from using these commands. However, if the asset has authorized users to save these filtered commands in a.sh script, 
such as eval ls, then execute the.sh script directly. Both commands can be executed. In this way, the command filtering function is bypassed. 
Remote commands may be executed in real situations, resulting in system security.

![image](https://github.com/296430468/lcc_test/assets/67642123/d6d4482e-d213-4750-97e1-dee4133b9201)
![image](https://github.com/296430468/lcc_test/assets/67642123/c65f9ae2-6803-4fe0-babb-c9a1b9a33062)
![image](https://github.com/296430468/lcc_test/assets/67642123/cfc7a21f-e6ce-4de0-b2b9-1b2c92a5d0d6)
![image](https://github.com/296430468/lcc_test/assets/67642123/062bc00c-cf2b-4071-8a52-85683e458455)


