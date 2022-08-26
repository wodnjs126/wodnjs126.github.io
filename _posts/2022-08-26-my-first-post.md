---
title:  "오늘 공부 끝"
excerpt: "간단한 htm 공부. "

categories:
  - Htm
tags:
  - [Blog, htm, Github, Git]

toc: true
toc_sticky: true
 
date: 2022-08-26
last_modified_at: 2022-08-26
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>수상 대장 만들기</h1>
    <script>
    a=prompt("평균점수를 입력하세요");
    d=prompt("결석 일수를 입력하세요");
    if(a=>90 && d==0){
        document.write("우수상 수여");
    }
    else{
        document.write("수상 대상자가 아닙니다");
    }
    </script>
</body>
</html>
