Structure: 
 - repoGMWN contains the multi-party GMW case study (in the lib folder) and the sources needed to run it (in the src folder). Run 
   maude lib/gmwN.maude
 in the repoGMWN folder. The proof takes approx. 18 seconds so you will need to wait for a result.
 - case-studies contains
    - the auth-to-secure case study in auth-to-secure.ipdl
    - the DHKE-OTP case study in dhke-otp.ipdl
    - the multi-party coin toss case study in coin-toss.ipdl
 - the archive IPDL.zip contains the source code 
 and the same case studies as in the folder case-studies. 
 To run them, extract the archive, cd to IPDL/src and run
  maude -no-banner -allow-files run-SpeX
 then at the resulting prompt enter  
  load dhke-otp.ipdl
 or 
  load auth-to-secure.ipdl  
 or
  load coin-toss.ipdl
 Note that the latter is a strict equality proof and therefore no bounds are displayed.
