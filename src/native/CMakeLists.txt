project(native)

include(wrap_elf)

wrap_elf(FreeType libfreetype.so)
wrap_elf(jpeg libjpeg.so)
wrap_elf(png libpng.so)
wrap_elf(tiff libtiff.so)
wrap_elf(gif libgif.so)
wrap_elf(X11 libX11.so)
wrap_elf(Xext libXext.so)
wrap_elf(XRandR libXrandr.so)
wrap_elf(Xcursor libXcursor.so)
wrap_elf(cairo libcairo.so)
wrap_elf(EGL libEGL.so)
wrap_elf(fontconfig libfontconfig.so)
wrap_elf(dbus libdbus-1.so)
wrap_elf(GL libGL.so "/System/Library/Frameworks/OpenGL.framework/Versions/A/Libraries")
