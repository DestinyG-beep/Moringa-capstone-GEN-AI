# Moringa-capstone-GEN-AI

Rookie’s guide to Golang (Go)
Technology Chosen: Go (Golang)

Why I Chose It: Go is widely used in cloud and backend systems (Docker, Kubernetes, Terraform) and is known for its speed, simplicity, and concurrency features.

Quick Summary of the Technology
What is it?
 Go is an open-source, statically typed programming language developed at Google.


Where is it used?
 Backend services, cloud infrastructure, APIs, and distributed systems.


Real-world example:
 Docker and Kubernetes — the backbone of modern DevOps — are written in Go.

System Requirements
OS: Windows, macOS, or Linux


Editor: VS Code (recommended) or any text editor


Tools: Go compiler (download from https://go.dev/dl/)

Installation & Setup Instructions
Download Go from https://go.dev/dl/ and install.


Verify installation:
///
 bash:
go version
///

Example output
/// 
Bash:
go version go1.23.0 linux/amd64
///
 
Or with WSL
 1. Update Packages
sudo apt update && sudo apt upgrade -y


2. Download Latest Go
Go to the official downloads page: https://go.dev/dl/


Copy the Linux .tar.gz link (e.g., go1.23.0.linux-amd64.tar.gz).


Download it:

 wget https://go.dev/dl/go1.23.0.linux-amd64.tar.gz




3. Extract and Install
(a) Remove any old Go versions (if you had them):

 sudo rm -rf /usr/local/go

(b) Extract into /usr/local:

  sudo tar -C /usr/local -xzf     go1.23.0.linux-amd64.tar.gz
4. Set Up PATH
Add Go’s bin to your shell config:
echo 'export PATH=$PATH:/usr/local/go/bin' >> ~/.bashrc
source ~/.bashrc

Check installation:
go version

✅ You should see something like: go version go1.23.0 linux/amd64

🔹 5. Set Up a Workspace
By default, Go uses ~/go as your workspace.

Inside it:
~/go/bin → installed binaries from go install


~/go/src → your projects


~/go/pkg → package cache


You may also add this to your PATH for convenience:
echo 'export PATH=$PATH:$HOME/go/bin' >> ~/.bashrc
source ~/.bashrc


 6. Test With Hello World
Create a file called main.In it try this:
	go:
package main
import "fmt"

func main() {
    // Print a simple message to the terminal
    fmt.Println("Hello, World from Go!")
}

Run it through the terminal with:
go run main.go

You can have a look at this project and try running it:
https://github.com/DestinyG-beep/Moringa-capstone-GEN-AI

You will need a github account for this, don’t worry, it’s simple to create one
(i) Fork your own copy of this repository
(ii) On your local machine’s terminal, create a new project folder
(iii) In that folder, clone your repository there:
	///
	Bash:
	git clone git @github.com:your repository’s name
	///
(iv)Now open the repository in your code editor
(v) In your code editor’s terminal, you can try running 
	go run main.go
      You should see an output like 

///   	Hello, Go on my machine!	 	///
