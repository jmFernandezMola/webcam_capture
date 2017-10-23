# webcam_capture
Per treballar amb aquest repositori s'ha fet:
* Primer cal assegurar-se que es té el repositori del *cmake* instal·lat. Per instal·lar-lo cal escriure al terminal:

  `sudo apt-get install cmake`


* També s'han instal·lat les llibreries del *openCV*. Per fer-ho:

  `sudo apt-get install libopencv-dev`
  

* S'ha fet un *fork* del repositori https://github.com/beta-robots/webcam_capture
* Aquest repositori cal clonar-lo al propi PC per poder treballar-hi. Primer cal situar-se a la carpeta on es vol fer el repositori  i a continuació s'escriu al terminal:

  `git clone 
https://github.com/my_github_name/webcam_capture.git`


* Si les llibreries s'han instal·lat correctament, per instal·lar el programa cal situar-se a la carpeta on s'ha fet el clone i a continuació:

  ` $ mkdir build`
  
  ` $ cd build`
  
  ` $ cmake ..`
  
  ` $ make`
  
    
* Si tot ha anat bé, el programa s'executa amb la instrucció `./webcam_capture`
* Per tancar-lo cal fer un `Ctrl + C`
