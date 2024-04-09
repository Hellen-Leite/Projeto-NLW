# Projeto NLW
Esse projeto foi criado junto ao evento NLW UNITE da rocketseat.
## Tecnologias utilizadas
Para desenvolvê-lo foi necessário utilizar 
* [ReactJS](https://react.dev/) 
* [Tipagem com TypeScript](https://www.typescriptlang.org/) 
* [Tooling com Vite](https://vitejs.dev/guide/)
* [Interface responsiva com TailwindCSS](https://tailwindcss.com/docs/installation) e 
* [Consumo de API com Node.js](https://nodejs.org/en).
## Bibliotecas adicionais:
* [Lucide](https://lucide.dev/guide/packages/lucide-react)
* [Tailwind Merge](https://www.npmjs.com/package/tailwind-merge)
* [Day JS](https://day.js.org/)
## Dependências e Versões Necessárias
* Node- Versão 20.6.0
## Como rodar o projeto
Para rodar o projeto, vc precisa clicar [aqui](https://github.com/rocketseat-education/nlw-unite-nodejs). Depois de aberto o link, vc precisa clicar no botão <strong> Code </strong> e copiar o link que irá aparecer.
Agora você vai dar o seguinte comando no seu terminal:
```
git clone
```
Depois de dado o git clone,você irá colar o link copiado pelo botão, e apertar <strong> Enter </strong>. Agora você poderá abrir o projeto pelo seu VSCode.
É necessário, dentro do projeto, criar um arquivo com nome <strong> .env </strong> e nele colar o seguinte: DATABASE_URL="file:./dev.db".
Após esses passos, você deve abrir novamente o terminal do seu VSCode, e lá dar o comando:
```
npx prisma seed
```
Depois:
```
npm install
```
e logo após:
```
npm run dev
```
Depois de dados esses comandos, no próprio terminal deve aparecer: <strong> HTTP server running </strong> e uma série de textos.

Agora com o repositório da API rodando localmente na sua máquina, você deve ir no botão "code", presente logo acima neste repositório, copiar o link do mesmo, depois abrir o seu terminal e na sua pasta de preferência, dar o comando:
```
 git clone
```
e logo em seguida colar com <strong> Ctrl+ Shift+V </strong> o link copiado anteriormente, apertando na tecla Enter.
Depois disso, entrar na pasta clonada, abri-la com o vscode, ou o programa editor de código de sua preferência, abrir o terminal pelo editor de código e dar um
```
npm install
```
Após esses passos, basta um
```
npm run dev
```
E aparecerá a seguinte mensagem no terminal:  <strong> ➜  Local:   http://localhost:5173/ </strong>

Agora basta clicar no endereço apontado pelo terminal e a página irá rodar no seu navegador padrão.
## ⚠️ Problemas enfrentados

Um dos principais problemas enfrentados por mim ao tentar rodar a aplicação, foi a questão do versionamento. Como dito anteriormente, ela roda perfeitamente se no seu computador estiver instalado o nodejs.
Se você não tem esse programa no seu computador, é recomendado que baixe-o, e caso tenha o vnm, basta abrir novamente o terminal, e nele executar:
```
nvm install v20.6.0

```
É a partir dessa versão do nodejs que a aplicação poderá rodar perfeitamente.

## Sobre a aplicação em si

Este é o layout da aplicação:
![Capturar_20240408212133](https://github.com/Hellen-Leite/Projeto-NLW/assets/146649332/4a1fe02a-c38e-4902-8267-2cadcde72509)
![Capturar_20240408212144](https://github.com/Hellen-Leite/Projeto-NLW/assets/146649332/6261462e-71bd-4fbc-af94-d296b79d2c9a)
![Capturar_20240408212154](https://github.com/Hellen-Leite/Projeto-NLW/assets/146649332/d2663722-18e2-4e59-9a32-d9d15dc693b1)
Ao clicar em cada uma dessas setas, a aplicação avança ou retorna 10 nomes fictícios pra frente, ou retorna, 10 nomes atrás.
Trata-se da simulação de uma página de evento com candidatos inscritos.

## Aprendizados

Através dessa aplicação tive minha primeira experiência com o ReactJS, pude explorar um pouco do mundo das bibliotecas, vi também como funciona o tailwindCSS, e pude em um único projeto adquirir muito conhecimento.
