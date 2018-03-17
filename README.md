# bbassett/openscad
This image is useful for automatically building 3D printing models designed in [OpenSCAD](http://www.openscad.org/).

## To Run
```
docker run -v /path/to/scad-files:/src bbassett/openscad openscad -o /src/file.stl /src/file.scad
```

