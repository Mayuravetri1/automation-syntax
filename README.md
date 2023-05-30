# automation-syntax
syntax for automation using C#
SELENIUM SYNTAX FOR AUTOMATE	Keywords
Create a new instance of the Chrome driver	IWebDriver driver = new ChromeDriver();
Open a webpage	driver.Navigate().GoToUrl("https://www.example.com");
Find an element by its ID	IWebElement element = driver.FindElement(By.Id("element_id"));
Interact with the element (e.g., enter text)	element.SendKeys("Hello, world!");
Click a button	IWebElement button = driver.FindElement(By.Id("button_id")); button.Click();
Wait for an element to be visible	WebDriverWait wait = new WebDriverWait(driver, TimeSpan.FromSeconds(10)); element = wait.Until(ExpectedConditions.ElementIsVisible(By.Id("element_id")));
Get the text of an element	string text = element.Text; Console.WriteLine(text);
Close the browser window	driver.Quit();
![image](https://github.com/Mayuravetri1/automation-syntax/assets/132995954/38ad5fb9-6b27-4be3-8900-54cd81303b04)
