##record daily learn from work and life
###2018-03-21
- **unzip .tgz:** tar -xvzf xxx.tgz
- **generate ssh key:** ssh-keygen -t <protocal>[rsa] -C<sign signal>["lunannan@pku.edu.cn"]
- **linux switch user:** su <user> [lunannan]
- **linux switch to root:** sudo -s
- **use anaconda to crate a virtual python envirment:**<br>
1.**install Anaconda**<br>
2.**search available python:** conda search "^python$"<br>
3.**create a vitual python envirment:** conda create -n <name>[chatbot] python=x.x anaconda<br>
4.**activate envirment:** source activate <name><br>
5.**install python packages:** conda install -n <name>[chatbot] <package> [numpy]<br>
6.**deactivate envirment:** source deactivate<br>
7.**delete virtual envirment:**conda remove -n <name>[chatbot] -all<br>
- **stand alone spark scala**<br>
1.intall jdk jre<br>
2.install scala<br>
3.install spark<br>
4.install sbt<br>
