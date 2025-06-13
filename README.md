mport java.util.*;
public class arjunbhushan {
    public static void main(String args[])
    {
        String name,choice;
        int ch,emp,visitor,enter_pin,pay;
        int R_no[]={101,102,103};
        int R_N,Ac,S_B_R,D_B_R,C_h;
        int pin[]={111111,222222,333333};
        Scanner sc=new Scanner(System.in);
        System.out.println("enter your id:");
        name=sc.next();
        System.out.println("enter your pin");
        enter_pin=sc.nextInt();
        if(enter_pin==111111)
        {
            
            System.out.println("1.employee\n2.visitor");
            System.out.println("enter your choice");
            ch=sc.nextInt();
            switch(ch)
            {
                case 1:
                    System.out.println("enter room number:");
                    R_N=sc.nextInt();
                    if(R_N==101)
                    {
                        System.out.println("room is clean!!");
                    }
                    else if(R_N==102)
                    {
                        System.out.println("room is not clean!!!");
                    }
                    else if(R_N==103)
                    {
                        System.out.println("room is clean!!");
    
                    }
                    else
                    {
                        System.out.println("this type room is not available!!");
                    }
                    break;
                case 2:
                    System.out.println("enter room number:");
                    R_N=sc.nextInt();
                    if(R_N==101)
                    {
                        
                        System.out.println("1.AC\n2.Single bedroom\nDouble Bedroom");
                        System.out.println("enter your choice:");
                        C_h=sc.nextInt();
                        switch(C_h)
                        {
                            case 1:
                                System.out.println("you choose AC room!!");
                                System.out.println("you want to book this room?");
                                System.out.println("if you want to book this room then print yes");
                                choice=sc.next();
                                if(choice.equals("yes"))
                                {
                                    System.out.println("you have to pay 2500 rupees");
                                    System.out.println("pay 2500 rupees");
                                    pay=sc.nextInt();
                                    if(pay==2500)
                                    {
                                        System.out.println("your room is booked!!");
                                    }
                                    else
                                    {
                                        System.out.println("please pay initialixed amount");
                                    }

                                }
                                else
                                {
                                    System.out.println("thank you for visiting!!!");
                                }
                                break;
                            case 2:
                                System.out.println("You choose single bedroom!!!");
                                System.out.println("you want to book this room?");
                                System.out.println("if you want to book this room then print yes");
                                choice=sc.next();
                                if(choice.equals("yes"))
                                {
                                    System.out.println("you have to pay 2000 rupees");
                                    System.out.println("pay 2000 rupees");
                                    pay=sc.nextInt();
                                    if(pay==2500)
                                    {
                                        System.out.println("your room is booked!!");
                                    }
                                    else
                                    {
                                        System.out.println("please pay initialixed amount");
                                    }

                                }
                                else
                                {
                                    System.out.println("thank you for visiting!!!");
                                }
                                break;
                            case 3:
                                System.out.println("You choose double bedroom!!!");
                                System.out.println("you want to book this room?");
                                System.out.println("if you want to book this room then print yes");
                                choice=sc.next();
                                if(choice.equals("yes"))
                                {
                                    System.out.println("you have to pay 3000 rupees");
                                    System.out.println("pay 2500 rupees");
                                    pay=sc.nextInt();
                                    if(pay==3000)
                                    {
                                        System.out.println("your room is booked!!");
                                    }
                                    else
                                    {
                                        System.out.println("please pay initialized amount");
                                    }

                                }
                                else
                                {
                                    System.out.println("thank you for visiting!!!");
                                }
                                break;
                            default:
                                System.out.println("not more choices are available!!!");
                                break;
                        }
                        System.out.println("************reviept************");
                        System.out.println("visitor id:+name");
                        System.out.println("room number:"+R_N);
                        System.out.println("payment:"+pay);
                        System.out.println("date:"+"13/06/2025");

                    }
                    else if(R_N==102)
                    {
                        System.out.println("1.AC\n2.Single bedroom\nDouble Bedroom");
                        System.out.println("enter your choice:");
                        C_h=sc.nextInt();
                        switch(C_h)
                        {
                            case 1:
                                System.out.println("you choose AC room!!");
                                System.out.println("you want to book this room?");
                                System.out.println("if you want to book this room then print yes");
                                choice=sc.next();
                                if(choice.equals("yes"))
                                {
                                    System.out.println("you have to pay 2500 rupees");
                                    System.out.println("pay 2500 rupees");
                                    pay=sc.nextInt();
                                    if(pay==2500)
                                    {
                                        System.out.println("your room is booked!!");
                                    }
                                    else
                                    {
                                        System.out.println("please pay initialixed amount");
                                    }

                                }
                                else
                                {
                                    System.out.println("thank you for visiting!!!");
                                }
                                break;
                            case 2:
                                System.out.println("You choose single bedroom!!!");
                                System.out.println("you want to book this room?");
                                System.out.println("if you want to book this room then print yes");
                                choice=sc.next();
                                if(choice.equals("yes"))
                                {
                                    System.out.println("you have to pay 2000 rupees");
                                    System.out.println("pay 2000 rupees");
                                    pay=sc.nextInt();
                                    if(pay==2500)
                                    {
                                        System.out.println("your room is booked!!");
                                    }
                                    else
                                    {
                                        System.out.println("please pay initialixed amount");
                                    }

                                }
                                else
                                {
                                    System.out.println("thank you for visiting!!!");
                                }
                                break;
                            case 3:
                                System.out.println("You choose double bedroom!!!");
                                System.out.println("you want to book this room?");
                                System.out.println("if you want to book this room then print yes");
                                choice=sc.next();
                                if(choice.equals("yes"))
                                {
                                    System.out.println("you have to pay 3000 rupees");
                                    System.out.println("pay 2500 rupees");
                                    pay=sc.nextInt();
                                    if(pay==3000)
                                    {
                                        System.out.println("your room is booked!!");
                                    }
                                    else
                                    {
                                        System.out.println("please pay initialixed amount");
                                    }

                                }
                                else
                                {
                                    System.out.println("thank you for visiting!!!");
                                }
                                break;
                            default:
                                System.out.println("not more choices are available!!!");
                                break;
                        }
                        System.out.println("************reviept************");
                        System.out.println("visitor id:+name");
                        System.out.println("room number:"+R_N);
                        System.out.println("payment:"+pay);
                        System.out.println("date:"+"13/06/2025");
                        
                    }
                    else if(R_N==103)
                    {
                         System.out.println("1.AC\n2.Single bedroom\nDouble Bedroom");
                        System.out.println("enter your choice:");
                        C_h=sc.nextInt();
                        switch(C_h)
                        {
                            case 1:
                                System.out.println("you choose AC room!!");
                                System.out.println("you want to book this room?");
                                System.out.println("if you want to book this room then print yes");
                                choice=sc.next();
                                if(choice.equals("yes"))
                                {
                                    System.out.println("you have to pay 2500 rupees");
                                    System.out.println("pay 2500 rupees");
                                    pay=sc.nextInt();
                                    if(pay==2500)
                                    {
                                        System.out.println("your room is booked!!");
                                    }
                                    else
                                    {
                                        System.out.println("please pay initialixed amount");
                                    }

                                }
                                else
                                {
                                    System.out.println("thank you for visiting!!!");
                                }
                                break;
                            case 2:
                                System.out.println("You choose single bedroom!!!");
                                System.out.println("you want to book this room?");
                                System.out.println("if you want to book this room then print yes");
                                choice=sc.next();
                                if(choice.equals("yes"))
                                {
                                    System.out.println("you have to pay 2000 rupees");
                                    System.out.println("pay 2000 rupees");
                                    pay=sc.nextInt();
                                    if(pay==2500)
                                    {
                                        System.out.println("your room is booked!!");
                                    }
                                    else
                                    {
                                        System.out.println("please pay initialixed amount");
                                    }

                                }
                                else
                                {
                                    System.out.println("thank you for visiting!!!");
                                }
                                break;
                            case 3:
                                System.out.println("You choose double bedroom!!!");
                                System.out.println("you want to book this room?");
                                System.out.println("if you want to book this room then print yes");
                                choice=sc.next();
                                if(choice.equals("yes"))
                                {
                                    System.out.println("you have to pay 3000 rupees");
                                    System.out.println("pay 2500 rupees");
                                    pay=sc.nextInt();
                                    if(pay==3000)
                                    {
                                        System.out.println("your room is booked!!");
                                    }
                                    else
                                    {
                                        System.out.println("please pay initialixed amount");
                                    }

                                }
                                else
                                {
                                    System.out.println("thank you for visiting!!!");
                                }
                                break;
                            default:
                                System.out.println("not more choices are available!!!");
                                break;
                        }
                        System.out.println("************reviept************");
                        System.out.println("visitor id:"+name);
                        System.out.println("room number:"+R_N);
                        System.out.println("payment:"+pay);
                        System.out.println("date:"+"13/06/2025");
                    }
                    else
                    {
                        System.out.println("this type room is not available!!");
                    }

        }
        }
        
    }
}
