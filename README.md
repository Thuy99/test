package bai6;

import org.junit.Test;

import static org.junit.Assert.*;

public class Test {

    @Test
    public void Test1() {
        int a[] = {1,2,3,4};
        int k = 10;
        int b = new Test().find(a, k);
        int t = -1;

        assertEquals(t, b);
    }

    @Test
    public void Test2() {
        int a[] = {1, 2,3,4};
        int k = 2;
        int b = new Test().find(a, k);
        int t= 0;

        assertEquals(t, b);
    }

    @Test
    public void Test3() {
        int a[] = {1, 2,3,4};
        int k = 5;
        int b= new Test().find(a, k);
        int t = -1;

        assertEquals(t, b );
    }

    @Test
    public void Test4() {
        int a[] = {1,2,3,4};
        int k = 1;
        int b = new Test().find(a, k);
        int t = 0;

        assertEquals(t, b );
    }
} 
