Tiny Core Linux (TCL) port of IMAP Server

Based on Washington University IMAP Server release
  Source: ftp.cac.washington.edu/imap/
  Mirror: https://www.mirrorservice.org/sites/ftp.cac.washington.edu/imap/

Please read the README first.

The build is:

  1. Set the dependacies
     For TCL it's

       tce-load -i[w] openssl-dev

  2. make slx

On successful compilation, the IMAP server should be 'imapd/imapd' and
POP2/POP3 in 'ipopd' folder (not stripped) and other tools in pertinent
folders. Depending on your scenario, you might do installation as
described in the README.
