# Beginner-Series-3-Sum-Of-Numbers-CodeWars-Java-Solution
Solution to Codwars Beginner Series #3 Sum of Numbers in Java

 public class Sum
  {
     public int GetSum(int a, int b)
     {
     //Math.abs takes the absolute value of the equation, thus if it is negative it takes the positive value
      return (a + b) * (Math.abs(a - b) + 1) / 2;
     }
  }
