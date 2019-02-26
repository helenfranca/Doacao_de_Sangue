# Doacao_de_Sangue
 ### Um serviço/app que convide a pessoa a doar sangue para o seu tipo específico

---------
- [Canvas do projeto](https://docs.google.com/drawings/d/1Jmqvl_LD88OZ8QNzajE3s6UOwYPANk9HTlujOv_FtAw/edit)
 
Rascunho

A pessoa informa seus dados como nome, e-mail, tipo e fator sanguíneo, se já realizou alguma doação e quando foi a última vez. Na parte do Hemocentro alguém será responsável por atualizar as informações no sistema sobre o atual nível de abastecimento do banco de sangue, sendo assim a pessoa terá que fazer um cadastro com as informações relevantes. Informando o tipo sanguíneo e com informações do banco de sangue do Hemocentro o sistema fará enviará uma notificação ao possível doador. Essa notificação será através da geolocalização, que ao localizar a pessoa verificará o Hemocentro mais próximo a ela, daí no caso de estar viajando seria possível indicá-la um banco de doação mais perto de onde está hospedada ou de passagem na cidade.

- Lembrete de doações para que a pessoa se torne um doador regular
- Informações importantes como como cuidar da saúde para ser um doador ou como cuidar para continuar sendo; pessoas que não podem doar e o porque.. 
- Possibilidade de montar grupos de doadores

Plus - Gameficação com base em pontuação
- Para estimular a participação das pessoas poderia funcionar como um jogo. A pessoa ganharia "tuntuns" - pontos a cada doação que poderia trocar por um brinde ou cupons de desconto de parceiros. Ranking dos doadores regulares. Indicando alguém e esse alguém comparecendo a doação poderia gerar pontos para quem indicou e para o próprio doador.

-------
Similares e referências

- Web e App [Hemoliga](http://hemoliga.com.br/) <br>
- App [Partiu Doar Sangue](https://play.google.com/store/apps/details?id=com.ionicframework.app190851)
- [Portal do governo](http://portalms.saude.gov.br/saude-de-a-z/doacao-de-sangue)
-------

### Definição do Escopo

#### Tipo de Requisitos<br>

| Funcionais | Prioridades (MoSCoW)|
|---------|---------|
| O sistema deve notificar ao doador o hemocentro mais próximo para que aconteça a doação |         |
| O sistema deve permitir ao doador deve realizar cadastro com dados básicos como nome completo, data de nascimento, email, tipo e fator sanguíneo, peso, se já realizou alguma doação e quando foi a última vez.|         |
| O sistema deve permitir o cadastro do hemocentro |         |
| O sistema deve permitir o reconhecimento/confirmação da doação        |         |
| O sistema deve permitir o doador pesquisar o hemocentro mais próximo      |         |
|  O sistema deve informar quando o doador está apto para doar        |         |
|  O possível doador deve permitir que o sistema tenha acesso a sua localização (GPS)       |         |
|         |         |


| Não Funcionais | Prioridades (MoSCoW)|
|---------|---------|
|  O possível doador deverá ser notificado por meio de web push notification / push notification / email.       |         |
|   O sistema deve funcionar em plataformas web e mobile       |         |
|   O sistema deve ser integrado com o serviço de mapas (Ex: Google Maps)      |         |
|         |         |


| Regras de Negócio |
|---------|
|O doador só poderá repetir a doação a cada 60 dias para homens e 90 dias para mulher. Entretanto, recomenda-se que o homem doe até 4 vezes por ano e a mulher até 3 vezes por ano.|
|O doador deve ter no mínimo de 50kg.|
|O doador deve ter idade entre 16 e 69 anos, desde que a primeira doação tenha sido feita até 60 anos.|
|         |


<br><br>Critérios: 
(É claro? É objetivo? É testável? Está padronizado? Não é ambíguo? Não é conflitante? É inucamente identificado?)

