...----Number Guessing Game----...








void main() {
  int num = 7; // user inut 1-10
  int guess = 7;

  if (num < guess) {
    print('increase');
  } else if (num > guess) {
    print('decrease');
  } else if (num == guess) {
    print('Correct guess');
  } else {
    print('Incorrect input');
  }
}
