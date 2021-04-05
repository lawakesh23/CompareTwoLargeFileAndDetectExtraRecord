CompareTwoLargeFiles:

This tool basically compare the existing url which is available in Staging.txt file and Production-Listing.txt file and fetch the unique URL which is not available in the Production-Listing.txt only. These Unique URLs are stored in already created final.txt file.

Steps to Use this Tool:

1. Download the source code.
2. If node_modules folder is not available, kindly Run "npm install" in the root folder where script file are available.
3. Open CMD at the current folder and hit the command "node comareRecords.js"
4. You will see the unique URLs in final.txt file as Output.

Note: This tool is created for reducing the time complexity, Comparing 1227691 URLs in less than 3 minutes. This tool operates when the URLs are in the similar way as in these two files( Starting with "/www/stg.eduplace.com/docs/" in Staging3.txt and "/www/eduplace.com/docs/" in Production-Listing.txt file.
