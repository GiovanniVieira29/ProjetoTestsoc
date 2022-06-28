import org.openqa.selenium.By;
import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

public class TesteAmbiente2 {

	
	public static void main(String[] args) { 
		
		System.setProperty("webdriver.chrome.driver", "c:\\Users\\ModalGR\\Desktop\\Selenium\\chromedriver_win32\\chromedriver.exe");
		
		WebDriver driver = new ChromeDriver();
		
		driver.get("https://www.soc.com.br/");
		
			
	}
	
	public void SOCNET(String arg) {
		
		System.setProperty("webdriver.chrome.driver", "c:\\Users\\ModalGR\\Desktop\\Selenium\\chromedriver_win32\\chromedriver.exe");
		
		WebDriver driver = new ChromeDriver();
		
		driver.findElement(By.linkText("https://www.soc.com.br/socnet/")).click();
		
	}
	  
	public void BuscarCredenciado(String arg) {
		
        System.setProperty("webdriver.chrome.driver", "c:\\Users\\ModalGR\\Desktop\\Selenium\\chromedriver_win32\\chromedriver.exe");
		
		WebDriver driver = new ChromeDriver();
		
		driver.findElement(By.name("Buscar credenciados")).click();
		
	}
	
	public void SelecionarEmpresa(String arg) {
		
		 System.setProperty("webdriver.chrome.driver", "c:\\Users\\ModalGR\\Desktop\\Selenium\\chromedriver_win32\\chromedriver.exe");
		
		 WebDriver driver = new ChromeDriver();
		 
		 driver.findElement(By.name("Empresa")).click();
	}
	
	public void Acervo(String arg1) {
		
		System.setProperty("webdriver.chrome.driver", "c:\\Users\\ModalGR\\Desktop\\Selenium\\chromedriver_win32\\chromedriver.exe");
		
		WebDriver driver = new ChromeDriver();
		
		driver.findElement(By.id("ipt-busca-credenciado-2")).sendKeys(arg1);
		 
	}
	
	public void BotãoDeBusca(String arg) {
		
        System.setProperty("webdriver.chrome.driver", "c:\\Users\\ModalGR\\Desktop\\Selenium\\chromedriver_win32\\chromedriver.exe");
		
		WebDriver driver = new ChromeDriver();
		
		driver.findElement(By.tagName("button")).click();
		
	}
	
	 public void VisualizarEmpresa(String arg) {
		 
		System.setProperty("webdriver.chrome.driver", "c:\\Users\\ModalGR\\Desktop\\Selenium\\chromedriver_win32\\chromedriver.exe");
			
		WebDriver driver = new ChromeDriver();
		
		driver.findElement(By.name("Saiba mais")).click();
		 
	 }
}
