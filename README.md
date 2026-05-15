# 🌊 Nexus - Aplicação Mobile

![Status do Projeto](https://img.shields.io/badge/Status-Em%20Desenvolvimento-blue)
![Plataforma](https://img.shields.io/badge/Plataforma-React%20Native-61dafb?logo=react)

O **Nexus** é uma solução tecnológica mobile voltada à prevenção, proteção social e fortalecimento da segurança urbana. O aplicativo utiliza recursos de geolocalização, comunicação em tempo real e participação comunitária para auxiliar moradores de áreas de risco durante situações de emergência (como enchentes, alagamentos e deslizamentos de terra).

Desenvolvido inicialmente para a cidade de **Recife**, o projeto possui um modelo de negócios **B2G (Business-to-Government)**, estruturado para ser adotado por prefeituras e órgãos públicos de defesa civil.

---

## 🚀 Funcionalidades Principais

### 🚨 Sistema de Alertas
* **Avisos em Tempo Real:** Emissão de alertas baseados em dados meteorológicos.
* **Notificações Push:** Avisos imediatos sobre riscos iminentes de enchentes e deslizamentos diretamente na tela do usuário.

### 📍 Geolocalização e Entidades de Apoio
* **Identificação Automática:** O app localiza o usuário e mapeia os pontos de apoio mais próximos.
* **Rede de Suporte:** Exibição detalhada de ONGs, escolas, abrigos municipais e pontos de acolhimento cadastrados.
* **Autocadastro:** Fluxo para que instituições de apoio possam se registrar na plataforma.

### 👥 Relatos Comunitários (Crowdsourcing)
* Os próprios usuários podem alimentar o mapa reportando:
  * Ruas e avenidas alagadas.
  * Riscos visíveis de queda de barreiras.
  * Áreas e vias inacessíveis.
  * Nível de lotação dos abrigos.

### 📴 Funcionamento Offline
* Pensado para momentos críticos onde a rede de dados pode falhar, o app permite:
  * Visualização de contatos de emergência locais.
  * Consulta de entidades próximas previamente salvas no cache do dispositivo.

---

## 🛠️ Tecnologias e Arquitetura

O ecossistema do projeto Nexus é composto pelas seguintes tecnologias:

* **Front-end (Mobile):** React Native
* **Back-end & Banco de Dados:** MySQL / PostgreSQL
* **Análise de Dados:** Power BI
* **Infraestrutura & APIs:**
  * Firebase Cloud Messaging (Notificações Push)
  * API de Geolocalização (Mapas e Posicionamento)
  * APIs de Monitoramento Meteorológico

---

## 🎨 Identidade Visual (Paleta de Cores)

A paleta de cores foi selecionada para transmitir seriedade, segurança e fácil leitura em situações de urgência:

* 🟦 **Azul Escuro (`#0B2D72`):** Elementos estruturais e identidade institucional.
* 🔷 **Azul Intermediário (`#0992C2`):** Botões e destaques principais.
* 🔹 **Azul Claro (`#0AC4E0`):** Elementos secundários e indicadores de fluidez.
* 🟨 **Areia Claro (`#F6E7BC`):** Fundo ou áreas de contraste para descanso visual.

---

## 👥 Equipe do Projeto

* Caio Henrique
* Allan Daniel
* Paulo Ferreira
* Arthur Vinicius
* Henrique Maciel
* Lucas Gabriel
* João Roberto
* Vinicius Santiago
* Alisson Marinho

---

## 💻 Como Executar o Projeto Localmente (Desenvolvimento)

### Pré-requisitos
Antes de começar, você vai precisar ter instalado em sua máquina:
* [Node.js](https://nodejs.org/)
* [Git](https://git-scm.com/)
* Ambiente configurado para React Native (Android Studio / Xcode)

### Passo a Passo

```bash
# 1. Clone este repositório
$ git clone [https://github.com/seu-usuario/nexus-app.git](https://github.com/seu-usuario/nexus-app.git)

# 2. Acesse a pasta do projeto
$ cd nexus-app

# 3. Instale as dependências
$ npm install # ou yarn install

# 4. Inicie o servidor do Metro (React Native)
$ npx react-native start

# 5. Rode a aplicação no emulador ou dispositivo conectado
# Para Android:
$ npx react-native run-android

# Para iOS:
$ npx react-native run-ios
