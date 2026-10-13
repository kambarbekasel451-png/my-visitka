```html
<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- META тегтер -->
    <meta name="description" content="Мен туралы жеке визитка-сайт. Оқуым, дағдыларым және қызығушылықтарым.">
    <meta name="keywords" content="студент, киберқауіпсіздік, HTML, ақпараттық қауіпсіздік">
    <meta name="author" content="Студент Қамбарбек Әсел">
    <meta name="referrer" content="strict-origin-when-cross-origin">
    <meta name="robots" content="noindex, nofollow">

    <!-- Open Graph -->
    <meta property="og:title" content="Менің жеке визиткам">
    <meta property="og:description" content="Менің оқуым, дағдыларым және қызығушылықтарым туралы сайт.">
    <meta property="og:image" content="https://placehold.co/600x400/172554/ffffff?text=My+Profile">

    <title>Менің жеке визиткам</title>

    <link rel="icon" href="https://placehold.co/32x32/172554/ffffff?text=M" type="image/png">

    <!-- Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

    <!-- Кірістірілген CSS стильдері -->
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2b7e5;
            color: #000108;
            margin: 0;
            line-height: 1.6;
        }

        header {
            background-color: #c38aee;
            color: white;
            text-align: center;
            padding: 30px;
            position: relative;
        }

        main {
            margin: 20px auto;
            padding: 20px;
        }

        section {
            background-color: white;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 10px;
        }

        h2 {
            color: #020613;
        }

        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            font-size: 12px;
        }

        th, td {
            border: 1px solid #94a3b8;
            padding: 8px;
            text-align: center;
        }

        th {
            background-color: #9cb4e8;
            color: white;
        }

        a {
            color: #594fe8;
        }

        footer {
            background-color: #c38aee;
            color: white;
            text-align: center;
            padding: 15px;
        }

        /* Position қасиеті */
        .profile-title {
            position: relative;
        }

        /* Bootstrap grid ішіндегі сурет */
        .profile-photo {
            width: 300px;
            max-width: 100%;
        }

        /* Медиасұраныс: телефон экрандары */
        @media (max-width: 600px) {
            header {
                padding: 20px 10px;
            }

            main {
                margin: 10px auto;
                padding: 10px;
            }

            section {
                padding: 12px;
                overflow-x: auto;
            }

            table {
                min-width: 550px;
            }

            h1 {
                font-size: 25px;
            }
        }
    </style>
</head>

<body>

    <header>
        <h1 class="profile-title">Менің жеке визиткам</h1>
        <p>Болашақ ақпараттық қауіпсіздік маманы</p>
    </header>

    <!-- Bootstrap container және grid -->
    <main class="container">

        <section class="row align-items-center">
            <div class="col-12 col-md-5 text-center mb-3">
                <h2>Мен туралы</h2>

                <img
                    class="profile-photo"
                    src="https://bukivedi.com/upload/medialibrary/970/9707cab7d857d5870931e0b9d06afb50.jpg"
                    alt="Қамбарбек Әселдің суреті">
            </div>

            <div class="col-12 col-md-7">
                <p><strong>Атым:</strong> Қамбарбек Әсел</p>
                <p><strong>Жасым:</strong> 17</p>
                <p><strong>Туған жерім:</strong> Талдықорған қаласы</p>

                <h3>Қысқаша ақпарат</h3>
                <p>Мен екінші курс студентімін. Ақпараттық қауіпсіздік саласына қызығамын.</p>
                <p>Бос уақытымда жаңа нәрселер үйреніп, кітап оқып, бағдарламалау дағдыларымды дамытамын.</p>
            </div>
        </section>

        <section>
            <h2>Менің дағдыларым</h2>
            <ul>
                <li>HTML және CSS негіздері</li>
                <li>Киберқауіпсіздік негіздері</li>
                <li>Компьютермен жұмыс істеу</li>
                <li>Ақпарат іздеу және талдау</li>
            </ul>
        </section>

        <section>
            <h2>Менің сабақ кестем</h2>

            <div class="table-responsive">
                <table>
                    <thead>
                        <tr>
                            <th>Уақыт</th>
                            <th>Дүйсенбі</th>
                            <th>Сейсенбі</th>
                            <th>Сәрсенбі</th>
                            <th>Бейсенбі</th>
                            <th>Жұма</th>
                        </tr>
                    </thead>

                    <tbody>
                        <tr>
                            <td>07:50–08:40</td>
                            <td>—</td>
                            <td>Математика III</td>
                            <td>—</td>
                            <td>—</td>
                            <td>Дене шынықтыру III</td>
                        </tr>

                        <tr>
                            <td>08:55–09:45</td>
                            <td>—</td>
                            <td>—</td>
                            <td>—</td>
                            <td>—</td>
                            <td>Дене шынықтыру III</td>
                        </tr>

                        <tr>
                            <td>10:00–10:50</td>
                            <td>Дискретті математика</td>
                            <td>—</td>
                            <td>—</td>
                            <td>—</td>
                            <td>—</td>
                        </tr>

                        <tr>
                            <td>11:05–11:55</td>
                            <td>Дискретті математика</td>
                            <td>Математика III</td>
                            <td>—</td>
                            <td>—</td>
                            <td>—</td>
                        </tr>

                        <tr>
                            <td>12:10–13:00</td>
                            <td>Дискретті математика</td>
                            <td>Математика III</td>
                            <td>Web бағдарламалау</td>
                            <td>—</td>
                            <td>—</td>
                        </tr>

                        <tr>
                            <td>13:15–14:05</td>
                            <td>—</td>
                            <td>Сыбайлас жемқорлыққа қарсы мәдениет</td>
                            <td>—</td>
                            <td>—</td>
                            <td>—</td>
                        </tr>

                        <tr>
                            <td>14:20–15:10</td>
                            <td>Философия</td>
                            <td>Сыбайлас жемқорлыққа қарсы мәдениет</td>
                            <td>Web бағдарламалау</td>
                            <td>—</td>
                            <td>—</td>
                        </tr>

                        <tr>
                            <td>15:25–16:15</td>
                            <td>Философия</td>
                            <td>Сыбайлас жемқорлыққа қарсы мәдениет</td>
                            <td>Әлеуметтік-саяси білім модулі</td>
                            <td>—</td>
                            <td>—</td>
                        </tr>

                        <tr>
                            <td>16:30–17:20</td>
                            <td>—</td>
                            <td>—</td>
                            <td>Web бағдарламалау</td>
                            <td>—</td>
                            <td>—</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </section>

        <section>
            <h2>Пайдалы сілтеме</h2>
            <p>
                HTML туралы көбірек білу үшін
                <a href="https://developer.mozilla.org/"
                   target="_blank"
                   rel="noopener noreferrer">
                    MDN Web Docs
                </a>
                сайтына кіріңіз.
            </p>
        </section>

    </main>

    <footer>
        <p>© 2026 Менің жеке визиткам</p>
    </footer>

</body>
</html>
```
