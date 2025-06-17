# Tree-Crown-Detection-ArcGis
Tree Crown Detection using ArcGIS Pro Deep Learning tools and NAIP imagery

#Tools Used
- ArcGIS Pro (Object Detection tools)
- NAIP Imagery (1-meter resolution)
- Deep Learning model (Tree crown detection)
- Symbology classification by confidence
- Map layout tools for final visualization


## 🔄 Workflow Summary

1. Clipped NAIP imagery to area of interest
2. Ran “Detect Objects Using Deep Learning” with a pretrained tree model
3. Styled results by confidence score using graduated color symbology
4. Exported detections as a shapefile (`tree_count_polygons.zip`)
5. Designed a map layout with:
   - North arrow
   - Scale bar
   - Legend (confidence and RGB bands)
6. Exported final layout as `final_layout_map.png`



## 📂 Files in This Repository

| File | Description |
|------|-------------|
| `tree_count_polygons.zip` | Shapefile of tree crown detections |
| `clipped_naip.tif` | NAIP image used for detection |
| `final_layout_map.png` | Final map layout showing results |
