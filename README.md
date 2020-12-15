# tekton-scorecard-image
a SDK Scorecard custom image for the tekton operator

This is an example of an operator-sdk scorecard custom
test image.  It is designed specifically to test the 
tekton pipeline operator.

## Build the image

```
make image-build
```

## Setup the Required RBAC for the Tests

```
make installrbac
```

## Run the Scorecard Tests

```
make runtests
```
