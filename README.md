# CDNdataset

The CDN domain name detection dataset.
Dataset is made up of 8189 features equences.
The first 38 rows is one-hot encoding of url, from a to z, 0 to 9 and blank space and dot.
The 39th field represents the number of resolution IPs.
The 40th field represents the access counts in sampling time(15 min)
The 41st, 42nd, 3rd field represents the num of dot, hyphen and digits.
The 44th represents if the 'cdn' is in url.
The 45th 46th are the resolution chain length of C\A record.
The 47th is the jaccard distance
The 48th is the time varying access count

The 49th is the label, 0 represents non=cdn, 1 represents cdn.

The data is from China Telecom and the label comes from CDNPlanet in 2023/3/17.
