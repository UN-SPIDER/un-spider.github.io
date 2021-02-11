---
layout: project
permalink: /:title/
category: projects

meta:
  keywords: "Floods, Python"

project:
  title: "Radar-based Flood Mapping"
  type: "Jupyter Notebook"
  url: "https://github.com/UN-SPIDER/radar-based-flood-mapping"
  logo: "/assets/images/projects/flood_mapping/flood_mapping_overview.jpg"
  tech: "Python, snappy, Sentinel-1"  

images:
  - image:
    url: "/assets/images/projects/flood_mapping/flood_mapping_python_ouput.png"
    alt: "Resulting flood mask for interactive visualization and export."
  - image:
    url: "/assets/images/projects/flood_mapping/flood_mapping_python_input.png"
    alt: "Input parameters required to execute script."
  - image:
    url: "/assets/images/projects/flood_mapping/flood_mapping_python_processing.png"
    alt: "Sentinel-1 radar imagery processing steps."
  - image:
    url: "/assets/images/projects/flood_mapping/flood_mapping_python_histogram.png"
    alt: "Automatic identification of waters using Sentinel-1 radar imagery based on minimum histogram value."
---
<p>The objective of this Recommended Practice is to determine the extent of flooded areas. The usage of Synthetic Aperture Radar (SAR) satellite imagery for flood extent mapping constitutes a viable solution with fast image processing, providing near real-time flood information to relief agencies for supporting humanitarian action.</p><br>
<p>This Jupyter Notebook covers the full processing chain from data query and download up to the export of a final flood mask product by utilizing open access Sentinel-1 SAR data.</p>