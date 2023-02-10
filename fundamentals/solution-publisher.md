# Solution publisher

Every solution has a publisher that should be specified when creating a solution.

The publisher of a solution where a component is created is considered the owner of that component. The owner of a component controls what changes other publishers of solutions including that component are allowed to make or restricted from making. It is possible to move the ownership of a component from one solution to another within the same publisher, but not across publishers. Once you introduce a publisher for a component in a managed solution, you can’t change the publisher for the component. Because of this, it's best to define a single publisher so you can change the layering model across solutions later.

The solution publisher specifies who developed the app. For this reason, you should create a solution publisher name that's meaningful.

### Solution publisher prefix <a href="#solution-publisher-prefix" id="solution-publisher-prefix"></a>

A solution publisher includes a prefix. The publisher prefix is a mechanism to help avoid naming collisions. This allows for solutions from different publishers to be installed in an environment with few conflicts.&#x20;
