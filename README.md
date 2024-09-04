<h1 align="left">RAG-QABot</h1>

###
A study was carried out as an example of developing an artificial intelligence-supported chat system by using the logs generated as a result of users visiting the website. In the system, some models with the ability to convert question, answer and log data into vectors were used. These models are taken from the HuggingFace platform. The models used in the study are all-MiniLM-L6-v2, gpt2, bert-base-uncased, distilbert-base-uncased, t5-small, gpt-neo-1.3B and roberta-base models.

In the process of designing the systems, the models were tested with different combinations as much as possible due to the hardware characteristics of the environment. The development of the systems was started in Colab and Kaggle and continued on the computer in local due to easier access to the outputs of the models, and the process was completed in Kaggle due to the notebook work taking a long time. Smaller scale models were tried to be tested due to the lack of RAM, low-level GPU and mid-level CPU in Local, which slowed down the process.


Systems,
- How many requests resulted in a 404 status code?
- What is the most common HTTP method?
- What is the most common status code?
- What is the most common user agent?
- Which User Agent was used most frequently?
- What is the average response size for requests to /user/profile?
- How many unique URLs were accessed?
- Which HTTP method was used most often for successful requests (status code 200)?

questions were asked.The questions were selected after determining the appropriateness of the ChatGPT-generated chat in which the data was generated. One of the most realistic scenarios would be to use human evaluation and testing to assess the accuracy, relevance and meaningfulness of system responses. However, since this study is more of an illustration of developments and the data was generated synthetically, it was analyzed and interpreted by myself. The answers to the questions given by the RAG models can be reviewed in full on GitHub and can be tested on local computer, Colab and Kaggle (recommended) with different questions upon request. The 5 most similar data were found to be almost identical except for a few answers by the vectorization models for each of the 8 questions, and the generator's answers are shown below. It is recommended to examine the notebook with the most similar data.


