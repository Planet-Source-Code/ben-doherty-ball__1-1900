<div align="center">

## Ball


</div>

### Description

This is a very simple code that allows you to move an image with

your arrow keys or the #s 8,6,4, and 2.
 
### More Info
 
I assume that you made your own image to move with the arrow keys

Note: you can change the speed of the ball by changing the number after

the plus or minus sign


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Ben Doherty](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ben-doherty.md)
**Level**          |Unknown
**User Rating**    |4.0 (4 globes from 1 user)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Games](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/games__1-38.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/ben-doherty-ball__1-1900/archive/master.zip)





### Source Code

```
Private Sub Form_KeyDown(KeyCode As Integer, Shift As Integer)
'you can change the speed of the ball by changing the numbers after the + and - signs
If KeyCode = vbKeyF1 Then
MsgBox ("Created by Ben Doherty, jake-d@mindspring.com or http://www.mindspring.com/~jake-d/vb/")
End If
If KeyCode = vbKeyUp Then
Image1.Top = Image1.Top - 30
End If
If KeyCode = vbKeyDown Then
Image1.Top = Image1.Top + 30
End If
If KeyCode = vbKeyLeft Then
Image1.Left = Image1.Left - 30
End If
If KeyCode = vbKeyRight Then
Image1.Left = Image1.Left + 30
End If
End Sub
Private Sub Form_Load()
End Sub
```

