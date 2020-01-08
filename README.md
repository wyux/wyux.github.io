# WYX的blog
## 个人blog
> blog
* 1
* 2
* 3
[baidu]()
![]()
**haod**
*k*
***
`  Dim param() As Double = Nothing
        Dim TempObj As Object = Nothing
        CoreObj.GetObj(fno, fid, rec.caption, rec.type, rec.status, ObjCode, TempObj)
        If TempObj Is Nothing Then Return False

        param = CType(TempObj, Double())

        Read(CoreObj, param)

        param = Nothing
        Return True`
