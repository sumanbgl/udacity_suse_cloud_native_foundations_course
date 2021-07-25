**Day 1 : 7th July 2021**
Yesterday: Re did the exercise Docker for Application Packaging (concept 7) from lesson 3.
Today: Plan to revise concepts 9-11 in lesson 3.
Blockers: No blockers so far.

**Day 2 : 8th July 2021**
Yesterday: Revised the concepts 9-11 in lesson 3.
Today: Redo concept 14 (exercise : deploy first k8s cluster) from lesson 3.
Blockers: No blockers so far.


**Day 3 : 9th July 2021**
Yesterday: Started redoing the concept 14 (exercise: deploy first k8s cluster) from lesson 3.
Today: Plan to explore the important options of kubectl to know the cluster state.
Blockers: No blockers so far.

**Day 4 : 10th July 2021**
Yesterday: Revised the 1-node cluster provisioning using k3s (concept 14 exercise) from lesson 3.
Today: Presented the webinar on Introduction to Docker along with co-speakers. Attended webinar on gardener. Plan to revise concept 16 from lesson 3.
Blockers: No blockers so far.

**Day 5: 11th July 2021**
Yesterday: Revised the concept 16 from lesson 3.
Today: Plan to revise concept 17 from lesson 3.
Blockers: No blockers so far.

**Day 6: 12th July 2021**
Yesterday: Could not work on Cloud native foundations content.
Today: Plan to revise concept 17 from lesson 3.
Blockers: No blockers so far.

**Day 7: 13th July 2021**
Yesterday: Revised concept 17 from lesson 3.
Today: Plan to revise concept 18 from lesson 3.
Blockers: No blockers so far.

**Day 8: 14th July 2021**
Yesterday: Revised concept 17,18 from lesson 3.
Today: Plan to redo concept 21 (Exercise: Kubernetes Resources) from lesson 3.
Blockers: No blockers so far.

```
Exercise: Kubernetes Resources
kubectl create namespace demo
kubectl get ns
kubectl label ns demo tier=test
kubectl describe ns demo

kubectl create deploy nginx-alpine --image=nginx:alpine -n demo -r 3
kubectl get deploy -n demo
kubectl describe -n demo deploy nginx-alpine
kubectl label deploy nginx-alpine app=nginx tag=alpine --namespace demo

kubectl expose deploy nginx-alpine --port 8111 -n demo

kubectl create configmap -n demo nginx-version --from-literal=version=alpine
kubectl describe cm -n demo nginx-version

```

**Day 9: 15th July 2021**
Yesterday: Redid concept 21 (Excercise: Kubernetes Resources) from lesson 3.
Today: Plan to revise concepts 23-28 from lesson 3.
Blockers: No blockers so far.

**Day 10: 16th July 2021**
Yesterday: Revised concepts 23-28 from lesson 3 and completed revision of lesson 3.
Today: Submitted my student story, wrote a blog for Blogathon event and completed Weekly Quiz # 4. Plan to start revision of lesson 5 concepts till CI fundamentals.
Blockers: No blockers so far.

**Day 11: 18th July 2021**
Yesterday: Took a day off due to sickness.
Today: Hosted 3 technical quizzes on docker, kubernetes, helm, argocd as part of study jam. Participated in CI/CD Quiz , Cloud Fundamentals Quiz, Fun Quiz on Docker, Kubernetes, Git, Crosswork Puzzle Quizzes and webinars on L3 - Container Orchestration, Intro to MLOps.
Blockers: No blocker so far.

**Day 12: 19th July 2021**
Yesterday: Study Jam day. Hosted 3 technical quizzes on docker, kubernetes, helm, argocd as part of study jam. Participated in CI/CD Quiz , Cloud Fundamentals Quiz, Fun Quiz on Docker, Kubernetes, Git, Crosswork Puzzle Quizzes and webinars on L3 - Container Orchestration, Intro to MLOps.
Today: Plan to revise CI concepts from Lesson 5.
Blockers: No blocker so far.

Identified following articles for further reading:
 https://rubygarage.org/blog/advantages-of-using-docker-for-microservices
 https://itnext.io/kubernetes-essential-tools-2021-def12e84c572

**Day 13: 20th July 2021**
Yesterday: Revised CI Concepts from Lesson 5.
Today: Plan to revise CD concepts from lesson 5.
Blockers: No blockers so far.

**Day 14: 21st July 2021**
Yesterday: Revised CD Concepts from Lesson 5.
Today: Plan to work on CD Exercise from lesson 5.
Blockers: No blockers so far.

**Day 15: 22nd July 2021**
Yesterday: Worked on CD Excercise from lesson 5.
Today: Attended SUSE Community AMA session. Plan to revise the configuration managers concepts from lesson 5.
Blockers: No blockers so far.

**Day 16: 24th July 2021**
Yesterday: Revised the procedure for CI, CD Excercise from lesson 5.
Today: Plan to revise Helm concepts from lesson 5. Watching https://www.youtube.com/watch?v=ks7tVTxH8FM to learn kubernetes operator concepts.
Blockers: No blockers so far.

**Day 17: 25th July 2021**
Yesterday: Started with revision of Helm concepts from lesson 5.
Today: Plan to complete revision of Helm concepts from lesson 5. Debug and fix the container error in my k3s cluster.
Blockers: None so far.


