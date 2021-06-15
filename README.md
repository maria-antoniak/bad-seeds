[**Bad Seeds: Evaluating Lexical Methods for Bias Measurement**](https://maria-antoniak.github.io/resources/2021_acl_bad_seeds.pdf)  
Maria Antoniak and David Mimno  
ACL 2021

This repository contains the seed lexicons gathered and evaluated in the above research paper.

You can view all the gathered seeds by clicking on the `gathered_seeds.json` file above.

You can load the seeds into a Pandas dataframe using the following Python snippet:

```
import pandas as pd
seeds_df = pd.read_json(json_path, orient='records')
```

When using these seeds, make sure to cite the original papers and give credit to the authors who curated the seed sets. Citations are given for each set in the JSON file.

If the seed list is empty, this means that we were unable to find a documented seed list for that category and paper.

If you'd like to add new seed sets or improve the documentation for this project, please submit a pull request or contact Maria Antoniak.
