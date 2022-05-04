# Temporal Java SDK Workshops

## Notable Temporal Links

* [Website](https://temporal.io/)
* [Community Forum](https://community.temporal.io/)
* [Slack](https://temporal.io/slack)
* [YouTube](https://temporal.io/youtube)
* [Meetups](https://temporal.io/meetup)

## Chapters

### 1. [Getting Started](src/main/java/io/workshop/CHAPTER1.md)

<p align="center">
 <a href="https://www.youtube.com/watch?v=VoSiIwkvuX0"><img src="media/workshop-1-video.png"/></a>
</p>

* [Section 1 - Set up](src/main/java/io/workshop/CHAPTER1.md#section-1)
* [Section 2 - Workflows](src/main/java/io/workshop/CHAPTER1.md#section-2)
* [Section 3 - Workers](src/main/java/io/workshop/CHAPTER1.md#section-3)
* [Section 4 - Activities ](src/main/java/io/workshop/CHAPTER1.md#section-4)
* [Section 5 - Child Workflows](src/main/java/io/workshop/CHAPTER1.md#section-5)
* [Section 6 - Testing](src/main/java/io/workshop/CHAPTER1.md#section-6)

### 2. [Client APIs, Versioning and Error Handling](src/main/java/io/workshop/CHAPTER2.md)

<p align="center">
 <a href="https://www.youtube.com/watch?v=h-TSDMULCf0"><img src="media/workshop-2-video.png" width="50%"/></a>
</p>

* [Section 1 - Client APIs continued](src/main/java/io/workshop/CHAPTER2.md#Section-1)
* [Section 2 - Sleep Duration](src/main/java/io/workshop/CHAPTER2.md#Section-2)
* [Section 2 - Versioning](src/main/java/io/workshop/CHAPTER2.md#Section-3)
* [Section 3 - Error Handling](src/main/java/io/workshop/CHAPTER2.md#Section-4)
* [Section 5 - Dynamic Workflow / Activities](src/main/java/io/workshop/CHAPTER2.md#Section-5)

### 3. [Workflow, Activity Types, ContinueAsNew, Client error handling and more](src/main/java/io/workshop/CHAPTER3.md)

<p align="center">
 <a href="https://www.youtube.com/watch?v=8DFox0fGjzI"><img src="media/workshop-3-video.png" width="50%"/></a>
</p>

* [Section 1 - Types](src/main/java/io/workshop/CHAPTER3.md#Section-1)
* [Section 2 - Typed vs untyped stubs](src/main/java/io/workshop/CHAPTER3.md#Section-2)
* [Section 3 - Dynamic signals and queries with typed stubs](src/main/java/io/workshop/CHAPTER3.md#Section-3)
* [Section 4 - Client errors and setting up SSL/mTLS](src/main/java/io/workshop/CHAPTER3.md#Section-4)
* [Section 5 -ContinueAsNew and signals](src/main/java/io/workshop/CHAPTER3.md#Section-5)

### 4. [How-tos, Patterns, SDK Metrics](src/main/java/io/workshop/CHAPTER4.md)

* [Section 1 - More "how tos" and "gotchas"](src/main/java/io/workshop/CHAPTER4.md#Section-1)
  * Parallel activity exec - error handling
  * Don't use native Java Thread in wf code and why ([workflow constraints](https://docs.temporal.io/docs/java/workflows#workflow-implementation-constraints))
  * Disable signals? Why would you want to?
  * Cron timezone
  * More error handling fun

* [Section 2 - Patterns](src/main/java/io/workshop/CHAPTER4.md#Section-2)
  * Polling
  * Recovery / Fallback
  * Pipeline (one workflow at a time)
  * Busy Loop with wait
    
* [Section 3 - SDK Metrics](src/main/java/io/workshop/CHAPTER4.md#Section-3)
  * Setting up (Docker Compose)
    * Prometheus scrape config
    * Grafana SDK dashboard
  * Enabling SDK metrics (Worker, "Starter")
  * Showing dashboard
  * [Worker tuning guide](https://docs.temporal.io/docs/operation/how-to-tune-workers/)
    
## 5. Things planned for future Workshops
* Let us know what you would like to have covered (open issue in this repo or ping us on slack!)


