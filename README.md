<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>LUNÉ-</title>
    <style>
      :root {
        --bg: #0f172a;
        --card: #111827;
        --text: #e5e7eb;
        --muted: #94a3b8;
        --accent: #f472b6;
        --accent-2: #a78bfa;
      }

      * {
        box-sizing: border-box;
      }

      body {
        margin: 0;
        min-height: 100vh;
        display: grid;
        place-items: center;
        font-family: Arial, Helvetica, sans-serif;
        background: linear-gradient(135deg, var(--bg), #1e293b);
        color: var(--text);
      }

      .card {
        width: min(90vw, 700px);
        background: rgba(17, 24, 39, 0.75);
        border: 1px solid rgba(255, 255, 255, 0.08);
        border-radius: 20px;
        padding: 48px 36px;
        box-shadow: 0 20px 45px rgba(0, 0, 0, 0.35);
        text-align: center;
      }

      h1 {
        margin: 0;
        font-size: clamp(2.5rem, 6vw, 5rem);
        letter-spacing: 0.08em;
        background: linear-gradient(90deg, var(--accent), var(--accent-2));
        -webkit-background-clip: text;
        background-clip: text;
        color: transparent;
      }

      p {
        margin-top: 18px;
        font-size: 1.1rem;
        line-height: 1.7;
        color: var(--muted);
      }

      .tag {
        display: inline-block;
        margin-top: 22px;
        padding: 10px 18px;
        border-radius: 999px;
        background: rgba(244, 114, 182, 0.12);
        border: 1px solid rgba(244, 114, 182, 0.35);
        color: #f9a8d4;
        letter-spacing: 0.08em;
        text-transform: uppercase;
        font-size: 0.8rem;
        font-weight: bold;
      }
    </style>
  </head>
  <body>
    <main class="card">
      <h1>LUNÉ-</h1>
      <p>My personal space</p>
      <div class="tag">Welcome</div>
    </main>
  </body>
</html>
