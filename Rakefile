task :deploy do
  puts "******************** Sync'ing local `_site` to S3."
  `s3cmd sync -P _site/ s3://discovery-studio-site --verbose`
  puts "******************** Huzzah! We're done!"
end
