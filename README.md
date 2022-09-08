# dx-gameworks-techinical-test
Teste técnico para a Dx Gameworks utilizando blueprints na Unreal Engine 5 

## Implementação principal :books:
 - O jogador deve poder controlar a movimentação do personagem do FirstPerson por WASD e atirar com o botão esquerdo do mouse. O personagem do jogador também deve implementar um feature de vida com valor configurável e um valor configurável de dano do tiro. A HUD deve mostrar uma barra de vida do jogador.
 - Deve existir no cenário também um inimigo (dummy “2D”) que se movimenta de forma não previsível em apenas um eixo do mundo e não gira, não precisando se portar de maneira inteligente, que atire de volta no jogador em uma frequência configurável. O inimigo deve implementar um feature de vida e dano com valores configuráveis também, a vida de um inimigo deve ser demonstrada por uma barra de vida logo acima do inimigo.
 - O inimigo não deve atirar quando o jogador se posiciona atrás do inimigo, e o inimigo também deve tomar mais dano quando o tiro é recebido por trás.
 - Quando o jogador leva um tiro, ele deve ser empurrado um pouco de acordo com a direção do tiro. O inimigo não deve receber esse empurrão quando tomar um tiro. Uma partícula deve ser ativada quando um tiro é recebido, tanto pelo jogador como pelo inimigo.

 - Efeito de Stun: Quando o inimigo ou jogador recebem um tiro, aquele que recebeu o tiro deve entrar em um estado onde será incapacitado de atirar novamente por um certo tempo. Durante esse tempo o afetado também não pode receber novos danos. Após o termino desse tempo, deve existir um novo período de tempo (configurável) de invulnerabilidade a Stun, dentro deste período o afetado receberá dano de novos tiros mas não receberá o efeito de stun.

 - Pontuação: O jogador deve ganhar 10 pontos a cada tiro que ele acerta no inimigo, e perder 5 pontos por cada tiro que ele recebe. Os pontos devem ser mostrados na HUD. Os pontos devem ser sempre ≥ 0. 

 - Quando a vida chega a zero, seja no personagem do jogador ou no inimigo, o personagem deve entrar em estado de “morto” e não deve mais poder atirar. Não deve ser possível sair desse estado sem recomeçar o jogo.

 - No level deve existir um estande com uma alavanca, quando o jogador sobe no estande o botão de tiro deve parar de atirar e passar a interagir com a alavanca, que pode ser ativada de um lado para o outro. Quando isso é feito o inimigo deve mudar de cor no material. 
