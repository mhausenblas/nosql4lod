# BNSOL: Benchmarking NoSQL solutions for Linked Data processing

[I](https://github.com/mhausenblas) recently asked: [can NoSQL help us in processing Linked Data](http://webofdata.wordpress.com/2011/05/02/nosql-linked-data-processing/)? Now, let's see where we are. 


This is benchmark, BNSOL, is to my knowledge the first attempt to benchmark NoSQL systems concerning Linked Data processing capabilities. It won't be perfect and it won't be comprehensive in the first iteration, but, hey, it's a start ;)

If you want to help out or have an idea what to improve, let me know ... 

## Candidates

For now, from each NoSQL family one representative is chosen. As an introduction, you might want to check out Rick Cattell's brilliant page on [scalable datastores](http://www.cattell.net/datastores/) - I'm following his categorisation to name the families:

* For key-value stores: [Riak](http://riak.basho.com/)
* For document stores: [MongoDB](http://mongodb.org/)
* For extensible-record stores: [Cassandra](http://cassandra.apache.org/)
* For graph stores: [Neo4j](http://neo4j.org/)

Why did I choose these? I guess a mixture of how mature and widely used they are as well as some earlier experiences. I plan to add more candidates over time.

## Data

I don't know yet, but for the start I'll put together some RDF documents myself and then, once the BNSOL infrastructure (environment + client) is stable, I guess I'll move to something more heavy-weight like the [BTC-2010](http://km.aifb.kit.edu/projects/btc-2010/).

## Environment

Hm. Either I'm going to use our in-house cluster at DERI or EC2 will have to do the job. Let's see. For now, all I need is my laptop.

Yahoo's [YCSB](https://github.com/brianfrankcooper/YCSB) looks like a promising start as well.

## License

The software and other artefacts (such as configurations, etc.) provided in the repository are in the Public Domain.