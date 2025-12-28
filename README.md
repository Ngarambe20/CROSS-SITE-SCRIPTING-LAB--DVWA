# CROSS-SITE-SCRIPTING-LAB--DVWA
Cross site scripting lab on DVWA 

Objective

The objective of this lab is to understand how Cross-Site Scripting (XSS) vulnerabilities occur in web applications by using the Damn Vulnerable Web Application (DVWA) in a controlled environment. The lab demonstrates how improper input validation allows client-side scripts to execute in a user’s browser

Tools Used

Web browser (Firefox)

DVWA

Local VM

Findings and Observations

At Low security, DVWA does not validate or sanitize user input

User input is reflected directly into the HTML response

This allows client-side script execution

Increasing the security level reduces or blocks the vulnerability

Proper input handling significantly improves security

Conclusion

This lab demonstrated how Cross-Site Scripting vulnerabilities arise when applications fail to properly handle user input. DVWA provides a safe environment to understand XSS behavior and reinforces the importance of secure web development practices.




