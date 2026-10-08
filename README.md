# thebadmin3-guide
This is the repo for my documentation for TheBadmin3 server. It is unfinished as I can't remember most of the details about how things work on the server.

# How to read it
I currently have this hosted at https://badmin3.taconator.com

# How to deploy locally
1. Grab `mdbook` binary from GitHub: https://github.com/rust-lang/mdBook/releases. Optionally, put it in your $PATH for easier access
2. Grab this repo: `git clone https://github.com/ItsTaconator/thebadmin3-guide.git`
3. Navigate to repo folder

   (Replace `mdbook` with path to `mdbook` binary)
   - Debugging: run `mdbook serve` and navigate to `192.168.1.117:3000` in a browser on a different computer
   - Release: run `mdbook build` and deploy `output` folder with the web server of your choice
