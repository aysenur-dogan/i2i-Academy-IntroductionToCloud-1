# i2i-Academy-IntroductionToCloud-1

# Introduction to Cloud - Homework 1

This repository contains my solution for the Introduction to Cloud homework.

## Objective

The goal of this homework was to:

- Create a Virtual Machine on Google Cloud Platform
- Verify connectivity using Ping
- Connect to the VM using SSH
- Create a file named `hello.txt`
- Verify the file contents

## VM Instance

A Debian Virtual Machine was successfully created.

![VM Instance](images/vm-instance.png)

## Ping Test

The VM public IP address was successfully reached from the local machine.

![Ping Test](images/ping-test.png)

## SSH Connection

Connected to the VM using SSH.

Commands executed:

```bash
echo "Hello i2i Academy!" > hello.txt
cat hello.txt
```

![SSH Connection](images/ssh-hello.png)

## Result

The virtual machine was successfully created and accessed remotely. The required file was created and verified successfully.
