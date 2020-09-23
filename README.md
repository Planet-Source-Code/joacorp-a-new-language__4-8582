<div align="center">

## A new language


</div>

### Description

it create a new language like "|-|i 0r ß-Y-€"

pretty cool :P
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Joacorp\.](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/joacorp.md)
**Level**          |Beginner
**User Rating**    |2.2 (37 globes from 17 users)
**Compatibility**  |ASP \(Active Server Pages\), VbScript \(browser/client side\)

**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__4-1.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/joacorp-a-new-language__4-8582/archive/master.zip)





### Source Code

```
<%
'this code create a new language
function tran (text)
text = replace(text,"a","@")
text = replace(text,"b","ß")
text = replace(text,"c","©")
text = replace(text,"e","€")
text = replace(text,"f","ƒ")
text = replace(text,"g","G")
text = replace(text,"h","|-|")
text = replace(text,"i","i")
text = replace(text,"n","ñ")
text = replace(text,"o","0")
text = replace(text,"y","-Y-")
tran = text
end function
'example:
%>
code:<% response.write(tran("hi and bye")) %>
```

