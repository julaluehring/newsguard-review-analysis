# newsguard-review-analysis

Public repository for [Best practices for source-based research on misinformation and news trustworthiness]([link to paper](https://doi.org/10.31234/osf.io/v6e4b)

We organized the subsections of our analysis in different Python notebooks. 
To reproduce the results, see the following scripts: 
1. Analyze trustworthiness and recreate Fig. 1 and 2: 'describe_trustworthiness.ipynb'
3. Compare NewsGuard with other lists: 'describe_overlaps.ipynb'
4. Analyze the political orientation labels and reproduce Fig. 4: 'describe_orientation.ipynb'
5. Analyze topic labels and reproduce Fig. 5: 'describe_topics.ipynb'

To recreate the conda environment, see 'environment.yml' or 'requirements.txt'.

In order to compile the dataset, we had access to NewsGuard's online database (Amazon S3 bucket). We followed a step-wise procedure:
1. We accessed and downloaded data from the NewsGuard database with the following code: 'access_newsguard.ipynb'
2. We tried different merging strategies to use multiple snapshots, see here: 'merge_snapshots.ipynb'
3. We observed some fluctuations in our sample depending on the strategy of merging the data, which is why we ended up sampling the database once per month: 'check_fluctuations.ipynb'
