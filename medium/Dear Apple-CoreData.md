# Publications

https://medium.com/@magesteve/dear-apple-we-need-a-replacement-for-core-data-320df019487e

## Dear Apple,
## Please finally admit that Core Data is to complex for most programmers, and instead give us a cross-platform safe NoSQL database API.
### Thank you, a Concerned Developer.

I am going to be brutal here. Apple, please admit that CoreData has been a failure for most developers. And give us what we want. A simple, cross-platform, NoSQL database that is supported on the system level, allowing automatic syncing between devices. Only you can provide this missing feature for developers. It would make our lives so much easier, and you would quickly see an explosion of released Apps using this SDK.
I can think of no Apple technology that is as disliked, or outright hated, as the Core Data APIs. Developers flinch when told that they have to support it in the code. The API is overly complicated for the simple uses, and for the more complex cases, it rarely has the performance desired. Numerous 3rd party libraries have been written to try to make life easier for developers using Core Data. Apple Engineers recommend their use, outright acknowledging the complexity issue.
Other deficiency of Core Data became apparent. The performance for any medium to large database was cringeworthy. Automatic network syncing was promised, but never entirely delivered by Apple. Lack of support for other platforms became more and more an issue, especially when working with Documents. Revision of the schema, the layout of the database, between revisions of the software, was another area that developers actively tried to dodge.
Worst of all, the API is not what we really want. It is not Core Data fault. Back in 2005, when Core Data was introduced, everyone thought relational databases were the best option for everything. Using the graphical editor to create a Schema, felt like using the popular 4th Dimension software, and was viewed as acceptable. People had not learned of the advantages of a faster, slimmer, NoSQL style database.
Things are different now. The relational aspect of databases is not as desirable as the speed of a flat database. Network syncing of the data, across platforms, cloud services, and multiple devices is considered a requirement for a modern App. We want a single consistent API to access a variable size database of objects. We want the same calls, whether we read the data from user settings, documents, or a network source.
And we don’t want to have to create, a schema every time. Now we have Swift Codable protocol to understand the data objects. Creating a Codable object should be all we need to do.
Yes, this will require some R&D work on your part. But if you do it well one time, thousands of Apple developers can use this new API to write better code. As it is now, each developer has to be a CoreData expert, to create something that is mediocre at best.
So please Apple, give me a Database API I will enjoy working with, not something everyone avoids.
A Concerned Developer.
Steve Sheets, Aug 21, 2019
Email: magesteve@mac.com
