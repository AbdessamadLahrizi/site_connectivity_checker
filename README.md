# Check a single URL

python checker.py --url https://google.com

# Check multiple URLs from a file

python checker.py --file urls.txt

# Save results to CSV

python checker.py --url https://example.com --output results.csv

# Retry failed checks (3 attempts)

python checker.py --url https://down-site.com --retry 3

# Use custom timeout (10 seconds)

python checker.py --url https://slow-site.com --timeout 10
