```html
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Computer Science Portfolio</title>

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

    <style>
        body{
            background-color:#f8f9fa;
        }

        .hero{
            background: linear-gradient(135deg,#0d6efd,#6610f2);
            color:white;
            padding:100px 0;
        }

        .section{
            padding:80px 0;
        }

        .project-card{
            transition:0.3s;
        }

        .project-card:hover{
            transform:translateY(-8px);
        }

        footer{
            background:#212529;
            color:white;
            padding:30px;
        }
    </style>
</head>
<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top">
    <div class="container">
        <a class="navbar-brand" href="#">My Portfolio</a>

        <button class="navbar-toggler"
                data-bs-toggle="collapse"
                data-bs-target="#menu">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="menu">
            <ul class="navbar-nav ms-auto">
                <li class="nav-item">
                    <a class="nav-link" href="#about">자기소개</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="#projects">프로젝트</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="#skills">기술스택</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link" href="#github">GitHub</a>
                </li>
            </ul>
        </div>
    </div>
</nav>


<!-- Hero -->
<section class="hero text-center">
    <div class="container">
        <h1 class="display-4 fw-bold">
            안녕하세요 👋
        </h1>

        <h2>컴퓨터공학과 학생 홍길동입니다.</h2>

        <p class="lead mt-3">
            백엔드와 웹 개발에 관심이 있으며
            사용자에게 가치 있는 서비스를 만드는 개발자를 목표로 하고 있습니다.
        </p>
    </div>
</section>


<!-- 자기소개 -->
<section id="about" class="section">
    <div class="container">

        <h2 class="text-center mb-5">자기소개</h2>

        <div class="card shadow">
            <div class="card-body">

                <h4>홍길동</h4>

                <p>
                    ○○대학교 컴퓨터공학과 재학 중이며
                    Java, Spring Boot, Python을 공부하고 있습니다.
                </p>

                <p>
                    새로운 기술을 배우고 프로젝트를 통해
                    문제를 해결하는 과정에 큰 흥미를 느끼고 있습니다.
                </p>

            </div>
        </div>

    </div>
</section>


<!-- 프로젝트 -->
<section id="projects" class="section bg-light">
    <div class="container">

        <h2 class="text-center mb-5">
            프로젝트
        </h2>

        <div class="row">

            <div class="col-md-6 mb-4">

                <div class="card shadow project-card">

                    <div class="card-body">

                        <h4>AI 챗봇 서비스</h4>

                        <p>
                            OpenAI API를 활용한 질의응답 서비스
                        </p>

                        <span class="badge bg-primary">
                            Spring Boot
                        </span>

                        <span class="badge bg-success">
                            React
                        </span>

                        <span class="badge bg-secondary">
                            MySQL
                        </span>

                    </div>

                </div>

            </div>


            <div class="col-md-6 mb-4">

                <div class="card shadow project-card">

                    <div class="card-body">

                        <h4>학사관리 시스템</h4>

                        <p>
                            학생 정보 및 수강신청 관리 웹 서비스
                        </p>

                        <span class="badge bg-warning text-dark">
                            Java
                        </span>

                        <span class="badge bg-info">
                            Bootstrap
                        </span>

                        <span class="badge bg-dark">
                            MySQL
                        </span>

                    </div>

                </div>

            </div>

        </div>

    </div>
</section>


<!-- 기술스택 -->
<section id="skills" class="section">

    <div class="container">

        <h2 class="text-center mb-5">
            기술 스택
        </h2>

        <div class="row text-center">

            <div class="col-md-3 mb-4">
                <div class="card shadow">
                    <div class="card-body">
                        <h4>Frontend</h4>
                        HTML<br>
                        CSS<br>
                        JavaScript<br>
                        Bootstrap
                    </div>
                </div>
            </div>


            <div class="col-md-3 mb-4">
                <div class="card shadow">
                    <div class="card-body">
                        <h4>Backend</h4>
                        Java<br>
                        Spring Boot<br>
                        Python
                    </div>
                </div>
            </div>


            <div class="col-md-3 mb-4">
                <div class="card shadow">
                    <div class="card-body">
                        <h4>Database</h4>
                        MySQL<br>
                        Oracle
                    </div>
                </div>
            </div>


            <div class="col-md-3 mb-4">
                <div class="card shadow">
                    <div class="card-body">
                        <h4>Tools</h4>
                        Git<br>
                        GitHub<br>
                        VS Code
                    </div>
                </div>
            </div>

        </div>

    </div>

</section>


<!-- Github -->
<section id="github" class="section bg-light">

    <div class="container text-center">

        <h2 class="mb-4">
            GitHub
        </h2>

        <a href="https://github.com/your-github-id"
           class="btn btn-dark btn-lg"
           target="_blank">

            GitHub 바로가기

        </a>

    </div>

</section>


<!-- Footer -->
<footer class="text-center">

    <h5>Contact</h5>

    <p>
        Email : example@email.com
    </p>

    <p>
        © 2026 Portfolio
    </p>

</footer>


<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
```
