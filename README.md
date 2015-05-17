package WeekTwo;

import java.util.LinkedList;

 
public class CollectionsLinkdList {
 
    public static void main(String a[]){
         
        LinkedList<String> ll = new LinkedList<String>();
        ll.add("HHC143");
        ll.add("HHC225");
        ll.add("HHC313");
        ll.add("HHC101");
        System.out.println(ll);
        System.out.println("Size of the linked list: "+ll.size());
        System.out.println("Is LinkedList empty? "+ll.isEmpty());
        System.out.println("Does LinkedList contains 'HHC313'? "+ll.contains("HHC313"));
    }
}
//This is the more current version. i decided to scrap and start from fresh. I used bumper numbers from my unit in Burley for
//this action for the list. it works.
