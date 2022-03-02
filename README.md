# Desafios---GFT-Start-4-Java-Nota-o-Cientifica
import java.io.IOException;
import java.util.Scanner;

public class CientificNotation 
{
  public static void main(String[] args) throws IOException 
  {
    Scanner sc = new Scanner(System.in);
    double value = sc.nextDouble();
    String signal = (Math.signum(value) > 0) ? "+" : "";
    System.out.printf("%s%10.4E\n", signal, value);
    sc.close();
  }
}