How many requests resulted in a 404 status code?
• Vectorization: all-MiniLM-L6-v2, generator: gpt2
o 3.
• Vectorization: bert-base-uncased, generator: gpt2
o 400 404 0 478 Mozilla/5.0 (iPhone; CPU iPhone OS 14_6 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/14.0 Mobile/15E.
• Vectorization: distilbert-base-uncased, generator: gpt2
o As of 12/07/10 a request containing information about a product or service status can lead to a 404 status code for all products or service services. Therefore, one can always obtain all the information about the product within the source and without any data
• Vectorization: t5-small, generator: gpt2
o 10. Request code: 0x8080. Request result code: 639. Response from the browser: Please respond using the "contact.response" message to your inquiry. After the response has been received, it must
• Vectorization: gpt-neo-1.3B, generator: gpt2
o In the following question, you received two different email addresses for the same question. The replies corresponded to the same email addresses which are the same person (with different name) but which have different mail addresses, which is the error message:
• Vectorization: roberta-base, generator: gpt2
o No, this is an example of a page on the web that might have been returned by the browser.POST /com.googleapis.apis.mobile.test HTTP/1.1 200 200 yes yes yes no yes.
What is the most common HTTP method?
• Vectorization: all-MiniLM-L6-v2, generator: gpt2
o HTTP/1.1 200 OK Yes OK Yes OK /about HTTP/1.1 403 633 Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML…
• Vectorization: bert-base-uncased, generator: gpt2
o HTTP/1.1. The following list contains the most frequently used HTTP methods that return errors. HTTP/1.1 GET /User/Profile HTTP/1.1 404 3837 Mozilla/5.0 (iPhone; CPU…
• Vectorization: distilbert-base-uncased, generator: gpt2
o It's the way Mozilla implements the web interface. When it changes the behaviour of a resource provider the Web interface will be changed. More information about this behavior is published elsewhere : https://developers.mozilla.org/en-US
• Vectorization: t5-small, generator: gpt2
o This parameter is an easy way to tell what HTTP method works. Get help with HTTP methods and how to make some queries. GET /request HTTP/1.1 200 OK Content-Type: application/json (charset=[…
• Vectorization: gpt-neo-1.3B, generator: gpt2
o If you have three possible options to get an expected response, then all of these might work as well if you have only a few options and there are only a handful of arguments the most common one to use would look something like this.
• Vectorization: roberta-base, generator: gpt2
o This is the most common HTTP method.
What is the most common status code?
• Vectorization: all-MiniLM-L6-v2, generator: gpt2
o The most common code is: "Content-Length": 1. HTTP status code is: 200 OK. I've read this site for years, but still haven't gotten past 100! Not only was my page never taken down…
• Vectorization: bert-base-uncased, generator: gpt2
o 0, The most common. 1: The last non-zero number (such as 15). 2: The last non-zero integer in the sequence (such as 16 or 29…
• Vectorization: distilbert-base-uncased, generator: gpt2
o HTTP/1.1 200 422 Mozilla/5.0 (iPhone; CPU iPhone OS 14_6 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/14.0 Mobile/
• Vectorization: t5-small, generator: gpt2
o This parameter is an easy way to tell what HTTP method works. Get help with HTTP methods and how to make some queries. GET /request HTTP/1.1 200 OK Content-Type: application/json (charset=[…
• Vectorization: gpt-neo-1.3B, generator: gpt2
o HTTP/1.1 503 2014 Mozilla/5.0 (iPhone; CPU iPhone OS 14_6 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/14.0 Mobile/…
• Vectorization: roberta-base, generator: gpt2
o There are a lot of different answers given here, but I would like to share my experience. Basically, after seeing this question, I've decided to go with no answer.
What is the most common user agent?
• Vectorization: all-MiniLM-L6-v2, generator: gpt2
o The most common is Mozilla's Firefox. However, you can use other websites which show different versions of Firefox and add it to your existing page. If you use a third party search engine to find it, you must specify your version of Firefox with a…
• Vectorization: bert-base-uncased, generator: gpt2
o If you think some software does better and others do better, then you are doing the right thing for many users. I have noticed that some software supports the most common user agent: Mozilla Firefox as default, as a default browser with…
• Vectorization: distilbert-base-uncased, generator: gpt2
o The most commonly used user agent is Safari, or the basic browser window manager. Source: http://developer.samsungwedge.com/samsung.html http://mobile.samsungwedge.com/samsung.
• Vectorization: t5-small, generator: gpt2
o The most common user agent is: http://www.google.com/view-ad-data?hl=en. This is how you want to use this. Check the box which you want.After some…
• Vectorization: gpt-neo-1.3B, generator: gpt2
o There are many common and quite useful agents for your business (sometimes called different users agents for some reasons). The results of this list are pretty good. In order to find the most common and useful users agents there is no one right answer.
• Vectorization: roberta-base, generator: gpt2
o Not much. Canonical says it has several extensions available for use on Macs. Many use this as the browser to hide any user agents from the browser or if it has access to the Internet for one or more purposes only. In particular
Which User Agent was used most frequently?
• Vectorization: all-MiniLM-L6-v2, generator: gpt2
o “Microsoft Windows" instead of "Linux" for Google Chrome
• Vectorization: bert-base-uncased, generator: gpt2
o https://gist.github.com/dodboggin/8164845dcd/file/7e78e29ca-5de-47ac-bb9b-3fc0e5de1
• Vectorization: distilbert-base-uncased, generator: gpt2
o From our experience, this is mostly not the case: there is clearly a lot of work to be done before it is clear who would benefit the most from this. We would love to hear if this has anything to do with Mozilla's experience in choosing
• Vectorization: t5-small, generator: gpt2
o WebKit/537.36 was the most-used browser when the original request went through (see the "User Agent Used Most Frequently" chart for more information). Here's how users are usually able to use their browsers to find and delete…
• Vectorization: gpt-neo-1.3B, generator: gpt2
o I haven't looked through the data to find out. PATI-X (I'm looking at you: http://stackoverflow.com/questions/3414862). GET /tags HTTP/1.
• Vectorization: roberta-base, generator: gpt2
o I chose the browser that most closely follows my needs and preferences. I was also curious about the other Mozilla-related things. You can check out what we have as an active topic on our list of frequently asked questions. What do please share…
What is the average response size for requests to /user/profile?
• Vectorization: all-MiniLM-L6-v2, generator: gpt2
o An error notification notification, A complete list of error conditions is given below, Error Condition: None, Response Size: 16384 bytes, Description: A complete list of error conditions is given below. Error Condition: None
• Vectorization: bert-base-uncased, generator: gpt2
o /users/{id}/{name} HTTP/1.1 500 4042 Mozilla/5.0 (iPhone; CPU iPhone OS 14_6 like Mac OS X) AppleWebKit/605.1.15 (KHTML,
• Vectorization: distilbert-base-uncased, generator: gpt2
o Response Length Type: response Description: GET /user/profile HTTP/1.1 200 422 Mozilla/5.0 (iPhone; CPU iPhone OS 14_6 like Mac OS X) AppleWebKit/604.1.15 (KHTML
• Vectorization: t5-small, generator: gpt2
o 1.0ms (or 100 MB) for all requests. Example: The "total" type response is 200 bytes, where 2MB is a total number of response bytes. You can specify a "total number" of responses from the…
• Vectorization: gpt-neo-1.3B, generator: gpt2
o Request size may very well be a determining factor in the response size. If a request is larger than or equal to your target user profile size, you should use a smaller response size. To ensure good response strength, check the client-side response size…
• Vectorization: roberta-base, generator: gpt2
o The average response size for requests to http://localhost:8080/webroot should be: HTTP/1.1 200 404 Not found HTTP/1.1 100 1 302 Not found HTTP/1.1 100 1 301 Not found…
How many unique URLs were accessed?
• Vectorization: all-MiniLM-L6-v2, generator: gpt2
o To answer this question, we need to start by comparing two datasets using the common database "QA: The Numbers" to see how many unique URL's were accessed. As shown in the Figure, the number of unique URLs that were accessed were…
• Vectorization: bert-base-uncased, generator: gpt2
o The numbers we used above are from the site's index.html. GET /api/1.0 557 2154 Firefox (1.1+) 3.0 Yes Yes Yes (default) yes yes Yes Yes 993 1790…
• Vectorization: distilbert-base-uncased, generator: gpt2
o The best way to test out the data for your user's specific search query is to dig down into a JSON file, sort by author name, and then see which results you got. If there are no answers, that's because Google has a weird…
• Vectorization: t5-small, generator: gpt2
o 1. We can't check the same list by all of the URLs which are searched. 2. On the same day there were no search queries for "parsing" the content. (Example: 1).
• Vectorization: gpt-neo-1.3B, generator: gpt2
o A total of 21 unique URLs accessed by Yahoo alone.
• Vectorization: roberta-base, generator: gpt2
o Yes, each unique URL is unique, which makes the entire web inaccessible. That being said, there are two ways to get around this limitation: By using the URL string you are giving users access to the entire website, and by using their web browser…
Which HTTP method was used most often for successful requests (status code 200)?
• Vectorization: all-MiniLM-L6-v2, generator: gpt2
o HTTP/1.1 504 2067 Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:90.0) Gecko/20100101 Firefox/90.0
• Vectorization: bert-base-uncased, generator: gpt2
o None.
• Vectorization: distilbert-base-uncased, generator: gpt2
o Some HTTP methods are useful for a lot of HTTP requests. Some options such as: GET responses from http://localhost HTTP/1.1 302 2016 Mozilla/5.0 (iPhone; CPU iPhone OS 14_6
• Vectorization: t5-small, generator: gpt2
o HTTP/1.1 302 3527 Mozilla/5.0 (iPhone; "iPad"; "iPhone"; "iPhoneOS"; "-webkit8;") AppleWebKit/621.10.4 (KHTML, like Gecko)
• Vectorization: gpt-neo-1.3B, generator: gpt2
o What type of requests?
• Vectorization: roberta-base, generator: gpt2
o HTTP/1.1 404 Not Found In 1.3 Content-Type: application/x-www-form-urlencoded Content-Length: 5078 Content-Class: application/x-www-form-urlencoded How many requests resulted in a 404 status code?
• Vectorization: all-MiniLM-L6-v2, generator: gpt-neo-1.3B
o There was only one 404.
• Vectorization: bert-base-uncased, generator: gpt-neo-1.3B
o Only one. The problem is: there isn't a 404 status code. (The http 404 is the HTTP status code that is returned by the server when a requested URL can not be found.)
• Vectorization: distilbert-base-uncased, generator: gpt-neo-1.3B
o I think the number of 404 requests should be zero, but that's only a guess. I used the code below to count requests by URL and counted the number of 404 codes.
• Vectorization: t5-small, generator: gpt-neo-1.3B
o I was wondering how many GET's the /product filter is filtering, in order to get the current count.
• Vectorization: gpt-neo-1.3B, generator: gpt-neo-1.3B
o 200 was the only response that was returned which was not due to server error.
Update: I got some better answers from other people in the answers below:
The request was NOT actually a 404, the status code was 5.
• Vectorization: roberta-base, generator: gpt-neo-1.3B
o 1.
What is the most common HTTP method?
• Vectorization: all-MiniLM-L6-v2, generator: gpt-neo-1.3B
o All. The most common HTTP method of course is GET. The server is telling the client that it needs some data from the request. Your browser is parsing the request and is sending the response.
• Vectorization: bert-base-uncased, generator: gpt-neo-1.3B
o GET, POST, PUT, DELETE, HEAD, OPTIONS, TRACE, TRACK, OPTIONS (HEAD and TRACE are also supported for OPTIONS responses)
• Vectorization: distilbert-base-uncased, generator: gpt-neo-1.3B
o PUT, DELETE. As you may have suspected, the HTTP methods by default are POST and GET, but the HTTP methods can be changed.
• Vectorization: t5-small, generator: gpt-neo-1.3B
o POST. I checked all the existing POST requests on this site: http://www.htc.org/htdocs/tools/request_tools.php. One thing that stands out is POST requests with a 302:
• Vectorization: gpt-neo-1.3B, generator: gpt-neo-1.3B
o GET. GET is the most common method (there are several other possible answers). Example: Using GET, GET http://www.test.com/products?product_id=9008.
• Vectorization: roberta-base, generator: gpt-neo-1.3B
o GET. The most common HTTP method is GET. HTTP/1.1 200 3075 Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:90.0). Geo/0.
What is the most common status code?
• Vectorization: all-MiniLM-L6-v2, generator: gpt-neo-1.3B
o 0 for all requests, but for some requests the status code can be different. Note: It is not possible for us to answer your question by saying "what is the most common status code" because we cannot know for a fact the…
• Vectorization: bert-base-uncased, generator: gpt-neo-1.3B
o 200 (OK) (or any other status code)
• Vectorization: distilbert-base-uncased, generator: gpt-neo-1.3B
o 302 on any HTTP status code, because the 302 response has already been removed: I can see how 302 is different from 302/301. But why does 302 code get removed when I access a link?
• Vectorization: t5-small, generator: gpt-neo-1.3B
o 302. I've seen this many different ways. Some people see it as an indication that the server is done processing the request. Other people think it's a redirect, which happens all the time. Others see it as an indication that the resource has…
• Vectorization: gpt-neo-1.3B, generator: gpt-neo-1.3B
o It depends... I'm thinking the answer will be different for different web servers (apache, tomcat, etc..). The most common status code is 500, which means that the request was not successful. The reason for this is that the…
• Vectorization: roberta-base, generator: gpt-neo-1.3B
o 200 – ok, 301 - no content, 404 - no such resource, 500 - server error
What is the most common user agent?
• Vectorization: all-MiniLM-L6-v2, generator: gpt-neo-1.3B
o Google/Chrome/Safari, Google Chrome is used by most mobile users, Safari is used by some and Microsoft Edge is used by some too. You can use this chrome-detection script to detect the…
• Vectorization: bert-base-uncased, generator: gpt-neo-1.3B
o Android. "What is the most common user agent" is a very broad question, so let me try to help with a few other things, When a user is on your website, what user agent gets sent to…
• Vectorization: distilbert-base-uncased, generator: gpt-neo-1.3B
o Apple's UA is Safari, The most common user agent is Safari. Not because this is the most popular browser, but because it's the most common browser. As you know, in iOS Safari is the default browser…
• Vectorization: t5-small, generator: gpt-neo-1.3B
o Google Chrome, Chrome has a preference pane that shows the user agent in the "Advanced" tab. It can change the user agent to "Mozilla/5.0 (Windows NT 5.1; en…
• Vectorization: gpt-neo-1.3B, generator: gpt-neo-1.3B
o The most common browser is Firefox. Browser: IE (Internet explorer), Safari, Google Chrome. OS: Mac OS X. Version: 14.0.5 (14A145). The most common browser is Firefox Browser.
• Vectorization: roberta-base, generator: gpt-neo-1.3B
o It is Chrome.
Which User Agent was used most frequently?
• Vectorization: all-MiniLM-L6-v2, generator: gpt-neo-1.3B
o Mozilla/5.0 (X11; Linux i686; rv:2.0.1.2pre3-s7) Gecko/20100101 Firefox/3.6.8
• Vectorization: bert-base-uncased, generator: gpt-neo-1.3B
o It was my personal preference to use the first one that would match the request. Why: The user agent is a web-based tool that helps you identify the browser used to send the request. It's a bit tricky to get your head around…
• Vectorization: distilbert-base-uncased, generator: gpt-neo-1.3B
o It was "Mozilla/5.0 (iPhone; CPU iPhone OS 14_6 like Mac OS X)"
• Vectorization: t5-small, generator: gpt-neo-1.3B
o Mozilla/5.0 (iPhone; CPU iPhone OS 14_6 like Mac OS X)
• Vectorization: gpt-neo-1.3B, generator: gpt-neo-1.3B
o User Agent was used most frequently, it was a Chrome. When we switch to Opera, Safari or another browser, Chrome was the most preferred User Agent.
• Vectorization: roberta-base, generator: gpt-neo-1.3B
o Chrome. It's not really a user agent problem, its a user's browser problem which causes issues like the current one.
What is the average response size for requests to /user/profile?
• Vectorization: all-MiniLM-L6-v2, generator: gpt-neo-1.3B
o I'd suspect that the max response size would be at least that seen here. However, /user/profile is a pretty large, complex page. Is there a simple way to find the average response time?
• Vectorization: bert-base-uncased, generator: gpt-neo-1.3B
o The average response size for requests to /user/profile is 2.4 KBytes, which is 5.5% of the 2.5 KBytes requested.
• Vectorization: distilbert-base-uncased, generator: gpt-neo-1.3B
o When I checked the Network tab for /user/profile, I saw that the average response size was 2KB, 2.1KB, 2.1KB, and 200 bytes.
• Vectorization: t5-small, generator: gpt-neo-1.3B
o According to the spec, the average response size is 0.7 KB. Is there a way to calculate the average response size?
• Vectorization: gpt-neo-1.3B, generator: gpt-neo-1.3B
o 1,000 KB
• Vectorization: roberta-base, generator: gpt-neo-1.3B
o The average response size for requests to /user/profile is 5 bytes. As of the time of this question the average response size is not tracked anywhere.
How many unique URLs were accessed?
• Vectorization: all-MiniLM-L6-v2, generator: gpt-neo-1.3B
o 1.6 billion.
• Vectorization: bert-base-uncased, generator: gpt-neo-1.3B
o The first query was found 0 times within one minute. The second query was found 0 times within one minute. The third query was found 0 times within one minute. The fourth query was found 0 times within one minute. The fifth query was found 0...
• Vectorization: distilbert-base-uncased, generator: gpt-neo-1.3B
o 6.
• Vectorization: t5-small, generator: gpt-neo-1.3B
o 4,086 unique requests.
• Vectorization: gpt-neo-1.3B, generator: gpt-neo-1.3B
o It looks like the server returned all the links in the same order. However, there is a slight difference in the HTML source code. I found the problem by testing each URL individually. I tried to create a GET request to each URL in the
• Vectorization: roberta-base, generator: gpt-neo-1.3B
o 0. You could try using curl_multi instead of cURL. As for the "hundreds of thousands of unique URLs accessed": You're using curl_multi to create multiple calls, which is a poor solution.
Which HTTP method was used most often for successful requests (status code 200)?
• Vectorization: all-MiniLM-L6-v2, generator: gpt-neo-1.3B
o GET.
• Vectorization: bert-base-uncased, generator: gpt-neo-1.3B
o POST. I've been browsing through the PHP logs and the only thing I see is POST, but I'm not sure if that makes any sense.
• Vectorization: distilbert-base-uncased, generator: gpt-neo-1.3B
o POST.
• Vectorization: t5-small, generator: gpt-neo-1.3B
o The GET method. The answer is simple, because the request URL and the request bodies are the same http://en.wikipedia.org/wiki/HTTP/1.0...
• Vectorization: gpt-neo-1.3B, generator: gpt-neo-1.3B
o Answer: POST, 302, 500... but most of time was 302.
• Vectorization: roberta-base, generator: gpt-neo-1.3B
o GET /payment HTTP/1.1 200 4983 Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:90.0) Gecko/20100101 Firefox/90.0. PUT /…


When the systems with the models are asked 8 different questions and the answers given are checked as much as possible with the dataset generated with the ChatGPT 4o model, it can be said that the answer with data is found in systems where the gpt-neo-1.3B model is the generator and the bert-base-uncased and distilbert-base-uncased models are used as Vectorization models. It is seen that there is confusion in models other than that. In addition to the system with gpt-neo-1.3B model used as both generator and vectorization model, it is also seen that there is a tendency to take information from the internet in the systems using gpt-neo-1.3B as generator.


The gpt2 and gpt-neo-1.3B modeled systems used as generators were developed in two separate notebooks and uploaded to GitHub because the pipeline process takes too long. The necessary outputs are located in folders named outputs_gpt2 and outputs_gptNemo after the notebook is run once. Thus, the processes can also be seen locally. If you need to test models with different questions, it is enough to map the question to the 'query' variable in the last section 'Testing with quesitons'. Running the test on Kaggle and creating a version is recommended due to the pipeline time. If outputs are generated, responses can be received by the models with a maximum of 30 seconds. To access outputs_gpt2 and outputs_gptNemo, you can visit outputs_links.txt and pull them directly to Kaggle and Colab environment (it can also be done in Local if desired).


###

