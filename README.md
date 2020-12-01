# CSRF-Protection-Double-Submit-Cookies
Cross-site Request Forgery protection in web applications using double submit cookies pattern<br>
Login credentials : <br>
  username: admin <br>
  password: 1234qwerty <br>
  
 enter any value to the text field in welcome.php and submit.<br>
 form will be submitted along with the csrf token generated based on session id of the particular form <br>
 if the submitted token is available and matched with the generated token you will see the Demo.php <br>
 click logout to logout from demo. <br>
 
 Known issues: had an error in fetching csrf token from welcome.php to demo.php <br> 
