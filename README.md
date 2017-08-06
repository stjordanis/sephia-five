
# Sephia Five - Military grade cryptography for the people

Sephia Five is a web server based email system, that among other things features military grade PGP cryptography, so ridiculously easy to use, that we refer to its design principles as KISS - _Keep It Simple and Stupid_.

Security starts with simplicity. Unless something is simple, it can never be secure. Complexity in the user interface makes people do erronous things. Simplicity eliminates a lot of these pitfalls, and such becomes a guarantor of security. When you open up Sephia Five, you are by default only presented the choices, that are the actions you most likely want to do. Two buttons, period! Compare our UX to that of GMail or Outlook, and you will realise the value of _"less is more"_.

![alt screenshot of Sephia Five](media/screenshots/screenshot-1.png)

The squid button, will toggle more options for you, allowing you to search your emails, page back and forth, access your settings, etc - But by default, these choices are hidden, to create as little _"cognitive noise"_ for you as possible.

## Security is more than cryptography

Most intrusions and data leaks occurs due to human behavior. Kevin Mitnick often referred to himself as a social engineer, and not a hacker, since he would primarily take advantage of human weakness, instead of launching a direct attack on a computer system. Medio 2017, the Norwegian government had a huge data leak, which created a lot of problems to the Norwegian minister of fish Per Sandberg. The reason was that a fishing tycoon had sent an email to _"per.sandberg@gmail.com"_ instead of _"persandberg@gmail.com"_. The guy who owned this email address, informed Norwegian media, and the scandal was a fact. There were raised concerns about corruption, and the minister of fish had a very rought time. I don't think poor Sandberg particularly enjoyed having his private emails dissected on the front page of some of Norway's largest news papers.

![alt screenshot of Sephia Five](media/screenshots/screenshot-2.png)

In Sephia Five you will be thoroughly warned if you attempt to send an email to somebody who is not on your list of contacts, largely eliminating these types of problems.

## Virus elimination

Sephia Five can be configured to be 100% secure in regards to virus and malware, never allowing an attachment that could potentially contain malware to be downloaded to the client. By default unfortunately, some attachments such as PDF files, which actually are responsible for more than 50% of malware in email attachments, are notoriously popular in use. We have solved this by having two types of _"whitelists"_ for attachments. One list of 100% safe attachments, such as images and text files, which will be downloaded immediately. Another list that will warn the user when he or she tries to download a file, that could potentially contain malware.

![alt screenshot of Sephia Five](media/screenshots/screenshot-3.png)

You can easily configure yourself which files are legal, illegal, and suspect. But the default configuration, would probably be good enough for most installations.

## Privacy is more than avoiding data theft

99% of all emails that are composed with rich HTML, are ads and distractions, intended to steal your attention. Microsoft once conducted research in this area, and found that even the smallest distractions, would destroy 23 minutes of productive work. In Sephia Five, we have simply eliminated the ability to render HTML emails. Unless an email has an alternative plain text view, Sephia Five will simply not show it. This will reduce the amount of _"cognitive noise"_, and allow you to enjoy your privacy, and stay more focused within your zone.

![alt screenshot of Sephia Five](media/screenshots/screenshot-4.png)

Compare the above email to your latest email from YouTube, and you will understand what this implies for your privacy.

## Hollywood spam filter

In Hollywood there is a saying - _"Don't call us, we'll call you"_. In Sephia Five we have created a spam filter according to these ideas. If you wish, you can turn on the Hollywood spam filter, which means that you will never again have an email from a person whom you did not send an email to first.

![alt screenshot of Sephia Five](media/screenshots/screenshot-5.png)

You can create exceptions to the above rule, for explicitly chosen email adresses.

## Time slots for reading email

_"Innocent distractions"_ are one of our primary productivity thieves. Often these can be social emails, sent by coworkers or friends, intended to allow people to socialise and interact with each other. In Sephia Five we have solved this by allowing you to declare at which times during the day its users are allowed to check for email. If an employee or user attempts to check his email outside of these times, Sephia Five will simply not check for email, and not allow him to update his or her inbox.

