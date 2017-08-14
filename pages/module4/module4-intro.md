---
title: Introduction of Module 4
keywords: 
last_updated: July 19, 2017
tags: [introduction]
summary: ""
sidebar: home_sidebar
permalink: module4-intro.html
folder: module4
published: false
---

In this module you will...

By the end you should:

* Know this...
* And this...

The last few weeks we've been focusing in on descriptive practices and the systems that support them. This week we're going to going to broaden our focus to think a bit more about the idea of 'context' and the possibilities of connecting descriptions.

### Context

We've mentioned context a number of times already, particularly when we were examining ideas of significance. For archives, in particular, understanding and documenting the context of collections is crucial in maintaining their evidential and cultural value over time.

We saw how collection management systems can help you capture context as part of the descriptive process. Remember how CollectionSpace allowed you to record information about associated people and places using a controlled list?

And yet, as Mike Jones notes in the blog post I included in the preparation for this week, we often don't do a very good job in capturing these connections or making them available as pathways for  discovery. Collection items are often presented...

> as discrete items with metadata attached, linked to various options for filtering and browsing other discrete items but rarely connected to other items, or to the sorts of context found in either exhibition spaces, catalogues, books or articles.

How could we do it better?

### Entities and relationships

Have you ever used the collections of the National Archives of Australia? Their collection database, RecordSearch, can be a bit frustrating at times, but it represents an important innovation in our understanding of archival collections.

