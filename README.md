# VITAL
Code of our paper - "VITAL: A New Dataset for Benchmarking Pluralistic Alignment in Healthcare"

**arXiv (Pre-print) version: [link](https://arxiv.org/abs/2502.13775)**

<br />

**The contributions of this work are as follows:**
- To the best of our knowledge, this work is the first to explore the pluralistic alignment of LLMs, specifically within the health domain.
- We construct and introduce a comprehensive benchmark dataset, VITAL, concentrating on the health domain for various pluralistic alignment methodologies.
- Using this dataset, we benchmark and evaluate the current state-of-the-art (SOTA) pluralistic alignment techniques through detailed analyses and ablation studies.
  Our findings demonstrate that current leading models exhibit limited performance on VITAL.

<br />

<div align="center">

<table>
  <tr>
    <td align="center">
      <img width="400" alt="Pluralistic alignment example" src="https://github.com/user-attachments/assets/ff82048e-62f6-44e3-8366-1998b11b4108" />
      <p><strong>A pluralistic alignment example from VITAL dataset</strong></p>
    </td>
    <td align="center">
      <img width="400" alt="Overview of alignment datasets" src="https://github.com/user-attachments/assets/23648543-b898-4038-9a71-125ac975091b" />
      <p><strong>Overview of alignment datasets</strong></p>
    </td>
  </tr>
</table>

</div>

<br />


## Abstract
Alignment techniques have become central to
eensuring that Large Language Models (LLMs)
generate outputs consistent with human values. However, existing alignment paradigms
often model an averaged or monolithic preference, failing to account for the diversity of perspectives across cultures, demographics, and
communities. This limitation is particularly
critical in health-related scenarios, where plurality is essential due to the influence of culture,
religion, personal values, and conflicting opinions. Despite progress in pluralistic alignment,
no prior work has focused on health, likely
due to the unavailability of publicly available
datasets. To address this gap, we introduce
VITAL, a new benchmark dataset comprising
13.1K value-laden situations and 5.4K multiple-choice questions focused on health, designed
to assess and benchmark pluralistic alignment
methodologies. Through extensive evaluation
of eight LLMs of varying sizes, we demonstrate
that existing pluralistic alignment techniques
fall short in effectively accommodating diverse
healthcare beliefs, underscoring the need for
tailored AI alignment in specific domains. This
work highlights the limitations of current approaches and lays the groundwork for developing health-specific alignment solutions.

## Citing

```
@article{shetty2025vital,
  title={VITAL: A New Dataset for Benchmarking Pluralistic Alignment in Healthcare},
  author={Shetty, Anudeex and Beheshti, Amin and Dras, Mark and Naseem, Usman},
  journal={arXiv preprint arXiv:2502.13775},
  year={2025}
}
```

### 
Our code is based on the work of [Modular Pluralism](https://github.com/BunsenFeng/modular_pluralism/)
