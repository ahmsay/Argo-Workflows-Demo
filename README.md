# Tekton-Demo

This repository contains basic examples from Tekton. It will be in more detail over time.
https://tekton.dev/docs/

### Keynotes
- If you are trying this on your own computer (e.g. Docker Desktop), Tekton will automatically create a PV when a PVC for a pipeline is created.
- Each pipelinerun references from a pipeline.
- Even if a task is defined in Tekton Community Hub, referencing it will not be enough. The task always must be created explicitly.
- When a pipelinerun is created (by ui or using kubectl), it will immediately start a new pipeline and execute the tasks inside it.
