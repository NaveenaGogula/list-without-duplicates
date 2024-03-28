# list-without-duplicates
import java.util.ArrayList;
import java.util.HashSet;
import java.util.List;

public class Main {
    public static void main(String[] args) {
      List<String>ListWithDuplicates=new ArrayList<>();
      ListWithDuplicates.add("Apple");
      ListWithDuplicates.add("Banana");
      ListWithDuplicates.add("Cherry");
      ListWithDuplicates.add("Apple");
      ListWithDuplicates.add("Banana");
      System.out.println("List with duplicates:"+ListWithDuplicates);
      HashSet<String> setWithoutDuplicates=new HashSet<>(ListWithDuplicates);
      System.out.println("List without duplicates:"+setWithoutDuplicates);
      }
    }
}
