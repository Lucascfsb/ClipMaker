# 🎬 ClipMaker - AI Viral Moments

Um aplicativo web inovador que utiliza **Inteligência Artificial** para ajudar você a criar e extrair os momentos mais virais de seus vídeos. Com ClipMaker, transforme seus vídeos longos em clips curtos, atraentes e otimizados para redes sociais.

## ✨ Recursos Principais

- 🤖 **Detecção IA de Momentos Virais** - Análise inteligente para encontrar os melhores trechos
- 📹 **Upload Facilitado** - Interface intuitiva com suporte a Cloudinary
- 🎨 **Design Moderno** - Interface responsiva com animações fluidas
- ⚡ **Processamento Rápido** - Powered by Google Gemini API
- 📱 **Mobile-Friendly** - Funciona perfeitamente em qualquer dispositivo

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **Tailwind CSS** - Estilização utility-first
- **GSAP** - Animações avançadas
- **Google Gemini API** - Processamento de IA
- **Cloudinary** - Gerenciamento de mídia
- **Lucide Icons** - Ícones modernos

## 🚀 Como Usar

### 1. Clone o Repositório
```bash
git clone https://github.com/seu-usuario/nlw-22.git
cd nlw-22
```

### 2. Configure sua API Key
- Obtenha uma chave API do [Google Gemini](https://aistudio.google.com/app/apikey)
- Cole a chave na interface da aplicação quando solicitado

### 3. Execute Localmente
```bash
# Abra o arquivo index.html em seu navegador
# Ou com um servidor local:
python -m http.server 8000
# Acesse http://localhost:8000
```

## 📋 Pré-requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Conexão com internet
- Google Gemini API Key (gratuita)
- Conta Cloudinary (opcional, para upload de vídeos)

## 📦 Instalação

Não há dependências externas para instalar! O projeto usa CDNs para todas as bibliotecas:

- Tailwind CSS via CDN
- GSAP via CDN
- Lucide Icons via CDN
- Cloudinary Widget via CDN

Basta servir o arquivo `index.html` em um servidor HTTP simples.

## 💻 Desenvolvimento

### Estrutura do Projeto
```
nlw-22/
├── index.html       # Página principal
├── README.md        # Este arquivo
└── .git/            # Repositório Git
```

### Personalizações

Você pode customizar:
- **Cores**: Modifique as variáveis CSS em `:root` no `<style>`
- **Animações**: Ajuste os parâmetros do GSAP
- **Configurações Cloudinary**: Atualize o widget widget de upload

## 🔐 Segurança

⚠️ **Importante**: Nunca commite sua API Key do Gemini! 
- Use variáveis de ambiente
- Considere usar um backend para processar as requisições
- Valide as entradas do usuário

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Faça um Fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto é distribuído sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.


## 🙏 Agradecimentos

- NLW 22 - Rocketseat
- Google Gemini API
- Cloudinary
- Tailwind CSS
- GSAP


---

**Aproveite! Crie momentos virais com ClipMaker! 🚀**
