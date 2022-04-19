---
layout: post
title: "Lab Report 1"
date: 2021-04-18
categories: jekyll blogging
---

This week we covered the following concepts:

* Installing VScode
* Remotely Connecting
* Trying Some Commands
* Moving Files with scp
* Setting an SSH Key
* Optimizing Remote Running

# Installing VS Code

<img width="1780" alt="Screen Shot 2022-04-18 at 11 48 00 PM" src="https://user-images.githubusercontent.com/65497162/163942683-9ca2cd1e-751c-4464-a0f4-8da1687a1949.png">

We begin by using this [link](https://code.visualstudio.com/download). Download the mac version and proceed to follow the installation instructions.

Once done, you should get the following screen once the application is opened. It won't look exactly like this, but do explore and play around with the settings. Unlike old text editors like Vim which require PlugIns using a text file, installing extensions (added features contributors made) are as easy as clicking a button! 

<img width="1792" alt="Screen Shot 2022-04-19 at 12 04 02 AM" src="https://user-images.githubusercontent.com/65497162/163945182-74ad528a-2bf6-4f7c-bce8-00802bbd5d7a.png">

The specific one shown above has a custom colour scheme and a vim mode extension.

# Remotely Connecting

Open up a terminal session by clicking Terminal -> New Terminal:

<img width="1792" alt="Screen Shot 2022-04-19 at 12 41 53 AM" src="https://user-images.githubusercontent.com/65497162/163951510-823e7b2a-cb39-4ca1-ba24-4ff2409a1993.png">

To ssh into another computer, all we need is to invoke the client via the ssh command, followed by an argument in the form of *username@hostname*, as demonstrated below:

<img width="1792" alt="Screen Shot 2022-04-19 at 12 58 00 AM" src="https://user-images.githubusercontent.com/65497162/163954374-68a4ece2-bebc-4a24-8f8a-bf2d34d7877b.png">

# Trying Some Commands

Some common programs include netstat, ping and ifconfig.

## Trying netstat:

<img width="1563" alt="Screen Shot 2022-04-19 at 1 07 20 AM" src="https://user-images.githubusercontent.com/65497162/163955957-a51454aa-0614-4115-b8b3-99c4b2d45bf9.png">

## Trying ping:

<img width="1567" alt="Screen Shot 2022-04-19 at 1 06 42 AM" src="https://user-images.githubusercontent.com/65497162/163955858-00eef572-4524-4ffd-8bdf-b03dde45c378.png">

## Trying ifconfig:

<img width="1792" alt="Screen Shot 2022-04-19 at 1 05 08 AM" src="https://user-images.githubusercontent.com/65497162/163955571-777fe6fb-e1c6-43d8-a712-332306859309.png">


# Moving Files with scp

The secure copy command allows for secure duplicating of files from one computer to another. The command is scp followed by the file to be copied, followed by an argument in the form of *username@hostname* again:

![Screen Shot 2022-04-19 at 1 22 16 AM](https://user-images.githubusercontent.com/65497162/163958687-17c572cf-a98a-4b0c-8b8d-a240a7a161d3.png)


# Setting an SSH Key

Since inputing our password everytime we ssh can be annoying, we can use the ssh-keygen command. This generates a public and private key which are saved on the remote computer (which we ssh into) and the client computer (that is us!) respectively. Here are the relevant commands:

![Screen Shot 2022-04-19 at 1 46 00 AM](https://user-images.githubusercontent.com/65497162/163963057-fa895706-6305-4335-a7e4-c09eceae6abc.png)


# Optimizing Remote Running

