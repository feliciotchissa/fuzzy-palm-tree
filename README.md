1# fuzzy-palm-tree
Site de negocio Felício Tchissa Electronics 
<!doctype html>
<html lang="pt">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Felício Tchissa Electronics — Soluções & Serviços</title>
  <meta name="description" content="Felício Tchissa Electronics — venda e assistência técnica de equipamentos electrónicos: smartphones, acessórios, reparações e serviços empresariais." />
  <!-- Open Graph básico -->
  <meta property="og:title" content="Felício Tchissa Electronics" />
  <meta property="og:description" content="Venda e assistência técnica de equipamentos electrónicos: smartphones, acessórios e serviços empresariais." />
  <meta property="og:type" content="website" />
  <meta name="theme-color" content="#0b74de" />

  <!-- Estilos integrados para facilidade de edição -->
  <style>
    :root{
      --bg:#f7f9fc; --card:#ffffff; --muted:#6b7280; --accent:#0b74de;
      --glass: rgba(255,255,255,0.6);
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:var(--bg);color:#0b1720;line-height:1.5}
    header{background:linear-gradient(90deg,var(--accent), #075fa8); color:white; padding:18px 20px; position:sticky; top:0; z-index:20}
    .container{max-width:1100px;margin:0 auto;padding:20px}
    .brand{display:flex;align-items:center;gap:12px}
    .brand .logo{width:44px;height:44px;border-radius:8px;background:white;color:var(--accent);display:flex;align-items:center;justify-content:center;font-weight:700}
    nav{margin-left:auto}
    .nav-list{display:flex;gap:18px;list-style:none;padding:0;margin:0}
    .nav-list a{color:rgba(255,255,255,0.95);text-decoration:none;font-weight:600}
    .hero{display:grid;grid-template-columns:1fr;gap:18px;align-items:center;padding:46px 0}
    .hero h1{font-size:28px;margin:0 0 10px}
    .hero p{color:var(--glass);margin:0 0 18px}
    .btn{background:var(--accent);color:white;padding:10px 16px;border-radius:10px;text-decoration:none;font-weight:700;display:inline-block}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:18px}
    .card{background:var(--card);padding:16px;border-radius:12px;box-shadow:0 6px 20px rgba(12,23,40,0.06)}
    .services .card h3{margin:0 0 8px}
    .products img{width:100%;height:160px;object-fit:cover;border-radius:8px;margin-bottom:8px}
    section{padding:28px 0}
    footer{padding:18px 0;color:var(--muted);font-size:14px}
    /* Responsivo: menu mobile */
    .menu-toggle{display:none}
    @media (max-width:880px){
      .nav-list{display:none}
      .menu-toggle{display:inline-block;background:transparent;border:1px solid rgba(255,255,255,0.12);color:white;padding:8px 10px;border-radius:8px}
      header .container{display:flex;align-items:center;gap:12px}
    }
    /* Form */
    form input, form textarea{width:100%;padding:10px;border-radius:8px;border:1px solid #e6e9ee;margin-top:8px}
    .muted{color:var(--muted)}
    /* Small utilities */
    .flex{display:flex;gap:12px;align-items:center}
    .space-between{display:flex;justify-content:space-between;align-items:center}
  </style>
</head>
<body>
  <header>
    <div class="container space-between">
      <div class="brand">
        <div class="logo">FT</div>
        <div>
          <div style="font-weight:800">Felício Tchissa Electronics</div>
          <div style="font-size:12px;color:rgba(255,255,255,0.9)">Soluções eletrónicas & assistência técnica</div>
        </div>
      </div>

      <nav>
        <button class="menu-toggle" aria-expanded="false" onclick="toggleMenu()">Menu</button>
        <ul class="nav-list" id="navList">
          <li><a href="#servicos">Serviços</a></li>
          <li><a href="#produtos">Produtos</a></li>
          <li><a href="#sobre">Sobre</a></li>
          <li><a href="#contacto">Contacto</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <main class="container">
    <!-- Hero -->
    <section class="hero">
      <div>
        <h1>Equipamentos, assistência e soluções inteligentes — feito para o negócio e para o cliente.</h1>
        <p class="muted">Venda de smartphones, acessórios, peças e um serviço técnico rápido e confiável. Estratégia comercial orientada à eficiência e margem — pensamos crescimento.</p>
        <div class="flex">
          <a class="btn" href="#produtos">Ver Produtos</a>
          <a style="align-self:center;text-decoration:none;color:var(--accent);font-weight:700" href="#contacto">Solicitar Orçamento →</a>
        </div>
      </div>
      <div class="card" aria-hidden="true">
        <!-- Espaço para imagem ou carrossel -->
        <img src="https://via.placeholder.com/700x420?text=Loja+Felicio+Tchissa" alt="Loja" style="width:100%;height:220px;object-fit:cover;border-radius:8px;margin-bottom:12px">
        <div style="display:flex;justify-content:space-between;gap:12px">
          <div>
            <div style="font-weight:700">10.000+</div>
            <div class="muted">Peças & acessórios</div>
          </div>
          <div>
            <div style="font-weight:700">+5 anos</div>
            <div class="muted">Experiência técnica</div>
          </div>
          <div>
            <div style="font-weight:700">Suporte</div>
            <div class="muted">Rápido e profissional</div>
          </div>
        </div>
      </div>
    </section>

    <!-- Serviços -->
    <section id="servicos">
      <h2>Serviços</h2>
      <div class="grid services">
        <div class="card">
          <h3>Assistência Técnica</h3>
          <p class="muted">Reparações de hardware, substituição de ecrãs, manutenção e diagnóstico. Garantia nas intervenções.</p>
        </div>
        <div class="card">
          <h3>Venda e Fornecimento</h3>
          <p class="muted">Stock de smartphones, acessórios e peças originais. Preços competitivos para revenda e empresa.</p>
        </div>
        <div class="card">
          <h3>Soluções para Empresas</h3>
          <p class="muted">Fleet management, contratos de manutenção e suporte técnico dedicado para equipas e lojas.</p>
        </div>
        <div class="card">
          <h3>Consultoria de Vendas</h3>
          <p class="muted">Aconselhamento em mix de produtos, margem e estratégia de posicionamento para maximizar lucros.</p>
        </div>
      </div>
    </section>

    <!-- Produtos -->
    <section id="produtos">
      <div style="display:flex;justify-content:space-between;align-items:center">
        <h2>Produtos em destaque</h2>
        <a href="#contacto" style="text-decoration:none;color:var(--accent);font-weight:700">Peça um orçamento →</a>
      </div>
      <div class="grid products" style="margin-top:12px">
        <!-- Troca as imagens e descrições pelos teus produtos reais -->
        <div class="card">
          <img src="https://via.placeholder.com/600x400?text=Smartphone+X" alt="Smartphone X">
          <h3>Smartphone Modelo X</h3>
          <p class="muted">Ecrã AMOLED, 128GB, garantia 12 meses.</p>
        </div>
        <div class="card">
          <img src="https://via.placeholder.com/600x400?text=Acessorio+Y" alt="Acessório Y">
          <h3>Acessório Y</h3>
          <p class="muted">Fones, carregadores e acessórios oficiais.</p>
        </div>
        <div class="card">
          <img src="https://via.placeholder.com/600x400?text=Peça+Z" alt="Peça Z">
          <h3>Peça de Substituição Z</h3>
          <p class="muted">Peças originais para reparação — stock para revenda.</p>
        </div>
      </div>
    </section>

    <!-- Sobre -->
    <section id="sobre">
      <h2>Sobre a Felício Tchissa Electronics</h2>
      <div class="card">
        <p class="muted">Somos uma empresa com foco em resultados comerciais e satisfação do cliente. Prioridade em rapidez de assistência, qualidade de peças e parcerias B2B. Operamos com transparência de preços e processos otimizados para reduzir tempo de reparo e aumentar a rotatividade de stock.</p>
        <ul style="margin-top:12px;color:var(--muted)">
          <li>Horário: Seg–Sáb 08:00–18:00</li>
          <li>Local: [Endereço da loja / cidade]</li>
          <li>Garantia em serviços: 90 dias (ajusta conforme política)</li>
        </ul>
      </div>
    </section>

    <!-- Contacto -->
    <section id="contacto">
      <h2>Contacto / Solicitar Orçamento</h2>
      <div class="grid" style="align-items:start">
        <div class="card">
          <h3>Fale connosco</h3>
          <p class="muted">Telefone: <strong>+258 8xx xxx xxx</strong><br/>Email: <strong>contacto@feliciotchissa.com</strong></p>
          <p class="muted">Atendemos pedidos comerciais com prioridade: indique modelo, quantidade e prazos.</p>

          <!-- Formulário simples (substituir action por endpoint real) -->
          <form id="contactForm" onsubmit="submitForm(event)">
            <label>Nome</label>
            <input type="text" id="name" required placeholder="Nome completo">

            <label>Empresa (opcional)</label>
            <input type="text" id="company" placeholder="Nome da empresa">

            <label>Telefone ou WhatsApp</label>
            <input type="tel" id="phone" required placeholder="+258 8xx xxx xxx">

            <label>Mensagem / Pedido</label>
            <textarea id="message" rows="4" required placeholder="Descreva o pedido: produto, quantidade, prazo"></textarea>

            <div style="margin-top:12px">
              <button class="btn" type="submit">Enviar pedido</button>
            </div>
            <div id="formStatus" style="margin-top:10px;color:var(--muted)"></div>
          </form>
        </div>

        <div class="card">
          <h3>Localização</h3>
          <p class="muted">Coloca aqui um mapa embebido (Google Maps) ou instruções de como chegar.</p>
          <!-- Placeholder para mapa -->
          <div style="background:#eef2f7;height:220px;border-radius:8px;display:flex;align-items:center;justify-content:center;color:var(--muted)">
            MAPA / EMBED AQUI
          </div>

          <h4 style="margin-top:14px">Horário</h4>
          <p class="muted">Seg–Sáb 08:00–18:00</p>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="container space-between">
      <div>
        © <strong>Felício Tchissa Electronics</strong> — Todos os direitos reservados.
      </div>
      <div class="muted">Política de privacidade • Termos • Desenvolvido por equipa interna</div>
    </div>
  </footer>

  <!-- JSON-LD para SEO local (personaliza o endereço/telefone) -->
  <script type="application/ld+json">
  {
    "@context":"https://schema.org",
    "@type":"Store",
    "name":"Felício Tchissa Electronics",
    "description":"Venda e assistência técnica de equipamentos electrónicos.",
    "telephone":"+2588xxxxxxx",
    "address":{
      "@type":"PostalAddress",
      "streetAddress":"[Rua e número]",
      "addressLocality":"[Cidade]",
      "addressRegion":"[Província]",
      "postalCode":"[Código postal]",
      "addressCountry":"MZ"
    },
    "openingHours":"Mo-Sa 08:00-18:00"
  }
  </script>

  <!-- JS mínimo -->
  <script>
    function toggleMenu(){
      const nav = document.getElementById('navList');
      const btn = document.querySelector('.menu-toggle');
      const open = nav.style.display === 'flex';
      nav.style.display = open ? 'none' : 'flex';
      btn.setAttribute('aria-expanded', String(!open));
    }

    // Submissão de formulário: por defeito usa mailto se não houver endpoint.
    function submitForm(e){
      e.preventDefault();
      const name = document.getElementById('name').value.trim();
      const company = document.getElementById('company').value.trim();
      const phone = document.getElementById('phone').value.trim();
      const message = document.getElementById('message').value.trim();
      const status = document.getElementById('formStatus');

      if(!name || !phone || !message){
        status.textContent = 'Preencha os campos obrigatórios.';
        return;
      }

      // Se tiveres um endpoint backend, substitui aqui por fetch('/api/contact', {method:'POST', body:...})
      // Enquanto isso: abre email com dados (fallback prático)
      const subject = encodeURIComponent('Pedido via site — ' + name);
      const body = encodeURIComponent(
        `Nome: ${name}\nEmpresa: ${company}\nTelefone:855304533 ${phone}\n\nPedido:\n${message}`
      );
      window.location.href = `mailto:contacto@feliciotchissa.com?subject=${subject}&body=${body}`;
      status.textContent = 'A abrir cliente de email para envio. Se não abrir, contacte diretamente o email.';
    }
  </script>
</body>
</html>![Uploading 20251129_144603.jpg…]()
