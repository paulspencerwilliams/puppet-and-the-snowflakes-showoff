puppet-and-the-snowflakes-showoff
=================================

On Thursday 13th March, I ran my first [BlackPepper](http://www,blackpepper.co.uk) [brown bag session](http://www.youtube.com/channel/UCfv_O_imhIqQMfXXzJtTuOw/feed) on the subject of snowflake servers, immutable services, infrastructure as code and Puppet, Vagrant and Docker. I enjoyed myself, I hope others enjoyed the session and I certainly learnt a fair bit primarily on Puppet and Vagrant. 

This repo contains the ShowOff based slidedeck that supported the session, and I have seperate GitHub repos that contain the [Application Server](https://github.com/paulspencerwilliams/vagrant-clojure) and [Neo4j Database Server](https://github.com/paulspencerwilliams/vagrant-neo4j) Vagrant / Puppet instances supporting this session. 

To run this slidedeck, assuming you have a recently Ruby installed, install Showoff, clone this repo and then run Showoff in the root of this repo. This should do the trick:

    gem install showoff
    git clone git@github.com:paulspencerwilliams/puppet-and-the-snowflakes-showoff.git
    cd puppet-and-the-snowflakes-showoff
    showoff serve
    

    
