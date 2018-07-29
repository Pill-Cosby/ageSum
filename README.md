# ageSum

public static void main(String[] args) {
        Scanner reader = new Scanner(System.in);
        
        System.out.print("Type your name ");
        String name = reader.nextLine();
        System.out.println("Thanks, " + name + ". What is your age?");
        int x = Integer.parseInt(reader.nextLine());
        
        System.out.print("Enter a different name ");
        String name2 = reader.nextLine();
        System.out.println("Thank you very much, " + name2 + ". What's your age?");
        int y = Integer.parseInt(reader.nextLine());
        
            System.out.println("Thanks for the info; your combined age is " + Math.addExact(x, y));
        
        }
                
    }
