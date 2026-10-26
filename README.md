# Dataset

### USAGE IN PROJECT

| # | Dataset Feature Name | Frontend UI Component Location (Where it maps) | Interaction Type |
|---|---|---|---|
| 1 | Historical_Crop_Sequence | Section 2: "Previous 2-3 crops / Crop history" dropdown matrices. | User Input |
| 2 | Target_Recommended_Crop | "Recommended Next Crop / Best next crop" card block (e.g., Summer Moong). | Model Target Output (Y) |
| 3 | Bacterial_Abundance_16S | Section 2: "Beneficial bacteria" & "Nitrogen-fixers" meter scores (72/100 block). | Model Output View |
| 4 | Fungal_Abundance_ITS | Section 2: "Fungi" horizontal meter score indicator bar. | Model Output View |
| 5 | Soil_ID | Hidden database transactional identifier. | System Metadata |
| 6 | Location_Latitude | Section 1: Generated when clicking "Use my location" or entering Village. | Auto-Inferred / API |
| 7 | Location_Longitude | Section 1: Generated when clicking "Use my location" or entering Village. | Auto-Inferred / API |
| 8 | Depth_cm | Section 3: Inferred based on the user's selected "Days since sowing (75 days)" root extension. | System Calculation |
| 9 | Texture | Desktop Summary Card: "Soil Type: Alluvial (auto from location)" label window. | Auto-Inferred / API |
| 10 | pH | Soil Score Card: Modulates the "Status: Okay / Moderate" radial gauge dial text. | Model Output View |
| 11 | Organic_Matter_% | Output Section: Drives the narrative warning "cereal-cereal rotation is draining the microbiome". | Model Output View |
| 12 | Moisture_Content_% | Section 3: Baseline linked directly to the selected "Irrigation (Tubewell/Canal)" choice. | User Input Interaction |
| 13 | Bulk_Density_g/cm³ | Background physical constraint mapped to the layout's "Field Size: 2.5 acre" density block. | System Calculation |
| 14 | Nitrogen_N_ppm | "Why it works" card text: Mapped directly to the "Moong can leave 20–40 kg N/acre" metric. | Model Output View |
| 15 | Phosphorus_P_ppm | Sub-surface nutrient engine calculation that scores the crop recommendation logic. | System Calculation |
| 16 | Potassium_K_ppm | Sub-surface nutrient engine calculation that scores the crop recommendation logic. | System Calculation |
| 17 | Cation_Exchange_Capacity_meq/100g | Soil buffer capacity constraint linked to the regional Alluvial soil profile configuration. | Auto-Inferred / API |
| 18 | Electrical_Conductivity_dS/m | Salinity check score that triggers the "Soil test not necessary" validation label. | Model Output View |
| 19 | Soil_Color | Tied to the visual theme color updates in the UI summary headers based on regional soil. | System UI Styling |
| 20 | Porosity_% | Aeration attribute layer tied to the "Standing crop (75 days)" compaction assessment. | System Calculation |
| 21 | Water_Holding_Capacity_% | Section 3: Directly matched to evaluate the "Irrigation status / Low water requirements" tags. | User Input Match |
| 22 | Daily_Precipitation_mm | Weather Widget: Integrated into the "Greater Noida 32°C" top banner API stream. | Live Web API |
| 23 | Mean_Air_Temperature_C | Weather Widget: Integrated into the "Greater Noida 32°C" top banner API stream. | Live Web API |
| 24 | Actual_Evapotranspiration_mm | Micro-climate parameters used to evaluate the "60 days return time" survival factor. | System Calculation |
| 25 | Root_Zone_Moisture_Capacity | Checked against the crop state selection buttons (Just Sown / Standing / Near Harvest). | User Input Match |
| 26 | Water_Table_Depth_m | Mapped via the "Western Uttar Pradesh Map Indicator Graphic" on the laptop screen. | Auto-Inferred / API |
| 27 | Mean_Soil_Depth_m | Mapped via the "Western Uttar Pradesh Map Indicator Graphic" on the laptop screen. | Auto-Inferred / API |
