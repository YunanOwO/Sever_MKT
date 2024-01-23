# Server_MKT

## Introduction

This document provides an overview of the Server_MKT specifications and guidelines for accessing and utilizing the software and resources available.

### Specifications

| Component        |                                                      Details |
| ---------------- | -----------------------------------------------------------: |
| Operating System |                                           Ubuntu 22.04.3 LTS |
| RAM              |                                                   257 GB RAM |
| CPU              | Intel® Xeon® Gold 6348 CPU @ 2.60GHz<br>28 cores per socket, 2 sockets, supporting 112 threads |
| Storage          |         `/dev/sdb1/disk1`: 15 TB<br>`/dev/sda1/disk2`: 15 TB |
| GPU              |                                  2 x NVIDIA GeForce RTX 3090 |

## How to Get Access

**Note:** Access to the server requires connection to the school's wired network and the use of a computer registered with the school.

To obtain access credentials, please fill out the form provided by the administrator.

Form Link: [Insert Link Here]

## Software

The server provides a suite of software for various computing needs.

### Python

#### Basic

**Jupyterhub** is the recommended and most user-friendly platform for running Python files. Access it using the link below with the credentials obtained from the administrator. First-time login will prompt the creation of a user-defined password.

[Log in to Jupyterhub](http://137.189.75.142/hub/login)

#### Advanced Usage

**Command Line:**

Python can be run from the command line using Jupyterhub's terminal or by connecting to the server via SSH.

SSH into the server using the provided admin credentials: `ssh -[username]@http://137.189.75.142`, then enter your password.

To use Python in console mode, enter:

```bash
python
```

To run a Python script, use:

```
bashCopy code
python file_path
```

##### For Long Duration Tasks

- Utilize the `screen` command in Linux. Note that processes running for more than 24 hours on login nodes may be terminated.

### R

#### Basic

**Jupyterhub** also serves as the recommended platform for running R scripts with similar access procedures as for Python.

[Log in to Jupyterhub](http://137.189.75.142/hub/login)

#### Advanced Usage

**Browser:**

For those who prefer the RStudio interface to Jupyterhub, access it using the system account through the following link:

[Log in to RStudio](http://137.189.75.142:8787/)

**Command Line:**

Alternatively, use SSH and launch R in console mode with:

```
R
```

Run R in batch mode:

```
Rscript file_path
```

### MATLAB

#### Basic

**Jupyterhub** supports MATLAB. Log in using the link below to create a new MATLAB kernel or reference it within a Python file.

[Log in to MATLAB](http://137.189.75.142/hub/login)

#### Advanced Usage

**Command Line:**

Use SSH and launch MATLAB in console mode with:

```
bashCopy code
matlab
```

To run your `.m` files:

```
bashCopy code
matlab -r "run('path/to/your_script.m')"
```



### Visual Guides

Below are the visual guides to assist with logging in and using the server's software interfaces:

**JupyterHub Login Interface:**

![截屏2024-01-23 11.37.31](JupyterHub Login.png)

**Creating or Switching Kernels in JupyterHub:**

![截屏2024-01-23 13.01.40](Switching Kernels.png)

**RStudio Login Interface:**

![RStudio Login](RStudio Login.png)

## Questions and Issues

For any server or software-related queries or issues, please utilize the GitHub Issues interface on [this page](https://github.com/YunanOwO/Sever_MKT/issues). You can search for existing issues to find answers or create new ones to post your questions. This approach helps in efficiently tracking and resolving any problems or inquiries.
