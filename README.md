# Anqi-Wu-Senior-Project
## Library downloads
1. The Layui Library can be downloaded from [Here](https://layui.itze.cn/)
2. The Swiper Library can be downloaded from [Here](https://www.cdnpkg.com/Swiper/file/swiper.js/)
3. The Javascript Library can be downloaded from [Here](https://www.cdnpkg.com/jquery-cookie/file/jquery.cookie.min.js/)
4. The PHPExcel can be downloaded from [Here](https://download.csdn.net/download/zqd76/10743168?utm_medium=distribute.pc_relevant_download.none-task-download-2~default~BlogCommendFromBaidu~Rate-3-10743168-download-75534937.topnsimilar_compare_v2&depth_1-utm_source=distribute.pc_relevant_download.none-task-download-2~default~BlogCommendFromBaidu~Rate-3-10743168-download-75534937.topnsimilar_compare_v2&dest=https%3A%2F%2Fdownload.csdn.net%2Fdownload%2Fzqd76%2F10743168&spm=1003.2020.3001.6616.3)
## Instructions
1. Drag all the entire Web Scraper folder to Pycharm 
2. Import the libraries that are on the top of each .py files
3. Download the ChromeDriver from [Here](https://chromedriver.storage.googleapis.com/index.html). Make sure the chromedriver version is the same as your chrome version.
4. Follow the [instructions](https://www.youtube.com/watch?v=-stXyMIrsck) to set up the chromedriver.
5. Run each .py files and you will obtain 5 excel files: redfin.xlsx, schoolInfo1.xlsx, weatherHigh.xlsx, weatherLow.xlsx. (Be aware that this step might take a very long time)
6. Drag these 5 files to the Jupyter folder. I already have the generated excels stored under the Jupyter folder， which also contains a blank excel and a cities.xlsx that needed for the data manipulation. If you want to regenerated these files by your own, delete the one that has the the same name in the Jupyter folder, then drag the new one in.
7. [Download Anaconda](https://www.anaconda.com/products/distribution) if you have not done so. 
8. Launch the Jupyter Notebook through Anaconda -> find the Jupyter folder -> open the .ipynb file
9. Run through the SeniorComp.ipynb file line by line to check out the data visualization and the data manipulating process. After running through this file, it will generate three new excel files in the Jupyter folder: final1.xlsx, final2.xlsx, and index.xlsx
10. The three files generated by step 9 will become the dataset for the City Picker website (they are located under the files folder in the City Picke folder).

## User Interface
- One way to check out the website is to [download MAMP](https://www.mamp.info/en/downloads/) as the local server environment -> run it (make sure the Anaconda is completely closed to avoid failure) -> drag the entire City Picker folder to the htdocs folder under MAMP -> copy and paste 'http://localhost:8888/City%20Picker' to the search bar.
- The second way is to click [Here](https://anzowu527.000webhostapp.com/), which I hosted my website using [000webhost](https://www.000webhost.com/).