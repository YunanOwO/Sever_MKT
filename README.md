# Sever_MKT

## **Introduction**

**Operating System** 

- Ubuntu 22.04.3 LTS, codenamed "Jammy Jellyfish."

**Memory**

- 257 GB RAM.

**CPU**

- Intel® Xeon® Gold 6348 CPU @ 2.60GHz.
- 28 cores per socket, 2 sockets, supporting 112 threads.

**Storage**

- `/dev/mapper/ubuntu--vg-ubuntu--lv`: Total capacity of 463 GB (281 GB used, 162 GB available).
- `/dev/nvme0n1p2`: Total capacity of 2.0 GB.
- `/dev/nvme0n1p1`: Total capacity of 1.1 GB.
- `/dev/sdb1`: Total capacity of 15 TB (12 TB used).
- `/dev/sda1`: Total capacity of 15 TB (154 GB used).

**GPU**

- Two NVIDIA GeForce RTX 3090 graphics cards.

**JupyterHub**

- JupyterHub installed on the server for managing multiple user Jupyter Notebook instances.

**Ubuntu system**

For a guide on common commands and operations in the Ubuntu system, you can refer to [this guide on Linux commands](https://scrp.econ.cuhk.edu.hk/guide/linux). This link provides additional resources and information that may be helpful for users new to the Ubuntu environment.



## **How to get access**

- **Requesting a Server Account**: To apply for a server account, you need to provide your name and email to the administrator. The format for the usernames will be `[name]-mkt-2`, so ensure to follow this format when submitting your details for account creation.
- **Accessing <u>Storage Space</u>**: After your account is created, you can log in to your allocated storage space (default is 1TB) using SSH. The command for this is `ssh -[username]@http://137.189.75.142`, where you should replace `[username]` with your specific username that follows the `[name]-mkt-2` format.

### **Software**

#### Python:

- **Using Jupyter Notebook for Python**: You can run your Python files through Jupyter Notebook. 
- To get access, submit your requirements to the administrator. They will create a JupyterHub account for you with the username format `[name]-mkt-nb`.
- **Accessing <u>JupyterHub</u>**: Access JupyterHub by entering `http://137.189.75.142` in your local browser. Log in using the provided username and create your own password. Once logged in, you'll be able to use Jupyter Notebook for your Python projects.
- For Long Duration running, use the Linux **screen**. 

#### R:

- **Accessing <u>R Studio</u>**: To use R, enter `http://137.189.75.142:8787` in your browser.
- Log in to R Studio using your existing system account credentials, formatted as `[name]-mkt-2`, along with your password.



## Questions and Issues

For any server or software-related queries or issues, please utilize the GitHub Issues interface on [this page](https://github.com/YunanOwO/Sever_MKT/issues). You can search for existing issues to find answers or create new ones to post your questions. This approach helps in efficiently tracking and resolving any problems or inquiries.