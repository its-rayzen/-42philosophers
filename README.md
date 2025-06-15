# Philosophers

This is a project from the 42 curriculum that explores multithreading and concurrency through the classic Dining Philosophers Problem.

## Description

The goal is to simulate a group of philosophers sitting at a table. Each philosopher alternates between thinking, eating, and sleeping. They must share forks (resources) without causing deadlocks or race conditions. The simulation must follow precise timing rules and avoid undefined behavior.

## Concepts Covered

- Thread creation and management (pthread)
- Mutexes for shared resource protection
- Deadlock avoidance
- Race condition handling
- Timing and precise control of concurrent behavior
- Process management (bonus version)

## Project Structure

- `philo/` - Mandatory version using threads and mutexes
- `philo_bonus/` - Bonus version using processes and semaphores

## Notes

This project is inspired by Edsger Dijkstra's Dining Philosophers Problem, designed to teach synchronization techniques in concurrent programming.
