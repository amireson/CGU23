---
layout: home
title: "WF-HYPE model workflow: a step backwards to “re-vectorize” WATFLOOD to advance reproducibility in hydrologic modelling"
---


Corresponding author: Dayal Wijayarathne: dayal.wijayarathne@ucalgary.ca

Coauthors: Nicholas Kouwen,Department of Civil & Environmental Engineering, University of Waterloo
 Tricia Stadnyk,Department of Geography, University of Calgary
 Alain Pietroniro,Department of Civil Engineering, University of Calgary 

The HYPE model is being generalized and automated in a Model Agnostic Framework (MAF) to improve the reproducibility of hydrologic experiments in large domains. The key contribution of current research is to show the general applicability of MAF by extending the MAF beyond the current models, HYPE, MESH, and SUMMA. Progress has been made to configure a gridded WATFLOOD model using a semi-distributed HYPE model instantiation. Code is written to create a vectorized WATFLOOD “watershed file” (shd.r2c) using the HYPE-Geofabric, “Basin file” (GeoData.txt), with other physiographic information for Bow River Basin (BRB) in Alberta, Canada. Each HYPE sub-basin outlet location is matched to a WATFLOOD grid cell, and that cell is given the identical attributes of the HYPE sub-watershed (many grid cells have no attributes and are ignored). Another code is written to generate WATFLOOD “events” using HYPE climate-forcing files (.txt) to facilitate the WATFLOOD run. To ensure that WATFLOOD cells have the identical precipitation and temperature as the HYPE model, the radius of influence is kept small (~1 grid size). The WF-HYPE workflow was tested for the BRB using Regional Deterministic Reforecast System (RDRS) climate data as meteorological input. Preliminary results show that WF-HYPE workflow model performances are comparable to HYPE model performances for the BRB, indicating the successful extension of MAF beyond the current MAF models. Even though WF-HYPE was tested for the BRB, the code was built to be applied to any watershed. Since the vector code written for HYPE-Geofabric can be used to expand the WATFLOOD domain to match World-wide HYPE, it is possible to generate WATFLOOD files Canada-wide and globally. This saves effort and time to develop a separate tool to configure WATFLOOD from scratch, saving more time for hydrological analysis. This study provides a prospect to add the WATFLOOD model to MAF, which offers the opportunity to use stable water isotopes to quantify hydrologic storages and fluxes using isoWATFLOOD across the globe.

Preferred format: Oral presentation
