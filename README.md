# Lab6
import java.util.ArrayList;
import java.util.Arrays;
import java.util.Collections;
import java.util.LinkedList;
import java.util.Queue;
import java.util.Scanner;

public class gradeCalculator {

	public static void main(String[] args) {
		
		double lab1;
		double lab2;
		double lab3;
		double lab4;
		double lab5;
		double practiceProblems1;
		double practiceProblems2;
		double practiceProblems3;
		double practiceProblems4;
		double practiceProblems5;
		double practiceProblems6;
		double midTerm1;
		double midTerm2;
		
		System.out.println("Enter your following grades using a 0-100 scale.");
		System.out.println("");
		
		Scanner input = new Scanner(System.in);
	      System.out.println("Enter grade for Lab 1:");
	      
	      lab1 = input.nextDouble();
	      
	      ArrayList<Double> grades = new ArrayList<Double>();
	      
	      
	      grades.add(lab1);
	      
	      Scanner input2 = new Scanner(System.in);
	      System.out.println("Enter grade for Lab 2:");
	      
	      lab2 = input2.nextDouble();
	      
	      grades.add(lab2);
	      
	      Scanner input3 = new Scanner(System.in);
	      System.out.println("Enter grade for Lab 3:");
	      
	      lab3 = input3.nextDouble();
	      
	      grades.add(lab3);
	      
	      Scanner input4 = new Scanner(System.in);
	      System.out.println("Enter grade for Lab 4:");
	      
	      lab4 = input4.nextDouble();
	      
	      grades.add(lab4);
	      
	      Scanner input5 = new Scanner(System.in);
	      System.out.println("Enter grade for Lab 5:");
	      
	      lab5 = input5.nextDouble();
	      
	      grades.add(lab5);
	      
	      Scanner input6 = new Scanner(System.in);
	      System.out.println("Enter grade for Practice Problems 1:");
	      
	      practiceProblems1 = input6.nextDouble();
	      
	      grades.add(practiceProblems1);
	      
	      Scanner input7 = new Scanner(System.in);
	      System.out.println("Enter grade for Practice Problems 2:");
	      
	      practiceProblems2 = input7.nextDouble();
	      
	      grades.add(practiceProblems2);
	      
	      Scanner input8 = new Scanner(System.in);
	      System.out.println("Enter grade for Practice Problems 3:");
	      
	      practiceProblems3 = input8.nextDouble();
	      
	      grades.add(practiceProblems3);
	      
	      Scanner input9 = new Scanner(System.in);
	      System.out.println("Enter grade for Practice Problems 4:");
	      
	      practiceProblems4 = input9.nextDouble();
	      
	      grades.add(practiceProblems4);
	      
	      Scanner input10 = new Scanner(System.in);
	      System.out.println("Enter grade for Practice Problems 5:");
	      
	      practiceProblems5 = input10.nextDouble();
	      
	      grades.add(practiceProblems5);
	      
	      Scanner input11 = new Scanner(System.in);
	      System.out.println("Enter grade for Practice Problems 6:");
	      
	      practiceProblems6 = input11.nextDouble();
	      
	      grades.add(practiceProblems6);
	      
	      Scanner input12 = new Scanner(System.in);
	      System.out.println("Enter grade for midterm 1:");
	      
	      midTerm1 = input12.nextDouble();
	      
	      grades.add(midTerm1);
	      
	      Scanner input13 = new Scanner(System.in);
	      System.out.println("Enter grade for midterm 2:");
	      
	     midTerm2 = input13.nextDouble();
	      
	      grades.add(midTerm2);
	      
	      double total = 0;
	      double avg;
	      for(int i = 0; i < grades.size(); i++)
	      
	          total += grades.get(i);
	          avg = total / grades.size(); 
	          System.out.println("Your average grade is: " + avg);
	      
	     
	}


	}
