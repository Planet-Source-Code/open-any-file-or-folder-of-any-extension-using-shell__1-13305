<div align="center">

## Open any file or folder of any extension  using shell


</div>

### Description

This code can open any files of any extension, really any extension!!! And please rate it or emailto me at leungchunghong8944563@yahoo.com to tell me about what you feel.. Thanks
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[N/A](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/empty.md)
**Level**          |Beginner
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0, VB Script
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__1-43.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/open-any-file-or-folder-of-any-extension-using-shell__1-13305/archive/master.zip)





### Source Code

```
Private Sub Command1_Click()
Shell "rundll32.exe url.dll,FileProtocolHandler _ File Path Name"
```

