# Ateliê Urbano - Site de Teste para Magic Banner Plugin

Site estático de e-commerce para testar o **Magic Banner Plugin** do desafio técnico Futuriza.

## 🎯 Objetivo

Este site simula uma loja de roupas online ("Ateliê Urbano - Coleção Verão 2026") para testar a funcionalidade do Magic Banner Plugin em diferentes URLs.

## 📁 Estrutura do Site

```
.
├── index.html          # Página principal com grid de produtos
├── vestido.html        # Vestido Floral Verão
├── blusa.html          # Blusa Leve Tropical
├── shorts.html         # Shorts Jeans Premium
├── conjunto.html       # Conjunto Praia Elegante
├── saia.html           # Saia Midi Estampada
├── macaquinho.html     # Macaquinho Casual
├── styles.css          # Estilos CSS
└── README.md           # Este arquivo
```

## 🚀 Como Fazer Deploy no GitHub Pages

### Passo 1: Criar Repositório no GitHub

1. Acesse [GitHub](https://github.com) e faça login
2. Clique em **"New repository"**
3. Nome sugerido: `atelie-urbano-test`
4. Marque como **Public**
5. Clique em **"Create repository"**

### Passo 2: Fazer Upload dos Arquivos

**Opção A - Via Interface Web:**
1. No repositório criado, clique em **"uploading an existing file"**
2. Arraste todos os arquivos do projeto (onde está o `index.html`)
3. Commit com mensagem: "Initial commit - Test site"

**Opção B - Via Git (linha de comando):**
```bash
cd c:\Desenvolvimento\atelie-urbano
git init
git add .
git commit -m "Initial commit - Test site"
git branch -M main
git remote add origin https://github.com/RainerTeixeira/atelie-urbano-test.git
git push -u origin main
```

### Passo 3: Ativar GitHub Pages

1. No repositório, vá em **Settings** > **Pages**
2. Em **Source**, selecione **"Deploy from a branch"**
3. Em **Branch**, selecione **"main"** e pasta **"/ (root)"**
4. Clique em **Save**
5. Aguarde alguns minutos

### Passo 4: Acessar o Site

Seu site estará disponível em:
```
https://RainerTeixeira.github.io/atelie-urbano/
```

## 🔧 Configurar o Magic Banner Script

Este site já está configurado para carregar o script público da Futuriza.

### Substituir em todos os arquivos:
```html
<script src="https://futuriza-challenge.vercel.app/magic-banner.js"></script>
```

### Arquivos que precisam ser atualizados:
- ✅ `index.html`
- ✅ `vestido.html`
- ✅ `blusa.html`
- ✅ `shorts.html`
- ✅ `conjunto.html`
- ✅ `saia.html`
- ✅ `macaquinho.html`

## 🧪 Testar o Magic Banner Plugin

### URLs Disponíveis para Teste:

1. **Página Principal:**
   - `https://RainerTeixeira.github.io/atelie-urbano-test/`

2. **Páginas de Produtos:**
   - `https://RainerTeixeira.github.io/atelie-urbano/vestido.html`
   - `https://RainerTeixeira.github.io/atelie-urbano/blusa.html`
   - `https://RainerTeixeira.github.io/atelie-urbano/shorts.html`
   - `https://RainerTeixeira.github.io/atelie-urbano/conjunto.html`
   - `https://RainerTeixeira.github.io/atelie-urbano/saia.html`
   - `https://RainerTeixeira.github.io/atelie-urbano/macaquinho.html`

### Como Testar:

1. **No painel administrativo do Magic Banner Plugin**, cadastre banners para as URLs acima
2. Configure diferentes horários de exibição (opcional)
3. Acesse as páginas e verifique se os banners aparecem corretamente
4. Teste em diferentes horários para validar a funcionalidade de horário

### Exemplo de Banner para Cadastrar:

**Banner 1 - Página Principal:**
- URL: `https://RainerTeixeira.github.io/atelie-urbano-test/`
- Imagem: Banner promocional da coleção
- Horário: 08:00 - 20:00

**Banner 2 - Produto Específico:**
- URL: `https://RainerTeixeira.github.io/atelie-urbano-test/vestido.html`
- Imagem: Promoção do Vestido Floral
- Horário: 10:00 - 18:00

## 🎨 Características do Site

- ✅ Design moderno e responsivo
- ✅ 6 páginas de produtos diferentes
- ✅ Layout de e-commerce realista
- ✅ Imagens de alta qualidade (Unsplash)
- ✅ Navegação funcional
- ✅ Pronto para receber banners dinâmicos

## 📝 Notas Importantes

1. **O script do Magic Banner deve ser carregado em todas as páginas** - já está incluído no `<head>` de cada arquivo HTML
2. **As URLs devem ser exatas** - ao cadastrar banners, use a URL completa incluindo `https://`
3. **GitHub Pages pode levar alguns minutos** para atualizar após mudanças
4. **Teste em diferentes navegadores** para garantir compatibilidade

## 🔄 Atualizar o Site

Para fazer alterações no site após o deploy:

1. Edite os arquivos localmente
2. Faça commit e push para o GitHub:
   ```bash
   git add .
   git commit -m "Descrição das mudanças"
   git push
   ```
3. Aguarde alguns minutos para o GitHub Pages atualizar

## 💡 Dicas para o Desafio

- Use URLs diferentes para testar a lógica de matching do plugin
- Teste com e sem horários configurados
- Verifique se o banner aparece apenas nas URLs corretas
- Teste a responsividade dos banners em mobile
- Valide que múltiplos banners não conflitam

---

**Desenvolvido para o Desafio Técnico Magic Banner Plugin - Futuriza** 🚀
