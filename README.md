Starting ChromeDriver 103.0.5060.53 (a1711811edd74ff1cf2150f36ffa3b0dae40b17f-refs/branch-heads/5060@{#853}) on port 49401
Only local connections are allowed.
Please see https://chromedriver.chromium.org/security-considerations for suggestions on keeping ChromeDriver safe.
ChromeDriver was started successfully.
Exception in thread "main" org.openqa.selenium.SessionNotCreatedException: Could not start a new session. Response code 500. 
Message: session not created: This version of ChromeDriver only supports Chrome version 103
Current browser version is 102.0.5005.115 with binary path C:\Program Files\Google\Chrome\Application\chrome.exe
Build info: version: '4.3.0', revision: 'a4995e2c09*'
System info: host: 'LAPTOP-MOLO1114', ip: '192.168.0.109', os.name: 'Windows 11', os.arch: 'amd64', os.version: '10.0', java.version: '18.0.1.1'
Driver info: org.openqa.selenium.chrome.ChromeDriver
Command: [null, newSession {capabilities=[Capabilities {browserName: chrome, goog:chromeOptions: {args: [], extensions: []}}], desiredCapabilities=Capabilities {browserName: chrome, goog:chromeOptions: {args: [], extensions: []}}}]
	at org.openqa.selenium.remote.ProtocolHandshake.createSession(ProtocolHandshake.java:144)
	at org.openqa.selenium.remote.ProtocolHandshake.createSession(ProtocolHandshake.java:102)
	at org.openqa.selenium.remote.ProtocolHandshake.createSession(ProtocolHandshake.java:67)
	at org.openqa.selenium.remote.HttpCommandExecutor.execute(HttpCommandExecutor.java:156)
	at org.openqa.selenium.remote.service.DriverCommandExecutor.invokeExecute(DriverCommandExecutor.java:167)
	at org.openqa.selenium.remote.service.DriverCommandExecutor.execute(DriverCommandExecutor.java:142)
	at org.openqa.selenium.remote.RemoteWebDriver.execute(RemoteWebDriver.java:569)
	at org.openqa.selenium.remote.RemoteWebDriver.startSession(RemoteWebDriver.java:264)
	at org.openqa.selenium.remote.RemoteWebDriver.<init>(RemoteWebDriver.java:179)
	at org.openqa.selenium.chromium.ChromiumDriver.<init>(ChromiumDriver.java:101)
	at org.openqa.selenium.chrome.ChromeDriver.<init>(ChromeDriver.java:81)
	at org.openqa.selenium.chrome.ChromeDriver.<init>(ChromeDriver.java:49)
	at software.Demo.main(Demo.java:11)
