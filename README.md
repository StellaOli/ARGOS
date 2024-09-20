# ARGOS

Construindo um software que auxilia juizes em diversos esportes. 

## Processo
  1.	Processo de análise e revisão da partida
  2.	Processo de gerar feedback

-	Detalhamento das tarefas do processo de análise/revisão humana 
Processo de análise e revisão da partida: Quando começar a partida, o juiz deve inicializar o programa, em que terá a computação gráfica da partida em tempo real. O Juiz da partida pode pedir revisão ou análise gráfica de uma determinada ação dentro do jogo.

- 1. Nome da Tarefa:	Início da partida. </br>
     Dados de entrada:	Juiz aperta um botão no apito. </br>
     Detalhamento do passo a passo da tarefa:	O botão envia um sinal para o sistema. </br>
     Dados de Saída:	O sistema inicia. </br>


- 2. Nome da Tarefa:	Gravação e Análise da partida. </br>
Dados de entrada:	Imagens adquiridas pelo sistema. </br>
Detalhamento do passo a passo da tarefa:	O sistema analisa a partida e procura por anomalias. </br>
Dados de Saída:	Mensagem de aviso. </br>


- 3. Nome da Tarefa:	Análise sobre a gravação.</br>
Dados de entrada:	Imagens fornecidas pelo sistema.</br>
Detalhamento do passo a passo da tarefa:	O juiz analisa o que o sistema apontou como uma quebra de regra e toma sua decisão.</br>
Dados de Saída:	Feedback para o sistema dizendo se a notificação veio com informação correta.</br>


- 4. Nome da Tarefa: Salvar o Feedback </br>
Dados de entrada	Mensagem enviada pelo juiz. </br>
Detalhamento do passo a passo da tarefa:	O sistema salva a mensagem para calcular sua taxa de acerto e melhorar suas análises. </br>
Dados de Saída:	Pergunta se a partida terminou. </br>


- 5. Nome da Tarefa: Fim da partida. </br>
Dados de entrada	Juiz finaliza a partida. </br>
Detalhamento do passo a passo da tarefa:	A partida acaba e uma notificação é enviada. </br>
Dados de Saída:	Notificação avisando o sistema do término. </br>



- Processo de gerar feedback: O aplicativo iniciará após a sua inicialização junto com a partida. O aplicativo terá a função de salvar em sua memória e analisar as ações dos jogadores para que tudo ocorra dentro das regras do esporte. Além disso, o aplicativo pode ser acessado pelo juiz por decisão própria ou, caso ocorra uma situação que não foi notificada, mas algum atleta pediu para o juiz que analise. Após o juiz analisar a ação, o mesmo deve advertir aos atletas e público presente sobre a decisão tomada.

 - 6. Nome da Tarefa:	Início da Partida </br>
  Dados de entrada:	Árbitro aperta um botão no apito </br>
  Detalhamento do passo a passo da tarefa:	Árbitro inicia a partida, o computador recebe a informação que deverá inicializar a gravação </br>
  Dados de Saída:	Inicialização do programa </br>




- 7. Nome da Tarefa:	Gravação e análise da partida </br>
  Dados de entrada:	Imagens adquiridas pelo sistema. </br>
  Detalhamento do passo a passo da tarefa:	O sistema analisa a partida e procura por anomalias. </br>
  Dados de Saída:	Mensagem de aviso. </br>

- 8. Nome da Tarefa:	Pedido de revisão de imagem </br>
  Dados de entrada:	Dados da imagem solicitada </br>
  Detalhamento do passo a passo da tarefa:	O juiz vai pedir as gravações e análises do computador de uma ação específica </br>
  Dados de Saída:	O sistema retorna as imagens </br>

 - 9. Nome da Tarefa: Solicita revisão </br>
  Dados de entrada	O capitão de um dos times pede revisão de uma ação </br>
  Detalhamento do passo a passo da tarefa:	Após alguma jogada, o capitão de um time pode pedir para o árbitro revisar a jogada. </br>
  Dados de Saída:	O juiz vai revisar a jogada </br>


- 10. Nome da Tarefa:	Enviar imagem </br>
  Dados de entrada:	O computador vai receber a ordem do juiz para enviar as imagens </br>
  Detalhamento do passo a passo da tarefa:	O computador vai receber a ordem do juiz, e vai analisar a ação em específico, e depois enviá-las para o árbitro </br>
  Dados de Saída:	O programa vai enviar as imagens e análises da jogada para o árbitro </br>

- 11. Nome da Tarefa: Tomada de decisão  </br>
  Dados de entrada	Análise humana da jogada </br>
  Detalhamento do passo a passo da tarefa:	Após o pedido do juiz ou do capitão e o programa analisar a jogada, o árbitro deve tomar uma decisão em cima da jogada. </br>
  Dados de Saída:	O árbitro mostra a todos a sua decisão sobre a jogada </br>


- 12. Nome da Tarefa: Final da partida </br>
Dados de entrada:	A partida é finalizada </br>
Detalhamento do passo a passo da tarefa:	O juiz apita e termina o processo do programa, em que finaliza a partida </br>
Dados de Saída:	O jogo termina </br>


## Modelagem
  
<div align = "middle">
 
Análise e revisão da partida

<img src="https://github.com/StellaOli/ARGOS/blob/main/Argos/analise.png">

</div>

<div align = "middle">
 
Geração de Feedback

<img src="https://github.com/StellaOli/ARGOS/blob/main/Argos/feedback.png">

</div>


