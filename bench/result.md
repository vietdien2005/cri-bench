# Result Benchmark Container Runtimes

## CRI-containerd

- Container benchmark about basic operations on Container

    create Container - Fastest Time: 0.032s, Average Time: 0.044s ± 0.007s, Slowest Time: 0.058s
    start Container - Fastest Time: 0.073s, Average Time: 0.098s ± 0.011s, Slowest Time: 0.112s
    Container status - Fastest Time: 0.000s, Average Time: 0.001s ± 0.000s, Slowest Time: 0.003s
    stop Container - Fastest Time: 0.112s, Average Time: 0.126s ± 0.008s, Slowest Time: 0.145s
    remove Container - Fastest Time: 0.005s, Average Time: 0.006s ± 0.000s, Slowest Time: 0.007s

- PodSandbox benchmark about operations on PodSandbox benchmark about listing PodSandbox

    list PodSandbox - Fastest Time: 0.002s, Average Time: 0.004s ± 0.001s, Slowest Time: 0.008s

- Container benchmark about listing Container

    list Container - Fastest Time: 0.001s, Average Time: 0.001s ± 0.000s, Slowest Time: 0.002s

- Image benchmark about basic operations on Image

    pull Image - Fastest Time: 5.440s, Average Time: 5.663s ± 0.119s, Slowest Time: 5.883s
    Image status - Fastest Time: 0.000s, Average Time: 0.001s ± 0.000s, Slowest Time: 0.001s
    remove Image - Fastest Time: 0.025s, Average Time: 0.029s ± 0.004s, Slowest Time: 0.047s

- PodSandbox benchmark about start a container from scratch

    create PodSandbox and container - Fastest Time: 0.344s, Average Time: 0.369s ± 0.013s, Slowest Time: 0.401s

- PodSandbox benchmark about lifecycle of PodSandbox

    create PodSandbox - Fastest Time: 0.208s, Average Time: 0.235s ± 0.021s, Slowest Time: 0.311s
    PodSandbox status - Fastest Time: 0.000s, Average Time: 0.001s ± 0.000s, Slowest Time: 0.001s
    stop PodSandbox - Fastest Time: 0.349s, Average Time: 0.385s ± 0.014s, Slowest Time: 0.405s
    remove PodSandbox - Fastest Time: 0.006s, Average Time: 0.007s ± 0.001s, Slowest Time: 0.008s

- Image benchmark about listing Image

    list Container - Fastest Time: 0.001s, Average Time: 0.001s ± 0.002s, Slowest Time: 0.009s

## dockershim

- PodSandbox benchmark about lifecycle of PodSandbox

    create PodSandbox - Fastest Time: 0.404s, Average Time: 0.439s ± 0.021s, Slowest Time: 0.487s
    PodSandbox status - Fastest Time: 0.001s, Average Time: 0.001s ± 0.000s, Slowest Time: 0.002s
    stop PodSandbox - Fastest Time: 0.305s, Average Time: 0.324s ± 0.013s, Slowest Time: 0.362s
    remove PodSandbox - Fastest Time: 0.009s, Average Time: 0.011s ± 0.001s, Slowest Time: 0.013s

- PodSandbox benchmark about start a container from scratch

    create PodSandbox and container - Fastest Time: 0.573s, Average Time: 0.631s ± 0.024s, Slowest Time: 0.682s

- Image benchmark about listing Image

    list Container - Fastest Time: 0.001s, Average Time: 0.002s ± 0.000s, Slowest Time: 0.003s

- Image benchmark about basic operations on Image

    pull Image - Fastest Time: 2.700s, Average Time: 2.810s ± 0.118s, Slowest Time: 3.192s
    Image status - Fastest Time: 0.001s, Average Time: 0.002s ± 0.001s, Slowest Time: 0.005s
    remove Image - Fastest Time: 0.001s, Average Time: 0.001s ± 0.000s, Slowest Time: 0.001s

- Container benchmark about listing Container

    list Container - Fastest Time: 0.002s, Average Time: 0.002s ± 0.000s, Slowest Time: 0.003s

- Container benchmark about basic operations on Container

    create Container - Fastest Time: 0.059s, Average Time: 0.073s ± 0.007s, Slowest Time: 0.083s
    start Container - Fastest Time: 0.086s, Average Time: 0.105s ± 0.010s, Slowest Time: 0.128s
    Container status - Fastest Time: 0.002s, Average Time: 0.002s ± 0.000s, Slowest Time: 0.003s
    stop Container - Fastest Time: 0.151s, Average Time: 0.171s ± 0.014s, Slowest Time: 0.215s
    remove Container - Fastest Time: 0.010s, Average Time: 0.011s ± 0.002s, Slowest Time: 0.015s

- PodSandbox benchmark about operations on PodSandbox benchmark about listing PodSandbox

    list PodSandbox - Fastest Time: 0.002s, Average Time: 0.002s ± 0.000s, Slowest Time: 0.003s

