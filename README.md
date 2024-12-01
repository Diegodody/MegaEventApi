# 🎉 API para Organização de Eventos

## 📖 Descrição do Projeto
A **API para Organização de Eventos** foi desenvolvida para facilitar o gerenciamento de eventos. Com ela, os usuários podem:
- Inscrever-se em eventos.
- Visualizar detalhes completos dos eventos.
- Receber notificações sobre atividades relacionadas.

A API e sua interface web são **conteinerizadas**, garantindo uma implantação simplificada e fácil manutenção.

---

## 🚀 Funcionalidades Principais
### 1. **Gerenciamento de Eventos (CRUD)**
- Criar, editar, excluir e listar eventos.
- Informações dos eventos incluem:
  - Nome
  - Local
  - Data
  - Tipo de evento
  - Número de vagas disponíveis

### 2. **Gerenciamento de Inscrições (CRUD)**
- Inscrição de usuários em eventos.
- Regras implementadas para:
  - Controle do número máximo de inscritos.
  - Evitar inscrições duplicadas no mesmo evento.

### 3. **Gerenciamento de Usuários (CRUD)**
- Cadastro e gerenciamento de usuários.
- Funcionalidades adicionais:
  - Listagem de eventos nos quais o usuário está inscrito.
  - Histórico completo de participações.

### 4. **Busca e Listagem de Eventos**
- Permite buscas por:
  - Data
  - Tipo de evento
  - Localidade

---

## ⚙️ Pré-requisitos
Certifique-se de que os seguintes requisitos estão atendidos antes de começar:
- **Docker**: Necessário para conteinerização da API e da interface web.
- **Node.js**: Versão mínima recomendada: **16.x**.
- **Git**: Para clonar e gerenciar o repositório.
- **Banco de Dados**: MySQL ou outro compatível com a API.

---

## 📥 Como Baixar e Configurar o Repositório
Siga os passos abaixo para clonar e configurar o projeto:

```bash
# Clone o repositório
git clone 

# Acesse o diretório do projeto
cd MegaEventAPI

# Construa e inicie os containers com Docker
docker-compose up --build
