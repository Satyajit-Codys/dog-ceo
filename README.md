# Dog-ceo API

## Author Name : 
   Satyajit Debnath
## Application Name : 
  Dog-ceo

## Objective : 
  To Make an Applicaton where user can different kinds of Breeds of Dogs. 

## Technology used :
   React
## Description :
   This is a React app with email & password login/register/Google Login after which
the web app shows the list of all the breeds from the dog.ceo API and also a detail page
which shows a random image for the picked dog (from the list). Also, shows a
logout button.
    The web app is robust enough so that if the user (logged in) exits the
browser and opens it again he should be automatically logged in without asking for
his/her email/password.This Application is responsive for desktop as well as Mobile view.
 All the details of the Explained below.
               
## Key Features : 
       
*  Sign up and Login has been done using Local Storage .
*  Google Login has been used to let the user login using their Google Account.(oauth2.0)
*  User's Login session has been maitain using token based login system .
*  The App is fully responsive for any kind of Device .

## Hosting Link : 

https://dogceo.herokuapp.com/

## Explanation : 
     
      --> First User have to Sign up with thie credential in this Application .His information will be stored 
          in the localstorage.
     
      --> Then,User have to log in to this App using same credentials . This App will validate and login inofrmation 
          with local storage.Login Authentication has been done using token-login .After the login,if he exits the browser.
          Next time when the User come App will show him as logged in.Login session is maintained .
         
      --> User can login with using their Google Account .No need to Sign up . Application will do oauth verification
          of the User and will redirect to the Home Page. For Google Login purpose 'react-google-login' package has been
          used.
         
      --> After that It will redirect to the Home Page ,Where All the breeds of Dogs and their small Images
          will be Displayed to the User.and one log out butoon will be displayed.
      
      --> If User Clicks  any breeds .It will Redirect to a page where User can see see the image of Dog in detail.
          In this page Random image of that breed will generate by clicking the "change" button
       
      -->  User cannot route with the help of URL .Authenticaton has been done.
     
      --> Log out button is there to log out from the Google Account .
     
                   
               







