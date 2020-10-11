/**
 * в) Создать класс Basket, содержащий массив купленных товаров.
 */
public class Basket {
    Product[] products = new Product[100];
    int amount = 0;

    public void add(Product pro) {//добавления товара в корзину
        products[amount] = pro;
        amount++;
    }

    public void show() {//метод метод для показа товаров в корзине
        if (amount == 0) {
            System.out.println("Корзина пуста");
        } else {
            for (int i = 0; i < amount; i++) {
                System.out.println("Имя товара:" + products[i].name);
                System.out.println("Цена товара:" + products[i].price);
                System.out.println("Рейтинг товара:" + products[i].rating);
                System.out.println("------------------------------------");
            }
        }
    }
}
