public class Animal {
    String food;
    String location;
    public Animal(){}
    public Animal(String food,String location){
        this.food = food;
        this.location = location;
    }
    public void makeNoise(){
        System.out.println("(звуки животного)");
    }

    public void eat(){
        System.out.println("Животное ест "+this.food);
    }

    public void sleep(){
        System.out.println("Zzzzzzzzzzzzzzzzzzzz");
    }
}
class Dog extends Animal{
    String unique = "страж и охотник";
    public Dog(String food, String location) {
        super(food,location);
    }
    @Override
    public void makeNoise() {
        System.out.println("Гав-гав");
    }

    @Override
    public void eat() {
        System.out.println("Собака ест "+this.food);
    }
}
class Cat extends Animal{
    String  unique = "пушистый охотник на мышей";

    public Cat(String food, String location) {
        super(food,location);
    }

    @Override
    public void makeNoise() {
        System.out.println("Мяу");
    }

    @Override
    public void eat() {
        System.out.println("Кошка ест "+this.food);
    }
}

class Horse extends Animal{
    String unique = "быстрый и выносливый товарищ";
    public Horse(String food, String location) {
        super(food,location);
    }
    @Override
    public void makeNoise() {
        System.out.println("Иго-го");
    }

    @Override
    public void eat() {
        System.out.println("Лошадь ест "+this.food);
    }
}
