$ javac -d out src/Main.java

$ java -cp out Main

Good start

$ jar -cvf app.jar out

added manifest

adding: out/(in = 0) (out= 0)(stored 0%)

adding: out/Main.class(in = 412) (out= 287)(deflated 30%)

$ jar -cvf app.jar -C out/ .

added manifest

adding: Main.class(in = 412) (out= 287)(deflated 30%)

$ java -jar app.jar

no main manifest attribute, in app.jar

$ java -cp app.jar Main

Good start

$ cat manifest.txt

Main-Class: Main

$ jar -cvfm app.jar manifest.txt -C out/ .

added manifest

adding: Main.class(in = 412) (out= 287)(deflated 30%)

$ java -jar app.jar

no main manifest attribute, in app.jar






