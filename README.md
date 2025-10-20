# Presell Page - Página de Confirmação

Uma página de presell profissional e responsiva, otimizada para dispositivos móveis.

## Deploy no Heroku

### Pré-requisitos
- Conta no Heroku
- Heroku CLI instalado
- Git instalado

### Passo a Passo para Deploy

1. **Faça login no Heroku**
   ```bash
   heroku login
   ```

2. **Crie um novo app no Heroku**
   ```bash
   heroku create nome-do-seu-app
   ```
   Ou deixe o Heroku gerar um nome aleatório:
   ```bash
   heroku create
   ```

3. **Inicialize o repositório Git (se ainda não estiver inicializado)**
   ```bash
   git init
   git add .
   git commit -m "Preparar para deploy"
   ```

4. **Faça o deploy**
   ```bash
   git push heroku main
   ```
   Ou se sua branch principal é `master`:
   ```bash
   git push heroku master
   ```

5. **Abra seu app**
   ```bash
   heroku open
   ```

### Alternativa: Deploy via Dashboard do Heroku

1. Acesse https://dashboard.heroku.com/
2. Clique em "New" > "Create new app"
3. Dê um nome ao seu app e escolha a região
4. Na aba "Deploy", conecte seu GitHub ou use Heroku Git
5. Clique em "Deploy Branch"

## Arquivos Importantes

- `index.html` - Página principal
- `server.js` - Servidor Express para servir a página
- `package.json` - Dependências do projeto
- `Procfile` - Instrução para o Heroku executar o servidor

## Recursos

- ✅ Design responsivo
- ✅ Otimizado para mobile
- ✅ Efeito de brilho automático no botão
- ✅ Redirecionamento configurado
- ✅ Pronto para produção

## Tecnologias

- HTML5
- CSS3
- Node.js
- Express.js
