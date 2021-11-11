# VisualStudio-Notes
Stuff useful using Visual Studio

#Reg Ex used to remove all comments including multi line and not break code lines
```
(\t+|\s+|\r\n)((/\*([^*]|[\r\n]|(\*+([^*/]|[\r\n])))*\*+/)|(//.*))
```
