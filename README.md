# Login with Google

### ->Hyperlink to google login page(createURL() function defined in googleOauth.js)






# Forgot Passwoord

### ->Redirect to forgot password page

                        "/forgotPassword" route is called

### ->useMutate() is called 
            login() is called 
                        sendLogin() is called 
                                    post request made,returns profileId and token
                                    #### ->sdfcasc

            On success,onLogin(profileId) is called 
                                    "/" is pushed to history     

            Else  

                                    set setShowModal("VERIFY EMAIL")  pushes "/" to history
                                   
# SignUp

### ->A hyperlink tag that will lead to Signup page

                        "SignUp" route is called

### ->onClick() function
        if onSignUpClick() is not empty
                        function is called which  will return setShowModal("VERIFY EMAIL") 
                
        else            
                        push "/signup" path to history

            


