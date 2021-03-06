# 100 Days Of Code - Log

### Day 1: January 5th, 2021

 #### Read 100DaysOfCode Challenge article from: https://www.freecodecamp.org/news/the-crazy-history-of-the-100daysofcode-challenge-and-why-you-should-try-it-for-2018-6c89a76e298d/

 #### Forking this project

#### The main language I want to use is typescript. 

#### I'm planning to write some posts about the following things: reverse-proxy, docker, setup a typescript project as an executable script, and some more. Implementing the example repositories accordingly. 

#### But first of all I need to know how to be able to publish a post in one site that you already have, so I will start with that. 

### Day 2: January 6th, 2021

Today I'm trying to setup github as a site so I'm able to publish and tests the posts in local. To do that I'm following the steps indicated here: https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/testing-your-github-pages-site-locally-with-jekyll, but I am getting errors when I'm trying to install bundler and jekyll. 

### Day 3: January 7th, 2021

Solving another error to set up GitHub pages.

I've found the solution in this link:
https://talk.jekyllrb.com/t/cant-create-a-new-test-site-w-jekyll/1989/5

At the end it was executing: 'bundle add jekyll'

After that all the 7th step of:
https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/creating-a-github-pages-site-with-jekyll worked

Next step test github site in local, that was execute: bundle exec jekyll serve

But I got the following error:

> /usr/local/lib/ruby/gems/3.0.0/gems/jekyll-3.9.0/lib/jekyll/commands/serve/servlet.rb:3:in `require': cannot load such file -- webrick (LoadError)

The solution was execute the following command: ``` bundle add webrick ```

### Day 4: January 8th, 2021

Today I figured out how themes work in Github pages, because I change it and I started to have errors. As well, how updates on _config.yml affects to the whole site. 

### Day 5: January 10th, 2021

Followed the setup: https://jekyllrb.com/docs/step-by-step/01-setup/, to understand how github pages work.

### Day 6: January 11th, 2021

I selected a theme for Jekyll and I have updated it so the blog looks like I want to without creating a new theme from scratch. 

### Day 7: January 12th, 2021

I added the first version of a post in my blog. It's amazing how you want to investigate how to define the concepts when you need to explain them. 

### Day 8: January 13th, 2021

Today I added some more format to the posts remembering a bit of Bootstrap and publish the blog in a github domain: https://sendami-tech.github.io/sendamiTechBlog/

### Day 9: January 18th, 2021

Today I've been learning how to add tags to the posts following this link: https://longqian.me/2017/02/09/github-jekyll-tag/, but I'm not abble to have it working.

### Day 10: January 20th, 2021

Today I've been reading info about SEO, to understand how it works and how to design a website according to that. 
I have read the following articles:
* https://www.smashingmagazine.com/2019/05/vue-js-seo-reactive-websites-search-engines-bots/
* https://dzone.com/articles/how-to-make-vuejs-website-seo-friendly

### Day 11: January 25th, 2021
Today I've been investigating how to add comments to every post I'm publishing. 
To figure it out I needed to read the following posts:
* https://stackoverflow.com/questions/59096243/adding-comments-in-blog-posts-on-github-pages
* https://utteranc.es/?installation_id=14297767&setup_action=install

### Day 12: January 31st, 2021
Learning webhooks: https://www.youtube.com/watch?reload=9&v=41NOoEz3Tzc

### Day 13: February 1st, 2021
Still learning webhooks: https://github.com/sendami-tech/webhooks-course/settings/hooks/278965216

### Day 14: February 5th, 2021
Still learning webhhooks: Today updating them in actual code

### Day 15: February 15th, 2021
Finally I finished the learning webhooks course. A bit boring at the end as it was full of tools but no creating things from code.
As well I came back to Hackerrank. I did a test of 3 exercise to prove my coding skills, and I don't know what happened yet, well, I know. First, my mind works slowly lately, and I need to practise more. So I will plan to include more Hackerank in my week tasks. 

### Day 16: February 16th, 2021
Today I didn't do any code, I read an article from FreeCodeCamp. This one: https://www.freecodecamp.org/news/from-hackathon-to-cto-in-3-years/. It is indeed very interesting and as a consequence I'm planning to read these two books: The Phoenix Project: A Novel About IT, DevOps, and Helping Your Business Win and Effective DevOps: Building a Culture of Collaboration, Affinity, and Tooling at Scale. Lately, I've been doing lots of tooling at work and I really enjoy it. I want to learn more about it. 

### Days 17, 18, 19: February 17th, 18th and 19th, 2021
Las week I was trying to setup my blog with GitHub Actions so everytime I add a new post automatically this log and twitter was updated. After three days, it's still not working. I followed this post: https://github.com/marketplace/actions/send-tweet-action. 

### Day 20: February 24th, 2021
Attending AWS Innovate https://innovate-emea.virtual.awsevents.com/e/202317533/I%27m+an+Application+Developer. Trying to find a reason to learn more about ML, but I didn't have any luck. I didn't understand anything. 

### Day 21: March 12th, 2021
Learn how to publish my blog post based on github pages in a custom domain. https://www.namecheap.com/support/knowledgebase/article.aspx/9645/2208/how-do-i-link-my-domain-to-github-pages/
