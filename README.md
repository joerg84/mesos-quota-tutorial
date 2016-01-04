# Mesos Quota Tutorial

This tutorial aims to provide an overview on how to use the new feature Quota.

It is hands-on and contains almost everything you: sample framework and scripts controlling them, so you only require a Mesos cluster with at least 2 agent and at least Mesos 0.27.0.

# Frameworks 

Let us start by introducing out participants, i.e. the frameworks sharing our Mesos Cluster

## Dracula
Dracula is a framework which wants to use as many resources as possible, i.e. it consumes every resource offered to it. Wyou should really watch out for this one. Dracula is running the only framework in role `Count`.

## Lucy 
Lucy is a framework not demanding much, it is happy with 2 cpus (but not less). Lucy is (for now) the only framework in role `Victim`.

## John and Mina 
John and Mina are two tighly coupled framework requiring 2 cpus each. As they are tighly coupled they are running both in the same role `Harker`

# Scene 1: Lucy and Dracula

Run script scene_1.sh ....

# Scene 2: Lucy reborn (aka upgrade)





