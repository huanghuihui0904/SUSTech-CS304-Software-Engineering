## LECTURE 1-overview
### SE Overview
#### Software Crisis
• Software crisis is a term used in the early days of computing science for the difficulty of writing useful and efficient computer programs in the required time
• The causes of the software crisis were linked to the overall complexity of hardware and the software development process.
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685606819682-63c4435e-e7df-4449-9cc4-a161605bcc19.png#averageHue=%23f7f5f4&clientId=u973e3004-afac-4&from=paste&height=164&id=u9cef126d&originHeight=256&originWidth=1212&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=56771&status=done&style=none&taskId=ucdcda200-ac6b-4a63-9c4a-7004b95de90&title=&width=775.68)
#### What is software engineering?
• Software: a program or set of programs containing instructions that provide desired functionality. 
• Engineering: the process of designing and building something that serves a particular purpose and finds a cost-effective solution to problems.
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685607014271-ac4de174-c416-4d01-b1bb-480d26a83c6f.png#averageHue=%23fcfaf9&clientId=u973e3004-afac-4&from=paste&height=216&id=u2eef160c&originHeight=338&originWidth=1172&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=43202&status=done&style=none&taskId=u3b3347b0-0d1a-451c-a8ae-1896dca0348&title=&width=750.08)
#### Software Engineering Vs. Programming
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685607090950-8f629349-c615-45cf-ac84-ff23b200d4a5.png#averageHue=%23f6f4f1&clientId=u973e3004-afac-4&from=paste&height=97&id=u000ff55a&originHeight=152&originWidth=1034&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=33089&status=done&style=none&taskId=u07cf0c50-465e-413d-bd34-7aa6ca8f05b&title=&width=661.76)
LIFE SPAN, RESOURCES, COMPLEXITY
programing：ddl前完成，对就好
se：长周期，要不断完善，考虑很多比如质量、开销、社会影响
### Time & Change
#### Hyrum' s law
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685607631508-3afcb530-1a40-49fe-8d2f-442eca5a7501.png#averageHue=%23f8f6f2&clientId=u973e3004-afac-4&from=paste&height=204&id=u0c843765&originHeight=319&originWidth=614&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=51569&status=done&style=none&taskId=u7acda252-dd47-4555-82cc-a19f0a1b258&title=&width=392.96)
### Scale & Efficiency
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685610393698-22727a88-6dd9-4725-bbf3-23a9ec6ad393.png#averageHue=%23f6f3f2&clientId=u973e3004-afac-4&from=paste&height=158&id=u120e382e&originHeight=247&originWidth=623&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=35052&status=done&style=none&taskId=u303290e7-1d02-4869-a692-5ecab1a33c2&title=&width=398.72)
### Trade-offs & Costs
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685610684228-0253c0f5-8470-4d06-98d2-768901196f7c.png#averageHue=%23f3f3f2&clientId=u973e3004-afac-4&from=paste&height=415&id=u5b7cd059&originHeight=649&originWidth=1028&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=116526&status=done&style=none&taskId=u438554fc-448b-4aa1-847b-a227d313427&title=&width=657.92)
## LECTURE 2-process
### Software Process Overview
#### Why software process?
• Writing code is easy
• Engineering good software system is HARD
• Organizations want a well-defined, well-understood, repeatable software development process
• Benefits
#### What is software process?
##### Activities
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685611132852-bf91c30a-06cf-429c-a0a1-528463365739.png#averageHue=%23f9f8f7&clientId=u973e3004-afac-4&from=paste&height=338&id=ucc000358&originHeight=528&originWidth=1273&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=113735&status=done&style=none&taskId=ue0e32363-c8b4-423f-863d-8a378a8cb22&title=&width=814.72)
• Plan-driven processes: processes where all of the process activities are planned in advance and progress is measured against this plan. 
• Agile processes: planning is incremental and it is easier to change the process to reflect changing customer requirements.
##### Products
the outcomes of a process activity.
##### Roles
Examples of roles are project manager, configuration manager, programmers, 
customers etc.
##### Pre- and post-conditions
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685611473214-eb1eebaa-c2e0-40d4-a512-2dc8fe9c434a.png#averageHue=%23f4f0eb&clientId=u973e3004-afac-4&from=paste&height=161&id=u48dd9f6c&originHeight=251&originWidth=1158&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=62530&status=done&style=none&taskId=ucf86093b-a0d9-4b7a-8057-129bbb82f4a&title=&width=741.12)
### Process Models
cons
Process models forget the frailties of the people who build computer software
Process models often deal with people’s common weaknesses with discipline (对于人类，高纪律的方法是错误的)
#### Waterfall Model
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685613136879-faf424f9-b1a0-4847-99a1-7aab888c4ea7.png#averageHue=%23f4efcc&clientId=u973e3004-afac-4&from=paste&height=243&id=ue95f7f32&originHeight=379&originWidth=1217&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=91899&status=done&style=none&taskId=u4b7f15dc-b420-4e8a-838f-53fe3fb69eb&title=&width=778.88)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685613950882-90f9fcd6-b235-4116-a0d7-5bd121444a38.png#averageHue=%23f2f1ef&clientId=u973e3004-afac-4&from=paste&height=416&id=ub59ff82e&originHeight=650&originWidth=1037&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=107274&status=done&style=none&taskId=u9ae5ac79-a475-4fe4-b8f1-9cafc703c64&title=&width=663.68)

#### Incremental Process Models
pros
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685614283504-6ea8c712-c936-4aa1-acf8-fb5406b4b0aa.png#averageHue=%23faf8f7&clientId=u973e3004-afac-4&from=paste&height=291&id=u0adbf165&originHeight=455&originWidth=1390&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=134001&status=done&style=none&taskId=udcd7cd8d-db6b-4489-8124-b3fee0b3c2c&title=&width=889.6)
cons
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685614345588-faf4a8f6-0d25-4e75-afc6-1f5b9c29684d.png#averageHue=%23f8f5f1&clientId=u973e3004-afac-4&from=paste&height=234&id=u9a58209a&originHeight=365&originWidth=561&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=51604&status=done&style=none&taskId=ufafc4a09-b78c-49a4-8964-04c64c7be6b&title=&width=359.04)

#### Evolutionary Process Models
##### prototyping model
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685619553762-47d4a3b4-452c-4bfd-84b9-76ddd6ef4ee2.png#averageHue=%23f8f6f5&clientId=u973e3004-afac-4&from=paste&height=307&id=u396d78d2&originHeight=479&originWidth=1300&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=148484&status=done&style=none&taskId=u967eb765-6bdb-42db-aae0-654f61971d0&title=&width=832)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685619472551-75a6558d-e4c5-4a07-b559-62e1af6ac3c8.png#averageHue=%23fdf9f7&clientId=u973e3004-afac-4&from=paste&height=88&id=ud72a9ecf&originHeight=137&originWidth=771&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=37583&status=done&style=none&taskId=u7364516a-750c-428d-ae76-e5bd8b9167a&title=&width=493.44)

##### spiral model
The spiral model couples the iterative nature of prototyping with the controlled and systematic aspects of the waterfall
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685620131645-e584e7a6-8881-4452-a9a6-e6414364f68e.png#averageHue=%23dbc9b3&clientId=u973e3004-afac-4&from=paste&height=266&id=uca6b199b&originHeight=416&originWidth=611&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=94594&status=done&style=none&taskId=u1e51fab8-ee6c-4648-aa0b-463a6454d79&title=&width=391.04)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685620149759-ba6a487d-0b1e-40a1-b0b9-4096681040b4.png#averageHue=%23f3efed&clientId=u973e3004-afac-4&from=paste&height=143&id=u789469d4&originHeight=223&originWidth=662&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=41510&status=done&style=none&taskId=ub5cb5494-72f1-42dd-9232-dc6e19d71c5&title=&width=423.68)
### Agile Development
agile适合开发团队，而不是运营团队(operations team)
#### Extreme Programming
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685621635893-76f10f7c-5478-41d5-9a66-95701bfb260e.png#averageHue=%23f5f2f0&clientId=u973e3004-afac-4&from=paste&height=143&id=u185721d2&originHeight=223&originWidth=1145&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=43159&status=done&style=none&taskId=ufc6fa0de-2718-4f6e-8e03-f708326402e&title=&width=732.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685621715016-4e9fa5ec-061a-4376-9226-e212b915173c.png#averageHue=%23ccb59f&clientId=u973e3004-afac-4&from=paste&height=316&id=u881b828f&originHeight=494&originWidth=656&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=111589&status=done&style=none&taskId=u1d89edd4-16b4-40a2-af7f-e1193b5f7f7&title=&width=419.84)
##### Planning
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685621778469-5f7216ae-41e6-40c0-96b5-e5e7ab35b6dd.png#averageHue=%23f4f1ee&clientId=u973e3004-afac-4&from=paste&height=129&id=u55f4a8bc&originHeight=202&originWidth=657&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=36172&status=done&style=none&taskId=u5954af2f-b2c4-435b-b837-10e92ccaf1c&title=&width=420.48)
##### Design
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685621800068-3c76ef52-1fab-4d15-9d8c-30d657acb2e5.png#averageHue=%23f0efee&clientId=u973e3004-afac-4&from=paste&height=303&id=ud8dfce1e&originHeight=473&originWidth=1398&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=206063&status=done&style=none&taskId=ud1d50c14-5b93-4046-be14-87b53772c73&title=&width=894.72)
##### Coding
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685621922093-423103e1-7df7-43be-8198-aebb1f4e5f02.png#averageHue=%23f5f2ee&clientId=u973e3004-afac-4&from=paste&height=242&id=u4d04a42e&originHeight=378&originWidth=652&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=66279&status=done&style=none&taskId=u47c81d76-a545-435a-8580-1e2cc261cdb&title=&width=417.28)
##### Testing
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685622043303-773bdbd2-4a2f-41df-8efb-f14e36bb2696.png#averageHue=%23f6f3ef&clientId=u973e3004-afac-4&from=paste&height=201&id=uc07faa04&originHeight=314&originWidth=689&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=52309&status=done&style=none&taskId=uf30c0730-877e-4a4c-a5af-919af6e79d9&title=&width=440.96)
#### SCRUM
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685623929936-616c6116-72be-4559-9e56-f13459afe619.png#averageHue=%23f5f4f3&clientId=u973e3004-afac-4&from=paste&height=358&id=u1a8adda9&originHeight=560&originWidth=996&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=59877&status=done&style=none&taskId=u366df27a-acda-46e7-9496-0bd99a53400&title=&width=637.44)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685622780159-e97f5405-645e-4dc0-8408-292a32b3e6fe.png#averageHue=%23ef9c52&clientId=u973e3004-afac-4&from=paste&height=314&id=uee7a429b&originHeight=491&originWidth=1068&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=66943&status=done&style=none&taskId=u387c124e-915b-426c-81f4-11e64ebdefe&title=&width=683.52)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685622810799-667609c0-4336-45ae-9a9d-d34ed71c5e06.png#averageHue=%23f0f0ec&clientId=u973e3004-afac-4&from=paste&height=387&id=ucb0d8524&originHeight=604&originWidth=1300&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=416972&status=done&style=none&taskId=uad04cc2c-3f48-4146-89fd-1ab004e0270&title=&width=832)
##### Product Backlog (product owner)
一个有优先级和重要程度的todolist
Product backlog is similar to requirements in classic software process model. 
However, product backlog is **prioritized and dynamic**, i.e., adapt to constant changes and refinements.
##### Sprint Planning Meeting & Sprint Bakclog (product owner & team)
Sprint (冲刺):Scrum项目管理方法中的一个常规、可重复的较短工作周期。在这个周期里，项目团队需快速完成预定的工作量（i.e., sprint backlog）
##### Sprint
A sprint duration is determined by the **Scrum Master**, typically lasts 30 days.
###### SCRUM Boards
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685623197443-61cb9705-3e27-4cb2-8637-3c18ee393db0.png#averageHue=%23f5f0e1&clientId=u973e3004-afac-4&from=paste&height=258&id=u13ea8597&originHeight=403&originWidth=861&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=113270&status=done&style=none&taskId=u5746a395-93c9-49bb-82cb-2c0cb05f146&title=&width=551.04)
###### Burndown Charts
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685623263753-ff240ca8-1c7c-4cb6-b3f3-e64a46ff369f.png#averageHue=%23f8f7f7&clientId=u973e3004-afac-4&from=paste&height=239&id=uc3fa8f37&originHeight=373&originWidth=902&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=63564&status=done&style=none&taskId=u2e4aa5e6-9527-4c92-8fc5-8bc0cd0d7c6&title=&width=577.28)
##### Daily Scrum (例会)
##### Sprint Review评审 (team presents to stakeholders) & Sprint Retrospective回顾 (all)
#### KANBAN
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685624702973-14fd6515-3722-4b92-8488-f2588c474ab6.png#averageHue=%23ecebea&clientId=u973e3004-afac-4&from=paste&height=220&id=u1d6df339&originHeight=344&originWidth=1372&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=150768&status=done&style=none&taskId=ud5dc3136-f687-43d1-a722-eed8e08be74&title=&width=878.08)
#### SCRUM VS. KANBAN
|  | Scrum | kanban |
| --- | --- | --- |
| ##### FLOW
 | has sprints. | no required time boxes or iterations. 只关心持续完成任务 |
