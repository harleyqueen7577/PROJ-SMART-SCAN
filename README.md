## SMART SCAN
npm init
npm de skeleton avec "webpack et babel pour compiler sur tel"
npm install material-design-icons
npm install materialize-css@next
npm install --save html2pdf.js
npm install cropperjs
npx cordova platform add android@9 
npm install cordova-res
npx cordova plugin add cordova-plugin-splashscreen
npx cordova plugin add cordova-plugin-device 
npx cordova plugin add cordova-custom-config
npx cordova plugin add cordova.plugins.diagnostic

# OBJECT ORIENTED
 ## COMPONENTS

 ### HOME
 ```js
      home.component.js
      home.component.html
      home.component.scss

      class HomeComponent {
             
             constructor {

                 
             }

            display(){
                return.onclick{(this.start())}

            }

            start(){
                
            }
       }
```
### TAKE_PICTURE
```js
      take-picture.component.js
      take-picture.component.html
      take-picture.component.scss
      class TakePictureComponent {
          
          constructor {

          }

          display(){

          }

          startCamera(){

          }

          signalError(){
            // ou restart/displayHome

          }

          takePicture(){

          }

      }
```
### PREVIEW
```js
      preview.component.js
      preview.component.html
      preview.component.scss

      class PreviewComponent{
        
         constructor{

           }
         display(){

            }
     
         editPicture(){

         }

         savePicture(){

         }

         displayPicture(){
         //   to add
         }
      }
```
### SAVE
```js
      save.component.js
      save.component.html
      save.component.scss
     import {file} from ... 
    
       class SaveComponent{

         constructor(){

         }

         display(){
          
          format.onclick{(this.chooseFormat())}

          return.onclick{(this.displayPreview())}
             

         }

         saveOption(){

            // checkbox

         }

         chooseFormat( ){

            // use {file}
            // use this.saveOption()

         }

         displayPreview( ){



         }

       }

```
   - barreOptions + FormatText:















   
      
```js
      home.component.js
      home.component.html
      home.component.scss
```
      
      
```js
      send.component.js
      send.component.html
      send.component.scss
      import {file} from 
      class SendComponent{

          constructor{

          }

        display(){
          
          

        }

        
        chooseClient(){
        // is name ok?
        }



      }
```

    
