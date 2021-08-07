This is a Small Console Based project I made on Hotel Management System using Java:

 Hotel Management System Modules:

(1) BreakFast

(2) Lunch

(3) Dinner


This is the project:

package com.comsats;

import javax.security.auth.callback.ChoiceCallback;
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Welcome to hotel abc");
        System.out.println("\n1. breakfast \n2. lunch \n3. dinner");
        int userchoice = sc.nextInt();

        if (userchoice == 1) {
            System.out.println("welcome to breakfast menu");
            System.out.println("\n1. coffee \n2. chai \n3. bread and butter \n4. milkshake \n5. Fried Egg \n6. Boiled Egg \n0. Back");
            Scanner ac = new Scanner(System.in);
            int userchoicebreakfast = ac.nextInt();
            if (userchoicebreakfast == 1) {
                System.out.println("you have ordered coffee..........Rs 100");
            }
            else if (userchoicebreakfast == 2) {
                System.out.println("you have ordered chai..........Rs 50");
            }
            else if (userchoicebreakfast == 3) {
                System.out.println("you have ordered Bread & Butter..........Rs 250");
            }
            else if (userchoicebreakfast == 4) {
                System.out.println("you have ordered Milkshake..........Rs 90");
            }
            else if (userchoicebreakfast == 5) {
                System.out.println("you have ordered Fried Egg..........Rs 200");
            }
            else if (userchoice == 6) {
                System.out.println("you have ordered Boiled Egg..........Rs 170");
            }
            else {
                System.out.println("Invalid Option");
            }
        } else if (userchoice == 2) {
            System.out.println("welcome to Lunch menu");
            System.out.println("\n1. daal & Rooti \n2. Boiled Rice \n3. Biryani \n4. Pizza \n5. Burger");
            Scanner bc = new Scanner(System.in);
            int userchoicelunch = bc.nextInt();

            if (userchoicelunch == 1) {
                System.out.println("you have ordered Daal & Rooti..........Rs 250");
            }
            else if (userchoicelunch == 2) {
                System.out.println("you have ordered Boiled Rice..........Rs 200");
            }
            else if (userchoicelunch == 3) {
                System.out.println("you have ordered Biryani..........Rs 300");
            }
            else if (userchoicelunch == 4) {
                System.out.println("you have ordered Pizza");
                System.out.println("which size would you like to have?");
                System.out.println("\na. Small \nb. Medium \nc. Large \nd. Extra Large");
                Scanner dc = new Scanner(System.in);
                char userchoicepizza = dc.next().charAt(0);

                if (userchoicepizza == 'a') {
                    System.out.println("you have ordered a small size pizza..........Rs 150");
                } else if (userchoicepizza == 'b') {
                    System.out.println("you have ordered a medium size pizza...........Rs 350");
                } else if (userchoicepizza == 'c') {
                    System.out.println("you have ordered a Large size Pizza...........Rs 550");
                } else if (userchoicelunch == 'd') {
                    System.out.println("you have ordered a Extra Large Pizza...........Rs 990");
                } else {
                    System.out.println("Invalid Input");
                }
            }
            else if(userchoicelunch == 5) {
                System.out.println("you have ordered a Burger...........Rs 500");
            }
            else {
                System.out.println("Invalid Option");
            }
        }
            else if (userchoice == 3) {
                System.out.println("welcome to dinner menu");
                System.out.println("\n1. Chicken Roast \n2. Biryani \n3. Pasta \n4. Cake \n5. Pastrey");
                Scanner cc = new Scanner(System.in);
                int userchoicedinner = cc.nextInt();

                if (userchoicedinner == 1) {
                    System.out.println("you have ordered a Chicken Roast...........Rs 250");
                } else if (userchoicedinner == 2) {
                    System.out.println("you have ordered a Biryani...........Rs 150");
                } else if (userchoicedinner == 3) {
                    System.out.println("you have ordered Pasta..........Rs 270");
                } else if (userchoicedinner == 4) {
                    System.out.println("you have ordered a Cake");
                    System.out.println("select the type of cake");
                    System.out.println("\na. Chocolate Cake \nb. Strawberry Cake \nc. Vanilla Cake \nd. Chocolate Forest Cake \ne. Eggless Cake");
                    Scanner gg = new Scanner(System.in);
                    char userchoicecake = gg.next().charAt(0);

                    if(userchoicecake == 'a') {
                        System.out.println("you have ordered a Chocolate Cake...........Rs 500");
                    }
                    else if(userchoicecake == 'b') {
                        System.out.println("you have ordered a Strawberry Cake...........Rs 450");
                }
                    else if(userchoicecake == 'c') {
                        System.out.println("you have ordered a Vanilla Cake...........Rs 600");
                    }
                    else if(userchoicecake == 'd') {
                        System.out.println("you have ordered a Chocolate Forest Cake..........Rs 750");
                    }
                    else if(userchoicecake == 'e') {
                        System.out.println("you have ordered an Eggless Cake..........Rs 550");
                    }
                else if(userchoicedinner == 5) {
                        System.out.println("you have ordered a Pastery..............Rs 355");
                    }
                else {
                        System.out.println("Invalid Input");
                    }
            }
        }
    }
}




