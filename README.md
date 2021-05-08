# RegJump2
My implementation of RegJump as a library
# Code Quality
I am still pretty new to coding in C++, so expect there to be lots of bad practice in my code.

Also does require C++ and cannot work with C due to usages of `wstring` for splitting and `vector` (although may be replaceable)
# How to use
Just download `regjump2.h` and use it in your project

To open a registry key, simply call `OpenRegistryAt(key)` where key is a wide string (`L"example wide string"`)

🛡 You application must also have Administrator Privileges to run this function properly.
⚠ RegJump2 will **NOT** check if your application already has administrator privileges before running
# License
Read LICENSE file
# Planned for the future
- Set the `HKEY_CURRENT_USERS\SOFTWARE\Microsoft\Windows\CurrentVersion\Applets\Regedit\LastKey` value if regedit is not already open instead of running regedit and jumping. Or add a function that has the same functionality
