# Create-thread
Creating thread using thread class
class Main extends Thread {
    public void run()
    {
        System.out.print("Thread Running");
    }
    public static void main(String[] args)
    {
        Main g = new Main(); 
        g.start(); 
    }
}
