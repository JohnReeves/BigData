#Getting Started

Open `Bath: Hacked` - https://data.bathhacked.org/ in a new tab (right click on the link - open in new tab)

##Finding and using datasets

`Bath: Hacked` hosts open data about Bath & North East Somerset. The data comes from the local council and national datasets, e.g. published by the Office of National Statistics or the Environment Agency. In the future we hope to have data from other local organisations.

`Socrata` hosts the datasets so `Bath: Hacked` can concentrate on publishing and using data, rather than worrying about running another website or set of databases.

There is documentation and some videos that can help you learn more about Socrata.

###Registration
-You don’t need to register to *use the data*. All the data can be accessed without a login. 

-You need to resigister to *use the APIS*. Extra queries can be made using your API key, which helps us track popular applications and datasets.


#Finding Datasets
Either:

1. Click on the categories on the homepage, e.g. to find all of the Environmental data
2. Search for data using a keyword, e.g. “parking”. This will search in the dataset titles, descriptions and also in the datasets themselves.
3. Narrow down your search using the datasets page which lets you combine searches, categories and more to find just the data you need.

The data store contains a number of things:

- *datasets* which are hosted in the platform and which can be downloaded, queried, and explored using the built in tools. E.g. live parking data
- *pointers to external datasets* which live elsewhere on the web. You can follow a link to those to download or use them
charts, maps, and a variety of other visualisations of the data

The charts, maps, and other “data lenses” can be created entirely in the data store. So you can make a useful visualisation or tool without having to create a separate website or application. For example someone has created a map showing restaurants with very poor hygiene ratings. These can be embedded in another website, e.g. a blog, to help you tell stories with the data. See the Socrata video tutorials for more help.

##Finding Your Way Around a Dataset
Open up the BANES Live Car Park Occupancy dataset in another browser window whilst you read this section.

Every dataset hosted in the store is presented in basically the same way. When you look at the dataset you’ll see:

- Its name
- A description that tells you more about the dataset
- A spreadsheet-like table that contains the actual data, each column should have a name that tells you what data it contains

![](http://i.imgur.com/K2z8OM7.png)

If the dataset is large or has a lot of columns then you can browse through it to explore it.

There are some additional controls on the right hand side of the screen which provide ways to explore, visualise or access the data. These are shown below:

![](http://i.imgur.com/LdNccpB.png)

###The top row has:

- Some social tools to share the dataset, subscribe to an RSS feed
- Options to change the page layout to give you a better view of the data, e.g. an easier view of individual records
- A search box to find data in the dataset
- A full-screen mode option which will give you more space

###The second row of coloured buttons gives you additional options:
 
- **Manage** – allows you to tweak the columns being shown and re-order them to tweak the presentation to your liking.

Tip: if you’re signed in, then you can save these views and share with others

- **More Views** – access to views, graphs and charts that others have made with this dataset

- **Filter** – allows you to sort, filter, and format the dataset to find the specific data you’re interested in.

Tip: again, if you’re signed in, then you can save these views and share with others

- **Visualize** – provides access to tools to present the data as a chart or a map (if it has some location data in it). The tools provide similar functionality to Excel or other spreadsheet software.

- **Export** – ability to download the dataset and links to its APIs

Tip: every hosted dataset has two APIs. Both offer similar basic features that support querying the data

- **Discuss** – a comment form to leave messages to the publisher

- **Embed** – code snippets to allow you to embed the dataset (or a chart or map) in a blog post

- **About** – more metadata about the dataset, e.g. when was it updated, who published it, and under what licence it is published 

Tip: the majority of datasets are under open licenses, but a few may have restrictions, e.g. to research use, please check!

##Downloading
To download a dataset:

Click the”Export” button on the dataset page
From the pull-out menu, choose a data format

The most commonly used will be CSV, XLS (for Excel), or JSON

##Accessing the API
To access the API for a dataset:

Click the “Export” button on the dataset page

The pull-out menu will give you two options for accessing the data:
- **A SODA API** – this is Socrata’s own API. Their developer portal has a lot more detail on it, and links to client libraries, etc.
- **An ODATA API** – this is a Microsoft API that is supported by a variety of tools. You can use it to import data into Excel or Tableau. More documentation.

Both APIs use JSON. Use whichever one is best for you. However the SODA API will also link to an online tool that will let you explore creating API queries in your browser. Here’s the one for the live car park dataset.

If you click on the field names in the tool then it will try to give you an example API query that uses that field and some real data.

	Tip: you can click on the example to see it in practice, or click the little pencil icon
to be taken to a hurl.it page (like this one) which will let you explore things a little 
more clearly.

###Further Reading
- Socrata Developer Portal [https://dev.socrata.com/]
- SODA API Getting Started Guide [https://dev.socrata.com/consumers/getting-started.html]
- Chris Metcalfe’s jsfiddle examples [http://jsfiddle.net/user/chrismetcalf/fiddles/]
