import java.util.LinkedList;
import java.util.Queue;
import java.util.Random;
import java.util.List;
import java.util.ArrayList;

interface numbers {
    void populate();
    void unpopulate();
}
public class Abdul implements numbers{
    public static void main(String[] args) {
        Queue<Integer> nums = new LinkedList<Integer>();
        List<?> list = new ArrayList<>( nums );
        //Random rand = new Random();

        Abdul abd = new Abdul();
        abd.populate();
    }

    @Override
    public void populate() {
        Random rand = new Random();
        Queue<Integer> nums = new LinkedList<Integer>();
        for(int i = 0; i < 5; i++){
            Integer randomInt = rand.nextInt(9);
            nums.add(randomInt);
        }
        System.out.println(nums);
    }

    @Override
    public void unpopulate() {
        Random rand = new Random();
        Queue<Integer> nums = new LinkedList<Integer>();
        Integer randomInt = rand.nextInt(4);

        Integer storage1 = 0;
        Integer storage2 = 0;
        Integer storage3 = 0;
        Integer storage4 = 0;
        Integer storage5 = 0;

        Integer position = 5;

        for(int i = 0; i < position; i++){
            if(position >= 1){
                storage1 = nums.remove();
            }
            if(position >= 2){
                storage2 = nums.remove();
            }
            if(position >= 3){
                storage3 = nums.remove();
            }
            if(position >= 4){
                storage4 = nums.remove();
            }
            if(position >= 5){
                storage5 = nums.remove();
            }
        }


        switch (randomInt){
            case 0:
                System.out.println(storage2 + storage3 + storage4 + storage5);
                break;
            case 1:
                System.out.println(storage1 + storage3 + storage4 + storage5);
                break;
            case 2:
                System.out.println(storage1 + storage2 + storage4 + storage5);
                break;
            case 3:
                System.out.println(storage1 + storage2 + storage3 + storage5);
                break;
            case 4:
                System.out.println(storage1 + storage2 + storage3 + storage4);
                break;
        }
    }
}
