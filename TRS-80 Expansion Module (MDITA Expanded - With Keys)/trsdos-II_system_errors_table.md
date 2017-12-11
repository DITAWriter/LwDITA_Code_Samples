---
id: trsdos_II_system_errors_table
shortdesc: List of the possible TRSDOS-II error messages you may encounter when using the <span data-keyref="computer_model" />.
author: Wilson Rodriquez
---

# TRSDOS-II System Errors Table

| Code | Message | Explanation/Action |
|-------|---------|--------------------|
| 0 | No Error Found. | No error occurred. |
| 1 | Bad Function Code On SVC Call Or No Function Exists. | Check the function code number used on the SVC call. |
| 2 | Character Not Available. | No record or character was available when you you called the SVC. |
| 3 | Parameter Error On Call. | Parameter is incorrect or a required parameter is missing. |
| 4 | CRC Error During Disk I/O. | Try the operation again, using a different diskette. If the problem occurs often, contact RSSC. |
| 5 | Disk Sector Not Found.   | Try a different diskette. |
| 6 | Attempt To Open A File Which Has Not Been Closed. | Close the file before re-opening. | 
| 7 | Illegal Disk Change. Disk Drive Not Ready. | TRSDOS-II detected an illegal disk swap. |
| 8 | Disk Drive Not Ready. | Drive door is open or the diskette is not in the drive. On Thinline drives, check the DRIVE command settings. |
| 9 | Invalid Data Provided By Caller. | Data stream to be processed has illegal characters. |
| 10 | Maximum Of 16 Files May Be Open At Once. | Too many files are open at once. |
| 11 | File Already In Directory. | Filename already exists as a directory entry. Kill the existing file, choose another filename, or specify a drive number. |
| 12 | No Drive Available For An Open. | No on-line drive <ul><li>is write enabled</li><li>has enough space to create a new file, or </li><li>has a system directory.</li></ul> |
| 13 | Write Attempt To A Read Only File. | File was opened for read only, not for read/write. |
| 14 | Write Fault On Disk I/O. | Error occurred during a write operation. Try a different diskette. If the problem continues, contact RSSC. |
| 15 | Disk Is Write Protected. | Write enable the disk. |
| 16 | DCB Is Modified And Is Unusable. | DCB (used in machine-language programming) has been modified since the last disk access (while the file was open). |
| 17 | Directory Read Error.    | Error occurred during an attempt to read the directory. Use a different diskette. |
| 18 | Directory Write Error.   | Error occurred during an attempt to write to the directory. Use a different diskette. |
| 19 | Improper File Name (Filespec). | Filespec you gave does not meet TRSDOS-II standard file specifications. |
| 20 | Unknown Error Code |  | 
| 21 | Unknown Error Code |  | 
| 22 | Unknown Error Code |  | 
| 23 | Unknown Error Code |  | 
| 24 | File Not Found. | Filename you gave was not found on the available disks or the file is the incorrect type for the desired operation. |
| 25 | File Access Denied Due To Password Protection. | You gave an incorrect password. See the ATTRIB command. |
| 26 | Directory Space Full. | Number of filenames has reached the amount set when you formatted the disk. |
| 27 | Disk Space Full. | No space is available on the disk. |
| 28 | Attempt To Read Past EOF. | Specified record number is past the EOF. |
| 29 | Read Attempt Outside Of File Limits. | Use valid record numbers. |
| 30 | No More Extents Available (16 Maximum). | Use the COPY command to copy the files and reduce fragmentation. See also SAVE/RESTORE and MOVE. |
| 31 | Program Not Found. | Specified program is not found on the available disks. |
| 32 | Unknown Drive Number (Filespec). | Specified drive number is not valid. |
| 33 | Disk Space Allocation Cannot Be Made Due To Fragmentation Of Space. | Use the COPY command to copy the files and reduce fragmentation. |
| 34 | Attempt To Use A NON Program File As A Program. | File specified for execution is not a program file or the load address given is illegal. Make sure you have a system diskette in Drive 0. |
| 35 | Memory Fault During Program Load. | Program is loaded incorrectly, possibly because of faulty memory or a "bad" load address. |
| 36 | Parameter For Open Is Incorrect. | Check the OPEN statements or the DCB for errors. |
| 37 | Open Attempt For A File Already Open. | File specified for open is already open. |
| 38 | I/O Attempt To An Unopen File. | Open the file before access. |
| 39 | Illegal I/O Attempt. | <ul><li>I command not given after a diskette swap.</li><li>Can be caused by an I/O attempt to a differently formatted disk. Format the disk under the current version of TRSDOS-II or use FCOPY.</li></ul> |
| 40 | Seek Error. | <ul><li>Data cannot be read from the disk -- faulty disk.</li><li>When re-initializing a hard disk, you must also reformat the secondary drives.</li></ul> |
| 41 | Data Lost During Disk I/O (Hardware Fault).   | Contact RSSC. |
| 42 | Printer Not Ready. | Check the connections, power, ribbon, on-line status, and so on. |
| 43 | Printer Out Of Paper. | Check the printer's paper supply. |
| 44 | Printer Fault (May Be Turned Off).   | Check the connections, power, ribbon, on-line status, and so on. |
| 45 | Printer Not Available. | Check the connections, power, ribbon, on-line status, and so on. |
| 46 | Not Applicable To VLR Type Files. | Operation performed is not valid for VLR files. |
| 47 | Required Command Parameter Not Found. | Required parameter or argument is missing from the command. |
| 48 | Incorrect Command Parameter. | Option or argument given in the command is incorrect. |
| 49 | Hardware Fault During Disk I/O. | Contact RSSC. |
| 50 | Invalid Space Descriptor. | The space descriptor that tells TRSDOS-II which extent to read next is invalid. Try a different diskette. |
| 51-255  | Unknown error code |  | 

These codes are also returned to machine code routines that call a SVC (System Service Call) of TRSDOS-II. Register A usually has a return code after any function call. The Z flag is set when no error occurs. Exceptions are certain computational routines, which use Registers A and F to pass back data and status information.

<p conref="conref.html#conref/contact" />










