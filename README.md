# The Graph Network - Econometric Analysis & Predictive Modelling Research

Website - https://thegraph.com/

This cadCAD model and notebook series is part of an on-going effort to analyze The Graph protocol's econometric design, simulate its behaviour under different market conditions, and create tools and libraries which can be used by the community to better understand its behaviour.

If you want to contribute / get involved, you can join our Discord server here - https://discord.gg/CpMYTU7ewb 

## About The Graph
The Graph Network decentralizes the API and query layer of the internet application stack.
 - In The Graph Network, any Indexer will be able to stake Graph Tokens (GRT) to participate in the network and earn rewards for indexing subgraphs and fees for serving queries on those subgraphs.
 - Consumers will be able to query this diverse set of Indexers by paying for their metered usage, proving a model where the laws of supply and demand sustain the services provided by the protocol.
 
 ## Protocol Roles
 These are the roles that interact with the system, the behaviors they must engage in for the protocol to function correctly, and what incentives motivate them.
 
 - Consumers : Consumers pay Indexers for queries. These will typically be end users but could also be web services or middleware that integrate with The Graph.

 - Indexers : Indexers are the node operators of The Graph. They are motivated by earning financial rewards.

 - Curators : Curators use GRT to signal what subgraphs are valuable to index. These will typically be developers and share their motivations but could also be end users supporting a valuable service they rely upon or a persona that is purely financially motivated.

 - Delegators : Delegators put GRT at stake on behalf of an Indexer in order to earn a portion of indexer rewards and fees, without having to personally run a Graph Node. They are financially motivated.


## What is cadCAD?
cadCAD (complex adaptive dynamics Computer-Aided Design) is a python based modeling framework for research, validation, and Computer Aided Design of complex systems. Given a model of a complex system, cadCAD can simulate the impact that a set of actions might have on it. This helps users make informed, rigorously tested decisions on how best to modify or interact with the system in order to achieve their goals. cadCAD supports different system modeling approaches and can be easily integrated with common empirical data science workflows. Monte Carlo methods, A/B testing and parameter sweeping features are natively supported and optimized for.
