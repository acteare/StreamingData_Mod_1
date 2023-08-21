# Important Notes from the Readings
Stream Processing (data streaming): a software paradigm that ingests, processes, and manages continuous streams of data while they're still in motion

Applications working with data streams will always require two main functions: storage and processing.
- Storage must be able to record large streams of data in a way that is sequential and consistent
- Processing must be able to interact with storage, consume, analyze and run computation on the data.

## Batch Processing vs Real-Time Streaming - What's the Difference?
- Batch Processing: The processing and analysis happens on a set of data that have already been stored over a period of time.
- Streaming Data Processing: Happens as the data flows through a system. This results in analysis and reporting of events as it happens.
- Real-Time Streaming: Guarantees that the real-time data will be acted on within a period of time, like milliseconds.
  ![image](https://github.com/acteare/StreamingData_Mod_1/assets/111468772/9ea41cf3-8346-402c-af84-84a97de36dc1)

## Top Challenges Building Real-Time Applications
- Scalability
- Ordering
- Consistency & Durability
- Fault Tolerance & Data Guarantees
