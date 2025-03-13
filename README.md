# Amigo-secreto
Este projeto é um dos desafios do Curso de Lógica de Programação do Programa One Oracle next education, cujo o objetivo é aplicar a Linguagem Java Script, possibilitando adicionar nomes a uma lista de amigos e realizar um sorteio entre esses nomes para que um acabe sendo escolhido de forma aleatória

COMO EXECUTAR O PROJETO
- Há um campo de texto na interface, qual você irá digitar o nome de um amigo
- Clique no botão "Adicionar amigo" para incluir o nome que você deseja na lista
- No campo abaixo, vai ser exibida a lista com todos os amigos que foram adicionados
- Quando terminar de adicionar, clique no botão "Sortear Amigo" para escolher aleatoriamente um dos nomes da lista
- O nome sorteado será exibido na tela

COMO O JAVA SCRIPT FUNCIONA
Uma explicação básica dos principais trechos do código:
- Array amigos[]: Guarda todos os nomes que foram adicionados
- adicionarAmigo():
  Vai pegar o valor digitado no input e verificar se algum nome foi digitado, se não, vai exibir um alerta
  Adiciona o nome ao array amigos[]
  Limpa o campo de input e mantém o foco nele
  Chama a função atualizarLista()
- atualizarLista():
  Limpa a lista no HTML
  Cria um elemento <li> para cada nome do array amigos[] e exibe na lista
- sortearAmigo():
  Verifica se há nomes na lista; senão, exibe um alerta
  Sorteia um nome aleatório usando Math.random() e Math.floor()
  Exibe o nome que foi sorteado
  Limpa a lista de amigos após o sorteio
