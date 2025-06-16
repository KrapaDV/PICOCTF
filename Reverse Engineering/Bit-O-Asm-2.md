## PICOCTF

# Reverse Engineering

# Bit-O-Asm-1
  When we download the given file, in the 6th line wee find '<+15>:    mov    DWORD PTR [rbp-0x4],0x9fe1a'. We need to convert 0x9fe1a from hex to decimal to get our flag. 0x9fe1a  in decimal is 654874.
  .
# Flag
  picoCTF{654874}