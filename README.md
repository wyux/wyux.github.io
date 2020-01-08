# WYX的blog
## 个人blog
> blog
* 1
* 2
* 3

[baidu]()

**haod**

*k*

***

``` vb.net
Public Overrides Function Read(ByRef CoreObj As MapFileCoreLib.MIGraphy, ByVal fno As Integer, ByVal fid As Integer, ByRef rec As GraphyRec) As Boolean
        Dim param() As Double = Nothing
        Dim TempObj As Object = Nothing
        CoreObj.GetObj(fno, fid, rec.caption, rec.type, rec.status, ObjCode, TempObj)
        If TempObj Is Nothing Then Return False

        param = CType(TempObj, Double())

        Read(CoreObj, param)

        param = Nothing
        Return True
    End Function
```

- [ ]
- [x]
