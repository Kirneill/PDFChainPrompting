READ ME:
(I RECOMMEND DOWNLOADING NOTEPAD++ or Sublime Text for windows)
-> PUT PDF OR TEXT YOU WANT TO SCAN IN PDF-> 
-> CLEAR OUT TEXTPDF FOLDER IF YOU RAN ANYTHING PRIOR (JUST MOVE TO ANOTHER FOLDER IF ANYTHING)
-> in WRITE_PDF.py, you need to change a few things:

1. Enter OpenAPI key where it says "ENTER API KEY HERE"
2. Change Pathfolder based on where you save your file.
It just needs to know the folder to search.
3. Change chunks = textwrap.wrap(alltext, "THIS NUMBER HERE")
if you get over the token limit error (rare, larger papers do this)
