Usage: roboscrapper.sh <hostname>

Description:
This bash script, roboscrapper.sh, is designed to retrieve disallowed endpoints from the robots.txt file of a given hostname (URL) and add the hostname to each disallowed endpoint. The script helps in quickly identifying which URLs are restricted from crawling by search engines or web crawlers.

The script takes a single argument, which should be the hostname for which you want to fetch the robots.txt file. The hostname should be specified without the protocol (e.g., example.com instead of https://example.com).

If you want to display usage instructions, you can run the script with the -h option (roboscrapper.sh -h). It will print a brief help message indicating the correct usage:
