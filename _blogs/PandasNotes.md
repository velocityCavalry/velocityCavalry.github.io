# Pandas Notes

1. Import

   ```import pandas as pd```

2. read tsv: 

   ```pd.read_csv(f'{name}.tsv', sep="\t", encoding='utf-8')```

   If tsv has no header, ```header=None```

   Select particular columns: ```usecols=['words', 'labels']```

   Or select the column idx,  ```usecols=[0, 1]```

3. $$\lambda$$

4. 