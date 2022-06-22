# alt_piramede
Altura Piramede decidida pelo usuario em C
#include <cs50.h>
#include <stdio.h>

    int main (void){


        int alt_piramede = get_int("Informe a altura da piramede: ");

    while (alt_piramede <1 || alt_piramede >8){
        alt_piramede = get_int("Informe a altura da piramede: ");
    }

       if(alt_piramede == 1){
           printf("#");
       }
       else if (alt_piramede == 2){
           printf("#\n");
           printf("##\n");
       }
        else if (alt_piramede == 3){
           printf("  #\n");
           printf(" ##\n");
           printf("###\n");
       }
       else if (alt_piramede == 4){
           printf("   #\n");
           printf("  ##\n");
           printf(" ###\n");
           printf("####\n");
       }
        else if (alt_piramede == 5){
           printf("    #\n");
           printf("   ##\n");
           printf("  ###\n");
           printf(" ####\n");
           printf("#####\n");
       }
        else if (alt_piramede == 6){
           printf("     #\n");
           printf("    ##\n");
           printf("   ###\n");
           printf("  ####\n");
           printf(" #####\n");
           printf("######\n");
       }
        else if (alt_piramede == 7){
           printf("      #\n");
           printf("     ##\n");
           printf("    ###\n");
           printf("   ####\n");
           printf("  #####\n");
           printf(" ######\n");
           printf("#######\n");
       }
        else if (alt_piramede == 8){
           printf("       #\n");
           printf("      ##\n");
           printf("     ###\n");
           printf("    ####\n");
           printf("   #####\n");
           printf("  ######\n");
           printf(" #######\n");
           printf("########\n");
       }
       else{
          alt_piramede = get_int("Informe a altura da piramede: ");
       }



}
