# Java

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
