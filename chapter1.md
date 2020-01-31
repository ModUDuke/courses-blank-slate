---
title: 'Chapter Title Here'
description: 'Chapter description goes here.'
---

## Example coding exercise

```yaml
type: NormalExercise
key: 2bafef99a3
lang: r
xp: 100
skills: 1
```

This is an example exercise. it's great

`@instructions`
1. first thing
2. Second thing
3) third thing

`@hint`
this is a cool hint bro

`@pre_exercise_code`
```{r}
a<-3
```

`@sample_code`
```{r}
# put 3 into a

	a<-3
```

`@solution`
```{r}
a<-3
```

`@sct`
```{r}
a<-3

success_msg("What a great job!")"
```

---

## it's a video

```yaml
type: VideoExercise
key: 1e83a10980
xp: 50
```

`@projector_key`
ba97f59907f1e58e0c76f989f6fcf30a

---

## Insert exercise title here

```yaml
type: PureMultipleChoiceExercise
key: 619086b26d
xp: 50
```

<!-- Guidelines for the question: https://instructor-support.datacamp.com/en/articles/2375516-course-multiple-choice-exercises. -->

This is such an amazing question

`@hint`
<!-- Examples of good hints: https://instructor-support.datacamp.com/en/articles/2379164-hints-best-practices. -->
- This is an example hint.
- This is another example hint.

`@possible_answers`
- [Correct answer 1]
- Wrong answer 2
- Wrong answer 3

`@feedback`
<!-- Examples of good feedback messages: https://instructor-support.datacamp.com/en/articles/2299773-exercise-success-messages.  -->
- Perfect!
- Error message answer 2
- Error message answer 3
