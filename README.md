Consegui criar um código que apresenta uma mensagem sobre a hora do dia e altera o fundo da página, como a imagem com base na hora atual. 
Toda a aparência é estilizada com CSS, enquanto a funcionalidade é implementada com JavaScript.
Os códigos são os seguintes:  HTML Define o título da página como “Hora do dia” e inclui um cabeçalho.
com o título “Hora do dia”  CSS Define o fundo da página como a cor azul; também, ao mesmo tempo, a cor do texto obtém a cor branca. Além disso, a mensagem deve ser centralizada.
Define o fundo da seção como branco e aplica um raio de borda de 10 px. Adiciona preenchimento de 15 px ao conteúdo na seção.
Define a largura da seção como 500 px e centraliza a seção na página: JavaScript Pega a referência, Obtém a hora atual do computador, Atualiza o conteúdo do <div> com id "msg" para mostrar a hora atual, 
Se for entre 0 e 12 (manhã), muda a imagem correspondente, Se for entre 12 e 18 (tarde), muda a imagem correspondente, Se for entre 18 e 24 (noite), muda a imagem correspondente.
