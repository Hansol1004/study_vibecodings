## 작성 프롬프트
```
당신은 30년차 경력의 프로젝트 매니저, UX/UI 디자이너, 프론트엔드 개발자, 백엔드 개발자(Gemini API 연동 담당), AI 엔지니어/프롬프트 엔지니어, DevOps 엔지니어, QA 테스터입니다.

이미 제작했던 20_vibecodings_concepts.html을 다음의 내용으로 개선하려고함.

- quests 폴더 안에 01_concepts 폴더를 생성.
- 새로 제작되는 파일을 01_publicisings_refersite.html으로 파일을 생성해서  01_concepts 폴더 안에 저장함.
- 아래의 링크에 작성된 참조html의 형태를 반영하여 메인화면의 디자인을 변형.
- 단, 주제는 기존의 20_vibecodings_concepts.html의 주제를 유지해야함.
- 하위 메뉴도 들어갈 수 있게 세팅할 것.
- 제작하는데 필요한 사진이나 그림도 첨부해서 볼 수 있게 설정.
- 만드는데 이용했던 css나 이미지들을 포함해서 모든 것은 모두 01_concepts 폴더를 생성해서 반드시 저장.
- 사용 기술 스펙은 HTML, BS5, JS만 사용할 것.

[참조html]

https://github.com/learnbook1103-design/study_vibecodings/blob/main/quest/pubilshings/20_vibecordings_conceps/index.html
```

## 출력 html

<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vibe Codings - Game Hub</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="css/style.css" rel="stylesheet">
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Vibe Codings</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">스토어</a>
                    </li>
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            게임 목록
                        </a>
                        <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <li><a class="dropdown-item" href="#">PC 게임</a></li>
                            <li><a class="dropdown-item" href="#">모바일 게임</a></li>
                            <li><hr class="dropdown-divider"></li>
                            <li><a class="dropdown-item" href="#">장르별</a></li>
                        </ul>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">커뮤니티</a>
                    </li>
                </ul>
                <form class="d-flex">
                    <input class="form-control me-2" type="search" placeholder="게임 검색" aria-label="Search">
                    <button class="btn btn-outline-light" type="submit">검색</button>
                </form>
            </div>
        </div>
    </nav>

    <main class="container my-4">
        <section class="jumbotron text-center p-5 rounded mb-5 bg-primary text-white">
            <h1 class="display-4">Vibe Codings Game Hub</h1>
            <p class="lead">당신이 찾던 모든 게임, 그리고 그 이상의 경험.</p>
            <a href="#" class="btn btn-light btn-lg mt-3">지금 인기있는 게임 보기</a>
        </section>

        <section class="mb-5">
            <h2 class="text-center mb-4">주요 게임</h2>
            <div id="game-list-container" class="row row-cols-1 row-cols-md-2 row-cols-lg-3 g-4">
                <!-- 게임 카드는 JavaScript에 의해 동적으로 채워집니다. -->
            </div>
        </section>
    </main>

    <footer class="text-center text-lg-start mt-auto bg-dark text-white">
        <div class="container p-4">
            <div class="row">
                <div class="col-lg-6 col-md-12 mb-4 mb-md-0">
                    <h5 class="text-uppercase">Vibe Codings</h5>
                    <p>
                        Vibe Codings는 게이머를 위한 최고의 경험을 제공합니다.
                    </p>
                </div>
            </div>
        </div>
        <div class="text-center p-3" style="background-color: rgba(0, 0, 0, 0.2);">
            © 2025 Vibe Codings. All rights reserved.
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
    <script src="js/script.js"></script>
</body>
</html>
