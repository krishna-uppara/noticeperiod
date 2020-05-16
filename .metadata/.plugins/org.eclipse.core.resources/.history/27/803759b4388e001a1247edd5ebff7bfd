package definitionsssss;

import java.util.List;
import java.util.Map;

import io.cucumber.datatable.DataTable;
import io.cucumber.java.en.Given;
import io.cucumber.java.en.Then;
import io.cucumber.java.en.When;

public class DDwithoutExample {
	@Given("^user is in the login page$")
	public void userIsAlreadyInTheLoginPage() throws Throwable {
		System.out.println("user is already in the login page");
		// Write code here that turns the phrase above into concrete actions

	}

	@When("^Verify the \"(.*)\" of the login page$")
	public void titleOfTheLoginPageIsFreeCRmm(String title) throws Throwable {
		// Write code here that turns the phrase above into concrete actions
		System.out.println("^title of the login page is free CRmm  " + title);

	}

	// With Examples keyword
	// ^user enters \"([^\"]*)\" and \"([^\"]*)\"$
	@Then("^user enters \"(.*)\" and \"(.*)\"$")
	public void userEnterUsernameAndPassword(String username, String password) throws Throwable {
		// Write code here that turns the phrase above into concrete actions
		System.out.println("user enter username and password");
		System.out.println("username of the user: " + username + " password of the user: " + password);
		System.out.println("llllllllllllllllllllllllllllllllllllllllllllllllllllllllllllllllllllllllllllllllllllll");
	}

	
	// Data tables with no header
	@Then("^user clicks on login button$")
	public void userClickOnLoginButton(DataTable cred) throws Throwable {
		// Write code here that turns the phrase above into concrete actions
		DataTable listname = cred;
		System.out.println("user click on login button");
		System.out.println("username" + listname.row(0).get(0));
		System.out.println("password" + listname.row(0).get(1));
		System.out.println("username" + listname.row(1).get(0));
		System.out.println("password" + listname.row(1).get(1));

	}

	
	// Datatables with Header
	@Then("^User is on home page$")
	public void userIsHomePage(DataTable names) throws Throwable {

		System.out.println("User is on home page");
		for (Map<Object, Object> data : names.asMaps(String.class, String.class)) {
			System.out.println(data.get("name"));
			System.out.println(data.get("phone"));
			System.out.println(data.get("age"));
			System.out.println(data.get("salary"));
			System.out.println("kkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkkk");

		}
		// Write code here that turns the phrase above into concrete actions
		System.out.println("User is home page");

	}

}
