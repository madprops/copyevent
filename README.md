Based on a merge request for clipnotify that wasn't merged after years

Merge request was made by andreblanke for the cdown repo

It allows using the -s flag like: copyevent -s clipboard,primary,secondary

Compilation: gcc copyevent.c -o copyevent -I/usr/X11R6/include -L/usr/X11R6/lib -lX11 -lXfixes