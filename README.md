# Toy-Problems
Checking If Sum of 2 numbers is Odd Or Even

import static java.util.Arrays.stream;

class Codewars {
    static String oddOrEven(final int[] array) {
        return stream(array).sum() % 2 == 0 ? "even" : "odd";
    }
}

OR

public class Codewars {
  public static String oddOrEven (int[] array) {
    int sum = 0;
    for (int n : array){
      sum += n;
    }
    return sum%2==0 ? "even" : "odd";
  }
}

