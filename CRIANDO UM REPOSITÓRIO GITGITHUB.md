# CRIANDO UM REPOSITÓRIO GIT/GITHUB



É de grande importância nos dias de hoje, manter seus dados, informações, disponível ao usuário onde quer que esteja.

Essa combinação GIT e GITHUB veio para no ajudar nesse dilema já que o  **GitHub** é uma excelente ferramenta. 

Sabemos que para o trabalho em equipe o GitHub é uma ferramenta maravilhosa cooperando para eficiência da equipe.

Quando se trata de um software ou um site que precisa ser criado em conjunto, por exemplo, a plataforma online facilita, sem dúvidas, a gestão do projeto. E essa ferramenta também está disponível para empresas: é conhecida como **GitHub** Enterprise.

## Passos para criação do repositório

#### Criação do Git Local: 

`git init` é um comando único que você usa durante a configuração inicial de um novo repositório. A execução desse comando cria um novo subdiretório `.git` no diretório.

- Criar um repositório localmente
- Adicionar (add) e comitar (commit)



#### Criação Repositório Público - GitHub

Começamos acessando site do gitHub: https://github.com/

- Criar uma conta com e-mail e senha

- Criar um repositório no GitHub

  Para criar um repositório, basta clicar sobre o botão “+” localizado no canto superior direito e selecionar a opção “New repository”.

  Com isso o repositório será criado e já estamos prontos para adicionar nossos projetos no GitHub

  

#### Conectando os repositórios

- Conectar o repositório local com o repositório público
- Sincronizar ambos os repositórios

###### Podemos seguir alguns passos para esse processo:

1. /* navegando até a pasta */
2. $ cd nomedaminhapasta 
3. /* estando dentro da pasta do projeto, indique a URL */
4. $ git remote add origin NOME-DO-REPOSITORIO
5. /* verificando a origem adicionada ao repositório */
6. $ git remote -v



##### Podemos também clonar um repositório já existente

Na página da Web do [repositório](https://github.com/WoMakersCode/Front-end-Study-Group), clique no botão verde "clone or download", no lado direito da página.

Selecione a opção "Usar HTTPS ou  SSH " - se estiver disponível - e copie o link.

No Terminal, navegue até sua pasta de desenvolvimento e digite:

1. $ cd Desktop(NOME ESCOLHIDO PARA SUA PASTA)
2. $ git clone https://github.com/WoMakersCode/Front-end-Study-Group.git nomedanovapasta 



Pronto! Agora é só aproveitar.

