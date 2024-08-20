### Undersoft Suite 
#### Undersoft Software Development Kit
#### Shared Service Center - Shared Vaccination Center - Shared Contact Center - Global Currency Converter

Open source conceptual resources to develop distributed, scalable, multi tenant web application in N-Tier architecture. Front tier with single code base hybrid web assembly, android, windows clients. Application tier with application server. Service tier with administration server and operational data services. Data tier with database stores (available: npgsql, mysql, mariadb, sqlserver, oracle, mongo, sqlite, cosmodb, azuresql, inmemorydb) and blob/file storages.       

#### Latest Add:
#### Plot: 
Specific type of graph. Plot can contain many crossed path lines. Paths can start from same or different source and ends on same or different target. Time is set as default kind of metric value. Below simple example where diagonal value is presented as max value from x, y correlated to time of movement on x and y started at the same time where distance of x, y is constant and can equal for example 1 meter for road map plot or 100 micrometers for high precision plot. By defining metric ranges, nodes can be excluded from computing and decrease complexity. For example ranges (from 0 to 1) will take only 0 (let's name it pedestrian crossing) and 1 (let's name it road) this ranges will compute path for cars on road. When ranges (from 2 to 2) where 2 (let's name it walk) and (from 0 to 0) will be defined result will compute path for walk road. Example source-target pairs {source:[x,y], target:[x,y]} first path (source:[Y,3], target:[B,3]}. Second {source:[P,0], target:[X,7]}. Third {source:[Y,3], target:[X,7]}.

<code> 
yx ABCDEFGHIJKLMNOPRSTUWVXY
0  888888888888821111288888
1  333333333333320000288888
2  222222222222220000222222
3  211111111111101111011111
4  222222222222220000222222
5  888888888888821111288888
6  222222222222220000222222
7  111111111111101111011112
8  222222222222220000222222
9  888888888888821111288888
</code>

#### Plot.QuickPath: 
ShortestPathDijkstra algorithm modification by replacing UpdatePriority to TryDequeue and Enqueue operation. UpdatePriority is not available in .NET 8, System.Collections.Generic.PriorityQueue. [https://github.com/undersoft-org/Undersoft.Suite/blob/07c9d385d8d969374991094c972859fa7c5d1b2d/src/SoftwareDevelopmentKit/src/Undersoft.SDK/Series/Complex/Plot/Plot.cs#L139](https://github.com/undersoft-org/Undersoft.Suite/blob/07c9d385d8d969374991094c972859fa7c5d1b2d/src/SoftwareDevelopmentKit/src/Undersoft.SDK/Series/Complex/Plot/Plot.cs#L139)
First Tests: 
[https://github.com/undersoft-org/Undersoft.Suite/blob/5053c6de6b45cdc8b7f502e8f2acdd5f6618e689/src/SoftwareDevelopmentKit/tests/Undersoft.SDK.Tests/Series/Complex/PlotTest.cs](https://github.com/undersoft-org/Undersoft.Suite/blob/5053c6de6b45cdc8b7f502e8f2acdd5f6618e689/src/SoftwareDevelopmentKit/tests/Undersoft.SDK.Tests/Series/Complex/PlotTest.cs)

#### SDK Benchmarks: 
[https://github.com/undersoft-org/Undersoft.Suite/tree/master/src/SoftwareDevelopmentKit/bench/Undersoft.SDK.Benchmarks](https://github.com/undersoft-org/Undersoft.Suite/tree/master/src/SoftwareDevelopmentKit/bench/Undersoft.SDK.Benchmarks)

#### Design overview screenshots: 
[https://github.com/undersoft-org/undersoft-org/Undersoft.Suite/src/SharedVaccinationCenter/docs/design/vaccination_software_design_album](https://github.com/undersoft-org/Undersoft.Suite/tree/master/src/SharedVaccinationCenter/docs/design/vaccination_software_design_album/solution)

<img src="https://github.com/user-attachments/assets/d055665b-de9f-4683-959c-c439a8da4291" width=50% height=50% />
<img src="https://github.com/user-attachments/assets/4d1a54ed-b8da-47ad-8452-3e0000dd2183" width=13% height=13% />
<img src="https://github.com/user-attachments/assets/b946504b-c4cf-403e-aa78-14f38377b316" width=28% height=28% />

| Banking Services | Grocery Services | Car Services | Travel Services | Health Services | Vet Services | Fashion Services | Security Services | Clean Services | Stock Services | Retail Services | Manufacturing Sevices | Design Services | Carrier Services | Government Services | Tax Services | Accounting Services | Party Services | Cooking Services | Catering Services | IT Services | Media Services | Licencing Services | Leasing Services | Rental Services | etc.

