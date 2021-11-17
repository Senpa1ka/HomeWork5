package geekbrains;

import java.text.MessageFormat;

public class Сотрудник {

    String FIO;
    String position;
    String email;
    int phone;
    int salary;
    int age;



    public static void main(String[] args) {
        personal();
company();

    }


public Сотрудник(String FIO, String position, String email, int phone, int salary, int age){
this.FIO = FIO;
this.position = position;
this.email = email;
    this.phone = phone;
    this.salary = salary;
    this.age = age;
}


public Сотрудник(){

}


    void Info()

    {
        System.out.println("Name : " + FIO);
        System.out.println("Position : " + position);
        System.out.println("email : " + email);
        System.out.println("phone : " + phone);
        System.out.println("Salary : " + salary);
        System.out.println("Age : " + age);
    }

    public static void personal() {
        Сотрудник personal = new Сотрудник("Федя", "Повар", "Fedor34@mail.ru", 79231351,100000, 34  );

personal.Info();
}

public static void company (){
    Сотрудник personal = new Сотрудник();
    Сотрудник[] persArray =  new Сотрудник[5];
    persArray[0] = new Сотрудник("Сеня", "Повар", "Senya@mail.ru", 71254121,90000, 41);
    persArray[1] = new Сотрудник("Нюра", "уборщица", "nura@mail.ru", 73468387,20000, 46);
    persArray[2] = new Сотрудник("Луи", "Кондитер", "Lyi31@mail.ru", 7435799,120000, 21);
    persArray[3] = new Сотрудник("Виктор", "Шеф", "Vitya@mail.ru", 73471334,300000, 55);
    persArray[4] = new Сотрудник("Лёва", "Су-Шеф", "Lev347@mail.ru", 7346531,170000, 36);

        }
    }
