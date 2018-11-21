# Trabalho2
Passo 1 <br/>
Antes de tudo, certifique-se que você tem o python 3.6  instalado em seu computador e se está utilizando o sistema operacional Windows. Depois de ter feito o clone do repositório ou baixado os arquivos no formato .ZIP(extraia os arquivos em  alguma parte do seu computador) e siga os passos seguintes.<br/>
Passo 2<br/>
Você deverá ver dois arquivos: um cujo nome é “main.py” e outro com o nome de “veiculo.py”. Para iniciar o programa, antes de tudo você deve abrir o IDLE, aberto o IDLE, clique em “file” no canto superior esquerdo e clique na opção “open”, então você deve ir na parte onde você guardou os arquivos baixado e o abra o arquivo “main.py” selecionando-o com um clique e acionando enter. Agora basta executar esse arquivo apertando F5 ou clicando em “run” na parte superior e na opção Run Module<br/>
Passo 3<br/>
Iniciará a tela principal do programa com as opções de tarefas que você deseja que o programa realize. Para cadastrar veículos ao sistema, digite o comando 2 na parte inferior onde é solicitado e pressione enter, após isso, será solicitado a marca do veículo, digite a marca do veículo e dê um enter, então será solicitado o modelo do veículo, digite o modelo e novamente enter, logo após isso também será solicitado o ano, digite o ano e enter, depois digite o valor e enter. Pronto, veículo cadastrado.<br/>
Passo 4<br/>
Para verificar quais veículos estão cadastrados no sistema e se existe veículos disponíveis, reservados ou alugados deve-se digitar o comando 1 e pressionar enter, depois disso aparecerá a lista dos veículos cadastrados com informações sobre o código do veículo, o modelo e se está disponível, alugado ou reservado. Então você pode digitar ‘s’ e pressionar enter para ver mais detalhes sobre os veículos cadastrados, como informações sobre marca, ano e valor, ou você pode digitar ‘n’ e pressionar enter para voltar a tela principal.<br/>
Passo 5<br/>
Para alugar ou reservar algum veículo, digitamos o comando 3 na tela principal e pressionamos enter. Após isso, você deve digitar o código do veiculo que você deseja alugar ou reservar e pressione enter, depois disso digite o nome do locatário e pressione enter, agora você deve ter cuidado ao passar a data que você deseja reservar o veículo, para isso você deve digitar os algarismos do dia da data(com dois algarismo) , do mês da data desejada(com dois algarismos) e o ano da data desejada(com dois algarismo) todos separados por ‘/’ e sem espaços. Por exemplo, se você for reservar para data 2 de janeiro de 2019, você digitar dessa forma: 02/01/2019. Agora digite o prazo que você deseja passar com o veículo, pressione enter e sua reserva está finalizada. Atenção: reservas somente poderão ser realizadas para no máximo 30 dias adiante (considerando a “data atual”) e se um mesmo veículo estiver reservado, por exemplo, para os dias 04, 05 e 06, e um cliente deseja alugar no dia 03 (do mesmo mês/ano) por 2 dias, esse módulo deve indicar que há sobreposição de datas e deve ser escolhido outro carro ou outra data, retornando ao início do módulo.

Passo 6<br/>
Para devolver algum veiculo alugado ou liberado, digite na tela principal do programa o comando 4 e pressione enter, após isso aparecerá uma lista dos veículos alugados/reservado com algumas informações, então será solicitado que você digite o código do veículo que deseja liberar/devolver e pressione enter. Caso o veículo estiver atrasado, aparecerá informações sobre o atraso e sobre o preço a ser pago, se simplesmente não for devolução e sim liberação de reserva aparecerá uma mensagem confirmando que a reserva foi liberada.

Passo 7<br/>
Para excluir algum do veículo do sistema você digita o comando 5 na tela principal e pressione enter. Então será solicitado o código do veículo que se deseja excluir do sistema. Lembrando que se o veiculo desejado possuir reservas, o sistema não realizará a exclusão e notificará com uma mensagem de erro, se o veiculo não possuir reservar, então o sistema notificará com uma mensagem de ação realizada com sucesso.

Passo 8<br/>
Para verificar o funcionamento do sistema você pode avançar a data em um dia, basta digitar o comando 6 e pressionar enter. Repita isso igual ao número de dias que deseja avançar.

Passo 9<br/>
Para finalizar o programa, digite o comando 7 na tela principal e acione enter


