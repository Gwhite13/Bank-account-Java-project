# Bank-account-Java-project
public abstract class Account
{
    //balance is money
    protected double balance;
    //Account is constructor
    protected Account(){
        balance = 0.0;
    }
    protected Account(double money){
        balance = money;
    }
    //deposit for putting in money
    protected void deposit(double money){
        balance = balance + money; 
    }
    //withdraw for taking out money
    protected void withdraw(double money){
        balance = balance - money;
    }
}
