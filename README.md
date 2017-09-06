# CV into LATEX

This one is my resume into LaTex. <a href="https://latex-project.org/guides/" target="\_blank">LaTex</a> is a markup language very convenient to build awesome documents as for example resumes or scientific papers.

## Using desktop tool (Mac Os X):

In my case I have used <a href="http://pages.uoregon.edu/koch/texshop/" target="\_blank">TeXShop</a> to work in Mac Os X. When this software is installed also are installed all libraries necessary to compile any 'tex' file. 

It is possible work with this graphical tool but also It is possible improve a 'text' document with your favorite editor and compile directly from terminal.

In order to compile from terminal to get a PDF output it is necessary use:

<pre><code data-trim class="bash">
$ pdflatex document.tex
</code></pre>

## Using command lines (Ubuntu):

A very flexible way is using Linux command lines to compile a LaTex project. This way has been chosen because I am starting to update my CV from a cloud server. 

Firstly it is necessary install a TeX distribution. TeX Live is a TeX distribution to get up and running with the TeX document production system. To install it, once you're in the terminal, enter the following command:

<pre><code data-trim class="bash">
$ sudo apt-get update
$ sudo apt-get install texlive-full
</code></pre>




In order to compile the LaTex project would be simply using the command:

<pre><code data-trim class="bash">
$ latext file.tex
</code></pre>

However, there are many interesting options which should be reviewed using the "help" option:

<pre><code data-trim class="bash">
$ latext --help

#######################################################################
Usage: pdftex [OPTION]... [TEXNAME[.tex]] [COMMANDS]
   or: pdftex [OPTION]... \FIRST-LINE
   or: pdftex [OPTION]... &FMT ARGS
  Run pdfTeX on TEXNAME, usually creating TEXNAME.pdf.
  Any remaining COMMANDS are processed as pdfTeX input, after TEXNAME is read.
  If the first line of TEXNAME is %&FMT, and FMT is an existing .fmt file,
  use it.  Else use `NAME.fmt', where NAME is the program invocation name,
  most commonly `pdftex'.

  Alternatively, if the first non-option argument begins with a backslash,
  interpret all non-option arguments as a line of pdfTeX input.

  Alternatively, if the first non-option argument begins with a &, the
  next word is taken as the FMT to read, overriding all else.  Any
  remaining arguments are processed as above.

  If no arguments or options are specified, prompt for input.

-draftmode              switch on draft mode (generates no output PDF)
-enc                    enable encTeX extensions such as \mubyte
-etex                   enable e-TeX extensions
[-no]-file-line-error   disable/enable file:line:error style messages
-fmt=FMTNAME            use FMTNAME instead of program name or a %& line
-halt-on-error          stop processing at the first error
-ini                    be pdfinitex, for dumping formats; this is implicitly
                          true if the program name is `pdfinitex'
-interaction=STRING     set interaction mode (STRING=batchmode/nonstopmode/
                          scrollmode/errorstopmode)
-ipc                    send DVI output to a socket as well as the usual
                          output file
-ipc-start              as -ipc, and also start the server at the other end
-jobname=STRING         set the job name to STRING
-kpathsea-debug=NUMBER  set path searching debugging flags according to
                          the bits of NUMBER
[-no]-mktex=FMT         disable/enable mktexFMT generation (FMT=tex/tfm/pk)
-mltex                  enable MLTeX extensions such as \charsubdef
-output-comment=STRING  use STRING for DVI file comment instead of date
                          (no effect for PDF)
-output-directory=DIR   use existing DIR as the directory to write files in
-output-format=FORMAT   use FORMAT for job output; FORMAT is `dvi' or `pdf'
[-no]-parse-first-line  disable/enable parsing of first line of input file
-progname=STRING        set program (and fmt) name to STRING
-recorder               enable filename recorder
[-no]-shell-escape      disable/enable \write18{SHELL COMMAND}
-shell-restricted       enable restricted \write18
-src-specials           insert source specials into the DVI file
-src-specials=WHERE     insert source specials in certain places of
                          the DVI file. WHERE is a comma-separated value
                          list: cr display hbox math par parend vbox
-synctex=NUMBER         generate SyncTeX data for previewers if nonzero
-translate-file=TCXNAME use the TCX file TCXNAME
-8bit                   make all characters printable by default
-help                   display this help and exit
-version                output version information and exit

#######################################################################
</code></pre>


## WRITING LATEX DOCUMENTS:

The last thing to take account is the marked syntax to write an awesome document. Learn to use this syntax practice and a good  <a href="https://wch.github.io/latexsheet/latexsheet.pdf" target="\_blank">LaTex cheat sheet</a> . 
