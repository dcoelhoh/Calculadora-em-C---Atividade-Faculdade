# Calculadora-em-C---Atividade-Faculdade
// Online C compiler to run C program online #include &lt;stdio.h> #include &lt;math.h>   int main()   {      printf("Diogo Henrique Marques Coelho\n\n");     printf("Aluno do curso Análise e Desenvolvimento de Sistemas do Unilasalle\n\n");     printf("Calculadora\nDigite:\n+ para soma\n- para subtração\n* para multiplicação\n/ para divisão\nr para raiz quadrada\np para potenciação\n\n");          char o;      printf("Operação: ");      scanf("%c", &amp;o);       if(o == '+')      {          float y1, y2, y3;          printf("Número inicial: ");          scanf("%f", &amp;y1);          printf("Mais...: ");          scanf("%f", &amp;y2);            y3 = y1 + y2;          printf("Resultado: %f\n", y3);      }      else if(o == '-')      {          float m1, m2, m3;          printf("Número inicial: ");          scanf("%f", &amp;m1);          printf("Menos...:");          scanf("%f", &amp;m2);            m3 = m1 - m2;          printf("Resultado: %f\n", m3);      }      else if(o == '*')      {          float v1, v2, v3;          printf("Número inicial: ");          scanf("%f", &amp;v1);          printf("Vezes...: ");          scanf("%f", &amp;v2);            v3 = v1 * v2;          printf("Resultado: %f\n", v3);      }      else if(o == '/')           {          float d1, d2, d3;          printf("Dividendo: ");          scanf("%f", &amp;d1);          printf("Divisor: ");          scanf("%f", &amp;d2);          d3 = d1 / d2;          printf("Resultado: %f\n", d3);      }          else if(o=='r')     {         float num, resultado;          printf("Número inicial: ");          scanf("%f", &amp;num);          resultado = sqrt (num);          printf("Resultado: %f\n", resultado);     }                    else if(o=='p')     {         float p1, p2, p3;                  printf("Número inicial: ");         scanf("%f", &amp;p1);                   printf("Número inicial: ");         scanf("%f", &amp;p2);                          p3 = pow (p1, p2);                 printf("Resultado: %f\n", p3);                       }     else      {      printf("Não é uma operação!");      }      return 0;  }
