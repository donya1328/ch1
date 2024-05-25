# ch1
public static void main(String[] args) {

   Rectangle rectangle = new Rectangle(5, 3);

    double area = rectangle.calculateArea();
    System.out.println("Area of the rectangle: " + area);

    double perimeter = rectangle.calculatePerimeter();
    System.out.println("Perimeter of the rectangle: " + perimeter);
}
}

public class Rectangle { private double length; private double width;

public Rectangle(double length, double width) {
    this.length = length;
    this.width = width;
}


public double calculateArea() {
    return length * width;
}

public double calculatePerimeter() {
    return 2 * (length + width);
}


public double getLength() {
    return length;
}

public double getWidth() {
    return width;
}
