<div align="center">

## Simple Scroll


</div>

### Description

This code is the simplest form of Scrolling Text. It uses a Timer controle to make a label scroll.

No consideration is required for screen cordinates or size or any other thing. Have a look at this simple scroll text application and Please do rate it :) I am watching from sachinweb@hotmail.com
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Sachin Mehra](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/sachin-mehra.md)
**Level**          |Beginner
**User Rating**    |4.0 (16 globes from 4 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Custom Controls/ Forms/  Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/custom-controls-forms-menus__1-4.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/sachin-mehra-simple-scroll__1-34876/archive/master.zip)





### Source Code

```
Form1 (starts)
======================
Dim str As String
------------------
Private Sub Form_Load()
Label1.Caption = "Hi all, I am Sachin "
Timer1.Enabled = True
Timer1.Interval = 300
End Sub
Private Sub Timer1_Timer()
str = Form1.Label1.Caption
str = Mid(str, 2, Len(str)) + Mid(str, 1, 1)
Form1.Label1.Caption = str
End Sub
=================================
Form1 (Ends)
```

