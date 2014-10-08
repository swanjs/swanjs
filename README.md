SWAN.JS
======

"What backend should I use with Angular?" A question that can be answered differently for every set of requirements. "How can I build an Angular application with seamless client and server ORM integration, configurable real time synchronized data models, model-based validation, and store transactional data in Postgres, documents in Mongo, faceted search in Elastic, all while writing less boiler-plate code?" Answer: SWAN.JS.
    
Okay, so SWAN.JS isn't really a thing yet. But it's coming! And what is it? It's a customized stack of open-source libraries built on Sails.js, Waterline ORM, AngularJS, and Node.js (shortened to SWAN.JS cuz, well, we don't have enough acroynms in our lives).
    
"So it's like the MEAN stack?" Well, yes, but not so "mean". MEAN.JS is a great stack, but is limited out of the box to building MongoDB-based applications. SWAN.JS doesn't care what backend technology you use. "So it does real-time data sync like Firebase?" Yep! Firebase is wonderful at providing a real-time data model, but what about when you need classic relational data? Or how about composing your model with a mix of relational and document-based storage?

# What to Expect:

* Over the next few weeks there will be some simple (albeit not fully-baked) examples published
  * Data models (client and server)
  * Validation
  * Real-time messaging/data sync
  * Authentication & Authorization
* Soon after we hope to get a little further in nailing down standard conventions and will update samples accordingly
  * Standardize on model to validation configuration so server/client read from the same file(s)
  * Standardize on build process
  * Standardize on out-of-the-box view/edit functionality
* And soon after that there will be generators. Lots of generators!
  * `swan generate new` to create a new app
  * `swan generate api` to create server model and api, as well as matching client REST interface and model
  * `swan generate auth` to build auth service and wire in on API and client
  * Lots more!
