# Debian Server Installation

### Hello World

<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/ddea0f07-cd9c-48b4-8f05-68bc7763f766" />

In this repository, you'll learn how to properly set up and install your own Debian Server on your VM, Debian is one of the most popular Linux Distro used widely for daily task and also can perform as a server OS.

### Prerequisite
1. Debian 13.6.0 NetInstaller
2. VMWare Workstation Full 26H1


## Installation Guide

### Step 1

<img width="1362" height="737" alt="image" src="https://github.com/user-attachments/assets/73764bc5-3314-441c-ac4c-c50ace730c52" />

Open your VMWare then select `Create a New Virtual Machine`

### Step 2

<img width="432" height="429" alt="image" src="https://github.com/user-attachments/assets/52676cd4-6209-4d02-b3f1-be3cf1c4359f" />

In this section I recommend you to choose the default option `Typical (Recommended)`

### Step 3

<img width="427" height="430" alt="image" src="https://github.com/user-attachments/assets/b7a79d63-5980-4a5d-a0b0-cc66ce371672" />

Tap `Browse` and locate your downloaded Debian ISO file then choose it, after that proceed to next step.

### Step 4

<img width="423" height="432" alt="image" src="https://github.com/user-attachments/assets/c9d8b009-64ec-4d9d-bb8b-0eedaee25762" />

You can configure your VM name here and choose desired location for the VM file, I recommend to set the location for the file to default.

### Step 5

<img width="427" height="428" alt="image" src="https://github.com/user-attachments/assets/d65f51ba-2689-45c4-8932-c907ab6722e6" />

Configure your disk size here, the minimum requirements is 20GB of Disk Storage and check the box `Store virtual disk as a single file`

### Step 6

<img width="431" height="432" alt="image" src="https://github.com/user-attachments/assets/876d5f5c-e10e-40a2-9ba7-99f2c9f67cd2" />

Tap `Customize Hardware`

### Step 7

<img width="414" height="405" alt="image" src="https://github.com/user-attachments/assets/00e6b4c6-2647-420e-93f0-ee2579e15f14" />
<img width="411" height="198" alt="image" src="https://github.com/user-attachments/assets/1a2221fa-84ee-43b8-bead-d237f7587333" />
<img width="418" height="329" alt="image" src="https://github.com/user-attachments/assets/9d2205a0-161c-4141-9565-07d7ad737ee8" />

- Minimum RAM is 1.5GB
- Minimum Processor is 1 and 1 Core each
- Network Adapter set to NAT
- Check the box `Virtualize Intel VT-X/EPT or AMD-V/RVI`

Then choose finish, after that the machine will be powered on and you can continue to the next step.

## Configuring The OS

### Step 1

<img width="1366" height="734" alt="image" src="https://github.com/user-attachments/assets/ea92a746-b246-4a8f-b4cf-5e0d195be406" />

Choose `GUI Install` or `Install` for CLI, for now i'll be using CLI Install because we doesn't need a GUI Interface for Debian Server.

### Step 2

<img width="1366" height="739" alt="image" src="https://github.com/user-attachments/assets/512c5dc8-26dc-4312-8db4-f9acf940298a" />

Choose you own desired language, I prefer `English`

### Step 3

<img width="1363" height="739" alt="image" src="https://github.com/user-attachments/assets/da262b0a-878a-4eb8-8564-b5a39162671c" />

Choose your country.

### Step 4

<img width="1366" height="736" alt="image" src="https://github.com/user-attachments/assets/44e6f8a8-bed4-4d74-8562-4e4b00b31a99" />

For Locale, I'd be use `en_US.UTF-8` (Default).

### Step 5

<img width="1366" height="728" alt="image" src="https://github.com/user-attachments/assets/fa15309d-7a28-49c8-83c9-5f147362595a" />

Keyboard Keymap choose `American English` for default.

### Step 6






