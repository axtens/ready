# ready
Tools written for the TSRBASIC compiler

TSRBASIC can be found at [The Programmer's Corner](https://www.pcorner.com/list/BASIC/TSRBASIC.ZIP/INFO/) -- The Programmer's Corner BBS Archive from the Past.

TSBASIC could be used to make TSR (Terminate Stay Resident) programs but I never used it for that. I was just happy to have a "compiler" that would bind itself to my scripts and give me EXE command line tools.

One of the downsides of TSRBASIC was its insistence on line numbers. I found some code that would let me mark GOTO and GOSUB destinations with labels in square brackets. You can see that code in READY.RDY. So I would make a READY.EXE which would convert scripts written in .RDY format into .BAS format and then hand the off to TSRBASIC.EXE for binding.

This was back in 1993. After that I discovered Modula-2 and started converting everything to that. The idea was to convert all these tools to Modula-2. That conversion started but didn't finish and likely never will.
