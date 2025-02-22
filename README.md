# Client-less
***Develop client applications NOT linked to any specific OS***

As I planned to work on a wrapper for Salesforce DX my experience with Salesforce Ant left me with a bitter taste. If you initiate your project with implementation teams in mind there is a common wall you will be hitting soon or later: **The developer OS of choice**.

The point of this project is to address the issue of the target machine OS compatibility in a world of client-server in general and SaaS in particular and even more in the case of Salesforce implementations.

Write once, run anywhere ([if you see what I mean](https://en.wikipedia.org/wiki/Write_once,_run_anywhere))

To start with, let's see what I think can be called multi-OS. The software needs to support:

The original target...
* [Microsoft Windows](https://www.microsoft.com/en-gb/windows)
* [Apple MacOS](https://www.apple.com/uk/macos)

While at it...
* [Linux](https://en.wikipedia.org/wiki/Linux)
* [Google Chrome](https://chromeos.google/)
* [Apple IPadOS](https://www.apple.com/uk/ipados)

# The official  OS list

Sorted by priority...

1. [Microsoft Windows](https://www.microsoft.com/en-gb/windows) This is the client OS of choice. Most programs are developed for Windows first then adapted to Apple if at all...
1. [Apple MacOS](https://www.apple.com/uk/macos)
1. [Linux](https://en.wikipedia.org/wiki/Linux)
1. [Google Chrome](https://chromeos.google/)
1. [Apple IPadOS](https://www.apple.com/uk/ipados)

# Main Challenge
***Platforms incompatibility (Microsoft vs. Apple)***

The original plan was to add an abstraction layer on top of the most popular OS that you can find in a project. This abstraction layer would be [VMWare](https://www.vmware.com/) or (VirtualBox)[https://www.virtualbox.org/] on a PC and [Parrallels](https://www.parallels.com/) on Mac. The problem is that these virtual environments are related to the micro-processor instruction set, hence whatever you do, soon or later you will be hitting the Intel vs. Apple processor challenge. I appreciate that nowadays [Parrallels](https://www.parallels.com/products/desktop/) is selling itself as a WinTel emulator but this has not been always the case especially in the early days of Apple move to their own silicium. More over, we are speaking about emulation here which can come with its own bugs and not be weclome in a Cloud Computing implemenmtation project.   

# Cool links

* [Interview of SalesforceDX's daddy](https://www.youtube.com/watch?v=Kfw_alKEmFY)
* [GitHub Live](https://github.dev/github/dev)
* [VS Code live](https://vscode.dev/)
