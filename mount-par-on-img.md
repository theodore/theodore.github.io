---
---

# How to mount a partition on a disk image

calculate offset, in bytes
{% highlight sh %}
losetup -o offset /dev/loop0 image.img
mount /dev/loop0 /mnt
umount ......
losetup -d /dev/loop0
{% endhighlight %}
