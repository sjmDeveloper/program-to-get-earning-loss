# Project Expense & Loss Calculator

## 1. About the Project
A desktop application built with C++ and Qt6 to calculate project expenses and financial losses accurately.

## 2. Motivation & Features
* **Motivation:** Built to apply practical knowledge of the **Qt framework**, leveraging its native widgets and layout tools to create clean, business-oriented graphical user interfaces (GUIs).
* **Key Features:**
  * **Expense & Loss Tracking:** Calculates total project expenses and net financial losses.
  * **Business-Oriented GUI:** Clean, structured desktop interface built with Qt6.

## 3. Prerequisites & Installation
Before building and running the application, ensure you have **Qt6**, **CMake**, and a C++ compiler installed:

### Linux
* **Ubuntu / Debian / Mint:**
  ```bash
  sudo apt-get update && sudo apt-get install qt6-base-dev cmake build-essential
  ```
* **Fedora / RHEL / CentOS:**
  ```bash
  sudo dnf install qt6-qtbase-devel cmake gcc-c++
  ```
* **Arch Linux / Manjaro:**
  ```bash
  sudo pacman -S qt6-base cmake base-devel
  ```
* **openSUSE:**
  ```bash
  sudo zypper install qt6-base-devel cmake gcc-c++
  ```
* **Alpine Linux:**
  ```bash
  sudo apk add qt6-qtbase-dev cmake build-base
  ```
* **Other Distributions:** Install via the [Official Qt Online Installer](https://qt.io) or your distribution's package manager.

### Windows
Download and install **Qt6** (along with MinGW and CMake) from the [Official Qt Download Page](https://qt.io).

## 4. Build & Run

### 1. Clone & Build
Open your Terminal (Linux) or Command Prompt (Windows) and run:
```bash
git clone https://github.com
cd YOUR_REPO_NAME
mkdir build && cd build
cmake ..
cmake --build .
```

### 2. Run the Application
* **On Linux:**
  ```bash
  ./economy
  ```
* **On Windows (CMD):**
  ```cmd
  economy.exe
  ```

## 5. Version
`1.0.0`
