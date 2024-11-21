if (scanf("%d", &a) == 1){ //pokud neni cislo
            fprintf(stderr, "Error: Chybny vstup!\n");
            return 100;
        }else if (a < 3 || a > 69){
            fprintf(stderr, "Error: Vstup mimo interval!\n");
            return 101;
        } 
//sirka
