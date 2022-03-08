#!/bin/sh

qemu-system-x86_64 -m 1G -nic user -boot d -cdrom alpine-virt-3.15.0-x86_64.iso -hda alpine.qcow2 -display curses -nographic -accel hvf -netdev user,id=mynet0,hostfwd=tcp::5007-:5007 -device e1000,netdev=mynet0
