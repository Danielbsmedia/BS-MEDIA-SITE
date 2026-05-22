# BS MEDIA — Landing Page

Site institucional da BS MEDIA Agency.

## Estrutura

```
bs-media-deploy/
├── index.html       ← site completo (HTML single-file)
├── assets/          ← imagens, logos e SVGs
├── vercel.json      ← configuração de deploy (cache + rotas)
├── .gitignore
└── README.md
```

## Deploy via GitHub + Vercel

### 1. Criar repositório no GitHub
1. Acesse [github.com/new](https://github.com/new)
2. Crie um repositório **privado** (ex: `bs-media-site`)
3. Não inicialize com README (já existe um aqui)

### 2. Enviar os arquivos
No terminal, dentro desta pasta:
```bash
git init
git add .
git commit -m "feat: deploy inicial BS MEDIA"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/bs-media-site.git
git push -u origin main
```

### 3. Conectar ao Vercel
1. Acesse [vercel.com](https://vercel.com) e faça login
2. Clique em **"Add New Project"**
3. Importe o repositório `bs-media-site` do GitHub
4. Nas configurações do projeto:
   - **Framework Preset:** Other
   - **Root Directory:** `.` (padrão)
   - **Build Command:** *(deixar vazio)*
   - **Output Directory:** `.` (ponto)
5. Clique em **Deploy**

O site ficará disponível em um domínio `.vercel.app` em menos de 1 minuto.

### 4. Domínio personalizado (opcional)
Em **Settings → Domains** no painel Vercel, adicione o domínio desejado e aponte o DNS conforme instrução da Vercel.

---

**Suporte:** gbatistadesousamedeiros@gmail.com
