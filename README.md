This is a program I created to examine texture in radiological imaging. 
The program can analize DICOM files or even JPEGS. 
The program then computes some parameters of texture within the area chosed.
Although I orginically created the program for abdominal imaging, the areas can be changed to suit whichever ones a researcher would want by simply changing the code a bit. 
-
Practical instructions for non-computer professionals without a strong background in computers:

0.Download the program onto you computer. 
Figure out what kinds of computer system you want to run the program on- Windows? Linux? Max OS?
Chances are high that if you do not have a strong background in computers you are running Windows or a Mac OS, and you do not have the neccesary libraries to make the program functional. You will need to download Anaconda as well. 
Download Anaconda from https://www.anaconda.com/

1. Start the Anaconda shell
2. The first time you run it, you will need to create `conda` environment:
   ``` sh
   conda create -n image-marker
   ```
   For more information on Anaconda environments see: 
   https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/
3. In Anaconda shell activate the program's environment by typing:
   conda activate image-marker
4. Previous action should have changed the prompt from saying "(base)"
to "(image-marker)".  Now, to switch current directory to D drive, type:
   d:
   
5. Now type:
   cd myprograms
   to switch to "myprograms directory" on D drive.
6. Now you should be able to deploy the program or start the server. To deploy the program type:
   python setup.py install
7. To run the program (start the server).Type:
     python bin\imarker
8. Once the server starts, it will print to the terminal the host and
address it is listening on.
   By default, it is "localhost:8080".  Navigate your browser to that
address to see the
   program's interface.
9. From your browser on localhost 8080 the program will appear- and has internal instructions on the interface.   
   
10. If this does not work out for you please email me at doctormakeda@gmail.com ; you can also send complaints, suggestions and so on, please include what kind of system you are running (Windows? Mac? and the browser you opened the program in)...
