// Online C compiler to run C program online

/* github: dcoelhoh
Não consegui realizar as operações conjuntas em 1 e 2, então tive que fazer tudo bem "Manual". As referências utilizadas foram as aulas interativas 2.1 e em diante, além do ebook e de alguns conhecimentos prévios básicos na linguagem, como a questão de fazer a raiz quadrada e o uso do pow para potenciação*/

#include <stdio.h>
#include <math.h>


int main()


{

    printf("Diogo Henrique Marques Coelho\n\n");
    printf("Aluno do curso Análise e Desenvolvimento de Sistemas do Unilasalle\n\n");
    printf("Calculadora\nDigite:\n+ para soma\n- para subtração\n* para multiplicação\n/ para divisão\nr para raiz quadrada\np para potenciação\n\n");
    
    char o;

    printf("Operação: ");

    scanf("%c", &o);


    if(o == '+')

    {

        float y1, y2, y3;

        printf("Número inicial: ");

        scanf("%f", &y1);

        printf("Mais...: ");

        scanf("%f", &y2);



        y3 = y1 + y2;

        printf("Resultado: %f\n", y3);

    }

    else if(o == '-')

    {

        float m1, m2, m3;

        printf("Número inicial: ");

        scanf("%f", &m1);

        printf("Menos...:");

        scanf("%f", &m2);



        m3 = m1 - m2;

        printf("Resultado: %f\n", m3);

    }

    else if(o == '*')

    {

        float v1, v2, v3;

        printf("Número inicial: ");

        scanf("%f", &v1);

        printf("Vezes...: ");

        scanf("%f", &v2);



        v3 = v1 * v2;

        printf("Resultado: %f\n", v3);

    }

    else if(o == '/')
    

    {

        float d1, d2, d3;

        printf("Dividendo: ");

        scanf("%f", &d1);

        printf("Divisor: ");

        scanf("%f", &d2);

        d3 = d1 / d2;

        printf("Resultado: %f\n", d3);

    }
    
    else if(o=='r')
    {
        float num, resultado;

        printf("Número inicial: ");

        scanf("%f", &num);

        resultado = sqrt (num);

        printf("Resultado: %f\n", resultado);
    }

        
         else if(o=='p')
    {
        float p1, p2, p3;
        
        printf("Número inicial: ");
        scanf("%f", &p1);
        
         printf("Número inicial: ");
        scanf("%f", &p2);
        
        
       p3 = pow (p1, p2);
       
        printf("Resultado: %f\n", p3);
        
        
    }
    else

    {

    printf("Não é uma operação!");

    }

    return 0;

}
