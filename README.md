<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }
        .btn{
            width: 300px;
            height: 50px;
            border: 1px solid black;
           text-align: center;
           padding: 10px;
            font-size: 20px;
            margin: 150px auto;
            position: relative;
            overflow: hidden;/
        }
        span{
            width: 100%;
            height: 5px;
            display: block;
            background-color: red;
            position: absolute;
        }
        span:nth-child(1){
            top: 0;
            left: 0;
            margin-left: 3px;
            background: linear-gradient(0deg, rgba(34,193,195,1) 10%, rgba(201,43,54,1) 30%, rgba(53,11,208,1) 42%, rgba(251,45,253,0.9836309523809523) 92%);
            animation: span1 1s linear infinite alternate-reverse;
        }


        @keyframes span1 {
            0%{
                transform: translatex(-100%)
            }
            100%{
                transform: translatex(100%);
            }
            
        }
        span:nth-child(2){
            transform: rotate(90deg);
            transform-origin: right;
            right: 0;
            bottom: 0;
            background: linear-gradient(0deg, rgba(34,193,195,1) 0%, rgba(201,43,54,1) 0%, rgba(53,11,208,1) 42%, rgba(251,45,253,0.9836309523809523) 92%);
            margin-right: 3px;
            animation: span2 1s linear infinite;
        }
        @keyframes span2 {
            0%{
                transform: translatey(-50px) rotate(90deg);
            }
            100%{
                transform: translatey(100%) rotate(90deg);
            }
            
        }
        span:nth-child(3){
            right: 0;
            bottom: 0;
            background: linear-gradient(to left, rgba(34,193,195,1) 0%, rgba(201,43,54,1) 0%, rgba(53,11,208,1) 42%, rgba(251,45,253,0.9836309523809523) 92%);
            animation: span3 1s linear infinite alternate-reverse;
        }
        
        @keyframes span3 {
            0%{
                transform: translatex(100%)
            }
            100%{
                transform: translatex(-100%);
            }
            
        }
        span:nth-child(4){
            /* transform: rotate(90deg); */
            /* transform-origin: right; */
            left: 0;
            top: 0;
            transform-origin: left;
            transform: rotate(90deg);
            background: linear-gradient(to top, rgba(34,193,195,1) 0%, rgba(201,43,54,1) 0%, rgba(53,11,208,1) 42%, rgba(251,45,253,0.9836309523809523) 92%);
            margin-left: 3px;
            animation: span4 1s linear infinite;
        }
         @keyframes span4 {
            0%{
                transform: translatey(100px) rotate(90deg);
            }
            100%{
                transform: translatey(-100%) rotate(90deg);
            }
            
        }
    </style>
</head>
<body>
     <div class="btn">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        Cutie_boyy_

     </div>
    
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }
        .btn{
            width: 300px;
            height: 50px;
            border: 1px solid black;
           text-align: center;
           padding: 10px;
            font-size: 20px;
            margin: 150px auto;
            position: relative;
            overflow: hidden;/
        }
        span{
            width: 100%;
            height: 5px;
            display: block;
            background-color: red;
            position: absolute;
        }
        span:nth-child(1){
            top: 0;
            left: 0;
            margin-left: 3px;
            background: linear-gradient(0deg, rgba(34,193,195,1) 10%, rgba(201,43,54,1) 30%, rgba(53,11,208,1) 42%, rgba(251,45,253,0.9836309523809523) 92%);
            animation: span1 1s linear infinite alternate-reverse;
        }


        @keyframes span1 {
            0%{
                transform: translatex(-100%)
            }
            100%{
                transform: translatex(100%);
            }
            
        }
        span:nth-child(2){
            transform: rotate(90deg);
            transform-origin: right;
            right: 0;
            bottom: 0;
            background: linear-gradient(0deg, rgba(34,193,195,1) 0%, rgba(201,43,54,1) 0%, rgba(53,11,208,1) 42%, rgba(251,45,253,0.9836309523809523) 92%);
            margin-right: 3px;
            animation: span2 1s linear infinite;
        }
        @keyframes span2 {
            0%{
                transform: translatey(-50px) rotate(90deg);
            }
            100%{
                transform: translatey(100%) rotate(90deg);
            }
            
        }
        span:nth-child(3){
            right: 0;
            bottom: 0;
            background: linear-gradient(to left, rgba(34,193,195,1) 0%, rgba(201,43,54,1) 0%, rgba(53,11,208,1) 42%, rgba(251,45,253,0.9836309523809523) 92%);
            animation: span3 1s linear infinite alternate-reverse;
        }
        
        @keyframes span3 {
            0%{
                transform: translatex(100%)
            }
            100%{
                transform: translatex(-100%);
            }
            
        }
        span:nth-child(4){
            /* transform: rotate(90deg); */
            /* transform-origin: right; */
            left: 0;
            top: 0;
            transform-origin: left;
            transform: rotate(90deg);
            background: linear-gradient(to top, rgba(34,193,195,1) 0%, rgba(201,43,54,1) 0%, rgba(53,11,208,1) 42%, rgba(251,45,253,0.9836309523809523) 92%);
            margin-left: 3px;
            animation: span4 1s linear infinite;
        }
         @keyframes span4 {
            0%{
                transform: translatey(100px) rotate(90deg);
            }
            100%{
                transform: translatey(-100%) rotate(90deg);
            }
            
        }
    </style>
