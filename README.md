# HelloWord
package somanumimpares;

/**
 *
 * @author lucas jacques
 */
public class SomaNumImpares {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
                              
            int x = 1;
            int y = 1000;
            int soma1 = 0;
            int soma2 = 0;
            int media = 0;
            
            while (x<=y){
                if(x%2==0){
                   /* Numeros Par */
                }else{
                    System.out.println(x+"");
                    soma1 = soma1 + 1;
                    soma2 = soma2 + x;  
                }                
                x++;
            }
            media = soma2 / soma1 ;
            System.out.println("Media de impares: "+ media);
            System.out.println("Soma de numeros impares: "+ soma2);     
    }   
}
