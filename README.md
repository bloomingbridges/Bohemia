# Bohemia

## Virtual gallery spaces for Unity3D-based artwork

![Screenshot](http://drop.lostwith.us/hanebouken/bohemia_screen.png)

The concept behind _Bohemia_ is loosely based upon a tweet by [Sophie Houlden](https://twitter.com/S0phieH), the exact wording of which I cannot recall but in its essence asking someone to create a platform that allows curation and presentation of games on the web in an expo-like fashion, i.e. convey the feeling that you are working from booth to booth and being able to show your support by leaving a tip.

I thought in addition to being able to browse games on canvasses in three dimensions, it would make sense to have a visual format to create the spaces from and allow anyone to quickly get a server up and running using the various _NodeJS_ hosting platforms out there.

The project hasn't been touched in a while for the following reasons:

1. The Unity Player API doesn't allow for pausing. My initial test showed that just having two players running side by side results in suboptimal performance and removing players from the DOM isn't desirable.
2. The tipping / donation mechanism might come with some legal issues that I haven't and don't want to think about
3. There is also the rumour going around that Unity will stop developing their browser plugin alltogether.
4. The last point would mean _Bohemia_ would have to include _JavaScript_-based work, which cannot come as neatly packaged in a single file by nature, i.e. too much hassle and takes away from the original focus of the project

So yeah, this is now public. If anyone feels up to the challenge, feel free to hack away :>
