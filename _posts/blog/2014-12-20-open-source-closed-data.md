---
layout: blog
categories: 
  - blog
title: "Open Source, Closed Data"
description: "One problem organizations have faced in the past when opening up their data is that, well, the data has to remain closed. For example, data with either HIPAA or FERPA provisions is pretty much stuck in a closed state. Furthermore, many organizations are reluctant to open up certain datasets. However, all hope is not lost - this post will advance the idea of Open Source, Closed Data and present several implementation strategies."
date: 2014-12-20
author: Hunter Owens
author_url: https://twitter.com/hunter_owens
author_image: /images/people/hunter_owens.jpg
author2:
author2_url:
author2_image:
published: true
---

<p>One problem organizations have faced in the past when opening up their data is that, well, the data has to remain closed. For example, data with either <a href="http://www.hhs.gov/ocr/privacy/" target="_blank">HIPAA</a> or <a href="http://www2.ed.gov/ferpa" target="_blank">FERPA</a> provisions is pretty much stuck in a closed state. Furthermore, many organizations are reluctant to open up certain datasets. However, all hope is not lost - this post will advance the idea of Open Source, Closed Data and present several implementation strategies.</p>
<p><!-- more --></p>
<h2>The Reality</h2>
<p>As much as voices in Civic Tech believe in the imperative of opening up datasets, there are certain situations in which it just cannot happen. This should not prevent an organization from being able to take advantage of the benefits of open sourcing their code, though.</p>
<p>Partners with the <a href="http://dssg.io/" target="_blank">Data Science for Social Good</a> fellowship know that we release all of our code under an open source license, but alas, not all are willing to let their data or information out into the public. However, as a civic tech community, we need to encourage non-profits, governments, and others to open up their code, even if they cannot or will not open up their data.</p>
<h2>Why?</h2>
<p>Organizations benefit from putting open source code out there - the benefits far outweigh the cost. First, open source code is a key metric that good talent will be looking for - hiring becomes a whole lot easier when you can just say &lsquo;here, take a look at what we&rsquo;ve done.&rsquo; Furthermore, participating in open source allows you and similar organizations to share efforts. For example, the <a href="https://github.com/nprapps/app-template" target="_blank">NPR Apps Template</a> and the <a href="http://tarbell.tribapps.com/" target="_blank">Chicago Tribune&rsquo;s Tarbell Project</a> have become standards in journalism, used outside of their organization and receiving improvements because of it.</p>
<p>Open sourcing acts as a signal that your organization is up to date with certain practices and norms - furthermore, this can be a way of modernizing and keeping up to date with best practices. However, many organization are wary of sharing code - this should not be as much of a concern as a it often is, alas. Working in the open often improves the quality of the work and the code, as bad practices such as putting secret keys into source control become untenable.&nbsp;<span>Large organizations such as Facebook, Google and smaller organizations release open source code, and civic groups should as well.</span></p>
<p>Concern over sharing code often comes down to the question of whether somebody is able to duplicate the work. However, the advantages of open source outweigh the costs. In fact, one may be able to drive industry specific standards by participating in open source. Another concern tends to be embarrassment over programming standards, but this fear is almost certainly unfounded. <a href="http://opentechstrategies.com/" target="_blank">Open Tech Strategies</a> is great at helping build support for open tech projects, and I would encouraging contacting them if you need help inside your organization.</p>
<h2>Strategies</h2>
<ul><li><span><strong>Fake Data</strong><br></span>One method that we have employed at the Data Science for Social Good fellowship is providing a separate open source repo with fake data. The <a href="https://github.com/dssg/match.edu" target="_blank">Match.Edu</a> open source repo contains scripts to generate fake, rather than real data, and we do development on the actual data in a separate, private, Github repo. The benefit of this method is that there is a full, functional project for people to play with. However, we have to keep the open source repo up to data with the closed source data, which is not always possible. Furthermore, building anonymous data with accurate distributions is tricky. This method is often best suited for research-type projects.</li>
<li><strong>Open Repo without Data</strong><br>At KIPP NJ, they have a <a href="https://github.com/TEAMSchools/mandi" target="_blank">repository</a> that consists of the database schemas for the entire organization. By open sourcing this, they have provided the way forward for many schools in the KIPP network and outside to adopt the KIPP NJ schema. Although you can not run analysis on the KIPP data, one can get an idea of what data is important to collect and what schemas work. This method works very well from inside institutions.</li>
<li><strong>Data Documentation</strong><br>Releasing data documentation allows others to build or at least think about what they can do with your data, and can be a way to build partnerships. Because data documentation is pretty easy to get out there, it represents a good first step. Often the US census does this with sensitive data. From there, researchers can request the specific data that they need.</li>
</ul><p>These methods are ways for organizations to help participate and build a strong technical footing, that ideally allows them to become part of the civic tech community in a deeper, more meaningful way. Open Source, Closed Data is a model with the potential to improve the quality of work at a whole host of institutions.</p>

<p><strong>About the Author</strong></p>
<p>Hunter Owens is a recovering student, urbanism nerd and taco aficionado. When not chronicling the multitude of dive bars in Chicago, Hunter can be found working on Open Source software, Data Stuff and Cities, and maybe complaining about the Weather. He can be found on twitter <a href="https://twitter.com/hunter_owens" target="_blank">@hunter_owens</a> and encourages you to pester him about this article there.</p>
