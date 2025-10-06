Problem Statement

1) Kernel died issue
Solution: I suggest to uninstall the anaconda and install miniconda. This is the only way to solve Kernel died issue.
<img width="1285" height="417" alt="image" src="https://github.com/user-attachments/assets/217fd132-ee72-4d31-ae85-7f969bf0fff0" />

- recommend install miniconda instead of anaconda. Miniconda does not come with a large set of pre-installed packages.

2) mat1 and mat2 cannot be multiplied
<img width="940" height="121" alt="image" src="https://github.com/user-attachments/assets/50f471f1-e1a2-4413-a9d1-b41ec5e723c7" />
definition:
<img width="874" height="142" alt="image" src="https://github.com/user-attachments/assets/de5a78c2-935f-4715-becb-8128654c4a79" />
Start_dim = 0 was an error. It should start from 1. This is because 0 is 32 but we want to start from 1 to 3 (3, 32, 32).
<img width="916" height="308" alt="image" src="https://github.com/user-attachments/assets/dde6cef7-9470-4c00-bff5-132bf123775e" />



Solution:
Change the Start_dim to 1

<img width="940" height="216" alt="image" src="https://github.com/user-attachments/assets/2c444545-536e-4a47-afe6-87ba1e7b3954" />






