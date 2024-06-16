# <p align="center">Arduino Genius</p>

## 🔹Descrição
>Basicamente, o jogo consiste em memorizar uma sequência de cores que irão piscar aleatoriamente. No início, apenas uma cor irá piscar, mas, a cada rodada, mais uma cor é adicionada a sequência, tornando cada vez mais difícil para o jogador guardar a ordem das cores.


<a align="center" p>
  <img width="550" src='https://raw.githubusercontent.com/Otto-Samuel/Arduino_Genius/main/genius_game.png'>
</p>

## 🔹Componentes
- Arduino Uno (ou equivalente)
- 4 LEDs (cores opcionais)
- 4 Botões
- Resistor de 220 ohms (para limitar a corrente dos LEDs)
- Breadboard (opcional, mas recomendado para prototipagem)
- 1 Buzzer

## 🔹Montagem
1. Conecte os LEDs aos pinos digitais do Arduino, através dos resistores de 220 ohms para limitar a corrente.
2. Conecte os botões a outros pinos digitais do Arduino.
3. Certifique-se de seguir o esquemático ou a descrição de pinagem no código fonte.

## 🔹Funcionamento
1. O jogo inicia com uma sequência aleatória de LEDs piscando.
2. O jogador deve repetir a sequência pressionando os botões correspondentes aos LEDs que piscaram.
3. Se o jogador errar a sequência, o jogo termina.
4. Se o jogador acertar, a sequência aumenta em complexidade.
5. O jogo continua até que o jogador erre a sequência.

## 🔹Contribuição
Contribuições são bem-vindas! Se você encontrar problemas ou tiver ideias para melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## 🧑‍💻 Autor
Este projeto foi desenvolvido por [otto samuel](https://github.com/Otto-Samuel) como um exemplo de aplicação prática do Arduino.

## Licença 📜
Este projeto é licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT) - veja o arquivo `LICENSE` para mais detalhes.
