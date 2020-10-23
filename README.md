# kottans-frontend

<html>
<body>
  <h2>Tasks Listing</h2>
  <div class="intro">
   <h3>1. Git intro</h3>
  <p>
  I'm really exciting about GIT. It was my first time working with it.
Thanks to git bash, I feel myself a real programmer.
The command line conception is interesting and adventuring for me. 
   VCS is super usefull fo developers, it helps to improve their code 
and makes their work much easier and stresless. You can always return
to that piece of code, which is the best in your opinion without 
worriing to loose some code or project. Git also makes collaboration
easier, allowing changes by multiple people to all be merged into one source. <br>
 
A Git repository (or repo for short) contains all of the project files and the entire revision history.
To record the changes firstly we should add (index) files to a staging (index) area. Then we make a commit,
Commit takes a picture of what files look like at the moment and stores a reference.<br>

Storing a copy of your Git repo with an online host (such as GitHub or
Bitbucket) gives you a centrally located place where you can upload your changes
and download changes from others, letting you collaborate more easily with other
developers. After you have a remote repository set up, you upload (push) your
files and revision history to it. After someone else makes changes to a remote
repo, you can download (pull) their changes into your local repo.<br> Pull
requests are a way to discuss changes before merging them into your codebase,
and decide if you want to merge it or not.</p>
<img src="./image/finish.png" width="600" height="300" alt="This is a screenshot of my course finish">

</div> 
      <h3>2. Linux CLI, HTTP</h3>
      <div class="linux-http">
<h4>Linux CLI</h4>
<p>This was my first experience with Linux system.
First two modules were quite simple.
I've wondered that the commands are similar with GIT commands.
That's why it was easy to understand and memorize it. <br>
Due to its single-tree approach, the Linux filesystem structure is much more flexible and usable than the Windows structure. 
<br>
I'd like to left here information about "grep" command - this is one of the most obscure and easily-forgotten command names in Linux, but it is also one of the most useful. You can use "grep" to find patterns in data. </p><br>
Picture, showed my result about learning Linux CLI, is <a href ="https://github.com/TaniaBondarenko/kottans-frontend/blob/main/task_linux_cli/linux_surv.png">here</a><br>

<h4>HTTP</h4> 
<p>In few words, HTTP allows for communication between a variety of hosts and
clients, and supports a mixture of network configurations.<br>
To make this possible, it assumes very little about a particular system, and
does not keep state between different message exchanges. This makes HTTP a
stateless protocol.<br>
Communication between a host and a client occurs, via a request/response pair.
The client initiates an HTTP request message, which is serviced through a HTTP
response message in return.<br>
There are a few different ways a server can collect this information, and most
websites use a hybrid of these approaches:
<ul>
<li>Request headers: From, Referer, User-Agent</li>
<li> Client-IP - the IP address of the
client </li>
<li>Fat Urls - storing state of the current user by modifying the URL and
redirecting to a different URL on each click; each click essentially accumulates
state.</li>
<li> Cookies - the most popular and non-intrusive approach.</li>
</ul>
 HTTP does support a rudimentary form of authentication called Basic Authentication, as well as the
more secure Digest Authentication. Web server needs a digital certificate to
identify itself. Certificates (or "certs") are issued by a Certificate Authority
(CA) and vouch for your identity on the web. The CAs are the guardians of the
PKI. Caches are used at several places in the network infrastructure, from the
browser to the origin server. Depending on where it is located, a cache can be
categorized as: private and public. Cache Processing Regardless of where a cache
is located, the process of maintaining a cache is quite similar:
<ul>
<li>Receive request message.</li>
<li> Parse the URL and headers.</li>
<li> Lookup a local copy; otherwise, fetch and store locally</li>
<li> Do a freshness check to determine the age of the content in the cache; make a request to refresh the content only if
necessary.</li>
<li> Create the response from the cached body and updated headers.</li>
<li> Send the response back to client.</li>
 <li>Optionally, log the transaction.</li>
 </ul>

</p>
      </div>
      <h3>3. Git Collaboration</h3>
<div class="git_collab">
<p>Forking a repository creates an identical copy of the original repository and moves this copy to our  account. We have total control over this forked repository. Modifying our forked repository does not alter the original repository in any way.</p>

<p>The <b>git log</b> command is extremely powerful, and we can use it to discover a lot about a repository. But it can be especially helpful to discover information about a repository that we're collaborating on with others. We can use git log to:
<dl>
  <ul>
  <li><dt><b>git shortlog</b></dt>
    <dd>group commits by author with git shortlog</dd></li>
  <li><dt><b>git log --author="last name"</b></dt>
    <dd>filter commits with the --author flag</dd></li>
<li><dt><b>git log --grep="something to search for"</b></dt>
    <dd>filter commits with the --author flag</dd></li>
  </ul>
    </dl>
</p>

<p><b>Pull Requests</b> is sending the original project's maintainer a request to include new code changes. 
Before the start doing any work, check the project's CONTRIBUTING.md file.<br>

Next, it's a good idea to look at the GitHub issues for the project:

<ul>
<li>look at the existing issues to see if one is similar to the change we want to contribute</li>
<li>if necessary create a new issue</li>
<li>communicate the changes we'd like to make to the project maintainer in the issue</li>
</ul>

To create a pull request, a couple of things need to happen:

<ul>
<li>fork the source repository</li>
<li>clone our fork down to our machine</li>
<li>make some commits (ideally on a topic branch!)</li>
<li>push the commits back to our fork</li>
<li>create a new pull request and choose the branch that has our new commits</li>
</ul>
</p>

<p>
The <b>git rebase</b> command will move commits to have a new base.
<p>Check my progress on courses <a href="https://github.com/TaniaBondarenko/kottans-frontend/blob/main/task_git_collaboration/finish_git_coll.png" alt ="Picture of finishing GIT_Collaborations">here</a>, <a href="https://github.com/TaniaBondarenko/kottans-frontend/blob/main/task_git_collaboration/main.png" alt="Picture of progress on Main gitbranching">here</a> and <a href="https://github.com/TaniaBondarenko/kottans-frontend/blob/main/task_git_collaboration/remote.png" alt="Picture of progress on Remote gitbranching">here.<a/> 
</p>
</div>
      <h3>4. Front-End Basics</h3>
      <h3>5. Responsive Layouts</h3>
      <h3>6. HTML & CSS Practice</h3>
      <h3>7. JavaScript Basics</h3>
      <h3>8. Document Object Model</h3>
      <h3>9. Building a Tiny JS World (pre-OOP) - practice</h3>
      <h3>10. Object-Oriented JavaScript - practice</h3>
      <h3>11. OOP exercise - practice</h3>
      <h3>12. Offline Web Applications - optional</h3>
      <h3>13. Memory – Pair Game - practice</h3>
      <h3>14. Website Performance Optimization - optional</h3>
      <h3>15. Friends App - practice</h3>

</div>
</body>
</html>
