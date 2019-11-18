# Javascript Accessibility Podcast

## Questions for ‘What is Web Accessibility?’ podcast

### Format
1. Introduction
2. Let’s start with telling us a bit about your career and what you currently do within Allstate.
  * Nicholas
    - This answer could be a podcast in itself.. my first full time job was back in 98 and I've worked for companies large and small since then
    - I've have worked in the public sector, banking sector, insurance sector, a web development shop and a start up.
    - Now in Allstate I am in the FEE engineering team working with a development team om one of Alstates largest web property that has a very substantial userbase
  * Gareth
    - #### I worked for an ad-agency in Belfast as a Front-End Developer for my placement year of University. When I gratudated I then returned there for a few years before moving to Allstate last August.
    - #### In Allstate I am part of the Front-End Engineering team working alonside Nicholas on one of the largest and most used products the company produces.
3. When people talk about ‘Web Accessibility’ what exactly do they mean?
  * Nicholas
     - Web accessibility is the inclusive practice of ensuring there are no barriers that prevent interaction with, or access to, websites on the World Wide Web by people with physical disabilities, situational disabilities, and socio-economic restrictions on bandwidth and speed. When sites are correctly designed, developed and edited, generally all users have equal access to information and functionality.
     - Companies that create browsers such as google, apple, microsoft and mozilla spend a lot of money ensuring that your code renders on screen what you intended but when users are accessing your site by for example using a screen reader your source code may not convey the same details that can be parsed visually so its important to take into consideration Web Accessibility when creating your website
    - Equality Act 2010 
    - Duty to make reasonable adjustments for disabled people
    - A person ... concerned with the provision of a service to the public or a section of the public (for payment or not) must not discriminate against a person requiring the service by not providing the person with the service.
4. Why Web Accessibility is Important and how can you accomplish it?
  * Gareth
    - #### Web Accessibility is very important as some of you user base may not be able to use your site or product in a way you might expect them too. Due to various impairments some users will need to navigate your site or product using a screen reader among other technologies.
    - #### Another reason it is vitally important is that could possibly have a lawsuit on your hands if you don’t make the effort to include web accessibility in your applications. This happened to Domino’s Pizza in America after a blind man accused the company of discrimination after he couldn’t place an order online. This was in violation of a 1990 law that bans discrimination based on disability.
    - #### The WCAG (Web Content Accessibility Guidelines) sets a goal of providing a shared standard for web accessibility. The documents related to this explain how we can make web content more accessible to people with disabilities. It is also broken down into 3 levels depending on the situation. A being the lowest, AA being the mid-level and AAA being the highest and most difficult to comply with. The level you aim for depends on the needs of your application and end users. For the application we are currently working on we are aiming for AA and therefore will test against these standards. 
    - #### There are a few different ways to accomplish web accessibility. 
    - #### Firstly by ensuring that your mark-up is semantically correct by using the correct HTML so that technologies such as screen readers and browsers can better understand your intentions for the end-user. 
    - #### Secondly by giving context to your code if required. For example if you were dealing with multiple car insurance policies and a screen reader needed to read these out to a user, without having accessibility best practices in place, a screen reader would possibly not give context to each policy e.g. Policy, Policy, Policy vs Auto Policy 1, Home Policy 2, Life Policy 3.
    - #### Another way to accomplish web accessibility is to learn about the best practices and how you can implement them as a developer in your day to day coding. There are lots of very useful resources on the internet that help us understand how to add accessibility to our code such as WebAIM, the Ally (a11y) project checklist and the WCAG checklist.  Another great resource is the Allycasts (A11y) series from Google Chrome Developers on Youtube. It is a few years old now but is a really great introduction to understanding web accessibility. 
    - #### Another thing to consider is testing your accessibility changes through a host of tools that we will chat more on later. 
5. Can you describe the first project you worked on with web accessibility in mind?
  * Nicholas
     - going to say that although I would have always tried to keep sites readable and keep users in mind that this is the first time I have been involved in a substantial effort to fully comply with WCAG AA for every single facet of accessing a website for all users whether they are impaired or not.
     - In previous iterations of web development stacks you could view all your code and that made it easier to take into consideration accessibility considerations such as semantic HTML but with javascript framework single page app component based architecture you are maybe working on a component in isolation from the rest of the codebase and its harder to ensure that your component is accessibile in relation to the rest of the application at development time
     - although now we have so many ways to tackle accessiblity through unit tests, integration and end-to-end tesing, QA, screenreader testing, colour testing, etc
