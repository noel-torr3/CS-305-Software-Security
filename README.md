# CS 305 Software Security

## Artemis Financial Portfolio Reflection

### Client and Software Requirements

For this project, I worked with Artemis Financial, which is a financial consulting company. They wanted to make their application more secure and make sure sensitive information was better protected. My job was basically to look for security issues and make changes to improve the security of the application.

### Software Security and Vulnerabilities

I think I did a good job using more than one way to look for vulnerabilities. I did a manual review, but I also used OWASP Dependency-Check to scan the dependencies for known vulnerabilities. Secure coding is important because even one vulnerability can potentially put company or customer information at risk. This is especially important for a financial company because people are trusting them with sensitive information.

### Challenges and Helpful Parts

One of the harder parts for me was getting Dependency-Check to actually work correctly. I ran into errors while setting it up and had to troubleshoot them before I could get a successful scan. Even though it was frustrating at times, it ended up being helpful because I got more experience using an actual security tool instead of only reading about vulnerabilities.

### Increasing Layers of Security

I added more security to the application by setting up HTTPS, generating a self-signed certificate, and using SHA-256 for the checksum. I also used Dependency-Check to scan the application's dependencies. In the future, I would probably use both automated tools and manual code review again because they can find different types of problems. The way I would fix a vulnerability would depend on what the problem is and how serious it is.

### Functional and Security Testing

After making the changes, I made sure the application still worked. I was able to run it using HTTPS on port 8443 and tested the checksum to make sure it was generating correctly. I also ran Dependency-Check again after making changes so I could check the dependencies for
