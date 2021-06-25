# HandChill Clone
Fansite CMS powered by Habbink. Developer by Hugoyin.

## How to install?
1. Download CMS.
 
2. Import the CMS files into your `HTDOCS` or `PUBLIC_HTML` folder.

3. Make your database connection via `Library > Sessions > Config` file.

		$dbhost     = "localhost";
		$dbusername = "Your username";
		$dbuserpass = "Your password";
		$dbname     = "Your database name";
    
4. And database settings.

    • PhpMyAdmin open.
    
    • Your database.
    
    • Open the config table.
    
    • URL and title edit.

5. Adapt the CMS to your hotel via the `Library > Sessions > Config > Language > En` file.

		"hotel name" => "Your Hotel Name",
		"hotel url" => "Your Hotel URL",
		"location" => "Your location",
		"twitter" => "Your Twitter Name",
		"version" => "1.0.0",
		"mail" => "Your fansite email address",
