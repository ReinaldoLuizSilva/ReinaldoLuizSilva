<!--
  Banner opcional: gere a imagem uma vez, salve como assets/banner.png
  neste repositório e descomente a linha abaixo. Assim ela nunca quebra.
-->
<!-- <div align="center"><img src="./assets/banner.png" alt="Reinaldo Luiz da Silva — Cloud & DevOps" width="100%" /></div> -->

<h1 align="center">Reinaldo Luiz da Silva</h1>
<p align="center"><strong>Cloud &amp; DevOps</strong> · Infraestrutura · Oracle &amp; OCI</p>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/reinaldoluizdasilva)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ReinaldoLuizSilva)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:reinaldodasilva@gmail.com)

</div>

---

## ⚡ Sobre mim

```bash
$ whoami
infraestrutura em produção + automação = cloud engineer em construção
```

Trabalho com **infraestrutura e bancos de dados Oracle em produção** há 2 anos, atendendo múltiplos clientes em **Oracle Cloud (OCI)** e on-premises — sustentação, automação de rotinas, monitoramento, redes e resolução de incidentes.

Estou direcionando essa base para **Cloud e DevOps**: certificação **Google Cloud Associate Cloud Engineer**, preparação para a **AZ-104**, e prática real com **Terraform**, **Docker** e **CI/CD** nos meus projetos.

- ☁️ **Google Cloud — Associate Cloud Engineer** · 2026 <!-- ajustar se o resultado ainda não saiu -->
- 📘 **AZ-104 (Azure Administrator)** · em preparação, exame previsto para out/2026
- 🏢 **BEG Support** — Analista de Sistemas / Oracle APEX Developer
- 🎓 **Tecnólogo em Análise e Desenvolvimento de Sistemas** — IENH (conclusão jul/2026)
- 🌍 Novo Hamburgo, RS — Brasil
- 🎯 Aberto a oportunidades como **Cloud Engineer**, **DevOps**, **SRE** e **Analista de Infraestrutura Cloud**

---

## 🚀 Projetos em destaque

### 🎫 [TicketOps](https://github.com/ReinaldoLuizSilva/TicketOps)

API REST de gestão de chamados em **arquitetura multi-cloud**, construída para demonstrar práticas de Cloud e DevOps de ponta a ponta — com custo de infraestrutura **R$ 0**.

```
GitHub Actions ──(Workload Identity Federation)──> GCP
                                                    ├── Cloud Run (API FastAPI, container)
                                                    ├── Artifact Registry
                                                    ├── Secret Manager
                                                    └── Cloud Monitoring
                                        Cloud Run ──(mTLS)──> Oracle Autonomous DB (OCI)
```

- **IaC** — Terraform provisionando toda a infraestrutura, com state remoto em bucket GCS
- **CI/CD** — pipeline com lint, testes, build da imagem e deploy automatizado a cada merge
- **Segurança** — autenticação por Workload Identity Federation, sem credenciais no repositório; segredos no Secret Manager
- **Observabilidade** — logs estruturados e alertas de erro no Cloud Monitoring

`Python` · `FastAPI` · `Docker` · `Terraform` · `GitHub Actions` · `GCP` · `Oracle Cloud`

---

## 🎯 Stack &amp; Tecnologias

**☁️ Cloud**

![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Oracle Cloud](https://img.shields.io/badge/Oracle%20Cloud-F80000?style=flat-square&logo=oracle&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

**🔧 DevOps &amp; Infraestrutura**

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Zabbix](https://img.shields.io/badge/Zabbix-D40000?style=flat-square&logo=zabbix&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**💾 Bancos de Dados**

![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![PL/SQL](https://img.shields.io/badge/PL%2FSQL-F80000?style=flat-square&logo=oracle&logoColor=white)
![Oracle APEX](https://img.shields.io/badge/Oracle%20APEX-F80000?style=flat-square&logo=oracle&logoColor=white)
![SQLcl](https://img.shields.io/badge/SQLcl-F80000?style=flat-square&logo=oracle&logoColor=white)

**💻 Linguagens**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Shell Script](https://img.shields.io/badge/Shell%20Script-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

---

## 💼 Experiência

```
💼 BEG Support Informática Aplicada                    2 anos
   │
   ├── 🔷 Analista de Sistemas / Oracle APEX Developer   jun/2025 → presente
   │      Sustentação de ambientes Oracle (produção, homologação e dev)
   │      para múltiplos clientes em OCI e on-premises · automação de
   │      rotinas · upgrades de plataforma · backup/restore (RMAN, Data
   │      Pump) · APIs REST com ORDS · troubleshooting em produção
   │
   └── ☁️  Estagiário de Infraestrutura Cloud            jun/2024 → jun/2025
          Monitoramento com Zabbix · servidores Linux · containers
          Docker · suporte a recursos em Oracle Cloud Infrastructure
```

---

## 📚 Formação &amp; Certificações

```
🏫 IENH — Instituição Evangélica de Novo Hamburgo
   📚 Tecnólogo em Análise e Desenvolvimento de Sistemas
   📅 fev/2023 → jul/2026

📜 Certificações
   ✅ Google Cloud — Associate Cloud Engineer (ACE)       2026
   🔄 Microsoft Azure Administrator Associate (AZ-104)    out/2026
   🔄 GitHub Actions (GH-200)                             2026
```

---

## 📈 GitHub Stats

<!--
  Cards gerados pelo workflow .github/workflows/profile-cards.yml e commitados
  em profile-summary-card-output/ neste mesmo repositório. São SVGs estáticos,
  não dependem de serviço externo em runtime — logo, não sofrem rate limit.
-->
<div align="center">

<img src="https://raw.githubusercontent.com/ReinaldoLuizSilva/ReinaldoLuizSilva/main/profile-summary-card-output/tokyonight/0-profile-details.svg" alt="Detalhes do perfil" />

<img src="https://raw.githubusercontent.com/ReinaldoLuizSilva/ReinaldoLuizSilva/main/profile-summary-card-output/tokyonight/3-stats.svg" alt="Estatísticas do GitHub" />

</div>
