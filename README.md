<div align="center">

## A Dream\!


</div>

### Description

Concat 2 Arrays (My Dream) - a simple function.... the point is that i wrote it in my dream! yes i did!!! and no i'm not stoned :-)
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[M\. J\. Highlander](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/m-j-highlander.md)
**Level**          |Beginner
**User Rating**    |4.8 (29 globes from 6 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/m-j-highlander-a-dream__1-58776/archive/master.zip)





### Source Code

```
Public Function CatArray(ByRef Array1 As Variant, ByRef Array2 As Variant) As Variant
Dim sTemp As String
sTemp = Join(Array1, vbNullChar) & vbNullChar & Join(Array2, vbNullChar)
CatArray = Split(sTemp, vbNullChar)
End Function
```

