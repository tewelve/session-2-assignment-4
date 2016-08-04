# session-2-assignment-4

package project;

import java.util.Scanner;

public class Month {
	public static void main(String[] args)

    {

    Scanner input = new Scanner (System.in);
     
    int MonthNum; 

    int numDays = 0;

    String Month = null;

    System.out.print("Please enter the Month #");
    MonthNum = input.nextInt();
    	
    if (MonthNum == 2)
    {
       
        }

    else if (MonthNum == 1 || MonthNum == 3 || MonthNum == 5 || MonthNum == 7 || MonthNum == 8 

                || MonthNum == 10 || MonthNum == 12)

        numDays = 31;

    else

        numDays = 30;

     

    if (MonthNum == 1)

        Month = "January";

    else if (MonthNum == 2)

        Month = "Feburary";

    else if (MonthNum == 3)

        Month = "March";

    else if (MonthNum == 4)

        Month = "April";

    else if (MonthNum == 5)

        Month = "May";

    else if (MonthNum == 6)

        Month = "June";

    else if (MonthNum == 7)

        Month = "July";

    else if (MonthNum == 8)

        Month = "August";

    else if (MonthNum == 9)

        Month = "September";

    else if (MonthNum == 10)

        Month = "October";

    else if (MonthNum == 11)

        Month = "November";

    else if (MonthNum == 12)

        Month = "December";
    {



    System.out.println(Month);

    System.out.println(numDays);

}

}

}
