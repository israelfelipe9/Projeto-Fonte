# **Projeto Fonte de Tensão**
## **SCC0180 - Eletrônica para a Computação - Prof. Simões** [GitHub](https://github.com/simoesusp)

# **Descrição:**
O projeto tem como objetivo a elaboração de uma fonte eletrôncia que seja capaz de a partir de uma tomada comum que possui tensão de 127V a 60 Hz, obter uma tensão que possa variar entre 3V-12V com uma corrente próxima a 100mA.

| **Componente** | **Justificativa** | 
|:---|---|
| Transformador | O transformador foi usado para modificar o nível de tensão de 127V CA para um valor próximo a 17V CA, dessa forma, obtemos uma tensão mais próxima de 3V-12V |
| 4 x Diodo | Os diodos foram usados para a formação de uma ponte retificadora(ponte de diodos), que tem como objetivo aproveitar o máximo do ciclo de tensão e, dessa forma, transformar a tensão de alternada para contínua |
| Capacitor | O objetivo do capacitor é armazenar carga, para durante as oscilações de tensão ele fornecer uma corrente necessária para manter o circuito em funcionamento |
| Diodo Zener | O diodo zener sendo um regulador de tensão, é utilizado para limitar a tensão que será obtida a partir dele, se a tensão de entrada for maior que a tensão zener, a tensão de saída será a tensão zener, caso contrário nada ocorrerá, logo, no projeto ele foi utilizado para prover ao circuito uma tensão final constante e superior a 12V |
## **Desenvolvido por:**
Israel Felipe da Silva - Nro. USP: 11796531
