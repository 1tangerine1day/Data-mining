# Data-mining HW
## Association Rules (FP-Growth) 
    Tid Items
    100 A, C, D
    200 B, C, E
    300 A, B, C, E
    400 B, E

    Strong rule
    {B, E}->C (2/3)
    C->A (2/3)
    A->C (2/2)
## Sequential Pattern (PrefixSpan) 
    SID Sequences
    100 <(1,5) (2) (3) (4)>
    200 <(1) (3) (4) (3,5)>
    300 <(1) (2) (3) (4)>
    400 <(1) (3) (5)>
    500 <(4) (5)>
 
    Some frequent sequential patterns
    {1,2,3,4}, {1,3,5}, {4,5}

## Classification (decision tree with gini index) 

    @attribute marital_status {S,M}
    @attribute num_children_at_home numeric
    @attribute member_card {Basic,Normal,Silver,Gold}
    @attribute age numeric
    @attribute year_income numeric

    Example database:
      {0 M,1 1,2 Silver,3 82,4 40000}
      {0 M,1 2,2 Silver,3 53,4 40000}
      
    {0 M,1 1,3 59,4 60000} member_card = basic
    {1 3,2 Silver,3 43,4 160000} member_card = basic
    {0 M,1 2,3 52,4 120000} member_card = silver 

## Clustering(Dbscan)

    Input: given a node with two dimensional attributes X and Y 
    Output: group these nodes into several clusters. The format is X Y ClusterID 
    Example 
    Input 2 3 (X=2, Y=3)
    Output 2 3 1(X=2 Y=3 ClusterID=1)
    
    There are five test data in the attachments
    Each row is a data point with x and y value
    Hint: 
    Test1-3 should be clustered to 4 clusters

