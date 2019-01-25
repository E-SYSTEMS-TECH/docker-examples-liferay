MIT License

Copyright (c) 2019 E-SYSTEMS TECH, LLC

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

If you see this exception, do not worry, it only means your database is taking longer to start itself.
This may happen if you never started that container before. Restart Liferay and you should have a regular boot.

   ERROR [localhost-startStop-1][HikariPool:541] HikariPool-1 - Exception during pool initialization.
   com.mysql.cj.jdbc.exceptions.CommunicationsException: Communications link failure__The last packet sent successfully to the server was 0 milliseconds ago. The driver has not received any packets from the server. [Sanitized]
           at com.mysql.cj.jdbc.exceptions.SQLError.createCommunicationsException(SQLError.java:590)

```
docker restart liferay
```
