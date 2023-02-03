Comandos do Git no Terminal:

git clone (link do repositório)
• Serve para clonar/armazenar todo o repositório postado na nuvem em seu computador

git log 
• Apresenta as alterações/commits feitos em detalhes para o usuário

git log --oneline (com o diretório do clone selecionado)
• Apresenta as alterações/commits feitos de uma forma mais simples e objetiva

git pull (com o diretório do clone selecionado)
• Sincroniza os dados do repositório local com o da nuvem, assim fazendo uma espécie de atualização

git restore --source (código de identificação do commit e qual arquivo deve ser 
restaurado [lembrando que o "." simboliza todos os arquivos do repositório])
• O git restore serve para retornar a um determinado período representado por um commit. Ou seja, com este comando, podemos retornar a versão do código commitada há 2 semanas atrás.