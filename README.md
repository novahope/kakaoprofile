# kakaoprofile
카톡 프로필 화면
<!doctype html>
<html lang="en">

<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
crossorigin="anonymous"></script>

<title>카카오톡 프로필 화면</title>


<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR&display=swap" rel="stylesheet">
<style>
    * {
        font-family: 'Noto Sans KR', sans-serif;

    }

    .form {border: solid 1px black;
        height: 800px;
        width: 480px;
        margin: 300px auto;

    }

    .mytitle {

        border: solid 1px black;
            height: 500px;
            width: 480px;

            background-image: url("https://ww.namu.la/s/33e12fa02156cfcfb517f6e9d25145e7e1f34ddba3d0244eb26dce1cd624d08e911e85d122276d58c6a89eaaf110aa22ba243f04037aa1e2de24f8e6ad51cdb36ead68b28c42128465a66df7d17b7c4b22d69e99676af0d507226906f6c2a906");
            background-position: center;
            background-size: cover;

            color: white;

            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
    #story {
        padding: 40px; text-align: center;
    }

    .profile {border: solid 1px black;
        position: relative; margin: 0 auto;
        z-index: 1;
        top: -90px;
        height: 180px;
        width: 180px;


    }
    #thumb {
        border-radius: 200px;
        height: 180px;
        width: 180px;

    }
    .myicon {border: solid 1px black;
            height: 300px;
            width: 480px;

    }
    #name {font-size: 25px;
        padding: 120px; text-align: center;
    }
    .icon {
        height: 50px;
        width: 50px;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        margin: 20px;
    }


</style>

<script>

</script>


</head>

<body>
    <div class="form">
        <div class="mytitle">
            <i class="fas fa-minus">_</i>
            <p id="story">아서스(Arthus)는 워크래프트 시리즈의 </br>2대 리치 왕(The Lich King)이자 </br>스컬지(언데드 세력)의 수장이지만, </br>태생은 인간 국가 ‘로데론’의 왕자님이었다.</p>
        </div>
        <div class="profile" >
            <img src="image/DSC_4127.jpg" id="thumb">
        </div>
        <div class="myicon">
                <p id="name">리치왕</p><i class="fas fa-pen"></i>
            <img src="icons/1.png" class="icon">
            <img src="icons/2.png" class="icon">
            <img src="icons/3.png" class="icon">
        </div>
    </div>


</body>

</html>
