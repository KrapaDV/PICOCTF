# PICOCTF

## Binary Exploitation

## Format String 0
  Connectinf to the server using 'nc mimas.picoctf.net 60350' we get a menu option to choose from. The question is named format String 0 so it has to do something with format specifier. In the 1st options we find 'Gr%114d_Cheese' here we have a format specifier. When provided next set of questions we have 'Cla%sic_Che%s%steak' which has format specifiers. when we choose it it gets us our flag.

# Flag
  picoCTF{7h3_cu570m3r_15_n3v3r_SEGFAULT_f89c1405}