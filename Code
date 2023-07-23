public class Rectangle {
    double width;
    double height;
}
...
public class Geometry {
    double area(Object shape) {
        if (shape instanceof Circle) {
            Circle circle = (Circle) shape;
            return Math.PI * circle.radius * circle.radius
        } else if (shape instanceof Rectangle) {
            Rectangle rectangle = (Rectangle) shape;
            return rectangle.width * rectangle.height;
        } else if (shape instanceof Square) {
            Square square = (Square) shape;
            return square.size * square.size;
        }
 
        throw new IllegalArgumentException("Unknown shape");
    }
}
