# Lecture 2 Introduction to Linux Notes 
 
## 1. What is an Operating System?

   * An operating system provides all fundamental software features of a computer. It enables you to use the computers hardware providing you the basic tools that make the computer impactful.
  
## 2. What is a kernel?

   * An OS Kernel is a software component thats responsible for managing low-level features of the computer, including CPU time, managing system hardware, etc..
  
## 3. Which other parts aside from the kernel identify an OS?

   * Other parts that identify an OS are Command-line shells, Graphical User Interfaces, Utility and Productivity  Programs and Libraries. Command line shells work by typing commands in a shell, it was the old way of using computers before the graphical interface was invented. Graphical interfaces rely on icons, menus, and a mouse clicker for user interaction. Utility and productivity programs are tools like web browsers, documents processors and text editors. Libraries are collections of programming functions that can by a variety of programs.
  
## 4. What is linux?

   * Linux is a Unix-like operating system that is popular in academic and business environments. It consists of libraries, kernel, and utilities that make up the entire operating system.

## 5. What is a linux distribution?

   * A linux distribution is any operating system that runs the Linux Kernel. Examples are Arch, Ubuntu, Debian, Fedora and many more. A complete Linux system package is made up of a Linux kernel, Core unix tools, Supplemental software, startup scripts and an installer.
  
## 6. List at least 4 linux characteristics:

     * Linux is open source software
  
     * Linux is available free of charge
  
     * Linux includes many of the Unix tools including many important internet server programs and programming languages outside of the box
  
     * Linux is also highly scalable and customizable
  
## 7. What is Ubuntu?

   * Ubuntu is a Linux distribution, freely available with both community and professional support. Ubuntu was built on the ideas that software should be free of charge, easily usable for everyone regardless of language or disability, and having the freedom to customize and alter to their liking. It was created to be a user friendly version of Debian but with time it became a major distribution of its own.

## 8. What is Debian?

   * Debian is an all-volunteer organization dedicated to developing free software and promoting ideals of the Free Software community. It began in 1993 when a group of developers created a coherent linux distribution. It is known as the godfather of all linux distributions.

## 9.  List and define the different types of licensing agreements

      1. Open source: the software may be distributed for a fee or free. The source code is distributed with the software
   
      2. Closed source: the software is not distributed with the source code, The user is restricted from modifying the code.
   
      3. Freeware: the software is free but the source code is not available.
   
      4. Shareware: the software is free on a trial basis
   

## 10. What is Free Software? Define the 4 freedoms.

   * Free software is software that is distributed with the source code, its usually free of charge or obtained by a fee.
      * The four freedoms include:
        * Freedom 0: use the software for any purpose
        * Freedom 1: examine the source code and modify it as you see fit
        * Freedom 2: redistribute the software
        * Freedom 3: redistribute your modified software

## 11. What is virtualization?

   * Virtualization is defined as creating virtual versions of something. It allows admins to divide the hardware and create multiple computers inside a single physical computer. It also allows the user to run multiple OSs on one physical machine at the same time.

## 12. List 3 benefits of virtualization

      1. Allows applications to be tested before installing them on the host machine.
      2. Allows running multiple OSs on one machine without dual booting
      3. It allows programs coded for one type of hardware or operating system to work on another that its not designed to work on.
   
## 13. What is a hypervisor? Include definitions of the 2 types

   * A hypervisor is the software or hardware in charge of creating, managing, and running virtual machines.
  
       * Type 1 (Bare-metal hypervisor): Runs directly on the hardware. The hypervisor is basically the operating system for the physical machine. It has better performance than Type 2 because there is no host OS involved and the system is dedicated to supporting virtualization.
  
       * Type 2: Runs on top of an operating system. Most commonly used in client-side virtualization. If the host fails the virtual machine will also fail.
  
## 14. What is the difference between Guest OS and Host OS?
   * The Host OS is the operating system that is running in the computer where the hypervisor is installed. While the Guest OS is the operating system that is being virtualized in the virtual machine.
  
## 15. What is virtualbox?
   * VirtualBox is a powerful x86 adn AMD64/Intel64 virtualization product for enterprise as well as home use. It's feature rich and high performance for enterprise customers while also being the only professional solution that is freely available as Open Source Software.