This allows you and your employees to _"stay in the zone"_, and focus on the task at hand, without distractions. This can of course be configured on a per user and role basis, and filtered according to the user's role. This allows you to for instance have your sales staff be able to check their emails all the time, while your system developers can only check their emails 08:00, 12:00 and 15:00 for instance.

If a user tries to check his email outside of his allocated time slots, he will simply not receive them.

## PGP miltary grade cryptography KISS

When Edward Snowden fled to Russia, he was communicating with journalists using PGP cryptography. Bruce Schneier once said _"PGP cryptography is the closest you come to military grade cryptography in the public space"_. PGP is however unfortunately ridiculously complex to use for people who are not computer geniouses. In Sephia Five we have reduced the complexity of using PGP cryptography, to the point where it almost automagically happens.

![alt screenshot of Sephia Five](media/screenshots/screenshot-6.png)

In Sephia Five we will even _"babelize"_ the subject line, by encrypting the original subject, and inserting a randomly fetched subject. This _"babelized"_ subject will be automatically fetched from a news provider, such as the New York Times, Wall Street Journal, or any other website you wish to use as a _"babelizing service"_. For an adversary picking up on your conversation, the email will be perceived as an innocent discussion about some random news article - While it could actually be a conversation between the US President to his minister of defense, carrying nuclear rocket launch codes, without any adversary having as much as a single suspicion.

With Sephia Five you can also create PGP key pairs up to 8192 bit strength, implying that every single super computer on the planet, would need billions of years working together, to be able to decrypt as much as a single byte from the original email!

![alt screenshot of Sephia Five](media/screenshots/screenshot-7.png)

Look carefully at the above screenshot, and notice the smiley. A happy face implies that the email was sent encrypted, and that it was cryptographically signed, with a private PGP key, that you have verified belongs to the one who claims to own it.

If you print your PGP fingerprint on for instance your business cards, then anyone you meet, and hand out a business card to, can easily verify that an email conversation has been cryptographically secured between you two.

To cryptographically sign a public PGP key, upload it to a key server, using the features of the _"web of trust"_, has literally been reduced to a happy face, and a sad face. And whenever anyone sends you a cryptographicall signed email, Sephia Five will automatically fetch that key from a public PGP key server. All this will happen automatically, leaving you with only occassionally having to look through your contacts, and verifying their fingerprints.

![alt screenshot of Sephia Five](media/screenshots/screenshot-8.png)

Basically, as long as you receive a happy email, you can be 100% perfectly confident on that the communication have been cryptographically secured. If you receive a neutral face email, you can be almost certain, but not entirely of that the communication is secured. If you receive a sad face email, you might as well start communicating using postcards.

The above screenshot also illustrates a crucial point, which is that every time Sephia Five requires you to carefully think before you act - It will show you a red warning. This is in fact the only use of colors we have in Sephia Five by default, which further reduces _"cognitive noise"_.

## Compose your emails using Markdown

Although Sephia Five does not accept HTML emails, you can still apply formatting to your emails using Markdown. This allows you to easily create some simple formatting to your text, by writing your emails using Markdown.

In addition, Sephia Five also supports something we have invented ourselves, which we are particularly proud of, which we refer to as _"conversations"_. Conversations allows you to keep the context in your email replies, by having Sephia Five automatically deduct who said what, as you bounce an email conversation back and forth a couple of times.

![alt screenshot of Sephia Five](media/screenshots/screenshot-9.png)

Sephia Five will accept any Markdown, but still _"wash"_ all emails it displays for any potentially malicious HTML elements, such as script inclusions, etc.

## Extreme availablity without compromising security

Even though Sephia Five is first of all built to be secure, it is also extremely easy to use, and has extreme availability. If you wish, you can set it up on a web server, and access your emails from any device you own, regardless of where you are in this world. If you combine this with SSL, you can have the convenience of reading your email from anywhere you might be in the world, while still having bullet proof cryptography protecting your privacy.

