**descrição telas e componentes:**

 
 1. App -> renderiza minhas rotas   

2. Components -> guarda os componentes a serem reutilizados.

- Pasta Botao: guarda estilos e um componente Botao que é um
TouchableOpacity rodeando uma tag text e recebe alguns parametros para estilização.

- Pasta CampoInteiro: é um text input personalizado que vai formatar os valores recebidos retirando os caracteres indesejados e o zero esquerdo.  

- Pasta StatusCarrinho: mostra a parte superior da area do carrinho com total  do valor e o KeyboardAvoidingView permite que o teclado não atrapalhe o conteúdo. 

- Tela padrão: renderiza o SafeAreaView da barar de notificações e da navegação e configura o teclado para não  


- Pasta Item e index:  *tem um campo tocavel que mostra o nome descricao e o valor ao tocar é disparado um complemento que mostraa quantidade com o function component CampoInteiro e mostra a quantidade total.
Tem a função que calculaTotal pega o valor e multiplica pelo preço.
Contém a função  atualizaQuantidadeTotal que recebe a quantidade e usa a função de CalculaTotal para atualizar o valor.
e contém a função que vai permitir visualizar o resto da view por meio do toque*

3. Telas 
  
- Pasta Serviços  index:  reutiliza o componente TelaPadrao e renderiza uma flatList com o item
	- item : contém um TouchableOpacity  com tags Text e que informam dados dos produtos,  e um camo que ao expandir revela o input de quantidade o valor total e um botão adicionar ao carrinho

- Pasta Carrinho e index:  redenriza a a flatlist dos items com status do carrinho envolta com o componente TelaPadrao  e uma ScrollView.
  - item: mostra meus items do carrinho e rederiza o botão removerdo carrinho.
