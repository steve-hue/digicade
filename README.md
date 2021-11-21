# Login with Google

### ->Hyperlink to google login page(createURL() function defined in googleOauth.js)




# Forgot Passwoord

### ->Redirect to forgot password page

### ->useMutate() is called 
            -->login() is called--> sendLogin() is called -->post request made,returns profileId and token

            On success,onLogin(profileId) is called 
                                    "/" is pushed to history     

            Else  

                                    set setShowModal("VERIFY EMAIL")  pushes "/" to history
            


