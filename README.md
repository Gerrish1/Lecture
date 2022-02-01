# Lecture

#include <stdio.h>

int
main ()
{
  int month;

  printf ("Please enter the month number e.g. January 1, Feburary 2  \n");
  scanf ("%d", &month);
  switch (month)
    {
    case 1:
      printf ("You have entered January \n");
      printf (" The first month of the year ; which has 31 days \n");
      break;
    case 2:
      printf ("You have entered Feburary \n");
      printf (" The second month of the year ; which has either 28 days, or 29 days during a leap year  \n");
      break;
    case 3:
      printf ("You have entered March  \n");
      printf (" The third month of the year ; which has 31 days \n");
      break;
    case 4:
      printf ("You have entered April \n");
      printf (" The forth month of the year ; which has 30 days  \n");
      break;
    case 5:
      printf ("You have entered May\n");
      printf (" The fifth month of the year ; which has 31 days \n");
      break;
   
    case 6:
      printf ("You have entered June \n");
      printf (" The sixth month of the year ; which has 30 days \n");
      break;
    case 7:
      printf ("You have entered July \n");
      printf (" The seventh month of the year ; which has 31 days \n");
      break;
    case 8:
      printf ("You have entered Auguest \n");
      printf (" The eighth month of the year ; which has 31 days \n");
      break;
    case 9:
      printf ("You have entered September \n");
      printf (" The ninth month of the year ; which has 30 days \n");
      break;
    case 10:
      printf ("You have entered October \n");
      printf (" The tenth month of the year ; which has 31 days \n");
      break;
      case 11: 
     printf ("You have entered November \n");
        printf(" The eleventh month of the year ; which has 30 days \n");
        case 12: 
     printf ("You have entered december \n");
        printf(" The twelfth  month of the year ; which has 31 days \n");
    break;
    break;
 default:
      printf ("you did not enter a number between 1 and 12\n");

    }
  return 0;
}
