# Tes121231

public class Main {
    public static void main(String[] args) {
        int[] arr = {18, 19, 4, 9, 1, 20};
        int index = -1;

        for (int i = 0; i < arr.length; i++) {
            if (arr[i] == 9) {
                index = i;
                System.out.println("Bilangan 9 ditemukan pada indeks ke-" + index);
                break;
            }
        }

        if (index == -1) {
            System.out.println("Bilangan 9 tidak ditemukan dalam larik");
        }
    }
}
