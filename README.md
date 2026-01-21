# dstech-site
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DSTECH | Soluções em Tecnologia</title>
  <style>
    :root {
      --primary: #0f172a;
      --secondary: #2563eb;
      --light: #f8fafc;
      --gray: #64748b;
    }
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Inter", Arial, sans-serif;
    }
    body {
      background: var(--light);
      color: var(--primary);
      line-height: 1.6;
    }
    header {
      padding: 80px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 3rem;
      letter-spacing: 2px;
    }
    header span {
      color: var(--secondary);
    }
    header p {
      margin-top: 20px;
      color: var(--gray);
      max-width: 600px;
      margin-inline: auto;
    }
    section {
      padding: 80px 20px;
      max-width: 1100px;
      margin: auto;
    }
    h2 {
      font-size: 2rem;
      margin-bottom: 30px;
      text-align: center;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 30px;
    }
    .card {
      background: #fff;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 10px 30px rgba(0,0,0,.05);
    }
    .card h3 {
      margin-bottom: 15px;
      color: var(--secondary);
    }
    .clients ul {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 15px;
      list-style: none;
      text-align: center;
    }
    .clients li {
      background: #fff;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 5px 15px rgba(0,0,0,.04);
    }
    .contact {
      text-align: center;
    }
    .contact p {
      margin-bottom: 10px;
      color: var(--gray);
    }
    footer {
      background: var(--primary);
      color: #fff;
      text-align: center;
      padding: 30px 20px;
      font-size: .9rem;
    }
  </style>
  <style>
    .whatsapp-float {
      position: fixed;
      bottom: 25px;
      right: 25px;
      background: #25D366;
      color: #fff;
      padding: 14px 20px;
      border-radius: 50px;
      text-decoration: none;
      font-weight: 600;
      box-shadow: 0 10px 25px rgba(0,0,0,.25);
      display: flex;
      align-items: center;
      gap: 10px;
      z-index: 999;
    }
    .whatsapp-float:hover {
      background: #1ebe5d;
    }
  </style>
