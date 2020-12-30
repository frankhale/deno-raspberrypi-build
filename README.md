# deno-raspberrypi-build

Builds of Deno for Raspberry Pi

***NOTE***: Use at your own risk. I simply compiled the latest release of Deno
directly on my Pi 4 using `cargo build --release`. The binary here is for 1.6.3. My Pi 4 is running Ubuntu Server 2010 64bit.

```text
ubuntu@ubuntu:~$ uname -a
Linux ubuntu 5.8.0-1010-raspi #13-Ubuntu SMP PREEMPT Wed Dec 9 17:14:07 UTC 2020 aarch64 aarch64 aarch64 GNU/Linux

ubuntu@ubuntu:~$ ./deno --version
deno 1.6.3 (release, aarch64-unknown-linux-gnu)
v8 8.8.278.2
typescript 4.1.3
```

This repository will be deleted once the Deno team officially supports Raspberry Pi 4.

### Date

30 December 2020

Frank Hale &lt;frankhaledevelops AT gmail DOT com&gt;