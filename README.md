# 👨‍💻 Espaker Kaminski

Desenvolvedor **full-stack autodidata** com foco em **TypeScript, Node.js e Python**, especializado em construir sistemas complexos e reais — lendo documentação técnica, mergulhando em código-fonte e entregando software de qualidade de forma rápida e independente.

Minha curva de aprendizado é acelerada porque entendo sistemas no **nível do protocolo**, não apenas na superfície da API. Isso me permite dominar tecnologias novas com velocidade fora do comum e integrar com stacks que poucos desenvolvedores web se aventuram.

Já integrei nativamente com o protocolo **AMI do Asterisk**, a **API não-oficial do WhatsApp (Baileys)**, stacks de telefonia **SIP/PJSIP**, a **API da OpenAI**, a plataforma **Genesys Cloud**, o framework **KDE Plasma 6 com QML** e **APIs proprietárias de PABX via protocolo TCP** — tudo a partir da documentação oficial, sem curso, sem tutorial.

Sou **usuário avançado de Linux** desde o fim de 2013 — passei por diversas distribuições ao longo dos anos e hoje uso **Fedora com KDE Plasma** como ambiente principal: moderno, atualizado e com o ambiente de desktop que mais me agrada. Esse histórico longo com Linux vai muito além do uso casual — é parte do meu dia a dia de desenvolvimento, servidores, scripts e configuração de ambiente.

---

## 🛠️ Habilidades Técnicas

### Linguagens

**TypeScript** e **JavaScript** são minhas linguagens principais — uso TypeScript com tipagem estrita, generics, tipos condicionais e padrões avançados de orientação a objetos. Tenho experiência sólida também com **Python** para APIs REST, automações, scripts de integração e invocação de ferramentas de ML. Além disso, trabalho com **PHP**, **Shell Script**, **SQL** e **QML** em contextos específicos.

Não me prendo a uma única linguagem: uso a ferramenta certa para cada camada do problema — mesmo que isso signifique **escrever código Python como string dentro do TypeScript**, persistir em arquivo temporário em runtime e invocar via `child_process.spawn` quando o ecossistema Node.js não oferece o equivalente necessário.

---

### Backend

Construo APIs **REST** e **WebSocket** robustas com **Node.js + Express**, com autenticação via **JWT + Passport.js**, upload de arquivos, logging estruturado com Winston e documentação automática via **Swagger/OpenAPI** e **AsyncAPI**. Tenho experiência com **Flask** em Python para APIs de integração e serviços utilitários com suporte a SSL, multithreading via Cheroot WSGI e logging rotativo.

Trabalho com **ORM e query builders** — **Knex.js** (com sistema de migrations versionadas e seeds) e **Sequelize** — e tenho boa noção de modelagem relacional complexa com dezenas de tabelas e foreign keys interdependentes.

Para comunicação em tempo real, projeto arquiteturas **event-driven** com **Socket.IO**, **EventEmitter** nativo e padrões de `Proxy` reativo para propagar mudanças de estado de forma eficiente e completamente desacoplada — sem polling, sem redundância de dados.

Tenho experiência também com a **Telegram Bot API** — construção de bots conversacionais com fluxos baseados em reply-to-message, teclados dinâmicos (`ReplyKeyboardMarkup`, `force_reply`), roteamento por regex de comandos e persistência de dados estruturados em MySQL via Knex.js. Formatação de moeda nativa com `Intl.NumberFormat` sem dependências externas.

---

### Telefonia e Telecomunicações

Área onde pouquíssimos desenvolvedores têm domínio real. Integro nativamente com o **Asterisk** via protocolo **AMI (Asterisk Manager Interface)** em TypeScript — tratando em tempo real eventos de chamadas, filas, agentes e troncos e propagando atualizações ao vivo via Socket.IO.

Tenho experiência com configuração completa de **SIP/PJSIP**, criação de **Dialplans** nativos do Asterisk, **URA/IVR** dinâmica gerada programaticamente a partir de banco de dados, **CDR/CEL**, voicemail, conferências e integração ODBC para realtime database. Implementei um **softphone SIP no browser** com **JsSIP**, permitindo realizar e receber chamadas diretamente pela interface web. Já integrei também com **protocolos TCP proprietários** de sistemas PABX de terceiros, incluindo gerenciamento de estado de chamada, cache de último estado conhecido e reconexão automática em thread daemon.

---

### Inteligência Artificial e Processamento de Mídia

Integro com a **API da OpenAI** para construir agentes conversacionais com estado, contexto multi-turno, parsing estruturado de respostas JSON tipadas e roteamento inteligente entre IA e atendimento humano — com suporte a classificação de leads por temperatura (`hot/warm/cold`) e extração de informações estruturadas das respostas.

Tenho experiência com **transcrição de áudio via Whisper** usando `faster-whisper`, com detecção automática de CUDA: alterna entre `float16` na GPU ou `int8` na CPU sem intervenção manual, reportando progresso em tempo real via stdout. Quando o ecossistema Node.js não oferece uma biblioteca equivalente, **escrevo o script Python diretamente no TypeScript como string, persisto em arquivo temporário em runtime e invoco via `child_process.spawn`** — capturando a saída linha a linha. Essa abordagem demonstra não apenas o domínio das duas linguagens, mas a disposição de usar a ferramenta certa para cada camada do problema.

Trabalhei também com **Azure Cognitive Services** (Speech SDK — TTS/STT) e **Puppeteer** para automação de browser. Processo mídia com **FFmpeg** — extração de áudio de vídeo com fallback automático de stream copy para recodificação WAV quando necessário, integrado em pipelines de processamento completos.

