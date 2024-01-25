3. Required Tools# [****3. Required Tools****](https://maldevacademy.com/modules/3)

## **Required Tools**

### **Introduction**

Before beginning the malware development journey, it is necessary to prepare the development workspace by installing malware development and reverse engineering tools. These tools will aid one in the development and analysis of the malware and will be used throughout the modules.

### **Reverse Engineering Tools**

Several of the tools mentioned focus more on reverse engineering rather than development. It is essential to reverse engineer the malware built to fully understand its internal workings and have an understanding of what the malware analysts will see upon inspecting the malware.

### **Tools To Install**

Install the following tools:

* [Visual Studio](https://visualstudio.microsoft.com/) - This is the development environment where the coding & compiling process will occur. Install the C/C++ Runtime.
* [x64dbg](https://x64dbg.com/) - x64dbg is a debugger that will be used throughout the modules to get an internal understanding of the developed malware.
* [PE-Bear](https://github.com/hasherezade/pe-bear) - PE-bear is a multiplatform reversing tool for PE files. It will also be used to assess the developed malware and look for suspicious indicators.
* [Process Hacker 2](https://processhacker.sourceforge.io/downloads.php) - Process Hacker is a powerful, multi-purpose tool that helps monitor system resources, debug software and detect malware.
* [Msfvenom](https://www.offensive-security.com/metasploit-unleashed/msfvenom/) - Msfvenom is a command line interface tool that is used to create, manipulate, and output payloads.

### **Visual Studio**

Visual Studio is an integrated development environment (IDE) developed by Microsoft. It is used to develop a wide array of software such as web applications, web services and computer programs. It also comes with development and debugging tools for building and testing applications. Visual Studio will be the main IDE used for development in this course.

[![](3%20Required%20Tools%204fe7ff0b0d174fa5a6d1ce0fd98d3197/Untitled.png)](3%20Required%20Tools%204fe7ff0b0d174fa5a6d1ce0fd98d3197/Untitled.png)### **x64dbg**

x64dbg is an open-source debugging utility for x64 and x86 Windows binaries. It is used to analyze and debug user-mode applications and kernel-mode drivers. It provides a graphical user interface that allows users to inspect and analyze the state of their programs and view memory contents, assembly instructions, and register values. With x64dbg, users can set breakpoints, view stack and heap data, step through code, and read and write memory values.

[![](3%20Required%20Tools%204fe7ff0b0d174fa5a6d1ce0fd98d3197/Untitled%201.png)](3%20Required%20Tools%204fe7ff0b0d174fa5a6d1ce0fd98d3197/Untitled%201.png)The main "CPU" tab has 4 screens:

1. Disassembly (Top-left): This window displays the assembly instructions being executed by the application.
2. Dump (Bottom-left): This window displays the memory contents of the application being debugged.
3. Registers (Top-right): This window displays the values of the CPU registers.
4. Stack (Bottom-right): This window displays the contents of the stack.

The remaining tabs also provide useful information but they will be discussed in the modules when they are used.

### **PE-Bear**

PE-Bear is a free, open-source tool designed to help malware analysts and reverse engineers quickly and easily analyze Windows Portable Executable (PE) files. It helps to analyze and visualize the structure of the PE file, view the imports and exports of each module, and perform static analysis to detect anomalies and possible malicious code. PE-bear also includes features such as PE header and section validation, as well as a hex editor.

[![](3%20Required%20Tools%204fe7ff0b0d174fa5a6d1ce0fd98d3197/Untitled%202.png)](3%20Required%20Tools%204fe7ff0b0d174fa5a6d1ce0fd98d3197/Untitled%202.png)### **Process Hacker**

Process Hacker is an open-source tool for viewing and manipulating processes and services on Windows. It is similar to Task Manager but provides more information and advanced features. It can be used to terminate processes and services, view detailed process information and statistics, set process priorities and more. Process Hacker will be useful when analyzing running processes to view items such as loaded DLLs and memory regions.

[![](3%20Required%20Tools%204fe7ff0b0d174fa5a6d1ce0fd98d3197/Untitled%203.png)](3%20Required%20Tools%204fe7ff0b0d174fa5a6d1ce0fd98d3197/Untitled%203.png)### **Msfvenom**

Msfvenom is a Metasploit framework standalone payload generator that allows users to generate various types of payloads. These payloads will be used by the malware created in this course.

[![](3%20Required%20Tools%204fe7ff0b0d174fa5a6d1ce0fd98d3197/Untitled%204.png)](3%20Required%20Tools%204fe7ff0b0d174fa5a6d1ce0fd98d3197/Untitled%204.png)