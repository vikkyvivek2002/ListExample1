import java.awt.*;  import java.awt.event.*; 
public class ListExample1  
{
public static void main(String args[])  
{  
        Frame f= new Frame();  
        List l1=new List();
//List vegetableList = new List(3);
       final List l2=new List(3);    
      //  l1.setBounds(100,100, 75,75); 
       //l2.setBounds(200,200, 100,100);   
        l1.add("Cricket");  
        l1.add("Football");  
        l1.add("Hockey"); 
        l1.add("Tennis"); 
        l1.add("Chess");
        l1.add("Carroms");
        l1.add("Vollyball");
        //l2.add("p1");
        //l2.add("p2");
        f.add(l1);  
//f.add(l2);
        f.setSize(400,400);  
        f.setLayout(new FlowLayout());  
        f.setVisible(true);  
f.addWindowListener(new WindowAdapter() {
         public void windowClosing(WindowEvent windowEvent){
            System.exit(0);
         }        
      }); 

     }  
}  