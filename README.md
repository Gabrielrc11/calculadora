# Calculadora

## Requisitos:
- NodeJS
  - Instalar NodeJS - <a href="https://nodejs.org/dist/v20.12.2/node-v20.12.2-x64.msi">Baixar!</a>

## Executando projeto
1. Através do GIT clone o repositório do projeto:
    - ```git clone https://github.com/Gabrielrc11/calculadora.git```
2. Entre na pasta **calculadora** com o comando:
    - ```cd calculadora```
3. Execute o seguinte comando para instalar as dependencias do Expo:
    - ```npm install --save-dev expo-cli```
4. Execute o seguinte comando para rodar o projeto:
    - ```npx expo start```
> [!NOTE]
> Para parar a execução do projeto use, no terminal, as teclas: ```Ctrl + C```

## Padronizações
### Commits
Os commits devem seguir o padrão mostrado no site do <a href="https://www.conventionalcommits.org/pt-br/v1.0.0/" target="_blank">Conventional Commits</a>

## Branches
A padronização das **Branches** é parecida com a padronização dos commits, onde o nome da branch precisa ter um ***préfixo*** da seguinte forma:
 - ```feature/name_branch```
Esses **préfixo** podem ser:

| Préfixos  | Descrição |
| ------------- | ------------- |
| feature | Usado na branch que tem o objetivo de adicionar, refatorar ou remover um recurso  |
| bugfix  | Usado na branch que tem o objetivo de corrigir um bug  |
| hotfix  | Usado na branch que tem o objetivo de alterar o código com uma solução temporária e/ou sem seguir o processo normal (geralmente devido a uma emergência)  |
| improvement  | Usado na branch que tem o objetivo criar uma melhoria para algo que já existente, seja de performance, de escrita, de layout, etc. |
