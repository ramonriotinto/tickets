# 🎟️ Sistema de Gestão de Tickets (Chamados)

Sistema para controle de atendimento em filas com priorização de chamados.

## ✨ Funcionalidades Principais

### 👥 Agentes do Sistema
| Sigla | Função |
|-------|--------|
| **AS** | Agente Sistema - Emite senhas e responde a comandos |
| **AA** | Agente Atendente - Chama próximos da fila e realiza atendimento |
| **AC** | Agente Cliente - Usa totem para emissão de senha |

### � Tipos de Senhas
| Tipo | Descrição | Tempo Médio (TM) |
|------|-----------|------------------|
| **SP** (Prioritária) | Atendimento prioritário | 15 min (±5 min) |
| **SG** (Geral) | Atendimento padrão | 5 min (±3 min) |
| **SE** (Exames) | Atendimento rápido | 1 min (95%) ou 5 min (5%) |


Fluxo de Atendimento
O sistema segue um padrão alternado de atendimento.
Garantindo que senhas prioritárias sejam atendidas primeiro, seguidas por senhas de exames ou gerais.


🖥️ Painel de Chamados
Exibe as 5 últimas senhas chamadas

Indica guichê disponível

Atualização em tempo real


🛠️ Tecnologias Utilizadas
Frontend:
Angular


# Clone o repositório
git clone https://github.com/ramonriotinto/tickets.git

# Instale as dependências executando o comando no terminal
npm install

# Inicie o servidor de desenvolvimento executando o comando no terminal
ionic serve