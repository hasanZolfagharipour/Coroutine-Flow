<img src="https://user-images.githubusercontent.com/68108209/234777579-4ccca87d-ccaa-4c76-95a6-18e34e11c422.png" width="256" height="512">

# **About this book**
Coroutines are the recommended solution in Kotlin and Android for
writing concurrent and asynchronous code. There are so many good
documents, books and especially articles on the web that it can be
useful if they are combined in one place, which is exactly the idea of
this book. It includes official documents of kotlinlang and Google, also
articles and books of engineers and developers of these companies, as
well as experts in this field that are referenced. But by changing or
adding examples and descriptions while respecting the originality, it
has made this book, a valuable modern resource. Therefore, this book is
useful for all those who want to start learning Coroutine-Flow but are
lost in the mass of contents and don't know where to start. This is a
free book for your personal use only. You are NOT allowed to sell this
book. If you have any suggestions or corrections regarding this book,
please send them to me.

# **Download**
[Coroutine-Flow.pdf](https://github.com/hasanZolfagharipour/Coroutine-Flow/files/11340315/Coroutine-Flow.pdf)

**Note:** This book is not the final version, currently it only contains
the first chapter (Coroutine) and the othre two chapters, Channel and
Flow, are coming soon.

# **About Author**
<img src="https://user-images.githubusercontent.com/68108209/234777526-3870689c-3dae-499f-aa66-5c302b1ad35e.jpg" width=96 height=96>

Hasan Zolfagharipour is an Android developer with 3+ years of experience in development cutting-edge Android applications. In his free time, Hasan likes to do volunteer works, read a book, be in nature or go to the gym.

Contact me:
[Gmail](mailto:hzolfagharipour@gmail.com),
[LinkedIn](https://www.linkedin.com/in/hasan-zolfagharipour/)

# **Contents**

**1 Coroutine**

1.1 Threads

1.1.1 Concurrency & Parallelism

1.1.2 Concurrency is Not Parallelism

1.1.2.1 The Gopher example

1.1.2.2 Coroutines in terms of concurrency and parallelism

1.2 Asynchronous work with threads

1.3 Coroutines

1.4 suspend

1.4.1 Suspend under the hood

1.5 Delay

1.5.1 awaitCancellation

1.5.2 Delay under the hood

1.6 Dispatchers

1.6.1 Blocking threads

1.6.2 Default dispatcher

1.6.2.1 Limiting the default dispatcher

1.6.3 IO dispatcher

1.6.3.1 Limiting the IO dispatcher

1.6.4 Main dispatcher

1.6.4.1 Immediate main dispatching

1.6.5 Unconfined dispatcher

1.6.6 Performance of dispatchers against different tasks

1.7 withContext

1.7.1 NonCancellable

1.7.2 Performance of withContext

1.7.3 Main-safety and withContext

1.8 Coroutine builders

1.8.1 runBlocking

1.8.2 launch

1.8.3 async

1.9 CoroutineStart

1.10 CoroutineContext

1.10.1 Contexts

1.10.1.1 EmptyCoroutineContext

1.10.1.2 Context in suspend function

1.10.2 Jobs

1.10.2.1 Job states

1.10.2.2 Job

1.10.2.3 SupervisorJob

1.10.2.4 Deferred

1.10.2.5 parent-child relation

1.10.3 Properties and methods

1.10.3.1 children

1.10.3.2 isActive, isCancelled, isCompleted

1.10.3.3 join

1.10.3.4 onJoin

1.10.3.5 cancel

1.10.3.6 cancelAndJoin

1.10.3.7 cancelChildren

1.10.3.8 invokeOnCompletion

1.10.3.9 start

1.10.3.10 ensureActive

1.11 Structured Concurrency

1.12 Cancellation

1.12.1 Catching exceptions

1.12.1.1 Catching exceptions in async builder

1.12.2 Handling exceptions

1.12.2.1 SupervisorJob

1.12.2.2 supervisorScope

1.12.3 Cancellation under the hood

1.13 CoroutineScope

1.13.1 coroutineScope

1.13.1.1 supervisorScope

1.13.1.2 withTimeout

1.13.2 GlobalScope

1.13.3 CoroutineScope

1.13.4 MainScope

1.13.5 lifecycle-aware scopes

1.13.5.1 LiveDataScope

1.13.5.2 viewModelScope

1.14 lifecycleScope

1.14.1 Flow collection

1.14.2 Restartable Coroutines

1.14.2.1 flowWithLifecycle

1.14.2.2 collectAsStateWithLifecycle

1.14.3 ProcessLifecycleOwner

1.14.4 lifecycleScope under the hood

1.15 Convert callback-based APIs to Coroutine and Flow

1.15.1 One-shot async call (suspendCancellableCoroutine)

1.15.2 Streaming data (callbackFlow)

1.16 Test

1.16.1 Overview

1.16.2 TestDispatchers

1.16.2.1 StandardTestDispatcher

1.16.2.2 UnconfinedTestDispatcher

1.16.3 Injecting test dispatchers

1.16.4 Setting the Main dispatcher

1.16.5 Creating dispatchers outside a test

1.16.6 Creating your own TestScope

1.16.7 Testing flows

1.16.7.1 Test the consumer of a flow

1.16.7.2 Test the producer flow

1.16.7.3 Turbine

1.16.7.4 Testing StateFlows

1.17 Coroutines best practices

1.18 Operations that shouldn’t be cancelled in Coroutines

1.18.1 WorkManager

1.18.2 Coroutines

1.19 Concurrency problems

1.19.1 Shared mutable state

1.19.1.1 Changing the problem

1.19.1.2 Changing is not possible

1.19.1.3 Understanding the problem

1.19.1.4 Atomic

1.19.1.5 Read/Write Locks

1.19.1.6 Thread confinement

1.19.1.7 Mutex

1.19.1.8 Actors

1.19.2 One shot request

1.19.2.1 Disable the button

1.19.2.2 Cancel the previous work

1.19.2.3 Queue the next work

1.19.2.4 Join previous work
