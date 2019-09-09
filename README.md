# ivory-teste-estagio-setembro-2019

Questão 1: Bem trata-se de uma aplicação que efetua o cálculo fatorial de um número (no casa o número 5). Algumas sugestões que eu daria, seria tirar o "static" da função recursiva : calcular. Já que por ela ser uma função que próprio se chama ( recursiva ) e se altera, ela não pode ser inalterável. Outra sugestão seria colocar a função dentro de uma classe, o que no caso padronizaria a aplicação, porém, por ser um tanto quanto pequena não sei se seria tanto viável assim.

using System;

namespace TesteProvaIvory
{
    class Program
    {
        static void Main(string[] args)
        {
            int resultado, numero = 5;
            resultado = calcular(numero);

            Console.WriteLine("Resultado: {0}", resultado);
            Console.ReadKey();

           int calcular(int numer)
            {
                int resultad;

                if (numero <= 1)
                {
                    return (1);
                }
                else
                {
                    resultad = numero * calcular(numero --);
                    return resultad;

                }


                }

            }
        }
    }

Questão 2: infelizmente não consegui mensurar uma solução para o desafio, tentei de varias maneiras(Vídeos, fóruns, conversar com pessoas mais experientes, etc.) solucionar o problema, mais não consegui soluciona-lo. Bem, tive até mesmo oportunidade de enviar um código enviado por um professor, mas acredito que a ivory precisa do meu conhecimento e não de outro. Desde ja agradeço pela oportunidade.
