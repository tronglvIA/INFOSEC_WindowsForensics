```
Question 1
How many bits in a byte?

2 bits


4 bits


10 bits


8 bits           #Correct
```

```
Question 2
Binary is a base___ numbering system?

Base 16

                    
Base 2           #Correct


Base 10


Base 8
```

```
Question 3
A bit has __ possible values?

256

2                #Correct

16

1
```

```
Question 4
A nybble is __ bytes long?

8    

2

10        

4                #Correct
```

```
Question 5
Hexadecimal is a base ___ numbering system?

8    

16                #Correct

4

2
```

```
Question 6
Data is stored on disk in ___ format?

Binary            #Correct

all zeros

Hexadecimal

decimal
```

```
Question 7
A signed integer is a negative number if __ ?

- if the least significant bit is turned on

- if the most significant bit is turned on            #Correct

- if the most significant bit is turned off

- Always
```

```
Question 8
Little Endiann data is read ____ ?

from left to right

from top to bottom

from right to left              #Correct

only as hexadecimal
```

```
Question 9
Intel processors tend to read data as _____?

Decimal

Big Endian

little Endian                    #Correct

never
```

```
Question 10
Low-level formatting is performed by ?

disk management

The user

only the system admin

The drive manufactures            #Correct
```

```
Question 11
Sectors are usually ____ bytes in size ?

2048

1024

10000

512                 #Correct
```

```
Question 12
___ are the smallest readable unit on a disk?

Clusters

Bytes

Sectors              #Correct

Nibbles
```

```
Question 13
Sector numbering starts at ___ ?

0                    #Correct

3

1

8
```

```
Question 14
Logical Block Addressing means that ?

- Each sector is numbered sequentially starting at 1,2,3,4,...
continuing until the end of the disk

- The sectors are not numbered sequentially

- The sectors do not have numbers

- Each sector is numbered sequentially starting at 0,1,2,3,4,...
continuing until the end of the disk.                                #Correct
```

```
Question 15
Clusters are a group of ____ ?

Volumes

Numbers

Sectors                 #Correct

Physical disks
```

```
Question 16
The master partition table can have up to __ entries?

2

128

8

4                        #Correct
```

```
Question 17
The master boot record is located at physical sector___ ?

2

1

3

0                          #Correct
```

```
Question 18
A GPT formatted disk can have up to ___ partitions?

1024

128                         #Correct

1

4
```

```
Question 19
On an MBR formatted disk a partition entry is ___ bytes long?

128

4

16                          #Correct

12
```

```
Question 20
What is located in sector 0 of a disk formatted with GPT partition schema?

a volume boot record

nothing

a GPT header

a protective master boot record              #Correct
```

```
Question 21
In FAT 32 the root directory is located in ?

The data area                    #Correct

At the end of the volume

The system area

Logical sector 0
```

```
Question 22
The most recent version of FAT is ?

exFAT

FAT 16

FAT 32                            #False

FAT 12
```

```
Question 23
What does the FAT table track?

Cluster allocation                #Correct

File types

Deleted files

User names
```

```
Question 24
To find the number of sectors per cluster you would look at?

The root directory

The Volume Boot Record            #Correct
```

```
Question 25
How many FAT's would you expect to find on a FAT32 volume?

2                                 #Correct

3

1

4
```

```
Question 26
A FAT32 Root directory entry is __ bytes long?

16

8

28

32                                #Correct
```

```
Question 27
Every file and folder located in the root of a FAT volume will have ?

a dos alias

an entry in the root directory    #Correct

a volume label

a long file name
```

```
Question 28
FAT file time is recorded in ?

UTC                                #Correct

the FAT table

the time zone of the local machine

the volume boot record
```

```
Question 29
The long file name attribute byte will always be ?

0x 0F                               #Correct

0x 00

0x 0E

0x E5
```

```
Question 30
0x E5 signifies what in the FAT root directory ?

nothing

a deleted file                       #Correct

the end of the root directory entries

an allocated file
```

```
Question 31
In NTFS, everything is stored as a ?

extended logical partition

in the system area

file                                  #Correct

volume
```

```
Question 32
The Master file table contains ?

- only system files for recovery

- only resident data files

- only fragmented files

- a record of every file and folder     #Correct
on the volume including itself
```

```
Question 33
The MFT Mirror contains ?

A full backup of the MFT

Is the same as the MFT

A partial backup of the MFT for recovery    #Correct

More records than the MFT
```

```
Question 34
The number of sectors per cluster in an NTFS volume can be found in ?

The Master Boot Record

The Volume Boot Record                        #Correct

The Master file Table

The root Directory
```

```
Question 35
An MFT file record header starts with ____ at offset 0? 

Allocation status flags

Sequence Count

Physical size of the MFT record

FILE                                    #Correct
```

```
36.
Question 36
The starting cluster of this data run  (0x 21 55 8b 05)  is ____ ?

1024

583

4096

1419                                    #Correct
```

```
Question 37
When a file is deleted in NTFS the file record ____ ?

Nothing happens to the file record

The sequence count is increased by one            #Correct

The record is zeroed out

The allocation flag indicates an allocated file
```

```
Question 38
What is not part of the exFAT system area ?

FAT

Cluster Heap                       #Correct

Backup Boot

Main Boot
```

```
Question 39
The exFAT FAT table only tracks ?

the bitmap

fragmented files                   #Correct

all files

file allocation
```

```
Question 40
The exFAT volume boot record is located at ?

physical sector 0 of the physical disk

logical sector 0 of the volume     #Correct

cluster 2

the root directory
```

```
Question 41
What does NOT happen when you delete a file in exFAT?

Directory entry set type flags set to not in use

the data is deleted                #Correct

the bitmap entries are set to 0

FAT may or may not be zeroed out
```

```
Question 42
The layout of the registry contains hives, Keys, sub-key, values, 
and ______ ?

data                #Correct

applications

hexadecimal

users
```

```
Question 43
The file path to the Sam, Security, Software and System files within a forensic image file is ?

Windows/users/system32/config

Users/appdata/config

Root/WindowsNT/system/config

Root/Windows/System32/config            #Correct
```

```
Question 44
Every ___ on a windows system has an NTuser.dat and a Usrclass.dat file ?

System

File

User            #Correct

Log File
```

```
Question 45
Every ___ on a windows system has an NTuser.dat and a Usrclass.dat file ?

- Active files and folders

- Program execution

- Each user such as login information, login password hashes, 
and group information                    #Correct

- Recent files accessed
```

```
Question 46
Time zone information can be found in which registry file ?

System

Software

SAM

NTUser.dat
```

```
Question 47
Recent documents by file type can be found in which registry file?

Software

NTUser.dat

SAM

System
```




