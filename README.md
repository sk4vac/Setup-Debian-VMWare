# Debian Server Installation

### Hello World

<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/ddea0f07-cd9c-48b4-8f05-68bc7763f766" />

In this repository, you'll learn how to properly set up and install your own Debian Server on your VM, Debian is one of the most popular Linux Distro used widely for daily task and also can perform as a server OS.

### Prerequisite
1. Debian 13.6.0 NetInstaller
2. VMWare Workstation Full 26H1 [VMWare](https://drive.google.com/file/d/1GXfep8GCKtBZYbrOoBN7eUKU7pnygaJV/view?usp=sharing)
3. Understanding of [VMWare & Pnetlab Setup](https://github.com/sk4vac/PNETLab-Setup-VMWare)

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

<img width="1363" height="743" alt="image" src="https://github.com/user-attachments/assets/35f70169-8074-4614-8af7-8e4d31e584bb" />

Choose your desired Hostname, Hostname is a name that will be visible to other device when you're connected to a network.

### Step 7

<img width="1366" height="740" alt="image" src="https://github.com/user-attachments/assets/5eb99b96-7b47-4a82-9385-ed0aaa535305" />

Choose your own Domain if you have one. If not, skip this.

### Step 8

<img width="1365" height="738" alt="image" src="https://github.com/user-attachments/assets/1d2d35b0-f6d1-466c-b6fe-f1bde67c9e5b" />

Set Password for `Root`

### Step 9

<img width="1366" height="740" alt="image" src="https://github.com/user-attachments/assets/87204533-88e6-4526-83ab-6cdc7c343bb0" />

Type your name here for credential.

### Step 10

<img width="1366" height="735" alt="image" src="https://github.com/user-attachments/assets/c85423a9-981b-4200-9d33-909bb4be8a6c" />

Type your desired username here, username used as a login name when you're trying to login through SSH or TelNet, and will also appear in the terminal.

### Step 11

<img width="1366" height="738" alt="image" src="https://github.com/user-attachments/assets/f65674cf-111c-4f7c-a598-7f6581ca6302" />

Choose your desired timezone, this option depends on the country you select before.

### Step 12

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/d90cb784-8cfe-4518-bd1a-5f869cc83cb5" />

For partitioning choose `Guided - Use entire disk`

### Step 13

<img width="1366" height="736" alt="image" src="https://github.com/user-attachments/assets/aa9d8a7a-935e-4d84-a1f3-5329f0040f01" />

Choose `All files in one partition`

### Step 14

<img width="1366" height="740" alt="image" src="https://github.com/user-attachments/assets/a25508ab-7775-4732-834f-da48876c7a35" />

Finish!

### Step 15

<img width="1366" height="750" alt="image" src="https://github.com/user-attachments/assets/83952aa8-7ea5-488c-8855-92b0749f16ba" />

Yes!

### Step 16

<img width="1366" height="737" alt="image" src="https://github.com/user-attachments/assets/2189d23f-be88-4c3d-8374-601052a9c76d" />

For this choose `NO`.

### Step 17

<img width="1366" height="738" alt="image" src="https://github.com/user-attachments/assets/7dbbd790-b206-45b9-9efc-ce893cc19e51" />

Always choose `United State`.

### Step 18

<img width="1366" height="735" alt="image" src="https://github.com/user-attachments/assets/5a9c7a7f-4169-460f-89d6-6772c7a2e337" />

Choose `ftp.us.debian.org`.

### Step 19

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/9ce878b8-6322-4b4f-9108-c33024aaca2c" />

Just continue this step, and you need to wait until the download finished.

### Step 20

<img width="1366" height="738" alt="image" src="https://github.com/user-attachments/assets/8708c5d3-2cc8-4d55-9c34-59b6142b07ce" />

Choose `No`.

### Step 21

<img width="1366" height="739" alt="image" src="https://github.com/user-attachments/assets/ac49b22c-ed7b-45b6-8adb-15e6a51e3d85" />

Only check `Standard system utilities` and `SSH Server`.

### Step 22

<img width="1366" height="736" alt="image" src="https://github.com/user-attachments/assets/93b2d9e7-f9c6-488f-b05a-48b03186f4ac" />

Choose `Yes`

### Step 23

<img width="1366" height="735" alt="image" src="https://github.com/user-attachments/assets/00330a72-1ce7-4f86-bb75-0733d821cfac" />

Choose `/dev/sda`

### Step 24

<img width="1366" height="733" alt="image" src="https://github.com/user-attachments/assets/c10896a2-59e1-47f9-8fe3-6f2fc7841800" />

Choose `continue` and your Debian will be restarted shortly, just wait until boot again and login with the credential you put earlier.

<img width="1366" height="738" alt="image" src="https://github.com/user-attachments/assets/bffd5ccd-0b05-427d-8cc4-70263f3577a0" />

Congratulation! You just installed the base minimal system of Debian.

## Package Installation

### Step 1 (Sudo Installation)

When you first install debian, it's doesn't come with sudo package, you must install it first in order to execute `sudo` command. Follow this steps!
1. `su -`
2. `apt update`
3. `apt upgrade`
4. `apt install sudo`
5. `usermod -aG sudo [your username]`
6. `reboot`

Wait until it finish reboot, and log in again, then type `sudo whoami` make sure the result is `root`

<img width="1366" height="741" alt="image" src="https://github.com/user-attachments/assets/3312be6f-a73e-4a86-8928-ec3a43910048" />
