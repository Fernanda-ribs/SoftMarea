# 🚗 SoftMarea - Sistema de Diagnóstico Automotivo

[📄 Acesse o documento no Google Docs](https://docs.google.com/document/d/1D_XnJqxyD7o8ch2mUMC-VJC3jwAez9PI/edit)

[📄 Acesse o Slide de apresentação](https://www.canva.com/design/DAGzbISPps4/JZF6IElBtqpaezclyITHhw/edit?utm_content=DAGzbISPps4&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

Um sistema web inteligente para diagnóstico automotivo que ajuda você a identificar problemas em veículos das principais marcas do mercado brasileiro de forma simples e guiada.

![SoftMarea Interface](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)
![Node.js](https://img.shields.io/badge/Node.js-20.x-green)
![MySQL](https://img.shields.io/badge/MySQL-8.0-blue)

## 🌟 Sobre o SoftMarea

O SoftMarea é uma plataforma web revolucionária no diagnóstico automotivo. Diferente dos métodos tradicionais que exigem conhecimento técnico, nossa solução oferece uma interface visual intuitiva onde qualquer pessoa pode identificar problemas em seu veículo seguindo um processo guiado e simplificado.

### 🎯 O Conceito Inovador

A principal inovação do SoftMarea é sua **interface panorâmica**, onde cada marca automotiva é apresentada em painéis visuais com vídeos de fundo. O usuário simplesmente clica na marca do seu veículo e é direcionado para um formulário específico onde pode selecionar modelo, ano e iniciar o diagnóstico guiado.

### 🚘 Marcas e Modelos Suportados

**Ford**: Ka, Fiesta, Focus, Fusion, EcoSport, Ranger, Territory, Maverick

**Chevrolet**: Onix, Onix Plus, Prisma, Cruze, Tracker, S10, Montana, Spin

**Toyota**: Etios, Yaris, Corolla, Corolla Cross, Hilux, SW4, RAV4

**Honda**: Fit, City, Civic, HR-V, WR-V, CR-V

**Volkswagen**: Gol, Polo, Virtus, T-Cross, Nivus, Saveiro, Jetta

**Fiat**: Mobi, Argo, Cronos, Pulse, Fastback, Toro, Strada


## 🛠️ Tecnologias Utilizadas

### 🔧 Backend (Servidor)

**🟢 Node.js**  
Plataforma JavaScript para servidor - rápida, escalável e eficiente para aplicações web modernas.

**⚡ Express.js**  
Framework web minimalista que facilita criação de APIs e gerenciamento de rotas.

**🗄️ MySQL**  
Banco de dados relacional robusto para armazenar dados de usuários e diagnósticos.

**🔐 Passport.js**  
Sistema de autenticação flexível com suporte a múltiplas estratégias de login.

**🔒 bcrypt**  
Biblioteca de criptografia para hash seguro de senhas com proteção salt.

**🎫 JWT (JSON Web Tokens)**  
Tokens seguros para autenticação stateless e gerenciamento de sessões.

**📧 Nodemailer**  
Envio de emails para verificação de conta e recuperação de senha.

### 🎨 Frontend (Interface)

**📄 HTML5**  
Linguagem de marcação semântica, acessível e otimizada para SEO.

**🎨 CSS3**  
Estilos modernos com Grid, Flexbox, animações e design responsivo.

**💻 JavaScript ES6+**  
Linguagem de programação moderna para interatividade e comunicação com API.

**🔥 Firebase**  
Plataforma Google para autenticação social (Google, Facebook) e SMS.

### 🔒 Segurança

**🛡️ CORS**  
Política de segurança para controlar acesso entre domínios diferentes.

**🍪 Express Session**  
Gerenciamento seguro de sessões e cookies de usuário.

**🔐 SSL/HTTPS**  
Conexões criptografadas para proteção de dados em trânsito.

### 🎬 Recursos Visuais

**📹 HTML5 Video**  
Vídeos de fundo nativos com autoplay, loop e carregamento otimizado.

**⚡ Lazy Loading**  
Carregamento inteligente de conteúdo para melhor performance.

**📱 Responsive Design**  
Interface adaptável para desktop, tablet e mobile.

## 🏗️ Arquitetura do Sistema

### 📊 Fluxo de Dados
1. **Frontend** 🎨 → Interface do usuário
2. **API REST** 🔄 → Comunicação entre frontend e backend  
3. **Backend** ⚙️ → Processamento de lógica e autenticação
4. **Banco de Dados** 💾 → Armazenamento persistente

### 🔄 Como as Tecnologias Se Conectam

**🌐 Cliente (Navegador)**  
HTML5 + CSS3 + JavaScript → Interface visual e interativa

**⬇️**

**🔗 API REST**  
Comunicação via HTTPS com tokens JWT

**⬇️**

**🖥️ Servidor Node.js + Express**  
Processamento, autenticação e lógica de negócio

**⬇️**

**🗃️ Banco MySQL**  
Dados de usuários, diagnósticos e configurações

---

<div align="center">
  <p><strong>🚗 SoftMarea</strong> - Tecnologia a serviço do diagnóstico automotivo</p>
  <p>💡 Inovação • 🔒 Segurança • ⚡ Performance</p>
</div>
