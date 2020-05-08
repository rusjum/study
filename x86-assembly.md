I started with "Intro to X86" crash [course](https://youtu.be/H4Z0S9ZbC0g). Watched first lecture. 

Key ideas:
1. Not that many assembly commands are actually used; 14 instructions account for 90% of code.
2. Byte (8 bits) -> Word (16) -> DoubleWord (32) -> QuadWord (64)
3. Conventions - callee and caller saved registers, EFLAGS
4. Push and Pop ops - add/remove 4 bytes to/from stack, decrement/increment ESP (stack pointer register)
5. Call conventions: 
  - cdecl
  - stdcall
