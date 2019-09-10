---


---

<blockquote>
<p>Written with <a href="https://stackedit.io/">StackEdit</a>.<br>
ununtu maas</p>
</blockquote>
<p>git config --global <a href="http://user.name">user.name</a> “lai”<br>
git config --global user.email <a href="mailto:%22sever0929@yahoo.com.tw">"sever0929@yahoo.com.tw</a>"<br>
git clone <a href="https://gitlab.com/laichienfu/gitlab-java-demo.git">https://gitlab.com/laichienfu/gitlab-java-demo.git</a><br>
cd gitlab-java-demo<br>
git add .<br>
git commit -m “add .”<br>
git push -u origin master</p>
<p>sudo curl -L  --output /usr/local/bin/gitlab-runner <a href="https://gitlab-runner-downloads.s3.amazonaws.com/latest/binaries/gitlab-runner-linux-amd64">https://gitlab-runner-downloads.s3.amazonaws.com/latest/binaries/gitlab-runner-linux-amd64</a></p>
<p>sudo curl -L --output /usr/local/bin/gitlab-runner <a href="https://gitlab-runner-downloads.s3.amazonaws.com/latest/binaries/gitlab-runner-linux-amd64">https://gitlab-runner-downloads.s3.amazonaws.com/latest/binaries/gitlab-runner-linux-amd64</a></p>
<p>sudo chmod +x /usr/local/bin/gitlab-runner</p>
<p>curl -sSL <a href="https://get.docker.com/">https://get.docker.com/</a> | sh</p>
<p>sudo useradd --comment ‘GitLab Runner’ --create-home gitlab-runner --shell /bin/bash</p>
<p>sudo gitlab-runner install --user=gitlab-runner --working-directory=/home/gitlab-runner</p>
<p>sudo gitlab-runner start</p>
<p>sudo gitlab-runner register</p>

