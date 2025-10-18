# EonGraph
## About this project
This is a project of visualizing graphs and Edit them.
## How to run it 
1. run backend [EonGraph-Backend](https://github.com/ProgramIsFun/EonGraph-Backend) according to readme
2. run  [ue5-force-graph53](https://github.com/ProgramIsFun/ue5-force-graph53)  if you want a game client   or   [EonGraph-Web](https://github.com/ProgramIsFun/EonGraph-Web)   if you want a web client 
## project structure

It is consist of the following components.

| # | Component                  | Description                                                      | Repository URL                                                   | Notes                                            |
|---|----------------------------|------------------------------------------------------------------|------------------------------------------------------------------|--------------------------------------------------|
| 1 | Unreal Engine Front End    | Visualizing/editing graphs in UE5, not maintained                | [ue5-force-graph](https://github.com/ProgramIsFun/ue5-force-graph)      | Used only for issue posting (code not used).     |
| 1 | Unreal Engine Main Repo    | Main Unreal Engine project                                       | [ue5-force-graph53](https://github.com/ProgramIsFun/ue5-force-graph53)  |                             |
| 2 | Website Front End          | Web-based graph visualization and editing                        | [EonGraph-Web](https://github.com/ProgramIsFun/EonGraph-Web)            |  Active development.                                                  |
| 3 | Back End                   | API and logic behind the graph visualizations                    | [EonGraph-Backend](https://github.com/ProgramIsFun/EonGraph-Backend)    |     Active development.                                             |
| 4 | Backup                     | Backup utility for the graph data                                | [EonGraph-BackupHelper](https://github.com/ProgramIsFun/EonGraph-BackupHelper)|                                                  |
| 5 | Database Management        | no longer used, for database management and backend code testing     | [EonGraph-DatabaseManager](https://github.com/ProgramIsFun/EonGraph-DatabaseManager)          | Test code before backend integration.            |
| 6 | Schema Management          | Graph schema definitions for backend and other components        | [EonGraph-Schema](https://github.com/ProgramIsFun/EonGraph-Schema)      | Schema shared across the project.                |

