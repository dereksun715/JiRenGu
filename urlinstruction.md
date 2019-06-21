# The process of inputting URL to show the website

>My first blog for the front-end.

This article will explain that the process and happenings of from input URL to show the website when a user opened a browser and input www.baidu.com.

## Typing URL on the browser

URL(Uniform Resources Locator) is used to located the resources on thge internet. It includes different ports, domain name and many of the portocols, Such as http,https,file,ftp.

## Analysis the domain name

Actullay, the browser do not know what is this URL, after you typed it. The browser needs to search the server ip address of this URL to find the target. Thus, we need to analysis the domain name of the URL, and the analysit is a way to transfer the URL that you typed to a ip address. Moreover, there are some of the process for the analysis to help you understand it more clearly.

1. Browser Caching
2. System Caching
3. Router Caching
4. ISP DNS Caching
5. If all of above unfound, it will visit the domain name server to search the IP Address, or transmit the request to next level based on the domain name server until find the ip address.[1]

## Server processes

The server is a machine with a system had installed on it, and the most common system are Linux, Windows Server 2012. Also, there is a application to manage the request in the system which is the Web Server, such as Apache, Nginx and IIS. The web server will accept the user's request and send to the code site, or anohter server.

![google.com](https://www.google.com/url?sa=i&source=images&cd=&ved=2ahUKEwj3pPvClfviAhWQMd4KHdMhC1wQjRx6BAgBEAU&url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FClient%25E2%2580%2593server_model&psig=AOvVaw2QwR-MpQhnxyvqZQdUeTUl&ust=1561226863729710)

## process of managing the website

### **mvc(Model View Controller)**[mvc](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller)

![google.com](https://www.google.com/url?sa=i&source=images&cd=&ved=2ahUKEwj0wbqAlvviAhUNIIgKHUe_AtsQjRx6BAgBEAU&url=http%3A%2F%2Fthomasbartsch.net%2Fhow-asp-net-mvc-works%2F&psig=AOvVaw1E3qKvIo7O3rcHnPXLqgOz&ust=1561226926221687)

### The process of browser managing
1. Analysis the HTML's character string
2. Analysis the Link tag and resend to request the css
3. Analysis the Script tag and resend to request the js, and execute code
4. Analysis the IMG tag and request the img's resources [2]


## References

[1] (https://xiedaimala.com/tasks/7d659df8-ce04-4002-865c-6f07f7f4bc07/video_tutorials/aa3351ab-8b59-4b0d-b0a2-e343aec12660)

[2] (https://xiedaimala.com/tasks/7d659df8-ce04-4002-865c-6f07f7f4bc07/video_tutorials/aa3351ab-8b59-4b0d-b0a2-e343aec12660)
