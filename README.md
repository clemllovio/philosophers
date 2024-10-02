# philosophers
The philosophers project is a simulation of the classic dining philosophers problem, designed to explore and solve synchronization issues in concurrent programming. This project aims to deepen understanding of threads, mutexes, and the challenges of shared resource management in a multi-threaded environment
## Installation
To use this program:
  1. Clone the repository:
     ``` bash
     git clone https://github.com/clemllovio/philosophers.git
     ```
  3. Navigate to the project directory and compile
## Usage
After compiling, you'll have a `philo` executable. Use it as follows:
```bash
./philo number_of_philosophers time_to_die time_to_eat time_to_sleep [number_of_times_each_philosopher_must_eat]
```
Parameters:
  
  • `number_of_philosophers`: The number of philosophers and forks

  • `time_to_die`: Time in milliseconds after which a philosopher dies if they haven't started eating

  • `time_to_eat`: Time in milliseconds it takes for a philosopher to eat

  • `time_to_sleep`: Time in milliseconds a philosopher spends sleeping

  • `number_of_times_each_philosopher_must_eat` (optional): If specified, the simulation stops when all philosophers have eaten this many times

  ## Output
  The program outputs the state changes of philosophers in the following format:
  ```
timestamp_in_ms X has taken a fork
timestamp_in_ms X is eating
timestamp_in_ms X is sleeping
timestamp_in_ms X is thinking
timestamp_in_ms X died
```
Where X is the philosopher number.

## Credits
This project was developed by Clémence Llovio as part of the curriculum at 42 School.