**Disclaimer** - It is crucial that you setup your web server to only serve Sephia Five over SSL if you allow access to it over the general internet. Otherwise, all the security measures we have created for you, are pointless!

Since Sephia Five is loaded within an SSL context, this means that once you close your browser window, nothing stays cached in your client. So even if somebody physically steals your phone, tablet or computer - They will still not have access to your emails, which are safely stored on your server.

If you can secure your server, Sephia Five can secure your emails, such that the only way an adversary could gain access to your emails, would be to physically break into your office or home, and steal your server. Needless to say, but this trait of Sephia Five, significantly reduces your risk when communicating with clients, friends, and partners.

Not even the private PGP key is stored on any of the clients you use to read your emails. All your data, including your private PGP key, is safely secured on your own personal server, which you can secure in your home or office.

The database used to store your PGP key pairs is GnuPG, which the German government believed so strongly in, that they chose to sponsor the project with government money to help maintain. Every third party component used in Sephia Five, is what is recommended as best practices for seuring your communication and data.

## Extreme usability

Sephia Five is carefully created to be as easy to use as possible. For instance, in Sephia, you can read multiple emails at the same time, and go back and forth between them, while replying to multiple emails, and composing several new emails at the same time.

This allows you to cross-reference content from multiple emails, empowering you in your communication, without having to juggle multiple browser windows. You can even perform a search for an email, open that email, perform another search, page back and forth several times, for then to open up another email - And the email you opened up originally will _"stick"_, and still be open.

![alt screenshot of Sephia Five](media/screenshots/screenshot-10.png)

These features of Sephia Five, gives you an enhanced user experience, allowing you to work the way you wish to work - And not the way some software vendor's limitations forces you to work.

## Bandwidth consumption

Sephia Five is ridiculously small in its bandwidth consumption. This implies that it will load faster over very slow internet connections, compared to other web mail clients. Below is a graph showing the difference in bandwidth consumption between GMail and Sephia Five.

![alt screenshot of Sephia Five](media/bandwidth-comparison.png)

For the record, less is more, and smaller is better.

## Do not trust us!

Even if somebody points a gun to our heads, we couldn't disclose any of your secrets. Most security vendors starts out their sales pitch with the words _"trust us, we know what we're doing"_. I betcha Judas told Jesus the same words. With us however, trust is a technical implementation feature, and an intrinsic part of our business model, implying that you'd never have to trust us, since you could yourself prove that what we are saying is accurate.

First of all, Sephia Five is open source, and does not contain as much as a single closed source component. All the way from the core of Linux, to MySQL as its database, to Sephia Five itself. Which means that what we say, can be verified by any technically savvy system developer, wanting to verify our claims.

In addition, we will never host your data or Sephia Five installation. In fact, even if you begged us to, we would refuse! This means that even if an adversary where to physically break into our office, put a gun to our head, and force us to disclose your secrets, we would simply have to answer him; _"Shot us, we cannot to do what you are asking, it is simply impossible"_.

The reasons why, is because contrary to many other email providers, we do not offer hosting. We simply offer you the tools, to setup your own server park, giving you 100% control over your own data. And even if we were to help you setup your own server, we would demand of you that you change any server passwords and such, after we have finished setting it up.

The director of Intel once famously said _"Only the paranoid will survive"_. We are survivors, are you ...?

## Getting started

