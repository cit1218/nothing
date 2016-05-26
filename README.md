# nothing
什么也没有

../configure --prefix=/usr --mandir=/usr/share/man --infodir=/usr/share/info  --enable-bootstrap --enable-shared --enable-threads=posix --enable-checking=release --with-system-zlib --enable-__cxa_atexit --disable-libunwind-exceptions --enable-gnu-unique-object --enable-languages=c,c++,objc,obj-c++,java --enable-java-awt=gtk --disable-dssi --with-java-home=/usr/lib/jvm/java-1.5.0-gcj-1.5.0.0/jre --enable-libgcj-multifile --enable-java-maintainer-mode --with-ecj-jar=/usr/share/java/eclipse-ecj.jar --disable-libjava-multilib --with-ppl --with-cloog --with-tune=generic  --build=x86_64-redhat-linux --disable-multilib
##修改后的
>./configure --prefix=/usr --mandir=/usr/share/man --infodir=/usr/share/info  --enable-bootstrap --enable-shared --enable-threads=posix --enable-checking=release --with-system-zlib --enable-__cxa_atexit --disable-libunwind-exceptions --enable-gnu-unique-object --enable-languages=c,c++,objc,obj-c++  --disable-dssi  --enable-libgcj-multifile  --with-ppl --with-cloog --with-tune=generic  --build=x86_64-redhat-linux --disable-multilib


-----
>./configure --prefix=/usr --mandir=/usr/share/man --infodir=/usr/share/info  --enable-bootstrap --enable-shared --enable-threads=posix --enable-checking=release --with-system-zlib --enable-__cxa_atexit --disable-libunwind-exceptions --enable-gnu-unique-object --enable-languages=c,c++,objc,obj-c++,java --enable-java-awt=gtk --disable-dssi --with-java-home=/usr/lib/jvm/jre-1.7.0-openjdk.x86_64  --enable-libgcj-multifile --enable-java-maintainer-mode  --disable-libjava-multilib --with-ppl --with-cloog --with-tune=generic --with-arch_32=i686 --build=x86_64-redhat-linux --enable-multilib
 
 >yum install glibc-devel.i686
 
 >yum install gtk2-devel

 >yum -y install libart_lgpl-devel
 
 >yum -y install libXtst-devel
