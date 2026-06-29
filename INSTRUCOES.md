# Como Publicar no GitHub Pages

## Passo 1: Criar o Repositório no GitHub

1. Acesse: https://github.com/new
2. No campo **Repository name**, digite: `lfcdrywall`
3. Selecione **Public**
4. Marque **Add a README file**
5. Clique em **Create repository**

## Passo 2: Enviar os Arquivos

### Opção A: Upload Direto (Mais Fácil)

1. No repositório criado, clique no botão **Add file** > **Upload files**
2. Arraste ou selecione os arquivos:
   - `index.html`
   - `README.md`
3. Clique em **Commit changes**

### Opção B: Usar Git (Se souber)

```bash
git clone https://github.com/SEU-USUARIO/lfcdrywall.git
cd lfcdrywall
# Copie o index.html para a pasta
git add .
git commit -m "Site LFC Drywall"
git push
```

## Passo 3: Ativar o GitHub Pages

1. No repositório, vá em **Settings** (Configurações)
2. No menu lateral, clique em **Pages**
3. Em **Source**, selecione:
   - **Deploy from a branch**
4. Em **Branch**, selecione:
   - **main** (ou master)
   - **/ (root)**
5. Clique em **Save**

## Passo 4: Aguardar e Acessar

Aguarde cerca de 2-5 minutos para o site ficar disponível.

Seu site estará em: `https://SEU-USUARIO.github.io/lfcdrywall`

---

## Estrutura do Site

```
lfcdrywall/
├── index.html    ← Página principal do site
└── README.md    ← Informações sobre o projeto
```

## Recursos do Site

✅ Design profissional e moderno
✅ Totalmente responsivo (desktop, tablet, celular)
✅ Botão WhatsApp em destaque: (15) 99618-7444
✅ Navegação suave entre seções
✅ Seções: Início, Serviços, Sobre, Contato
✅ Botão flutuante do WhatsApp
✅ Imagens de alta qualidade
✅ Cores profissionais (azul e dourado)
