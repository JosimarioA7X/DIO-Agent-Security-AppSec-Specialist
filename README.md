# 🛡️ DIO Agent — Security & AppSec Specialist

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.10+-yellow.svg)](https://www.python.org/)
[![Hermes AI Agent](https://img.shields.io/badge/Agent-Hermes_Framework-purple.svg)](#)

Especialização defensiva do **DIO Agent** para atuação como **AppSec & Security Advisor**. Esta evolução transforma o agente em um mentor de cibersegurança que analisa vulnerabilidades de código e infraestrutura com base na matriz de risco, boas práticas do OWASP Top 10 e mapeamento de táticas do MITRE ATT&CK®.

---

## 💡 Por que esta Especialização?

Em vez de fornecer soluções genéricas ou comandos diretos sem avaliar os riscos, esta habilidade garante que o agente:
1. **Exija contexto antes da ação:** Pergunta sobre o ambiente (laboratório, produção, regras de firewall) antes de sugerir configurações de infraestrutura.
2. **Priorize a Postura Defensiva:** Foca em remediação de código, sanitização de dados e arquitetura segura, sem fornecer scripts funcionais de exploração.
3. **Padronize Análises de Risco:** Avalia a tripla **Impacto × Probabilidade × Severidade** para priorizar a correção de falhas de forma pragmática.

---

## 🗂️ Arquivos do Projeto

A personalização do agente foi realizada exclusivamente via arquivos de conhecimento, roteiro de habilidades e instruções de persona (sem necessidade de re-treinamento de modelo):

```text
dio-agent/
├── AGENTS.md                          # Tabela de habilidades ativas do agente
├── agent/
│   ├── persona.md                     # Perfil comportamental defensivo do AppSec Advisor
│   └── knowledge/
│       └── security-basics.md        # Conceitos fundamentais: Tríade CIA, CVSS, OWASP e MITRE
└── skills/
    └── vulnerability-analysis/
        ├── SKILL.md                   # Roteiro de análise defensiva e regras de contexto
        └── README.md                  # Documentação técnica da skill
## 🚀 Como Executar

### Pré-requisitos
- Python 3.10+ instalado.
- Framework **Hermes** instalado e configurado.

### Passo a Passo
1. Clone o repositório para sua máquina local:
   ```bash
   git clone [https://github.com/JosimarioA7X/DIO-Agent-Security-AppSec-Specialist.git](https://github.com/JosimarioA7X/DIO-Agent-Security-AppSec-Specialist.git)
   cd DIO-Agent-Security-AppSec-Specialist
hermes
import sqlite3

def login(username, password):
    conn = sqlite3.connect('database.db')
    cursor = conn.cursor()
    # Vulnerabilidade: Concatenação de SQL sem sanitização
    query = f"SELECT * FROM users WHERE username = '{username}' AND password = '{password}'"
    cursor.execute(query)
    return cursor.fetchone()
import sqlite3

Desenvolvido por Josimário Barros da Silva durante os estudos de Análise e Desenvolvimento de Sistemas e especialização em Engenharia de Prompt / AppSec.

GitHub: https://github.com/JosimarioA7X