</head>
<body>
     <div class="btn">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        Cutie_boyy_

     </div>
    
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }
        .btn{
            width: 300px;
            height: 50px;
            border: 1px solid black;
           text-align: center;
           padding: 10px;
            font-size: 20px;
            margin: 150px auto;
            position: relative;
            overflow: hidden;/
        }
        span{
            width: 100%;
            height: 5px;
            display: block;
            background-color: red;
            position: absolute;
        }
        span:nth-child(1){
            top: 0;
            left: 0;
            margin-left: 3px;
            background: linear-gradient(0deg, rgba(34,193,195,1) 10%, rgba(201,43,54,1) 30%, rgba(53,11,208,1) 42%, rgba(251,45,253,0.9836309523809523) 92%);
            animation: span1 1s linear infinite alternate-reverse;
        }


        @keyframes span1 {
            0%{
                transform: translatex(-100%)
            }
            100%{
                transform: translatex(100%);
            }
            
        }
        span:nth-child(2){
            transform: rotate(90deg);
            transform-origin: right;
            right: 0;
            bottom: 0;
            background: linear-gradient(0deg, rgba(34,193,195,1) 0%, rgba(201,43,54,1) 0%, rgba(53,11,208,1) 42%, rgba(251,45,253,0.9836309523809523) 92%);
            margin-right: 3px;
            animation: span2 1s linear infinite;
        }
        @keyframes span2 {
            0%{
                transform: translatey(-50px) rotate(90deg);
            }
            100%{
                transform: translatey(100%) rotate(90deg);
            }
            
        }
        span:nth-child(3){
            right: 0;
            bottom: 0;
            background: linear-gradient(to left, rgba(34,193,195,1) 0%, rgba(201,43,54,1) 0%, rgba(53,11,208,1) 42%, rgba(251,45,253,0.9836309523809523) 92%);
            animation: span3 1s linear infinite alternate-reverse;
        }
        
        @keyframes span3 {
            0%{
                transform: translatex(100%)
            }
            100%{
                transform: translatex(-100%);
            }
            
        }
        span:nth-child(4){
            /* transform: rotate(90deg); */
            /* transform-origin: right; */
            left: 0;
            top: 0;
            transform-origin: left;
            transform: rotate(90deg);
            background: linear-gradient(to top, rgba(34,193,195,1) 0%, rgba(201,43,54,1) 0%, rgba(53,11,208,1) 42%, rgba(251,45,253,0.9836309523809523) 92%);
            margin-left: 3px;
            animation: span4 1s linear infinite;
        }
         @keyframes span4 {
            0%{
                transform: translatey(100px) rotate(90deg);
            }
            100%{
                transform: translatey(-100%) rotate(90deg);
            }
            
        }
    </style>
