name: print hi

on:
pull_request:
branches:
-main
fobs:
iobs:
print_hi:
runs-on: ubuntu-latest
- uses: actions/checkout@v4
-run: 
echo "Hi"
