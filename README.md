  # Operating System 作業系統

  長庚大學作業系統課程的作業紀錄，涵蓋 Linux 核心開發、系統呼叫實作與嵌入式即時作業系統。

  ## 目錄結構

  ```
  Operating-system/
  └── HW/
      ├── HW1/                        # Linux Kernel Module 實作
      ├── OSHomework2B1228005.pdf     # Linux Kernel 編譯
      ├── OSHomework3B1228005.pdf     # System Call 新增
      ├── OSHomework4B1228005.pdf     # µC/OS-II 環境建置
      └── OSHomework5B1228005.pdf     # µC/OS-II 多工實作
  ```

  ## 作業內容

  | 作業 | 主題 | 說明 |
  |------|------|------|
  | HW1 | Linux Kernel Module | 安裝 VirtualBox + Ubuntu，撰寫並載入 `hello.ko` 與 `Module_B1228005.ko` 核心模組 |
  | HW2 | Linux Kernel 編譯 | 下載 Linux 6.8 原始碼，編譯並安裝核心，修改 GRUB 開機選單 |
  | HW3 | System Call 新增 | 在 Linux Kernel 中新增自訂 System Call（編號 470），並撰寫測試程式驗證 |
  | HW4 | µC/OS-II 環境建置 | 在 VirtualBox 安裝 Windows XP，配置 Borland C++ 與 Turbo Assembler，執行 µC/OS-II 範例 |
  | HW5 | µC/OS-II 多工實作 | 實作 Normal Mode 與 Emergency Mode 的多工排程系統，含倒數計時、亂數產生與畫面顯示任務 |

  ## 使用環境

  - Oracle VirtualBox
  - Ubuntu 22.04
  - Linux Kernel 6.8 / 6.17.5
  - Windows XP（用於 µC/OS-II）

   Course assignments from the Operating System class at Chang Gung University, covering Linux kernel development, system
   call implementation, and embedded real-time operating systems.

  ## Repository Structure

  ```
  Operating-system/
  └── HW/
      ├── HW1/                        # Linux Kernel Module implementation
      ├── OSHomework2B1228005.pdf     # Linux Kernel compilation
      ├── OSHomework3B1228005.pdf     # Custom System Call
      ├── OSHomework4B1228005.pdf     # µC/OS-II environment setup
      └── OSHomework5B1228005.pdf     # µC/OS-II multitasking
  ```

  ## Assignments

  | Assignment | Topic | Description |
  |------------|-------|-------------|
  | HW1 | Linux Kernel Module | Set up VirtualBox + Ubuntu, write and load `hello.ko` and `Module_B1228005.ko` kernel
  modules |
  | HW2 | Linux Kernel Compilation | Download Linux 6.8 source code, compile and install the kernel, modify the GRUB
  boot menu |
  | HW3 | Custom System Call | Add a custom system call (No. 470) to the Linux kernel and write a test program to verify
   it |
  | HW4 | µC/OS-II Environment Setup | Install Windows XP on VirtualBox, configure Borland C++ and Turbo Assembler, run
  µC/OS-II sample code |
  | HW5 | µC/OS-II Multitasking | Implement a multitasking system with Normal Mode and Emergency Mode, including
  countdown timer, random number generation, and display tasks |

  ## Environment

  - Oracle VirtualBox
  - Ubuntu 22.04
  - Linux Kernel 6.8 / 6.17.5
  - Windows XP (for µC/OS-II)
  - Borland C++ 4.5 + Turbo Assembler

  ---
  - Borland C++ 4.5 + Turbo Assembler

  ---
