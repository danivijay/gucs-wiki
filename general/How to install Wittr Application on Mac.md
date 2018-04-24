# Installing Wittr Application on Mac
Follow the following steps to install **Wittr** on **Mac OS**:

**1**. Install [**Node.js**](https://nodejs.org/en/) by following the on-screen instructions.

**2**. Create a new folder in your desired location from **Finder** and `cd` into that folder. E.g.: If I want to store the Wittr Application in **Documents**, I would open up **Terminal from Application** and type this: `cd Documents`. We would then see that we are in the **Documents** folder through **Terminal**.

**3**. Type `git clone https://github.com/jakearchibald/wittr`.

**4**. Now go inside the Wittr directory by typing `cd Wittr` and type `npm install`. This will take some time depending upon your internet speed. 

**5**. Once the installation is complete, type `npm run serve`. This will start the server in your computer and run the project on it. If everything goes fine, then, you can find the find the application running on port **`8888`**. Enter the following URL to see it in action! [http://localhost:8888](http://localhost:8888).

>Note:  If the above command fails, it means that the app can't run on port **`8888`**. Try **changing the port number** from `server\index.js` in the Wittr directory to **any other number apart from** **`8888`**. Now repeat step **5** by replacing **`8888`** in the URL to the port number which you specified in `server/index.js`.

