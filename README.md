
# Minecraft Installation

_A brief description on how to install Minecraft using TLauncher on any Linux Distribution_

![Logo](https://www.bitrefill.com/content/cn/b_rgb%3Affffff%2Cc_pad%2Ch_242%2Cw_400/v1614007464/minecraft-java.jpg)

## Installation

Follow the following steps to install Minecraft (Java Edition) on your favourite Linux Distribution
---

### Step 1
    a) Go to the official TLauncher site.
    b) Choose Linux as a platform to begin.
    c) Download the TLaucnher application for Linux.

```bash
  site: "https://tlauncher.org/en/"
```

### Step 2
    a) Right-click on the file you've downloaded, go to "Properties."
    b) Go to the "Permissions" tab and check the box next to "Enable file execution as a program".

### Step 3
    - If the launcher did not start or an error occurred:
    a) Install Java: sudo apt-get install openjdk-8-jre
    b) After install JavaFX: sudo apt-get install openjfx
_(If you have Java 9 or 10, you need to install Java 8 and get the launcher to work from it,
or completely remove Java 9 or 10.)_

### Step 4
**Important!**

    We recommend that you run with root if you run without root privileges,then there are problems with the graphics (gpu).
    Run as follows:
        a) Navigation: Navigate to the client folder using the CD command
        b) Running: sudo java -jar TLauncher-2.841.jar

### Step 5 (For Debian/Mint Linux)
    a) Update your system: sudo apt-get update , and then "sudo apt-get upgrade" .
    b) Install packets: sudo apt install default-jdk

### Step 6 (For Arch Linux)
    a) Update your system: sudo pacman -Suuy
    b) Install packets: sudo pacman -S java8-openjfx jdk8-openjdk jre8-openjdk jre8-openjdk-headless

### Step 7 (For Fedora/CentOS)
    a) Update your system: sudo yum update
    b) Install packets: sudo yum install java-11-openjdk
    c) Execute the command: "sudo update-alternatives --config java" and indicate in the field the number of the corresponding
       version of Java 11 to set it as default.

    
