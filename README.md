# ASCADA-2.0-DemoRelease
The ASCADA is designed for quick and easy design of systems for visual control of process parameters 
transmitted from microcontrollers or industrial controllers using serial ports.
It is used in home solutions for displaying and automating various parameters, 
as well as when debugging microcontroller software (for simple visual control of setting parameters).

Copyright (C) MikeKozlovAVR Kozlov M. 
29.03.2022


  EXAMPLE of a simple Data Pack transmitted via COM-port to ASCADA:
  "0&100*"           - in this example data pack we transmitted int/float value "100" to Tag ID=0, "&" - sympol-splitter, " * " - symbol End of data pack;
  "19&Hello World*"  - in this example data pack we transmitted string value "Hello World" to Tag ID=19;
  "1&1*"             - in this example data pack we transmitted bool value "true" to Tag ID=1;
  "1&0*"             - in this example data pack we transmitted bool value "false" to Tag ID=1;
  "234&1958,59*"     - in this example data pack we transmitted float value "1958,59" to Tag ID=234;
  
  Attention: When transferring data, observe the correctness of the transferred data and the used data type of the Tag.
  Please, if you notice a bug or have suggestions for improving the interface of this program, then please write to me about it by mail: kozlovmikhail8@gmail.com

  Sincerely, Kozlov M.
