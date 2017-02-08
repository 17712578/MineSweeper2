# MineSweeper2
// I have decided to work on timing as the first component as it is important that i master this topic, due to its possible importance in future projects


import java.util;
class MyClass
  {
  public static void main(String[] args) throws Exception
    {
    long timeStamp = (System.nanoTime() / 10000000);
    String startedString = String.format("This program %s at %d\n", "started", timeStamp);
    System.out.print(startedString);
    Thread.sleep(5000);
    timeStamp = (System.nanoTime() / 10000000);
    String endedString = String.format("This program %s at %d\n", "ended", timeStamp);
    System.out.print(endedString);
    }
  }
