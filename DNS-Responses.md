---
layout: page
title: "DNS Responses"
permalink: /DNS/
---
#DNS Questions and My Responses

1. I used the command **dig umich.edu** and it output this response: ![DiG 9.10.6 response for umich.edu](/img/Question_1.png)
2. I used the command **dig umich.edu > umich-dns-record.txt**. The piped file can be found in the repository for this website!
3. To return the "answer" section of query, you can use the command **dig  +noall +answer umich.edu**
4. Bonus Question: To get the desired output using dig and awk, I would recommend using the following command: **dig +noall +answer si.umich.edu umich.edu wisc.edu education.wisc.edu | awk '{print $1 "," $5}'**