6. What are the needs that Web Accessibility aims to address?
 - Can you give some examples of Visual impairments?
   * Gareth
    - #### Visual impairments may include blindness, various common types of low vision and poor eyesight and also various types of colour blindness.
 - What about motor impairments?
   * Nicholas
      - This could take the form of a user not being able to use a mouse, when a user can't difficulty or inability to use the hands, including tremors, muscle slowness, loss of fine muscle control, etc., due to conditions such as Parkinson's disease, muscular dystrophy, cerebral palsy, stroke;
     - What about hearing impairments?
   * Gareth
    - #### Hearing impairments can include deafness or being hard of hearing. This can impact a user as they may not be able to hear dialog or music.
 - can you tell us a bit about cognitive impairments?
   * Nicholas
      - User has an issue with understanding complex language, Developmental disabilities, learning difficulties (dyslexia, dyscalculia, etc.), and cognitive disabilities (PTSD, Alzheimer's) of various origins, affecting memory, attention, developmental "maturity", problem-solving and logic skills, etc.
7. How do you go about understanding the users diversity?
 * Nicholas
    - This a tricky one to if you are not providing specialists software or a website that is specifically for users with impairments
    - The reason for this is that Screen readers aren't user agents so they won't be picked up by analystics software as a screen reader but will instead as safari for example. So your google analytics won't show a certain percentage as screen readers or voice assistance
    - I would say the best approach would be to consider your users diversity to be a reflection of the percentage of the general population that have an impairment of some type
    - You can build this into any statistics you generate about your browser support, we as front end engineers will spend a lot of time ensuring that our sites display the same across all browsers as we would not want to exclude a significant  percentage of our users based on what browser they use. So it is worth the effort then also to make sure your site works for users whether they have a visual impairment, motor impairment or any other type of impairment
8. As UI engineers, how can you make the web more accessible?
 * Gareth
   - #### We can help make the web more accessible by always thinking about web accessibility when working on anything web related. We can aim to write code that enhances web accessibility by following the standards set and also from various resources across the internet. We should also test the code we write against web accessibility standards, there are some tools available for this that help create a good process for writing web accessible code. We will touch on those soon.
   - #### Also I feel it is important to keep learning about web accessibility when you can. It is something that’s principles may not change too much but as technology grows and evolves so will the need for a more accessible web for everyone. There are some great resources that we spoke about earlier that would enhance any UI Engineers understanding of web accessibility.
   - #### I also believe that we can act as teachers for web accessibility. Even if we have a little bit of knowledge on web accessibility we should try and share that with those we work with if possible. For a front-end developer this could be with designers, developers and project managers. It would help them understand the importance of web accessibility and why we should take care to ensure it is implemented in any application.
9. What Web Accessibility Tools are available for developers?
 * Nicholas
 - Unit Testing - axe-core from Deque
 - End to End Testing - axe-webdriverjs for selenium, cypress-axe for react cypress 
 - Chrome DevTools tools - Accessibility Tab in the Styles Windows
 - Chrome extensions - site improve, axe, lighthouse 
 - Manual TestingScreen readers, Narrator for windows, NVDA for windows, Voiceover for mac - https://webaim.org/articles/voiceover/  
 - Visibility Colour Contrast - color contrast analyzer, site improve accessibility checker
10. What assistive technologies are used for web browsing?
 * Gareth
   - #### Technologies used for web browsing may include screen readers, speech recognition and screen magnifiers.
   - #### Screen readers may be used by users with visual impairments such as blindness and low vision. Technologies used my include:   
   - #### JAWS – can be expensive but seen to be one of the leading screen reading technologies.
   - ####	NVDA – an open-source tool that’s is provided by a non-profit called NV access. 
   - ####	Windows Screen reader – built into Windows OS.
   - #### VoiceOver – built into MacOS and iOS.
   - #### Talkback – built into Android devices.
   - #### Speech recognition may be used by users with mobility issues to use voice commands to operate technology. Technologies used may include: 
   - #### Windows Speech Recognition.
   - #### iOS Speech Recognition/Siri.
   - #### Android Speech Recognition/Google Assistant.
   - #### Captioning tools such as YouTube – uses machine learning to create captions for the video.
   - #### Screen magnifiers may be used by users with visual impairments such as limited vision. Technologies may include:
   - #### Most browsers will have a zoom tool
   - #### Text size on OS can be increased  - MacOS, Windows, iOS, Android
11. What guidelines are available for the developers and designers?
 * Nicholas
    - WCAG - Web Content Accessibility Guidelines - https://www.w3.org/WAI/standards-guidelines/wcag/
    - WAI ARAI Practices - Web Accessibility Initiative - Accessible Rich Internet Applications - https://www.w3.org/TR/wai-aria-practices/example
12. Accessibility can’t fall on one person’s shoulders. It’s a collective involvement throughout
your organisation and projects. Do you agree?
 * Nicholas, Gareth
   - #### Yes, accessibly is for everyone to consider. The more people who are aware of its importance the more it would become a normality to consider it in day to day work. 
   - #### From designers and developers to testers and project managers, everyone has an input into moving towards a more accessible web, whether that entails colour contrast issues for designers to resolve or giving your application more context for disabled users so they can better understand the applications intentions. It’s also important that accessibility is tested before it goes out to production to ensure that users with impairments are getting the best possible experience of your application.
 
## Example of sites with great accessibility
 - https://www.citizensadvice.org.uk
 - https://www.gov.uk/
 - https://www.bbc.co.uk/
 - https://www.starbucks.co.uk/
 - https://www.airbnb.co.uk/

## Statistics
 - 13.3 million people in the UK have some kind of disability
 - 8% of men and 0.5% of women are colour blind
 - 10% of the UK population are dyslexic
 - Over 2 million people in UK live with sight loss
 - 19% of the UK population have a hearing loss – of which 6.5 million are over 60 years of age
 - 1.5 million people in the UK have a learning difficulty
 - 2.4 million people in the UK have a manual dexterity issue

## Image

![alt text](https://user-images.githubusercontent.com/1111211/69015722-d7dfdd00-098e-11ea-98be-3b787eced0b2.png)
