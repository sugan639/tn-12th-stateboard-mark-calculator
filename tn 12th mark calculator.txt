package com.sugan;

import java.sql.SQLOutput;
import java.util.Arrays;
import java.util.Locale;
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        // write your code here


        System.out.println("SUGANKARTHICK's STATE BOARD 12th MARK CALCULATOR");

        float r=2;
        float n=6;
        float o=7;
        float q=9;
        int l=30;
        int x;
        int y;
        int z;
        int t ;
        int e;
        int p;
        int c;
        int m;
        int b;
        Scanner input = new Scanner(System.in);
        System.out.println("Enter your first highest mark in SSLC:");
        x =  input.nextInt();
        System.out.println("Enter your second highest mark in SSLC:");
        y = input.nextInt();
        System.out.println("Enter your third highest mark in SSLC:");
        z = input.nextInt();
        System.out.println("Enter your 11th tamil mark:");
        t=input.nextInt();
        System.out.println("Enter your 11th english mark:");
        e=input.nextInt();
        System.out.println("Enter your 11th physics mark:");
        p=input.nextInt();
        System.out.println("Enter your 11th chemistry mark:");
        c=input.nextInt();
        System.out.println("Enter your 11th mathematics mark:");
        m=input.nextInt();
        System.out.println("Enter your 11th biology mark:");
        b=input.nextInt();
        float u=r/o;
        float s= r/q;
        float d= (x+y+z)/n;
        float t1=t*s;
        float e1=e*s;
        float p1=p*u;
        float c1=c*u;
        float m1=m*s;
        float b1=b*u;

        System.out.println("Tamil:"+ (d +l+ t1));
        System.out.println("English:"+(d+l+e1));
        System.out.println("Physics:"+(d+l+p1));
        System.out.println("Chemistry:"+(d+l+c1));
        System.out.println("Maths:"+(d+l+m1));
        System.out.println("Biology:"+(d+l+b1));
        System.out.println("Total mark:"+((d +l+ t1)+(d+l+e1)+(d+l+c1)+(d+l+p1)+(d+l+m1)+(d+l+b1)));
        System.out.println("Engineering cutoff:"+((d+l+m1)+((d+l+p1)/2)+((d+l+c1)/2)));
}}