# Curso de Git e GitHub

- **Git:** Software ou ferramenta que vai criar esse acompanhamento de versões e comparações de projetos;

- **GitHub:** Plataforma que permite armazenar e criar backups de projetos;

- **Colaboração:** Para inclusão de colaboradores, o proprietário do repositório deve acessar seu repositório no GitHub>Settings>Collaborators>Add people, inserir o e-mail do colaborador, o qual deve criar o repositorio local, utilizando o comando gitr clone <ssh>.

- 

# Áreas Conceituais

1. **Área de Desenvolvimento:** Onde eu desenvolvo e salvo meus arquivos referentes ao meu projeto

2. **Repositório Local:** Gestão das versões do projeto

3. **Staging Área:** Área onde você realizará algo

4. **Área Remota:** Local que os arquivos gerados serão depositados no git online (nuvem)

**Git add PS:** o git add pode ser utilizado para adicionar outros diretórios tendo em mente a logistica e linha do tempo que será criada

Boa tarde, quero criar um caos, vou criar um conflito

Branch: criar um local paralelo na sua linha do tempo, que tem como função realizar testes de versões, softwares, sem ter risco de alterar a linha do tempo principal

1. Git branch: criar um local

2. git branch --list: listar os branchs existentes 

Checkout: Será o nosso delorian passeando pela linha do tempo a depender do id do commit que você colocar além de entrar e sair do branch

1. git checkout <nome>

2. git checkout <id>

# Conflitos

Principalmente quando trabalhar em colaboração a existência de "conflitos" é iminente, neste sentido é importante saber solucionar esses conflitos

1. Push <textão>

2. Pull <aviso de conflito>

3. Abrir o arquivo > Resolver (ESCOLHER A MENSAGEM QUE VAI FICAR E EXCLUIR AS DEMAIS/CRIAR UMA NOVA MSG) > Salvar usando a rotina:
   
   1. add
   
   2. commit
   
   3. push

Efeito espelho: arquivos que estão depositados no git se encontra na pasta no projeto e uma ação feita em qualquer parte, vai refletir em outro.



Criar tags: dar nome ao commit 

git push --tag enviar tag para o repositório remoto



git merge: juntar uma linha do tempo aleatória a linha do tempo principal
