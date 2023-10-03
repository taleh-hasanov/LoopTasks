# LoopTasks
/filter
public class LoopTasks {
    public static void main(String[] args) {

        String hello = "Hello World!";
        int stringHello = hello.length();
        int index = 0;
        String newString = "";



        while (index < stringHello){
            char findCharacter = hello.charAt(index);
            if(findCharacter == 'o'){
                newString = newString + 0;

            } else {
                newString = newString + findCharacter;

            }
            index++;
        }
        System.out.println(newString);


    }
}
