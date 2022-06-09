# MArSum: Moroccan Articles Summarization dataset
- [Description](#description)
- [Dataset](#dataset)
- [Citation](#citation)

## Description

This dataset contains **19,806** news articles written in Moroccan Arabic dialect along with their titles. The articles were crawled from [Goud.ma](http://www.goud.ma) website between 01/01/2018 and 12/31/2020. 
The articles are written mainly in Moroccan Arabic dialect (Darija) but some of them contain Modern Standard Arabic (MSA) passages. All the titles are written in Darija. 
The following table summarize some tatistics on the MArSum Dataset.


<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky" rowspan="2">Size</th>
    <th class="tg-0pky" colspan="3">Titles length</th>
    <th class="tg-0pky" colspan="3">Articles length</th>
  </tr>
  <tr>
    <th class="tg-lqy6">Min.</th>
    <th class="tg-lqy6">Max.</th>
    <th class="tg-lqy6">Avg.</th>
    <th class="tg-lqy6">Min.</th>
    <th class="tg-lqy6">Max.</th>
    <th class="tg-0lax">Avg.</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-dvpl">19,806</td>
    <td class="tg-dvpl">2</td>
    <td class="tg-dvpl">74</td>
    <td class="tg-dvpl">14.6</td>
    <td class="tg-dvpl">30</td>
    <td class="tg-dvpl">2964</td>
    <td class="tg-0pky">140.7</td>
  </tr>
</tbody>
</table>

The following figure describes the creation process of MArSum:

![alt text](MArSum_schema_Color1.png)

You may refer to our paper, cited below, for more details on this process.

## Dataset

The dataset is split into Train/Test subsets using a 90/10 split strategy. Both subsets are available for direct donwload.
                      
## Citation

Please cite the following paper if you decise to use the dataset:

    Gaanoun, K., Naira, A. M., Allak, A., & Benelallam, I. (2022). Automatic Text Summarization for Moroccan Arabic Dialect
    Using an Artificial Intelligence Approach. In International Conference on Business Intelligence (pp. 158-177). Springer, Cham.
