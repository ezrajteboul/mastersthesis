Instructions:

1) Download a Tex editor.  (TexWorks is a popular free choice.  Also of note is a Tex plugin for Eclipse, which is nice because it enables easy navigation through the thesis with an outline tool, and uses other nice features of Eclipse.  The best is Bakoma Tex, but it costs a hundred bucks; Bakoma enables you however to edit directly into a pdf, bypassing laborious coding.)

2) Open the docVars.tex file.  Replace the document variables (e.g. where it says "Title Here") with your own details.  Most of the front matter stuff for the thesis should be placed in using these variables.

3) If you have additional front matter you'd like to add (e.g. a list of abbreviations), or would like to remove certain pages (e.g. the quotation page) edit the main.tex file.  

4) Set up a rough chapter structure.  Open the Chapters folder, copy the Chapter Template a few times and rename them to a few rough chapter titles (e.g. Background, etc.).  You may divide these chapters into several parts, each with its own folder, if desired. (Delete the sample chapters; they are there just to suggest a file and naming structure to use, though the introduction tex file you should first read, it has some details on using this template)

5) Open the chapterOrdering.tex file and use the \part{partTitle} and \input{chapterTitle} commands to set up the thesis structure/order.  (Delete the old sample ordering)

6) Open each chapter tex file you created in chaper 4 and write.  (Consult the 0-introduction.tex file for some basic pointers.)

7) Whenever you'd like to see a pdf of your code, use your tex editor to compile; it will generate your doc as main.pdf


OTHER:
* To adjust formatting of the title page (clear whatever format you use with the grad studies administrative assistant, presentl Ruth Dube), open titlePage.tex

* To add other packages, best to add them into the Thesis.cls file.

* In the docVars.tex file, there are two flags you can set: one that indicates if the pdf is for printing (\papertrue) or viewing electronically (\paperfalse); the other if the thesis is finished (\finaltrue) or still in progress (\finalfalse), telling whether or not to display the DRAFT watermark.  I recommend you remove the "Draft" watermark only when you're truly finished, to avoid confusion if the doc were to get distributed.