# CBT602
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 602 is from Mike Newell and contains two REXX execs and   *   FILE 602
//*           accompanying panels for one of them.  The two         *   FILE 602
//*           applications are called LSPCR and PUT.                *   FILE 602
//*                                                                 *   FILE 602
//*           email:  sbgolob.attglobal.net  (for questions)        *   FILE 602
//*                                                                 *   FILE 602
//*      This file consists of a pds which contains a couple of     *   FILE 602
//*      REXX execs and their associated ISPF panels and            *   FILE 602
//*      documentation.                                             *   FILE 602
//*                                                                 *   FILE 602
//*      The two REXX execs are called PUT and LSPCR.               *   FILE 602
//*                                                                 *   FILE 602
//*      PUT is an edit macro which lets you PUT lines from a       *   FILE 602
//*      dataset or pds member that you are editing into another    *   FILE 602
//*      dataset or PDS member. I used to do a lot of work on       *   FILE 602
//*      VM/CMS, and made good use of the CMS PUT command, so I     *   FILE 602
//*      decided to create a version for ISPF.                      *   FILE 602
//*                                                                 *   FILE 602
//*      LSPCR is a REXX exec that executes the TSO LSPACE          *   FILE 602
//*      command and displays the output in a scrollable panel.     *   FILE 602
//*      You can sort the panel display on one of several           *   FILE 602
//*      fields. The scrollable panel is a lot easier to read       *   FILE 602
//*      than the output from the TSO command.                      *   FILE 602
//*                                                                 *   FILE 602
//*      An XMIT for a load library containing the LSPACE and       *   FILE 602
//*      LSPC TSO commands has been included in this pds, as        *   FILE 602
//*      member LSPC.  You need only execute a TSO RECEIVE          *   FILE 602
//*      command against this member (see member $$NOTE1 for        *   FILE 602
//*      instructions), to get a load library containing the        *   FILE 602
//*      LSPACE TSO command (source from File 136) and its          *   FILE 602
//*      alias LSPC.  These may then be copied to the               *   FILE 602
//*      TSO-accessible load library of your choice.                *   FILE 602
//*                                                                 *   FILE 602
```
