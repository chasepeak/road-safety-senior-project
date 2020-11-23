# road-safety-senior-project

This machine learning model was constructed with images sourced from:

```
@InProceedings{MVD2017,
title=    {The Mapillary Vistas Dataset for Semantic Understanding of Street Scenes},
author=   {Neuhold, Gerhard and Ollmann, Tobias and Rota Bul\`o, Samuel and Kontschieder, Peter},
booktitle={International Conference on Computer Vision (ICCV)},
year=     {2017},
url=      {https://www.mapillary.com/dataset/vistas}
}
```

### Configuration
- Determine a set of labels that the model will identify, then update the array 'labels' in `machine_has_learned.ipynb` to adhere to that.
- Image label data is in PASCAL VOC format, and .xml label files should be stored within the same directories as the corresponding images. Create directories `train`, `validate` and `test` and populate them with your labeled/unlabeled street images.