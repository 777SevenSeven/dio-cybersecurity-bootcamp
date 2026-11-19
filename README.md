# 🛡️ Laboratórios Práticos — Bootcamp Riachuelo × DIO (Cibersegurança)

Repositório consolidado dos projetos práticos desenvolvidos durante o **Bootcamp Riachuelo - Cibersegurança (2ª edição)**, oferecido pela [Digital Innovation One (DIO)](https://www.dio.me) em parceria com a [Riachuelo](https://www.riachuelo.com.br) e o [Santander Open Academy](https://app.santanderopenacademy.com).

> 📚 **Contexto do curso:** programa gratuito de ~40 horas, lançado em março de 2026, com trilha completa de segurança da informação — de fundamentos de IA e Linux até testes de invasão e defesa. Ao final, certificado digital e acesso à Talent Match da DIO.

## 🧭 Estrutura da Trilha

| # | Módulo | Foco |
|---|--------|------|
| 1 | Princípios e Aprendizagem com IA | Engenharia de prompts, NotebookLM aplicado ao estudo |
| 2 | Linux e Máquinas Virtuais | Administração segura de sistemas, acesso remoto |
| 3 | Fundamentos de Cibersegurança | Redes, proteção de dados, automação com Python |
| 4 | Hacking Ético: Vulnerabilidades e Testes de Invasão | Kali Linux, enumeração, força bruta, exploração |
| 5 | Análise e Proteção de Ataques Cibernéticos | Detecção, mitigação e cultura de segurança |

## 🔬 Projetos do Portfólio

### 1. [Simulação de Malware — Vetor de Engenharia Social](malware-simulation-python/)

**Módulo:** Hacking Ético / Ataques e Defesas

Um **Trojan (cavalo de Troia)** completo em ambiente 100% controlado: uma extensão de navegador funcional para o Facebook Marketplace atua como fachada (isca), enquanto um instalador Python executa keylogger e exfiltração de dados via Telegram (C2).

- 💻 Python 3 (threads, `pynput`, Telegram API)
- 🌐 Extensão Chrome Manifest V3 (JavaScript)
- 🧠 Inclui **kill-switch ético** que impede execução totalmente oculta
- 📄 [README detalhado do projeto →](malware-simulation-python/README.md)
- 🔗 [Repositório original →](https://github.com/777SevenSeven/dio-malware-simulation-python)

### 2. [Exploração de Credenciais SMB — O Fator Humano](smb-credential-exploit/)

**Módulo:** Testes de Invasão / Força Bruta

Laboratório de pentest em ambiente isolado (Kali Linux × Metasploitable 2): reconhecimento com Nmap, wordlists próprias, ataque de força bruta SMB com **Medusa** e validação manual via `smbclient`.

- 🎯 Enumeração de serviços + brute force SMB (`smbnt`)
- 🧪 Metodologia completa documentada: recon → wordlists → ataque → validação
- 🧠 Análise de falsos-positivos e mitigação (MFA, account lockout)
- 📄 [README detalhado do projeto →](smb-credential-exploit/README.md)
- 🔗 [Repositório original →](https://github.com/777SevenSeven/dio-smb-credential-exploit)

## 🧠 O que esses labs demonstram

- **Ciclo de invasão completo**: reconhecimento, exploração e pós-exploração em ambientes autorizados
- **Engenharia social como vetor real**: o malware só funciona porque explora confiança humana — não apenas falhas técnicas
- **Defesa em profundidade**: assinaturas, heurística e — principalmente — conscientização do usuário
- **Documentação técnica**: cada projeto registra metodologia, comandos e evidências, não só o resultado

---

⚠️ **Aviso legal:** todos os laboratórios foram executados exclusivamente em ambientes controlados e autorizados, com finalidade estritamente educacional e defensiva. O uso destas técnicas fora desse contexto é ilegal e antiético.

<div align="center">
  <sub>André Antonio da Silva Queiroz · UTFPR · <a href="https://github.com/777SevenSeven">github.com/777SevenSeven</a></sub>
</div>
