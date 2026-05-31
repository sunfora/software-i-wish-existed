# Software I wish existed

A lot of software keeps coming in, SAAS, AI, CRM, blah blah blah... whatever.  
But not the software I wish existed. Not the software I wish to use, I would actually use.

This is a personal curated list of things the world is lacking, I might develop somewhat of it in the future.  
And maybe this might be an inspiration for somebody browsing world wide web.

Maybe you can help? If you have developed something which solves any of these issues I have — let me know.  
I would include a link to your poject here. Or if you have spotted something on the internet that looks related.

Mail me at ivasandovinzzz@gmail.com.

## Productivity & fun

- **Non-linear todo app.**
    
  Linear todo apps if you just keep adding things into it become a garbage pit.  
  You always don't have time to do some task right now and you have left if somewhere.  
    
  There are todo apps which allow you to make your tasks hierarchial, but that is nothingburger.  
  Because it is just a linear list with sections. You can hide something but it makes things more obscure.  
    
  You can make something in [Obsidian](https://obsidian.md/), or you can make a roadmap on whiteboard of your choice.  
  There are a lot of options... Idk when I was in university, we have been tasked to use and try [Miro](https://miro.com/ru/).  
  I have recently found [Kinopio](https://kinopio.club/).  
    
  But there is a lot of maintainance required to use them. I find that quite autistic.  
  Proper thing should just work out of the box, you shouldn't think of it too much, organize the organizer.  
  Should be not as rigid as usual todo list or calendar but not as freeing like a software whiteboard.  
    
  Also it should guide my ADHD brain. And I should feel rewared when things are actually completed.  
  I should keep my progress and track what was done and how was it done.

  _Solutions:_
  1. [hexodo](https://github.com/sunfora/hexodo)  
    
- **Light embeddable spreadsheet component.**
    
  I hate to use google docs and open source alternatives for microsoft excel to edit some tables.  
  I wish it was more integrated with other software (inside-out not outside-in).  
    
  Excellent spreadsheet is perfectly embedable, you just render it in a separate window as a component.  
  And you feed it real data, the work of spreadsheet is to display, handle the input, stream the data back and compute derived data (formulas).  
    
  It should not be a monolithic monster that swallows you and dictates to write extensions to it.  
    
- **Tool to locate things in your actual home or base.** 
    
  You draw your home, photo your items, put qr codes as anchor points in your house to your shelfs.  
  Now yoi scan them via mobile phone to discover what lives in this shelf. Or whether an item exists.  
    
  Should be cozy.
    
- **Achievemnt-Unlocked network**  
  While web is a perfect platform for independent publishing of games, there is no real actual place where you can gather your achievements.  
  Also, lots and lots of resources grant you achivements, but they are kinda scattered. I wish to merge them all into one place.  
    
## Social
- **Wiki for tech and design approaches.**
    
  Resource like [wikipedia](https://www.wikipedia.org/) or [fonts in use](https://fontsinuse.com/) but featuring technologies and design approaches in software.
    
  Order of relevance:
    (3.0). personal blog post / video,  
    (2.0). book / scientific journal / conference,  
    (1.0). proprietary library or software actually executed this code or pattern  
    (0.5). proprietary, but the part featuring exact pattern execution or code / idea / algorithm  
           is disclosed to the public  
    (0.0). open source library or software actually executed this code or pattern  
    
  The lesser order the better a source.  
    
- **Steam but for work software.**
    
  I hate managing work software.
    
  It should: 
    
  1. download everything
  2. sell & distribute
  3. sync my profiles
  4. provide a social layer like we have in games
  5. provide good API's for the developers
  6. include open source software  
     and free2play software (yes for work)  
  7. be crossplatform
    
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
  Maybe a detective suit.  
    
## Tools for the developers

- **A proper interactive Canvas 2D debugger.**  
    
  Canvas has been around for quite a while. A lot of stuff can be done with it.  
  But it is lacking, and the first thing is that it is essentially a black-box.  
    
  You create a path and you don't see it. You can't test things.  
  Chrome doesn't even let you see what is drawn when you step debug inside [requestAnimationFrame](https://developer.mozilla.org/en-US/docs/Web/API/Window/requestAnimationFrame).  
    
  Although perfectly valid thing to do, from the DX it is a total nightmare.  
  I have vibecoded some shitty debugger specifically for chrome in case I need to debug in it.  
  But right now I spend my time in firefox.
    
- **Universal debugger.**
    
  There are tons of languages, runtimes weird tech stacks used DAILY in our projects.  
  It is hard to setup debuggers let alone use them.
    
  They do not compose nicely today, but they absolutely should.  
  I should see everything: from TCP down to PHP VM opcodes and raw assembly my machine is crunching.  
  Without complicated setup. Error prone to specific project.
    
  Currently I use vscode (and editor) with DAP to perform debugging.  
  But it is a bad solution to a hard problem. Universal debugger should be much more transparent, simpler to use.  
  And it should allow you to inspect different VM's.
    
- **Testing framework integrateed with debugger.**
    
  Currently there are two conflicting paradigms: 
  1. You have tests which you write then run.  
       
     They require a lot of boilerplate to write.  
     You can't just invoke a function or some specific line of code.  
     You have to make it a language primitive, you have to isolate it and mock it.  
       
  2. You have debugger / repl sessions.
       
      You can't save or replay your findings. Once the debugger is off the only thing that you have are:  
        breakpoints and maybe configured watchwindow.  
      You can't run automatic checks once the debugger is up, you have to manually watch and step debug it again.  
    
  My issues is that this is a tragic waste of human resources.  
  And if you use AI, computing resources, I don't care.  
    
  Debuggers are excelent way to find a bug or get in touch with your program.  
  Test suits are great to prevent stupid mistakes.  
    
  Both paradigms should not compete with each other and testing frameworks should debug stuff.

- **Light desktop runtime for canvas heavy apps.**
    
  Canvas2D is a perfect tech for developing a small game or some interactive utility.  
  There are easy ways to host an interactive application written for desktop: WASM compilation target.  
    
  I need something in reverse: runtime, maybe integrated with good debugger.  
  That lets you get off from the web but doesn't require turning your app into 200MB electron chromium monster.
    
  Would be nice if it can switch between js implementations and canvas implementations of real browsers.  
  I want to test things without constant switching between browsers.
    
- **Chrome / firefox devtools but in command line.**
    
  At least a debugger. What I have tried looks, works and feels like shit.  
  I should have a proper cli repl for chrome. I should grep and search objects, tabs and iframes.
  It should be way simpler and more intuitive than using CDP directly.

## Programming Languages 

- **Low level very interactive lisp.**
    
  Like racket, but where scope is not #lang, but #device.  
  So that you can kinda hack with devices. Run them actually or emulate and debug.
    
  It should also adopt very educative nature of racket. But maybe less academic.
    
  I have a very messy and chaotic [sketch](https://sunfora.github.io/sicp/extra/devices.html) on how would it look like.  
  Which I have wrote in 3 days. But a lot of design work and implementation must be done prior.
    
  I am no expert in low level computing and that is kinda the reason I need it.  
  C is very much not very friendly language, all the ceremony around pogramming asm is kinda crazy.  
  Things should be more interactive than they are now.  
    
  I have tried to use debuggers in the past (the good experience was raddbg) and C interpreters: cling, clang-repl (they were pretty bad).
  But I wish it was even more lispy.
