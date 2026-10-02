# Matter vs antimatter in 1 GB of LHCb open data

Hands-on notebook for the talk *Open Datasets from CERN* (F. L. Redi), OpSciHack 2026, Zurich, 3 October 2026.

[**Open in Google Colab**](https://colab.research.google.com/github/leoredi/opscihack-2026-lhcb-open-data/blob/main/LHCb_matter_antimatter.ipynb), then choose *Runtime › Run all*.

The notebook downloads 1.1 GB of 2011 LHCb data (B± → h± h⁺ h⁻ candidates, [record 4900](https://opendata.cern.ch/record/4900), DOI [10.7483/OPENDATA.LHCB.AOF7.JH09](https://doi.org/10.7483/OPENDATA.LHCB.AOF7.JH09), CC0), selects three-kaon events and recomputes the B⁺/B⁻ asymmetry measured by LHCb in [Phys. Rev. Lett. 111 (2013) 101801](https://doi.org/10.1103/PhysRevLett.111.101801).

To run it locally instead: `pip install uproot awkward matplotlib jupyterlab`, then `jupyter lab LHCb_matter_antimatter.ipynb`.
