package Definition;

import java.util.Map;

import org.openqa.selenium.WebDriver;
import org.testng.Assert;

import io.cucumber.datatable.DataTable;
import io.cucumber.java.en.Given;
import io.cucumber.java.en.Then;
import io.cucumber.java.en.When;


public class Mapdatatable{
	
	
//	WebDriver driver ;
	
	
	@Given("xyxz")
	public void xyxz() {
	System.out.println("verify the super");	
	}

	@When("abc")
	public void abc() {
		System.out.println("verify the abc");
		
			
	}
	

	@Then("def")
	public void def(DataTable test) {

		
		for(Map<Object, Object> aaa:test.asMaps(String.class,String.class))
		{
			System.out.println(aaa.get("username"));
			System.out.println(aaa.get("password"));
	
			
		}
	}	
	
	
	
	
	
	
	
	
	
	
//	@Before
//	
//	public void startTest(Scenario scenario) {
//		System.setProperty("webdriver.chrome.driver","E:/NoticeperiodSelenium/seleniumLearning/exes/chromedriver.exe");
//	 driver = new ChromeDriver();
//	}
//	
//	
//	
//	@After
//	public void endTest(Scenario scenario) {
//		
//		
//		
//		final byte[] screenshot = ((TakesScreenshot) driver).getScreenshotAs(OutputType.BYTES);
//		if (scenario.isFailed()) {
//
//			try {
////				final byte[] screenshot = ((TakesScreenshot) driver).getScreenshotAs(OutputType.BYTES);
//				scenario.embed(screenshot, "image/png"); // ... and embed it in
//			} catch (WebDriverException e) {
//				e.printStackTrace();
//			}
//
//		} else {
//			try {
//				
//				scenario.embed(screenshot, "image/png");
//			} catch (Exception e) {
//				e.printStackTrace();
//			}
//		}
//		
//		driver.close();

//}
	
	
	
	

}