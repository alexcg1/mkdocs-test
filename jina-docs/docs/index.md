# Welcome to Jina!

!!! tip

    Take our **[user experience survey](https://10sw1tcpld4.typeform.com/to/EGAEReM7?utm_source=doc&utm_medium=github&utm_campaign=user%20experience&utm_term=feb2023&utm_content=survey)** to let us know your thoughts and help shape the future of Jina!

{%
   include-markdown "../README.md"
   start="<!-- start jina-description -->"
   end="<!-- end jina-description -->"
%}

## Install

Make sure that you have Python 3.7+ installed on Linux/macOS/{ref}`Windows <jina-on-windows>`.

=== "via PyPI"
    ```shell
    pip install -U jina
    ```

=== "via Conda"
    ```shell
    conda install jina -c conda-forge
    ```

## Getting Started

Jina supports developers in building AI services and pipelines:



=== "Build AI Services"
    {%
       include-markdown "../README.md"
       start="<!-- start build-ai-services -->"
       end="<!-- end build-ai-services -->"
    %}

=== "Build Pipelines"
    {%
       include-markdown "../README.md"
       start="<!-- start build-pipelines -->"
       end="<!-- end build-pipelines -->"
    %}


## Next steps

:::::{grid} 2
:gutter: 3


::::{grid-item-card} {octicon}`cross-reference;1.5em` Learn DocArray API
:link: https://docarray.jina.ai

DocArray is the foundational data structure of Jina. Before starting Jina, first learn DocArray to quickly build a PoC. 
::::

::::{grid-item-card} {octicon}`gear;1.5em` Learn Executor
:link: concepts/executor/index
:link-type: doc

{term}`Executor` is a Python class that can serve logic using `Documents`.

::::

::::{grid-item-card} {octicon}`workflow;1.5em` Learn Flow
:link: concepts/flow/index
:link-type: doc


{term}`Flow` orchestrates Executors into a processing pipeline to accomplish a task.
::::

::::{grid-item-card} {octicon}`package-dependents;1.5em` Explore Executor Hub
:link: concepts/executor/hub/index
:link-type: doc
:class-card: color-gradient-card-1


Executor Hub is a marketplace that allows you to share, explore and test Executors.

::::


::::{grid-item-card} {octicon}`cpu;1.5em` Deploy a Flow to Cloud
:link: concepts/jcloud/index
:link-type: doc
:class-card: color-gradient-card-2

Jina AI Cloud is the MLOps platform for hosting Jina projects.
::::



:::::
{%
   include-markdown "../README.md"
   start="<!-- start support-pitch -->"
   end="<!-- end support-pitch -->"
%}
