# CBT162
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 162 IS FROM DAVE COLE WHO IS NOW AT COLE SOFTWARE IN      *   FILE 162
//*           CHARLOTTESVILLE VIRGINIA.  THIS FILE CONTAINS A COPY  *   FILE 162
//*           OF A GLOBAL CROSS-REFERENCE LISTING GENERATOR CALLED  *   FILE 162
//*           XREFASM.  THIS FILE IS IN IEBUPDTE SYSIN FORMAT.      *   FILE 162
//*           THE MACROS NEEDED FOR THIS CODE ARE CONTAINED IN      *   FILE 162
//*           FILE 408 OF THIS TAPE.   PLEASE SEE BELOW FOR         *   FILE 162
//*           ADDITIONAL INFORMATION ON XREFASM.                    *   FILE 162
//*                                                                 *   FILE 162
//*    Dave Cole has updated most of his contributions, and         *   FILE 162
//*    they are available for direct download from his web          *   FILE 162
//*    site at www.colesoft.com.  The following list of             *   FILE 162
//*    his software is currently available there:                   *   FILE 162
//*                                                                 *   FILE 162
//*         Cole Software LLC's File Upload/Download Area           *   FILE 162
//*                                                                 *   FILE 162
//*       The following shareware is available for download         *   FILE 162
//*                                                                 *   FILE 162
//*      Filename   Platform            Description                 *   FILE 162
//*    asm2zap.zip   z/OS      A utility for converting an          *   FILE 162
//*                            assembly listing into SUPERZAP       *   FILE 162
//*                            cards.                               *   FILE 162
//*                                                                 *   FILE 162
//*    blksptrk.zip  z/OS      A TSO command that computes and      *   FILE 162
//*                            displays track capacities for any    *   FILE 162
//*                            IBM DASD device for any BLKSIZE,     *   FILE 162
//*                            with or without key fields.          *   FILE 162
//*                                                                 *   FILE 162
//*    macros.zip    z/OS      A set of Assembler/390 macros        *   FILE 162
//*                            needed for assembling the various    *   FILE 162
//*                            programs available from Cole         *   FILE 162
//*                            Software LLC.                        *   FILE 162
//*                                                                 *   FILE 162
//*    schedrun.zip  z/OS      A set of MVS programs for            *   FILE 162
//*                            scheduling the execution of System   *   FILE 162
//*                            Operator Commands on an interval     *   FILE 162
//*                            or calendar basis. Can be used to    *   FILE 162
//*                            control production scheduling.       *   FILE 162
//*                                                                 *   FILE 162
//*    xrefasm.zip   z/OS      A pair of programs for producing     *   FILE 162
//*                            master cross-reference listings      *   FILE 162
//*                            for multi-assembly programs.         *   FILE 162
//*                                                                 *   FILE 162
//*          Colesoft Marketing, Inc.                               *   FILE 162
//*          414 3rd ST. NE                                         *   FILE 162
//*          Charlottesville, VA 22902 USA                          *   FILE 162
//*          540-456-8210                                           *   FILE 162
//*          www.colesoft.com                                       *   FILE 162
//*          email:  dbcole@gmail.com                               *   FILE 162
//*                                                                 *   FILE 162
//*          MANY LARGE PROGRAMMING SYSTEMS ARE CONSTRUCTED         *   FILE 162
//*       FROM A LARGE NUMBER OF SEPARATELY ASSEMBLED OR            *   FILE 162
//*       COMPILED SECTIONS.  SUCH SYSTEMS MUST MANAGE              *   FILE 162
//*       INTERNAL COMMUNICATIONS BY MEANS OF A SET OF VECTOR       *   FILE 162
//*       TABLES AND OTHER CONTROL BLOCKS THAT ARE KNOWN TO         *   FILE 162
//*       EACH OF THE SEPARATE SECTIONS; WHICH IS TO SAY, SUCH      *   FILE 162
//*       CONTROL BLOCKS MUST CONTAIN FIELDS THAT MAY BE            *   FILE 162
//*       REFERENCED AND/OR CHANGED BY ANY OR ALL OF THE            *   FILE 162
//*       SECTIONS.  ACCORDINGLY, A GLOBAL CROSS-REFERENCE          *   FILE 162
//*       LISTING, REPORTING WHICH SECTIONS REFERENCE WHICH         *   FILE 162
//*       FIELDS, IS A VERY USEFUL TOOL FOR A LARGE-SYSTEMS         *   FILE 162
//*       DEVELOPER TO HAVE.                                        *   FILE 162
//*                                                                 *   FILE 162
//*          XREFASM IS A RELATIVELY SIMPLE SYSTEM THAT             *   FILE 162
//*       GENERATES SUCH GLOBAL CROSS-REFERENCE LISTINGS.           *   FILE 162
//*       SPECIFICALLY, XREFASM GENERATES A REPORT SHOWING A        *   FILE 162
//*       SORTED LIST OF ALL LABELS USED IN A GIVEN SET OF          *   FILE 162
//*       SEPARATE ASSEMBLIES OR COMPILATIONS.  THE ENTRIES         *   FILE 162
//*       FOR EACH LABEL SHOW BOTH WHICH ASSEMBLIES (OR             *   FILE 162
//*       COMPILATIONS) REFERENCE THAT LABEL AND HOW MANY           *   FILE 162
//*       REFERENCES EACH ASSEMBLY HAS TO THAT LABEL.               *   FILE 162
//*                                                                 *   FILE 162
```
