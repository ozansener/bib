- Hidden loops: your input features might be impacted by the performance (RL like setting, action impacts state). Undeclared consumer: you might not even aware who is using the output and causing hidden loops. There are lots of non-statinirity in the world, it might be good to timestamp and freeze things instead of using current ones. It might be good to use a tool which detects data/feature dependencies and annotate them. It is almost always better to use output of a different system as a additional feature instead of input. Most ML systems has 95% glue code and 5% algorithm. So, it might be beneficial to re-implement the algorithm.
- Good idea is state based, and a full graph of what impacts what so you know what is safe. Also, a visualization/metric pipeline for each. Timestamping/versioning all intermediate data properlt and may be writing seperate readers for each so it does not fail.