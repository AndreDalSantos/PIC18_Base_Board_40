# Placa PIC18F_Base_40_pinos

<h1 align="center">
    <img src="image_board.png" alt="Imagem Placa" title="Vista da placa" />
</h1>

## Sobre

A Placa PIC18F_Base_40_pinos foi desenvolvida utilizando o Software **Kicad** para criação de esquemáticos e layouts de PCB's. Tem como objetivo auxiliar nos projetos que usam microcontroladores de 8 bits da familia PIC18F DIP de 40 pinos como por exemplo o PIC18F4620 ou o PIC18F4550.

---

## Características
- 8 leds onboard ligados no PORTD.
- 4 botões N/A ligados em PORTB0, PORTB1, PORTB2 e PORTB3.
- 2 trimpots ligados nas portas analógicas PORTA0 e PORTA1.
- Barras de pinos para cada PORT (A, B, C, D e E) totalizando 36 I/O's.
- DIP Switchs para desacoplamento elétrico dos leds, botões e trimpots do MCU caso usar estes pinos para outras funções.
- Alimentação por fonte externa (7,5V - 20V) com conector P4, possuí regulador 7805 para 5V ou, pode ser alimentada diretamente em 5V pelos pinos +5VDC e GND.
- Cristal oscilador de 20 MHz podendo este ser desacoplado elétricamente pela DIP Switch para utilização do oscilador interno do MCU.
- Botão de reset.
- A gravação pode ser feita pelo PICKIT da Microchip através dos pinos do ICSP.

---

## Como baixar o projeto

No canto superior direito da página clicar em **Code** 
<h3 align="center">
    <img src="baixar_github1.png">
</h3>

Depois clicar em download ZIP para baixar o projeto compactado
<h3 align="center">
    <img src="baixar_github2.png">
</h3>

### OBS: Deve ter instalado o [Kicad](https://www.kicad.org/download/) no computador para abrir o projeto
---

<h3 align="center">
    <img src="image_top_view.png">
    <a>Vista do layer top</a>
</h3>

---

<h3 align="center">
    <img src="image_bottom_view.png">
    <a>Vista do layer bottom</a>
</h3>

---