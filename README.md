# framework_test
TASK 2: selectors

Scouts Panel ==> //*[@id="__next"]/form/div/div[1]/h5
                 //h5[@class="MuiTypography-root MuiTypography-h5 MuiTypography-gutterBottom"]
                 //child::div/h5

Change Language ==> //*[@id="__next"]/form/div/div[2]/div
                    //div[@class="MuiInputBase-root MuiInput-root MuiInput-underline jss6"]
                    //*[@id="__next"]/form/div/div[2]/div
                    
Login Btn  ==>    //*[@id="__next"]/form/div/div[2]/button
                  //*[text()="Zaloguj"]
                  //button[@type="submit"]
                   
