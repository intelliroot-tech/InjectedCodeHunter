# InjectedCodeHunter
“Intelliroot Code Injection Hunter” is a tool that can to help you identify injected malicious code. The tool can identify and extract possibly injected code from the processes on a LIVE windows system. The tool can be used for Threat Hunting, Malware Analysis and Incident Response.

#How to use 

The tool is pretty easy to use. You can download the tool from the following github <a href="https://github.com/intelliroot-tech/InjectedCodeHunter"><mark style="background: #d32525; color: #FFFFFF; padding: 1px 4px;">https://github.com/intelliroot-tech/InjectedCodeHunter</mark></a>
The tool has both x86 and x64 versions. 
You can run the tool from the command prompt running in administrator mode.
The tool iterates through various processes by applying certain heuristics and is able to identify the injected code.
Our tool not only identifies the injected code but also creates a dump of the injected code to a file just like the Volatility Malfind plugin.
The only difference is it does not need a memory dump to do so and can execute on a live machine.
