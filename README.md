# Dirk Heniges
[LinkedIn](https://www.linkedin.com/in/dirk-heniges-10465219)  
[Github](https://github.com/dheniges)

A most-likely outdated overview of public code fun and work.

You'll find me coding in ruby and javascript mainly. PHP happens when the need arises :)

# Open Source Contributions

## Ruby

Most of my Ruby work is on lockdown and unshareable. However, I have a few projects publicly available:

**Drive-Writer**  
An incomplete rails 4 app that integrates with the Google Drive API and uses Google oauth for sign-in.    
[Drive Writer](https://github.com/dheniges/drive-writer)

**ResumAPI**  
A fully functional Rails 3 based REST API for resumes  
[ResumAPI](https://github.com/dheniges/resumapi)

**Steamworks**  
An attempt at a Ruby game utilizing [Gosu](https://www.libgosu.org/)  
[Steamworks](https://github.com/dheniges/steamworks)

**Chompy**  
[Chompy](https://github.com/dheniges/chompy) is a hipchat bot.



## Node.js

**Liquid Node**  
We started using Jekyll as a quick way to build out training courses, and the plan was to build an import of a Jekyll site into our platform. So we needed to support liquid rendering in node.js. At the time, the liquid-node lib did not support file `includes` so I started porting the functionality over to liquid-node. This was my first foray into CoffeeScript.  
[Commit History](https://github.com/dheniges/liquid-node/commits/master)

**Passport SAML**  
For SSO integration, I've used passport-saml. Unfortunately the lib seems to have lost a maintainer, so a bugfix I wrote to handle inclusive namespaces in the XML parsing of a SAML response hasn't been merged into the upstream project.  
[Local PR](https://github.com/dheniges/passport-saml/pull/1)  
[passport-saml issue](https://github.com/bergie/passport-saml/issues/164)


## PHP (Drupal)

While at Seabourne working on FCC.gov, we were able to open source a number of
modules, sponsored by FCC.gov.

**ContentAPI**  
The module is a plug-and-play way to expose all of your Drupal content via API.
I coded the original implementation, and then FCC.gov sponsored open-sourcing the module 
so my team cleaned it up and posted it on Drupal.org  
[ContentAPI](https://www.drupal.org/project/contentapi)

**SlashMaps**  
Integrate MapBox maps directly into Drupal.
I did the work to open source this, other folks wrote the original code.  
[SlashMaps](https://www.drupal.org/project/slashmaps)

**LayoutManager**  
This was an early attempt to making custom layouts easy in Drupal.
This was a team effort from multiple folks, including myself.  
[LayoutManager](https://www.drupal.org/project/layout_manager)


