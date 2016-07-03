# D3 charts in Ember
  1. I'm Matt Payne.  I'm excited to connect with you.
     1. [@MattPayneOrg](https://twitter.com/MattPayneOrg)
  1. TALK URL HERE use gh pages!
  1. I’ll present [Sophie DeBenedetto](https://twitter.com/sm_debenedetto)’s blog post [“Using Ember Charts to Integrate D3.js into your Ember App”](http://www.thegreatcodeadventure.com/using-ember-charts-to-integrate-d3-with-ember/) for five to six minutes. She created [Who-ipedia](https://whoipedia.herokuapp.com/): an [ember front end](https://github.com/SophieDeBenedetto/whoipedia-front) with [rails serving an api](https://github.com/sophiedebenedetto/whoipedia-api). I’ll present her work and my brief experience with it. This talk will set you up to start enjoying Sophie’s wonderful work.

---

# Screen shot of the bubble chart

---



## Quickstart
  1. Read Sophie's blog, for an overview.  Plan to return later.  [SQ3R](https://en.wikipedia.org/wiki/SQ3R) FTW
  1. `git clone front end`
     1. `cd front-end`
     1. `npm install`
     1. `bower install`
     1. `ember serve`
     1. http://LocalHost:4200 -- note it is using Sophie's heroku server :-(

---

## Get your own server!  -- Prerequisites      
  1. Launch http://postgresapp.com
  1. Install ruby on rails....
     1. `\curl -sSL https://get.rvm.io | bash -s stable`
---

   
  1. git clone back-end
     1. cd back-end
     1. bundle
     1. bin/rake db:setup # Behold all the data it scrapes!
     1. bin/rails s
  1. Edit front-end as described in the README.md to point at your backend on localhost.   Don't forget to change the https to http.  
     1. ember serve
     1. `rails c` or `psql` etc to change the data....
     1. TODO(MGP): Try this!!

## Walk through Sophie's blog:
   1. D3 can be used via the xyzzy component
      1. pre-configured with a few things.
      1. https://github.com/Addepar/ember-charts  
      1. Demo at http://output.jsbin.com/zujifu/
         1. My copy at http://jsbin.com/zujifu         
