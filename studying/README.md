# 공부한 내용들을 정리

- [\<html\> 태그의 xmlns 속성](http://tcpschool.com/html-tag-attrs/html-xmlns)
  - 해당 문서를 위한 XML namespace를 명시
  - 해당 문서가 XHTML 문서일 경우 반드시 명시되어야 하며, HTML5에서는 선택 사항.
  - W3C에서 제공하는 HTML 유효성 검사에서는 XHTML 문서의 <html> 태크에 `xmlns` 속성이 명시되어 있지 않아도 유효성 검사를 무사히 통과
- [Understanding the runat server attribute](https://stackoverflow.com/questions/11510502/understanding-the-runat-server-attribute)
  - `ASP.NET`
  ```html
  <head runat="server">
    <title>Hallo</title>
    <link href="~/Styles/Site.css" rel="stylesheet" type="text/css" />

    <!-- This part is run on the server. So why does the head tag
         also need a runat=server ?? -->
    <asp:ContentPlaceHolder ID="HeadContent" runat="server">
    </asp:ContentPlaceHolder>
</head>
  ```
