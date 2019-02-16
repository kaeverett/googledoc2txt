# googledoc2txt
pull google docs from API and output as text, so I can apply unix command line processing (awk, grep, sed..)

# setup
See https://developers.google.com/docs/api/quickstart/ruby
1) enable and download download client config
2) gem install google-api-client -v '~> 0.8'
3) ruby googledoc2txt.rb <google doc id> | awk '{print $1}' | grep whatever
