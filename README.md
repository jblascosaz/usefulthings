# usefulthings
Useful data from internet

► Comprar WETH en Ronin con FIAT
https://www.youtube.com/watch?v=mVgwiAPTMT0

► Freak's Axie Extension:
https://chrome.google.com/webstore/de...

► Axie Breeding Calculator:
https://freakitties.github.io/axie/ca...

► Axie Breeding Simulator:
https://axie.zone/breeding-simulator?...

► Excel Calculadora de Costos - Breeds:
https://docs.google.com/spreadsheets/...

► Excel Niveles más Worth (EXP+SLP):
https://docs.google.com/spreadsheets/d/1wW-_addB3Ja4r5OOm1Rd9lX2gz1XgL0hnZTwBN_2jAc/edit#gid=1187747329

https://open.spotify.com/playlist/6ogbg9BFwnSLNkNMn7NrfF?si=uF8jiCqZRpuE6U2eFWt4BQ&dl_branch=1

https://open.spotify.com/playlist/7gkzLJUad4X8R4er1aFNam?si=ckZigX7vQEeYwrIsRvAG2g&dl_branch=1

BGBF4D8F1873

       public WebElement findElement(By locator) throws Exception {
             WebElement element = null;
             try {
                    element = getDriver().findElement(locator);
             } catch (Exception e) {
                    e.printStackTrace();
                    takeErrorScreenshot(getDriver(), "findElement");
//                  getDriver().close();
//                  getDriver().quit();
                    if(debug) {
                           throw new Exception(e);
                    }
                    throw new Exception("\nCan't find element "+locator);

             }
             return element;
       }

             Select nombreSelect = new Select(findElement(xpathSelect));
             nombreSelect.selectByValue("1");
