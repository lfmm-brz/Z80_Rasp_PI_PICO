Emulação do Z80 e CP/M80 usando o Raspberry PI PICO

Para os que querem relembrar ou aprender sobre o Z80 e não querem investir valores altos, esta é uma solução muito boa e barata.
A descrição deste ótimo trabalho está aqui https://www.extremeelectronics.co.uk/the-rc2040/ 
O projeto completo está aqui https://github.com/ExtremeElectronics/RC2040
Fiz um resumo aqui https://github.com/lfmm-brz/Z80_Rasp_PI_PICO
Tudo é muito simples, conectar alguns fios, fazer o upload de alguns arquivos, configurar o emulador de terminais e pronto.
No primeiro teste usei somente o Pi Pico e o módulo SD Card, sem jumpers e sem micro switches, funcionou perfeitamente.

Temos o programa monitor que é o Small Computer Monitor, BASIC e CP/M. Também temos uma porta de 8 bits (GPIO16, GPIO17, GPIO18, GPIO19, GPIO20, GPIO21, GPIO26, GPIO27).
