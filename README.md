# Welcome to the JDK!

For build instructions please see the
[online documentation](https://openjdk.org/groups/build/doc/building.html),
or either of these files:

- [doc/building.html](doc/building.html) (html version)
- [doc/building.md](doc/building.md) (markdown version)

See <https://openjdk.org/> for more information about the OpenJDK
Community and the JDK and see <https://bugs.openjdk.org> for JDK issue
tracking.

For WSL:
1. Install WSL: `wsl --install`
2. Set default distro: `wsl -s Ubuntu`
3. Login to Ubuntu and download JDK
4. Run: `bash configure --with-boot-jdk=/home/nhannn_unix/jdk/jdk-21 --build=x86_64-unknown-linux-gnu --openjdk-target=x86_64-unknown-l
inux-gnu`

How to run:
1. /mnt/c/NhanNguyen/Work/OpenJDK/Source/JDK/build/linux-x86_64-server-release/images/jdk/bin/javac <file>.java
2. /mnt/c/NhanNguyen/Work/OpenJDK/Source/JDK/build/linux-x86_64-server-release/images/jdk/bin/java <file>

For Cygwin
1. Install [Cygwin](http://www.cygwin.com)
2. Run: `cd /cygdrive/c/NhanNguyen/Work/OpenJDK/Source/JDK`
3. Install Visual Studio 2022 with "Desktop Development with C++"
4. Run: `bash configure --with-boot-jdk=/cygdrive/c/NhanNguyen/Work/OpenJDK/Document/JDK-21/jdk --with-toolchain-version=2022`
5. Run: `make images`
