![barner2](https://user-images.githubusercontent.com/66249668/114359667-2d81de80-9baf-11eb-86a6-1589f6d65334.jpg)
### Hi there 👋, my name is yusuke from JAPAN

---

##### Most of the time I'm using R and python to handling data, but I also curious about new technologies, such as React(javascript web development). This is why you can also find my React and vanillaJs projects in my github.👋

---


### Programming Languages

<p float="left">
  <img alt="R" src="https://img.shields.io/badge/r-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white"/>
  <img alt="Python" src="https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white"/>
  <img alt="NodeJS" src="https://img.shields.io/badge/node.js-%2343853D.svg?style=for-the-badge&logo=node-dot-js&logoColor=white"/>
  <img alt="JavaScript" src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
  <img alt="HTML5" src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"/>
  <img alt="CSS3" src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white"/>
  <img alt="C++" src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white"/>
</p>


### Frameworks and libraries

<p float="left">
 <img alt="Django" src="https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white"/>
 <img alt="DjangoREST" src="https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray"/>
 <img alt="OpenCV" src="https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white"/>
 <img alt="React" src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB"/>
 <img alt="Express.js" src="https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB"/>
 <img alt="Bootstrap" src="https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white"/>
 <img alt="Material UI" src="https://img.shields.io/badge/materialui-%230081CB.svg?style=for-the-badge&logo=material-ui&logoColor=white"/>
</p>

### Databases 
<p float="left">
  <img alt="Postgres" src ="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img alt="MongoDB" src ="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white"/>
</p>

### IDEs / Editors
<p float = "left">
 <img alt="Visual Studio Code" src="https://img.shields.io/badge/VisualStudioCode-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white"/>
 
</p>

### Hosting 
<p float = "left">
  <img alt="Heroku" src="https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white"/>
  <img alt="Firebase" src="https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase"/>
</p>

### ML / DL

<p float = "left">
  <img alt="PyTorch" src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white" />
  <img alt="Pandas" src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white" />
  <img alt="NumPy" src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white" />
</p>

---
## R
 - [DAG] : Reinforcement Learning

   - ##### purpose :  create DAG (Directed Acyclic Graphs) 
   - ##### score function : AIC(Akaike information criterion) / BIC(Bayesian information criterion)
   - ##### Algorithms :  Hill Climbing Algorithm 
   - ##### Core methods : choose score function, and proceed hill climbing argorithm( randomly add arc and caluculate score ... , check more details [DAG] .)

  
  

 
 [DAG]: https://github.com/TokyoProgramming/path_analysis_hill_climbing
 


## python 
 - #### pure python projects

    <!---just
    - [data_processing]
 
    [data_processing]: https://github.com/TokyoProgramming/data_processing
    
     --->
     
     
    
    - [password_generator]
      - what you can do ...
        - set number of Passwords which you need , and password's length   
        - the output is such as like this

    ```
    passwords = pass_generate(5, 9) # 5 passwords have 9 degits in length
    passwords
    ```
    
    ```
    ['5KO68x7W5', 'D2JdGkFRw', 'R8xaTUtz8', '2VOwUoNsa', 'Wr358HC7r']
    ```
 
 [password_generator]: https://github.com/TokyoProgramming/password_generator

 - #### deep learning
    - [RNN_LSTM] Covid-19 Twitter Text data - 78.9% accuracy
        - total data shape = (41157 ,3)
        - train data shape = (28809, 3)
        - test data  shape = (12348, 3)
    

   


    |                     | Extremely Negative  |  Negative | Neutral | Positive |  Extremely Positive | 
    | :------------ |:---------------:| -----:|:------------ |:---------------:| -----:|
    | Extrememly  Negative | 1068 | 470  | 8    | 25   | 1   |
    | Negative             | 206  | 2343 | 134  | 312  | 10  |
    | Neutral              | 3    |  121 | 1992 | 171  | 5   |
    | Positive             | 5    |  240 | 202  | 2792 | 251 |
    | Extremely Positive   | 1    |  12  | 10   | 422  | 1544|

    [RNN_LSTM]: https://github.com/TokyoProgramming/Corona_NLP 
    - [Regression] Cancer data Diagnosis - 95% accuracy 
        - total data shape = (569, 31)
        - training data shape = (398, 31)
        - test data shape = (171, 31)
    

    | Predicted / Actual    | 0  | 1 |
    | :------------ |:---------------:| -----:|
    | 0     | 105 | 3  |
    | 1      | 5  | 58 |
    
    [Regression]: https://github.com/TokyoProgramming/Cancer_Predict
    
    - [openCV]  Car_detection
      - car_classification_trained model + openCV API 


    ![project_example](https://user-images.githubusercontent.com/66249668/120982186-61ded900-c7b3-11eb-9048-d1ba528e1458.gif) 
    
    [openCV]: https://github.com/TokyoProgramming/opencv_car_detection/tree/master
    
    
    - pygame RPG: coming soon
    
 ## React
 
 - [Chat_App] (MERN) 

[Chat_App]: https://github.com/TokyoProgramming/ChatApp_MERN_pusher

 - [facebook_UI]
 
 [facebook_UI]: https://github.com/TokyoProgramming/facebook__clone 
 
  - [tiktok_UI]
  
 [tiktok_UI]:https://github.com/TokyoProgramming/tiktoc_clone___react_firebase
 
 - [youtube_UI]

 [youtube_UI]:https://github.com/TokyoProgramming/youtube_clone__react_firebase
 

## Vanilla javascript 

- [ChessApp] 

  - description : <br/>
This app is created by HTML5, CSS3 and vanilla javascript!!  
As you know, European Chess is well known board game all over the world.  
In this time, I covered basic movements of all the pieces(pawn, rook, knight, bishop, queen, king) and judge whether game is over or not (checkmate function).  
There are special movemnets in the specific situation in the game which was covered in this projects, such as Castling(both kingSideCastling and QueenSideCastling are covered in this app), pawnPassant and PawnPromotion.  
<br />

Go to check the projects: [ChessApp]

[ChessApp]:https://github.com/TokyoProgramming/ChessGame-vanillaJS

- [SudokuSolver] 

[SudokuSolver]: https://github.com/TokyoProgramming/sudoku-solver-2
