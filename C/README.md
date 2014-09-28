--------------------------------------------------
Step 1 : Check the GCC Version
---------------------------------------------------
vdhulappanavar@demo-project:~/workspace (master) $ gcc --version
gcc (Ubuntu 4.8.2-19ubuntu1) 4.8.2
Copyright (C) 2013 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

--------------------------------------------------
Step 2 : Compile hello.c using GCC
---------------------------------------------------

vdhulappanavar@demo-project:~/workspace (master) $ gcc hello.c
vdhulappanavar@demo-project:~/workspace (master) $ ls
README.md*  a.out*  hello.c  html/  node.js/  php/  python/  ruby/  vidya.class  vidya.java

--------------------------------------------------
Step 3 : Run the a.out
---------------------------------------------------

vdhulappanavar@demo-project:~/workspace (master) $ ./a.out 
hello world vidya!vdhulappanavar@demo-project:~/workspace (master) $ ./a.out
hello world vidya!vdhulappanavar@demo-project:~/workspace (master) $ node --version
v0.10.30

--------------------------------------------------
Step 3 : Compile the hello.o to vidya.out
---------------------------------------------------
vdhulappanavar@demo-project:~/workspace (master) $ gcc hello.c -o vidya.out
vdhulappanavar@demo-project:~/workspace (master) $ ls
README.md*  a.out*  hello.c  html/  node.js/  php/  python/  ruby/  vidya.class  vidya.java  vidya.out*
vdhulappanavar@demo-project:~/workspace (master) $ ./vidya.out 
hello world vidya!

vdhulappanavar@demo-project:~/workspace (master) $