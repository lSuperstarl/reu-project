# reu-project

## SSL Certificate 
- copy `.keystore` and `server.xml` into `conf/` directory of apache installation
- change `keystoreFile` path variable in `server.xml`

## Links
- configure apache tomcat w/ SSL: https://medium.com/analytics-vidhya/a-step-by-step-guide-to-apache-tomcat-with-ssl-configuration-8e407bc6b503
- add self-signed certificate to android (technique 1): https://www.netspi.com/blog/technical/mobile-application-penetration-testing/four-ways-bypass-android-ssl-verification-certificate-pinning/
- android emulator networking (10.0.2.2 for computer's localhost): https://developer.android.com/studio/run/emulator-networking
- Use self-signed certificates w/ okhttp: https://blog.codavel.com/accepting-self-signed-certificates-in-okhttp3#:~:text=CertPathValidatorException%3A%20Trust%20anchor%20for%20certification%20path%20not%20found.,-view%20raw%20gistfile1&text=The%20errors%20listed%20above%20basically,entity%20trusted%20by%20the%20client.

## Connection settings (linux)
- database url: `jdbc:mysql://localhost:3306/cybersafe?serverTimezone=UTC`  
- make sure table names are capitalized
- make sure ip address in apiHandler class corresponds to one on `enx**` interface

## JSON library
- https://search.maven.org/remotecontent?filepath=org/json/json/20230618/json-20230618.jar
