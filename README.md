# Client-less
***Develop client applications NOT linked to a specific OS***

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

# Main Challenge
***Platforms incompatibility (Microsoft vs. Apple)***

The original plan was to add an abstraction layer on top of the most popular OS that you could find in a project. This abstraction layer would be [VMWare](https://www.vmware.com/) or (VirtualBox)[https://www.virtualbox.org/] on a PC and [Parrallels](https://www.parallels.com/) on Mac.
