# first-day-demo

#  Instructor Demo: Git

* It is important to be able to store and manage code as well as share it with others. In this class, we will be using a tool called Github.

* Open [Github](https://github.com/) in your browser.

  * In this class, we will share code in repositories using Github.

  * Click on the `new` button to demonstrate how to create a new repository.

  * Give the new repository the name `first-day-demo`.

  * Click on `add README` to add a README.md file.

  * Click on `create repository`.

  * While the remote repo is now created, we need to pull down the repository to our machine to make changes to it.

  * Click on the `code` button and select the HTTPS option under clone to copy the URL.

* Open up a terminal on your machine.

.cd ./Documents/GitHub/BOOTCAMP
golna@Golnaz MINGW64 ~/Documents/GitHub/BOOTCAMP (master)

golna@Golnaz MINGW64 ~/Documents/GitHub/BOOTCAMP (master)
$ git clone https://github.com/golzolfa/first-day-demo.git

golna@Golnaz MINGW64 ~/Documents/GitHub/BOOTCAMP (master)
$ cd first-day-demo

golna@Golnaz MINGW64 ~/Documents/GitHub/BOOTCAMP/first-day-demo (main)
$ touch index.html

golna@Golnaz MINGW64 ~/Documents/GitHub/BOOTCAMP/first-day-demo (main)
$ git add -A

golna@Golnaz MINGW64 ~/Documents/GitHub/BOOTCAMP/first-day-demo (main)
$ git commit -m "first commit"
[main 0e90a47] first commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.html

golna@Golnaz MINGW64 ~/Documents/GitHub/BOOTCAMP/first-day-demo (main)
$ git push origin main
   
   
   golna@Golnaz MINGW64 ~/Documents/GitHub/BOOTCAMP/first-day-demo (main)
$ git push --help

golna@Golnaz MINGW64 ~/Documents/GitHub/BOOTCAMP/first-day-demo (main)
$ git pull origin main
