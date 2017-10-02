---
title: Collections in context
last_updated: October 1, 2017
sidebar: home_sidebar
permalink: module4-context.html
folder: module4
published: true
---

### Understanding contexts

We've mentioned context a number of times already, particularly when we were examining ideas of significance. For archives, in particular, understanding and documenting the context of collections is crucial in maintaining their evidential and cultural value over time.

We saw how collection management systems can help you capture context as part of the descriptive process. Remember how CollectionSpace allowed you to record information about associated people and places using a controlled list?

And yet, as Mike Jones notes in [this blog post](http://www.mikejonesonline.com/contextjunky/2016/08/26/two-presentations-in-one/) from last year, we often don't do a very good job in capturing these connections or making them available as pathways for discovery. Collection items are often presented...

> as discrete items with metadata attached, linked to various options for filtering and browsing other discrete items but rarely connected to other items, or to the sorts of context found in either exhibition spaces, catalogues, books or articles.

How could we do it better?

{: .bg-context .bg-warning}
**Portfolio alert!** Read Mike Jones's post and look back over the previous modules to see where 'context' was mentioned. In a minimum of 100 words describe what you think context means and explain its significance for documenting and using cultural heritage collections.

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

* Click on the 'Agency no.' heading to order the agencies by number. *Which agency has the number 'CA 1'?*

* Browse through the list. *Can you find an agency that's been in existence under its current name for more than 100 years -- what is it?*

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

*What is the oldest agency associated with postal services -- where was it?*

* Click on **Series** for agency number 'CA 1033'.

* Click on the 'Accum. date range' heading to order the series by date. *What's the oldest series created by CA 1033?*

* Click on 'P960' to view more information about this series. What is it?

Hmm... did you expect to find correspondence from the Hobart Telegraph Office in 1857 in the collections of the National Archives? And we've discovered it without a single keyword search!

Unfortunately this series isn't digitised, but here's a digitised list of Tasmanian postmasters and mistresses from 1899 to 1912 (Click to [browse](https://recordsearch.naa.gov.au/SearchNRetrieve/Interface/ViewImage.aspx?B=10727126).)

{% include image.html file="10727126-p1.jpg" url="https://recordsearch.naa.gov.au/SearchNRetrieve/Interface/ViewImage.aspx?B=10727126" alt="First page from NAA: P2157, 1" caption="NAA: P2157, 1, page 1" %}

By exploring the contextual information in RecordSearch we not only have a better idea about what records are held and how they're organised, we've made discoveries! Keyword searches only work if we know what to search for, context enables us to find connections that we don't expect.

{: .bg-context .bg-warning}
**Portfolio alert!** In your portfolio record answers to the questions in italics above: Which agency has the number 'CA 1'? Can you find an agency that's been in existence under its current name for more than 100 years -- what is it? What is the oldest agency associated with postal services -- where was it? What's the oldest series created by CA 1033?

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

``` rdf
<http://nla.gov.au/nla.party-612109> <https://schema.org/name> 'Clement Wragge'
```

These statements can be published and shared in a number standard ways, such as [RDFa](https://rdfa.info/) and [JSON-LD](http://json-ld.org/). But don't worry -- usually you won't be creating triples manually, you'll set up your database to create them all for you.

All this sharing of identifiers, vocabularies and triples makes it possible to aggregate and interpret data from lots and lots of different sources and find new connections. If it all seems a bit too technical, give yourself a break and play around with [Linked Open Jazz](https://linkedjazz.org/network/), a project that [uses LOD to explore new connections](https://linkedjazz.org/about-the-project/) in the world of jazz music.

### Making connections

Remember the point of all this is to recognise that collection items exist within an ever-growing network of connections that extend far beyond the boundaries of any institution. LOD enables us to document and share these connections to create new opportunities for exploration and understanding. Like the Series System, LOD enables us to contexts of our collections in a flexible and extensible way.

But what sorts of connections are out there? Let's start with a few items from Trove:

* [Antarctic sledge](http://trove.nla.gov.au/version/249811938)

* [Opera costume](http://trove.nla.gov.au/version/249776243)

* [Telescope](http://trove.nla.gov.au/version/248002260)

Choose one and start exploring -- I want you to find at least ten people, places, events, books, photographs, whatever! Look for interesting or unusual connections, and go deep -- if you find a person, look for photos or biographical records about that person, find their families, their pets! Use services like Geonames and Wikipedia to find records for places or events. Record both the name of the thing, and **a url** that links to it.

{: .bg-context .bg-warning}
**Portfolio alert!** In your portfolio create a table and list your ten related things, providing both the name, and a url that links to a page about that thing. Of course, remember to include the object you started with!

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

{% include image.html file="melba-graph.png" url="images/melba-graph.png" alt="Screen capture from RDFA playground" caption="The completed network of relationships." %}

You should end up with a graph that looks like this. You can see for a fairly short and simple description, we've generated a lot of potentially useful data that others could use to explore the context of the object.

### LOD in action

Linked Open Data is still in it's relatively early days, but you're already using it without knowing it. LOD is now embedded in many web pages and is used by Google, Facebook and others to harvest and display structured information about things. Services such as OCLC -- the big library consortium -- is embedding LOD in a number of its products, such as WorldCat. For example, look at this [WorldCat entry](https://www.worldcat.org/title/romance-of-the-south-seas/oclc/8435964&referer=brief_results) for Clement Wragge's book *The Romance of the South Seas*. It just looks like a normal webpage, but what happens when we feed that page to a service that extracts LOD from RDFa? [Have a look](https://www.w3.org/2012/pyRdfa/extract?uri=https%3A%2F%2Fwww.worldcat.org%2Ftitle%2Fromance-of-the-south-seas%2Foclc%2F8435964%26referer%3Dbrief_results&format=turtle&rdfagraph=output&vocab_expansion=false&rdfa_lite=false&embedded_rdf=true&space_preserve=true&vocab_cache=true&vocab_cache_report=false&vocab_cache_refresh=false)! Se all the triples?

But what's really exciting about Linked Open Data is the posibility of bringing together information from different sources so that we can see the past differently. Every few years, the [LODLAM](http://lodlam.net/) (Linked Open Data in Libraries, Archives and Museums) summit discusses the possibilities of linking up cultural collections. They also run a competition. This video from the 2015 winner gives you a sense of how powerful LOD might be.

<iframe width="100%" height="500" src="https://www.youtube.com/embed/ilwoRwWHInY" frameborder="0" allowfullscreen></iframe>