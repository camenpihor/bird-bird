# Bird Bird

## Installation

### Requirements

- [protobuf](https://grpc.io/docs/protoc-installation/)
  - Unfortunately... The specific model we use here is not yet compatible with
    [TensorFlow](https://www.tensorflow.org/hub), and so we have to use the config
    language from tf1, which requires protobuf.

### Instructions

1. `git clone https://github.com/camenpihor/bird-bird.git`
1. `git submodule update --init`
1. Make sure that [Requirements](#Requirements) are installed
1. `scripts/install`

## Update Submodule

[For more info about git submodules...](https://git-scm.com/book/en/v2/Git-Tools-Submodules)

1. `git submodule update --init --remote --recursive`
