A simple 5-mins kata which can help you to master the basics of java programm creation using CLI

mkdir simple_java_app_kata
cd simple_java_app_kata
mkdir out
mkdir src
touch .git ignore
touch README.md
cd src
touch Main.java
git add README.md
 git commit -m "Create README.md"
[master a653551] Create README.md
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 HW_Ivashchenko/simple_java_app_kata/README.md
git add src/Main.java
 git commit -m "Create Main.java"
[master 350d807] Create Main.java
 1 file changed, 1 insertion(+)
 create mode 100644 HW_Ivashchenko/simple_java_app_kata/src/Main.java
git add src/Main.java
git commit -m "Added some code in to Main.java"
[master 9b5228c] Added some code in to Main.java
 3 files changed, 29 insertions(+), 1 deletion(-)
 create mode 100644 HW_Ivashchenko/simple_java_app_kata/.gitignore

$ javac -d out src/Main.java
$ git commit -m "Compile Main.java"
[master b870a78] Compile Main.java
 1 file changed, 5 insertions(+), 1 deletion(-)


$ java -cp out Main
Good start

$ git commit -m "Run Main.class"
[master 7646948] Run Main.class
 1 file changed, 14 insertions(+)

$ jar -cvf app.jar out
added manifest
adding: out/(in = 0) (out= 0)(stored 0%)
adding: out/Main.class(in = 412) (out= 287)(deflated 30%)






