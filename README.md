# CLAT-1
Programe for CLAT 1

#include <stdio.h>
#include <string.h>
#include <math.h>   
#include <stdlib.h>

int main() {
    int sec,days,hours,mins;
    scanf("%d",&sec);
    days=sec/(60*60*24);
    sec= sec%(60*60*24);
    hours=sec/(60*60);
    sec=sec%(60*60);
    mins=sec/60;
    sec=sec%60;
    printf("The Duration is %d days %d hours %d minutes %d seconds",days,hours,mins,sec);
    return 0;
}
