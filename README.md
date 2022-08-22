# Software configuration

## Why did I choose to participate in the challenge portfolio?

Hello!

My name is Alla.

From participating in the project, I expect to gain and assimilate knowledge, 

as well as practice in the work of a tester. 

**Working as a tester is my main and most important goal.**

# Subtask 1 #

**Scouts Panel_hyperlink_xpath**

 //*[@id="__next"]/form/div/div[1]/h5
 
 //*[text()="Scouts Panel"]
 
 //div//h5 

**Login_hyperlink_xpath**

//*[@id="login"]

//*[text()="Login"]

//input[@name="login"]

**Password_hyperlink_xpath**

 //*[@id="password"]
 
 //input[@name="password"]
 
//input[@type="password"]

**English_hyperlink_xpath**

 //*[text()="English"]


**Polski_hyperlink_xpath**

//*[text()="Polski"]

 //*[contains(@class, "MuiInput-underline jss6")]

**Sign in_hyperlink_xpath**

//*[text()="Sign in"]

 //*[@class='MuiButton-label']
 
//*[contains(@class, "MuiButton-label")]


button_xpath="//*[contains(@class, "MuiButton-label")]"

 class LoginPage(BasePage):
 
     login_field_xpath = "//*[@id='login']"
     
     password_field_xpath = "//*[@id='password']"
     
    sign_in_button_xpath ="//*[contains(@class, 'MuiButton-label')]"
    
