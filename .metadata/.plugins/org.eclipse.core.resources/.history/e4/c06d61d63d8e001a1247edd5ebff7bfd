package Definition;

import java.util.Map;

import org.openqa.selenium.WebDriver;
import io.cucumber.datatable.DataTable;
import io.cucumber.java.Scenario;
import io.cucumber.java.en.Given;
import io.cucumber.java.en.Then;
import io.cucumber.java.en.When;


public class Mapdatatable{
	
	
	WebDriver driver ;
	
	
	@Given("xyxz")
	public void xyxz() {
	System.out.println("verify the super");	
	}

	@When("abc")
	public void abc(Scenario sec) {
		System.out.println("verify the abc");
		System.out.println("scenario name:   "+ sec.getName());
		System.out.println("Scenario id :   "+sec.getId());
		System.out.println("Scenario Line :   "+sec.getLine());
		System.out.println("Scenario tagnames :   " + sec.getSourceTagNames());
		System.out.println("Scenario status :   " +sec.getStatus());
		System.out.println("Scenario uri :   " +sec.getUri());
		System.out.println("Scenario fail or pass :   "+sec.isFailed());
//		System.out.println("Scenario id :   "+sec.write("fdf"));
	}
	

	@Then("def")
	public void def(DataTable test) {

		
		for(Map<Object, Object> aaa :test.asMaps(String.class,String.class))
		{
			System.out.println(aaa.get("username"));
			System.out.println(aaa.get("password"));
//			Assert.fail();
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