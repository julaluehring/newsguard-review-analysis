# newsguard-review-analysis

Public repository for [link to paper].
We organized the subsections of our analysis in different Python notebooks. To reproduce the results, see the following scripts: 
1. How to analyze trustworthiness and re-create figures 1 and 2: 'describe_trustworthiness.ipynb'
3. How to analyze overlaps with other lists: 'describe_overlaps.ipynb'
4. How to analyze orientation: 'describe_orientation.ipynb'
5. How to analyze topics: 'describe_topics.ipynb'


To recreate the conda environment, see 'environment.yml' or 'requirements.txt'.
We downloaded data from the NewsGuard database with the following code: 'access_newsguard.ipynb'
In addition, we tried different merging strategies to use multiple snapshots: 'merge_snapshots.ipynb'
We observed some fluctuations in our sample depending on the strategy of merging the data, see here: 'check_fluctuations.ipynb'

