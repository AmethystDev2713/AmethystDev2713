# Who is AmethystDev2713?

Hi, I'm a young developer with skills in front-end development, some C++ programming, and am currently learning OS programming and electronics.

![Favorite Languages](https://img.shields.io/badge/Favorite%20Language-JavaScript-007C3C)&nbsp;&nbsp;![My Field](https://img.shields.io/badge/My%20field-Front--End%20Development-007C3C)&nbsp;&nbsp;![Experience](https://img.shields.io/badge/Experience-1%20year%20of%20activity-007C3C)

Important Information about me:

🔒 I am using GitHub for personal uses and therefore rarely make public repos, much less would I even think about licensing one for your purposes

⚠️ Unless I say so in a license or readme document, **nobody is allowed to copy, edit, fork, clone, reproduce, distribute, or create derivative works from anything and everything in my public repos**

Where I learn from:

[![Stack Overflow](https://i.postimg.cc/s2WpRrLw/Stack-Overflow.png "Stack Overflow")]("https://stackoverflow.com")&nbsp;&nbsp;[![W3Schools](https://i.postimg.cc/TPCMJzdY/W3-Schools.png "W3Schools")]("https://w3schools.com")&nbsp;&nbsp;[![Microsoft Copilot](https://i.postimg.cc/qq7sSZCL/Microsoft-Copilot.png "Microsoft Copilot")]("https://bing.com/chat")

📰 If you're curious, you can read my programming story below

***

# Evolution of my coding skills
## Stage 1: Simple websites

My coding story begins in the spring of 2021. At the time, I was very curious about how websites and apps worked. So I copied some C# code from a video in Notepad, saved it as a .exe file, and expected it to run. I would get very pissed off when it kept saying "This app can't run on your PC". Oh how stupid I used to be...

So I slowed WAY down and learned HTML from html.com, and not much longer, I had made my first website about what I used to do at that time! From there, I kept coding, debugging, and making more and more complicated websites. Before long, I started to implement JavaScript to make my website do things. The first JS I learned was making a button trigger an alert saying some random, silly message. I used this code trick:

document.getElementById("btn").onclick = function() { alert("RRRRRRRRRR!!!") }

But there was one mistake that drove me crazy every time I typed something like this: I kept typing Document.GetElementById instead of document.getElementById. Hilarious now that I look back on it. After that, CSS hopped on the train. By now, I have become highly proficient in designing and programming websites. My most recent project was a pixel art program (It's hidden just so you know)

## Stage 2: Creating Apps

This is more difficult/advanced than coding websites/web apps. To start my app/software development journey, I started learning C# and used Microsoft Visual Studio as my IDE/Compiler. I don't remember from the top of my head what it was about, but after making sure my code was free of errors, I compiled my app, and it worked! I was so proud that my app finally worked, but it didn't last long, because when I went into File Explorer and launched, it only stayed open for seemingly 1ms. I was very confused as to why, and later found out that that's how console apps work: they stay open until all code execution has finished. That's when I learned about Sleep commands/pauses, which keep the app open after all code execution has finished/preventing a game from running too fast. After implementing a pause at the end of my program, it finally stayed open, and I could admire my work.

Since I figured that programming a GUI would be SUPER hard, I decided to start programming CLI apps (CLI stands for Command-Line Interface and GUI stands for Graphical User Interface).

So I started making basic CLI apps capable of things like writing to text files. This is when C# started to fail me. I would always get errors on how a file was in use by another process even though my program is the only one using it, and the one that created it. So I went out in search of a programming language that had proper User I/O functionality and file I/O functionality. On top of that, I wanted it to NOT be dependent on a runtime so that I could run my programs on other computers without the need for runtime software (portability reasons). After extensive searching on the web, I found it: C++. It worked like a charm, fulfilling all 3 requirements. Unfortunately, I was still using Microsoft Visual Studio and discovered that it uses the stupidest thing ever: Microsoft Visual C++. Seriously, what's the f*****g point? As far as I have studied, there is no feature benefit in using Microsoft Visual C++ (built into MS Visual Studio) over normal C++. The only difference between C++ and MS VC++ is you need a runtime for MS VC++, which is exactly what I don't want. That's why I changed the IDE/Compiler I use from MS Visual Studio to Code::Blocks (That's its formal name, but I call it "CodeBlocks"). It's optimized for C/C++ programming, and it requires absolutely no runtimes or anything ridiculous to get your programs running on other computers. Also, it's open source and 100% free! The best part is that it still makes the same console apps that MSVS does. I still use CodeBlocks to this day, and for other languages, I use MSVSC (Visual Studio Code, which is just an editor and debugger). Point of clarification: Natively, C++ is a programming language that needs no runtime at all and can even be used to make operating systems (I discovered that field in Stage 3). With my programming/distribution problems solved, I continued making more and more complex and featureful programs. Oh, what fun it is to make CLI apps! They're really simple to code and are a good start to app/software development. Do you know what comes after app development?

## Stage 3: Operating System Development

### 3.1: Overview

Making your own Operating System (OS) is one of the most difficult programming projects one could take on. And I'm going to do it. Here is how an OS works in its simplest form:

**Bootloader -->** Usually written in Assembly (AAAAH) and the lowest-level high-level language, C. What I mean by lowest-level high-level language is this: Low-level refers to a language, such as Assembly (screams again), which is the CPU's specific instruction set, that is sort of like its own programming language, capable of providing the programmer with complete control on the hardware environment of the computer, which includes the CPU, CPU Registers, and Memory or RAM. A high-level language provides little or no control over the hardware environment but has significantly enhanced features for program development, such as OOP (Object-oriented Programming), string handling (cut/slice strings), user input (taking keyboard input, mouse input, joystick input, etc), and enhanced display output (graphics modes and more). Assembly is a low-level language, and C is a hybrid of the two types. The purpose of the bootloader is to load the kernel into RAM and tell the computer to execute it.

**Kernel -->** This is the brain of your operating system, and mostly handles low-level functions like memory management (giving programs space to run/execute from, giving files space to load into so the OS can perform actions on them requested by the user or as needed by the OS), outputting to the display/monitor, disk access (load/editing/saving files to the disk), and much more.

**User programs/functionality/shell -->** Now you have an OS that can boot (start) and can do what it needs alongside what the programmer wants it to be capable of doing, you need a program that can execute functions made by the kernel upon the user's request, which can be anything from writing notes to a text file, to loading and playing a video game! This program is usually started once the kernel is fully loaded and ready to perform what it needs to do. In my case, this user program will be a CLI program, because, as I said earlier, CLI apps are very easy to code, and, they give a retro vibe, as that's what OSes from the '70s to the early '90s were like. Famous examples include BASIC and MS-DOS. My OS will be more similar to MS-DOS (even though I have more experience with BASIC, specifically Commodore BASIC) because it has a simpler interface than Commodore BASIC. It looks almost the same as Command Prompt in Windows OS! Speaking of Windows OS, the home screen is pretty much a user program itself! Also, you're using a user program right now to read this very extensive document!

### 3.2: What I want from my OS

I have nowhere enough experience in programming through my long programming journey to make a kernel, let alone a bootloader. I don't want to get even close to x86 or x64 Assembly, it terrifies me! (screams yet again) Whereas something like 8-Bit 6502 assembly is nowhere near as horrifying. Here's a code sample if you're curious:

lda #$02

ldx #$00

ldy #$00


loop:

  sta $0200,x
  
  adc #$04
  
  sta $0201,x
  
  sty $0300
  
  inx
  
  jmp loop


This is a simple program that produced a very satisfying animation of colors when compiled with Skilldrick's 6502js Assembler [https://github.com/skilldrick/6502js]

How can I make an OS if I don't want to make a bootloader and can't make a kernel? Simple: Use GRUB and the Linux Kernel! Both of them are open-source software used in making many, many operating systems, such as Debian, Ubuntu, Zorin, and many others. But that's only the Bootloader (GRUB) and the Kernel (The Linux Kernel) situated, what about the user program? I make it myself! I can make CLI user programs, so that's not a big deal. If I didn't even make the user program, the simplest part and the part that makes the OS yours, I could not have called it mine! While it's going to be super difficult to make my OS, I'm sure it will be a fun and very rewarding project once I get it up and running.

That's all I'm going to say about OS Development. The rest of it is a secret (I'm all about making sure my work isn't stolen or plagiarized)
