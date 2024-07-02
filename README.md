# mbcac_project

## 팀 프로젝트 안내
* 주제 : 열심히 하자
* 기간 : 3개월
  + 1개월 : 분석
  + 2개월 : 설계
  + 3개월 : 구현
    - 1주 : 로그인
    - 2주 : 게시판
    - 3주 : 뉴스
<a name="top"></a>

[go to code7](#code7)
## 아래의 코드를 참고하세요!
```jsp
<%@ page language="java" contentType="application/json; charset=UTF-8"
    pageEncoding="UTF-8" trimDirectiveWhitespaces="true"%>

<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>

<jsp:useBean id="dao" class="com.mbcaca.BoardDAO"/>
<jsp:useBean id="board" class="com.mbcaca.BoardVO">
	<jsp:setProperty name="board" property="*"/>
</jsp:useBean>
<c:set var="added" value="${dao.add(board)}"/>
{"added":${added}}
```
[github마크다운으로 색상 설정하기](https://gist.github.com/luigiMinardi/4574708d404cdf4fe0da7ac6fe2314db)
$\color{#ff0000}{\textsf{색상 설정}}$

<p>
	
<a name="code1">code1</a> [go to top](#top)
	
```jsp
<%@ page language="java" contentType="application/json; charset=UTF-8"
    pageEncoding="UTF-8" trimDirectiveWhitespaces="true"%>

<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>

<jsp:useBean id="dao" class="com.mbcaca.BoardDAO"/>
<jsp:useBean id="board" class="com.mbcaca.BoardVO">
	<jsp:setProperty name="board" property="*"/>
</jsp:useBean>
<c:set var="added" value="${dao.add(board)}"/>
{"added":${added}}
```
<a name="code2">code2</a> [go to top](#top)
```jsp
<%@ page language="java" contentType="application/json; charset=UTF-8"
    pageEncoding="UTF-8" trimDirectiveWhitespaces="true"%>

<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>

<jsp:useBean id="dao" class="com.mbcaca.BoardDAO"/>
<jsp:useBean id="board" class="com.mbcaca.BoardVO">
	<jsp:setProperty name="board" property="*"/>
</jsp:useBean>
<c:set var="added" value="${dao.add(board)}"/>
{"added":${added}}
```
<a name="code3">code3</a> [go to top](#top)
```jsp
<%@ page language="java" contentType="application/json; charset=UTF-8"
    pageEncoding="UTF-8" trimDirectiveWhitespaces="true"%>

<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>

<jsp:useBean id="dao" class="com.mbcaca.BoardDAO"/>
<jsp:useBean id="board" class="com.mbcaca.BoardVO">
	<jsp:setProperty name="board" property="*"/>
</jsp:useBean>
<c:set var="added" value="${dao.add(board)}"/>
{"added":${added}}
```
<a name="code4">code4</a> [go to top](#top)
```jsp
<%@ page language="java" contentType="application/json; charset=UTF-8"
    pageEncoding="UTF-8" trimDirectiveWhitespaces="true"%>

<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>

<jsp:useBean id="dao" class="com.mbcaca.BoardDAO"/>
<jsp:useBean id="board" class="com.mbcaca.BoardVO">
	<jsp:setProperty name="board" property="*"/>
</jsp:useBean>
<c:set var="added" value="${dao.add(board)}"/>
{"added":${added}}
```
<a name="code5">code5</a> [go to top](#top)
```jsp
<%@ page language="java" contentType="application/json; charset=UTF-8"
    pageEncoding="UTF-8" trimDirectiveWhitespaces="true"%>

<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>

<jsp:useBean id="dao" class="com.mbcaca.BoardDAO"/>
<jsp:useBean id="board" class="com.mbcaca.BoardVO">
	<jsp:setProperty name="board" property="*"/>
</jsp:useBean>
<c:set var="added" value="${dao.add(board)}"/>
{"added":${added}}
```
<a name="code6">code6</a> [go to top](#top)
```jsp
<%@ page language="java" contentType="application/json; charset=UTF-8"
    pageEncoding="UTF-8" trimDirectiveWhitespaces="true"%>

<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>

<jsp:useBean id="dao" class="com.mbcaca.BoardDAO"/>
<jsp:useBean id="board" class="com.mbcaca.BoardVO">
	<jsp:setProperty name="board" property="*"/>
</jsp:useBean>
<c:set var="added" value="${dao.add(board)}"/>
{"added":${added}}
```
<a name="code7">code7</a> [go to top](#top) <a name="code7"></a>
```jsp
<%@ page language="java" contentType="application/json; charset=UTF-8"
    pageEncoding="UTF-8" trimDirectiveWhitespaces="true"%>

<%@ taglib prefix="c" uri="http://java.sun.com/jsp/jstl/core" %>
<%@ taglib prefix="fmt" uri="http://java.sun.com/jsp/jstl/fmt" %>

<jsp:useBean id="dao" class="com.mbcaca.BoardDAO"/>
<jsp:useBean id="board" class="com.mbcaca.BoardVO">
	<jsp:setProperty name="board" property="*"/>
</jsp:useBean>
<c:set var="added" value="${dao.add(board)}"/>
{"added":${added}}
```
</p>
