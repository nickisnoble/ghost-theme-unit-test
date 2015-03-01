# The Ghost Theme Unit Test

An importable file of test cases for [Ghost](https://ghost.org/) themes. It's based on the concept (and the content!) of the [WordPress Theme Unit Test](http://codex.wordpress.org/Theme_Unit_Test).

This step in Theme testing correlates to a Ghost export (`json`) file that you can import into a Ghost installation to test your theme. To be clear, this is only one of many ways you should/could test a theme.

## Getting Setup
Assuming you've already gotten Ghost set up locally and it is running your theme, here are the steps to setting up the unit test:

1. Download this repo.
1. Go to the labs section of your Ghost installation's settings (`http://example.com/ghost/settings/labs/`)
2. Click the red 'Delete' button to clear the database of all existing content, and confirm (this gives us a clean slate)
3. Click 'Choose File' under Import 
4. In the resulting file picker, navigate to wherever you downloaded the repo and select the `json` file.
5. Click the blue `Import` button.

## Testing
Each post or page is usually pretty self explanatory, or has instructions included. Have fun!

## License

This [beerware](https://tldrlegal.com/license/beerware-license). As long as you retain this notice you can do whatever you want with this stuff. If we meet some day, and you think this stuff is worth it, you can buy me a beer :) - Nick Noble

## Contributing
Submit a pull request, or complain loudly on Twitter [@nickisnoble](https://twitter.com/intent/tweet?text=@nickisnoble)!
