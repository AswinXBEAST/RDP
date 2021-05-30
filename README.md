Windows Server 2019 Github RDP Access (ngrok US)

Link :- https://github.com/AswinXBEAST/RDP

How to use it
1) go to  https://dashboard.ngrok.com/ and sign up or sign in 
2) go to auth token tab and copy your token :- https://dashboard.ngrok.com/auth/your-authtoken
3) Fork my repo 
4) go to settings > secrets > new repo secret > in "NAME" type "NGROK_AUTH_TOKEN" > in value paste your token 
5) go to Code > .github/workflow > main.yml > copy the code and delete it
6) Go to Action tab > set up this workflow > in edit file paste the code which you copied 
7) Then start commit > then go to "CI" > run workflow 
8) refresh the page > press "ci" in the workflow > press "built" > in "Connect to your RDP 2core-7GB Ram." you will get your IP, Username, Password

Now Enjoy it <3
