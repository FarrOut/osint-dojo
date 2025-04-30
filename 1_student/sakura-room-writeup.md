# TryHackMe: Sakura Room

Link to [Sakura Room](https://tryhackme.com/room/sakura)

## Investigation

### Task 1: Introduction

```Let's Go!```

### Task 2: Tip-off

#### Objectives
> What username does the attacker go by?

```SakuraSnowAngelAiko```

#### Methodology

[Image clue](https://raw.githubusercontent.com/OsintDojo/public/3f178408909bc1aae7ea2f51126984a8813b0901/sakurapwnedletter.svg)

1. Download image file

``` wget https://raw.githubusercontent.com/OsintDojo/public/3f178408909bc1aae7ea2f51126984a8813b0901/sakurapwnedletter.svg```

2. Grab metadata

``` exiftool sakurapwnedletter.svg```
```
ExifTool Version Number         : 13.10
File Name                       : sakurapwnedletter.svg
Directory                       : .
File Size                       : 850 kB
File Modification Date/Time     : 2025:04:30 09:43:39-04:00
File Access Date/Time           : 2025:04:30 09:43:39-04:00
File Inode Change Date/Time     : 2025:04:30 09:43:39-04:00
File Permissions                : -rw-rw-r--
File Type                       : SVG
File Type Extension             : svg
MIME Type                       : image/svg+xml
Xmlns                           : http://www.w3.org/2000/svg
Image Width                     : 116.29175mm
Image Height                    : 174.61578mm
View Box                        : 0 0 116.29175 174.61578
SVG Version                     : 1.1
ID                              : svg8
Version                         : 0.92.5 (2060ec1f9f, 2020-04-08)
Docname                         : pwnedletter.svg
Export-filename                 : /home/SakuraSnowAngelAiko/Desktop/pwnedletter.png
Export-xdpi                     : 96
Export-ydpi                     : 96
Metadata ID                     : metadata5
Work Format                     : image/svg+xml
Work Type                       : http://purl.org/dc/dcmitype/StillImage
Work Title                      : 
    
```

Under *Export-filename* we can deduce the username is ```SakuraSnowAngelAiko```.

### Task 3: Reconnaissance
### Task 4: Unveil
### Task 5: Taunt
### Task 6: Homebound