---

### Frontend

Construo interfaces com **React 18**, gerenciamento de estado com **Redux**, **Zustand** e **React Query**, roteamento com **React Router** e build com **Vite**. Tenho experiência com **Ant Design**, **Material UI (v4 e v5)**, **Styled Components** e **Less** para estilização.

Já implementei componentes complexos como softphones SIP, dashboards de monitoramento em tempo real, editores de fluxo com **ReactFlow**, players de mídia com marcadores de timestamp sincronizados com transcrição, e relatórios interativos gerados dinamicamente como HTML standalone.

---

### Bancos de Dados

**MySQL/MariaDB** é meu banco principal — trabalho com schemas complexos, índices, queries otimizadas e integração via ODBC para realtime com o Asterisk. Tenho experiência também com **PostgreSQL**, **MongoDB** (incluindo persistência de sessões e auth state de WhatsApp), **Redis** (cache com TTL, pub/sub, persistência de estado entre reinicializações) e **SQLite** para contextos locais e offline-first.

---

### Linux

Usuário avançado de Linux desde o **fim de 2013** — mais de 10 anos de uso contínuo, passando por diversas distribuições ao longo dos anos. Hoje uso **Fedora com KDE Plasma** como ambiente principal: prefiro Fedora pela praticidade, pelo ciclo de atualizações moderno e pelo compromisso com tecnologias recentes; e o KDE por ser o ambiente de desktop mais completo e personalizável disponível no Linux.

Esse histórico vai muito além do uso casual: envolve configuração de servidores, provisionamento de ambientes, shell scripting, gerenciamento de pacotes, permissões, firewall, systemd, montagem de partições, integração ODBC, configuração de drivers e desenvolvimento do dia a dia.

---

### Desktop

Desenvolvo aplicações **multiplataforma** com **Electron + Vite + React + TypeScript**, distribuídas como instalador **NSIS para Windows** e **AppImage para Linux** via `electron-builder`. Tenho atenção a detalhes de integração com o sistema operacional — como definir `WM_CLASS` no X11 e `app_id` no Wayland para que o KDE Plasma reconheça o ícone corretamente no taskbar.

Desenvolvo também widgets nativos para **KDE Plasma 6** com **QML**.

---

### DevOps e Infraestrutura

Faço deploy e provisionamento em **VPS Linux** (Rocky Linux, RHEL, AlmaLinux) com configuração completa de **Nginx** como proxy reverso, suporte a WebSocket e SSL. Trabalho com **Docker** e **Docker Compose** para orquestração de ambientes de desenvolvimento e produção. Faço deploy de frontends com **Vercel**.

Escrevo **Shell Scripts** de automação complexos — incluindo instaladores que provisionam ambientes inteiros do zero (PABX, banco de dados, cache, firewall, certificados SSL) sem nenhuma intervenção manual, scripts de build, versionamento automático e deploy em VPS.

Empacoto aplicações Node.js como **binários standalone Linux** com `pkg` e `nexe`, eliminando a dependência de Node.js instalado no servidor.

---

### Distribuição de Software

Gerencio o ciclo completo de **distribuição de software** com **GitHub Releases**: versionamento semântico automatizado, build do binário, empacotamento do instalador e publicação de assets diretamente na release — mantendo histórico de versões rastreável e download sempre apontando para a versão mais recente. Não apenas entrego software funcionando — entrego software **distribuível e instalável por usuários finais**, do zero ao `.run`.

---

### Tooling e Boas Práticas

Uso **pnpm** como gerenciador de pacotes principal, **ESLint + Prettier** para qualidade de código e **TypeScript strict** em todos os projetos. Documento APIs com **Swagger/OpenAPI** para REST e **AsyncAPI** para contratos de WebSocket. Versiono aplicações com geração automática de `version.ts` via `genversion`. Tenho familiaridade com monorepos e workspace configs (`pnpm-workspace.yaml`).

---

## 🧠 Como aprendo

Não espero que exista um curso sobre o que preciso. Leio a documentação oficial, analiso o código-fonte das bibliotecas e entrego. Essa abordagem me permite absorver tecnologias novas com velocidade e profundidade que cursos raramente proporcionam — porque entendo o *porquê*, não apenas o *como*.

---

## 📊 Stack Rápida

| Camada | Tecnologias |
|---|---|
| **Linguagens** | TypeScript · JavaScript · Python · PHP · Shell Script · SQL · QML |
| **Backend** | Node.js · Express · Flask · Socket.IO · JWT · Passport.js · Knex.js · Sequelize |
| **Frontend** | React 18 · Vite · Ant Design · MUI · Redux · Zustand · React Query · ReactFlow |
| **Bancos de Dados** | MySQL/MariaDB · PostgreSQL · MongoDB · Redis · SQLite |
| **Telecom** | Asterisk · SIP/PJSIP · AMI · AGI · JsSIP · DTMF · CDR/CEL · ODBC |
| **IA & Integrações** | OpenAI API · Whisper · Azure Cognitive Services · Baileys · Genesys Cloud · FFmpeg · Telegram Bot API |
| **DevOps** | Docker · Nginx · Linux (RHEL/Rocky/Fedora) · Shell Script · Vercel · GitHub Releases |
| **Desktop** | Electron · KDE Plasma 6 · QML |
| **Tooling** | pnpm · ESLint · Prettier · Swagger/OpenAPI · AsyncAPI · pkg · nexe · electron-builder |