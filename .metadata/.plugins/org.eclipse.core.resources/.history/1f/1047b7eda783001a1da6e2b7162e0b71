package Definition;



import java.util.concurrent.TimeUnit;

import org.openqa.selenium.OutputType;
import org.openqa.selenium.TakesScreenshot;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;
import org.testng.Assert;

import io.cucumber.java.After;
import io.cucumber.java.Before;
import io.cucumber.java.Scenario;
import io.cucumber.java.en.Given;
import io.cucumber.java.en.Then;
import io.cucumber.java.en.When;

public class Test123 {
	WebDriver driver;
	
	@Given("^user is already in the login page$")
	public void userIsAlreadyInTheLoginPage() throws Throwable {
		System.out.println("user is already in the login page");
		Assert.fail();
	    // Write code here that turns the phrase above into concrete actions
	    
	}

	@When("^title of the lgin page is free CRmm$")
	public void titleOfTheLoginPageIsFreeCRmm() throws Throwable {
	    // Write code here that turns the phrase above into concrete actions
		System.out.println("^title of the login page is free CRmm");
	    
	}

	@Then("^user enter username and password$")
	public void userEnterUsernameAndPassword() throws Throwable {
	    // Write code here that turns the phrase above into concrete actions
		System.out.println("user enter username and password");
		System.out.println("verify the abc");

	}

	@Then("^user click on login button$")
	public void userClickOnLoginButton() throws Throwable {
	    // Write code here that turns the phrase above into concrete actions
		System.out.println("user click on login button");
	    
	}

	@Then("^User is home page$")
	public void userIsHomePage() throws Throwable {
	    // Write code here that turns the phrase above into concrete actions
		System.out.println("User is home page");
	    
	}

	
	@Given("^user is lookin up$")
	public void user_is_lookin_up() throws Throwable {
		System.out.println("user is looking up");
	}
	    // Write code here that turns the phrase above into concrete actions
	    
	

	@When("^user is taken up$")
	public void user_is_taken_up() throws Throwable {
		System.out.println("user is taken up");
//		Assert.assertEquals("sadsa", "sdsa");
	    // Write code here that turns the phrase above into concrete actions
	}

	@Before()
	public void intialiazOrder() throws Exception
	{
		System.out.println("before scenarios order");
		System.setProperty("webdriver.chrome.driver","E:/NoticeperiodSelenium/seleniumLearning/exes/chromedriver.exe");
		 driver= new ChromeDriver();
		Thread.sleep(1000);
		driver.manage().timeouts().setScriptTimeout(5, TimeUnit.SECONDS);
		driver.manage().window().maximize();
		driver.get("http://www.executeautomation.com");
	}
	
	@SuppressWarnings("deprecation")
	@After
public void tearDown(Scenario sec)
{
	System.out.println("After scenarios");
	System.out.println("scenario name:   "+ sec.getName());
	System.out.println("Scenario id :   "+sec.getId());
	System.out.println("Scenario Line :   "+sec.getLine());
	System.out.println("Scenario tagnames :   " + sec.getSourceTagNames());
	System.out.println("Scenario status :   " +sec.getStatus());
	System.out.println("Scenario uri :   " +sec.getUri());
	System.out.println("Scenario fail or pass :   "+sec.isFailed());
	sec.write("krishnauppara");
	if(sec.isFailed())
	{
		final byte[] screen=((TakesScreenshot)driver).getScreenshotAs(OutputType.BYTES);
		//sec.embed(screen,"image/png");
		sec.embed(screen, "image/png", sec.getName());
		System.out.println("screenshot captured");
	}
	driver.close();
}

}
