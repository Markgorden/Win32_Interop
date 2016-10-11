# Win32_Interop
My Win32_Interop version
In order to fix a bug that receive data that fix win32_interop namespace conflict.
rename posix's function win32_xx
you can completely non-intrusive to use this library in your project.
don't have to worry about errors that C2011: 'ip_mreq' : 'struct' type redefinition etc.

#original source
the original source code from https://github.com/MSOpenTech/redis/tree/3.0/src/Win32_Interop

#fix issue 'redefinition' errors in Win32_FDAPI.h
and other way fix issue 81  https://github.com/MSOpenTech/redis/issues/225
