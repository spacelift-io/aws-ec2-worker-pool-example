# AWS EC2 Worker Pool Example

This repository is a self-contained example of how to create a private Spacelift worker pool on AWS EC2. This is meant as an example for learning purposes. It is not production-ready.

## Instructions

- Fork this repository.
- [Create a stack in your Spacelift account](https://docs.spacelift.io/concepts/stack/creating-a-stack) that uses the forked repository. Make sure to mark the stack as [administrative](https://docs.spacelift.io/concepts/stack/stack-settings#administrative).
- Create an [AWS Cloud Integration](https://docs.spacelift.io/integrations/cloud-providers/aws), if needed.
- [Attach an AWS Cloud Integration to the stack](https://docs.spacelift.io/integrations/cloud-providers/aws#using-the-integration).
- [Trigger a tracked run](https://docs.spacelift.io/concepts/run/tracked#triggering-manually).

Once the tracked run successfully completed, you should have a new Worker Pool configured and ready to use. To test it, have a stack use it and trigger a run for that stack.
