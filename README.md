# Chrome-PasswordDecrypt
Java Chrome Password Decrypter for Win32

This is a CLI tool for extracting local passwords and decrypting them using the 
Windows Data Protection API. This tool only works on the system the passwords were
initially encrypted on, not for remote use as-is. 

Usage: "java -jar CompiledJar.jar"

Flags are -q, -o, and -s, more information in the -help flag.

Requires JDBC and JNA/JNA platform libraries!
