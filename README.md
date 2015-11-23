# Certification overview

##Introduction

Talking about needs of certifcates and encryption in the internet world (know the end points of communications and make them tamperproof). Motivations of the paper :

1. Comparative review of three methods (X509, PGP and SKIP)
2. Issues of those methods
3. Evaluation for other existing or to be developed methods
4. Identify improvements
5. Safety guidelines for users when resolving certificate issues
6. Impact on Internet security transactions due to Gov. policies

##Certification methods

Why do we need to use certification methods : who is the sender, who is the receiver, are they really are who they pretend to be?
Presenting the solutions that are central to the paper :
1. Directory method : X.509 and CA
2. Referral methods : PGP
3. Collaborative methods : SKIP

##X.509 and CAs

###Description of the different entities

1. CA : can be public (like banks with clients), commercial (like Verisign) or private (like internal departement of a compagny, to log user)
2. Subscriber : sends some infos to the CA to add it to his certificate
3. User : ask infos to CA(s), it's central to the process, since the user party is relying on the informations and is thus at risk

###Concerns about the authentification services provided by CAs

1. The content of a certificate needs to be discussed, as well as certificate revocation
2. Issues about DN (Distinguished Name) and CA : a user can possess one or more DN, and use one or more DN on one or more DN
3. Validation of the user, using an ID, which is easily subject to fraud

Going deeper with user validation : DN scheme based on X.500 Recomendation, but it is not completly defined, and will (in 1998) probably not be. Also, X509 certification depends on many others such as ISO, ANSI, ITU and IETF. Thus lead to a lack of harmonization.
Plus, there is a big problem with CPS (Certification Practice Statements), that also can be seen such as flexibility (for pros), because each CA answer specific needs, so no harmonization again.

Some kind of conclusion about harmonization (lack of), in a world wide vision.

###List of the most important conceptual, legal and implementation flaws (16 of them).

[...]

##PGP

Euuuuuh...

##SKIP (Simple Key-Management for Internet Protocol)

