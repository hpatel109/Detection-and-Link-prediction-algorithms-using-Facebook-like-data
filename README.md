# Detection-and-Link-prediction-algorithms-using-Facebook-like-data

Here, I implemented community detection and link prediction algorithms using Facebook "like" data.
The file `edges.txt.gz` indicates like relationships between facebook users. This was collected using snowball sampling: beginning with the user "Bill Gates", I crawled all the people he "likes", then, for each newly discovered user, I crawled all the people they liked.
We clustered the resulting graph into communities, as well as recommend friends for Bill Gates.
