# cryptbook
ONLINE SOCIAL NETWORKS AND PRIVACY – LEVERAGING CRYPTOGRAPHY TO GAIN CONTROL 

This project researches the state of online social networking platforms in regards to privacy with a focus on Facebook. 

In addition it discusses existing and, in the context of social networks and mobile phones, novel mitigation techniques that enable users to take control and prevent unauthorized users from accessing their social networking data. A mobile application, codenamed “Project Cryptbook” is implemented that leverages client side encryption capabilities before posting information to the social network. This will prevent the social networking platform or other users, who do not possess the appropriate decryption key, to recover the plaintext message. 

In addition to encryption, Project Cryptbook enables signing capabilities for posts, which further improves the security of the user accounts and the integrity of messaging on the social network. If an account gets compromised, the attacker is not able to post on a user’s behalf because the victim’s private signing key is not accessible from within the social network.

The mobile application is implemented for Windows Phone 7. 

I built this in 2011 as part of my MSc at the University of Liverpool, so they code is outdated and prototype like.

Greetings,
Johann Rehberger.




ABSTRACT - ONLINE SOCIAL NETWORKS AND PRIVACY – LEVERAGING CRYPTOGRAPHY TO GAIN CONTROL 

Online Social Networking platforms allow their customers to store and share information. A user might want to store information for themselves or share data with a small group of people, like family and close friends, or potentially everyone in the world. Users store personal information in online social networks and hence privacy aspects become relevant. If a user wants to keep certain information private or limited to a small audience, the user should be able to control that.

If an attacker compromises a social networking account, the attacker is able to read messages and post new information on the user’s behalf. In such a scenario, the attacker is impersonating the user and the user has no privacy control over his or her personal information.

Furthermore, a user may not trust how a service provider protects their data and may therefore prefer not to store information in clear text with the social network. If the clear text data is leaked, anyone can read it, regardless of whether the leak happened accidentally or through vulnerability in the service.

Encryption and signing techniques can enable advanced use scenarios for online social networking platforms to secure content. Social networks provide programmatic interfaces to query and post information. This opens up the avenue for social network client applications that encrypt and sign data before submitting such data to the social network. The main goal of this project is to research the privacy aspects of social networking platforms (in particular Facebook) and provide mitigation techniques that will help end users protect their data beyond what social networks currently provide.

In particular, a mobile phone application, codenamed “Project Cryptbook” is discussed and implemented that allows users to encrypt information before posting the information to the social network. Even if the data accidentally becomes accessible to a third party, the third party will not be able to decrypt such data without the correct decryption key. Additionally the prototype allows seamless decryption of the encrypted information to provide access to the intended recipient.

ONLINE SOCIAL NETWORKS AND PRIVACY – LEVERAGING CRYPTOGRAPHY TO GAIN CONTROL By JOHANN REHBERGER A DISSERTATION Submitted to The University of Liverpool in partial fulfillment of the requirements for the degree of MASTER OF SCIENCE 26/11/2011
