**API Rate Limiting**

    API Rate Limiting is the process of limiting the number of calls a user can make to your API within a given time.

    If the limit is exceeded, furthur APIs will fail.

* **Implementing Rate Limiting is necessary when designing a good and safe API because it provides control and security.**

    It protects against potential DDoS attacks and malicious bots that may otherwise flood the API with requests, hinder traffic, and severely impact performance

* **Rate Limiting also makes your API scalable.**

    If your API suddenly becomes popular and there's a spike in usage, too many calls will slow down performance. Rate limiting enables control to prevent this.

* **There are three methods of Rate Limiting that are most common:**

**Throttling**

    The API will assess each request made. When the throttle is triggered, the user may be disconnected or have their bandwidth reduced, slowing down the response time.

**Rate Limiting algorithms**

    There are several popular algorithms used to control API calls.
    Leaky Bucket, Sliding Window, and Fixed Window are the most well-known and used.

**Request Queues**

    This means limiting the number of requests per a given time period, for example, allowing only ten requests per second.

As well as these Rate Limiting methods, there are also two types of Rate Limiting approaches.

These are Key Level and API Level.

    * Key Level controls traffic from IP addresses to ensure each user does not exceed the limit.
    * API Level deals with incoming traffic from all users to ensure that an overall call limit is not exceeded.
