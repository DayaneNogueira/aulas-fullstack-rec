HISTORICO DE COMANDOS UTILIZADOS NO GITBASH

eval "$(ssh-agent -s)" - Inicia o agente SSH e configura o ambiente para o uso de chaves SSH. 
A opção -s é usada para definir variáveis de ambiente de forma que o terminal reconheça o agente SSH.

ssh-add ~/.ssh/id_ed25519 - Adiciona a chave SSH localizada em ~/.ssh/id_ed25519 ao agente SSH para autenticação.

clip < ~/.ssh/id_ed25519.pub - Copia o conteúdo do arquivo ~/.ssh/id_ed25519.pub (chave pública SSH) para a área de transferência.

ls - Lista os arquivos e diretórios no diretório atual.

cd Desktop/ - Muda o diretório de trabalho para o diretório Desktop.

mkdir exemplo - Cria um novo diretório chamado exemplo.

cd exemplo/ - Muda o diretório de trabalho para o diretório exemplo.

ls -la - Lista todos os arquivos e diretórios no diretório atual, incluindo arquivos ocultos.

git init - Inicializa um novo repositório Git no diretório atual.

git status - Mostra o status atual do repositório Git, incluindo alterações não rastreadas e mudanças que foram feitas.

nano teste - Abre o editor de texto nano para criar ou editar um arquivo chamado teste.

nano teste.md - Abre o editor de texto nano para criar ou editar um arquivo chamado teste.md.

git add . - Adiciona todos os arquivos e mudanças no diretório atual ao índice do Git, preparando-os para o commit.

git rm --cached teste.md - Remove o arquivo teste.md do índice do Git, mas não do diretório de trabalho. Ou seja, o arquivo será desconsiderado em commits futuros.

git commit -m "meu primeiro commit" - Cria um novo commit com a mensagem "meu primeiro commit", contendo todas as mudanças que foram adicionadas ao índice.

git checkout -b dev - Cria um novo branch chamado dev e muda para ele.

git branch - Lista todos os branches do repositório e mostra o branch atual (dev).

nano teste2.md - Abre o editor de texto nano para criar ou editar um arquivo chamado teste2.md.

ls -ls - Lista os arquivos e diretórios no diretório atual com detalhes adicionais, incluindo tamanho dos arquivos em blocos.

git add . - Adiciona todos os arquivos e mudanças no diretório atual ao índice do Git, preparando-os para o commit.

git commit -m "meu segundo commit"  - Cria um novo commit com a mensagem "meu segundo commit", contendo todas as mudanças que foram adicionadas ao índice.

git checkout 'master' - Muda para o branch master.

git merge dev - Mescla as mudanças do branch dev no branch master.

git branch -d dev - Remove o branch dev localmente, se ele já tiver sido mesclado com o branch atual (no caso, master).

git branch - Lista todos os branches do repositório e mostra o branch atual, confirmando que o branch dev foi removido.

cd .. - Muda o diretório de trabalho para o diretório pai.

rm -rf exemplo/ - Remove o diretório exemplo e todo o seu conteúdo de forma recursiva e forçada.

git clone git@github.com:DayaneNogueira/portifolio.git - Clona o repositório Git do URL especificado

cd portifolio/ - Muda o diretório de trabalho para o diretório portifolio, que foi clonado do repositório Git.