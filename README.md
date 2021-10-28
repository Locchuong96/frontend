# Frontend
html,css,javscript,Bootstrap,etc

# html,css

https://www.youtube.com/watch?v=R6plN3FvzFY&list=PL_-VfJajZj0U9nEXa4qyfB4U5ZIYCMPlz

### Install extentsion "live server"

### Add smart page ruler

https://chrome.google.com/webstore/detail/smart-page-ruler/nmibbjghlmdiafjolcphdggihcbcedmg

_________________________________________________________________________________________________________________________________________________________________________________
_________________________________________________________________________________________________________________________________________________________________________________

# Bootstrap

https://www.youtube.com/watch?v=-bbE-eUvYTI&list=PLxF76yfppeZY9Nn90xAAnA04AvzBiS9zA

https://www.youtube.com/watch?v=qIewm54rTF4&list=RDCMUC8vjHOEYlnVTqAgE6CFDm_Q&start_radio=1&rv=qIewm54rTF4&t=1118

## Download Bootstrap

https://getbootstrap.com/docs/5.1/getting-started/download/

## CDN (content devilery network)

## Starting
### 1/ html5 doctype

    <!doctype html>
    <html lang = 'en'>
      <head>
        <meta charset = 'utf-8'>
      </head>
    </html>

### 2/ mobile first
    
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    
   width = device-width: sẽ hiện thị tùy theo độ rộng của thiết bị
   
   initial-scale = 1: mức zoom mặc định ban đầu
   
### 3/ Khai báo CDN

    <link rel = 'stylesheet' href = 'http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css'>
    <script src = 'https://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js'></script>
    <script src = 'http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js'></script>
    
### 4/ Container
    
    container: cung cấp các layout có độ rộng cố định trong một lớp container
    
    container-fluid: cung cấp các layout có động rộng toàn màn hình
    
   *Note: Các container này không được phép lồng vào nhau
   
### 5/ Grid

<img width="605" alt="bootstrap_4_grid" src="https://user-images.githubusercontent.com/73679364/139051320-8e992b27-7951-471c-88c7-e3d570dbf651.png">

    1200-1170/12
    
Các class trong Grid Bootstrap: Có 4 class:

    . xs : cực nhỏ ( các thiết bị là phone )
    . sm : nhỏ ( các thiết bị máy tính bảng )
    . md : vừa ( màn hình desktop )
    . lg : lớn ( màn hình desktop lớn )
   
Hệ thống grid bootstrap

    <div class = 'container'>
        <div class = 'row'>
            <div class = 'col-*-*'></div>
        </div>
        <div class = 'row'>
            <div class = 'col-*-*'></div>
            <div class = 'col-*-*'></div>
            <div class = 'col-*-*'></div>
        </div>
        <div class = 'row>
        ...
        </div>
    </div>
        
        
