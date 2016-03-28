# alpine-maven
alpine-maven

Usage:
docker run --rm -v `pwd`:/t izotoff/alpine-maven mvn dependency:get -Dartifact=mygroupid:test:0.0.1:zip -Ddest=/t -DremoteRepositories=http://myreposite/content/repositories/releases/
