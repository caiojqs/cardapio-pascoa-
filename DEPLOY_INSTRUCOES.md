# 🚀 Instruções para Deploy Permanente - Vercel

## Passo 1: Criar Conta no GitHub (Gratuito)

1. Acesse: https://github.com
2. Clique em "Sign up"
3. Preencha com seus dados:
   - Email: seu email
   - Senha: crie uma senha forte
   - Username: pode ser "patriciamathias" ou similar
4. Confirme o email

## Passo 2: Criar um Novo Repositório no GitHub

1. Após fazer login, clique no "+" no canto superior direito
2. Selecione "New repository"
3. Preencha:
   - Repository name: `cardapio-pascoa`
   - Description: "Cardápio Digital de Páscoa - Patricia Mathias"
   - Public (deixe marcado)
   - Clique em "Create repository"

## Passo 3: Fazer Upload dos Arquivos para GitHub

Você tem 2 opções:

### Opção A: Usando Git (Recomendado)

```bash
cd /home/ubuntu/cardapio-pascoa
git remote add origin https://github.com/SEU_USERNAME/cardapio-pascoa.git
git branch -M main
git push -u origin main
```

Substitua `SEU_USERNAME` pelo seu username do GitHub.

### Opção B: Fazer Upload Direto (Mais Fácil)

1. No GitHub, na página do repositório, clique em "Add file" > "Upload files"
2. Arraste todos os arquivos (exceto .git)
3. Clique em "Commit changes"

## Passo 4: Conectar Vercel ao GitHub

1. Acesse: https://vercel.com
2. Clique em "Sign Up" > "Continue with GitHub"
3. Autorize o Vercel a acessar sua conta GitHub
4. Clique em "New Project"
5. Procure por "cardapio-pascoa"
6. Clique em "Import"
7. Deixe as configurações padrão e clique em "Deploy"

## Passo 5: Aguardar Deploy

- Vercel vai processar em alguns segundos
- Você receberá um URL permanente como: `https://cardapio-pascoa-XXXXX.vercel.app`
- Compartilhe este link com seus clientes!

## ✅ Pronto!

Seu site agora está:
- ✅ Permanente (não expira)
- ✅ Gratuito
- ✅ Atualizado automaticamente quando você faz mudanças no GitHub
- ✅ Com HTTPS seguro
- ✅ Rápido e confiável

## 📝 Para Fazer Alterações Depois

1. Edite os arquivos localmente
2. Faça commit: `git add . && git commit -m "Descrição da mudança"`
3. Faça push: `git push`
4. Vercel atualiza automaticamente em segundos!

## 🆘 Precisa de Ajuda?

- GitHub Help: https://docs.github.com
- Vercel Docs: https://vercel.com/docs
- Suporte Vercel: https://vercel.com/support

---

**Seu cardápio estará online permanentemente! 🎉**
