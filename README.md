
# André Silva | Senior Software Developer & Architect

Desenvolvedor de Software especializado em sistemas distribuídos, arquiteturas de alta disponibilidade e resiliência. Projetei e sustentei o core de plataformas processando milhões de requisições por minuto para uma base de mais de 30 milhões de usuários ativos. 

Minha atuação foca na intersecção entre engenharia rigorosa, Arquitetura de negocios e Cibersegurança, garantindo que a escalabilidade agressiva do negócio não comprometa a estabilidade, a performance de I/O ou a proteção dos dados.


<div align="center">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <br>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <br>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/Cybersecurity-000000?style=for-the-badge&logo=strapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Cursor_AI-555555?style=for-the-badge&logo=openai&logoColor=white" />
</div>

## Filosofia de Engenharia & Arquitetura

Minhas decisões de arquitetura baseiam-se na análise rigorosa de trade-offs, priorizando manutenibilidade e confiabilidade em sistemas de missão crítica:

* **Sistemas Distribuídos & Mensageria:** Desacoplamento de fluxos monolíticos utilizando Event-Driven Architecture (EDA). Gerenciamento de processamento assíncrono massivo e tolerância a falhas via RabbitMQ e Redis.
* **Segurança Integrada (Security by Design):** Especialista em Cibersegurança pela PUC Minas. Implementação nativa de criptografia, mitigação de vetores de ataque (OWASP) e governança rigorosa de dados (LGPD) na camada base da aplicação.
* **Qualidade e Confiabilidade:** Liderança técnica na adoção de testes automatizados avançados. Histórico de entrega de 100% de code coverage (TDD) em gateways de pagamento e fluxos transacionais que exigem idempotência absoluta.
* **Performance e Escalabilidade:** Tuning avançado em bancos relacionais (PostgreSQL, MySQL), estratégias de lock distribuído para evitar race conditions e caching em múltiplas camadas para suportar SLAs rigorosos sob alto estresse de tráfego.

## Stack Core & Infraestrutura

* **Backend & Arquitetura:** PHP (Laravel, Service Layer/Repositories), Node.js, TypeScript, C# (ASP.NET MVC).
* **Arquitetura de Dados:** PostgreSQL, MySQL, Redis (Caching/PubSub), SQL Server.
* **Infraestrutura & Cloud:** AWS (EC2, S3, RDS, CloudWatch), Azure, Traefik, Docker. Automação de pipelines CI/CD para zero-downtime deployments.
* **Frontend:** Vue.js, React, React Native, Vanilla JS (Performance-first).
* **Automação & Scraping:** Extração e ingestão de dados em larga escala utilizando Selenium, Laravel Dusk e integrações de API complexas (GraphQL/REST).

## Projetos e Arquiteturas em Destaque

### 1. Smart Resume (Arquitetura Serverless & Edge Computing)
[🔗 andreodevv.github.io/portfolio/](https://andreodevv.github.io/portfolio/)
Portfólio interativo projetado sob a filosofia Zero-Dependency (Vanilla JS/CSS) para atingir a pontuação máxima (100/100) no Core Web Vitals. A infraestrutura de frontend é distribuída globalmente via Edge CDN (Vercel/GitHub Pages) para latência mínima. No backend, projetei um pipeline de telemetria assíncrona customizada que ingere métricas de tráfego em tempo real para um banco de dados PostgreSQL gerenciado (Supabase), operando de forma Serverless.

### 2. Bar.Ganha (Plataforma de E-commerce & Economia Circular)
Plataforma de comércio estruturada em C# e ASP.NET MVC. A arquitetura monolítica foi desenhada com uma separação rigorosa de camadas (BLL - Business Logic Layer e DAL - Data Access Layer), garantindo alta integridade transacional via SQL Server e pronta para escalabilidade vertical/horizontal no ecossistema Azure. O rigor técnico do projeto resultou em nota máxima e convite formal para incubação pela PUC Minas.

### 3. CalorieCounter (Motor Biofísico & Clean Architecture)
Plataforma Full Stack (Laravel/Vue.js) construída para processar cálculos de variáveis biofísicas e ajustes preditivos de macronutrientes. A base de código aplica princípios estritos de Clean Architecture, isolando regras complexas de domínio através de Service e Repository Patterns. Essa decisão arquitetural garantiu alto índice de testabilidade e desacoplamento total da camada de persistência (PostgreSQL).

### 4. FinImprover (Pipeline ETL & BI Financeiro)
Sistema de inteligência financeira e motor preditivo de orçamento. O core da aplicação conta com um pipeline de ingestão de dados (ETL) desenvolvido para automatizar a importação, sanitização e categorização de bases financeiras estruturadas (planilhas legadas). A interface de análise foi otimizada para I/O de baixa latência utilizando Laravel Livewire com MySQL, permitindo a projeção de cenários de fluxo de caixa em dashboards analíticos em tempo real.

## Contato e Discussões Técnicas

Disponível para discutir desafios arquiteturais de alta complexidade, modernização de sistemas legados ou mentoria técnica em ambientes de alto desempenho.

* **LinkedIn:** [linkedin.com/in/andreodev](https://linkedin.com/in/andreodev)
* **Currículo Dinâmico:** [Acesse a Vitrine Técnica](https://andreodevv.github.io/portfolio/)
* **Email Oficial:** [andreodevv@gmail.com](mailto:andreodevv@gmail.com)
