// **Copy this code to your Mind Stone**
//
// Set up files URL 
var gh_base = "https://raw.githubusercontent.com"
var gh_user = "ww-insight"
var repo = "stone_script"
var branch = "main"
var url = gh_base + "/" 
^+ gh_user + "/" 
^+ repo + "/" 
^+ branch
sys.SetFileUrl(url)

// Parameters for Main function
var use_talisman = false
var use_blade = false
var use_mask = false

// Run Main
import main
Main(use_talisman, use_blade, use_mask)