# EonGraph
## About this project
This is a project of visualizing graphs and Edit them.
## How to run it 
1. run backend [EonGraph-Backend](https://github.com/ProgramIsFun/EonGraph-Backend) according to readme
2. run  [ue5-force-graph53](https://github.com/ProgramIsFun/ue5-force-graph53)  if you want a game client   or   [EonGraph-Web](https://github.com/ProgramIsFun/EonGraph-Web)   if you want a web client 
## Project structure

It is consist of the following components.

| # | Component                  | Description                                                      | Repository URL                                                   | Notes                                            |
|---|----------------------------|------------------------------------------------------------------|------------------------------------------------------------------|--------------------------------------------------|
| 1 | Issues for Front End (Unreal Engine)   |    Posting issues here for UE related thing            | [ue5-force-graph](https://github.com/ProgramIsFun/ue5-force-graph)      | Used only for issue posting (code not used).     |
| 1 | Front End (Unreal Engine)   | Unreal Engine-based front end for  graph visualization and editing                       | [ue5-force-graph53](https://github.com/ProgramIsFun/ue5-force-graph53)  |                             |
| 2 | Front End (Website)          | Web-based front end for graph visualization and editing                        | [EonGraph-Web](https://github.com/ProgramIsFun/EonGraph-Web)            |  Active development.                                                  |
| 3 | Back End                   | API and logic behind the graph visualizations                    | [EonGraph-Backend](https://github.com/ProgramIsFun/EonGraph-Backend)    |     Active development.                                             |
| 4 | Backup                     | Backup utility for the graph data                                | [EonGraph-BackupHelper](https://github.com/ProgramIsFun/EonGraph-BackupHelper)|                                                  |
| 5 | Useful Scripts       |  for database management, etc     | [EonGraph-UsefulScripts](https://github.com/ProgramIsFun/EonGraph-UsefulScripts)          | Test code before backend integration.            |
| 6 | Schema Management          | Graph schema definitions for backend and other components        | [EonGraph-Schema](https://github.com/ProgramIsFun/EonGraph-Schema)      | Schema shared across the project.                |

## Meaning of this project
1. Just want to have a tool that visualization the connection between things in life. I believe a force directed 3D graph is appropriate. With such connections, I believe it is easier to find something quickly by go through the hops starting from one node to some other node. 
