# cognitive

Explicação do código:
Caixa de Cores:

A cor é gerada aleatoriamente entre as opções definidas e exibida dentro de uma caixa (#colorBox). O nome da cor também aparece dentro da caixa.
A cor é mostrada por 5 segundos ou até que o paciente clique em uma das opções de resposta. Caso o paciente não clique até o tempo limite, é exibida uma mensagem dizendo "Tempo esgotado!".
Respostas:

O paciente pode clicar em um dos botões de cor (Vermelho, Verde, Azul ou Amarelo) para tentar adivinhar a cor mostrada.
Se a resposta estiver correta, aparece "Cor correta!" em verde, caso contrário, "Cor errada" é exibida com a cor correta em vermelho.
Controle de Tempo:

O tempo de 5 segundos é controlado com a função setTimeout. Caso o paciente clique no botão antes desse tempo, o clearTimeout é chamado para impedir que a mensagem de "Tempo esgotado!" apareça.
Se o paciente não clicar no botão dentro de 5 segundos, a cor é considerada errada, e o tempo se esgota.
Nova cor:

Após cada interação (seja correta ou não), o exercício é reiniciado automaticamente com uma nova cor.
Como funciona:
Ao carregar a página, a cor é mostrada por 5 segundos ou até que o paciente clique.
Após a interação, o sistema dá feedback se a resposta foi correta ou não e gera uma nova cor para o paciente tentar novamente.