## CRI-O

- Container benchmark about basic operations on Container

    create Container - Fastest Time: 0.099s, Average Time: 0.108s ± 0.006s, Slowest Time: 0.123s
    start Container - Fastest Time: 0.029s, Average Time: 0.032s ± 0.003s, Slowest Time: 0.046s
    Container status - Fastest Time: 0.000s, Average Time: 0.000s ± 0.000s, Slowest Time: 0.001s
    stop Container - Fastest Time: 0.137s, Average Time: 0.142s ± 0.005s, Slowest Time: 0.158s
    remove Container - Fastest Time: 0.018s, Average Time: 0.020s ± 0.001s, Slowest Time: 0.023s

- Container benchmark about listing Container

    list Container - Fastest Time: 0.000s, Average Time: 0.001s ± 0.000s, Slowest Time: 0.001s

- PodSandbox benchmark about lifecycle of PodSandbox

    create PodSandbox - Fastest Time: 0.225s, Average Time: 0.241s ± 0.006s, Slowest Time: 0.254s
    PodSandbox status - Fastest Time: 0.000s, Average Time: 0.001s ± 0.001s, Slowest Time: 0.003s
    stop PodSandbox - Fastest Time: 0.196s, Average Time: 0.202s ± 0.004s, Slowest Time: 0.212s
    remove PodSandbox - Fastest Time: 0.018s, Average Time: 0.019s ± 0.001s, Slowest Time: 0.021s

- Image benchmark about listing Image

    list Container - Fastest Time: 0.001s, Average Time: 0.001s ± 0.001s, Slowest Time: 0.005s

- PodSandbox benchmark about start a container from scratch

    create PodSandbox and container - Fastest Time: 0.372s, Average Time: 0.387s ± 0.019s, Slowest Time: 0.463s

- PodSandbox benchmark about operations on PodSandbox benchmark about listing PodSandbox

    list PodSandbox - Fastest Time: 0.000s, Average Time: 0.000s ± 0.000s, Slowest Time: 0.001s

- Image benchmark about basic operations on Image

    pull Image - Fastest Time: 7.690s, Average Time: 7.882s ± 0.148s, Slowest Time: 8.264s
    Image status - Fastest Time: 0.002s, Average Time: 0.002s ± 0.001s, Slowest Time: 0.008s
    remove Image - Fastest Time: 0.009s, Average Time: 0.011s ± 0.002s, Slowest Time: 0.017s

## gVisor (runsc)

- PodSandbox benchmark about start a container from scratch

    create PodSandbox and container - Fastest Time: 0.353s, Average Time: 0.392s ± 0.026s, Slowest Time: 0.454s

- Container benchmark about listing Container

    list Container - Fastest Time: 0.001s, Average Time: 0.002s ± 0.002s, Slowest Time: 0.012s

- Image benchmark about basic operations on Image

    pull Image - Fastest Time: 5.440s, Average Time: 5.713s ± 0.286s, Slowest Time: 6.834s
    Image status - Fastest Time: 0.001s, Average Time: 0.001s ± 0.000s, Slowest Time: 0.001s
    remove Image - Fastest Time: 0.027s, Average Time: 0.029s ± 0.004s, Slowest Time: 0.046s

- PodSandbox benchmark about operations on PodSandbox benchmark about listing PodSandbox

    list PodSandbox - Fastest Time: 0.002s, Average Time: 0.003s ± 0.000s, Slowest Time: 0.004s

- Container benchmark about basic operations on Container

    create Container - Fastest Time: 0.035s, Average Time: 0.045s ± 0.006s, Slowest Time: 0.057s
    start Container - Fastest Time: 0.069s, Average Time: 0.101s ± 0.015s, Slowest Time: 0.130s
    Container status - Fastest Time: 0.001s, Average Time: 0.001s ± 0.000s, Slowest Time: 0.001s
    stop Container - Fastest Time: 0.108s, Average Time: 0.131s ± 0.012s, Slowest Time: 0.156s
    remove Container - Fastest Time: 0.005s, Average Time: 0.006s ± 0.001s, Slowest Time: 0.010s

- Image benchmark about listing Image

    list Container - Fastest Time: 0.001s, Average Time: 0.001s ± 0.000s, Slowest Time: 0.001s

- PodSandbox benchmark about lifecycle of PodSandbox

    create PodSandbox - Fastest Time: 0.211s, Average Time: 0.239s ± 0.014s, Slowest Time: 0.259s
    PodSandbox status - Fastest Time: 0.000s, Average Time: 0.001s ± 0.000s, Slowest Time: 0.001s
    stop PodSandbox - Fastest Time: 0.353s, Average Time: 0.380s ± 0.015s, Slowest Time: 0.410s
    remove PodSandbox - Fastest Time: 0.006s, Average Time: 0.007s ± 0.001s, Slowest Time: 0.009s
