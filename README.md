/* 
Autor: Caio Felipe
Data da criação:  18/05/24
Versão: v1.0
*/

#include <stdio.h>

int main()
{
     char a1, a2, a3, a4, a5;    //alunos
    float p1, p2, p3, p4, p5;   // notas em portugues
    float m1, m2, m3, m4, m5;   // notas em Matematica
    float g1, g2, g3, g4, g5;   // notas em Geografia
    float c1, c2, c3, c4, c5;   // notas em ciencias
    // nt = nota total
    
    
    // ALUNO 1
    printf ("Digite o nome do 1° aluno: ");
    scanf ("%s", &a1);
    printf ("Nota em portugues: ");
    scanf ("%f", &p1);
    if (p1 > 10) {
printf ("ERRO NA NOTA!! \n\n");
}
    printf ("Nota em Matematica: ");
    scanf ("%f", &m1);
    if (m1 > 10) {
printf ("ERRO NA NOTA!! \n\n");
}
    printf ("Nota em Geografia: ");
    scanf ("%f", &g1);
    if (g1 > 10) {
printf ("ERRO NA NOTA!! \n\n");
}
    printf ("Nota em Ciencias: ");
    scanf ("%f", &c1);
    if (c1 > 10) {
printf ("ERRO NA NOTA!! \n\n");
}
    float nt1 = p1 + m1 + g1 + c1;
    printf ("Nota total: %.2f \n", nt1);
    float Ma1 = (p1 + m1 + g1 + c1) /4;
    printf ("Média aritmetica: %.2f \n\n", Ma1);
    
    
    if (Ma1 >= 6) {
        printf ("Aprovado!! \n \n \n");
    }
    else if (Ma1 >= 4 && Ma1 < 6){
        printf ("Recuperação \n \n \n");
    }
    else if (Ma1 < 4) {
        printf ("Reprovado \n \n \n");
    }
    
    
    
    //ALUNO 2
    printf ("Digite o nome do 2° aluno: ");
    scanf ("%s", &a2);
    printf ("Nota em portugues: ");
    scanf ("%f", &p2);
    if (p2 > 10) {
printf ("ERRO NA NOTA!! \n\n");
}
    printf ("Nota em Matematica: ");
    scanf ("%f", &m2);
    if (m2 > 10) {
printf ("ERRO NA NOTA!! \n\n");
}
    printf ("Nota em Geogrfia: ");
    scanf ("%f", &g2);
    if (g2 > 10) {
printf ("ERRO NA NOTA!! \n\n");
}
    printf ("Nota em Ciencias: ");
    scanf ("%f", &c2);
    if (c2 > 10) {
printf ("ERRO NA NOTA!! \n\n");
}
    float nt2 = p2 + m2 + g2 + c2;
    printf ("Nota total: %.2f \n", nt2);
    float Ma2 = (p2 + m2 + g2 + c2) /4;
    printf ("Média aritmetica: %.2f \n\n", Ma2);
    if (p2, m2, g2, c2 > 10) {
printf ("ERRO NAS NOTAS... \n\n");
}
    
    if (Ma2 > 6) {
        printf ("Aprovado!! \n \n \n");
    }
    else if (Ma2 >= 4 && Ma2 < 6){
        printf ("Recuperação \n \n \n");
    }
    else if (Ma2 < 4) {
        printf ("Reprovado \n \n \n");
    }
    
    
    
    //ALUNO 3
    printf ("Digite o nome do 3° aluno: ");
    scanf ("%s", &a3);
    printf ("Nota em portugues: ");
    scanf ("%f", &p3);
    if (p3 > 10) {
printf ("ERRO NA NOTA!! \n\n");
}
    printf ("Nota em Matematica: ");
    scanf ("%f", &m3);
    if (m3 > 10) {
printf ("ERRO NA NOTA!! \n\n");
}
    printf ("Nota em Geografia: ");
    scanf ("%f", &g3);
    if (g3 > 10) {
printf ("ERRO NA NOTA!! \n\n");
}
    printf ("Nota em Ciencias: ");
    scanf ("%f", &c3);
    if (g3 > 10) {
printf ("ERRO NA NOTA!! \n\n");
}
    float nt3 = p3 + m3 + g3 + c3;
    printf ("Nota total: %.2f\n", nt3);
    float Ma3 = (p3 + m3 + g3 + c3) /4;
    printf ("Média aritmetica: %.2f \n\n", Ma3);
    if (p3, m3, g3, c3 > 10) {
printf ("ERRO NAS NOTAS... \n\n");
}
    
    if (Ma3 > 6) {
        printf ("Aprovado!! \n \n \n");
    }
    else if (Ma3 >= 4 && Ma3 < 6){
        printf ("Recuperação \n \n \n");
    }
    else if (Ma3 < 4) {
        printf ("Reprovado \n \n \n");
    }
    
    
    
    //ALUNO 4
    printf ("Digite o nome do 4° aluno: ");
    scanf ("%s", &a4);
    printf ("Nota em portugues: ");
    scanf ("%f", &p4);
    if (p4 > 10) {
printf ("ERRO NA NOTA!! \n\n");
}
    printf ("Nota em Matemtica: ");
    scanf ("%f", &m4);
    if (m4 > 10) {
printf ("ERRO NA NOTA!! \n\n");
}
    printf ("Nota em Geografia: ");
    scanf ("%f", &g4);
    if (g4 > 10) {
printf ("ERRO NA NOTA!! \n\n");
}
    printf ("Nota em Ciencias: ");
    scanf ("%f", &c4);
    if (c4 > 10) {
printf ("ERRO NA NOTA!! \n\n");
}
    float nt4 = p4 + m4 + g4 + c4;
    printf ("Nota total: %.2f \n", nt4);
    float Ma4 = (p4 + m4 + g4 + c4) /4;
    printf ("Média aritmetica: %.2f \n\n", Ma4);
    if (p4, m4, g4, c4 > 10) {
printf ("ERRO NAS NOTAS... \n\n");
}
    
    if (Ma4 > 6) {
        printf ("Aprovado!! \n \n \n");
    }
    else if (Ma4 >= 4 && Ma4 < 6){
        printf ("Recuperação \n \n \n");
    }
    else if (Ma4 < 4) {
        printf ("Reprovado \n \n \n");
    }
    
    
    //ALUNO 5
    printf ("Digite o nome do 5° aluno: ");
    scanf ("%s", &a5);
    printf ("Nota em portugues: ");
    scanf ("%f", &p5);
    if (p5 > 10) {
printf ("ERRO NA NOTA!! \n\n");
}
    printf ("Nota em Matemtica: ");
    scanf ("%f", &m5);
    if (m5 > 10) {
printf ("ERRO NA NOTA!! \n\n");
}
    printf ("Nota em Geografia: ");
    scanf ("%f", &g5);
    if (g5 > 10) {
printf ("ERRO NA NOTA!! \n\n");
}
    printf ("Nota em Ciencias: ");
    scanf ("%f", &c5);
    if (c5 > 10) {
printf ("ERRO NA NOTA!! \n\n");
}
    float nt5 = p5 + m5 + g5 + c5;
    printf ("Nota total: %.2f \n", nt5);
    float Ma5 = (p5 + m5 + g5 + c5) /4;
    printf ("Média aritmetica: %.2f \n\n", Ma5);
    if (p5, m5, g5, c5 > 10) {
printf ("ERRO NAS NOTAS... \n\n");
}
    
    if (Ma5 < 4) {
        printf ("Reprovado \n \n \n");
    }
    else if (Ma5 >= 4 && Ma5 < 6){
        printf ("Recuperação \n \n \n");
    }
    else if (Ma5 > 6) {
        printf ("aprovado! \n \n \n");
    }
    
    
     char A, B, C;
    printf ("A- Editar notas do aluno \t");
    printf ("B- Ajuda \t");
    printf ("C- Encerrar programa \n\n");
    printf ("Opção a ser digitada: ");
    
    scanf ("%s %s %s", &A, &B, &C);
    
    if (A){
        printf ("Digite a matéria e a nova nota: ");
        scanf ("%s", &A);
    }
    else if (B) {
        printf ("Óla, caso deseje algum atendimento ao cliente, envie uma solicitação no gmail: 0001066527@senaimgaluno.com.br ");
    }
    else if (C) {
        printf ("Obrigado pela escolha :)");
    
    }
    else if (C){
        printf ("Opção invalida");
    }

 
    return 0;
}
