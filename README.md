gtkada2
=======

Auxiliary project file to build from debian packaged sources.

Recent Gnat GPL versions have moved onto Gtk3. At this time I have been unable to easily locate the last GPL Gtk2 release.

Because of this, one can use the gtkada2 packaged with debian/ubuntu. Unfortunately, it cannot be linked directly, because
the incompatible ali files prevent (with good reason) this.

With this project file, the packaged gtkada sources are recompiled with your GPL compiler and everything works fine.
