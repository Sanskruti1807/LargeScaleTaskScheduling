# Large-Scale Task Scheduling

## Problem
Assign a large number of tasks to available cloud resources while satisfying
resource constraints and scheduling objectives.

## Task Attributes
- Task ID
- Execution time
- Priority
- Deadline
- Required capacity

## Resource Attributes
- Resource ID
- Capacity
- Available time

## Constraints
1. A task can only be assigned to a resource with sufficient capacity.
2. A resource cannot execute multiple tasks simultaneously.

## Objectives
1. Minimize deadline violations.
2. Minimize makespan.
3. Improve resource utilization.
4. Reduce load imbalance.

## Algorithms
1. FCFS
2. Priority + Earliest Deadline First
3. Priority + Greedy Resource Allocation

## Parallelization
OpenMP will be used to parallelize suitable independent computations.

## Performance Metrics
- Execution time
- Speedup
- Parallel efficiency
- Makespan
- Deadline violations
- Resource utilization
- Load imbalance

## Input Sizes
- 1,000
- 5,000
- 10,000
- 50,000
- 100,000
- 500,000 tasks

## Thread Counts
- 1
- 2
- 4
- 8