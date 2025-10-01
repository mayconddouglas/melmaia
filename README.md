# MelMaia Privacy Site

Site de privacy para Mel Maia - Landing page de conversão otimizada para monetização.

## 📋 Descrição

Este é um site estático responsivo que simula uma plataforma de conteúdo premium, desenvolvido com foco em conversão e experiência do usuário. O projeto inclui funcionalidades como sistema de assinatura, conteúdo bloqueado, analytics integrado e design moderno.

## 🚀 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica e responsiva
- **CSS3** - Estilização moderna com variáveis CSS e flexbox
- **JavaScript** - Interatividade e funcionalidades dinâmicas
- **Bootstrap** - Framework CSS para responsividade
- **Google Analytics** - Rastreamento e análise de dados
- **Microsoft Clarity** - Análise de comportamento do usuário

## 📁 Estrutura do Projeto

```
MelMaia/
├── index.html              # Página principal
├── images/                 # Imagens do projeto
│   ├── bannermelmaia3.jpg
│   ├── fotomelmaia1.jpg
│   ├── fotomelmaia3.jpg
│   ├── fotoperfilmelmaia1.jpg
│   ├── images-logo.webp
│   └── 219-images-favicon.png
├── media/                  # Arquivos de vídeo
│   ├── videomelmaia02.mp4
│   └── videomelmaia03.mp4
├── favicons/              # Páginas de erro 404
│   ├── 2402-images-favicon.html
│   └── 5022-images-favicon.html
├── package.json           # Configuração do projeto
├── vercel.json           # Configuração da Vercel
├── .gitignore            # Arquivos ignorados pelo Git
└── README.md             # Este arquivo
```

## 🛠️ Instalação e Configuração

### Pré-requisitos

- Node.js (versão 16 ou superior)
- npm ou yarn
- Conta na Vercel

### Instalação Local

1. Clone o repositório:
```bash
git clone <url-do-repositorio>
cd MelMaia
```

2. Instale as dependências:
```bash
npm install
```

3. Execute o projeto localmente:
```bash
npm run dev
```

O site estará disponível em `http://localhost:3000`

## 🚀 Deploy na Vercel

### Método 1: Deploy via CLI da Vercel

1. Instale a CLI da Vercel:
```bash
npm install -g vercel
```

2. Faça login na Vercel:
```bash
vercel login
```

3. Execute o deploy:
```bash
vercel
```

4. Siga as instruções no terminal para configurar o projeto.

### Método 2: Deploy via GitHub

1. Faça push do código para um repositório GitHub
2. Acesse [vercel.com](https://vercel.com)
3. Conecte sua conta GitHub
4. Importe o repositório
5. A Vercel detectará automaticamente as configurações do `vercel.json`

### Método 3: Deploy via Interface Web

1. Acesse [vercel.com](https://vercel.com)
2. Clique em "New Project"
3. Faça upload da pasta do projeto
4. A Vercel configurará automaticamente o deploy

## ⚙️ Configurações da Vercel

O arquivo `vercel.json` inclui:

- **Roteamento SPA**: Todas as rotas redirecionam para `index.html`
- **Headers de Segurança**: X-Content-Type-Options, X-Frame-Options, X-XSS-Protection
- **Cache Otimizado**: Cache de longo prazo para assets estáticos
- **URLs Limpas**: Remoção de extensões .html

## 🔧 Scripts Disponíveis

- `npm run dev` - Inicia servidor de desenvolvimento
- `npm start` - Inicia servidor de produção
- `npm run build` - Build do projeto (não necessário para sites estáticos)
- `npm run preview` - Preview do projeto

## 📊 Analytics e Tracking

O projeto inclui integração com:

- **Google Analytics 4** - ID: G-XXXXXXXXXX
- **Google Tag Manager** - ID: GTM-XXXXXXX
- **Microsoft Clarity** - Para análise de comportamento
- **UTMify** - Para rastreamento de campanhas

## 🔒 Segurança

- Headers de segurança configurados
- Proteção contra XSS
- Proteção contra clickjacking
- Content-Type sniffing desabilitado

## 🎨 Funcionalidades

- ✅ Design responsivo e moderno
- ✅ Sistema de assinatura simulado
- ✅ Conteúdo bloqueado/premium
- ✅ Player de vídeo customizado
- ✅ Analytics integrado
- ✅ Otimização para conversão
- ✅ Cookie consent banner
- ✅ Tabs de conteúdo dinâmicas

## 📱 Compatibilidade

- ✅ Desktop (Chrome, Firefox, Safari, Edge)
- ✅ Mobile (iOS Safari, Chrome Mobile)
- ✅ Tablet (iPad, Android tablets)

## 🐛 Solução de Problemas

### Erro 404 em rotas

Verifique se o `vercel.json` está configurado corretamente com o redirecionamento SPA.

### Problemas de cache

Limpe o cache do navegador ou use o modo incógnito para testar.

### Vídeos não carregam

Verifique se os arquivos de vídeo estão na pasta `media/` e se os caminhos estão corretos.

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

## 👥 Contribuição

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📞 Suporte

Para suporte técnico ou dúvidas sobre o projeto, entre em contato através dos canais oficiais.

---

**Desenvolvido com ❤️ para conversão otimizada**