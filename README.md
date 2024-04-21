# ORB-SLAM3

Public Fork of the ORB-SLAM 3 repository made by
**Authors:** Carlos Campos, Richard Elvira, Juan J. Gómez Rodríguez, [José M. M. Montiel](http://webdiis.unizar.es/~josemari/), [Juan D. Tardos](http://webdiis.unizar.es/~jdtardos/).

Modified, used and run for 4th year final project.

Main project repository found at: [Pyperbot-v2]https://github.com/HahnLam20/Pyperbot-v2

#Installation of dependencies

To get this code to build correctly, first install the dependencies:
- OpenCV 4.2.0 and 3.2.0
- OpenCV 3.2.0
- Pangolin

# Build
To build, download the repository and build using
```
./build.sh
```


#Run

To run and execute the files , download the repository and execute:

Mono:
```
./Examples/Monocular/mono_euroc ./Pyperbot Config Files/PiModule3.yaml <images> <timestamp txt> <destination>

```

Mono-inertia:
```
./Examples/Monocular-Inertial/mono_inertial_euroc ./Vocabulary/ORBvoc.txt ./Pyperbot Config Files/PiModule3.yaml <images> <timestamp txt> <destination>
```
