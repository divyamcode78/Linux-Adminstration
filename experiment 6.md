Experiment-6 Create the operator1 user and confirm that it exists in the system. Set the password for operator1. Create the additional operator2 and operator3 users.

Set their passwords as well. Run the usermod -c command to update the comments of the operator1 user account. Remove the operator3 user from the system.

Approach- Create the operator1, operator2, and operator3 users, set their passwords, and confirm their existence. Update operator1’s comment using usermod -c, then remove operator3 from the system.

![image](https://github.com/user-attachments/assets/849a639d-5029-4d26-9fe3-69d33a63a2c5)
![image](https://github.com/user-attachments/assets/ab6ade9c-cc3b-403d-855c-84ada86b2884)

Commands used: useradd operator1, passwd operator1, useradd operator2, passwd operator2, useradd operator3,passwd operator3, usermod -c "" operator1, userdel operator3