</head>
<body>
     <div class="btn">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        Cutie_boyy_

     </div>
    
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }
        .btn{
            width: 300px;
            height: 50px;
            border: 1px solid black;
           text-align: center;
           padding: 10px;
            font-size: 20px;
            margin: 150px auto;
            position: relative;
            overflow: hidden;/
        }
        span{
            width: 100%;
            height: 5px;
            display: block;
            background-color: red;
            position: absolute;
        }
        span:nth-child(1){
            top: 0;
            left: 0;
            margin-left: 3px;
            background: linear-gradient(0deg, rgba(34,193,195,1) 10%, rgba(201,43,54,1) 30%, rgba(53,11,208,1) 42%, rgba(251,45,253,0.9836309523809523) 92%);
            animation: span1 1s linear infinite alternate-reverse;
        }


        @keyframes span1 {
            0%{
                transform: translatex(-100%)
            }
            100%{
                transform: translatex(100%);
            }
            
        }
        span:nth-child(2){
            transform: rotate(90deg);
            transform-origin: right;
            right: 0;
            bottom: 0;
            background: linear-gradient(0deg, rgba(34,193,195,1) 0%, rgba(201,43,54,1) 0%, rgba(53,11,208,1) 42%, rgba(251,45,253,0.9836309523809523) 92%);
            margin-right: 3px;
            animation: span2 1s linear infinite;
        }
        @keyframes span2 {
            0%{
                transform: translatey(-50px) rotate(90deg);
            }
            100%{
                transform: translatey(100%) rotate(90deg);
            }
            
        }
        span:nth-child(3){
            right: 0;
            bottom: 0;
            background: linear-gradient(to left, rgba(34,193,195,1) 0%, rgba(201,43,54,1) 0%, rgba(53,11,208,1) 42%, rgba(251,45,253,0.9836309523809523) 92%);
            animation: span3 1s linear infinite alternate-reverse;
        }
        
        @keyframes span3 {
            0%{
                transform: translatex(100%)
            }
            100%{
                transform: translatex(-100%);
            }
            
        }
        span:nth-child(4){
            /* transform: rotate(90deg); */
            /* transform-origin: right; */
            left: 0;
            top: 0;
            transform-origin: left;
            transform: rotate(90deg);
            background: linear-gradient(to top, rgba(34,193,195,1) 0%, rgba(201,43,54,1) 0%, rgba(53,11,208,1) 42%, rgba(251,45,253,0.9836309523809523) 92%);
            margin-left: 3px;
            animation: span4 1s linear infinite;
        }
         @keyframes span4 {
            0%{
                transform: translatey(100px) rotate(90deg);
            }
            100%{
                transform: translatey(-100%) rotate(90deg);
            }
            
        }
    </style>
</head>
<body>
     <div class="btn">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        Cutie_boyy_

     </div>
    
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }
        .btn{
            width: 300px;
            height: 50px;
            border: 1px solid black;
           text-align: center;
           padding: 10px;
            font-size: 20px;
            margin: 150px auto;
            position: relative;
            overflow: hidden;/
        }
        span{
            width: 100%;
            height: 5px;
            display: block;
            background-color: red;
            position: absolute;
        }
        span:nth-child(1){
            top: 0;
            left: 0;
            margin-left: 3px;
            background: linear-gradient(0deg, rgba(34,193,195,1) 10%, rgba(201,43,54,1) 30%, rgba(53,11,208,1) 42%, rgba(251,45,253,0.9836309523809523) 92%);
            animation: span1 1s linear infinite alternate-reverse;
        }


        @keyframes span1 {
            0%{
                transform: translatex(-100%)
            }
            100%{
                transform: translatex(100%);
            }
            
        }
        span:nth-child(2){
            transform: rotate(90deg);
            transform-origin: right;
            right: 0;
            bottom: 0;
            background: linear-gradient(0deg, rgba(34,193,195,1) 0%, rgba(201,43,54,1) 0%, rgba(53,11,208,1) 42%, rgba(251,45,253,0.9836309523809523) 92%);
            margin-right: 3px;
            animation: span2 1s linear infinite;
        }
        @keyframes span2 {
            0%{
                transform: translatey(-50px) rotate(90deg);
            }
            100%{
                transform: translatey(100%) rotate(90deg);
            }
            
        }
        span:nth-child(3){
            right: 0;
            bottom: 0;
            background: linear-gradient(to left, rgba(34,193,195,1) 0%, rgba(201,43,54,1) 0%, rgba(53,11,208,1) 42%, rgba(251,45,253,0.9836309523809523) 92%);
            animation: span3 1s linear infinite alternate-reverse;
        }
        
        @keyframes span3 {
            0%{
                transform: translatex(100%)
            }
            100%{
                transform: translatex(-100%);
            }
            
        }
        span:nth-child(4){
            /* transform: rotate(90deg); */
            /* transform-origin: right; */
            left: 0;
            top: 0;
            transform-origin: left;
            transform: rotate(90deg);
            background: linear-gradient(to top, rgba(34,193,195,1) 0%, rgba(201,43,54,1) 0%, rgba(53,11,208,1) 42%, rgba(251,45,253,0.9836309523809523) 92%);
            margin-left: 3px;
            animation: span4 1s linear infinite;
        }
         @keyframes span4 {
            0%{
                transform: translatey(100px) rotate(90deg);
            }
            100%{
                transform: translatey(-100%) rotate(90deg);
            }
            
        }
    </style>
</head>
<body>
     <div class="btn">
        <span></span>
        <span></span>
        <span></span>
        <span></span>
        Cutie_boyy_

     </div>
    
</body>
</html>
