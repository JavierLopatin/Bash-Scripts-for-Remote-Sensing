# Bash-Scripts-for-Remote-Sensing

### Here you find a set of Unix bash sripts to process images in bach mode using gdal tools.

### For example, you can use them as:
- Convert all images in a directory to GTiff
  - sh Convert2TIFF.sh Input/directory/ Output/directoy/ inputFileExtension

- Change the resolution information in the metadata:
  - sh SetResolution.sh Input/directory/ Output/directoy/ outputResolution

- Transform the raster resolution:
  - sh TransformImageRes.sh Input/directory/ Output/directoy/ inputFileExtension outputResolution

