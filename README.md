#include <stdio.h>

int main() {
    int runs;

  printf("Enter total career runs of player: ");
    scanf("%d", &runs);

  if (runs > 15000) {
        printf("Grade: GOD of Cricket\n");
        printf("Nomination: Player is nominated for Arjun Khel Ratna Award ✅\n");
    }
    else if (runs > 12000) {
        printf("Grade: Legend\n");
        printf("Nomination: Player is nominated for Arjun Khel Ratna Award ✅\n");
    }
    else if (runs > 9000) {
        printf("Grade: Excellent\n");
        printf("Nomination: Player is nominated for Arjun Khel Ratna Award ✅\n");
    }
    else if (runs > 6000) {
        printf("Grade: Good\n");
        printf("Nomination: Player is not nominated for Khel Ratna Award ❌\n");
    }
    else if (runs > 3000) {
        printf("Grade: Average\n");
        printf("Nomination: Player is not nominated for Khel Ratna Award ❌\n");
    }
    else {
        printf("Grade: Needs Improvement\n");
        printf("Nomination: Player is not nominated for Khel Ratna Award ❌\n");
    }

   return 0;
}
