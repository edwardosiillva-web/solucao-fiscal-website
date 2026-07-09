# Solução Fiscal - Website

Website profissional para Solução Fiscal, consultoria especializada em regularização fiscal, emissão de notas fiscais e parcelamento de débitos.

## 🎨 Características

- ✅ **Design Responsivo** - Funciona perfeitamente em desktop, tablet e mobile
- ✅ **Paleta Verde e Branca** - Design profissional e moderno
- ✅ **Seções Completas**:
  - Página inicial com banner de apresentação
  - Apresentação da empresa
  - 6 serviços detalhados
  - Passo a passo de atendimento
  - Benefícios
  - FAQ interativo
  - Formulário de contato
  - Botão flutuante WhatsApp
  - Footer com informações

- ✅ **Animações Suaves** - Transições e efeitos visuais
- ✅ **Menu Mobile** - Navegação responsiva
- ✅ **Scroll Suave** - Navegação entre seções

## 📂 Estrutura do Projeto

```
solucao-fiscal-website/
├── index.html          # Arquivo HTML principal
├── styles.css          # Estilos CSS
├── script.js           # Funcionalidades JavaScript
└── README.md           # Este arquivo
```

## 🚀 Como Usar

1. **Clone o repositório**:
```bash
git clone https://github.com/edwardosiillva-web/solucao-fiscal-website.git
cd solucao-fiscal-website
```

2. **Abra no navegador**:
- Abra o arquivo `index.html` diretamente no navegador, ou
- Use um servidor local (Python, Node.js, Live Server do VS Code)

## ⚙️ Configurações Necessárias

### Atualizar Número WhatsApp

No arquivo `script.js` (linha ~92), atualize o número WhatsApp:

```javascript
whatsappButton.setAttribute('href', 'https://wa.me/SEU_NUMERO_AQUI?text=Olá%20Solução%20Fiscal%21%20Gostaria%20de%20uma%20consulta%20gratuita.');
```

**Exemplo**: Para o número `11 99999-9999`, use `5511999999999`

### Atualizar E-mail de Contato

No arquivo `index.html`, procure por `solucaofiscalcontato@gmail.com` e atualize conforme necessário.

### Personalizar Textos e Conteúdo

Todos os textos da página podem ser facilmente editados diretamente no arquivo `index.html`.

## 🎯 Seções do Website

### 1. Navbar (Menu)
- Logo com ícone
- Links de navegação
- Menu hambúrguer para mobile

### 2. Hero (Banner Principal)
- Título principal
- Subtítulo descritivo
- Botão de chamada para ação

### 3. Sobre
- Quem é a Solução Fiscal
- Missão da empresa
- Lista de valores

### 4. Serviços
- Emissão de Notas Fiscais
- Levantamento de Débitos Fiscais
- Parcelamento Simples Nacional
- Parcelamento MEI
- Regularização Fiscal
- Consultoria Fiscal

### 5. Como Funciona
- 5 passos do processo de atendimento
- Fluxo visual intuitivo

### 6. Benefícios
- 6 benefícios principais com ícones

### 7. FAQ
- 6 perguntas frequentes
- Accordion interativo

### 8. Contato
- Informações de contato
- Formulário com validação
- Horário de atendimento

### 9. Botão WhatsApp
- Botão flutuante fixo
- Links diretos para conversa

### 10. Footer
- Links rápidos
- Informações da empresa
- Copyright

## 🎨 Paleta de Cores

- **Verde Primário**: `#1abc9c`
- **Verde Escuro**: `#16a085`
- **Verde Claro**: `#d5f4e6`
- **Branco**: `#ffffff`
- **Texto Escuro**: `#2c3e50`
- **Texto Claro**: `#7f8c8d`
- **Cinza Claro**: `#ecf0f1`

## 📱 Responsividade

O site é totalmente responsivo com breakpoints em:
- **Desktop**: 1200px+
- **Tablet**: 769px - 1199px
- **Mobile**: até 768px
- **Small Mobile**: até 480px

## 🔧 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Styling com variáveis CSS e Grid/Flexbox
- **Vanilla JavaScript** - Funcionalidades interativas
- **Font Awesome** - Ícones

## 📋 Funcionalidades JavaScript

1. **Menu Mobile Toggle** - Abre/fecha menu em dispositivos móveis
2. **FAQ Accordion** - Expande/recolhe respostas de FAQ
3. **Form Submission** - Valida e processa formulário de contato
4. **Scroll Animations** - Anima elementos ao entrar no viewport
5. **Smooth Scroll** - Navegação suave entre seções

## 🚀 Próximos Passos (Opcional)

Para aprimorar ainda mais o site, considere:

1. **Backend para Formulário** - Integrar com serviço de e-mail (SendGrid, Mailgun, etc)
2. **CMS** - Implementar painel administrativo para editar conteúdo
3. **Blog** - Adicionar seção de artigos sobre fiscal
4. **Analytics** - Google Analytics para rastrear visitantes
5. **SEO** - Otimizar para buscadores
6. **PWA** - Transformar em Progressive Web App

## 📧 Suporte

Para dúvidas ou sugestões sobre o website, entre em contato:
- Email: solucaofiscalcontato@gmail.com
- WhatsApp: [Seu número aqui]

## 📄 Licença

Este projeto é de propriedade da Solução Fiscal.

---

**Criado com ❤️ para Solução Fiscal**
