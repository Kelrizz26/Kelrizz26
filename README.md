public class CAMPOS_ACTIVITY_II {
    public static void main(String []args){
        String [][] cars = {{"Lesbert","Boang","Yunson"},
                           {"Larvio","France","Lord"},
                           {"Jay","Joseph","Magsayo"}};

        cars[0][0] = "Lesbert";
        cars[0][1] = "Boang";
        cars[0][2] = "Yunson";
        cars[1][0] = "Larvio";
        cars[1][1] = "France";
        cars[1][2] = "Lord";
        cars[2][0] = "Jay";
        cars[2][1] = "Joseph";
        cars[2][2] = "Magsayo";
        
        for( int i= 0; i<cars.length; i++){
            System.out.println();
            for( int j= 0; j<cars[i].length; j++){
                System.out.println(cars[i][j]+".");
            }
        }
   
    }
}

