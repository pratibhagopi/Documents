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
	    
	    //email in click,take the path by inspecting the element and copy that xpath below,from the website which u chose)
	    webElement emailClick=driver.findElement(By.xpath("//*[@id=\"email\"]"));
	    emailClick.click();
	    Thread.sleep(3000);(this is used to give time to process any functuionality for going to the next step(it takes 2-3 sec,for ex:Once you type the login ID  and click than it has to go to passowrd tab so the time taken to go to that tab is the sleep time give, another ex:if you search a item in search area than hit enter and wait for that item to appear, so the time between these two step is called as thread.sleep and the number provided is the secounds you can to give for it to appear)
	    
	    //input email id,take the path by inspecting the element and copy that xpath below,from the website which u chose)
	    webElement typeemailid=driver.findElement(By.xpath("type email id here"));
	    typeemailid.type();
	    Thread.sleep(3000);
	    
	    
	    //password click,take the path by inspecting the element and copy that xpath below,from the website which u chose)
	    webElement passwordClick=driver.findElemnt(By.xpath("//*[@id=\"pass\"]"));
	    passwordClick.click();
	    Thread.sleep(4000);
	    
	    //input password,take the path by inspecting the element and copy that xpath below,from the website which u chose)
        webElement typepassword=driver.findElement(By.xpath("type the password here"));
        typepassword.type();
        Thread.sleep(3000);
	    
	    
	    //log In click,take the path by inspecting the element and copy that xpath below,from the website which u chose)
	    webElement log In click=driver.findElement(By.xpath("//*[@id=\"u_0_5_7U\"]"));
	    log InClick.click();
	    Thread.sleep(2000);
	    
	    //forgot password,take the path by inspecting the element and copy that xpath below,from the website which u chose)
	    webElement Forgot password click=driver.findElement(By.xpath("//*[@id=\"u_0_2_Mo\"]/div[3]/a"));
	    Forgot password.click();
	    Thread.sleep(4000);
