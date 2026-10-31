<div align="center">

  <!-- ==================== 00 // HERO BANNER CYBERPUNK HUD ==================== -->
  <a href="https://github.com/DevNaur">
    <img src="./assets/header.svg" width="100%" alt="Caick Ruan — Software Engineer &amp; Cybersecurity" />
  </a>

  <br/><br/>

  <!-- ==================== QUICK ACCESS CYBER HUD BUTTONS ==================== -->
  <p align="center">
    <a href="https://www.linkedin.com/in/caick-santana-dev" target="_blank">
      <img src="https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    &nbsp;&nbsp;
    <a href="mailto:caickruan2@gmail.com" target="_blank">
      <img src="https://img.shields.io/badge/GMAIL-caickruan2@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" />
    </a>
    &nbsp;&nbsp;
    <a href="https://tryhackme.com" target="_blank">
      <img src="https://img.shields.io/badge/TRYHACKME-RED_&_BLUE_DEFENSE-C0392B?style=for-the-badge&logo=tryhackme&logoColor=white" alt="TryHackMe" />
    </a>
    &nbsp;&nbsp;
    <a href="https://github.com/DevNaur/curriculum-vitae" target="_blank">
      <img src="https://img.shields.io/badge/CURRÍCULO_CV-ACESSO_DIRETO-10B981?style=for-the-badge&logo=googledocs&logoColor=white" alt="Currículo CV" />
    </a>
  </p>

  <!-- Dynamic Typing Subtitle -->
  <a href="https://github.com/DevNaur">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=3000&pause=1200&color=00F5D4&background=0D111700&center=true&vCenter=true&width=750&lines=%3E_Software+Engineer+%7C+Full+Stack+%26+Cybersecurity;%3E_Graduando+em+Engenharia+de+Software+%40+UNEB+(4%C2%BA+Semestre);%3E_Pesquisador+Zero-Trust+%26+Defesa+de+Microsservi%C3%A7os;%3E_Core%3A+React+%E2%80%A2+TypeScript+%E2%80%A2+Python+%E2%80%A2+Django+%E2%80%A2+Linux;%3E_Construindo+sistemas+resilientes%2C+escal%C3%A1veis+e+seguros." alt="Typing Terminal" />
  </a>

</div>

<br/>

---

### 🖥️ `devnaur@uneb-mainframe:~$ neofetch --profile`

```text
┌──(devnaur㉿uneb-security-node)-[~]
└─$ neofetch --release 2026.4
      /\_/\          USER ........: Caick Ruan (DevNaur)
     ( o.o )         ROLE ........: Software Engineer | Full Stack & Defensive Security
      > ^ <          EDUCATION ...: Bacharelado em Engenharia de Software @ UNEB (4º Semestre)
    /|     |\        LOCATION ....: Bahia, Brasil 🇧🇷
   (_|_ _|_|_)       CORE STACK ..: TypeScript, React, Python, Django, PostgreSQL, Linux
                     SECURITY ....: Zero-Trust Model, Defesa de Aplicações, DevSecOps
                     AFFILIATIONS : Pesquisa Acadêmica UNEB | Coletivos Saruëz & SGIE
                     TARGET ......: Estágio / Desenvolvedor Júnior (Full Stack / DevSecOps)
                     DIAGNOSTIC ..: System Nominal // Shift-Left Security Activated 🟢
```

---

<br/>

<!-- ==================== 01 // SOBRE MIM ==================== -->
<div align="center">
  <img src="./assets/section1_about.svg" width="100%" alt="01 // Sobre Mim — About Me" />
</div>

<br/>

---

<br/>

<!-- ==================== 02 // ARSENAL TECNOLÓGICO ==================== -->
<div align="center">
  <img src="./assets/section2_stack.svg" width="100%" alt="02 // Arsenal Tecnológico — Tech Stack" />
</div>

<br/>

---

<br/>

<!-- ==================== 03 // PROJETOS EM DESTAQUE ==================== -->
<div align="center">
  <img src="./assets/section3_projects.svg" width="100%" alt="03 // Projetos em Destaque — Featured Projects" />
</div>

<br/>

<!-- Action Bar for Projects -->
<div align="center">

