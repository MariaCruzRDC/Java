# Java-bubble sort E insertion Sort

public Class Principal {

   public static void main (String[] args) {
      int [] x = {2 , 4 , 3 , 5 , 6};
           bolha (x);
System.out.println(Array.toString(v));
}

    private static void bolha (int[] x) {
       for (int ultimo = x.length-1; ultimo>0; ultimo--){
         for (int i = 0; i<ultimo; i++)
            if (v[i] > v [i+1])
               trocar (v, i , i+1);
}
}
  private static void trocar (int [] x , int i, int j ){
       int aux = x[i];
           x[i] = x[j];
                v[j] = aux;

   }
  }
 }

//Fim do BUBBLE SORT//

//Inicia INSERTION SORT pois github não dá escolha a não ser importar ou vincular e meu computador não tem nenhuma IDE instalada por conta do espaço//

import java.util.Arrays;
import java.util.Random;

public class Principal {

public static void main (String [] args ){
int []x= {9, 3, 4, 6 ,7};
insertionSort(v);
System.out.println(Arrays.toString(v));
}
public static int [] gerarVetor(28){
int[] v = new int[n];
Random gerador = new Random();
for (int i = 0; i < n ; i++){
v[i]= gerador.nextInt(100);
return v;
]}

private static void insertionSort(int[] v) {
 int v , j;
for (int i = 1; i<length; i++){
x=v[i];
j=i-1;
while ((j>=0) && v [j] > x {
v[j+1] = v[j];
j=j-1;
}
v[j+1]=x;
}
}
}

 }
}
