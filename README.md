# Software I wish existed

## Tools for the developers

- A proper interactive Canvas 2D debugger.  
    
  Canvas has been around for quite a while. A lot of stuff can be done with it.  
  But it is lacking, and the first thing is that it is essentially a black-box.  
    
  You create a path and you don't see it. You can't test things.  
  Chrome doesn't even let you see what is drawn when you step debug inside [requestAnimationFrame](https://developer.mozilla.org/en-US/docs/Web/API/Window/requestAnimationFrame).  
    
  Although perfectly valid thing to do, from the DX it is a total nightmare.  
  I have vibecoded some shitty debugger specifically for chrome in case I need to debug in it.  
  But right now I spend my time in firefox.
    
- **Universal debugger**
    
  There are tons of languages, runtimes weird tech stacks used DAILY in our projects.  
  It is hard to setup debuggers let alone use them.
    
  They do not compose nicely today, but they absolutely should.  
  I should see everything: from TCP down to PHP VM opcodes and raw assembly my machine is crunching.  
  Without complicated setup. Error prone to specific project.
    
  Currently I use vscode (and editor) with DAP to perform debugging.  
  But it is a bad solution to a hard problem. Universal debugger should be much more transparent, simpler to use.  
  And it should allow you to inspect different VM's.
    
- **Testing framework integrateed with debugger**
    
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

- **Light desktop runtime for canvas heavy apps**
    
  Canvas2D is a perfect tech for developing a small game or some interactive utility.  
  There are easy ways to host an interactive application written for desktop: WASM compilation target.  
    
  I need something in reverse: runtime, maybe integrated with good debugger.  
  That lets you get off from the web but doesn't require turning your app into 200MB electron chromium monster.
    
  Would be nice if it can switch between js implementations and canvas implementations of real browsers.  
  I want to test things without constant switching between browsers.
