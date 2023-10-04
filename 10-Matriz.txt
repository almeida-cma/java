class Matriz {
    
    public static void main(String args[]) {
        // declarando e inicializando a array
        int arr[][] = {
            {1, 2, 3},
            {2, 4, 5},
            {4, 4, 5}
        };

        // imprimiendo matriz 2D
        for (int i = 0; i < 3; i++) {
            for (int j = 0; j < 3; j++) {
                System.out.print(arr[i][j] + " ");
            }
            System.out.println();
        }
    }
}
