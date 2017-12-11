---
id: model_II_boot_errors_table
shortdesc: List of the possible error messages you may encounter when using the <span data-keyref="computer_model" /> upon boot-up.
author: Wilson Rodriquez
---

# Model II Boot Errors Table


| Error | Message | Explanation/Action |
|-------|---------|--------------------|
| BOOT ERROR CK | Checksum error -- possibly a defective ROM. | Contact RSSC. |
| BOOT ERROR CT | Defective CTC chip. | Contact RSSC. |
| BOOT ERROR DC | Floppy disk controller error. <ol><li>Defective diskette.</li><li>Floppy disk expansion unit not on.</li><li>Defective FDC Chip or Drive.</li></ol> | <ol><li>Try a different diskette.</li><li>Turn on the floppy disk expansion unit.</li><li>Contact RSSC.</li></ol> |
| BOOT ERROR DM | DMA chip failure. | DMA chip failure. | 
| BOOT ERROR D0 | Drive not ready. <ol><li>Improperly inserted diskette.</li><li>Defective diskette.</li><li>Defective drive.</li></ol> | <ol><li>Insert the diskette again and press .</li><li>Try a different diskette. </li><li>Contact RSSC.</li></ol> |
| BOOT ERROR HA | Controller error. Aborted command: Problem during boot-up of hard disk. | Re-initialize the hard disk or contact RSSC. |
| BOOT ERROR HC | CRC error. Invalid data in data field. | Re-initialize the hard disk or contact RSSC. |
| BOOT ERROR HD | Controller error. Busy not reset. | <ol><li>Re-initialize the hard disk.</li><li>Power down, wait 10 seconds, and power up.</li></ol> If the error occurs again, contact RSSC. |
| BOOT ERROR HI | CRC error. Invalid data in ID field. | Re-initialize the hard disk. | 
| BOOT ERROR HM | Data address mark not found. | Re-initialize the hard disk. |
| BOOT ERROR HN | ID not found. No Boot Track. | Re-initialize the hard disk. | 
| BOOT ERROR H0 | Track 0 error on hard disk. <ol><li>Didn't find Track 0 before time-out.</li><li>Secondary hard disk drives not turned on.</li></ol> | <ol><li>Press RESET.</li><li>Turn on your secondary hard disk drives.</li></ol> |
| BOOT ERROR HT | Time-out while waiting for Ready. <ol><li>Hard disk drive not powered up.</li><li>Hard disk drive isn't turned on and ready within 10 seconds after the computer.</li><li>Hard disk drive is disconnected.</li></ol> | <ol><li>Follow correct procedure: Turn on the hard disk first.</li><li>Press RESET.</li><li>Connect the hard disk drive or operate under floppy disk control.</li></ol> |
| BOOT ERROR LD | Lost data during read -- FDC (floppy disk controller) or drive fault. | Try another TRSDOS-II diskette or contact RSSC. |
| BOOT ERROR MF | Memory failure in address range X'1000'-X'7FFF'. | Contact RSSC. |
| BOOT ERROR MH | Memory failure in address range X'8000'-X'FFFF'. | Contact RSSC. |
| BOOT ERROR ML | Memory failure in address range X'0000'-X'0FFF'. | Contact RSSC. |
| BOOT ERROR PI | Defective PIO Chip. | Turn on the expansion bay if it is off. If the error occurs again, contact RSSC. |
| BOOT ERROR RS | The diskette in Drive 0 is not <span data-keyref="company_name" /> operating system format. | Insert a TRSDOS-II formatted diskette into Drive 0 and press RESET. |
| BOOT ERROR SC | CRC Error. Invalid data on diskette or defective diskette. | Try a different diskette. |
| BOOT ERROR TK | Record not found bootstrap track. Improperly formatted or defective diskette.| Re-format your diskette or try a different diskette. |
| BOOT ERROR Z8 | Defective CPU. | Contact RSSC. | 
| NOT A SYSTEM DISK | Diskette in Drive 0 isn't a TRSDOS-II operating system diskette. | Insert a TRSDOS-II operating system diskette into Drive 0. |

<p conref="conref.html#conref/contact" />