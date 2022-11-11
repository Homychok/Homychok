public class Main { 
    public static void main(String[] args) { 
        task1(); 
        task2();
        task3();
        task4();
        task5();
        task6();
        task7();
        task8();
    }

    public static void task1 () { 
        System.out.println("Задача 1"); 
        var dog=8;
        System.out.println(dog);
        var cat=3.6;
        System.out.println(cat);
        var paper=763789;
        System.out.println(paper);// Пишем код для задачи 1
    }

    public static void task2 () { 
        System.out.println("Задача 2"); 
        var dog = 8;
        dog = dog + 4;
        System.out.println(dog);
        var cat = 3.6;
        cat = cat + 4;
        System.out.println(cat);
        var paper = 763789;
        paper = paper + 4;
        System.out.println(paper); // Пишем код для задачи 2
    }
    
        public static void task3 () { 
        System.out.println("Задача 3"); 
        var dog = 8.0;
        dog = dog - 3.5;
        System.out.println(dog);
        var cat = 3.6;
        cat = cat - 1.6;
        System.out.println(cat);
        var paper = 763789;
        paper = paper - 7639;
        System.out.println(paper); // Пишем код для задачи 3
    }
    
    public static void task4 () { 
        System.out.println("Задача 4"); 
        var friend = 19;
        System.out.println(friend);
        friend = friend + 2;
        System.out.println(friend);
        friend = friend / 7;
        System.out.println(friend); // Пишем код для задачи 4
    }
    
    public static void task5 () { 
        System.out.println("Задача 5"); 
        var frog = 3.5;
        System.out.println(frog);
        frog = frog * 10;
        System.out.println(frog);
        frog = frog / 3.5;
        System.out.println(frog);
        frog = frog + 4;
        System.out.println(frog);// Пишем код для задачи 5
    }
    
    public static void task6 () { 
        System.out.println("Задача 6"); 
        var boxer1 = 78.2;
        var boxer2 = 82.7;
        var totalWeight = boxer1 + boxer2;
        System.out.println(totalWeight);
        var differenceWeight = boxer2 - boxer1;
        System.out.println(differenceWeight); // Пишем код для задачи 6
    }
    
    public static void task7 () { 
        System.out.println("Задача 7"); 
        var boxer1 = 78.2;
        var boxer2 = 82.7;
        var differenceWeight = boxer2 - boxer1;
        System.out.println(differenceWeight);
        var remainsWeight = boxer2 % boxer1;
        System.out.println(remainsWeight);// Пишем код для задачи 7
    }
    
    public static void task8 () { 
        System.out.println("Задача 8"); 
        var totalHours = 640;
        var workingHours = 8;
        var numberOfEmployees = totalHours / workingHours;
        System.out.println("Всего работников в компании - " + numberOfEmployees + " человек" );
        var employees = numberOfEmployees + 94;
        var totalHours2 = employees * workingHours;
        System.out.println("Если в компании работает " + employees + " человек, то всего " + totalHours2 + " часов работы может быть поделено между сотрудниками "); // Пишем код для задачи 8
    }
}
