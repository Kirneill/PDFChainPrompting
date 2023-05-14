Add folders:

textPDF | PDFs

Step-by-step:

0. Converts the PFD file into a .txt file
1. Slice the 73 000 word into chunks of text
2. Summarize the chunks
3. Merge all the chunks
3. Write a new summary of the merged chunks
4. Write Key Notes from the summary
5. Write a Step-by-Step Guide from the Notes
6. Summarize the Notes in a the bare essencials of the book
7. Write a Blog post from the notes
8. Create Midjourney prompts from the notes or illustrations

# Personal Notes:
(I RECOMMEND DOWNLOADING NOTEPAD++ or Sublime Text for windows)
-> PUT PDF OR TEXT YOU WANT TO SCAN IN PDF-> 
-> CLEAR OUT TEXTPDF FOLDER IF YOU RAN ANYTHING PRIOR (JUST MOVE TO ANOTHER FOLDER IF ANYTHING)
-> in WRITE_PDF.py, you need to change a few things:

1. Enter OpenAPI key where it says "ENTER API KEY HERE"
2. Change Pathfolder based on where you save your file.
It just needs to know the folder to search.
3. Change chunks = textwrap.wrap(alltext, "THIS NUMBER HERE")
if you get over the token limit error (rare, larger papers do this)


