# TED-project
import java.awt.*;
Import java.awt.event.*;
Import javax.swing.*;

public class Operator extends JFrame implements ActionListener
	{
Label l,l3;	
JLabel l2,l1;
Font f;
Button b1,b2,b3,b4,b5,b8,b9,b10;
Container c1;
        
Operator()
	{
        c1=getContentPane();
       c1.setLayout(new FlowLayout());
		
        setBackground(Color.LIGHT_GRAY);

       f=new Font("Arial",Font.BOLD,20);

        setFont(f);
        
		ImageIcon i=new ImageIcon("criminal1.jpg");

       

	   l=new Label("         Welcome  Chandu!!!!!!!!        ");
	   l2=new JLabel("     Hi,                 ",i,JLabel.LEADING);

	   l3=new Label("           This is Operator                                                       ",Label.CENTER);
      
       
      
       b3=new Button("   Identifying of Images                   ");

       b4=new Button("   Images from Data Base      ");
      
       //b5=new Button("   Images from Eyewitnesses   ");
       
       b8=new Button("   Drawing of Images          ");
       
	  // b9=new Button("   Matching of Images          ");
       
	 //b10=new Button("   Data to Administrator       ");
       

	   addWindowListener(new WindowAdapter()
		{
			public void windowClosing(WindowEvent  e)
			{
				System.exit(0);
			}
		});


       l.setForeground(new Color(100,100,100));
       l.setFont(new Font("Arial",Font.BOLD,30)); 
       l2.setForeground(new Color(100,100,100));
       l2.setFont(new Font("Arial",Font.BOLD,20)); 
       l3.setForeground(new Color(0,64,64));
       l3.setFont(new Font("Arial",Font.BOLD,20)); 

       b3.setForeground(new Color(255,255,255));
       b3.setBackground(new Color(0,64,64));
       b3.setFont(new Font("Arial",Font.BOLD,15)); 
       
	   b4.setForeground(new Color(255,255,255));
       b4.setFont(new Font("Arial",Font.BOLD,15)); 
       b4.setBackground(new Color(0,64,64));
       
	  // b5.setForeground(new Color(255,255,255));
     //  b5.setFont(new Font("Arial",Font.BOLD,15)); 
      // b5.setBackground(new Color(0,64,64));
       
	   b8.setForeground(new Color(255,255,255));
       b8.setFont(new Font("Arial",Font.BOLD,15)); 
       b8.setBackground(new Color(0,64,64));
       
       /*b9.setForeground(new Color(255,255,255));
       b9.setFont(new Font("Arial",Font.BOLD,15)); 
       b9.setBackground(new Color(0,64,64));
       
       b10.setForeground(new Color(255,255,255));
       b10.setFont(new Font("Arial",Font.BOLD,15)); 
       b10.setBackground(new Color(0,64,64));*/
       
