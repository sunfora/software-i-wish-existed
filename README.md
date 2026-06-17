# Software I wish existed

A lot of software keeps coming in, SaaS, AI, CRM, blah blah blah... Whatever.  
But not the software I wish existed. Not the software I wish to use, I would actually use.  
  
This is a personal curated list of things the world is lacking, I might develop somewhat of it in the future.  
And maybe this might be an inspiration for somebody browsing world wide web.  
  
Maybe you can help? If you have developed something which solves any of these issues I have — let me know.  
I would include a link to your project here. Or if you have spotted something on the internet that looks related.  
  
Mail me at ivasandovinzzz@gmail.com.  
  
## Productivity & fun  
  
- **Non-linear todo app.**  
  
  Linear todo apps if you just keep adding things into it become a garbage pit.  
  You always don't have time to do some task right now and you have left if somewhere.  
  
  There are todo apps which allow you to make your tasks hierarchical, but that is nothingburger.  
  Because it is just a linear list with sections. You can hide something but it makes things more obscure.  
  
  You can make something in [Obsidian](https://obsidian.md/), or you can make a roadmap on whiteboard of your choice.  
  There are a lot of options... Idk when I was in university, we have been tasked to use and try [Miro](https://miro.com/ru/).  
  I have recently found [Kinopio](https://kinopio.club/).  
  
  But there is a lot of maintenance required to use them. I find that quite autistic.  
  Proper thing should just work out of the box, you shouldn't think of it too much, organize the organizer.  
  Should be not as rigid as usual todo list or calendar but not as freeing like a software whiteboard.  
  
  Also it should guide my ADHD brain. And I should feel rewarded when things are actually completed.  
  I should keep my progress and track what was done and how was it done.  
  
  _Solutions:_  
  1. [hexodo](https://github.com/sunfora/hexodo)  
  
- **Light embeddable spreadsheet component.**  
  
  I hate to use google docs and open source alternatives for microsoft excel to edit some tables.  
  I wish it was more integrated with other software (inside-out not outside-in).  
  
  Excellent spreadsheet is perfectly embeddable, you just render it in a separate window as a component.  
  And you feed it real data, the work of spreadsheet is to display, handle the input, stream the data back and compute derived data (formulas).  
  
  It should not be a monolithic monster that swallows you and dictates to write extensions to it.  
  
- **Tool to locate things in your actual home or base.**  
  
  You draw your home, photo your items, put qr codes as anchor points in your house to your shelves.  
  Now you scan them via mobile phone to discover what lives in this shelf. Or whether an item exists.  
  
  Should be cozy.  
  
- **Achievement-Unlocked network**  
  While web is a perfect platform for independent publishing of games, there is no real actual place where you can gather your achievements.  
  Also, lots and lots of resources grant you achievements, but they are kinda scattered. I wish to merge them all into one place.  
  
- **Code reader.**  
  
  There are many open-source projects out there & source reading is a great way to learn something new.  
  The process though is not funny and rewarding. At least you should have some sense of progress there.  
  And markup what you have read already and what you did not. + Notes.  
  
  One should create a file format which stores these notes and pages / line / byte ranges you have read.  
  Plus many plugins for many editors and perhaps just a code reader itself.  
  
## Social  
- **Wiki for tech and design approaches.**  
  
  Resource like [wikipedia](https://www.wikipedia.org/) or [fonts in use](https://fontsinuse.com/) but featuring technologies and design approaches in software.  
  
  Order of relevance:  
    (3.0). Personal blog post / video,  
    (2.0). Book / scientific journal / conference,  
    (1.0). Proprietary library or software actually executed this code or pattern  
    (0.5). Proprietary, but the part featuring exact pattern execution or code / idea / algorithm  
           is disclosed to the public  
    (0.0). Open source library or software actually executed this code or pattern  
  
  The lesser order the better a source.  
  
- **Steam but for work software.**  
  
  I hate managing work software.  
  
  It should:  
  
  1. Download everything  
  2. Sell & distribute  
  3. Sync my profiles  
  4. Provide a social layer like we have in games  
  5. Provide good API's for the developers  
  6. Include open-source software  
     and free2play software (yes for work)  
  7. Be crossplatform  
  
- **Version control system for 2d art especially animation.**  
  
  Like multator / toonator but federalized, local first.  
  Custom vcs + bittorent protocol to synchronized user's toons.  
  
  I have seen a death of multator but I find the idea nice and fun.  
  There have been revivals, but the core issues are not solved and they are doomed to fail again and again.  
  
  __Active multator revival__:  
  1. [toonator.site](https://www.toonator.site/)  
  
- **News Map.**  
  
  Fetch news from news resources like [ground news](https://ground.news/) does.  
  But now you can put them on map, select them on map. Connect and annotate.  
  
  Replay the happenings in order.  
  Maybe a software suite for a detective.  
  
- **Card-Game Hiring.**  
  
  @originally: [tweet](https://x.com/sandovin34721/status/2061321345909063886)  
  
  I am bored out from looking the job postings and sending motivation letters.  
  And also the first akward ping-pong between the parties.  
  
  Maybe we can do better: why not make this whole process a card game?  
  You have your cards: technologies you are familiar with.  
  
  The corporation or employer has a stack they are working with.  
  They push "PHP" on a table, you cover it with PHP, they push "Go", you cover it with idk "C".  
  
  Then if the employing party is satisfied, they give you the cards  
  and you can push them on table and ask questions about say the specifics of the project.  
  
  They give you an offer and a paygrade you push counteroffer on a table. :)  
  At some point in the game you should reveal something not nice about you  
  or the system would grab something from anonymous reviews. Or straight from the magazines.  
  But now you can put them on map, select them on map. Connect and annotate.  
  
## Tools for the developers  
  
- **A proper interactive Canvas 2D debugger.**  
  
  Canvas has been around for quite a while. A lot of stuff can be done with it.  
  But it is lacking, and the first thing is that it is essentially a black-box.  
  
  You create a path and you don't see it. You can't test things.  
  Chrome doesn't even let you see what is drawn when you step debug inside [requestAnimationFrame](https://developer.mozilla.org/en-US/docs/Web/API/Window/requestAnimationFrame).  
  
  Although perfectly valid thing to do, from the DX it is a total nightmare.  
  I have vibecoded some shitty debugger specifically for chrome in case I need to debug in it.  
  But right now I spend my time in Firefox.  
  
- **Universal debugger.**  
  
  There are tons of languages, runtimes weird tech stacks used DAILY in our projects.  
  It is hard to setup debuggers let alone use them.  
  
  They do not compose nicely today, but they absolutely should.  
  I should see everything: from TCP down to PHP VM opcodes and raw assembly my machine is crunching.  
  Without complicated setup. Error prone to specific project.  
  
  Currently I use vscode (and editor) with DAP to perform debugging.  
  But it is a bad solution to a hard problem. Universal debugger should be much more transparent, simpler to use.  
  And it should allow you to inspect different VM's.  
  
- **Testing framework integrated with debugger.**  
  
  Currently there are two conflicting paradigms:  
  1. You have tests which you write then run.  
  
     They require a lot of boilerplate to write.  
     You can't just invoke a function or some specific line of code.  
     You have to make it a language primitive, you have to isolate it and mock it.  
  
  2. You have debugger / repl sessions.  
  
      You can't save or replay your findings. Once the debugger is off the only thing that you have are:  
        breakpoints and maybe configured watch window.  
      You can't run automatic checks once the debugger is up, you have to manually watch and step debug it again.  
  
  My issues is that this is a tragic waste of human resources.  
  And if you use AI, computing resources, I don't care.  
  
  Debuggers are excellent way to find a bug or get in touch with your program.  
  Test suits are great to prevent stupid mistakes.  
  
  Both paradigms should not compete with each other and testing frameworks should debug stuff.  
  
- **Light desktop runtime for canvas heavy apps.**  
  
  Canvas2D is a perfect tech for developing a small game or some interactive utility.  
  There are easy ways to host an interactive application written for desktop: WASM compilation target.  
  
  I need something in reverse: runtime, maybe integrated with good debugger.  
  That lets you get off from the web but doesn't require turning your app into 200MB electron chromium monster.  
  
  Would be nice if it can switch between js implementations and canvas implementations of real browsers.  
  I want to test things without constant switching between browsers.  
  
  _Solutions:_  
  1. [mystralnative](https://github.com/mystralengine/mystralnative)  
  
- **Chrome / firefox devtools but in command line.**  
  
  At least a debugger. What I have tried looks, works and feels like shit.  
  I should have a proper cli repl for chrome. I should grep and search objects, tabs and iframes.  
  It should be way simpler and more intuitive than using CDP directly.  
  
- **Assembly IDE.**  
  
  @originally [tweet](https://x.com/sandovin34721/status/2061759136002457830)  
  
  A good UX/UI challenge to solve is to make ASM programming nice.  
  
  Add a typescript like semanthic layer which would sit entirely in a comment.  
  Something like  
  ```asm  
  ; @layout {{id: uint32, age: uint32}} User  
  
  ; @register {User} rdi  
  mov eax, [rdx + 4]  
  ;          ^^^^ this would show you that you are accessing User.age for example now  
  ;               on hower in IDE and also when you type brackets  
  ;               it would autocomplete the fields avilable in that view  
  ```  
  
  Also it should support moving the RIP anywhere you want and running N+1 steps from the saved state.  
  The memory view has to be nice enough to use and see diffs.  
  
- **Generator for HTTP boilerplate.**  
  
  Everytime you want to do some simple server in a new language.  
  You need to define bunch of constants for return codes, headers and etc.  
  
  It would be much better if we had not the library but some cross language generator.  
  Which would output definitions and comments in target language right from MDN WebDocs.  
  
- **Code reader.**  
  
  There are many open-source projects out there & source reading is a great way to learn something new.  
  The process though is not funny and rewarding. At least you should have some sense of progress there.  
  And markup what you have read already and what you did not. + Notes.  
  
  One should create a file format which stores these notes and pages / line / byte ranges you have read.  
  Plus many plugins for many editors and perhaps just a code reader itself.  
  
- **Free-Roam-Camera Pager**  
  
  Most pagers are designed around reading append logs.  
  While it mostly handles most use cases there is one particular  
  where most pagers fail to provide good user experience to my taste.  
  
  The case is such:  
  
    consider using something like `entr -c` for dynamic recompilation / test running  
    or any other file watcher, which dumps logs into your console and then clears the screen.  
  
  This is quite an effective workflow:  
  
    you never start compilation manually or run anything manually  
    it just reactively recompiles on its own.  
  
  But there is a problem you would definitely encounter:  
  
    this workflow becomes completely unusable  
    if you try to read the stdout of the program you interactively restart  
    when stdout is significantly long.  
  
  When `entr -c` clears your screen most terminals are obliged to scroll your viewport to the top.  
  Then you would be fed with lines from your filewatcher like entr and terminal would scroll your viewport down.  
  On every recompilation.  
  
  Say your logs are quite consistent: every time you start the app, line 10 contains the value you are interested in.  
  Then if you wish to monitor that 10th line: you have to scroll back and forth on each recompilation.  
  Which is not what you have certainly wished.  
  
  It would be nicer if the viewport of the terminal would not be so attached to the current line input.  
  Because there is no point jumping to say from line 10 to line 0, from line 0 to line 10 or something past it,  
  if whatever you are interested with is say some printf of the variable located right at that line 10 on each content refresh.  
  
  In fact it would be nice if lines were drawn on some sort of virtual infinite terminal.  
  And you would just move your camera over it.  
  
  So this is it. This is an idea for `free-roam camera pager`.  
  
- **TTY Debugger**  
  I am working on a pager described above.  
  When you work on pager you have to implement and then test tty's.  
  
  I wish to have a nice tui which creates pty and forwards data from the real tty into that pty,  
  while rendering parsed keystrokes and just bytes sent over the channel.  
  The app is then started with this custom pty as ctrl stream.  
  
  Maybe a little bit of replay + record / reference on terminal escape codes.  
  render of the termios struct state.  
  
## Programming Languages  
  
- **Low level very interactive lisp.**  
  
  Like racket, but where scope is not #lang, but #device.  
  So that you can kinda hack with devices. Run them actually or emulate and debug.  
  
  It should also adopt very educative nature of racket. But maybe less academic.  
  
  I have a very messy and chaotic [sketch](https://sunfora.github.io/sicp/extra/devices.html) on how would it look like.  
  Which I have wrote in 3 days. But a lot of design work and implementation must be done prior.  
  
  I am no expert in low level computing and that is kinda the reason I need it.  
  C is very much not very friendly language, all the ceremony around programming asm is kinda crazy.  
  Things should be more interactive than they are now.  
  
  I have tried to use debuggers in the past (the good experience was raddbg) and C interpreters: cling, clang-repl (they were pretty bad).  
  But I wish it was even more lispy.
