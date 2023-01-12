# mark-six-2
// Assuming the lottery has 49 numbers and players pick 6 numbers

int total_numbers = 49;
int numbers_picked = 6;

double chance_of_winning = (Combination(total_numbers, numbers_picked)) / (Combination(total_numbers, numbers_picked) * (Math.pow(total_numbers - numbers_picked, numbers_picked)));
