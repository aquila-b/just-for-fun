# just-for-fun
Hey, take a look at the game system I created in Dart! The game is: Rock, paper and scissors! I'm still a beginner in this language :) 
This code is also subtitled in portuguese.


void main() { // função principal/main function
 
  // ROCK, PAPER AND SCISSORS IN CODE! || PEDRA , PAPEL E TESOURA NO CÓDIGO!!
  
  var hand1 = 'rock';
  var hand2 = 'scissor'; // VARIÁVEIS || VARIABLES

  
    // PAPER AND SCISSORS BELOW || PAPEL E TESOURA ABAIXO

  if(hand1 == 'scissor' && hand2 == 'paper') {
    print('hand1 won.');
  }
  else if (hand1 == 'paper' && hand2 == 'scissor') {
    print('hand2 won.');
  }
    // PAPER AND SCISSORS ABOVE || PAPEL E TESOURA ACIMA


    // PAPER AND ROCK BELOW || PAPEL E PEDRA ABAIXO


  else if (hand1 == 'paper' && hand2 == 'rock') {
    print('hand1 won.');
  }
  else if (hand1 == 'rock' && hand2 == 'paper') {
    print('hand2 won.');
  }


    // PAPER AND ROCK ABOVE || PAPEL E PEDRA ACIMA
  
    
    // ROCK AND SCISSORS BELOW || PEDRA E TESOURA ABAIXO


  else if (hand1 == 'rock' && hand2 == 'scissor') {
    print('hand1 won.');
  }
  else if (hand1 == 'scissor' && hand2 == 'rock') {
    print('hand2 won.');
  }


    // ROCK AND SCISSORS ABOVE || PEDRA E TESOURA ACIMA
  
  
  else {
    print('try again.');
  }
  

}
