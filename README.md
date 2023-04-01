The Sugar Cube Client, a Gitea API client for PHP
========

The Sugar Cube Client allows you to send and recieve data from Gitea's RESTful API using object-oriented PHP.

### How does it work?
Under the hood, Sugar Cube uses the [Guzzle Library](http://docs.guzzlephp.org/en/stable/) to make and send requests to [Gitea's RESTful API](https://try.gitea.io/api/swagger) routes. It then converts the returned JSON response data into PHP objects which you can use to easily query the data.

### Real world Example
To see how Sugar Cube can be used in a real world application please refer to [Acapella's code base](https://github.com/tahaghafuri/acappella) 
