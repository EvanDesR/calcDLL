# calcDLL

DLL file that is loaded when injectorDLL, calls CreateRemoteThread using notepad.exe, as the remote process, and using the buffer holding calcDLL path, as the library to load(Loaded via GetProcAddress for LoadLibraryW Function).

The injectorDLL program can be found Here https://github.com/EvanDesR/injectorForDLL
