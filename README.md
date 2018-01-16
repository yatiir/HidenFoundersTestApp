# HidenFoundersTestApp

this app it's using a webservice to display some informations, 
so when the starts i start a service where i can get the data using a thread, when i recieve that i send a broadcast to the main activity in order to display informations, while the data is coming on webservice in the main activity user can see a progresse bar until a get data then i hide the progess bar and show the data list. 

when u scroll down and u're about to end the first group of data that i get from webservice, i reuse the same webservice to get more data ( pagination ) and while the data is coming i show the same progresse bar until i recieve a broadcast informing me that the data it's ready to be shown, so i hide the progress bar and show the data that i get using notifydatasetchanged

the app file is zipped 

Thanks
Yassine.
