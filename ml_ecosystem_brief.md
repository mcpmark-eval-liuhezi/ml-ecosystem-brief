# Machine Learning Ecosystem Briefing

A data-backed snapshot of who drives open-source machine learning on GitHub.

## How the data was gathered

GitHub's organization search was queried for the term "machine learning" with results ranked by follower count (descending), and the top five organizations actually returned by the search were taken: scikit-learn, ml-explore, LAION-AI, googlecolab, and thuml. For each of those organizations, a repository search ranked by star count was used to collect the ten most-starred repositories (50 repositories in total) along with each repository's primary language, and exact follower counts were read from each organization's GitHub profile. All collected data was aggregated in a Python script, and the metric summary below is reported exactly as the data returned it.

## The five organizations

| # | Organization | Followers | Flagship repository | Flagship stars |
|---|--------------|-----------|---------------------|----------------|
| 1 | scikit-learn | 5,775 | scikit-learn/scikit-learn | 67,829 |
| 2 | ml-explore | 5,486 | ml-explore/mlx | 28,843 |
| 3 | LAION-AI | 4,307 | LAION-AI/Open-Assistant | 37,369 |
| 4 | googlecolab | 3,652 | googlecolab/colabtools | 2,592 |
| 5 | thuml | 2,691 | thuml/Time-Series-Library | 12,970 |

## Metric summary

```
org_count: 5
repo_count: 50
top_org_by_followers: scikit-learn
total_stars: 197471
median_stars: 536.0
top_repo_overall: scikit-learn/scikit-learn (67829 stars)
top_language: Python (26 repositories)
```

---

*This briefing was compiled and published under the GitHub account **HeziLiu** (https://github.com/HeziLiu). Data sourced from GitHub's organization and repository search APIs at the time of collection.*