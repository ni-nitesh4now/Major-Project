
This project develops metaheuristic load balancing algorithms using Cloud Analyst, an extension of CloudSim. The aim is to identify effective load balancing algorithms based on data center response time and service processing metrics. The approach involves developing advanced load balancing algorithms using Swarm Intelligence and comparing them through simulations.

## Ant Colony Optimization (ACO)

ACO mimics ant foraging behavior by depositing pheromone trails on paths, influencing path selection probabilities. 

### Steps Used

1. **Initialization:** Initialize pheromone levels on paths.
2. **Ant’s Movement:** Ants choose paths based on pheromone levels.
3. **Update Pheromones:** Update pheromone levels based on ant trails.
4. **Evaporation:** Evaporate pheromone levels to prevent stagnation.
5. **Termination:** Check if termination condition is met.

## Honeybee Optimization

Honeybee Optimization mimics honeybee foraging behavior, with employed bees exploiting food sources and scout bees exploring new sources.

### Steps Used

1. **Initialization:** Initialize scout and employed bees.
2. **Exploitation:** Employed bees exploit food sources.
3. **Communication:** Onlooker bees choose sources based on employed bees' information.
4. **Update Employed Bees:** Employed bees update based on onlooker bees' choices.
5. **Exploration:** Scout bees search for new sources.
6. **Termination:** Check if termination condition is met.

## Round Robin Algorithm

Round Robin assigns tasks to resources in a circular order.

### Steps Used

1. **Initialization:** Prepare resource list and task queue.
2. **Task Assignment:** Assign tasks to resources in order.
3. **Task Execution:** Execute tasks for a fixed time.
4. **Task Management:** Move unfinished tasks to end of queue.
5. **Resource Rotation:** Move to next resource and repeat.
6. **Completion:** Continue until all tasks are completed.

## Simulation

1. **Launch CloudAnalyst:** Start CloudAnalyst.
2. **Configure Data Centre:** Define data center characteristics.
3. **Define User Base:** Specify user characteristics.
4. **Configure Deployment:** Define application deployment.
5. **Select Load Balancing:** Choose algorithms.
6. **Run Simulation:** Start simulation.
7. **Monitor Progress:** Monitor in real-time.
8. **Analyze Results:** Evaluate simulation outcomes.
9. **Optimize Parameters:** Refine parameters if necessary.
10. **Generate Reports:** Generate comprehensive reports.
