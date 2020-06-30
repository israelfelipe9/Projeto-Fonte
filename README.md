# **Projeto Fonte de Tensão**
## **SCC0180 - Eletrônica para a Computação - Prof. Simões** [GitHub](https://github.com/simoesusp)

# **Descrição:**
O projeto tem como objetivo a elaboração de uma fonte eletrôncia que seja capaz de a partir de uma tomada comum que possui tensão de 127V a 60 Hz, obter uma tensão que possa variar entre 3V-12V com uma corrente próxima a 100mA.

| **Componente** | **Justificativa** | 
|:---|---|
| Transformador | O transformador foi usado para modificar o nível de tensão de 127V CA para um valor próximo a 17V CA, dessa forma, obtemos uma tensão mais próxima de 3V-12V |
| 4 x Diodo | Os diodos foram usados para a formação de uma ponte retificadora(ponte de diodos), que tem como objetivo aproveitar o máximo do ciclo de tensão e, dessa forma, transformar a tensão de alternada para contínua |
| Capacitor | O objetivo do capacitor é armazenar carga, para durante as oscilações de tensão ele fornecer uma corrente necessária para manter o circuito em funcionamento |
| Diodo Zener | O diodo zener sendo um regulador de tensão, é utilizado para limitar a tensão que será obtida a partir dele, se a tensão de entrada for maior que a tensão zener, a tensão de saída será a tensão zener, caso contrário nada ocorrerá, logo, no projeto ele foi utilizado para prover ao circuito uma tensão final constante e proxima de 12V |
| Resistor ... | Este resistor foi utilizado para limitar a corrente que passará pelo diodo zener, visto que, quando ele estiver em funcionamento (com tensão de entrada superior a tensão zener) ele se tornará uma espécie de curto circuito, além disso, ele foi utilizado para garantir a menor perca possível de energia e também para limitar o valor da corrente de base do transistor NPN |
| Resistor ... | Este resistor ajuda limitar a tensão do potenciômetro, para garantir que exista uma tensão de pelo menos 3V fornecida ao transistor |
| Potenciômetro | Permite alternar a tensão de saída para um valor entre 3V-12V |
| Transistor NPN | O transistor NPN foi utilizado para de maneira mútua conseguir aproveitar a tensão de saída do potenciômetro (-0.7V entre a base e o emissor) com uma corrente amplificada e definida pelo produto da corrente de base com o ganho estático de corrente (beta ou hFE) |
## **Desenvolvido por:**
Israel Felipe da Silva - Nro. USP: 11796531
