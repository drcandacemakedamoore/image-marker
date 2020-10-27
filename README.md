This is a program my husband and I created to examine texture in radiological imaging. 
The program can analize DICOM files or even JPEGS. 
The program then computes some parameters of texture within the area chosed.
Although I orginically created the program for abdominal imaging, the areas can be changed to suit whichever ones a researcher would want by simply changing the code a bit. 
I have placed a version on Zenodo.-
Practical instructions for non-computer professionals without a strong background in computers:

0.Download the program onto you computer. 
Figure out what kinds of computer system you want to run the program on- Windows? Linux? Max OS?
Chances are high that if you do not have a strong background in computers you are running Windows or a Mac OS, and you do not have the neccesary libraries to make the program functional. You will need to download Anaconda as well. 

If you want step by step instructions for non-programmers using Windows- go here![howto](howto/howto.org)
Download Anaconda from https://www.anaconda.com/

1. Start the Anaconda shell
1.5 realize these instructions are bad...you need to create and environment and tehn run setup.py--but this is near impossible without an infrastructure-aware programmer looking at your specific computer. Continue at your own risk of frustration
WRITE ME HOW THIS WORKS_ I WILL GET BACK TO YOU AND HELP YOU FIX THE PROBLEMS WITHIN 49 hours
2. In Anaconda shell activate the program's environment by typing:
   conda activate image-marker
3. Previous action should have changed the prompt from saying "(base)"
to "(image-marker)".  Now, to switch current directory to D drive, type:
   d:
   
4. Now type:
   cd myprograms
   to switch to "myprograms directory" on D drive.
5. Now you should be able to deploy the program or start the server. To deploy the program type:
   python setup.py install
6. To run the program (start the server).Type:
     python bin\imarker
6. Once the server starts, it will print to the terminal the host and
address it is listening on.
   By default, it is "localhost:8080".  Navigate your browser to that
address to see the
   program's interface.
7. From your browser on localhost 8080 the program will appear- and has internal instructions on the interface.   
   
   8. If this does not work out for you please email me at doctormakeda@gmail.com ; you can also send complaints, suggestions and so on, please include what kind of system you are running (Windows? Mac? and the browser you opened the program in)...
