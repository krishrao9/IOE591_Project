# IOE591_Project
## Vehicle Routing Problem applied to grocery delivery at Ann Arbor

For this purpose we use the city of Ann Arbor with Kroger stores as the depot for our vehicles,
and based on the residential areas we distribute the customers throughout the region. The goal
is to determine the optimal route from the depots to each customer location which generates the
minimum travel cost. Two approaches have been discussed here, one with vehicles being allocated
through bin-packing applied to different items, and the other by assuming all item demands into
a single overall demand. The problem is then divided into three parts - Single-depot VRP, Multidepot
VRP and heuristic approach through k-Means clustering - to understand trade-offs between
alternatives. Through our results we try to highlight what factors come into play in achieving a good
objective value in each alternative and the choice of best performing model based on CPU runtime
and achieved objective value.


