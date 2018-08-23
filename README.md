# Java-Atividades

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


//FIM do INSERTION SORT//


//Inicia BUSCA BINÁRIA pois github não dá escolha a não ser importar ou vincular e meu computador não tem nenhuma IDE instalada por conta do espaço//

public class Program {
public static void main (String [] args){
 int []S ={1,9,11,21,31,40};
 int indice =  binaria (S, 31);
 System.out.println(indice);

}
 private static int binaria (int [] s , int x) {
 int meio
 int inicio, fim;
 inicio = 0;
 fim = S.length-1;

 while (inicio <= fim){
 meio = (inicio + fim)/2;
 if (s[meio] < x) inicio = meio +1;
 else if (s[meio]< x) início = meio +1;
 else if (s[meio]> x) fim = meio-1;
  }
 return -1;
 }
}

//FIM BUSCA BINÁRIA//

//Inicia JOPTION PANE pois github não dá escolha a não ser importar ou vincular e meu computador não tem nenhuma IDE instalada por conta do espaço//

import java.swing.JOptionPane;

public class Main
{
public static void main(String [] args)
}
 int g = -1;
 while (g<0)
{
 String input = JOptionPane.showInputDialog("Insira um número:");
 if (input.lenght()>0)
{
 g++;
System.out.println("Belezura");
} else
 System.out.Println ("Tente inserir um número:");
  }
 }
}

//FIM JOPTION PANE//

