
# Submission 1484, Review 1
Title: Towards the Measurement of Human-Robot Motion Imitation with Inertial Sensor  
Reviewer:           external

### Summary

   The paper describes a method to compute how well a human is imitating the
   movements of a NAO robot using an inertial sensor. The method succeeds in
   showing differences in the imitation performance of different users,
   which shall be used for giving feedback about the performance level in
   the future.

### Feedback Comments

   The paper covers an interesting and relevant topic. The impact is a
   little difficult to assess in the current state. It has a potential to be
   impactful because the method seems to be successful for very simple
   movements. However, it is not clear if that will actually scale up for
   more difficult movements and if it will be a good basis to suggest
   assessments. As a late breaking report, I think it will be interesting to
   the community anyway.

   Before it can be published, it needs some minor work:
   - In general, the paper needs work on the grammar and coherent writing
   style. For example, the research question is barely understandable due to
   a missing main verb and preposition. Please revise the whole paper
   carefully and pay attention to that.
   - In the introduction, it is not clear where the proposed difference
   between the approach in the paper and the approach by Guneysu et al. is.
   Another clarifying sentence would be helpful.
   - In Section "Participants", you write that you used 12 participants and
   9 of them were male and 2 female. What about the last participant? Did
   that person not provide the information? Clarify.
   - You are writing the sensor was attached to the right arm of both the
   robot and the participant. In the image, however, the robot wears it on
   it's left arm (which also makes more sense in a front to front
   imitation). Please work on the consistence here.
   - It remains unclear why only one axis was taken into account in the
   computations. In Section 2.4 you write it is due to the simplicity of the
   proposed movement, but in Section 3 it is only one movement due to the
   space constraint. Another sentence for clarification in 2.4 would be
   helpful to understand the method.
   - In terms of structure, I would propose to move 2.5 to a separate
   section and rename it so it is obvious that this is very you actually
   present your computation model
   - In the caption of Figure 1, the number for the participant in (F) is
   missing
   - The headline "References" should be in the same column as the first
   reference
   - In general, one sentence that discusses the selection of the inertial
   sensor would be helpful. While it avoids the obstructions using an RGB-D
   sensor, it requires participants to wear a device they are not used to,
   which might not be highly appreciated.


# Submission 1484, Review 2
Title: Towards the Measurement of Human-Robot Motion Imitation with Inertial Sensor
Reviewer:           external

### Summary

   The authors have verified the using of inertial sensors during the
   imitation between human and humanoid robot. For that purpose, inertial
   sensors have been touched to NAO robot and to different participants.
   Simple experiments have been performed on twelve healthy participants.
   Principal Component Analysis (PCA) has been used to reconstruct the state
   space.

### Feedback Comments

   Strengths:
   Promising approach which can help to predict the ability of the humans
   during the rehabilitation. Furthermore, the robot can change its speed,
   path etc. according to the patient's situation.
   Weakness:
   -    The motivation of the current version of the work is unfortunately not
   convincing.
   -    Doubt about the novelty of the work
   -    Some wrong grammar, poor punctuation and many typos
   Overall Evaluation:
   I was expecting that the authors will handle with rehabilitation or they
   will explain the main benefit of their work. Unfortunately, the
   motivation has focused only on the inertial sensors. I think the research
   questions was not that successful: Can the use inertial sensor attached
   both….. ?
   The answer for me way clear of course “yes”. However, the main point
   in my opinion should be: how to use them in optimal way and how to
   analysis the obtained data??
   PCA is used as the default extraction method in the SPSS Factor Analysis
   routines. The authors have ignored to mention other analysis methods. It
   was important to explain why PCA have been here used in comparison with
   other methods.
   The novelty of the current version of the paper with the current version
   of the result was low. Maybe if the authors have performed more complex
   movements with real patients and not with healthy participants.
   Furthermore, there are some general mistakes, e.g.:
   1.   In 2.3: twelve healthy participants (two females and nine males)????
   2.   In 2.4: Inertial sensors were attached to the right hand of the robot
   and the right hand of the participant. However, in the image 1.A, the
   inertial sensors are attached to the left hand of the robot???
   3.   The shortcut PCA have been mentioned without any explanation. It
   should be short written.
   While the presented work is promising, it does not seem to be ready for
   publication due to comments above.