Some years ago I created this little widget to illustrate the way information is structured in RecordSearch. (If you don't see anything below, just [click here](http://wraggelabs.com/shed/crs/crs_diagram.html) to view the diagram.)

{: .img-example}
<iframe src="http://wraggelabs.com/shed/crs/crs_diagram.html" frameborder="0"  width="100%" height="670"></iframe> 

On the surface it looks like a pretty standard hierarchy -- moving from organisations at the top, right down to individual items at the bottom. Indeed, cultural heritage collections have traditionally been described in hierarchies of various types. But mouse over the diagram and you'll see that the connections don't just point up and down. The levels don't represent different sized containers -- they're different **types of things**, and they are linked by a **variety of relationships**. A government agency, for example, 'performs' functions and 'creates' series.

In fact this is a very simplified version of how records are described in the National Archives under what is called the [Commonwealth Record Series System](http://www.naa.gov.au/collection/fact-sheets/fs06.aspx). Series can 'control' other series -- a set of index cards, for example, might control a collection of files. Relationships can also be limited by date. One particular agency might perform a function for a certain amount of time, but after a government reshuffle that function might be moved elsewhere. (See my post on [The Functions of Government](http://discontents.com.au/the-functions-of-government/).) Agencies also split and merge. They change their names. One series may have been contributed to, or controlled by, a variety of different agencies over time. All of this information is captured as a network of relationships in RecordSearch. It's not just a collection database, it's a historical model of government.

The [Series System](http://ica2012.ica.org/files/pdf/Full%20papers%20upload/ica12Final00414.pdf), as it is more generally known, is an Australian archival innovation developed in the 1960s. It was ahead of its time in understanding archival collections, not as hierarchies, but as a network of entities and relationships. Context is not not some sort of fuzzy aura that surrounds our collections and bestows significance -- it is something to be documented and captured alongside the records themselves.

{: .bg-info .bg-context}
[Entity-Relationship models](https://en.wikipedia.org/wiki/Entity%E2%80%93relationship_model) are now widely used in database design.

Let's have a look around RecordSearch to explore the contexts it captures:

* Go to [RecordSearch](http://recordsearch.naa.gov.au/).

* Resist the lure of the search box, and click on the 'Advanced search' tab.

* Oh -- that's a familiar looking diagram! Click on 'Organisations'.

* Type 'CO 1' into the 'Organisation number' box and click **Search**.

Congratulations, you've found the record for the whole of the Commonwealth of Australia!

* Click on **Agencies** to see a list of government agencies controlled by the Commonwealth.

* Click on the 'Agency no.' heading to order the agencies by number. Which agency has the number 'CA 1'?

* Browse through the list. How many agencies can you find that have been in existence for more than 100 years?

* Click on **Series** to view the records created by an agency. Click on **Items listed** to see a list of files in a series. 

{: .bg-info .bg-context}
Some series have no files listed, why would that be?

So 'CO 1' is Australia -- you might be wondering whether there are any other 'Commonwealth organisations'? Could there be?

* Click on **New search**.

* Type 'CO 2' into the 'Organisation number' box.

What the...? Why would the Colony of NSW be described in the archives of the Commonwealth of Australia? 

Who knows their Constitution? One important role of the Constitution is in setting out who does what -- what powers were the federating colonies giving to the new central government. Services like post offices and customs became a Commonwealth responsibility, and the records followed the function. So the context of Commonwealth archives extends back before the formation of the Commonwealth itself. Neat huh?

Let's explore this further:

* Click on the 'Advanced search' tab again.

* This time click on **Functions**.

* Click on 'P' and find 'POSTAL SERVICES'. Click on it to view a list of agencies that have performed the function.

* Click on the 'Date function with agency' heading to order the agencies by date.

What is the oldest agency associated with postal services? Where was it?

* Click on **Series** for agency number 'CA 1033'.

* Click on the 'Accum. date range' heading to order the series by date. What's the oldest series?

* Click on 'P960' to view more information about this series. What is it?

Hmm... did you expect to find correspondence from the Hobart Telegraph Office in 1857 in the collections of the National Archives? And we've discovered it without a single keyword search!

Unfortunately this series isn't digitised, but here's an 1870 book of post office returns from Hobart. (Click to [browse](http://recordsearch.naa.gov.au/SearchNRetrieve/Interface/ViewImage.aspx?B=331465).)

[![Postal returns page]({{site.baseurl}}/images/NAA-331465-p2.jpg){: .img-example .img-responsive}](http://recordsearch.naa.gov.au/SearchNRetrieve/Interface/ViewImage.aspx?B=331465)

By exploring the contextual information in RecordSearch we not only have a better idea about what records are held and how they're organised, we've made discoveries! Keyword searches only work if we know what to search for, context enables us to find connections that we don't expect.

### Linked Open Data

The Series System demonstrates the power of an entity-relationship model to capture contextual links between cultural heritage collections and the people and organisations associated with them. But RecordSearch is a closed system. We can't jump out to find where other records from the Hobart Telegraph Office might be held. What if we could define a network of entities and relationships across institutions, collections and databases? 

We can. It's called Linked Open Data.

What's Linked Open Data? Have a look at this introductory video from Europeana:

{: .img-example}
<iframe src="https://player.vimeo.com/video/36752317" width="100%" height="500" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

Put simply, Linked Open Data (LOD) is just a way of using the web to share structured information about the world -- information about things, and the properties or characteristics those things have. It was first proposed by Tim Berners-Lee, the inventor of the web, who described it as moving us from a 'web of documents' to a 'web of data'. Berners-Lee talked about the evolution of the web and the possibilities of LOD [in a TED talk](https://www.ted.com/talks/tim_berners_lee_on_the_next_web?nolanguage=en%3Futm_source%3Dtedcomshare) in 2009.

The important word in the paragraph above is 'share'. It's sharing that puts the 'linked' into Linked Open Data. It's what makes it possible for Linked Open Data to make connections across collection databases. Specifically, to create LOD you:

* share identifiers or labels for the things that you want to talk about;

* share the vocabularies or properties that you use to describe those things;

* share your descriptions of things in machine-friendly ways.

#### Identifiers

What are identifiers? Identifiers are just a label of some sort that uniquely identifies an entity. When we created a description in CollectionSpace we had to supply a unique collection number. For LOD we need an identifer that will be unique not only within the context of our own database, but around the world. The way this is normally done is to use urls -- the unique addresses we use to identify resources on the web. Using urls has another benefit -- we can follow them to find more information about the entity they identify.

Where can you find identifiers? There are a number of services around the world that provide trusted sources of identifiers.

**People and Organisations**

* [Trove People zone](http://trove.nla.gov.au/people/result?q=) -- eg: Clement Wragge is <http://nla.gov.au/nla.party-612109>
* [VIAF](https://viaf.org/) -- eg: Clement Wragge is <https://viaf.org/viaf/73513973/>
* [Wikipedia](https://en.wikipedia.org/) -- eg: Clement Wragge is <https://en.wikipedia.org/wiki/Clement_Lindley_Wragge>

**Subjects**

* [Library of Congress Subject Headings](http://id.loc.gov/authorities/subjects.html) -- eg: Meteorology is <http://id.loc.gov/authorities/subjects/sh85084334>
* [FAST](http://experimental.worldcat.org/fast/) -- eg: Meteorology is <http://id.worldcat.org/fast/1018441>

**Places**

* [GeoNames](http://www.geonames.org/) -- eg: Canberra is <http://www.geonames.org/2172517/>
* [Wikipedia](https://en.wikipedia.org/) -- eg: Canberra is <https://en.wikipedia.org/wiki/Canberra>

#### Vocabularies / schemas / ontologies

If we're going to share information about collections, we need to know that we're using the same language to describe them. If one database uses the term 'family name' and another uses 'surname' we might not realise that they're actually talking about the same thing. Linked Open Data uses shared vocabularies (sometimes called schemas or ontologies) to overcome this sort of problem.

You're already very familiar with one of these vocabularies -- yes, good old Dublin Core is widely used in the LOD world. So if we wanted to describe the relationship between a book and its author we could use the Dublin Core's 'creator' property. But how do we know we're talking about the 'creator' property as defined in Dublin Core and not in some other vocabulary? Identifiers to the rescue again! Both vocabularies and individual properties have their own unique identifiers. DC's creator element can be uniquely identified as <http://purl.org/dc/elements/1.1/creator>.

[Schema.org](http://schema.org/) is another commonly used vocabulary. It was originally developed as a collaboration between Google, Microsoft, and Yahoo to improve the accuracy of search engines. But it now has its own community, and groups such as [BibExtend](http://www.w3.org/community/schemabibex/wiki/Bib.schema.org-1.0) are developing [extensions](https://bib.schema.org/) for the cultural heritage domain.

As well as defining the properties we use to describe things, vocabularies like Schema.org also provide identifiers for **types** of things that we're talking about. Are we describing a person, a book, or a place? It's important to know the difference! These types might be arranged in a hierarchy, from general to specific. For example:

* [CreativeWork](https://schema.org/CreativeWork) -- 'The most generic kind of creative work, including books, movies, photographs, software programs, etc.'

* [Article](https://schema.org/Article) -- this is a more specific type of CreativeWork.

* [NewsArticle](https://schema.org/NewsArticle) -- this is a more specific type of article.

* [Person](https://schema.org/Person) -- 'A person (alive, dead, undead, or fictional)'

If you click on any of the links above, you'll see a list of the properties that are associated with each type of thing. So a 'Person' has properties for 'birthDate' and 'parent', while an 'Article' has a property for 'pagination'. All with their own unique identifiers!

#### Descriptions

How do we put identifiers, types, properties together in a standard form so we can actually share our descriptions of things? LOD descriptions are actually a whole lot of short statements about the world. These statements are called triples because have three parts -- a subject, a predicate, and an object.

It's much simpler than it sounds. A triple is just made up of:

* The thing we're describing (subject) -- such as an identifier for a person

* The particular property of this thing we want to describe (predicate) -- such as the schema.org 'name' property.

* The value of the property (object) -- this might be another identifier, or just a text string.

So the statement below just says that the thing with the identifier <http://nla.gov.au/nla.party-612109> has the name of 'Clement Wragge'.

```
<http://nla.gov.au/nla.party-612109> <https://schema.org/name> 'Clement Wragge'
```

These statements can be published and shared in a number standard ways, such as [RDFa](https://rdfa.info/) and [JSON-LD](http://json-ld.org/). But don't worry -- usually you won't be creating triples manually, you'll set up your database to create them all for you.

All this sharing of identifiers, vocabularies and triples makes it possible to aggregate and interpret data from lots and lots of different sources and find new connections. If it all seems a bit too technical, give yourself a break and play around with [Linked Open Jazz](https://linkedjazz.org/network/), a project that [uses LOD to explore new connections](https://linkedjazz.org/about-the-project/) in the world of jazz music.

### Making connections

Remember the point of all this is to recognise that collection items exist within an ever-growing network of connections that extend far beyond the boundaries of any institution. LOD enables us to document and share these connections to create new opportunities for exploration and understanding. Like the Series System, LOD enables us to contexts of our collections in a flexible and extensible way.

But what sorts of connections are out there? Let's start with a few items from Trove:

* [Peter the stuffed dog](http://trove.nla.gov.au/version/194345597) we've met before.

* [Antarctic sledge](http://trove.nla.gov.au/version/210436751)

* [Opera costume](http://trove.nla.gov.au/version/210409873)

Choose one and start exploring -- I want you to find people, places, events, books, photographs, whatever! Look for interesting or unusual connections, and go deep -- if you find a person, look for photos or biographical records about that person, find their families, their pets!

Wherever possible, I want you to record the name of the thing, and a url that links to it.

### Making LOD

That last little exercise should have given you a sense of the rich contexts within which collections are situated. But how can we document and share them as Linked Open Data. One simple way is by using RDFa -- a standard for embedding LOD in any old web page.

I'm going to start with another object, this [part for a silver vapouriser](http://trove.nla.gov.au/version/216497037) and build up a simple description of it using LOD, RDFa, and good old HTML. Don't worry about the technical details, I just want you to see how we can enrich collection descriptions with a range of links to other resources.

For this exercise, we're going to make use of the [RDFa Playground](https://rdfa.info/play/) -- this is a neat little tool that lets you play around with examples of LOD.

Ok, let's start with the basics. Just copy and past the code below into RDFa Play and see what happens.

``` html
<div vocab="http://schema.org/" about="http://trove.nla.gov.au/version/216497037" typeof="CreativeWork">
  <h1 property="name">Part for Silver Vapouriser</h1>
</div>
```

In this fragment of RDFa we're saying:

* we're using the vocabulary you can find at <http://schema.org/>

* we're talking about the thing identified by the url <http://trove.nla.gov.au/version/216497037>

* the thing is a type of 'CreativeWork'

* the name of the thing is 'Part for Silver Vapouriser'

But we can do better than that! The description in Trove notes, that this object was created by 'Mitchell's Cement Works' in 1916 for 'Madame Melba', aka 'Dame Nellie Melba'. If you search for [Melba](http://trove.nla.gov.au/result?q=nellie+melba) in Trove you'll find lots of things, including a [record](http://nla.gov.au/nla.party-505278) for her in the People zone, a [photograph](http://trove.nla.gov.au/version/182675786), and a [recording](http://trove.nla.gov.au/version/217100350). Let's add some of this information to our page. Again just cut and paste this code into RDFa Play and see how it changes.

``` html
<div vocab="http://schema.org/" about="http://trove.nla.gov.au/version/216497037" typeof="CreativeWork">
  <h1 property="name">Part for Silver Vapouriser</h1>
    <p>This vapouriser was created for <a property="mentions" typeof="Person" href="http://nla.gov.au/nla.party-505278"><span property="name">Dame Nellie Melba</span></a> by <span typeof="Organization" rel="creator" resource="#cw" ><span property="name">Mitchell's Cement Works</span></span> in <span property="dateCreated">1916</span>.</p>
</div>
```

Here we've said:

* the vapouriser 'mentions' (there's no property that directly matches 'made for') a 'Person' who is identified by the url <http://nla.gov.au/nla.party-505278>

* the name of that 'Person' is 'Dame Nellie Melba'

* the 'creator' of the object was an 'Organization' with the name of 'Mitchell's Cement Works'

* I couldn't find an identifier for Mitchell's Cement works, so I just created my own '#cw' -- that's perfectly ok in LOD land!

* the object was created ('dateCreated') in 1916

Now let's add the other items:

``` html
<div vocab="http://schema.org/" about="http://trove.nla.gov.au/version/216497037" typeof="CreativeWork">
  <h1 property="name">Part for Silver Vapouriser</h1>
  <p>This vapouriser was created for <a property="mentions" typeof="Person" href="http://nla.gov.au/nla.party-505278"><span property="name">Dame Nellie Melba</span></a> by <span typeof="Organization" rel="creator" resource="#cw" ><span property="name">Mitchell's Cement Works</span></span> in <span property="dateCreated">1916</span>.</p>
  <p about="http://nla.gov.au/nla.party-505278">Nellie Melba was a famous opera singer. Here's a <a rel="image" href="http://trove.nla.gov.au/version/182663869">photo</a> of her from 1892.</p>
  <p typeof="MusicRecording" about="http://trove.nla.gov.au/version/44857446">Here's a recording of <span rel="creator" resource="http://nla.gov.au/nla.party-505278">Melba singing</span> <a href="http://trove.nla.gov.au/version/44857446"><span property="name">'God Save the King'</span></a>.</p>
</div>
```

We've added the information that:

* there is an 'image' of Melba identified by <http://trove.nla.gov.au/version/182663869>

* there is a 'MusicRecording' identified by <http://trove.nla.gov.au/version/44857446> with the 'name' of 'God Save the King'

* the recording was created by Nellie Melba

So far we haven't really added much new information, but with a bit of poking around I discovered something interesting. Mitchell's Cement Works, which was located in the Melbourne suburb of Richmond, was founded by David Mitchell, who also happened to be Melba's father! Ah the gift makes a bit more sense in that context doesn't it. Let's add this information. Cut and paste as before.

``` html
<div vocab="http://schema.org/" about="http://trove.nla.gov.au/version/216497037" typeof="CreativeWork">
  <h1 property="name">Part for Silver Vapouriser</h1>
  <p>This vapouriser was created for <a property="mentions" typeof="Person" href="http://nla.gov.au/nla.party-505278"><span property="name">Dame Nellie Melba</span></a> by <span typeof="Organization" rel="creator" resource="#cw" ><span property="name">Mitchell's Cement Works</span></span> in <span property="dateCreated">1916</span>.</p>
  <p about="http://nla.gov.au/nla.party-505278">Nellie Melba was a famous opera singer. Here's a <a rel="image" href="http://trove.nla.gov.au/version/182663869">photo</a> of her from 1892.</p>
  <p typeof="MusicRecording" about="http://trove.nla.gov.au/version/44857446">Here's a recording of <span rel="creator" resource="http://nla.gov.au/nla.party-505278">Melba singing</span> <a href="http://trove.nla.gov.au/version/44857446"><span property="name">'God Save the King'</span></a>.</p>
  <p about="#cw">Mitchell's Cement Works in <a typeof="Place" rel="located" href="http://www.geonames.org/2151649/"><span property="name">Richmond</span></a> was founded by <span rel="parent" about="http://nla.gov.au/nla.party-505278" resource="http://nla.gov.au/nla.party-1462186">Melba's father</span>, <a rel="founder" typeof="Person" href="http://nla.gov.au/nla.party-1462186"><span property="name">David Mitchell</span></a></p>
</div>
```

Now we've added that:

* Mitchell's Cement Works was located in a 'Place' identified by <http://www.geonames.org/2151649/> which has the 'name' of Richmond

* The 'founder' of the cement works was a 'Person' identified by <http://nla.gov.au/nla.party-1462186> who had the 'name' of 'David Mitchell'.

* David Mitchell was the parent of Nellie Melba

Have a close look at the visualisation created by RDFa Play. Some of the circles are coloured in -- what happens when you click on them?

![Melba graph]({{site.baseurl}}/images/melba-graph.png){: .img-responsive .img-example}

You should end up with a graph that looks like this. You can see for a fairly short and simple description, we've generated a lot of potentially useful data that others could use to explore the context of the object.

{: .bg-info .bg-context}
Have a go at recording the information you collected using RDFa Play.

### LOD in action

Linked Open Data is still in it's relatively early days, but you're already using it without knowing it. LOD is now embedded in many web pages and is used by Google, Facebook and others to harvest and display structured information about things. Services such as OCLC -- the big library consortium -- is embedding LOD in a number of its products, such as WorldCat. For example, look at this [WorldCat entry](https://www.worldcat.org/title/romance-of-the-south-seas/oclc/8435964&referer=brief_results) for Clement Wragge's book *The Romance of the South Seas*. It just looks like a normal webpage, but what happens when we feed that page to a service that extracts LOD from RDFa? [Have a look](https://www.w3.org/2012/pyRdfa/extract?uri=https%3A%2F%2Fwww.worldcat.org%2Ftitle%2Fromance-of-the-south-seas%2Foclc%2F8435964%26referer%3Dbrief_results&format=turtle&rdfagraph=output&vocab_expansion=false&rdfa_lite=false&embedded_rdf=true&space_preserve=true&vocab_cache=true&vocab_cache_report=false&vocab_cache_refresh=false)! Se all the triples?

But what's really exciting about Linked Open Data is the posibility of bringing together information from different sources so that we can see the past differently. Every few years, the [LODLAM](http://lodlam.net/) (Linked Open Data in Libraries, Archives and Museums) summit discusses the possibilities of linking up cultural collections. They also run a competition. This video from the 2015 winner gives you a sense of how powerful LOD might be.

<iframe width="100%" height="500" src="https://www.youtube.com/embed/ilwoRwWHInY" frameborder="0" allowfullscreen></iframe>

### Discovery, access, and use

How do people find things in cultural heritage collections?

In our last session we explored the importance of documenting context, both for preserving the value of collections, and for opening up new avenues for exploration.

BUT.

While both cultural heritage professionals and researchers understand the value of context, where do we go when we want to find something online?

Yep, Google. A [2013 study of Dutch scholars](https://arxiv.org/abs/1309.2434) highlighted the 'paradoxical attitude' of scholars who, while emphasising the important of provenance and context to research, nonetheless relied heavily on Google to discover resources.

What's wrong with that? Nothing -- as long as we understand the biases and limitations of search engines like Google. As the study notes, search engines 'do not simply retrieve information, but co-produce information by ranking and indicating the importance of information'. The results we see when we search for something in a search box are the result of complex ranking algorithms that try to predict what will be most relevant.

Most relevant to who? Your results might not be the same as mine. Search results are [increasingly personalised](http://tentacleinbound.com/articles/personalized-search) based on things like your location and web browsing activity. The exact formulae used for results ranking are largely unknown. Search engine algorithms tend to be 'black boxes' -- we use them, but we don't really understand how they work.

Try the following search in Google [`site:trove.nla.gov.au`](https://www.google.com.au/search?q=site:trove.nla.gov.au). The `site:` modifier is a handy little trick that tells Google to limit results to a particular site or domain -- in this case Trove. How many results does Google find? When I tried Google thought there were 'About 1,900,000 results'. But you might get a different estimate -- it can vary between computers and users. Don't be tricked into thinking that Google tells the 'truth'. 

Hopefully you will remember that Trove holds considerably more than 1,900,000 resources (try half a billion). So what's going on? As well as the mysteries of results ranking, and the inaccuracy of its estimates, Google only indexes what Google indexes. While Search Engine Optimisation is now a business in itself, you simply can't make Google index all your stuff. All you can do is to try and make your online content as Google-able as possible. And hope.

### Discovery happens elsewhere

Back in 2007, the library thinker Lorcan Dempsey coined the phrase 'discovery happens elsewhere' to encourage libraries to think about how they were exposing their metadata to the world. It's not enough to have your own shiny web interface because, like it or not, a large proportion of your users will prefer to use Google.

Ok, so I just said that we really don't have any control over what Google indexes and displays. That's true, but there are things we can do to make collections more discoverable on the open web.

* **Use persistent urls.** If you want people to find your stuff DON'T CHANGE YOUR URLS! It seems sort of common sense, but it's amazing the number of times institutions install new systems or redesign their sites and break all their links. Have a look at ['Cool URIs don't change'](https://www.w3.org/Provider/Style/URI.html) for the basic arguments. And if you don't think this is a problem, have a look at the Wikipedia article on [Link Rot](https://en.wikipedia.org/wiki/Link_rot).

* **Expose links to your collection items.** If the only access to your collection is through a search box, Google can't index your collection. You need to provide ways for search engines (and human beings) to browse your collection -- to follow links that lead through to individual items. You can also use things like [sitemaps](http://www.sitemaps.org/) and RSS feeds to publish lists of links in a form that machines can understand.

* **Include metadata.** Remember our discussion about Linked Open Data and Schema.org? Schema.org was developed by search engines to aid discovery. You can use it to share basic information about collection items -- like their title and creator -- with search engines or other data aggregators. At the very least, you can [use 'meta' tags](http://www.wordstream.com/meta-tags) to provide basic page-level data. Here's an [interesting blog post](http://blogs.library.duke.edu/bitstreams/2014/03/27/schema-org-and-google-for-local-discovery-some-key-takeaways/) about using Schema.org and Google to provide library search services. 

There are more Google-specific strategies you can implement, but the three points above are fundamental to web resource discovery in all its forms.

### Sharing collections online

![Flickr commons]({{site.baseurl}}/images/nla-flickr.jpg){: .img-responsive .img-example}

But as well as optimising your own collection site for improved discovery, you can push your collections out into the wider world. Set your collections free!

For example, cultural institutions often share their photographic collections using platforms such as Flickr. In fact, there's a whole special section called the [Flickr Commons](https://www.flickr.com/commons/) where cultural organisations can share public domain images. (What's public domain? We'll talk about that below...) By sharing images on Flickr, organisations open their collections to new audiences. Often the images will be viewed many more times on Flickr than they will on the institution's own site. Some small organisations without their own web presence have used Flickr as their main collection site. Have a browse of the Commons' list of ['participating organisations'](https://www.flickr.com/commons/institutions/) -- how many Australian organisations can you find? How many images do they share on Flickr?

There are doubts nowadays about the future of Flickr, but there are plenty of other ways to share collections. The State Library of Queensland, for example, donated [50,000 images to the Wikimedia Commons](https://commons.wikimedia.org/wiki/Commons:State_Library_of_Queensland). Indeed, GLAM organisations all over the world are collaborating with the Wikimedia community in a number of different ways to highlight the contents of our cultural collections. See the [GLAM-Wiki](https://en.wikipedia.org/wiki/Wikipedia:GLAM) site for more information and ideas.

One great example of the possibilities is provided by the British Library which, in 2013, released over [1 million images on Flickr](http://britishlibrary.typepad.co.uk/digital-scholarship/2013/12/a-million-first-steps.html). The [images](https://www.flickr.com/photos/britishlibrary) came from scanned books from the 17th, 18th and 19th centuries and were shared without any restrictions for people to use, research and play. This generated enormous excitement and large amounts of web traffic on Flickr. The Wikimedia community started [adding the images](https://commons.wikimedia.org/wiki/Category:Images_from_the_British_Library_Mechanical_Curator_collection) to the Wikimedia Commons as well, but they also developed a series of indexes to make it easier for for people to explore the collection. Here's the [Australian images](https://commons.wikimedia.org/wiki/Commons:British_Library/Mechanical_Curator_collection/Synoptic_index,_Asia_and_Australasia#Australia). 

{: .bg-info .bg-context}
See what you can find and share the results on Slack. 

The images have even been used in an [art installation at the Burning Man festival](http://blogs.bl.uk/digital-scholarship/2014/08/the-british-library-meets-burning-man.html) in Nevada.

{: .img-example}
<iframe width="100%" height="500" src="https://www.youtube.com/embed/Q3SBxO34Zlc" frameborder="0" allowfullscreen></iframe>

### Life on the outside

Why should you expect people to come to your web site to find and use collections? Why not push collections out into the spaces where people already congregate. Social media provides another way of making collections discoverable.

As well as being on Flickr and the Wikimedia Commons, the British Library's million images are also shared on Tumblr and Twitter. Computer scripts (usually called bots) choose and post random images. The British Library's [@MechCuratorBot](https://twitter.com/mechcuratorbot) is just one example of a growing army of Twitter bots sharing random collection items.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">16 Jun 1928: &#39;&quot;WEST AUSTRALIAN&quot; v. &quot;SUNDAY TIMES.&quot;&#39; <a href="https://t.co/aFgTty3NrE">https://t.co/aFgTty3NrE</a> // re ABC: <a href="https://t.co/danO3Qo3Ep">https://t.co/danO3Qo3Ep</a></p>&mdash; TroveNewsBot (@TroveNewsBot) <a href="https://twitter.com/TroveNewsBot/status/781795900301672449">September 30, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

I've made a few myself! [@TroveNewsBot](https://twitter.com/trovenewsbot) shares newspaper articles from Trove, while [@TroveBot](https://twitter.com/trovebot) does the for the rest of Trove's resources. But these bots do more than just post random stuff. Tweet keywords at them and they'll search Trove, tweeting back the most relevant result. Yes, you can search Trove without ever leaving Twitter! There are more search options on the GitHub pages for @TroveNewsBot and @TroveBot. Here's a few things you can try:

* Tweet #luckydip at either bot for a random resource.
* Tweet a url and the hashtag #keywords to find resources relating to a web page.

But social media can hold dangers for cultural heritage collections. Have you ever come across the @HistoryInPics (or some similar) Twitter feed? It's an account that tweets out historical images. Sounds good huh? Hmmm, perhaps you should read Sarah Werner's post ['It's history not a viral feed'](http://sarahwerner.net/blog/2014/01/its-history-not-a-viral-feed/).

While it's great to see cultural heritage collections turning up on social media, accounts like @HistoryInPics aren't very interested in fundamental things like attribution or accuracy. Often their posts are generated by bots -- just scraped from other picture sites. The captions are often wrong, the photos sometimes faked. You can learn a few of their tricks by following [@PicPedant](https://twitter.com/PicPedant).

So what can we do? Again, the main thing is to get the basics right. If your collections are easily discoverable through Google and elsewhere then someone trying to uncover the source of a posting by @HistoryInPics should be able to find it using Google's [reverse image search](https://images.google.com/) or a service like [Tin Eye](https://www.tineye.com/). 

* Go to [@HistoryInPics](https://twitter.com/HistoryInPics) and download one of the images they share. (Right click > Save Image)

* Then go to [Tin Eye](https://www.tineye.com/), click on the upload button and select the image you downloaded.

* What can you find out? Why might a service like Tin Eye be useful for cultural heritage workers?  

If you want people to share your collections then make it easy for them to do it properly:

* **Use persistent urls** I know I've mentioned it already, but IT'S SO IMPORTANT I can't help but mention it at every opportunity. Some collection sites still don't have individual urls for items. Seriously. Some collection urls break when you try to share them (looking at you RecordSearch). If we want people to attribute the source of collection items we need to give them urls that work!

* **Provide example citations**. If you want people to properly attribute a collection item, show them how. Provide an automatically generated citation that can just copy and paste into their post.

* **Include metadata**. This one's worth repeating as well. Services like [Twitter](https://dev.twitter.com/cards/overview) and [Facebook](http://ogp.me/) define specific guidelines for publishing item metadata so that it can be easily retrieved and displayed when someone shares that item. It's this metadata that's used to create things like Twitter cards.

* **Tell people how they can use your collection**. Persistent urls and the rest are not much good if the licensing information you provide makes people frightened to share your collection. If something is out-of-copyright, then say so. If it's openly licensed, include details. Blanket statements about checking with the institution before use do not encourage sharing or creativity.

Sarah Werner provides some important tips in her talk on [how to destroy special collections with social media](http://sarahwerner.net/blog/2015/07/how-to-destroy-special-collections-with-social-media/).

### Beyond the silos of the LAMs

A 2008 study called 'Beyond the silos of the LAMs' explored ways that libraries, archives and museums could collaborate to improve discovery. I mention it here mainly because it has the best title of all time.

A lot has happened since 2008. In particular a number of large-scale aggregation services have been developed to pull together collection items from across the GLAM sector. There's:

* [Trove](http://trove.nla.gov.au) (of course, aggregating content from Australia)
* [DigitalNZ](http://digitalnz.org.nz/) (New Zealand)
* [DPLA](http://dp.la/) (Digital Public Library of America)
* [Europeana](http://europeana.eu/) (many European countries)

Each of these services has a different emphasis and use different technologies, but they all aim to make cultural collections easier to find and use. They do this by:

* Harvesting and indexing collection item metadata from lots of different GLAMs (and other organisations). This is the aggregation part of things -- it creates a big centralised database of stuff.
* Making all this stuff easily available for discovery and reuse. 

Discovery *and reuse*? Each of these services provides a familiar-looking search portal -- just type in your queries and off you go. But, more importantly, each of these services makes their aggregated data available in a form that computers can understand [via an API](https://www.nla.gov.au/our-publications/staff-papers/from-portal-to-platform) (Application Programming Interface). This means that anybody can build new tools and interfaces that open up cultural collections in innovative and interesting ways.

Europeana's WWI portal provides a good example of what APIs make possible. 

* Go to <http://www.europeana1914-1918.eu/en>

* Type 'Somme' in the box and click **Search**.

You'll see results from Europeana's own collections, but you'll also notice a series of tabs headed 'New Zealand sources', 'American sources', and 'Australian sources'.

* Click on 'Australian sources'. Where do you think these pictures are coming from?

* Click on one of the photos.

* Click on the 'View on partner's website' link.

* Where are you now?

What's going on? Europeana is using APIs to pull WWI content from Trove, DigitalNZ, and the DPLA. When you clicked on the 'Australian sources' tab, the site fired off a request to the [Trove API](http://help.nla.gov.au/trove/building-with-trove). Trove replied with lots of nice structured, machine-readable data that Europeana could easily display within its own portal. 

Aggregation brings metadata together. APIs send it back out into the world. Together these technologies enable new forms of discovery. We'll explore more examples of this in a few weeks when we look at collection interfaces. 

### Licensing lessons and copyright confusions

As I noted above, if we want people to share and use online collections we need to provide information on how they can use them. Institutions often attach rights statements to items that are really not very useful (and are sometimes inaccurate). An [analysis](http://www.deanfarr.com/viz/rights.php) of the records harvested by the DPLA showed that more than 26,000 different rights statements were being used across institutions. How are users supposed to make sense of all that?

Standard licensing schemes like Creative Commons can help if you're the creator or copyright holder of a particular digital object. But CC licences don't cover all of the situations that cultural institutions confront. That's why the DPLA and Europeana have developed a set of [12 standard rights statements](http://rightsstatements.org/en/) for cultural heritage organisations. By using these we can lessen the confusion of users, and make it easier for them to find resources that they are free to share or use in their own projects.

But while institutions can make better use of standard licenses and statements, the copyright system makes it hard for them to provide accurate information. 

Here's a collection of resources. Have a look at the images and related information and sort them into two groups -- 'in copyright' and 'out of copyright'. 

***Gathered Moss* by Charles Fenner, published in 1946 in Melbourne. (Another [image]({{site.baseurl}}/images/gatheredmoss1.jpg).)**

[![Gathered moss]({{site.baseurl}}/images/gatheredmoss2.jpg){: .img-responsive .img-example}]({{site.baseurl}}/images/gatheredmoss2.jpg)

***Two Frontiers* by E.J. Brady, published in Sydney in 1944. (Another [image]({{site.baseurl}}/images/two_frontiers1.jpg).)**

[![Two frontiers]({{site.baseurl}}/images/two_frontiers2.jpg){: .img-responsive .img-example}]({{site.baseurl}}/images/two_frontiers2.jpg)

**A photo of a macaque, taken in Indonesia in 2011.**

![Monkey]({{site.baseurl}}/images/650px-Macaca_nigra_self-portrait_large.jpg){: .img-responsive .img-example}

**A photo of floods in Maitland, taken by the Newcastle Morning Herald in 1950.**

![Floods 1950]({{site.baseurl}}/images/2828210401289.jpg){: .img-responsive .img-example}

**A photo of floods in Maitland, taken by Jim Lucy in 1955.**

![Floods 1955]({{site.baseurl}}/images/2967415889_eb70f616c2_b.jpg){: .img-responsive .img-example}

**Letter from Atlee Hunt to Edmund Barton forwarding an umbrella, 8 October 1903.**

[![Barton letter]({{site.baseurl}}/images/nla.obj-225111194-1.jpg){: .img-responsive .img-example}]({{site.baseurl}}/images/nla.obj-225111194-1.jpg)

What did you base your decisions on and why? 

[Here's the answers](https://docs.google.com/document/d/1LyeyH7lEdaemL_YievXYEuElmOZ8hczzZo6WWx5-K8s/edit?usp=sharing) (don't peek!).

Here's a few useful resources on copyright:

* [Library Guide to Copyright](http://canberra.libguides.com/content.php?pid=273640&sid=2255896)
* [Copyright information for clients](http://www.nsla.org.au/sites/www.nsla.org.au/files/publications/NSLA.copyright_information_for_clients_2011.pdf) (NSLA)
* [Duration of Copyright](http://www.copyright.org.au/acc_prod/AsiCommon/Controls/BSA/Downloader.aspx?iDocumentStorageKey=7384f456-8e8a-4c69-97ca-206bb46df5da&iFileTypeCode=PDF&iFileName=Duration%20of%20Copyright)  (Australian Copyright Council)