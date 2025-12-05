<!DOCTYPE html>

<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ravensburg ROLEPLAY - Regelwerk</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #12122b;
            color: #f0f0f0;
            margin: 0;
            padding: 0;
        }

```
    header {
        background-color: #1e1e3f;
        padding: 20px;
        text-align: center;
    }

    header h1 {
        margin: 0;
        color: #ffcc00;
    }

    main {
        max-width: 900px;
        margin: 30px auto;
        padding: 0 20px;
    }

    .accordion {
        background-color: #1e1e3f;
        color: #f0f0f0;
        cursor: pointer;
        padding: 18px;
        width: 100%;
        border: none;
        text-align: left;
        outline: none;
        font-size: 1.2em;
        transition: 0.3s;
        margin-bottom: 5px;
        border-radius: 8px;
    }

    .accordion:hover {
        background-color: #28284f;
    }

    .accordion.active {
        background-color: #28284f;
    }

    .panel {
        padding: 0 18px 18px 18px;
        display: none;
        background-color: #1a1a33;
        border-radius: 0 0 8px 8px;
        overflow: hidden;
    }

    .panel ul {
        list-style: disc;
        padding-left: 20px;
    }

    footer {
        background-color: #1e1e3f;
        text-align: center;
        padding: 15px;
        margin-top: 40px;
        font-size: 0.9em;
    }

    footer a {
        color: #ffcc00;
        text-decoration: none;
    }

    footer a:hover {
        text-decoration: underline;
    }
</style>
```

</head>
<body>
    <header>
        <h1>Ravensburg ROLEPLAY</h1>
    </header>
    <main>
        <button class="accordion">Chatregeln</button>
        <div class="panel">
            <ul>
                <li>Sei freundlich zu anderen Spielern.</li>
                <li>Keine Beleidigungen oder Rassismus.</li>
                <li>Kein Spamming im Chat.</li>
            </ul>
        </div>

```
    <button class="accordion">Roleplay-Regeln</button>
    <div class="panel">
        <ul>
            <li>Halte dich an die Rolle deines Charakters.</li>
            <li>Keine Meta-Gaming oder Power-Gaming.</li>
            <li>Immersives Verhalten wird erwartet.</li>
        </ul>
    </div>

    <button class="accordion">Strafen</button>
    <div class="panel">
        <ul>
            <li>Verwarnung bei ersten Regelverstößen.</li>
            <li>Temporärer Bann bei wiederholten Verstößen.</li>
            <li>Dauerhafter Bann bei schweren Regelverstößen.</li>
        </ul>
    </div>
</main>
<footer>
    &copy; 2025 Ravensburg ROLEPLAY | Discord: <a href="https://discord.gg/deinlink" target="_blank">Hier klicken</a>
</footer>

<script>
    const accordions = document.querySelectorAll(".accordion");

    accordions.forEach(acc => {
        acc.addEventListener("click", () => {
            acc.classList.toggle("active");
            const panel = acc.nextElementSibling;
            panel.style.display = panel.style.display === "block" ? "none" : "block";
        });
    });
</script>
```

</body>
</html>
