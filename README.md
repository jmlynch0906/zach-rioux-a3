
## Build Instructions

To run this demo experiment locally, you will need to install node on your computer. 

* Clone `https://github.com/revisit-studies/study`
* Run `yarn install`. If you don't have yarn installed, run `npm i -g yarn`. 
* To run locally, run `yarn serve`.
* Go to [http://localhost:8080](http://localhost:8080) to view it in your browser. The page will reload when you make changes. 

## Release Instructions

Releasing reVISit.dev happens automatically when a PR is merged into the `main` branch. The name of the pull request should be the title of the release, e.g. `v1.0.0`. Releasing creates a tag with the same name as the PR, but the official GitGub release should be created manually. The `main` branch is protected and requires two reviews before merging.

The workflow for release looks as follows:
Develop features on feature branch
| PRs
Dev branch
| PR (1 per release)
Main branch
| Run release workflow on merge
References are updated and commit is tagged

## Assignment Details

Link to the study: https://zrioux10.github.io/zach-rioux-a3/?tab=Others 

<img width="706" alt="Screenshot 2025-03-06 at 11 59 24 AM" src="https://github.com/user-attachments/assets/98448734-5802-4891-9210-106c096894f4" />

Description of our study:
Our study consisted of 12 questions for participants to answer. The idea of this study was to create dots like in a heatmat where two are marked. The objective is to estimate the percentage of the lighter dot relative to the darker dot. In the screenshot above from our tutorial, we show participants the box they will input their value into and three examples with the correct answers shown. At the end of the study, we asked participants three questions to gauge if there were any difficulties with the wording or image shown. A few individuals reported difficulties understanding the wording of the study, and others wanted to see examples of benchmarks for the percentages. Overall, the results were positive.

Below are the 12 visualizations we tested, ranked from least accurate to most accurate.  
12:  
![12: Green visualization 4](https://github.com/jmlynch0906/zach-rioux-a3/blob/2de53e24fab62cd46290795d7d8d241f1e61e3b3/test%20screenshots/green4.png)  
11:  
![11: Blue visualization 1](https://github.com/jmlynch0906/zach-rioux-a3/blob/2de53e24fab62cd46290795d7d8d241f1e61e3b3/test%20screenshots/blue1.png)  
10:  
![10: Red visualization 4](https://github.com/jmlynch0906/zach-rioux-a3/blob/2de53e24fab62cd46290795d7d8d241f1e61e3b3/test%20screenshots/red4.png)  
9:  
![9: Blue visualization 4](https://github.com/jmlynch0906/zach-rioux-a3/blob/2de53e24fab62cd46290795d7d8d241f1e61e3b3/test%20screenshots/blue4.png)  
8:  
![8: Green visualization 2](https://github.com/jmlynch0906/zach-rioux-a3/blob/2de53e24fab62cd46290795d7d8d241f1e61e3b3/test%20screenshots/green2.png)  
7:  
![7: Red visualization 3](https://github.com/jmlynch0906/zach-rioux-a3/blob/2de53e24fab62cd46290795d7d8d241f1e61e3b3/test%20screenshots/red3.png)  
6:  
![6: Red visualization 2](https://github.com/jmlynch0906/zach-rioux-a3/blob/2de53e24fab62cd46290795d7d8d241f1e61e3b3/test%20screenshots/red2.png)  
5:  
![5: Red visualization 1](https://github.com/jmlynch0906/zach-rioux-a3/blob/2de53e24fab62cd46290795d7d8d241f1e61e3b3/test%20screenshots/red1.png)  
4:  
![4: Green visualization 1](https://github.com/jmlynch0906/zach-rioux-a3/blob/2de53e24fab62cd46290795d7d8d241f1e61e3b3/test%20screenshots/green1.png)  
3:  
![3: Blue visualization 2](https://github.com/jmlynch0906/zach-rioux-a3/blob/2de53e24fab62cd46290795d7d8d241f1e61e3b3/test%20screenshots/blue2.png)  
2:  
![2: Blue visualization 3](https://github.com/jmlynch0906/zach-rioux-a3/blob/2de53e24fab62cd46290795d7d8d241f1e61e3b3/test%20screenshots/blue3.png)  
1:  
![1: Green visualization 3](https://github.com/jmlynch0906/zach-rioux-a3/blob/2de53e24fab62cd46290795d7d8d241f1e61e3b3/test%20screenshots/green3.png)  

While the results seem relatively mixed, the blue and green heat maps seemed to be the most and least accurate. The red heat maps had medium accuracy. More testing may need to be done to see if this phenomenon is a result of our study or an actual result of the colors.
Design Achievements:
- Use and modification of reVISit (we thought this would give the best results)
- Help button brought the participant back to the tutorial
- Closing study questions for further iterations to improve the study if it was done again

Technical Achievements:
- Heatmap coloring for questions
- Color on results graph is mapped to the question it came from  

