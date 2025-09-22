<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Assignment 2 – GitHub Pages</title>
  <meta name="description" content="Assignment 2 page: name, short introduction, and hobbies presented in a table." />
  <style>
    :root {
      --bg: #0b1220;
      --card: #111a2b;
      --text: #e6edf3;
      --muted: #9fb0c3;
      --accent: #58a6ff;
      --border: #263043;
    }
    * { box-sizing: border-box; }
    html, body { height: 100%; }
    body {
      margin: 0;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji", "Segoe UI Emoji";
      background: radial-gradient(1200px 800px at 10% 0%, #0f172a 0%, var(--bg) 45%, #070c16 100%);
      color: var(--text);
      line-height: 1.6;
      display: grid;
      place-items: center;
      padding: 2rem;
    }
    .container {
      width: min(900px, 100%);
    }
    header {
      margin-bottom: 1.5rem;
      text-align: center;
    }
    header h1 { margin: 0 0 .25rem; font-size: clamp(1.6rem, 2.2vw + 1rem, 2.4rem); }
    header p { margin: 0; color: var(--muted); }

    .card {
      background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.0));
      border: 1px solid var(--border);
      border-radius: 18px;
      padding: 1.25rem;
      box-shadow: 0 10px 30px rgba(0,0,0,0.25);
    }

    table { width: 100%; border-collapse: collapse; margin-top: .5rem; }
    thead th {
      text-align: left;
      font-weight: 700;
      padding: .75rem .9rem;
      border-bottom: 1px solid var(--border);
      color: var(--muted);
      letter-spacing: .02em;
    }
    tbody td { padding: .9rem; vertical-align: top; border-bottom: 1px dashed var(--border); }
    tbody tr:last-child td { border-bottom: none; }

    .footer {
      margin-top: 1rem;
      color: var(--muted);
      font-size: .95rem;
    }
    a { color: var(--accent); text-decoration: none; }
    a:hover { text-decoration: underline; }

    .note {
      margin-top: 1rem;
      padding: .75rem 1rem;
      border: 1px solid var(--border);
      background: #0a1323;
      border-radius: 12px;
      font-size: .95rem;
      color: var(--muted);
    }
    code { font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, "Liberation Mono", monospace; font-size: .95em; }
  </style>
</head>
<body>
  <main class="container">
    <header>
      <h1>Welcome to My GitHub Page</h1>
      <p>Assignment 2 – GitHub Pages (live site + source repo)</p>
    </header>

    <section class="card" aria-labelledby="info-heading">
      <h2 id="info-heading" style="margin:0 0 .5rem 0; font-size:1.15rem; color:var(--muted);">Required Information</h2>
      <table role="table" aria-label="Profile table">
        <thead>
          <tr>
            <th scope="col">Name</th>
            <th scope="col">Introduction</th>
            <th scope="col">Hobbies</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <!-- TODO: Replace placeholder content with your real info -->
            <td><strong>Your Name</strong></td>
            <td>Hello, I am a junior in the BS IT program. I enjoy coding Python and R.</td>
            <td>Programming, making websites</td>
          </tr>
        </tbody>
      </table>

      <
