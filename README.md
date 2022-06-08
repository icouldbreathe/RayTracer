# Ray Tracing in One Weekend

An attempt at making a ray tracer. Based on [Ray Tracing in One Weekend](https://raytracing.github.io/books/RayTracingInOneWeekend.html).

## Progress

- [x] Output an image (PPM)
- [x] Implement progress indicator
- [x] Implement basic vector class
- [x] Implement basic ray class
- [x] Implement basic camera, viewport and background
- [x] Implement a build solution (make)
- [ ] Ray-Sphere intersection
- [ ] Surface normals and multiple objects
- [ ] Antialiasing
- [ ] Diffuse materials
- [ ] Metal
- [ ] Dialectrics
- [ ] Positionable Camera
- [ ] Defocus Blur
- [ ] Final Render

## Usage
### Make

Use `make <debug|release>` to build debug or release builds. `make` or `make render` will also output the rendered image.

```shell
$ cd IOW_RayTracer
$ make <debug|release|render|remake|clean>
```

### View PPM files

Possible options [here](https://fileinfo.com/extension/ppm#portable_pixmap_image_file_open?target=_blank).
