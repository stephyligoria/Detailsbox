# Detailsbox
package detailsbox; 
import javax.swing.*;
import java.awt.*;

public class Aboutme extends JFrame {
    List me;
    Aboutme(){
        setLayout(new BorderLayout());
        setTitle("Details About me");
        setSize(300,350);
        setVisible(true);
        me=new List(9,true);
        add(me,BorderLayout.CENTER);
        me.add("Stephy Alphonse Ligoria");
        me.add("Im 20");
        me.add("DOB:MM-DD:12/2-30/2");
        me.add("Bsc coputer science student");
        me.add("Pursuing degree at NCAS");
    }
    public static void main(String args[]){
        new Aboutme();
    }
}
