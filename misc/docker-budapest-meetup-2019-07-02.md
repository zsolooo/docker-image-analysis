# Meetup notes

## Karesz

- buildx over buildkit
- multiplatform image build via qemu
- ARM support
- containerd industry standatrd
- docker foundation?
- docker captain twitter list

- collabnix.com blog

- 19.03 includes native GPU support, no nvidia plugin required

- jetsson nano?

- community theater, Karoly Kass video on official site

- mentoring: why mentors matter

## Lalyos

<https://www.slideshare.net/AkihiroSuda/kubeconeu-building-images-efficiently-and-securely-on-kubernetes-with-buildkit>

- multistage dependency graph can be parallelized -> buildkit does it

    ```bash
    BUILDKIT_HOST=docker-container://buildkit
    BUILDKIT_HOST=kube-pod://buildkit
    ```

- buildkit architecture

```asciidrawing
INPUTFILE   ->   frontend    ->    solver     ->     ARTIFACT
               dockerfile.v0
                 Procfile
                   ...
```

- buildkit not send context anymore

- can compile go modules: <https://asciinema.org/a/138699>

- WebAssembly + Docker Meetup 5/23/2019
