# 📱 Minha Vida Organizada — PWA / APK

## Arquivos incluídos
```
index.html      ← o app principal
manifest.json   ← configurações do PWA
sw.js           ← service worker (modo offline)
icons/          ← ícones do app (todos os tamanhos)
```

---

## 🚀 Passo a Passo: Hospedar e Gerar APK

### 1. Hospedar gratuitamente no Netlify (5 minutos)

1. Acesse https://netlify.com e crie uma conta gratuita
2. Na tela inicial, clique em **"Add new site" → "Deploy manually"**
3. **Arraste a pasta inteira** (com todos os arquivos) para a área indicada
4. Aguarde o deploy — você receberá uma URL tipo: `https://seu-app.netlify.app`
5. Teste abrindo a URL no celular ✅

### 2. Gerar o APK no PWABuilder

1. Acesse https://pwabuilder.com
2. Cole a URL do seu app (ex: `https://seu-app.netlify.app`)
3. Clique em **"Start"** — ele vai analisar o PWA
4. Clique em **"Package for stores"**
5. Escolha **Android** → **"Download Package"**
6. Você receberá um arquivo `.apk` pronto

### 3. Instalar o APK no Samsung

1. Transfira o `.apk` para o celular (WhatsApp, Google Drive, cabo USB)
2. Abra o arquivo no celular
3. Se aparecer aviso de segurança:
   - Vá em **Configurações → Segurança → Instalar apps desconhecidos**
   - Autorize o app que você usou para abrir o arquivo (ex: Chrome, Arquivos)
4. Volte e instale normalmente
5. O app aparece na tela inicial! 🎉

---

## 💡 Dicas

- **Seus dados ficam salvos** no próprio celular (localStorage)
- **Funciona offline** — sem internet tudo funciona normalmente
- Para **atualizar o app**, edite o index.html, faça novo deploy no Netlify e o PWABuilder gera um novo APK
- A integração com **Google Calendar** continua funcionando (requer internet)

---

Feito com ❤️ usando Claude
