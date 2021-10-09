---
title: Demo Page
layout: demo_template
author: Mark
---


This page is written by {{page.author}}.


{% include Jekyll.txt%}

A command line interface (CLI) is a text-based user interface (UI) used to view and manage computer files. Command line interfaces are also called command-line user interfaces, console user interfaces and character user interfaces.

History and features of CLI
Before the mouse, users interacted with an operating system (OS) or application with a keyboard. Users typed commands in the command line interface to run tasks on a computer.

Typically, the command line interface features a black box with white text. The user responds to a prompt in the command line interface by typing a command. The output or response from the system can include a message, table, list, or some other confirmation of a system or application action.

Today, most users prefer the graphical user interface (GUI) offered by operating systems such as Windows, Linux and MacOS. Most current Unix-based systems offer both a command line interface and a graphical user interface.

The MS-DOS operating system and the command shell in the Windows operating system are examples of command line interfaces. In addition, programming languages can support command line interfaces, such as Python.



An explanation of a shell
The software that handles the command line interface is the shell, also commonly referred to as a command language interpreter. Two well-known shells are Windows shell and Bash for Linux and macOS.


Grasp the concepts behind PowerShell objects

Play

Mute
Loaded: 0.00%

Picture-in-Picture

Fullscreen
PowerShell objects tutorial
This PowerShell lesson details the concepts of properties and methods.
Shells are the outermost layer of the OS and are often separated from the underlying OS kernel. A shell operates like an application and can be replaced. Because the shell is only one layer above the OS, users can perform operations that are not available in other interface types, such as moving files within system folders and deleting locked files.

Shells require users to know the syntax of a scripting language. Most command line shells save sequences of commands for reuse in a script, which is the foundation of basic systems management automation.

Prompts and commands
There are hundreds of different commands available in a command line. The set of commands may vary dramatically between operating systems or applications.

The following is a list of commands in the Microsoft task configuration and automation framework PowerShell:

Get-Date: Retrieves the current time and date.
cd: Used to change directories.
Stop-Process: Terminates one or more system processes.
Although some commands operate alone, others require the use of arguments. The argument follows the command and provides additional details or specifics. For example, the cd command tells the OS to change to a different directory, but the command line must include the name of the desired directory path, as well.

For example, a full command with an argument appears as:

cd \documents\user

The arguments used with commands can also be extremely complex and granular. For example, the following command line string shows the PowerShell syntax to retrieve detailed network configuration information from a Windows machine:

Get-NetIPAddress | Sort InterfaceIndex | FT InterfaceIndex, InterfaceAlias, AddressFamily, IPAddress, PrefixLength -Autosize

CLI versus GUI
The graphical user interface is the most popular user interface today. A GUI uses windows, menus and icons to execute commands. A mouse is the most common way to navigate through a GUI, although many GUIs allow navigation and execution via a keyboard.

One example of a GUI-based application is Microsoft Word. A user can change options for page layouts and styles by selecting the corresponding icon with a mouse or keyboard.

PowerShell command line
An example of output from the PowerShell command line
The advantage of a GUI is the interface visually displays the available functions. However, because of its simplicity and ease of use, a GUI does not have the same level of functionality and granular control as a command line interface. For example, it may take numerous clicks and movement through several dialog boxes in a GUI to accomplish the same result as a single command line.

In addition, GUIs do not readily support scripting or automation. For common tasks, a user must repeat each click or navigate each dialog within the GUI manually.

Administrators who manage thousands of systems or user configurations will find a GUI far less efficient than a CLI. But a simple CLI command can easily adjust configurations for a large group of systems at once.

Commands and arguments can also be combined and saved, then executed as a script each time that specific action -- or comprehensive set of actions -- is required. The CLI is the preferred tool for many enterprise-wide systems management tasks.

CLI advantages and disadvantages
The advantages of a command line interface are:

granular control of an OS or application;
faster management of a large number of operating systems;
ability to store scripts to automate regular tasks; and
basic command line interface knowledge to help with troubleshooting, such as network connection issues.
The disadvantages of a command line interface are:

GUI is more user-friendly;
steeper learning curve associated with memorizing commands and complex syntax/arguments; and
different commands used in different shells.