| Projeto em Destaque | Links Rápidos de Código & Documentação |
| :--- | :--- |
| 🏛️ **SGA-Edu (UNEB Campus II)** | [🔗 Explorar Repositório & Arquitetura](https://github.com/PedroUneb2025/Sistema-Escolar) • [📑 Guia de Integração Frontend](https://github.com/PedroUneb2025/Sistema-Escolar/blob/main/INTEGRACAO-FRONTEND.md) |
| 💳 **Gateway / Pagamentos** | [🔗 Ver Módulo Corporativo Django](https://github.com/DevNaur) • *Consistência ACID & Idempotência* |
| 🛡️ **Pesquisa Zero-Trust** | [🔗 Ver Artigo & Modelagem Técnica](https://github.com/DevNaur) • *Contenção de Blast-Radius em Microsserviços* |
| 📱 **Mini-Servidor DIY Mobile** | [🔗 Ver Blueprint & Setup Termux](https://github.com/DevNaur) • *Laboratório Linux Headless Portátil* |

</div>

<br/>

<!-- ==================== INTERACTIVE ACCORDIONS / DOSSIERS ==================== -->
<details>
  <summary><b>📂 [CLIQUE PARA EXPANDIR] Dossiê Técnico: Arquitetura RBAC do SGA-Edu</b></summary>
  <br/>
  <ul>
    <li><b>Autenticação Segura:</b> <code>AuthContext</code> com persistência em storage, emissão de cabeçalho <code>Authorization: Bearer &lt;token&gt;</code> via interceptor Axios centralizado.</li>
    <li><b>Proteção de Rotas:</b> Componente <code>ProtectedRoute</code> validando múltiplos perfis permitidos (<code>admin</code>, <code>secretaria</code>, <code>coordenacao</code>, <code>professor</code>, <code>aluno</code>, <code>financeiro</code>).</li>
    <li><b>Resiliência:</b> Interceptor tratando respostas <code>401 Unauthorized</code> e <code>403 Forbidden</code> com expurgo de sessão e redirecionamento automático.</li>
    <li><b>Qualidade:</b> Validação estrita de contratos de dados em tempo de execução com <b>Zod</b> e suíte de testes com <b>Vitest</b>.</li>
  </ul>
</details>

<details>
  <summary><b>📂 [CLIQUE PARA EXPANDIR] Outros Repositórios & Experimentos Práticos</b></summary>
  <br/>
  <ul>
    <li>💊 <b>FarmaTech:</b> Sistema de controle de estoque e dispensação farmacêutica com modelagem relacional estrita e consultas otimizadas.</li>
    <li>🎟️ <b>Sistema de Gestão de Eventos (Java):</b> Aplicação desenvolvida com Programação Orientada a Objetos rigorosa, separação em camadas e padrões de projeto (POO/Patterns).</li>
    <li>💧 <b>Modelo de Árvore de Decisão para Potabilidade:</b> Pipeline analítico de Machine Learning para classificação de segurança de corpos hídricos.</li>
    <li>🎮 <b>Laboratórios de Lógica & Interatividade Web:</b> Projetos de algoritmos e interação pura em JavaScript ES6+ (Adivinhe o Número, MATEMÁGICA).</li>
  </ul>
</details>

<br/>

---

<br/>

<!-- ==================== 04 // CERTIFICAÇÕES & QUALIFICAÇÕES ==================== -->
<div align="center">
  <img src="./assets/section4_certs.svg" width="100%" alt="04 // Certificações &amp; Qualificações" />
</div>

<br/>

---

<br/>

<!-- ==================== 05 // ESTATÍSTICAS DO GITHUB ==================== -->
<div align="center">
  <img src="./assets/section5_metrics.svg" width="100%" alt="05 // Estatísticas do GitHub — Metrics &amp; Telemetry" />
</div>

<br/>

---

<br/>

<!-- ==================== 06 // METODOLOGIA & COMO TRABALHO ==================== -->
<div align="center">
  <img src="./assets/section6_workflow.svg" width="100%" alt="06 // Metodologia &amp; Como Trabalho" />
</div>

<br/>

---

<br/>

<!-- ==================== 07 & 08 // FOCO ATUAL & COMUNIDADE ==================== -->
<div align="center">
  <img src="./assets/section7_learning_community.svg" width="100%" alt="07 &amp; 08 // Foco Atual &amp; Engajamento Comunitário" />
</div>

<br/>

---

<br/>

<!-- ==================== FOOTER & CONNECT ==================== -->
<div align="center">

  <img src="./assets/footer.svg" width="100%" alt="Footer — Empresa + Talento = Impacto" />

  <br/><br/>

  <p align="center">
    <a href="https://www.linkedin.com/in/caick-santana-dev" target="_blank">
      <img src="https://img.shields.io/badge/CONECTAR_NO_LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Conectar no LinkedIn" />
    </a>
    &nbsp;&nbsp;&nbsp;&nbsp;
    <a href="mailto:caickruan2@gmail.com" target="_blank">
      <img src="https://img.shields.io/badge/ENVIAR_MENSAGEM_DIRETA-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Enviar E-mail" />
    </a>
  </p>

  <br/>

  <!-- Profile Visitor Counter (Cyber Scan) -->
  <img src="https://komarev.com/ghpvc/?username=DevNaur&color=00f5d4&style=flat-square&label=CYBER_ID_SCANS%20%3A%3A%20VISITORS" alt="Profile Telemetry Views" />

  <br/>

</div>
