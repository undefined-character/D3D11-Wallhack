# D3D11-Wallhack
D3D11 Hook Wallhack x86/x64

1. Compile dll and inject into a d3d11 game
2. Find models by brute-forcing Stride or IndexCount etc. (see universal.cpp: countnum == Stride) 
3. Brute-force the correct depth of those models (countEdepth and countRdepth)

- apex: Edepth = 1; Rdepth = 3; 
- ut4: Edepth = 11; Rdepth = 12;
- serious sam fus: Edepth = 11; Rdepth = 4;
- quake c: Edepth = 0; Rdepth = 2;

Credits: dracorx, evolution536, test4321, Momo5000

Menu key = insert, ALT + L = options
![alt tag](https://github.com/DrNseven/D3D11-Wallhack/blob/master/keyboard.jpg)
