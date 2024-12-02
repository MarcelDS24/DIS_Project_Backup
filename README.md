[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=16283726)
Title: Tbd
Team Haghgoo, Gandler, 

1) Top Level File will be "Project.ipynb" (still not available)
	Everything can be exectuted from there.
    
    
2) You can download the CoinGecko and Reddit data with the corresponding jupyter notebooks. 
	Everything can be exectuted from there. NOTE: For the CoinGecko data you would need to create a Spark Session. 
	In order to avoid having to load the data everytime, everything is temporary saved inside the folders
	"json_files_Reddit" and 
	"tables_CoinGecko"

2) You will need a pw.py and a tokens.py file, that hold your Reddit API credentials.
	These files have to be inside this folder (./pw.py AND ./tokens.py)
	
	pw.py:
		username = "YOUR_USERNAME"
		password = "YOUR_PASSWORD"
	
	tokens.py:
		CLIENT_ID = "YOUR_CLIENT_ID"
		SECRET = "YOUR_CLIENT_SECRET"
		
3) We have created Python-Modules for functions we wanted to use more often and import in other notebooks (CoingeckoModule.py).
	Those files are commented for documentation.
	
