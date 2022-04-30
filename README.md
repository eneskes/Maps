# Maps
import java.util.ArrayList;
import java.util.HashMap;
import java.util.List;
import java.util.Map;
public class C01_Maps {
    public static void main(String[] args) {
       
        List<Object> list = new ArrayList<>();
        list.add("enes");
        list.add(15);
        list.add(10.2);
        System.out.println(list);
        list.set(1, (Integer)(list.get(1)) + 10);
        Map<Integer,String> sinifList = new HashMap<>();
        sinifList.put(101,"noc, nac, Dev");
        sinifList.put(102,"nic, nuc, QA");
        sinifList.put(103,"tik, tak, C#");
        System.out.println(sinifList);
        System.out.println(sinifList.keySet()); 
        System.out.println(sinifList.values());
       }
}

        
    
  
       
