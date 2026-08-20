# Marine Heatwave Monitoring in Spain with <code>copernicusmarine</code> & <code>xarray

This repository contains interactive Python tutorials designed to demonstrate how to programmatically create Marine Heat Waves data set, based on the high-resolution **Sea Surface Temperature** (**SST**) data using the `copernicusmarine` API and `xarray`. 

By applying the **Hobday et al.** Marine Heatwave (MHW) classification framework, we calculate 30-year climate baselines (1991–2020) and generate spatial maps of daily and monthly MHW categories across key coastal zones in Spain (Balearic Sea and Galician Rías).

---

## 📚 Notebooks Included

We provide two identical versions of the tutorial:

* 🇬🇧 **[Marine Heatwave Tutorial (English)](marine_heat_waves.ipynb)** — Full English walkthrough.
* 🇪🇸 **[Tutorial de Olas de Calor Marinas (Español)](marine_heat_waves_spanish.ipynb)** — Traducción completa al español.

---

## 🛠️ Environment Setup

To run the notebooks without dependency conflicts (ensuring compatible versions of `copernicusmarine`, `xarray`, `cartopy`, and `matplotlib`), use the provided `cop_env.yml` file.

```bash
conda env create -f cop_env.yml
conda activate cop_mar_env
```

<hr>
&copy; 2026 thriveGEO GmbH
