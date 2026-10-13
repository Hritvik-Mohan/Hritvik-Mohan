### Hi, I'm Hritvik 👋

I'm a software engineer in Bengaluru, currently an SDE at **Newton School**. Most of my work is backend and systems work in TypeScript and Node.js, with enough frontend and mobile along the way to ship a whole product when it needs shipping.

### What I'm working on

**A system design simulator.** This is my main project and the one I enjoy explaining the most. You draw an architecture on a canvas - API servers, load balancers, queues, caches, databases - connect the pieces, and press run. A discrete event engine then pushes traffic through it, so you can watch the system saturate, fail, and recover before any of it exists in production.

I built the engine underneath it: the event loop, routing and load balancing (least response time, power of two choices, consistent hashing), failure and rate-limiting behaviour, and a metrics and tracing pipeline that reports latency percentiles the way a real system would. A lot of it rests on queueing theory, which I did not expect to like as much as I do. An earlier public version lives at [system-design-simulator](https://github.com/Hritvik-Mohan/system-design-simulator).

**[Scout](https://github.com/Hritvik-Mohan/scout) 🐝** A side project in TypeScript. It polls public job boards, keeps the roles that match a profile you define, scores them against your real experience, and writes everything to a Google Sheet you own. It prepares the work and leaves the sending to you - it never applies or contacts anyone on your behalf. The search profile sits in its own private files, so anyone can fork it and point it at a different role, stack, or city.

### Before this

I spent two years as a Technical Program Manager at Newton School, which was a more hands-on job than the title suggests. I built NS Trinity, a React Native app with a Django REST backend, led a small distributed team on a data aggregation platform, reviewed a lot of code, wrote a few hundred coding problems, and interviewed a good number of engineers. That stretch is where I picked up the habit of writing things down - specs, ADRs, design reviews - and I still think explaining a system clearly is half of building it.

### Tools I reach for

- **Languages:** TypeScript, JavaScript, C++, SQL, Python when Django is involved
- **Backend:** Node.js, Express, Django REST Framework, WebSockets, PostgreSQL, MongoDB
- **Frontend and apps:** React, Next.js, React Native, Electron
- **Infra:** AWS, Docker, NGINX, GitHub Actions

### Also

I'm doing a part-time MCA at VIT alongside work. Outside of code I watch a lot of films - Fincher, Nolan, Villeneuve, Tarkovsky - and I will happily argue about any of them.

### Say hi

[Portfolio](https://hritvik.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/hritvik-mohan-33162b131/) · [X](https://twitter.com/hritvik_io)
