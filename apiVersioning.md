**API Versioning**

* API versioning is the practice of managing changes in your API.
* Clients can still access the old version and their products won't break as soon as  as you launch a new release.
* There are 3 different types of versioning updates: 
    * **URL versioning**
    This is the most common versioning strategy , although it violates every URL should contain a unique resource. 
    Ex : 
    https://website.com/api/v1/users
    https://website.com/api/v2/users

    * **Query Parameters Versioning**
    This strategy states the version of an API by using query parameters .
    Ex :
    https://website.com/users?version=1

    * **Custom Headers Versioning**
    Versioning can also be done by passing custom request headers.
    Ex :
    curl -H "accept-version: 1" https://website.com/users
