# LotjSoftware  
Import the files you wish and read below how to use them  
  
## Jump intercept (jint)  
To use simply type  
jint shipname  
this will attempt to calculate and jump you to an intercept  
it is recommended you turn off any auto radars first  
if you wish to cancel a jint simply tipe  
jintclear  
  
## Generate encyrption (genenc)  
simply uses the channel as a seed and gives output after a number of runs has passed  
genenc 812,0   will output 812 082 every time allowing for reliable encryptions of channels  
genenc 812,1   will output 812 584  
and so on, can be used like the operation has a standard rot 5, navy wants to use channel 050  
so they all can run  
genenc 050,5 and all get 050 35  
as you can change the "standard rot" every day and put in clanmotd this can provide more secure  
channels of communication  
