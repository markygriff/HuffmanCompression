# Running the Compressor
Execute the compress.py script to compress files. 

For example, to add a new file somefile.pdf to be served by the web server, copy it to the wwwroot/ directory, 
change to that directory, and run 'python3 ../compress.py somefile.pdf'

This will generate somefile.pdf.huf and you will be able to access the decompressed version at the URL http://localhost:8000/somefile.pdf.
