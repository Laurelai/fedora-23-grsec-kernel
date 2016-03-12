# fedora-23-grsec-kernel
grsecurity patched kernel for fedora 23


See fedora 20 grsec kernel for references.

These files should be all you need for that kernel version.

Replace native files with ones provided.

use diff to see what was changed, note the grsecurity patch had to be altered to place an email at the top or rpmbuild puked, so i copied and pasted one from another patch. This works but eventually ill write something else.

Eventually i will have a repo for prebuilt binaries, but mostly its for my own convenience. Use at your own risk but if you run into trouble hit me up and ill try to help. Dont go crying to fedora or spender as ive edited the grsec patch and custom kernels arent supported. They will not help you, nor should they.
