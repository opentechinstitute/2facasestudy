1. The Distant Past
    1. Idea developed out of One Time Pads for bankers - add a "test word" to the cipher to demonstrate authenticity
    1. Bellovin, 2011
    1. Bank card + pin
1. The Digital Age
    1. Ad hoc solutions
        1. Are there examples of ad-hoc solutions prior to standardization?
        1. Patented applied for 1984, granted in 1988 - [RSA Key Patent](https://www.google.com/patents/US4720860)
        1. First sold in 1986 - [Press Release Announcing 10 millionth Key Sold](http://www.itweb.co.za/index.php?option=com_content&view=article&id=90940)
        1. Mostly used by enterprises to secure access to corporate systems
        1. No IETF standards for another 20 years, why not? What algorithm was RSA using?
    1. Standardization
        1. IETF RFC 4226 (HOTP 2005) and RFC 6238 (TOTP 2011)
        1. RSA spreads 2FA to other devices in 2006 - [RSA Press Release](http://www.prnewswire.com/news-releases/rsa-security-to-enable-ubiquitous-authentication-as-rsa-securidr-technology-reaches-everyday-devices-and-software-55317397.html)
        1. Initial release of Google Authenticator (Apps for Domains): September 20, 2010 [TechCrunch Article](http://techcrunch.com/2010/09/20/google-secure-password/)
        1. Subsequent release for consumer accounts: February 10, 2011 [Google Blog Post](https://googleblog.blogspot.com/2011/02/advanced-sign-in-security-for-your.html)
    1. Spread of access
        1. Google Authenticator and the server side software it works with are initially open source
        1. And based on open standards from IETF
        1. Google encourages other sites to implement?
        1. 2013, Google closes source on Authenticator, though it is still interoperable with third party HOTP and TOTP servers
        1. 2013, FreeOTP launched to provide open source alternative. Also existing is OTP Authenticator
        1. Not all services use an Authenticator app
            1. Twitter uses the Twitter app, Steam uses Steam app
            1. Some services use SMS (talk about unique issues regarding interception)
        1. Public pressure mounts
            1. [Two Factor Auth](https://twofactorauth.org/) lists who does and doesn't support. Has twitter links to tell sites that don't have it that you want it.
            1. Chris Soghoian makes a name by calling on people to turn on 2FA [ACLU Blog Post](https://www.aclu.org/blog/five-ways-keep-your-data-safe-right-now) and [Bloomberg Article](http://www.bloomberg.com/news/articles/2013-04-11/how-to-secure-your-online-identity-by-the-aclus-christopher-soghoian)
            1.

Gmail China hack timing?
Twitter turn on?
Facebook?
Etc?
Matt Honan article?
@deray hacked in 2016 on SMS
Still succeptible to phishing
U2F next step
