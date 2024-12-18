public class TrianglePattern {
    public static void main(String[] args) {
        int rows = 5; // Tirada safafka

        for (int i = 1; i <= rows; i++) { // Safafka
            for (int j = 1; j <= i; j++) { // Columns
                System.out.print("* "); // Daabac calaamada '*'
            }
            System.out.println(); // Gudub saf cusub
        }
    }
}
