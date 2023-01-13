# My login code for web application
//this code is used for login and other functionality(dependency will be there, take the latest version for selenium)

import org.openqa.selenium.chrome.ChromeDriver;

public class commanLoginlogoutfunc {
	public static <webDriver> void main (String []args) {
		
		System.set.property("webdriver.chrome.driver", "C:\\Chrome Driver.chromedriver.exe"));
		webDriver driver=new ChromeDriver();
		
	    driver.manage().window().maximize();
	    
	    driver.get("write the website in which you want to login");
	    Thread.sleep(3000);
	    
	    //email in click,take the path from the website which u using
	    webElement emailClick=driver.findElement(By.xpath("//*[@id=\"email\"]"));
	    emailClick.click();
	    Thread.sleep(3000);
	    
	    //input email id,take the path from the website which u using
	    webElement typeemailid=driver.findElement(By.xpath("type email id here"));
	    typeemailid.type();
	    Thread.sleep(3000);
	    
	    
	    //password click,take the path from the website which u using
	    webElement passwordClick=driver.findElemnt(By.xpath("//*[@id=\"pass\"]"));
	    passwordClick.click();
	    Thread.sleep(4000);
	    
	    //input password,take the path from the website which u using
        webElement typepassword=driver.findElement(By.xpath("type the password here"));
        typepassword.type();
        Thread.sleep(3000);
	    
	    
	    //log In click
	    webElement log In click=driver.findElement(By.xpath("//*[@id=\"u_0_5_7U\"]"));
	    log InClick.click();
	    Thread.sleep(2000);
	    
	    //forgot password
	    webElement Forgot password click=driver.findElement(By.xpath("//*[@id=\"u_0_2_Mo\"]/div[3]/a"));
	    Forgot password.click();
	    Thread.sleep(4000);