| ##### ROLES
 | has a set of mendatory roles. | no set of roles, maybe an agile coach. |
| ##### COMMITMENT承诺
 | 每个sprint都保证固定数量的任务，如果保证太多会sprint失败 | 基于WIP限制，防止同一时间做太多任务 |
| ##### PLANNING
 | 在每个sprint之前都有计划 | 没有计划 just-in-time palnning |
| ##### WORKLOAD
 | 完成每个sprint要求的任务数量 | 限制同一时间正在做的任务数量 |
| ##### CHANGES
 | sprint开始之后就不能新加任务了 | 可以持续新增以及减少任务 |
| ##### KPI
 | 使用burndown chart和velocity chart，关心一个story完成的速度 | 关心lead time和cycle time，计算的是平均一个任务从开始到完成的时间 |
| ##### BOARD
 |  | 有WIP limits |
| **APPLICATION** | 适合快速开发，固定任务，需要协调，不成熟的队伍 | 适合对任务会不断地改变，成熟的队伍 |

### DevOps
DevOps integrates developers and operations teams to improve collaboration and productivity by
• Automating infrastructure
• Automating workflows
• Continuously measuring application performance
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685630270292-b625a96d-610b-440c-adb9-61c510008433.png#averageHue=%23f2efea&clientId=u973e3004-afac-4&from=paste&height=474&id=u36d716e9&originHeight=741&originWidth=1412&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=299398&status=done&style=none&taskId=u5d0f7bda-347b-4ccc-8153-bf3db9e25c6&title=&width=903.68)

## LECTURE 3-vcs
### Version Control
#### Local vcs- RCS
只在本地，不能和别人共享
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685687394118-4201ee24-5324-4c25-95dd-72ff50d328f9.png#averageHue=%23e4e4e4&clientId=u47d3c7f1-65b6-4&from=paste&height=282&id=u270af5bc&originHeight=441&originWidth=525&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=33397&status=done&style=none&taskId=ua9c45c56-6121-471c-90b8-04c6286893d&title=&width=336)
#### Centralized vcs- CVS, Subversion, and Perforce
单点问题，服务器毁了就都没了
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685687572170-cd88777a-f4c5-4575-a53f-e8c46fab66c2.png#averageHue=%23e6e5e5&clientId=u47d3c7f1-65b6-4&from=paste&height=305&id=u06597970&originHeight=477&originWidth=671&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=93123&status=done&style=none&taskId=ub9383056-7d66-450c-bedf-bc86414a3b2&title=&width=429.44)
#### Distributed vcs-Git, Mercurial, Bazaar or Darcs
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685687676445-906daad6-0a63-4a12-9adb-535c17ab911d.png#averageHue=%23f2f2f0&clientId=u47d3c7f1-65b6-4&from=paste&height=372&id=ub937a241&originHeight=581&originWidth=497&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=59235&status=done&style=none&taskId=u29035991-52bc-43b0-9b86-4fbf00b20c8&title=&width=318.08)
### Git
#### Snapshots, Not Differences
others: delta-based version control: store information as a list of file-based changes
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685691594078-de6b7770-2088-4080-91d1-ac0d4240e642.png#averageHue=%23f0ebd7&clientId=u47d3c7f1-65b6-4&from=paste&height=205&id=ucebaf60f&originHeight=320&originWidth=820&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=108518&status=done&style=none&taskId=u893257b4-ec1b-4928-88f6-659d0dac66e&title=&width=524.8)
git:  store a series of snapshots of a miniature filesystem, takes a picture of what all your files look like at that moment and stores a **reference** to that snapshot.
#### Nearly Every Operation Is Local
#### Git Has Integrity
The mechanism that Git uses for this checksumming is called a SHA-1 hash.
#### Git Generally Only Adds Data
It is hard to get the system to erase data in any way.
### Git Architecture
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685692770694-c4272d3b-f425-4e62-b6f6-57e5ca66f136.png#averageHue=%23eae8e6&clientId=u47d3c7f1-65b6-4&from=paste&height=346&id=u61492a1e&originHeight=541&originWidth=650&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=54680&status=done&style=none&taskId=ua30e698a-3a22-42b3-8fd8-8cf79a03c75&title=&width=416)
pull=fetch + merge/rebase
#### Git Local Repo
##### 3 Stages
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685692866385-0fcbb4fd-e749-4405-abfd-3c7191054d1c.png#averageHue=%23f4f4f4&clientId=u47d3c7f1-65b6-4&from=paste&height=289&id=u21ba0cef&originHeight=451&originWidth=654&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=35270&status=done&style=none&taskId=u09247a0b-503b-4bc4-a96e-a000a059a12&title=&width=418.56)

| **Untracked** | Git is aware the file exists, but still hasn't saved it in its internal database. |
| --- | --- |
| **Staged** | marked a modified file in its current version to go into your next commit snapshot. |
| **Committed** | the data is safely stored in your local database |
| **Modified** | changed the file but have not committed it to your database yet. |

##### 3 Sections
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685693512622-2ce2cf31-ed89-4d97-a4b8-2fb9abc1ebdc.png#averageHue=%23e9e1dc&clientId=u47d3c7f1-65b6-4&from=paste&height=264&id=u15799699&originHeight=413&originWidth=726&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=91693&status=done&style=none&taskId=u31a830a1-9b06-45c0-b227-43a22cf62f4&title=&width=464.64)
Working tree: a single checkout of one version of the **project**.
Staging area (index): a file in your Git directory, that stores information about what will go into your next commit.
Git directory (repository): where Git stores the metadata and object database for your project.
##### Workflow
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685693634570-7da98e6c-34f9-4e58-a85f-4da16a6a0b28.png#averageHue=%23ede8e4&clientId=u47d3c7f1-65b6-4&from=paste&height=260&id=u5ae738ed&originHeight=407&originWidth=662&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=65712&status=done&style=none&taskId=uc7c83bd6-d0c0-468c-b2af-8a575c95007&title=&width=423.68)
modified file in working directory--git add-->staged file in staging area--git commit-->commited file in repository
##### Working With Remote Repo
Push works only if you cloned from a server to which you have **write access** and if nobody has pushed in the **meantime**.
#### Git Internals
key-value data store, persistent
Key: hash
Value: a sequence of bytes representing files, directories, commits, etc.
##### Objects
content of files, directories, commits, and tags, identified by SHA-1 hash, stored in .git/objects/

| **Blob** | file content, identified by a hash |
| --- | --- |
| **Tree object** | list of pointers to blob (file), or tree (directory), identified by a hash |
| **Commit object** | Reference to the top-level tree for the snapshot of the project at that point 
Parent commits if any
Author info, commit message, etc. |
| **Tag object** | name associated with a commit (+ potential metadata) |

