Alpha
=====

This is a repository of legal documents organized as source texts, and "Deal" docs that use them. 

To get going, you need to pull this repository and then launch a command line, go to your folder, then run the perl script.  

E.g.:

perl parser2.pl Doc/Test/Render_Me.txt > Doc/Test/Output.html

With your browser, view that output file:  {YourRoot}/Doc/Test/Output.html.  

To render different docs, edit Render_Me.txt - putting a line like the following near the top of the file:

=[Path/Name_of_Doc]

Parsing starts by looking for the first "Model.Root=foo", where foo can be or contain an {expression} to expand. 

* fflb={Fruit} flies like {bananas}.
* Fruit=Time
* Model.Root={fflb}
* bananas=an arrow

This parser is totally rudimentary and has a few known bugs.  But it lets us write legal forms in their source format and start on the job of making a form book for everyone. 


A few highlights:

* Doc/Forms/AGT/Acquisition/ABA_MSPA/ is a mine of excellent drafting.
* Doc/Deal/ has a number of examples.  (We need to build out the collection of persons.)

Questions?  
  Primavera and Jim - contact@commonaccord.org
