1. Within a Github action that runs whenever code is pushed. Because an automated GitHub workflow would ensure no incorrect or buggy code gets merged to the main branch and get into the final product. While option 2 is also a good way to test but its manual and the question asks automated tests.
2. No. This is because E2E testing is for testing user actions through the site not testing functions. Unit tests are used for functions.
3. Navigation modes asseses the page on reload, which resets the page, on the other hand snapshot mode asseses the page at its current state and no reload is involved. So, navigation mode can be used to assess the speed or performance of a website, and snapshop mode is best used for assesing a website's accessibility at any given state.
4. Three things that can be improved are:
a. The website does not have a lang attribute, this could cause issues with screen readers and lang=en should be added.
b. There is no meta description for the site. Adding this will improve its search engine visbility and SEO score.
c. Lighthouse asks to preconnect the javascript file main.js as it is a large file and might slow down the website. Preconnecting ensures that the file is loaded earlier in the page load reducing the latency when its functions are actually used.




