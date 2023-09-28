# AmethystDev2713: Evolution of my coding skills
## Stage 1: Simple websites

My coding story begins in the spring of 2021. At the time, I was very curious on how websites and apps worked. So I copied some C# code from a video in Notepad, saved it as an .exe file, and expected it to run. I would get very pissed off when it kept saying "This app can't run on your PC". Oh how stupid I used to be...

So I slowed WAY down and learned HTML from html.com, and not much longer, I had made my first website about what I used to do at that time! From there, I kept coding, debugging, and making more and more complicated websites. Before long, I started to implement JavaScript to make my website do things. The first JS I learned was making a buttom trigger an alert saying some random, silly message. I used this code trick:

document.getElementById("btn").onclick = function() { alert("RRRRRRRRRR!!!") }

But there was one mistake which drove me crazy every time I typed something like this: I kept typing Document.GetElementById instead of document.getElementById. Hilarious now that I look back on it. After that, CSS hoped on the train. By now, I have become highly proficient in designing and programming websites. My most recent project being a pixel art program (It's hidden just so you know)

## Stage 2: Creating Apps

This is obviously more difficult/advanded than coding websites/web apps. To start my app/software development journey, I started learning C# and used Microsoft Visual Studio as my IDE/Compiler. I don't remember from the top of my head what it was about, but after making sure my code was free of errors, I compiled my app, and it worked! I was so proud that my app finally worked, but it didn't last long, because when I went into file explorer and launched, it only stayed open for seemingly 1ms. I was very confused as to why, and later found out that that's how console apps work: they stay open until all code execution has finished. That's when I learned about Sleep commands/pauses, which keep the app open after all code execution has finished/preventing a game from running too fast. After implementing a pause at the end of my program, it finally stayed open, and I could admire my work.

Since I figured that programming a GUI would be SUPER hard, I decided to start programming CLI apps (CLI stands for Command-Line Interface and GUI stands for Graphical User Interface).

So I started making basic CLI apps capable of things like writing to text files. This is when C# started to fail me. I would always get errors on how a file was in use by another process even though my program is the only one using it, and the one that created it. So I went out in search of a program which had proper User I/O functionality and file I/O functionality. On top of that, I wanted it to NOT be dependent on a runtime so that I could run my programs on other computers without the need of runtime software (portability reasons). After extensive searching on the web, I found it: C++. It worked like a charm, fufilling all 3 requirements. Unfortunatly, I was still using Microsoft Visual Studio, and discovered that it uses the stupidist thing ever: Microsoft Visual C++. Seriously, what's the f*****g point? As far as I have studied, there is no feature benifit in using Microsoft Visual C++ (built into MS Visual Studio) over normal C++. The only difference between C++ and MS VC++ is you need a runtime for MS VC++, which is exactly what I dont want. That's why I changed the IDE/Compiler I use from MS Visual Studio to Code::Blocks (That's it's formal name, but I call it "CodeBlocks"). It supports just as many, if not more, programming languages as MSVS, but it requires absolutely no runtimes or anything ridculous to get your programs running on other computers. Also, it's open source and 100% free! Best part: It still makes the same console apps that MSVS does. I still use CodeBlocks to this day. Point of clarification: Nativley, C++ is a programming language which needs no runtime at all and can even be used to make operating systems (I discover that field in Stage 3). With my programming/distribution problems solved, I continued making more and more complex and featureful programs. Oh, what fun it is to make CLI apps! They're really simple to code and are a good start to app/software development.
