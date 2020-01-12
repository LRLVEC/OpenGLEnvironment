# OpenGLEnvironment
How to create OpenGL and OpenVR environment for Visual Studio...

//Note: []: folders or files to operate... 

1. Put include\\[GL] into [C:\Program Files (x86)\Microsoft Visual Studio\2019\Preview\VC\Tools\MSVC\14.20.27404\include]
2. Put lib\\x64\\[GL] into [C:\Program Files (x86)\Microsoft Visual Studio\2019\Preview\VC\Tools\MSVC\14.20.27404\lib\x64]
3. Put lib\\x86\\[GL] into [C:\Program Files (x86)\Microsoft Visual Studio\2019\Preview\VC\Tools\MSVC\14.20.27404\lib\x86]
4. If you want to use x64, put System32 - x64\\[glfw3.dll, glfw3d.dll] into [C:\Windows\System32],
   else put System32 - x86\\[glfw3.dll, glfw3d.dll] into [C:\Windows\System32].

//Note: After updating Visual Studio, you must do 1,2,3 again...
