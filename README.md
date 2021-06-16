<html lang="zh-tw">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
    <style>
        .well,
        .panel {
            text-align: center;
        }
    </style>

    <title>這是作業HW010的網站</title>

</head>

<body>
    <header>
        <div class="container-fluid">
            <div class="row text-center border border-primary">
                這是web測試
            </div>
        </div>
    </header>
        <nav class="navbar navbar-light bg-light">
            <div class="container-fluid">
            <a class="navbar-brand" href="#">第一選項</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Features</a>
                </li>
            </ul>
            </div>
            </div>
        </nav>

    <main>
        <article>
            <div class="container-fluid">
                <div class="row">
                    <div class="col-sm-6">
                        <div class="card">
                            <div class="card-body">
                            <h5 class="card-title">第一種BMI作法</h5>
                            <p class="card-text">
                                <form oninput="result.value=((parseFloat(b.value))/(parseFloat(a.value)/100)/(parseFloat(a.value)/100))">
                                    <p>體重<input type="range" id="b" name="b" value="52" />kg</p>
                                    <p>身高<input type="number" id="a" name="a" value="155" />cm</p>
                                    <p>bmi=<output name="result" for="a b">21.6</output></p>
                                </form>
                            </div>
                        </div>
                    </div>
                    <div class="col-sm-6">
                        <div class="card text-white bg-primary border-secondary">
                            <div class="card-body">
                            <h5 class="card-title">第二種BMI作法</h5>
                            <p class="card-text">
                                <form oninput="result.value=((parseFloat(b.value))/(parseFloat(a.value)/100)/(parseFloat(a.value)/100))">
                                    <p>體重<input type="number" id="b" name="b" value="52" />kg</p>
                                    <p>身高<input type="number" id="a" name="a" value="155" />cm</p>
                                    <p>bmi=<output name="result" for="a b">21.6</output></p>
                                </form>
                            </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </article>
    </main>
    <footer>
        <p class="text-end text-muted">
            Updated on 2021/6/16 by Kate
        </p>
    </footer>
    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
        <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.min.js" integrity="sha384-Atwg2Pkwv9vp0ygtn1JAojH0nYbwNJLPhwyoVbhoPwBhjQPR5VtM2+xf0Uwh9KtT" crossorigin="anonymous"></script>
        -->
</body>

</html>
