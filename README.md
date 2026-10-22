```
╔══════════════════════════════════════════════════════════════════╗
║  GABRIEL MIRANDOLA                             SUEDTIROL, ITALY  ║
║  ──────────────────────────────────────────────────────────────  ║
║  COMPILERS · LOW-LEVEL · EMBEDDED                 [ 1986 BAUD ]  ║
╚══════════════════════════════════════════════════════════════════╝

C:\> dir

 VOLUME IN DRIVE C IS GABRIEL
 DIRECTORY OF C:\

ABOUT    TXT       1 file
TOOLS    TXT       1 file
LINKS    TXT       1 file
KLYF         <DIR>
TELETABLE    <DIR>
SILLIES      <DIR>


C:\> type ABOUT.TXT

I wrote a compiler so I'd have a new language to blame.


C:\> cd KLYF
C:\KLYF> type README.TXT

KLYF: own language + compiler            [C#, LLVM]

  source --> lexer --> parser --> semantic (lazy) --+--> own back-end
                                                     +--> LLVM

  Lock-free, CAS-based compiler. Written in C#.
  Will one day compile itself.
  Front-end ~85%, the rest in progress. Open source after v1.


C:\KLYF> cd ..\TELETABLE
C:\TELETABLE> type README.TXT

TELETABLE: autonomous transport vehicle  [ESP32, Fusion 360]

  A small autonomous vehicle that drives to where you tell it to.
  Hardware, chassis and CAD by me.

  github.com/TeleTable-StartUp-Lab


C:\TELETABLE> cd ..\SILLIES
C:\SILLIES> type README.TXT

SILLIES: file compression app            [C#, C, x64 asm]

  Compression, in three languages, one of them assembly.

  codeberg.org/RampantCat/Sillies


C:\SILLIES> cd ..
C:\> type TOOLS.TXT

C# · C · C++ · Java · x64 asm · LLVM · Linux · Docker · Git


C:\> type LINKS.TXT

gabrielmirandola.com


C:\> _
```
