# 💌 Gerador de Convites Mágicos (Convity)

> Um Web App **Mobile-First** para criar convites interativos, animados e personalizados que funcionam via WhatsApp. Sem banco de dados, puramente mágico. ✨

![Badge Status](https://img.shields.io/badge/Status-Finalizado-success)
![Badge Tech](https://img.shields.io/badge/Tech-HTML%20%7C%20CSS%20%7C%20JS-blue)
![Badge License](https://img.shields.io/badge/License-MIT-yellow)

## 📱 Sobre o Projeto

Uma aplicação web intuitiva que permite criar convites personalizados com design moderno e animações envolventes. Compartilhe via WhatsApp através de um link único e interativo.

**Diferenciais:** Interface animada com efeitos de partículas, design Glassmorphism e temas dinâmicos que mudam instantaneamente.

## 🌟 Funcionalidades Principais

- **🎨 Temas Dinâmicos:** 5 vibes disponíveis (Romântico, Festa, Amizade, Natureza, Dark)
- **✨ Animações em Canvas:** Partículas interativas (Corações, Confetes, Folhas)
- **🔗 Serverless:** Dados compactados em Base64 na URL
- **📱 Mobile-First:** 100% otimizado para celulares
- **💬 Integração WhatsApp:** Resposta pré-preenchida automática

## 🚀 Como Funciona

1. Usuário preenche dados no `index.html`
2. JavaScript converte dados em JSON
3. Codificação Base64 via `btoa()` e `encodeURIComponent()`
4. Link gerado: `convite.html?d=CÓDIGO_BASE64`
5. Página renderiza dinamicamente ao abrir o link

## 🛠️ Instalação

**Pré-requisito:** Navegador web moderno

### Rodando Localmente
```bash
git clone https://github.com/SEU-USUARIO/NOME-DO-REPO.git
```
Abra `index.html` no navegador.

### Hospedagem Gratuita
- [Netlify](https://www.netlify.com/)
- [Vercel](https://vercel.com/)
- [GitHub Pages](https://pages.github.com/)

## 📂 Estrutura

```
├── index.html      # Criador de convites
├── convite.html    # Template de exibição
├── README.md       # Documentação
└── assets/         # (Opcional) Mídia
```

## 🎨 Personalização

Adicione novos temas editando o objeto `themes`:

```javascript
const themes = {
    novoTema: { 
        color: '#COR_HEX', 
        bg: 'linear-gradient(...)', 
        emoji: '😎' 
    }
};
```

## 🤝 Contribuição

1. Fork do projeto
2. Crie uma Branch (`git checkout -b feature/MinhaFeature`)
3. Commit das mudanças (`git commit -m 'Adicionando X'`)
4. Push (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

## 📄 Licença

MIT License - Livre para usar e modificar.

---

Feito com ❤️ por [Leonardo]