![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685695161784-c6eb52c1-0137-4611-bf6f-029b403bb34e.png#averageHue=%23faf8f7&clientId=u47d3c7f1-65b6-4&from=paste&height=382&id=ucc041902&originHeight=597&originWidth=1135&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=149354&status=done&style=none&taskId=u9e673c4b-2214-4fa8-800f-568c172de30&title=&width=726.4)
##### References/branch
A branch, remote branch or a tag, which is simply a **pointer** to an object, stored in plain text in .git/refs/
**Fast-forward merge**
举例来说，当我们从 master checkout feature 分支进行开发，如果之后 master 都没有新的改动，那么当我们的 feature 分支和入 master 的时候，git 就会使用 fast forward 的方式进行
**3-way Merge**
举例来说，当我们从 master checkout feature 分支进行开发，如果之后 master 都没有新的改动，那么当我们的 feature 分支和入 master 的时候，git 就会使用 fast forward 的方式进行
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685699249354-2b5f5259-474c-4f5c-93da-2d59dd84b7d6.png#averageHue=%23f7f1ec&clientId=u47d3c7f1-65b6-4&from=paste&height=214&id=uaf0c5d08&originHeight=334&originWidth=1027&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=95914&status=done&style=none&taskId=u9fe714bf-0069-42aa-8386-245a193a31a&title=&width=657.28)
Git creates a new snapshot that results from this 3-way merge and automatically creates a new commit that points to it. 
This is referred to as a merge commit, and is special in that it has more than one parent.
**MERGING VS. REBASING**
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685705420538-d3c8cfdc-0d22-428d-a3ff-3ee9ee43bcd9.png#averageHue=%23faf9f9&clientId=u47d3c7f1-65b6-4&from=paste&height=305&id=u1050bde4&originHeight=476&originWidth=1260&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=69666&status=done&style=none&taskId=ue4a689a1-4327-4823-86c7-50a3dd4f74f&title=&width=806.4)
**GIT CLONE VS. FORK**
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685705589253-f9eb59d9-dd98-40ee-9073-8dfecb5cec6f.png#averageHue=%23fcfbfa&clientId=u47d3c7f1-65b6-4&from=paste&height=313&id=u24699b90&originHeight=489&originWidth=1327&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=99205&status=done&style=none&taskId=u2446579e-c304-45dd-bbae-742d6c9685d&title=&width=849.28)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685705670091-76abfa5e-f360-4b46-9d5f-eacf7b9c18b5.png#averageHue=%23f0efef&clientId=u47d3c7f1-65b6-4&from=paste&height=342&id=ufa338287&originHeight=534&originWidth=1280&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=249088&status=done&style=none&taskId=u11785e82-c861-47f7-a9d1-646dbee67e3&title=&width=819.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1685705649030-49baa5c4-b141-4a2a-bc06-6cdfed1c6b5f.png#averageHue=%23eeeae5&clientId=u47d3c7f1-65b6-4&from=paste&height=366&id=uc554dc88&originHeight=572&originWidth=687&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=252784&status=done&style=none&taskId=uc2cd7f3b-d933-4632-851c-a80f09c5331&title=&width=439.68)
##### Index
是一个二进制文件，其他都是文件夹
a **staging area**, stored as a **binary file** in .git/index
#### Git Best Practices
Make clean, single-purpose commits
Commit early, commit often
Write meaningful commit messages
Don't commit generated files or dependencies
## LECTURE 4-requirements
### Requirements Overview
The requirements establish the system's **functionality**, **constraints**, and **goals**.
Severe deficiencies in software requirements
• Incomplete requirements
• Incorrect requirements
• Ambiguous requirements
• Inconsistent requirements
### Stakeholders（涉众）
#### Primary Stakeholders
Customers
Project Managers
Business Analysts
Developers (belong to development team)
QA engineers (belong to development team)
UI&UX designers
#### Secondary Stakeholders
End-users
Government
Competitors
Media
Consultants
Other IT employees
### Types of requirements
#### Software Requirements
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686035094651-2a8d4ca6-f33f-4a98-a74f-a405b74a8f19.png#averageHue=%23f7d4d4&clientId=u0cf5358a-37d6-4&from=paste&height=182&id=uf76d07df&originHeight=284&originWidth=504&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=23897&status=done&style=none&taskId=u1562c163-a68e-4311-baf2-6d4d73105dd&title=&width=322.56)
Business View: define the **WHY** behind a software project.
User View:  describe the **WHO** of a software project.
System View: dive into the **HOW** of a software project. (describe software as functional modules and non-functional attributes.)
#### Functional Requirements
in the form of **input** to be given to the system, the **operation** performed and the **output** expected.
stated by the **user** which one can see **directly** in the final product.
#### Non-Functional Requirements
specify the software's **quality** attribute.
define the general characteristics, behavior of the system, and features that affect the experience of the user
like: performance, reliability, security, usability, 产品约束, 过程约束
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686036031687-ff1843f1-9df7-4a59-821e-502948be4335.png#averageHue=%23f5f5f4&clientId=u59116cd0-5d32-4&from=paste&height=262&id=u2d829c11&originHeight=410&originWidth=920&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=99961&status=done&style=none&taskId=u18b9a245-99d9-49e0-9ae5-eb6ec1f7f2e&title=&width=588.8)
#### Decompose Tasks
**User requirements**, as visions (愿景), need to be iteratively decomposed (分解) and refined (精化), until achieving detailed and actionable **system requirements**
**AND relation** between subtasks: the task is satisfied only if all subtasks are satisfied
**OR relation** between subtasks: the task is satisfied if any one of the subtasks is satisfied
### Requirements Modeling
##### Unified Modeling Language (UML)
In UML, a model consists of a **diagram** and a **specification**
particularly suited to **object-oriented** program development
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686037210800-08315593-8de3-47b4-9e2c-b6e52ee4a7f7.png#averageHue=%23f4f4f4&clientId=ueedd8867-d253-4&from=paste&height=211&id=pjhi3&originHeight=329&originWidth=635&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=55719&status=done&style=none&taskId=u21b19f7a-c69c-4178-a9d0-a3c369ba98b&title=&width=406.4)
#### Scenario-based models
Scenarios capture the system, as viewed from the **outside** (e.g., by a user), using specific examples
Developing a scenario with a **client clarifies** many **functional requirements** that must be agreed before a system can be built
**Murphy' s Law**: “If anything can go wrong, it will”
##### Modeling scenarios as uses cases
###### Use Case Diagram(用例图)- behavior diagrams
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686037898368-006658ac-5cba-4f3b-a4df-2faf9553e4d8.png#averageHue=%23f4f4f4&clientId=ueedd8867-d253-4&from=paste&height=241&id=vD7FX&originHeight=377&originWidth=526&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=121043&status=done&style=none&taskId=u0b36b621-8462-4459-b076-0f49a3ac745&title=&width=336.64)
Use cases
Actors
An actor can be human or an **external system**
Associations
<<extends>>: alternate flow or an exception
<<includes>>
generalize: one thing is more typical than the other thing
extension point
System boundary boxes
optional
###### Natural language template
When a use case involves a **critical activity** or describes a **complex set of steps** with a significant number of **exceptions**, a more formal approach may be desirable.
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686038307758-c9db8486-a9d5-4525-899b-6844ac27bc8b.png#averageHue=%23fbfaf8&clientId=ueedd8867-d253-4&from=paste&height=185&id=ue1251a33&originHeight=289&originWidth=695&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=53175&status=done&style=none&taskId=u3bdab55c-aba6-4ffc-b305-cabeee304db&title=&width=444.8)
##### Interactions Between Use Cases
###### Activity Diagram(活动图)- behavior diagrams
describes the **business** and **operational step-by-step** activities of the components in a system.
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686039542613-06b440e9-201f-4f68-9b6e-74a95b4bc40f.png#averageHue=%23fbf9f8&clientId=ueedd8867-d253-4&from=paste&height=305&id=u6e5ac076&originHeight=476&originWidth=428&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=40683&status=done&style=none&taskId=uacacbe0a-4d07-40d2-956e-7ba431ba100&title=&width=273.92)
###### Swimlane Diagram(泳道图)- behavior diagrams
variation of the activity diagram
groups activities performed by the same **actor** on an activity diagram in a single thread (lane)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686039494947-7bbed443-89ad-4426-8968-775935f44fd3.png#averageHue=%23f8f8f8&clientId=ueedd8867-d253-4&from=paste&height=323&id=u9c833529&originHeight=505&originWidth=832&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=82186&status=done&style=none&taskId=u2c5955e6-5c91-495c-8316-ae79ef0b805&title=&width=532.48)
###### Sequence Diagrams
#### Class-based models
objects, operations, relationships between the objects, collaborations between the classes
##### Analysis Class(分析类)
Analysis classes specify elements of an early conceptual model for things in the system that have **responsibilities** and **behavior**.
We might identify analysis classes by identifying **nouns** or **noun phrases** in the use cases
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686040133820-fa2626e5-5a43-4ebb-ad9d-a71794aa3fec.png#averageHue=%23cee3e3&clientId=ueedd8867-d253-4&from=paste&height=160&id=ue2e976a1&originHeight=250&originWidth=821&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=50132&status=done&style=none&taskId=uc3efc10b-131f-4b90-a48d-a988a6fc92f&title=&width=525.44)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686040145577-ffe63328-dd3c-4abf-9149-bc8d7c9f2df1.png#averageHue=%23cbe1e1&clientId=ueedd8867-d253-4&from=paste&height=152&id=u6c9bfbc6&originHeight=237&originWidth=840&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=42265&status=done&style=none&taskId=uc875270f-0221-497c-bde1-31714b11e0b&title=&width=537.6)
##### Class Diagrams- structure diagrams
###### Attributes & Operations
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686040268731-f12f0e2b-5511-471d-aed8-c0ce06bc671d.png#averageHue=%23e3e3e3&clientId=ueedd8867-d253-4&from=paste&height=141&id=u0d52d1b0&originHeight=220&originWidth=259&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=30500&status=done&style=none&taskId=ub32ab316-9e27-466c-9f3d-f264f8144f1&title=&width=165.76)
###### Relations
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686040504112-71f1c40b-d2d9-438f-9db2-eb3bb1b0110e.png#averageHue=%23f7f7f7&clientId=ueedd8867-d253-4&from=paste&height=173&id=u3be6f5ab&originHeight=270&originWidth=308&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=21085&status=done&style=none&taskId=ufc63b301-211e-4c7a-8ea5-d3bf5e532ee&title=&width=197.12)
Association: owns
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686040626497-861e8c79-a3a9-4e47-807a-5b96d9132a11.png#averageHue=%23fcfefb&clientId=ueedd8867-d253-4&from=paste&height=180&id=u9e9ffb03&originHeight=281&originWidth=203&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=22379&status=done&style=none&taskId=u8cf6bbae-a670-4242-aac6-d7f9968a9e5&title=&width=129.92)
Aggregation: **separate** lifetimes
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686040704467-3f0b0ad5-f75c-4fbf-a6f7-0d60c226fa3e.png#averageHue=%23f6f5f5&clientId=ueedd8867-d253-4&from=paste&height=88&id=ua2308503&originHeight=137&originWidth=427&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=15712&status=done&style=none&taskId=u41b51e58-de31-4b83-a024-a781eb48817&title=&width=273.28)
Composition: **same** lifetimes
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686040714681-9473d6d0-496b-46a6-9db7-13cc1f9c025d.png#averageHue=%23f6f6f6&clientId=ueedd8867-d253-4&from=paste&height=81&id=u1e4dfadf&originHeight=126&originWidth=359&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=11083&status=done&style=none&taskId=u3e6d237d-fa9f-4777-92c5-ee823e83cf6&title=&width=229.76)
Dependency: use
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686040728036-331e657f-7875-4aff-bb42-6085d35f4f40.png#averageHue=%23f5ebc2&clientId=ueedd8867-d253-4&from=paste&height=92&id=u5eec72c7&originHeight=143&originWidth=550&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=18822&status=done&style=none&taskId=u2811d895-c35c-4cad-9f87-8bfa5ddcf4f&title=&width=352)
###### Multiplicity
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686041074305-e39896ba-cc91-4f86-b81a-bb62277e703f.png#averageHue=%23f0efee&clientId=ueedd8867-d253-4&from=paste&height=151&id=u88eabd9c&originHeight=236&originWidth=639&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=39889&status=done&style=none&taskId=u36b6797d-ca3c-4368-91ec-e37da4a8ad5&title=&width=408.96)
#### Behavioral models
a system performs actions due to **external** **events**, with changes of **internal states**
##### State Machine Diagram- behavior diagrams
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686041246477-a6125b01-6319-4b6e-b52e-78b2bf2d08a5.png#averageHue=%23f3f3f3&clientId=ueedd8867-d253-4&from=paste&height=275&id=ua375ca26&originHeight=429&originWidth=762&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=103383&status=done&style=none&taskId=u11f9952c-6585-4485-b1bd-58be7771000&title=&width=487.68)
##### Sequence Diagram- behavior diagrams
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686041257195-a42f4e6f-7517-4877-bec8-5504b509cc9d.png#averageHue=%23f3f3f3&clientId=ueedd8867-d253-4&from=paste&height=260&id=u6b0735c3&originHeight=406&originWidth=644&originalType=binary&ratio=1.5625&rotation=0&showTitle=false&size=100500&status=done&style=none&taskId=u62e00468-7e9f-48ba-b344-3d2aba22302&title=&width=412.16)

## LECTURE 5-design
### Design model
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686195775075-b3e6d4ee-7221-4fe3-b998-fd4aa0e08c41.png#averageHue=%23b7b6b3&clientId=u7333d728-18d2-4&from=paste&height=236&id=KrsmX&originHeight=369&originWidth=747&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=204366&status=done&style=none&taskId=uaacf25c5-57b0-48f1-81af-03ad8a127d1&title=&width=478.08)
#### Data Design
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686196038155-b02a78a9-6dd0-4673-9f70-0ffd610d9bdd.png#averageHue=%23ece9e6&clientId=u7333d728-18d2-4&from=paste&height=246&id=u6079b40a&originHeight=385&originWidth=863&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=75560&status=done&style=none&taskId=u9de7a53d-c46d-4b82-8225-2051c434c40&title=&width=552.32)
#### Architectural Design
##### 4+1 View Model
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686196216221-390e66d4-375e-4f11-b330-1f9ccc03405c.png#averageHue=%23e2dfdc&clientId=u7333d728-18d2-4&from=paste&height=173&id=u2b8ad3e1&originHeight=270&originWidth=482&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=84734&status=done&style=none&taskId=u3aa164af-9e42-4ccb-a59e-c53c7e8ed53&title=&width=308.48)![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686196705187-6d231077-a393-4e02-80a1-607a8213eb84.png#averageHue=%23eaeaea&clientId=u7333d728-18d2-4&from=paste&height=222&id=u133993e6&originHeight=347&originWidth=724&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=52886&status=done&style=none&taskId=ube216dae-c278-4c29-bf16-c2737863926&title=&width=463.36)
###### Use Case View
use case diagram
###### Logical View
class diagram, state diagram, and component diagram
###### Development View
package diagram and component diagram
###### Process View
activity diagram and sequence diagram
###### Deployment View
deployment diagram
##### Architectural Style
Different architectural styles are NOT mutually exclusive; instead, they are often applied in combination
For example, a **layered **style can be combined with a **data-centered** architecture in many **database** applications.
In a browser-server **web** application, both **layered** architecture and **object-oriented** architecture can be applied
###### Data-centered architecture
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686197150868-4194237e-15c2-45fc-81ae-2e78d3105691.png#averageHue=%23d4a532&clientId=u7333d728-18d2-4&from=paste&height=234&id=u0e550e79&originHeight=365&originWidth=994&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=95443&status=done&style=none&taskId=u57d2760e-339d-472e-b52d-be215e44969&title=&width=636.16)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686197231721-f74ccd7c-95f7-4d97-8c48-b183d92aa3af.png#averageHue=%23f5f5f5&clientId=u7333d728-18d2-4&from=paste&height=239&id=u581a8136&originHeight=373&originWidth=504&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=48682&status=done&style=none&taskId=uebfe8cf7-3814-43d2-a011-6762779b5bd&title=&width=322.56)
###### Data-flow architecture
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686197301661-0ec74699-1a60-42f4-b742-48510264dbc0.png#averageHue=%23c7a481&clientId=u7333d728-18d2-4&from=paste&height=193&id=udb184212&originHeight=301&originWidth=558&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=28316&status=done&style=none&taskId=ue88070d5-c365-42f4-994a-93c0e22e681&title=&width=357.12)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686197292688-5e2bbe48-aade-48fe-af56-aa093f4aa01f.png#averageHue=%23f2e9d4&clientId=u7333d728-18d2-4&from=paste&height=102&id=u49d8466f&originHeight=159&originWidth=800&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=38458&status=done&style=none&taskId=u7fa1a169-d6fe-4047-8902-8f27ea7e44f&title=&width=512)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686197242380-f0409a5a-7df3-406d-926b-44cf60c0d112.png#averageHue=%23f0f0f0&clientId=u7333d728-18d2-4&from=paste&height=113&id=ue55106e7&originHeight=176&originWidth=611&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=41460&status=done&style=none&taskId=u22f8113f-c8f6-45f6-a9ee-a2d64d70751&title=&width=391.04)

###### Call-and-return architecture
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686197362171-765033f6-b19b-4dd7-b7d7-320a919743b9.png#averageHue=%23cda35a&clientId=u7333d728-18d2-4&from=paste&height=205&id=u456b5565&originHeight=321&originWidth=1018&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=96366&status=done&style=none&taskId=u775ae630-e70f-4e10-997f-352aee5629b&title=&width=651.52)
###### Layered architecture
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686206513524-2c2feda1-efd7-4fb9-87a0-daa6c575b72b.png#averageHue=%23a5b8ca&clientId=u7333d728-18d2-4&from=paste&height=216&id=u0c1500f7&originHeight=337&originWidth=405&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=51742&status=done&style=none&taskId=uf94c5c41-a4b8-40d2-9d55-ecbc537f642&title=&width=259.2)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686206520760-ba7936ea-a7f6-4b97-a5c7-5c9ba79a095e.png#averageHue=%23f6f6f6&clientId=u7333d728-18d2-4&from=paste&height=209&id=u824a42a0&originHeight=327&originWidth=1050&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=94560&status=done&style=none&taskId=ue4609e32-852b-4c45-8650-9486075efe1&title=&width=672)
###### Object-oriented architecture
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686206454366-66b92138-14e5-4133-8e31-ea519cd4f999.png#averageHue=%23edebe7&clientId=u7333d728-18d2-4&from=paste&height=226&id=ub86d41c4&originHeight=353&originWidth=787&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=112374&status=done&style=none&taskId=u23a62d63-d48e-4a2d-8f48-5fd6829b77e&title=&width=503.68)
#### Interface Design
##### UI Design
UI design incorporates different elements
• Aesthetic elements (美学): layout, color, graphics, interaction mechanisms, etc. 
• Ergonomic elements (人体工程学): information layout and placement, UI navigation
• Technical elements (技术元素): UI patterns, reusable components
###### Eeternal/Internal Interface Design
The design of external interfaces should incorporate error checking and (when necessary) appropriate security features
#### Component Level Design
The component-level design for software fully describes the **internal detail** of each software component. 
• **Data structures** for all local data objects
• **Algorithmic details** for all processing that occurs within a component
•** Interfaces** that allow access to all component operations (behaviors)
### Design concepts
#### Abstraction
#### Pattern
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686207496352-3ca99042-c8e0-4f08-8e89-9d1badcb0678.png#averageHue=%23f4f1ec&clientId=u7333d728-18d2-4&from=paste&height=228&id=u0da34fc9&originHeight=357&originWidth=1014&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=156388&status=done&style=none&taskId=u7f42f82a-c898-4733-995e-9fafad91f0f&title=&width=648.96)
#### Separation of concerns
#### Modularity
Modularity (模块化) is the most common manifestation of **separation of concerns**.
We should avoid undermodularity and overmodularity
#### Imformation Hiding
#### Functional Independence
loose coupling, high cohesion
### OO Design Concepts (SOLLID)
#### Single Responsibility Principle
**high cohesion**
Every class, module, or function should have **only one** reason to change
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686208485807-8411c0fb-eada-48ed-8480-f608a33ed2d7.png#averageHue=%23f3f3f2&clientId=u7333d728-18d2-4&from=paste&height=221&id=u7425cb53&originHeight=345&originWidth=1050&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=92166&status=done&style=none&taskId=u5f8981f1-cf35-4820-81e7-9511a632d09&title=&width=672)
#### Open Closed Principle
open for extension, but closed for modification
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686208471202-fce6b185-8370-4595-8c1a-a33cdc8f848c.png#averageHue=%23f6f6f6&clientId=u7333d728-18d2-4&from=paste&height=273&id=u0565c76a&originHeight=427&originWidth=1191&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=149258&status=done&style=none&taskId=u97806c90-59dd-4cb3-a0ed-58b3d3db050&title=&width=762.24)
#### Liskov Substitution Principle
The Liskov Substitution Principle (里式替换原则) states that objects of a superclass should be replaceable with objects of its subclasses without breaking the application.
Objects of subclasses should behave in the **same way **as the objects of superclass.
The Liskov Substitution Principle is supported by object-oriented design abstraction concepts of **inheritance** and **polymorphism**.
#### Law of Demeter
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686208425182-8ebf47a3-ef55-477f-be86-46e9b01bb803.png#averageHue=%23f6f2ea&clientId=u7333d728-18d2-4&from=paste&height=259&id=ue04e88e1&originHeight=405&originWidth=1172&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=116985&status=done&style=none&taskId=u856e45e2-35e4-43bb-89c8-1bb3ba12ca1&title=&width=750.08)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686208554901-eea0019d-d5d6-491a-b1f5-480670263eb5.png#averageHue=%23f2f2f2&clientId=u7333d728-18d2-4&from=paste&height=212&id=u5fd27b0e&originHeight=331&originWidth=1125&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=97041&status=done&style=none&taskId=ufc6a2adb-0e81-44f9-884d-dbfea0327de&title=&width=720)
#### Interface Segregation Principle
a client should not be exposed to methods it doesn't need
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686208727400-4ccf733a-06f9-40da-85e4-74a34678571a.png#averageHue=%23fefaf7&clientId=u7333d728-18d2-4&from=paste&height=134&id=u1b870c8b&originHeight=210&originWidth=483&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=18462&status=done&style=none&taskId=u35d3472a-fec0-41df-baeb-cd3d447a068&title=&width=309.12)
例子，图一圈红就是客户本身不需要的
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686208761840-fe79549a-8a41-4172-b674-d8e092dcd797.png#averageHue=%23d3d3ad&clientId=u7333d728-18d2-4&from=paste&height=356&id=u0b86e014&originHeight=557&originWidth=1152&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=121525&status=done&style=none&taskId=u9e3d7c8b-58d9-4b97-8614-a11c86358f3&title=&width=737.28)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686208773536-738620a5-87d9-4d7a-b588-4543987d824b.png#averageHue=%23b5d69f&clientId=u7333d728-18d2-4&from=paste&height=339&id=ucd19dfae&originHeight=529&originWidth=1112&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=106118&status=done&style=none&taskId=u2bedcd5a-9b0b-4ad9-99fb-5544037ae29&title=&width=711.68)
#### Dependence Inversion Principle
reduce dependencies to specific implementations, but **rely on interfaces**.
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686208911721-4826cb9c-4d49-435d-9ca6-416a2a813b13.png#averageHue=%23fdfdfd&clientId=u7333d728-18d2-4&from=paste&height=253&id=u8fe62e19&originHeight=395&originWidth=973&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=96199&status=done&style=none&taskId=u91c6ff76-68da-44b0-876f-f1f9b419d98&title=&width=622.72)
## LECTURE 6-build
### Dependency
#### Internal vs External Dependency
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686210625700-3f2c6484-958e-4104-b913-faa3005de547.png#averageHue=%23f5f2ef&clientId=u7333d728-18d2-4&from=paste&height=138&id=u11355a8f&originHeight=215&originWidth=370&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=26448&status=done&style=none&taskId=u75d8b0b5-9211-4de8-b5fb-0e7b1558058&title=&width=236.8)
#### Task vs Artifact Dependency
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686210643200-57a733b4-1780-436d-b4f5-822e96befe45.png#averageHue=%23f5f2ef&clientId=u7333d728-18d2-4&from=paste&height=147&id=u73777b51&originHeight=230&originWidth=373&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=31343&status=done&style=none&taskId=uaf6af242-45d3-47ed-9bac-4ce2c18d570&title=&width=238.72)
#### Dependency Scopes
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686210696390-15402c4d-2434-47d1-be1a-5fb23504aa1d.png#averageHue=%23f9f7f5&clientId=u7333d728-18d2-4&from=paste&height=108&id=u3bf7bf33&originHeight=168&originWidth=854&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=32178&status=done&style=none&taskId=u14aa5b68-ad66-450c-ba86-948072051b8&title=&width=546.56)
### Build system
Building is the process of creating a complete, executable software by **compiling** and **linking** the software components, external libraries, configuration files, etc.
Building involves assembling a large amount of info about the **software** and its **operating environment**.
#### Task-based Build Systems
Engineers define a series of steps to execute
System is flexible and powerful, but hard to guarantee correctness and parallelize
Most major build systems (e.g., Ant, Maven, Gradle, Grunt, and Rake), are task based
Most modern build systems require engineers to create **buildfiles** that describe how to perform the build (e.g., pom.xml for Maven)
对于开发人员灵活度高Engineers can write arbitrary code to execute any tasks during build
但是系统不好察觉依赖情况Systems can' t have enough information/control to always be able to run builds quickly and correctly
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686211134380-c449d087-adf7-474f-8758-afd5ca5d926d.png#averageHue=%23f0f0f0&clientId=u7333d728-18d2-4&from=paste&height=303&id=u80ecdc62&originHeight=473&originWidth=927&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=173229&status=done&style=none&taskId=u81ca951e-87a1-4f13-b9ac-d57a5e5020a&title=&width=593.28)
##### Drawbacks
###### Difficulty maintaining & debugging build scripts
A依赖B，但是B不知道有人依赖他，之后B把自己路径改，A知道运行的时候报错才知道他依赖的B不见了
A依赖B，B依赖C，以及A需要的依赖刚好只有C才能生产，某天B不依赖C了，A就运行失败了
在我的电脑可以跑但是你那跑不了，因为我这依赖了一些固定的文件位置或者环境变量
每次build后的结果都不一样，因为依赖了一些可变的东西，不如网络实时下载的文件或者时间戳
race condition，A同时依赖了B和C，A每次会得到不一样的结果取决于BC谁快
###### Difficulty performing incremental builds
难以发现细小的变化，每次build都要重新跑一遍所有的
###### Difficulty of parallelizing build steps
hard to determine task dependencies and change impact，因此无法并行运行去build工程，以及hard to distribute the build across multiple machines

#### Artifact-based Build Systems
Engineers declare a manifest describing the input and output  (with the result but not how)
System provides strong guarantees about the correctness and easy to parallelize
In a build process, the role of system is producing **artifacts** (e.g., executable binary, documentation, etc.)
Engineers still need to tell the system **what** to build, **but how** to do the build would be left to the system
The approach that Google takes with **Blaze** (internal version) and **Bazel** (open-source version)
Buildfiles in artifact-based build 
##### buildfiles
buildfiles define targets
describing:
• A set of artifacts to build
• Their dependencies
• Limited set of configurations
Engineers run blaze by specifying a set of targets to build (the "**what**")
Blaze is responsible for configuring, running, and scheduling the compilation steps (the "**how**")
##### targets
Every target has
• **name**, which could be used to reference this target
• **srcs**, which define the source files that must be compiled to create the artifact for the target
• **deps**, which define other targets that must be built before this target and linked into it
##### first time build
生成图依赖关系，从叶子节点开始build
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686213656474-74cca13d-6da2-4f6a-9573-63e44834c1fe.png#averageHue=%23f9f3e7&clientId=u7333d728-18d2-4&from=paste&height=243&id=u26993e28&originHeight=379&originWidth=549&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=69969&status=done&style=none&taskId=u761ab5e8-7058-402c-8da5-5695a21f787&title=&width=351.36)
##### Benefits
###### Parallelism
因为用的是自己的execution strategy所以更能保证一些事情，比如并行执行
###### Incremental Builds
因为依赖的是java编译器的结果，那么源代码不变，编译结果不变，也就不会重新build
因为它很懂自己编译的过程，所以有变化也只需要rebuild only the minimum set of artifacts，并且有所保证

### Dependency management
#### Internal Dependendy
A target depends on other targets in the **same source repository**
##### strict transitive dependencies
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686214546727-fa1a55c0-b404-44c0-a669-f9e8a0ba95ec.png#averageHue=%23f8f4ec&clientId=u7333d728-18d2-4&from=paste&height=210&id=ufef73ec0&originHeight=328&originWidth=856&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=63157&status=done&style=none&taskId=ucda3e0bc-7484-4ed4-b803-c46f89287fa&title=&width=547.84)
#### External Dependency
A target depends on artifacts built and stored **outside** **of the project** and typically **accessed via Internet**
##### Reliability Risks- mirroring
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686214711752-5f0212a0-1e03-4422-b919-39c419099f56.png#averageHue=%23f2eee9&clientId=u7333d728-18d2-4&from=paste&height=111&id=u8ee677da&originHeight=174&originWidth=885&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=44461&status=done&style=none&taskId=ubd5b1322-e879-4935-bc85-3575cd5ac9f&title=&width=566.4)
##### Diamond Dependency Issues
当依赖的两个库同时依赖另一个库但是是不同版本，你的工程要不存在冲突，要不存在重复
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686214806645-5d25f3be-b711-4c49-942b-b067636c038d.png#averageHue=%23f3f1ee&clientId=u7333d728-18d2-4&from=paste&height=228&id=u5677922c&originHeight=356&originWidth=950&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=103106&status=done&style=none&taskId=ud64c2635-e834-401f-8647-5d8a5495988&title=&width=608)
#### Semantic Versioning
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686214954432-b2ff9255-87be-4628-bd9b-504f36fd75d4.png#averageHue=%23f3ebd9&clientId=u7333d728-18d2-4&from=paste&height=200&id=u3bc439c8&originHeight=313&originWidth=947&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=79241&status=done&style=none&taskId=ue23c4897-70f7-4e64-a01e-b8ee3a8c577&title=&width=606.08)
对依赖的要求
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686215270606-b5a037ed-5e0a-420e-bbc1-5c152635c779.png#averageHue=%23f8f7f6&clientId=u7333d728-18d2-4&from=paste&height=158&id=ubfeb8c11&originHeight=247&originWidth=741&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=36153&status=done&style=none&taskId=u477e649b-d0cb-4ec1-93aa-4301284e04a&title=&width=474.24)
Bar和Baz依赖同一个库，为了不出现冲突因此要选择他们依赖的库一样的版本
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686215289129-d6192c9d-8155-4ce0-a5b1-7370090c50e9.png#averageHue=%23fcfaf7&clientId=u7333d728-18d2-4&from=paste&height=276&id=u8e551f1f&originHeight=431&originWidth=1056&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=82865&status=done&style=none&taskId=ube9515f9-9b07-462f-ac5d-1cefae9f48c&title=&width=675.84)
## LECTURE 7-quality
**External quality** can be measured through feature tests, QA and customer feedback.
**Internal quality** can be measured through linters, unit tests etc.
### Code quality
#### Understandability (可理解性)
Confusing identifiers命名不容易理解
Misleading indentation缩进
Deep nesting太多if
Improper exception type异常处理类型不对或者没必要
Potential bugs: no null-checking/missing/missing else block
Meaningful identifier names:
• Use Intention-Revealing Names
• Name Functions as Verbs
• Name Classes as Nouns
• Use Meaningful Distinction不要用arr1，arr2来区分
• Use Pronounceable Names
• Use Searchable Names 用有名字的常量不是，而不是数字
#### Maintainability (可维护性)
Good for:
Search
Extend
Modify & Reuse
##### Code Clone
Increase code size
Increase maintenance cost
###### types
Type 1: Exact copy, only differences in white space and comments.
Type 2: Same as type 1, but also variable renaming.
Type 3: Same as type 2, but also changing or adding few statements.
Type 4: Semantically identical, but not necessarily same syntax.
###### reduce methods
Extract method: Extract duplicate code to a new method
Pull up method: taking a method and "Pulling" it up in the **inheritance** chain.
##### Code Clone Detection
###### Text matching
No program **structure** is taken into consideration
Detect Type-1 clones & some Type-2 clones
Two types of text matching
• Exact string match: diff (cvs, svn, git) is based on exact text matching
• Ambiguous match: LCS, n-gram match
###### Token sequence matching
No program structure is taken into account
Detect Type-1 and Type-2 clones
可以识别对变量重命名的
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686225432281-aa0cf194-5377-4318-9c70-64c2648405da.png#averageHue=%23f7f7f6&clientId=udd0f8a4d-947f-4&from=paste&height=244&id=ua9a478c4&originHeight=382&originWidth=673&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=168185&status=done&style=none&taskId=udfc0dbb0-a37d-4bb1-8a44-4f710240f0c&title=&width=430.72)
###### Graph matching
Detect Type-1, Type-2, and Type-3 clones
Graphs for modeling source code
• AST (Abstract Syntax Tree)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686225525376-1cf386d9-417b-41eb-9962-64691bade088.png#averageHue=%23f6f6f4&clientId=udd0f8a4d-947f-4&from=paste&height=234&id=ua6d0f9c0&originHeight=365&originWidth=606&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=45480&status=done&style=none&taskId=u01bab0a1-49f2-47f1-9cd6-399f01f56d5&title=&width=387.84)
• CFG (Control Flow Graph)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686225560845-7afd611f-1354-43b2-a788-1068f012268e.png#averageHue=%23f4f4f4&clientId=udd0f8a4d-947f-4&from=paste&height=364&id=uf1b33f6d&originHeight=569&originWidth=417&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=114254&status=done&style=none&taskId=u8853eaa3-cbe6-4ada-94ba-d7b01ba89f9&title=&width=266.88)
• PDG (Program Dependency Graph)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686225575328-1d10a31b-d2d3-4dd8-8b7d-aa98e2ec3099.png#averageHue=%23faf9f9&clientId=udd0f8a4d-947f-4&from=paste&height=230&id=u0affada6&originHeight=359&originWidth=588&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=65274&status=done&style=none&taskId=u385e6c90-c520-4383-990d-34351a034d9&title=&width=376.32)
#### Reliability (可靠性)
##### Error handling
For Reliability: proper error handling ensures the normal execution of 
the program
For Maintainability: proper error handling logs error conditions, which 
facilitate debugging and fixing.
###### Safety-critical system (SCS)- no incorrect
For SCS, error handling should value software **correctness**: the software could **terminate**, but should **never return incorrect results.**
###### Mission-critical system (MCS)- no terminate
For MCS, error handling should value software **robustness**: the software could tolerate certain errors, but **should not terminate**
#### Security (安全性)
Input validation
#### Efficiency (高效性)
time behavior
resource behavior
#### Portability (可移植性)
from one environment to another
### Code review
#### Types of code changes to be reviewed
Modifications to existing code (Bug fixes and rollbacks)
Entirely new code
Automatically generated code (E.g., refactoring tools, intelligent code generators)
#### Benefits
##### Code correctness
Many correctness checks are performed automatically through techniques such as static analysis and automated testing
##### Code readability
##### Code consistency
##### Knowledge sharing
#### Code review flow at Google
At Google, code reviews take place before a change can be committed to the codebase; this stage is also known as a **precommit review**.
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686226702132-ababcfa5-af06-4672-991f-49eec06e5d77.png#averageHue=%23e8e3d5&clientId=udd0f8a4d-947f-4&from=paste&height=131&id=u6b9eec40&originHeight=204&originWidth=491&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=31084&status=done&style=none&taskId=u67aa8b4a-0a68-4a77-8b92-e675a1fc07c&title=&width=314.24)
#### Best practice
##### write small changes
~200 LoC
##### write good change descriptions
Explain what is changed and why
• E.g., “bug fix” is not a good change description
A good change description also allows Code Search tools to find changes
##### keep reviewers to a minimum
##### automate where possible
## LECTURE 8-metrics
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686228037924-b773a1be-8835-45f6-a2b2-a14a3a34b9d3.png#averageHue=%23f4f2ef&clientId=udd0f8a4d-947f-4&from=paste&height=246&id=u06ec6817&originHeight=384&originWidth=869&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=100693&status=done&style=none&taskId=ue56caa25-3e34-460f-8c34-8df10774445&title=&width=556.16)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686228044140-617fe5a3-0968-4728-8210-2717ae4299b3.png#averageHue=%23f1efec&clientId=udd0f8a4d-947f-4&from=paste&height=250&id=u1d05d308&originHeight=391&originWidth=818&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=146639&status=done&style=none&taskId=u80e2fbad-9df2-4b5d-9e92-2d2341bafbb&title=&width=523.52)
**Code size** still dominates many metrics
### Metrics types
#### Product Metrics
e.g., size, complexity, performance, etc.
#### Process Metrics
e.g., # bugs found, bug fixing time, # features added
#### Project Metrics
e.g., # of developers, money spent, time spent

### Measure the complexity of a system
#### Lines of code
##### normalizing
不要有没用的空行
##### language matters
不同的编程语言同样行数表达的信息量不同
##### LoC is a valid metric when
• Use within the **same** programming language
• Code measured use standard, consistent **formatting**
• Code has been **reviewed** first
#### Cyclomatic complexity (圈复杂度)
the complexity of code depends on the number of decisions in the code **(if, while, for)**
computed using the **control-flow graph** (控制流图) of the program
used to estimate the required effort for **writing tests**
复杂度一样不代表same readability & maintainability
复杂度高不代表low readability
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686229186503-86b33bf6-3677-4be2-9f26-075ceb1777db.png#averageHue=%23eeedec&clientId=udd0f8a4d-947f-4&from=paste&height=229&id=ue9a3bd3e&originHeight=358&originWidth=768&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=58952&status=done&style=none&taskId=u3ca04bbf-0cc1-4a82-9127-71b0e0886ac&title=&width=491.52)
### Coupling & Cohesion
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686229466462-6f99e55f-e48a-4587-94ea-9e17deb145cc.png#averageHue=%23f5f0e3&clientId=udd0f8a4d-947f-4&from=paste&height=170&id=uec65c928&originHeight=265&originWidth=541&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=38853&status=done&style=none&taskId=u0f529706-70da-476f-9fe0-bbefa2e3a19&title=&width=346.24)
##### Martin's coupling metrics
###### Efferent coupling (Ce)- 依赖别人的数量
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686229681796-40127218-046c-4a06-8b9c-249a77e2e4e8.png#averageHue=%23f8ece2&clientId=udd0f8a4d-947f-4&from=paste&height=147&id=u8e7cb346&originHeight=230&originWidth=501&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=36065&status=done&style=none&taskId=ubfa257f9-d9bb-4bff-b780-c1a8b5bdaca&title=&width=320.64)
###### Afferent coupling (Ca)- 被别人依赖的数量
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686229729493-df5e91c6-0c20-444b-8322-dbfa3a52d0f7.png#averageHue=%23fae5d9&clientId=udd0f8a4d-947f-4&from=paste&height=147&id=u66ba76d1&originHeight=229&originWidth=613&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=37341&status=done&style=none&taskId=ud82f699b-ebe9-4f0e-9187-24864e1f61c&title=&width=392.32)
###### Instability calculate- 依赖别人数/所有依赖
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686229802328-f444e3c9-5f2d-4f3a-b316-815a2ba28bc8.png#averageHue=%23fbfbfa&clientId=udd0f8a4d-947f-4&from=paste&height=221&id=ud0a9a4b6&originHeight=346&originWidth=775&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=52362&status=done&style=none&taskId=ucaa40976-14c2-4b95-8314-9f52e724884&title=&width=496)
太高->1：依赖的太多Ce high，不稳定
太低->0：被依赖太多Ca high，不好修改
### OO Metrics
#### Weighted Methods per Class (WMC)
indicate the development and maintenance effort for the class
Classes with **large** numbers of methods are more likely to be **application specific and less reusable**
#### Depth of Inheritance Tree (DIT)
The deeper a class is in the hierarchy, the more methods it inherits and so it is **harder to predict** its behavior
The deeper a class is in the hierarchy, the more methods it **reuses**
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686230541835-a0b4ea6d-18eb-4364-8902-d4f6fa545c2d.png#averageHue=%23f4f4f4&clientId=udd0f8a4d-947f-4&from=paste&height=172&id=u84cf52d2&originHeight=268&originWidth=309&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=8832&status=done&style=none&taskId=u1de5eb01-f3ec-49d5-ab9f-8c1594633ad&title=&width=197.76)
#### Number of Children (NOC)
 immediate subclasses
A class with a large NOC is probably very **important** and needs a **lot of testing**
#### Coupling between Object Classes (CBO) 
CBO doesn't care about the direction of a dependency
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686230693807-a3318d00-b050-4944-b3eb-bec681f355bb.png#averageHue=%23fbfaec&clientId=udd0f8a4d-947f-4&from=paste&height=191&id=ue87e0e5c&originHeight=298&originWidth=553&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=33750&status=done&style=none&taskId=u72533b12-bdfe-4009-8c75-1613590f1c0&title=&width=353.92)
#### Response for a Class (RFC)
If a large number of methods can be invoked in response to a message, **testing** becomes more complicated
The more methods that can be invoked from a class, the greater the **complexity** of the class
#### Lack of Cohesion in Methods (LCOM)
LCOM counts the sets of methods in a class that are **not related** through the **sharing** of some of the class's fields.
不共享的对-共享的对
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686230928648-e1342d6f-90d3-41eb-aad3-0573cbd8ff67.png#averageHue=%23f7f5f3&clientId=udd0f8a4d-947f-4&from=paste&height=115&id=u600d076b&originHeight=179&originWidth=849&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=26126&status=done&style=none&taskId=u1950df3c-fb43-482d-aa76-dbe185788f3&title=&width=543.36)
Cohesiveness of methods is a sign of encapsulation
**Lack of cohesion** implies that classes should be** split **(如果LCOM太低，说明方法里的方法都不太相关，这个类应该被分解)
### Measurement is difficult
#### Streetlight effect
只会关心能够测量的，不能够测量的也很重要的不被注意到
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686231125910-9570fe7e-d3c7-460e-8af8-77f654a4a266.png#averageHue=%23919191&clientId=udd0f8a4d-947f-4&from=paste&height=225&id=ud0c19852&originHeight=351&originWidth=375&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=116721&status=done&style=none&taskId=u9cefd800-4f34-411e-ae02-1bd9b86829a&title=&width=240)
#### Flaw of averages
只关心平均值会有问题，以及只关心一个值会有问题
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686231243050-e77f8253-7e65-40b5-b763-01c12c77cef3.png#averageHue=%23f1eee6&clientId=udd0f8a4d-947f-4&from=paste&height=217&id=u0677fb54&originHeight=339&originWidth=951&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=113399&status=done&style=none&taskId=u41a3500a-af3a-4d51-be5f-37b65eeac7e&title=&width=608.64)
#### Survivorship bias
只关注了成功的案例，没有关注失败的案例
#### Correlation does not imply causation- 关联不等于因果
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686231495193-2dff5488-7d14-47d4-9203-dee76efcf8fd.png#averageHue=%23f1f0f0&clientId=udd0f8a4d-947f-4&from=paste&height=221&id=ubf1cc49f&originHeight=345&originWidth=704&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=67772&status=done&style=none&taskId=u86a021d5-42da-489a-9be6-2827aecc2ed&title=&width=450.56)
#### Simpson's paradox
Simpson's paradox is a phenomenon in probability and statistics in which a trend appears in several groups of data but disappears or reverses when the groups are combined.
在不同的环境有两个完全相反的结论
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686231627020-2fd6a923-e36e-4bb3-b675-869f127b73a9.png#averageHue=%23f8f5f3&clientId=udd0f8a4d-947f-4&from=paste&height=201&id=ud942f8a8&originHeight=314&originWidth=1267&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=84178&status=done&style=none&taskId=ufb8628dd-040d-4658-a5e2-40aa47d36aa&title=&width=810.88)
### Measurement validity
#### Internal validity
focuses on the accuracy of the conclusions drawn based on a cause and effect relationship (is the Cause-Effect okay?)
#### External validity
Can the conclusions be generalizable?
Our findings are drawn by studying Java code. Can we say the same thing for Python?

### Measurement reliability
Extend to which a measurement yields **similar results** when applied **multiple times**
Law of large numbers (大数定律)
## LECTURE 9-evolution
### Software evolution
Research suggests that 85–90% of organizational software costs are evolution costs.
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686232475174-f22581f1-89ab-43ac-9246-7b622a7c582c.png#averageHue=%23f2efec&clientId=udd0f8a4d-947f-4&from=paste&height=220&id=u5b51580e&originHeight=344&originWidth=852&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=65850&status=done&style=none&taskId=uc2174ecf-5f72-4eed-a051-32440534d8d&title=&width=545.28)

#### Legacy systems & codes
##### Why not replace?
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686232636563-994f5d5d-e6fa-450d-b6d9-054838061b94.png#averageHue=%23eeece8&clientId=udd0f8a4d-947f-4&from=paste&height=194&id=u2e445fec&originHeight=303&originWidth=919&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=61663&status=done&style=none&taskId=uf5827746-1ff5-4aba-80da-489f3116d54&title=&width=588.16)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686232728562-07267110-294a-4420-8802-abe341377dea.png#averageHue=%23f2ecde&clientId=udd0f8a4d-947f-4&from=paste&height=147&id=u170930e0&originHeight=229&originWidth=927&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=44646&status=done&style=none&taskId=u526e425a-fc03-4335-a0d7-89f8bc0ffad&title=&width=593.28)
##### Decisions
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686232822180-6abd0897-a4f0-4213-b994-4a2210052011.png#averageHue=%23eceae9&clientId=udd0f8a4d-947f-4&from=paste&height=205&id=u247e7d98&originHeight=320&originWidth=883&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=57889&status=done&style=none&taskId=uf3029004-61c6-47fd-b2ea-2aea5fd7dc3&title=&width=565.12)
##### Which decision?
商业价值高的不能abandon，低的可以
质量好的就维持
![微信截图_20230608220409.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686233195173-1ee675bd-daf6-4e03-ba2f-a8f04e20744c.png#averageHue=%23fcf7f5&clientId=udd0f8a4d-947f-4&from=paste&height=244&id=u0ee0ceea&originHeight=381&originWidth=566&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=96699&status=done&style=none&taskId=u6d64fb82-72af-4e2c-b99c-0cff0da11c3&title=&width=362.24)
#### Deprecation
##### What should be deprecated?
Old doesn't mean obsolete老不代表过时比如latex
Deprecation is best suited for systems/modules/code/APIs/features that are demonstrably obsolete and a replacement exists that provides comparable functionality. 过时了，而且有更好的的时候弃用旧的
##### How to?
###### Dependency discovery
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686233584619-2cf30517-2abb-47cd-988a-94f725096257.png#averageHue=%23f6f1e7&clientId=udd0f8a4d-947f-4&from=paste&height=141&id=ua04e4357&originHeight=221&originWidth=806&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=37846&status=done&style=none&taskId=u5209bbb2-f3a4-4d6c-bad6-a89a3cd7da0&title=&width=515.84)
###### Warning flags
Owners of deprecated systems add compiler annotations** **to deprecated symbols (e.g., the **@deprecated Java annotation**)
###### Sunset period
Sunset period provides API consumers with an adequate time to upgrade to a newer version or retire the functionality before the API stops working.
To provide a smooth transition for customers and internal developers, some providers defines sunset period as a combination of **6 months of fully** functional and supported API and another 6 months of functional API with **no additional support**.
###### Migration & Testing
Using tools to **automatically update** the codebase to refer to new libraries or runtime services
Using **test suite** to automatically determine whether all references to deprecated symbols have been **removed** without breaking existing functionalities
### Software maintenance
Effort distribution:
Coding errors < Design errors < Requirements errors
Metrics:
Number of requests for corrective maintenance
Average time required for impact analysis
Average time taken to implement a change request
#### Reengineering
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686235751042-b7f0b151-ce3b-4251-ad72-60324290c3be.png#averageHue=%23f9d4ac&clientId=udd0f8a4d-947f-4&from=paste&height=290&id=uc186d8a3&originHeight=453&originWidth=773&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=102723&status=done&style=none&taskId=ud1c54d7e-803f-42d3-8098-e2fc42f51ef&title=&width=494.72)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686236167427-0ab484f1-e654-43ca-9ebf-007c823c0cb0.png#averageHue=%23f2f2f1&clientId=udd0f8a4d-947f-4&from=paste&height=319&id=Xr8eH&originHeight=499&originWidth=1336&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=213833&status=done&style=none&taskId=u92aaec17-c089-4a48-b5a3-3f2ea5457c5&title=&width=855.04)
##### Input & Output
Input: 
• The original legacy system
Output: 
• An improved and restructured version of the same program
• Program documentation
• Reengineered data
##### 3-stages
###### Reverse engineering
###### System transformation
further transformed into other representations **at the same abstraction level**.
The aim is to improve the software structure, quality, and stability.
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686235997277-c9e16b60-93e0-4e08-92a8-72314849b89b.png#averageHue=%23e6dbc1&clientId=udd0f8a4d-947f-4&from=paste&height=150&id=VAyXJ&originHeight=235&originWidth=525&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=49680&status=done&style=none&taskId=uf4c9b71f-23f4-48d6-92dd-3e481f5afad&title=&width=336)
###### Forward engineering
##### Document restructuring
Update the documentation for the parts of the system that is currently undergoing change
##### Reverse engineering
representation of it at a **higher level of abstraction** than source code
Goal is to understand **how it was built**
##### Data restructuring
Can be a very **expensive and prolonged** process
##### Code restructuring/refactoring
This can be **partially automated**, but some manual intervention is usually required.
##### Forward engineering
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686236108140-df75bbc7-4215-4b50-8328-d09a44373e36.png#averageHue=%23ede9e6&clientId=udd0f8a4d-947f-4&from=paste&height=231&id=u16b44cdb&originHeight=361&originWidth=543&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=65088&status=done&style=none&taskId=u43c721f4-20a7-409f-8c6c-e3510f3d44d&title=&width=347.52)

#### Refactoring
##### What is?
Preserves the external **behavior** of the software
Improves the internal **structure** of the software
##### When to?
###### Rule of three
When you're doing something for the **third** time, start refactoring.
###### When adding a feature
If you have to deal with someone else's dirty code, **try to refactor it first**. Clean code is much easier to grasp.
###### When fixing a bug
If a bug is very hard to trace, refactor first to make the code more understandable
###### During a code review
##### What to refactor- code smells
###### Bloaters臃肿
**Long Method** ->  Extract Method
**Long Parameter List** -> Replace Parameter With Method Call
###### OO Abusers
**Refused Bequest拒绝遗产 **(Violation of the Liskov Substitution Principle) -> Replace Inheritance With Delegation / pushdown methods/fields
###### Change Preventers
Shotgun Surgery (Violation of the Single Responsibility Principle) -> Extract Method
###### Dispensables
Duplicate code
Dead code (unused and obsolete code)
Lazy class (classes that don't do enough to earn your attention)
###### Couplers
Feature Envy
## LECTURE 10-documentation
### Software documentation
#### Internal Software Documentation
##### Administrative documentation
high-level administrative guidelines, roadmaps and product requirements
##### Developer documentation
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686238118017-5e688e92-7fa8-42e6-8ce8-11f2d0b8132c.png#averageHue=%23f6f4f2&clientId=udd0f8a4d-947f-4&from=paste&height=126&id=uee7258e4&originHeight=197&originWidth=912&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=41273&status=done&style=none&taskId=ufd3a9e7e-5589-43e4-9039-08ad7de73c8&title=&width=583.68)
#### External Software Documentation
##### End-user documentation
##### Enterprise user documentation
used for IT staff who deploy the software across the enterprise
##### Just-in-time documentation
provides end users with **support documentation** at the exact time they will need it (e.g., **FAQ pages**, how-to documents)
#### Writing Good Documentation
##### Self-Documenting Code
好代码一眼就看懂
##### Code Comments
不是写干了啥，而是写要干啥，写意图
Code comments are ignored by compilers and interpreters when producing the final executable.
However, too many or unnecessary comments reduce readability.
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686238716319-d1f9be9a-89a6-46f4-9063-e8829de24ca8.png#averageHue=%23e3dfd9&clientId=udd0f8a4d-947f-4&from=paste&height=177&id=u3ee5402f&originHeight=276&originWidth=763&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=64894&status=done&style=none&taskId=u0838cd3d-b371-41c1-92db-161c57d78c6&title=&width=488.32)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686238787347-eb87f640-a319-4f29-ae1f-a5d735570559.png#averageHue=%23eae4d5&clientId=udd0f8a4d-947f-4&from=paste&height=236&id=u49a62899&originHeight=368&originWidth=763&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=57961&status=done&style=none&taskId=ub980aecf-e37b-4e11-a45c-b4e1a7f30c6&title=&width=488.32)

#### JAVADOC
Javadoc (included in **JDK**) automatically generates API documentation from comments present in the Java **source code**.
Javadoc style comments may contain **HTML tags** as well.
Two comment way:
1.Extra asterisk at the beginning
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686239096458-281ac2c4-cd8f-48ca-ad23-c5b198d37fa7.png#averageHue=%23f9f8f7&clientId=udd0f8a4d-947f-4&from=paste&height=166&id=u359cbbe5&originHeight=259&originWidth=465&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=23238&status=done&style=none&taskId=u1c8870aa-2e98-48f2-a042-804373828cd&title=&width=297.6)
2.The standalone block tags (marked with the “@” symbol)
## LECTURE 11-testing
### Overview
#### Developer Driven Testing (DDT)
Every coded feature should be tested completely once, by the **developer** responsible for implementing it
### Testing Concepts
#### Test case (测试用例)
A test case specifies the prerequisites, post conditions, steps, and data required for feature verification.
Test case example: Check results when a valid Login Id and Password are entered.
#### Test suites (测试套件、测试集)
a test suite for product purchase has multiple test cases
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686245792057-0b73041c-4956-4cc9-b1af-70140e85fdc0.png#averageHue=%23fcfbfb&clientId=udd0f8a4d-947f-4&from=paste&height=99&id=uc9c56253&originHeight=155&originWidth=947&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=32304&status=done&style=none&taskId=u873c3653-36fc-4a65-aeb7-e1fe8587973&title=&width=606.08)
#### Test Oracle (测试预言、测试判断准则)
 is a fault free source of expected outputs: it accepts every test input specified in software's specification and should always generate a **correct result**
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686245934922-2a8f321f-3795-4e96-b969-ff95026246fb.png#averageHue=%23f6f5f4&clientId=udd0f8a4d-947f-4&from=paste&height=254&id=ufa34669c&originHeight=397&originWidth=1196&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=92138&status=done&style=none&taskId=u66adfc46-6944-417a-a62c-57c4139da2b&title=&width=765.44)
#### Types
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686245958828-4712159e-123e-4aaf-bf96-08d1547fb2e1.png#averageHue=%23efeded&clientId=udd0f8a4d-947f-4&from=paste&height=317&id=u9f486c00&originHeight=495&originWidth=1221&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=230313&status=done&style=none&taskId=u2e00961d-13ca-44a3-8499-3915e4b4239&title=&width=781.44)
##### Functional Testing
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686246335835-ecf3cb38-899b-4ac4-8565-44894fb30af3.png#averageHue=%23f3f2ef&clientId=udd0f8a4d-947f-4&from=paste&height=152&id=ub2df556f&originHeight=237&originWidth=1177&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=147078&status=done&style=none&taskId=u8623c3ac-2935-4c9a-a428-0fabcb5a3b6&title=&width=753.28)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686246325828-5e5d9b84-2c5d-417e-aaa1-040c63801528.png#averageHue=%23564c27&clientId=udd0f8a4d-947f-4&from=paste&height=313&id=YDFjq&originHeight=489&originWidth=506&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=42501&status=done&style=none&taskId=u1b4675fe-2614-4715-9bf8-2d6b0352d33&title=&width=323.84)
###### Unit testing
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686246121218-0da54ea6-e883-4e7e-b04d-d3d3e390a3ae.png#averageHue=%23ede5d3&clientId=udd0f8a4d-947f-4&from=paste&height=237&id=udf09e1bd&originHeight=371&originWidth=621&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=65711&status=done&style=none&taskId=ue5e7e5e4-cd74-41e5-a77f-da81c9faf97&title=&width=397.44)
###### Integration testing
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686246154917-ad518268-b744-40b4-9cfc-de1027e884ed.png#averageHue=%23ede3cb&clientId=udd0f8a4d-947f-4&from=paste&height=146&id=u885ec5e8&originHeight=228&originWidth=590&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=40275&status=done&style=none&taskId=ud91a71ef-0219-49c4-890a-8c8e6c686e3&title=&width=377.6)![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686246163610-8cf1989e-19d9-469a-9c61-5afe907d2ff0.png#averageHue=%23e1f3f0&clientId=udd0f8a4d-947f-4&from=paste&height=269&id=u2a849e7c&originHeight=444&originWidth=571&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=59698&status=done&style=none&taskId=u558527f5-1cea-4be2-aaa6-850832ec051&title=&width=345.44000244140625)

###### System testing
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686246299430-2250497e-a951-44fe-8436-d4c6fb48400c.png#averageHue=%23efe4c6&clientId=udd0f8a4d-947f-4&from=paste&height=142&id=ud94ea0b3&originHeight=222&originWidth=1245&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=60320&status=done&style=none&taskId=u49aa129e-4ba2-4156-a392-54d410aad78&title=&width=796.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686246290525-f6a34a55-ed23-4417-82a1-d1631b153166.png#averageHue=%23f5f1e7&clientId=udd0f8a4d-947f-4&from=paste&height=270&id=uce0e4b81&originHeight=422&originWidth=1252&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=174187&status=done&style=none&taskId=ucf77d6d3-96ae-4726-85dd-6d3ca7a1ab3&title=&width=801.28)
###### Acceptance testing
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686246382449-8f0e032c-3cc9-4043-ad6b-80579c8ff818.png#averageHue=%23ebdaae&clientId=udd0f8a4d-947f-4&from=paste&height=214&id=u0a7d8ae9&originHeight=335&originWidth=620&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=62651&status=done&style=none&taskId=uf3d5f97b-4673-4f47-8bfc-5e137d9b5bf&title=&width=396.8)
##### Non-Functional Testing
#### Size
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686246469786-209f1f52-3104-4291-8b76-9c870ef4d647.png#averageHue=%23f7f6f5&clientId=udd0f8a4d-947f-4&from=paste&height=223&id=u9fdda314&originHeight=348&originWidth=703&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=17072&status=done&style=none&taskId=u18a7c843-ee98-4054-997c-fcb3e298878&title=&width=449.92)
##### Small tests
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686246456673-47765aa8-60fe-4475-a8da-52845f8e136b.png#averageHue=%23e9cf86&clientId=udd0f8a4d-947f-4&from=paste&height=97&id=u94428a44&originHeight=151&originWidth=540&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=28625&status=done&style=none&taskId=u579bb2e3-f961-440e-bace-917ef32a3fe&title=&width=345.6)
##### Medium tests

![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686246502798-0788d93a-6043-44ab-8902-09dc99b7be24.png#averageHue=%23eee3c6&clientId=udd0f8a4d-947f-4&from=paste&height=211&id=u457db397&originHeight=329&originWidth=497&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=57781&status=done&style=none&taskId=u7a1fcd53-4d9f-494e-9f9f-4040e19bf24&title=&width=318.08)
##### Large tests
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686246536431-12125d4b-9ee5-4401-b6b7-94f5d0f70685.png#averageHue=%23efe7d4&clientId=udd0f8a4d-947f-4&from=paste&height=141&id=u622398b2&originHeight=220&originWidth=540&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=32853&status=done&style=none&taskId=ub07bbbc2-c435-4757-abbb-82aef8c94b6&title=&width=345.6)
#### Scope
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686246620694-c5afb111-bc96-4d26-ac58-967536e15625.png#averageHue=%23f4ecd8&clientId=udd0f8a4d-947f-4&from=paste&height=215&id=ueec2b9c6&originHeight=336&originWidth=1232&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=71979&status=done&style=none&taskId=u52bde195-c7ea-4902-9605-94fb0847cdc&title=&width=788.48)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686246627028-6b3cb161-c6d7-449b-bf51-a7dbc5c989e4.png#averageHue=%23dbbd90&clientId=udd0f8a4d-947f-4&from=paste&height=279&id=u3c138424&originHeight=436&originWidth=455&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=40457&status=done&style=none&taskId=u815de699-33f6-4bac-9621-ba90d8dc1e6&title=&width=291.2)

### Blackbox & Whitebox Testing
|  | White-box testing | Black-box testing |
| --- | --- | --- |
| base | Based on **software code** | Based on **software specification** |
| pros | comprehensive testing, early defect detection | **simplicity**, **realistic** results (simulate end users) |
| cons | requires technical expertise, **expensive**, limited real-world simulation. | limited coverage, **incomplete** testing |

#### White-box testing
##### Statement coverage
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686247109649-a5c54ff1-0d8a-47df-81fe-e6d0064072b2.png#averageHue=%23f1f1f1&clientId=udd0f8a4d-947f-4&from=paste&height=100&id=u1398fc14&originHeight=157&originWidth=947&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=37672&status=done&style=none&taskId=u5de091cb-1f86-4966-b820-db2f53472e4&title=&width=606.08)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686247190137-aaf232c5-61e1-4f11-aebd-ad35e621235b.png#averageHue=%23faf8f8&clientId=udd0f8a4d-947f-4&from=paste&height=264&id=udbc09bfb&originHeight=413&originWidth=1309&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=78082&status=done&style=none&taskId=ue5cc6e46-7665-4fae-81f5-5a12cf09fe5&title=&width=837.76)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686247207218-c232bf65-b9a6-4d68-a73c-6319c544bb78.png#averageHue=%23f9f8f7&clientId=udd0f8a4d-947f-4&from=paste&height=254&id=u608da9da&originHeight=397&originWidth=1310&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=80787&status=done&style=none&taskId=u7df1ce5d-badd-4210-a737-9584b223a6f&title=&width=838.4)
###### 忽视部分分支
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686247252043-0d391f9d-34bb-43bc-9b22-2f9e79264f42.png#averageHue=%23faf9f8&clientId=udd0f8a4d-947f-4&from=paste&height=278&id=uf75cbd77&originHeight=435&originWidth=1311&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=104372&status=done&style=none&taskId=u6c4163f7-3e8e-45f7-936e-757aedef108&title=&width=839.04)

##### Branch coverage
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686247297396-4c3e89b2-e6ed-47df-8151-6fe5baa2b4c6.png#averageHue=%23f7f5f4&clientId=udd0f8a4d-947f-4&from=paste&height=40&id=uc92c0054&originHeight=63&originWidth=1131&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=12580&status=done&style=none&taskId=u6566fec8-bf3f-4070-bdd7-0e66072bd72&title=&width=723.84)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686247360380-e8ca35d1-3f59-40db-aa6e-92a1cb435ae9.png#averageHue=%23fbfaf9&clientId=udd0f8a4d-947f-4&from=paste&height=312&id=u4c112443&originHeight=488&originWidth=1161&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=101420&status=done&style=none&taskId=u9f10d365-caee-4124-82ec-6a2bd64b719&title=&width=743.04)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686247393013-6173d97e-eceb-417d-a860-c9b1548bac14.png#averageHue=%23fbf9f9&clientId=udd0f8a4d-947f-4&from=paste&height=308&id=u8c91474f&originHeight=481&originWidth=1162&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=103449&status=done&style=none&taskId=u19b9cf39-2c0c-44c5-8495-b36a8293754&title=&width=743.68)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686247414928-e5239a73-5157-491e-985b-5c67499a4900.png#averageHue=%23f9f8f7&clientId=udd0f8a4d-947f-4&from=paste&height=336&id=ua9c8e903&originHeight=525&originWidth=1142&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=112504&status=done&style=none&taskId=u0917c153-422d-4381-83ad-790b90ebed5&title=&width=730.88)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686247465767-723682dc-5e61-4931-89fb-86a3beda4d89.png#averageHue=%23f8f6f5&clientId=udd0f8a4d-947f-4&from=paste&height=333&id=u3e2c2dff&originHeight=521&originWidth=1167&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=114443&status=done&style=none&taskId=u955f7549-7532-488b-b403-cd424bba52d&title=&width=746.88)
###### 忽视运行时错误
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686247522634-0f61c9a7-d2b8-498b-82b5-3ff6554b75c6.png#averageHue=%23faf9f9&clientId=udd0f8a4d-947f-4&from=paste&height=319&id=u4d000ae5&originHeight=499&originWidth=1147&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=98006&status=done&style=none&taskId=u5000217c-c4bb-4b69-9a1c-db73c455535&title=&width=734.08)
##### Condition coverage
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686247650853-efe7f1bd-a29b-40d7-88b4-5fc63dc7c82a.png#averageHue=%23f6f5f3&clientId=udd0f8a4d-947f-4&from=paste&height=38&id=u8ede831c&originHeight=60&originWidth=1380&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=13152&status=done&style=none&taskId=uba031e5d-e5c7-435e-a529-101e8f54fb3&title=&width=883.2)
###### 忽视else分支
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686247915840-bca3440a-4880-4233-b4c4-8e20122f84c5.png#averageHue=%23faf6f5&clientId=udd0f8a4d-947f-4&from=paste&height=322&id=u5fe78d74&originHeight=503&originWidth=1150&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=109832&status=done&style=none&taskId=u3b2e4cf5-95cb-47c2-8dea-cf082b8d4ff&title=&width=736)
有两个判断语句，所以分母是2
x==0满足过TF，y>0也满足过TF，所以分子是2
##### B & C coverage
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686248017230-994623e1-7a92-440f-bdb8-cf8f46888280.png#averageHue=%23f9f8f8&clientId=udd0f8a4d-947f-4&from=paste&height=325&id=u79ee04ce&originHeight=508&originWidth=1144&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=94588&status=done&style=none&taskId=ud14e0528-d7c6-48c4-a901-8f697eb8c15&title=&width=732.16)
#### Black-box testing
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686248079218-4ea843b9-6eff-4d2e-b96f-2db28c6dd37d.png#averageHue=%23e8e8e8&clientId=udd0f8a4d-947f-4&from=paste&height=189&id=u3a28f835&originHeight=295&originWidth=775&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=117411&status=done&style=none&taskId=u632426e7-ed11-40f0-93ae-79e2c332402&title=&width=496)
##### Test Data Selection
###### Exhaustive Testing
###### Random Testing
###### Partition Testing
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686248197525-c1b74fed-1d6d-4c03-a12e-0ca696d2c9a8.png#averageHue=%23e9e0c7&clientId=udd0f8a4d-947f-4&from=paste&height=253&id=ufd7ae6a3&originHeight=396&originWidth=614&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=66634&status=done&style=none&taskId=ufc723705-000a-4c58-84e6-1d394579375&title=&width=392.96)
###### Equivalence Partition Hypothesis
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686248284078-11580310-57b7-4b5c-a3aa-5f7a781b7927.png#averageHue=%23eceae7&clientId=udd0f8a4d-947f-4&from=paste&height=175&id=u8d673191&originHeight=274&originWidth=596&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=38177&status=done&style=none&taskId=ua4c83e9e-6107-4939-a9dd-e1a7ad4d015&title=&width=381.44)
###### Boundary testing


### Test Doubles
Test doubles are commonly used in **unit testing**
#### Fakes- natural, not real
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686248750812-48615cda-1491-4fd8-a33e-9f971236b1fd.png#averageHue=%23f3ecdd&clientId=udd0f8a4d-947f-4&from=paste&height=253&id=u65051a74&originHeight=396&originWidth=1157&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=93579&status=done&style=none&taskId=u315871c5-0541-44a5-bb30-5956e446ccf&title=&width=740.48)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686248823071-3cfedd5a-778b-4e24-89b8-1fc01de0d1c9.png#averageHue=%23686765&clientId=udd0f8a4d-947f-4&from=paste&height=133&id=u3d45415b&originHeight=208&originWidth=1247&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=149235&status=done&style=none&taskId=uf3c71686-2420-476e-b89d-93086be9afc&title=&width=798.08)
#### Stubs- unnatural
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686248867656-2a4d4712-e255-4bed-b824-a21a21a4b779.png#averageHue=%23f2ede1&clientId=udd0f8a4d-947f-4&from=paste&height=199&id=uc9c52e7a&originHeight=311&originWidth=1139&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=81289&status=done&style=none&taskId=u38ae8b0a-1023-4e2a-9bc6-24f2b3d86bf&title=&width=728.96)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686248918800-cfc2078f-0c31-400a-b5a3-af72e787d43b.png#averageHue=%23535251&clientId=udd0f8a4d-947f-4&from=paste&height=113&id=u8a754d43&originHeight=176&originWidth=1336&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=140786&status=done&style=none&taskId=u9a100c80-9275-4e08-bcf3-3905dfddc78&title=&width=855.04)

#### Mocks- verification added
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686249340148-b16aadca-3bf7-4088-91d4-95b07e0c3ad9.png#averageHue=%23eadcbb&clientId=udd0f8a4d-947f-4&from=paste&height=127&id=ueb0f6175&originHeight=199&originWidth=1171&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=67224&status=done&style=none&taskId=u41b82167-edaa-47ad-b9a9-20db395466e&title=&width=749.44)
Mockito, a mocking framework for **Java**
### Maintainable Unit Tests
#### Unchanging Tests
Ideally, after a test is written, it never needs to change unless the **requirements** of the system under test change
Only changing the system's existing behavior would require the updates to existing tests
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686249580237-bebc0090-cebf-491e-855f-3a82f043faec.png#averageHue=%23f0eadf&clientId=udd0f8a4d-947f-4&from=paste&height=81&id=u7bb919b2&originHeight=127&originWidth=1283&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=46585&status=done&style=none&taskId=uf9407976-951c-43b7-a910-f88d5e0de12&title=&width=821.12)
#### Test Via Public Apis
Public APIs change much** less frequently **than internal implementations
Hence, tests on public APIs change less frequently (**more maintainable**)

#### Test Behaviors, Not Methods




## LECTURE 12-cicd
### CI/CD 
#### Continuous Integration
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686272894651-5e1ef9c5-d3d6-4688-9066-d9d9014cb785.png#averageHue=%23f9f6f1&clientId=udd0f8a4d-947f-4&from=paste&height=81&id=u8bf4e52a&originHeight=127&originWidth=1045&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=24767&status=done&style=none&taskId=uf9105569-3bfa-419e-8e5a-5d3ad4e9ee1&title=&width=668.8)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686272877907-7bc5aa92-cb63-4ac1-9e67-8cd0ac3f61ea.png#averageHue=%23e7c699&clientId=udd0f8a4d-947f-4&from=paste&height=188&id=u9a603a84&originHeight=294&originWidth=746&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=65766&status=done&style=none&taskId=ueeaed2ab-0e87-454c-a70e-b99590895f6&title=&width=477.44)
##### CB
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686272354719-19470487-02d0-4086-a3e5-e1dfa32e9a04.png#averageHue=%23f7efe4&clientId=udd0f8a4d-947f-4&from=paste&height=94&id=u181457bb&originHeight=147&originWidth=1012&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=44867&status=done&style=none&taskId=u203187b5-1d8b-49c5-b995-cad68d38357&title=&width=647.68)
###### continuous testing
determining when to test what
presubmit
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686272532132-510de071-c689-486f-bd37-157761c73c7e.png#averageHue=%23f7f3ea&clientId=udd0f8a4d-947f-4&from=paste&height=258&id=u82b10874&originHeight=403&originWidth=1001&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=104997&status=done&style=none&taskId=uf401ce41-8972-4647-9e28-499ab4a5269&title=&width=640.64)
postsubmit/CB
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686272575868-581b6ccf-8691-4db5-9fb1-1eb3aae57c6a.png#averageHue=%23f7f3ec&clientId=udd0f8a4d-947f-4&from=paste&height=250&id=uda20d6f9&originHeight=391&originWidth=1028&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=105133&status=done&style=none&taskId=udada38b1-3b7f-46ab-b6ee-c34dc5376f6&title=&width=657.92)
RC(release candidate) promotion/CD
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686272710425-81879e4b-90a8-44de-948b-13ceb1292f16.png#averageHue=%23f8f3e9&clientId=udd0f8a4d-947f-4&from=paste&height=252&id=ud6642886&originHeight=394&originWidth=1057&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=103601&status=done&style=none&taskId=u84cb1781-8d81-416a-ac1f-eb44a03c506&title=&width=676.48)
##### CD
Continuous delivery automates deployment of a release to a **staging or testing environment**
Continuous deployment: automates deployment of a release all the way to the **production environment**, no human intervention
### Deployment Strategy
#### Blue-Green Deployment (蓝绿部署)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686273037906-6d9239db-3ca4-46b4-878b-6b98d6f5f00a.png#averageHue=%23f2efea&clientId=udd0f8a4d-947f-4&from=paste&height=246&id=u53f061c5&originHeight=385&originWidth=1002&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=101300&status=done&style=none&taskId=ud6ca32bb-b75c-4f28-8b27-989011c6a33&title=&width=641.28)


#### Canary/Greyscale Release (金丝雀发布/灰度发布)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686273093198-158942b6-d7ca-43c5-9e9d-f1eb92bdc02b.png#averageHue=%23f3f2f0&clientId=udd0f8a4d-947f-4&from=paste&height=244&id=u9ce9db37&originHeight=381&originWidth=1004&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=89788&status=done&style=none&taskId=u7930b12e-04b8-4ee4-8143-ff17ac2efc5&title=&width=642.56)



### Cloud-native Applications
#### DevOps/Continuous Delivery
#### Microservices
##### Monolithic architecture单体架构
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686273286708-c70c37c5-bc2a-44d5-90c5-8079364d8619.png#averageHue=%23f6f4ec&clientId=udd0f8a4d-947f-4&from=paste&height=262&id=uc817ffb0&originHeight=409&originWidth=1024&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=139395&status=done&style=none&taskId=ue7a86c65-73c7-46b6-96ef-5ea104d9f3a&title=&width=655.36)
##### Microservice Architecture微服务架构
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686273318049-4e2a4f1e-ba21-4650-ae5e-1679b82b9bf5.png#averageHue=%23f5f3f0&clientId=udd0f8a4d-947f-4&from=paste&height=274&id=u3bae2299&originHeight=428&originWidth=1117&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=179690&status=done&style=none&taskId=uf1a2ec7d-3a38-489a-b143-7ce413dfdef&title=&width=714.88)

#### Containers
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686273467085-6e0ba60d-947d-49ee-9fe1-a915bbba9f61.png#averageHue=%23eae5da&clientId=udd0f8a4d-947f-4&from=paste&height=193&id=ueb28da39&originHeight=301&originWidth=1082&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=69237&status=done&style=none&taskId=ub4baeefa-7bed-4887-9fce-e2413a3d3f2&title=&width=692.48)
##### Services
###### REST Services
###### RPC Services
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686273605355-c3227055-ba57-45e2-9114-7605e13a3d72.png#averageHue=%23f6ebe1&clientId=udd0f8a4d-947f-4&from=paste&height=241&id=uaba4cba8&originHeight=376&originWidth=1099&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=109258&status=done&style=none&taskId=ud253bc8b-5d32-482c-9343-8a8bb8707bc&title=&width=703.36)
##### Docker
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686273640653-95585932-2cb9-4a90-93f6-041742350db0.png#averageHue=%23f8f5f1&clientId=udd0f8a4d-947f-4&from=paste&height=229&id=u160a3d53&originHeight=358&originWidth=1099&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=142421&status=done&style=none&taskId=u6ff737e6-3914-4c37-b0eb-dfb216dee7c&title=&width=703.36)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686273771427-e62ebb7e-9e70-4f9f-bd42-b122b5075ac6.png#averageHue=%23ca9e3f&clientId=udd0f8a4d-947f-4&from=paste&height=269&id=uf014988c&originHeight=420&originWidth=1053&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=160365&status=done&style=none&taskId=uf6ac3f31-322d-4412-b9ab-424d5da03bd&title=&width=673.92)
##### Scale out
container orchestration
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686274136757-7fbe6197-2527-4efb-bdae-b4504c7aaa82.png#averageHue=%23f4f2ee&clientId=udd0f8a4d-947f-4&from=paste&height=255&id=u1104402e&originHeight=399&originWidth=959&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=154073&status=done&style=none&taskId=ub3309e14-96cd-4d8b-87d4-48edfad70a0&title=&width=613.76)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686274333372-6329e166-5efe-42a7-ad9d-b0fce4e6c4e1.png#averageHue=%23cbaa76&clientId=udd0f8a4d-947f-4&from=paste&height=340&id=u0161d204&originHeight=531&originWidth=1083&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=143839&status=done&style=none&taskId=u9de6742b-cc9d-4dd9-8b64-6bd98589dbe&title=&width=693.12)
#### Cloud-native Open Standards
### Deployment Pipelines
#### Jenkins
It helps automate **building, testing, and deploying** process
It facilitates **continuous integration and continuous delivery**
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686274614508-73a90675-10aa-4399-bad9-bcd582b7bb4a.png#averageHue=%23f8f7f7&clientId=udd0f8a4d-947f-4&from=paste&height=232&id=ue8dec350&originHeight=362&originWidth=663&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=142830&status=done&style=none&taskId=ue72ab74e-0f32-4079-acde-7e9a16a0e46&title=&width=424.32)
![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686274682111-0202f395-868b-4d89-92f7-88528d205107.png#averageHue=%23efe8db&clientId=udd0f8a4d-947f-4&from=paste&height=107&id=u6975045d&originHeight=167&originWidth=346&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=27322&status=done&style=none&taskId=u8c2ad3c2-e51d-40ba-9497-ffb8f9592d7&title=&width=221.44)![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686274688576-46475257-0fa2-4508-9ca8-e8cf63605f8f.png#averageHue=%23f4efe6&clientId=udd0f8a4d-947f-4&from=paste&height=111&id=ufbbe5f0b&originHeight=173&originWidth=409&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=26339&status=done&style=none&taskId=uc5bd4d89-0a54-45cb-82c1-c2c2e0c41af&title=&width=261.76)![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686274694652-a01d150e-0b5f-4920-89ae-fb093c621f52.png#averageHue=%23f1ede8&clientId=udd0f8a4d-947f-4&from=paste&height=125&id=uab18083f&originHeight=196&originWidth=442&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=38656&status=done&style=none&taskId=ue24bbb90-22dd-4170-a02e-5d497f75810&title=&width=282.88)![image.png](https://cdn.nlark.com/yuque/0/2023/png/25785971/1686274701116-8a264799-6bc4-491b-9de1-de1446624091.png#averageHue=%23f2eeeb&clientId=udd0f8a4d-947f-4&from=paste&height=98&id=uf50e18bd&originHeight=153&originWidth=436&originalType=binary&ratio=1.25&rotation=0&showTitle=false&size=28338&status=done&style=none&taskId=u35e08b4e-40cf-4cd5-8904-827cf6eaeae&title=&width=279.04)


