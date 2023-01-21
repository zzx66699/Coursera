# Chapter1 Marketing analytics foundation

## 1. What a marketer should do?
- Market/consumer research
- Create promotional content
- Marketing planning 
- Campaign optimization
- Evalution campaign effectiveness

## 2. What is marketing analytics
measuring and analyzing data to inform, evaluate, and improve the performance of your marketing initiatives.  
- identify target audience
- planning and forecasting
- evaluating marketing effectiveness
- marketing optimization
  - adjust your marketing mix
  - optimize within a channel
  - use testing to optimize 
- optimize the sales funnel (reduce the number of people drop out)
  - awareness  
  - interest   
You just don't get your message across or don't explain the benefits of your product very well.   
That may mean you have to change your advertising message.  
  - decision   
Competitor have more attracted offer, or they may have a better message and people may decide to buy their product instead.
  - action   
There's friction in the checkout process for instance, like on a website that's hard to navigate or that does not work well on a mobile phone.
 
## 3. Type of data
### 3.1 Offline data
- contact form
- loyalty program
- survey
- POS (point of sales 销售点)   
Offline data can also be tracked through point of sale information, when your customers make a purchase. You learn what product they bought, the date, any amount they spent.  
- call center
- in-store tracking

#### What they can do with offline data
- understand in-store traffic
- calculate customer lifetime value
- plan inventory
- product recommendation

### 3.2 Online data
- social media insight (facebook & ins)
- website insights (google analytics & adobe analytics)
- online business (shopify)
- sign-up for newsletter / loyalty program / feedback questionnaires
- third-party database (nielsen / comscore)
know their competitors information, user demographic data
- social listening tool 
know people outside their audience think about their brands

## 4. Online interaction generate data
- Every publisher website starts with a blank canvas made of code and stored on a web server.  
- To fill this canvas, the publisher uses a tool called content management system, CMS. It enables publisher to store, create, and manage content on their websites.
- The publisher will leave some space on the website for advertising. Ads server will place the ads.
- When person's browser requests a web page from the publisher, some data about a person is sent to the publisher. That information is used to bring the right content to the person, but it's also sent to the Ad server to make sure a relevant Ad is displayed. 

## 5. Source of digital data
### 5.1 Web server log
A server record of a person and a website or app  
- user's ip address
- a unique identifier  
  This identifier is typically pulled from the person's browser and is usually a sequence of characters. Note, that this is not personally identifiable information also referred to as PII. So, no names or physical addresses are stored here.   
- username 
- date and timestamp
- content request 
- http status code(200 for success and 404 for fail)
- size of content  
<img width="474" alt="image" src="https://user-images.githubusercontent.com/105503216/212895125-66e7923c-9164-468e-8996-41f4d85aa46d.png">

### 5.2 Cookie
 A formatted piece of text that gets stored in a person's browser.    
Web and ad servers can store some information about your interaction in a special storage area in your browser. When you interact with content from the same publisher or advertiser later, the publisher can call up the information it's stored in your browser to help it remember a few things about you and your previous interactions.  

- First-party cookie  
text files stored in your browser by the sites that you're actually visiting. 

- Third-party cookie  
text files stored in your browser by a third party with whom you don't have a direct relationship.    
there may be an advertiser who stores some information in your browser while you visit a news site.   
The advertisers can do that because it has an ad showing on the news site you are visiting

#### 5.2.1 Cookie related problems
- People use multiple devices and browers
- can be erased or blocked
- can't work on mobile apps

#### 5.2.2 Example of cookie
Present people who hesitate to subscribe with a coupon on their next visit.   
- when people access the Calla & Ivy website, a cookie is added to their browser. It stores information about a user's visit to the site and it stores whether people accessed the page that describes the subscription.   
- when people leave the site and come back at a later point, the cookie will help recall that this person had already been to the site and had shown an interest in the subscription.   
- If that is the case, a large overlay with the coupon comes up on the page the user is visiting, encouraging them to subscribe and get the free bouquet.

### 5.3 Tags/pixel
Small piece of code that instructs website to send information to a third party(google analytics).   
The code is added by the publisher.  
<img width="440" alt="image" src="https://user-images.githubusercontent.com/105503216/212913164-389d43ea-c187-437b-8bd2-c3f5e942d335.png">

### 5.4 SDK(software developer kit) for mobile apps
The toolbox contains code developers can install to help create applications. In some ways, you can think of it as a library of ready-made code that makes the life of the developer easier.  
- apps on your phone where you were asked to log in with your Google or Facebook account  
- Instead of manually programming a way for you to log in, developers would use the Facebook SDK, which has code they can implement in their app to let you log in with your Facebook credentials.  
- By having your users log in with their Facebook ID using the SDK, some data is sent back to Facebook. This makes it possible for you to see things like whether people who saw an ad on Facebook for your gaming app, download your app. And, you could even see whether these people are more likely to make in-app purchases, like purchasing extra powers inside your game, for instance.  

<img width="864" alt="image" src="https://user-images.githubusercontent.com/105503216/212917267-86afcefc-9dc6-4ac3-9ed7-cc3379f0ae44.png">

### 5.5 API(application programming interface) 
a tool that establishes a connection between two pieces of software.   

The marketing takes place using one system, like advertising using Google for instance. But behavior we want to influence takes place on other, a purchase on a website, an app download, a purchase in a store, and so on. 

#### 5.5.1 Example of API
- Owners can connect their instore customer management software to the Facebook API. 
- every time a purchase is made in-store, data can be sent to Facebook. Based on some information that may be known about the purchaser, like the email address for instance, it may be possible to link the purchaser to a known Facebook user Id.  
- team can then assess whether the purchaser saw an Instagram ad and may thus have been influenced by that ad to make a purchase.


### 5.6 UID(Unique user id)
It is a unique text or number string that identifies a person and it is created when the user logs in.   

The UID makes it possible for publishers to link behavior from a person on different browsers and on apps so that it's possible to get a clearer and more complete picture of the users across platforms. 

### 5.7 Device ID
- In both iOS and android, an ID is stored in the settings of the device and that ID can be accessed by advertisers if the user allows it.   
- When users interact with advertising in an app and they have opted in to share their device ID with advertisers, it makes it possible for the advertisers to advertise to you across different apps. 
- they can show ads and track behavior on one app, like Instagram for instance, and then use that information to advertise to you while you're using a different app.   
<img width="224" alt="image" src="https://user-images.githubusercontent.com/105503216/212923069-e57942d0-e4d9-4671-95be-e3b46d0117ac.png">
