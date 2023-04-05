# Interpreter
The CGIb Interpreter is a simple programming language for Windows, designed for basic syntax users who want to run scripts on a web server or locally on a console window. It supports external modules and offers easy integration with ActiveX. The language is compiled into a standalone .exe file for easy deployment without any external dependencies.
 Consol start:
 cgib.exe helloword.cgib 
 --result: Hello Word!--
 or
 cgib.exe helloword.cgib /d=yes
 --result: Hello Word (current date and time)!
 
 URL start:
 http://[url address]/helloword.cgib
 or
 http://[url address]/helloword.cgib?d=yes
