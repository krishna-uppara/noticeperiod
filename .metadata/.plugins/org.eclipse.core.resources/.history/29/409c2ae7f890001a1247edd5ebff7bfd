package RunnerClass;
import org.testng.annotations.AfterClass;
import org.testng.annotations.BeforeClass;
import org.testng.annotations.DataProvider;
import org.testng.annotations.Test;

import io.cucumber.testng.AbstractTestNGCucumberTests;
import io.cucumber.testng.FeatureWrapper;
import io.cucumber.testng.PickleWrapper;
import io.cucumber.testng.TestNGCucumberRunner;
 

@io.cucumber.testng.CucumberOptions(features = "E:/NoticeperiodSelenium/cucumberreports/src/main/java/Features",
				 glue = "Definition",
				 monochrome = true,
//				 dryRun=true,
				//strict=true
				  plugin={ "pretty","html:target/target1/cucumber-html"
						  ,"json:target/target1/Cucumber.json"
						  ,"pretty:target/target1/cucumber-html.txt"
						  ,"junit:target/target1/cucumber-html.xml"
//						  ,"usage:target/cucumber-html1.json"
//						  ,"rerun:target/rerun.txt"
						  }
				 // OR {"@,@"}
				 //,tags={"@smoke,@regressions"}
				 // AND {"@","@"}
				 //,tags={"@smoke","@regressions"}
				 //NOT {"~@"}
                 //,tags={"~@smoke,~@regressions"}
				 
					)

public class Runner extends AbstractTestNGCucumberTests {
	
 TestNGCucumberRunner testNGCucumberRunner;
	 
    @BeforeClass(alwaysRun = true)
   
    public void setup() {
       

        testNGCucumberRunner =new TestNGCucumberRunner(this.getClass());
    }
 
    @Test(groups = "cucumber scenarios", description = "Runs Cucumber Scenarios", dataProvider = "scenarios")
    public void scenario(PickleWrapper pickleEvent, FeatureWrapper cucumberFeature) throws Throwable {
        testNGCucumberRunner.runScenario(pickleEvent.getPickle());//runScenario(pickleEvent.getPickle());
    }
 
    /**
     * @return returns two dimensional array of {@link CucumberFeatureWrapper}
     *         objects.
     */
    @DataProvider(parallel =true)
    public Object[][] scenarios() {
        return testNGCucumberRunner.provideScenarios();//super.scenarios();
    }
 
    @AfterClass(alwaysRun = true)
    public void tearDown() {
       
        testNGCucumberRunner.finish();
    }
}


