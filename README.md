# Projeto Causa Dev Design System

Este é o repositório do design system utilizado nos projetos do Causa Dev, uma iniciativa para garantir o padrão das interfaces criadas para os nossos projetos assim como a simplificação dos processos que envolvem a criação de projetos front-end.

<!-- ## Contribuição e Projeto Causa Dev // TODO: Escrever sobre o projeto Causa Dev e como interessados podem fazer para entrar no projeto. -->

## Motivação

A motivação para criar essa biblioteca de componentes vem do objetivo de manter as coisas organizadas desde o começo e evitar retrabalho.
Os projetos do Causa Dev sempre presarão pela praticidade do desenvolvedor, logo, essa biblioteca busca abstrair para o desenvolvedor todos os detalhes de design necessários para se construir uma interface padronizada, acessível e bonita.

<!-- ## Estrutura // TODO: Descrever sobre o Atomic Design -->

<!-- ## Demonstração, Documentação e Testes // TODO: Descrever sobre o uso do Storybook -->

## Como executar localmente

Siga as instruções abaixo para executar este projeto em sua máquina:

1. Clone o repositório para sua máquina local usando `git clone https://github.com/Causa-Dev/causa-dev-design-system.git`.

2. Navegue até o diretório clonado usando `cd causa-dev-design-system`.

3. Instale todas as dependências do projeto usando `npm i`.

<!-- 4. Para executar o servidor de desenvolvimento, use o comando `npm start`. // TODO: adaptar para o uso do Storybook -->

<!-- 5. Acesse `http://localhost:2460/` para visualizar a página do projeto localmente. // TODO: adaptar para o uso do Storybook -->

6. Para criar uma versão de produção, use o comando `npm run build`.


<!-- ## React Mínimo // TODO: Descrever um pouco sobre o projeto React Mínimo e deixar claro o porque esse projeto é um fork dele. -->


## Licença

Este projeto está sob a licença GNU. Veja o arquivo `LICENSE` para mais detalhes.

### Versionamento:

**Exemplo de Versão: "1.04.01"**

**Estrutura da Versão: A.B.C**

**Significado dos Componentes:**

- **A (Mudanças Grandes):** 
  - Representa modificações significativas que alteram a forma de utilização da biblioteca.
  - Estas mudanças requerem atualizações em projetos dependentes.
  - Sempre que uma alteração desse calibre for implementada, o número da versão em "A" deve ser incrementado.

- **B (Adição de Recursos):**
  - Corresponde às adições de novas funcionalidades, como os layouts de retrospectiva no contexto deste projeto.
  - A cada inclusão de um novo layout, a porção "B" da versão deve ser incrementada.

- **C (Mudanças Menores):**
  - Envolve ajustes e modificações pequenas, principalmente nos layouts existentes.
  - Quando houver qualquer mudança simples a porção "B" da versão deve ser incrementada.

### Deploy:

- **Regras**
  - Não subir modificações diretamente para a branch `Master`.
  - Manipular o número de versão corretamente antes de submeter qualquer modificação para esse repositório.

- **CI/CD**
  - Esse repositório está configurado para realizar um deploy automático de um pacote no `Github Packages` assim que a branch `Master` recebe um push.
  - Os repositórios dependentes devem atualizar suas dependências sempre que um novo package for lançado usando o comando `npm i` ou `yarn`.


