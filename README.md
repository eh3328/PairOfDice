# PairOfDice
/**
 * @(#)PairOfDice.java
 *
 *
 * @author 
 * @version 1.00 2018/12/7
 */

import java.util.Random;
public class PairOfDice 
{
    public static void main(String[] args) 
    {
    final int DIGITS = 6;
    double count = 0;
    int Dice1 = 1;
    int Dice2 = 1;
    int x = 0;
    //int num1();
	while(x<=1000)
	{
    Dice1 = (int) (Math.random() * DIGITS);
    Dice2 = (int) (Math.random() * DIGITS);
    
    if (Dice1 == Dice2)
    {
    	count++;
    	x++;
    System.out.println("You got "+count+" Box Cars!");
	}
	else
	{
		x++;
	}
    }
    //count/1000=num1;
    System.out.println("The rate is "+count/1000);
}
}
