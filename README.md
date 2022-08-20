# Algoritmo de PID

## O que é?
* Este é uma Algoritmo básico de PID genérico desenvolvido por Rafael Farias Meneses para utilização geral.
* Escrito em C++ deve ser criado um objeto da classe ``Pid``.

## Utilização
Ao criar um objeto da classe PID deve ser passado as constantes de P, I e D
~~~ C++
// Pid(double k_p, double k_i, double k_d);
Pid pid1(0.5, 0.000001, 0.1);
~~~

Função membro disponivel, deve ser passado o erro, e será retornado o resultado calculado:
~~~ C++
double calculate(double error);
~~~

> O feedback loop já está sendo automaticamente operado pelo objeto.

O exemplos de utilizações pode ser encontrado em: [https://github.com/RafaelFariasUTFPR/GenericPid/tree/main/examples](https://github.com/RafaelFariasUTFPR/GenericPid/tree/main/examples)
