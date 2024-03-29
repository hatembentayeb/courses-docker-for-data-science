---
title: 'Docker basic command line'
description: 'master the basics of docker Cli'
free_preview: true
---

## What is Docker ?

```yaml
type: PureMultipleChoiceExercise
key: 0c70786226
xp: 50
```

Docker is the most container technology used in the market, It was first started in 2013 and is developed by `Docker, Inc.`.
But what is a `container` ?.

The container is an environment that is isolated ( little bit like the virtual machine ) from the host OS which mean it has his own processes and file system  but it shares the basic infrastructure which is the Linux kernel. The `Docker engine (server)` is the responsible for running and managing containers ( clients ).



Docker is used to ship all the requirements of the application like libraries, configuration files  and source code in a single package called `image`. images are a collection of layers ( locked and editable). locked layers belongs to the base image, editable layers are created in the build phase and it contains the app source code and config files.  


How to create a docker image ? `Dockerfile` is a yaml file that contain instructions or steps to build custom images based on a standard images like Alpine, debian, ubuntu and centos often founded on `Dockerhub` which is a public container registry that contains a lot of images created by other people. 

Docker is used to ship all the requirements of the application like libraries, configuration files  and source code in a single package called `image`. images are a collection of layers ( locked and editable). locked layers belongs to the base image, editable layers are created in the build 
phase and it contains the app source code and config files.  


How to create a docker image ? `Dockerfile` is a yaml file that contain instruction or steps to build custom images based on a standard images (alpine, Debian, Ubuntu, Centos ...) often founded on `Dockerhub` which is a public container registry that contains a lot of images created by other people. 


_Choose  the correct statement that `Describe` Docker._ 




<!-- Guidelines for the question: https://instructor-support.datacamp.com/en/articles/2375516-course-multiple-choice-exercises. -->

`@hint`
<!-- Examples of good hints: https://instructor-support.datacamp.com/en/articles/2379164-hints-best-practices. -->
- Docker images are based on the `linux kernel`

`@possible_answers`
- [ Every docker image can run on any linux system]
- Docker images can run directly on windows
- Dockerfiles are used to deploy images 
- Dockerhub can run apps on docker containers

`@feedback`
<!-- Examples of good feedback messages: https://instructor-support.datacamp.com/en/articles/2299773-exercise-success-messages.  -->
- Perfect! Docker containes are based on the linux kernel so they works on every linux system
- yes it can ! but on a linux virtual machine
- NO ! we create images with dockerfiles
- we push and pull images, Dockerhub is a `conatainer registry`

---

## Basic Docker commands

```yaml
type: MultipleChoiceExercise
key: d60cab3dbe
xp: 50
```

<!-- Guidelines for the question: https://instructor-support.datacamp.com/en/articles/2375523-course-multiple-choice-with-console-exercises. -->

`@possible_answers`
- [Correct answer 1]
- Wrong answer 2
- Wrong answer 3

`@hint`
<!-- Examples of good hints: https://instructor-support.datacamp.com/en/articles/2379164-hints-best-practices. -->
- This is an example hint.
- This is an example hint.

`@pre_exercise_code`
```{python}

```

`@sct`
```{python}
# Check https://instructor-support.datacamp.com/en/articles/2375523-course-multiple-choice-with-console-exercises on how to write feedback messages for this exercise.
```

---

## Insert exercise title here

```yaml
type: TabExercise
key: ef0d667d3d
xp: 100
```

<!-- Guidelines for contexts: https://instructor-support.datacamp.com/en/articles/2375525-course-sequential-exercises. -->

`@pre_exercise_code`
```{python}

```

***

```yaml
type: MultipleChoiceExercise
key: 07da725020
xp: 100
```

`@question`


`@possible_answers`
- [Correct answer 1]
- Wrong answer 2
- Wrong answer 3

`@hint`
<!-- Examples of good hints: https://instructor-support.datacamp.com/en/articles/2379164-hints-best-practices. -->
- This is an example hint.
- This is an example hint.

`@sct`
```{python}
# Check https://instructor-support.datacamp.com/en/articles/2375523-course-multiple-choice-with-console-exercises on how to write feedback messages for this exercise.
```

***

```yaml
type: NormalExercise
key: 8e3601583b
```

`@instructions`
<!-- Guidelines for instructions https://instructor-support.datacamp.com/en/articles/2375526-course-coding-exercises. -->
- Instruction 1
- Instruction 2

`@hint`
<!-- Examples of good hints: https://instructor-support.datacamp.com/en/articles/2379164-hints-best-practices. -->
- This is an example hint.
- This is an example hint.

`@sample_code`
```{shell}

```

`@solution`
```{shell}

```

`@sct`
```{python}
# Examples of good success messages: https://instructor-support.datacamp.com/en/articles/2299773-exercise-success-messages.
```

***

```yaml
type: MultipleChoiceExercise
key: 5a89336f4d
```

`@question`


`@possible_answers`
- [Correct answer 1]
- Wrong answer 2
- Wrong answer 3

`@hint`
<!-- Examples of good hints: https://instructor-support.datacamp.com/en/articles/2379164-hints-best-practices. -->
- This is an example hint.
- This is an example hint.

`@sct`
```{python}
# Check https://instructor-support.datacamp.com/en/articles/2375523-course-multiple-choice-with-console-exercises on how to write feedback messages for this exercise.
```
