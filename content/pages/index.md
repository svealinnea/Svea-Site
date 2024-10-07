---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: >-
      Welcome to My Netlify Take-Home Project
    subtitle: >-
      Below is the answers to the specific questions asked in the prompts
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
    type: HeroSection
    actions: []

  - colors: colors-f
    type: TextSection
    elementId: ''
    title: How I Built This Site
    subtitle: >-
      I used the netlify next.js template to build this site, I was interested in building using this because I have played around with it a little bit but not as much as I would like to. One challenge I came across was that I had a grand idea of tabbing out all the questions so that they would be in the header, but then my daughter woke up from her nap and for the sake of time I decided it would be best to probaby just have everything live on the main page.
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
      title:
        textAlign: left
      subtitle:
        textAlign: left

  - colors: colors-f
    type: TextSection
    elementId: ''
    title: Thoughts on Netlify
    subtitle: >-
      For me, deploying the site was seamless, I was able to get it up and running in no time. I really appreciated how on the overview page on netlify there is a section called Set up your site, I like how that section walks you through all the neccesary next steps like setting up a custom domain and securing your site with HTTPS. I would also eventually love to explore the logs and site analytics at some point but obviously that is not in the cards for this exercise.
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
      title:
        textAlign: left
      subtitle:
        textAlign: left

  - colors: colors-f
    type: TextSection
    elementId: ''
    title: 5 favorite and 5 least favorite Activities
    text: >-
      Favorites:
      1. Develop a code example to share with a customer
      2. Dig through server logs to troubleshoot a customer's website behavior
      3. Suggest and champion improvements to the Support team's workflow
      4. Help train and onboard new support teammates
      5. Submit bug reports and potentially bug fixes

      Least Favorite:
      1. Engage multiple users at once via chat to answer their questions and troubleshoot problems
      2. Respond to Netlify customers on Twitter
      3. Work with a customer to figure out if Netlify's service can solve a particular workflow or integration challenge they have
      4. Work with prospective customers to explain our service and the pricing model
      5. Help manage communications during a service outage
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
      title:
        textAlign: left
      subtitle:
        textAlign: left

  - colors: colors-f
    type: TextSection
    elementId: ''
    title: Documentation Example
    text: >-
      I recommend the Smart Car API https://smartcar.com/docs/api-reference/intro for its ease of use and the features that it provides, not only can you use this to lock, unlock a car but you can also use it to check out the charging behavior of the car and the odometer or even tire pressure. I have implemented this in the past and the docs are so well written and the support team is readily available that if someone wanted to create a custom app to lock and unlock their car if they forgot their keys somewhere or wanted to remotely check in on their tire pressure this is a great resource to do so!
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
      title:
        textAlign: left
      subtitle:
        textAlign: left

  - colors: colors-f
    type: TextSection
    elementId: ''
    title: DNS Configuration Challenges
    subtitle: >-
      Two major challenges for less-technical customers are honestly just the unfamiliaroty of it all, when you are changing DNS records in Wix or another platform reading the instructions can feel overwhelming because of all of the technical jargon but the beauty of it is that once you get through the steps its really just a matter of copying and pasting the needed changes. I really do think for less technical folks it is just the unkown. I remember having to teach my husband this and once he realized how it really it just copying and pasting he felt much more confident that he could do it on his own in the future, Another challenge I think is the time it can take to update the records. When working with DNS configurations it can take awhile to see those updates and for someone who is unfamiliar that can probably feel a bit overwhelming and they may give up or think something is wrong when the process is just not quite finished.
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
      title:
        textAlign: left
      subtitle:
        textAlign: left

  - colors: colors-f
    type: TextSection
    elementId: ''
    title: Troubleshooting Customer Issue
    subtitle: >-
      First I would look through slack, netlify docs or other resources at my disposal for that particular error code ( Build failed due to a user error: Build script returned non-zero exit code:) to see how we have resolved this issue for customers in the past by looking at old tickets, etc. If that did not produce anything valuable or help me figure out my next steps I would probaby reach out to the customer and maybe ask them what changes they have made that caused the site not to build, had the site been built in the past? I want to see if this is an issue where the user has never been able to get their site to build on netlify or if it possibly has to do with a breaking change that they have made recently.
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
      title:
        textAlign: left
      subtitle:
        textAlign: left

  - colors: colors-f
    type: TextSection
    elementId: ''
    title: Customer Response
    text: >-
      Thank you for reaching out and letting me know about the issue with your site not building. I completely understand how frustrating it can be when things aren’t working as expected, and I’m here to help! I noticed from the build logs that there was an error indicating a "user error" with a non-zero exit code: 2. This usually points to a problem with the configuration. Since your repository is private, I can’t look directly at the code, but I’d love to work with you to figure this out. Could you share if you made any recent changes to your project? I’m also happy to provide resources or documentation that might assist you as you troubleshoot this. Please don’t hesitate to reach out if you have any questions or need more support—I’m here for you!
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - colors: colors-f
    type: TextSection
    elementId: ''
    title: 301 redirect
    text: >-
      according to this doc: https://docs.netlify.com/routing/redirects/#syntax-for-the-redirects-file you would add the following code to your netlify.toml file
       `[[redirects]]
        from = "/netlify/anything"
        to = " https://www.google.com/search?q=anything"
        status = 301
        force = false
        query = {path = ":path"
        conditions = {Language = ["en"], Country = ["US"], Role = ["admin"]}`
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
      title:
        textAlign: left
      subtitle:
        textAlign: left

  - colors: colors-f
    type: TextSection
    elementId: ''
    title: Security Incident
    text: >-
      First I would try and see if i could replicate the issue, if I couldnt I would reach out to someone who could and tell my manager of the report. In order to show the reporter that we are on top of things I would respond by saying: "Thank you so much for reaching out and sharing this security concern, I have escalated this to the appropriate parties and we are working diligently to solve this, our users and their data is of the utmost priority to us. We will keep you in the loop on our progress towards a resolution." I would escalate this issue to my managers and suggest that we get this information out on a broader channel, whether slack or otherwise in case more reports of the same come in. Also I would recomend that we shut down the portion of the site with the security risk and facilitate an engineer video chat to talk through remediation steps. It is important that we have someone documenting all communication and resolution actions so that we have a clear idea on what went down when we work through a retrospective at some point. I think that if the security threat is real, making sure that none of our users are impacted is of the utmost priority and if that means we need to shut down part of the site, so be it.
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
      title:
        textAlign: left
      subtitle:
        textAlign: left
---
