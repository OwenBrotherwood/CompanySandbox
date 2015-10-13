[![Stories in Ready](https://badge.waffle.io/OwenBrotherwood/CompanySandbox.png?label=ready&title=Ready)](https://waffle.io/OwenBrotherwood/CompanySandbox)
[![Stories in In Progress](https://badge.waffle.io/OwenBrotherwood/CompanySandbox.png?label=in progress&title=In Progress)](https://waffle.io/OwenBrotherwood/CompanySandbox)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/OwenBrotherwood/CompanySandbox?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

Work in progress @ https://polar-savannah-1404.herokuapp.com/explorer/ 

# CompanySandbox
A little exercise for myself to check the status of LoopBack(something old) as to how quickly it is possible to understand and produce a result from the latest version. I would also like to test Xamarin as a IDE(something new) with Loopback . I may see if I can reuse the Loopback examples(someting borrowed) as reference and of course, reevaluate StrongLoops Build, Deploy and Scale(something blue) in order that a scalable solution is obtained.

The result of this little Sandbox should hopefully land in a Docker on Heroku. 

## Basic Data
A basic data definition is usually needed for any little sandbox. I often have to deal with events from devices inside a company: often multiple companies reporting to a central focal point. So I pick a little part of the general model of an a company in which any specific details of events or transactions or whatever can be hitched on.

### Company
* Company ID
* Name
* Address
* City
* Country
* E-mail (not required)
* Phone Number (not required)
* One or more directors and beneficial owners: contacts. 
  * Probably  a use case for another data model but I will see

## Inteface
One thing I want is AAA and may look at Auth0 to see if it is still as easy as last time I looked at it: depends how it fits with Loopback

### API
Some API for insert update and delete. Swagger documentation a must.

### "Human Interface"
See how easy Xamarin is to create a human interface. Xamarin is something I want to look at due to C#, new Loopback support and general interest. Although I will probably make a simple HTLM5 version.

