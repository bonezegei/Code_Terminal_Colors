# Code_Terminal_Colors
Colorful Terminal Prints


### Format
| ESC | Color Code | String or Character|
|-----|------------|--------------------|

* <strong>ESC</strong> Escape Character "\033" 
* <strong>Color Code</strong>  Equivalent code
* <strong>String or Character </strong> 

### Color Terminal in C
![IMG](https://raw.githubusercontent.com/bonezegei/Code_Terminal_Colors/main/doc/sample1.png "sample 1")

```c
  #include <stdio.h>
  #include <stdlib.h>
  #define RESET    "\033[0m"
  //Font Colors
  #define BLK "\033[30m"
  #define RED "\033[31m"
  #define GRN "\033[32m"
  #define YEL "\033[33m"
  #define BLU "\033[34m"
  #define MAG "\033[35m"
  #define CYN "\033[36m"
  #define WHT "\033[37m"
  #define GRY "\033[90m"
  //Font Colors Light

  #define LRED "\033[91m"
  #define LGRN "\033[92m"
  #define LYEL "\033[93m"
  #define LBLU "\033[94m"
  #define LMAG "\033[95m"
  #define LCYN "\033[96m"
  #define LWHT "\033[97m"

  //Background Colors
  #define BKG_BLK "\033[40m"
  #define BKG_RED "\033[41m"
  #define BKG_GRN "\033[42m"
  #define BKG_YEL "\033[43m"
  #define BKG_BLU "\033[44m"
  #define BKG_MAG "\033[45m"
  #define BKG_CYN "\033[46m"
  #define BKG_WHT "\033[47m"

  int main(){
      system("cls");
      printf(RED " RED " GRN" GREEN " BLU" BLUE " YEL" YELLOW " CYN" CYAN " MAG " MAGENTA \n" RESET );
      printf(BKG_RED " RED " BKG_GRN" GREEN " BKG_BLU" BLUE " BKG_YEL" YELLOW "  BKG_CYN" CYAN " BKG_MAG " MAGENTA \n" RESET );
      return 0;
  }

```
