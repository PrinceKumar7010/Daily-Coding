# Daily-Coding
# JAVA DAILY CODING SOLUTIONS


import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
       
   Scanner sc = new Scanner(System.in);
        double price = sc.nextDouble();
        double gstRate = sc.nextDouble();

        // Calculate GST on the price, considering only the Rupees part
        double gst = price * gstRate / 100;
        // Add GST to the price, considering only the Rupees part
        double finalPrice = price +gst;

        // Display only the Rupees part of the final price
        System.out.println((int)finalPrice);  
    
    
    
    
    
    
    }
}
