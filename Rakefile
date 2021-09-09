task :travis_deploy do
  token = ENV['GITHUB_TOKEN']
  sh "bundle exec jgd -u http://aolshevskiy:#{token}@github.com/aolshevskiy/aolshevskiy.github.io.git -r source -b master"
end
