# 1212
12121
str = "";
Regex r = new Regex("/[A-Za-z0-9_\-\u4e00-\u9fa5]+/");
if (!r.IsMatch(str))
{
	return "此次验证不通过";
}
//需要添加此引用：using System.Text.RegularExpressions;
