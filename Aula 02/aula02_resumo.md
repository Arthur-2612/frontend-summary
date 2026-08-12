# Aula 02 — Configuração do Ambiente de Desenvolvimento

**Disciplina:** Frameworks Front-end
**Foco:** Preparação do ambiente, versionamento, Git, Node.js, React e deploy
**Professor:** Prof. Me. Deivison S. Takatu

---

## Conteúdos

- Versionamento e SemVer
- Git e GitHub
- Tags, Branches e boas práticas
- Visual Studio Code
- Node.js e NPM
- Criação de projetos React
- Deploy com Vercel

---

## Versionamento

O versionamento permite controlar e registrar as alterações realizadas em um projeto, facilitando a colaboração, auditoria e recuperação de versões anteriores.

### SemVer

Utiliza o padrão:

\`\`\`
MAJOR.MINOR.PATCH
\`\`\`

- **MAJOR**: mudança incompatível.
- **MINOR**: nova funcionalidade compatível.
- **PATCH**: correção de bugs.

**Exemplo:**

\`\`\`
1.0.0 → versão estável
1.1.0 → nova funcionalidade
1.1.1 → correção de bug
2.0.0 → mudança incompatível
\`\`\`

---

## Git

O Git é utilizado para controlar versões e acompanhar as alterações do projeto.

### Configuração inicial

\`\`\`bash
git config --global user.name "<Nome>"
git config --global user.email "<Email>"
\`\`\`

### Boas práticas

- Fazer commits pequenos e frequentes;
- Utilizar mensagens claras;
- Utilizar branches para novas funcionalidades;
- Testar antes de realizar merge.

---

## Node.js e NPM

O **Node.js** permite executar JavaScript no servidor.

O **NPM** gerencia pacotes e dependências do projeto, utilizando principalmente o `package.json`.

### Verificar instalação

\`\`\`bash
node --version
npm --version
\`\`\`

---

## React

### Criação de um projeto

\`\`\`bash
npx create-react-app meu-projeto-react
cd meu-projeto-react
code .
npm start
\`\`\`

### Principais diretórios e arquivos

\`\`\`
node_modules/ → dependências
public/       → arquivos públicos
src/          → código React
App.js        → componente principal
index.js      → entrada da aplicação
package.json  → dependências e scripts
\`\`\`

---

## Deploy com Vercel

**Deploy** é o processo de disponibilizar uma aplicação em produção. A **Vercel** permite conectar o projeto ao GitHub e realizar deploys automaticamente após novos `pushes`.

### Fluxo

\`\`\`
VS Code → Git → GitHub → Vercel → Aplicação Online
\`\`\`

---

## Atividade

Desenvolver uma aplicação React, versioná-la com Git, publicar no GitHub e realizar o deploy utilizando a Vercel.