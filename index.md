---
layout: default
link: Overview
title: A Visual Analysis of Layout Patterns
order: 1
permalink: /
---

Layout design is a foundational part of designing and developing websites. It is typically a result of the wireframing process, in which designers conceptualize behaviors and user flows, but often goes into varying levels of refinement throughout visual design phases, e.g. being applied to an updated grid system and receiving stylistic treatment to aid with emphasis. It may seem like just one of the many mundane steps in creating a website or app, but do layout designs hold any merit in their own right, and if so, how can its effects be quantified or evaluated?

Web design consists almost solely of a collection of archetypes based on the principle that functionality and layout are mutually dependent. This project presents a set of case studies as well as initial explorations into other groupings of sites to prove that any given website can be categorized by layout alone and its functionality and purpose will naturally suit those of others in its grouping.

The most confirming piece of evidence supporting this is the reverse application of the sorting technique. If you group websites together by function alone (i.e. social media, news media, forum, etc), you'll notice the groupings form in the same way as if you categorized based on layout alone. My reason for not simply sorting by function, however, is that implementation and user flows are much more flexible than layout design, and tend to fluctuate significantly between even these similar websites. Staying within the base-level of layout patterns, I've been able to provide a consistent and accurate taxonomy of web design.

Most websites can be grouped into the following categories:
{: #archetypes}
<figure>
  <div class="table--wrapper">
    <table>
      <thead>
        <tr>
          <th><h3>Layout Pattern</h3></th>
          <th><h3>Use Cases</h3></th>
          <th><h3>Examples</h3></th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><img src="/images/bulletin.png" title="Bulletin Pattern">Bulletin</td>
          <td>Non-chronological mulitmedia content</td>
          <td>News (legacy): AOL, Yahoo</td>
        </tr>
        <tr>
          <td><img src="/images/feed.png" title="Feed Pattern">Feed</td>
          <td>Chronological multimedia content</td>
          <td>Social Media: Facebook, Twitter, Tumblr</td>
        </tr>
        <tr>
          <td><img src="/images/frame.png" title="Frame Pattern">Frame</td>
          <td>Interactive applications and complex interfaces</td>
          <td>Email: Gmail, Outlook<br>Apps: Wordpress (back-end), Expression Engine (back-end)</td>
        </tr>
        <tr>
          <td><img src="/images/stadium.png" title="Stadium Pattern">Stadium</td>
          <td>Independent content</td>
          <td>Streaming Video: Youtube, Vimeo, Twitch<br>Photography: Flickr</td>
        </tr>
        <tr>
          <td><img src="/images/thread.png" title="Thread Pattern">Thread</td>
          <td>Highly collaborative and simultaneously active chronological content</td>
          <td>Forums: Reddit</td>
        </tr>
        <tr>
          <td><img src="/images/grid.png" title="Grid Pattern">Grid</td>
          <td>Content composed of a multitude of categories</td>
          <td>News (modern): MSN</td>
        </tr>
      </tbody>
    </table>
  </div>
  <figcaption>Layout patterns and usage</figcaption>
</figure>

<p>These archetypes of web design can be extended by the components of each. Above, these components are shown in categories described by their color: <span class="box--green box--small"></span> <strong>Primary Navigation</strong>, <span class="box--red box--small"></span> <strong>Secondary Navigation / Toolbars</strong>, <span class="box--blue box--small"></span> <strong>Primary Content</strong> and <span class="box--yellow box--small"></span> <strong>Secondary Content</strong>. As such:</p>

1. **Bulletin**
  * Combination navigation-header
  * Single column content
  * Usually no sidebars (functionally limited)

2. **Feed**
  * Navigation bar
  * Navigation sidebar (usually on the left)
  * Endless feed
  * External sidebar

3. **Frame**
  * Highly hierarchical, embedded panes of content
  * Minimal site-level features
  * Toolbars

4. **Stadium**
  * Navigation bar
  * Large, central content
  * Compact sidebar navigation
  * External sidebar
  * Simple footer

5. **Thread**
  * Header bar
  * Navigation bar
  * Highly paginated content

6. **Grid**
  * Navigation bar
  * Header bar
  * Content sidebars
  * Gridded content
  * Multi-column footer

This taxonomy provides a method of categorization for future layout patterns and a simple assessment of their most likely function, which is a positive indicator of their best suited purpose. For example, if we collect a group of sites with similar components and apply one of the groupings defined above, we can see that blogs are best suited to the Feed layout pattern and more typical news sites follow the Bulletin pattern. Most relevant to my case studies, news media seem to be best fit by the Grid pattern.

The uniformity of layout patterns, in essence, is also an indication of homogeneity across web design. However, it is just as easily said that this trait is simply a necessity in the unique and highly competitive environment of the web. The focus of this project was neither to prove nor disprove such a moot point though, so this overview and the case studies largely ignore this avenue of thought.

### On Continuation and Usage

I believe my definitions of layout patterns can be further abstracted into a more flexible and less content-based system of components. This project, seen through the lens of the web, should be a stepping stone to a more genuine, unbiased view of all digital design. Hopefully layout patterns can be utilized in design practice to provide more promising methods of experimentation and to help beginners understand just how multifaceted digital design can be.

[**Dive into the case studies to learn more &rarr;**](/case-studies)