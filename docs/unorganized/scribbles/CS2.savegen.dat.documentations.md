savegen.dat
(CatSystem2 Savegen Header Signature "CSS")
===================================================================
  Offset: | 00 01 02 03 | 04 05 06 07 | 08 09 0A 0B | 0C 0D 0E 0F | 
-------------------------------------------------------------------
00000000: | 43 53 53 00 | 37 05 00 00 | 88 0E 00 00 | 10 00 00 00 |
          | "CSS"       | 1335        | 3720        | 16          |
          |(file sig)   |(orig len)   |(compr len)  |(off/hdr len)|
-------------------------------------------------------------------
00000010: | 78 DA .. .. | .. .. .. .. | .. .. .. .. | .. .. .. .. |
          | "xZ"        |             |             |             |
          |(deflate hdr)|             |             |             |
-------------------------------------------------------------------
00000020: | ...