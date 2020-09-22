<div align="center">

## GetCurrentDir


</div>

### Description

The GetCurrentDir function will return a string which contains the name of the current directory.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[N/A](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/empty.md)
**Level**          |Beginner
**User Rating**    |4.0 (8 globes from 2 users)
**Compatibility**  |Delphi 5, Delphi 4, Pre Delphi 4
**Category**       |[Files/ File Controls/ Input/ Output](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/files-file-controls-input-output__7-3.md)
**World**          |[Delphi](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/delphi.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/getcurrentdir__7-22/archive/master.zip)





### Source Code

```
procedure TForm1.Button1Click(Sender: TObject);
begin
  Label1.Caption := GetCurrentDir;
end;
```

