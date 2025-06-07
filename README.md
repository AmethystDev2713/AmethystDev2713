# Who is AmethystDev2713?

Hi, I'm a young developer with skills in front-end development, some C++ programming, and 65C02 Assembly.

![Favorite Language](https://img.shields.io/badge/Favorite%20Language-JavaScript-007C3C)&nbsp;&nbsp;![Favorite Code Editor](https://img.shields.io/badge/Favorite%20Code%20Editor-VS%20Code-007C3C)&nbsp;&nbsp;![My Fields](https://img.shields.io/badge/My%20fields-Front--End%20+%208--Bit%20Software-007C3C)&nbsp;&nbsp;![Experience](https://img.shields.io/badge/Experience-4%20years%20of%20activity-007C3C)

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

## Stage 2: Creating Simple Apps

This is more difficult/advanced than coding websites/web apps. To start my app/software development journey, I started learning C# and used Microsoft Visual Studio as my IDE/Compiler. I don't remember from the top of my head what it was about, but after making sure my code was free of errors, I compiled my app, and it worked! I was so proud that my app finally worked, but it didn't last long, because when I went into File Explorer and launched, it only stayed open for seemingly 1ms. I was very confused as to why, and later found out that that's how console apps work: they stay open until all code execution has finished. That's when I learned about Sleep commands/pauses, which keep the app open after all code execution has finished/preventing a game from running too fast. After implementing a pause at the end of my program, it finally stayed open, and I could admire my work.

Since I figured that programming a GUI would be SUPER hard, I decided to start programming CLI apps (CLI stands for Command-Line Interface and GUI stands for Graphical User Interface).

So I started making basic CLI apps capable of things like writing to text files. This is when C# started to fail me. I would always get errors on how a file was in use by another process even though my program is the only one using it, and the one that created it. So I went out in search of a programming language that had proper User I/O functionality and file I/O functionality. On top of that, I wanted it to NOT be dependent on a runtime so that I could run my programs on other computers without the need for runtime software (portability reasons). After extensive searching on the web, I found it: C++. It worked like a charm, fulfilling all 3 requirements. Unfortunately, I was still using Microsoft Visual Studio and discovered that it uses the stupidest thing ever: Microsoft Visual C++. Seriously, what's the f*****g point? As far as I have studied, there is no feature benefit in using Microsoft Visual C++ (built into MS Visual Studio) over normal C++. The only difference between C++ and MS VC++ is you need a runtime for MS VC++, which is exactly what I don't want. That's why I changed the IDE/Compiler I use from MS Visual Studio to Code::Blocks (That's its formal name, but I call it "CodeBlocks"). It's optimized for C/C++ programming, and it requires absolutely no runtimes or anything ridiculous to get your programs running on other computers. Also, it's open source and 100% free! The best part is that it still makes the same console apps that MSVS does. I still use CodeBlocks to this day, and for other languages, I use MSVSC (Visual Studio Code, which is just an editor and debugger). Point of clarification: Natively, C++ is a programming language that needs no runtime at all and can even be used to make operating systems (I discovered that field in Stage 3). With my programming/distribution problems solved, I continued making more and more complex and featureful programs. Oh, what fun it is to make CLI apps! They're really simple to code and are a good start to app/software development. Do you know what comes after app development?

## Stage 3: Advanced Programming Work

### 3.1: Trying to make an OS from x86

Making your own Operating System (OS) is one of the most difficult programming projects one could take on, requiring a deep understanding of how hardware interacts with software, how a CPU & computer environment works, etc. Here is how an OS works in its simplest form:

**Bootloader -->** Usually written in Assembly and/or C. The purpose of the bootloader is to load the kernel into RAM, or some other main/master program, and tell the computer to execute it.

**Kernel -->** Some people's operating systems might skip this all together if their system architecture/goals are simple enough, but for more complex OSes, a kernel can be helpful, as it can act as a code base to know how to allocate CPU time for multiple programs in a multitasking OS, allow filesystem functions, and more than anything, functions that the BIOS can't provide.

**User programs & other system programs -->** Now that you have the grunt work done for your OS, you can do the fun part, which is the programs that make the OS yours. This can vary from a program to write notes to a text file, loading and playing a video game, etc.

This was a bit too much for 2 years ago me, so I've been looking more into building something on the 6502 platform, as it's *much* simpler to get started on and get working (Ben Eater is a great teacher on this).

### 3.2: Cryptography

This is a fun division of Cybersecurity to discover. You'll learn how to password protect websites, securly store, recieve, and transmit data, and much more!