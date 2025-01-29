# sorting-visualizer
Java and data structure based project.
# How to use

### Build 
```
mkdir -p dist target
javac src/array/visualizer/ArrayVisualizer.java -sourcepath src -d target/
jar -cvfm dist/ArrayVisualizer.jar manifest.mf -C target/ ./
```

### Run
```
java -jar dist/ArrayVisualizer.jar
```
=======