If you wish to try out Sephia Five, you can download it from [this link](https://github.com/polterguy/sephia-five/releases). For a simple test, you can use it in combination with Visual Studio, Xamarin, or Mono Develop. In addition, you will need to have MySQL installed.

1. [Download Phosphorus Five](https://github.com/polterguy/phosphorusfive/releases) 
2. [Download Sephia Five](https://github.com/polterguy/sephia-five/releases)
3. [Download Micro](https://github.com/polterguy/micro/releases)
4. [Download System42](https://github.com/polterguy/system42/releases)
5. Put the unzipped _"micro"_, _"sephia-five"_ and _"system42"_ folders into the _"p5.webapp"_ folder inside of your Phosphorus Five folder. Make sure you rename the _"system42-xx-yy"_ folder to be named **only** _"system42"_.
6. [Download MySQL](https://dev.mysql.com/downloads/) -You will probably want to download also the MySQL Workbench, in addition to the core database.
7. Create a database in MySQL, name it e.g. _"sephia"_.
8. Modify the connection string in the _"web.config"_ file, inside of the Phosphorus Five folder called _"p5.webapp"_ to point to your MySQL database.
9. Open up the _"p5.sln"_ file in either Visual Studio, Xamarin or Mono Develop and start your debugger.

When System42 have started, create a server salt, a root password, and open up _"Apps/CMS"_, and create a new _"lambda"_ page, by clicking the _"+"_. Click the _"Settings"_ button, and make sure you use the _"empty"_ template. Paste in the following code into the CodeMirror Hyperlambda code editor.

```
sys42.utilities.execute-lambda-file:@SEPHIA/launch.hl
```

Click _"View page"_ and enjoy your privacy.

### Using Sephia with your GMail address

Sephia Five's default configuration, points to GMail's POP3 servers and SMTP servers. This means that as you start up Sephia Five, and go through the setup process - The only thing you'll have to do, to test it, is to supply your GMail username and password, and Sephia Five will immediately start using your GMail address.

You might have to make sure you enable POP3 access for your GMail account, but Sephia Five's setup process will guide you through these steps.

![alt screenshot of Sephia Five](media/screenshots/screenshot-11.png)

If you use Sephia Five in combination with your GMail address, all your email will still be perfectly encrypted and safe, and not even the employees of GMail can read your email. Not even the subjects of your emails.

### Using Sephia without a web server

Although Sephia Five is a web server email system, you could still install it locally on e.g. something such as a Linux laptop, having Apache and MySQL running in the background, with mod_mono mappings to get Apache to serve your ASP.NET web application. If you do, you could simply create a shortcut on your desktop that points to _"localhost/xx"_, and Sephia would open up in your browser, running your local website. We are currently working on creating an automatic Debian based packet repository, that would significantly reduce the complexity of this setup process. However, for the time being, unfortunately you're on your own if you wish to create such a configuration.

When we have done this though, to install Sephia Five on either a Linux laptop, or a Linux web server (Debian based), would imply nothing else than simply add our repository to your packet manager, choose Sephia Five, and start the installation process.

### User management

Sephia Five is a multiuser system (obviously), and we provide a _"professional addon"_ to Sephia Five, which allows you to manage your users. This module is not open source, since we too need bread and butter. However, if you would want to create multiple users for your system, you could do this with the _"Executor"_ in System42, by typing in something like the following, and evaluating it.

```
p5.auth.users.create:some-username
  password:some-pa$$word
  role:super
```

However, if you would want to have a more easy way to manage your users, we would be happy to talk to you about our professional user module. If so, feel free to toss our CTO an email at thomas@gaiasoul.com.

The user management module, also features a lot of additional features, such as the ability to _"lock out"_ users from Sephia Five, run some diagnostics, in addition to that it easily allows you to manage your existing users, within the comforts of a nice GUI, easily accessible for any _"root"_ account on your system. For a professional company, with multiple employees, this would provide a highly more convenient way of managing your users and your Sephia Five installation. We also provide professional support and help, in addition to installation help for companies and organisations who purchase our user management module.

## Getting professional help

The creators of Sephia Five, are providing professional services, and helping companies and organisations to setup Sephia Five. If you wish to speak with us about our commercial offerings, or need help to initially secure your email server, you can contact our CTO at thomas@gaiasoul.com. We only ask two things of you.

1. Change all your server passwords after we have initially setup your server
2. [Read this](https://gaiasoul.com/2017/08/05/how-to-become-a-customer-of-us/), and realise we mean business!

Kind Regards,

Thomas Hansen

![alt screenshot of Sephia Five](media/snowden.png)