</head>
<body>

  <header>
    <h1>DS<span>TECH</span></h1>
    <p>Soluções tecnológicas inteligentes para reduzir custos, aumentar a segurança e manter sua empresa sempre online.</p>
    <a href="#contato" style="display:inline-block;margin-top:30px;padding:15px 30px;background:var(--secondary);color:#fff;border-radius:30px;text-decoration:none;font-weight:600;">Solicitar Diagnóstico Gratuito</a>
  </header>

  <section>
    <h2>Por que escolher a DSTECH?</h2>
    <div class="services">
      <div class="card"><h3>Atendimento Rápido</h3><p>Suporte técnico com resposta em menos de 3 horas para evitar paradas no seu negócio.</p></div>
      <div class="card"><h3>Especialistas Certificados</h3><p>Profissionais atualizados com as tecnologias mais usadas no mercado corporativo.</p></div>
      <div class="card"><h3>Soluções Sob Medida</h3><p>Projetos personalizados de acordo com a necessidade real da sua empresa.</p></div>
    </div>
  </section>

  <section>
    <h2>Serviços</h2>
    <div class="services">
      <div class="card">
        <h3>Redes & Conectividade</h3>
        <p>Banda larga, redes wireless, QoS, diagnóstico de tráfego e documentação de redes.</p>
      </div>
      <div class="card">
        <h3>Segurança & CFTV</h3>
        <p>Instalação de câmeras, projetos CFTV, configuração de DVR, firewall e monitoramento remoto.</p>
      </div>
      <div class="card">
        <h3>Servidores & Cloud</h3>
        <p>Servidores Linux e Windows, Docker, cloud AWS, storage e rotinas de backup.</p>
      </div>
      <div class="card">
        <h3>Suporte Técnico</h3>
        <p>Chamados avulsos ou contratos, manutenção de hardware, desktops, notebooks e softwares.</p>
      </div>
    </div>
  </section>

  <section>
    <h2>Planos a partir de R$ 650,00</h2>
    <p style="text-align:center;max-width:700px;margin:0 auto 40px;color:var(--gray);">Escolha o plano ideal para manter sua empresa segura, produtiva e com suporte técnico especializado.</p>
    <div class="services">
      <div class="card">
        <h3>Plano Essencial</h3>
        <p style="font-size:1.5rem;font-weight:700;margin:15px 0;">R$ 650,00 / mês</p>
        <p>✔ Suporte técnico remoto<br>✔ Manutenção de desktops e notebooks<br>✔ Chamados avulsos<br>✔ Avaliação de novas tecnologias</p>
        <a href="https://wa.me/5581984324555?text=Olá!%20Tenho%20interesse%20no%20Plano%20Essencial%20de%20R$650." target="_blank" style="display:inline-block;margin-top:20px;padding:12px 25px;background:var(--secondary);color:#fff;border-radius:30px;text-decoration:none;font-weight:600;">Quero esse plano</a>
      </div>
      <div class="card" style="border:2px solid var(--secondary);">
        <h3>Plano Profissional</h3>
        <p style="font-size:1.5rem;font-weight:700;margin:15px 0;">Sob Consulta</p>
        <p>✔ Tudo do Essencial<br>✔ Administração de servidores<br>✔ Backup e storage<br>✔ Firewall e segurança<br>✔ Monitoramento contínuo</p>
        <a href="https://wa.me/5581984324555?text=Olá!%20Gostaria%20de%20informações%20sobre%20o%20Plano%20Profissional." target="_blank" style="display:inline-block;margin-top:20px;padding:12px 25px;background:var(--secondary);color:#fff;border-radius:30px;text-decoration:none;font-weight:600;">Falar com consultor</a>
      </div>
      <div class="card">
        <h3>Plano Enterprise</h3>
        <p style="font-size:1.5rem;font-weight:700;margin:15px 0;">Personalizado</p>
        <p>✔ Projetos de CFTV<br>✔ Cloud AWS<br>✔ Docker & DevOps<br>✔ Monitoramento 24x7<br>✔ SLA dedicado</p>
        <a href="https://wa.me/5581984324555?text=Olá!%20Quero%20um%20plano%20Enterprise%20personalizado." target="_blank" style="display:inline-block;margin-top:20px;padding:12px 25px;background:var(--secondary);color:#fff;border-radius:30px;text-decoration:none;font-weight:600;">Solicitar proposta</a>
      </div>
    </div>
  </section>

  <section class="clients">
    <h2>Clientes</h2>
    <ul>
      <li>Tower Tecnologia</li>
      <li>Centro Nordestino de Medicina Popular</li>
      <li>Fluxo Digital</li>
      <li>Macedo Rocha Contabilidade</li>
      <li>Tecvia Engenharia</li>
      <li>Sacolão Medicamentos</li>
    </ul>
  </section>

  <section class="contact" id="contato">
    <h2>Fale com um Especialista</h2>
    <p>Receba uma avaliação gratuita da infraestrutura da sua empresa.</p>
    <form style="max-width:500px;margin:40px auto;display:grid;gap:15px;">
      <input type="text" placeholder="Nome" required style="padding:12px;border-radius:8px;border:1px solid #cbd5f5;">
      <input type="email" placeholder="E-mail" required style="padding:12px;border-radius:8px;border:1px solid #cbd5f5;">
      <input type="tel" placeholder="Telefone / WhatsApp" required style="padding:12px;border-radius:8px;border:1px solid #cbd5f5;">
      <textarea placeholder="Descreva sua necessidade" rows="4" style="padding:12px;border-radius:8px;border:1px solid #cbd5f5;"></textarea>
      <button type="submit" style="padding:15px;border:none;border-radius:30px;background:var(--secondary);color:#fff;font-weight:600;cursor:pointer;">Quero ser contactado</button>
    </form>
    <p>📍 Recife - PE · 📞 (81) 98432-4555 · ✉️ danilo@dstechpe.com.br</p>
  </section>

  <footer>
    © 2026 DSTECH · Tecnologia que conecta resultados
  </footer>

  <a class="whatsapp-float" href="https://wa.me/5581984324555?text=Olá!%20Gostaria%20de%20solicitar%20um%20diagnóstico%20gratuito%20de%20TI." target="_blank">
    💬 Falar no WhatsApp
  </a>

</body>
</html>
