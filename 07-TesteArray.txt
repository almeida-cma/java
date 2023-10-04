public class TesteArray {

    public static void main(String[] args) {
        // Declaração e instanciação
        int[] a = new int[5];

        // Inicialização
        a[0] = 10;
        a[1] = 20;
        a[2] = 70;
        a[3] = 40;
        a[4] = 50;

        // Percorrendo e exibindo o array usando o loop for tradicional
        for (int i = 0; i < a.length; i++) {
            System.out.println(a[i]);
        }
    }
}
