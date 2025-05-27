<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>EcoCycle Home</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Inter', sans-serif; }
    body { background: #f3f4f6; color: #111827; }
    header { background-color: #10b981; color: white; padding: 2rem 1rem; text-align: center; }
    h1 { font-size: 2.5rem; margin-bottom: 0.5rem; }
    h2 { font-size: 1.75rem; margin-top: 2rem; text-align: center; }
    p { font-size: 1rem; margin: 1rem 0; text-align: center; max-width: 700px; margin-left: auto; margin-right: auto; }
    .features { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1.5rem; padding: 2rem; max-width: 1100px; margin: auto; }
    .feature { background: white; padding: 1.5rem; border-radius: 1rem; box-shadow: 0 2px 8px rgba(0,0,0,0.1); }
    .cta { background: #10b981; color: white; padding: 2rem 1rem; text-align: center; }
    input[type="email"] { padding: 0.75rem; width: 300px; border: none; border-radius: 0.5rem 0 0 0.5rem; }
    button { padding: 0.75rem 1rem; border: none; border-radius: 0 0.5rem 0.5rem 0; background: #059669; color: white; cursor: pointer; font-weight: 600; }
    footer { text-align: center; padding: 1rem; color: #6b7280; font-size: 0.875rem; }
  </style>
</head>
<body>
  <header>
    <h1>EcoCycle Home</h1>
    <p>Transforme seus resíduos orgânicos em fertilizante natural de forma rápida, limpa e automatizada.</p>
  </header>

  <section class="features">
    <div class="feature">
      <h3>Sem Odor</h3>
      <p>Filtros de carvão ativado e ozônio garantem um processo sem cheiros desagradáveis.</p>
    </div>
    <div class="feature">
      <h3>Fácil de Usar</h3>
      <p>Interface simples com painel touch ou app para operação intuitiva.</p>
    </div>
    <div class="feature">
      <h3>Resultado Rápido</h3>
      <p>Transforma restos de comida em fertilizante em poucas horas com auxílio de biotecnologia.</p>
    </div>
    <div class="feature">
      <h3>Conectado ao Verde</h3>
      <p>Doa o excedente para hortas urbanas e registre sua pegada sustentável no app.</p>
    </div>
  </section>

  <section class="cta">
    <h2>Receba novidades e seja um dos primeiros a testar!</h2>
    <form>
      <input type="email" placeholder="Digite seu e-mail" required />
      <button type="submit">Quero Participar</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 EcoCycle Home. Sustentabilidade com inteligência.</p>
  </footer>
</body>
</html>
