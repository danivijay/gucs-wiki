# Installing Wittr App on Windows
Follow the below steps to install **wittr** app on **Windows**:

**1**. Install [**Node.js**](https://nodejs.org/en/).

**2**. Install [**Git**](https://git-scm.com/).

**3**. Create a folder and open **Command Prompt** and type `git clone https://github.com/jakearchibald/wittr`

**4**. After the repository is cloned then go to **wittr** directory, open **Command Prompt** and type `npm install`. This will install all the dependencies which are required for the project. If there are no errors while installing dependencies then you can skip steps **5** and **6**

**5**. If step **4** gives errors then, type `npm install -g windows-build-tools` (_this will install all the dependencies which are required to compile native *Node modules*_). 
> Note: Installation of **`windows-build-tools`** take some time, so please be patient.

**6**. After build tools are installed then type `npm install` 

**7**. Type `npm run serve` to start the server. If there are no errors while starting server, navigate to [http://localhost:8888](http://localhost:8888) to access Wittr App.

>Note:  If your app is unable to run on port **`8888`** then try changing the port number from `server/index.js` to anything other than **`8888`** and repeat step **7** by replacing  **`8888`** in the url to the port number which you specified in `server/index.js`.
