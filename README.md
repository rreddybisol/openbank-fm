# openbank-fm
Openbanking framework - postman collection
Open Banking Gateway
Provides tools, adapters and connectors for transparent access to open banking apis. The initial effort focuses on the connectivity to banks that implement the European PSD2 directive either through one of the common market initiatives like : The Berlin Group NextGenPSD2, The Open Banking UK, The Polish PSD2 API or even through proprietary bank api like the ING’s PSD2 API.

What this Project is about
Tackle the Key Challenge for Third Party Providers of Payment Services
The European PSD2 as the first regulator driven Open Banking initiative offers many opportunities for both banks, known as traditional provider of payment services (called ASPSPs in this context) and other Third Party Providers of payment services (TPPs). TPPs can use account information and payment services provided by banks to offer new innovative services to bank account holders. The more banks and TPPs can interact with each other, the more payment account holders can be provided with reacher banking solutions, which in turn simplifies and leverage commercial value chains.

Being able to interact with different banking APIs can be a time and cost consuming challenge. Even though the PSD2 requires European/MENA banks to provide APIs and despite the effort of market initiatives to provide common standard interfaces, there is still a multitude of divergent authorization schemes involved and a lot of space for implementation options. A bank can even decide not to join one of the known market initiatives and define it's own PSD2 compliant API.

The purpose of this open banking gateway is to provide the community with a common and simple interface for accessing major Open Banking APIs.

Introducing the FinTech as a Major Role
Being a regulator driven initiative, PSD2 mandates the regulation of TPPs. With this additional detail, the market is experiencing a distinction between regulated TPPs and non regulated FinTechs. This framework is therefore designed taking in consideration the existence of the category of payment service providers called FinTech that used APIs exposed by a regulated TPP to access payment services exposed by banks.

Address Security Issues associated with PSU Access to Multiple Interfaces
In the Open Banking Context, a payment service user (PSU or banking account holder) might have to deal with up to 3 different user interface to initiate, authorize and get the requested banking service executed. There being redirected back and forth from one UserAgent (resp. device) to another. This intensive use of redirection in Open Banking bearing a lot of risk of impersonating the PSU, we set a goal of this Framework to dissect the complexity involved with those redirection processes and open forums for discussion of possible solutions and sample implementations. Following papers are the first attempt to capture the problem (UserAgent Redirection, PSU Access Security Design).
