# COBOL
COBOL was built in the late 1950s and early 1960s by CODASYL, the Conference on Data Systems Languages.
At the time, the cost of programming for businesses and governments was extremely high.
To combat rising costs, the conference formed and asked the United States Department of Defense to sponsor their efforts to create a common "business language" for most computer programs to run on. The initiative hoped to save time in developing and translating existing programs. 
Considering the Department of Defense had already spent hundreds of millions of dollars (USD) for programming for their computers, they agreed to sponsor the conference.
Eager to begin, the conference started its work, eventually coming up with the language known as COBOL, an acronym for "Common Business-Oriented Language".

COBOL is a compiled programming language with syntax inspired by English.
It was used across industries, for purposes like accounting, insurance processing, and banking systems.
Today, the language has majorly declined, with many COBOL programmers retiring. In fact, most of the COBOL programmers still active today work to maintain existing systems that may be too costly or complicated to rewrite. You might not think it, but this means that COBOL programmers are still in demand today by financial and government institutions.

<figure style="float: right; width:30%; height:50%; object-fit:contain;">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/27/COBOL_Report_Apr60.djvu/page1-780px-COBOL_Report_Apr60.djvu.jpg" alt="A photocopy of the front page of the Department of Defense's 1960 report to CODASYL.">
<figcaption>A photocopy of the front page of the Department of Defense's 1960 report to CODASYL.</figcaption>
</figure>

# Nerd Stuff
COBOL is an imperative and procedural programming language. Simply put, COBOL uses statements (commands) that tell the computer exactly what to do, and these commands can be split into procedures (functions) that are called throughout execution.

With more than 300 keywords (think `AND`, `OR`, etc.), it was designed to be highly verbose.

COBOL has been expanded upon for decades. In fact, in 2002, it was expanded to become object-oriented (although this standard has been poorly and inconsistently supported). Many implementations of COBOL exist, including those by [IBM](https://developer.ibm.com/languages/cobol/) and [FSF](https://gnucobol.sourceforge.io/).

# Ecosystem
There is no standard application for executing COBOL code, although [OpenCobolIDE](https://pypi.org/project/OpenCobolIDE/) is rather popular.

# Examples
The following is an example of a "Hello World!" program in COBOL.
Note that this may work on some COBOL implementations, but not others (this depends on syntax strictness and what standard is being implemented).
The difference is what makes it fun (or something like that)!
```
IDENTIFICATION DIVISION.
PROGRAM-ID. HELLO.
ENVIRONMENT DIVISION.
DATA DIVISION.
PROCEDURE DIVISION.
     DISPLAY "Hello World!"
     STOP RUN.
```

# Stats
This language may not be that well-liked or popular today, but it's still in wide use!
A 2017 [Reuters Report](https://fingfx.thomsonreuters.com/gfx/rngs/USA-BANKS-COBOL/010040KH18J/) found that there are still over 220 billion lines of COBOL in use today.
In fact, a large percentage of the banking system still relies on COBOL code too.
Recent interest in its application in other areas has driven a small uptick in popularity, but for the most part it has died down. This is also seen by the fact that most COBOL programmers are in likely to be in their fifties today.
